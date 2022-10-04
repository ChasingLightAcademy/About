---
name: 入园申请表
about: 签订契约，成为魔法少女吧！
title: "【入园申请】<此处填写你的名字>"
labels: 入园申请
assignees:
  - qyl27
body:
  - type: input
    id: name
    attributes:
      label: 名字/ID
      description: 我们如何称呼你？
    validations:
      required: true
  - type: input
    id: email
    attributes:
      label: 邮箱/Email
      description: 联系方式，将被用于发布部分通知/邮件列表等。
    validations:
      required: true
  - type: markdown
    attributes:
      label: 想要学习的是？
      description: 用于我们提供合适的教程。
    validations:
      required: true
---

<!-- Ver 1.0.0 -->
<!-- 请勿修改这一行上面的内容 -->
