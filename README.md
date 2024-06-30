# *목표*

안드로이드 앱에서 음성 및 동영상 재생/ 저장 기능은 강의, 회의, 인터뷰 등을 기록하는 데 사용될 수 있으며,
또 음악, 팟캐스트 또는 기타 오디오 프로젝트를 만들기 위해 음성 녹음을 사용할 수 있습니다.    
중요한 개인적 또는 업무적 순간을 기록하고 보관하는 데 도움이 됩니다. 이는 나중에 참조하거나 추억을 되새기는 데 유용할 수 있습니다    
학생들은 강의를 녹음하여 나중에 복습할 수 있으며, 교사들은 교육 자료를 만들기 위해 동영상을 녹화할 수 있습니다  
다양한 프로젝트에 적용될 수 있는 음성 및 동영상 재생/ 저장 기능을 만들어보고 향후 프로젝트에 적용하기 위함입니다.   

## 관련 권한 추가
```kotlin
 <!-- 음성 녹음을 위한 권한 사용 추가 -->
    <uses-permission android:name="android.permission.RECORD_AUDIO" />
    
    <!-- 카메라 기능 사용 -->
    <uses-feature
        android:name="android.hardware.camera"
        android:required="true"/>
```
```
음성 녹음에 대한 사용 권한과 카메라 기능(Feature)에 관한 권한 사용을 추가하였습니다.
```
## 레이아웃
![image](https://github.com/chihyeonwon/Voice_Record/assets/58906858/6439a6d7-ba39-454a-8562-db194952754b)
```
레이아웃은 상단에 음성을 녹음하고 재생하는 버튼 두개와 바로 밑에 동영상 녹화하는 버튼을 주고
동영상 녹화 버튼 아래에 녹화한 동영상을 재생할 수 있는 인터페이스를 줬다.
```
