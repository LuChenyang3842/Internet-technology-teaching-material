# Internet-technology-teaching-material
- This repo will be updated weekly, normally on Monday or Tuesday
- If you find any error in the slides, please send an email to me to discuss, or you can write on issue section.
- Please email me in advance if you want to use these slides as teaching material, copy right reserved. 


## Tutor feedback <br>
https://apps.eng.unimelb.edu.au/casmas/index.php?r=qoct/feedback&subjCode=COMP90007



**------Update 5th Sep----------- <br>**
**There are some minor updates to workshop6 page7 and page13** <br>
The major change is in page7.<br>
There are two different parity methods --- even parity and odd parity. <br>
In the workshop, the approach we discussed to determine the parity is: For even parity, we XOR evey bits (including parity) together to be 0. For odd parity, we XOR evey bit(including parity) together to be 1.  <br> <br>
However, I realize this methods might not be easy for you to understand. So I provid anoher approach for you (which is also taught in lecture) to determine pariy: <br>

In the case of even parity, for a given set of bits, the occurrences of bits whose value is 1 is counted. If that count is odd, the parity bit value is set to 1, making the total count of occurrences of 1s in the whole set (including the parity bit) an even number. If the count of 1s in a given set of bits is already even, the parity bit's value is 0. <br>

In the case of odd parity, the coding is reversed. For a given set of bits, if the count of bits with a value of 1 is even, the parity bit value is set to 1 making the total count of 1s in the whole set (including the parity bit) an odd number. If the count of bits with a value of 1 is odd, the count is already odd so the parity bit's value is 0. <br>


<br>
<br>
<br>


------Update 28th August----------- <br>
I did some minor update to week5 at 11:50 AM 28th Aug, please download the newest version 



------Update 24th August----------- <br>
For next week's tutorial, we will be walking through Project 1 to get you acquainted with the tasks at hand by showing you a few demo's of how to run the needed commands and gather data.  <br>
I hope all of you can have a look of project1 documents before coming to my workshop.


------Update 17th August----------- <br>
Note: I have made an minor update to week2 and week3 workshop slides<br>
A more precise definition of TCP is provided:
1. TCP is one of the main protocols in TCP/IP networks
2. Establish Connection between two hosts.
3. Manages flow control and handles retransmission.
