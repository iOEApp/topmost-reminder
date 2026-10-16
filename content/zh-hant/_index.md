---
title: '置頂計時器'
date: 2026-10-16
type: landing

seo:
  title: '置頂計時器 — 四種計時類型，全部置頂顯示'
  description: '置頂計時器：集合計時器、倒數計時器、碼錶、鬧鐘四種類型的計時軟體，支援分組管理與多任務同步計時，所有計時器均可釘選在畫面最上層，重要提醒絕不錯過。'

sections:
  - block: hero
    id: top
    content:
      eyebrow: '支援 Windows 10/11'
      title: '把計時器[釘在畫面最上層]'
      text: '置頂計時器集合了計時器、倒數計時器、碼錶、鬧鐘四種類型，可對不同事件分別計時，同時管理與監控多個任務；所有計時器都可以釘選在畫面上，永遠顯示在畫面最上層，專心工作時也不會錯過重要提醒。'
      primary_action:
        text: 'Microsoft Store 下載'
        url: 'https://apps.microsoft.com/detail/9PKWCKBP9F6H'
        icon: 'brands/windows'
        style: gradient
      secondary_action:
        text: '查看螢幕截圖'
        url: '/zh-hant/#screenshots'
        icon: 'hero/photo'
        style: outline
      media:
        type: image
        src: 'topmost-reminder-screenshot/topmost-reminder-zh-hant-01.png'
        alt: '置頂計時器的分組計時器與畫面置頂效果'
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
      title: '同時解決計時管理三大痛點'
      text: |
        1. **事情一多，計時器鋪滿畫面還總錯過提醒？** —— 由「計時器分組」解決。
        2. **專心工作時切換視窗看時間，錯過關鍵節點？** —— 由「畫面置頂」解決。
        3. **倒數計時、鬧鐘提醒方式單一？** —— 由「聲音、訊息與系統通知」解決。
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"
      spacing:
        padding: ["4rem", 0, "3rem", 0]

  - block: gallery
    id: screenshots
    content:
      title: '螢幕截圖'
      subtitle: '看看置頂計時器的實際使用效果。'
      items:
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hant-01.png'
          alt: '分組計時器與畫面置頂'
          caption: '多分組計時器同時運行，全部置頂顯示'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hant-02.png'
          alt: '建立四類計時器'
          caption: '建立倒數計時、計時器、碼錶、鬧鐘，提醒方式一應俱全'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hant-03.png'
          alt: '調整置頂計時器'
          caption: 'Ctrl+F3 調整釘選在畫面中的計時器，隨時釘選或取消'
        - src: 'topmost-reminder-screenshot/topmost-reminder-zh-hant-04.png'
          alt: '拖曳計時器擺位'
          caption: '用滑鼠把計時器拖曳到畫面任意位置'
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
      title: '置頂計時器介紹'
      text: |
        置頂計時器是一款集合了計時器、倒數計時器、碼錶、鬧鐘四種類型的計時軟體。可用於對不同的事件進行分別計時，同時管理與監控多個任務；同時，也可以透過新增分組來建立不同的計時項目組，例如廚房計時組、工作計時組、運動計時組、待辦鬧鐘組等，輕鬆管理不同類型的工作、生活、運動、待辦事項的計時與提醒需求。

        另一項特色是，所有計時器都可以釘選在畫面上，永遠顯示在畫面最上層，且不會影響您操作其它軟體，針對特別重要的計時，確保您就算專心工作時也不會錯過。

        倒數計時器與鬧鐘支援聲音、訊息提醒和重複計時；鬧鐘功能即使關閉軟體，仍可透過系統傳送通知。
    design:
      spacing:
        padding: ["4rem", 0, "4rem", 0]

  - block: features
    id: features
    content:
      subtitle: '為什麼選擇置頂計時器'
      title: '主要功能'
      text: '十二項能力，讓計時與提醒變得輕鬆自如。'
      items:
        - name: '四種計時類型'
          icon: 'hero/clock'
          description: '計時器、倒數計時器、碼錶、鬧鐘，一應俱全。'
        - name: '計時器分組'
          icon: 'hero/rectangle-group'
          description: '依專案新增分組，廚房、工作、運動各成一組。'
        - name: '多任務同步計時'
          icon: 'hero/bolt'
          description: '同時管理與監控多個計時項目與事件。'
        - name: '畫面置頂'
          icon: 'hero/map-pin'
          description: '計時器釘選在畫面最上層，重要提醒絕不錯過。'
        - name: '不干擾其它軟體'
          icon: 'hero/window'
          description: '置頂顯示的同時，不影響操作其它視窗。'
        - name: '循環計時'
          icon: 'hero/arrow-path'
          description: '倒數計時支援循環重複，週期任務自動化。'
        - name: '聲音提醒'
          icon: 'hero/speaker-wave'
          description: '提醒鈴聲隨時設定，到點即響。'
        - name: '訊息提醒'
          icon: 'hero/chat-bubble-left-ellipsis'
          description: '到點彈出訊息通知，忙碌也不錯過。'
        - name: '鬧鐘系統通知'
          icon: 'hero/bell-alert'
          description: '關閉軟體後，鬧鐘仍可觸發系統通知。'
        - name: '名稱與顏色'
          icon: 'hero/tag'
          description: '計時器名稱、顏色自訂，一目了然。'
        - name: '拖曳擺位'
          icon: 'hero/arrows-up-down'
          description: '用滑鼠把計時器拖曳到畫面任意位置。'
        - name: '快速鍵支援'
          icon: 'hero/command-line'
          description: 'Ctrl+F3 等快速鍵，編輯擺位更高效。'
    design:
      layout: bento
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: '四種計時類型'
          text: '計時器、倒數計時器、碼錶、鬧鐘四種類型涵蓋絕大多數計時情境：正計時的計時器用於統計時長，倒數計時器用於限定時間，碼錶用於運動與競速，鬧鐘用於到點提醒。四種類型可在同一視窗混合使用，分別計時、分別提醒。'
          feature_icon: check
          features:
            - '**計時器**：從 0 開始正向累計，統計各項事務耗時'
            - '**倒數計時器**：設定目標時間倒數，支援循環重複'
            - '**碼錶**：精準到毫秒，適合運動、烹飪等情境'
            - '**鬧鐘**：設定響鈴時間，支援依週期重複'
        - title: '分組管理'
          text: '透過新增分組來建立不同的計時項目組，例如廚房計時組、工作計時組、運動計時組、待辦鬧鐘組等，輕鬆管理不同類型的工作、生活、運動、待辦事項的計時與提醒需求。分組以標籤頁形式組織，切換一目了然。'
          feature_icon: check
          features:
            - '依專案新增分組，計時器各歸其位'
            - '同一分組內的計時器可分別計時、分別提醒'
            - '多任務同步管理與監控，繁忙情境也從容'
        - title: '畫面置頂'
          text: '所有計時器都可以釘選在畫面上，永遠顯示在畫面最上層，且不會影響您操作其它軟體。針對特別重要的計時，確保您就算專心工作時也不會錯過。置頂的計時器還可以用滑鼠拖曳到畫面任意位置。'
          feature_icon: check
          features:
            - '一鍵將計時器釘選在畫面最上層或取消'
            - '置頂不影響其它軟體的操作與互動'
            - 'Ctrl+F3 進入編輯，拖曳擺位、停止編輯'
        - title: '提醒方式'
          text: '倒數計時器與鬧鐘支援聲音、訊息提醒和重複計時；鬧鐘功能即使關閉軟體，仍可透過系統傳送通知，不會錯過任何重要節點。'
          feature_icon: check
          features:
            - '聲音提醒：鈴聲可設定'
            - '訊息提醒：到點彈出通知'
            - '循環計時：倒數計時可重複執行'
            - '系統通知：關閉軟體後鬧鐘依然響鈴'
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: pricing
    id: versions
    content:
      title: '版本說明'
      subtitle: '免費版提供有限數量的計時器以供測試體驗；完整版不限計時器數量、支援分組且無廣告。具體以下載的軟體為準。'
      tiers:
        - name: '免費版'
          description: '零成本體驗核心計時能力。'
          price_note: '免費'
          highlight: false
          features:
            - text: '四種計時類型'
              included: true
            - text: '最多 5 個計時器'
              included: true
            - text: '計時器分組'
              included: false
            - text: '畫面置頂與拖曳擺位'
              included: true
            - text: '循環計時與重複提醒'
              included: true
            - text: '聲音、訊息與系統通知'
              included: true
            - text: '無廣告'
              included: false
        - name: '完整版'
          badge: '推薦'
          description: '不限數量，解鎖分組與無廣告體驗。'
          price_note: '應用程式內購買'
          highlight: true
          features:
            - text: '四種計時類型'
              included: true
            - text: '不限數量的計時器'
              included: true
            - text: '計時器分組'
              included: true
            - text: '畫面置頂與拖曳擺位'
              included: true
            - text: '循環計時與重複提醒'
              included: true
            - text: '聲音、訊息與系統通知'
              included: true
            - text: '無廣告'
              included: true

  - block: cta-card
    id: contact
    content:
      title: '聯繫我們'
      text: '任何意見、建議、反饋都可以聯繫我們，聯繫郵箱：oeapp@outlook.com'
      button:
        text: '發送郵件'
        url: 'mailto:oeapp@outlook.com'
        icon: 'hero/envelope'
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
---
