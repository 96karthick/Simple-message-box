# Simple-message-box
Using html,java script and CSS to create this box
Overview:

The code creates a simple message box with the following functionality:

A textarea for typing a message.

Character count display, showing how many characters are entered (up to 200).

Two buttons: Copy (to copy the text to the clipboard) and Clear (to clear the textarea).

Key Components:

HTML Structure:

A container card holds the textarea and buttons.

The textarea allows users to type a message with a 200-character limit.

Two buttons beneath the textarea trigger copy and clear actions.

CSS Styling (Tailored for a Clean Design):

Centered layout with black background and a white card for contrast.

Simple form controls with subtle styling, like rounded corners and shadows.

A character counter aligned to the right of the textarea.

JavaScript Logic:

The character counter updates in real-time as the user types.

The copyText() function selects and copies the text from the textarea.

The clearText() function clears the textarea and resets the counter to 0.

Functionality:

Typing: As the user types in the textarea, the character count updates dynamically.

Copy: Clicking the Copy button copies the entered text to the clipboard.

Clear: Clicking the Clear button clears the textarea and resets the character count.
