<p> 
See my 2 Design Studio PDFS (1 the scanned form, and the other typed notes) in addition to the screenshot
of my Problem 2 visualization, with the massive d3.js data that I took (showing that my Problem 2 
implementation is not good for displaying a massive dataset.) 
</p>

<p>
From the Lee paper, the current visualization is not very good at filtering or sorting; it's inherently bound to a display by time (i.e. the scale is adjusted to time) or by a fixed distance (which is still time, but advances by commit, not whether events in the interim took place over a day, a week, or a month.) So, I am looking to work on that for Problem 4.
</p>

<p>
d3, jquery, and bootstrap all have much more volume of commits, and additionally many more users who have contributed unique repos to the projects (i.e. they have many more rows of user names than, say, caleydo does.) What this means for displaying that information, is that a large group of users with many more commits is unwieldy to take a "Big Picture" of, with respect to time. So, for my visualization I am eliminating that component to try to look at individual contributors, as opposed to at commit-centric visualization which the Github Network Graph proudly is.
</p>

<p>
For more details on how Lee's paper and extra data affect my proposed visualization, see the Design Studio materials, and additionally my Problem 4 explanation where I explain the design choices -- the ideal version, and what I was able to realistically accomplish given my novelty to the language.
</p>
