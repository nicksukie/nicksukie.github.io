---
layout: default
---
<div class="page-content">
    <div class=" text-body paragraph-text-home mx-auto mb2">
<h2>Who Am I?</h2>
<p>
<br>

I'm currently a PhD student doing research on deep learning enabled recommender systems (and more!). Having taken an unconventional career path, my experiences living and travel abroad for ~10 years will serve (whether I like it or not) as the mental context and foundational inspiration for all of my work, technical or otherwise. I have spent quite some time trying to reconcile all the aspects of my life, only to realize that doing so is impossible, at least at this point in my state of <a href="/">consciousness</a>. As such, I will here be focusing primarily on technology and academia, and whatever tangential topics happen to be related to my academic journey. What I hope to achieve here is, well... nothing. I just want an outlet to express myself. And if, in the process, I am able to offer tips, guidance, inspiration, tools and/or resources to help others succeed in academia, that would be nice too.
<br>
<br>
<div style="font-style: italic;">
Tl;dr - I'll be using this site as a platform to share my research journey, but in a "meta" (not -verse) sense, i.e. all the aspects that go into a research career, minus the actual research, which will (ideally) be published self-evidently. </div>
<br>
<br>

<h2> Some Previous Projects </h2>
<br>

<div class="content-list">

<p >
<ul>
<li>
Prior to starting my PhD, I attempted to summarize the learnings of my decade of travel and life (mostly) in Asia put into the context of the post-pandemic world, via an online course: <a href="https://www.globalthinkingcourse.com">Global Thinking in the 21st Century</a>. Along with this, I created a life/mindset coaching business where I would train students in the mindset set forth in my course: <a href="https://www.nicksnomadlife.com/">Global Thinking Nick</a>. This initiative also included a language learning component my own systemized immersion methods meant to propel one to fluency in <a href="https://nicksnomadlife.com/you-dont-need-to-be-in-china-to-learn-chinese/" >Mandarin Chinese</a>. </li>
<br>
<li>
During the pandemic, after my master's and prior to starting my PhD, I started <a href="https://www.nickstravelworld.com">travel blogging</a>, to make use of the time in which I and millions of others were (and perhaps, still are...?) unemployable due to a crippled economy, and in my case, the added perk of being a "fresh grad". Along with this, I started a <a href="/reflection-project">Reflection Project</a> involving photography and reflective/philosophical writing pieces (some of which later became inspiration for the content found in my course, linked above)</li>
<br>
<li>
I have also done a bit of volunteer and freelance work for a handful of startup and farms, the outcomes of which shall remain with me, and not to be used as CV fodder.</li>
<br>
<li>During my masters, from September 2017 to December 2019, I worked on a startup-slash-research project attempting to solve the problem of low-quality news and misinformation on social media. The remnants of that project can be found <a href="inflo">here</a>.</li>
<br>
<li>
 The purpose of this blog is to express myself in a non-technical context, as a hobby, whereas my _actual_ career will highly niche and technical.</li>
<br>
 I'm also passionate about learning mandarin and photography.

</p>

</div>
</div>

<hr>

<div class="recent-entries-container">

<h1 class="center"> Recent Entries </h1>
<br>
<div class="recent-entries clearfix">

<ul class="list-reset post-list">
  {% for post in site.posts limit:4 %}
  <div class="post-preview post-preview-home sm-col sm-col-3">

    <li>

      <!--a href="{{ post.url }}"--><a href="/">
	  <div class="image-contain">
        <img class="featured_img-preview" src="{{ post.featured_img }}" /></div></a>

        <!--a href="{{ post.url }}"--><a href="/">  <h2 class="home-post-title">{{ post.title }} </h2></a>
      <div class="mt1"><span class="date-text">{{ post.date | date_to_string }}</span></div>
    </li>
	</div>
  {% endfor %}
</ul>

</div>
</div>
</div>
