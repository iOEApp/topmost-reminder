---
title: '置顶计时器'
date: 2026-10-16
type: landing

seo:
  title: '置顶计时器 — 四种计时类型，全部置顶显示'
  description: '置顶计时器：集合计时器、倒计时、秒表、闹钟四种类型的计时器软件，支持分组与多任务同步计时，所有计时器均可钉在屏幕最前面，重要提醒绝不错过。'

sections:
  - block: hero
    id: top
    content:
      eyebrow: '支持 Windows 10/11'
      title: '把计时器[钉在屏幕最前面]'
      text: '置顶计时器集合了计时器、倒计时器、秒表、闹钟四种类型，可对不同事件分别计时，同时管理和监控多个任务；所有计时器都可以钉在屏幕上，永远显示在最前面，专注工作时也不会错过重要提醒。'
      primary_action:
        text: 'Microsoft Store 下载'
        url: 'https://apps.microsoft.com/detail/9PKWCKBP9F6H'
        icon: 'brands/windows'
        style: gradient
      secondary_action:
        text: '查看屏幕截图'
        url: '/zh-hans/#screenshots'
        icon: 'hero/photo'
        style: outline
      media:
        type: image
        src: 'topmost-reminder-screenshot/topmost-reminder-zh-hans-01.png'
        alt: '置顶计时器的分组计时器与屏幕置顶效果'
    design:
      layout: stacked
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "#0a0e27"
        gradient:
          type: radial
          start: "rgba(56,120,255,0.45)"
          end: "transparent"
          position: "50% -10%"
          shape: ellipse
          size: "80% 80%"
        gradient_mesh:
          enable: true
          style: orbs
          intensity: medium
          animation: pulse
          colors: ["primary-500/25", "secondary-500/25"]
          orb_count: 2
          positions: ["top-1/3 left-1/4", "bottom-1/3 right-1/4"]
          sizes: ["w-[32rem] h-[32rem]", "w-[26rem] h-[26rem]"]

  - block: markdown
    id: painpoints
    content:
      title: '同时解决计时管理三大痛点'
      text: |
        1. **事情一多，计时器铺满屏幕还总错过提醒？** —— 由「计时器分组」解决。
        2. **专注工作时切窗口看时间，错过关键节点？** —— 由「屏幕置顶」解决。
        3. **倒计时、闹钟提醒方式单一？** —— 由「声音、消息与系统通知」解决。
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"
      spacing:
        padding: ["4rem", 0, "3rem", 0]

  - block: gallery
    id: screenshots
    content:
      title: '屏幕截图'
      subtitle: '看看置顶计时器的实际使用效果。'
      items:
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hans-01.png'
          alt: '分组计时器与屏幕置顶'
          caption: '多分组计时器同时运行，全部置顶显示'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hans-02.png'
          alt: '创建四类计时器'
          caption: '创建倒计时、计时器、秒表、闹钟，提醒方式一应俱全'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hans-03.png'
          alt: '调整置顶计时器'
          caption: 'Ctrl+F3 调整钉在屏幕上的计时器，随时钉住或取消'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hans-04.png'
          alt: '拖动计时器摆位'
          caption: '用鼠标把计时器拖动到屏幕任意位置'
    design:
      layout: slideshow
      aspect_ratio: wide
      caption_position: below
      lightbox: true
      autoplay: true
      autoplay_interval: 5000

  - block: markdown
    id: introduce
    content:
      title: '置顶计时器介绍'
      text: |
        置顶计时器是一款集合了计时器、倒计时器、秒表、闹钟四种类型的计时器软件。可用于对不同的事件进行分别计时，同时管理和监控多个任务；同时，也可以通过新建分组来创建不同的计时项目组，比如厨房计时组、工作计时组、运动计时组、待办闹钟组等，轻松管理不同类型的工作、生活、运动、待办事项等的计时和提醒需求。

        另一个特色是，所有计时器都可以被钉在屏幕上，永远显示在屏幕最前面，且不会影响您操作其它软件，对于特别重要的计时，确保您即便在专注工作时也不会错过。

        对于倒计时器和闹钟，支持声音、消息提醒和重复计时；对于闹钟，即便关闭软件，仍然可以通过系统进行通知。
    design:
      spacing:
        padding: ["4rem", 0, "4rem", 0]

  - block: features
    id: features
    content:
      subtitle: '为什么选择置顶计时器'
      title: '主要功能'
      text: '十二项能力，让计时和提醒变得轻松自如。'
      items:
        - name: '四种计时类型'
          icon: 'hero/clock'
          description: '计时器、倒计时、秒表、闹钟，一应俱全。'
        - name: '计时器分组'
          icon: 'hero/rectangle-group'
          description: '按项目新建分组，厨房、工作、运动各成一组。'
        - name: '多任务同步计时'
          icon: 'hero/bolt'
          description: '同时管理和监控多个计时项目与事件。'
        - name: '屏幕置顶'
          icon: 'hero/map-pin'
          description: '计时器钉在屏幕最前，重要提醒绝不错过。'
        - name: '不干扰其它软件'
          icon: 'hero/window'
          description: '置顶显示的同时，不影响操作其它窗口。'
        - name: '循环计时'
          icon: 'hero/arrow-path'
          description: '倒计时支持循环重复，周期任务自动化。'
        - name: '声音提醒'
          icon: 'hero/speaker-wave'
          description: '提醒铃声随心设置，到点即响。'
        - name: '消息提醒'
          icon: 'hero/chat-bubble-left-ellipsis'
          description: '到点弹出消息通知，忙碌也不错过。'
        - name: '闹钟系统通知'
          icon: 'hero/bell-alert'
          description: '关闭软件后，闹钟仍能触发系统通知。'
        - name: '名称与颜色'
          icon: 'hero/tag'
          description: '计时器名称、颜色自定义，一目了然。'
        - name: '拖动摆位'
          icon: 'hero/arrows-up-down'
          description: '用鼠标把计时器拖到屏幕任意位置。'
        - name: '快捷键支持'
          icon: 'hero/command-line'
          description: 'Ctrl+F3 等快捷键，编辑摆位更高效。'
    design:
      layout: bento
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: '四种计时类型'
          text: '计时器、倒计时器、秒表、闹钟四种类型覆盖绝大多数计时场景：正计时的计时器用于统计时长，倒计时器用于限定时间，秒表用于运动与竞速，闹钟用于到点提醒。四种类型可在同一窗口混合使用，分别计时、分别提醒。'
          feature_icon: check
          features:
            - '**计时器**：从 0 开始正向累计，统计各项事务耗时'
            - '**倒计时器**：设定目标时间倒计时，支持循环重复'
            - '**秒表**：精准到毫秒，适合运动、烹饪等场景'
            - '**闹钟**：设定响铃时间，支持按周期重复'
        - title: '分组管理'
          text: '通过新建分组来创建不同的计时项目组，比如厨房计时组、工作计时组、运动计时组、待办闹钟组等，轻松管理不同类型的工作、生活、运动、待办事项的计时和提醒需求。分组以标签页形式组织，切换一目了然。'
          feature_icon: check
          features:
            - '按项目新建分组，计时器各归其位'
            - '同一分组内的计时器可分别计时、分别提醒'
            - '多任务同步管理和监控，繁忙场景也从容'
        - title: '屏幕置顶'
          text: '所有计时器都可以被钉在屏幕上，永远显示在屏幕最前面，且不会影响您操作其它软件。对于特别重要的计时，确保您即便在专注工作时也不会错过。置顶的计时器还可以用鼠标拖动到屏幕任意位置。'
          feature_icon: check
          features:
            - '一键将计时器钉在屏幕最前或取消'
            - '置顶不影响其它软件的操作与交互'
            - 'Ctrl+F3 进入编辑，拖动摆位、停止编辑'
        - title: '提醒方式'
          text: '倒计时器和闹钟支持声音、消息提醒和重复计时；闹钟即便在关闭软件后，仍然可以通过系统进行通知，不会错过任何重要节点。'
          feature_icon: check
          features:
            - '声音提醒：铃声可设置'
            - '消息提醒：到点弹出通知'
            - '循环计时：倒计时可重复执行'
            - '系统通知：关闭软件后闹钟依然响铃'
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: pricing
    id: versions
    content:
      title: '版本说明'
      subtitle: '免费版提供有限数量的计时器以供测试体验；完整版不限计时器数量、支持分组且无广告。具体以下载的软件为准。'
      tiers:
        - name: '免费版'
          description: '零成本体验核心计时能力。'
          price_note: '免费'
          highlight: false
          features:
            - text: '四种计时类型'
              included: true
            - text: '最多 5 个计时器'
              included: true
            - text: '计时器分组'
              included: false
            - text: '屏幕置顶与拖动摆位'
              included: true
            - text: '循环计时与重复提醒'
              included: true
            - text: '声音、消息与系统通知'
              included: true
            - text: '无广告'
              included: false
        - name: '完整版'
          badge: '推荐'
          description: '不限数量，解锁分组与无广告体验。'
          price_note: '应用内购买'
          highlight: true
          features:
            - text: '四种计时类型'
              included: true
            - text: '不限数量的计时器'
              included: true
            - text: '计时器分组'
              included: true
            - text: '屏幕置顶与拖动摆位'
              included: true
            - text: '循环计时与重复提醒'
              included: true
            - text: '声音、消息与系统通知'
              included: true
            - text: '无广告'
              included: true

  - block: cta-card
    id: contact
    content:
      title: '联系我们'
      text: '任何意见、建议、反馈都可以联系我们，联系邮箱：oeapp@outlook.com'
      button:
        text: '发送邮件'
        url: 'mailto:oeapp@outlook.com'
        icon: 'hero/envelope'
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
---
