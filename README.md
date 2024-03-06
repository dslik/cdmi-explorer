CDMI Explorer
=============

[![license][license-img]][github] [![github][github-img]][github]

CDMI Explorer is a HTML/JS/AJAX browser-resident CDMI client that provides
basic access to a CDMI server.

Functionality supported includes:

* Listing the contents of a CDMI container
* Navigating through a hierachy of CDMI containers
* Creating new CDMI containers
* Deleting CDMI containrs
* Uploading one or more files as CDMI data objects
* Accessing the contents of a CDMI data object in the browser
* Deleting CDMI data objects
* Viewing Last Modified and Size metadata of CDMI data objects

The CDMI Explorer is deployed by uploading it to a CDMI server, then
accessing it through a web browser.

![image](https://github.com/dslik/cdmi-explorer/assets/5757591/b0fc4fb2-44d9-4d8e-8aec-fd3a96cdbf47)


## Releases

### 1.5.0 Release

Release for 2018 Storage Developer's Conference.

The following features have been added:

* Mimetypes for uploaded files
* Viewing of CDMI representations of objects
* Editing of CDMI representations of objects

CDMI Explorer has been tested in Safari 11 and FireFox 58.

### 1.3.3 Release

First public release.

This software was developed as part of NetApp, Inc's contributions to the SNIA
Cloud Storage Technical Working Group in order to validate and demonstrate CDMI
functionality.

CDMI Explorer has been tested in Safari 5, Safari 6, and Chrome 37.

### Future Releases

The following features are under consideration for addition in a future release:

* Enabling/disabling of functionality based on capabilities
* Object Inspector - Capability view

## License
Clear BSD License

Copyright (c) – 2014, NetApp, Inc.  All rights reserved. 
        
Redistribution and use in source and binary forms, with or without modification, are
permitted (subject to the limitations in the disclaimer below) provided that the
following conditions are met: 

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer. 
* Redistributions in binary form must reproduce the above copyright notice, this
  list of conditions and the following disclaimer in the documentation and/or
  other materials provided with the distribution. 
* Neither the name of NetApp, Inc. nor the names of its contributors may be used
  to endorse or promote products derived from this software without specific prior
  written permission. 

NO EXPRESS OR IMPLIED LICENSES TO ANY PARTY'S PATENT RIGHTS ARE GRANTED BY THIS LICENSE.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL
THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF
THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

[github]: https://github.com/dslik/CDMI-Explorer

[license-img]: http://img.shields.io/badge/license-BSD-a0a060.svg?style=flat-square
[github-img]: http://img.shields.io/badge/github-dslik/CDMI--Explorer-a0a060.svg?style=flat-square
