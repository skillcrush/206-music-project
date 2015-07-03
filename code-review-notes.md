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

- header
- nav
- main-content
- footer

Had to remove some css classes that should have been in v07.02

###v07.02

Add classes for a bunch of the various layout elements with percentages for widths, etc.

Cleaned up the branches and renamed the branch from v07.02b --> v07.02

###v07.03

Add in media queries for tablets and start writing styles to a bunch of sections.

.clear class actually showed up here so I am deleting it from here on out. Use the .clearfix class instead!

###v07.04

Students add in styles for desktop, it's still pretty plain...

###v08.01

Make sure to note to the students that the responsive images are not set up yet which is why things look cray cray!

Also, I am removing the .clear class, because HTML5 comes with .clearfix as a default style and it does what you are using the .clear class for! Going to make this edit throughout the branches.

###v08.02


###v08.03

