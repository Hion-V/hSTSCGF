# hSTSCGF
hion's Simple TypeScript Canvas Graphics Framework

Because ActionScript is officially deprecated with Adobe Flash's EOL coming up at the end of this month (December 2020) I am forcing myself to jump over to TS for prototyping simple graphical applications. There is one big problem with this though. There's currently no good robust way of interacting with HTML Canvas that doesn't suck ass and fits my usecase. Therefore I am taking it upon myself to build a simple framework that allows for the pain-free development of interactive web experiences without using bad developers' bad javascript spaghetticode.

# Goals

Making the development of interactive graphical browser applications fun and suck-free again. This will be accomplished by providing some degree of abstraction so that the framework is relatively easy to use while still allowing developers to build robust systems around it. Most libraries/ frameworks that I have looked at so far that attempt to do this miserably fail to deliver either on simplicity, or they abstract everything away to the point that building more complex systems is a big hassle.

# Building

Make sure you have the TypeScript compiler installed and simply run `tsc` from your commandline in the project root.

# Structure

The application's entrypoint index.js is compiled from index.ts and is linked in index.html as a js(es2015) module. From here it passes the `<canvas>` element into the Main class where you can start programming whatever you want to happen at init and on each animation frame as part of your "Game loop".

# Documentation

I currently have no plans of my own to create detailed documentation for this project as it is primarily just meant as a tool for my own personal use. If you however think it's useful to you in any way shape or form, feel free to use and build upon it.
