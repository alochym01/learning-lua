# Install Lua 5.3
- using ius repo
  + install https://centos7.iuscommunity.org/ius-release.rpm
  + yum install lua53u
  + using lua(version 5.3) cli -> lua-5.3 or /bin/lua-5.3
- comments in lua

```
	--single line comment

	--multiple line comment

	--[[
		this is a first line in comment
		this is a second line in comment
	--]]
```
- Variables
  + Global variables: All variables are considered global unless explicitly declared as a local
    + Syntax

	```
		alochym = "Global variable declare"

		--[[declaration of d and f as global variables. Here value of f is nil --]]
		d, f = 10
	```
  + Local variables: When the type is specified as local for a variable then its scope is limited with the functions inside their scope.
    + Syntax

	```
		local alochym
	```
  + Table fields: This is a special type of variable that can hold anything except nil including functions.
- Data Types
  + nil: Used to differentiate the value from having some data or no(nil) data.
  + boolean: Includes true and false as values. Generally used for condition checking
  + number: Represents real(double precision floating point) numbers
  + string: Represents array of characters.
  + function: Represents a method that is written in C or Lua.
  + userdata: Represents arbitrary C data
  + thread: Represents independent threads of execution and it is used to implement coroutines
  + table: Represent ordinary arrays, symbol tables, dictionary, sets, records, graphs, trees, etc., and implements associative arrays. It can hold any value (except nil).
  + type: enables us to know the type of the variable
	
	```
		print(type(true))		=> boolean
		print(type("alochym"))	=> string
	```
  + 
  + 
  + 
  + 