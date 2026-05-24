# Third Party Notices

最終更新日: 2026-05-24

このドキュメントは、Nocoro が利用している第三者製ソフトウェア、ライブラリ、フレームワーク、開発ツール等に関する権利表示とライセンス情報をまとめたものです。

Nocoro 本体の利用条件については `LICENSE.md` を確認してください。第三者製ソフトウェアについては、それぞれの提供元が定めるライセンス条件が適用されます。

## 1. 基本方針

Nocoro は、アプリの実装、ビルド、配布にあたり、オープンソースソフトウェア、ライブラリ、フレームワーク、開発ツール等を利用しています。

それらの著作権、商標、その他の権利は、各権利者に帰属します。このドキュメントにおける記載は、Nocoro が各第三者ソフトウェアの権利を主張するものではありません。

## 2. 依存関係の確認元

この一覧は、公開用リポジトリに含まれる以下のファイルをもとに確認しています。

- `package.json`
- `package-lock.json`
- `src-tauri/Cargo.toml`
- `src-tauri/Cargo.lock`

実際に利用される推移的依存関係は、リリース時点の lockfile に従います。

## 3. 主な第三者ソフトウェア

### npm packages

| 名称 | バージョン | 用途 | ライセンス |
|---|---:|---|---|
| `@tauri-apps/api` | 2.10.1 | Tauri フロントエンド API | Apache-2.0 OR MIT |
| `@tauri-apps/plugin-opener` | 2.5.3 | Tauri opener plugin API | MIT OR Apache-2.0 |
| `@sveltejs/adapter-static` | 3.0.10 | SvelteKit 静的出力 adapter | MIT |
| `@sveltejs/kit` | 2.57.1 | フロントエンドアプリ基盤 | MIT |
| `@sveltejs/vite-plugin-svelte` | 5.1.1 | Svelte 用 Vite plugin | MIT |
| `@tauri-apps/cli` | 2.10.1 | Tauri ビルド / 開発 CLI | Apache-2.0 OR MIT |
| `svelte` | 5.55.4 | フロントエンド UI | MIT |
| `svelte-check` | 4.4.6 | Svelte / TypeScript 検査 | MIT |
| `typescript` | 5.6.3 | TypeScript コンパイラ | Apache-2.0 |
| `vite` | 6.4.2 | フロントエンドビルド | MIT |
| `vitest` | 4.1.5 | テストランナー | MIT |

### Rust crates

| 名称 | バージョン | 用途 | ライセンス |
|---|---:|---|---|
| `active-win-pos-rs` | 0.10.1 | アクティブウィンドウ情報の取得 | MIT OR Apache-2.0 |
| `arboard` | 3.6.1 | クリップボード操作 | MIT OR Apache-2.0 |
| `base64` | 0.22.1 | Base64 エンコード / デコード | MIT OR Apache-2.0 |
| `chrono` | 0.4.44 | 日時処理 | MIT OR Apache-2.0 |
| `image` | 0.25.10 | 画像処理 | MIT OR Apache-2.0 |
| `regex` | 1.12.3 | 正規表現 | MIT OR Apache-2.0 |
| `reqwest` | 0.12.28 | HTTP client | MIT OR Apache-2.0 |
| `serde` | 1.0.228 | シリアライズ / デシリアライズ | MIT OR Apache-2.0 |
| `serde_json` | 1.0.149 | JSON 処理 | MIT OR Apache-2.0 |
| `tauri` | 2.10.3 | デスクトップアプリ基盤 | Apache-2.0 OR MIT |
| `tauri-build` | 2.5.6 | Tauri build script helper | Apache-2.0 OR MIT |
| `tauri-plugin-opener` | 2.5.3 | URL / ファイルを開く Tauri plugin | Apache-2.0 OR MIT |
| `tokio` | 1.52.1 | 非同期 runtime | MIT |
| `windows` | 0.62.2 | Windows API bindings | MIT OR Apache-2.0 |
| `xcap` | 0.9.4 | スクリーンキャプチャ | Apache-2.0 |

上記は主要な直接依存関係です。推移的依存関係の完全な一覧は `package-lock.json` および `src-tauri/Cargo.lock` を確認してください。

## 4. 素材について

Nocoro に含まれるキャラクター画像、アプリアイコン、スクリーンショット、説明文、UI画像等のうち、作者が作成したものは Nocoro 側の権利物です。これらは、`LICENSE.md` に定める利用条件の対象です。

第三者の素材を利用する場合は、以下をこのドキュメントに追記します。

| 素材名 | 用途 | ライセンス | 権利者 / 配布元 | 備考 |
|---|---|---|---|---|
| なし | - | - | - | 現時点では未記載 |

## 5. AIモデル・外部ツールについて

Nocoro は、ユーザーが設定したローカル LLM、Vision モデル、または外部ツールと連携できる場合があります。

ユーザーが別途導入したモデル、ツール、サーバー、APIについては、それぞれの提供元が定める利用条件やライセンスが適用されます。Nocoro は、それら第三者モデルや外部サービスの利用条件を変更するものではありません。

## 6. 更新について

この一覧は、リリース時点の `package-lock.json` および `src-tauri/Cargo.lock` に基づいて更新します。

依存関係や配布物に含まれる素材を変更した場合は、各提供元のライセンス条件を確認し、必要に応じて本ドキュメントを更新します。

## 7. 注意

このドキュメントは、第三者製ソフトウェアのライセンス表示を補助するためのものです。最終的なライセンス確認は、リリース時点の実際の依存関係、配布物に含まれるファイル、各提供元のライセンス文に基づいて行ってください。

不足や誤りが見つかった場合は、速やかに修正します。
