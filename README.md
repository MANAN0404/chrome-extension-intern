# Chrome-Extension-Intern

This project is one oft the toughest thing i have done as time given was limited and to make it and resources were also less for it but that is the fun here to learn
something new in less time which also excites me.

In this project I have made an extension that works on top of any assessment website, starting when the
user opens a test page. Once the user clicks the &quot;end test&quot; button, the chrome
extension should be disabled and the browser should return to its normal state.

There are basically four files in this project.
1. background.js
2. icon.jpg
3. manifest.json
4. popup.html

Out of these manifest.json is one of the most important files because without this extension would not work.
In background.js we have first created an array where all the sites where our extension need to work currently i only added a sample reference site but you can
add any other site as well.
Next, I have created a function to check if the current tab is a test page, and as we proceed I have made a check if current tab is test page it will go 
full screen when the extension is activated.
The next basic thing added is for tab switch event as during test it is very common method of cheating and if new tab is created we will listen for it.
I have also created a function to check for audio, camera and internet stability along with there permissions and lastly storing the user-related data in 
local storage.


