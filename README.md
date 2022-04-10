# TVTest-builder

TVTest 関連のプロジェクトを GitHub Actions でビルドします。(Release|x64, 一部 Release|Win32, AVX, AVX2, AVX512 命令セットに対応)

## 対象リポジトリ

| リポジトリ | 説明 | Workflow |
|---|---|---|
| [DBCTRADO/TVTest](https://github.com/DBCTRADO/TVTest) | TVTest 本体 | [![TVTest](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTest.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTest.yml) |
| [DBCTRADO/TVTestVideoDecoder](https://github.com/DBCTRADO/TVTestVideoDecoder) | TVTest 付属の MPEG-TS デコーダ | [![TVTestVideoDecoder](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTestVideoDecoder.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTestVideoDecoder.yml) |
| [xtne6f/NicoJK](https://github.com/xtne6f/NicoJK) | 実況プラグイン | [![NicoJK](https://github.com/SlashNephy/TVTest-builder/actions/workflows/NicoJK.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/NicoJK.yml) |
| [xtne6f/TVCaptionMod2](https://github.com/xtne6f/TVCaptionMod2) | 字幕表示プラグイン | [![TVCaptionMod2](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaptionMod2.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaptionMod2.yml) |
| [xtne6f/TvtPlay](https://github.com/xtne6f/TvtPlay) | ファイル再生プラグイン | [![TvtPlay](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvtPlay.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvtPlay.yml) |
| [noriokun4649/TVTComment](https://github.com/noriokun4649/TVTComment) | 実況プラグイン | [![TVTComment](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTComment.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVTComment.yml) |
| [xqq/BonDriver_EPGStation](https://github.com/xqq/BonDriver_EPGStation) | EPGStation 向け BonDriver | [![BonDriver_EPGStation](https://github.com/SlashNephy/TVTest-builder/actions/workflows/BonDriver_EPGStation.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/BonDriver_EPGStation.yml) |
| [logue/CasProcessor](https://github.com/logue/CasProcessor) | CAS 処理 プラグイン<br>BonDriver_EPGStation を使用する際は不要 | [![CasProcessor](https://github.com/SlashNephy/TVTest-builder/actions/workflows/CasProcessor.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/CasProcessor.yml) |
| [logue/TvCas](https://github.com/logue/TvCas) | CasProcessor プラグイン<br>BonDriver_EPGStation を使用する際は不要 | [![TvCas](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvCas.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TvCas.yml) |
| [xtne6f/TTRec](https://github.com/xtne6f/TTRec) | 予約拡張プラグイン | [![TTRec](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TTRec.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TTRec.yml) |
| [SlashNephy/MuteInact](https://github.com/SlashNephy/MuteInact) | ミュートプラグイン | [![MuteInact](https://github.com/SlashNephy/TVTest-builder/actions/workflows/MuteInact.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/MuteInact.yml) |
| [nns779/px4_drv](https://github.com/nns779/px4_drv) | 非公式 PLEX ドライバ (winusb) | [![px4_drv](https://github.com/SlashNephy/TVTest-builder/actions/workflows/px4_drv.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/px4_drv.yml) |
| [xtne6f/TVCaption3](https://github.com/xtne6f/TVCaption3) | 字幕表示プラグイン | [![TVCaption3](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaption3.yml/badge.svg)](https://github.com/SlashNephy/TVTest-builder/actions/workflows/TVCaption3.yml) |

以下のプロジェクトは各リポジトリを参照してください。

| リポジトリ | 説明 | Workflow |
|---|---|---|
| [SlashNephy/TvTestRPC](https://github.com/SlashNephy/TvTestRPC) | Discord RPC プラグイン | [![TvTestRPC](https://github.com/SlashNephy/TvTestRPC/actions/workflows/latest.yml/badge.svg)](https://github.com/SlashNephy/TvTestRPC/actions/workflows/latest.yml) |
| [SlashNephy/TVTestAnnictRecorder](https://github.com/SlashNephy/TVTestAnnictRecorder) | Annict 記録プラグイン | [![TVTestAnnictRecorder](https://github.com/SlashNephy/TVTestAnnictRecorder/actions/workflows/latest.yml/badge.svg)](https://github.com/SlashNephy/TVTestAnnictRecorder/actions/workflows/latest.yml) |
