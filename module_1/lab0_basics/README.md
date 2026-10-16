### Homework evidence table
| Deployment | Public IPv4 address | Connection method   | Screenshot                                | Instance terminated? |
| ---------- | ------------------- | ------------------- | ----------------------------------------- | -------------------- |
| 1          | `54.226.235.176`    | EC2 Connect / (SSH) | ![[Pasted image 20261015202615.png\|177]] | (Yes) / No           |
| 2          | `54.88.209.224`     | (EC2 Connect) / SSH | ![[Pasted image 20261015204033.png]]      | (Yes) / No           |
| 3          | `54.196.250.252`    | EC2 Connect / (SSH) | ![[Pasted image 20261015205853.png]]      | (Yes) / No           |




#### Instance 1
Instance ID:  i-04b146cf2582047fe
Instance Type:  t3.micro

For this instance, I started by making the launch template. I'm not sure if we went over it in class so I just asked ChatGpt to explain it. Once I made the template, everything else was very straightforward. Since i added the script to the template, I did not have to do much other than giving the new instance a unique name. Once the instance was made, I connected to it via SSH. I had to once again look to see what that was and learned that Git Bash is an SSH. I got an error trying to run the first command so I had to navigate to my downloads folder and retry it. It had me change the mode of the key pair file and then run the other command which allowed me to see what was in the EC2.  From there I was able to see everything and take my screenshots.


#### Instance 2
Instance ID: i-073f05442e485370b
Instance Type: t3.micro

This second instance was much smoother thanks to the template being set up previously. This time the instance is taking a bit longer to be ready. My process so far is to go to the launch instance from template tab, then confirm that its the correct template, and then click the "launch instance" button. From there I end up on a screen that pretty much breaks down the specification of the EC2 and I can collect  the information necessary for the homework. I then click the connect button. For this instance I am using EC2 Connect.


#### Instance 3
Instance ID:  i-013f2585096fce0b6
Instance Type: t3.micro

Now that the process is becoming monotonous, when creating the instance,  I am only checking the summary of the template before launching the instance. It has become much faster to get through this now that I know what to look for and what steps I can ignore. The autofill function is quite convenient. I'm pausing before I click onto the instance ID because I know it won't be ready immediately. In the meantime I made my file structure for the Git repo. Back on the instance, the status and the steps indicate that I can now connect. I'm doing the SSH method once again. On the technical side, the CPU information is telling me how much of the processing power of  the instance is being used. Memory is about how much RAM being used. The Disk usage refers to the amount of space that's being occupied and the Uptime refers to how long the instance had been running since it first booted.