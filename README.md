
## Table of Contents

### Topics of Study
- [ ] [System Design, Scalability, Data Handling](#system-design-scalability-data-handling) (if you have 4+ years experience)
- [X] [Algorithmic complexity / Big-O / Asymptotic analysis](#algorithmic-complexity--big-o--asymptotic-analysis)
- [X] [Data Structures](#data-structures)
    - [X] [Arrays](#arrays)
    - [X] [Linked Lists](#linked-lists)
    - [X] [Stack](#stack)
    - [X] [Queue](#queue)
    - [X] [Hash table](#hash-table)
- [X] [More Knowledge](#more-knowledge)
    - [X] [Binary search](#binary-search)
    - [X] [Bitwise operations](#bitwise-operations)
- [X] [Trees](#trees)
    - [X] [Trees - Notes & Background](#trees---notes--background)
    - [X] [Binary search trees: BSTs](#binary-search-trees-bsts)
    - [X] [Heap / Priority Queue / Binary Heap](#heap--priority-queue--binary-heap)
- [X] [Sorting](#sorting)
    - [X] selection
    - [X] insertion
    - [X] heapsort
    - [X] quicksort
    - [X] merge sort
- [X] [Graphs](#graphs)
    - [X] directed
    - [X] undirected
    - [X] adjacency matrix
    - [X] adjacency list
    - [X] traversals: BFS, DFS
- [ ] [Even More Knowledge](#even-more-knowledge)
    - [X] [Recursion](#recursion)
    - [X] [Dynamic Programming](#dynamic-programming)
    - [X] [Design Patterns](#design-patterns)
    - [X] [Combinatorics (n choose k) & Probability](#combinatorics-n-choose-k--probability)
    - [X] [NP, NP-Complete and Approximation Algorithms](#np-np-complete-and-approximation-algorithms)
    - [X] [How computers process a program](#how-computers-process-a-program)
    - [X] [Caches](#caches)
    - [X] [Processes and Threads](#processes-and-threads)
    - [X] [Testing](#testing)
    - [X] [String searching & manipulations](#string-searching--manipulations)
    - [X] [Tries](#tries)
    - [X] [Floating Point Numbers](#floating-point-numbers)
    - [X] [Unicode](#unicode)
    - [X] [Endianness](#endianness)
    - [X] [Networking](#networking)
- [ ] [Final Review](#final-review)

### Getting the Job

- [Update Your Resume](#update-your-resume)
- [Find a Job](#find-a-job)
- [Interview Process & General Interview Prep](#interview-process--general-interview-prep)
- [Be thinking of for when the interview comes](#be-thinking-of-for-when-the-interview-comes)
- [Have questions for the interviewer](#have-questions-for-the-interviewer)
- [Once You've Got The Job](#once-youve-got-the-job)

**---------------- Everything below this point is optional ----------------**

### Optional Extra Topics & Resources

- [Additional Books](#additional-books)
- [Additional Learning](#additional-learning)
    - [Compilers](#compilers)
    - [Emacs and vi(m)](#emacs-and-vim)
    - [Unix command line tools](#unix-command-line-tools)
    - [Information theory](#information-theory-videos)
    - [Parity & Hamming Code](#parity--hamming-code-videos)
    - [Entropy](#entropy)
    - [Cryptography](#cryptography)
    - [Compression](#compression)
    - [Computer Security](#computer-security)
    - [Garbage collection](#garbage-collection)
    - [Parallel Programming](#parallel-programming)
    - [Messaging, Serialization, and Queueing Systems](#messaging-serialization-and-queueing-systems)
    - [A*](#a)
    - [Fast Fourier Transform](#fast-fourier-transform)
    - [Bloom Filter](#bloom-filter)
    - [HyperLogLog](#hyperloglog)
    - [Locality-Sensitive Hashing](#locality-sensitive-hashing)
    - [van Emde Boas Trees](#van-emde-boas-trees)
    - [Augmented Data Structures](#augmented-data-structures)
    - [Balanced search trees](#balanced-search-trees)
        - AVL trees
        - Splay trees
        - Red/black trees
        - 2-3 search trees
        - 2-3-4 Trees (aka 2-4 trees)
        - N-ary (K-ary, M-ary) trees
        - B-Trees
    - [k-D Trees](#k-d-trees)
    - [Skip lists](#skip-lists)
    - [Network Flows](#network-flows)
    - [Disjoint Sets & Union Find](#disjoint-sets--union-find)
    - [Math for Fast Processing](#math-for-fast-processing)
    - [Treap](#treap)
    - [Linear Programming](#linear-programming-videos)
    - [Geometry, Convex hull](#geometry-convex-hull-videos)
    - [Discrete math](#discrete-math)
    - [Machine Learning](#machine-learning)
- [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)
- [Video Series](#video-series)
- [Computer Science Courses](#computer-science-courses)
- [Papers](#papers)

---

## Let's Get Started

Alright, enough talk, let's learn!

But don't forget to do coding problems from above while you learn!

## Algorithmic complexity / Big-O / Asymptotic analysis

- Nothing to implement here, you're just watching videos and taking notes! Yay!
- There are a lot of videos here. Just watch enough until you understand it. You can always come back and review.
- Don't worry if you don't understand all the math behind it.
- You just need to understand how to express the complexity of an algorithm in terms of Big-O.
- [X] [Harvard CS50 - Asymptotic Notation (video)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
- [X] [Big O Notations (general quick tutorial) (video)](https://www.youtube.com/watch?v=V6mKVRU1evU)
- [X] [Cheat sheet](http://bigocheatsheet.com/)

Well, that's about enough of that. 

When you go through "Cracking the Coding Interview", there is a chapter on this, and at the end there is a quiz to see 
if you can identify the runtime complexity of different algorithms. It's a super review and test.

## Data Structures

- ### Arrays
    - [X] About Arrays:
        - [Arrays (video)](https://www.coursera.org/lecture/data-structures/arrays-OsBSF)
        - [Dynamic Arrays (video)](https://www.coursera.org/lecture/data-structures/dynamic-arrays-EwbnV)
        - [Jagged Arrays (video)](https://www.youtube.com/watch?v=1jtrQqYpt7g)
    - [X] Time
        - O(1) to add/remove at end (amortized for allocations for more space), index, or update
        - O(n) to insert/remove elsewhere
    - [X] Space
        - contiguous in memory, so proximity helps performance
        - space needed = (array capacity, which is >= n) * size of item, but even if 2n, still O(n)

- ### Linked Lists
    - [X] Description:
        - [X] [Singly Linked Lists (video)](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
    - [X] [C Code] not the whole video, just portions about Node struct and memory allocation
    - [X] Linked List vs Arrays:
        - [Core Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-linked-lists-vs-arrays-rjBs9)
        - [In The Real World Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/in-the-real-world-lists-vs-arrays-QUaUd)
    - [X] [why you should avoid linked lists (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
    - [X] Gotcha: you need pointer to pointer knowledge:
        (for when you pass a pointer to a function that may change the address where that pointer points)
        This page is just to get a grasp on ptr to ptr. I don't recommend this list traversal style. Readability and maintainability suffer due to cleverness.
        - [Pointers to Pointers](https://www.eskimo.com/~scs/cclass/int/sx8.html)
    - [X] Implement (I did with tail pointer & without):
    - [X] Doubly-linked List
        - [Description (video)](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
        - No need to implement

- ### Stack
    - [X] [Stacks (video)](https://www.coursera.org/lecture/data-structures/stacks-UdKzQ)
    - [X] Will not implement. Implementing with array is trivial

- ### Queue
    - [X] [Queue (video)](https://www.coursera.org/lecture/data-structures/queues-EShpq)
    - [X] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
    - [X] Implement using linked-list, with tail pointer:
        - enqueue(value) - adds value at position at tail
        - dequeue() - returns value and removes least recently added element (front)
        - empty()
    - [X] Implement using fixed-sized array:
        - enqueue(value) - adds item at end of available storage
        - dequeue() - returns value and removes least recently added element
        - empty()
        - full()
    - [X] Cost:
        - a bad implementation using linked list where you enqueue at head and dequeue at tail would be O(n)
            because you'd need the next to last element, causing a full traversal each dequeue
        - enqueue: O(1) (amortized, linked list and array [probing])
        - dequeue: O(1) (linked list and array)
        - empty: O(1) (linked list and array)

- ### Hash table
    - [X] Videos:
        - [X] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
        - [X] [PyCon 2017: The Dictionary Even Mightier (video)](https://www.youtube.com/watch?v=66P5FMkWoVU)
    - [X] Online Courses:
        - [X] [Core Hash Tables (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-hash-tables-m7UuP)
        - [X] distributed hash tables:
            - [X] [Instant Uploads And Storage Optimization In Dropbox (video)](https://www.coursera.org/lecture/data-structures/instant-uploads-and-storage-optimization-in-dropbox-DvaIb)
            - [X] [Distributed Hash Tables (video)](https://www.coursera.org/lecture/data-structures/distributed-hash-tables-tvH8H)

    - [X] Implement with array using linear probing
        - hash(k, m) - m is size of hash table
        - add(key, value) - if key already exists, update value
        - exists(key)
        - get(key)
        - remove(key)

## More Knowledge

- ### Binary search
    - [X] [Binary Search (video)](https://www.youtube.com/watch?v=D5SrAga1pno)
    - [X] [detail](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search/)
    - [X] Implement:
        - binary search (on sorted array of integers)
        - binary search using recursion

- ### Bitwise operations
    - [X] [Bits cheat sheet](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/bits-cheat-sheet.pdf) - you should know many of the powers of 2 from (2^1 to 2^16 and 2^32)
    - [X] Get a really good understanding of manipulating bits with: &, |, ^, ~, >>, <<
        - [X] [words](https://en.wikipedia.org/wiki/Word_(computer_architecture))
        - [X] Good intro:
            [Bit Manipulation (video)](https://www.youtube.com/watch?v=7jkIUgLC29I)
        - [X] [C Programming Tutorial 2-10: Bitwise Operators (video)](https://www.youtube.com/watch?v=d0AwjSpNXR0)
        - [X] [Bit Manipulation](https://en.wikipedia.org/wiki/Bit_manipulation)
        - [X] [Bitwise Operation](https://en.wikipedia.org/wiki/Bitwise_operation)
        - [X] [Bithacks](https://graphics.stanford.edu/~seander/bithacks.html)
        - [X] [The Bit Twiddler](https://en.wikipedia.org/wiki/Bit_twiddler)
		- [X] [Practice Operations](https://pconrad.github.io/old_pconrad_cs16/topics/bitOps/)
    - [X] 2s and 1s complement
        - [Binary: Plusses & Minuses (Why We Use Two's Complement) (video)](https://www.youtube.com/watch?v=lKTsv6iVxV4)
    - [X] Count set bits
        - [Count Bits](https://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan)
    - [X] Swap values:
        - [Swap](https://bits.stephan-brumme.com/swap.html)
    - [X] Absolute value:
        - [Absolute Integer](https://bits.stephan-brumme.com/absInteger.html)

## Trees

- ### Trees - Notes & Background
    - [X] [Series: Trees (video)](https://www.coursera.org/lecture/data-structures/trees-95qda)
    - basic tree construction
    - traversal
    - manipulation algorithms
    - [X] [BFS(breadth-first search) and DFS(depth-first search) (video)](https://www.youtube.com/watch?v=uWL6FJhq5fM)
        - BFS notes:
           - level order (BFS, using queue)
           - time complexity: O(n)
           - space complexity: best: O(1), worst: O(n/2)=O(n)
        - DFS notes:
            - time complexity: O(n)
            - space complexity:
                best: O(log n) - avg. height of tree
                worst: O(n)
            - inorder (DFS: left, self, right)
            - postorder (DFS: left, right, self)
            - preorder (DFS: self, left, right)

- ### Binary search trees: BSTs
    - [X] [Binary Search Tree Review (video)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)    
    - [X] Implement:
        - [X] insert    // insert value into tree
        - [X] get_node_count // get count of values stored
        - [X] print_values // prints the values in the tree, from min to max
        - [X] delete_tree
        - [X] is_in_tree // returns true if given value exists in the tree
        - [X] get_height // returns the height in nodes (single node's height is 1)
        - [X] get_min   // returns the minimum value stored in the tree
        - [X] get_max   // returns the maximum value stored in the tree
        - [X] is_binary_search_tree
        - [X] delete_value
        - [X] get_successor // returns next-highest value in tree after given value, -1 if none

- ### Heap / Priority Queue / Binary Heap
    - visualized as a tree, but is usually linear in storage (array, linked list)
    - [X] [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure))
    - [X] [Heap Sort - jumps to start (video)](https://youtu.be/odNJmw5TOEE?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3291)
    - [X] [CS 61B Lecture 24: Priority Queues (video)](https://archive.org/details/ucberkeley_webcast_yIUFT6AKBGE)
    - [X] [Linear Time BuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
    - [X] Implement a max-heap:
        - [X] insert
        - [X] sift_up - needed for insert
        - [X] get_max - returns the max item, without removing it
        - [X] get_size() - return number of elements stored
        - [X] is_empty() - returns true if heap contains no elements
        - [X] extract_max - returns the max item, removing it
        - [ ] sift_down - needed for extract_max
        - [X] remove(i) - removes item at index x
        - [X] heapify - create a heap from an array of elements, needed for heap_sort
        - [X] heap_sort() - take an unsorted array and turn it into a sorted array in-place using a max heap or min heap

## Sorting

- [X] Notes:
    - Implement sorts & know best case/worst case, average complexity of each:
        - no bubble sort - it's terrible - O(n^2), except when n <= 16
    - [X] Stability in sorting algorithms ("Is Quicksort stable?")
        - [Stability In Sorting Algorithms](http://stackoverflow.com/questions/1517793/stability-in-sorting-algorithms)
    - [X] Which algorithms can be used on linked lists? Which on arrays? Which on both?
        - I wouldn't recommend sorting a linked list, but merge sort is doable.
        - [Merge Sort For Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)

- For heapsort, see Heap data structure above. Heap sort is great, but not stable

- [X] [Bubble Sort (video)](https://www.youtube.com/watch?v=P00xJgWzz2c&index=1&list=PL89B61F78B552C1AB)
- [X] [Insertion Sort (video)](https://www.youtube.com/watch?v=c4BRHC7kTaQ&index=2&list=PL89B61F78B552C1AB)
- [X] [Merge Sort (video)](https://www.youtube.com/watch?v=GCae1WNvnZM&index=3&list=PL89B61F78B552C1AB)
- [X] [Quicksort (video)](https://www.youtube.com/watch?v=y_G9BkAm6B8&index=4&list=PL89B61F78B552C1AB)
- [X] [Selection Sort (video)](https://www.youtube.com/watch?v=6nDMgr0-Yyo&index=8&list=PL89B61F78B552C1AB)

- [X] Merge sort code:
    - [X] [Using output array (Python)](https://github.com/jwasham/practice-python/blob/master/merge_sort/merge_sort.py)
- [X] Quick sort code:
    - [X] [Implementation (Python)](https://github.com/jwasham/practice-python/blob/master/quick_sort/quick_sort.py)

- [X] Implement:
    - [X] Mergesort: O(n log n) average and worst case
    - [X] Quicksort O(n log n) average case
    - [X] Selection sort and insertion sort are both O(n^2) average and worst case
    - [X] For heapsort, see Heap data structure above

- [X] Not required, but I recommended them:
    - [X] [Radix Sort (video)](https://www.youtube.com/watch?v=xhr26ia4k38)
As a summary, here is a visual representation of [15 sorting algorithms](https://www.youtube.com/watch?v=kPRA0W1kECg).
If you need more detail on this subject, see "Sorting" section in [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)

## Graphs

Graphs can be used to represent many problems in computer science, so this section is long, like trees and sorting were.

- Notes:
    - [X] There are 4 basic ways to represent a graph in memory:
        - [X] objects and pointers
        - [X] adjacency matrix
        - [X] adjacency list
        - [X] adjacency map
    - [X] Familiarize yourself with each representation and its pros & cons
    - [X] BFS and DFS - know their computational complexity, their trade offs, and how to implement them in real code
    - [X] When asked a question, look for a graph-based solution first, then move on if none

- Full Coursera Course:
    - [X] [Algorithms on Graphs (video)](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome)

- I'll implement:
    - [ ] DFS with adjacency list (recursive)
    - [ ] DFS with adjacency list (iterative with stack)
    - [ ] DFS with adjacency matrix (recursive)
    - [ ] DFS with adjacency matrix (iterative with stack)
    - [ ] BFS with adjacency list
    - [ ] BFS with adjacency matrix
    - [ ] single-source shortest path (Dijkstra)
    - [ ] minimum spanning tree
    - DFS-based algorithms (see Aduni videos above):
        - [ ] check for cycle (needed for topological sort, since we'll check for cycle before starting)
        - [ ] topological sort
        - [ ] count connected components in a graph
        - [ ] list strongly connected components
        - [ ] check for bipartite graph

## Even More Knowledge

- ### Recursion
    - [X] Stanford lectures on recursion & backtracking:
        - [X] [Lecture 8 | Programming Abstractions (video)](https://www.youtube.com/watch?v=gl3emqCuueQ&list=PLFE6E58F856038C69&index=8)
        - [X] [Lecture 9 | Programming Abstractions (video)](https://www.youtube.com/watch?v=uFJhEPrbycQ&list=PLFE6E58F856038C69&index=9)
        - [X] [Lecture 10 | Programming Abstractions (video)](https://www.youtube.com/watch?v=NdF1QDTRkck&index=10&list=PLFE6E58F856038C69)
        - [X] [Lecture 11 | Programming Abstractions (video)](https://www.youtube.com/watch?v=p-gpaIGRCQI&list=PLFE6E58F856038C69&index=11)
    - [X] When it is appropriate to use it?
    - [X] How is tail recursion better than not?
        - [X] [What Is Tail Recursion Why Is It So Bad?](https://www.quora.com/What-is-tail-recursion-Why-is-it-so-bad)
        - [X] [Tail Recursion (video)](https://www.coursera.org/lecture/programming-languages/tail-recursion-YZic1)

- ### Dynamic Programming
    - You probably won't see any dynamic programming problems in your interview, but it's worth being able to recognize a 
    problem as being a candidate for dynamic programming.
    - This subject can be pretty difficult, as each DP soluble problem must be defined as a recursion relation, and coming up with it can be tricky.
    - I suggest looking at many examples of DP problems until you have a solid understanding of the pattern involved.
    - [X] Videos:
        - [X] [Simonson: Dynamic Programming 0 (starts at 59:18) (video)](https://youtu.be/J5aJEcOr6Eo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3558)
        - [X] [Simonson: Dynamic Programming I - Lecture 11 (video)](https://www.youtube.com/watch?v=0EzHjQ_SOeU&index=11&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [X] [Simonson: Dynamic programming II - Lecture 12 (video)](https://www.youtube.com/watch?v=v1qiRwuJU7g&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=12)

- ### Design patterns
    - [X] [Quick UML review (video)](https://www.youtube.com/watch?v=3cmzqZzwNDM&list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc&index=3)
    - [X] Learn these patterns:
        - [X] strategy
        - [X] singleton
        - [X] adapter
        - [X] prototype
        - [X] decorator
        - [X] visitor
        - [X] factory
        - [X] abstract factory
        - [X] facade
        - [X] observer
        - [X] proxy
        - [X] delegate
        - [X] command
        - [X] state
        - [X] memento
        - [X] iterator
        - [X] composite
        - [X] flyweight
    - [X] [Series of videos (27 videos)](https://www.youtube.com/playlist?list=PLF206E906175C7E07)
    - [X] [Handy reference: 101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)
    - [X] [Design patterns for humans](https://github.com/kamranahmedse/design-patterns-for-humans#structural-design-patterns)❤️

- ### Combinatorics (n choose k) & Probability
    - [X] [Math Skills: How to find Factorial, Permutation and Combination (Choose) (video)](https://www.youtube.com/watch?v=8RRo6Ti9d0U)
    - [X] [Make School: Probability](https://www.youtube.com/watch?v=sZkAAk9Wwa4)

- ### NP, NP-Complete and Approximation Algorithms
    - [X] Know about the most famous classes of NP-complete problems, such as traveling salesman and the knapsack problem,
        and be able to recognize them when an interviewer asks you them in disguise.
    - [X] Know what NP-complete means.
    - [X] Simonson:
        - [X] [Greedy Algs. II & Intro to NP Completeness (video)](https://youtu.be/qcGnJ47Smlo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=2939)
        - [X] [NP Completeness II & Reductions (video)](https://www.youtube.com/watch?v=e0tGC6ZQdQE&index=16&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - Peter Norvig discusses near-optimal solutions to traveling salesman problem:
        - [X] [Jupyter Notebook](http://nbviewer.jupyter.org/url/norvig.com/ipython/TSP.ipynb)

- ### How computers process a program

    - [X] [How CPU executes a program (video)](https://www.youtube.com/watch?v=XM4lGflQFvA)
    - [X] [How computers calculate - ALU (video)](https://youtu.be/1I5ZMmrOfnA)
    - [X] [Registers and RAM (video)](https://youtu.be/fpnE6UAfbtU)
    - [X] [The Central Processing Unit (CPU) (video)](https://youtu.be/FZGugFqdr60)
    - [X] [Instructions and Programs (video)](https://youtu.be/zltgXvg6r3k)

- ### Caches
    - [X] LRU cache:
        - [X] [The Magic of LRU Cache (100 Days of Google Dev) (video)](https://www.youtube.com/watch?v=R5ON3iwx78M)
    - [X] CPU cache:
        - [X] [Cache memory(video)](https://www.youtube.com/watch?v=IA8au8Qr3lo)

- ### Processes and Threads
    - [X] Operating Systems:
        - [X]  short videos 
        - [X] [Operating Systems and System Programming (video)](https://www.youtube.com/watch?v=qdkxXygc3rE)
    - [X] [What Is The Difference Between A Process And A Thread?](https://www.quora.com/What-is-the-difference-between-a-process-and-a-thread)
    - Covers:
        - [X] Processes, Threads, Concurrency issues
            - [X] Difference between processes and threads
            - [X] Processes
            - [X] Threads
            - [X] Locks
            - [X] Mutexes
            - [X] Semaphores
            - [X] Monitors
            - [X] How they work?
            - [X] Deadlock
            - [X] Livelock
        - [X] interrupts
        - [X] context switching
        - [X] Modern concurrency constructs with multicore processors
        - [X] [Paging, segmentation and virtual memory (video)](https://www.youtube.com/watch?v=LKe7xK0bF7o&list=PLCiOXwirraUCBE9i_ukL8_Kfg6XNv7Se8&index=2)
        - [X] [Interrupts (video)](https://www.youtube.com/watch?v=uFKi2-J-6II&list=PLCiOXwirraUCBE9i_ukL8_Kfg6XNv7Se8&index=3)
        - [X] Process resource needs (memory: code, static storage, stack, heap, and also file descriptors, i/o)
        - [X] Thread resource needs (shares above (minus stack) with other threads in the same process but each has its own pc, stack counter, registers, and stack)
        - [X] Forking is really copy on write (read-only) until the new process writes to memory, then it does a full copy.
        - [X] How context switching is initiated by the operating system and underlying hardware?

- ### Testing
    - To cover:
        - [X] how unit testing works
        - [X] what are mock objects
        - [X] what is integration testing
        - [X] what is dependency injection
        - [X] https://www.guru99.com/software-testing-introduction-importance.html
    - [X] [Agile Software Testing with James Bach (video)](https://www.youtube.com/watch?v=SAhJf36_u5U)
    - [X] [Open Lecture by James Bach on Software Testing (video)](https://www.youtube.com/watch?v=ILkT_HV9DVU)
    - [X] [Steve Freeman - Test-Driven Development (that’s not what we meant) (video)](https://vimeo.com/83960706)
        - [slides](http://gotocon.com/dl/goto-berlin-2013/slides/SteveFreeman_TestDrivenDevelopmentThatsNotWhatWeMeant.pdf)
    - [X] Dependency injection:
        - [X] [video](https://www.youtube.com/watch?v=IKD2-MAkXyQ)
        - [X] [Tao Of Testing](http://jasonpolites.github.io/tao-of-testing/ch3-1.1.html)
    - [X] [How to write tests](http://jasonpolites.github.io/tao-of-testing/ch4-1.1.html)

- ### String searching & manipulations
    - [X] [Sedgewick - Suffix Arrays (video)](https://www.coursera.org/learn/algorithms-part2/lecture/TH18W/suffix-arrays)
    - [X] [Sedgewick - Substring Search (videos)](https://www.coursera.org/learn/algorithms-part2/home/week/4)
        - [X] [1. Introduction to Substring Search](https://www.coursera.org/learn/algorithms-part2/lecture/n3ZpG/introduction-to-substring-search)
        - [X] [2. Brute-Force Substring Search](https://www.coursera.org/learn/algorithms-part2/lecture/2Kn5i/brute-force-substring-search)
        - [X] [3. Knuth-Morris Pratt](https://www.coursera.org/learn/algorithms-part2/lecture/TAtDr/knuth-morris-pratt)
        - [X] [4. Boyer-Moore](https://www.coursera.org/learn/algorithms-part2/lecture/CYxOT/boyer-moore)
        - [X] [5. Rabin-Karp](https://www.coursera.org/learn/algorithms-part2/lecture/3KiqT/rabin-karp)
    - [X] [Search pattern in text (video)](https://www.coursera.org/learn/data-structures/lecture/tAfHI/search-pattern-in-text)

    If you need more detail on this subject, see "String Matching" section in [Additional Detail on Some Subjects](#additional-detail-on-some-subjects).

- ### Tries
    - Note there are different kinds of tries. Some have prefixes, some don't, and some use string instead of bits
        to track the path
    - [X] [Tries]
        - [X] [1. R Way Tries]
        - [X] [2. Ternary Search Tries]
        - [X] [3. Character Based Operations]
    - [X] Short course videos:
        - [X] [Introduction To Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/08Xyf/core-introduction-to-tries)
        - [X] [Performance Of Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/PvlZW/core-performance-of-tries)
        - [X] [Implementing A Trie (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/DFvd3/core-implementing-a-trie)
    - [X] [The Trie: A Neglected Data Structure](https://www.toptal.com/java/the-trie-a-neglected-data-structure)

- ### Floating Point Numbers
    - [X] simple 8-bit: [Representation of Floating Point Numbers - 1 (video - there is an error in calculations - see video description)](https://www.youtube.com/watch?v=ji3SfClm8TU)
    - [X] 32 bit: [IEEE754 32-bit floating point binary (video)](https://www.youtube.com/watch?v=AOVkS9BJDjE)

- ### Unicode
    - [X] [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets]( http://www.joelonsoftware.com/articles/Unicode.html)
    - [X] [What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](http://kunststube.net/encoding/)

- ### Endianness
    - [X] [Big And Little Endian](https://web.archive.org/web/20180107141940/http://www.cs.umd.edu:80/class/sum2003/cmsc311/Notes/Data/endian.html)
    - [X] [Big Endian Vs Little Endian (video)](https://www.youtube.com/watch?v=JrNF0KRAlyo)

- ### Networking
    - **if you have networking experience or want to be a reliability engineer or operations engineer, expect questions**
    - Otherwise, this is just good to know
    - [X] [Khan Academy](https://www.khanacademy.org/computing/code-org/computers-and-the-internet)
    - [X] [UDP and TCP: Comparison of Transport Protocols (video)](https://www.youtube.com/watch?v=Vdc8TCESIg8)
    - [X] [TCP/IP and the OSI Model Explained! (video)](https://www.youtube.com/watch?v=e5DEVa9eSN0)
    - [X] [Packet Transmission across the Internet. Networking & TCP/IP tutorial. (video)](https://www.youtube.com/watch?v=nomyRJehhnM)
    - [X] [HTTP 2.0 (video)](https://www.youtube.com/watch?v=E9FxNzv1Tr8)
    - [X] [Subnetting Demystified - Part 5 CIDR Notation (video)](https://www.youtube.com/watch?v=t5xYI0jzOf4)
    - [X] [Socket Programming (video)](https://www.pubnub.com/blog/socket-programming-in-python-client-server-p2p/)

---

## Final Review

    This section will have shorter videos that you can watch pretty quickly to review most of the important concepts.
    It's nice if you want a refresher often.

- [ ] Series of 2-3 minutes short subject videos (23 videos)
    - [Videos](https://www.youtube.com/watch?v=r4r1DZcx1cM&list=PLmVb1OknmNJuC5POdcDv5oCS7_OUkDgpj&index=22)
- [ ] Series of 2-5 minutes short subject videos - Michael Sambol (18 videos):
    - [Videos](https://www.youtube.com/channel/UCzDJwLWoYCUQowF_nG3m5OQ)
- [ ] [Sedgewick Videos - Algorithms I](https://www.coursera.org/learn/algorithms-part1)
- [ ] [Sedgewick Videos - Algorithms II](https://www.coursera.org/learn/algorithms-part2)


## Interview Process & General Interview Prep

- [X] [How to Pass the Engineering Interview in 2021](https://davidbyttow.medium.com/how-to-pass-the-engineering-interview-in-2021-45f1b389a1)
- [X] [Demystifying Tech Recruiting](https://www.youtube.com/watch?v=N233T0epWTs)
- [ ] How to Get a Job at the Big 4:
    - [ ] [How to Get a Job at the Big 4 - Amazon, Facebook, Google & Microsoft (video)](https://www.youtube.com/watch?v=YJZCUhxNCv8)
    - [ ] [How to Get a Job at the Big 4.1 (Follow-up video)](https://www.youtube.com/watch?v=6790FVXWBw8&feature=youtu.be)
- [ ] Cracking The Coding Interview Set 1:
    - [ ] [Gayle L McDowell - Cracking The Coding Interview (video)](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
    - [ ] [Cracking the Coding Interview with Author Gayle Laakmann McDowell (video)](https://www.youtube.com/watch?v=aClxtDcdpsQ)
- [ ] Cracking the Facebook Coding Interview:
    - [ ] [The Approach](https://www.youtube.com/watch?v=wCl9kvQGHPI)
    - [ ] [Problem Walkthrough](https://www.youtube.com/watch?v=4UWDyJq8jZg)
- Prep Courses:
    - [Software Engineer Interview Unleashed (paid course)](https://www.udemy.com/software-engineer-interview-unleashed):
        - Learn how to make yourself ready for software engineer interviews from a former Google interviewer.
    - [Python for Data Structures, Algorithms, and Interviews (paid course)](https://www.udemy.com/python-for-data-structures-algorithms-and-interviews/):
        - A Python centric interview prep course which covers data structures, algorithms, mock interviews and much more.
    - [Intro to Data Structures and Algorithms using Python (Udacity free course)](https://www.udacity.com/course/data-structures-and-algorithms-in-python--ud513):
        - A free Python centric data structures and algorithms course.
    - [Data Structures and Algorithms Nanodegree! (Udacity paid Nanodegree)](https://www.udacity.com/course/data-structures-and-algorithms-nanodegree--nd256):
        - Get hands-on practice with over 100 data structures and algorithm exercises and guidance from a dedicated mentor to help prepare you for interviews and on-the-job scenarios.
    - [Grokking the Behavioral Interview (Educative free course)](https://www.educative.io/courses/grokking-the-behavioral-interview):
        - Many times, it’s not your technical competency that holds you back from landing your dream job, it’s how you perform on the behavioral interview.

Mock Interviews:
- [Gainlo.co: Mock interviewers from big companies](http://www.gainlo.co/) - I used this and it helped me relax for the phone screen and on-site interview
- [Pramp: Mock interviews from/with peers](https://www.pramp.com/) - peer-to-peer model of practice interviews
- [interviewing.io: Practice mock interview with senior engineers](https://interviewing.io) - anonymous algorithmic/systems design interviews with senior engineers from FAANG anonymously

## Be thinking of for when the interview comes

Think of about 20 interview questions you'll get, along with the lines of the items below. Have at least one answer for each.
Have a story, not just data, about something you accomplished.

- Why do you want this job?
- What's a tough problem you've solved?
- Biggest challenges faced?
- Best/worst designs seen?
- Ideas for improving an existing product
- How do you work best, as an individual and as part of a team?
- Which of your skills or experiences would be assets in the role and why?
- What did you most enjoy at [job x / project y]?
- What was the biggest challenge you faced at [job x / project y]?
- What was the hardest bug you faced at [job x / project y]?
- What did you learn at [job x / project y]?
- What would you have done better at [job x / project y]?

- If you find it hard to come up with good answers of these types of interview questions, here are some ideas: 
    - [General Interview Questions and their Answers](https://ayedot.com/119/MiniBlog/General-Interview-Questions-and-their-Answers-for-Tech-Jobs)

## Have questions for the interviewer

Some of mine (I already may know the answers, but want their opinion or team perspective):

- How large is your team?
- What does your dev cycle look like? Do you do waterfall/sprints/agile?
- Are rushes to deadlines common? Or is there flexibility?
- How are decisions made in your team?
- How many meetings do you have per week?
- Do you feel your work environment helps you concentrate?
- What are you working on?
- What do you like about it?
- What is the work life like?
- How is the work/life balance?

## Once You've Got The Job

Congratulations!

Keep learning.

You're never really done.

---

    *****************************************************************************************************
    *****************************************************************************************************

    Everything below this point is optional. It is NOT needed for an entry-level interview.
    However, by studying these, you'll get greater exposure to more CS concepts, and will be better prepared for
    any software engineering job. You'll be a much more well-rounded software engineer.
    
    *****************************************************************************************************
    *****************************************************************************************************

---

## System Design, Scalability, Data Handling

**You can expect system design questions if you have 4+ years of experience.**

- Scalability and System Design are very large topics with many topics and resources, since
      there is a lot to consider when designing a software/hardware system that can scale.
      Expect to spend quite a bit of time on this
- Considerations:
    - Scalability
        - Distill large data sets to single values
        - Transform one data set to another
        - Handling obscenely large amounts of data
    - System design
        - features sets
        - interfaces
        - class hierarchies
        - designing a system under certain constraints
        - simplicity and robustness
        - tradeoffs
        - performance analysis and optimization
- [X] **START HERE**: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [X] [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
- [X] [How Do I Prepare To Answer Design Questions In A Technical Interview?](https://www.quora.com/How-do-I-prepare-to-answer-design-questions-in-a-technical-interview?redirected_qid=1500023)
- [X] [8 Things You Need to Know Before a System Design Interview](http://blog.gainlo.co/index.php/2015/10/22/8-things-you-need-to-know-before-system-design-interviews/)
- [X] [Database Normalization - 1NF, 2NF, 3NF and 4NF (video)](https://www.youtube.com/watch?v=UrYLYV7WSHM)
- [X] [System Design Interview](https://github.com/checkcheckzz/system-design-interview) - There are a lot of resources in this one. Look through the articles and examples. I put some of them below
- [X] [Numbers Everyone Should Know](http://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
- [X] [How long does it take to make a context switch?](http://blog.tsunanet.net/2010/11/how-long-does-it-take-to-make-context.html)
- [X] [Transactions Across Datacenters (video)](https://www.youtube.com/watch?v=srOgpXECblk)
- [X] [A plain English introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
- [X] [Distributed Systems](https://www.youtube.com/playlist?list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB)
- [X] Consensus Algorithms:
    - [X] Paxos - [Paxos Agreement - Computerphile (video)](https://www.youtube.com/watch?v=s8JqcZtvnsM)
    - [X] Raft - [An Introduction to the Raft Distributed Consensus Algorithm (video)](https://www.youtube.com/watch?v=P9Ydif5_qvE)
        - [X] [Easy-to-read paper](https://raft.github.io/)
        - [X] [Infographic](http://thesecretlivesofdata.com/raft/) ❤️
- [X] [Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
- [X] [NoSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [X] [NoSQL overview](https://www.youtube.com/watch?v=0buKQHokLK8)
- [X] Scalability:
    - You don't need all of these. Just pick a few that interest you.
    - [X] [Great overview (video)](https://www.youtube.com/watch?v=-W9F__D3oY4)
    - [X] Short series:
        - [X] [Clones](http://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
        - [X] [Database](http://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
        - [X] [Cache](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
        - [X] [Asynchronism](http://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)
    - [ ] [Fallacies of Distributed Computing Explained](https://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf)
    - [ ] [Introduction to Architecting Systems for Scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
    - [ ] [How Google Does Planet-Scale Engineering for Planet-Scale Infra (video)](https://www.youtube.com/watch?v=H4vMcD7zKM0)
    - [ ] [The Importance of Algorithms](https://www.topcoder.com/community/competitive-programming/tutorials/the-importance-of-algorithms/)
    - [ ] [Sharding](http://highscalability.com/blog/2009/8/6/an-unorthodox-approach-to-database-design-the-coming-of-the.html)
    - [ ] [Engineering for the Long Game - Astrid Atkinson Keynote(video)](https://www.youtube.com/watch?v=p0jGmgIrf_M&list=PLRXxvay_m8gqVlExPC5DG3TGWJTaBgqSA&index=4)
    - [ ] [7 Years Of YouTube Scalability Lessons In 30 Minutes](http://highscalability.com/blog/2012/3/26/7-years-of-youtube-scalability-lessons-in-30-minutes.html)
    - [ ] [video](https://www.youtube.com/watch?v=G-lGCC4KKok)
    - [X] [How to Remove Duplicates in Large Datasets](https://blog.clevertap.com/how-to-remove-duplicates-in-large-datasets/)
    - [X] [What Led Amazon to its Own Microservices Architecture](http://thenewstack.io/led-amazon-microservices-architecture/)
    - [X] [Google's Transition From Single Datacenter, To Failover, To A Native Multihomed Architecture]( http://highscalability.com/blog/2016/2/23/googles-transition-from-single-datacenter-to-failover-to-a-n.html)
    - [X] [A Patreon Architecture Short](http://highscalability.com/blog/2016/2/1/a-patreon-architecture-short.html)
    - [X] [Tinder: How Does One Of The Largest Recommendation Engines Decide Who You'll See Next?](http://highscalability.com/blog/2016/1/27/tinder-how-does-one-of-the-largest-recommendation-engines-de.html)
    - [ ] [Design Of A Modern Cache](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)
    - [X] [A Beginner's Guide To Scaling To 11 Million+ Users On Amazon's AWS](http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html)
    - [X] [A 360 Degree View Of The Entire Netflix Stack](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)
    - [ ] [Latency Is Everywhere And It Costs You Sales - How To Crush It](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)
    - [X] [What Powers Instagram: Hundreds of Instances, Dozens of Technologies](http://instagram-engineering.tumblr.com/post/13649370142/what-powers-instagram-hundreds-of-instances)
    - [ ] [O'Reilly MySQL CE 2011: Jeremy Cole, "Big and Small Data at @Twitter" (video)](https://www.youtube.com/watch?v=5cKTP36HVgI)
    - [X] review: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
    - [X] [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
    - [X] [cheat sheet](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/system-design.pdf)
    - Exercises:
        - [ ] [Design a random unique ID generation system](https://blog.twitter.com/2010/announcing-snowflake)
        - [ ] [Design a key-value database](http://www.slideshare.net/dvirsky/introduction-to-redis)
        - [ ] [Design a picture sharing system](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
        - [ ] [Design a recommendation system](http://ijcai13.org/files/tutorial_slides/td3.pdf)
        - [ ] [Design a URL-shortener system: copied from above](http://www.hiredintech.com/system-design/the-system-design-process/)
        - [ ] [Design a cache system](https://www.adayinthelifeof.nl/2011/02/06/memcache-internals/)

## Additional Learning

    I added them to help you become a well-rounded software engineer, and to be aware of certain
    technologies and algorithms, so you'll have a bigger toolbox.

- ### Compilers
    - [How a Compiler Works in ~1 minute (video)](https://www.youtube.com/watch?v=IhC7sdYe-Jg)
    - [Harvard CS50 - Compilers (video)](https://www.youtube.com/watch?v=CSZLNYF4Klo)
    - [C++ (video)](https://www.youtube.com/watch?v=twodd1KFfGk)
    - [Understanding Compiler Optimization (C++) (video)](https://www.youtube.com/watch?v=FnGCDLhaxKU)

- ### Emacs and vi(m)
    - Familiarize yourself with a unix-based code editor
    - vi(m):
        - [Editing With vim 01 - Installation, Setup, and The Modes (video)](https://www.youtube.com/watch?v=5givLEMcINQ&index=1&list=PL13bz4SHGmRxlZVmWQ9DvXo1fEg4UdGkr)
        - [VIM Adventures](http://vim-adventures.com/)
        - set of 4 videos:
            - [The vi/vim editor - Lesson 1](https://www.youtube.com/watch?v=SI8TeVMX8pk)
            - [The vi/vim editor - Lesson 2](https://www.youtube.com/watch?v=F3OO7ZIOaJE)
            - [The vi/vim editor - Lesson 3](https://www.youtube.com/watch?v=ZYEccA_nMaI)
            - [The vi/vim editor - Lesson 4](https://www.youtube.com/watch?v=1lYD5gwgZIA)
        - [Using Vi Instead of Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Using_Vi_instead_of_Emacs)
    - emacs:
        - [Basics Emacs Tutorial (video)](https://www.youtube.com/watch?v=hbmV1bnQ-i0)
        - set of 3 (videos):
            - [Emacs Tutorial (Beginners) -Part 1- File commands, cut/copy/paste, cursor commands](https://www.youtube.com/watch?v=ujODL7MD04Q)
            - [Emacs Tutorial (Beginners) -Part 2- Buffer management, search, M-x grep and rgrep modes](https://www.youtube.com/watch?v=XWpsRupJ4II)
            - [Emacs Tutorial (Beginners) -Part 3- Expressions, Statements, ~/.emacs file and packages](https://www.youtube.com/watch?v=paSgzPso-yc)
        - [Evil Mode: Or, How I Learned to Stop Worrying and Love Emacs (video)](https://www.youtube.com/watch?v=JWD1Fpdd4Pc)
        - [Writing C Programs With Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Writing_C_programs_with_Emacs)
        - [(maybe) Org Mode In Depth: Managing Structure (video)](https://www.youtube.com/watch?v=nsGYet02bEk)

- ### Unix command line tools
    - I filled in the list below from good tools.
    - bash
    - cat
    - grep
    - sed
    - awk
    - curl or wget
    - sort
    - tr
    - uniq
    - [strace](https://en.wikipedia.org/wiki/Strace)
    - [tcpdump](https://danielmiessler.com/study/tcpdump/)

- ### Information theory (videos)
    - [Khan Academy](https://www.khanacademy.org/computing/computer-science/informationtheory)
    - More about Markov processes:
        - [Core Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/waxgx/core-markov-text-generation)
        - [Core Implementing Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/gZhiC/core-implementing-markov-text-generation)
        - [Project = Markov Text Generation Walk Through](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/EUjrq/project-markov-text-generation-walk-through)
    - See more in MIT 6.050J Information and Entropy series below

- ### Parity & Hamming Code (videos)
    - [Intro](https://www.youtube.com/watch?v=q-3BctoUpHE)
    - [Parity](https://www.youtube.com/watch?v=DdMcAUlxh1M)
    - Hamming Code:
        - [Error detection](https://www.youtube.com/watch?v=1A_NcXxdoCc)
        - [Error correction](https://www.youtube.com/watch?v=JAMLuxdHH8o)
    - [Error Checking](https://www.youtube.com/watch?v=wbH2VxzmoZk)

- ### Entropy
    - Also see videos below
    - Make sure to watch information theory videos first
    - [Information Theory, Claude Shannon, Entropy, Redundancy, Data Compression & Bits (video)](https://youtu.be/JnJq3Py0dyM?t=176)

- ### Cryptography
    - Also see videos below
    - Make sure to watch information theory videos first
    - [Khan Academy Series](https://www.khanacademy.org/computing/computer-science/cryptography)
    - [Cryptography: Hash Functions](https://www.youtube.com/watch?v=KqqOXndnvic&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=30)
    - [Cryptography: Encryption](https://www.youtube.com/watch?v=9TNI2wHmaeI&index=31&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- ### Compression
    - Make sure to watch information theory videos first
    - Computerphile (videos):
        - [Compression](https://www.youtube.com/watch?v=Lto-ajuqW3w)
        - [Entropy in Compression](https://www.youtube.com/watch?v=M5c_RFKVkko)
        - [Upside Down Trees (Huffman Trees)](https://www.youtube.com/watch?v=umTbivyJoiI)
        - [EXTRA BITS/TRITS - Huffman Trees](https://www.youtube.com/watch?v=DV8efuB3h2g)
        - [Elegant Compression in Text (The LZ 77 Method)](https://www.youtube.com/watch?v=goOa3DGezUA)
        - [Text Compression Meets Probabilities](https://www.youtube.com/watch?v=cCDCfoHTsaU)
    - [Compressor Head videos](https://www.youtube.com/playlist?list=PLOU2XLYxmsIJGErt5rrCqaSGTMyyqNt2H)
    - [(optional) Google Developers Live: GZIP is not enough!](https://www.youtube.com/watch?v=whGwm0Lky2s)

- ### Computer Security
    - [MIT (23 videos)](https://www.youtube.com/playlist?list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Introduction, Threat Models](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Control Hijacking Attacks](https://www.youtube.com/watch?v=6bwzNg5qQ0o&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=2)
        - [Buffer Overflow Exploits and Defenses](https://www.youtube.com/watch?v=drQyrzRoRiA&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=3)
        - [Privilege Separation](https://www.youtube.com/watch?v=6SIJmoE9L9g&index=4&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Capabilities](https://www.youtube.com/watch?v=8VqTSY-11F4&index=5&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Sandboxing Native Code](https://www.youtube.com/watch?v=VEV74hwASeU&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=6)
        - [Web Security Model](https://www.youtube.com/watch?v=chkFBigodIw&index=7&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Securing Web Applications](https://www.youtube.com/watch?v=EBQIGy1ROLY&index=8&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Symbolic Execution](https://www.youtube.com/watch?v=yRVZPvHYHzw&index=9&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Network Security](https://www.youtube.com/watch?v=SIEVvk3NVuk&index=11&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Network Protocols](https://www.youtube.com/watch?v=QOtA76ga_fY&index=12&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Side-Channel Attacks](https://www.youtube.com/watch?v=PuVMkSEcPiI&index=15&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- ### Garbage collection
    - [GC in Python (video)](https://www.youtube.com/watch?v=iHVs_HkjdmI)
    - [Deep Dive Java: Garbage Collection is Good!](https://www.infoq.com/presentations/garbage-collection-benefits)
    - [Deep Dive Python: Garbage Collection in CPython (video)](https://www.youtube.com/watch?v=P-8Z0-MhdQs&list=PLdzf4Clw0VbOEWOS_sLhT_9zaiQDrS5AR&index=3)

- ### Parallel Programming
    - [Coursera (Scala)](https://www.coursera.org/learn/parprog1/home/week/1)
    - [Efficient Python for High Performance Parallel Computing (video)](https://www.youtube.com/watch?v=uY85GkaYzBk)

- ### Messaging, Serialization, and Queueing Systems
    - [Thrift](https://thrift.apache.org/)
        - [Tutorial](http://thrift-tutorial.readthedocs.io/en/latest/intro.html)
    - [Protocol Buffers](https://developers.google.com/protocol-buffers/)
        - [Tutorials](https://developers.google.com/protocol-buffers/docs/tutorials)
    - [gRPC](http://www.grpc.io/)
        - [gRPC 101 for Java Developers (video)](https://www.youtube.com/watch?v=5tmPvSe7xXQ&list=PLcTqM9n_dieN0k1nSeN36Z_ppKnvMJoly&index=1)
    - [Redis](http://redis.io/)
        - [Tutorial](http://try.redis.io/)
    - [Amazon SQS (queue)](https://aws.amazon.com/sqs/)
    - [Amazon SNS (pub-sub)](https://aws.amazon.com/sns/)
    - [RabbitMQ](https://www.rabbitmq.com/)
        - [Get Started](https://www.rabbitmq.com/getstarted.html)
    - [Celery](http://www.celeryproject.org/)
        - [First Steps With Celery](http://docs.celeryproject.org/en/latest/getting-started/first-steps-with-celery.html)
    - [ZeroMQ](http://zeromq.org/)
        - [Intro - Read The Manual](http://zeromq.org/intro:read-the-manual)
    - [ActiveMQ](http://activemq.apache.org/)
    - [Kafka](http://kafka.apache.org/documentation.html#introduction)
    - [MessagePack](http://msgpack.org/index.html)
    - [Avro](https://avro.apache.org/)

- ### A*
    - [A Search Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
    - [A* Pathfinding Tutorial (video)](https://www.youtube.com/watch?v=KNXfSOx4eEE)
    - [A* Pathfinding (E01: algorithm explanation) (video)](https://www.youtube.com/watch?v=-L-WgKMFuhE)

- ### Fast Fourier Transform
    - [An Interactive Guide To The Fourier Transform](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/)
    - [What is a Fourier transform? What is it used for?](http://www.askamathematician.com/2012/09/q-what-is-a-fourier-transform-what-is-it-used-for/)
    - [What is the Fourier Transform? (video)](https://www.youtube.com/watch?v=Xxut2PN-V8Q)
    - [Divide & Conquer: FFT (video)](https://www.youtube.com/watch?v=iTMn0Kt18tg&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=4)
    - [Understanding The FFT](http://jakevdp.github.io/blog/2013/08/28/understanding-the-fft/)

- ### Bloom Filter
    - Given a Bloom filter with m bits and k hashing functions, both insertion and membership testing are O(k)
    - [Bloom Filters (video)](https://www.youtube.com/watch?v=-SuTGoFYjZs)
    - [Bloom Filters | Mining of Massive Datasets | Stanford University (video)](https://www.youtube.com/watch?v=qBTdukbzc78)
    - [Tutorial](http://billmill.org/bloomfilter-tutorial/)
    - [How To Write A Bloom Filter App](http://blog.michaelschmatz.com/2016/04/11/how-to-write-a-bloom-filter-cpp/)

- ### HyperLogLog
    - [How To Count A Billion Distinct Objects Using Only 1.5KB Of Memory](http://highscalability.com/blog/2012/4/5/big-data-counting-how-to-count-a-billion-distinct-objects-us.html)

- ### Locality-Sensitive Hashing
    - Used to determine the similarity of documents
    - The opposite of MD5 or SHA which are used to determine if 2 documents/strings are exactly the same
    - [Simhashing (hopefully) made simple](http://ferd.ca/simhashing-hopefully-made-simple.html)

- ### van Emde Boas Trees
    - [Divide & Conquer: van Emde Boas Trees (video)](https://www.youtube.com/watch?v=hmReJCupbNU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=6)
    - [MIT Lecture Notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2012/lecture-notes/MIT6_046JS12_lec15.pdf)

- ### Augmented Data Structures
    - [CS 61B Lecture 39: Augmenting Data Structures](https://archive.org/details/ucberkeley_webcast_zksIj9O8_jc)

- ### Balanced search trees
    - Know at least one type of balanced binary tree (and know how it's implemented):
    - "Among balanced search trees, AVL and 2/3 trees are now passé, and red-black trees seem to be more popular.
        A particularly interesting self-organizing data structure is the splay tree, which uses rotations
        to move any accessed key to the root." - Skiena
    - Of these, I chose to implement a splay tree. From what I've read, you won't implement a
        balanced search tree in your interview. But I wanted exposure to coding one up
        and let's face it, splay trees are the bee's knees. I did read a lot of red-black tree code
        - Splay tree: insert, search, delete functions
        If you end up implementing red/black tree try just these:
        - Search and insertion functions, skipping delete
    - I want to learn more about B-Tree since it's used so widely with very large data sets
    - [Self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)

    - **AVL trees**
        - In practice:
            From what I can tell, these aren't used much in practice, but I could see where they would be:
            The AVL tree is another structure supporting O(log n) search, insertion, and removal. It is more rigidly
            balanced than red–black trees, leading to slower insertion and removal but faster retrieval. This makes it
            attractive for data structures that may be built once and loaded without reconstruction, such as language
            dictionaries (or program dictionaries, such as the opcodes of an assembler or interpreter)
        - [MIT AVL Trees / AVL Sort (video)](https://www.youtube.com/watch?v=FNeL18KsWPc&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=6)
        - [AVL Trees (video)](https://www.coursera.org/learn/data-structures/lecture/Qq5E0/avl-trees)
        - [AVL Tree Implementation (video)](https://www.coursera.org/learn/data-structures/lecture/PKEBC/avl-tree-implementation)
        - [Split And Merge](https://www.coursera.org/learn/data-structures/lecture/22BgE/split-and-merge)

    - **Splay trees**
        - In practice:
            Splay trees are typically used in the implementation of caches, memory allocators, routers, garbage collectors,
            data compression, ropes (replacement of string used for long text strings), in Windows NT (in the virtual memory,
            networking and file system code) etc
        - [CS 61B: Splay Trees (video)](https://archive.org/details/ucberkeley_webcast_G5QIXywcJlY)
        - MIT Lecture: Splay Trees:
            - Gets very mathy, but watch the last 10 minutes for sure.
            - [Video](https://www.youtube.com/watch?v=QnPl_Y6EqMo)

    - **Red/black trees**
        - These are a translation of a 2-3 tree (see below).
        - In practice:
            Red–black trees offer worst-case guarantees for insertion time, deletion time, and search time.
            Not only does this make them valuable in time-sensitive applications such as real-time applications,
            but it makes them valuable building blocks in other data structures which provide worst-case guarantees;
            for example, many data structures used in computational geometry can be based on red–black trees, and
            the Completely Fair Scheduler used in current Linux kernels uses red–black trees. In the version 8 of Java,
            the Collection HashMap has been modified such that instead of using a LinkedList to store identical elements with poor
            hashcodes, a Red-Black tree is used
        - [Aduni - Algorithms - Lecture 4 (link jumps to starting point) (video)](https://youtu.be/1W3x0f_RmUo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3871)
        - [Aduni - Algorithms - Lecture 5 (video)](https://www.youtube.com/watch?v=hm2GHwyKF1o&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=5)
        - [Red-Black Tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
        - [An Introduction To Binary Search And Red Black Tree](https://www.topcoder.com/community/competitive-programming/tutorials/an-introduction-to-binary-search-and-red-black-trees/)

    - **2-3 search trees**
        - In practice:
            2-3 trees have faster inserts at the expense of slower searches (since height is more compared to AVL trees).
        - You would use 2-3 tree very rarely because its implementation involves different types of nodes. Instead, people use Red Black trees.
        - [23-Tree Intuition and Definition (video)](https://www.youtube.com/watch?v=C3SsdUqasD4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=2)
        - [Binary View of 23-Tree](https://www.youtube.com/watch?v=iYvBtGKsqSg&index=3&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [2-3 Trees (student recitation) (video)](https://www.youtube.com/watch?v=TOb1tuEZ2X4&index=5&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

    - **2-3-4 Trees (aka 2-4 trees)**
        - In practice:
            For every 2-4 tree, there are corresponding red–black trees with data elements in the same order. The insertion and deletion
            operations on 2-4 trees are also equivalent to color-flipping and rotations in red–black trees. This makes 2-4 trees an
            important tool for understanding the logic behind red–black trees, and this is why many introductory algorithm texts introduce
            2-4 trees just before red–black trees, even though **2-4 trees are not often used in practice**.
        - [CS 61B Lecture 26: Balanced Search Trees (video)](https://archive.org/details/ucberkeley_webcast_zqrqYXkth6Q)
        - [Bottom Up 234-Trees (video)](https://www.youtube.com/watch?v=DQdMYevEyE4&index=4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [Top Down 234-Trees (video)](https://www.youtube.com/watch?v=2679VQ26Fp4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=5)

    - **N-ary (K-ary, M-ary) trees**
        - note: the N or K is the branching factor (max branches)
        - binary trees are a 2-ary tree, with branching factor = 2
        - 2-3 trees are 3-ary
        - [K-Ary Tree](https://en.wikipedia.org/wiki/K-ary_tree)

    - **B-Trees**
        - Fun fact: it's a mystery, but the B could stand for Boeing, Balanced, or Bayer (co-inventor).
        - In Practice:
            B-Trees are widely used in databases. Most modern filesystems use B-trees (or Variants). In addition to
            its use in databases, the B-tree is also used in filesystems to allow quick random access to an arbitrary
            block in a particular file. The basic problem is turning the file block i address into a disk block
            (or perhaps to a cylinder-head-sector) address
        - [B-Tree](https://en.wikipedia.org/wiki/B-tree)
        - [B-Tree Datastructure](http://btechsmartclass.com/data_structures/b-trees.html)
        - [Introduction to B-Trees (video)](https://www.youtube.com/watch?v=I22wEC1tTGo&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=6)
        - [B-Tree Definition and Insertion (video)](https://www.youtube.com/watch?v=s3bCdZGrgpA&index=7&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [B-Tree Deletion (video)](https://www.youtube.com/watch?v=svfnVhJOfMc&index=8&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [MIT 6.851 - Memory Hierarchy Models (video)](https://www.youtube.com/watch?v=V3omVLzI0WE&index=7&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)
                - covers cache-oblivious B-Trees, very interesting data structures
                - the first 37 minutes are very technical, may be skipped (B is block size, cache line size)


- ### k-D Trees
    - Great for finding number of points in a rectangle or higher dimension object
    - A good fit for k-nearest neighbors
    - [Kd Trees (video)](https://www.youtube.com/watch?v=W94M9D_yXKk)
    - [kNN K-d tree algorithm (video)](https://www.youtube.com/watch?v=Y4ZgLlDfKDg)

- ### Skip lists
    - "These are somewhat of a cult data structure" - Skiena
    - [Randomization: Skip Lists (video)](https://www.youtube.com/watch?v=2g9OSRKJuzM&index=10&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [For animations and a little more detail](https://en.wikipedia.org/wiki/Skip_list)

- ### Network Flows
    - [Ford-Fulkerson in 5 minutes — Step by step example (video)](https://www.youtube.com/watch?v=Tl90tNtKvxs)
    - [Ford-Fulkerson Algorithm (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [Network Flows (video)](https://www.youtube.com/watch?v=2vhN4Ice5jI)

- ### Disjoint Sets & Union Find
    - [UCB 61B - Disjoint Sets; Sorting & selection (video)](https://archive.org/details/ucberkeley_webcast_MAEGXTwmUsI)
    - [Sedgewick Algorithms - Union-Find (6 videos)](https://www.coursera.org/learn/algorithms-part1/home/week/1)

- ### Math for Fast Processing
    - [Integer Arithmetic, Karatsuba Multiplication (video)](https://www.youtube.com/watch?v=eCaXlAaN2uE&index=11&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [The Chinese Remainder Theorem (used in cryptography) (video)](https://www.youtube.com/watch?v=ru7mWZJlRQg)

- ### Treap
    - Combination of a binary search tree and a heap
    - [Treap](https://en.wikipedia.org/wiki/Treap)
    - [Data Structures: Treaps explained (video)](https://www.youtube.com/watch?v=6podLUYinH8)
    - [Applications in set operations](https://www.cs.cmu.edu/~scandal/papers/treaps-spaa98.pdf)

- ### Linear Programming (videos)
    - [Linear Programming](https://www.youtube.com/watch?v=M4K6HYLHREQ)
    - [Finding minimum cost](https://www.youtube.com/watch?v=2ACJ9ewUC6U)
    - [Finding maximum value](https://www.youtube.com/watch?v=8AA_81xI3ik)
    - [Solve Linear Equations with Python - Simplex Algorithm](https://www.youtube.com/watch?v=44pAWI7v5Zk)

- ### Geometry, Convex hull (videos)
    - [Graph Alg. IV: Intro to geometric algorithms - Lecture 9](https://youtu.be/XIAQRlNkJAw?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3164)
    - [Geometric Algorithms: Graham & Jarvis - Lecture 10](https://www.youtube.com/watch?v=J5aJEcOr6Eo&index=10&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [Divide & Conquer: Convex Hull, Median Finding](https://www.youtube.com/watch?v=EzeYI7p9MjU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=2)

- ### Discrete math
    - [Computer Science 70, 001 - Spring 2015 - Discrete Mathematics and Probability Theory](http://www.infocobuild.com/education/audio-video-courses/computer-science/cs70-spring2015-berkeley.html)
    - [Discrete Mathematics by Shai Simonson (19 videos)](https://www.youtube.com/playlist?list=PLWX710qNZo_sNlSWRMVIh6kfTjolNaZ8t)
    - [Discrete Mathematics By IIT Ropar NPTEL](https://nptel.ac.in/courses/106/106/106106183/)

- ### Machine Learning
    - Why ML?
        - [How Google Is Remaking Itself As A Machine Learning First Company](https://backchannel.com/how-google-is-remaking-itself-as-a-machine-learning-first-company-ada63defcb70)
        - [Large-Scale Deep Learning for Intelligent Computer Systems (video)](https://www.youtube.com/watch?v=QSaZGT4-6EY)
        - [Deep Learning and Understandability versus Software Engineering and Verification by Peter Norvig](https://www.youtube.com/watch?v=X769cyzBNVw)
    - [Google's Cloud Machine learning tools (video)](https://www.youtube.com/watch?v=Ja2hxBAwG_0)
    - [Google Developers' Machine Learning Recipes (Scikit Learn & Tensorflow) (video)](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
    - [Tensorflow (video)](https://www.youtube.com/watch?v=oZikw5k_2FM)
    - [Tensorflow Tutorials](https://www.tensorflow.org/versions/r0.11/tutorials/index.html)
    - [Practical Guide to implementing Neural Networks in Python (using Theano)](http://www.analyticsvidhya.com/blog/2016/04/neural-networks-python-theano/)
    - Courses:
        - [Great starter course: Machine Learning](https://www.coursera.org/learn/machine-learning)
              - [videos only](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
              - see videos 12-18 for a review of linear algebra (14 and 15 are duplicates)
        - [Neural Networks for Machine Learning](https://www.coursera.org/learn/neural-networks)
        - [Google's Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning--ud730)
        - [Google/Kaggle Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree-by-google--nd009)
        - [Self-Driving Car Engineer Nanodegree](https://www.udacity.com/drive)
        - [Metis Online Course ($99 for 2 months)](http://www.thisismetis.com/explore-data-science)
    - Resources:
        - Books:
            - [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka/dp/1783555130/)
            - [Data Science from Scratch: First Principles with Python](https://www.amazon.com/Data-Science-Scratch-Principles-Python/dp/149190142X)
            - [Introduction to Machine Learning with Python](https://www.amazon.com/Introduction-Machine-Learning-Python-Scientists/dp/1449369413/)
        - [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
        - Data School: http://www.dataschool.io/

---

## Additional Detail on Some Subjects

    I added these to reinforce some ideas already presented above, but didn't want to include them
    above because it's just too much. It's easy to overdo it on a subject.
    You want to get hired in this century, right?

- **SOLID**   
    - [ ] [Bob Martin SOLID Principles of Object Oriented and Agile Design (video)](https://www.youtube.com/watch?v=TMuno5RZNeE)
    - [ ] S - [Single Responsibility Principle](http://www.oodesign.com/single-responsibility-principle.html) | [Single responsibility to each Object](http://www.javacodegeeks.com/2011/11/solid-single-responsibility-principle.html)
        - [more flavor](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
    - [ ] O - [Open/Closed Principle](http://www.oodesign.com/open-close-principle.html)  | [On production level Objects are ready for extension but not for modification](https://en.wikipedia.org/wiki/Open/closed_principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
    - [ ] L - [Liskov Substitution Principle](http://www.oodesign.com/liskov-s-substitution-principle.html) | [Base Class and Derived class follow ‘IS A’ Principle](http://stackoverflow.com/questions/56860/what-is-the-liskov-substitution-principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
    - [ ] I - [Interface segregation principle](http://www.oodesign.com/interface-segregation-principle.html) | clients should not be forced to implement interfaces they don't use
        - [Interface Segregation Principle in 5 minutes (video)](https://www.youtube.com/watch?v=3CtAfl7aXAQ)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
    - [ ] D -[Dependency Inversion principle](http://www.oodesign.com/dependency-inversion-principle.html) | Reduce the dependency In composition of objects.
        - [Why Is The Dependency Inversion Principle And Why Is It Important](http://stackoverflow.com/questions/62539/what-is-the-dependency-inversion-principle-and-why-is-it-important)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)

- **Union-Find**
    - [Overview](https://www.coursera.org/learn/data-structures/lecture/JssSY/overview)
    - [Naive Implementation](https://www.coursera.org/learn/data-structures/lecture/EM5D0/naive-implementations)
    - [Trees](https://www.coursera.org/learn/data-structures/lecture/Mxu0w/trees)
    - [Union By Rank](https://www.coursera.org/learn/data-structures/lecture/qb4c2/union-by-rank)
    - [Path Compression](https://www.coursera.org/learn/data-structures/lecture/Q9CVI/path-compression)
    - [Analysis Options](https://www.coursera.org/learn/data-structures/lecture/GQQLN/analysis-optional)

- **Advanced Graph Processing** (videos)
    - [Synchronous Distributed Algorithms: Symmetry-Breaking. Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=mUBmcbbJNf4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=27)
    - [Asynchronous Distributed Algorithms: Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=kQ-UQAzcnzA&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=28)


# Coding Interview University

[Why I studied full-time for 8 months for a Google interview](https://medium.freecodecamp.org/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13)

## Don't feel you aren't smart enough

- Successful software engineers are smart, but many have an insecurity that they aren't smart enough.
- [The myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)
- [It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech](https://www.youtube.com/watch?v=1i8ylq4j_EY)

## Don't Make My Mistakes

This list grew over many months, and yes, it got out of hand.

Here are some mistakes I made so you'll have a better experience. And you'll save months of time.

### 1. You Won't Remember it All

I watched hours of videos and took copious notes, and months later there was much I didn't remember. I spent 3 days going
through my notes and making flashcards, so I could review. I didn't need all of that knowledge.

Please, read so you won't make my mistakes:

[Retaining Computer Science Knowledge](https://startupnextdoor.com/retaining-computer-science-knowledge/).

### 2. Use Flashcards

To solve the problem, I made a little flashcards site where I could add flashcards of 2 types: general and code.
Each card has different formatting. I made a mobile-first website, so I could review on my phone or tablet, wherever I am.

Make your own for free:

- [Flashcards site repo](https://github.com/jwasham/computer-science-flash-cards)

### 3. Do Coding Interview Questions While You're Learning

THIS IS VERY IMPORTANT.

Start doing coding interview questions while you're learning data structures and algorithms.

You need to apply what you're learning to solving problems, or you'll forget. I made this mistake. 

Once you've learned a topic, and feel somewhat comfortable with it, for example, **linked lists**:
1. Open one of the [coding interview books](#interview-prep-books) (or coding problem websites, listed below) 
1. Do 2 or 3 questions regarding linked lists. 
1. Move on to the next learning topic.
1. Later, go back and do another 2 or 3 linked list problems.
1. Do this with each new topic you learn. 

**Keep doing problems while you're learning all this stuff, not after.**

You're not being hired for knowledge, but how you apply the knowledge.
