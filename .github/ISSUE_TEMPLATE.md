name: 新規翻訳タスク(New Translation Task)
description: 新規翻訳タスク用issueを作成する
title: "[task]: "
labels: []
body:
  - type: textarea
    id: purpose
    attributes:
      label: 目的
      description: このissueの目的を記入してください。
      placeholder: 
    validations:
      required: true
  - type: textarea
    id: task_list
    attributes:
      label: タスクリスト
      description: このタスクの達成に必要な作業を具体的に列挙してください。
      value: |
        + [ ] 
    validations:
      required: false
  - type: textarea
    id: definition_of_done
    attributes:
      label: Doneの定義
      description: このタスクが「完了した」と言える状態を教えてください。
    validations:
      required: true

  - type: textarea
    id: reference
    attributes:
      label: 参考
      description: 関連する資料やissueがあれば教えてください。
    validations:
      required: false
  - type: textarea
    id: notice
    attributes:
      label: 留意事項
      value: |
        * 
    validations:
      required: false
  - type: textarea
    id: consideration
    attributes:
      label: 検討事項
      value: |
        * 
    validations:
      required: false
  - type: markdown
    id: special-thanks
    attributes:
      value: |
        Beta testing 
