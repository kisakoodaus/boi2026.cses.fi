+++
title = "Rules"
weight = 20
draft = true
+++

### Participation

The Baltic Olympiad in Informatics 2026 (BOI 2026) is an individual contest between contestants from ten member countries (Denmark, Estonia, Finland, Germany, Iceland, Latvia, Lithuania, Norway, Poland, Sweden) and one guest country (Ukraine).

Each country can participate with up to six contestants. All contestants must be eligible to compete in IOI 2026 to be participants in BOI 2026.

### Contest schedule

The contest days of BOI 2026 are Thursday, April 16, and Friday, April 17. On each contest day, the contestants will have five hours to complete three tasks.

There will be a practice session on Friday, April 15, where the contestants can familiarise themselves with the contest environment. The solutions submitted during the practice session will not be considered in the final ranking.

### Environment and supplies

Each contestant will have a desk with a workstation, including a screen, a keyboard and a mouse. The software environment will be the same on all workstations.

Contestants may bring their own stationery (pens, pencils, erasers, etc.). Paper will be available in the contest room, so you should not bring your own paper.

Each contestant may bring one wired non-programmable USB keyboard and/or one wired non-programmable USB mouse to use instead of the keyboard and mouse that are provided by the organizers. Contestant keyboard and mouse should be presented to the Technical Committee during the practice session and be accepted by a committee member.

Each contestant may bring one printed, non-annotated natural language dictionary. Contestants may bring small mascots such as stuffed toy animals.

Drinks and snacks will be provided during the contest.

Contestants are not allowed to bring any additional reference materials such as books, program listings or notes. Contestants may not bring any electronic devices (phones, smart watches, etc.).

Contestants who want to bring any other items must contact the Jury via their team leaders during the practice session.

Any stationery, keyboards, mice, dictionaries, or mascots must be brought to the contest room during the practice session. They will be checked and provided to the contestant during the contest sessions.

After the practice session and after the first contest day, the contestant must leave these items on their table if they want to use them during the contest next day. After the second contest day, the contestant must take all of these items with them.

### Tasks and solutions

The contest tasks posed at BOI 2026 are intended to be of an algorithmic nature. That is, the focus is on designing correct and efficient algorithms. In some tasks, the efficiency of implementation may also be a factor. Each task will be divided into one or more subtasks, each worth a portion of the total points.

Unless stated otherwise in the task description, the solution of a task is a program written in C++ or Python in one source code file. Solutions must be submitted via the contest system.

TODO: code/binary size limit / compilation time/memory limit?

<!--
Each submitted source code file must not exceed 100 KB and the evaluation server must be able to compile it in less than 30 seconds and use at most 512 MiB of memory. The compiled file must not exceed 10 MiB.
-->

Solutions have to run within the time and memory limits, which are specified for every task separately. Limits are applied to individual test runs. Using multiple threads is not allowed.

The Jury guarantees that there are C++ solutions which fit within the specified memory and time limits. Unless otherwise stated in the task description, solutions are required to read data from standard input and write to standard output.

### Starting the contest

When contestants enter the contest room at the beginning of the contest, their workstations will be running. Contest task descriptions are provided digitally via the contest system.

TODO: printed task statements?

<!--
and in print inside the same envelope. Contestants are not allowed to open the envelopes or touch anything on the workstations until the start signal is given.
-->

The task descriptions are presented in English and the native language of the contestant if such a translation has been prepared by a team leader. In case of any discrepancies, the English text is binding and official.

### Assistance and requests

During the contest, communication is allowed only with room supervisors and the Jury.

Contestants may ask a room supervisor for assistance at any time by raising a colored card available on the contestant’s desk. The supervisors will deliver the paper, attend to hardware problems, help to find toilets, etc. However, the supervisors will not answer questions about the contest tasks.

Contestants should submit questions about the contest tasks via the contest system. The question can be written in English or in the contestant's native language. In the latter case the team leader will be asked to translate the question into English.

A question about a task should be phrased so that a yes/no answer is meaningful. The Jury will answer every question submitted by the contestants. The answer will be one of the following:

- "YES"
- "NO"
- "NO COMMENT" – The contestant is asking for information that the Jury cannot give or the task description contains enough information.
- "INVALID QUESTION" – The question is not phrased so that a yes/no answer is meaningful. The contestant is encouraged to rephrase the question.

The Jury may give announcements related to tasks or the competition via the contest system.

Contestants are free to phrase their technical or contest related issues in any form. These issues/questions should not be related to contest tasks.

### Submissions and grading

The contestants submit their solutions via the contest system and can use the system to view the status of their submissions. When a solution is submitted, it will be compiled and graded. After this, the contestant will be able to view the score achieved by this submission and additional feedback if available. Input and output data are not shown to the contestant.

TODO: maximum number of submissions?

<!--
Contestants may submit at most 50 solutions for each task.
-->

Each submission will be graded on several test cases. Each test case will have one of the following outcomes:

- ACCEPTED: your program produced the correct answer
- WRONG ANSWER: your program produced an incorrect answer
- TIME LIMIT EXCEEDED: your program used too much time
- RUNTIME ERROR: an error occurred in the execution of your program, or it used too much memory
- OUTPUT LIMIT EXCEEDED: your program printed too much text

Test cases are grouped into subtasks, each worth some points.

A subtask is solved if every test in it is solved correctly and within time and memory limits. A submission will receive points for all subtasks that it solves.

The final score for a subtask is the maximum of the scores for that subtask over all submissions. The final score for a task is the sum of the final scores for its subtasks.

TODO: CSES must support this

The contestants will see their final score for each task in the contest system. However, there is a small chance that the score will change later due to appeals: submissions may be re-graded, and the final score will be that yielded by the last grading.

Grading procedures for a task can be overridden in the task description.

### Ending the contest

Contestants will be given warnings 30 and 10 minutes before the end of the contest. After the end of the contest, during the analysis mode, no further submissions will be included in a contestant's score.

In case of a technical failure, a contestant or a group of contestants will be granted additional time corresponding to the time that was needed to address the failure.

### Cheating

Any of the actions outlined below are considered illegal during contest sessions:

- Using any printed materials, except official BOI 2026 materials and unannotated natural language dictionaries brought to the practice session and cleared for use in contest sessions.
- Using any electronic devices or data carriers, except official BOI 2026 equipment and keyboards and mice brought to the practice session and cleared for use in contest sessions.
- Communicating in any form to other contestants or people other than BOI 2026 staff.
- Using a workstation or an account assigned to someone else.
- Tampering with or compromising the contest system.
- Attempting to gain access to the hidden test data used for grading solutions.
- Attempting to escalate privileges on the workstation.
- Attempting to access any machine other than their own or the contest system.
- Attempting to reboot or alter the boot sequence of any workstation.
- Any other action that is deemed by the Jury as intentionally aimed at gaining an unfair advantage over other contestants.

Moreover, the following rules apply to submissions:

- Submissions must not attempt to access any files on the file system.
- Submissions must not attempt to use network functions.
- Submissions must not try to execute other programs.
- Breaching any of the rules outlined above may be considered cheating and may result in disqualification.

### Appeal process

After each contest day, the contestants will have time to check the full results of their submissions, including test data used in grading.

In case of any disagreement with the results, the team leader may submit an appeal during the contest analysis. The Jury will answer each appeal and give a short report to the team leaders about all appeals received after each contest. In the event that every submission of a task should be re-graded and re-scored as a consequence of an accepted appeal, note that re-scoring may result in a higher or lower score for any contestant. Should anyone's score change after grading results have been published, new results will be published again. Score changes resulting from this are not appealable.

### Medal allocation

All contestants are ranked in descending order with respect to their final scores. Gold, silver and bronze medals, as well as honourable mentions, are awarded to the contestants using the following algorithm:

- The score necessary to achieve a gold medal is the largest score such that at least one-twelfth of all contestants receive a gold medal;
- The score necessary to achieve a silver medal is the largest score such that at least one-quarter of all contestants receive a gold or silver medal. A silver medal is awarded to those who obtained this score but did not obtain a gold medal;
- The score necessary to achieve a bronze medal is the largest score such that at least one-half of all contestants receive a medal. A bronze medal is awarded to those who obtained this score but obtained neither a gold nor a silver medal;
- A contestant who does not receive a medal will be awarded an honourable mention if, in at least one of the two competition days, fewer than half of the contestants have a higher score.

Unofficial contestants from the guest countries are not included when computing the medal boundaries. However, they are eligible to receive medals and honourable mentions according to their achieved scores. The algorithm for awarding them is the same as for the official contestants.

Note that:

- The score necessary for an unofficial contestant to achieve a certain type of medal is the minimum score achieved by any official contestant who got that type of medal;
- The honourable mention is awarded to an unofficial contestant if in at least one of the two competition days, fewer than half of the official contestants have a higher score.
