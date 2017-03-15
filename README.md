Chrome extensions for show jenkins jobs in gerrit page
======================================================

example of the result:

```
+--------------------+------------------ -+
|header row          | header 2           |
|(jenkins pipeline)  | (the time to run)  |
+====================+====================+
|body row (job)      | result + run time  |
+--------------------+--------------------+

```

User Guide
----------

1. Clone the toggle-ci from github:

   git clone https://github.com/openzero-team/toggle-ci 

2. Load the extension:

   1)Visit chrome://extensions in your browser, or open up the Chrome menu by
     clicking the icon to the far right of the Omnibox:  The menu's icon is
     three horizontal bars. Select Extensions under the Tools menu to get to
     the same place
   2)Ensure that the Developer mode checkbox in the top right-hand corner is
     checked.
   3)Click Load unpacked extension… to pop up a file-selection dialog
   4)Navigate to the directory(jenkins-jobs-show/code) in which your extension
     files live, and select it.

   Alternatively, you can drag and drop the XXX.crx file onto
   chrome://extensions in your browser to load it.

   If the extension is valid, it'll be loaded up and active right away! If
   it's invalid, an error message will be displayed at the top of the page.
   Correct the error, and try again.

3. Go to your gerrit page and refresh

   Now you can see the summary of the pipeline, all jenkins jobs and results
   under the 'Label' in the gerrit page.
 
   ![img](https://github.com/openzero-team/toggle-ci/raw/master/img/ci_jobs.png)

   click the `Toggle Ci` in the bottom, you can hide the ci comments in the
   page.

   ![img](https://github.com/openzero-team/toggle-ci/raw/master/img/hide_ci.png)
