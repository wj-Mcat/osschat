# Osschat

[![Powered by Wechaty](https://img.shields.io/badge/Powered%20By-Wechaty-brightgreen.svg)](https://github.com/wechaty/wechaty)
[![Build Status](https://travis-ci.com/kaiyuanshe/OSS-bot.svg?branch=master)](https://travis-ci.com/kaiyuanshe/OSS-bot)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## What is Osschat

OSS-bot is for bridging IM apps (e.g., WeChat) and Apache community tools (e.g., mailing list, and jira).

OSS-bot will serve users as a cloud service.

- YouTube Video: [Introducing OSS Bot: Sync GitHub Issues with WeChat Groups for Open-source Projects](https://youtu.be/HNksCmm_pvY), talk from [@huan](https://github.com/huan) from [OSS Bot Meeting](https://shimo.im/docs/wGHydDxvWGjWKgDK) 2020-03-05 (Thu) 20:30 - 21:00 CST

## Using Osschat as a service

TBD

## Preliminary

To compile OSS-bot, typescript environment is needed. If you have `npm`, you can run:

```shell
npm install
```

## Run

```shell
./node_modules/.bin/ts-node bin/main.ts
```

- Localhost

You can get the following result, open <http://localhost:8788>, scan qrcode and begin to use the bot!

```shell
16:57:45 INFO Wechaty <wechaty-puppet-puppeteer>(heroku-wechaty) start() v0.29.7 is starting...
16:57:47 INFO startWeb startWeb() listening to http://localhost:8788
```

After scan the qrcode, you can find the following result here

```shell
17:12:57 INFO chatops chatops(Der! I just got online!
OSS Bot v0.0.24)
17:12:57 INFO startBot onLogin(Contact<李佳芮>) 李佳芮 Heroku Wechaty Getting Started v0.29.7 logined
```

- Advance

1. Using docker to get a more stable version
2. Using an advance puppet to get a more stable version

## Staging

We are current DevOps the master branch from the repo to Heroku under the protection of Travis CI.

You can visit the staging system at <http://oss-bot.kaiyuanshe.cn/>

## Meeting Notes

- [Weekly Meeting Notes](https://shimo.im/docs/wGHydDxvWGjWKgDK)

## Apache Incubator Proposal

- [Incubator OSS Bot Proposal](https://cwiki.apache.org/confluence/display/INCUBATOR/OSSBotProposal)

## Mentors

- [Craig L. Russell](https://github.com/clr-apache), Chairman, Apache Software Fundation
- [Junping Du](https://github.com/JunpingDu), Chairman, Tencent Open Source Alliance
- [Ted Liu](https://github.com/tedliu1), Chairman, kaiyuanshe
- To Be Added ...

## Committers

- [Zhuang Biaowei](https://github.com/zhuangbiaowei), [(庄表伟)](http://www.zhuangbiaowei.com/blog/), Product Manager from Huawei technologies co. ltd
- [Huan](https://github.com/huan) [(李卓桓)](http://linkedin.com/in/zixia) [Wechaty](https://github.com/wechaty/wechaty) Author, <zixia@zixia.net>
- [Rui](https://github.com/lijiarui),[(李佳芮)](https://lijiarui.github.io) [Wechaty](https://github.com/wechaty/wechaty) Co-author, Founder of [JuziBot](https://www.botorange.com/)
- To Be Added ...

## Pilots

To be added...

## Thanks

- OSS mentored by: Apache Software Fundation
- Project Lead by: 开源社
- Heroku Dyno sponsored by: [JuziBot](https://www.juzi.bot)
- Wechaty Puppet Padplus sponsored by: [JuziBot](https://www.juzi.bot)
- Heroku Getting Started Template from [Wechaty](https://github.com/wechaty/)
