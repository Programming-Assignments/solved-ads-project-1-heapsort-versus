Download Link: https://assignmentchef.com/product/solved-ads-project-1-heapsort-versus
<br>
<span class="kksr-muted">Rate this product</span>

1 Project description

You are going to implement a program that implements two sorting algorithms: selection sort and heapsort. But you are not going to implement two different sorting algorithms. Instead, you are going to implement a single algorithm with two different data structures:

2

• A vector. In this implementation the operation FindMaxAndSwap (finding the maximum element and swapping it on the last position) takes Θ(n) time.

• A heap. In this implementation the operation FindMaxAndSwap (finding the maximum element and swapping it on the last position) takes Θ(1) time. Of course, to maintain the heap property you have to call Heapify, which takes a further Θ(logn) time.

Guidelines

Your program should have the following basic functionality:

<ul>

 <li>Create two different classes corresponding to the two different implementations. Each of them should have the needed member functions. Data should be private, and accessible from the main program only through calling member functions.</li>

 <li>You have freedom to the design of the two classes. Discuss your design choices in the report you submit.</li>

 <li>The main program will have two identical functions Sort. They will differ through the type of the parameter, corresponding to the two different classes (Heap/Vector)Note: A better mechanism exists in C++, that allows us to write a single sorting function, but I won’t require this feature in the project.1</li>

</ul>

3

• The main function should call these two functions with two different objects corresponding to the same sequence, and print in both cases the sorted sequence.

What to turn in

You will turn in1. a short written report containing:

4

• A description of the significant choices/issues in the design of your code.

• Listing of your experiments, showcasing the capabilities of the program.

2. Thesourcecodeofyourprogram.You may turn in the document via elearning.e-uvt.ro (Class moodle).

Coding standards