# Download
[Wikipedia](https://en.wikipedia.org/wiki/Download)

## Parallel downloading
- Web browsers
  - Chromium: [Enable Chrome (Edge) Multi-threaded Downloading - Power's Wiki](https://wiki-power.com/en/%E5%BC%80%E5%90%AFChrome%EF%BC%88Edge%EF%BC%89%E5%A4%9A%E7%BA%BF%E7%A8%8B%E4%B8%8B%E8%BD%BD/)
    - `edge://flags/#enable-parallel-downloading`
    - 为什么不默认开启？
    - 2021-05 [TIP: You can enable Chrome Flag: `chrome://flags/#enable-parallel-downloading` to enable parallel downloading for accelerated download speed : r/chrome](https://www.reddit.com/r/chrome/comments/n88mda/tip_you_can_enable_chrome_flag/)
  - [ipull: Super Fast 🔥 File Downloader 🚀 (parallels connections)](https://github.com/ido-pluto/ipull)
  - [multithreaded-downloader-js: A browser based multithreaded downloader implemented in Javascript](https://github.com/backblaze-b2-samples/multithreaded-downloader-js)
  - [Implement Concurrent Download of Large Files in JavaScript](https://gist.github.com/semlinker/8453bbad093caaf321b153285b350d84)

  2020-10 [Downloading in parallel / HTML, CSS, PHP, JavaScript, etc. / Textpattern CMS support forum](https://forum.textpattern.com/viewtopic.php?id=51097)

  [multithreading - How to multithread a download in client-side javascript - Stack Overflow](https://stackoverflow.com/questions/49907569/how-to-multithread-a-download-in-client-side-javascript)

## Libraries
Rust:
- [downloader: Simple HTTP/HTTPS file downloader crate.](https://github.com/hunger/downloader)
  - Largest recent downloads (86,355)

- [cargo-binstall/binstalk-downloader](https://github.com/cargo-bins/cargo-binstall/tree/main/crates/binstalk-downloader)

- [manic: Rust download library](https://github.com/x0f5c3/manic) (inactive)
  - Progress reporting

- [rhtdl: reliable http downloads that do the right thing by default - Codeberg.org](https://codeberg.org/binarycat/rhtdl)
  - Automatically resume downloads using the `Range` header in the case of an error
  - Stalled download timeouts
  - Detection of mid-air collisions
  - Logging
  - Progress reporting
  - Not on crates.io

  [Rhtdl: Reliable HTTP download - code review - The Rust Programming Language Forum](https://users.rust-lang.org/t/rhtdl-reliable-http-download/120503)

- [http-downloader: 用 Rust 写的支持多线程与断点续传的 HTTP 下载库](https://github.com/ycysdf/http-downloader)
  - 下载速度追踪
  - 下载速度限制

- [ml-downloader: Simple blocking downloader based on reqwest](https://github.com/malaire/ml-downloader)

- [bic-potato/download\_rs: 一个简单的文件下载库](https://github.com/bic-potato/download_rs)

- [siwi-download: file downloader](https://github.com/rs-videos/siwi-download)

- [rust-cached-path: 🦀 Rust utility for accessing both local and remote files through a unified interface](https://github.com/epwalsh/rust-cached-path)
  - Sync
- [data\_downloader: A simple way to download files in Rust](https://github.com/tillarnold/data_downloader)
  - Sync

[What is the fastest libary for downloading files (all sizes) from web? : r/rust](https://www.reddit.com/r/rust/comments/14a5fml/what_is_the_fastest_libary_for_downloading_files/)

## Download managers
- [aria2](https://aria2.github.io/) ([GitHub](https://github.com/aria2/aria2))

  aria2 is a lightweight multi-protocol & multi-source command-line download utility. It supports HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink. aria2 can be manipulated via built-in JSON-RPC and XML-RPC interfaces.

Rust:
- [rlget: RLget: Rust Parallel Download client](https://github.com/shockron22/rlget)

### [aria2](https://aria2.github.io/)
[GitHub](https://github.com/aria2/aria2)

[Aria2 Manual](https://aria2.github.io/manual/en/html/index.html)

[Aria2 新手入门教程 - P3TERX ZONE](https://p3terx.com/archives/aria2-started-guide.html)

Deployment:
- [Aria2 Pro Docker](https://github.com/P3TERX/Aria2-Pro-Docker)
- [Aria2 一键安装管理脚本 增强版](https://github.com/P3TERX/aria2.sh) (discontinued)
- [Aria2 完美配置](https://github.com/P3TERX/aria2.conf)

GUI:
- [AriaNg: a modern web frontend making aria2 easier to use](https://github.com/mayswind/AriaNg)
- [WebUI-Aria2: The aim for this project is to create the worlds best and hottest interface to interact with aria2. Very simple to use, just download and open index.html in any web browser.](https://github.com/ziahamza/webui-aria2)

Troubleshooting:
- [Aria2 相关项目常见问题及解决方案（FAQ） - P3TERX ZONE](https://p3terx.com/archives/aria2_perfect_config-faq.html)
- [Aria2 无法下载磁力链接、BT种子和速度慢的解决方案 - P3TERX ZONE](https://p3terx.com/archives/solved-aria2-cant-download-magnetic-link-bt-seed-and-slow-speed.html)
  - [Aria2 是一个不合格的 BT 下载客户端，添加的 tracker 永远只会使用第一个 - V2EX](https://www.v2ex.com/t/795517)
