Certificate Authorities and SSL Presentation
============================================

Generate the Presentation
-------------------------
Install the dependencies:
```bash
bundle install --path vendor --binstubs
```

Generate the presentation site:
```bash
bin/slideshow presentation
```

View the Presentation
---------------------
Load the site in a browser: `file:///your/local/code/path/presentation.html`

Be sure to allow javascript if running locally for full presentation support.
