
# FAQ

## Are my files sent to a remote server? 
No. Texti runs entirely in your browser--no files leave your device.

## What is the license of this software?
Texti uses the open source AGPLv3 license.  This license is required due to using the dependency muPDF to read PDF files.  

## Where can I view the code?
The code is available on GitHub [here](https://github.com/Balearica/texti).

## Why isn't x format supported?
We are not philosophically opposed to including any file format.  If a format is not supported, either (1) nobody has gotten to adding it yet or (2) reading the format would require an additional JavaScript/Webassembly library and no such (acceptable) library exists.  Feel free to suggest new formats on our [GitHub page](https://github.com/Balearica/texti), or better yet, contribute a read function yourself and open a pull request.

For a JavaScript library to be acceptable for including, it must (1) execute code entirely in the browser [user files cannot be sent to any remote server], (2) have a compatible license, and (3) uphold a reasonable standard of quality [e.g. does not bloat load times, does not frequently throw errors, etc.].  