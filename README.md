# BIO-CSS

##Combining CSS methodologies with BIO
Writing good CSS code started to be a common foundation for large projects, as every other programming language we often have different problems such as over-engineering, overwritten code, hard debugging, no comments, messy code,  no best practice considered etc.

![gif angry](https://media.giphy.com/media/ToMjGpIYtgvMP38WTFC/giphy.gif)

To avoid these problems you should use a css methodology.
 
But before starting, let's take a step back!

**Scalable, Maintainable, Modular**.
These are the main words we usually hear when we talk about CSS methodologies, so let's explain the meaning:

* **Scalable CSS**: when CSS increases in size but it can be still maintained easily.
* **Maintainable CSS**: the possibility to make changes without worrying about accidentally caused problems somewhere else.
* **Modular CSS**: gives you opportunity to split your CSS code into independent parts, which are called modules. Now let's understand what a module is: a module is a unit that works independently from other units.
For example, imagine a living room with tv, library and sofà.
In this case tv, library, sofà are independent modules and we can conclude that tv doesn't need library to work and neither the sofà or the library needs each other to work. Modules can have also components, for instance: the television has the controller as component. **As tv, sofà and library create the living room, different modules can create complex system**.

The CSS methodologies are useful because they make the CSS code **Scalable**, **Maintainable** and **Modular**. The most famous are: **BEM, SMACSS, OOCSS, ITCSS**
I'm not here to explain you these methodologies, you can find here some very good explanation: BEM, SMACSS, OOCSS and ITCSS.
I have been thinking a while if mixing all 4 methodologies is the best solution and how it is possible.
I've understood that SMACSS is very difficult to use with the others, especially for 2 reason:

* It could be confusing if you use BEM and you start to use the prefix of SMACSS
* In my opinion it's more useful to organize CSS rules with ITCSS instead of SMACSS

Meanwhile I've understood that combining:
**B**EM
**I**TCSS
**O**OCSS
We can reach perfect CSS structure!

#### HOW TO USE THEM
Do you remember how I explained above what modular means?
Using  BEM and some new frameworks like React or Vue.js, it's becoming very important the concept of component, so in BIO we should think like that:
**MODULAR    → BIO**
Module  → Components
Components → Elements

In **BIO** we can imagine a module like a component (it would be a block in BEM) where the component can have different elements (as the BEM convention say).
In few words in BIO we have to use the files structure of ITCSS, using the naming convention of BEM and the principle of OOCSS: when CSS "object" is a repeating visual pattern, is better to abstract it into an independent snippet of CSS. Something like that 👇

![code example](https://postimg.cc/87MXZrN5)

With this CSS structure you have everything on a visual level and that makes everything easier, readable, speaking, no messy code, easy to debug, using best practice, no overwritten code because it's obvious where to add code.

That's why **BIO** makes it easier to work with large scale css projects.

![gif yeah](https://media.giphy.com/media/l4HohVwFLzHKcwa6A/giphy.gif)