<h1>
CIS 191 Project 3
</h1>

ec3-54-200-167-91.us-west-2.compute.amazonaws.com

<ol>

<li> A bare repo is a repository that does not have a working tree It has a <strong>.gitsubdirectory</strong> in the main directory itself unlike a regular repo </li>

<li>The python server pushes the contents of www online via 9001.</li>

<li>The hook recognizes that stuff was pushed to ec2 and takes the contents of deploy copies it into <code>~/www</code>. The server is then reset to show the changes.</li>

</ol>
