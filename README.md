我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

<p align="center">
  <img src="https://raw.githubusercontent.com/tiagorlampert/CHAOS/master/content/logo.png">
</p>

<h1 align="center">CHAOS Payload Generator</h1>
<p align="center">
  <a href="https://golang.org/">
    <img src="https://img.shields.io/badge/Golang-1.10-blue.svg">
  </a>
  <a href="https://github.com/tiagorlampert/CHAOS/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-BSD%203-lightgrey.svg">
  </a>
  <a href="https://github.com/tiagorlampert/CHAOS/blob/master/CHAOS.go">
    <img src="https://img.shields.io/badge/Release-2.5.0-red.svg">
  </a>
    <a href="https://opensource.org">
    <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen.svg">
  </a>
</p>

<p align="center">
  CHAOS allow generate payloads and control remote Windows systems.
</p>

## Disclaimer
<p align="center">
  :books: This project was created only for learning purpose.
</p>

THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. YOU MAY USE THIS SOFTWARE AT YOUR OWN RISK. THE USE IS COMPLETE RESPONSIBILITY OF THE END-USER. THE DEVELOPERS ASSUME NO LIABILITY AND ARE NOT RESPONSIBLE FOR ANY MISUSE OR DAMAGE CAUSED BY THIS PROGRAM.

## Features
- [x] Reverse Shell
- [x] Download File
- [x] Upload File
- [x] Screenshot :new:
- [x] Keylogger :new:
- [x] Persistence
- [x] Open URL Remotely
- [x] Get Operating System Name
- [x] Run Fork Bomb

## Tested On
[![Kali)](https://www.google.com/s2/favicons?domain=https://www.kali.org/)](https://www.kali.org) **Kali Linux - ROLLING EDITION**

## How To Use
```bash
# Install dependencies (You need Golang and UPX package installed)
$ apt install golang xterm git upx-ucl -y

# Clone this repository
$ git clone https://github.com/tiagorlampert/CHAOS.git

# Get and install external imports (requirement to screenshot)
$ go get github.com/kbinani/screenshot && go get github.com/lxn/win
$ go install github.com/kbinani/screenshot && go install github.com/lxn/win

# Maybe you will see the message "package github.com/lxn/win: build constraints exclude all Go files".
# It's occurs because the libraries are to windows systems, but it necessary to build the payload.

# Go into the repository
$ cd CHAOS

# Run
$ go run CHAOS.go
```

## Screenshot (outdated)
<p align="center">
<img src="https://github.com/tiagorlampert/CHAOS/blob/master/content/screenshot.gif">
</p>

## Video
<p align="center">
<a href="https://www.youtube.com/watch?v=9P-3qSA_ZjQ">
  <img src="https://img.youtube.com/vi/9P-3qSA_ZjQ/maxresdefault.jpg" width="700"/>
</a></p>

## FAQ
> #### Why does Keylogger capture all uppercase letters?
> All the letters obtained using the keylogger are uppercase letters. It is a known issue, in case anyone knows how to fix the Keylogger function using golang, please contact me or open an issue.

> #### Why are necessary get and install external libraries?
> To implement the screenshot function i used a third-party library, you can check it in https://github.com/kbinani/screenshot and https://github.com/lxn/win. You must download and install it to generate the payload.

## Contact
:email: **tiagorlampert@gmail.com**

## License

>The [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
>
>Copyright (c) 2017, Tiago Rodrigo Lampert
>
>All rights reserved.
>
>Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
>
>* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.
>
>* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.
>
>* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
this software without specific prior written permission.
>
>THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
