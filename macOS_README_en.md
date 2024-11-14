If you are a novice/newbie/cannot open/do not know which file to download, please read the following instructions.

If your computer (MacBook) has an Apple silicon chip,

Then download the file that ends with mac-arm64.dmg (line 4), otherwise download the file that ends with mac-x64.dmg (line 7).

After downloading, open the zip archive, then open the dmg file, then move the application to Applications.

Open a terminal (look for it in the bootstrap) and type the following 👇 commands

xattr -dr com.apple.quarantine /Applications/FreeTube.app

Then enter and open the FreeTube app again.

Still not working?

Open System Settings -> Privacy & Security Scroll down to the lowest level, find the FreeTube app, and allow it to open.

Still not working?

Open a terminal and type in the following 👇 command

sudo spctl --master-disable

Then enter, enter your password and then enter again, find the FreeTube application under the Applications path and right-click on it and then click Open.


The above content is translated from Chinese. If there are any errors, please point them out and correct them.