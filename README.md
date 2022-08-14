# PHP-Basics

### PHP - SYNTAX:
**A PHP script starts with `<?php` and ends with `?>`.**
```
<?php 
-----php code goes here------ 
?>
```
**Example:** 
```
<html>
<body>
<p>Printing Hello World using php</p>

<?php
echo "Hello World!";
?>

</body>
</html>
```
```
Output : 
Printing Hello World using php
Hello World!
```

### Comments in PHP : 
```
<?php
// This is a single-line comment

# This is also a single-line comment

/* Multi
      Line
        Comment */
?>
```

### PHP VARIABLES : 
In PHP, a variable starts with the `$` sign, followed by the name of the variable.

syntax :
```
$var_1 = "Hello PHP" 
```
Here,in the syntax `$var_1` is the ariable name which we have declared and 
"Hello PHP" is the value assigned to that variable.

_A variable declared outside a function has a GLOBAL SCOPE and can only be accessed outside a function.<br>
A variable declared within a function has a LOCAL SCOPE and can only be accessed within that function._ <br>
**Example:**
```
<html>
<head>
  <title>PHP Variable</title>
 </head>
 <body>
      <?php
      $var_1 = "Hello PHP";
      echo $var_1;
      ?>
 </body>
 </html> 
 ```
 
 ```    
Output:
Hello PHP
```

### PHP Data Types : <br><br>
**PHP supports the following data types:**
<br>
**Pre-defined data types**
-   String(Sequence of characters)<br>
-   Integer(Whole Numbers)<br>
-   Float/Double(Floating Point numbers)<br>
-   Boolean(True/False)<br>
**User defined data types**
-   Array(Stores Collection of values of similar data types)<br>
-   Object(instance of the class)<br>
**Special data types**
-   NULL(having only null values)<br>
-   Resource<br><br>
**Pre-defined data types Example :**
```
<html>
<head>
  <title>PHP Data Types</title>
 </head>
 <body>

      <?php
      $var_1 = "Hello PHP";
      echo $var_1; //String
      echo "\n\n";

      $x = 999;
      var_dump($x); //Integer
      echo "\n\n";

      $y = 9.99;
      var_dump($y); //Float

      $z = true;
      var_dump($z); //Boolean
      ?>

 </body>
 </html>
 ```
 **User defined data types** <br>
 **Example(Arrays)**
 ```
 <html>
<head>
  <title>PHP Data Types</title>
 </head>
 <body>

      <?php
      $fruits = array("Apple","Banana","Kiwi");
      var_dump($fruits); //Arrays
      ?>

 </body>
 </html>
 ```



       
        
  
  
  
      
      
      
      
      
      
      
      
      
      
      
      
      

