---
layout: archive
title: "Curly"
permalink: /curly/
author_profile: true
---

I am thrilled to introduce you to the love of my life—Curly (Chinese name: 小卷毛儿 Xiao Juan Mao Er), my adorable Blenheim Cavapoo. Curly has brought immense joy and companionship into my world, and I can't wait to share her story with you.

## Curly's Background

Curly was born in Jan 2023. She is a mix of the Cavalier King Charles Spaniel and Poodle breeds. With her Blenheim-colored coat—a combination of white and reddish-brown patches—she is as stunning as affectionate. Cavapoos are known for their intelligence, loyalty, and gentle nature, making them perfect furry friends for individuals and families alike.

## Curly's Personality
Curly is an absolute sweetheart, spreading joy by enthusiastically greeting everyone she meets. Her curiosity about nature is boundless, and she showcases her intelligence by quickly grasping instructions. Surprisingly brave, Curly fearlessly takes on new challenges, and she remains calm even during visits to the hospital.

## Curly's Adventures
Curly and I have embarked on countless adventures together.

<style>
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

<div class="row">
  <div class="column">
    <figure>
      <img src='../images/IMG_3050.png'  style="width:100%">
      <figcaption>Fig.1 - Curly with the outdoor sculpture of Martha R. Ingram on the Vanderbilt campus. Martha R. Ingram was the first woman to chair the Vanderbilt Board of Trust. </figcaption>
    </figure>
    
  </div>
  <div class="column">
    <figure>
      <img src='../images/IMG_2109.png' style="width:100%">
      <figcaption>Fig.2 - Curly in a little black dress. </figcaption>

    </figure>
    
  </div>
</div>
<div class="row"> 
  <div class="column">
     <figure>
      <img src='../images/IMG_2437.png' style="width:100%">
      <figcaption>Fig.3 - Curly in the Dogs & Dogwoods Festival at Cheekwood, Nashville, TN.  </figcaption>
    </figure>
  </div>
   <div class="column">
     <figure>
      <img src='../images/IMG_3282.png' style="width:100%">
      <figcaption>Fig.4 - Curly in Cloud Gate The Bean in Chicago, IL.  </figcaption>
    </figure>
  </div>
</div>

And more!

<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
 -->
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
