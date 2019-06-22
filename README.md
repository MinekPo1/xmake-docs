---
search: en
---

<p>
<div align="center">
  <a href="https://xmake.io">
    <img width="200" heigth="200" src="https://tboox.org/static/img/xmake/logo256c.png">
  </a>  

  <h1>xmake</h1>

  <div>
    <a href="https://travis-ci.org/xmake-io/xmake">
      <img src="https://img.shields.io/travis/xmake-io/xmake/master.svg?style=flat-square" alt="travis-ci" />
    </a>
    <a href="https://ci.appveyor.com/project/waruqi/xmake/branch/master">
      <img src="https://img.shields.io/appveyor/ci/waruqi/xmake/master.svg?style=flat-square" alt="appveyor-ci" />
    </a>
    <a href="https://aur.archlinux.org/packages/xmake">
      <img src="https://img.shields.io/aur/votes/xmake.svg?style=flat-square" alt="AUR votes" />
    </a>
    <a href="https://github.com/xmake-io/xmake/releases">
      <img src="https://img.shields.io/github/release/xmake-io/xmake.svg?style=flat-square" alt="Github All Releases" />
    </a>
  </div>
  <div>
    <a href="https://github.com/xmake-io/xmake/blob/master/LICENSE.md">
      <img src="https://img.shields.io/github/license/xmake-io/xmake.svg?colorB=f48041&style=flat-square" alt="license" />
    </a>
    <a href="https://www.reddit.com/r/tboox/">
      <img src="https://img.shields.io/badge/chat-on%20reddit-ff3f34.svg?style=flat-square" alt="Reddit" />
    </a>
    <a href="https://gitter.im/tboox/tboox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge">
      <img src="https://img.shields.io/gitter/room/tboox/tboox.svg?style=flat-square&colorB=96c312" alt="Gitter" />
    </a>
    <a href="https://t.me/tbooxorg">
      <img src="https://img.shields.io/badge/chat-on%20telegram-blue.svg?style=flat-square" alt="Telegram" />
    </a>
    <a href="https://jq.qq.com/?_wv=1027&k=5hpwWFv">
      <img src="https://img.shields.io/badge/chat-on%20QQ-ff69b4.svg?style=flat-square" alt="QQ" />
    </a>
    <a href="https://xmake.io/pages/donation.html#donate">
      <img src="https://img.shields.io/badge/donate-us-orange.svg?style=flat-square" alt="Donate" />
    </a>
  </div>

  <p>A cross-platform build utility based on Lua</p>
</div>
</p>

## Introduction 

xmake is a cross-platform build utility based on lua. 

The project focuses on making development and building easier and provides many features (.e.g package, install, plugin, macro, action, option, task ...), 
so that any developer can quickly pick it up and enjoy the productivity boost when developing and building project.

## Installation

#### Master

##### via curl

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tboox/xmake/master/scripts/get.sh)
```

##### via wget

```bash
bash <(wget https://raw.githubusercontent.com/tboox/xmake/master/scripts/get.sh -O -)
```

##### via powershell

```bash
Invoke-Expression (Invoke-Webrequest 'https://raw.githubusercontent.com/tboox/xmake/master/scripts/get.ps1' -UseBasicParsing).Content
```

#### Windows

##### via installer

1. Download xmake windows installer from [Releases](https://github.com/xmake-io/xmake/releases)
2. Run xmake-[version].exe

##### via scoop

```bash
scoop install xmake
```

#### MacOS

```bash
$ brew install xmake
```

