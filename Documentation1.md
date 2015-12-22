# Name: Mathbased_PythagoreanTheorem 

## Examples:



void draw(){
  println(pythagoreanThrm(5,6));  //display the hypotneuse of a right triangle
  
}  
  


float pythagoreanThrm (int a, int b){  // create function pythagorean theorem 
 float c = sqrt(sq(a) + sq(b));  //formula
  return c;  // return result
  
  

}

## Description:
Create a pythagorean theorem function.  In void draw use println() to display the hypotneuse,c, of a right triangle.  Outisde of void draw, the function, pythagroean theorem, must be created. It will have the parameters of the side lengths of the triangle, a and b, while c will be the result we want to dislay when we run the function.

## Syntax:
pythagorean theorem, c = sqrt(sq(a) + sq(b)); 

##Parameters: 
pythagoreanThrm(float a, float b);

##Returns:
return c; //this is the hypotneuse of the right triangle.

##Other notes:
make sure to use println() within void draw to display c when the program is runned 
