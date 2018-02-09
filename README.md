# Uno
### Setup instructions
1. install jGRASP following the instructions [here](https://courses.cs.washington.edu/courses/cse14x/software/jgrasp.html)
1. download [this zip file](https://drive.google.com/open?id=1UCMPdlqFl6zOxCwGJhXbM7xrl6LeQTUA)
1. extract it to a working location on your computer
1. open the `uno` folder (from the newly extracted folder! not from inside the zip file)
1. find the file `keyboardCat_UnoPlayer.java` and rename it to replace `keyboardCat` with your school username (like `18skywan_UnoPlayer.java`)
1. go back up one folder, then double-click the `Uno.gpj` file (type "jGRASP project), which your computer should open in jGRASP
1. in the `Open Projects` section of the screen, you should see a little purple document icon next to a project called `Uno`
1. right-click `Uno` and select `Add files`, then navigate to and add the file you just renamed in one of the steps above
1. in the `Open Projects` section of the screen, look under the little purple document icon called `Uno` for a folder called `source files` (if you don't see it, click the little plus button next to the purple icon to expand it)
1. expand the `source files` folder by pressing the little plus button next to it and you should see 7-10 files
1. one of those files is `players.txt`. open that file and change `keyboardCat` to your username, and press CTRL-S (or CMD-s) to save
1. go back to the source files and find the one called `TestCaseProcessor.java`. open that file. then from the menubar select Build, then select Run Arguments. a long skinny textbox just appeared above your edit window, with a label next to it that says "Run Arguments". in that empty textbox, write your username.
1. go back to the source files and find the one called `UnoSimulation.java`. open that file. then from the menubar select Build, then select Run Arguments. a long skinny textbox just appeared above your edit window, with a label next to it that says "Run Arguments". in that empty textbox, write `1 verbose`.
1. go back to the source files and find the one with your username in the title. double-click that file to open it in the edit window
1. ~~edit the code. save often with CTRL-s or CMD-s~~skip this step for now, we'll do it in class together Monday
1. when you are ready to run your code, press CTRL-r (or maybe CMD-r on Mac?), select one of the following options, and click okay:
   1. select `uno.TestCaseProcessor` to test your code on 10,000 hands to be sure your code doesn't throw any errors
   1. OPTIONAL: select `uno.UnoSimulation` to run one round. study the contents of the `Run I/O` tab to see how the round played out.

### Definition of done
Your code:
* passes all the tests in `TestCaseProcessor`
* meets the requirements of "For a B..." or "For an A..." in the grading section of the tournament packet

To submit your code, send Mr. Smith an email (andrewsmith@wcsu.net) with your `USERNAME_UnoPlayer.java` file as an attachment
