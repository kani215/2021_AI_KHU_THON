# 2021_AI_KHU_THON
2021_2_ai hackerthon project 

# 1. 팀원명 - 우리 팀원 중에 버스 기사 있나요?

[팀원 ](https://www.notion.so/6303383d94124416a1e9bad5c55e2235)

# 2. 개발 일정

11/1 ~ 11/13

# 3. README

## #1. structure
- presentation # 프로젝트 설명 & 요약 

-src

  -output    # 모델 분석 결과 폴더 - 영상, 이미지, 분석 결과 그래프, 면접 평가 점수 나온다.

  -SaveVideo.mp4 # 촬영된 비디오 test data

  -_mini_XCEPTION.102-0.66.hdf5 # 이미지 감정 학습 모델

  -a.png # 사용 이미지

  -b.png # 사용 이미지

  -data.csv # 분석 결과 표 

  -haarcascade_frontalface_default.xml # 모델 사용 전면 인식

  -realtime_final.ipynb # 실시간 웹캠 인지 모델 

  -video_analyze_main.ipynb # 촬영된 비디오 분석 모델 

## #2. model intruction

### 2-1. realtime_final.ipynb

- 실행 시 실시간 웹캠 촬영
- 모델은 바로 작동하여 현재 얼굴 촬영 후 분석 진행

### 2-2. video_analyze_main.ipynb 

- 실행 시 프로그램 작동 시작
- REC 버튼 클릭 시 지금 모습을 실시간 녹화
- ESC키 로 녹화 종료
- 녹화 종료 후 , 저장된 동영상이 있다면 분석 진행
- 표 그래프 분석 완료 동영상이 output 폴더에 자동 업로드

# 4. 구현 및 시현 test

- [https://youtu.be/AoDKj5wpGWs](https://youtu.be/AoDKj5wpGWs)
- 
# 5. 참고 문헌 링크

- cv2 실시간 촬영 바로 저장

https://deep-learning-study.tistory.com/108

- flask 실시간 웹캠 촬영 서버 만들기OpenCV를 사용하여 웹캠에서 얼굴 감지를 구현하고 Flask를 사용하여 웹 애플리케이션에서 구현하는 방법의 예를 보여줍니다

https://towardsdatascience.com/how-to-display-video-streaming-from-a-webcam-using-flask-7a15e26fbab8

[SeoJinHyuk14/facialExpression: 머신러닝을 이용한 얼굴인식 및 표정분류 (github.com)](https://github.com/SeoJinHyuk14/facialExpression)- 얼굴인식, 표정분류(실시간은 불분명), 플라스크를 활용한 웹서버 구현 방식 참고?

- 영상데이터가 있을 때 감정 표현 제시 코드

[https://towardsdatascience.com/the-ultimate-guide-to-emotion-recognition-from-facial-expressions-using-python-64e58d4324ff](https://towardsdatascience.com/the-ultimate-guide-to-emotion-recognition-from-facial-expressions-using-python-64e58d4324ff)

- 

[Real-time Age, Gender and Emotion Prediction from Webcam with Keras and OpenCV | by Sun Weiran | Towards Data Science](https://towardsdatascience.com/real-time-age-gender-and-emotion-prediction-from-webcam-with-keras-and-opencv-bde6220d60a)

- 동영상 분석

[https://itsourcecode.com/free-projects/python-projects/real-time-emotion-detection-opencv-python-with-source-code/](https://itsourcecode.com/free-projects/python-projects/real-time-emotion-detection-opencv-python-with-source-code/)

[한국인 감정인식을 위한 복합 영상 | AI 허브 (aihub.or.kr)](https://aihub.or.kr/aidata/27716) - AI 모델까지 존재

- 구글 27개 감정인식

[https://www.aitimes.kr/news/articleView.html?idxno=22937](https://www.aitimes.kr/news/articleView.html?idxno=22937)

- 오바마 실시간으로 웹캠 영상을 받아 감정 인식 분류까지(예시 화면)

[https://github.com/vjgpt/Face-and-Emotion-Recognition](https://github.com/vjgpt/Face-and-Emotion-Recognition)

- 감정인식분류,눈깜박임

https://github.com/coconutstd/video-chat-solution#%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5-%EA%B8%B0%EC%88%A0%EC%9D%84-%ED%86%B5%ED%95%9C-%EC%96%BC%EA%B5%B4-%EA%B0%90%EC%A0%95%EB%B6%84%EC%84%9D-%EB%B0%8F-%EB%88%88-%EA%B9%9C%EB%B9%A1%EC%9E%84-%EB%B6%84%EC%84%9D

- 동영상올리기 방법

[https://studyforus.tistory.com/98](https://studyforus.tistory.com/98)

[GitHub - omar178/Emotion-recognition: Real time emotion recognition](https://github.com/omar178/Emotion-recognition)
