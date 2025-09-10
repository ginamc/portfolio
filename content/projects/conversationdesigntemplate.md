---
# title: Conversation Design Template
linkTitle: Cvent Assistant
toc: true
type: blog
draft: false
breadcrumbs: true
sidebar:
    exclude: true
---

# Cvent Assistant
<font size="3">
Cvent — June - September 2024<br>
Conversation Designer ⸱ Pattern Designer ⸱ Content Strategist<br>
</font>
<font size="2">CONVERSATION DESIGN ⸱ AI ⸱ PATTERN LIBRARY</font>

![Example of how the design iterations became the foundation for our AI pattern library. The skeleton of the chatbot was designed such that it can be adapted for a variety of uses, from standard conversation to generating content for social media, etc.](/images/convodesign/convodesign_pattern2.png)

<font size="5">Cvent was looking for ways to enhance product experience with the introduction of AI and chatbots in some key product areas. This project aimed to set the foundation for how to design chatbots and conversation design more broadly, and support designers in creating mocks for stakeholder presentations. This then became the blueprint for UX's AI chatbot pattern library.</font>

<p></p>
<p></p>

<hr>

<p></p>
<p></p>

## The problem
With increased interest in providing AI experiences, we needed a way to provide our product designers with a ready-made pattern from which to build chatbot interfaces. Up until this point, individual product teams were building the interfaces and experiences independent of each other resulting in a variety of solutions and approaches that lacked continuity across the product experience and Cvent branding.

## The approach
We can't design for the actual chatbot conversation, especially when we use LLMs instead of a direct script; however, we still want to be able to design the concept with a plausible conversation between a chatbot and its user. I wanted to provide a template with just enough conversation elements that covered as many flows as possible to give product and content designers a starting point for their designs.[^1] To achieve this, I needed to understand the goals for the chatbot, and the primary problem areas we wanted to solve with the chatbot in Attendee Hub.[^2]

### Workshops
I facilitated two workshops, and used Figjam to brainstorm and organize information.

|Workshop 1: Product Managers, Client Services, and Sales|
|:-----|
|Objective:<ul><li>Understand the business value and needs of a chatbot interface in the product</li><li>Understand how we talk about about Attendee Hub</li><li>Understand what kind of help attendee users typically seek.</li></ul> We discussed information categories that should be prioritized within the chatbot, and which categories were considered secondary and tertiary to the chatbot's purpose. This allowed us to map the different conversation flows[^3] and to prioritize the chatbot's primary function.<br>![Possible topics for each conversation flow.](/images/convodesign/convodesign_wkshp1.png "Figjam with ideas and topoics from Workshop 1.")|

|Workshop 2: UX Designers|
|:-----|
|Objective: <ul><li>Explore how information would be presented in a chatbot interface.</li></ul>We also discussed information categories but looked at it from an experiential perspective, namely, what's the best format to present certain types of information? How can we appropriately build engagement opportunities? How can we best support our users without introducing cruft and unnecessary interactions that might make the chatbot unusable?<br>![Possible experiences for each conversation flow.](/images/convodesign/convodesign_wkshp2.png "Figjam with ideas and topoics from Workshop 2.")|

**WORKSHOP SUMMARY**

| |W1 |W2 |
|:-----|:-----|:----|
|Hello flow|<ul><li>Sets the expectation for what the chatbot can do</li><li>Greet the user, preferably by name (personalization)</li><li>Help first-time and returning users navigate the event app.</li></ul>|<ul><li>Personalization, speak directly to the user</li><li>Communicate new features and guide them on how to use it</li><li>Encourage users to finish outstanding tasks (event profile, etc.)</li></ul>|
|Primary flow|<ul><li>Event logistics (WiFi passwords, accessing on-demand recordings, etc.)</li><li>Overview of event schedules, ability to modify a uer's schedule on the go, quickly connecting with others at the vent</li><li>Helping find information about registration, messaging others, and accessing event featuresin the app.</li></ul>|<ul><li>Assisting attendees throughout the duration of the event in various tasks, including finding information about the venue and its surrounding areas</li><li>Helping users understand the app's main features</li><li>Assistting users with session registrations</li><li>Providing recommendations for sessions, exhibitors, other attendees based on profile inforamtion</li><li>Assisting with basic troubleshooting issues with the app</li></ul>|
|Secondary|<ul><li>Low-hanging fruit tasks the chatbot can reasonably do with high success rates</li><li>Provide venue details, including directions on how to get there</li><li>Standard FAQs</li></ul>|<ul><li>Provide help with event sessions, including recommendations to fill up the user's event schedule</li><li>Provide details about the venue, including a map of room locations, bathrooms, etc.</li><li>Provide travel recommendations so user gets the most from the event</li></ul>|
|Catch-all and errors|<ul><li>System errors, connectivity issues</li><li>Communicating room and session capacities, associated fees with workshops and other session rules</li></ul>|<ul><li>Responding to language and terminology differences between an attendee and event organizer</li><li>Considerations for handling non-English language speakers who use the app</li><li>Ability for attendees to report inappropriate behaviors while attending the event</li><li>Providing the user guidance in cases where there are issues with registration, the venue or something else. If the chatbot is unable to help, the user should be given an option to reach out to the event organizer.</li></ul>|
|Goodbye flow|<ul><li>Sending event and session feedback surveys</li><li>Ability for attendees to communicate with planners</li></ul>|<ul><li>Collecting feedback to improve user experience</li><li>Allowing users' answers to be saved for future events</li><li>Post-event conversations to continue engagement and incite excitement for the next event</li></ul>|

### Design: Conversation
![Part of the Hello flow script](/images/convodesign/convodesign_script1.png "Excerpt of chatbot script flow.")

To create the script flow, I used the template provided by UXCC in its *Conversation Design for Chatbots* course[^1]. Before jumping into drafting the mock conversation flows, I did preliminary work to establish scope and set expectations for what this chatbot should do once built and deployed.

In steps 1-3, we determined which elements to include in our chatbot, and mapped out the primary actions, secondary actions, and catch-all and error handling actions. We also outlined the voice and tone of the chatbot. Doing this before designing the conversation allowed us to stay on track and stay aligned with the group.

![Bot actions](/images/convodesign/convodesign_script3.png "Identifying the actions our chatbot can do. This also acted as a task list to make sure we covered everything that was agreed to during the workshops.")

I then created tabs for as many known flows as we might have--though, because this was meant to be a template, it is not a total representation of a "complete" script flow. We just needed enough for designers to use to create plausible prototypes to present to stakeholders without going through the laborious effort of drafting a script each and every time they wanted to design a chatbot experience.

![Flow tabs (1a)](/images/convodesign/convodesign_script4a.png "First bit of the tabs with different conversation flows.")
![Flow tabs (1b)](/images/convodesign/convodesign_script4b.png "Second bit of the tabs with different conversation flows.")
![Conversation flow for FAQ](/images/convodesign/convodesign_script5.png "FAQ conversation flow. Includes notes that this isn't exhaustive but the general pattern can be reused as needed for other FAQ objects.")
![Error handling flow](/images/convodesign/convodesign_script6.png "Excerpt from an error-handling flow.")

### Design: Chatbot interface
To tie it all together, I designed a chatbot prototype using our Design System library. I explored key elements, including button iterations and how best to present certain types of information (e.g., FAQs, session details, maps, etc.).

![Chatbot design iterations](/images/convodesign/convodesign_pattern1.png "Design iterations for the chatbot--determining flow, interaction patterns, and presentation format for information. We explored interaction elements with quick reply buttons, information density, linked information (carousel, list, card, etc.), and so on.")

## Final output

### Chatbot pattern library
The design iterations became the basis for our AI pattern library, which has been widely adopted and used by designers across multiple products.
![Example of patterning chatbot designs](/images/convodesign/convodesign_pattern2.png "Example of how the design iterations became the foundation for our AI pattern library. The skeleton of the chatbot was designed such that it can be adapted for a variety of uses, from standard conversation to generating content for social media, etc.")

### Chatbot script template
The script I designed for this specific project became a mock template. Teams started using bits and pieces of the script as a way to populate their prototypes rather than trying to come up with their own elaborate conversation. This helped them get their concepts to stakeholders faster to facilitate discussion and decisionmaking for the final product.
![Returning user flow](/images/convodesign/convodesign_script8.png "Excerpt of the chatbot script. Shows the Hello Flow for returning attendee users.")

## Lessons learned
Applying what I learned in the UX Content Collective workshop was an object lesson. Sometimes, when you're given a template at a workshop, it's difficult to assess how and when to use that template in your own work. The template itself is relatively simple and easy to use but I found its application initially difficult. Once I figured out how to organize the conversation flows and had an idea of what pathways to pursue, the template became a lot easier to use--and revealed an important aspect of the project at large. It's easy for us to go straight into designing the interfaces but this project showed very quickly how untenable that approach was. Drafting out the script and, at minimum, 50% of the pathways was critical for helping visualize the UI for the chatbot. Without the script itself, I'm not sure we would've been able to design the chatbot interface pattern as quickly as we did. It also made it easier to discuss how to present certain types of information within the chatbot window.


[^1]: I applied learnings from UX Content Collective's [Conversation Design for Chatbots](https://uxcontent.com/conversation-design/) course.
[^2]: The project was completed as part of an exploration to support attendee users of [Attendee Hub](https://www.cvent.com/en/event-marketing-management/attendee-hub).
[^3]: Conversation designs have a foundation of 5 flows: (1) Hello flows greet the user and sets interaction expectations, (2) Primary flow consists of the main objective of the interface, (3) Secondary flow consits of elements that may not be as important as the primary but can still be considered within reasonable scope of the interface, (4) Catch-all and Error consists of scenarios that are absolutely not in the scope of the interface, as well as all error handling situations, and (5) Goodbye flow ends the conversation, either by directing the user to a human agent for additional support or closing the conversation because the initial problem was resolved.