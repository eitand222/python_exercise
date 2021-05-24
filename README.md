# python_exercise
 
Question 1 - repository clone 
===================================
Please create a free github account (or use your existing one).
We would like to automate and track a code repository. write a program that clones a repository. Provide the user to ability to choose the verobse level, where he can control the stdout, stderr.
 
Question 2 - files sort and diff
===============================
Please download these two zipped text files.
The files represent data processed from a video clip and appears in the following format:

[frame] [category] [sub category] [data 0] … [data N]

Between each section there is space.

For example, the line:

0 ebaedd6fdf89c816477f81fd233e61b6 dc7abba23fea7c6eb23be7ff2bac6f05 0 18029 32472 63206 14612
 

The zip files provided contain 2 folders with 2 files each with identical names. 
The size of the extracted files is ~1GB.
Please compare the files within the folders, for a comparison purposes, please note the following:
    -File is bit-exact to another if the [data 0..data N] part is identical given the same frame, category and sub-category in both files.
    -The first and last line of each file should be ignored in the comparison process. 
    -Frames inside the files are not necessarily ordered.
    -The files may be over 1GB in size (but not necessarily). Please take this into account.
    -Please provide running-time for your program.
    -If you can think of runtime optimizations for your program that you did not implement, please elaborate on why and estimate how this will affect the results.
 
Question 3 - Create pipline/action.
===============================
Please upload the zip files to your github account.
Please create a pipeline which extracts those zip files and compare the folders as described in 2 after each push. 
If the files are not the same please fail the test. Otherwise pass.
 

Question 4 (BONUS) - GUI
================
Write an application that runs Question 1 as a QT GUI as follow
Notes:
     - the application should have one button "Run" and a text box that shows the running progress
     - the application should indicate a text message before it runs
     - the application should indicate a text message after it runs
     - the application should indicate about the job's success\failure
