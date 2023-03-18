# Night's Bloxflip Predictor

Bloxflip Predictor written in Python using customtkinter and hiddenselenium

Very high accuracy (>85%) in mines, crash, etc. 

**HOW TO USE:**
1. Make sure your anti-virus is not deleting the file - this happens because your antivirus detects that hiddenselenium is injecting into bloxflip (needed for the predictor). If it is, turn it off and then back on after running the file.

2. Wait for the prompt that says "Looking for Bloxflip instance" and then open the Bloxflip website. The predictor will automatically find your browser window and launch the GUI.

3. Select game mode in the predictor and run the same mode on the Bloxflip website.

4. Enjoy! 

- **NOTE:** DO *NOT* WIN OVER 10K ROBUX IN THE SAME DAY USING THIS. Bloxflip staff will check your win logs and catch on because of the high win rate / accuracy.

Q: What browsers are supported?

A: Currently, most modern browsers that are compatible with selenium such as Chrome, Brave, OperaGX, Edge, and Firefox are supported. Safari may work too, but it has not been tested as it uses MacOS.


Q: Crashed with error code 400 : Invalid Website.

A: This means it could not find an instance of bloxflip running in your browser. Try restarting your browser or using a different one. This will be fixed in a future update to be more reliable.

TODO:
- Use pypuppeteer or playwright instead of hiddenselenium which is outdated.
- Convert into a discord bot.
- Make predictions based on round ids instead of injecting into browser.
- Fix random crashes 
- Implement support for MacOS and Linux.
- Change color scheme based on system color settings. (DONE)

GUI:

![gui](https://user-images.githubusercontent.com/127027405/226115440-d5765159-8c2d-4e60-bae4-5c5b69d69976.png)
