# weather

This is simple weather forecast app built with ClojureScript and Reagent.

## Development

To get an interactive development environment run:

    make start

This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    make clean

To create a production build run:

	make build


## License

Copyright © 2018 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
