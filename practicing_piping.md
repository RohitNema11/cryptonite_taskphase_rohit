# Redirecting output
`hacker@dojo:~$ echo hi > asdf`<br>
The > character redirect the output of echo hi (which will be hi) to the file asdf. We can then use a program such as cat to output this file. <br>
<br>
pwn.college{spqCSoAlWVz-OS4Igc-JkTz-86R.dRjN1QDL1IjN0czW} <br>
<br>
# Redirecting more output
Aside from redirecting the output of echo, we can redirect the output of any command. <br>
<br>
![image](https://github.com/user-attachments/assets/cff2811c-d143-40ea-b1fb-9aa6705d8d40)<br>
<br>
# Appending output
>> charcter can be used to append all the outputs to the same file<br>
<br>
![image](https://github.com/user-attachments/assets/ecf8c61f-fe7a-427c-9045-6c7ee9d185c0)<br>
<br>
# Redirecting errors
2> will give standard error<br>
`hacker@dojo:~$ /challenge/run 2> errors.log` <br>
This will redirect standard error (FD 2) to the errors.log file <br>
<br>
<br>
![image](https://github.com/user-attachments/assets/75e417c6-9685-4b37-8a8f-c959a4965f23)<br>
<br>

# Redirecting input
We can redirect input to program using < character. <br>
<br>
![image](https://github.com/user-attachments/assets/5eb5f97c-9581-4bf1-86f5-b73ed32a946d)<br>
<br>
# Grepping stored results
![image](https://github.com/user-attachments/assets/22cb0fc5-7fa6-4189-bead-e11723022560)<br>
<br>

# Grepping live output
![image](https://github.com/user-attachments/assets/c5e7f640-8dc1-4431-a0c0-a9d223886d7e)<br>
<br>
# Grepping errors

# Duplicating piped data with tee
# Writing to multiple programs
# split piping stderr and stdout
