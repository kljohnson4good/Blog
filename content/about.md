---
date: "2022-09-01T21:48:51-07:00"
title: About
---

<!--- START PAGINATE FEATURE --->
<!--- #################### section 1 ########################### --->

<span class="about1">

# About Me

<font size = 5>
Kristi Johnson
</font>
<br/>
Data Scientist, Software Programmer, Engineer, Mentor, Dog Mom
<br/>
Born/Live: California, USA
<br/>
<br/>

I have have been an engineer for over 20 years, starting with my first internship in 1997 during college where I learned to love software automation, drawing histograms and applying visualizations, math and statistics to manufacturing and test challenges.  

After graduating with a B.S in **Computer Engineering**, my professional roles required software development and hardware debug to deliver a product, but I continued to be drawn to using data and visualizations to excel at debug and problem solving.  Finally in 2017 I decided to return to academics to take my education to the next level and graduated from [**Pennsylvania State University** online Master's degree program](https://bulletins.psu.edu/graduate/programs/majors/statistics/) in 2020.

I consider myself to be multi-faceted in most aspects of my life, hardly settling on being an expert at one thing.  For example, my college athletic interests consisted of 8 **track-and-field** events (7 events for the Heptathlon + triple jump) during the Spring, and playing multiple positions on the **soccer** field (including goalie) during the Fall.  

Applied to my career, my multi-dimensional interests have enabled me to go deep as a software developer, as well as exercise leadership by achieving big goals through the coordination of team efforts.  My wide focus helps me to see interdependencies and bring cross-functional teams together synergystically to solve problems.

I am an **introvert**, and my #1 strengh according to [strength assessment](https://www.viacharacter.org/) is **Humility**.  As an athlete I pretty much had to be dragged onto an awards podium and I hated pictures (good thing nobody had cell phones in those days!).  Even holding eye contact with other people can feel uncomfortable.  Growing up, these traits can feel like weaknesses, but over time I am learning how to turn them into strengths.  For example, I don't pretend to have all the answers, and I love learning and sharing the stage with others and seeing them rise above their own limiting beliefs.

</span> 

<!--- end about1 --->

<!--- ############################################### --->

<span class="about1-2" style="display:none">

### Most Memorable Career Moments

Top experiences that have shaped me include:

1. Living and working in **Haifa, Israel** for 2 months surrounding Rosh Hashanah
2. The adrenaline rush of a product "**Power-On**" and getting things to work under schedule pressure.
3. Achieving audacious goals through coordination of many people working together as a **team**
4. Company and Team celebrations where lifelong **friendships** are made

</span> 

<!--- ############################################### --->

<span class="about1-3" style="display:none">

### Track and Field Records

Just for fun, here are my college bests:

|Event             |Record       |
|:--------------   |:--------    |
|Heptathlon        | 4684 points |
|Long Jump         | 18'3"       |
|Triple Jump       | 38'3"       |
|High Jump         | 5'5"        |
|Javelin           | 148'2" (*)  |
|Shot Put          | 35'2"       |
|200m              | 26.9s       |
|100m Hurdles      | 15.9s       |
|800m              | let's not talk about that :-/ |

(*) National championship All-American and still holds the record at Chico State University (as of 2022).  This achievement landed me in [Chico's **Atehletic Hall-Of-Fame** 2018](https://chicowildcats.com/sports/2019/1/3/chico-state-hall-of-fame-class-of-2018.aspx), and inducted into my junior college [Diablo Valley College Athletic Hall of Fame](https://diablovalley.prestosports.com/HOF/HOF_2020) in 2020.  

</span> 

<!--- ############################################### --->

<span class="about1-4" style="display:none">

### Hobbies

**Travel**:

**Road Cycling**:
Riding 72 miles at 6500 ft of elevation around South Lake Tahoe, CA.  

**Mountain Biking**: Specialized full suspension StumpJumper

**Wellness**: [Beachbody On-Demand](https://www.beachbodyondemand.com/), Walking my dog.

**Martial Arts**: Black belt in Mui Thai kickboxing and self defense.

**Reading**: nonstop

**Movies**: comedy, action (never horror)

**Podcasts**: Brene Brown on Spotify

**Music**: From country (Dolly Parton) to hard rock (A7X), and seen them in concert too.

**Blog**: This is it, you're already here! :-)

</span> 

<!--- ############################################### --->

<span class="about1-link">

----------------------------------------------------------------------

* <a href="#" class="page1-3">Track and Field Records</a>
* <a href="#" class="page1-4">Hobbies</a>

</span>

<!--- end page1-2 --->

<!--- #################### STEP 2 ########################### --->
<span class="about2" style="display:none">

# Credits and Acknowledgement

This site was inspired by the ASA Committee on Career Development [Portfolio Project](https://ccdportfolio.netlify.app) written in Amstat news June 2022.  Source code and method follows the fantastic tutorial [bookdown](https://bookdown.org/yihui/blogdown/) by Yihui Xie, Amber Thomas, Alison Presmanes Hill (2022-08-08).
<br/>
Icon sources:
* <a href="https://www.freepnglogos.com/pics/logo-home-png">Logo Home from freepnglogos.com</a>
* <a href="https://www.freepnglogos.com/pics/512x512-logo">512x512 Logo from freepnglogos.com</a>
* <a href="https://www.freepnglogos.com/pics/linkedin-logo-png">Linkedin Logo from freepnglogos.com</a>



</span>

<!--- #################### STEP 3 ########################### --->
<span class="about3" style="display:none">

# Site Development

**<u>How this site is created</u>**
<br/>
This site is built using R language blogdown package and hosted from Netlify connected to my github source code.  I used the default theme that came by following the bookdown tutorial and then leveraged some bits from ccdportfolio's 'minimal' theme to add category and tag links on the home page above the blog title.  I like the concept to include those to assist users to find content they are looking for if the number of blog titles continue to increase.

</span>



<!--- #################### end of content ########################### 
--->

<p><b>Navigation: <span style="color: #3d85c6;">
<a href="#" class="page1">About Me</a>
<a href="#" class="page2">Site Credits</a>
<a href="#" class="page3">Site Development</a>
</b></p>

<!--- below code will show/hide sections based on which is selected --->

<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<script style="text/javascript">
jQuery(document).ready(function(){
jQuery('.page1').click(function(){
jQuery('.about1').show();jQuery('.about1-link').show();
jQuery('.about1-2').hide();
jQuery('.about1-3').hide();
jQuery('.about1-4').hide();
jQuery('.about2').hide();
jQuery('.about3').hide();
jQuery('.window').scrollTo(0,0);
return false;
});
jQuery('.page1-2').click(function(){
jQuery('.about1').show();jQuery('.about1-link').show();
jQuery('.about1-2').show();
jQuery('.about1-3').hide();
jQuery('.about1-4').hide();
jQuery('.about2').hide();
jQuery('.about3').hide();
return false;
});
jQuery('.page1-3').click(function(){
jQuery('.about1').show();jQuery('.about1-link').show();
jQuery('.about1-2').hide();
jQuery('.about1-3').show();
jQuery('.about1-4').hide();
jQuery('.about2').hide();
jQuery('.about3').hide();
return false;
});
jQuery('.page1-4').click(function(){
jQuery('.about1').show();jQuery('.about1-link').show();
jQuery('.about1-2').hide();
jQuery('.about1-3').hide();
jQuery('.about1-4').show();
jQuery('.about2').hide();
jQuery('.about3').hide();
return false;
});
jQuery('.page2').click(function(){
jQuery('.about1').hide();
jQuery('.about1-2').hide();
jQuery('.about1-3').hide();
jQuery('.about1-4').hide();
jQuery('.about1-link').hide();
jQuery('.about2').show();
jQuery('.about3').hide();
jQuery('.window').scrollTo(0,0);
return false;
});
jQuery('.page3').click(function(){
jQuery('.about1').hide();
jQuery('.about1-2').hide();
jQuery('.about1-3').hide();
jQuery('.about1-4').hide();
jQuery('.about1-link').hide();
jQuery('.about2').hide();
jQuery('.about3').show();
jQuery('.window').scrollTo(0,0);
return false;
});
});
</script>

<!--- END PAGINATE FEATURE --->