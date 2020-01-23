---
layout: post
title: Android 01. Selendroid
category: Project
tags: [Project]
comments: true
---

# Selendroid 사용법

1. ~~http://selendroid.io/setup.html#launchingSelendroid
    Launching Selendroid항목에 있는 selendroid-standalone.jar파일 다운~~
    위 링크에서 받으면 실행 안됨
    https://drive.google.com/open?id=1YtCr9rV4K73q6c13V6bGSSCPfoRQeUCa
    이 링크에서 받기

2. C:\selendroid 파일에 1에서 다운 받은 jar파일을 이동
3. 명령프롬프트를 실행해 해당 root로 이동한 후
   **java -jar selendroid-standalone-0.17.0-with-dependencies_fixed.jar -app selendroid-test-app-0.17.0.apk**
   위 명령어 실행

4. http://localhost:4444/wd/hub/status 접속 후 서버 실행 확인
