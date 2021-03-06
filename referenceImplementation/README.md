IMVVM Reference Implementation
=====

[IMVVM](https://github.com/entrendipity/imvvm) helps implement the Model-View-ViewModel pattern in [React](http://facebook.github.io/react/) applications. It's role is to provide the framework to create Models and ViewModels, with React acting as the View. It is designed to complement React. The IMVVM API gets its inspiration from the React library. So it feels like React. This makes it easy to understand and enables you to be productive in a short time frame.

This example application is a reference implementation to be read with the [Developer's Guide](https://github.com/entrendipity/imvvm/wiki/Developer's-Guide). It is a little contrived and not necessarily the way you would strucuture your application, but it uses all of the API to demonstrate how each function is used. 

IMVVM Documentation can be found [here.](https://github.com/entrendipity/imvvm/wiki)  
#### Screen shot
![Screen shot](/referenceImplementation/ScreenShot_Example.png?raw=true)

## Setup Example Application
* clone or download repository
* open console
* navigate to download directory
* run `npm install`
* cd app
* run `bower install`
* cd ..
* run `grunt serve`

_n.b. The application uses client-side pushState routing and does not reference a server. If you lose the application, navigate to localhost:9000 and not localhost:9000/people to reinitialize the application. This is not how it would work when using a remote server._

## Author
Frank Panetta  - [Follow @fattenap](https://twitter.com/intent/follow?screen_name=fattenap)

##License
###The MIT License (MIT)

Copyright (c) 2014 Entrendipity

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.