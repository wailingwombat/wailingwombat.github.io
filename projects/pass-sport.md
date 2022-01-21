---
layout: page
title: PassSport
---

![pass-sport](/images/bigshots-pass.png)

**Project**: An iOS App protoype (done in Atomic prototyping which has now been closed down). The app connects international student athletes with US coaches for college sports recruitment. This project helped the client better understand her app and vet the overall idea before committing significant resources to develop an entire mobile application.

**Goal**: Create a hi-fidilty prototype that a developer could reference while building the real app.

**Role**: Designer

**Process**:

1. **Research**: After some competitive analysis, I found that the main design issue with sports recruiting apps is that they use long and clunky forms. For example, fields are often too small and dropdowns are too wide. During the design process I focused on making the forms as user-friendly as possible.

2. **Wireframing**: When I began working on the project, wireframes had already been created. I updated the the elements that were not user friendly like cramped buttons, illogical screen flows, etc. The wireframes used placeholder text; however, because the app is meant to display a significant amount of specialized data, sports statistics and academic credentials, I updated them to use realistic dummy text. With the text in place, I then rearranged the UI elements to accommodate it.

3. **Insights from Wireframes and Research**

    - **Content**: Because sports recruiting apps are very text heavy, going forward I needed to make sure that the content is the first consideration in every design decision I make.

    - **Forms**: Because the content in the app is all provded by the user, the design of the forms is crucial to the user experience.

    - **Readability**: One feature of the app is the ability for coaches to compare students side by side and vice versa. I had to consider readability issues when displaying statistics side by side on a small screen.

4. **Screenflow**: I worked with the client to create the user journey from sign up to matches between coaches and students. This helped her better understand the product she wanted to create and the users.

5.  **Prototyping**: Below are some highlights for the reasoning behind the design choices.

    - **Lists**: I had to account for the list length variability. Some lists were significantly longer there were content that is long which mean I had to balance readbility with screen real estate.

    - **Comparing Coaches**: I liked the guided selection for comparing products on the [Apple website](https://www.apple.com/mac/compare/). While I had not seen that experience on a mobile site or app before, I thought it would help the users understand that they were limited to comparing two coaches.

    - **Forms**: Instead of trying to design custom forms like the other recruiting apps, I used standard iOS form components which have been vetted with research for usabiltiy and are familiar to users.

    - **Exploration Page**: I wanted this page to be a quick browse of all the coaches and athletes so I displayed them as profile cards. The small cards by themselves do not contain enough information so the prototype has a force-touch/long-press functionality that will pop open the card to show more information. Althernatively, a single column list view with larger cards containing more content, or removing the profile picture in favor of statistics could solve this problem. Removing the pictures could reduce the chance of someone selecting a profile based on superficial factors. Below are some iterations of the design.
![pass-sport](/images/older-designs-pass.png)


**Final Output**:
See the ~[demo](http://bit.ly/PassSportPrototype)~ (done in Atomic prototyping which has now been closed down)
![pass-sport](/images/passport_overview.gif)

See the Pas-sport [social media](https://www.instagram.com/passportathlete/?hl=en)

**Learnings**:
- **Design around the content**. In this case of a sports application this is especially important since the content is the value proposition.

- **Generate realistic dummy data**. Seeing templates filled in with content of variable lengths can help expose the weaknesses of the design.

- **Don't reinvent the wheel**. Use the standard design experience when possible because it is backed by research and familiar to users.

- **Work on paper first**. You can quickly weed out the bad ideas and figure out the technical constraints so you don't waste time. For example, my client wanted the app to include a way for students to upload a sports reel video. Because hosting video is difficult and expensive, I suggested that the app should simply allow students to include a link to a video on their profile.
