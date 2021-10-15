# Driver Setup
## MFlix Application Architecture
This lecture provides a walkthrough of the mflix-js application. To follow along, please download the handout and unzip it. Downloading may take a few minutes.

Note: The handout contains some hidden files like .babelrc. Please ensure you copy the entire directory to a new location rather than selecting all files within your system's file browser to copy and paste into a new directory.

## Asynchronous Programming in Node.js
```s
npm test -t callbacks-promises-async.spec.js 
```

And that covers callbacks, promises, and async/await at a high level and how the Node driver will behave when passed a callback or not.

If any of this is unclear, head to our forums to ask for help.

If you are very new to JavaScript and aren't familiar with callbacks or promises, there is a link in the documentation for this lesson that I highly recommend you read.

There are some things to remember.

You should always wrap await statements with a try and catch block.

If you aren't comfortable with promises, you can always supply a callback to the driver methods that are asynchronous.

And if you don't pass a callback, a promise will be returned.

## Basic Reads
To follow along with this lesson, open the file test/lessons/basic-reads.spec.js.


