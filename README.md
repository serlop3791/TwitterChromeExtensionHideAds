# TwitterChromeExtensionHideAds
A Chrome Extension for Twitter to hide annoying ads.
As you scroll through your home timeline, 
tweets with the word promoted are hidden before you even notice them.

Steps To Run:
1. Download source code and zip folder

Optional step: Read Security note at bottom.

2. Enable developer extensions on chrome settings.
Enter chrome://settings in search bar.

3. Load your extension in chrome settings 
More Tools > Extensions > Load Unpacked 

4. Load twitter. Click on the extension icon near the search bar (to the right) to enable the extension.
Scroll away.

A side note on security:
There are two files in the source code. 
One of the files contains a copy of the entire jquery library because I am lazy.
The jQuery library is needed to run the selector function ("$").
The selector function is highly convenient but I do not recommend you run minified code like this in your browser. A better security practice is to go to the jquery site (https://code.jquery.com/jquery-3.6.0.min.js) and download the jquery library yourself and then copy and paste it in the source code of this project before zipping and loading the extension.
