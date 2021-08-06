# Learn-0.4
## Video Processing

You  guys might've finished the previous module, [Learn-0.3](https://github.com/Training-2024/Learn-0.3), if not, make sure you finish that first!<!--first finish that and then visit this module.--> Now we're going to discuss about the application of OpenCV that is *Video Processing*. Let us get into the topic now.

<p>Digital images and Videos are everywhere these days – in thousands of scientific (e.g., astronomical, bio-medical), consumer, industrial, and artistic applications. Moreover they come in a wide range of the electromagnetic spectrum - from visible light and infrared to gamma rays and beyond. The ability to process image and video signals is therefore an incredibly important skill to master for engineering/science students, software developers, and practicing scientists.   Digital image and video processing continues to enable the multimedia technology revolution we are experiencing today. Some important examples of image and video processing include the removal of degradations images suffer during acquisition (e.g., removing blur from a picture of a fast moving car), and the compression and transmission of images and videos (if you watch videos online, or share photos via a social media website, you use this everyday!), for economical storage and efficient transmission.  </p>

## Aruco Marker

<p> Markers are reference shapes which can be helpful to give some info to change our space from 2D to 3D. ArUco markers are normally squared binary(Black&White) markers. These markers are stored in the ArUco dictionary as binary. After the detection of the markers in the image, they are compared to the ones in the dictionary and calculated which marker has which id.Ok..let's not go deep into it here..</p>


As <!--previously-->told in the First Module, our **Robotics Club** <!--is promoting-->encourages and expects **_SELF LEARNING_**. So you guys might have understood what to do now...

Use these resources thatt we have curated for you to learn Video Processing.
- [Videoprocessing Tutorials](https://github.com/Training-2024/Learn-0.4/tree/main/video_processing_tutorials)
- [Arucomarker Tutorials](https://github.com/Training-2024/Learn-0.4/tree/main/aruco_marker_tutorials)

You can ask your doubts to the assigned mentors.

<hr/>
<h2>Task Description</h2>
<li>
 <a href='https://github.com/Training-2024/Learn-0.4/tree/main/task3'>Task files</a>
</li>
<h2><a class="header" href="#b-problem-statement" id="b-problem-statement">Problem Statement</a></h2>
<ul>
<li>
<p>You are given with the video <em><strong>aruco_bot.mp4</strong></em> in the task3 folder. In this video a small bot on which an aruco marker is placed is rotating around a circle.</p>
</li>
<li>
<p>Task is to capture a given frame in the video and <strong>detect the aruco marker </strong>and mark the corners of the aruco marker and also the id of the marker.</p>
 <li>
<p>Dictionary of the aruco marker in the video is <strong>DICT_5X5_50 </strong></p>
  </li>
 </ul>
<h3><a class="header" href="#task-instructions" id="task-instructions">Task Instructions</a></h3>
<hr />
<p>Inside <em><strong>the task3 folder</strong></em> you will find <strong>files</strong> as shown below:</p>
<ul>
<li><em>task3.py</em></li>
<li><em>aruco_bot.mp4</em>
</li>
</ul>
<p>For this part of the task we have provided a <strong>“snippet”</strong> of outline code in <strong><code>task3.py</code></strong> file:</p>
<ul>
<li>You have to modify the <strong><code>get_frame(),detect_Aruco(),mark_Aruco()</code></strong> functions and comments are provided in each of the three functions.</li>
<li>When you run the <strong><code>task3.py</code></strong>, as a default, the <strong>main()</strong> function will be called and it calls three functions in the written order.</li>
 <li>The video provided to you has less brightness,you need to capture the frame at the required second and adjust the contrast accordingly and detect the aruco and mark the corners and id of the marker.</li> 
<li>The output image <strong>output.jpg</strong> is the frame captured at 4th second you can try at different frames.</li>
</ul>
