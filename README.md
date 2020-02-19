# Tello-Python





## Introduction

파이썬 기반 **Tello** 제어 샘플 코드 모음



## Project Description

이 툴킷( Toolkit )에는 **tello sdk** 와 **python2.7** 을 기반으로하는 `Single_Tello_Test`, `Tello_Video` 및 `Tello_Video_With _Pose_Recognition` 을 포함한 세 가지 샘플 코드와 **Tello** 의 여러가지 상태값을 모니터링 할 수 있는  `tello_state.py` 코드가 포함되어있다.



- **Single_Tello_Test**

`Single_Tello_Test` 는 **txt** 스크립트를 작성하여 **Tello** 가 미리 만들어 둔 순서의 작업을 실행할 수 있는 명령 시퀀스를 만들 수 있다.



- **Tello_Video**

`Tello_Video` 는, **Tello** 로부터 비디오 스트림 데이터를 수신, **h264** 디코딩 라이브러리를 이용한 비디오를 디코딩,   **Tkinter** 및 **PIL** 기반 GUI 인터페이스를 이용한 디코딩된 비디오의 디스플레이와  **Tello** 를 조작 할 수있는 제어판 예제를 제공한다.  즉, 비디오 데이터를 수신 및 처리하고 가져 오는 샘플코드이다. ( 레퍼런스로 사용할 수 있는 **h264** 디코딩 라이브러리의 소스 코드 또한 패키지로 제공된다. )



- **Tello_Video_With_Pose_Recognition**

 `Tello_Video_With_Pose_Recognition` 은 앞의  `Tello_Video` 의 응용 버전으로, **Tello_Video** 를 기본으로 만들어졌다.   `Tello_Video_With_Pose_Recognition` 은 디코딩된 비디오 데이터에서 단일 프레임 이미지를 추출하여, **pose** 를 인식하고 인식된 **pose** 에 할당된 제어명령을 수행하여, 결과적으로 **pose** 나 **gesture** 를 이용하여 드론을 제어하는 영상 데이터 활용 샘플 코드이다.



- **tello_state.py**

 `tello_state.py` 는 **Tello** 의 여러가지 상태 데이터를 읽을 수 있는 샘플 코드이다. **Tello** 의 상태를 모니터링하거나, 제어코드를 디버깅하는 툴로도 충분히 사용가능하다.



## Environmental configuration

* 이상의 샘플 코드들은 **python 2.7** 을 기반으로 작성되었다. 
* `Single_Tello_Test` 및 `tello_state.py` 의 실행을 위해선 추가 라이브러리가 필요가 없다.
* `Tello_Video` 및 `Tello_Video_With_Pose_Recognition` 의 경우 추가 라이브러리가 필요하다. 
* 제공되는 각 폴더에 있는 원 클릭 설치 스크립트( Windows32 / 64, Linux, Mac OS )를 이용하여 필요한 추가 라이브러리들을 쉽게 설치할 수 있다.
* 세부 사항은 각 패키지 폴더의 readme 파일을 참조한다.
* [**64bit 윈도우 환경에서의 환경설정**](./0_how2config/how2config.md)



## Contact Information

이 샘플 코드 및 설치에 대한 질문이 있으면 sdk@ryzerobotics.com 로 문의 바랍니다.

최근 새로운 **FAQ** 문서를 `Tello-Python` 에 업로드하였으니, 의문점이 생길 경우, 먼저 이 **FAQ** 내용을 확인하기 바랍니다.





## About Multi-Tello-Formation

**Tello** 를 이용한 편대비행에 대한 사항은 github repository https://github.com/TelloSDK/Multi-Tello-Formation.
의 정보를 참고하시오.



------



