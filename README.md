Download Link: https://assignmentchef.com/product/solved-cse-ece578-assignment-2-the-concept-of-homography-estimation-and-stereo-calibration
<br>
<strong>Instructions:</strong>

<ul>

 <li>The assignment aims to familiarize you with the concept of homography estimation and stereo calibration.</li>

 <li><strong>Make sure that the assignment that you submit is your own work. Any breach of this rule could result in serious actions including an F grade in the course.</strong></li>

 <li><strong>This is a fairly large assignment. The experiments and report writing will take time. Start your work early and do not wait till the deadline.</strong></li>

 <li>Make sure your files can be opened. Corrupted files will not be entertained.</li>

 <li>You can use C/C++, Python or Matlab for this. However, you are expected to implement it yourselves and not use an existing implementation.</li>

</ul>

<strong>Tasks:</strong>

<h1>Image Mosaicing</h1>

<ol>

 <li>Use any feature detector and descriptor (e.g. SIFT) to find matches between two partially overlapping images. You can use inbuilt functions for this.</li>

 <li>Estimate the homography matrix between the two images robustly.</li>

 <li>Transform one of the images to the others reference frame using the homography matrix.</li>

 <li>Stitch the two images together.</li>

 <li>Repeat this for multiple images to produce a singly mosaic/panorama.</li>

</ol>

<h1>Bonus</h1>

<ol>

 <li>Think of an algorithm which can stitch images given in any order without human intervention? If yes, modify your exisitng code accordingly.</li>

 <li>Is it possible to stitch a panorama without human intervention, given noisy images which do not belong to the same scene? If yes, how?</li>

</ol>

<h1>Instructions</h1>

<ul>

 <li>Write modular code, with comments clearly outlining the function of each module.</li>

 <li>The code must be robust and scalable, i.e, it should work for any number of images of any size and generate a reasonable output.</li>

 <li>There are some sample images included in the assignment, these images are NOT the exhaustive test set. Your code may be tested on a different set.</li>

 <li><strong>Show results on additional images captured with your camera.</strong></li>

 <li>You are allowed to use in-built functions for feature detection and matching but are required to write the code to build the homography matrix by yourself</li>

 <li>Submit a pdf report with procedure, code, results of intermediate steps and additional images from your cameras.</li>

</ul>

<h1>Stereo Correspondences</h1>

<ol>

 <li>Perform Intensity Window-based correlation on the given pair of images.</li>

 <li>Rectify the pairs of images and with these new images, repeat step 1.</li>

 <li>Compare with Greedy Matching and Dynamic programming solution for Stereo Correspondence on the rectified images.</li>

</ol>

<h1>Bonus</h1>

<ol>

 <li>Perform dense SIFT-based matching on the given pair of Images and give the comparison with that of Intensity window-based correlation.</li>

</ol>

<h1>Instructions</h1>

<ul>

 <li>Write modular code, with comments clearly outlining the function of each module.</li>

 <li>The code must be robust and scalable i.e, it should work for any number of images of any size and generate a reasonable output.</li>

 <li>There are some sample images included in the assignment, these images are NOT the exhaustive test set. Your code may be tested on a different set.</li>

 <li>Add the procedure and the images of intermediate steps in the report. Add the code to the report as well and explain it wherever necessary.</li>

 <li>Demonstrate the results on the given images and additional images from your camera.</li>

 <li>Make sure you provide the code separately also and not just in the report.</li>

 <li>Please ensure that the report contains your roll number. Zip the code and report for submission. The zip file should be named RollNumber Assignment2.zip .</li>

</ul>