# Flexstrap
Flexstrap is a responsive library that is based on flexbox, and can be used alongside bootstrap.

Unlike bootstrap's row + col- class, flexstrap only needs to include the class in the parent element and it will automatically columnize it's child elements depending on the given pixels.

# Syntax
Flexstrap accepts inputs from 300px up to 1200px with 50px intervals  
Always include the class **`f1`** (flex center) then the flexstrap class.  
More combinations will be provided after the sample codes    

![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--3 `format child elements to column if width is less than 300px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--3.5 `format child elements to column if width is less than 350px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--4 `format child elements to column if width is less than 400px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--4.5 `format child elements to column if width is less than 450px`  
.  
.  
.  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--10.5 `format child elements to column if width is less than 1050px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--11 `format child elements to column if width is less than 1100px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--11.5 `format child elements to column if width is less than 1150px`  
![#00FA9A](https://placehold.it/15/00FA9A/000000?text=+) .col--12 `format child elements to column if width is less than 1200px`  

# Sample Codes
![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Format child elements to column if parent element is less than 350px  

```
<section class='container f1 col--3.5'>  
  <p>Element 1</p>  
  <p>Element 2</p>  
  <p>Element 3</p>  
</section>
```
