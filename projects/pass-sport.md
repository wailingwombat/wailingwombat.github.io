---
layout: page
title: PassSport
---

![pass-sport](/images/bigshots-pass.png)

**Project**: An iOS App [demo](https://app.atomic.io/d/aW2RvfdaIzyT) for US college sport recruitment, connecting international students with US coaches. This was a side project to help my friend jumpstart her app development. .

**Goal**: Create a hi-fidilty demo (including interactions and screenflow) so that developers can use as a jumping point to create the backend.

**Role**: Designer

**Process**:

1. **Research**: For design I looked at several sports recruiting apps (NCSA, BeRecruited, RecruitU, Lemonaid, JumpForward). This was a sports apps, this is very stats heavy and every competitor application I looked at had long clunky forms. We chose the most popular sports to start with. ![pass-sport](/images/stats1.png)
![pass-sport](/images/stats2.png)
![pass-sport](/images/stats3.png)

2. **Wireframing**: These were already created when I started helping. So I took what was already created updated design elements I thought were not user friendly (buttons too close, screen flows that didn't make sense etc).
![pass-sport](/images/wireframes-pass.png)

3. **Insights from Wireframes and Research**

  - **Content Issue**:  This app was all about sports statistics and would have many forms for users to fill out. In addition, each sport had its own set of statistics, therefore the wireframe would need to actually have the correct content mapped out before designing. Lorem Ipsum was not going to cut it.

  - **Form Filling Issue**: related to the first point, because of the extensive amount of data a user had to provide, how the forms were design was crucial to the user experience.

  - **Readbility Issue**: To connect coaches and students, users would need to compare stats therefore, displaying the information side by side in a small screen will have readability issues. I did suggest with something so content heavy it would work better on a website format (she later did pursue this route).

4. **Screenflow and Content**: I had my friend work with me through all the content that needed to populate the app and exactly where the information would reside.

5.  **Prototyping**: I wanted to be able to convey interaction so I ended using atomic.io since it was less limited than InVision. Below were some highlights for the reasoning behind the design choices.

  - **Data Visualization**: I had to account for the list length variability, there is content that is quite long which mean I had to balance readbility with screen real estate.

  - **List Views:** There were a couple of options for list views, experimenting with a bunch of layouts, the main thing I want the list to be is readable since it's such a large list of items, scannability for the user on the mobile is important. One option has alot of white space, the other is optimized for quick scan but looks bad, and the last one is looks more consistent but I suspect there's more scanning since the items are too far apart.

  - **Comparing Coaches**: I liked how the [Apple website](https://www.apple.com/mac/compare/) did the guided selection for comparing apple products, so I used that, I have not seen it on mobile, but I thought it would help users understand that you were limited to two coaches to compare.

  - **Exploration Page**: I wanted this page to be a quick browse of all the coaches/athlete so I made them into tiny profile cards, two horizontally. This might be problematic in the future because there's no way to discern why a coach would favourite a player with only their profile picture and the city and country they are in. This will likely need to be rethought. The althernatives are single profile view with more information, or a list view with information spread out horizontally. Below are some older iterations of the design.
![pass-sport](/images/older-designs-pass.png)


**Final Output**:
See the [demo](https://app.atomic.io/d/aW2RvfdaIzyT)

**Learnings**:
- You should always **design around the content**, and in this case for a sport application this was especially important since the information is the main thing you are showing to the user.
- **Generate realistic dummy data** this helps you see the variability in lengths
Keep it simple and readable, instead of trying design my own forms like the other applications, I used iOS designs which has been vetted for and more familiar to a user
- Work with your friend/stakeholder/client on what they want by **working on paper first**, this way you can quickly weed out the bad ideas, or figure the technical constraints so you’re not designing for something unrealistic
