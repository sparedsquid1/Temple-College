---
kindle-sync:
  bookId: '3804'
  title: Introduction to C# Joes 2 Pros
  author: 'Peter Bako, Rick A. Morelan, Ward Henneberry, and Joel Heidal'
  asin: B004JN0GA8
  lastAnnotatedDate: '2023-11-01'
  bookImageUrl: 'https://m.media-amazon.com/images/I/71qYUUoG1cL._SY160.jpg'
  highlightsCount: 16
---
# Introduction to C# Joes 2 Pros
## Metadata
* Author: [Peter Bako, Rick A. Morelan, Ward Henneberry, and Joel Heidal](https://www.amazon.comundefined)
* ASIN: B004JN0GA8
* ISBN: 1451581718
* Reference: https://www.amazon.com/dp/B004JN0GA8
* [Kindle link](kindle://book?action=open&asin=B004JN0GA8)

## Highlights
Notice the difference.  There is no longer a set of curly braces after the else clause of the initial if statement, since this is not counted as multiple lines. — location: [1501](kindle://book?action=open&asin=B004JN0GA8&location=1501) ^ref-48461

In our work environment do we ever use if else or do we only use if and else?

---
do while loop — location: [2433](kindle://book?action=open&asin=B004JN0GA8&location=2433) ^ref-40170

---
you are definitely going to get at least one pass through your code. — location: [2433](kindle://book?action=open&asin=B004JN0GA8&location=2433) ^ref-46354

---
Within — location: [3939](kindle://book?action=open&asin=B004JN0GA8&location=3939) ^ref-10389

---
Now take — location: [3943](kindle://book?action=open&asin=B004JN0GA8&location=3943) ^ref-7964

---
“CH9c”. — location: [4014](kindle://book?action=open&asin=B004JN0GA8&location=4014) ^ref-64151

---
you leave the keyword public off, — location: [4052](kindle://book?action=open&asin=B004JN0GA8&location=4052) ^ref-31042

would leaving public off be the same as declaring private?

---
Notice the first line of code inserted into Main.  In the past whenever we declared a variable, all we had to do was enter the data type followed by a name for the new variable – this was even true when using a struct as the data type.  When using a class, things are a little bit different.  Actually, you can just type the name of the class followed by a variable name, which technically will create a variable.  When creating an instance of a new class, you need to use the new keyword, which you do not need to use with a struct.  If you don’t use the new keyword the compiler will give you an error, specifically “Use of unassigned local variable”.  What the heck does that mean?  Instead of thinking of a variable as a container which can hold a value of a specific data type, think of the variable as an address to a spot in memory. — location: [4608](kindle://book?action=open&asin=B004JN0GA8&location=4608) ^ref-13566

Confused.  Need to reread the struct section.  Similarities between struct and class in this example are too close for me to understand differences clearly.

---
the field declarations. — location: [4644](kindle://book?action=open&asin=B004JN0GA8&location=4644) ^ref-22964

Field declartions?  I dont remember that term being used before this chapter.  I assume this pertains to the public access at the beginning of the Location class?

---
would seem to be — location: [4859](kindle://book?action=open&asin=B004JN0GA8&location=4859) ^ref-36580

---
Think of variables in memory as being like a collection of Post Office boxes.  Each little cubby hole is a variable into which I can put a single slip of paper that holds the value of the variable and where the number on the box is the name of the variable.  When a method is called by value, the compiler takes the slip of paper that holds the value to be passed in out of the cubby and copies it onto another slip of paper.  The first slip of paper goes back into the original cubby hole, and the second slip goes into a new cubby hole that the method owns.  As the method works, it might scribble all over its slip of paper but the original one is not modified. — location: [5068](kindle://book?action=open&asin=B004JN0GA8&location=5068) ^ref-33477

if a method can be called by a value how else can it be called?

---
If you recall, from our explanation of the static vs. non-static methods, by making this routine a static I do not have to make an instance of the MyMath class. — location: [5107](kindle://book?action=open&asin=B004JN0GA8&location=5107) ^ref-10207

---
So far, the only constructor we have takes two parameters but the instantiation line is trying to call one without any parameters. — location: [5714](kindle://book?action=open&asin=B004JN0GA8&location=5714) ^ref-53687

the constructor we built "public Person(string aName, byte theAge)" in the Person class is requiring both aName and theAge as arguments.  the instantiation in Program class "new Person()" is not referencing any arguments.

---
constructor is used to prepare the object that was just instantiated. — location: [5749](kindle://book?action=open&asin=B004JN0GA8&location=5749) ^ref-32303

---
mentioned that the constructor is executed whenever a new instance of a class is created.  This kind of a constructor is more precisely know as an Instance Constructor, or Class Constructor.  However, your class definition can also contain static methods, which are available without having to create an instance of the object – meaning an instance constructor will not be executed.  Som what can you do if you need to prepare something (such as variables) which your static methods will need? — location: [5760](kindle://book?action=open&asin=B004JN0GA8&location=5760) ^ref-51716

what?   why would you have a static method in the constructor?

---
this — location: [5907](kindle://book?action=open&asin=B004JN0GA8&location=5907) ^ref-20921

this keyword can be used anywhere in the class or just in a given method?

---
