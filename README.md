Static Auth Sample
==================


Description
-----------

This sample demonstrates how to restrict access to authenticated users on
Windows Azure Websites.

It is based on this article:

Apply ASP.NET Authentication and Authorization Rules to Static Content with
IIS 7.0's Integrated Pipeline Feature
http://www.4guysfromrolla.com/articles/122408-1.aspx


Instructions
------------

1. Deploy on a Windows Azure Website.
2. Access "http://websitename.azurewebsites.net". It should display
"Public file".
3. Access "http://websitename.azurewebsites.net/private". It should require
credentials (Alice/secret) and then display "Private file".

The sample built-in credentials can be replaced by an ASP.NET authentication
provider.


License
-------

The MIT License (MIT)

Copyright (c) 2013 Fernando de Alcântara Correia (www.fernandocorreia.info)

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