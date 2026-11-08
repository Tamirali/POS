# Smart POS Pro - APK Build Guide

## Prerequisites
- Node.js installed (https://nodejs.org)
- Android Studio installed (https://developer.android.com/studio)
- Java JDK 17

## Step 1: Install dependencies
npm install

## Step 2: Add Android platform
npm install @capacitor/android
npx cap add android

## Step 3: Copy web files
npx cap copy

## Step 4: Sync plugins
npx cap sync

## Step 5: Open in Android Studio
npx cap open android

## Step 6: Build APK
In Android Studio:
- Build → Build Bundle(s) / APK(s) → Build APK(s)

## APK Location
android/app/build/outputs/apk/debug/app-debug.apk

## Share APK
- WhatsApp pe bhej dein
- Google Drive pe upload karein
- Direct USB se copy karein

## Install on Phone
1. APK phone mein copy karein
2. Settings → "Unknown sources" enable karein
3. APK tap karein → Install
4. Done!
