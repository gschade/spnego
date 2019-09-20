SPNEGO
======

## Overview

This project is forked from [spnego.sourceforge.net](http://spnego.sourceforge.net/ "spnego.sourceforge.net").

### Infos

This version fixes a bug occurring on systems running with Windows encoding (mainly Windows-1252) that are trying to decode
a BASIC-Authentication token build on systems running with different (e.g. UTF-8) encoding. 

This version of the filter uses a rather pragmatic solution for this problem: it uses a fixed UTF-8 encoding to break up the BASCIC-Token.

