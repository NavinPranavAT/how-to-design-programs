#**Notes** 
By *“good programming,”* we mean an approach to the creation of software that relies on systematic thought, planning, and understanding from
the very beginning, at every stage, and for every step.
###Systematic program design
A program interacts with people, dubbed users, and other programs, in which case we speak of server and client components
In this context, “systematic program design” refers to a mix of two concepts: design recipes and iterative refinement.
Design Recipes apply to both complete programs and individual functions.

###Functional-level design recipes
My notes - basically they are sharing six steps for design process
1. From Problem Analysis to Data Definitions - *Identify the information that must be represented and how it is represented in the chosen programming language. Formulate data definitions and illustrate them with examples.*
2. Signature, Purpose Statement, Header - *State what kind of data the desired function consumes and produces. Formulate a concise answer to the question what the function computes. Define a stub that lives up to the signature.*
3. Functional Examples - *Work through examples that illustrate the function’s purpose.*
4. Function Template - *Translate the data definitions into an outline of the function.*
5. Function Definition - *Fill in the gaps in the function template. Exploit the purpose statement and the examples.*
6. Testing - *Articulate the examples as tests and ensure that the function passes all. Doing so discovers
mistakes. Tests also supplement examples in that they help others read and understand the
definition when the need arises—and it will arise for any serious program.*

Iterative refinement 
Notes - Getting everything right at the first is nearly imposible
iterative refinement
recommends stripping away all inessential details at first and finding a solution for the remaining core problem. A refinement step adds in one of these omitted details and resolves the expanded problem, using the existing solution as much as possible. Here the author mentiones that programmer are mini scientist who predict model.

DrRacker and the Teaching languages

This is book is build with their own programming language. This language is similar to the major current trending languages like Python, js, java etc.
