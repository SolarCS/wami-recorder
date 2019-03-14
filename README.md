# wami-recorder
Fork of https://code.google.com/archive/p/wami-recorder/ .
A JavaScript/Flash solution to recording audio from a browser.

The current version is an extension of the original one, to allow pause/resume recording.

## Setup
* Download Adobe's free Flex SDK.
* Build/compile using the command:
```
mxmlc -compiler.source-path=src -static-link-runtime-shared-libraries=true -output example/client/Wami.swf src/edu/mit/csail/wami/client/Wami.mxml
```
