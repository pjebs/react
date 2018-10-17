Go with React [![GoDoc](http://godoc.org/github.com/rocketlaunchr/react?status.svg)](http://godoc.org/github.com/rocketlaunchr/react) [![Go Report Card](https://goreportcard.com/badge/github.com/rocketlaunchr/react)](https://goreportcard.com/report/github.com/rocketlaunchr/react)
===============

Facebook's React is one of the most dominant libraries for front-end development around. Google's Go programming language is one of the most elegantly crafted languages for server development. Why not combine the two?

See [Tutorial here](https://medium.com/@rocketlaunchr.cloud/go-with-react-24d987c6ec6e)

## Dependencies

* [React 16.5.2](https://www.npmjs.com/package/react) (it will probably work with lower)
* [Gopherjs](https://github.com/gopherjs/gopherjs)
* [create-react-class](https://www.npmjs.com/package/create-react-class)

## Examples

### Uptime Timer

* How to create a React Class components
* How to pass props from parent to child
* How to use **HydrateProps()** and **HydrateState**
* How to use **state()** and **setState()**
* How to create strongly-typed structured props and states

### Event Handling

* How to create functional components
* How to handle events (and pass extra arguments)
* How to create a Ref and interact with dom object directly

## Performance Tips

* Use `-m` command line flag to instruct gopher.js to minify code. Then minify further with webpack.
* Apply (gzip compression)[https://en.wikipedia.org/wiki/HTTP_compression]
* Use int instead of (u)int8/16/32/64
* Use float64 instead of float32
* Try to avoid importing `fmt` package (either directly or indirectly)
* Use **react.JSFn()** and use native javascript functions as much as possible.
* https://github.com/gopherjs/gopherjs/wiki/JavaScript-Tips-and-Gotchas

#

### Legal Information

The license is a modified MIT license. Refer to `LICENSE` file for more details.

**© 2018 PJ Engineering and Business Solutions Pty. Ltd.**

### Final Notes

Feel free to enhance features by issuing pull-requests.

**Star** the project to show your appreciation.
