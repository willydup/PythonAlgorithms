<h1>Python: Algorithm for File Updates</h1>

<h2>Description</h2>
In this practice scenario, an organization has restricted access to certain information. They have an “allow list” of IP addresses that identifies the employees who can access the restricted content, which is under the file name “allow_list.txt”. There is also a “remove list” that identifies IP addresses that shouldn’t have access. I created an algorithm to automate updating the “allow_list.txt” file and remove the IP addresses that should not have access.
 
<br />

<h2>Step by Step</h2>

<p align="center">
Open the File that Contains the Allow List: <br/>
<img src="https://i.imgur.com/77RdUpA.png" height="80%" width="80%"
 <br /> 
<br />
Read the File Contents:  <br/>
<img src="https://i.imgur.com/rT5Z2iG.png" height="80%" width="80%"
<br />
<br />
Convert the String into a List: <br/>
<img src="https://i.imgur.com/XIWVkGz.png" height="80%" width="80%"
<br />
  <br />
Iterate Through the Remove List: <br/>
<img src="https://i.imgur.com/N1Qi3gl.png" height="80%" width="80%"
<br />  
  <br />
Remove IP Addresses that are on the Remove List: <br/>
<img src="https://i.imgur.com/03cUNEx.png" height="80%" width="80%"
<br />  
  <br />
Update the File with the Revised List of IP Addresses: <br/>
<img src="https://i.imgur.com/ndmgIY3.png" height="80%" width="80%"
  <br />
  <br />
Summary: <br/>
<img src="https://i.imgur.com/7OwDHrd.png" height="80%" width="80%"
<br />  
  <br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
