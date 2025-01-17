Lecture content, spring 2021
============================

[Go up to the CS 2150 page](../index.html) ([md](../index.md))

This page contains the material discussed during lecture times.  You can view previous material in the repo in this directory, but it is not necessarily going to be the same as the material discussed this semester.


The code, images, and notes linked to from this page is what was discussed during the lecture periods in the spring of 2021 in both the 10 a.m. and 1 p.m. lectures.  Some notes about the content on this page:

- The code herein is what was the state at the end of that lecture period; the development of the code helped explain the concepts, and that can be found in the lecture recordings; thus, there are no comments included in the files.
- Any images that were sketched on [sketch.io](https://sketch.io/sketchpad/) are included as well (in SVG format).
- Unless stated otherwise in the code comments, all code is compiled with `clang++ *.cpp` or `make` (the latter if a Makefile is present).
    - However, a few of the lecture files have multiple programs, and each one will have to be compiled separately (`clang++ <file1>.cpp`, `clang++ <file2>.cpp`, etc.).
- The material gone over will have already been covered in the lecture recordings, but not necessarily that day's lecture recordings -- sometimes the review covers material from a past recording.

### Lecture period content

- Lecture 29: Mon, Apr 12 (advanced C++ to 8.5) 
    - [classes.cpp](lec29/classes.cpp.html) ([raw code](lec29/classes.cpp))
- Lecture 28: Fri, Apr 9 (finished assembly; advanced C++ to slide 6.11)
    - Went over a number of exam questions:
        - [fall 2019 final](https://uva-cs.github.io/pdr/exams/final-f19.pdf), questions 6 and 7
	    - [spring 2019 final](https://uva-cs.github.io/pdr/exams/final-s19.pdf), question 7
        - [fall 2018 final](https://uva-cs.github.io/pdr/exams/final-f18.pdf), question 13
- Lecture 27: Wed, Apr 7 (assembly through slide 10.12)
    - Went over a number of exam questions:
        - [fall 2019 exam 2](https://uva-cs.github.io/pdr/exams/exam2-f19.pdf), question 11
	    - [spring 2019 exam 2](https://uva-cs.github.io/pdr/exams/exam2-s19.pdf), questions 11 & 12
        - [fall 2018 exam 2](https://uva-cs.github.io/pdr/exams/exam2-f18.pdf), questions 14 & 15
- Lecture 26: Mon, Apr 5 (assembly through slide 8.15)
    - [assembly.s](lec26/assembly.s.html) ([raw code](lec26/assembly.s))
    - [main.cpp](lec26/main.cpp.html) ([raw code](lec26/main.cpp))
    - [Makefile](lec26/Makefile.html) ([raw code](lec26/Makefile))
	- If you want to compile this on a Mac, you need to change the nasm output type from `elf64` to `macho64`, and change the name of the `factArray` and `factorial` subroutines to `_factArray` and `_factorial` (note the initial underscore; this is twice in the program for each name)
- Lecture 25: Fri, April 2 (assembly through slide 7.3)
	- [assembly.s](lec25/assembly.s.html) ([raw code](lec25/assembly.s))
	- [main.cpp](lec25/main.cpp.html) ([raw code](lec25/main.cpp))
	- [Makefile](lec25/Makefile.html) ([raw code](lec25/Makefile))
	- If you want to compile this on a Mac, you need to change the nasm output type from `elf64` to `macho64` in the Makefile, and change the name of the `addOrMult` subroutine to `_addOrMult` (note the initial underscore; this is twice in the program, on lines 9 and 13)
- Lecture 24: Wed, Mar 31 (assembly through slide 5.6)
    - This was a Q&A about hash lab and a review of the x86 addressing scheme
- (Mon, Mar 29 was a UVA break day, so no lecture materials from that day)
- Lecture 23: Fri, Mar 26 (finished IBCM; finished trees)
    - This was a Q&A about IBCM (not many questions asked about that) and a review of amortized analysis from the trees slide set
- Lecture 22: Wed, Mar 24 (IBCM through slide 6.12)
    - We discussed the array-summation program in IBCM, and [the memory diagram for such](lec22/lec22.svg)
- Lecture 21: Mon, Mar 22 (IBCM through slide 5.15)
    - Today was a Q&A period, and thus there was no material prepared in advance
- Lecture 20: Fri, Mar 19 (finished hashes)
    - [Makefile](lec20/Makefile.html) ([raw code](lec20/Makefile)) for lab 2
    - [sketched image](lec20/lec20.svg) which is the solutions to questions 5 and 6 on [midterm 2 from fall 2017](../../exams/exam2-f17.pdf)
- Lecture 19: Wed, Mar 17 (hashes through slide 7.4)
    - We went over collision resolution algorithms via the animation sites at [Open hashing a.k.a. Separate Chaining](https://www.cs.usfca.edu/~galles/visualization/OpenHash.html) and [Closed hashing a.k.a. Open Addressing](https://www.cs.usfca.edu/~galles/visualization/ClosedHash.html)
- Lecture 18: Mon, Mar 15 (trees through slide 9.12; hashes through slide 5.5)
    - Animations are at [https://www.cs.usfca.edu/~galles/visualization/](https://www.cs.usfca.edu/~galles/visualization/), specifically the ones for [AVL trees](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html) and [Red-Black trees](https://www.cs.usfca.edu/~galles/visualization/RedBlack.html)
    - [Tree exam questions](lec18/code.txt) from page 3 of [fall 2019 exam 2](../../exams/exam2-f19.pdf) and page 3 of [spring 2019 exam 2](../../exams/exam2-s19.pdf)
- Lecture 17: Fri, Mar 12 (trees through slide 7.31)
    - Animations are at [https://www.cs.usfca.edu/~galles/visualization/](https://www.cs.usfca.edu/~galles/visualization/), specifically the one for [AVL trees](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html)
    - [rotation before](lec17/after.svg), [rotation after](lec17/before.svg)
- Lecture 16: Wed, Mar 10 (trees through slide 7.9)
    - Animations are at [https://www.cs.usfca.edu/~galles/visualization/](https://www.cs.usfca.edu/~galles/visualization/), specifically the [one for BSTs](https://www.cs.usfca.edu/~galles/visualization/BST.html)
    - [Exam 2, fall 2018](../../exams/exam2-f18.pdf): the [answer to question 8](lec16/exam2-f18-q8.txt)
- Lecture 15: Mon, Mar 8 (trees through slide 5.11)
    - Animations are at [https://www.cs.usfca.edu/~galles/visualization/](https://www.cs.usfca.edu/~galles/visualization/), specifically the [one for BSTs](https://www.cs.usfca.edu/~galles/visualization/BST.html)
    - [sketched image](lec15/lec15.svg)
- Lecture 14: Fri, Sep 25 (finished arrays arrays & big-Oh)
    - [comparison graph image](lec14/lec14-graph.svg)
    - [big-Oh proof image](lec14/lec14-proof.svg)
- Lecture 13: Wed, Mar 3 (arrays & big-Oh to 5.8)
    - [errors-no-comments.cpp](lec13/errors-no-comments.cpp.html) ([raw code](lec13/errors-no-comments.cpp))
    - [errors-fixed.cpp](lec13/errors-fixed.cpp.html) ([raw code](lec13/errors-fixed.cpp))
- Lecture 12: Mon, Mar 1 (finished numbers, arrays & big-Oh to 4.4)
    - [arrays.cpp](lec12/arrays.cpp.html) ([raw code](lec12/arrays.cpp))
    - [sketched image](lec12/lec12.svg)
- Lecture 11: Fri, Feb 26 (numbers through 9.21)
    - [Fall 2019, exam 1, question 10](lec11/lec11-a.svg) ([exam PDF](../../exams/exam1-f19.pdf))
    - [Spring 2019, exam 1, question 9, part a](lec11/lec11-b.svg) ([exam PDF](../../exams/exam1-s19.pdf))
    - [Spring 2019, exam 1, question 9, part b & c](lec11/lec11-c.svg) ([exam PDF](../../exams/exam1-s19.pdf))
- Lecture 10: Wed, Feb 24 (numbers through slide 8.10)
    - [Radix conversion image](lec10/lec10-a.svg)
    - [Base 2 <-> base 16 conversion image](lec10/lec10-b.svg)
    - [Endian-ness conversion image](lec10/lec10-c.svg)
    - [Two's complement conversion image](lec10/lec10-d.svg)
- Lecture 9: Mon, Feb 22 (finished lists; numbers through slide 5.2)
    - [vectors.cpp](lec09/vectors.cpp.html) ([raw code](lec09/vectors.cpp))
    - [sketched image](lec09/lec09.svg)
- Lecture 8: Fri, Feb 19: lists to 6.11
    - [copying.cpp](lec08/copying.cpp.html) ([raw code](lec08/copying.cpp))
    - [sketched image](lec08/lec08.svg)
- (Wed, Feb 17 was a UVA break day, so no lecture materials from that day)
- Lecture 7: Mon, Feb 15: finished C++; lists to 4.6
    - [destructors.cpp](lec07/destructors.cpp.html) ([raw code](lec07/destructors.cpp))
    - [sketched image](lec07/lec07.svg)
- Lecture 6: Fri, Feb 12 (c++ through slide 12.10)
    - [stuff.cpp](lec06/stuff.cpp.html) ([raw code](lec06/stuff.cpp))
    - [moreswap.cpp](lec06/moreswap.cpp.html) ([raw code](lec06/moreswap.cpp)) ([swap sketched image](lec05/swap.svg))
    - [dangling.cpp](lec06/dangling.cpp.html) ([raw code](lec06/dangling.cpp)) ([dangling sketched image](lec06/dangling.svg))
- Lecture 5: Wed, Feb 10 (c++ through slide 10.17)
    - [swap sketched image](lec05/swap.svg)
    - [notswap.cpp](lec05/notswap.cpp.html) ([raw code](lec05/notswap.cpp))
    - [mistakes.cpp](lec05/mistakes.cpp.html) ([raw code](lec05/mistakes.cpp)) and the [mistakes sketched image](lec05/mistakes.svg)
- Lecture 4: Mon, Feb 8 (c++ through slide 9.19)
    - [pointers.cpp](lec04/pointers.cpp.html) ([raw code](lec04/pointers.cpp))
    - [sketched image](lec04/lec04.svg)
- Lecture 3: Fri, Feb 5 (c++ through slide 8.1)
    - [item.cpp](lec03/item.cpp.html) ([raw code](lec03/item.cpp))
    - [item.h](lec03/item.h.html) ([raw code](lec03/item.h))
    - [main.cpp](lec03/main.cpp.html) ([raw code](lec03/main.cpp))
- Lecture 2: Wed, Feb 3 (finished course intro; c++ through slide 5.5)
    - [helloworld.cpp](lec02/helloworld.cpp.html) ([raw code](lec02/helloworld.cpp))
- Lecture 1: Mon, Feb 1 (course intro to slide 3.40)
    - This lecture discussed the class structure, so no code was developed
