nide
====

`nide` is a web-based IDE for node.js. It’s designed with simplicity and ease-of-use in mind.
`nide` was initially developed as part of the Node Knockout 48 hour coding competition.

`nide`’s current features:

- Project tree display
- File operations (create/delete/rename files and folders, hide/show hidden files)
- Syntax highlighted code editing
- OS X Lion-style automatic save
- OS X Lion-style version management with revert and side-by-side editing features
- Real time project tree filtering (using regular expressions)
- NPM integration (display currently installed packages, add/remove packages)
- Sleek interface reminiscent of TextMate
- Node.JS Documentation browsing

Planned features:

- Git integration
- Simultaneous multi-user editing

Instructions
============

First, install nide with:

    sudo npm install -g nide

On a new or existing directory, use the following command to setup a new nide project:

    nide init

This command will setup a `.nide` directory, automatically add it to your `.npmignore`
and `.gitignore` files, and start the `nide` server on port 8123. Fire up your web browser
at `localhost:8123` to use nide. If a directory is already a nide project, you can run
nide simply by using:

    nide

License
=======

Nide is released under a **MIT License**:

    Copyright (C) 2011 by Marco Aurélio
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.