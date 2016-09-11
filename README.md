## Website Performance Optimization portfolio project

To optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques I've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

## How to run
- To run this web site go into the root directory.
- Fire up the terminal/cmd.
- Run `python SimpleHTTPServer 3000`.
- Now fire up the browser head over to `localhost:3000`.

### Optimizations
- reduced the size of images sufficently.
- used async attribute to script tags.
- reduced crp length by using defer and async.
- Removed forced synchronous layout by removing the layout triggring code from the `views/js/main.js`.
- Added vendor prefixes in the `views/css/style.css` file.
- Added `strict mode`.
-