# alpine-jq
Docker image for [jq](http://stedolan.github.io/jq/) based on [alpine linux](https://alpinelinux.org/) image.

This image also contains [curl](https://curl.haxx.se/) to make HTTP requests and [bash](https://www.gnu.org/software/bash/).

# Docker Image
You could either download the latest built image from docker hub or build one locally with the Dockerimage.

## 1.1 Download the latest Image

```
docker pull ganeshpl/alpine-jq
```

## 1.2 Build One Locally

```
docker build -t <TAG_NAME> .
```

# Usage
Start the container with this:

```
docker run -it alpine-jq /bin/bash
```

# License

```
Copyright 2017 ThoughtWorks, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
