#Code Writing Kids: Game Design -- Week  2 Notes
----------
![](https://farm3.staticflickr.com/2290/2462966749_528417d708_d.jpg)


##Today will be.. Quite eventful!
Last week, we started getting settled down with Game Maker. If you were able to follow through with the Platformer tutorial between last class and now, you'll have a pretty good feel for where everything is in Game Maker. That's awesome! Now we can get to more of the nitty-gritty about how games are written in Game Maker: Events and actions.

Last class we looked at the list of events, and the list of actions. There are quite a lot of each! We'll spend today looking at these events and actions in dept, seeing where we might use each. We'll pay some special attention to the Create, Step, and Alarm actions.

##Understanding goals
You'll be able to understand: 

 - the concept of frames in games
 - games as looping code
 - counting frames/steps
 - framerates
 - relative and absolute events and coordinates
 - how objects can affect other objects from their own actions

##Skill goals
You'll be able to perform the following tasks:

 - Use Game Maker's various actions in your games
 - Run code at certain intervals
 - Run code over and over in the step event
 - Run code right as an object is creative
 - Wait a certain amount of time to run code
 - Make objects move/bounce/etc
 - Use actions to rotate objects
 - Use degrees to set directions for events
 - End the game or display a game over message

##Points to Remember

 - Games update graphics over and over.
 - Each update creates a new *frame*.
 - How many frames are created per second is the *framerate*
 - Code can run at every step/frame
 - GM's events basically check for events at every step, and only run them if the event happens.
 - Alarms can be set up as events, and called from other actions
 - Less for actions is usually better
 - Keep things simple, and consider which action should be performing which event.
 - Objects can create other objects
 - **Directions**: right is zero degrees. Up is 90. Left is 180. Down is 270 or -90.

## Don't forget...

 - You can easily delete an action just by selecting hitting the 'Delete' key on your keyboard
 - You can use Control+Z to undo what you do in Game Maker, in case you make some small mistake.
 - There are tabs full of actions in GM! Just click the tab names on the right side of the object menu
	 - ![](http://i.snag.gy/l4m43.jpg)
 - You can create up to 13 alarm events in an object. Careful how you use them!
	 - ![](http://i.snag.gy/vgHIF.jpg)
 - For the Step event, you can run your code over and over. For this, the regular Step event is fine. But if you specifically need to run code at the beginning or ending of a step, there are options available!
	 - ![](http://i.snag.gy/IA858.jpg)

##After Class

Try using what we've learned in class to make a simple top-down shooter game! You don't need complex graphics (though those are welcome!). You might want to start by playing a few top-down shooters, and see how they work.

> Written with [StackEdit](https://stackedit.io/).