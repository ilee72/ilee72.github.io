---
layout: project
type: project
image: images/hacc.png
title: HACC-HUI ICS 414
permalink: projects/hacc-hui
# All dates must be YYYY-MM-DD format!
date: 2020-12-13
labels:
  - Meteor
  - React
  - JSX
  - MongoDB
  - Hawaii Annual Code Challenge
  - ICS 414
summary: HACC-HUI provided an easy-to-use virtual registration and team formation system for the Hawaii Annual Code Challenge 2020.  
---
<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/haccLogo.png">
</p>

# Context to HACC 2020

The Hawaii Annual Code Challenge would bring approximately 200 developers every year. This amount of participants made forming teams a difficult task for participants and administrators. This obstacle became more apparent when the pandemic happened which resulted in no in-person meeting for [HACC 2020](https://hacc.hawaii.gov/). ICS 414 Software Engineering II was tasked by the hackathon hosts to build an application that allowed for easy registration and team formation for participants. This application used tool we used from ICS 314 including React, Meteor, MongoDB, and Semantic-UI. This was the first time ICS 414 would take on such a task and it was unprecendented. 

[HACC-HUI](https://hacchui.ics.hawaii.edu/)

# Team Deployments

At the beginning of the semester, we were split into teams of four to five. I was part of team MIJJ which had the first letters of our names from Manalu, Isaac, Joshua and Joel. During the first half of the semester, our team worked on milestone's with four to five issues with each being claimed by each member. We would use Discord to decide which issues we wanted and would then implement the issues by ourselves. If we ran into any issues, we would immediately ask for help on discord. The other members of my team did more of leadership and asking questions while I took requests. 

<img class="ui image" src="../images/teamPic.png">

This system went on for Milestone 1 and 2 when we were able to finish these issues and grab the best of the implementations from teams. However, due to time constraints and the inability to get the code from different sources to merge well, we eventually moved toward working from one master repository to ensure that there would be code interoperability amongst 20+ coders. Within this Final Sprint, we more or less broke our teams and started working on individual tasks from a large list of issues. Eventually, I cooperated with people with issues that were interconnected with mine. Communication became ad hoc with questions and I even went to other random members asking for advice on how to implement code to solve an issue. 

I became heavily invested in the implementation of the Slack bot and database so I worked heavily with Wei Mai who had experience with the database. At the same time, I had working accounts and could help provide quality assurance and testing for the database and Slack for Wei as well. Together, we were able to go over issues regarding the database as it was directly correlated with the Slack Bot's functionality which was what I focused on. 

# Milestones and Final Sprint

## Milestone 1
[Milestone 1 GitHub](https://github.com/MIJJ-HACC/HACC-Hui/projects/5)


[Milestone 1 Specs](https://hacc-hui.github.io/docs/requirements/milestone1)

For Milestone 1, I worked primarily on issue US-D4 Backend Create Team Page. I essentially created a page for the creation of a team by any user. This page would have fields for team leaders to fill out that would ensure that the name of the team, challenges, skills, tools, description, and availability would be shown for other participants to see. The page was very simple and plain as I focused primarily on getting the functionality rather than the look and style of the page. I had problems figuring out the database and how to ensure that the information filled out by the team leader would be saved.


## Milestone 2
[Milestone 2 GitHub](https://github.com/MIJJ-HACC/HACC-Hui/projects/6)


[Milestone 2 Specs](https://hacc-hui.github.io/docs/requirements/milestone2)

For Milestone 2, I worked on issue US-D6 Delete Team. I was to allow for only the team leader to see the team that he own and enable him to be able to delete his team. This meant that I made sure to check if the user was the owner of the team and that he could see the button. This ensured that no random person or teammate could accidently delete the team without permission. Next, I worked on making the button visible for the owner and that once he clicked the button, he would receive a warning of his permanent decision. Once he clicked the button, a sweet alert would confirm that the deletion was successful. 

## Final Sprint
[Final Sprint GitHub](https://github.com/HACC-Hui/HACC-Hui)

When it was realized that the difficulty of integrating the code of many teams into the master repo as well as the time constraints we faced, it was decided that all of us in the class were to work on all the issues at once and have access to one master repo. In essence, our entire class became one team to work on numerous issues. I worked primarily on the user interface design/style, integrating slack bot support with the application, and providing testing for other students like Wei Mai. 

First, I worked on the implementation of the slack bot with the application. First, I ensured that when the bot could not understand what the user was typing, the slack bot would then send out a automated message that provided information to the user on what keywords to say.

<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/dontunderstand.png">
</p>

Then, when the user used the right keywords such as "help" or "register", the bot would then provide the necessary information. If the user said "help", the bot would provide an automated message with a link to the help page of the website. If the user said "register", the bot would then provide the host domain url and their credentials for access to the website. 

<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/register.png">
</p>

Finally, Wei Mai and I worked on allowing the bot to alert a team owner or applicant on whether they were sent a invite or had a user wanting to join their team. We tested this to ensure that only the necessary participant would get this vital information. This required us to access the database of team owners IDs and applicant IDs. We would then print out the statement with the retrieved ID name. 

<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/teamrequest.png">
</p>

I then moved on from the slack bot integration to smaller issues regarding the style and visual look of certain pages. For starters, I ensured that the landing page footer had padding. 

Before:
<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/beforefooter.png">
</p>
After:
<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/afterfooter.png">
</p>

I worked on ensuring that the profile page had the contents not in bold. This required me looking at each category to unbold each one. Challenges, Skills, and Tools and different ways that they were bolded that required me looking through different pages and widgets to try and unbold them. 

Before:
<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/beforebold.png">
</p>
After:
<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/afterbold.png">
</p>

I finally worked on the admin view page,which showed all teams, to ensure that it followed the theme colors and style, looked more like a list, highlighted non-compliant teams (teams with minor participants), and other errors on the page. As you can see in the picture, I was able to successfully let the page fit the theme of the website as well as have all non-compliant teams be highlighted while not highlighting compliant teams. 

<p align="center">
  <img class ="ui large rounded image" width="460" height="300" src="../images/highlight.png">
</p>

# Conclusion
ICS 414's project was one of the most intense experiences to date. It was stressful trying to keep up with other schoolwork and then invest hours into trying to make an issue work. I felt that a quarter of the time was spent trying to make Meteor and React to work by troubleshooting;the other quarter was spent trying to research how to implement the functionality needed and that the other half of time was spent trying to make it work. The time constraints were definitely one of the hardest aspects of the work and it feels very closely to real world development cycles. I realized how I had to manage my time and priorities as well as rely heavily on my team and, later, other members associated to my tasks. 

I felt that the communication platforms such as Discord was far superior to Slack in that it allowed for Voice over IP calls within the platform. It was also more robust and simple than Slack which required lots of troubleshooting on my part. Additional functionality like the search bar which allowed me to look at past conversations or screen sharing was so useful. This convenience saved time and energy which outshined Slack. I would definitely recommend using Discord over Slack. 

This was an intense but rewarding project that had me proud of the work I did. I was able to show my friends, who were HACC 2020 participants, the work we did. Furthermore, it had motivated me to work harder on learning Javascript and other tools such as MongoDB and Semantic-UI. I wanted to match my peers who were able to complete their tasks with ease and I now want to get to their level. Overall, I feel that I accomplished a lot and I now have something to look back on after graduation. 

 
