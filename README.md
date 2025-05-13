# dic-homework-final-exam-image-filter-engine-solved
**TO GET THIS SOLUTION VISIT:** [DIC Homework Final Exam-Image Filter Engine Solved](https://www.ankitcodinghub.com/product/dic-homework-final-exam-image-filter-engine-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93295&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DIC Homework Final Exam-Image Filter Engine Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

We often use the different types of filters to extract features from an image or remove noise from an image or signal. In this exam, please implement an image filter engine, which uses 3×3 mean filter, 5×5 mean filter, 3×3 max filter, and threshold to process the image. The specification and function of IFE circuit will be described in detail in the following section.

2 Design Specifications 2.1 Block overview

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 1 – System operation flow

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.2 I/O Interface

Name I/O

clk I 1

reset I 1 ready I 1

</div>
<div class="column">
System clock signal. This system is synchronized with the positive edge of the clock.

Active-high asynchronous reset signal.

Grayscale image ready indication signal. When this signal is high, the grayscale image memory is already

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Width

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
System busy indication signal. When IFE receives high level ready signal and IFE is ready to start the calculation, this signal has to be set as high. After the calculation is completed and the result is completely output, set this signal to low and the testbench will start checking if the results are correct.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
busy

</div>
</div>
<div class="layoutArea">
<div class="column">
iaddr

</div>
<div class="column">
O

O 14 I

I

O

O

O

I

</div>
<div class="column">
prepared. IFE can start sending grayscale image address to obtain the data.

The signal for grayscale image memory address, which is used to request grayscale image pixel data.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
idata

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
data_rd

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
addr

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
data_wr

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
wen

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sel

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Input grayscale image pixel data signal, which represents an 8 bits unsigned integer. The testbench will send the pixel data according to the address iaddr indicates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory read data signal, which represents an 8 bits unsigned integer. This signal is used to send the result memory data to IFE circuit.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory read/write address.

This signal indicates which address of the result memory will be read or written.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory write data signal, which represents an 8 bits unsigned integer. The operation result of the IFE circuit is written to result memory using this signal.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory write enable signal.

When this signal is low (read), the data with address addr in result memory is sent by data_rd.

When this signal is high (write), the data sent by data_wr is written to the address addr in result memory.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The function selection signal. This signal will not change when an operation is being processed.

If sel == 2’d0, the IFE circuit will use 3×3 mean filter to process the image.

If sel == 2’d1, the IFE circuit will use 5×5 mean filter to process the image.

If sel == 2’d2, the IFE circuit will use 3×3 max filter to process the image.

If sel == 2’d3, the IFE circuit will use threshold to process the image.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
2.3 Function Description

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input Image: 128x128x1

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
Zero padding

</div>
<div class="column">
Mean Filter Max filter

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
Threshold

Fig. 2 – Operation flow.

</div>
<div class="column">
Result image

Result image

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The size of the input image in this system is 128×128, which is stored in the grayscale image memory. The correspondence between each pixel of the grayscale image and memory arrangement is shown in Figure 4. In the operation process, the IFE circuit uses the iaddr signal to send the address of requested image data (as shown in Figure 3. t1 time point). After the negative edge of each clock, the pixel data at requested address will be sent into the IFE circuit by the idata signal (as shown in figure 3. t2 time point).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 3 – Timing diagram while reading grayscale image memory

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
…

</div>
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
8 bits

</div>
</div>
<div class="layoutArea">
<div class="column">
128 pixels

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 3

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Pixel Pixel Pixel Pixel 012 127

</div>
</div>
<div class="layoutArea">
<div class="column">
Pixel 128

Pixel 16256

</div>
<div class="column">
Pixel 129

Pixel 16257

</div>
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
16384 pixels

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16381

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16382

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16383

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Fig. 4 – Arrangement mapping between grayscale image memory and input image.

</div>
</div>
<div class="layoutArea">
<div class="column">
Pixel 16383

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The first step of the system is to check the select signal to decide which function will be executed.

If sel is 0 , the IFE circuit will process the image with 3×3 mean filer. Zero- padding has to be applied on the image to keep the size of the image unchanged. Then the padded image is convolved with 3×3 mean filter to obtain result image. The function of 3×3 mean filter is as follows :

Result(x, y) = 1 ∑ 𝑖𝑚𝑔(𝑠, 𝑡), 𝑤h𝑒𝑟𝑒 𝑚, 𝑛 = 3

Let 𝑆𝑥𝑦 represent the set of coordinates in a rectangular subimage window of size 𝑚𝑥𝑛 (m,n is 3), centered at point (x, y).The arithmetic mean filtering process computes the average value of the corrupted image 𝑖𝑚𝑔(𝑠, 𝑡) in the area defined by 𝑆𝑥𝑦. The value of the result image at any point (x, y) is simply the arithmetic mean computed using the pixels in the region defined by 𝑆𝑥𝑦.

Hint: Round down the result value to an integer.

If sel is 1 , the IFE circuit will process the image with 5×5 mean filer. Zero- padding has to be applied on the image. Since the filter size is 5×5, two rows and two columns have to be padded to each side to keep the size of the image unchanged. Then the padded image is convolved with 5×5 mean filter to obtain result image. The function of 5×5 mean filter is as follows :

Result(x, y) = 1 ∑ 𝑖𝑚𝑔(𝑠, 𝑡), 𝑤h𝑒𝑟𝑒 𝑚, 𝑛 = 5

Hint: Round down the result value to an integer.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑚𝑛 (𝑠,𝑡)∈𝑆𝑥𝑦

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑚𝑛 (𝑠,𝑡)∈𝑆𝑥𝑦

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
128 pixels

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
If sel is 2, the IFE circuit will process the image with 3×3 max filter. Zero- padding has to be applied on the image to keep the size of the image unchanged. Then the padded image is convolved with 3×3 max filter to obtain result image. The function of 3×3 max filter is as follows :

Result(x, y) = max {𝑖𝑚𝑔(𝑠, 𝑡)} (𝑠,𝑡)∈𝑆𝑥𝑦

Let 𝑆𝑥𝑦 represent the set of coordinates in a rectangular subimage window of size 3𝑥3, centered at point (x, y). The arithmetic max filtering process computes the max value of the corrupted image 𝑖𝑚𝑔(𝑠, 𝑡) in the area defined by 𝑆𝑥𝑦. The value of the result image at any point (x, y) is simply the max value computed using the pixels in the region defined by 𝑆𝑥𝑦.

If sel is 3, the IFE circuit will use a threshold to segment the image. The operation is defined as follows:

If img(x, y) &lt; 127 , 𝑅𝑒𝑠𝑢𝑙𝑡(𝑥, 𝑦) = 0; else 𝑅𝑒𝑠𝑢𝑙𝑡(𝑥,𝑦)=img(x,y);

If the image intensity is less than 127, set the new intensity as zero. Otherwise, set the new intensity as origin intensity.

After the operation is finished, the busy signal should be set to 0, and then testbench will start the verification process.

In the reading phase of result memory, the addr signal represents the memory address to read and the data_rd signal will provide the data. wen signal should be set as low. The timing diagram of result memory reading operation is shown in figure 6.

In the writing phase of result memory, the addr signal informs the memory address to be written and the data_wr signal should provide the writing data. wen signal should be set as high. The timing diagram of result memory writing operation is shown in figure 7.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 6 – Timing diagram of reading result memory.

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 7 – Timing diagram of writing result memory.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3 Scoring

</div>
</div>
<div class="layoutArea">
<div class="column">
3.1

</div>
<div class="column">
Functional Simulation [120%]

3.1.1 Successfully pass the testfixture_mean_3x3.v. [20%] 3.1.2 Successfully pass the testfixture_mean_5x5.v. [20%] 3.1.3 Successfully pass the testfixture_max.v. [30%]

3.1.4 Successfully pass the testfixture_threshold.v. [30%] 3.1.5 The Program can finish successfully. [20%]

Your design must iteratively access the memory and control busy signal properly to get this part of scores.

</div>
</div>
<div class="layoutArea">
<div class="column">
4 Submission

4.1 Submitted files

You should classify your files into two directories and compress them to .zip

format. The naming rule is final_studentID_name.zip. If your file is not named according to the naming rule, you will lose five points. Please submit the compressed file to moodle and email it to diclab62547@gmail.com. The title of email should be set as final_studentID_name.

*.v All of your Verilog RTL code

4.2 Report file

Please follow the spec of report. If your report does not meet the spec, you may

lose part of score. You are asked to describe which testfixture you passed. Any information that you want to tell TA can also be written in the report.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
RTL category

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Documentary category

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
*.pdf

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The report file of your design (in pdf).

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
4.3 Note

Please do not modify any content of testfixture. Upload your code no matter

your design can pass or not. Otherwise, TA can’t give you any point without code.

</div>
</div>
</div>
