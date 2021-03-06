# auto_keystroke
 Automate synced key presses on two computers
 
 This is currently a prototype! What it does is just to trigger one single key press on each of the two computers, initiated by one key from the sender.
 
 Requires Max/MSP and Java SDK
 
 Make sure the repository is cloned within the Max search path, or put /java/ into the Max Library folder.
 [mxj autobot source](https://sites.google.com/site/theoldmanthesea/download/)
 
## Instructions for auto_keystroke_send
 To be opened with the computer doing the trigger
 1. Select the keyboard device.
 2. Turn on toggle for detection of keypress on the specified keyboard.
 3. Turn on toggle for detecting the code for key for triggering.
 4. Press the desired key once on your keyboard. The number is now updated.
 5. Turn off the toggle in step 3.
 6. Turn on toggle for testing output.
 7. Open a text editor and try to press the triggering key. See what is typed right after. Change the number in the box to amend the output and try again if necessary. The key press codes should be in alphabetical order (e.g. if P is 80, then Q is 81 and R is 82).
 8. Testing for key presses is now done. Turn off toggle in step 6.
 9. Press the button to send a ping to the auto_keystroke_receive patch opened on another computer.
 10. The latency is now shown in the number box. Leave it as it is unless it doesn't work.
 11. Run a latency test in your desired external server and enter the ping time in the number box.
 12. Enter the receiving computer's ping time in the server.
 13. All done. Turn on the toggle and see if everything works!
 
## Instructions for auto_keystroke_receive
 To be opened with the passive computer 
 1. Open a text editor. Turn on the toggle to test output. Go to the text editor window and see what is being typed.
 2. If the key being pressed is not the desired output, change the number in the box. You might have to experiment a bit.
 3. All done. Turn off toggle and enjoy!
