Download Link: https://assignmentchef.com/product/solved-solvedp1-traffic-animation-solution
<br>
In this assignment, you are going to create an animation of a vehicle that moves across the window in a traffic lane. You have flexibility to draw whatever you want, as long as it has the same relative complexity as a multi-part vehicle and still involves multiple shapes and colors.

Objectives

Add code to a method in a given skeleton class to paint a scene.Use methods from the Graphics class.Use variables to manage data and expressions to calculate size and position of your shapes.Use the Color class.Specification

Create an animation of a vehicle moving across the window in a lane. Your scene will include an avatar watching the vehicle move by and some interesting scenery.

Traffic Animation Sample Frame 1 Traffic Animation Sample Frame 2 Traffic Animation Sample Frame 3 Traffic Animation Sample Frame 4Complete the TrafficAnimation class by doing the following in its paintComponent() method:

Draw your vehicle relative to an anchor position (the xOffset variable) so that the position of your vehicle will change every time the paintComponent() method is called.The TrafficAnimation() constructor method in the provided starter code sets up the animation and updates the xOffset anchor coordinate for you. All you have to do is make sure that you draw your vehicle relative to this coordinate.When the vehicle goes off one edge of the window, it should come back on the other edge.Again, if you draw your vehicle relative to the xOffset coordinate, this is already done for you.Draw a visual lane in which the vehicle moves. Make sure the lane scales correctly by specifying the position and dimensions relative to the width and height of the screen.Draw an avatar observer to the scene, out of the path of traffic. You may use an image in place of drawing for the avatar.Use at least five different methods from the Graphics class to draw the vehicle and environment. This means different shapes (rectangles, ovals, lines) as well as both fill and draw methods.Display some text in the window – a title, a quotation or whatever seems appropriate.Add whatever else you want to the scene to make the picture interesting to you!Use at least three colors in your scene. At least one of them should be a custom color. There are a number of sites on the web where you can find color samples with their RGB values.Make your scene adjust appropriately when the window gets resized. For example, centered text should remain centered, the vehicle should travel the entire width of the window, and all graphics should adjust or scale as needed.Extra Credit Options (+10 points max)

Animate the wheels of your vehicle. (+4 points)Smooth out the wrapping – the vehicle should not abruptly disappear when it reaches one side of the frame or abruptly reappear on the other side. It should look like it went off screen, around the block, and then back onto the screen after a few seconds. (+3 points)Have vehicles traveling in different directions in separate lanes. (+3 points)Sample video showing an animation in action (with extra credit features):

Inspiration

Here are some sample solutions to give you an idea of what your scene could look like. You can be creative!

Traffic Animation Example 1 Traffic Animation Example 2 Traffic Animation Example 3Getting Started

Create a new Eclipse project for this assignment and import TrafficAnimation.java into your project.Don’t forget you use the graphics examples that you checked out in Eclipse if you need some help getting started.Submitting Your Project

Testing

Once you have completed your program in Eclipse, copy your TrafficAnimation.java file and README file into a directory on the onyx server, with no other files (if you did the project on your computer). Test that you can compile and run your program from the console in the lab to make sure that it will run properly for the grader.

javac TrafficAnimation.javajava TrafficAnimationDocumentation

If you haven’t already, add a javadoc comment to your program. It should be located immediately before the class header. If you forgot how to do this, go look at the Documenting Your Program section from lab .

Have a class javadoc comment before the class (as you did in the first lab)Your class comment must include the @author tag at the end of the comment. This will list you as the author of your software when you create your documentation.Include a plain-text file called README that describes your program and how to use it. Expected formatting and content are described in README_TEMPLATE. See README_EXAMPLE for an example.

Submission

You will follow the same process for submitting each project.

Open a console and navigate to the project directory containing your source files,Remove all the .class files using the command, rm *.class.In the same directory, execute the submit command for your section as shown in the following table.Look for the success message and timestamp. If you don’t see a success message and timestamp, make sure the submit command you used is EXACTLY as shown.Required Source FilesRequired files (be sure the names match what is here exactly):TrafficAnimation.java (main class)READMEAny image files that your program uses should be in the same folderSection Instructor Submit Command1 Luke Hindman (TuTh 1:30 – 2:45) submit lhindman cs121-1 p12 Greg Andersen (TuTh 9:00 – 10:15) submit gandersen cs121-2 p13 Luke Hindman (TuTh 10:30 – 11:45) submit lhindman cs121-3 p14 Marissa Schmidt (TuTh 4:30 – 5:45) submit marissa cs121-4 p15 Jerry Fails (TuTh 1:30 – 2:45) submit jfails cs121-5 p1After submitting, you may check your submission using the “check” command. In the example below, replace

submit -check