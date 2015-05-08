# Distributed API Management using [Kong](http://getkong.org)

[getkong.org](http://getkong.org)

Trent Oswald - Full Stack Engineer at Mashape - [@therebelrobot](http://twitter.com/therebelrobot)

*For Enterprise-specific questions, please contact us at [getkong.org/enterprise](http://getkong.org/enterprise/)*

## Distributed APIs is hard

There are many things needed when managing distributed APIs, and can lead to a lot of code duplication:

- Rate Limiting
- Authentication
- Logging
- Monitoring
- Transformations
- CORS

## Kong is designed to make it easier

- **Admin CLI**: Control your Kong cluster from the command line just like Neo in The Matrix.
- **Admin REST API**: Kong can be operated with its RESTful API for maximum flexibility.
- **Scalable**: Distributed by nature, Kong scales horizontally simply by adding nodes.
- **
- **Built for Performance**: Kong handles load with ease by scaling and using NGINX at the core.
- **Open Source**: Kong is built on nginx and Lua, and the source code is available under the MIT license.
- **Runs on most systems**: Kong binaries are available for most server architectures, including Docker, CentOS, Debian, Ubuntu, even Mac OS X
- **Extendable Plugin Architecture**: Need custom functionality? Extend Kong with your own Lua plugins!

### Kong Core Features

- **Single-Point Proxy**: One location to route all of your API microservices, internal, external, or third-party
- **Logging**: Log requests and responses to your system over TCP, UDP or to disk.
- **Monitoring**: Live monitoring provides key load and performance server metrics.
- **Authentication**: Manage consumer credentials query string and header tokens.
- **Rate-limiting**: Block and throttle requests based on IP or authentication.
- **Transformations**: Add, remove or manipulate HTTP params and headers on-the-fly.
- **CORS**: Enable cross-origin requests to your APIs that would otherwise be blocked.

## Install

Kong binaries are available for most server architectures, including Docker, CentOS, Debian, Ubuntu, Mac OS X, and any others through the Luarocks module management system. You can install and run Kong on any system that supports nginx, Apache Cassandra, and Lua, and that has more than 512M RAM. To install, find the appropriate section for your platform on http://getkong.org/download/ and follow the instructions there. You can run Kong any time by using `sudo kong start`. To stop or reload Kong, use `sudo kong stop` or `sudo kong reload` respectively.

Once installed, you can take a look at http://getkong.org/docs/0.2.0-2/admin-api/ for more information about the Admin API to manage your new Kong service.
