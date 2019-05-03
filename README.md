# A simple way is to masquerade the HTML app as a PHP App to run on HEROKU
https://stackoverflow.com/questions/10551273/is-it-possible-to-upload-a-simple-html-and-javascript-file-structure-to-heroku
1. Rename your index.html file to home.html.
2. Create an index.php file and include your entry html file. If your HTML entry file is named home.html as recommended, your index.php      should look like:

<?php include_once("home.html"); ?>

# Core

Core is a small game built using the HTML5 canvas element and plenty of JavaScript.

Curious about how this looks in action? [Check out the live demo.](http://hakim.se/experiments/html5/core/01).\

## Sound

Sound design by Luis Bergmann (@luisbergmann)

## License

MIT licensed

Copyright (C) 2018 Hakim El Hattab, http://hakim.se
