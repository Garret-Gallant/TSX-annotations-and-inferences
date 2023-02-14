# Type annotations and Type inferences

Type annotations are:
<ul>
<li>Code we add to tell TS what type of value a variable will refer to</li>
</ul>
Type inferences are:
<ul>
<li>Code we add to tell TS what type of value a variable IS referring to</li>
</ul>

Annotation format is as follows during definition: 
let variableName: type = value;

Array Specific Annotation
let variableName: arrayOfStrings[] = ["actualArray", "actualArrayValueTwo"];
let variableName: arrayOfBooleans[] = [true, true, false];

Class/Instance Specific Annotation:
class NameOfClass {}
let variableName: NameOfClass = new NameOfClass();

Object Literal: 
let point: { x: number; y: number; } = {
  x: 10,
  y: 20
}




