# I've joined the #100DaysOfCode Challenge!

I forked this from: [Original Repo](https://github.com/kallaway/100-days-of-code)
And here is the [The #100DaysOfCode Official Site](http://100daysofcode.com/)

My goals for this challenge: :star:

- Become better with my front-end development skills
- Learn something new everyday
- Contribute to open source code
- Having something to do while under lockdown (thanks Coronavirus -- no I don't have the coronavirus!).

# 100 Days Of Code :sparkles:

### Day 0: April 4 2020

##### Project: rosalie.dev

**Today's Progress**: Scrapped redundant code, re-build CSS.

**Thoughts:** I struggled a bit with this rebuild in terms with, package versions and updating other packages and removing libraries that no longer serve the purpose. I have succeeded in making a successful build that was suitable for tomorrow's work. (1.5hr)

**Link to work:** [Rosalie's website](http://www.rosalie.dev)

### Day 1: April 5, 2020

**Today's Progress**: Added styled-components, fonts and redesigned the app using Figma.

**Thoughts**: Adding fonts was a bitch, but we got there. I used Styled components, and utilised ThemeConsumer and GlobalStyles properties to append styles/fonts to the NextJS app. Pushed these changes to master to reflect them in production.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 2: April 6, 2020

**Today's Progress**: Added the dark/light mode toggle using React Hooks and styled-components.

**Thoughts**: This was challenging to add with NextJS. To change the theme colors, I discovered that we had to append the theme colour scheme to the ThemeProvider which was in \_app.js. This worked successfully when adding in Header component inside \_app.js. I soon realised that this was not a sustainable idea and I discovered a bug when you refresh or first land on the website. I have an idea on how to fix this and will look at the issue closely tomorrow.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 3: April 7, 2020

**Today's Progress**: Dark/Light mode bug: on refresh.

**Thoughts**: I didn't write any code, but I have been doing more research into how NextJS handles state and I have an idea on how to fix this bug. I'd say today was not a code day, but rather a background research day. I had passover tonight and I couldn't code/work on this after dark.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 4: April 8, 2020

**Today's Progress**: Forked 100DaysOfCode repo and added my log notes, FIXED my bug!!

**Thoughts**: I couldn't write as much code as I wanted to tonight, because my family are doing some Easter things. I had instead, forked the 100 Days of Code repo and entered my logs for the past few days. I have also cleaned up the code on my website, but nothing much to commit here! Happy Passover! :heart:

EDIT: I managed to fix my Light/Dark mode bug on my website! It turned out that I needed to make the Header component and add all my logic for switching from Light -> Dark mode in there. I'm so glad i fixed this tonight!

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 5: April 9, 2020

**Today's Progress**: Added basic SEO, a Favicon and fixed some minor accessibility issues.

**Thoughts**: I noticed these issues arising so I have fixed some of these tonight. I added some basic SEO guidelines, added in an emoji Favicon and fixed up some minor accessibility issues. I'll be looking into how I may be able to reduce the loading time of the images.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 6: April 10, 2020

**Today's Progress**: Learning React Redux and making a simple TODO List

**Thoughts**: I was following a few tutorials, making a simple todo list app using react-redux, nextjs and the react redux nextjs wrapper. I will be working more on this project to expand it into a Goals app with more functionality than just a TODO list.

**Link(s) to work**: [Learning Redux repository](https://github.com/developerpeachy/learning-redux)

### Day 7: April 11, 2020

**Today's Progress**: Adding some styles to the TODO list tutorial i was learning Redux from.

**Thoughts**: I thought about adding some CSS to improve the usability of the TODO app, however, I got really busy today with personal and family commitments and decided to commit to 30 mins of coding today. I had only added some small CSS changes to the app.

**Link(s) to work**: [Learning Redux repository](https://github.com/developerpeachy/learning-redux)

### Day 8: April 12, 2020

**Today's Progress**: Added the styles to the todo list tutorial

**Thoughts**: I continued adding more styles to the TODO list tutorial, not that much progress today as I dont feel well (headache).

**Link(s) to work**: [Learning Redux repository](https://github.com/developerpeachy/learning-redux)

### Day 8: April 13, 2020

**Today's Progress**: Tried to deploy to now server, failed

**Thoughts**: I tried to deploy this onto a server and it didnt work, so I kinda gave up on the coding bits and decided to delve into Blockchain research for my next mini blog.

**Link(s) to work**: [Learning Redux repository](https://github.com/developerpeachy/learning-redux)

### Day 9: April 14, 2020

**Today's Progress**: I have started adding the bits for my blog feature on my website.

**Thoughts**: I am using Prismic with NextJS for my new serverless headless cms blog thing. This is more of an experiment, but if it works, I'll be happy.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 10: April 15, 2020

**Today's Progress**: I was able to successfully serve blogs from my prismic server to my nextjs blog :)

**Thoughts**: This was a bit of a workaround for me to get working, I had to make sure that I was mapping the right document types to the right places. Had to read the documentation to make sure it was right. Time to add more styling and support for images, quotes etc.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 11: April 16, 2020

**Today's Progress**: Style changes to website but failed to deploy to now server :(

**Thoughts**: This was so good at first until i actually checked my logs and realised that lol they BROKE so im going to have a go at fixing this tomorrow.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 12: April 20, 2020

**Today's Progress**: Fixed issues that accumulated over the weekend, fixed styling and published blogs

**Thoughts**: This was so good to fix tonight! all weekend I was a bit devestated that it didnt work out as expected, after researching what went wrong, I soon realised that there were a lot of case typings and typos in some of the components. I thought that ES Lint would pick them up but I soon realised that I had two linting things working at the same time on my IDE. Finally fixed and published the changes.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 13: April 21, 2020

**Today's Progress**: I added Prismic CMS to load all my projects and volunteering details.

**Thoughts**: I have been meaning to do this for a while and I finally got around to doing this. So now that Prismic is set up with all of my endpoints, I'm able to update and delete posts for projects and volunteering on Prismic. This means that I wouldn't need to load all my text and images statically from ./public. This will ease some performance issues I hope!

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 14: April 22, 2020

**Today's Progress**: I had started on fixing performance and styling issues

**Thoughts**: I have seen improvements in performance before and i want to continue doing that tonight. I have a migraine so im going to sleep early tonight. I had done some CSS and some accessibility fixes.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 15: April 21, 2020

**Today's Progress**: I made some changes to design and fixed accessibility issues.

**Thoughts**: Recycled components and styles so that every page had the same spacing and layout. I also fixed accessibility issues.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 16: April 22, 2020

**Today's Progress**: I did some design changes to my home page.

**Thoughts**: Learned a bit about Keyframes and CSS animations to do the gradient fill effect and animations.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 17: April 23, 2020

**Today's Progress**: I had to fix mobile version of my website

**Thoughts**: I somehow got the margins wrong on mobile and saw that this needed to be prioritised so I went ahead to fix, seems to be okay now.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 18: April 27, 2020

**Today's Progress**: I needed to get preview versions running on my website for blog drafts

**Thoughts**: I could not get this working so i will try tomorrow, but i have managed to update and make a new blog.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 18: April 27, 2020

**Today's Progress**: I needed to get preview versions running on my website for blog drafts

**Thoughts**: I could not get this working so i will try tomorrow, but i have managed to update and make a new blog.

**Link(s) to work**: [Rosalie's website](https://rosalie.dev/)

### Day 19: April 28, 2020

**Today's Progress**: I worked on my latest Instagram post which took some time into coding

**Thoughts**: I worked on coding at work all day so I thought I would blog today.

### Day 20: April 29, 2020

**Today's Progress**: I worked on work things, but also didn't want to fry my brain too much by coding more at night.

**Thoughts**: I worked on implementing new UI library things at work and I didn't feel like coding after work.

### Day 21: April 30, 2020

**Today's Progress**: I also worked on work things all day, didn't see much energy working on things after it.

**Thoughts**: I worked on implementing new UI library things at work and I didn't feel like coding after work.

### Day 22: May 1, 2020

**Today's Progress**: I rushed to get some features done for work so I did not bother coding on other things after work.

**Thoughts**: I worked on implementing new UI library things at work and I didn't feel like coding after work.

### Day 23: May 3, 2020

**Today's Progress**: I got myself a volunteering gig to clean and redo the UTS Playmakers website, so I'll be doing this!

**Thoughts**: Created a blueprint for the new UTS Playmakers website. I'll be working on this for a couple of days.

**Link(s) to work**: [UTS Playmakers's github](https://github.com/utsplaymakers)
