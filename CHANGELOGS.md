# Changelogs

Also seen in [GitHub Releases](https://github.com/juicity/juicity/releases)

## Query history releases

```bash
curl --silent "https://api.github.com/repos/juicity/juicity/releases" | jq -r '.[] | {tag_name,created_at,release}'
```

## Releases

<!-- BEGIN NEW TOC ENTRY -->
- [v0.1.2 (Latest)](#v012-latest)
- [v0.1.1](#v011)
- [v0.1.0](#v010)
<!-- BEGIN NEW CHANGELOGS -->

### v0.1.2 (Latest)

> Release date: 2023/08/05

### Features

- feat: support certificate pinning in [#61](https://github.com/juicity/juicity/pull/61) by (@mzz2017)
- feat(internal/relay): add support to inspect source for UDP traffic in [#57](https://github.com/juicity/juicity/pull/57) by (@yqlbu)
- feat(log): add exra cmd-flags for file logger in [#56](https://github.com/juicity/juicity/pull/56) by (@yqlbu)
- feat(sever): add support to inspect source for TCP traffic in [#53](https://github.com/juicity/juicity/pull/53) by (@yqlbu)

### Bug Fixes

- fix(server): support to dial domain in UDP (quic) in [#54](https://github.com/juicity/juicity/pull/54) by (@mzz2017)
- patch(server): fix golang lint warning in [#51](https://github.com/juicity/juicity/pull/51) by (@yqlbu)

### Others

- chore: upgrade softwind and quic(to 0.37.2) in [#67](https://github.com/juicity/juicity/pull/67) by (@mzz2017)
- docs(server): add UUID Generator section in [#64](https://github.com/juicity/juicity/pull/64) by (@yqlbu)
- ci: add linting workflow in [#52](https://github.com/juicity/juicity/pull/52) by (@yqlbu)

### 特性支持

- 特性: 支持证书固定 in [#61](https://github.com/juicity/juicity/pull/61) by (@mzz2017)
- 特性(内部/中继): 添加支持打印 UDP 来源 in [#57](https://github.com/juicity/juicity/pull/57) by (@yqlbu)
- 特性(日志): 为文件日志添加额外的命令标志 in [#56](https://github.com/juicity/juicity/pull/56) by (@yqlbu)
- 特性(服务器): 添加支持打印 TCP 来源 in [#53](https://github.com/juicity/juicity/pull/53) by (@yqlbu)

### 问题修复

- 修复(服务器): 支持在 UDP（quic）中拨号到域名 in [#54](https://github.com/juicity/juicity/pull/54) by (@mzz2017)
- 补丁(服务器): 修复 golang lint 报错 in [#51](https://github.com/juicity/juicity/pull/51) by (@yqlbu)

### 其他变更

- 杂项: 升级 softwind 和 quic (到 0.37.2) in [#67](https://github.com/juicity/juicity/pull/67) by (@mzz2017)
- 文档(服务器): 添加 UUID 生成器部分 in [#64](https://github.com/juicity/juicity/pull/64) by (@yqlbu)
- 自动化: 添加 linting 工作流程 in [#52](https://github.com/juicity/juicity/pull/52) by (@yqlbu)

**Full Changelog**: https://github.com/juicity/juicity/compare/v0.1.1...v0.1.2

### v0.1.1

> Release date: 2023/07/31

### Features

- feat(client): add protect_path support for android vpn in [#44](https://github.com/juicity/juicity/pull/44) by (@arm64v8a)
- optimize: upgrade quic-go to v0.37.0 to support GSO in [#40](https://github.com/juicity/juicity/pull/40) by (@mzz2017)
- feat/refactor(pkg/log): add log writer stream in [#39](https://github.com/juicity/juicity/pull/39) by (@yqlbu)
- optimize: little more faster in [#36](https://github.com/juicity/juicity/pull/36) by (@mzz2017)
- feat(server): support fwmark in [#18](https://github.com/juicity/juicity/pull/18) by (mzz2017)
- feat: support send_through in [#17](https://github.com/juicity/juicity/pull/17) by (mzz2017)

### Bug Fixes

- fix: should support hex fwmark in [#20](https://github.com/juicity/juicity/pull/20) by (mzz2017)
- hotfix: fix server instantiation in [#19](https://github.com/juicity/juicity/pull/19) by (@yqlbu)

### Others

- feat/refactor: add constant pkg in [#31](https://github.com/juicity/juicity/pull/31) by (@yqlbu)
- ci/hotfix(build): fix secret inputs missing issue in [#33](https://github.com/juicity/juicity/pull/33) by (@yqlbu)
- docs: add authentication docs of http/socks5 listening in [#46](https://github.com/juicity/juicity/pull/46) by (@mzz2017)
- chore/fix: upgrade softwind to support to set udp buffer size in [#45](https://github.com/juicity/juicity/pull/45) by (@mzz2017)
- chore(pr_template): fix typos in [#43](https://github.com/juicity/juicity/pull/43) by (@yqlbu)
- ci: add generate-changelogs workflow in [#37](https://github.com/juicity/juicity/pull/37) by (@yqlbu)
- ci(build,daily-build): demise post-actions stage in [#35](https://github.com/juicity/juicity/pull/35) by (@yqlbu)
- ci(build,pr-build,daily-build): enable check_run stages in [#32](https://github.com/juicity/juicity/pull/32) by (@yqlbu)
- chore: add example-{client,server}.json in [#29](https://github.com/juicity/juicity/pull/29) by (@mzz2017)
- chore/optimize(log): change log format to datetime in [#26](https://github.com/juicity/juicity/pull/26) by (@mzz2017)
- docs: refine README in [#25](https://github.com/juicity/juicity/pull/25) by (@mzz2017)
- docs(readme): add daed client as a new juicity client in [#21](https://github.com/juicity/juicity/pull/21) by (@mzz2017)
- refactor/patch: rework logger instantiation in [#16](https://github.com/juicity/juicity/pull/16) by (@yqlbu)
- ci/feature: add release builds in [#15](https://github.com/juicity/juicity/pull/15) by (@yqlbu)

### 特性支持

- 特性(client): 为安卓 vpn 添加 protect_path 支持 in [#44](https://github.com/juicity/juicity/pull/44) by (@arm64v8a)
- 优化: 升级 quic-go 到 v0.37.0 以支持 GSO in [#40](https://github.com/juicity/juicity/pull/40) by (@mzz2017)
- 特性/重构(pkg/log): 添加日志写入流 in [#39](https://github.com/juicity/juicity/pull/39) by (@yqlbu)
- 优化: 小幅提升速度 in [#36](https://github.com/juicity/juicity/pull/36) by (@mzz2017)
- 特性(server): 支持 fwmark in [#18](https://github.com/juicity/juicity/pull/18) by (mzz2017)
- 特性: 支持 send_through in [#17](https://github.com/juicity/juicity/pull/17) by (mzz2017)

### 问题修复

- 修复: 应当支持十六进制 fwmark in [#20](https://github.com/juicity/juicity/pull/20) by (mzz2017)
- 紧急修复: 修复服务器实例化问题 in [#19](https://github.com/juicity/juicity/pull/19) by (@yqlbu)

### 其他变更

- 特性/重构: 添加常量包 in [#31](https://github.com/juicity/juicity/pull/31) by (@yqlbu)
- 自动化/修复(build): 修复 secret 输入丢失问题 in [#33](https://github.com/juicity/juicity/pull/33) by (@yqlbu)
- 文档: 添加 http/socks5 监听的身份验证文档 in [#46](https://github.com/juicity/juicity/pull/46) by (@mzz2017)
- 杂项/修复: 升级 softwind 以支持设置 UDP 缓冲区大小 in [#45](https://github.com/juicity/juicity/pull/45) by (@mzz2017)
- 杂项(pr_template): 修复拼写错误 in [#43](https://github.com/juicity/juicity/pull/43) by (@yqlbu)
- 自动化: 添加 generate-changelogs 工作流程 in [#37](https://github.com/juicity/juicity/pull/37) by (@yqlbu)
- 自动化(build,daily-build): 移除 post-actions 阶段 in [#35](https://github.com/juicity/juicity/pull/35) by (@yqlbu)
- 自动化(build,pr-build,daily-build): 启用 check_run 阶段 in [#32](https://github.com/juicity/juicity/pull/32) by (@yqlbu)
- 杂项: 添加 example-{client,server}.json in [#29](https://github.com/juicity/juicity/pull/29) by (@mzz2017)
- 杂项/优化(log): 更改日志格式为日期时间 in [#26](https://github.com/juicity/juicity/pull/26) by (@mzz2017)
- 文档: 优化 README in [#25](https://github.com/juicity/juicity/pull/25) by (@mzz2017)
- 文档(readme): 将 daed client 添加为新的 juicity client in [#21](https://github.com/juicity/juicity/pull/21) by (@mzz2017)
- 重构/补丁: 重新设计日志记录实例化 in [#16](https://github.com/juicity/juicity/pull/16) by (@yqlbu)
- 自动化/特性: 添加发布构建 in [#15](https://github.com/juicity/juicity/pull/15) by (@yqlbu)

**Full Changelog**: https://github.com/juicity/juicity/compare/v0.1.0...v0.1.1

### New Contributors

- @arm64v8a made their first contribution in #44

### v0.1.0

> Release date: 2023/07/30

### Notes

> **Note**: initial release

Juicity is a quic-based proxy protocol. It has strong performance and is of great help to improve the network quality of the proxy. We have mature experience in proxy protocol, which can ensure that you avoid procedural and design problems as much as possible when using them. Have fun!

Juicity 是一个基于 quic 的代理协议，它有着强劲的性能，对网络质量较差的代理环境有较大的改善。我们在代理协议上具有成熟的经验，能保证您在使用时尽可能避免程序性和设计性的问题。最后，玩得开心！
