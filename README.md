# Solidity-0.7.0
All the solidity Programs supports version 0.6.3  to 0.7.0;

![](https://sixpl.com/wp-content/uploads/2018/05/solidity-1520540026519.png)


## Warning :

Be careful with using Unicode text, as similar looking (or even identical) characters can have different code points and as such are encoded as a different byte array.

## Note :

All identifiers (contract names, function names and variable names) are restricted to the ASCII character set. It is possible to store UTF-8 encoded data in string variables.

## Solidity Types : Main Tips
► Solidity value types include booleans, integers, fixed point numbers, addresses, contract types, 
  fixed-size byte arrays, rational and integer literals, and enums.
  
► Reference types such as arrays and structs can be stored in these options: memory, storage, and calldata.

► Mapping in Solidity is seen as hash tables (initialized virtually) with the goal to contain 
  each potential key and map it to a value (its byte-representation should consist of zeroes only).
 
► LValue a is related to delete and delete a operators. a also has operators as shorthands.
