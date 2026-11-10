# HUFS 대학원 딥러닝 · 실데이터 실습 노트북

한국외국어대학교 국제경영학과 대학원 딥러닝 세미나 실습 시리즈의 Colab 노트북.
강의 페이지: https://hufs-ai-lecture.pages.dev/practice/

| 회차 | 노트북 | Colab |
|---|---|---|
| 1 시계열 — 예측과 역 군집 | `notebooks/01_timeseries.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/notebooks/01_timeseries.ipynb) |
| 2 텍스트 — 임베딩·제로샷·군집 | `notebooks/02_text.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/notebooks/02_text.ipynb) |
| 3 이미지·멀티모달 | `notebooks/03_image_multimodal.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/notebooks/03_image_multimodal.ipynb) |
| 4 인과추론 실습 | `notebooks/04_causal.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/notebooks/04_causal.ipynb) |

각 노트북은 ① 데이터 로드 셀만 바꾸면 자기 데이터에 그대로 돈다. 텍스트·이미지 회차는 Cloudflare Workers AI 무료 계정의 API 토큰이 필요하다(노트북 첫 셀에서 입력).
데이터: 서울 지하철 일별 총승차(`data/subway_daily_total.csv`, 서울 열린데이터광장 OA-12914 를 일 단위로 합산). 나머지 데이터는 노트북이 공개 URL 에서 직접 받는다.

## 학부 「인공지능」 보너스 실습

| 실습 | 노트북 | Colab |
|---|---|---|
| 1회차 · 낙서 맞히기 AI (Quick, Draw! CNN · 그림판 게임 · 데이터 증강 · 확산 모델) | `undergrad/lab07b_doodle.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/undergrad/lab07b_doodle.ipynb) |
| 2회차 · AI 그림 공방 (낙서→작품 · AI 전화 게임 · 조건부 확산과 가이던스, Cloudflare Workers AI 무료 토큰 필요) | `undergrad/lab07c_studio.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/undergrad/lab07c_studio.ipynb) |
| RNN · 한 단어씩 읽는 감성 AI (NSMC 감성 분류 · RNN 대 LSTM · 단어별 판단 변화 · AI 리뷰 작가) | `undergrad/lab07d_sentiment.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juho127/hufs-dl-practice/blob/main/undergrad/lab07d_sentiment.ipynb) |

안내 페이지: https://hufs-ai-lecture.pages.dev/ai/doodle · 데이터: Google Quick, Draw! Dataset (CC BY 4.0), 노트북이 카테고리별 앞부분 6,000장만 직접 받는다.
