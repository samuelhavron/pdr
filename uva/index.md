Program and Data Representation: CS 2150 Specific Content
=========================================================

## Fall 2016

[Go up to the main README file][111] ([md][112])

Much of the rest of this git repo is meant to be generic to anybody who has a class such as this one.  But this page contains details specific to the CS 2150 version of the course at the University of Virginia.

------------------------------------------------------------

Links
-----

There are a number of links and other parts of this course that are **NOT** included in this repository.  They are:

- The set of online tools, which can be accessed through Collab or [here][160].
    - These tools are: [support requests][161], [lab submission][162], [regrades][163], [gradebook][164], [lab extensions][165], and the [office hours queue][166]
- The announcements, which are posted to the CS 2150 twitter feed: [\@UVaCS2150][151]
- The [CS 2150 Google calendar][150]
- Grading guidelines, which are available in the Collab wiki ([here][171] is the direct link, although Collab login is required)
- Email list archive, which is a Collab tool ([here][170] is the direct link, although Collab login is required)
- [Piazza][152]; Collab can log you in directly; the Collab tool link is [here][173] (again, Collab login required)

The parts of this course that are in this repo are:

- [Daily announcements slide set][102]
- [Course introduction slide set][80]
- [Course syllabus][103] ([md][104]): the course syllabus
- [Lab due dates][105] ([md][106]): When the various lab parts are due
- [UNIX honor pledge][172], which needs to be signed by all the students in the course (it is created from a [.tex][114] file)
- [Generic review session slide set][113], which is really just a blank set of slides
- [Frivolous regrade policy][109] ([md][110]) for exams

------------------------------------------------------------

Labs and Tutorials
------------------

This is a series of links to the labs and tutorials that are elsewhere in this repository.  A bunch of notes:

- The lab parts are all due on specific times throughout the week, as detailed on the [lab due dates][105] ([md][106]) page
    - Each lab is for a given week, which (for sake of argument) we claim starts on a Monday
    - Which lab is done on which week is listed below in the semester schedule
- The lab is released the week before, typically on a Wednesday or Thursday
    - While a version of the lab will be in this github repo for some time prior, there **WILL** be modifications to that lab up until the "official" release, which is when it is announced as released on the twitter feed: [\@UVaCS2150](http://twitter.com/UVaCS2150)
- All the labs and tutorials can be found on the [labs page][107] ([md][108]) and the [tutorials page][100] ([md][101]).
    - In particular, these pages have additional details and links not described here

------------------------------------------------------------

Semester Schedule
-----------------

The links in the right-most column link directly to the lecture recording on Collab, and you have to be logged into Collab first before the link will work. Some plugins (such as NoScript) will block that link from working.

| Num | Date | Day of week | Lab & Tutorial (on Tue) | Planned topic | Lecture 1 progress | Lecture 2 progress |
|-----|--------|-------------|----------------------------------------------------------|--------------------------|-----------|--------------| 
|1|Aug 24| Wednesday | no lab this week | [Course introduction][80] | [course intro][80], slides [1][80] to [5.3][1000402] ([recording][201]) | [course intro][80], slides [1][80] to [5.0][10004] |
|2|Aug 26| Friday    | | [Course introduction][80], [01: C++][81] | [course intro][80], slides [5.4][1000403] to [7.2][1000601]; [C++][81], slides [1][81] to [4.13][1010312] ([recording][202]) | [course intro][80], slides [5.0][10004] to [6.1][1000601]; [C++][81], slides [1][81] to [6.1][10105] |
|3|Aug 29| Monday    | [Lab 1: Intro to C++][1] ([md][21]) / [Tutorial 1: Intro to UNIX][41] ([md][61]) | [01: C++][81] | [C++][81], slides [4.14][1010313] to [7.9][1010608] ([recording][203]) | [01:C++][81], slides [6.1][10105] to [8.5][1010704] |
|4|Aug 31| Wednesday | | [01: C++][81] | [C++][81], slides [8.1][10107] to [9.19][1010818] ([recording][204]) | [01:C++][81], slides [9.1][10108] to [9.17][1010816] |
|5|Sep 2| Friday    | | [01: C++][81] | [C++][81], slides [10.1][10109] to [10.16][1010915] ([recording][205]) | [01:C++][81], slides [9.18][1010817] to [10.13][1010912] |
|6|Sep 5| Monday    | [Lab 2: Linked lists][2] ([md][22]) / [Tutorial 2: LLDB][42] ([md][62]) *OR* [Tutorial 2: GDB][52] ([md][72]) (see [lab 2][2] for which one to pick) | [01: C++][81] | | [01:C++][81], slides [10.13][1010912] to [12.4][1011103] |
|7|Sep 7| Wednesday | | [01: C++][81], [02: Lists][82] | | |
|8|Sep 9| Friday    | | [02: Lists][82] | | |
|9|Sep 12| Monday    | [Lab 3: Stacks][3] ([md][23]) / [Tutorial 3: More UNIX, part 1][63], introduction and sections 1-4 | [02: Lists][82], [03: Numbers][83] | | |
|10|Sep 14| Wednesday | | [03: Numbers][83] | | |
|11|Sep 16| Friday    | | [03: Numbers][83] | | |
|12|Sep 19| Monday    | [Lab 4: Numbers][4] ([md][24]) / [Tutorial 4: More UNIX, part 2][64], sections 5-8 | [03: Numbers][83] | | |
|13|Sep 21| Wednesday | | [04: Arrays & big-Oh][84] | | |
|14|Sep 23| Friday    | | [04: Arrays & big-Oh][84] | | |
|  |Sep 25| Sunday    | | Exam 1 review session | | |
|15|Sep 26| Monday    | Exam 1 instead during Tuesday's lab | [04: Arrays & big-Oh][84] | | |
|16|Sep 38| Wednesday | | [05: Trees][85] | | |
|17|Sep 30| Friday    | | [05: Trees][85]| | |
|  |Oct 3| Monday    | No lab this week due to fall break | (fall break) | | |
|18|Oct 5| Wednesday | | [05: Trees][85] | | |
|19|Oct 7| Friday    | | [05: Trees][85], [06: Hashes][86] | | |
|20|Oct 10| Monday    | [Lab 5: Trees][5] ([md][25]) / [Tutorial 5: make][45] ([md][65]) | [06: Hashes][86] | | |
|21|Oct 12| Wednesday | | [06: Hashes][86] | | |
|22|Oct 14| Friday    | | [06: Hashes][86], [07: IBCM][87] (machine language) | | |
|23|Oct 17| Monday    | [Lab 6: Hashes][6] ([md][26]) / Tutorial 6: Shell scripting, part 1 (part of [this link][46]; the specific sections are mentioned on the [tutorials page][40]) | [07: IBCM][87] (machine language) | | |
|24|Oct 19| Wednesday | | [07: IBCM][87] (machine language) | | |
|25|Oct 21| Friday    | | [08: assembly][88] (assembly language) | | |
|26|Oct 24| Monday    | [Lab 7: IBCM][7] ([md][27]) / Tutorial 7: Shell scripting, part 2 (remainder of [here][47], as described on the [tutorials page][40]) | [08: assembly][88] (assembly language) | | |
|27|Oct 26| Wednesday | | [08: assembly][88] (assembly language) | | |
|28|Oct 28| Friday    | | [08: assembly][88] (assembly language) | | |
|29|Oct 31| Monday    | [Lab 8: assembly, part 1][8] ([md][28]) / Tutorial 8: nasm, which is two book chapters: [1][53] and [2][54] | [08: assembly][88], [09: Advanced C++][89] | | |
|30|Nov 2| Wednesday | | [09: Advanced C++][89] | | |
|31|Nov 4| Friday    | | [09: Advanced C++][89] | | |
||Nov 6|Sunday| |Exam 2 review session| | |
|32|Nov 7| Monday    | Exam 2 instead during Tuesday's lab | [10: Heaps and Huffman coding][90] | | |
|33|Nov 9| Wednesday | | [10: Heaps and Huffman coding][90] | | |
|34|Nov 11| Friday    | | [10: Heaps and Huffman coding][90] | | |
|35|Nov 14| Monday    | [Lab 9: assembly, part 2][9] ([md][29]) / [Tutorial 9: C][49] ([md][69]) | [10: Heaps and Huffman coding][90], [11: Graphs][91] | | |
|36|Nov 16| Wednesday | | [11: Graphs][91] | | |
|37|Nov 18| Friday    | | [11: Graphs][91] | | |
|38|Nov 21| Monday    | [Lab 10: Huffman coding][10] ([md][30]) / (no tutorial) | [11: Graphs][91] | | |
||Nov 23| Wednesday | | (Thanksgiving break) | | |
||Nov 25| Friday    | | (Thanksgiving break) | | |
|39|Nov 28| Monday | [Lab 11: Graphs][11] ([md][31]) | [11: Graphs][91] | | |
|40|Nov 30| Wednesday    || [12: Memory][92] | | |
|41|Dec 2| Friday    || [12: Memory][92] | | |
|42|Dec 5| Monday   | [Lab 12: Objective C][12] ([md][32])|[13: Esoteric PLs][93], [Course conclusion][94] | | |
||Dec 7| Wednesday || Final exam review session | | |
||Dec 9| Friday    | Final exam from 7:00 p.m. - 10:00 p.m. in the lecture classroom| Final exam from 7:00 p.m. - 10:00 p.m. in the lecture classroom | | |


------------------------------------------------------------

Grading Concerns
----------------

None yet!


[1]: ../labs/lab01/index.html
[2]: ../labs/lab02/index.html
[3]: ../labs/lab03/index.html
[4]: ../labs/lab04/index.html
[5]: ../labs/lab05/index.html
[6]: ../labs/lab06/index.html
[7]: ../labs/lab07/index.html
[8]: ../labs/lab08/index.html
[9]: ../labs/lab09/index.html
[10]: ../labs/lab10/index.html
[11]: ../labs/lab11/index.html
[12]: ../labs/lab12/index.html

[21]: ../labs/lab01/index.md
[22]: ../labs/lab02/index.md
[23]: ../labs/lab03/index.md
[24]: ../labs/lab04/index.md
[25]: ../labs/lab05/index.md
[26]: ../labs/lab06/index.md
[27]: ../labs/lab07/index.md
[28]: ../labs/lab08/index.md
[29]: ../labs/lab09/index.md
[30]: ../labs/lab10/index.md
[31]: ../labs/lab11/index.md
[32]: ../labs/lab12/index.md

[40]: ../tutorials/index.html
[41]: ../tutorials/01-intro-unix/index.html
[42]: ../tutorials/02-lldb/index.html
[43]: ../tutorials/03-04-more-unix/index.html
[44]: ../tutorials/03-04-more-unix/index.html
[45]: ../tutorials/05-make/index.html
[46]: http://en.wikibooks.org/wiki/Bash_Shell_Scripting
[47]: http://en.wikibooks.org/wiki/Bash_Shell_Scripting
[48]: http://cs.lmu.edu/~ray/notes/nasmexamples/
[49]: ../tutorials/09-c/index.html
[50]: ../tutorials/10-objc/index.html
[51]: ../tutorials/11-doxygen/index.html
[52]: ../tutorials/02-gdb/index.html
[53]: ../book/x86-asm-chapter.pdf
[54]: ../book/x86-ccc-chapter.pdf

[61]: ../tutorials/01-intro-unix/index.md
[62]: ../tutorials/02-lldb/index.md
[63]: ../tutorials/03-04-more-unix/index.html
[64]: ../tutorials/03-04-more-unix/index.html
[65]: ../tutorials/05-make/index.md
[69]: ../tutorials/09-c/index.md
[70]: ../tutorials/10-objc/index.md
[71]: ../tutorials/11-doxygen/index.md
[72]: ../tutorials/02-gdb/index.md

[80]: course-introduction.html#/
[81]: ../slides/01-cpp.html#/
[82]: ../slides/02-lists.html#/
[83]: ../slides/03-numbers.html#/
[84]: ../slides/04-arrays-bigoh.html#/
[85]: ../slides/05-trees.html#/
[86]: ../slides/06-hashes.html#/
[87]: ../slides/07-ibcm.html#/
[88]: ../slides/08-assembly.html#/
[89]: ../slides/09-advanced-cpp.html#/
[90]: ../slides/10-heaps-huffman.html#/
[91]: ../slides/11-graphs.html#/
[92]: ../slides/12-memory.html#/
[93]: ../slides/13-esoteric-pls.html#/
[94]: course-conclusion.html#/

[100]: ../tutorials/index.html
[101]: ../tutorials/index.md
[102]: daily-announcements.html#/
[103]: syllabus.html
[104]: syllabus.md
[105]: labduedates.html
[106]: labduedates.md
[107]: ../labs/index.html
[108]: ../labs/index.md
[109]: frivolous-regrades.html
[110]: frivolous-regrades.md
[111]: ../README.html
[112]: ../README.md
[113]: exam-review.html#/
[114]: unix-honor-pledge.tex
[115]: grades.md
[116]: grades.html

[150]: https://www.google.com/calendar/embed?src=1ea0dfillqvhlop8d7t0m8afuo%40group.calendar.google.com&amp;amp;ctz=America/New_York
[151]: http://twitter.com/UVaCS2150
[152]: https://piazza.com/

[160]: https://libra.cs.virginia.edu/~pedagogy/
[161]: https://libra.cs.virginia.edu/~pedagogy/support.php
[162]: https://libra.cs.virginia.edu/~pedagogy/submit.php
[163]: https://libra.cs.virginia.edu/~pedagogy/regrades.php
[164]: https://libra.cs.virginia.edu/~pedagogy/gradebook.php
[165]: https://libra.cs.virginia.edu/~pedagogy/labextension.php
[166]: https://libra.cs.virginia.edu/~pedagogy/queue.php

[170]: https://collab.itc.virginia.edu/portal/directtool/ae2a5a5b-fcd3-4d31-8c75-ecf38423b324/
[171]: https://collab.itc.virginia.edu/portal/directtool/9fbe1e59-10dc-45a6-8b1e-f1062f52388b/
[172]: unix-honor-pledge-f16.pdf
[173]: https://collab.itc.virginia.edu/portal/directtool/8723e3bb-c094-4e9e-8371-6206aad68e64/

[201]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/course-introduction-1/course-introduction-1.htm
[202]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-1/01-cpp-1.htm
[203]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-2/01-cpp-2.htm
[204]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-3/01-cpp-3.htm
[205]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-4/01-cpp-4.htm
[206]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-5/01-cpp-5.htm
[207]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/01-cpp-6/01-cpp-6.htm
[208]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/02-lists-1/02-lists-1.htm
[209]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/02-lists-2/02-lists-2.htm
[210]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/03-numbers-1/03-numbers-1.htm
[211]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/03-numbers-2/03-numbers-2.htm
[212]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/03-numbers-3/03-numbers-3.htm
[213]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/03-numbers-4/03-numbers-4.htm
[214]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/04-arrays-bigoh-1/04-arrays-bigoh-1.htm
[215]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/04-arrays-bigoh-2/04-arrays-bigoh-2.htm
[216]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/04-arrays-bigoh-3/04-arrays-bigoh-3.htm
[217]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/exam1-review/exam1-review.htm
[218]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/05-trees-1/05-trees-1.htm
[219]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/05-trees-2/05-trees-2.htm
[220]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/05-trees-3/05-trees-3.htm
[221]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/05-trees-4/05-trees-4.htm
[222]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/05-trees-5/05-trees-5.htm
[223]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/06-hashes-1/06-hashes-1.htm
[224]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/06-hashes-2/06-hashes-2.htm
[225]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/06-hashes-3/06-hashes-3.htm
[226]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/07-ibcm-1/07-ibcm-1.htm
[227]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/07-ibcm-2/07-ibcm-2.htm
[228]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/07-ibcm-3/07-ibcm-3.htm
[229]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/07-ibcm-4/07-ibcm-4.htm
[230]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-1/08-assembly-1.htm
[231]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-2/08-assembly-2.htm
[232]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-3/08-assembly-3.htm
[233]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-4/08-assembly-4.htm
[234]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-5/08-assembly-5.htm
[235]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/08-assembly-6/08-assembly-6.htm
[236]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/09-advanced-cpp-1/09-advanced-cpp-1.htm
[237]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/09-advanced-cpp-2/09-advanced-cpp-2.htm
[238]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/exam2-review/exam2-review.htm
[239]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/09-advanced-cpp-3/09-advanced-cpp-3.htm
[240]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/10-heaps-huffman-1/10-heaps-huffman-1.htm
[241]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/10-heaps-huffman-2/10-heaps-huffman-2.htm
[242]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/10-heaps-huffman-3/10-heaps-huffman-3.htm
[243]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/10-heaps-huffman-4/10-heaps-huffman-4.htm
[244]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/11-graphs-1/11-graphs-1.htm
[245]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/11-graphs-2/11-graphs-2.htm
[246]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/11-graphs-3/11-graphs-3.htm
[247]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/11-graphs-4/11-graphs-4.htm
[248]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/12-memory-1/12-memory-1.htm
[249]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/12-memory-2/12-memory-2.htm
[250]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/12-memory-3/12-memory-3.htm
[251]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/course-conclusion/course-conclusion.htm
[252]: https://collab.itc.virginia.edu/access/content/group/96c378c9-1219-45c7-a514-acd313ae6c00/lectures/final-review/final-review.htm

[1000228]: ../uva/course-introduction.html#/2/28
[1000303]: ../uva/course-introduction.html#/3/3
[10004]: ../uva/course-introduction.html#/4
[1000402]: ../uva/course-introduction.html#/4/2
[1000403]: ../uva/course-introduction.html#/4/3
[10005]: ../uva/course-introduction.html#/5
[1000601]: ../uva/course-introduction.html#/6/1
[1010310]: ../slides/01-cpp.html#/3/10
[1010311]: ../slides/01-cpp.html#/3/11
[1010312]: ../slides/01-cpp.html#/3/12
[1010313]: ../slides/01-cpp.html#/3/13
[1010404]: ../slides/01-cpp.html#/4/4
[10105]: ../slides/01-cpp.html#/5
[1010503]: ../slides/01-cpp.html#/5/3
[1010505]: ../slides/01-cpp.html#/5/5
[1010608]: ../slides/01-cpp.html#/6/8
[10107]: ../slides/01-cpp.html#/7
[1010704]: ../slides/01-cpp.html#/7/4
[10108]: ../slides/01-cpp.html#/8
[1010809]: ../slides/01-cpp.html#/8/9
[1010815]: ../slides/01-cpp.html#/8/15
[1010816]: ../slides/01-cpp.html#/8/16
[1010817]: ../slides/01-cpp.html#/8/17
[1010818]: ../slides/01-cpp.html#/8/18
[10109]: ../slides/01-cpp.html#/9
[1010905]: ../slides/01-cpp.html#/9/5
[1010911]: ../slides/01-cpp.html#/9/11
[1010912]: ../slides/01-cpp.html#/9/12
[1010913]: ../slides/01-cpp.html#/9/13
[1010914]: ../slides/01-cpp.html#/9/14
[1010915]: ../slides/01-cpp.html#/9/15
[1010919]: ../slides/01-cpp.html#/9/19
[1010920]: ../slides/01-cpp.html#/9/20
[10110]: ../slides/01-cpp.html#/10
[1011001]: ../slides/01-cpp.html#/10/1
[1011103]: ../slides/01-cpp.html#/11/3
[1011104]: ../slides/01-cpp.html#/11/4
[1011105]: ../slides/01-cpp.html#/11/5
[1011106]: ../slides/01-cpp.html#/11/6
[1011205]: ../slides/01-cpp.html#/12/5
[1011213]: ../slides/01-cpp.html#/12/13
[10200]: ../slides/02-lists.html
[1020304]: ../slides/02-lists.html#/3/4
[1020305]: ../slides/02-lists.html#/3/5
[10204]: ../slides/02-lists.html#/4
[1020505]: ../slides/02-lists.html#/5/5
[1020507]: ../slides/02-lists.html#/5/7
[1020508]: ../slides/02-lists.html#/5/8
[1020515]: ../slides/02-lists.html#/5/15
[10206]: ../slides/02-lists.html#/6
[1020606]: ../slides/02-lists.html#/6/6
[1020607]: ../slides/02-lists.html#/6/7
[1020706]: ../slides/02-lists.html#/7/6
[10208]: ../slides/02-lists.html#/8
[1020803]: ../slides/02-lists.html#/8/3
[10304]: ../slides/03-numbers.html#/4
[1030403]: ../slides/03-numbers.html#/4/3
[1030404]: ../slides/03-numbers.html#/4/4
[1030303]: ../slides/03-numbers.html#/3/3
[10307]: ../slides/03-numbers.html#/7
[1030701]: ../slides/03-numbers.html#/7/1
[1030608]: ../slides/03-numbers.html#/6/8
[1030705]: ../slides/03-numbers.html#/7/5
[1030801]: ../slides/03-numbers.html#/8/1
[1030809]: ../slides/03-numbers.html#/8/9
[1030810]: ../slides/03-numbers.html#/8/10
[1030813]: ../slides/03-numbers.html#/8/13
[1030814]: ../slides/03-numbers.html#/8/14
[1030815]: ../slides/03-numbers.html#/8/15
[1030816]: ../slides/03-numbers.html#/8/16
[1030825]: ../slides/03-numbers.html#/8/25
[1030832]: ../slides/03-numbers.html#/8/32
[1030833]: ../slides/03-numbers.html#/8/33
[1030834]: ../slides/03-numbers.html#/8/34
[1040306]: ../slides/04-arrays-bigoh.html#/3/6
[1040307]: ../slides/04-arrays-bigoh.html#/3/7
[1040311]: ../slides/04-arrays-bigoh.html#/3/11
[10404]: ../slides/04-arrays-bigoh.html#/4
[1040402]: ../slides/04-arrays-bigoh.html#/4/2
[1040403]: ../slides/04-arrays-bigoh.html#/4/3
[1040409]: ../slides/04-arrays-bigoh.html#/4/9
[1040410]: ../slides/04-arrays-bigoh.html#/4/10
[1040419]: ../slides/04-arrays-bigoh.html#/4/19
[1040420]: ../slides/04-arrays-bigoh.html#/4/20
[1040507]: ../slides/04-arrays-bigoh.html#/5/7
[1050305]: ../slides/05-trees.html#/3/5
[1050306]: ../slides/05-trees.html#/3/6
[1050311]: ../slides/05-trees.html#/3/11
[1050410]: ../slides/05-trees.html#/4/10
[1050411]: ../slides/05-trees.html#/4/11
[1050412]: ../slides/05-trees.html#/4/12
[1050415]: ../slides/05-trees.html#/4/15
[1050416]: ../slides/05-trees.html#/4/16
[1050417]: ../slides/05-trees.html#/4/17
[10505]: ../slides/05-trees.html#/5
[10506]: ../slides/05-trees.html#/6
[1050604]: ../slides/05-trees.html#/6/4
[1050609]: ../slides/05-trees.html#/6/9
[1050610]: ../slides/05-trees.html#/6/10
[1050612]: ../slides/05-trees.html#/6/12
[1050617]: ../slides/05-trees.html#/6/17
[1050630]: ../slides/05-trees.html#/6/30
[10507]: ../slides/05-trees.html#/7
[1050703]: ../slides/05-trees.html#/7/3
[1050709]: ../slides/05-trees.html#/7/9
[1050711]: ../slides/05-trees.html#/7/11
[10508]: ../slides/05-trees.html#/8
[1050801]: ../slides/05-trees.html#/8/1
[1050802]: ../slides/05-trees.html#/8/2
[1050808]: ../slides/05-trees.html#/8/8
[10509]: ../slides/05-trees.html#/9
[1050909]: ../slides/05-trees.html#/9/9
[10604]: ../slides/06-hashes.html#/4
[1060411]: ../slides/06-hashes.html#/4/11
[1060412]: ../slides/06-hashes.html#/4/12
[1060413]: ../slides/06-hashes.html#/4/13
[1060401]: ../slides/06-hashes.html#/4/1
[1060404]: ../slides/06-hashes.html#/4/4
[1060405]: ../slides/06-hashes.html#/4/5
[1060414]: ../slides/06-hashes.html#/4/14
[10605]: ../slides/06-hashes.html#/5
[1060502]: ../slides/06-hashes.html#/5/2
[1060507]: ../slides/06-hashes.html#/5/7
[10606]: ../slides/06-hashes.html#/6
[1060604]: ../slides/06-hashes.html#/6/4
[1060608]: ../slides/06-hashes.html#/6/8
[1060609]: ../slides/06-hashes.html#/6/9
[1060611]: ../slides/06-hashes.html#/6/11
[10607]: ../slides/06-hashes.html#/7
[1060702]: ../slides/06-hashes.html#/7/2
[1060706]: ../slides/06-hashes.html#/7/6
[1070302]: ../slides/07-ibcm.html#/3/2
[1070303]: ../slides/07-ibcm.html#/3/3
[1070401]: ../slides/07-ibcm.html#/4/1
[1070402]: ../slides/07-ibcm.html#/4/2
[1070404]: ../slides/07-ibcm.html#/4/4
[1070405]: ../slides/07-ibcm.html#/4/5
[1070407]: ../slides/07-ibcm.html#/4/7
[1070415]: ../slides/07-ibcm.html#/4/15
[10705]: ../slides/07-ibcm.html#/5
[1070503]: ../slides/07-ibcm.html#/5/3
[1070505]: ../slides/07-ibcm.html#/5/5
[1070506]: ../slides/07-ibcm.html#/5/6
[1070511]: ../slides/07-ibcm.html#/5/11
[1070601]: ../slides/07-ibcm.html#/6/1
[1070604]: ../slides/07-ibcm.html#/6/4
[1070609]: ../slides/07-ibcm.html#/6/9
[1080306]: ../slides/08-assembly.html#/3/6
[1080410]: ../slides/08-assembly.html#/4/10
[1080304]: ../slides/08-assembly.html#/3/4
[1080305]: ../slides/08-assembly.html#/3/5
[10805]: ../slides/08-assembly.html#/5
[1080502]: ../slides/08-assembly.html#/5/2
[1080504]: ../slides/08-assembly.html#/5/4
[1080505]: ../slides/08-assembly.html#/5/5
[1080607]: ../slides/08-assembly.html#/6/7
[1080608]: ../slides/08-assembly.html#/6/8
[1080609]: ../slides/08-assembly.html#/6/9
[10807]: ../slides/08-assembly.html#/7
[1080713]: ../slides/08-assembly.html#/7/13
[10808]: ../slides/08-assembly.html#/8
[1080804]: ../slides/08-assembly.html#/8/4
[1080805]: ../slides/08-assembly.html#/8/5
[10809]: ../slides/08-assembly.html#/9
[1080906]: ../slides/08-assembly.html#/9/6
[1080908]: ../slides/08-assembly.html#/9/8
[1080914]: ../slides/08-assembly.html#/9/14
[1080915]: ../slides/08-assembly.html#/9/15
[1080929]: ../slides/08-assembly.html#/9/29
[1080930]: ../slides/08-assembly.html#/9/30
[1080932]: ../slides/08-assembly.html#/9/32
[1080934]: ../slides/08-assembly.html#/9/34
[1090308]: ../slides/09-advanced-cpp.html#/3/8
[1090408]: ../slides/09-advanced-cpp.html#/4/8
[10905]: ../slides/09-advanced-cpp.html#/5
[1090508]: ../slides/09-advanced-cpp.html#/5/8
[1090509]: ../slides/09-advanced-cpp.html#/5/9
[1090518]: ../slides/09-advanced-cpp.html#/5/18
[1090519]: ../slides/09-advanced-cpp.html#/5/19
[1090520]: ../slides/09-advanced-cpp.html#/5/20
[1090521]: ../slides/09-advanced-cpp.html#/5/21
[10906]: ../slides/09-advanced-cpp.html#/6
[1090708]: ../slides/09-advanced-cpp.html#/7/8
[1090710]: ../slides/09-advanced-cpp.html#/7/10
[1090711]: ../slides/09-advanced-cpp.html#/7/11
[1100406]: ../slides/10-heaps-huffman.html#/4/6
[1100407]: ../slides/10-heaps-huffman.html#/4/7
[1100408]: ../slides/10-heaps-huffman.html#/4/8
[11005]: ../slides/10-heaps-huffman.html#/5
[1100501]: ../slides/10-heaps-huffman.html#/5/1
[1100503]: ../slides/10-heaps-huffman.html#/5/3
[1100508]: ../slides/10-heaps-huffman.html#/5/8
[1100512]: ../slides/10-heaps-huffman.html#/5/12
[1100515]: ../slides/10-heaps-huffman.html#/5/15
[1100605]: ../slides/10-heaps-huffman.html#/6/5
[11006]: ../slides/10-heaps-huffman.html#/6
[1100606]: ../slides/10-heaps-huffman.html#/6/6
[1100705]: ../slides/10-heaps-huffman.html#/7/5
[1100706]: ../slides/10-heaps-huffman.html#/7/6
[1100718]: ../slides/10-heaps-huffman.html#/7/18
[1100730]: ../slides/10-heaps-huffman.html#/7/30
[11008]: ../slides/10-heaps-huffman.html#/8
[1100808]: ../slides/10-heaps-huffman.html#/8/8
[1110304]: ../slides/11-graphs.html#/3/4
[1110305]: ../slides/11-graphs.html#/3/5
[1110402]: ../slides/11-graphs.html#/4/2
[11104]: ../slides/11-graphs.html#/4
[1110406]: ../slides/11-graphs.html#/4/6
[1110408]: ../slides/11-graphs.html#/4/8
[11105]: ../slides/11-graphs.html#/5
[1110507]: ../slides/11-graphs.html#/5/7
[1110508]: ../slides/11-graphs.html#/5/8
[1110509]: ../slides/11-graphs.html#/5/9
[1110513]: ../slides/11-graphs.html#/5/13
[11106]: ../slides/11-graphs.html#/6
[1110605]: ../slides/11-graphs.html#/6/5
[11107]: ../slides/11-graphs.html#/7
[1110708]: ../slides/11-graphs.html#/7/8
[11108]: ../slides/11-graphs.html#/8
[1110806]: ../slides/11-graphs.html#/8/6
[1110814]: ../slides/11-graphs.html#/8/14
[1120303]: ../slides/12-memory.html#/3/3
[1120304]: ../slides/12-memory.html#/3/4
[1120308]: ../slides/12-memory.html#/3/8
[1120311]: ../slides/12-memory.html#/3/11
[1120312]: ../slides/12-memory.html#/3/12
[1120325]: ../slides/12-memory.html#/3/25
[11204]: ../slides/12-memory.html#/4
[1120407]: ../slides/12-memory.html#/4/7
[1120414]: ../slides/12-memory.html#/4/14
[1120415]: ../slides/12-memory.html#/4/15
[1120418]: ../slides/12-memory.html#/4/18
[1130325]: ../slides/13-esoteric-pls.html#/3/25
[1130512]: ../slides/13-esoteric-pls.html#/5/12
[12009]: course-conclusion.html#/9
[12010]: course-conclusion.html#/10
[12011]: course-conclusion.html#/11

