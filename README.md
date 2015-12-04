# Website Loading Performance Project

This repository contains a pseudo-blog of an astronomist with a homepage and several articles. This website loads slowly; its articles have only 69 points in Google PageSpeed Insights. Your challenge is to optimize it to as high score as you can and write helpful Gulp tasks that could do the routine in the future.

The project is a task for [Website Performance lecture](http://iamakulov.com/talks/web-perf) listeners.

## Get the project

**Clone the repository:**

    $ git clone https://github.com/iamakulov/web-perf-task.git
    $ cd web-perf-task
    $ npm install
    
**Start the server:**

    $ gulp
    
This will build the project, start watching the files for changes, connect autoreload and launch a local server on [localhost:8080](http://localhost:8080/).
You might need to install `gulp` firstly:

    $ npm install gulp -g
    
**Connect localhost to a publicly accessible URL:**

    $ npm install ngrok -g
    $ ngrok http 8080
    
(The first `ngrok` launch could take a while.)


## Code

Once the server is started, code!

What to optimize:

* Article template: some CSS and JavaScript is render-blocking. 
* Code: some code might need minification and compression.
* Images: some images could be have too high dimensions or size.

Consider writing `gulp` tasks for the last two points. 

 
## License

MIT © [Ivan Akulov](http://iamakulov.com)

