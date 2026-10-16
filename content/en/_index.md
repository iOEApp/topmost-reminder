---
title: 'Topmost Reminder'
date: 2026-10-16
type: landing

seo:
  title: 'Topmost Reminder — Four timer modes, all pinned on top'
  description: 'Topmost Reminder is a timer app integrating Timer, Countdown, Stopwatch and Alarm. Create groups to organize timer projects, and pin every timer on top of your screen so you never miss an alert.'

sections:
  - block: hero
    id: top
    content:
      eyebrow: 'For Windows 10/11'
      title: 'Timers that [stay on top] of your screen'
      text: 'Topmost Reminder integrates four timer modes — Timer, Countdown, Stopwatch and Alarm. Time separate events independently, manage and monitor multiple tasks at once, and pin every timer on top of your screen so you never miss an important alert.'
      primary_action:
        text: 'Get it on Microsoft Store'
        url: 'https://apps.microsoft.com/detail/9PKWCKBP9F6H'
        icon: 'brands/windows'
        style: gradient
      secondary_action:
        text: 'View screenshots'
        url: '/en/#screenshots'
        icon: 'hero/photo'
        style: outline
      media:
        type: image
        src: 'topmost-reminder-screenshot/topmost-reminder-en-01.png'
        alt: 'Topmost Reminder timer groups pinned on top of the screen'
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
      title: 'Three timing headaches, solved'
      text: |
        1. **Timers cluttering your screen and alerts slipping by?** — solved by timer groups.
        2. **Missing key moments while focused on work?** — solved by on-top pinning.
        3. **Limited ways to be reminded?** — solved by sound, notification and system alerts.
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"
      spacing:
        padding: ["4rem", 0, "3rem", 0]

  - block: gallery
    id: screenshots
    content:
      title: 'Screenshots'
      subtitle: 'A look at Topmost Reminder in action.'
      items:
        - src: 'topmost-reminder-screenshot/topmost-reminder-en-01.png'
          alt: 'Timer groups pinned on top'
          caption: 'Multiple timer groups running at once, all pinned on top'
        - src: 'topmost-reminder-screenshot/topmost-reminder-en-02.png'
          alt: 'Create four timer types'
          caption: 'Create countdown, timer, stopwatch and alarm clocks with flexible alerts'
        - src: 'topmost-reminder-screenshot/topmost-reminder-en-03.png'
          alt: 'Adjust pinned timers'
          caption: 'Adjust timers pinned on your screen with Ctrl+F3, pin or unpin anytime'
        - src: 'topmost-reminder-screenshot/topmost-reminder-en-04.png'
          alt: 'Drag timers anywhere'
          caption: 'Drag timers to any position on your screen'
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
      title: 'Introduction to Topmost Reminder'
      text: |
        Topmost Reminder is a timer app integrating four modes: Timer, Countdown, Stopwatch and Alarm. You can time separate events independently, manage and monitor multiple tasks at the same time. You may also create groups to organize timer projects, such as Kitchen Timers, Work Timers, Workout Timers, To-do Alarms, etc. It easily handles timing and alert needs for your work, daily life, sports and to-do items.

        Another key feature: all timers can be pinned on top of your screen. They stay visible above other windows without interfering with your work in other apps. For critical timing tasks, you will not miss alerts even when you are focused.

        Countdowns and Alarms support sound alerts, notification alerts and recurring timing. Alarms will still trigger system notifications even if the app is closed.
    design:
      spacing:
        padding: ["4rem", 0, "4rem", 0]

  - block: features
    id: features
    content:
      subtitle: 'Why Topmost Reminder'
      title: 'Key features'
      text: 'Twelve capabilities that make timing and reminding effortless.'
      items:
        - name: 'Four timer modes'
          icon: 'hero/clock'
          description: 'Timer, Countdown, Stopwatch and Alarm in one app.'
        - name: 'Timer groups'
          icon: 'hero/rectangle-group'
          description: 'Organize timer projects — kitchen, work, workout.'
        - name: 'Multi-task timing'
          icon: 'hero/bolt'
          description: 'Manage and monitor multiple timers and events at once.'
        - name: 'Always on top'
          icon: 'hero/map-pin'
          description: 'Pin timers above every window and never miss an alert.'
        - name: 'Non-intrusive'
          icon: 'hero/window'
          description: 'Pinned timers never get in the way of other apps.'
        - name: 'Recurring timing'
          icon: 'hero/arrow-path'
          description: 'Countdowns can repeat automatically for cycle tasks.'
        - name: 'Sound alerts'
          icon: 'hero/speaker-wave'
          description: 'Pick the ringtone that gets your attention.'
        - name: 'Notification alerts'
          icon: 'hero/chat-bubble-left-ellipsis'
          description: 'Pop-up notifications when time is up.'
        - name: 'System notifications'
          icon: 'hero/bell-alert'
          description: 'Alarms still ring through the system with the app closed.'
        - name: 'Names and colors'
          icon: 'hero/tag'
          description: 'Rename and recolor timers to tell them apart at a glance.'
        - name: 'Drag to place'
          icon: 'hero/arrows-up-down'
          description: 'Drag timers to any position on your screen.'
        - name: 'Keyboard shortcuts'
          icon: 'hero/command-line'
          description: 'Ctrl+F3 and friends make editing and placing faster.'
    design:
      layout: bento
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: 'Four timer modes'
          text: 'Timer, Countdown, Stopwatch and Alarm cover virtually every timing need: the Timer counts up to track how long things take, the Countdown limits a task, the Stopwatch measures sports and races, and the Alarm rings at a set time. All four can run side by side in one window, each timing and alerting on its own.'
          feature_icon: check
          features:
            - '**Timer**: counts up from zero to track elapsed time'
            - '**Countdown**: set a target time, with optional repeat'
            - '**Stopwatch**: millisecond precision for sports and cooking'
            - '**Alarm**: rings at a set time, on a repeating schedule'
        - title: 'Timer groups'
          text: 'Create groups to organize timer projects — Kitchen Timers, Work Timers, Workout Timers, To-do Alarms and more. Groups appear as tabs, so switching between projects takes one click.'
          feature_icon: check
          features:
            - 'Create a group per project and keep timers organized'
            - 'Timers inside a group time and alert independently'
            - 'Manage and monitor multiple projects at the same time'
        - title: 'Always on top'
          text: 'All timers can be pinned on top of your screen. They stay visible above other windows without interfering with your work in other apps. For critical timing tasks, you will not miss alerts even when you are focused. Pinned timers can also be dragged to any position.'
          feature_icon: check
          features:
            - 'Pin or unpin timers with one click'
            - 'Pinned timers never block interaction with other apps'
            - 'Press Ctrl+F3 to edit, drag to place, then stop editing'
        - title: 'Alert options'
          text: 'Countdowns and Alarms support sound alerts, notification alerts and recurring timing. Alarms will still trigger system notifications even if the app is closed, so no important moment slips by.'
          feature_icon: check
          features:
            - 'Sound alerts: choose your ringtone'
            - 'Notification alerts: pop-up when time is up'
            - 'Recurring timing: countdowns can repeat'
            - 'System notifications: alarms ring even with the app closed'
    design:
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: pricing
    id: versions
    content:
      title: 'Version information'
      subtitle: 'The free version includes a limited number of timers so you can try the app. The full version removes the timer limit, adds groups and contains no ads. The downloaded app is authoritative.'
      tiers:
        - name: 'Free version'
          description: 'Try the core timing experience at no cost.'
          price_note: 'Free'
          highlight: false
          features:
            - text: 'Four timer modes'
              included: true
            - text: 'Up to 5 timers'
              included: true
            - text: 'Timer groups'
              included: false
            - text: 'On-top pinning and drag to place'
              included: true
            - text: 'Recurring timing and repeat alerts'
              included: true
            - text: 'Sound, notification and system alerts'
              included: true
            - text: 'No ads'
              included: false
        - name: 'Full version'
          badge: 'Recommended'
          description: 'Unlimited timers, groups and an ad-free experience.'
          price_note: 'In-app purchase'
          highlight: true
          features:
            - text: 'Four timer modes'
              included: true
            - text: 'Unlimited timers'
              included: true
            - text: 'Timer groups'
              included: true
            - text: 'On-top pinning and drag to place'
              included: true
            - text: 'Recurring timing and repeat alerts'
              included: true
            - text: 'Sound, notification and system alerts'
              included: true
            - text: 'No ads'
              included: true

  - block: cta-card
    id: contact
    content:
      title: 'Contact us'
      text: 'Any comments, suggestions or feedback are welcome — reach us at oeapp@outlook.com'
      button:
        text: 'Send email'
        url: 'mailto:oeapp@outlook.com'
        icon: 'hero/envelope'
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
---
