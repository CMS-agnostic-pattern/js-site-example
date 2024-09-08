# Basic JS client site example

It's a basic illustration of how to use content data from the repository: 
https://github.com/CMS-agnostic-pattern/content-examples/tree/main/simple_site

You can see a demo here:
https://cms-agnostic-pattern-js-site-example.netlify.app

The idea is that we can take the content directly from the repository.

The problem with such implementation is that we need to have an index file with the list of JSONs, see 
https://raw.githubusercontent.com/CMS-agnostic-pattern/content-examples/main/simple_site/index.json

In the case of the static site generator approach, we can avoid that file, get the list of records locally, and generate the static site locally.
