# 토론부기 - AI 토론 수업 도우미 🦉

경기 토론 수업 모형을 기반으로 한 초등학교 6학년 학생들을 위한 AI 토론 수업 지원 도구입니다.

## 주요 기능

- **토론 주제 추천**: 학생들의 관심사에 맞는 토론 주제를 추천해 드립니다.
- **찬반 논거 아이디어**: 선택한 주제에 대한 찬성/반대 의견을 제시합니다.
- **경기 토론 수업 모형 안내**: 토론을 진행하는 3단계 방법을 친절하게 안내합니다.
- **의견 피드백**: 학생들이 작성한 의견에 대한 피드백을 제공합니다.
- **토론 마무리**: 다양한 의견을 모아 공동의 해결책을 찾는 활동을 지원합니다.

## 설치 방법

1. 저장소를 클론합니다.
```
git clone https://github.com/reallygood83/aidebate.git
cd aidebate
```

2. 필요한 패키지를 설치합니다.
```
pip install -r requirements.txt
```

3. Google AI Studio에서 Gemini API 키를 발급받습니다.
   - [Google AI Studio](https://aistudio.google.com/) 방문
   - API 키 발급 후 `.streamlit/secrets.toml` 파일에 저장
   ```
   GEMINI_API_KEY = "발급받은 API 키"
   ```

## 실행 방법

```
streamlit run app.py
```

## 사용 방법

1. 토론 주제 추천 기능을 통해 관심 주제를 입력하고 토론 주제를 얻습니다.
2. 선택한 주제에 대한 찬반 논거를 확인합니다.
3. 경기 토론 수업 모형의 3단계(다름과 마주하기, 다름을 이해하기, 다름과 공존하기)를 참고하여 토론을 진행합니다.
4. 자신의 의견을 작성하고 피드백을 받습니다.
5. 토론 마무리 활동을 통해 다양한 의견을 통합하고 공동의 해결책을 찾습니다.

## 개발자

© 2024 안양 박달초 김문정 | [유튜브 배움의 달인](https://www.youtube.com/@%EB%B0%B0%EC%9B%80%EC%9D%98%EB%8B%AC%EC%9D%B8-p5v/videos)

## 라이선스

MIT License
