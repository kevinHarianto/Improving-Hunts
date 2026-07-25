---
title: How I'm Developing a Meaningful DFIR Software Project From Scratch (And How You Can Too) Part 1
date: 2026-07-21
draft: false
description: Your DFIR project development woes end now. Begin your journey with me and show your value to others in the community.
thumbnail: "/images/Pasted%20image%2020260721031637.png"
---
# Key Takeaways
1. It is always possible to identify opportunities in order to develop a meaningful programming project.
2. By focusing on and mirroring current DFIR workflows, I can identify friction points in the investigation process through personal observation.
3. This leads to identifying problems organically and smoothing out the experience instead of demoralizing yourself.
4. You do not need to feel discouraged if what you are developing already has multiple solutions that do similar things. As long as your project is created for a meaningful reason, it will be impactful to the community.

Many aspiring software engineers who want to get involved in the security engineering side try to brute-force their way into a potential project idea by simply copying others or using AI to think for them. But that won’t set you apart from so many others doing the same; you need to build something impactful in your area.

A lot of people struggle to come up with a meaningful software project idea; just search on YouTube and Reddit, and you can see countless interjections and desperate cries for help.

However, the ultimate way is to first identify the underlying issues that your development skills can help with.

In this article, I will be sharing an example of how you could come up with that meaningful software project, all the way to development, where in this part, I will be covering the actual creation of the idea. The thing that stumps countless people.

# Why Develop Your Own Project Idea Through Personal Experience?

[Source](https://www.pmi.org/learning/library/impact-project-benefit-methodology-accountability-6446)
![Image Description](/images/Pasted%20image%2020260712054454.png)

**Demonstrating Your Potential Impact:** By highlighting your abilities to identify possible improvements in the DFIR Workflow (or your own/personal life), it flags to potential recruiters how you are able to apply your thinking to improve their processes as well.

**The Bridge to Networking:** Through the YouTube video [Lattice’s Advice for CS Students](https://www.youtube.com/watch?v=RoW5E-HGP5Y)(and countless others), he highlights how sharing your project (even just the progress) already grants you something to talk and connect about.

**Entrepreneurship Potential:** Your meaningful open-source projects can spiral into something much more profitable, such as the story[ of Grafana,](https://grafana.com/blog/the-story-of-grafana-documentary-the-business-of-open-source/) where Grafana initially started as a simple free project designed to solve a problem personally experienced, but with passion, it grew into something bigger.

**It's just simply more fun:** By working on something more personal to you, your project becomes so much more than “just a to-do app or Tic-tac-toe” but something that would improve your life (and others in the same boat).

[Source](https://www.michaelpage.com.au/advice/career-advice/career-progression/top-12-benefits-networking-why-networking-important)
![Image Description](/images/Pasted%20image%2020260712055620.png)

# How I Found a Meaningful Idea (and How You Could As Well)

**The Initial Hypothesis:**
By working on the Mosse threat hunting certificate with my initial goal to further advance my hunting abilities, Source: [Mosse Threat Hunting Certificate](https://www.mosse-institute.com/)-, I noticed how obtrusive it was to investigate multiple Windows Sysmon Event logs together.
![Image Description](/images/Pasted%20image%2020260712193834.png)

**The Search for Pre-existing Solutions:**

1. EventLogExpert: known for multi-log analysis, did not function well in terms of displaying the large sets of data efficiently, with multiple errors being observed in terms of displaying the data directly in the table. [Event Log Expert](https://github.com/microsoft/EventLogExpert)

2. The default Event viewer: is super small and annoying to filter through and view the information related towards the compromised device. Especially brutal when comparing and quickly scrolling through a lot of evidence.

3. Other solutions like Chainsaw is powerful; however, due to a lack of GUI elements, it was harder to scroll through more massive amounts of data quickly without knowing what you want first. [Chainsaw](https://github.com/WithSecureLabs/chainsaw) Plus, I would prefer something more intuitive in a GUI format, such as for scrolling across vast amounts of information.

**The Inspiration**: 
1. **Improved Filtering Capabilities:** From XSOAR XDR or Strata Logging Solution, due to how easy it is not having to study or research how I could filter for certain events and immediately was able to jump into it.
2. **Higher view against Abnormalities:** From Process Monitor, I was impressed with how I was able to quickly take note of odd processes occurring, which would be relevant to incorporate.


**The Solution:** I will be developing software with simplicity in mind to execute simply the quick and rapid filtering of event data without being so cumbersome to use and glance over large amounts of information across multiple logs, with direct inspiration from Eric Zimmerman’s toolsets (Timeline Explorer). You can check here [Eric Zimmerman](https://ericzimmerman.github.io/#forensic-tools).

![Image Description](/images/Pasted%20image%2020260715043907.png)
# Ready to Make an Impact? Here's Your Next Step

**Getting your first Idea:** By immersing yourself in the DFIR workflows (Labs, CTFs, etc.), keep notes of any limitations and restraints that you experienced during the investigative process.

**Finding that “Impact” you can make:**  
Especially if you had to “settle” for one or were forced to use multiple tools in a “clunky” manner.

**Putting it together:**
1. When setting up a nested Virtual Machine in order to dynamically collect malware information for CAPE Sandbox in regards to a lab.
2. You have noticed how cumbersome it is to set it up and how you were not able to do so due to your PC not being strong enough.
3. **The Impact:** You can develop an open-source local software that dynamically collects  information like CAPE Sandbox, but is easy to launch and does not require a powerful PC.

# What's next: Writing the User Stories
After identifying a single (or multiple) possible solutions to make your work easier, begin the creation of the User Stories.

This allows you to establish a legitimate reason for being:
![Image Description](/images/Pasted%20image%2020260712053215.png)

Where I will be going through the motion with an example as per [How I Plan My Coding Projects - 9 Steps](https://www.youtube.com/watch?v=AGWyx96lP8U) in Part 2. This channel is known for providing guidance on project development.
