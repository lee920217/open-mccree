# MCCREE
[![license](https://img.shields.io/github/license/xiongmaotv/open-mccree.svg)](https://github.com/xiongmaotv/open-mccree)

A front end solution for mutlimedia loading, mux, demux, stream and play.

- [About](#about)
- [Structure](#structure)
- [Getting Started](#getting-started)
- [Modules and Status](#modules-and-status)
- [Contributors](#license)
- [License](#license)

## About

Mccree is a front end multimedia framework, which is able to loading, mux, demux and play. It is written in ECMAScript 6, use Lerna for package management. The ability of mccree is highly depends on its packages. Currently, it support the following features:
- Load source through the web fetch API.
- Load source through the Mozilla XMLHttpRequest API.
- Load source through the Tencent p2p SDK.
- Demux Flv format video.
- Remux H264 and AAC to Mp4 format.
- Playback through the web MediaSource Extension.
  
The following features will be supported soon:

- Load hls source through the web XMLHttpRequest API.
- Load source from local flv file.
- Demux m3u8 and ts file (hls).
- Audio Context (Gain) feature.


## Structure

<img alt="Mccree" src="https://i.ssl.pdim.gs/b819064a86027ec2487d74d8a0702807.png" width="1000">


## Getting Started
TBA (After panda-mccree-live module released)

## Modules and Status
|name|dev|test|doc|comments|developer|org|version|
|---|---|---|---|---|---|---|---|
|mccree-core|100%|100%|√|√|Yuqing Jiang|PandaTv|realesed|
|mccree-core-track|100%|100%|√|√|Yuqing Jiang|PandaTv|realesed|
|mccree-core-loaderbuffer|100%|100%|√|√|Yuqing Jiang|PandaTv|[![npm](https://img.shields.io/npm/v/mccree-core-loaderbuffer.svg)](https://www.npmjs.com/package/mccree-core-loaderbuffer)|
|mccree-helper-utils|100%|100%|√|√|Yuqing Jiang|PandaTv|[![npm (tag)](https://img.shields.io/npm/v/mccree-helper-utils.svg)](https://img.shields.io/npm/v/mccree-helper-utils)|
|mccree-helper-logger|100%|100%|√|√|Yuqing Jiang|PandaTv|[![npm](https://img.shields.io/npm/v/mccree-helper-logger.svg)](https://www.npmjs.com/package/mccree-helper-logger)|
|mccree-helper-browser|100%||||Yuqing Jiang|PandaTv|---|
|mccree-controller-loader|100%||||Yuqing Jiang|PandaTv|---|
|mccree-loader-fetch|100%||||Yuqing Jiang|PandaTv|---|
|mccree-loader-moz-xhr|100%||||Yuqing Jiang|PandaTv|---|
|mccree-loader-tencentp2p|100%||||Tencent Team|Tencent|availible soon|
|mccree-loader-hls|70%||||Jiaqi Li|PandaTv|---|
|mccree-demuxer-flv|100%||||Yuqing Jiang|PandaTv|---|
|mccree-demuxer-ts|30%||||Jiaqi Li|PandaTv|---|
|mccree-remuxer-mp4live|100%||||Yuqing Jiang|PandaTv|---|
|panda-mccree-live|100%||||Yuqing Jiang|PandaTv|---|


## Contributors

#### core team
- PandaTv team

|name|github|email|blog|
|---|---|---|---|
|Yuqing Jiang|[yqjiang](https://github.com/yqjiang)|jiangyuqing@panda.tv||
|Jiaqi Li|[lee920217](https://github.com/lee920217)|lijiaqi@panda.tv||

#### Other contributors
TBA 

## Join us
Read ./docs/en/developer.md

## License
    Copyright [2017] [Shanghai Panda Interactive Entertainment And Culture Company Limited]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
