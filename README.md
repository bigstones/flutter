# flutter <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=Flutter&logoColor=white"/>


flutter를 구성하면서 필요한 내용들을 정리하려고 만들었습니다




## 어플리케이션 이름 설정
flutter 어플리케이션을 만들 때 어플리케이션 이름을 설정할 수 있다


#### Android

##### android/app/src/main


    <application
    android:label="App Name">
    
    
    

#### IOS

##### ios/Runner

    <key>CFBundleName</key>
    <string>App Name</string> // Your app name here



#### Android & IOS

##### pubspec.yaml

    dependencies:
        flutter_launcher_name: ^0.0.1
    flutter_launcher_name:
        name: "App Name"

설정하시고

    $ flutter pub get
    $ flutter pub run flutter_launcher_name:main
    
    
하시면 Android와 IOS모두 설정이 완료돼있을겁니다




## 상태관리 라이브러리

#### GetX
