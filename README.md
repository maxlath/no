NO
==

"Nice" redirect page for websites banned by [LeechBlock](https://addons.mozilla.org/fr/firefox/addon/leechblock/) with:
- a picture expliciting that you have nothing to do here
- a frame with my todo.txt


HowTo
-----
*copy this repo somewhere-on-your-pc
`cd $somewhere-on-your-pc`
`git clone git@github.com:maxlath/no.git`

*move your todo in this same somewhere-on-your-pc/no/ folder

*change the object property `data="todo"` to match the path to your todo
(`data="todo"` will work only if your file is in this same $somewhere-on-your-pc/no/ folder with the name `todo`)

*change the settings in LeechBlock to redirect to the url `file://$somewhere-on-your-pc/no/no.html`
(beware of the tripple `/` in `file:///home/path/to/no/no.html`)

*enjoy a nice way to bash yourself for your attention deficit disorder syndroms \o/