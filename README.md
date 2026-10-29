# VisoHub — Open Source Compliance / 开源合规材料

VisoHub (iOS, iPadOS, tvOS) uses open-source libraries, some under the GNU LGPL, linked statically. For every released
build this repository provides, as a release asset:

- the corresponding source code of each LGPL / MPL component at the exact version linked, with build scripts, patches
  and the configuration of the linked binaries;
- the app's object files, all static libraries and the exact link command (`relink.sh`), so the app can be relinked
  with a modified version of any LGPL library, plus the unsigned app bundle of the same build;
- every license text and the notices shown in the app (Settings › About › Open Source Licenses).

VisoHub（iOS、iPadOS、tvOS）以静态链接方式使用了包括 GNU LGPL 在内的开源库。每个发布版本在 Releases 中提供：各 LGPL /
MPL 组件在所链接版本的对应源码、构建脚本、补丁与编译配置；App 的目标文件、全部静态库和该版本的链接命令（`relink.sh`），
可用修改后的 LGPL 库重新链接 App；同一版本的未签名 App 包；全部许可证文本与 App 内显示的开源许可声明。

| Version | Release | Contents |
|---|---|---|
| 1.0.0 (5) | [`1.0.0-build5`](../../releases/tag/1.0.0-build5) | iOS / iPadOS (root) and tvOS (`tvos/`) |

Inside the archive, `README.md` explains how to relink, and `MANIFEST.txt` lists every file with its SHA-256.
压缩包内的 `README.md` 说明重新链接步骤，`MANIFEST.txt` 列出每个文件及其 SHA-256。

Questions / 联系：xcplay564@gmail.com
