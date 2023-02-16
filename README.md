# SavedText
If you have a lot of text you commonly use, you can use this "website" to simply click to get it to your clipboard.

## How to use
### Download and "install"
Download `SavedText.html` and save it anywhere. Then simply open it in any webbrowser by double clicking it. This will open up the SavedText program.

### Adding a saved text
Saved texts are refered to as `commands`. Commands are formated in a specific way with a name and a textblob which should be put into the clipboard when the "Copy" button next to the name is pressed.

The program comes with a couple of example `commands`, you are free to remove all of them. That is anything between the `[]` in `var commands = [...]`.

### Formating text
At the end of the website there is a tool to format your text. Simply enter a name which will be shown next to the "Copy" button, and the text in which should be put in the clipboard when the "Copy" button is pressed.

When you press the "Generate command" button below this tool the "command" will be put in your clipboard. You will then have to add this to the `commands` variable as an element of the array. Hit save and reload the page in the browser to have the new command added.

#### Step-by-step to formating text
1. Enter the name of the text (which will be visible next to the "Copy"-button) in the first text box.
2. Enter the text which should be added to the clipboard when the "Copy"-button is pressed. Multiple lines is allowed.
3. Click "Generate command and put in Ctrl-V", this will put the correctly formated `command` in your clipboard.
4. Open the `SavedText.html` in a text editor, Notepad will do, and add the `command` inside the `[]` characters in `var commands = [..]` by using Ctrl+V.
5. Save `SaveText.html`.
6. Refresh the browser/reopen `SaveText.html` in the browser.
