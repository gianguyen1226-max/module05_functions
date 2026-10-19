# debug_log.md
# Author: [Gia Nguyen]

## Bug 1

Error type: KeyError: 'amout'
File + line: week8_buggy.py, line 5
What the error means: Python is trying to find the key word of amount but is not able to due to the incorrect spelling of "amout".
What I told the duck: The functions starts at 0 but then loops around through each record. The first orginal line there is a spelling mistake.
What I tried: I ran the orginial code and saw that their was an error in the code and from there I realized that their was an issue.
How I fixed it: I added a n to the word amount.

## Bug 2

Error type: TypeError
File + line: week8_buggy.py, line 17
What the error means: Python is not able to process the integer 1000 with the '' around it and the '' are incorrect formating. 
How I fixed it: I got rid of the '' on the 1000

## After Fixing Both Bugs

Final output: Total: $5150.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes 
If yes -- exact prompt I used: "debug_log.md template"
What AI explained: AI assisted me in understanding the keyerror in line 5 to fix the code to make it running. 
What I changed myself: I identify the error in the error and was able to switch it and fix the spelling.
Can I explain every fixed line? Yes 

## What I learned
I learned that Python can nagivate problems within the code and even if it is a small issue in spelling. A simple issue in spelling can throw off the whole code from operating and running smoothly. 