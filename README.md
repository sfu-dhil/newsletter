# DHIL Newsletters

This is the repository for the DHIL newsletters. It has two directories:

1. `template/`

    This contains a file called `base.html`, which is the basic template to be used for the DHIL newsletters. It can certainly be modified, but note that any modifcations used to it *will not* change any previous emails.

2. `sent/`

    This contains all of the sent emails. They should be named for the date they are sent in ISO format (i.e. `2020-02-01.html`)
    
    
    
## How to use this

### First time:

1. The first time you work with this, you will have to fork the repo into your personal account

### Every other time:

1. Make sure your repository is up to date with the sfu-dhil upstream one.
1. Copy `template/template.html` into the `sent/` folder with the date you plan to send the email (`i.e. sent/2020-04-02.html`).
1. Modify the template with the new content; the HTML is gnarly (because it's an email), but the comments inside should give a fairly good indication of what content goes where.
1. You can view the HTML and see how everything looks by opening it in any browser (just right click and open using Chrome or whatever, or just drag the HTML file into the browser)
1. Once you're finished and happy with the email template, make sure to do a pull request and push it back to the main repository


### Sending the email

1. To send the email, you can simply copy and paste the *rendered content from the browser* into an email client. Outlook works well for this, since it's the most constrained. 
1. Make sure to send the email to yourself and others in the DHIL group and test on a variety of email platforms to make sure everything looks relatively ok (there will be differences between them, but there's no way to really resolve that).