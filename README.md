This whole project is pretty much useless at this point with the token limit increase and file uploads. Was nice when it was needed though.


# Chat Gpt Long Text Input
A browser plugin for ChatGPT that simplifies sending large texts by breaking them into multiple messages. 


- Custom initial message.
- Custom prepended message before each section of the of the split up text.
- Custom appended message after each section of the split up text.
- Optional Custom final message after completing message input.
- Reset button resets prompts to defaults 
- Resume button resumes entry from specified starting point in the input text.
- Stop buttoncancels any active input.
- Import text files (.txt, .csv, .xml, etc)
- Real time estimate of batch completion
- Display how many messages will be sent before sending

To import text files, click the enable file picker button option above the "Text to Import" box while in a chatgpt chat window. This will add a button onto the current chat to the left of the regenerate response button if it is visisble. Clicking this will open a file dialog, which will import the file into the plugins input area.

I tried to add the filepicker to the plugin popup but was unable to do so with the lifecycle of the popup when the filepicker popup grabs focus. 

# Install

|Platform|Current version|
|------------------|-----|
|[Official Firefox Plugin](https://addons.mozilla.org/firefox/addon/chat-gpt-long-text-input/)| 1.8.4 |
|[Official Chrome Plugin](https://chrome.google.com/webstore/detail/chat-gpt-long-text-input/hbomibpicdjokaedngbojejahflkippj)|1.8.4 |


## Screencaps:
![Popup](https://raw.githubusercontent.com/NicoleFaye/Chat-Gpt-Long-Text-Input/Firefox-Main/screencaps/mainPage.png)
![Settings](https://raw.githubusercontent.com/NicoleFaye/Chat-Gpt-Long-Text-Input/Firefox-Main/screencaps/settingsPage.png)

