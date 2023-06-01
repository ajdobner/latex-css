## Document structure
The following structure for the `body` of an html page containing latex articles makes sense semantically to me:

* `header` for a website banner (and possibly a `nav`)
* `main` for any website content that's not a banner or footer. If the page contains a blog post or note, then we have an:
  * `article` tag
    * another `header` containing the title and abstract
    * a `nav` if there's table of contents
    * content of the article
* `footer` for website stuff e.g. saying "Created by blah"

Possibly the `article` tag is unnecessary but it seems semantically relevant. For example: could have multiple articles in a page; or could place a link to a pdf version of the article in `main` and outside the `article` tag.
