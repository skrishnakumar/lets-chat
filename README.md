![Let's Chat](http://i.imgur.com/0a3l5VF.png)

![Screenshot](http://i.imgur.com/C4uMD67.png)

A self-hosted chat app for small teams built by [Security Compass][seccom].

[![Build Status](https://travis-ci.org/sdelements/lets-chat.svg?branch=master)](https://travis-ci.org/sdelements/lets-chat)
[![Dependency Status](https://david-dm.org/sdelements/lets-chat.svg)](https://david-dm.org/sdelements/lets-chat)
[![devDependency Status](https://david-dm.org/sdelements/lets-chat/dev-status.svg)](https://david-dm.org/sdelements/lets-chat#info=devDependencies)

## Features and Stuff

* BYOS (bring your own server)
* Persistent messages
* Multiple rooms
* Private and password-protected rooms
* New message alerts / notifications
* Mentions (hey @you/@all)
* Image embeds / Giphy search
* Code pasting
* File uploads (Local / [Amazon S3][s3] / [Azure][azure])
* Transcripts / Chat History (with search)
* XMPP Multi-user chat (MUC)
* 1-to-1 chat between XMPP users
* Local / [Kerberos][kerberos] / [LDAP][ldap] authentication
* [Hubot Adapter][hubot]
* REST-like API
* Basic i18n support
* MIT Licensed


## Deployment on Cloud Foundry

Navigate inside the folder which has manifest file

cf api https://api.cf.sap.hana.ondemand.com/

cf login 

cf create-service mongodb v3.0-container mongodb

cf push 

## Note:  

please add a suffix or prefix (or change the entire name) to the host attribute within the manifest.yml file to avoid 'The host is taken' error. 

## License

Released under [the MIT license][license].


[wiki]: https://github.com/sdelements/lets-chat/wiki
[troubleshooting]: https://github.com/sdelements/lets-chat/blob/master/TROUBLESHOOTING.md
[mailing-list]: https://groups.google.com/forum/#!forum/lets-chat-app
[tracker]: https://github.com/sdelements/lets-chat/issues
[contributing]: https://github.com/sdelements/lets-chat/blob/master/CONTRIBUTING.md
[new-issue]: https://github.com/sdelements/lets-chat/issues/new
[editorconfig]: https://github.com/sdelements/lets-chat/blob/master/.editorconfig
[license]: https://github.com/sdelements/lets-chat/blob/master/LICENSE
[ldap]: https://github.com/sdelements/lets-chat-ldap
[kerberos]: https://github.com/sdelements/lets-chat-kerberos
[s3]: https://github.com/sdelements/lets-chat-s3
[seccom]: http://securitycompass.com/
[hubot]: https://github.com/sdelements/hubot-lets-chat
[azure]: https://github.com/maximilian-krauss/lets-chat-azure
[install-local]: https://github.com/sdelements/lets-chat/wiki/Installation
[install-docker]: https://registry.hub.docker.com/u/sdelements/lets-chat/
[install-heroku]: https://github.com/sdelements/lets-chat/wiki/Heroku
[install-vagrant]: https://github.com/sdelements/lets-chat/wiki/Vagrant
