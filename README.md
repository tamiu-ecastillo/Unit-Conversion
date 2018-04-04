# Unit-Conversion
Texas A&M International University
ENGR 1202 - Spring 2018
Course Project

Introduction.

This project involves the development of a MATLAB-based, menu-driven application to aid in the unit conversion. This is a group project and you are encouraged to work with other groups on the required programming concepts. Each group will be responsible for submitting their own deliverables. (See below.)

Coding Standard.

It is important to observe good coding practices when implementing large code projects, like this one. The following is a short list of guidelines that you should follow when writing your code. It is by no means an exhaustive set of guidelines for creating high quality code, but it is definitely the minimum requirement.

**Comment your code**

~ Comments should explain the code’s intent or summarize what it does

~ Comments should be kept up to date

~ Comments should be clear and correct

~ Avoid endline comments

~ Focus on why rather than how

~ Avoid abbreviations

~ Remove extraneous, redundant, and self-indulgent comments

~ Comment on units and ranges of data

~ Comment on limitations of input data

~ Comment every global variable

~ Don’t use a comment where renaming a variable or function would also work

~ Explain the purpose of every routine and give facts about its input, output, usage, limitations, error corrections, global effects, and sources of algorithms

~ Good code should document itself; if the code requires extensive commenting, rewrite the code

**Variable and routine naming**

~ Names should fully and accurately describe the entity the variable represents, or the function the routine computes

~ Names should not be too short or too long, somewhere between 10 and 16 characters on average is the best

~ Pick a naming convention and use it consistently

  > Differentiate between variable names and routine names, between global and local variables, between constants and variables
  
  > Use camel case, underscoring, or both (for different things), but not neither
  
    - Camel Case: numberOfWidgets
    
    - Underscoring: number_of_widgets
    
  > Constants are all uppercase: GRAVITY, COEFF_FRICTION, KG_PER_LBM
  
  > Indices are i,j,k
  
  > c is a character, s is a string, n is a counting number
  
**Error handling**

~ Practice defensive programming

~ Handle garbage in

  > Check values of data from external sources
  
  > Check values of all input parameters
  
  > Decide how to handle bad inputs
  
~ Handle expected errors appropriately, e.g. one or a combination of

  > Substitute the next piece of valid data
  
  > Substitute the closest legal value
  
  > Return the same answer as the previous time
  
  > Return an error code
  
  > Display an error/warning message
  
  > Log an error/warning message to a file
  
  > Shut down
  
~ Fail gracefully on unexpected errors:

  > use try/catch blocks
  
  > make it very hard to crash the program
  
**Code layout and style**

~ Use whitespace appropriately to maximize readability

  > Spaces, tabs, newlines
  
~ Good visual layout accurately and consistently represents the logical structure of a program

~ Group related code together into blocks, like paragraphs in an essay

  > Put a blank line between blocks
  
~ No more than 80 characters per line

  > Indent continuation lines


Deliverables.

As stated above, this is a group project and each group is responsible for the deliverables listed below.
There will be two deliverables for this project:
1. Your MATLAB code. We will need all *.m files required to run your code including any user-defined functions that you may use.
2. A short report describing the operation of your code (i.e. a user manual, similar to MATLAB’s own help documentation) and how you went about testing that the code works properly and provides correct results. The testing section of your report should state what tests the code has to pass, argue that the tests adequately cover the specifications for the program, and demonstrate that the code passes the tests. This report should be typed in 12pt Times New
Roman with 1-inch margins and double spaced lines. The report should not be more than 10 pages in length.
Please note: The above represents minimal requirements for the project. You are encouraged to add additional features to make the program more useable and useful for you.

Grading.

The grade for this project is worth 40% of your total course grade as stated in the syllabus.
As part of the grading procedure for this project, all groups’ code will be submitted to the MOSS system to search for examples of plagiarism. MOSS (Measure of Software Similarity) can detect the level of similarity between any one code and all others submitted. Software plagiarism is considered cheating. So, please work together at the concept level, but write your own code for submission.
