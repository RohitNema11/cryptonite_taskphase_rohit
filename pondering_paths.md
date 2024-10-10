# Linux file paths
/ - root(directory) of filesystem
it contains other directories and files <br>
<br>
## The Root
The filesystem starts at /
<br>
The path that starts with the root directory, is referred to as an "absolute path".<br>
<br>
`/pwn`<br>
**pwn.college{cJI9iEWNZVlXJCWwfsrPhBHInJw.dhzN5QDL1IjN0czW}<br>**
<br>
## Program and absolute path
Running a program present inside a directory<br>
<br>
`/challenge/run`<br>
**pwn.college{oVUFjKe-o2pO5D81dPELTbEWNoy.dVDN1QDL1IjN0czW}}<br>**
<br>
## Position thy self
cd (change directory) command - navigate around directories<br>
<br>
`cd /usr/share/zoneinfo/posix/Asia`<br>
`/challenge/run`<br>
**pwn.college{MA_kjZgL5ywYpvohzGQSBTZXg_5.dZDN1QDL1IjN0czW}**<br>
<br>
## Position elsewhere
`cd /usr/share/build-essential`<br>
`/challenge/run`<br>
**pwn.college{QyrS7tPzc5US99Y1IWHiVUuFNGh.ddDN1QDL1IjN0czW}**<br>
<br>
## Position yet elsewhere
`cd /usr/share/zoneinfo/posix/Asia`<br>
`/challenge/run`<br>
**pwn.college{MK9t5xpM784liCxiO8KT9aVGLN3.dhDN1QDL1IjN0czW}**<br>
<br>
## implicit relative paths, from /
`cd /`<br>
`challenge/run`<br>
**pwn.college{ojNxLaI52-ha77yS5tmNwehM5yi.dlDN1QDL1IjN0czW}**<br>
<br>
## explicit relative paths, from /
`cd /` <br>
`./challenge/run` <br>
**pwn.college{ITbxDIAAu8m_lD3pdCuQKqHkyDl.dBTN1QDL1IjN0czW}**<br>
<br>
## implicit relative path
`cd /challenge` <br>
`./run` <br>
**pwn.college{U5kbEPUxipGPtZNaph1-MPCRsjm.dFTN1QDL1IjN0czW}**<br>
<br>
## home sweet home
`/challenge/run ~/a` <br>
**pwn.college{Yf2OoDTeG82W04HjlrR3iQLOlD3.dNzM4QDL1IjN0czW}**

