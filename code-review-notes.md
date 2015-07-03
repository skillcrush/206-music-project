#206 Music Project Code Edits

This is an overview of the edits I am making to the 206 music challenge project

###v06.03
Changing the logo to H1 (it's semantic!)

###v06.04

In this instance:

```
<a href="#"><div class="btn">See All</div></a>
```
The div is actually unneccesary, so I edited it to this:

```
<a href="#" class="btn">See All</a>
```

###v06.05 & v06.06
On the news detail page:

```
<h1>Wilco Announces New Album and Summer Tour</h1>
<p>Author Name  |  June 09, 2015</p>
```

An h1 is right, but since the logo is the h1 it conflicts UNLESS, you wrap it in a header element since every header can have an h1:

```
<header class="article-header">
    <h1>Wilco Announces New Album and Summer Tour</h1>
    <ul class="article-meta-info">
		<li class="article-author">Author Name</li>
		<li class="article-pub-date"><time>June 09, 2015</time></li>
	</ul>
</header>
```

I also changed the article info to a ul, since it's a list of info (you can style it to look however you want), gave each section a class related to it's content and also added the time HTML5 tag for the time element.

[This is a good stack overflow thread that discusses an example very close to this one.](http://stackoverflow.com/questions/7290504/which-html5-tag-should-i-use-to-mark-up-an-author-s-name)

###v07.01

Add percentages to header & footer (those are good)

There are also a bunch of classes added to the main.css --> this should be added to the challenge

###v07.02b

###v07.03

###v07.04

###v08.01

###v08.02