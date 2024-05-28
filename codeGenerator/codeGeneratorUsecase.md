# Code Generator 


# Target
A program helping trying you to find the right code to open a secured lock"

## Light Description  
This "< **LANGUAGE** >" application propose help the user testing  possibilities among a list code, for opening a locked for instance. We have a set of codes from "00" to "99". the user can ask the application to propose randomly a code among those possibilities, the user then can validate if the proposed code was ok or not. If the code is valid then the program must say "Success" else the programm must remove the proposed code from the possibilities and allows the user to ask for a new code. 
This application must save in memory the list of tested code and the codes that have not been tested yet

## Deeper Description 
give me an <html + javascript>  code with three buttons, one is 'init', the second is 'generate', the last one is save.

The code must have 2 arrays of string between "00" and "99".  Array named "freeCodes" is filled with the entire list, Array named "usedCode" is empty.

When I click on 'init' button, arrays are loaded from local storage,
When I click on 'generate' button, 1 string picked randomly from "freeCodes", removed from "freeCode" and  pushed to "usedCode". The generate button propose the picked code to the user and allow him to validate or nor. If the 
When I click on "save" button, arrays are saved into localstorage

## UML diagrams

TODO

