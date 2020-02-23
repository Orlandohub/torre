# Torre
<hr>

## Challenge

One big issue digital social platforms, of all kinds, face nowadays is identity theft.
<br>
Whether we are looking into personal day-to-day platforms as Instagram / Facebook or professional platforms such as Upwork / Freelancer, identity theft plays a major role on the list of concerns this kind of platforms need to address to provide their users a safe environment to promote themselvs and / or their business.
<br><br>
Once I was presented the opportunity to develop a feature with Torre data, identity theft came across as the first thing I would like to test so I could be rest assured users could safely promote themselves whithout fear of being victims of plagiarism.
<br>
I started by creating a new account with a different email and successfully added same profile picture, name, linkedin & personal website links without a problem. This demonstrated how easy it would be for someone with the wrong intentions to simply copy my profile and start using the platform.
<br>

## Solution

With this feature I'll attempt to start what could later on become a full fledged peace of software which would provide administrators at Torre (or some AI module) flags which would alert them when we believe duplicate accounts are created.
<br><br>
For simplicity sake due to the nature of this project and the limited time we have, in this project we will focus mainly on the uploaded picture of users, feed them into a AI face recognition module and later on look for matches. If the same face appears more than once we will flag it and leave a notification for administrators to analyse later on. Manually the administrators could investigate if links such as LinkedIn, Github or personal website are duplicated as well and have enough info to take an educated decision.

## Tech Stack

- Python / Flask / Heroku: Microservice responsible for face recognition
- React / Creat React App / Netlify: User interface