```
add.wasm:	file format wasm 0x1

Section Details:

Type[1]:
 - type[0] (i32, i32) -> i32
Function[1]:
 - func[0] sig=0 <add>
Export[1]:
 - func[0] <add> -> "add"
Code[1]:
 - func[0] size=7 <add>
```

**Type[1]** - Has a single type signature
```(i32,i32) -> 2``` Takes in two i32 params and outputs one i32 value

**Function[1]** Has a single function
```sig=0 <add>``` Function of which the name is add

**Export[1]** Has a single export
```func[0] <add> -> "add"``` Function add is exported as "add"

