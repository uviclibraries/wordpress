---
layout: default
title: 2-Home Page 
nav_order: 3
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
# Website Planning & Home Page Considerations

**1. Static Home Page vs Blog Posts Home Page:**

 There are two different options for the front page, or home page of your Wordpress website: Static Front Page & Blog Post Front Page. Here is what each of them are:
 - Static Front Page: This is a traditional static HTML site model with a fixed front page and content placed in Pages, rarely if ever using posts, categories, or tags. If you would like to make the front page of your website static, please follow the directions below in Step 3.
  - Blog Post Front Page: This is the traditional front page blog format with blog posts featured in reverse chronological order. This is the default Front Page type, so if you'd like this style of website you don't need to do anything.
 
**2. Change your Home Page Type:**
  - On the left navigation bar click on **Settings**.
  - On the left navigation bar click on **Reading**.
  - On the web page click on either **Your latest posts** or **A static page**. If you select _A static page_, you'll need to select (or create) pages for your Homepage, and your Posts page. Ask your instructor if you have any questions about this.<br>

**3. Chnaging Templates**


 <button onclick="toggle('gif1')">Show / Hide Animation </button>
 <div id="gif1">
 <img src="images/homepage-01b.gif">
  </div>


<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Create your first Blog Post](first-blog-post.html){: .btn .btn-blue }
