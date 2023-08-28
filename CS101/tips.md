---
layout: page
title: CS101 Tips
---
<!-- **Table of Content**
* auto-gen TOC:
{:toc} -->
<!-- # Table of Content -->

<buttona class="accordion">How to write a program? (5Cs)</buttona>
<div class="panel">
	<p></p>
	<ul>
		<li> Carefully go through the problem statement</li>
		<li> Check your understanding of problem using solved examples and practice testcases</li>
		<li> Compose the programming approach on paper</li>
		<li> Consolidate your approach by verifying its correctness on testcases by doing <a href="#What is Dry Run?">dry runs</a></li>
		<li> Code it up (finally!)</li>
	</ul>

<h2 align="center" id="Good Programming Practices">Good Programming Practices</h2>
<ul>
	<li>Clearly writing documentation explaining what the program does, how to use it, what quantities it takes as input, and what quantities it returns as output.</li>
	<li>Using explanatory variable/function names and appropriate indentation.</li>
	<li>Extensive internal comments explaining how the program works.</li>
	<li>Complete error handling with informative error messages.</li>
</ul>

<h2 align="center" id="Debugging">Debugging</h2>

<span class="image main"><img src="https://i.stack.imgur.com/NFwZj.png" alt="programming cartoon" /></span>
<p>Pic Courtesy - <a href="https://stackoverflow.com/questions/84556/whats-your-favorite-programmer-cartoon/84624#84624">stackoverflow</a> </p>

<h3 align="center" id="What is Dry Run?">What is Dry Run?</h3>
The most important step in debugging
<ul>
	<li>Select a testcase</li>
	<ul>
		<li>Manually go through the code to trace the value of variables (or you can simply output these variable values using <code>cout</code>)</li>
		<li>Check if the values of variables matches with their expected values</li>
		<ul>
			<li>If they do not match for any variable at any time then your program is incorrect, consider debugging/rewriting it</li>
			<li>If they match for all variables at all times, Hurray your program is correct for the current testcases!</li>
		</ul>
	</ul>
	<li>Now repeat the procedure for a different testcase :)</li>
</ul>

<h3 align="center" id="How to Remove Errors?">How to Remove Errors?</h3>

<h4 align="center" id="Program does not compile">Program does not compile</h4>
<ul>
	<li>Get comfortable with common syntactical errors
		<ul>
			<li><a href="https://help.mimir.io/en/articles/2761300-cpp-common-compiler-errors-with-explanations">Common errors</a></li>
			<li><a href="https://www.geeksforgeeks.org/errors-in-cc/">Types of errors</a></li>
		</ul>
	</li>
	<li>Missing semicolons, curly braces, multiplication symbol (<code>ab</code> instead of <code>a*b</code>)</li>
	<li>variables out of scope</li>
</ul>

<h4 align="center" id="Program compiles but gives no output">Program compiles but gives no output</h4>
<ul>
	<li>Uninitialized variables</li>
	<li>Division by zero</li>
	<li>Infinite Loop?</li>
	<li>Accessing out-of-range indexes</li>
</ul>

<h4 align="center" id="Program compiles but gives wrong output">Program compiles but gives wrong output</h4>
<ul>
	<li>Integer overflow</li>
	<li>Logical error</li>
</ul>

<h4 align="center" id="Program passing testcases in PC but not on BodhiTree">Program passing testcases in PC but not on BodhiTree</h4>
<p>Your program has undefined behaviour. Below are some examples</p>
<ul>
	<li>pow (in older C++ versions)</li>
	<li>Uninitialized variables</li>
	<li>Accessing out-of-range indexes</li>
</ul>
<p>More examples <a href="https://en.cppreference.com/w/cpp/language/ub">here</a></p>
</div>
<p></p>
<buttona class="accordion">How to Practice?</buttona>
<div class="panel">
	<p></p>
	<p>Most important - CODE, CODE, CODE</p>
	<ul>
		<li>in-video, out-video quizzes (if recorded lectures are provided)</li>
		<li>slide program exercises</li>
		<li>previous week's lab optional problems</li>
		<li><a href="https://paramrathour.github.io/CS-101/Problems.pdf">practice problems</a></li>
		<li>book exercises</li>
		<li>Regularly go through previous labs solution, understand their approach, follow the good programming practices and <i>tricks</i> used</li>
	</ul>
</div>
<p></p>
<buttona class="accordion">Evaluation</buttona>
<div class="panel">
	<p></p>
<h2 align="center" id="SAFE Quizzes">SAFE Quizzes</h2>
<ul>
	<li><a href="https://cs101.has.coffee/safe-quiz-guidelines">SAFE Quiz Guidelines</a></li>
	<li>Notify the TA immediately for any issue you face during the quiz</li>
	<li>If submission is pending - keep retrying/restarting SAFE until it submits (NEVER LOGOUT during such issues)</li>
	<li>Set up environment properly, look only at mobile screen, show the successful submission screen to the TA</li>
</ul>

<h2 align="center" id="Labs">Labs</h2>
<h3 align="center" id="Submissions">Submissions</h3>
<ul>
	<li><a href="https://docs.google.com/document/d/17LY_k_xldGEYfx8ACW3jjFbVRqo2fAmku5Q0ReKeSnM/edit?usp=sharing">BodhiTree Usage Instructions</a></li>
	<li>Submit early, as soon as you can solve a problem</li>
	<li>Do not wait till the last minute to upload</li>
	<li>Expect that at the last moment</li>
	<ul>
		<li>Computers will crash</li>
		<li>Networks will stop working</li>
		<li>Power will fail</li>
		<li>BodhiTree will be slow</li>
		<li>Murphy's law - Anything that can go wrong will go wrong</li>
	</ul>
</ul>

Courtesy - Prof Parag Chaudhari

<h3 align="center" id="Plagiarism">Plagiarism</h3>
<ul>
	<li>Plagiarism is not just copying of the written word/code, it is of ideas and thoughts too</li>
	<li>When can a match happens between person 1 and 2</li>
	<ul>
		<li>1 shared their program and/or explained the code/ideas with 2</li>
		<li>1 and 2 got/copied the code/idea from 3 (internet or another person)</li>
	</ul>
</ul>
<!-- Discussion vs Cheating (My thoughts) -->

<h4 align="center" id="Punishments">Punishments</h4>
<ul>
	<li>Both one who copied and from whom it was copied are treated equally</li>
	<li>Very severe <a href="https://www.iitb.ac.in/newacadhome/academicMalpractices.jsp">punishments</a> (One Grade Down to Semester Repeat)</li>
</ul>
</div>
<p></p>
<buttona class="accordion">Resources</buttona>
<div class="panel">
	<p></p>
<h2 align="center" id="Reference Manuals">Reference Manuals</h2>
<ul>
	<li><a href="https://www.cse.iitb.ac.in/~ranade/book.html">An Introduction to Programming through C++ by Abhiram G. Ranade</a></li>
	<li><a href="https://www.cse.iitb.ac.in/~ranade/iticse16.pdf">Introductory Programming: Let Us Cut through the Clutter!</a></li>
	<li><a href="https://www.cse.iitb.ac.in/~ranade/simplecpp/">Simplecpp Webpage</a></li>
	<li><a href="https://www.cse.iitb.ac.in/~cs101/2014.2/Project/Manual_Code::Blocks_Simplecpp.pdf">Code::Blocks and Simplecpp</a></li>
	<li><a href="https://www.cse.iitb.ac.in/~ranade/simplecpp/gallery.html">Simplecpp Gallery</a></li>
</ul>

<h2 align="center" id="Article/Blogs">Article/Blogs</h2>
<ul>
	<li><a href="https://en.cppreference.com/">C++ Documentation</a></li>
	<li><a href="http://learncpp.com/">Learn C++</a></li>
	<li><a href="http://geeksforgeeks.org/">GeeksforGeeks</a></li>
	<li><a href="https://cp-algorithms.com/">Competitive Programming Algorithms</a></li>
</ul>

<h2 align="center" id="Video Tutorials">Video Tutorials</h2>
<ul>
	<li><a href="https://youtube.com/playlist?list=PLOzRYVm0a65eklyMDXGSWObRA-7lCdkSm">An Introduction to Programming through C++ by Abhiram G. Ranade</a></li>
	<li><a href="https://youtube.com/playlist?list=PLfqMhTWNBTe0b2nM6JHVCnAkhQRGiZMSJ">C++ Full Course by Apna College</a></li>
	<li><a href="https://www.youtube.com/playlist?list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb">C++ by The Cherno</a>, Courtesy - Tirthankar Mazumder</li>
</ul>

<h2 align="center" id="Practice Programming Online">Practice Programming Online</h2>
<ul>
	<li><a href="https://cses.fi/problemset/">CSES Problem Set</a></li>
	<li><a href="https://www.spoj.com/">SPOJ</a></li>
	<li><a href="https://www.hackerrank.com/dashboard">HackerRank</a></li>
	<li><a href="https://www.codechef.com/">CodeChef</a></li>
	<li><a href="https://codeforces.com/">Codeforces</a></li>
	<li><a href="https://projecteuler.net/">Project Euler</a></li>
	<li><a href="https://atcoder.jp/">AtCoder</a></li>
	<li><a href="http://www.usaco.org/">USACO</a></li>
</ul>
</div>
<p></p>
<buttona class="accordion">Fun</buttona>
<div class="panel">
	<p></p>
<h2 align="center" id="Interesting Books">Interesting Books</h2>
<span class="image main"><img src="https://raw.githubusercontent.com/paramrathour/website-assets/master/computer-science-for-fun.png" alt="Interesting CS Books" /></span>
<ul>
	<li>A Brief History Of Computing by Gerard O'Regan</li>
	<li>Code The Hidden Language of Computer Hardware and Software by Charles Petzold</li>
	<li>Hackers Delight (2nd Edition) by Henry S. Warren</li>
	<li>Nine Algorithms That Changed The Future - The Ingenious Ideas That Drive Today's Computers by John MacCormick</li>
	<li>Algorithmic adventures from knowledge to magic by Juraj Hromkovic</li>
	<li>Guide to Competitive Programming Learning and Improving Algorithms Through Contests by Antti Laaksonen</li>
	<li>The Code Book How to Make It, Break It, Hack It, Crack It by Simon Singh</li>
</ul>
<!-- + Computer Science The Hardware, Software and Heart of It by Blum -->

<h2 align="center" id="YouTube Channels">YouTube Channels</h2>
<ul>
	<li><a href="https://www.youtube.com/c/Reducible">Reducible</a></li>
	<li><a href="https://www.youtube.com/channel/UC9-y-6csu5WGm29I7JiwpnA">Computerphile</a></li>
	<li><a href="https://www.youtube.com/c/TheCodingTrain">The Coding Train</a></li>
	<li><a href="https://www.youtube.com/channel/UCD8yeTczadqdARzQUp29PJw">WilliamFiset</a></li>
	<li><a href="https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw">3Blue1Brown</a></li>
	<li><a href="https://www.youtube.com/channel/UC1_uAIS3r8Vu6JjXWvastJg">Mathologer</a></li>
	<li><a href="https://www.youtube.com/user/standupmaths">Stand-up Maths</a></li>
	<li><a href="https://www.youtube.com/c/tomscottgo">Tom Scott</a></li>
</ul>

<h2 align="center" id="YouTube Videos">YouTube Videos</h2>
For more such videos check out "Fun Video" section of my <a href="https://paramrathour.github.io/CS-101/Problems.pdf">practice problems</a>. I have mentioned select videos here.
<ul>
	<li><a href="https://youtu.be/PZRI1IfStY0">Floating Point numbers -- Computerphile</a></li>
	<li><a href="https://youtu.be/0poh3w_Vm_A">Tetration: The operation you were (probably) never taught -- Taylor Series</a></li>
	<li><a href="https://youtu.be/7eboFOkRHr4">7 Factorials You Probably Didn't Know -- blackpenredpen</a></li>
	<li><a href="https://youtu.be/leFep9yt3JY">Ramanujan's infinite root and its crazy cousins -- Mathologer</a></li>
	<li><a href="https://youtu.be/Ks1pw1X22y4">Random Numbers with LFSR (Linear Feedback Shift Register) -- Computerphile</a></li>
	<li><a href="https://youtu.be/pQs_wx8eoQ8">Why computers are bad at algebra -- PBS Infinite Series</a></li>
	<li><a href="https://youtu.be/2SUvWfNJSsM">Binary, Hanoi and Sierpinski, part 1  -- 3Blue1Brown</a></li>
	<li><a href="https://youtu.be/bdMfjfT0lKk">Binary, Hanoi and Sierpinski, part 2  -- 3Blue1Brown</a></li>
	<li><a href="https://youtu.be/3s7h2MHQtxc">Hilbert's Curve: Is infinite math useful? -- 3Blue1Brown</a></li>
	<li><a href="https://youtu.be/rf6uf3jNjbo">Towers of Hanoi: A Complete Recursive Visualization -- Reducible</a></li>
	<li><a href="https://youtu.be/ngCos392W4w">5 Simple Steps for Solving Any Recursive Problem -- Reducible</a></li>
	<li><a href="https://youtu.be/b-Fa6HtvGtQ">Recursive PowerPoint Presentations [Gone Fractal!] -- Stand-up Maths</a></li>
	<li><a href="https://youtu.be/i7sm9dzFtEI">The Most Difficult Program to Compute? -- Computerphile</a></li>
	<li><a href="https://youtu.be/sPFWfAxIiwg">11.11.11 -- Numberphile</a></li>
	<li><a href="https://youtu.be/z2x3SSBVGJU">The Doomsday Algorithm -- Numberphile</a></li>
	<li><a href="https://youtu.be/cbGB__V8MNk">Square & Multiply Algorithm -- Computerphile</a></li>
	<li><a href="https://youtu.be/uCsD3ZGzMgE">The Josephus Problem -- Numberphile</a></li>
	<li><a href="https://youtu.be/gMlf1ELvRzc">The Discovery That Transformed Pi -- Veritasium</a></li>
	<li><a href="https://youtu.be/J0I1NuxUcpQ">What You Don't Know About Pascal's Triangle -- Tipping Point Math</a></li>
	<li><a href="https://youtu.be/xNx3JxRhnZE">Dungeon Numbers -- Numberphile</a></li>
	<li><a href="https://youtu.be/FGC5TdIiT9U">The Slightly Spooky Recam´an Sequence -- Numberphile</a></li>
	<li><a href="https://youtu.be/prh72BLNjIk">The Fairest Sharing Sequence Ever -- Stand-up Maths</a></li>
	<li><a href="https://youtu.be/Dgcoa2yAUfw">The Harmonic Series -- Tipping Point Math</a></li>
	<li><a href="https://youtu.be/ea7lJkEhytA">Look-and-Say Numbers (feat John Conway) -- Numberphile</a></li>
	<li><a href="https://youtu.be/iJ8pnCO0nTY">The hardest What comes next (Euler's pentagonal formula) -- Mathologer</a></li>
	<li><a href="https://youtu.be/0hlvhQZIOQw">Funny Fractions and Ford Circles -- Numberphile</a></li>
	<li><a href="https://youtu.be/uWwUpEY4c8o">Kill the Mathematical Hydra -- PBS Infinite Series</a></li>
	<li><a href="https://youtu.be/oBOZ2WroiVY">How Infinity Explains the Finite -- PBS Infinite Series</a></li>
</ul>
</div>
<p></p>
<buttona class="accordion">What after CS101?</buttona>
<div class="panel">
	<p></p>
You are free to choose your route, but in case you did not know, here are somethings that can be done

<h2 align="center" id="IITB">IITB</h2>
<ul>
	<li>ITSP, <a href="https://wncc-iitb.org/soc/">SoC</a>, SURP, projects under professors, self project</li>
	<li>CS/DS Minor, IDDDP (Interdisciplinary Dual Degree Programme) (for non-CS students) - Need to do 5 CSE courses to get a minor degree</li>
	<li>Additional CSE Courses as Electives and CDEEP (often, other departments too offer courses intersecting with CSE)</li>
	<li>Web and Coding Club, DevCom for enthusiasts</li>
	<li>Technical Teams too have software subsystems with diverse fields</li>
	<li>Web Secretary position for various departments, technical teams, clubs and many more</li>
</ul>

<h2 align="center" id="Non-IITB">Non-IITB</h2>
<ul>
	<li>Introductory Courses available on Coursera, Edx, MIT, Stanford... Some recommendations below</li>
	<ul>
		<li>DSA</li>
		<ul>
			<li><a href="https://www.coursera.org/learn/algorithmic-toolbox">Algorithmic Toolbox - Coursera</a></li>
			<li><a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/">Introduction to Algorithms - MIT OpenCourseWare 6.006</a></li>
			<li><a href="https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/">Design and Analysis of Algorithms - MIT OpenCourseWare 6.046</a></li>
		</ul>
	</ul>
	<ul>
		<li>AI/ML</li>
		<ul>
			<li><a href="https://www.coursera.org/learn/machine-learning">Machine Learning</a>, <a href="https://www.coursera.org/specializations/deep-learning">Deep Learning</a> - Coursera</li>
			<li><a href="http://cs229.stanford.edu/">CS229: Machine Learning</a></li>
			<li><a href="http://cs230.stanford.edu/">CS230: Deep Learning</a></li>
		</ul>
	</ul>
	<li><a href="https://stackoverflow.blog/2020/08/03/getting-started-with-contributing-to-open-source/">Open Source</a></li>
	<li><a href="https://summerofcode.withgoogle.com/">Google Summer of Code</a></li>
</ul>	
</div>
<p></p>
<p><a href="https://www.flagcounter.me/details/dby"><img class="inversion" src="https://www.flagcounter.me/dby/" alt="Flag Counter"></a></p>