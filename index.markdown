---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: David Schmitt
---
## Personal Bio

I'm David Schmitt, a senior computer science student with a mathematics minor at the University of South Carolina, undergraduate researcher at the AFRL lab at UofSC, and the secretary of my college's ACM chapter. My research focuses on visual odometry with applications to autonomous field robotics. I have experience working in both academic and professional settings via my research and as a desktop support intern respectively. I'm enthusiastic about learning and communicating new problems and solutions in the computer science domain, be they theoretical or practical, and I frequently engage with other students, faculty, and the larger professional computing world as an executive member of UofSC's ACM chapter, organizing events such as our yearly codeathon and trip to the competitive coding competition ICPC.

## Statement of Purpose

I'm primarily focused on visual odometry with applications to autonomous field robotics. I have also gained experience with stereo camera systems and their calibration as well as image processing techniqes including undistorting fisheye lens footage. I have experience working with ROS (Robotic Operating System). I have conducted pool trials with the amphibious robot aqua which itself operates on ROS. Another ROS system I've worked with is the lab's StereoRig, a submersible handheld stereo camera system with IMU and onboard computer. I had to study and troubleshoot the StereoRig system in order to support other projects in the AFRL lab.
## Resume
<object data="/assets/Resume_NEEDSREVISION_David_Schmitt.pdf" type="application/pdf" width="100%" height="600px">
  Your brower doesn't support PDF embedding. Download the resume <a href="/assets/Resume_NEEDSREVISION_David_Schmitt.pdf">here</a>.
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
