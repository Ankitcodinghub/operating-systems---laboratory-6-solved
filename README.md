# operating-systems---laboratory-6-solved
**TO GET THIS SOLUTION VISIT:** [Operating-Systems – Laboratory 6 Solved](https://www.ankitcodinghub.com/product/operating-systems-laboratory-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116569&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Operating-Systems - Laboratory 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Part I

Write a simple image processing application in C/C++.

● The input to the application should be a ppm image file. There are many free utilities to convert from jpeg images to ppm ones.

● Your application must read this file and store the pixel information in a matrix.

● Then, it must perform two transformations to the image, one after the other. Choose some simple transformations such as “RGB to grayscale”, “edge detection”, “image blur”, etc. Let us call the two transformations T1 and T2.

● Write the resultant pixel matrix to a new ppm file.

● Usage: ./a.out &lt;path-to-original-image&gt; &lt;path-to-transformed-image&gt;

Part II

Now suppose you have a processor with two cores. You want your application to finish faster. You can do this by having the file read and T1 done on the first core, passing the transformed pixels to the other core, where T2 is performed on them, and then written to the output image file. Do this in the following ways:

1. T1 and T2 are performed by 2 different threads of the same process. They communicate through the process’ address space itself.

a. Synchronization using atomic operations

b. Synchronization using semaphores

2. T1 and T2 are performed by 2 different processes that communicate via shared memory. Synchronization using semaphores.(Single source file)

3. T1 and T2 are performed by 2 different processes that communicate via pipes. (Single source file)

● Briefly describe the chosen image transformations in your report.

● Devise a method to prove in each case that the pixels were received as sent, in the sent order. Describe the method in your report.

● Try with three different image sizes.

● Study the run-time and speed-up of each of the approaches and discuss.

● Discuss the relative ease/ difficulty of implementing/ debugging each approach.

Submit a single zip file with the source code, a makefile, an input ppm image, and a report.

● make part1 should compile the Part I version of the code and run it, creating the file output_part1.ppm

● make part2_1a should compile the multi-thread, atomic operation version of the code and run it, creating the file output_part2_1a.ppm

● make part2_1b should compile the multi-thread, semaphore version of the code and run it, creating the file output_part2_1b.ppm

● make part2_2 should compile the shared memory version of the code and run it, creating

the file output_part2_2.ppm

● make part2_3 should compile the pipe version of the code and run it, creating the file output_part2_3.ppm

Table format:

Image size Part1(Sequential) Part2.1a (Threads atomic operations) Part2.1b

(Threads – Semaphores) Part 2.2

(Process – Shared memory) Part 2.3

(Process

– Pipe)
