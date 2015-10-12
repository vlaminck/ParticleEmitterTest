# ParticleEmitterTest
A test project for trying to figure out pausing particle emitters. [StackOverflow question](http://stackoverflow.com/questions/33070766/skemitternode-gap-when-paused-unpaused)

The problem I'm trying to figure out is why my `SKEmitterNode` has weird gaps when the view is paused (like when the app is backgrounded then foregrounded). This project has a single `SKEmitterNode`. To see the problem I'm having, background the app for about 5 seconds then foreground it, or just click to pause/unpause.

Here is a screenshot of what it looks like when you foreground or unpause the app after about 5 seconds of being backgrounded/paused.

![emitter gif](https://raw.githubusercontent.com/vlaminck/ParticleEmitterTest/master/EmitterPause.gif)


### Update
This is a bug in iOS9, and tvOS. I have not tested OSX, but have confirmed the bug does not exist in iOS8. A bug report has been filed with Apple.
