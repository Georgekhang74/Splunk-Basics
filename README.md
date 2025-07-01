# Splunk-Basics


</p>

<h1>Basic search in Splunk</h1>
This tutorial outlines completing a basic search with Splunk. <br />



<h2>Environments and Technologies Used</h2>

- Splunk cloud




<h2>Upload data</h2>

![Screenshot 2025-07-01 124857](https://github.com/user-attachments/assets/9df521c9-6f86-42aa-9830-53f476a28722)


</p>
<p>
 - In this lab I will be uploading a file called "tutorialdata.zip"
  <p>
  - make sure these are the right settings for the input data:
    <p>
  Input Type: Uploaded File
<p>
  File Name: tutorialdata.zip
<p>
  Source Type: Automatic
<p>
  Host: Source path segment number: 1 
<p>
  Index: Default
</p>
<br />


![Screenshot 2025-07-01 125311](https://github.com/user-attachments/assets/ec377424-6014-4e84-b21b-26bf3c26c147)


</p>
<p>
 - Do a simple search 
</p>
<br />


![image](https://github.com/user-attachments/assets/e50904f8-8cab-4c10-a81d-eea211fd1550)


</p>
<p>
 - When Splunk indexes data, it attaches fields to each event. These fields become part of the searchable index event data.
  <p>
    -Examine the feilds
  </p>
</p>
<br />


![image](https://github.com/user-attachments/assets/fdfff124-be63-401a-96d5-d8317d8c4f0d)




</p>
<p>
 - Narrow down your search
 <p>
   -This search expands on the search from the previous task and searches for the keyword fail*. The wildcard tells Splunk to expand the search term to find other terms that contain the word fail such as failure, failed, etc. Lastly, the keyword root searches for any event that contains the term root.
 </p>

  
