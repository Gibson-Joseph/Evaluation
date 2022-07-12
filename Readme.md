# TypeScript Evaluation1:

# 1. Which of the following is valid command to compile typescript file?
a. ts abc.ts  
b. t abc.ts  
c. tsc abc.ts  
d. tst abc.ts  

ANSWER:  
d. tsc abc.ts

---

# 2. Which is not true about typescript?
a. It is interpreted like javascript  
b. It is a superset of javascript  
c. It does support static data types  
d. Typescript is case sensitive  

ANSWER:  
a. It is interpreted like javascript

---

# 3. Which of the following is valid typescript statement?
a. var string a=”Hello”;  
b. string a=”Hello”;  
c. var a:string=”Hello”;  
d. var a=”Hello”:string;  

ANSWER:  
c. var a:string=”Hello”;

---

# 4. Which statement does yield error in typescript?
a. var a=”Hello”;  
b. var a:string;  
c. var b:number=12;  
d. var a:string=12;  

ANSWER:  
d. var a:string=12;

---

# 5. What will be output of : var a:string=47; console.log(“Value of a= ”+a);
```javascript
var a:string=47;
console.log('value of a ='+ a);
```
a. Value of a=47  
b. Value of a=0  
c. Value of a=  
d. None of the above  

ANSWER:  
d. None of the above

---

# 6)Which of the following function definition is correct in typescript?
a. number function abc(string a){return 12;}  
b. function abc(string a,number b){return 12;}  
c. both a and b  
d. none of the above  

Answer:  
c. both a and b

---

# 7) What is type of a?
```javascript
  var a = function (): number {
  return 12;
};
a();
```
a. number  
b. int  
c. both a and b  
d. none of the above  

ANSWER:   
d. none of the above.

---

# 8. class keyword is:
a. a feature of typescript  
b. feature of javascript  
c. both a and b  
d. none of the above  

ANSWER:  
c. both a and b

---

# 9)What will be output of obj
```javascript
 class Bird {
Bird () { console.log('I am Bird');}
}
var obj=new Bird();
```
a. Error  
b. I am Bird  
c. Bird am I  
d. None of these  

Answer:  
d. None of these  

---

# 10) What is the Output of the Bellow code?
```javascript
class MyClass {
  var a=12;
  }
  var obj=new MyClass();
  console.log('Value of a=' +a);
```
a. Error  
b. Value of a =12  
c. A is private and cannot be accessed  
d. None of the above  

Answer:  
a. Error

---

# 11) Which of following is true?
```javascript
class MyClass{
  a:number;
  func(){
    
  }
}
```
a. func is public and a is private  
b. func is public and a is protected  
c. both are public  
d. both are private  

Answer:  
c. both are public.

---

# 12. Which of the following is not true about typescript?
a. It supports inheritance.  
b. It supports abstract classes.  
c. It supports interfaces.  
d. None of the above.  

ANSWER:  
b. It supports abstract classes.

---

# 13. Which of the following is correct syntax for making a static variable in typescript?
a. static st:string;  
b. st:string:static;  
c. static(st:string);  
d. none of the above  

ANSWER:  
static st:string;

---

# 14). Which of the following is correct way of inheriting in typescript?
a. class B:A{}  
b. class B inherits A{}  
c. class B: class A{}  
d. class B extends A{}  
e. class B extends class A{}  

ANSWER:  
d. class B extends A{}

---

# 15. Program that converts a code from one high level language to another high level language is called
a. Compiler  
b. Decompiler  
c. Inter translator  
d. None of the above  

Answer:  
a.compiler

---

# 16. What will be the output of following in typescript?
```javascript
var a=12;
a='Yes';
console.log(a);
```
a. 12  
b. Yes  
c. 12Yes  
d. None of the above  

ANSWER:  
d. None of the above

---

# 17. What will be the output of : abc();
```javascript
function abc(a:string){
  console.log(a);
  }
  abc();
```
a. Error  
b. NULL   
c. “”  
d. None of the above  

ANSWER:  
a. Error

---

# 18) What is role of constructor keyword?
a. No such keyword exists in typescript.  
b. Is used to call constructor of an instance.  
c. Is used to define constructor for class.  
d. None of the above.  

ANSWER:  
c. Is used to define constructor for class.

---

# 19. Can we use alert() in typescript?
a. Yes  
b. No  

ANSWER:  
a. yes

---

# 20. What is the error in following code?
```javascript
class A{
var abc:number;
}
```
a. No Error  
b. There must be a constructor  
c. There must be ; at end of the class  
d. var should not be used inside class  

ANSWER:  
d. var should not be used inside class

---
