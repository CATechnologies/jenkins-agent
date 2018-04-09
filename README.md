# jenkins-agent

This an image that can be used as an agent within a Jenkins pipeline build. The image uses an Ubuntu Xenial image as its base and creates a user `jenkins` that has the ability to perform sudo operations within the image.

## Legal Stuff
This image is based upon the [evarga/jenkins-slave](https://github.com/evarga/docker-images/tree/da691f8f8481a11ad019c47772732acad88759b1) which is licensed under the MIT license.

Below are the additions to the above docker image:

- Uses Ubuntu Xenial (16.04) instead of Ubuntu Trusty (14.04) as the base
- The `jenkins` user is no longer has to pipe `jenkins` as the password to use sudo within the image.

### License (evarga/docker-images)

```
The MIT License (MIT)

Copyright (c) 2016 miyo@eficode.com
Copyright (c) 2014 Ervin Varga

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
