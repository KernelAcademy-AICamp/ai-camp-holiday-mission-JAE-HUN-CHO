# 미션 1: 야놀자 리뷰 요약

## 📌 미션 정보

- **날짜**: 2025.10.03 (금)
- **학습 범위**: Part4 - 야놀자 리뷰 요약
- **제출 기한**: 2025.10.03 23:59

---

## 🎯 학습 목표

이 미션에서는 야놀자 숙박 리뷰 데이터를 활용하여 리뷰를 요약하는 AI 서비스를 개발합니다.

### 주요 학습 내용
- LLM을 활용한 텍스트 요약
- 프롬프트 엔지니어링 기초
- 리뷰 데이터 전처리 및 분석

---

## 📝 실습 내용

### 구현 기능
- [x] 야놀자 리뷰 데이터 수집/로드
- [x] 리뷰 데이터 전처리
- [x] LLM을 활용한 리뷰 요약
- [x] 요약 결과 평가

### 사용 기술
- Python
- OpenAI API / LangChain
- Jupyter Notebook

---

## 💻 실행 방법

```bash
# 필요한 패키지 설치
pip install -r requirements.txt

# Jupyter Notebook 실행
jupyter notebook

# 또는 Python 파일 실행
python main.py
```

---

## 📊 실행 결과

> 이곳에 실행 결과 스크린샷이나 출력 내용을 추가하세요

| Method           | Wins | Losses | Ties |
| ---------------- | ---- | ------ | ---- |
| baseline         | 7    | 3      | 0    |
| improving_prompt | 5    | 4      | 0    |
| improving_data   | 9    | 1      | 0    |
| one_shot         | 7    | 3      | 0    |
| two_shot         | 3    | 7      | 0    |

- baseline : 기초적인 prompt 사용
- imrpoving_prompt : prompt 고도화
- improving_data : prompt 고도화 + 데이터 품질 강화
- one_host : one_shot + baseline
- two_shot : two_shot + baseline

---

## 🤔 학습 내용 정리



### 배운 점
- OpenAI를 활용하는 새로운 방법 습득

- LLM 성능 평가 방법 이해 및 실습

- 프롬프트 수정·고도화가 성능 향상에 중요한 요소 재확인

### 어려웠던 점
- 평가 방법 설정과 적용 방식이 궁금했음


### 개선하고 싶은 점
- 리뷰 데이터가 3개로 제한 → 데이터 확장 필요

- 긍정적 리뷰만 사용 → 낮은 평점 리뷰도 포함 필요

- 상업적 이용 가능한 데이터 소스 진행 고려
---

## 📚 참고 자료

- [온라인 강의 링크](https://fastcampus.co.kr/data_online_llmservice)
- [관련 문서](https://github.com/rein20/ai-service/tree/main)

---

**작성자**: [조재훈]  
**작성일**: 2025.10.03

