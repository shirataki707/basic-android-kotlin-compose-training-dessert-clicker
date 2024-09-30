Dessert Clicker app
=====================

Code for Android Basics with Compose Codelab.
[Codelab](https://developer.android.com/codelabs/basic-android-kotlin-compose-activity-lifecycle?continue=https://developer.android.com/courses/pathways/android-basics-compose-unit-4-pathway-1?hl%3Dja%23codelab-https://developer.android.com/codelabs/basic-android-kotlin-compose-activity-lifecycle#6)

Screenshot
----------
<img src="https://github.com/user-attachments/assets/241876db-3df5-4069-be20-8c9b8209500b" width="300">

Learn
-----
![lifecycle](https://github.com/user-attachments/assets/aedb4f6b-84b5-4935-801f-0acc8ba32a4b)
- Lifecycle
  - onCreate
    - Activityが作成されるとき
  - onRestart
    - ActivityがonStop状態から再開されるとき
  - onStart
    - Activityが表示されるとき
  - onResume
    - Activityがフォーカスを持っているとき
  - onPause
    - Activityの一部が見えているが、フォーカスがないとき(共有ボタンを押した時とか)
  - onStop
    - アプリがバックグラウンドに移動したとき
  - onDestroy
    - アプリを終了するとき
    - Configuration changes(Localの変更、画面の回転など)でも呼ばれる
    - Configuration ChangesのときにComposableの状態を保持するには、rememberSavableを使う

Introduction
------------

Dessert Clicker is a game about making desserts.

Press the button, make a dessert, earn the big bucks.

You use this app in the course to explore the Android lifecycle and log messages to
the Android console (Logcat).

Pre-requisites
--------------

You need to know:
- How to open, build, and run apps with Android Studio.
- What an activity is, and how to create one in your app.
- What the activity's onCreate() method does, and the kind of operations
  that are performed in that method.


Getting Started
---------------

1. Download and run the app.
