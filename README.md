# Unity Coding Basics Part 2 - Loops and Arrays

If you've been using Unity for a while, or are just getting started with Unity and decided it's time for you to start learning how to write code - this is the video series you need to start your programming journey!

In this tutorial repository (with [associated video](https://youtu.be/MB6B9nHSrps)), aimed at absolute beginners who have very little to no coding experience whatsoever, you'll learn:
* What Loops are.
* What kinds of Loops are available in C#
* A step-by-step breakdown of what each statement is doing, why it's happening, and how it works.
* How to make multiple TextMeshProUGUI components on the screen count up over time from a single script

**📝📝📝YOUR HOMEWORK!📝📝📝**

Tip: There's a bunch of ways to approach this, but one way that I like to do it takes advantage of a handy "remainder" operator called the modulus operator: https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/arithmetic-operators#remainder-operator-

Update this script so will display the updated TimeDisplay on only a single TextMeshProUGUI component on a frame.

On frame 1, the first TextMeshProUGUI component should display the TimeDisplay

On frame 2, the second TextMeshProUGUI component should display the updated TimeDisplay, the first TextMeshProUGUI component should still show the last TimeDisplay value.

On frame 3, the third TextMeshProUGUI component should display the updated TimeDisplay, the first TextMeshProUGUI component should still show the first TimeDisplay value, and the second TextMeshProUGUI component should display the last value.

etc... through the end of the TextMeshProUGUI components. Once we've reached frame 8 (since we only have 7 TextMeshProUGUI components) it should update the first TextMeshProUGUI component again and continue with this pattern.

This should work for any number of TextMeshProUGUI components, or any size of the Texts array.

Add a comment below with a video showing your code and the end result.

📚 Here are the resources I mentioned and/or brought up during the video 📚
* https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/iteration-statements
* https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/
* https://en.wikipedia.org/wiki/For_loop
* https://en.wikipedia.org/wiki/While_loop
* https://en.wikipedia.org/wiki/Do_while_loop
* https://en.wikipedia.org/wiki/Foreach_loop


[![Youtube Tutorial](./Video%20Screenshot.png)](https://youtu.be/MB6B9nHSrps)

## Patreon Supporters
Have you been getting value out of these tutorials? Do you believe in LlamAcademy's mission of helping everyone make their game dev dream become a reality? Consider becoming a Patreon supporter and get your name added to this list, as well as other cool perks.
Head over to https://patreon.com/llamacademy to show your support.

### Phenomenal Supporter Tier
* YOUR NAME HERE!

### Tremendous Supporter Tier
* YOUR NAME HERE!

### Awesome Supporter Tier
* Raphael
* Andrew Bowen
* Gerald Anderson
* AudemKay
* YOUR NAME HERE!

### Supporters
* Bastian
* Trey Briggs
* YOUR NAME HERE!

## Other Projects
Interested in other AI Topics in Unity, or other tutorials on Unity in general? 

* [Check out the LlamAcademy YouTube Channel](https://youtube.com/c/LlamAcademy)!
* [Check out the LlamAcademy GitHub for more projects](https://github.com/llamacademy)

## Requirements
* Requires Unity 2020.3 LTS or higher. 