# Assignment 6
You've been provided with an executable that connects to a server and adds whatever name you provide to the list of names with the student role. There is also a teacher role which the executable checks whenever it's given a name. The executable's only behavior under normal circumstances is to add the given name to the student list. Your job is to utilize Ghidra or another decompilation tool to inspect the executable and find a way to get the name you provided onto the list of names with the teacher role. 

## Submission
Your submission to canvas should be whatever name I should look for in the list of teachers, and a short description of the exploit and how you found it (max 300 words). Please make sure the string you submit to canvas and the string that gets stored in the teacher list match exactly. 

### Submission Note 
There's no minimum word count for your description but I'm looking for it to be sufficient for an unfamiliar reader to reproduce the exploit.

## Grade 
- 40% The name you submitted is stored in the Teachers list and the same name is submitted to Canvas
- 30% Your description of the exploit
- 30% Your notes on how you discovered the exploit

## Tips
- The executable prints out some addresses that might be useful.
- The "name" does not necessarily need to be your name, it can be any string as long as it's unique to you and properly submitted to canvas.
- When you provide a name the executable will tell you if it's already been added to the student or teacher roles.
- The executable was compiled with the following and should be executable on other linux distributions:
  - Processor: AMD Ryzen 9 3900X (24) @ 3.800GHz
  - OS: openSUSE Tumbleweed x86_64
  - Kernel: 6.11.6-2-default
- HTTPie could be useful if you cannot run it natively. 
