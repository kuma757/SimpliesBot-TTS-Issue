name: Bug Report
description: SimpliesBot TTS の不具合を報告します
title: "[Bug]: "
labels:
  - bug

body:
  - type: markdown
    attributes:
      value: |
        SimpliesBot TTS の不具合報告ありがとうございます。
        できるだけ詳しく記載していただけると、調査がスムーズになります。

  - type: textarea
    id: bug_description
    attributes:
      label: 不具合の内容
      description: どのような問題が発生していますか？
      placeholder: |
        例:
        読み上げが途中で止まる
        VCへ接続できない
        音声生成が失敗する
    validations:
      required: true

  - type: textarea
    id: reproduce_steps
    attributes:
      label: 再現手順
      description: 不具合を再現する方法を記載してください
      placeholder: |
        1. /join を実行
        2. メッセージを送信
        3. 読み上げが開始されない
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: 本来期待される動作
      placeholder: |
        正常に読み上げが開始される
    validations:
      required: true

  - type: dropdown
    id: severity
    attributes:
      label: 影響度
      options:
        - 軽微
        - 普通
        - 重大
        - 致命的
    validations:
      required: true

  - type: input
    id: discord_server
    attributes:
      label: サーバーID (任意)
      placeholder: "123456789012345678"

  - type: input
    id: channel_id
    attributes:
      label: チャンネルID (任意)
      placeholder: "123456789012345678"

  - type: textarea
    id: logs
    attributes:
      label: ログ・エラー内容
      description: エラーログやスクリーンショットなど
      render: shell
      placeholder: |
        ERROR: Unknown interaction
        VoiceboxAPI timeout

  - type: dropdown
    id: bot_type
    attributes:
      label: 使用ボット
      options:
        - Main Bot
        - Sub1
        - Sub2
        - Sub3
        - Sub4
        - Sub5
    validations:
      required: true

  - type: checkboxes
    id: confirmations
    attributes:
      label: 確認事項
      options:
        - label: 最新状態でも問題が発生しています
          required: true
        - label: 同様のIssueが存在しないことを確認しました
          required: true
