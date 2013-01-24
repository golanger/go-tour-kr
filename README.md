## Go Tour Korean App Engine version.

Korean: [http://go-tour-kr.appspot.com](http://go-tour-kr.appspot.com)  
English: [http://tour.golang.org](http://tour.golang.org)

Korean translation: [http://github.com/golanger/go-tour-translator](http://github.com/golanger/go-tour-translator)


*Below is the original Go Tour App Engine README file.*
----------
This is the App Engine version of the Go Playground.

To deploy: (instructions relative to the appengine directory)

1. Make a copy of the static and template directories.
	
	cp -r ../{static,template} .

2. Edit static/mode.js to set the tourMode variable to "appengine".

3. Edit app.yaml to set the application name to something you have access to.

4. Use appcfg.py to deploy it.

	/path/to/sdk/appcfg.py update .

