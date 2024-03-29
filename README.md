# Buddy OnDemand - Code Server

[![GitHub Release](https://img.shields.io/github/v/release/UCO-HPC/buddy_code-server?style=flat-square)](https://github.com/UCO-HPC/buddy_code-server/blob/devel/CHANGELOG.md)
[![GitHub License](https://img.shields.io/github/license/UCO-HPC/buddy_code-server?style=flat-square)](https://opensource.org/licenses/MIT)

An app designed for UCO's OnDemand that launches Code Server

## Prerequisites

The following should be made available on the compute nodes
- [Code Server] 3.12.0+
- [Git] 2.0+
- [websockify] 0.6.0+

For module support:

- [Lmod] 8.1.0+

[Code Server]: https://github.com/cdr/code-server
[Git]: https://git-scm.com/
[websockify]: https://github.com/novnc/websockify
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## Installation

You can either use the "New App" feature in the Open OnDemand development tab, or clone this app directly to the /var/www/ood/apps/sys folder. 

## Contributing

Please note that this application is specific to our university. Please feel free to copy and use as needed according to the associated license. If you discover a bug during use, please feel free to create a new branch and submit a pull request. 

## License

* Code, documentation, and content are licensed under MIT (see LICENSE.txt) at this time. License is subject to change without notice. 
* VSCode and any and all Microsoft Inc. brand, product, service and feature names, logos and slogans are trademarks or registered trademarks of Microsoft Inc. or its subsidiaries located in the United States or other countries.
* Singularity, Sylabs, and any and all Sylabs, Inc. brand, product, service and feature names, logos and slogans are trademarks or registered trademarks of Sylabs, Inc. or its subsidiaries located in the United States or other countries.
* Code Server and it's source code are copyrighted by Coder. 
* OnDemand and it's source code are copyrighted by Ohio Supercomputer Center
