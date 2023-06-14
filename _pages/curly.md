---
layout: archive
title: "Curly"
permalink: /curly/
author_profile: true
---

I am thrilled to introduce you to the love of my life—Curly (Chinese name: 小卷毛儿 Xiao Juan Mao Er), my adorable Blenheim Cavapoo. Curly has brought immense joy and companionship into my world, and I can't wait to share her story with you.

## Curly's Background

Curly is born in Jan 2023. She is a mix of the Cavalier King Charles Spaniel and Poodle breeds. With her blenheim-colored coat—a combination of white and reddish-brown patches—she is as stunning as she is affectionate. Cavapoos are known for their intelligence, loyalty, and gentle nature, making them perfect furry friends for individuals and families alike.

## Curly's Personality
Curly is an absolute sweetheart, spreading joy by enthusiastically greeting everyone she meets. Her curiosity about nature is boundless, and she showcases her intelligence by quickly grasping instructions. Surprisingly brave, Curly fearlessly takes on new challenges, and she remains calm even during visits to the hospital.

## Curly's Adventures
Curly and I have embarked on countless adventures together.

<div class="image-gallery">
  <div class="grid-item"><img src="../images/IMG_3050.png" alt="Image 1"></div>
  <div class="grid-item"><img src="../images/IMG_2109.png" alt="Image 2"></div>
  <div class="grid-item"><img src="../images/IMG_2437.png" alt="Image 3"></div>
  <div class="grid-item"><img src="../images/IMG_3282.png" alt="Image 3"></div>
  <!-- Add more grid items as needed -->
</div>

<!-- <img src='../images/IMG_3050.png' width="500" >
<img src='../images/IMG_2109.png' width="500" >
<img src='../images/IMG_2437.png' width="500" >
<img src='../images/IMG_3282.png' width="500" > -->


<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
 -->
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
