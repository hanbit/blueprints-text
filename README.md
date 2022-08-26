# 파이썬 라이브러리를 활용한 텍스트 분석

## 텍스트에서 통찰을 이끌어내는 98가지 자연어 처리 전략

-----------------------------------------------------------------------------------

## 오류 신고
코드에서 오류를 발견한다면 저자들의 깃허브에서 [이슈를 남겨주세요](https://github.com/blueprints-for-text-analytics-python/blueprints-text/issues).

**스페이시 3.0과 젠심 4.0**
이 도서의 코드는 스페이시(spaCy) 2.3.2과 젠심(gensim) 3.8.3을 기준으로 작성되어 있습니다. 하지만 현재 스페이시는 3.0이 릴리즈 되었으며 이에 따라 API도 변화되었습니다. 저자들 또한 실습 코드를 스페이시 3.0에 맞춰 업데이트 했습니다. 하지만 textacy는 스페이시 3.0을 지원하지 않으므로 저자들이 수정을 가한 파일을 제공하고 있습니다.

## 노트북 실행법

각 노트북은 세 가지 링크를 제공합니다.
  * "git" 링크는 깃허브에서 노트북을 확인합니다.
  * "nbviewer" 링크는 nbviewer.ipython.org에서 노트북을 확인합니다.
  * "colab" 링크는 구글 콜랩에서 노트북을 확인합니다(**저자들은 콜랩 사용을 권장합니다)**.

If you run the notebook locally or on Colab, you can execute each cell separately by hitting "Shift-enter". Do not skip cells and don't forget to run the first code cells for the setup.

  * **1장 텍스트 데이터에서 찾는 통찰**
  [[git](ch01/First_Insights.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch01/First_Insights.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch01/First_Insights.ipynb)]
  * **2장 API로 추출하는 텍스트 속 통찰**
  [[git](ch02/API_Data_Extraction.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch02/API_Data_Extraction.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch02/API_Data_Extraction.ipynb)]
  * **3장 웹사이트 스크래핑 및 데이터 추출**
  [[git](ch03/Scraping_Extraction.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch03/Scraping_Extraction.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch03/Scraping_Extraction.ipynb)]
  * **4장 통계 및 머신러닝을 위한 텍스트 데이터 준비**
  [[git](ch04/Data_Preparation.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch04/Data_Preparation.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch04/Data_Preparation.ipynb)]
  * **5장 특성 엔지니어링 및 구문 유사성**
  [[git](ch05/Feature_Engineering_Similarity.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch05/Feature_Engineering_Similarity.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch05/Feature_Engineering_Similarity.ipynb)]
  * **6장 텍스트 분류 알고리즘**
  [[git](ch06/Text_Classification.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch06/Text_Classification.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch06/Text_Classification.ipynb)]
  * **7장 텍스트 분류기**
  [[git](ch07/Explainable_AI.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch07/Explainable_AI.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch07/Explainable_AI.ipynb)]
  * **8장 비지도 학습: 토픽 모델링 및 클러스터링**
  [[git](ch08/Topic_Modeling_Clustering.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch08/Topic_Modeling_Clustering.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch08/Topic_Modeling_Clustering.ipynb)]
  * **9장 텍스트 요약**
  [[git](ch09/Text_Summarization.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch09/Text_Summarization.ipynb)]
  [[Colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch09/Text_Summarization.ipynb)]
  * **10장 단어 임베딩으로 의미 관계 탐색**
  [[git](ch10/Embeddings.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch10/Embeddings.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch10/Embeddings.ipynb)]
  * **11장 텍스트 데이터를 이용한 감성 분석**
  [[git](ch11/Sentiment_Analysis.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch11/Sentiment_Analysis.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch11/Sentiment_Analysis.ipynb)]
  * **12장 지식 그래프 구축**
  [[git](ch12/Knowledge_Graph.ipynb)]
  [[nbviewer](https://nbviewer.ipython.org/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch12/Knowledge_Graph.ipynb)]
  [[colab](https://colab.research.google.com/github/blueprints-for-text-analytics-python/blueprints-text/blob/master/ch12/Knowledge_Graph.ipynb)]
  * **13장 프로덕션에서 텍스트 분석 사용**
  [[git](ch13/)]
  [[app](https://github.com/blueprints-for-text-analytics-python/sentiment-app)]


## 로컬 환경 설정법

`git clone` 명령어를 사용해 저장소를 내려받습니다.
```sh
git clone https://github.com/blueprints-for-text-analytics-python/blueprints-text.git
cd blueprints-text
```

로컬 환경을 구성하기 위해 [Miniconda](https://docs.conda.io/en/latest/miniconda.html)를 추천합니다. [Miniconda 공식 홈페이지](https://docs.conda.io/en/latest/miniconda.html)에서 제공하는 설치 방법을 따라 Miniconda를 설치합니다.

Miniconda의 설치를 마쳤다면 프로젝트 디렉터리에서 아래 명령어를 실행합니다.

```sh
conda env create --name blueprints --file blueprints.yml
conda activate blueprints
```

환경이 실행되면 프롬프트에 `blueprints` 라는 문구가 출력됩니다. 환경 설정 파일에 추가되어있는 주피터 노트북용 확장기능들을 활성화합니다.

```sh
jupyter nbextension enable toc2/main
jupyter nbextension enable execute_time/ExecuteTime
jupyter nbextension enable varInspector/main
```

이제 주피터 노트북 서버를 실행합니다.

```sh
jupyter notebook
```

만약 WSL 환경이라면 `--no-browser` 옵션을 추가하세요.

이제 각 장마다 있는 `.ipynb`를 열어 노트북을 확인합니다.
