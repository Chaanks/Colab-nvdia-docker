Docker image of Colaboratory local runtime
========================================

Install and RUN
==============

```
build docker image


$ docker run --runtime=nvidia -it --rm -p 8081:8081 --cap-add SYS_ADMIN --device /dev/fuse \
             --security-opt apparmor=unconfined image-name
```

LICENSE
=======

This repository is forked from
https://github.com/googlecolab/backend-container/blob/bcbbf44/containers/Dockerfile

The original license is as follows.

```
Copyright 2017 Google Inc. All rights reserved.

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
