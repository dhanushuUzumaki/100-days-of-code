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
