#jquery.latest-commit.js

###What does this do?
This jQuery plugin uses the GitHub API to retrieve the latest commit information from a repository. It's cool for showing off the latest changes for a project on a page.

### Usage
Stick this somewhere: `<div class="latest-commit" data-github="<user>/<repo>"></div>`, where `<user>` is a username, and `<repo>` is a repository name (do not include the angled brackets!).

Example: `<div class="latest-commit" data-github="skulbuny/jquery.latest-commit.js"></div>`

And include this dude somwhere (after you include jQuery), too: `<script src="/path/to/jquery.latest-commit.min.js"></script>`

### Styling
- `.latest-commit`: Styles the entire div
- `.commit-file`: Styles the link to the commit file
- `.commit`: Styles the commit message
- `.commit-link`: Styles the link to the commit

###Notes
Since this method does *not* use OAuth, the GitHub API limits API calls to 60/hr with basic authentication (what this plugin uses).

###[License](LICENSE)