---
layout: post
title:  "Sit down and think what features to remove"
categories: software
author_name : Ville
author_url : /author/ville
author_avatar: ville
show_avatar : false
read_time : 34
feature_image: feature-orava
show_related_posts: false
square_related: recommend-wolf
excerpt_separator: <!--more-->
---

Success of a software product is hugely dependent on ability to change and improve it during its lifetime. You want to minimize the time, effort and cost to further develop and improve your product starting from the first early release. This is usually obvious to everyone. But there are other aspects and not all of them are equally obvious.

There is a huge life-cycle cost and burden in software complexity. Simple, clean design and good engineering practices help alot. But there is one central point where things get serious: **More software you add the more complexity you get.**

In addition to great engineering practices you need *a strict culture of adding only the absolutely necessary features and evaluate their value all the time*. Like many of the things in software development this is nothing new. Just look at the mindset of the early Unix developers [^1]:

> Everything was small... and my heart sinks for Linux when I see the size of it. [...] The manual page, which really used to be a manual page, is now a small volume, with a thousand options... **We used to sit around in the Unix Room saying, 'What can we throw out?** Why is there this option?' It's often because there is some deficiency in the basic design — you didn't really hit the right design point. Instead of adding an option, think about what was forcing you to add that option.

Have you tried sitting down with your team to think what features to throw out? If you haven't, do it right away!

All professionals would like to create simple and elegant solutions. But as a industry we follow a very different mindset than the people quoted above. 

* Our prevailing contracting models often dictate big upfront design with late big batch deliveries. 
* Long delivery cycles make iterating on small valuable items impossible. 
* Feature creep is incorporated deeply in "list all the requirements and get them right in the first place".
* And with detailed plans made before the first phase-gate, all you need to manage is the 100% efficiency and follow the plans. 

It's a problem deep the mindset and habits of our industry. 

But you, a software development professional, want to do better and optimize long-term benefits to keep productivity high and costs low. That includes explaining your customer that **"we are going to deliver as little code and features as possible and that is for your benefit".**

---

[^1]: Bill McGonigle, [Ancestry of Linux - How the Fun Began.](https://archive.org/details/DougMcIlroy_AncestryOfLinux_DLSLUG)