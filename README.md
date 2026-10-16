<div align="center">

# iOS Prework: Intro App

A first UIKit app made as an introduction to Xcode and iOS development.

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift"/>
<img src="https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=apple&logoColor=white" alt="UIKit"/>
<img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode"/>

</div>

> Prework project for CodePath's **iOS 101: Intro to iOS Development** course. Submitted by Abhishek Yadav. Time spent: about 1 hour.

## Overview

The assignment is a single-screen app with three labels and a button. Tapping the button changes the background to a random color. The walkthrough GIF below shows the finished app running in the simulator.

## Course checklist

**Required features**

- [x] The user sees a screen with three labels and a button
- [x] Tapping the button changes the screen color to a random color

## Walkthrough

<img src="./IOS%20101.gif" title="Video Walkthrough" alt="Video walkthrough of the iOS prework app" />

## Tech stack

| Layer | Technology |
| --- | --- |
| Language | Swift 5 |
| UI | UIKit, storyboards |
| Lifecycle | `AppDelegate` + `SceneDelegate` |
| Target | iOS 16.4 deployment target |

## Project structure

```text
.
├── IOS/
│   ├── AppDelegate.swift
│   ├── SceneDelegate.swift
│   ├── ViewController.swift
│   ├── Base.lproj/
│   │   ├── Main.storyboard
│   │   └── LaunchScreen.storyboard
│   ├── Assets.xcassets/
│   └── Info.plist
├── IOS.xcodeproj/
└── IOS 101.gif               # walkthrough recording
```

## Getting started

1. Open `IOS.xcodeproj` in Xcode (14.3 or later for the iOS 16.4 SDK).
2. Select an iPhone simulator.
3. Build and run with `Cmd + R`.

## App brainstorming (Step 4)

The prework also asked for a short analysis of three existing apps.

| App | Key ideas |
| --- | --- |
| Instagram | Visual storytelling through photo and video sharing; filters and editing; direct messaging |
| LinkedIn | Professional networking; job search and applications; sharing insights with your network |
| YouTube | Wide range of educational and entertainment video; channel subscriptions; user-generated content |

## Notes

- The committed source matches the default Xcode app template. `ViewController.swift` contains only `viewDidLoad`, and `Main.storyboard` has no labels or button. The finished app appears only in the walkthrough GIF.
- The author's note: it was enjoyable working in Xcode.

---

Built by [Abhishek Yadav](https://github.com/abhiishek340)
