Download Link: https://assignmentchef.com/product/solved-cpe457-lab2-pe-file-analysis
<br>
<strong>Lab Description: </strong>The goal of this lab is to provide a practical application to study the PE file format. In completing this lab you will demonstrate a working knowledge of the data contained within the PE file format and demonstrate the use of tools used for parsing this information.

<strong>Lab Environment: </strong>The following PE parsing utilities are recommended, these all require a Windows OS to run.

<ul>

 <li>PE Studio: https://www.winitor.com/</li>

 <li>Dependency Walker: http://www.dependencywalker.com/</li>

</ul>

<strong>Lab Files that are Needed: </strong>example.bin

<h3><strong>Lab Exercise 1:</strong></h3>

In this lab, you will download and use PE studio/Dependency Walker to dive into the example PE file. PE Studio will point out any suspicious items, and generally give you a simple interface to view the contents of an executable or dynamically-linked library (DLL).  Explore the application and use it to answer the following questions:

<ol>

 <li>What is the image base? Does this deviate from the standard image base value used by most compilers?</li>

 <li>What is the value for the <strong>Size of code</strong>?</li>

 <li>Where is the base of code? What section is this in?</li>

 <li>What are the names of the sections in this file? Do any of them deviate from standard names?</li>

 <li>Based on the imported functionality, what do you suspect this program does? What other information can you use to determine program functionality?</li>

</ol>