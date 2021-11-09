<p align="center">
  <a href="https://jip.dev"><img src="https://i.imgur.com/Xh152w6.png"></a><br>
  <a href="https://jip.dev">jip.dev</a> · <a href="https://stackoverflow.com/users/101090/jorge-israel-pe%c3%b1a">stackoverflow</a> · <a href="https://www.linkedin.com/in/jorge-israel-p/">linkedin</a>
</p>

- I am a versatile, self-directed engineer of +16 years of experience[^1] (3 professional).

- I dive deep into unfamiliar projects to quickly make meaningful contributions.

- I have a proven record for designing, planning, leading, and developing complex projects from the ground up.

- I love the thrill of the chase of debugging. This has led me to diagnose and address subtle and elusive bugs in all manner of previously-unfamiliar, complex, and diverse projects (see examples below), and all have been tremendous learning opportunities.

- I consistently clear obstacles. If something is broken or lacking, I dive in to investigate, file a thorough ticket, and most of the time fix or implement the feature myself (see example [issue](https://github.com/aws/aws-cdk/issues/10921) and [PR](https://github.com/aws/aws-cdk/pull/10922)), and if what I need doesn't exist yet, [I will build it](https://github.com/blaenk/hoedown#readme).

- I constantly read and learn new things. See my extensive [notes](https://jip.dev/notes/) and my recent [reading list](https://jip.dev/reads/).

[^1]: I started programming at 13, which I don't count, but my first serious projects were at 15: leading a team of friends creating a standalone game on the industry professional [Quake 3 engine](https://en.wikipedia.org/wiki/Id_Tech_3) (C codebase. I also created NSIS installer scripts, Python infrastructure, websites, etc.). I also created an [iPod MP3 retriever app](https://jip.dev/work/mypod/), [Last.fm clone](https://jip.dev/work/musicaster/), screenshot app, and various WordPress and phpBB plugins. It was a productive year.

<details>
<summary align="center"><strong>🔽 Click here to expand some of my varied open source contributions 🔽</strong></summary>
<br>

See the full list [here](https://jip.dev/work/).

<!-- prettier-ignore -->
| Project | Language | Description |
| :------ | :------: | :---------- |
| [AWS CDK](https://github.com/aws/aws-cdk/pulls?q=author%3Ablaenk+is%3Apr)<br>Infrastructure as Code | TypeScript | I implemented native `.dockerignore` and `.gitignore` support to fix confusing and erratic behavior, and also added support for the AWS Lambda `WorkDir` option. [Learn more](https://jip.dev/work/cdk/). |
| [Minio](https://github.com/minio/minio/issues?q=author%3Ablaenk+is%3Amerged)<br>Kubernetes Native Object Storage | Go | I optimized listings of large HDFS directories with +1,500 files by 200x to aid a company merger. [Learn more](https://jip.dev/work/minio/). |
| [Rust](https://github.com/rust-lang/rust/pull/22351)<br>Systems Programming Language | Rust | I was an early Rust user since before 2014 and consistently helped to adapt Rust packages to breaking changes of syntax, semantics, and libraries. I [reported compiler errors](https://github.com/rust-lang/rust/issues?q=is%3Aissue+sort%3Aupdated-desc+author%3Ablaenk+is%3Aclosed) that I discovered by using bleeding-edge nightly features, and contributed a speedy fix in time for the 1.0 release. [Learn more](https://jip.dev/work/rust/). |
| [libtorrent](https://github.com/rakshasa/libtorrent/pull/40)/[rtorrent](https://github.com/rakshasa/rtorrent/pull/127)<br>BitTorrent Library/Client | C++ | I fixed elusive platform-specific bugs reported by Solaris users caused by non-portable signal handling due to non-POSIX compliant system calls. [Learn more](https://jip.dev/work/rtorrent/) and [more](https://jip.dev/work/libtorrent/). |
| [hoedown](https://github.com/hoedown/hoedown/pulls?q=author%3Ablaenk+is%3Apr)<br>Markdown C Library | C | Early on Rust lacked a fully-featured Markdown library and I needed one for the static site generator I was writing ([diecast](https://github.com/diecast/diecast)), so I wrote **idiomatic** [bindings to hoedown for Rust](https://github.com/blaenk/hoedown) which exposed previously unknown edge cases in the C library through different combinations of feature flags. [Learn more](https://jip.dev/work/hoedown/). |
| [WP-reCAPTCHA](https://jip.dev/work/wp-recaptcha/)<br>Official reCAPTCHA WordPress Plugin | PHP | Back in 2008 the lead engineer of the Carnegie Mellon University project [reCAPTCHA](https://en.wikipedia.org/wiki/Recaptcha) asked if I would be interested in creating the official WordPress plugin for reCAPTCHA and I accepted. After over half a million installs, I transferred ownership to Google after they acquired reCAPTCHA. [Learn more](https://jip.dev/work/wp-recaptcha/). |
| [Hakyll](https://github.com/jaspervdj/hakyll/pulls?q=author%3Ablaenk)<br>Static Site Generator | Haskell | I fixed a [reported bug](https://github.com/jaspervdj/hakyll/issues/250) that appeared without any changes to code nor to the Hakyll library, something especially rare in Haskell. [Learn more](https://jip.dev/work/hakyll/). |
| [Aura](https://github.com/fosskers/aura/pull/233)<br>AUR [Package Helper](https://wiki.archlinux.org/title/AUR_helpers) | Haskell | I implemented search-result count limiting. [Learn more](https://jip.dev/work/aura/). |
| [Syncplay](https://github.com/Syncplay/syncplay/issues?q=author%3Ablaenk)<br>Media Player Synchronizer | Python | I contributed features to the synchronization algorithm and made Syncplay packageable on Linux, then created ArchLinux [AUR packages](https://aur.archlinux.org/packages/?O=0&SeB=nd&K=syncplay&outdated=&SB=n&SO=a&PP=50&do_Search=Go) for them. [Learn more](https://jip.dev/work/syncplay/). |
| [Handlebars-Rust](https://github.com/sunng87/handlebars-rust/issues?q=author%3Ablaenk)<br>Template Engine | Rust | I kept it updated against the frequent breaking changes of pre-1.0 Rust. |
| [MPC-HC](https://github.com/mpc-hc/mpc-hc/pull/38)<br>Media Player | C++ | I fixed remote web UI seeking. |
| [notify](https://github.com/notify-rs/notify/issues?q=author%3Ablaenk)<br>File System Events | Rust | I kept it updated against the frequent breaking changes of pre-1.0 Rust, as well as fixed general bugs and made certain optimizations. |
| [git2](https://github.com/rust-lang/git2-rs/pulls?q=author%3Ablaenk)<br>Rust Bindings to [libgit2](https://libgit2.org/) | Rust | I increased C library binding coverage. |
| [inotify-rs](https://github.com/hannobraun/inotify-rs/pull/14)<br>Rust Bindings to Linux [`inotify`](https://en.wikipedia.org/wiki/Inotify) | Rust | I adapted it to pre-1.0 breaking changes by interpreting Linux documentation for the correct kind of error to yield. |

</details>
