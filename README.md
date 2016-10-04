[issue.js](https://github.com/andreastt/issue-widget/blob/master/issue.js)
provides a widget that will appear in HTML documents
when text is selected
that allows extraction of prose
to form quotations of new GitHub issues.

The widget will appear
when the user selects text in the document.
When clicking the button that appears,
the selected text is quoted,
along with references to the chapter and section
from whence the quote came,
in the new GitHub issue that is created.

Configure by setting the GitHub project URL
and any optional parameter fields
in the new issue form you want populated:

    <html
     data-issue-url="https://github.com/w3c/webdriver"
     data-issue-param-milestone="Level 1">

This is inspired by the “Simple Bug File Assistant”
which was available for the W3C Bugzilla bug tracker.

The widget currently assumes
that it is being used with
a ReSpec formatted W3C specification,
but it can be made to work independently.
