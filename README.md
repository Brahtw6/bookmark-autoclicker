# bookmark-autoclicker
An AutoClicker bookmarklet. Does what it says on the tin.
## How to use:
Put the following script in the URL of a bookmark.
`javascript:fetch("https://raw.githubusercontent.com/sylvxa/bookmark-autoclicker/main/autoclicker.js").then((response) => response.text()).then((responseText) => {eval(responseText)});`
