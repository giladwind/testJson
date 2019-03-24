Simple test file create a JSON.parse by myself

all the code is inside the index.html file

in the script part a new object will be created into a variable named : JSONParse
this will only have one function : parse  (JSONParse.parse)

the function receives 2 params JSONParse.parse(textToParse : string , {} : options)

options can be : {
   dateFromStringParseFunction: function with 1 parm as sting will try to create a date from string returns Date or null (default has a sample function)
   mustBeJSON: bool : will allow for values that are not in json to be returned as well if set to false  (default : false)
   };


if not options will be sent a default set will be used

the defaults can be changed so that all calls will run the same




