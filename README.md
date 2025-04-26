# ceg-4350-operating-systems-project-assignment-designing-and-implementing-a-cpu-scheduling-simulator
**TO GET THIS SOLUTION VISIT:** [CEG 4350 Operating Systems Project Assignment Designing and Implementing a CPU Scheduling Simulator ](https://www.ankitcodinghub.com/product/ceg-4350-operating-systems-project-assignment-designing-and-implementing-a-cpu-scheduling-simulator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;10985&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CEG 4350 Operating Systems Project Assignment  Designing and Implementing a CPU Scheduling Simulator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong><u>Objectives:</u></strong> The purpose of this project is to give you a chance to implement/simulate a few typical CPU scheduling policies discussed in the class. You will write a C/C++ program to implement a simulator with different scheduling algorithms, i.e., the simulator selects a task to run from ready queue(s) based on the scheduling algorithm selected. Since the project intends to simulate a CPU scheduler, so it does not require any actual process creation or execution. When a task is scheduled, the simulator will simply print out what task is selected to run at a time. It outputs the way similar to Gantt chart style.

<strong><u>Process States:</u></strong> In this CPU scheduling simulation, there are 3 possible states for a process:

<ul>
<li>READY – The process is ready to execute, and is waiting to be scheduled on a CPU.</li>
<li>RUNNING – The process is currently executing on a CPU.  TERMINATED – The process has completed.</li>
</ul>
&nbsp;

<strong><u><img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/07/344.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw=="></u></strong>

<strong><u>Scheduling Algorithms:</u></strong> For your simulator, you will implement the following three CPU scheduling algorithms:

<ul>
<li><em>First-Come, First Served (FCFS)</em> – Runnable processes are kept in a first-in, first-out ready queue. FCFS is non-preemptive; once a process begins running on a CPU, it will continue running until it either completes or blocks for I/O.</li>
<li><em>Round-Robin</em> – Each process is assigned a timeslice when it is scheduled. At the end of the timeslice, if the process is still running, the process is preempted, and moved to the tail of the ready queue. Use timeslice (i.e., quantum) = 8 ms.</li>
<li><em>Multi-Level Feedback Queue</em> scheduling algorithm:
<ul>
<li>A new process first enters Queue 0 which is served in RR. When it gains CPU, process receives 8 ms. If it does not finish in 8 ms, process is preempted and moved to Queue 1.</li>
<li>At Queue 1, process is again served in RR and receives 16 additional ms. If it still does not complete, it is preempted and moved to Queue 2.</li>
<li>At Queue 2, process is served in FCFS.</li>
<li>When a running process is preempted by a new process arriving at a higher priority queue, it will be put back to the end of its current queue. i.e., its priority keeps the same. A new full quantum will be given to it the next time it starts running.</li>
</ul>
</li>
</ul>
<strong><u>&nbsp;Input (Process Information) </u></strong><u>:</u> The process information will be read from an input file. The format is <em>pid arrival_time burst_time</em> . All of fields are integer type where <em>pid</em> is a unique numeric process ID, <em>arrival_time</em> is the time when the task arrives in the unit of milliseconds, and <em>burst_time</em> the is the CPU time requested by a task, in the unit of milliseconds The time unit for <em>arrival_time, burst_time</em> is millisecond.

Command-line Usage Examples:

myCPUScheduler input_file [FCFS|RR|MLFQ]

Input file example:

% more input.txt

PID&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ArrivalBurst

<ul>
<li>0 10</li>
<li>1 9</li>
<li>2 8</li>
<li>3 7</li>
</ul>
<strong><u>Output:</u></strong>

<ol>
<li>When a task is scheduled, the simulator will simply print out what task is selected to run at a time. Show the status of related process at each scheduling event, e.g.,: <em>starts running, has finished, is preempted into Queue #, or continues running</em>.</li>
<li>Print statistical information. As soon as all tasks are completed, the program should compute and print 1) average waiting time, 2) average response time, 3) average turnaround time.</li>
</ol>
<em>Example:</em>

%myCPUScheduler input_file FCFS

Selected Scheduling algorithm: FCFS

<table width="275">
<tbody>
<tr>
<td width="48">PID</td>
<td width="144">starts running</td>
<td width="48">at</td>
<td width="35">TIME</td>
</tr>
<tr>
<td width="48">PID</td>
<td width="144">has finished at</td>
<td width="48">TIME</td>
<td width="35"></td>
</tr>
<tr>
<td width="48">PID</td>
<td width="144">starts running</td>
<td width="48">at</td>
<td width="35">TIME</td>
</tr>
<tr>
<td width="48">PID

…
</td>
<td width="144">has finished at</td>
<td width="48">TIME</td>
<td width="35"></td>
</tr>
</tbody>
</table>
=============================

Average waiting time: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 10.00 ms

Average response time: 3.00 ms

Average turnaround time: 13.00 ms

===============================

<strong><u>What to submit in Pilot Dropbox:</u></strong>

<ol>
<li>The project in one ZIP file, including a readme file and a make file.</li>
<li>Copy all your source codes into a single text document and submitted for plagiarism check.</li>
<li>A project report on your design and implementation, problems unsolved if any, and etc. Typically, 2 pages.</li>
</ol>
