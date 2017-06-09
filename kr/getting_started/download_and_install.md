# 다운로드와 설치

아래 섹션에서는 각 플랫폼에 대해서 *QGroundControl* 의 [현재 안정 버전](../releases/release_notes.md)을 다운받는 방법에 대해서 알아봅니다.

## Windows

Windows Vista 이후 버전에 대해서 *QGroundControl* 설치:

1. [QGroundControl-installer.exe](https://s3-us-west-2.amazonaws.com/qgroundcontrol/latest/QGroundControl-installer.exe) 다운받기.
1. 인스톨러를 실행하기 위해서 더블클릭


## Mac OS X

Mac OS X 10.8 이후 버전에 대해서 *QGroundControl* 설치:

1. [QGroundControl.dmg](https://s3-us-west-2.amazonaws.com/qgroundcontrol/latest/QGroundControl.dmg) 다운받기.
1. .dmg 파일을 더블클릭하여 마운트하고 QGroundControl 어플리케이션을 Application 폴더로 드래기 하기


## Ubuntu Linux

Ubuntu Linux 14.04 LTS 이후 버전에 대해서 *QGroundControl* 설치. AppImage나 압축 파일 중에 하나로 설치 가능:

### AppImage

1. [QGroundControl.AppImage](https://s3-us-west-2.amazonaws.com/qgroundcontrol/latest/QGroundControl.AppImage) 다운로드.
1. 터미널 명령 사용하여 설치:
   ```sh
   chmod +x ./QGroundControl.AppImage
   ./QGroundControl.AppImage  (or double click)
   ```

### 압축 파일

1. [QGroundControl.tar.bz2](https://s3-us-west-2.amazonaws.com/qgroundcontrol/latest/QGroundControl.tar.bz2) 다운로드.
1. 터미널 명령으로 압축 풀기:
   ```sh
   tar jxf QGroundControl.tar.bz2
   cd qgroundcontrol
   ./qgroundcontrol-start.sh
   ```
1. <a class="urlextern" title="https://github.com/mavlink/qgroundcontrol" href="https://github.com/mavlink/qgroundcontrol" rel="nofollow">README</a>를 참조하여 추가 패키지를 설치. Qt를 설치하지 않아도 됨.


## Android

 Android 5.1 이후 버전에 대해서 *QGroundControl* 설치:

1. Google Play Store [QGroundControl link](https://play.google.com/store/apps/details?id=org.mavlink.qgroundcontrol) 열기.
1. 지시에 따라 설치


## iOS

> **Note** iOS용 *QGroundControl* 은 현재 베타버전입니다. [daily build](../releases/daily_builds.md#installing-ios-beta-using-test-flight)를 설치하세요.

iOS 8.0 이후 버전에 대해서 *QGroundControl* 설치:

1. [Installing iOS Daily Beta using Test Flight](../releases/daily_builds.md#installing-ios-beta-using-test-flight) 지시에 따라 설치


## 기존 안정 버전

기존 안정 버전은 <a href="https://github.com/mavlink/qgroundcontrol/releases/" target="_blank">GitHub</a> 를 참고하세요.

## Daily Builds

Daily builds는 [여기서 다운로드](../releases/daily_builds.md)를 참고하세요.
