# Companies Hub videos

This project is an HTML page that is included in the [companies hub page](http://markets.ft.com/research/Markets/Company-Content) to create a video widget.  To include it, copy this HTML into the companies hub page:

    <iframe src="http://financial-times.github.io/comphubvids/" style="width: 590px; height:370px; overflow: hidden; border:none;" frameborder="0"></iframe>

The live version of the widget is located at http://financial-times.github.io/comphubvids/.

## Editing the videos

To edit the videos you need to edit the HTML file in this repository, and upload new images for the video thumbnails.

1. If you don't already have an account on GitHub, get one by filling in the big registration form on the homepage of [GitHub.com](http://github.com).
2. If you do not already have commit rights on the **comphubvids** module, ask one of the FT's GitHub administrators to give you access.
3. If you haven't already got the GitHub app installed on your computer, [download it](http://windows.github.com/) (or [for mac](http://mac.github.com/))
4. Run the Github app on your computer and sign in using your GitHub account
5. Clone the **comphubvids** project to your computer
6. Open the `index.html` file (created by Github on your computer) in a text editor such as Notepad (if you double click it, it will open in your internet browser, so don't do that.  Instead, open Notepad first, then choose File > Open to open the index.html file)
7. Edit the data between the lines `// START EDITING HERE` and `// STOP EDITING HERE` and save when done
8. Update the images in the *images* folder, using the filenames you set in the data you put into index.html
9. Double click the index.html file to preview your changes in your web browser.  Click each video in turn to make sure they load and play correctly.
10. Switch back to the Github app and commit and sync your changes.
11. Within a few minutes, the live version of the widget will update to reflect your changes.
