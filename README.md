# css-bootstrap

An extremely minimal CSS/Compass/Sass bootstrap for new projects. Like... seriously minimal. That's how I roll.

To compile the CSS for testing, first [install Compass](http://compass-style.org/). Then, run the following command:

``` compass compile ```

To have Compass watch the .sass files and automatically recompile each time a change is detected, run the following command:

``` compass watch ```

By default, Compass adds comments to the compiled CSS file which reference line numbers from the source Sass files. This is great for testing, but makes the file much larger than needed so it shouldn't be used in production. To compile and compress the file for production, run the following command:

``` compass compile -e production --force ```
