---
layout: post
title: Some Challenges faced so far as a new Student developing web technologies on Bloc
---

So, some background. Prior to Bloc, I've done 2 specializations at Coursera, I have a Masters degree (which I avoided coding in anything other than Matlab like the plague), and I did take a C++ course eons ago in the early 2000 for my undergrad.

So you could say I did come into this sort of initiated.

However, I have run into some issues so far in my Bloc studies. One mainly, is the fact that to my Java and Python trained eye, Javascript feels like spaghetti code! It looks and kind of feels sometimes like a jarbled mess!

I have come to start seeing and understanding JS code a bit better. One thing in particular that I think lead to this is the fact that there seems to be a facination in JS to do this.

```Javascript
var awesomeVariable = function() {

	// add code logic here
	// add world domination backdoor logic here
	return "cake"
}
```

That is, functions are values! This threw me for a loop initially, but I've gotten used to it because it sort of makes sense... I guess... if you like that sort of thing.

Also, another challenge which has been burned into my brain because I probably spent an hour or so staring at my code, trying to figure out what was wrong, only to realize that:

```Javascript
actionAtClick = function(){

	console.log("lollipops)"

}


$(.whatever).click(actionAtClick())
```

was not the right way to go about adding this to as a click handler. That is because the function `actionAtClick()` was actually being executed. The `()` represent this execution. Hence, it would have already have been run, and there would be nothing to run there at all.

The correct way to do this would be:

```Javascript
actionAtClick = function(){

        console.log("lollipops)"

}


$(.whatever).click(actionAtClick)
```

This way, the click handler would go about doing it's business the right way.

These have been primarily JS issues that I've run into. Small things, that can be attributed to the behavior of the language. I know that I can get this down once I understand the language better, and have worked for it with a while.

Besides that, so far as a Bloc student, one thing that I was concerned about initially was that I didn't know how much would be expected of me! That is, how much I would need to remember of each lesson, of each checkpoint. Talking with others within the cohort, I was curious as to how much they were retaining. I also sounded this question off to my mentor at the time, Kevin Lowe.

I got back that, of course, because of the amount of information we were seeing initially, it would be virtually impossible to remember 100% of everything. I also got the same feedback from my peers as well. They were just as overwhelmed as I was, which made me feel that I was par for the course.

The methodology that I'm trying to implement is to do the first part of the checkpoint (pre-assignment) as best I can by following the instructions or videos that will guide me through this part. Second, once the assignment kicks in, I use what was learned in the first part, and truly apply the concepts.

Once I get to a Module review, or a quiz review, I try to review as best as possible, all the information that I had seen in the previous module. Mainly focusing on the objectives of each checkpoint, and the new concepts to take away.

This, so far, has been my methodology, and has kept me pretty sharp going through the coursework at Bloc. Any time I'm stuck, fortunately, I can always reach out to my mentor.
