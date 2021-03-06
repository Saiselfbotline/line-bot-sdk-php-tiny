line-bot-sdk-php-tiny
==
[![License](https://img.shields.io/badge/license-Apache--2.0-FF3333.svg)](LICENSE) [![Line](https://img.shields.io/badge/lineapi-v2-00DD77.svg)](https://developers.line.me) ![Version](https://img.shields.io/badge/version-2.1-00BBFF.svg) ![PHP](https://img.shields.io/badge/php-5.x-B94FFF.svg) 

[![LINE](http://lineofficial.blogimg.jp/tw/imgs/2/2/22f62401.png)](https://line.me)

A simple SDK  for the LINE Messaging API for PHP.

Description
--

The origin version is [line-bot-sdk-tiny](https://github.com/line/line-bot-sdk-php/tree/master/line-bot-sdk-tiny) by LINE Corp.

The version of LINE Messaging API by [SuperSonic](https://github.com/supersonictw) as Third Party Update to support more LINE features.

The API has only a "api.php" file to include into your LINEBOT.

I think that it don`t need full API if someone wants to make a "Simple" BOT.

By the way, as a file, you can carry your BOT to anywhere you want.

If you want official PHP LINEAPI, see [line-bot-sdk-php](https://github.com/line/line-bot-sdk-php) to get full version.

Notice
--
The API uses "file_get_contents()" as HttpClient.

So it maybe will be crashed by SELinux.

Please turn off it, or using full version API.

Example
--

See [document](https://supersonictw.github.io/line-bot-sdk-php-tiny/) or [example](./example/).

When running examples, make sure that you have set your Channel access token and Channel secret.

Requirements
--

    PHP >= 5.4

License
--

```
Copyright 2016 LINE Corporation

LINE Corporation licenses this file to you under the Apache License,
version 2.0 (the "License"); you may not use this file except in compliance
with the License. You may obtain a copy of the License at:

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.
```
