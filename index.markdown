---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: David Schmitt
resume: assets/David_Schmitt_Resume_FINAL_01_14_22.pdf
---
## Personal Bio

I'm David Schmitt, a senior computer science student with a mathematics minor at the University of South Carolina, undergraduate researcher at the AFRL lab at UofSC, and the secretary of my college's ACM chapter. My research focuses on visual odometry with applications to autonomous field robotics. I have experience working in both academic and professional settings via my research and as a desktop support intern respectively. I'm enthusiastic about learning and communicating new problems and solutions in the computer science domain, be they theoretical or practical, and I frequently engage with other students, faculty, and the larger professional computing world as an executive member of UofSC's ACM chapter, organizing events such as our yearly codeathon and trip to the competitive coding competition ICPC.

## Statement of Purpose

I'm primarily focused on visual odometry with applications to autonomous field robotics. My research has led me to learn Iterative Closest Point techniques for point cloud registration. I have also gained experience with stereo camera systems and their calibration as well as image processing techniqes including undistorting fisheye lens footage. Through my research and educaction, I have experience working with ROS (Robotic Operating System). I have conducted pool trials with the amphibious robot Aqua which itself operates on ROS. Another ROS system I've worked with is the lab's StereoRig, a submersible handheld stereo camera system with an IMU and onboard computer. I had to study and troubleshoot the StereoRig system in order to support other projects in the AFRL lab, which familiarized me with the camera triggering mechanism and settings. My education has supplemented these research experiences with a strong background in mathematics and robotics from coursework I've completed. Outside the lab my intrests extend to organizng talks and events for the Univeresity of South Carolina's ACM chapter, for which I serve as the secratary. Events like our yearly codeathon involve cooperation with local companies which sponsor the events. Maintaining these professional relationships is an important part of being an executive ACM member. Futhermore I strive to create a welcoming comunity for learning about computing. Being an ACM exec member has taught me important skills in leadership and communication. Research has provided me with a strong technical background. Together these attributes support  me in fufilling my purpose of taking on problems in the computer science and robotics domains. 

## Portfolio
<div class="container">
  <div class="row">
    <div class="one-half column">
      <h5><a href="https://github.com/schmitd/schmitd.github.io">Website Repository</a></h5>
      View this site's source.
    </div>
    <div class="one-half column">
      <h5><a href="https://github.com/schmitd/Twitter-Substitutions-Sentiment-Analysis">Twitter Sentiment Analysis</a></h5>
      An introduction into text processing and sentiment analysis using the tweepy library.
    </div>
  </div>
</div>

## Resume
<object data="{{ page.resume }}" type="application/pdf" width="100%" height="600px">
  Your brower doesn't support PDF embedding. Download the resume <a href="{{ page.resume }}">here</a>.
</object>
<br>
## Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
