---
layout: page
title: Recherch&eacute; Travel
tagline: Uniquely Wild Travel for the Audacious at Heart
---
{% include JB/setup %}
{{ site.description }}  

Let me introduce myself, I'm Kristan Armstrong and I'm the daughter of an outrageously adventurous woman who has been an avid traveler her whole life.  Some people just have the travel bug
and others learn it from others, but once you get it it's hard to get rid of.  That's what happened to my mother, and now subsequently my sister and myself also suffer from the same
disease. It's hard to stay in one place your whole life when there is so much more to discover.  Discovery is dangerous.  It can be an addiction that runs through your veins so potent that
you end up doing things you never dreamed you would do. For me, discovery has been a catalyst to wanting to know more, experiencing new things and asking more questions about life, politics
and science.  Discovery is what lead me to graduate with a double degree in Engineering Physics and Applied Mathematics, I wanted to know more about life and what I was capable of achieving.

You see, before going to college I wasn't even sure I was going to graduate high school.  In fact, my GPA was so low coming out of high school that I had to attend a community college for a 
year before applying to CU - Boulder.  This wasn't because I had hard time learning, I just simply didn't apply myself nor did I want to.  I was a competitive figure skater, I was more focused
on what I could push my body to do than what I could push my brain to do.  I never had physics or chemistry in high school, so of course I never dreamed that I would get a degree in Physics or
any other subject remotely related to it.  My inquisitive nature and the urge for discovery lead me down that path, as well as, many other avenues which I will share with you soon...

![Image description](/pictures/DSC08351.JPG)    

Now I know that was a little long winded and you're probably wondering when I am going to introduce my family.  Well first off, here we all are:

{% img class "/pictures/DSC08351.JPG" 'title text' 'alt text' %} 

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


