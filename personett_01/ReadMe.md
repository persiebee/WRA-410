<--* Instructions *-->
There are two stylesheets - good.css, and bad.css.

Your job is to make two different menus using the same valid HTML5 <nav> element structure:

one that looks good and behaves well, and
one that should be as ugly and unusable as you would like it to be.
You must use at least one CSS transition in each CSS file.

Please detail your process, any people you may have worked with, specific tutorials that may have found useful, tales of your interactions with AI, or anything else you might want to document in the space below.

Not including this part will instantly cost you 10 points:

<--*Read Me Notes *-->
~! I first started with looking through the provided CSS and HTML for the good section, working from the previous lecture I started to play around with the CSS to get understanding of what does what. Then I started to make some permanent changes as I decied the colors I wanted and alignment of things. Though I did get tripped up a couple of times when coding the CSS on which section was for the small and large screen but the fixes were easy. Once I was happy with the CSS layout I then thought about what to do for my CSS transision. At first I wanted to make the hover options pop closer to the user when hovered but in trying to do so it just looked very back and was very hard to use. So next I came up with the Idea of adding images to spin as I thought that would be super fun but also easy to accomplish, I looked up how to accomplish this and found a couple of recourses but ended up just using the google AI search as it was right there when I looked it up. So I took that CSS and found some cute images to apply it to, as well made sure to make it also reactive to the screen size. 

~! for the bad CSS and HTML section I just took what I had from my good section and started to mess around with it, I changed all the colors to really ugly ones and found a very ugly and hard to read font. I also changed out my photos, they were too cute. I started to mess around with my transitions that I used for my good HTML and CSS for the bad one making stuff spin like crazy. I also tilted things and made the proportion of text and flex boxes very weird. I really liked the spinning and wanted it for my nav bar but sense this was the bad version I really didnt want to spend the time figuring out how to do it, so I just asked claude how to make it; which is this code: 

nav ul:hover {
	animation: spin 1s linear infinite;
}

@keyframes spin {
	from {
		transform: rotate(0deg);
	}
	to {
		transform: rotate(360deg);
	}
}

I think it came out very bad but TECHNICALLY still usable which I think is even more funny.