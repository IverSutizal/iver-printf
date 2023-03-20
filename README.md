# How to create a printf?
src="https://raw.githubusercontent.com/IverSutizal/Recursos-de-imagenes/main/Presentaci%C3%B3n%20diapositiva%20Marca%20creativa%20Doodle%20Blanco%20y%20marr%C3%B3n.png" height="90%" width="70%"></h1>

## Description

The printf project is a collaboration between Daisy Chipana and Iver Sutizal, actual students of Software Engineering at Holberton School, were a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".


 - The **_printf()** function takes one argument:

	 A string with / without specifiers to print and gives the output formatted. 
	 
	 The string is printed character by character and when founds a '%' with a letter calls one of that parameters and print them instead the specifiers.

## Format Specifiers

Format generators are a format with which we tell the function to take the arguments ​​according to the indicated type.

|**Type**|FORMAT  |
|--|--|
|**%c**|: Print a character passed as parameter.  |
| **%s** |: Prints a string.  |
| **%%** |: Print a percentage symbol.|
| **%d** |: Prints a signed decimal number.|
| **%i** |:Prints a signed number (int).|


## Future Features
- **%u** : Prints an unsigned decimal number.
- **%o** : Prints the octal unsigned integer conversion.
- **%x** : Unsigned hex conversion to lowercase.
- **%X** : Unsigned hex conversion to uppercase.
- **%p** : Print a memory address(pointer).
- **%b** : Converts the unsigned integer to binary and prints it.
- **%r** : Print the inverted string.
- **%R** : Use ROT13 to converts the letters with the thirteenth letter forward of the alphabet.
- **%b** : The specifier %b doesn't work all correctly
## Principal function
|**Functions** <a href="https://www.youtube.com/watch?v=NyP98HXK6A4" target="_blank"><img height="32" src="http://assets.stickpng.com/thumbs/580b57fcd9996e24bc43c545.png" target="_blank"> </a>|printf |
|--|--|

## Functions used
|**Functions**|printf|
|--|--|
|**print_caracter:**| caracter.  |
|**print_hexa:**| hexa.  |
|**print_string:**| string.|
|**print_float:**| float.|
|**print_floatExpo:**| floatExpo.|
|**print_floatGeneral:**| floatGeneral.|
|**print_DecixAsi:**| DecixAsi.|
|**print_numDec_Int:**| Dec or Int.|
|**print_octal:**| octal.|

## Example
1. Print a character :
    ```c 
	    Input _printf("Character:[%c]\n", 'H'); 
		Output Character:[H]
2. Print percentage:
    ```c 
	    Input _printf("hello %%%world\n", "world", 1, 2, 3, 4);
	    Output: hello %%world
4. Print numbers:
    ```c 
	    Input _printf("Negative:[%d]\n", -762534);
	    Output: Negative:[-762534]
5. Print a string:
    ```c 
	    Input _printf("Let's try to printf a simple sentence.\n");
	    Output: Let's try to printf a simple sentence.
	    
## *Recommendation*
+ Be calm.
+ Ask your peers (friends).
+ Read the resources.
+ Find additional sources.
+ Assemble your flowchart.
+ Review your flowchart.
+ Ask your peers.
+ Review past projects to be clear about what you will do.
+ Organize your ideas to create the functions.
+ Important: Pass Betty.

## Flowchart
<h1 align ="center">
<img src="https://raw.githubusercontent.com/IverSutizal/Recursos-de-imagenes/main/printf.png" height="100%" width="90%"></h1> 

<h1 align ="center"> <img src="https://raw.githubusercontent.com/IverSutizal/Recursos-de-imagenes/main/printf1.png" height="100%" width="90%"></h1>


## Demonstration of the use of printf
Give it a click <a href="https://www.youtube.com/watch?v=NyP98HXK6A4" target="_blank"><img height="32" src="http://assets.stickpng.com/thumbs/580b57fcd9996e24bc43c545.png" target="_blank"> </a>       
[![Alt text](https://img.youtube.com/vi/NyP98HXK6A4/0.jpg)](https://www.youtube.com/watch?v=NyP98HXK6A4)
## References when creating a printf
1. https://www.it.uc3m.es/pbasanta/asng/course_notes/input_output_printf_es.html
2. http://www.firmcodes.com/write-printf-function-c/
3. https://www.equestionanswers.com/c/c-printf-scanf-working-principle.php

## References when creating a man printf
1. https://linux.die.net/man/3/printf
2. https://man7.org/linux/man-pages/man3/printf.3.html
3. https://www.cyberciti.biz/faq/linux-unix-creating-a-manpage/
4. https://www.howtogeek.com/682871/how-to-create-a-man-page-on-linux/

## Authors
| [<img src="https://avatars.githubusercontent.com/u/105659277?v=4" width=130><br><sub> Daisy Geraldine </sub>](https://github.com/DaisyGeraldine)   | [<img src="https://avatars.githubusercontent.com/u/104711420?v=4" width=130><br><sub> Iver Sutizal </sub>](https://github.com/IverSutizal)   |
|--|--|
| <div align="center"> <a href="mailto:chipanal@hotmail.com" target="_blank"> <img height="32" src="https://www.pngall.com/wp-content/uploads/12/Gmail-Email-PNG-Pic.png" target="_blank"> <a href="https://twitter.com/DaisyChipana" target="_blank"> <img height="32" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c53e.png"> </a> <a href="https://www.instagram.com/dage_cl/" target="_blank"> <img height="32" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c521.png" target="_blank"> </a>  </div>| <div align="center" > <a href="mailto:chipanal@hotmail.com" target="_blank"> <img height="32" src="https://www.pngall.com/wp-content/uploads/12/Gmail-Email-PNG-Pic.png" target="_blank"> <a href="https://twitter.com/IverSutizal" target="_blank"> <img height="32" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c53e.png"> </a> <a href="https://www.instagram.com/iversutizal/" target="_blank"> <img height="32" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c521.png" target="_blank"> </a> </div> |
| <div align="center"><a href="https://www.linkedin.com/in/daisy-chipana-lapa-1b96861b4/" target="_blank"> <img height="32" src="https://www.marcoszuniga.com/wp-content/uploads/2020/05/Linkedin-Logo.png" target="_blank"> </a> <a href="https://medium.com/@chipanal" target="_blank"> <img height="32" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" target="_blank"> </a> <a href="https://www.youtube.com/channel/UCCq-zyaajPYrAUL_AXUOcaQ" target="_blank"><img height="32" src="http://assets.stickpng.com/thumbs/580b57fcd9996e24bc43c545.png" target="_blank"> </a></div> |   <div align="center"> <a href="https://www.linkedin.com/in/iver-sutizal-3aa913197/" target="_blank"> <img height="32" src="https://www.marcoszuniga.com/wp-content/uploads/2020/05/Linkedin-Logo.png" target="_blank"> </a> <a href="https://medium.com/@iversutizal" target="_blank"> <img height="32" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" target="_blank"> </a> <a href="https://www.youtube.com/channel/UCaFAl3KzbcNQl29MG5PAxqA" target="_blank"><img height="32" src="http://assets.stickpng.com/thumbs/580b57fcd9996e24bc43c545.png" target="_blank"> </a> </div>|
