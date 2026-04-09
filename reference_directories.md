---
name: 常用目錄路徑
description: 跨專案通用的目錄路徑與結構慣例
type: reference
---

## 我的實際路徑（neil）
- `{BASE_DIR}` = `/Users/neil/_3.xUpProject`
- `{ANDROID_SDK_DIR}` = `/Users/neil/AndroidSDK`

---

<!-- 替換說明：將 {BASE_DIR} 改為你的專案根目錄，例：/Users/yourname/_3.xUpProject -->
<!-- 將 {ANDROID_SDK_DIR} 改為你的 Android SDK 目錄，例：/Users/yourname/AndroidSDK -->

## 遊戲引擎
- Axmol 引擎原始碼：`{BASE_DIR}/axlib`

## 工具
- GodGameToolBox 3.0 (Android Studio)：`{ANDROID_SDK_DIR}/GodGameToolBox_3.0/android-studio`

## 渲染
- Android 渲染使用 OpenGL（非 Vulkan）

## 專案目錄結構慣例
所有專案放在 `{BASE_DIR}/{專案名}/` 底下，固定包含：
- `proj.ios/` — iOS 平台相關檔案
- `proj.android-axlib/` — Android 平台相關檔案
- `proj.web/` — Web 平台相關檔案
- `Classes/` — C++ 原始碼（.cpp / .h）

例如：
- `{BASE_DIR}/MixMJ_Fish_v7.9/proj.web`
- `{BASE_DIR}/MixMJ_Fish_v8.0/proj.ios`
