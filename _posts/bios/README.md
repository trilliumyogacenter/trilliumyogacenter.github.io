This "bios" folder contains posts that represent teacher and counselor 
biographies on the website.

Each file contains one biography.

Each file starts with a header section, that looks like this:

---
title:  "Name"
date:   2015-07-01 12:00:00
categories: 
shortname: 
headshot: 
---

The "Teacher Name" should be replaced by the name of the person. The date is largely 
irrelevant - you can more or less put anything. I created all the bios with the date:
"2015-07-01 12:00:00" which was chosen rather arbitrarily.

The "categories" line should contain:
	1) "teacherbio" if you want the bio to appear under the "Teachers" section
	2) "counselor" if you want the bio to appear under the "Counselors" section
	3) Any other single-word value you think is relevant (see existing bios for examples)
	
The "shortname" is the person's last-name. This is used to alphabetize the profiles on the site, 
and also to cross-reference the bios so they can be linked properly in the schedule.

The "headshot" is the image that will be displayed in the biography's thumbnail. For example, 
the headshot value in Terry's bio is: "/images/delavega.jpg" since that is the path to her 
photo.

Any content you put below the header section (delimited by the "---"'s) is the bio content, and
should be formatted using "markdown" syntax.