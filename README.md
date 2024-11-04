# Programming Project #1. Classification Problem / AI Programming
Kaggle URL :  https://www.kaggle.com/competitions/titanic/data

주제

Kaggle Titanic 문제를 이용해서 분류를 수행한다. 

      Kaggle URL :  https://www.kaggle.com/competitions/titanic/data

 

목표

아래와 같이 4가지 목표를 가지고 프로젝트를 수행한다.

데이터 전처리 방법을 익힌다.

여러개의 분류방법을 수행해 본다.

Confusion matrix를 통해 결과를 분석할 수 있다.

성능 개선을 할 수 있다.

Colab으로 수행하는 것을 기본으로 하지만, 어떤 환경에서 프로그램이 수행되어도 괜찮다.

 

세부 수행 과제

데이터 전처리

데이터는 kaggle에서 주어지는 train.csv와 test.csv를 이용한다.(첨부파일)

train.csv를 8:2 로 나누어 8은 training, 2는 validation으로 사용하며, validation 을 이용하여 모델의 성능을 측정한다.
전처리가 필요한 부분은 ‘결측치’와 ‘범주형데이터’의 처리이다. ‘결측치’는 중간값으로 채우고, 범주형은 LabelEncoder를 이용하여 변경한다.

전처리 전후를 비교하여 어떻게 변경되는지 예제를 통해 확인한다.

분류 수행

분류를 수행할 알고리즘은 아래와 같다.

Decision Tree

Support Vector Machine

Random Forest

Logistic Regression

각각을 수행하여 성능을 비교한다.

각 분류 알고리즘의 성능 비교 분석

성능은 Confusion matrix를 이용하여, accuracy, precision, recall, F1-score로 한다.

각 값을 비교하여 보고, 어떤 알고리즘이 성능이 좋은지 평가한다.

성능 개선 시도

위에서 사용한 4개의 알고리즘중에 조정이 가능한 것들이 있다면 조정하여 성능을 향상시키고, 어떤 이유에서 성능이 향상되었는지 이유를 보고한다.

 

제출 

제출 할 것은 아래와 같이 두 가지이며, 각 항목을 포함한다.

소스코드

소스코드는 실험에 사용한 코드와 그 결과를 제출한다. ( 조교의 설명에 따라)

소스코드는 4개의 서로다른 코드여도 되며, 위의 방법을 모두 하나의 코드에 담은 1개의 코드여도 좋다. 1개의 코드에 담은 것에 가산점을 줄 수 있다.

보고서

전처리를 어떻게 수행하였는지와 필요한 이유를 포함한다.

각 알고리즘의 성능을 비교할 수 있는 하나의 표를 포함한다.

그 표를 이용하여 어떤 알고리즘이 왜 우수한지 혹은 열등한지 설명한다.

각 알고리즘의 성능을 개선하려는 시도가 있었다면, 어떻게 하였는지 설명하고 어떤 이유로 개선을 가져온 것인지 설명한다. 이 항목에는 가산점이 있을 수 있다. ( Ex. SVM의 hyper parameter를 수정하여 성능 개선 등)

 

제출은 e-class를 통해서 하되, 조교의 설명을 따른다.

 

기타 

 

코드 작성 및 기타 여러 부분에서 LLM의 도움을 받아도 좋다. 다만, LLM을 사용한 부분에 대하여 사용하였음을 간략히 기록하도록 한다. LLM을 사용한 부분에 대해서는 감점이 존재하지 않는다. 

다른 학생과 제출한 것이 상당하게 같은 경우 copy로 판정하며 감점 등의 penalty가 존재한다.

(필요한 경우) Decision Tree를 수행하는 예제 코드를 제공할 수 있다.
제출기한은 11월 19일 (목) 자정으로 한다. 





Project for 24-2 AI Programming Assignment
2024 HUFS Global Campus

24-2 AI 프로그래밍 과제를 위한 프로젝트입니다.
2024 한국외국어대학교 글로벌캠퍼스
