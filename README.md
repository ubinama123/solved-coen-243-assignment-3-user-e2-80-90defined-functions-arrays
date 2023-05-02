Download Link: https://assignmentchef.com/product/solved-coen-243-assignment-3-user%e2%80%90defined-functions-arrays
<br>



<strong>Type:               </strong>Group Assignment

(maximum number of group members is

2 people)

<strong>Weight:            </strong>5%

<strong> </strong><strong>Exercises: </strong>

<strong> </strong>

<strong>Q1. (25 marks) </strong>Write a C++ program that uses an array to store the grades of N students (N is entered by the user), and outputs the information below. Your program should be structured using functions. Each functionality should be implemented in a separate function.

<ol>

 <li>Maximum grade</li>

 <li>Minimum grade</li>

 <li>Average grade</li>

 <li>Median grade</li>

 <li>Number of A grades (grades more than 80)</li>

 <li>Number of B grades (grades between 70 and 80)</li>

 <li>Number of C grades (grades between 55 and 70)</li>

 <li>Number of D grades (grades between 40 and 55)</li>

 <li>Number of F grades (grades less than 40)</li>

</ol>




<strong>Q2. (25 marks) </strong>Write a user-defined function that takes an integer number and outputs the reverse of that number. Call the function twice in the main function and test your program with two 3-digits and 4-digits numbers.

<strong> </strong>

<strong>Example of output:  </strong>

<strong>Type an integer number: </strong>345

<strong>Output: </strong>543

<strong> </strong>

<strong>Type an integer number: </strong>3097

<strong>Output: </strong>7903

<strong> </strong>




<strong>Q3. (50 marks) </strong>We want to create a program that controls the movements of a robot in an array of size Initially, the robot is at position 0. The controller supports the following commands:

‐    right (n): the robot moves n cells right

‐    left (n): the object moves n cells left

‐    reboot: the object comes back to cell 0

1 COEN 243 – Winter 2021

Consider the following example:




<table width="356">

 <tbody>

  <tr>

   <td width="36">^</td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

  </tr>

 </tbody>

</table>

0       1       2       3       4       5       6       7       8       9




The new array after executing the command right(5) will look like this:




<table width="356">

 <tbody>

  <tr>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36">^</td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

  </tr>

 </tbody>

</table>

0       1       2       3       4       5       6       7       8       9




The new array after executing the command left(3) will look like this:




<table width="356">

 <tbody>

  <tr>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36">^</td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

   <td width="36"></td>

  </tr>

 </tbody>

</table>

0       1       2       3       4       5       6       7       8       9







The program takes commands from a user as shown in the following example:




Controller Menu:

<ol>

 <li>Right</li>

 <li>Left</li>

 <li>Display</li>

 <li>Reboot</li>

 <li>Show Array</li>

 <li>Exit</li>

</ol>




Command “Display” display the position of the robot in the array. Command “Show Grid” displays the array. Command “Exit” terminates the program.

‐ Implement the controller’s commands using functions. Add the necessarily checks to ensure that the robot does not go out of bounds. Your program should be structured using functions. For example, each command should be implemented in a separate function. (30 marks)

‐   We want to add the following commands (20 marks):

<ul>

 <li>cancel (n): The program cancels the last n operations and returns the robot to the initial position</li>

 <li>replay (n): The program replays the last n operations that have been cancelled.</li>

</ul>

2