---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single_home

#title: "Welcome to My Resume Website"
permalink: /
---
<div class="home-page">
<div class="about-me-container" style="display: flex; align-items: flex-start; gap: 1em; margin-top: 1em;">
  <!-- Left Column: About Me Text -->
  <div class="about-text" style="flex: 2; text-align: left;">
    <div class="project-title-wrapper" style="text-align: center;">
      <h2 class="color-title">About Me</h2>
    </div>
    <p>
      I’m Balaji Iyer, a data scientist and software developer. Explore my resume, projects, and skills.
    </p>
    <p>
      Check out my CV/Resume</p>
    <div class="project-title-wrapper" style="text-align: center;">
      <h2 class="color-title" style="margin-bottom: 0em">Contact Me</h2>
    </div>    
    <!-- modify this form HTML and place wherever you want your form -->
    <form class="contact-form" action="https://formspree.io/f/mdkeejdv" method="POST">    
    <label>Your email:<input style="border: 1px solid #007acc" type="email" name="email"></label>
    <label>Your message: <textarea name="message"></textarea></label>
  <!-- your other form fields go here -->
    <button type="submit">Send</button> 
    </form>
    
 </div>
  
  <!-- Right Column: Image -->
  <div class="about-image-right" style="flex: 1; text-align: center;">
    <div class="images-grid" style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1em; margin-top: 1em;">        
        <img src="/assets/images/Balaji_1.jpg" alt="Image 1" style="width: 90%; height: auto;">        
        <img src="/assets/images/Balaji_1.jpg" alt="Image 2" style="width: 90%; height: auto;">
        <img src="/assets/images/Balaji_1.jpg" alt="Image 3" style="width: 90%; height: auto;"> 
        <img src="/assets/images/Balaji_1.jpg" alt="Image 4" style="width: 90%; height: auto;"> 
    </div>
  </div>

</div>



<!-- <div class="project-title-wrapper" style="text-align: center;">
<h2 class="color-title"> About Me </h2>
</div>

I’m Balaji Iyer, a data scientist and software developer. Explore my resume, projects, and skills.-->
