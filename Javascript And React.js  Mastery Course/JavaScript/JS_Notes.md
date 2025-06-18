1.what is JS ?
  JAvascript is a  scripting programming language. it is used to make page dynamic &intracrtive.

2.what is console ?
  console.log() is a function in JavaScript used to print messages or output values to the browser's console.

3.how to write comment ?
  we have two options to do comment  
  1.//(backward slash)
  2.  /*
        comment
    */

4.why we need this ?
  Comments in JavaScript are lines that are not executed by the browser. They are written just for understanding, explanation, or reminders for yourself or other developers reading the code.


  //Variables and Constants

  what is variable ?
    variable is a container that is used to store data values. such as numbers, strings, or objects.

    we have three ways to declare variables
    Let Var Const

    Ex:-
    let name = "Amrit";      // Stores a string
    const pi = 3.14;         // Constant value
    var age = 25;            // Old method


var → Purana hai, function scope me kaam karta hai

let → Naya aur safe hai, block scope me hota hai

const → Constant hai, value change nahi hoti



var is old, function-scoped, allows redeclaration and value change.
let is modern, block-scoped, allows value change but not redeclaration.
const is also block-scoped, but its value cannot be changed or redeclared.

🗨️ Hindi + English Mix Version:

var purana hai, function scope me kaam karta hai, value aur naam dono change ho sakte hain.
let naya hai, block scope me kaam karta hai, sirf value change ho sakti hai.
const block scope me hota hai, value aur naam dono fix hote hain.

      var x = 10;  // can redeclare & reassign
      let y = 20;  // can reassign, not redeclare
      const z = 30; // can't reassign or redeclare







              <!-- Data Types  -->

what is Data Types ?
  A data type defines the kind of value a variable can hold — like numbers, text, true/false, etc.


 1. Primitive Data Types (Basic types)
Type	Example
String	"Hello"
Number	123, 3.14
Boolean	true, false
Undefined	Variable declared but no value
Null	Empty or no value
BigInt	Very large numbers
Symbol	Unique value

🔸 2. Non-Primitive (Reference) Data Types
Type	Example
Object	{ name: "Amrit" }
Array	[1, 2, 3]
Function	function() {}

🗨️ Hindi + English Mix:
JavaScript me data types batate hain ki variable kis type ka data store karega — jaise number, text, true/false, object, etc.
Primitive types simple hote hain, aur non-primitive types complex ya multiple value rakhte hain.



let name = "Amrit";      // String
let age = 22;            // Number
let isStudent = true;    // Boolean
let data = null;         // Null
let info = { city: "Delhi" }; // Object







