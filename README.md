# CopilotControlPowerApps
Copilot コントロールのコードを共有しています。
現在、プレビューで提供されている

## 現在提供されているチャット形式のPower Apps にCopilot を持ち込む機能

現在主に3種類のチャット形式でCopilot コントロールが提供されています。

### Copilot コントロール

[キャンバスアプリCopilot コントロール](https://learn.microsoft.com/ja-jp/power-apps/maker/canvas-apps/add-ai-copilot)はブラウザの言語が英語の際にはコントロール一覧に表示されます。

![image](https://github.com/user-attachments/assets/37f09b33-7ea3-426b-8aaf-28553e941f8f)

ブラウザが日本語の環境ではCopilot コントロールはコントロール一覧に表示されません。

![image](https://github.com/user-attachments/assets/cba82dc2-6cf4-4590-9cec-beef78e08edc)

こちらのコードを用意していますので、別の環境でも使いたい場合は以下のコードをペーストするとキャンバスアプリ内で利用することができます。

```
- Copilot1:
    Control: Copilot
    Variant: pcfdataset
```

貼り付け方は以下のように行います。

![image](https://github.com/user-attachments/assets/ab701805-cd8a-42f6-b53c-2098772bf1ae)


### チャットボットコントロール
[チャットボットコントロール](https://learn.microsoft.com/ja-jp/power-apps/maker/canvas-apps/add-ai-chatbot)はCopilot Studio で作成したCopilot をキャンバスアプリ内に埋め込むことができるコントロールです。

![image](https://github.com/user-attachments/assets/56ad11db-68fd-4996-8d2d-280a870ee268)

このコントロールは[こちら](https://github.com/geekfujiwara/CopilotStudioinPowerAppsControl)でコードを共有しています。

### App Copilot

[App Copilot](https://learn.microsoft.com/ja-jp/power-apps/maker/canvas-apps/add-custom-copilot)はキャンバスアプリの画面の外に表示させることができるCopilot Studio で作成したCopilot のコントロールです。

![image](https://github.com/user-attachments/assets/98e2e22d-91b5-4049-ac8a-d69881308e4e)

キャンバスアプリの画面をCopilot が専有しないというメリットがあります。


