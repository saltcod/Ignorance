Ignorance
=========

A bookmarklet to help tone down the pervasive ignorance on Youtube.

Youtube is (mostly) a hate-filled cesspool of ignorance. This tiny project is a bookmarklet to help this in check. 

Installation
============

  1. Create a new bookmark in your bookmarks bar. 
  2. Name the bookmark Ignorance or whatever you like
  3. Paste the contents of Ignorance into the URL field: <img src="http://f.cl.ly/items/2k050c2h1J1U1h3L2q41/Screen%20Shot%202012-12-27%20at%2011.05.14%20AM.png">
  4. Click the Ignorance button while watching a video and watch the trolls just fade away!

Customizing
============

This bookmarklet hides the comments and the sidebar. You'll likely want the comments to hide, but may want to keep the sidebar recommendations. To do that, just remove the 'watch7-sidebar' part of the code (don't forget to remove the comma as well) so that it looks like this: 

<pre>
var ids = ['watch7-discussion']
</pre>

