# alexaSample
Test code for Amazon's Alexa.

Learning from https://acloud.guru/course/intro-alexa-free/dashboard

**"alexa-skills-kit-js-deprecated"** was copied from https://github.com/amzn/alexa-skills-kit-js/tree/deprecated on March 14th, 2017.

**"Game_helper"** code was copied using a link found at https://developer.amazon.com/blogs/post/Tx352Z9W8L4QZ3B/new-alexa-skills-kit-template-for-developers-gamehelper

(For "Game_helper": after editing .js code, zip all files in folder except for the subfolder speechAssets.)

**"master-story"** (aka "interactive-adventure-game-tool") code copied from https://github.com/alexa/interactive-adventure-game-tool link found at https://developer.amazon.com/blogs/post/TxEQV5K754YS77/announcing-a-new-tool-for-building-interactive-adventure-games-on-alexa

(The "interactive-adventure-game-tool" folder can just be copied for use as a template, instead of having to re-install the Alexa ADK for each game instance or folder in this case.)

In Terminal, run:

    git clone https://github.com/alexa/interactive-adventure-game-tool

In Terminal, go inside the folder "interactive-adventure-game-tool" (mine is renamed as "master-story"), and enter:

    npm install

To run interactive story GUI, go into story1 folder (which is a copy of the "master-story" folder) and in Terminal enter:

    npm start
