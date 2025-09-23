## What is JSON

- JSON stands for JavaScript Object Notation.
- JSON is a lightweight format for storing and transporting data.
- JSON is often used when data is sent from a server to a web page.
- JSON is *"self-describing"* and easy to understand.

- In other words:
    - JSON is used for storing.
    - JSON format is lightweight.

## Example 
````
{
"employees":[
    {"firstName":"John", "lastName":"Doe"},
    {"firstName":"Anna", "lastName":"Smith"},
    {"firstName":"Peter", "lastName":"Jones"}
]
}
````
## JSON Syntax Rules
- Data is in name/value pairs.
- Data is separated by commas.
- Curly braces hold objects.
- Square bracket hold arrays.

## JavaScript Object Notation
- The JSON format is syntactically identical to the code creating JavaScript object.
- Because of this similarity, a JavaScript program can easily convert JSON data into native JavaScript object.

## JSON Data
- JSON data is written as name/value pairs, just like JavaScript object properties.
- A name/value pair consists of a field name (in double quotes), followed by a colon, followed by a value:

    `` "firstName":"John" ``

## JSON Object
- JSON objects are written inside curly braces.
- Just like in JavaScript, objects can contain multiple name/value pairs:

``{"firstName":"John", "lastName":"Doe"}``

## JSON Array
- JSON arrays are written inside square brackets.
- Just like in JavaScript, an array can contain objects:
````
"employees":[
    {"firstName":"John", "lastName":"Doe"},
    {"firstName":"Anna", "lastName":"Smith"},
    {"firstName":"Peter", "lastName":"Jones"}
]
````
- In the example above, the object "employees" is an array. It contains three objects.
- Each object is a record of a person (with a first name and a last name).