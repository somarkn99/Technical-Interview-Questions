# PHP Interview Questions

1.  What are the differences between include and require in PHP?
    <br>
    `include` and `require` both include a file, but `require` will produce a fatal error if the file is not found, while `include` will only produce a warning.
    <br>
    <br>
2.  What is the difference between == and === ?
    <br>
    `==` is the equality operator and checks if the values are equal, while `===` is the identity operator and checks if the values and types are equal.
    <br>
    <br>
3.  How can you prevent SQL injection in PHP?
    <br>
    SQL injection can be prevented by using prepared statements with parameterized queries or by using PDO (PHP Data Objects) or MySQLi with parameter binding.
    <br>
    <br>
4.  What is the difference between abstract and interface Classes?
    <br>

- The interface does not accept properties but the abstract accepts.
- All Function within interface must be public but abstract accepts public and protected.
- Able to inherit more than interface within Class but abstract accepts only one inheritance
- For inheritance of the interface we use implementation and the abstract we use extend.
  <br>
  <br>

5. What is final class?
   <br>
   It's the class of the inheritance process from it is forbidden.
   <br>
   <br>
6. What is final method ?
   <br>
   She method does not accept overidden
   <br>
   <br>

7.
