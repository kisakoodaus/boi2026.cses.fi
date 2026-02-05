+++
title = "Rules"
weight = 11
draft = true
+++

TODO: NOT READY YET

### Participation

The Baltic Olympiad in Informatics 2026 (BOI 2026) is an individual contest between participants from ten member countries (Denmark, Estonia, Finland, Germany, Iceland, Latvia, Lithuania, Norway, Poland, Sweden) and one guest country (Ukraine).

Each country can send up to six contestants. All contestants must be eligible to compete in IOI 2026 to participate in BOI 2026.

### Contest schedule

The contest days of BOI 2026 are Thursday, April 16, and Friday, April 17. On each contest day, contestants will have five hours to complete three tasks.

There will be a practice session on Wednesday, April 15, where the contestants can familiarise themselves with the contest environment. Solutions submitted during the practice session will not be considered in the final ranking.

### Environment and supplies

Each contestant will have a desk with a workstation, including a screen, keyboard, and mouse. The software environment will be the same on all workstations.

Contestants may bring their own stationery (pens, pencils, erasers, etc.). Paper will be available in the contest room. It is not allowed to bring paper.

Each contestant may bring one wired non-programmable USB keyboard and/or one wired non-programmable USB mouse to use instead of the keyboard and mouse provided by the organizers. Contestant keyboard and mouse should be presented to the Technical Committee during the practice session and accepted by a committee member.

Each contestant may bring one printed, non-annotated natural language dictionary. Contestants may bring small mascots such as stuffed toy animals.

Drinks and snacks will be provided during the contest.

Contestants are not allowed to bring any additional reference materials such as books, program listings or notes. Contestants may not bring any electronic devices (phones, smart watches, etc.).

Contestants who want to bring any other items must contact the Jury through their team leaders before the event or during the practice session.
Any items to be used during the contest must be brought to the contest room during the practice session. These items will be checked and provided to the contestant during the contest sessions.
After the practice session and after the first contest day, contestant must leave these items on their table if they want to use them during the contest next day. After the second contest day, contestant must take all of these items with them.

### Tasks and solutions

The contest tasks at BOI 2026 are algorithmic programming tasks. The focus is on designing and implementing correct and efficient algorithms. Each task is divided into one or more subtasks, each worth a portion of the total points.

Unless stated otherwise in the task description, the solution to a task is a program written in C++ or Python in one source code file. Solutions must be submitted via the contest system.

Each submitted source code file must not exceed 128 kB, and the evaluation server must be able to compile it in less than 10 seconds using at most 512 MB of memory. The compiled file size must not exceed 2 MB.

Solutions must run within the time and memory limits, which are specified for each task separately. Limits are applied to individual test runs. Using multiple threads is not allowed.

The Jury guarantees that there are C++ solutions which fit within the specified memory and time limits. Unless otherwise stated in the task description, solutions are required to read data from standard input and write to standard output.

### Starting the contest

When contestants enter the contest room at the beginning of the contest, their workstations are running. Contest task descriptions are provided digitally via the contest system.

TODO: printed task statements?

<!--
and in print inside the same envelope. Contestants are not allowed to open the envelopes or touch anything on the workstations until the start signal is given.
-->

The task descriptions are presented in English and the native language of the contestant if such a translation has been prepared by a team leader. In case of any discrepancies, the English text is binding and official.

### Assistance and requests

During the contest, communication is allowed only with room supervisors and the Jury.

Contestants may ask a room supervisor for help at any time. Supervisors will assist with hardware problems, help to find toilets, and similar issues. However, the supervisors will not answer questions about the contest tasks.

Contestants should submit questions about the contest tasks through the contest system. Questions can be written in English or in the contestant's native language. If a question is written in a native language, the team leader will be asked to translate it into English.

A question about a task should be phrased so that a yes/no answer is possible. The Jury will answer every question submitted by the contestants. The answer will be one of the following:

- "YES"
- "NO"
- "NO COMMENT" – The contestant is asking for information that the Jury cannot give or the task description contains enough information.
- "INVALID QUESTION" – The question is not phrased so that a yes/no answer is meaningful. The contestant is encouraged to rephrase the question.

The Jury may give announcements related to tasks or the competition via the contest system.

### Submissions and grading

The contestants submit their solutions via the contest system. After the solution has been graded, the contestant can view the score achieved by the submission and additional feedback if available.

TODO: maximum number of submissions?

Each submission will be graded on several test cases. Each test case will have one of the following outcomes:

- ACCEPTED: your program produced the correct answer
- WRONG ANSWER: your program produced an incorrect answer
- TIME LIMIT EXCEEDED: your program used too much time
- RUNTIME ERROR: an error occurred in the execution of your program, or it used too much memory
- OUTPUT LIMIT EXCEEDED: your program printed too much text

Test cases are grouped into subtasks, each worth some points. The contestant is shown a single outcome for each subtask. If the outcome of each test case is ACCEPTED, the outcome of the subtask is ACCEPTED. Otherwise the outcome of the subtask is the outcome of the first test case that is not ACCEPTED.

A subtask is solved if every test in it is solved correctly and within time and memory limits. A submission will receive points for all subtasks that it solves.

The final score for a subtask is the maximum of the scores for that subtask over all submissions. The final score for a task is the sum of the final scores for its subtasks.

The contestants can see their final score for each task in the contest system. However, there is a small chance that the score will change later due to appeals: submissions may be re-graded, and the final score will be that yielded by the last grading.

Grading procedures for a task can be overridden in the task description.

### Ending the contest

After the end of the contest, no further submissions will be included in a contestant's score.

In case of a technical failure, a contestant or a group of contestants will be granted additional time corresponding to the time that was needed to address the failure.

### Cheating

Any of the actions outlined below are considered illegal during contest sessions:

- Using any printed materials, except for official BOI 2026 materials and unannotated natural language dictionaries that were brought to the practice session and approved for use in contest sessions.
- Using any electronic devices or data carriers, except for official BOI 2026 equipment and keyboards and mice that were brought to the practice session and approved for use in contest sessions.
- Communicating in any form with other contestants or with people other than BOI 2026 staff.
- Using a workstation or an account assigned to someone else.
- Tampering with or compromising the contest system.
- Attempting to gain access to the hidden test data used for grading solutions.
- Attempting to escalate privileges on the workstation.
- Attempting to access any machine other than their own or the contest system.
- Attempting to reboot or alter the boot sequence of any workstation.
- Taking any other action that the Jury deems as intentionally aimed at gaining an unfair advantage over other contestants.

Moreover, the following rules apply to submissions:

- Submissions must not attempt to access any files on the file system.
- Submissions must not attempt to use network functions.
- Submissions must not try to execute other programs.
- Breaching any of the rules outlined above may be considered cheating and may result in disqualification.

### Appeal process

After each contest day, contestants will have time to check the full results of their submissions, including test data used in grading.

If there is any disagreement with the results, the team leader may submit an appeal during the contest analysis session. The Jury will respond to each appeal and give a brief report to the team leaders about all appeals received after each contest. If every submission for a task needs to be re-graded and re-scored because of an accepted appeal, note that re-scoring may result in a higher or lower score for any contestant.

### Medal allocation

All contestants are ranked in descending order based on their final scores. Gold, silver, and bronze medals, as well as honourable mentions, are awarded to the contestants using the following algorithm:

- The score needed to receive a gold medal is the highest score such that at least one-twelfth of all contestants get a gold medal;
- The score needed to receive a silver medal is the highest score such that at least one-quarter of all contestants get a gold or silver medal. A silver medal is awarded to those who reach this score but did not obtain a gold medal;
- The score needed to receive a bronze medal is the highest score such that at least one-half of all contestants get a medal. A bronze medal is awarded to those who reach this score but did not get a gold or silver medal;
- A contestant who does not receive a medal will be awarded an honourable mention if, on at least one of the two competition days, fewer than half of the contestants have a higher score.

Unofficial contestants from guest countries are not included when calculating the medal boundaries. However, they are eligible to receive medals and honourable mentions based on their scores. The algorithm for awarding them is the same as for the official contestants.

Note that:

- The score needed for an unofficial contestant to receive a certain type of medal is the minimum score achieved by any official contestant who received that type of medal.
- An honourable mention is awarded to an unofficial contestant if, on at least one of the two competition days, fewer than half of the official contestants have a higher score.
