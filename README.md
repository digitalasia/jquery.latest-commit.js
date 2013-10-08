#jquery.latest-commit.js

### Usage
Stick this somewhere: `<div class="latest-commit" data-github="<user>/<repo>"></div>`
Example: `<div class="latest-commit" data-github="skulbuny/jquery.latest-commit.js"></div>`

And include this dude somwhere, too: `<script src="/path/to/jquery.latest-commit.js"></script>`

###Notes
Since this method does *not* use OAuth, the GitHub API limits API calls to 60/hr with basic authentication (what this plugin uses).

###[License](LICENSE)