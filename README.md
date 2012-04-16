## Jekyll / deck.js Presentation Template

* Recursively clone this repository.
* Delete either `example.markdown` and `_posts`, or `index.html`.
  * One is for Markdown presentations, the other for HTML.
* Write your presentation in `index.html` (HTML) or `_posts` (Markdown).
* Run [Jekyll](https://github.com/mojombo/jekyll).
* Your presentation will be under `_site`, with
  [deck.js](http://imakewebthings.com/deck.js/) included.

While it would be nice to write a presentation in Markdown, Jekyll
unfortunately requires that each slide be an individual file under
`_posts`. This is tedious, but it's there for your use. HTML is a lot
more flexible when using deck.js.
