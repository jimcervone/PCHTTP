# PCHTTP: A Simple Cocoa HTTP Client#

The mobile world (and more) is run on REST. Why is it such a pain in the ass?

Well, it's not any more. Introducing PCHTTP, a foolproof and simple interface to HTTP. It's been written from the ground up to be fundamentally less complex than many of the behemoth REST libraries out there. You don't need to include any external frameworks, and every HTTP method is its own PCHTTP method.

## The Whole of It ##

Sorry guys, but in order to keep it simple, PCHTTP requires at least iOS 4.0/OS X 10.6. Blocks, you know.

On the plus side, there's no need to muck about with .a or .framework files or linker flags. Just drag PCHTTP's files into your project, and `#import "PCHTTP.h"`. Done.

## Documentation ##

- [PCHTTPClient](http://pcperini.com/github/PCHTTP/PCHTTPClient/)
- [PCHTTPResponse](http://pcperini.com/github/PCHTTP/PCHTTPResponse/)
- [PCHTTPSerializer](http://pcperini.com/github/PCHTTP/PCHTTPSerializer/)

## Oh, and... ##

PCHTTP is ARCed. It also teneously relies on part of my PCSnippets project, `PCContainerComprehension` (also included in this project). If you _really_ don't want to use those categories, just change `+keyValueEvaluateDictionary:` in `PCHTTPSerializer`.