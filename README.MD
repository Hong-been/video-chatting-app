# Pinto : Video Chatting App for Student in college.

## 프론트엔드 주요 기술스택 : React Native

### 해결해야 할 문제

- 주어진 기간에 앱 형태의 결과물을 구현해내야 한다.
- 디자이너가 의도한 UI대로 정확히 구현해야 한다.
- 백엔드와 통신하기 위한 API구현과 담당자와의 원활한 소통

### 문제해결을 위한 기술스택 선정 이유

- 주어진 기간내에 네이티브 앱(Native App)과 Fluttter 등의 프레임워크를 새롭게 익히기에 시간이 부족하고 또한 효율적으로 쓰여지지 못할 것이라고 판단하였다.
- 따라서 학습시간이 가장 적게 들고 Mobile Cross-Platform개발이 가능한 프레임워크인 React Native를 주요 기술스택으로 선정하였다.
- 이미 익숙한 JavaScript Library인 React를 사용하며 컴포넌트를 스타일하는 방식이 CSS가 웹에서 동작하는 방식과 흡사하다.
- 때문에 문제해결에 비교적 수월할 것이며 빠르고 정확하게 의도한 기능과 디자인을 구현할 수 있다.

## 외부 라이브러리

- React Native webRTC : 화상채팅에 사용되는 peer to peer connection을 위한 라이브러리. RTCPeerConnection에 대해 브라우저와 똑같이 동작하며 웹RTC APIs의 대부분을 지원한다.
- React Native Community/blur : 기획한 핀토앱의 채팅대기화면에서 필요한 라이브러리. 카메라 컴포넌트 위에 BlurView 컴포넌트를 한 겹 올려 블러처리된 카메라화면을 볼 수 있도록 한다.
- React Native Camera : 채팅대기화면에서 카메라를 켜기위해 필요한 라이브러리.
- React Native community/cameraroll : 사용자의 프로필사진을 설정하기 위해 유저의 로컬 사진첩에 접근가능하게 하는 라이브러리
- React Native Navigation : React Native App에 대해 Android와 IOS에서100% 네이티브 플랫폼 네비게이션을 제공한다.
- React Native Gesture Handler : React Native에서 가능한 터치, 제스쳐 관리 API를 제공하는 라이브러리
- React Native Vector Icons : 버튼 등에 사용하는 아이콘을 스타일링하고 프로젝트에 추가하기 위한 라이브러리.

## 결과물이 동작하는 OS : iOS, Android

## 데모버전이 시연될 환경

- iOS : Iphone 8 디바이스(iOS 15.1)
- Android : Android Studio Simulator(Android 11.0, API 30)
