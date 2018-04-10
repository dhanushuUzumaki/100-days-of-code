## Log of Round 1 of #100DaysOfCode



### Day 1: Jan-03-18 Wednesday 
**Today's Progress**: Wrote a shell script that will log into the 100-days-of-code journal. 

**Thoughts**: Since this was my first shell script, learned a lot and had a lot of fun. 

**Link To Work**: [100-days-of-code-logger](https://github.com/dhanushuUzumaki/100-days-of-code-logger)


### Day 2: Jan-04-18 Thursday 
**Today's Progress**: In choices app, implemented add option functionality. Refactoring is required. 

**Thoughts**: Getting the modal like I wanted was quite difficult still haven't achieved it. Should also allow users to exit the modal using the back button. 

**Link To Work**: [Choices](https://github.com/dhanushuUzumaki/choices)


### Day 3: Jan-05-18 Friday 
**Today's Progress**: Implemented functionality to delete an option in choices app. 

**Thoughts**: As usual styling was difficult but somehow got it working. Refactoring is required. 

**Link To Work**: [Choices](https://github.com/dhanushuUzumaki/choices)


### Day 4: Jan-06-18 Saturday 
**Today's Progress**: Added back button and icon to choices app. Published it on google play store. 

**Thoughts**: Publishing was cumbersome there were a lot of things to be done but it's a great experience. Not sure if I have done everything correctly. Tested it only on emulators and one nougat device. Hope it works. Fingers crossed. 

**Link To Work**: [Choices](https://github.com/dhanushuUzumaki/choices)


### Day 5: Jan-07-18 
**Today's Progress**: Only after pushing the Choices app to production I realised I haven't tested the production build. It seems like RN has some issues with production build and app crashes immediately after launch. It's primarily because of View.PropTypes but I am unable to find any occurance of it. Spent a lot of time on it but still haven't found the solution. Working on it. 

**Thoughts**: I tried grep-ing the node-modules but no results were found.. I am going to try all the methods proposed in the RN issue comments. 

**Link To Work**: [Choices - Issue - Production Build Fails](https://github.com/dhanushuUzumaki/choices/issues/5)


### Day 6: Jan-08-18 Monday 
**Today's Progress**: Got the app published successfully. Had to downgrade to RN 0.45.1 to solve the issue. 

**Thoughts**: Downgrading was a bit tricky. But did it. The app is simple but it feels really good. 

**Link To Work**: [Choices - Google Play](https://play.google.com/store/apps/details?id=com.choices)


### Day 7: Jan-09-18 Tuesday 
**Today's Progress**: Started off with FreeCodeCamp's React Project Markdown Previewer. 

**Thoughts**: Wanted to set up my own build configs but I also wanted to try out create-react-app so did that for this one. Just changed some styles. Hoping to complete it tomorrow. 

**Link To Work**: [FCCReactProjects](https://github.com/dhanushuUzumaki/FCCReactProjects)


### Day 8: Jan-10-18 Wednesday 
**Today's Progress**: Worked on the markdown previewer. Made the functionality working but having textarea is causing some issues. Should work on fixing that. 

**Thoughts**: On using textarea it gets modified because of grammarly. As a workaround tried conteneditable div but that is not capturing new lines so markdown is not being rendered properly. Should use textarea and fix that grammarly issue. 

**Link To Work**: [Markdown Previewer](https://github.com/dhanushuUzumaki/FCCReactProjects)


### Day 9: Jan-11-18 Thursday 
**Today's Progress**: Completed the markdown previewer. 

**Thoughts**: Fixed the grammarly issue with a data-attribute. I like the look and feel of the app but not so sure about users. Should put it in a github page and hope for the best. 

**Link To Work**: [MarkDownPreviewer](https://github.com/dhanushuUzumaki/FCCReactProjects)


### Day 10: Jan-12-18 Friday 
**Today's Progress**: Added favicon and deployed md previewer in gh page. 

**Thoughts**: I initially tried to have all the projects in a single repo and have apps inside it but i was unable to achieve it using gh pages so now md previewer has its own repo. 

**Link To Work**: [Markdown Previewer](https://dhanushuuzumaki.github.io/markdown_previewer/)


### Day 11: Jan-13-18 Saturday 
**Today's Progress**: Created a repo for fcc camper leaderboard. Worked on setting up webpack. 

**Thoughts**: This is the first time I understood and set up my own webpack.config. Still have to add HMR to it. 

**Link To Work**: [Camper Leaderboard](https://github.com/dhanushuUzumaki/camper_leaderboard)


### Day 12: Jan-14-18 
**Today's Progress**: Added HMR and linting to the camper leaderboard project and made a yeoman generator out of it. 

**Thoughts**: Learned how yeoman works and hoping to enchance the generator going forward. 

**Link To Work**: [Generator Uzumaki](https://github.com/dhanushuUzumaki/generator-uzumaki)


### Day 13: Jan-15-18 Monday 
**Today's Progress**: Worked on the camper_leaderboard. Added loader and fetching data. 

**Thoughts**: Learned some nice css-tricks ;) 

**Link To Work**: [Camper Leaderboard](https://github.com/dhanushuUzumaki/camper_leaderboard)


### Day 14: Jan-16-18 Tuesday 
**Today's Progress**: Worked on camper leaderboard. Tried out several data-grids but wound up using custom table and css. Functionality is done. Its pretty much responsive but still needs some work. 

**Thoughts**: Learned quite a few css tricks and have been facing some issue with hot reloading but not sure what is causing it should look into it if happens again. 

**Link To Work**: [Camper Leaderboard](https://github.com/dhanushuUzumaki/camper_leaderboard)


### Day 15: Jan-17-18 Wednesday 
**Today's Progress**: Completed camper_leaderboard 

**Thoughts**: Learned how to make table responsive. 

**Link To Work**: [Camper Leaderboard](https://github.com/dhanushuUzumaki/camper_leaderboard)


### Day 16: Jan-18-18 Thursday 
**Today's Progress**: Started with recipie box but haven't made much progress. Was looking into serveral components. Added favicon to camper leaderboard and webpack copy plugin. 

**Thoughts**: Should add the copy plugin to the generator also. Thinking of not using any components and write my own. Hope I can learn a little more this way.


### Day 17: Jan-19-18 Friday 
**Today's Progress**: Worked on modifying generator-uzumaki. Read about composablity in yeoman and moved the earlier one into react-basic sub generator. 

**Thoughts**: Should work on other variations also currently planning on react-basic (completed), react-router, react-router-redux. 

**Link To Work**: [generator-uzumaki](https://github.com/dhanushuUzumaki/generator-uzumaki)


### Day 18: Jan-20-18 Saturday 
**Today's Progress**: Added static file copying to basic generator. 

**Thoughts**: Tried adding router but facing some issues. Should work on that tomorrow.


### Day 19: Jan-21-18 
**Today's Progress**: Added react-router scaffolding to the generator. 

**Thoughts**: Since the routing needs the js file to be loaded initially any reloads will fail. 

**Link To Work**: [SO answer regarding this issue](https://stackoverflow.com/a/36623117/6599083)


### Day 20: Jan-22-18 Monday 
**Today's Progress**: Wrapped up react-router scaffolding and published the package. 

**Thoughts**: The issue I have been facing is the expected behaviour. So added help notes to the generator which will show up once the installation is done. 

**Link To Work**: [generator-uzumaki](https://github.com/dhanushuUzumaki/generator-uzumaki)


### Day 21: Jan-23-18 Tuesday 
**Today's Progress**: Finally figured how to add multiple keywords in the generator. And wrote basic test case for both subgenerators. 

**Thoughts**: Due to this learned some ejs syntax and understood diference between jest and mocha. Landed an article about airbnb migrating from mocha to jest which was a good read. 

**Link To Work**: [Unlocking Test Performance — Migrating from Mocha to Jest](https://medium.com/airbnb-engineering/unlocking-test-performance-migrating-from-mocha-to-jest-2796c508ec50)


### Day 22: Jan-24-18 Wednesday 
**Today's Progress**: Started with the recipe box. But actually worked on a starter page for the generator. 

**Thoughts**: Currently used an image but the scaling of it is not so good. So thinking of moving to a text based approach.

### Day 23: Jan-25-18 Thursday 
**Today's Progress**: Worked on the recipe box. Create an accordion component and added styles to it. It is just html with hide and show functionality for now. 

**Thoughts**: Earlier something like this would have been a daunting task for me. Now even though it's not perfect I was able to make something really quick. So I'm happy in that aspect. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 24: Jan-26-18 Friday 
**Today's Progress**: Worked on recipe box. Added Material desing button to add recipie. 

**Thoughts**: Learned a little about material design. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 25: Jan-27-18 Saturday 
**Today's Progress**: Worked on recipe-box modal component. Made a simple component but unable to make it more accessible like close modal when esc is pressed and such. 

**Thoughts**: While using prebuilt components never even thought about how these things are being done. Having so much fun. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 26: Jan-28-18 Sunday 
**Today's Progress**: Fixed the sunday not entered issue on logger. Was looking into several modal components as to how they were designed. 

**Thoughts**: The keyUp functionality is not working as I expected. Should find out what I am doing wrong.


### Day 27: Jan-29-18 Monday 
**Today's Progress**: Wrapped up the breadcrumb PR in freecodecamp guides. Hope it gets merged today. Apart from that got some nice info on accessiblity of the modal. 

**Thoughts**: My keyup listened was not working because it was on the modal.. If it's attached to the document, then it will be captured for sure. 

**Link To Work**: [Added Breadcrumbs to search results #751](https://github.com/freeCodeCamp/guides/pull/751)


### Day 28: Jan-30-18 Tuesday 
**Today's Progress**: Worked on the modal component. Made it accessible. Tried out some animations for opening accordion. 

**Thoughts**: Was trying different things with transition property, then one stackoverflow answer mentioned animation that's when I realized I forgot it all along. But still the question of whether the animation is necessary is a mystery. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 29: Jan-31-18 Wednesday 
**Today's Progress**: Started with the input component but having some issue. 

**Thoughts**: When I use the "value" as a prop name, nothing is being rendered. 

**Link To Work**: [StackOverflow Question](https://stackoverflow.com/questions/48544584/having-a-prop-named-value-stops-rendering)


### Day 30: Feb-01-18 Thursday 
**Today's Progress**: fixed the broken breadcrumbs issue in fcc guides and the input issue in recipe box. 

**Thoughts**: The input issue was because of my stypid mistake. I set the state to a string instead of an abject. 

**Link To Work**: [Fix #8028 Broken Breadcrumbs](https://github.com/freeCodeCamp/guides/pull/8042)


### Day 31: Feb-02-18 Friday 
**Today's Progress**: Worked on recipe box. Styled input and textarea components but I don't think what I am doing is the right way to do these. 

**Thoughts**: In chrome mobile view input and textarea are styled but when I open it in my mobile it is not. Should look into it. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 32: Feb-03-18 Saturday 
**Today's Progress**: Was working on the css thing from yesterday. Read some new cool stuff and tried them but I wasn't able to find the cause. 

**Thoughts**: There are a lot of things in html and css itself that can be done to improve page load time and here I was thinking it's mainly related to JS alone. Leason Learned :)


### Day 33: Feb-04-18 Sunday 
**Today's Progress**: Was looking into AWS. Played a little around IAM and S3. There are way too many services in AWS. 

**Thoughts**: Trying to learn more about EC2 and cloud formation scripts and architecting infrastructure.


### Day 34: Feb-05-18 Monday 
**Today's Progress**: Worked on recipe box. Completed till adding recipies, and interacting with local storage. 

**Thoughts**: Should work on editing and deleting recipies which I hope will be relatively simple since all the ground work has already been done. Hoping to complete it by tomorrow. 

**Link To Work**: [Recipe Box](https://github.com/dhanushuUzumaki/recipe-box)


### Day 35: Feb-06-18 Tuesday 
**Today's Progress**: Have a working version of recipe box. 

**Thoughts**: As I thought completing the remaining pieces of the recipe box was quite easy. Next is Game of life. So excited. 

**Link To Work**: [Recipe Box](https://dhanushuuzumaki.github.io/recipe-box/public/)


### Day 36: Feb-07-18 Wednesday 
**Today's Progress**: Played around with S3 and aws cli. 

**Thoughts**: Got to learn a lot of new things. Following acloud guru's videos.


### Day 37: Feb-08-18 Thursday 
**Today's Progress**: Started off with game of life as part of freecodecamp's react project. 

**Thoughts**: I understood how it works but not sure about what makes it so special, trying to figure those things out. Planned for a lot of features for this. So, should plan and do things step by step.


### Day 38: Feb-09-18 Friday 
**Today's Progress**: Worked on game-of-life. First time played around with svg and made a grid with event handling (this is not a big thing.. just saying ;) ) 

**Thoughts**: Never gave SVG a try and was in a belief that it was difficult... but it doesn't seem so. Maybe Should explore it more before coming to conclusion. 

**Link To Work**: [Game of Life](https://github.com/dhanushuUzumaki/game-of-life)


### Day 39: Feb-10-18 Saturday 
**Today's Progress**: Wrapped up the game of life. Its working but its not optimised. 

**Thoughts**: It was fun. Didn't know time passed by. Completed in about 2 hours. 

**Link To Work**: [Game Of Life](https://dhanushuuzumaki.github.io/game-of-life/public)


### Day 40: Feb-11-18 Sunday 
**Today's Progress**: Played around with S3. 

**Thoughts**: Tried setting up replication, cdn and lifecycle events.


### Day 41: Feb-12-18 Monday 
**Today's Progress**: Was looking into canvas and how to create an exploring kind of area with it for freecodecamp dungeon crawler game. 

**Thoughts**: I am not exactly sure as to how this is going to work.. this is something that I have been confused with for quite some time. So I hope by completing this I can understand some things about this.


### Day 42: Feb-13-18 Tuesday 
**Today's Progress**: Was looking into depth first back tracker maze generation algorithm and a implementaion video of it by coding train. 

**Thoughts**: Hope all this KD will end by tomorrow and soon have an awesome game.


### Day 43: Feb-14-18 Wednesday 
**Today's Progress**: Started working with canvas. Spent some time in getting started with Google India Scholarship Challenge. 

**Thoughts**: Reading through MDN on canvas and have a simple grid. Currently on codepen but planning to have a new repo for maze generator which will be similar to the game of life one in terms of UI but with canvas instead of svg. 

**Link To Work**: [CodePen - Maze Generator. Grid only for now.](https://codepen.io/dhanushuUzumaki/pen/bLopVO)


### Day 44: Feb-15-18 Thursday 
**Today's Progress**: Worked on maze generator. Did a lot of things wrong yesterday without understanding. Recitifer them today and learned quite a few things. 

**Thoughts**: Unable to fill the shape I formed with fill don't know why its happening. similarly the walls even after setting to false are not updated on the cell object. Should look into all these things. 

**Link To Work**: [Maze generator](https://codepen.io/dhanushuUzumaki/full/bLopVO/)


### Day 45: Feb-16-18 Friday 
**Today's Progress**: Have a mvp of the maze generator.. yay :D so happy.. 

**Thoughts**: Tried out several things for fixing my stupid mistakes.. now i draw lines to show walls but fill with a seperate rect without border. 

**Link To Work**: [Maze Generator](https://codepen.io/dhanushuUzumaki/full/bLopVO/)


### Day 46: Feb-17-18 Saturday 
**Today's Progress**: Completed 90% of lesson 2 in google udacity pwa scholarship. 

**Thoughts**: My knowledge on pwa was very limited to the 2 day training I had in google hyd. But this one is very promising. Learning a lot of interesting things.


### Day 47: Feb-18-18 Sunday 
**Today's Progress**: Worked through udacity pwa. 

**Thoughts**: Completed lesson 3 on service workers.. learnt a lot about life cycles and to how to deliver the updates to the user. Started lesson 4 on idb and done almost 70% of it.


### Day 48: Feb-19-18 Monday 
**Today's Progress**: Completed the pwa part in google udacity course. 

**Thoughts**: Learned interesting stuffs. Hoping to put them to good use. :)


### Day 49: Feb-20-18 Tuesday 
**Today's Progress**: Went through several articles in search for gaining info on dungeon crawler game. 

**Thoughts**: Landed up on webGL somehow and looked at some videos with respect to it. 

**Link To Work**: [Introduction to WebGL with Tony Parisi](https://www.youtube.com/watch?v=Y7xLuDBpZAY)


### Day 50: Feb-21-18 Wednesday 
**Today's Progress**: Wanted to do something cool for half century, but ended up sucking. Tried to have typing css effect story but came up with this. 

**Thoughts**: Will not work in mobile and I am not sure what to do about it. Should have to look into it more. 

**Link To Work**: [CSS Typing Text animation.](https://codepen.io/dhanushuUzumaki/full/ZroqjR/)


### Day 51: Feb-22-18 Thursday 
**Today's Progress**: Attended AWS Innovate: Machine Learning conference. Learned a lot of interesting things possible through aws. 

**Thoughts**: The simplicity they provide in terms of infrastructure is just amazing. Hoping to learn a lot more.


### Day 52: Feb-23-18 Friday 
**Today's Progress**: followed acloudguru's videos and played around with s3 and also with css variables. 

**Thoughts**: High fever, so these are the only things I was able to do. Hoping the fever goes by tomorrow and things get back to normal.


### Day 53: Feb-24-18 Saturday 
**Today's Progress**: Worked on the uzumaki generator. Wrote scaffolding for redux. But having redux with nothing to do is really stupid and I also wanted to have some kind of starter project inside the generator. So planning to add a simple todo app with it. 

**Thoughts**: Used the same code from journal app for the redux setup and here it is reflecting in dev tools. It must be that I did some stupid shit with state over there for things to break. Should find and fix it.


### Day 54: Feb-25-18 Sunday 
**Today's Progress**: Started with a simple todo project for having inside generator. It took 2 hours just to set things up because of a stupid versioning issue. 

**Thoughts**: Had react-router v4 which needs v5 of react-router-redux while having v4 of it. But I was writing code for v5 of it with connected router and provider kept on throwing an error saying invalid element. I don't know why it struck but after 1.5 hrs of trouble looked into package.json to find this stupid thing. Leason learnt. :( 

**Link To Work**: [Todo App](https://github.com/dhanushuUzumaki/todo-app)


### Day 55: Feb-26-18 Monday 
**Today's Progress**: Wanted to try page transition animations with react router. was looking into articles and tried something. But what I have currently is a component that will render two divs. Should really improve a lot. 

**Thoughts**: Should have an action plan and follow it else I am ending up doing stupid things like this. 

**Link To Work**: [Todays awful commit](https://github.com/dhanushuUzumaki/todo-app/tree/e74022f2931e57ddb2e89a36d70f81d3ef14c863)


### Day 56: Feb-27-18 Tuesday 
**Today's Progress**: Did a mvc of todo app. It doesn't have any styles so far. 

**Thoughts**: Hope to completely wrap this up tomorrow and wrap up generator. 

**Link To Work**: [Today's commit - Todo app](https://github.com/dhanushuUzumaki/todo-app/tree/790bf20d6ddc9f60207578931a6747deaf6566af)


### Day 57: Feb-28-18 Wednesday 
**Today's Progress**: Yesterday forgot the main point of doing this. Hooking up with redux. So did that today. 

**Thoughts**: Nothing specific. But I don't know how I forgot this yesterday. 

**Link To Work**: [Today's commit - Todo App](https://github.com/dhanushuUzumaki/todo-app/tree/25cf06dfee321ccbeea2bdfa7a2dda2961f122b5)


### Day 58: Mar-01-18 Thursday 
**Today's Progress**: Was following wes bos's css grid tuts on cssgrid.io and trying things out. 

**Thoughts**: This is so that I can use them correctly in the todo app. Completed about 10 videos.


### Day 59: Mar-02-18 Friday 
**Today's Progress**: Continued on wes bos's css grid tutus. From that got to know about operator mono and so set up fira code and flottflott. 

**Thoughts**: I have some experience with css grids from work but really learning a lot from this videos.


### Day 60: Mar-03-18 Saturday 
**Today's Progress**: Completed wes bos's css grid tuts. 

**Thoughts**: The last 5-6 videos helped me learn a lot of cool stuff. Hoping to recreate one of them soon.


### Day 61: Mar-04-18 Sunday 
**Today's Progress**: Worked on the todo app. Added some accessibility to the app but linter says not to use +ve tab index should look into that. Styled the app using grids and used css variables. :) 

**Thoughts**: When items are added to the list, ui is breaking should fix that. 

**Link To Work**: [Today's Commit - Todo App](https://github.com/dhanushuUzumaki/todo-app/tree/30c17115ecee87cf3b41b0e47020c5b742cb4444)


### Day 62: Mar-05-18 Monday 
**Today's Progress**: Fixed the scroll issue. Not convinced with the current ui. Should modify it a little more. 

**Thoughts**: Planning to move add item to the top and have it there always. Hoping to completely wrap this up tomorrow. Taking so much time for a simple todo app. 

**Link To Work**: [Today's commit - Todo App](https://github.com/dhanushuUzumaki/todo-app/tree/4c34c54a2ea00148c103d3798504706d9bee8757)


### Day 63: Mar-06-18 Tuesday 
**Today's Progress**: Changed the UI of todo app. Its almost responsive. 

**Thoughts**: Feel like I might have overused grid. But it's done, don't think it will be a good idea to waste any more time on this. 

**Link To Work**: [Today's commit - Todo App](https://github.com/dhanushuUzumaki/todo-app/tree/37f18cd4423850c8f9db633dc94f1d32bfe765df)


### Day 64: Mar-07-18 Wednesday 
**Today's Progress**: Updated the generator and published. Now it has 3 scaffoldings, all with basic todo app. the app is almost reponsive. 

**Thoughts**: Tried to set up auto publish with travis ci. But having some difficulties with nsp. I am not sure whether this is because of the api token. Should look into it. 

**Link To Work**: [Generator Uzumaki - V0.1.0](https://github.com/dhanushuUzumaki/generator-uzumaki/tree/0.1.0)


### Day 65: Mar-08-18 Thursday 
**Today's Progress**: Was spending some time on the travis auto publishing, but it ended in vain. So, left it for some other time. Started with the rougelike. Was readinga a article on generating dungeons. 

**Thoughts**: The process seems so complicated, but it's also a good thing. For too long I have been in the comfort zone. So I am planning to do this correctly. 

**Link To Work**: [Generating a Dungeon](http://journal.stuffwithstuff.com/2014/12/21/rooms-and-mazes/)


### Day 66: Mar-09-18 Friday 
**Today's Progress**: Played around with EC2 while following acloud guru's videos. 

**Thoughts**: Should have started working on the rougelike, but don't know why I did this today. :(


### Day 67: Mar-10-18 Saturday 
**Today's Progress**: Follwed up on the same thing. Ec2 following acloudgurus videos. 

**Thoughts**: Hoping to start with AMI stuff tomorrow and also planning to test out packer.


### Day 68: Mar-11-18 Sunday 
**Today's Progress**: Felt like the rougelike is going to take a lot more time than I thought. So decided to finish up the D3 challenges first. Hoping to complete all the D3 challenges in next 2 weeks. Today started with gdp visualization. 

**Thoughts**: It was like walking blind. Made a shitty basic data display but that is of no use. Should look at how to actually do things in D3. 

**Link To Work**: [Today's commit - GDP Visualization](https://github.com/dhanushuUzumaki/gdp-visualization/tree/874eb470f40523d892f38693cfc4d3b2c25d31b0)


### Day 69: Mar-12-18 Monday 
**Today's Progress**: Wrapped up the GDP visualization. 

**Thoughts**: I believe this the hello world of D3.. hoping to learn more. 

**Link To Work**: [GDP Visualization](https://dhanushuuzumaki.github.io/gdp-visualization/)


### Day 70: Mar-13-18 Tuesday 
**Today's Progress**: Completed Scatter plot visualization challenge of freecodecamp. 

**Thoughts**: So happy I actually did it within 1.5 hrs. 

**Link To Work**: [Race Result Visualization - Scatter Plot](https://dhanushuuzumaki.github.io/race-result-visualization/)


### Day 71: Mar-14-18 Wednesday 
**Today's Progress**: Started with the heatmap visualization. Haven't made any progress yet. Hoping to complete it by tomoroow. 

**Thoughts**: If I could finish all these D3 challenges within next week then I would be really happy.


### Day 72: Mar-15-18 Thursday 
**Today's Progress**: Tried to recreate some single div objects I saw yesterday.. but it ended in vain. 

**Thoughts**: I wanted to do it without looking at the original code but it has been very diffiult so far.


### Day 73: Mar-16-18 Friday 
**Today's Progress**: Started javascript30 and watched day 1 video. Drum Kit. Implemented it. 

**Thoughts**: Never knew there is a html tag called kbd.. saw this today on the video.. should do 2nd video on this as well as heatmap tomorrow. 

**Link To Work**: [Drum Kit](https://dhanushuuzumaki.github.io/Javascript30/d1-drum-kit/)


### Day 74: Mar-17-18 Saturday 
**Today's Progress**: Did day 2 of JS30. Accessing CSS variables from JS. 

**Thoughts**: Wanted to do the heatmap today.. but couldn't. 

**Link To Work**: [Image filter and location using CSS Variables](https://dhanushuuzumaki.github.io/Javascript30/d2-css-variables-in-js/)


### Day 75: Mar-18-18 Sunday 
**Today's Progress**: Wrapped up the heatmap and did javascript 30 

**Thoughts**: Somehow I missed the 2nd video and went to 3rd yesterday in JS30.. so did day 2's content today. 

**Link To Work**: [Global Temperature Visualization using HeatMap](https://dhanushuuzumaki.github.io/global-temperature-visualization/)


### Day 76: Mar-19-18 Monday 
**Today's Progress**: Worked on the force directed graph and day 4 of JS30. 

**Thoughts**: Got the graph working.. but the flag sprite is not rendered. Should figure that out tomorrow. 

**Link To Work**: [Today's Commit - Force Directed Graph](https://github.com/dhanushuUzumaki/national-contiguity-visualization/tree/a4534492f37457a1bd792e5b51e2f23843fd9a6d)


### Day 77: Mar-20-18 Tuesday 
**Today's Progress**: Did Day 5 of JS30, flex panel image gallery. 

**Thoughts**: Wanted to look into the flag rendering issue in force directed graph.. but couldn't. Hoping to wrap it up by tomorrow. 

**Link To Work**: [Flex Panel Image Gallery](https://dhanushuuzumaki.github.io/Javascript30/d5-flex-panels-image-gallery/)


### Day 78: Mar-21-18 Wednesday 
**Today's Progress**: Did Day 6 of JS30.. Ajax type ahead. 

**Thoughts**: Still didn't fix the flag rendering issue.. should wrap it up and start with the next visualization. 

**Link To Work**: [AJAX Type Ahead](https://dhanushuuzumaki.github.io/Javascript30/d6-ajax-type-ahead/)


### Day 79: Mar-22-18 Thursday 
**Today's Progress**: Followed day 7 of JS30. 

**Thoughts**: Still haven't resolved image rendering...


### Day 80: Mar-23-18 Friday 
**Today's Progress**: Yet another day with only JS30. 

**Thoughts**: Did a kind of canvas drawboard. 

**Link To Work**: [Canvas Drawboard](https://dhanushuuzumaki.github.io/Javascript30/d8-fun-with-canvas/)


### Day 81: Mar-24-18 Saturday 
**Today's Progress**: Spent time on the image rendering issue in force directed graph. 

**Thoughts**: Found svg image doesn't support gif.. so got a png background and tried with it.. that also didn't work.. then I tried having the img tag directly inside a foriegnobject tag.. that works in another svg but not when constructing through d3... Hoping to fix it by tomorrow atleast. :(


### Day 82: Mar-25-18 Sunday 
**Today's Progress**: Wrapped up the force directed graph visualization with the help of some people from stackoverflow. 

**Thoughts**: It can still be improved but I have left it for now. Also catched up JS30. 

**Link To Work**: [National Contiguity Visualization](https://dhanushuuzumaki.github.io/national-contiguity-visualization/)


### Day 83: Mar-26-18 Monday 
**Today's Progress**: Did a custom HTML5 video player following wes bos on JS30.

**Thoughts**: Wanted to add fullscreen to it. Will do it tomorrow. 


### Day 84: Mar-27-18 Tuesday 
**Today's Progress**: Did key sequence detection  in JS30 and implemented fullscreen feature in yesterday's code.

**Thoughts**: Hoping to start with the next visualization tomorrow. 


### Day 85: Mar-28-18 Wednesday 
**Today's Progress**: Started with the meteorite landing visualization and did JS30. 

**Thoughts**: Only got a simple projection today. :(


### Day 86: Mar-29-18 Thursday 
**Today's Progress**: Followed up on JS30 and have an mvp of the meteorite landing visualization. 

**Thoughts**: Having problem with replotting the data on zoom. Been at it for hours, still no idea on how to solve it. So asked on SO. 

**Link To Work**: [StackOverflow Question](https://stackoverflow.com/questions/49558496/redraw-points-on-mapprojection-while-zooming)


### Day 87: Mar-30-18 Friday 
**Today's Progress**: Followed up on JS30. Added checkall, uncheckall and deleteall to it. 

**Thoughts**: Was also looking into the visualization thing.. I am unable to comeup with anything so far.. 

**Link To Work**: [Today's Commit](https://dhanushuuzumaki.github.io/Javascript30/d15-localstorage-and-event-delegation/)


### Day 88: Mar-31-18 Saturday 
**Today's Progress**: Followed up on JS30. Some time on visualization. 

**Thoughts**: Got some help from freecodecamp gitter and also tried out some new ways from d3's documentation.


### Day 89: Apr-01-18 Sunday 
**Today's Progress**: The visualization thing - I am lost. Just did JS30 and was trying some things from a medium article.

**Thoughts**: I am thinking of removing the zoom capability as such and just display the points.

### Day 90: Apr-02-18 Monday 
**Today's Progress**: Did JS30 and updated the scroll behaviour in markdown previewer. 

**Thoughts**: Also looked into the meteor landing.. tried few other methods and got some help from gitter also.. but still not resolved. 

**Link To Work**: [Markdown Previewer - update](https://dhanushuuzumaki.github.io/markdown_previewer/)


### Day 91: Apr-03-18 Tuesday 
**Today's Progress**: Worked only on JS30 today. 

**Thoughts**: Learned several new things today from JS30.. 

**Link To Work**: [WebCam Fun](https://dhanushuuzumaki.github.io/Javascript30/d19-webcam-fun/)


### Day 92: Apr-04-18 Wednesday 
**Today's Progress**: Played around with speechrecognition api following JS30. 

**Thoughts**: Also worked on making the meteorite landing into bounded zoom as I have seen an example with that.. 

**Link To Work**: [Speech Detection](https://dhanushuuzumaki.github.io/Javascript30/d20-speech-detection/)


### Day 93: Apr-05-18 Thursday  
**Today's Progress**: Played around with geolocation api following JS30. 

**Thoughts**: Haven't touched the meteor landing yet. Have to complete that and rougelike before Round 1 ends.


### Day 94: Apr-06-18 Friday 
**Today's Progress**: Followed up with JS30 and did a similar animation to that.

**Thoughts**: Also went through the new things possible in React 16.


### Day 95: Apr-07-18 Saturday 
**Today's Progress**: Following JS30 explored speech synthesis api.

**Thoughts**: Before this I never even thought of browsers having these things natively. 🆒 (Cooooool)

**Link To Work**: [Speech Synthesis](https://dhanushuuzumaki.github.io/Javascript30/d23-speech-synthesis/)


### Day 96: Apr-08-18 Sunday 
**Today's Progress**: Following JS30 did a sticky navigation.

**Thoughts**: Also spent some time on a medium article on using python like decorators in JS and some examples of where it might be useful.

**Link To Work**: [Sticky Nav](https://dhanushuuzumaki.github.io/Javascript30/d24-sticky-nav/)

### Day 97: Apr-09-18 Monday 
**Today's Progress**: Learned some new stuff regarding JS's event handling. 

**Thoughts**: Nothing in particular... spent most of the time on MDN today after JS30.


### Day 98: Apr-10-18 Tuesday 
**Today's Progress**: Attended Oracle Code @ Banglore - IN. Great talk by [@christhalinger](https://twitter.com/christhalinger) on GRAAL and [@prpatel](https://twitter.com/prpatel).. Thanks a lot guys. 

**Thoughts**: Followed up on JS30 and did a stripe like follow along nav and made one small change to that. 

**Link To Work**: [Stripe Follow Along Nav](https://dhanushuuzumaki.github.io/Javascript30/d26-stripe-follow-along-nav/)
