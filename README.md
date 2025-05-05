# 4601-assignment-1-susceptibility-weighted-imaging-solved
**TO GET THIS SOLUTION VISIT:** [4601 Assignment 1-Susceptibility Weighted Imaging Solved](https://www.ankitcodinghub.com/product/4601-assignment-1-susceptibility-weighted-imaging-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95484&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;4601 Assignment 1-Susceptibility Weighted Imaging Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Susceptibility Weighted Imaging

Through this assignment you will learn about susceptibility weighted imaging (SWI). You are provided with real data acquired on a 7T MRI scanner (single human brain slice, gradient recalled echo acquisition with an echo time of 16.81ms). You are required to use a corresponding magnitude and phase image and create a susceptibility weighted image. Additionally, you will investigate how susceptibility weighted images are created and how contrast in these images can be changed via the phase mask.

Prior to starting the assignment, you will need to:

o get access to MATLAB.

o download NIAK tools (https://www.nitrc.org/projects/niak/)

o download the data provided and open it in MATLAB using the NIAK tool to read .nii (NIfTI) files.

o start to learn the basics of MATLAB in viewing and working with images (use the ‘imshow’ command to view

images and change the scale and see how to best visualise the images).

o read the 2000 paper by Wang et al. which outlines the method of homodyne filtering (Eqs. 5-7).

o read the 2004 paper by Haacke et al. which describes SWI, and the process used to create a phase mask.

Once you have completed the above tasks you are ready to start create a susceptibility weighted image. Enjoy!

What you need to do (20 marks in total):

<ol>
<li>1) &nbsp;Show the magnitude and raw phase images in MATLAB. Use the data cursor tool and highlight values around the image, you will see that the raw phase image contains values in the [-π, π] range. Why is this the case?</li>
<li>2) &nbsp;You will now work with the magnitude and raw phase image data. Your task is to implement homodyne filtering and produce an image of tissue phase.

You need to submit your homodyne filter script. Save the tissue phase image and plot it over a range [-2, 2]. What happened to the wraps present in the raw tissue phase? [Note: as a first step, use a filter size of 1⁄4 of the matrix size, and consider using the ‘hann’ function in MATLAB for the creation of the 2D filter]</li>
<li>3) &nbsp;Now you will create a phase mask. Create the phase mask from tissue phase using positive tissue phase values only.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Show the image over the range [0.7, 1] and save it for submission.

</div>
</div>
<div class="layoutArea">
<div class="column">
4) With the tissue phase mask in hand, now you will be able to investigate how raising the phase mask to a power (P) influences the result. Create a susceptibility weighted image when

</div>
</div>
<div class="layoutArea">
<div class="column">
o P=1.Savetheimageandlabelit. o P = 2. Save the image and label it. o P = 4. Save the image and label it.

Discuss the influence of P on the susceptibility weighted result. How should P be chosen?

</div>
</div>
<div class="layoutArea">
<div class="column">
5) Create a susceptibility weighted image using P = 2 and by emphasizing negative tissue phases only. Describe the steps you used to create this image. Save your result and label it clearly. How does this image differ from

</div>
</div>
<div class="layoutArea">
<div class="column">
when positive tissue phase values are used to create the phase mask?

</div>
</div>
<div class="layoutArea">
<div class="column">
6) Instead of using 1⁄4 of the matrix size in your homodyne filter setting, try different sizes such as 1⁄2 and 1/8.

</div>
</div>
<div class="layoutArea">
<div class="column">
Show the images and discuss how filter size affects tissue phase.

</div>
</div>
</div>
