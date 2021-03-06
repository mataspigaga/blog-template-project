---
title: '#100DaysOfCode'
date: 2021/9/02
description: Follow my journey here and on Twitter.
tag: Learning
---

# #100DaysOfCode

Follow the journey on [Twitter](https://twitter.com/mataspigaga)

_I'll probably arrange this in reverse chronological order after a few more days. Or figure out how to sort it with a button... that'll be fun._

## Day [1/100]

- September 2nd, 2021
- Time spent: 3 hours
- Main project: Building a very basic cryptocurrency named MatCoin
- **Takeaways:**
  1. The source code/algorithm is not the same for Bitcoin and Litecoin.
  2. An understanding of the underlying tech is not essential, so I'm now wary of any altcoins I see.
  3. This technology is **really exciting**, I'm quite interested in seeing how this algorithm works under the hood.
- **Challenges:**
  1. Never written anything in C or C++, had to very closely follow the tutorial to avoid syntactic errors.
  2. Still researching the economic implications of mining limits.
  3. Understanding how to start something like this from purely following the breadcrumbs rather than a step-by-step tutorial, but I think that comes with time.

## Day [2/100]

- September 3rd, 2021
- Time spent: 3 hours
- _No main project_
- Spent too much time on figuring out the crypto code until I decided to take a simpler approach. That led me down a road of learning about the various wallets and exchanges, but I'm locked out of deploying the code until the funds clear.
- Spent the rest of the time focusing on sharpening my JS skills, I think that'll really improve my React.js understanding.
- Built a simple drum kit on a static page using JS, using [#JavaScript30](https://javascript30.com/)
- **Takeaways:**
  1. It's important to set out a roadplan for the day of learning and/or building. Otherwise, you'll get lost chasing links and ideas.
  2. You can write JS scripts right in the HTML file. In reality, I breazed by JS months ago and went straight to React.js, this is really making things click already.
  3. I need to be using console.log() way more than I have been during practice projects. The course made it clear how he got from just listening to an event to the final result.
- **Challenges:**
  1. Figuring out how to deploy a static site using Vercel. Ideally, I would want to have all of these challenges either part of this site or easily linked.
  2. Trying to understand how the file structure needs to be laid out for deployment.
  3. (Crypto Project): A greater understanding of Solidity and in general blockchain will allow me to feel confident on creating an ERC-20 token.

## Day [3/100]

- September 4th, 2021
- Time spent: 1.5 hours
- Main project: Built a simple JS/CSS powered clock
- **Takeaways:**
  1. You can directly interact with CSS from a JS file, updating very quickly.
  2. It's very convenient to modify CSS attributes in the 'inspect element' section of Chrome Dev Tools to figure out a Bezier curve for a transition, for example.
  3. Many beatiful features of a website take **so little code** to implement.
- **Challenges:**
  1. Modifying the existing CSS to make the hours hand smaller. Couldn't figure it out in the time I was working.
  2. How to add these functions within a React component.
  3. I spent the first part of this session looking into how this blog's underlying code works. I'm not really understanding how Nextra is built based on the provided documentation. Then I looked into what it would take to build this exact site out from scratch, importing MDX functionality myself. I think that'll be an instructive journey.

## Day [4/100]

- September 5th, 2021
- Time spent: 1 hour
- Main project: Built a test page for CSS variables
- **Takeaways:**
  1. Data attributes. You can create your own attributes so that for example you can add a 'px' suffix to a value being updated.
  2. I'm less timid about updating CSS selectors to make the page fit my needs.
  3. I looked through the addEventListener documentation and saw a simple build of drawing with JS and CSS.
- **Challenges:**
  1. Figuring out how to make the color wheel update realtime like the input sliders.
  2. Not sure if it's possible to make the spacing slider go off screen in all directions rather than extend into the bottom right.
  3. Still not 100% on the uses of the dataset attribute.

## Day [5/100]

- September 6th, 2021
- Time spent: 3 hours
- Main project: Practiced array methods / Flexbox and JS
- **Takeaways:**
  1. The array methods haven???t made this much sense to me, mainly because the challenges I???ve done in the past combined too many concepts at once.
  2. It???s relatively simple to create animations by implementing event listeners on elements with transform attributes using flexbox.
  3. Gatsby.js seems like a good framework to explore for building out the portfolio since it has faster static site generation, lazy loading, and it populates the page with the HMTL/CSS before hydrating the rest of the function.
- **Challenges:**
  1. The flexbox challenge already had some of the CSS prebuilt which makes it so it doesn???t 100% click on how the transformations were set up.
  2. The array methods made sense when using local data, but I can???t really picture moving to external data or even markdown file names which is the goal.
  3. Timing and consistency were something I was definitely struggling with yesterday. Although I have a pretty rough sleep schedule, I still feel like I could have doubled or even tripled the amount of time I spent on this yesterday. As the evening hit, I lost my energy to keep going, which I can see hindering me in the future. I might try to work in a well lit place at night when this happens again.

## Day [6/100]

- September 7th, 2021
- Time spent: 1 hour
- Main project: AJAX type ahead form
- **Takeaways:**
  1. This is by far the best understanding I have had of the fetch API because I console.logged every step of the way. Quick note, I can put the fetch link in a const so that it's easier to read.
  2. I learned some things about regex or regular expressions that allowed for word matching. Need to dive deeper on this.
  3. Using the span element and the .innerHTML property, I'm able to update the DOM on every keystoke which is when the .map method runs.
- **Challenges:**
  1. I couldn't picture where to go to get to the end result of this challenge so I had to follow the instructions pretty closely. I'm not sure what the best learning method from here is, whether I should rewatch or try to dig deeper into forums.
  2. I'm not sure I would have had the foresight to find the function needed to add commas to the population data, I need to spend more time on my search skills.
  3. I need to make better comments, I'm already finding myself forgetting some of the functions I built in challenges a couple days ago when I go back for reference.

## Day [7/100]

- September 8th, 2021
- Time spent: 2 hours
- Main project: Array methods & Gatsby portfolio project
- **Takeaways:**
  1. Array methods are really useful, which sounds painfully obvious for anyone with any experience with them, but seeing them in action is another thing.
  2. The Gatsby tutorial is very well written. I got such a strong understanding of the core concepts that I've spent hours trying to digest. When confused on a topic, I really need to read on it through several sources.
  3. React components and pages are making much more sense. I understand that I can create a component that holds the individual project and insert it straight into the Layout component. I wonder if there's a faster way to add in the data to have a project component that maps the different projects' data.
- **Challenges:**
  1. Not sure how to make the Link component be highlighted differently if that is the page that is currently displayed. Not much luck googling it, yet.
  2. Still can't imagine how I would implement the actually JS projects onto separate pages on the site, or even several on one page...
  3. Design and UX is a huge thing for me to work on. In the process of reading the book "Steal Like An Artist" because I'm having difficulty finding ideas and inspiration out of thin air.

## Day [8/100]

- September 9th, 2021
- Time spent: 2 hours
- Main project: HTML5 Canvas & Gatsby Portfolio Project
- **Takeaways:**
  1. I was able to do something as add a button with styling without almost any instruction that also had functionality. It was a satisfying step for me after going through several of these JS challenges.
  2. You can loop through if statement by just have a changing event. For example, every time the mouse is clicked down AND moved, the function to draw is activated, so then I can change the color as the draw function is running.
  3. I could see how it's possible to build a drawing app like awwapp.com
- **Challenges:**
  1. It was difficult to align 3 elements in the header bar that would have the middle element spaced directly in the center regardless of the size of the button and text on either side.
  2. I was not able to figure out how to make the canvas only the height of the viewport and also have a header. Once the header was added, the canvas would extend that height below the viewport and you would have to scroll on the page to see all of it.
  3. I'm still not 100% on how I created a flag that only ran the function when clicking down AND moving.

## Day [9/100]

- September 10th, 2021
- Time spent: 30 minutes
- Main project: Learned Dev Tools Tricks
- **Takeaways:**
  1. So many of the things I am taught are only surface level, but it makes sense why console.log has the '.' in the middle, it's one of many methods.
  2. I keep being surprised for some reason just how much functionality the browser has and how much data you can work with.
  3. Even when it's 2:30 in the morning after a 20 hour day filled with work and necessary errands, I can still sit down and do something to continue the workflow streak.
- **Challenges:**
  1. Remembering that I can use these tools to enhance my workflow, I guess it will just take time and revisitation.
  2. Finding the time to build something or code every day with a work / life balance, as well. I know that it will be a struggle to have this balance on my upcoming 4 day trip with friends.
  3. Being ok with just doing 30 minutes when I committed to an hour. Could I have just sacrificed more sleep, is that worth the several day negative effects?

## Day [10/100]

- September 15th, 2021
- Time spent: 1.5 hours
- Main project: Building a Custom Video Player
- **Takeaways:**
  1. I didn't realize that you can just build video functionality from scratch like this, I always assumed the video processing was very complicated and embedding was essential.
  2. I could see adding some video functionality to my own portfolio where you could click on various buttons on the site to control a video story in the background.
  3. I finally understand creating a flag variable to make it so scrubbing is only active when the mouse is down AND moving.
- **Challenges:**
  1. I didn't have the time to explore a couple functions that I know will likely be a challenge to figure out, like showing the volume slider in a pull-up bar and changing the playback speed to pre-set buttons.
  2. I couldn't figure out how to set a max-width and max-height that kept the consistent 16:9 ratio. Maybe by using a container div to lock the max-width.
  3. The progress bar starts at 50% not 0% when the page is first loaded, not sure how to change that still.

## 10-Day Recap

- In progress

## Day [11/100]

- September 16th, 2021
- Time spent: 2 hours
- Main project: JS Challenges / Gatsby Portfolio Project
- **Takeaways:**
  1. I can see how I could make my portfolio interacive with Key Sequence Detection, like typing while on the page to find easter eggs or even an on page command terminal for answering questions.
  2. Slide in on scroll is useful to really create that Apple event like experience on your site. I can see how it can be abused, but would be a great way to make the page feel alive while scrolling.
  3. Getting back into working on the portfolio is making me realize how to original site template I used works. There is a data layer that I wasn't seeing before, but now that I understand some of the simple functionality of GraphQL, it's starting to click.
- **Challenges:**
  1. It took me quite a while to wrap my head around the .splice() and .join() methods even though they are pretty simple, not to mention everything being wrapped in a .forEach() method. Maybe a CS degree would've helped with this...
  2. I'm struggling to think of how to style the portfolio using the tools I'm learning rather than brute-forcing it. There's an elegance to short and intentional code that I'm trying to internalize.
  3. I'm still not 100% on the usefulness of using gatsby-source-filesystem to move simple data within the file, maybe this will be more important when I'm introduced to using a CMS.

## Day [12/100]

- September 17th, 2021
- Time spent: 1 hour
- Main project: JS Challenges / Organization
- **Takeaways:**
  1. I don't see the value yet, but just finding something to post every day on this blog article is one of the most valuable things I can be doing in the early stages. Builds a good habit and will be more and more valuable as time passes on my coding career.
  2. I'm understanding the importance of data manipulation and I just discovered how to clone an object, never seen that before.
  3. CSS Variables are immediately useful, as I picked out a color palette for the portfolio today.
- **Challenges:**
  1. It was more difficult today than other days to dive into work, I just kept finding myself distracted. Just posting about the struggle and continuing the 100days challenge is a small win, though.
  2. I feel like I might be in tutorial hell trying to figure out this portfolio project, but how do you not get lost in tutorials even when building a project? I feel like I keep pulling threads and then I get lost in the info it leads me to.
  3. Again, design for the portfolio is really nagging at me, not sure where I want to go with it. Maybe that shouldn't be a huge worry though and I should move on the ecom store. I want to build something for the upcoming iPhone release so I can try selling some cases.

## Day [13/100]

- September 20th, 2021
- Time spent: 2.5 hours
- Main project: Local Storage Challenge / Gatsby Portfolio Project
- **Takeaways:**
  1. I created and added an SVG to the site on my own, adding it to the header using flexbox. This was not nearly as difficult as I thought it might be.
  2. During the local storage JS challenge, I saw just how much work it takes to create something as simple as a dynamic list using Vanilla JS, I'm glad I'm focusing on using a framework so that things like this aren't unnecessarily time consuming.
  3. It's easy to get lost searching how to do something very specific on a build, but I'm improving my prioritization and instead read up on topics that were more useful to exactly what I was trying to do. For example, Flexbox and CSS Grid.
- **Challenges:**
  1. I either don't have a fundamental understanding of how CSS works or I'm just not used to how slow of a process it is to get things right. It definitely gets frustrating at times.
  2. It seemed too daunting of a task to figure out the "clear all", "check all", and "uncheck all" functionality, so I decided to instead work on the portfolio project. I'm not sure if I would've gotten a lot out of figuring that out, but I think my insight is slowly getting better and I felt my time was better used on this project.
  3. I tried to implement the first JS challenge, the drum kit, into one of the pages on the portfolio. I did get the page rendered and added the basic HTML/CSS, but I couldn't really picture how to move forward with the actual functionality of the keyboard not using eventListeners.

## Day [14/100]

- September 21st, 2021
- Time spent: 4 hours
- Main project: Mousemove-Shadow JS Challenge / CSS Proficiency / Gatsby Portfolio Project
- **Takeaways:**
  1. Making a responsive mousemove element on the page (as well as an editable one) is much easier than I would have imagined. It also led me down several rabbit holes on other CSS tricks I could use and to look into the Chrome Dev Tools more whilst editing CSS.
  2. Now that I started to use GraphQL to actually query the body of the articles I want to have on the site, I see some of the usefulness of the tool. It really keeps everything organized and concise.
  3. It took quite a while, but eventually I found how to display my favicon and custom fonts on the Gatsby portfolio, I wonder if there was an easier way.
- **Challenges:**
  1. I'm not sure what happens to the performance of my site everytime I install a dependency but I don't end up using it. I should look up if there's a way to get rid of dependencies I don't need or if it's not even worth the trouble deleting.
  2. Again, it's difficult to not get distracted chasing a little bug or feature for sometimes hours because it doesn't occur until the end that the time could have been better spent on broader things.
  3. I'm stuck on the formatString argument and why it's not working on my query. The articles I found were not really helping, now I'm wondering if I should follow a different tutorial or if I should just skip this bug. Probably just skip the bug until later.

## Day [15/100]

- September 22nd, 2021
- Time spent: 1.5 hours
- Main project: JS Challenges / Gatsby Portfolio Project
- **Takeaways:**
  1. I'm realizing that I now have a pretty solid understanding of flexbox and basic CSS in general. It took me no time or googling to get my About page to look how I wanted. The thing I wonder is if there are ways I could be setting things up to cut down on repeated code... or if it's even worth it performance-wise when it comes to CSS.
  2. I realized how simple it is to sort arrays of strings and numbers using .sort(), now I wonder how to implement that with the blog posts to sort the various days on the spot, if that's possible.
  3. It finally feels like the new site isn't looking absolutely terrible, the about page is really coming together for almost having no content. The buttons look pretty good, I want to replace or enhance them with the actual company logos.
- **Challenges:**
  1. It took me a while to sit down and actually get to work and then I ended working on the About Page rather than the Posts Page because I knew it was an easier task to tackle.
  2. I tried to figure out why https://www.matas.io is not working but https://matas.io, http://matas.io, and http://www.matas.io are. It has something to do with SSL certificates I'm pretty sure, but I need to contact support or something because I'm stuck.
  3. I think my CSS code is already becoming a mess because I didn't set up my layout well, or maybe I should be making separate CSS files for separate pages. OR should I be putting the About Page into a component and then rendering that component in the actual pages folder. That seems like something to look into...
