

# Sublime Writer

![Sublime Writer](http://f.cl.ly/items/2b3B2t0F1P2V3G3I1h10/sublime-writer.png)

Sublime Writer is a quick color scheme I made to mimic the aesthetic of iA writer inside of Sublime Text. The goal being when you open, edit, or create a new file in markdown, it is automatically themed to look like sublime writer.

Becuase of Sublime Text 2's amazing "Distraction Free" mode you can even run at full screen, much like in iA Writer. If you don't think this is awesome yet, imagine iA Writer with multiple cursors. Yeah, I thought so.

## Installing
1. Install Nitti.otf (or similar font, see notes).
2. Drop the provided "Markdown.sublime-settings" (Sublime Writer > User > Markdown.sublime-settings) into your User Folder. (Sublime Text 2 > Browse Packages > User)
3. Drop the "Color Scheme - Sublime Writer" folder to your packages folder. (Sublime Text 2 > Browse Packages)

## Extras ##
I've also included sublime-settings files for the amazing [Plain Tasks](https://github.com/aziz/PlainTasks "Plain Tasks") package (available via package control). Putting this file in your User folder will apply the sublime writer theme to .todo files as well as markdown files.

## Important Notes ##
Sublime Writer relies on Blue Monday's "Nitti Light" font, available [here.](http://www.boldmonday.com/en/nitti_overview "Blue Monday - Nitti Light") Obviously due to the EULA of the font, I can't make that available for download. If you don't have this font, feel free to use another monospace font such as Menlo, Inconsolata or Courier New, many of which are free. Just change line 16 of the sublime-settings file to whatever font you'd like to use.

Additionally, you can apply the theme to work for whatever file format you'd like by simply creating a new file of the type you'd like to apply the theme to, then selecting Sublime Text 2 > Preferences > Settings - More > Syntax Specific - User. This will open a new file, just copy the contents of Markdown.sublime-settings into this new file and save. Let me know if you have any trouble: @paulcpederson.
