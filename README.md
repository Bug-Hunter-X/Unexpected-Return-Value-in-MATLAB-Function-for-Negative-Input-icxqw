This repository contains a MATLAB function that demonstrates an uncommon error related to unexpected return values when handling negative input.  The bug.m file shows the original function with the error, while bugSolution.m provides a corrected version.  The issue stems from the use of a 'return' statement within a conditional block, prematurely exiting the function before all code is executed.