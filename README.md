# resume_templates
Script that assists with automated application entry using autohotkey.

As you know, applying to jobs online can be quite tedious. 
Not only do sites request a copy of your resume and your cover letter, 
it is often required that you to manually enter all, or parts, of your 
work history into their application. Enter this script.

As you can see from the code, we are basically adding buttons to a GUI window. 
When you click the button for the Title, for example, the program switches back 
to the last active window (line 12) with Alt+Esc (where you clicked the cursor), 
it then sends (types) whatever text you place on line 13. 

If you do not want to hardcode your data, I would recommend [delimiting](https://www.autohotkey.com/docs/commands/_EscapeChar.htm#Delimiter) the 
text and reading in your document systematically to ameliorate the impact
of submitting many applications. Good luck out there.
