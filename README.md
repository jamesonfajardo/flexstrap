# Flexstrap
Flexstrap is a responsive library that is based on flexbox, and can be used alongside bootstrap.

Unlike bootstrap's row + col- class, flexstrap's columnizer only needs to include the class in the parent element and it will automatically format its child elements to column depending on the given pixels.

# Syntax
Flexstrap columnizer accept inputs from 300px up to 1200px with 50px intervals  
Always include the class **`f1`** (flex center) then the flexstrap columnizer class.  
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
If container is above 350px  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/horizontal.png)  
If container is below 350px  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/vertical.png)  

# Flex Combinations  
Basic flex styles are bound to classes a, b, c, d, f  
Here are some combinations that you can use standalone or together with columnizer  
Assuming that the parent element is 100x100 pixels and has no padding
___
![#800080](https://placehold.it/15/800080/000000?text=+) **top-left**  
`class='a b1 c1'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/top-left.png)  

![#800080](https://placehold.it/15/800080/000000?text=+) **top-center**  
`class='a b2 c1'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/top-mid.png)  

![#800080](https://placehold.it/15/800080/000000?text=+) **top-right**  
`class='a b3 c1'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/top-right.png)  

![#800080](https://placehold.it/15/800080/000000?text=+) **top-space_around**  
`class='a b4 c1'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/top-sa.png)  

![#800080](https://placehold.it/15/800080/000000?text=+) **top-space_between**  
`class='a b5 c1'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/top-sb.png)  
___
![#F08080](https://placehold.it/15/F08080/000000?text=+) **center-left**  
`class='a b1 c2'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/mid-left.png)  

![#F08080](https://placehold.it/15/F08080/000000?text=+) **center-center**  
`class='a b2 c2'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/mid-mid.png)  

![#F08080](https://placehold.it/15/F08080/000000?text=+) **center-right**  
`class='a b3 c2'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/mid-right.png)  

![#F08080](https://placehold.it/15/F08080/000000?text=+) **center-space_around**  
`class='a b4 c2'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/mid-sa.png)  

![#F08080](https://placehold.it/15/F08080/000000?text=+) **center-space_between**  
`class='a b5 c2'`  
![pysql](https://raw.githubusercontent.com/jamesonfajardo/flexstrap/master/mid-sb.png)  
