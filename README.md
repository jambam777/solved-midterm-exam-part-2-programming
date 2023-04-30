Download Link: https://assignmentchef.com/product/solved-midterm-exam-part-2-programming
<br>
<h2><a id="user-content-timing-and-general-instructions" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm#timing-and-general-instructions" aria-hidden="true"></a>Timing and general instructions</h2>

You have <strong>1 hour</strong> to complete the programming part of the midterm exam. This is a closed notes exam so you should not open any website other than the Titanium midterm exam page. Do not communicate with your classmates or look at their screens. Direct all your questions to the instructor or lab assistant only.

You are allowed to view your own study guide and use paper for scratch work that will be provided for you.

You are free to use any editor and the command line on Tuffix to write, compile, and test your program. The instructors will use <code>clang++</code> to check your programs so make sure your code works with it.

You are expected to have used the programming environment during our lab sessions so instructors and lab assistants will not answer questions regarding interpretting syntax errors or debugging code.

<h2><a id="user-content-problem-and-points" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm#problem-and-points" aria-hidden="true"></a>Problem and points</h2>

There are three programming problems that you need to complete.

<ol>

 <li>Discounted sum (<em>5 points</em>)</li>

 <li>Radio (<em>5 points</em>)</li>

 <li>Student info (<em>5 points</em>)</li>

</ol>

<h1><a id="user-content-submission" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm#submission" aria-hidden="true"></a>Submission</h1>

Your answers will be submitted through GitHub. You can push your code as many times as you want before the end of the midterm exam. We will check the last version that you pushed.

When you are done, verify you have pushed your code properly on GitHub. Simply refresh your GitHub repo and click on the individual files to see if they have been changed.

On Titanium, click on the <code>Add submission</code> button in the midterms page. Provide the URL for your GitHub repo containing the midterm exam and click on <code>Save changes</code>. Finally click on <code>Submit assignment</code>.

Before leaving the room, please approach the instructor who will verify that you submitted your exam properly. Also turn in your scratch paper and study guide to the instructor.




<h1>Discounted prices</h1>

Create a function called <em>discounted_sum</em>. This function receives two parameters, an array that contains item prices, and the total number of items inside that array.

The function will go through each price in the array and compute the total price. However, whenever a price is over $50.00, that price will get a 5% discount. Take note, it is only that item that gets the discount, not the total amount.

The function should return the total price.

You need to create the function prototype in <code>discount.hpp</code> and the function implementation in <code>discount.cpp</code>. Modify the <em>main</em> function inside <code>main.cpp</code> to call your function. More detailed instructions are found inside <code>main.cpp</code>.

<em>Even though the main function uses an array of five elements, your discounted_sum function should be able to handle any number of elements.</em>

<h1><a id="user-content-code-evaluation" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm/prob01#code-evaluation" aria-hidden="true"></a>Code evaluation</h1>

Open the terminal and navigate to the folder that contains this problem. Assuming you have pulled the code inside of <code>/home/student/midterm</code> and you are currently in <code>/home/student</code> you can issue the following commands

<pre><code>cd midterm</code></pre>

You also need to navigate into the problem you want to answer. To access the files needed to answer problem 1, for example, you need to issue the following command.

<pre><code>cd prob01</code></pre>

When you want to answer another problem, you need to go back up to the parent folder and navigate into the next problem. Assuming you are currently in <code>prob01</code>, you can issue the following commands to go to the parent folder then go into another problem you want to answer; <code>prob02</code> for example.

<pre><code>cd ..cd prob02</code></pre>

Use the <code>clang++</code> command to compile your code and the <code>./</code> command to run it. The sample code below shows how you would compile code save in <code>discount.cpp</code> and <code>main.cpp</code>, and into the executable file <code>main</code>. Make sure you use the correct filenames required in this problem. Take note that if you make any changes to your code, you will need to compile it first before you see changes when running it.

<h6><code>clang++ -std=c++17 main.cpp discount.cpp -o main</code></h6>

./main

<h6><code></code></h6>




<h1>Radio</h1>

Create a class called <code>Radio</code>. It has three data members.

<ul>

 <li><em>volume</em>: indicates how loud the radio is (for example, 1 is lowest and 10 is highest)</li>

 <li><em>station</em>: refers to a radio station (for example, 103.5)</li>

 <li><em>is_on</em>: which refers to whether the radio is on or off</li>

</ul>

Create accessors and mutators for all the data members.

In the <em>main</em> function, create a <code>Radio</code> object, change its volume to 3, change its station to 98.3, and turn the radio on. Use the object’s accessors to display information about the radio on the screen. More detailed instructions are found inside <code>main.cpp</code>.

You need to create the <code>Radio</code> class inside <code>radio.hpp</code> and modify the <em>main</em> function inside <code>main.cpp</code>. You do not need to create other files aside from these two.

<h1><a id="user-content-code-evaluation" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm/prob02#code-evaluation" aria-hidden="true"></a>Code evaluation</h1>

Open the terminal and navigate to the folder that contains this problem. Assuming you have pulled the code inside of <code>/home/student/midterm</code> and you are currently in <code>/home/student</code> you can issue the following commands

<pre><code>cd midterm</code></pre>

You also need to navigate into the problem you want to answer. To access the files needed to answer problem 2, for example, you need to issue the following command.

<pre><code>cd prob02</code></pre>

When you want to answer another problem, you need to go back up to the parent folder and navigate into the next problem. Assuming you are currently in <code>prob02</code>, you can issue the following commands to go to the parent folder then go into another problem you want to answer; <code>prob03</code> for example.

<pre><code>cd ..cd prob03</code></pre>

Use the <code>clang++</code> command to compile your code and the <code>./</code> command to run it. The sample code below shows how you would compile code saved in <code>main.cpp</code>, and into the executable file <code>main</code>. Make sure you use the correct filenames required in this problem. Take note that if you make any changes to your code, you will need to compile it first before you see changes when running it.

<h6><code>clang++ -std=c++17 main.cpp -o main</code></h6>

./main

<h6><code></code></h6>

<h1>Student Info</h1>

The program in <code>main.cpp</code> should read the data inside <code>students.txt</code> and display it on screen. However, the programmer who built the code suddenly had to leave and it is up to you to complete their program. Find and fix the errors in <code>main.cpp</code>.

Take note of how the data is organized inside <code>students.txt</code>. It will always contain a name followed by a CWID. The name can contain an arbitrary number of strings. We will not know before-hand the number of students in the file, so your program should handle files with any number of students.

After making your modifications, the output should match the following format exactly, including spaces and newlines:

<pre><code>Name: John DoeCWID: 8194487Name: Jane SmithCWID: 8173258Name: Edith Summers LeeCWID: 8165834</code></pre>

You only need to modify <code>main.cpp</code>.

<h1><a id="user-content-code-evaluation" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/copy/Exams/Midterm/prob03#code-evaluation" aria-hidden="true"></a>Code evaluation</h1>

Open the terminal and navigate to the folder that contains this problem. Assuming you have pulled the code inside of <code>/home/student/midterm</code> and you are currently in <code>/home/student</code> you can issue the following commands

<pre><code>cd midterm</code></pre>

You also need to navigate into the problem you want to answer. To access the files needed to answer problem 3, for example, you need to issue the following command.

<pre><code>cd prob03</code></pre>

When you want to answer another problem, you need to go back up to the parent folder and navigate into the next problem. Assuming you are currently in <code>prob03</code>, you can issue the following commands to go to the parent folder then go into another problem you want to answer; <code>prob01</code> for example.

<pre><code>cd ..cd prob01</code></pre>

Use the <code>clang++</code> command to compile your code and the <code>./</code> command to run it. The sample code below shows how you would compile code saved in<code>main.cpp</code>, and into the executable file <code>main</code>. Make sure you use the correct filenames required in this problem. Take note that if you make any changes to your code, you will need to compile it first before you see changes when running it.

<pre><code>clang++ -std=c++17 main.cpp -o main./main</code></pre>


