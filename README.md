# homebrew-tap

统一的 Homebrew Tap 仓库，用于分发 `hooziwang` 旗下多个命令行工具。

## 已收录 Formula

- `syl-listing`
- `syl-md2ppt`
- `muna-image-google`
- `muna-video-google`
- `clawpipeline`

## 安装

```bash
brew tap hooziwang/tap
brew install syl-listing
brew install syl-md2ppt
brew install muna-image-google
brew install muna-video-google
brew install clawpipeline
```

## 维护说明

- Formula 由各项目仓库的 Release 工作流（GoReleaser）自动更新。
- 常规不手动改版本号与 `sha256`，以源项目发版结果为准。
