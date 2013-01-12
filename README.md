TopWatch_IPK
============

Example of am IPK file and screen shots built for submission to the webOS store.

This is Part IIb of my [rambling tutorial](http://pcimino.blog.com/enyo/). Not necessarily a step-by-step, and not exactly lessons learned, somewhere in between, like "brunch."

In the [TopWatch_Build](https://github.com/pcimino/TopWatch_Build) project, I have a script tools\install_webos.bat which takes the code created in the \deploy directory, and creates the IPK package file used to submit the application to the webOS catalog (ie app store).

This project contains the IPK, this readme, and a directory with files required to submit the application. I include it to show how easy it is to submit your apps, and if you're building a portable app, why not take the minimal effort required to broaden your audience? The HP/Palm devices were officially dicontinued in the summer of 2011, but I still get some revenue from sales every month.

Not a webOS developer? [Signup here](), the forums are still active, although most developers are moving over to [Enyojs](http://enyojs.com/).

## What's in Here
	\README.md : This file.  
	\submission  
		com.translunardesigns.topwatch_1.0.0_all.ipk : This is the package file that can be installed onto a webOS device  
		desc.txt : Text describing the application, submitted with the applciation  
		ApplicationScreen_Languages.png : Screen shot of the lsupported language tabs from the app submission process  
		\icons  
			icon48.png : Application 48 x 48 pixel icon  
			icon64.png : Application 64 x 64 pixel icon  
		\phone_screens : Contains 3 screen shots in 320x480 (or 480x320) pixels  
		\tablet_screens : Contains 3 screen shots in 768x1024 (or 1024x768) pixels  
			
## Submitting the app

There are rules and procedures, none too daunting. And there is a review process, but if your app doesn't get approved in a week, go onto the forums and you'll find how to contact someone and ask for a status. Sometimes apps get stuck in process and need a little human intervention.

So go to the [Palm (yes, Palm) developer website](https://developer.palm.com/) and signup, login and have your app and images ready to go. The first time it took me a while and multiple tries; once your know what you're doing and you're prepared, it takes a few minutes.

## The tricky Prep
On any screen during the submit process you can save your progress and come back later. But there are a few things worth knowing to speed up the process.

1. Know if you're making it free or paid. You can submit two similar apps with similar (but not identical) package names (e.g. com.translunar.amtrakfree and com.translunar.amtrak) but once an app is submitted you can't convert form paid to free or vice versa. You CAN change the price, and you can generate demo codes to give out free copies of a paid app. Paid apps require some extra hoops setting up your profile so you can get paid.
2. Know which open source license you want to use:  
	Apache License  
	Artistic License  
	Eclipse Public License  
	GNU General Public License  
	GNU Lesser General Public License  
	MIT License  
	Mozilla Public License  
	New BSD License  
Discussions on the forums are a good place to learn some of the pros and cons of these. Obviously, you might actually want to READ some of them to make sure your comfortable.
3. Know which OS versions you're going to submit to, Enyo 2 doesn't appear to work on older 1.x devices. Ver. 2.x is available on the Pre3 (HP branded phone, not officially released outside the UK, but plenty out there) and 3.x is on the Touchpad tablet.
3. Know your distribution: App Catalog is probably the one you want. Beta is for beta testing feeds, and Web Distribution provides a way for you to host it and people can downlaod and install from a link. I've never done this, no idea if it's trivial or tricky.
4. Have your images ready. The important thing are the sizes, which are easy if you have the devices or emulator and take screen shots, but you can also manually create them.  
	Palm Pre/Pe+ (320x480)  
	HP Pre3 (480x800)  
	HP TouchPad (768x1024 or 1024x768)  
5. On the Application Info (3rd) page you're asked about your company, notice the language tabs, if you don't want to fill out one for each language, X out the one's you don't want (need at least one). This is the part I often forget until I get to the last step and can't figure out why I can't submit my app.
![Languages in submission](https://github.com/pcimino/TopWatch_IPK/blob/master/submission/ApplicationScreen_Languages.png)


