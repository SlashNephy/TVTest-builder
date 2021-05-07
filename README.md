# TVTest-builder

TVTest 関連のプロジェクトを GitHub Actions でビルドします。(Release|x64 構成)

以下のプロジェクトが対象です。

| リポジトリ | 説明 | ワークフロー | 成果物 | 
|---|---|---|---|
| [DBCTRADO/TVTest](https://github.com/DBCTRADO/TVTest) | TVTest 本体 | [![TVTest](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTest.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTest.yml) | `TVTest.exe`, `TVTest_Image.dll`, サンプルプラグイン |
| [DBCTRADO/TVTestVideoDecoder](https://github.com/DBCTRADO/TVTestVideoDecoder) | TVTest 付属の MPEG-TS デコーダ | [![TVTestVideoDecoder](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTestVideoDecoder.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTestVideoDecoder.yml) | `TVTestVideoDecoder.ax` |
| [xtne6f/NicoJK](https://github.com/xtne6f/NicoJK) | 実況プラグイン | [![NicoJK](https://github.com/SlashNephy/TVTest-builder/actions/workflows/NicoJK.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/NicoJK.yml) | `NicoJK.tvtp` |
| [xtne6f/TVCaptionMod2](https://github.com/xtne6f/TVCaptionMod2) | 字幕表示プラグイン | [![TVCaptionMod2](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaptionMod2.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaptionMod2.yml) | `TVCaptionMod2.tvtp` |
| [xtne6f/TvtPlay](https://github.com/xtne6f/TvtPlay) | ファイル再生プラグイン | [![TvtPlay](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvtPlay.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvtPlay.yml) | `TvtPlay.tvtp`, `BonDriver_Pipe.dll`, ~~`TvtAudioStretchFilter.ax`~~ |
| [noriokun4649/TVTComment](https://github.com/noriokun4649/TVTComment) | 実況プラグイン | [![TVTComment](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTComment.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTComment.yml) | `TvtComment.tvtp`, `TvtComment.exe` |
| [xqq/BonDriver_EPGStation](https://github.com/xqq/BonDriver_EPGStation) | EPGStation 向け BonDriver | [![BonDriver_EPGStation](https://github.com/SlashNephy/TVTest-builder/actions/workflows/BonDriver_EPGStation.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/BonDriver_EPGStation.yml) | `BonDriver_EPGStation.dll` |
| [noriokun4649/TvTestRPC](https://github.com/noriokun4649/TvTestRPC) | Discord RPC プラグイン | [![TvTestRPC](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvTestRPC.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvTestRPC.yml) | `TvTestRPC.tvtp` |
| [logue/CasProcessor](https://github.com/logue/CasProcessor) | CAS 処理 プラグイン<br>BonDriver_EPGStation を使用する際は不要 | [![CasProcessor](https://github.com/SlashNephy/TVTest-builder/actions/workflows/CasProcessor.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/CasProcessor.yml) | `CasProcessor.tvtp` |
