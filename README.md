Download Link: https://assignmentchef.com/product/solved-cs1026a-assignment-2
<br>
<strong>Purpose:  </strong>

To gain experience with:

<ul>

 <li>Using methods</li>

 <li>Using loops</li>

 <li>Picture manipulation</li>

</ul>

<strong> </strong>

<strong>Part A: </strong>

You are to create a total of <strong>6 object methods</strong> within the <em>Picture</em> class. These methods will perform some kind of picture modification (ex. Grayscale, mirror, flip, make more red, blur, etc.). You can check out lecture slides, lecture code, labs, or the textbook for examples. For these methods, <strong>4</strong> need to be original, and <strong>2</strong> can be from other resources (see examples above). Be creative! Have fun!




<strong>Functional Specifications for part A: </strong>

<ol>

 <li>Add the 6 methods to the <em>Picture</em> class (the <em>java</em> file) after the commented line:</li>

</ol>

<strong> </strong>

<strong>/////////////////// methods ////////////////////// </strong>




<ol start="2">

 <li>You will call these newly created methods from your own class called <em>Assign2</em>. Create a file called <em>java</em> and add the following code:</li>

</ol>

<strong> </strong>import java.awt.Color;

public class Assign2

{

public static void main(String[] args)

{

/* Insert your code here */

}

}




You will need to create the picture objects and invoke your object methods by adding the appropriate code within the main method. See lecture code for hints on how to do this. <strong>Remember</strong>, you will need to show() the picture after you have made the changes in order to see what has actually changed.







A high level snapshot of the algorithm will look something line this:




<ul>

 <li>Create a new picture object and show it on the screen – For each of the 6 methods:</li>

 <li>Create a new image that’s a copy of the original o Change the image with your method o Show the changed image to the screen</li>

</ul>




You can use whatever – appropriate – .jpg you want: you can take a selfie, you can use a picture you have taken, or you can use a picture provided by the textbook. <strong>However</strong>, it would be ideal if the picture had a lowish resolution for part B.




<strong> </strong>

<strong>Note: The working directory – Use files <em>without</em> FileChooser </strong>

The working directory is what programmers call the folder (directory) where the program is being run.  In Dr. Java, the working directory is the same as the location of the “.class” file that you are running.  You can see the working directory listed at the top of the interactions pane when you hit <strong>“Run”</strong> in Dr. Java. In the figure below, my working directory is “C:jhughe54Desktop”.




To use files that are saved in the working directory in your program, you simply list their name and the program will know to look in the working directory for that file.  If it is not there, you will get an error when you try to load the Picture file.




For example, if I had the files for this Part A in the folder “Asn3”, along with two images like this:




I could create a picture object using the following line since swan.jpg is within the working directory.

Picture startPic = new Picture(“swan.jpg”);

You <strong>must </strong>use a file from the working directory for this assignment.  You will submit the picture files you want us to use to OWL with your .java files. <strong>You cannot use a file chooser!</strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Part B: </strong>

Make a collage of modified pictures! In this part you are to make a large picture consisting of modified versions of your original picture. Your collage must consist of at least 6 modified versions of your original image (6 versions modified with the object methods written for <strong>Part A</strong>). Feel free to include more method and more than 6 modified versions of the original image in the collage. Your collage may contain the original image; however, if you choose to include it, then you must have at least 7 versions of the original image (6 new + 1 original). See high quality examples below:




<ol>

 <li>You may arrange the images however you would like.</li>

 <li>The original file must be loaded from the working directory (see above).</li>

 <li>Remove the code from the main method from Part A and replace it with the code required to do Part B</li>

 <li>You <strong>must</strong> also save the resulting collage with the file name <em>“myCollage.jpg”</em> (without quotes).</li>

</ol>

/*assume we have a picture object called myPic */ myPic.write(“MyCollage.jpg”);




<strong>Resizing:  </strong>

Since your original image can be one of the ones provided or your own, you may need to reduce the size of the image in order to use it properly.  This can be done using commercial software or the method getPictureWithHeight in the picture class. This method will create a picture with the specified height from an existing picture, and will keep the same height/width ratio.  Here is an example of how to use the method:




/*assume you are starting with a Picture object

referenced by a reference variable called largerPic */




Picture smallerPic = largerPic.getPictureWithHeight(200);  smallerPic.write(“filepath goes here /smallerPic.jpg”);




<strong>Non-functional Specifications:</strong>

<ol>

 <li>Include comments for your classes</li>

</ol>

// CS1026B Assignment 2

// <em>Your name</em>

// <em>A brief description of what this program does</em>

<ol start="2">

 <li>Include brief comments in your code that explain what each method is doing.</li>

 <li>Include comments for any code which is unclear.</li>

 <li>Assignments are to be done individually and must be your own work. <u>Software will be used</u> <u>to detect cheating.</u></li>

 <li>Use Java conventions and good Java programming techniques, for example:</li>

 <li>Meaningful variable names ii. Conventions for naming variables and constants iii. Use of constants where appropriate</li>

 <li>Readability: indentation, white space, consistency</li>

</ol>

<strong> </strong>

<strong>Important! You must follow all the specifications above for your program </strong>

<strong> </strong>

<strong>What You Will Be Marked On: </strong>

<ol>

 <li>Functional specifications:</li>

</ol>

Are the required methods written according to specifications?

Do they work as specified? Pay attention to details!

Are they called as specified?

Are the two objects drawn according to the specifications?

<ol start="2">

 <li>Non-functional specifications: as described above</li>

</ol>


