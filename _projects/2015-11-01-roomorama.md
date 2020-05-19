---
title: Roomorama
subtitle: Vacation rentals in the travel space
date: 2015-11-01 08:00:00 +08:00
description: Similar space to other short term rental, roomorama was a space for hosts (owners) and guests (renters) to fulfil each other’s demand. We were however positioned slightly different that other players since it was a shift towards the B2B and B2C space as a property aggregator in recent years.
featured_image: roomorama-intro.gif
accent_color: '#d4222a'
project_id: roomorama
gallery_images:
  - roomorama-intro.gif
---

High intensity, fast paced, and working within a close neat team; [Roomorama](https://roomorama.com) is a place where the team took pride in what they do. It's a place I truly enjoy the international culture where almost each individual represents a nation on it's own. Travel and culture, what better way to have discover learning and insights every single day!

Similar space to other short term rental, roomorama was a space for hosts (owners) and guests (renters) to fulfil each other’s demand. We were however positioned slightly different that other players since it was a shift towards the B2B and B2C space as a property aggregator in recent years.

As with any role, the first was to inherit and get on-boarded to task at hand. However without a designer or proper documentation in place, it was my job to work with team to fully understood what the current challenges were. So I rolled up my sleeves and dig into the Rails backend for the first time, couple with multiple sessions of walking through the experience with the product manager.

{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/projects/roomorama-whiteboard.jpg,/images/projects/roomorama-plan.jpg,
	"
%}

### Structure, evaluate, and plan

I took this opportunity to put in place some level of documentation of all the userflows we had (aside from the usual code based wiki) as I capture the full scope of functionality we had.

![Roomorama site flows](/images/projects/roomorama-flows.gif)

##### Capturing multiple userflows

As the documentation was conducted, I worked with our data scientist to evaluate some of our analytics on conversations, drop offs, and anywhere we could identify as potential area. While at the same time ran some research to marry both the quantitative and qualitative data.


{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/roomorama-personas.png
	"
%}

##### Data became personas, for better relationship

As the challenges, became clear on what to focus on, the roadmap was better defined to solve for some of the key areas for both host and guests. Guest asked for clarity and transparency in content, hosts for easier inventory management. Both very different problem to tackle.

### First up, the hosts

![Roomorama sorting](/images/projects/roomorama-sorting.jpg)

*Sorting content hierarchy with socks on*

Sorting through all the data points revealed a structure has to be reworked to better surface important element to the both hosts and guests.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/roomorama-host.png,/images/projects/roomorama-host2.png
	"
%}

*Host dashboard before and after*

To ensure we deal with the source of the confusion, I focus on improving the flow of the host management tool. Incremental steps help solve for confusion and error, but also help ease the flow by giving plenty of breathing space for the host to focus on each task. Initial test show that hosts now spend **an average of 8 mins vs 17 mins** before to complete the basic requirement to host.

### Make it easy for guests


{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/projects/roomorama-guests.jpg,
	"
%}
*Property page before*

Realising that people where spending too much time browsing and hoping between with bounce at about 60-80%, it was down to 2 factors. People was either shopping around for prices, or they were not finding what they needed.

Changing the content hierarchy and surfacing easy to find information has helped reduce the bounce down to 40% and slightly bump conversation here. It was important to provide clarity on what a guest would be interested in, but the outcome was actually a realisation of the combination of those 2 factors, if I were to sum it up on a high level.

{% include post-components/video.html
	url = "https://player.vimeo.com/video/192870553"
	full_width = true
%}
*Property page after*


### Power of design framework

One of the thing that really allowed us to move quickly was down to the fact that I spent a lot of time to build a scalable and modular design framework. We had to refactor a lot of our code base using the ```Block--Element__Modifier``` (slightly modified) model.

The outcome was Aurora Design, as we slowly move away from larger more opinionated framework like bootstrap at the time.

Writing front end work was tedious and tough with a lot of the dependencies from the start, but as we work through and uncouple them one-by-one, we were able to work through stories after stories in a faster pace.

{% include post-components/video.html
	url = "https://player.vimeo.com/video/192872796"
	full_width = true
%}
*SVG animation experiments with velocity.js*

It helped us free up a lot more room to experiment and exploration, which was a huge payoff for the hours spent at the start.

Learning, planning, and executing. This was a great process to went through and one of the transformative journey in my career. I was fortunate to experience it, thanks to the awesome Roomorama team.

{% include post-components/gallery.html
	columns = 1
	full_width = false
	images = "/images/projects/roomorama-team.jpg,/images/projects/roomorama-travel.jpg
	"
%}
*Diverse working group and a fun bunch to work with*

