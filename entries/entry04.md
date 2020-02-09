# Entry 4
##### 2/10/2020

## Updates, Progress, and Knowledge
Looking back at my next steps from the previous blog entry, I can say that my group and I have completed the goal that was set. Aaliyah was able to connect our Android Studio IDE to Github so that our code is shareable among all of us. She googled how to connect Android Studio and Github and came across a [Stack Overflow answer](https://stackoverflow.com/questions/37093723/how-to-add-an-android-studio-project-to-github), which had directions that she followed to connect our project to a Github repository that she made. After this, we were able to successfully commit and push any changes we made to our project so that we can all see the code from different places. She then started to write in the pseudocode that we wrote earlier into the MainActivity.java file as comments to follow later.
![comments](../comments.png)

While Aaliyah was doing this, Elizabeth and I finally started with getting into the code of the app. We looked at our GDrawing where we designed our app and decided to start working on our main page. I started to play with the code that was already in the activity_main.xml file and looked at how to code a button.

I googled how buttons work in Android Studio and read through a [guide to buttons](https://developer.android.com/guide/topics/ui/controls/button) on the android website. Then I googled how to make a circular button since most of the buttons in our app will be circle shaped. This led me to a [website](https://android--code.blogspot.com/2015/01/android-round-button.html) that showed the code of a circular button. I copied and pasted the first code snippet into the activity_main.xml file, which looked like this . . .
![mainCircleButton](../mainCircleButton.png)

I looked at the second snippet and noticed how it came from a file called button_bg_round.xml in the drawable folder. I made a file with the same name in the drawable folder and copied and pasted the second snippet in the file, which looked like this . . .
![drawableCircleButton](../drawableCircleButton.png)

These two code snippets created a round button on the preview page.
![originalCircleButton](../originalCircleButton.png)

We wanted to customize this button and change the colors, so I looked at the code that I pasted into the activity_main.xml file and noticed how each line was responsible for a different part button. For example, the height, width, and text of the button had its own line of code. I googled how to change the color of a button’s text and went to a [Stack Overflow link](https://stackoverflow.com/questions/32671004/how-to-change-the-color-of-a-button), which said that you would have to use this code . . .
![textColor](../textColor.png)

I inserted the second line of the code into the activity_main.xml file, and instead of using `"@android:color/black"` , I used a Hex color. This is on line 25 in the image below.
![mainTextColor](../mainTextColor.png)

To change the color of the actual button, I looked at the code in the button_bg_round.xml file and noticed that lines 5 changed the color of the border and line 6 changed the color of the inside. I changed both of these to be red using a [color generator](http://coolors.co/app).
![drawableButtonColor](../drawableButtonColor.png)

In addition to this, I changed the text that shows up on the button to “+” because it will be the button to use to add a new medicine. With all of these changes, our new button looks like this . . .
![finalButton](../finalButton.png)

## Engineering Design Process
We are currently on the 5th step of the Engineering Design Process, **creating a prototype**. We have started to code the actual parts of our app, starting with all the buttons that can be clicked by the user. My group and I plan to be in this stage for the majority of the rest of the time we have because of the amount of aspects we want to add to our app. We have already decided to not add some things, like the ability to log in and having accounts, because we believed that we did not need it for a **minimum viable product (MVP)**. We still have a lot to complete even with the removal of the login process, so our goal is to continue to break down all our tasks into smaller and manageable steps so that we are not overwhelmed like we were in the past.

## Skills
Since the last blog entry, my group and I have still been working on the same skills. We have been trying to work on **problem decomposition** and **organization**.

We have recently been using **problem decomposition** to figure out what we specifically have to work on to complete an MVP. We are breaking down all the things that we want to work on and doing them one at a time. **Organizing** our thoughts and actions have also been something that we are practicing. To keep track of what we are all doing, we have a Google Doc where we take note of what we are doing as we are doing it. This helps us keep track of what we are doing, and what everyone else is doing.

## Next Steps
My group and I will definitely try to dive deeper into the code of our app and not just plan on what it will do and what it will look like. More specifically, our goal is to continue to work on our buttons. We are currently trying to add functionality to the button we just made, and we want to continue working on that for now.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)