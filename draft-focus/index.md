# Privacy Policy / プライバシーポリシー

## English

# Privacy Policy for draft focus

Last updated: 2026-02-26

## 1. Overview

draft focus ("the App") is a coding keyboard application for iOS. We are committed to protecting your privacy. This policy explains how the App handles your data.

## 2. Data Collection

The App does not collect, store, or transmit any personal data to our servers. There are no analytics, tracking, advertising, or telemetry systems of any kind embedded in the App.

## 3. Local Data Storage

All data created or configured within the App is stored exclusively on your device:

- Keyboard settings and preferences (stored in UserDefaults / App Group)
- Memos and prompt templates (stored in App Group JSON files)
- API keys for AI providers:
  - Stored in iOS Keychain by the host app
  - The selected provider key is synchronized to App Group UserDefaults so the keyboard extension can send AI requests
- Chat history with AI assistants (stored in local SQLite database in the host app)

We do not transmit this local data to our own servers. When you use AI features, messages and related request metadata are sent directly to the AI provider you selected.

## 4. Network Communication

The App communicates over the network only when you explicitly use AI features (e.g., AI chat). In this case, your message is sent directly to the AI provider you have selected and configured:

- OpenAI (api.openai.com)
- Anthropic (api.anthropic.com)
- Google (generativelanguage.googleapis.com)
- xAI (api.x.ai)

No data is routed through our servers. The App acts as a direct client to the provider's API.

## 5. Keyboard Input

The App functions as a custom keyboard extension on iOS. Despite requiring "Full Access" for AI features, the App:

- Does NOT silently record, log, or monitor your keystrokes
- Does NOT transmit keyboard input in the background
- Does NOT use Full Access for any purpose other than AI network requests

Important distinction: When you actively use the AI chat feature and press "send," the message you composed is transmitted to the AI provider you selected. This is an explicit, user-initiated action - not passive keystroke capture. The App never silently monitors or transmits what you type.

The basic keyboard, trackpad, and Japanese IME features work without Full Access.

## 6. Full Access Permission

iOS requires "Allow Full Access" for keyboard extensions that need network access. draft focus uses this permission for AI chat communication with the provider you configured.

## 7. Third-Party Services

When you use AI features, your messages are processed by the AI provider you selected. Please review the privacy policies of these providers:

- OpenAI: https://openai.com/privacy
- Anthropic: https://www.anthropic.com/privacy
- Google: https://policies.google.com/privacy
- xAI: https://x.ai/legal/privacy-policy

Provider names (OpenAI, Anthropic, Google, xAI, and their model names) are trademarks of their respective owners. draft focus is an independent client and is not affiliated with or endorsed by these providers.

## 8. Children's Privacy

The App does not knowingly collect any data from children under 13.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last updated" date above.

## 10. Contact

If you have questions about this Privacy Policy, please contact us through the App Store listing.

---

## 日本語

# draft focus プライバシーポリシー

最終更新日: 2026-02-26

## 1. 概要

draft focus（以下「本アプリ」）は、iOS 向けのコーディングキーボードアプリケーションです。私たちはユーザーのプライバシーを保護することに尽力しています。本ポリシーでは、本アプリがデータをどのように取り扱うかを説明します。

## 2. データ収集

本アプリは、個人データの収集、保存、送信を一切行いません。アナリティクス、トラッキング、広告、テレメトリーなどのシステムは一切含まれていません。

## 3. ローカルデータの保存

本アプリで作成・設定されたすべてのデータは、お使いのデバイス内にのみ保存されます:

- キーボード設定（UserDefaults / App Group に保存）
- メモ・プロンプトテンプレート（App Group JSON ファイルに保存）
- AI プロバイダーの API キー:
  - ホストアプリの iOS Keychain に暗号化保存
  - 選択中のプロバイダーのキーは、キーボード拡張が AI リクエストを送信できるよう App Group UserDefaults に同期
- AI アシスタントとのチャット履歴（ホストアプリのローカル SQLite データベースに保存）

これらのローカルデータを当社のサーバーに送信することはありません。AI 機能を使用する場合、メッセージと関連するリクエストメタデータは、選択した AI プロバイダーに直接送信されます。

## 4. ネットワーク通信

本アプリがネットワーク通信を行うのは、AI 機能（例: AI チャット）を明示的に使用した場合のみです。この場合、メッセージは選択・設定した AI プロバイダーに直接送信されます:

- OpenAI (api.openai.com)
- Anthropic (api.anthropic.com)
- Google (generativelanguage.googleapis.com)
- xAI (api.x.ai)

当社のサーバーを経由するデータはありません。本アプリはプロバイダーの API に直接接続するクライアントとして機能します。

## 5. キーボード入力

本アプリは iOS のカスタムキーボード拡張として機能します。AI 機能に「フルアクセス」が必要ですが、本アプリは:

- キー入力を密かに記録・ログ収集しません
- キーボード入力をバックグラウンドで送信しません
- AI ネットワークリクエスト以外の目的でフルアクセスを使用しません

重要な区別: AI チャット機能を使用して「送信」を押した場合、あなたが作成したメッセージは選択した AI プロバイダーに送信されます。これは明示的なユーザー操作であり、キー入力の密かな取得ではありません。本アプリはあなたの入力を無断で監視・送信することは一切ありません。

基本キーボード、トラックパッド、日本語 IME 機能はフルアクセスなしで動作します。

## 6. フルアクセスの許可

iOS では、ネットワークアクセスが必要なキーボード拡張に「フルアクセスを許可」が必要です。draft focus はこの許可を、設定した AI プロバイダーとの AI チャット通信にのみ使用します。

## 7. サードパーティサービス

AI 機能を使用する場合、メッセージは選択した AI プロバイダーによって処理されます。各プロバイダーのプライバシーポリシーをご確認ください:

- OpenAI: https://openai.com/privacy
- Anthropic: https://www.anthropic.com/privacy
- Google: https://policies.google.com/privacy
- xAI: https://x.ai/legal/privacy-policy

プロバイダー名（OpenAI、Anthropic、Google、xAI およびそのモデル名）は、それぞれの所有者の商標です。draft focus は独立したクライアントであり、これらのプロバイダーとの提携や推薦関係はありません。

## 8. お子様のプライバシー

本アプリは、13 歳未満のお子様からのデータ収集を意図的に行いません。

## 9. ポリシーの変更

本プライバシーポリシーは随時更新される場合があります。変更は上記の「最終更新日」に反映されます。

## 10. お問い合わせ

本プライバシーポリシーに関するご質問は、App Store のリスティングからお問い合わせください。
