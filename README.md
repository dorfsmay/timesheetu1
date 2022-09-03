## Purpose and history
Originally created for a customer's specific reporting requirements, the html, css and javascript content are all contained within a single html file. It defaults to the previous week (Sunday based) and a typical 40 hour. The resulting timesheet is updated automatically when the date and duration fileds are changed.

## Usage
Either:
- Load [the html file on htmlpreview.github.io](https://htmlpreview.github.io/?https://github.com/dorfsmay/timesheetu1/blob/main/timesheetu1.html) in your browser

Or:
- download [timesheetu1.html](timesheetu1.html)
- modify the html and javascript if needed
- point your browser to file:///path/to/your/file

Then:
- adjust date and hours if needed
- select the table and copy
- paste in an html email

_note_: There is a bug in Firefox (see bugzilla [#1772785](https://bugzilla.mozilla.org/show_bug.cgi?id=1772785) and [#1646515](https://bugzilla.mozilla.org/show_bug.cgi?id=1646515)), copy/paste of rich text does not copy the styling. Use Chromium for now.
