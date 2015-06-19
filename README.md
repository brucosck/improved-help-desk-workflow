## Tested Working Example ##

Just go to: https://docs.google.com/spreadsheet/ccc?key=0An3fRKgHaQCzdEIxemZzQ1ZTVkJfSnBiU19lbU9MZlE

I've already installed the script through Script Gallery and you can see the form at Form > Go to live form.

# Installation #

  1. Go to Google Spreadsheet > Script Gallery.
  1. Search for 'Improved Help Desk Workflow'
  1. Install it.
  1. Create a form with 3 options:
    * Automatically retrieve user e-mail in Apps Domain (if you do not have Google Apps Domain, just create a text item named "Username")
    * A drop-down list named 'Type of problem'
    * A paragraph-text named 'Description'
  1. The drop-down list must contain (without quotes):
    * "Gmail", "Fileserver", "Internet", "Calendar", "Hardware", "Group", "Software", "Google Docs", "Other plataforms - Google Apps (Sites etc)", "Other"
  1. You can create more of them if you want. But you will need to customize the script.
  1. Add manually all those headers columns in your spreadsheet (without quotes):
    * "Criticality", "Status", "Operator", "SLA answer", "SLA solution", "Resolution", "Notes", "Start time", "End time", "Delta"
  1. Some of them will already be in the spreadsheet due to the form creation.
  1. Go to Google Spreadsheet > Script Editor.
  1. Open the file Globals and edit with all your Apps Domain settings
  1. Inside the script editor, go to Resources > Current script triggers
  1. Create 2 triggers like the screenshot:
    * ![https://s3.amazonaws.com/geral_cube/triggers.png](https://s3.amazonaws.com/geral_cube/triggers.png)
  1. Test it sending a ticket through the form!
  1. Enjoy!