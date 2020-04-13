## 项目迁移

1. 这个repo由于名字太长，编译uclibs会出现[No such file or directory这个错误](https://github.com/coolsnowwolf/lede/issues/4192#issuecomment-609736953)
2. 现已转到[NanoR1s](https://github.com/i6o6i/NanoR1s)

<p align=center>
  <br>
  <span>NanoPi R1S-H5 OpenWrt Autobuild</span>
  <br>
  <span>Customize your own OpenWrt firmware for FriendlyArm NanoPi R1S-H5 using Github Actions.</span>
  <br>
  <br>
  <a target="_blank" href="LICENSE" title="License: MIT"><img src="https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE"></a>
  <a target="_blank" href="https://github.com/tjuyy/NanoPi-R1S-H5-Openwrt-Autobuild/stargazers" title="Stars"><img src="https://img.shields.io/github/stars/tjuyy/NanoPi-R1S-H5-Openwrt-Autobuild.svg?style=flat-square&label=Stars"></a>
  <a target="_blank" href="https://github.com/tjuyy/NanoPi-R1S-H5-Openwrt-Autobuild/fork" title="Forks"><img src="https://img.shields.io/github/forks/tjuyy/NanoPi-R1S-H5-Openwrt-Autobuild.svg?style=flat-square&label=Forks"></a>
</p>

<p align="center">
  <a href="#usage">Usage</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#acknowledgments">Acknowledgments</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>
</p>




## Usage

1. Fork [this repository](https://github.com/tjuyy/NanoPi-R1S-H5-Openwrt-Autobuild)
2. Modified R1S-H5.diffconfig to add some package if necessary 
3. Click the `Star` button of your own forked repository or `Create a new release` in your forked repository 
4. Github Actions workflow will be triggered and run automaticlly
5. Wait completion of the workflow and download files from `Aritifact`

## Info

- gateway: 192.168.2.1
- wifi password: password
- wan.ifname='eth0'
- lan.ifname='eth1'

## Acknowledgments

- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [P3TERX/debugger-action](https://github.com/P3TERX/debugger-action)
- [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)

## License

MIT © [tjuyy](https://github.com/tjuyy)
