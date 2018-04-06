---
layout: page
title: PassSport
---

![pass-sport](/images/bigshots-pass.png)

**Project**: An iOS App [demo](https://app.atomic.io/d/aW2RvfdaIzyT). The app connects international students with US coaches for college sports recruitment. This was a side project to help my friend jumpstart her app development.

**Goal**: Create a hi-fidilty demo (including interactions and screenflow) so that developers can use as a jumping point to create the backend.

**Role**: Designer

**Process**:

1. **Research**: For the design I looked at several sports recruiting apps (NCSA, BeRecruited, RecruitU, Lemonaid, JumpForward). This was a sports apps, this is very stats heavy and every competitor application I looked at had long clunky forms. Based on research we chose the most [popular sports](https://www.ncaa.org/sites/default/files/2017INC_FOR_Research_to_Better_Understand_the_International_Student-Athlete_Experien_20170524.pdf) to start with.

2. **Wireframing**: The wireframes were already created when I started helping. Starting from there I updated the design elements I thought were not user friendly such as buttons being too close, screen flows that didn't make sense, etc.
![pass-sport](/images/wireframes-pass.png)

3. **Insights from Wireframes and Research**

    - **Content Issue**:  The majority of the app's content would be sports statistics. This information, in addition to academic information would be required to filled out by the user. Each sport would also have it's own set of statistics, therefore the wireframe would need realisitc content mapped out before designing. Lorem Ipsum was not going to cut it.

    - **Form Filling Issue**: Related to the first point, because of the extensive amount of data a user had to provide, how the forms were designed would be crucial to the user experience.

    - **Readbility Issue**: To connect coaches and students, users would need to compare stats, displaying the information side by side in a small screen will have readability issues. I did suggest early on that with an app so content heavy it would work better on a website (she later did pursue this route).

4. **Screenflow and Content**: I had my friend work with me through all the content that needed to populate the app and exactly where the information would reside.

5.  **Prototyping**: Below are some highlights for the reasoning behind the design choices.

    - **Data Visualization**: I had to account for the list length variability, there were content that is long which mean I had to balance readbility with screen real estate.

    - **List Views:** The main priority I had for the list view was readable, and scannable for a mobile device.

    - **Comparing Coaches**: I liked how the [Apple website](https://www.apple.com/mac/compare/) did the guided selection for comparing apple products, so recreated that experience. I haven't seen that as an interaction on a mobile device before, but I thougt it would help the users understand that they were limited to two coaches to compare.

    - **Forms**: Instead of trying design my own forms like the other recruiting applications, I used iOS standard design which has been vetted with research for usabiltiy and would be more familiar to users.

    - **Exploration Page**: I wanted this page to be a quick browse of all the coaches/athlete so I made them into tiny profile cards. This could be problematic in the future because there's no way to discern why a coach would favourite a player with only their profile picture and the city and country they are in. This will likely need to be rethought. The althernatives are single profile view with more information, or a list view with information spread out horizontally. Below are some older iterations of the design.
![pass-sport](/images/older-designs-pass.png)


**Final Output**:
See the [demo](https://app.atomic.io/d/aW2RvfdaIzyT)

**Learnings**:
- You should always **design around the content**, and in this case for a sport application this was especially important since the content is the value proposition.

- **Generate realistic dummy data**, this helps you see the variability in lengths when you design

- **Don't reinvent the wheel**, use the standard design experience when possible

- Work with your friend/stakeholder/client on what they want by **working on paper first**, this way you can quickly weed out the bad ideas, or figure the technical constraints so you’re not designing for something unrealistic. For example, she wanted to design a page to allow students to upload a sports reel video. I told her it would be better to allow the students to add a link from youtube/vimeo/etc. since you probally don't want to deal with hosting video content or risking a bad experience playing the video in-app.
