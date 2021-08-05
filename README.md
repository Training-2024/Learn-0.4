# Learn-0.4



- [Videoprocessing Tutorials](https://github.com/Training-2024/Learn-0.4/tree/main/video_processing_tutorials)
- [Arucomarker Tutorials](https://github.com/Training-2024/Learn-0.4/tree/main/aruco_marker_tutorials)


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
