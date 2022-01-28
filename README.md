## OpenDLV Microservice to interface with CAN

This repository provides source code to interface with data from a CAN bus
for the OpenDLV software ecosystem.


## Table of Contents
* [Dependencies](#dependencies)
* [Usage](#usage)
* [License](#license)


## Dependencies
No dependencies! You just need a C++14-compliant compiler to compile this
project as it ships the following dependencies as part of the source distribution:

* [libcluon](https://github.com/chrberger/libcluon) - [![License: GPLv3](https://img.shields.io/badge/license-GPL--3-blue.svg
)](https://www.gnu.org/licenses/gpl-3.0.txt)
* [Unit Test Framework Catch2](https://github.com/catchorg/Catch2/releases/tag/v2.1.2) - [![License: Boost Software License v1.0](https://img.shields.io/badge/License-Boost%20v1-blue.svg)](http://www.boost.org/LICENSE_1_0.txt)


## Usage
This microservice is created automatically on changes to this repository.

To run this microservice using our pre-built Docker image, simply start it as follows:

```
docker run --rm -ti --net=host --privileged chrberger/opendlv-device-can-raw:latest --cid=111 --can-channels=can0:0,can1:1
```


## License

* This project is released under the terms of the GNU GPLv3 License

