# Angry Professor
"Angry Professor" Quiz

A Discrete Mathematics professor has a class of students. Frustrated with their lack of discipline, the professor decides to cancel class if fewer than some number of students are present when class starts.<br>
Arrival times go from on time (![image](https://user-images.githubusercontent.com/33404432/120790379-16cb8880-c55d-11eb-85fb-9733ed152781.png))to arrived late (![image](https://user-images.githubusercontent.com/33404432/120790454-319dfd00-c55d-11eb-81ec-29578793df8e.png)).
<br>
Given the arrival time of each student and a threshhold number of attendees, determine if the class is cancelled.<br>
Example:<br>
![image](https://user-images.githubusercontent.com/33404432/120790577-572b0680-c55d-11eb-9e98-e6996d815426.png)<br>
The first 3 students arrived on. The last 2 were late. The threshold is 3 students, so class will go on. Return **YES**.<br>
Note: Non-positive arrival times (a[i] <= 0) indicate the student arrived early or on time; positive arrival times (a[i] >0) indicate the student arrived a[i] minutes late.<br>
Function Description<br>
Complete the angryProfessor function in the editor below. It must return YES if class is cancelled, or NO otherwise.<br>
angryProfessor has the following parameter(s):<br>
>>int k: the threshold number of students<br>
>>int a[n]: the arrival times of the  students<br>

**Returns**<br>
>>string: either YES or NO<br>

Input Format:<br>
The first line of input contains t, the number of test cases.<br>
Each test case consists of two lines.<br>
he first line has two space-separated integers, n and k, the number of students (size of k) and the cancellation threshold. 
The second line contains n space-separated integers (a[1],a[2],...,a[n]) that describe the arrival times for each student.<br>
Constraints:<br>
<br>Sample Input<br>
2<br>
4 3<br>
-1 -3 4 2<br>
4 2<br>
0 -1 2 1<br>
<br>Sample Output<br>
YES<br>
NO<br>
<br>Explanation:<br>
For the first test case, k=3. The professor wants at least 3 students in attendance, but only 2 have arrived on time (-3 and -1) so the class is cancelled.
<br>For the second test case, k=2. The professor wants at least 2 students in attendance, and there are 2 who arrived on time (0 and -1). The class is not cancelled.







