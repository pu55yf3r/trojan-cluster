# trojan

[![Build Status](https://dev.azure.com/kunagisamari/trojan-redis/_apis/build/status/DenrianWeiss.trojan-cluster?branchName=master)](https://dev.azure.com/kunagisamari/trojan-redis/_build/latest?definitionId=1&branchName=master)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDenrianWeiss%2Ftrojan-cluster.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FDenrianWeiss%2Ftrojan-cluster?ref=badge_shield)

An unidentifiable mechanism that helps you bypass GFW.

Trojan features multiple protocols over `TLS` to avoid both active/passive detections and ISP `QoS` limitations.

Trojan is not a fixed program or protocol. It's an idea, an idea that imitating the most common service, to an extent that it behaves identically, could help you get across the Great FireWall permanently, without being identified ever. We are the GreatER Fire; we ship Trojan Horses.  

This is a forked version of trojan, which is optimized for running as a server.

## Documentations

An online documentation can be found [here](https://trojan-gfw.github.io/trojan/).  
Installation guide on various platforms can be found in the [wiki](https://github.com/trojan-gfw/trojan/wiki/Binary-&-Package-Distributions).  
If you want to use it with sspanel or something alike, see [llc's ssmgr for trojan](https://github.com/llc1123/ssmgr-trojan-client)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Dependencies

- [CMake](https://cmake.org/) >= 3.7.2
- [Boost](http://www.boost.org/) >= 1.66.0
- [OpenSSL](https://www.openssl.org/) >= 1.1.0
- [libmysqlclient](https://dev.mysql.com/downloads/connector/c/)
- [hiredis](https://github.com/redis/hiredis)

## License

[GPLv3](LICENSE)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDenrianWeiss%2Ftrojan-cluster.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDenrianWeiss%2Ftrojan-cluster?ref=badge_large)