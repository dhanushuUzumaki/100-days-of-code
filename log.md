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
