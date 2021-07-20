# SNU Bigdata Fintech Program

**서울대학교 4차산업혁명 아카데미 - 빅데이터 핀테크 전문가 양성 과정** (2020. 12 – 2021. 7)

빅데이터 핀테크 과정을 수료하면서 진행한 팀 프로젝트를 모아놓은 Repository 입니다. 프로젝트에 대한 자세한 설명과 전체 코드는 연결된 링크를 통해서 확인할 수 있습니다. 모든 프로젝트는 파이썬의 쥬피터노트북을 활용하여 작성되었습니다. 몇몇 프로젝트에서 데이터의 용량 문제 혹은 공개 불가능 문제로 자료의 데이터가 누락된 경우가 있습니다. 프로젝트 내용과 관련된 문의는 yesorno36@gmail.com 으로 해주시면 감사하겠습니다.



**Seoul National University AI Institute - Bigdata Fintech Program** (2020. 12 – 2021. 7)

This is a repository of team projects that I worked on while completing the Bigdata Fintech course. Click on the projects to see full analysis and code. All the projects are created in Python using Jupyter Notebooks. There may be missing data because the data exceeded the file size limit or the data cannot be public in some projects. Feel free to contact me at yesorno36@gmail.com if you have any questions.

<br>

## &#128176; Lending Club

- [Notebook](https://github.com/cgvvxx/SNU_Bigdata_Fintech/tree/master/Lending_Club) / [PDF](https://github.com/cgvvxx/SNU_Bigdata_Fintech/blob/master/Lending_Club/Lending_Club.pdf)
- Lending Club에서 제공하는 대출에 대한 전체 자료와 대출 현황 및 최근 지급 정보 등에 대한 데이터를 이용하여 Lending Club 사용자의 원금 상환 여부를 예측하였습니다. 부도 예측 실패로 인한 Lending Club의 비용을 최소화할 수 있는 예측 모형을 LPM, Logistic, Probit을 이용하여 구현하였습니다.
- We use the entire data on the loan provided by the Lending Club, the status of the loan, and the latest payment information. We predicted whether the users of the Lending Club will repay. We developed a prediction model that can minimize the cost of the Lending Club due to the failure of predicting bankruptcy using LPM, Logistic, and Probit model.

## &#128081; Psychological Propensity Prediction

- [Source](https://dacon.io/competitions/official/235647/overview/description) / [Notebook](https://github.com/cgvvxx/SNU_Bigdata_Fintech/tree/master/Psychological_Propensity_Prediction) / [PDF](https://github.com/cgvvxx/SNU_Bigdata_Fintech/blob/master/Psychological_Propensity_Prediction/Psychological_Propensity_Prediction.pdf)

- Dacon의 심리 성향 예측 AI 경진대회에서 제공하는 데이터를 이용하여 심리테스트를 활용한 국가 선거 투표 여부를 예측하였습니다. Ridge, Lasso부터 Random Forest, Adaboost, XGBoost 등의 다양한 ML 모델들의 성능 비교 분석을 하였고 최종적으로 앙상블을 통한 최종 모델을 구현하였습니다.
- We use the data provided by Dacon's psychological propensity prediction AI competition. And we predict whether or not to vote in national elections using psychological tests. We did a performance comparative analysis of various ML models, from Ridge, Lasso, Random Forest, Adaboost, and XGBoost, and eventually implemented the final model through an ensemble.

## &#127971; Chest X-Ray

- [Source](https://www.kaggle.com/prashant268/chest-xray-covid19-pneumonia) / [Notebook](https://github.com/cgvvxx/SNU_Bigdata_Fintech/tree/master/Chest_X-ray) / [PDF](https://github.com/cgvvxx/SNU_Bigdata_Fintech/blob/master/Chest_X-ray/Chest_X-ray.pdf)

- Kaggle에서 제공하는 흉부 X-ray 사진을 이용하여 환자가 질병을 가지고 있는지(코로나-19, 폐렴) 혹은 정상인지 여부를 예측하였습니다. Tensorflow를 활용하였고 VGGNet, ResNet, AlexNet 등의 CNN 모델들의 앙상블을 통해 최종 모델을 구현하였습니다. 또한 LIME을 활용하여 최종 모델의 결과에 대한 해석 가능한 설명력을 살펴보았습니다.
- Using the chest X-ray photographs provided by Kaggle, we predicted whether the patient had a disease (Corona-19, pneumonia) or was normal. We leveraged Tensorflow and implemented the final model through an ensemble of CNN models such as VGGNet, ResNet, and AlexNet. We also looked at the interpretable explanation of the results of the final model using LIME.

## &#128218; Font Style Transfer

- [Link](https://github.com/cgvvxx/Font_Style_Transfer)

- GAN을 활용한 다양한 형태를 가진, 양질의 글꼴 데이터를 생성하는 글꼴 이미지 생성 모델을 개발하였습니다.  Font Style Transfer에 대한 자세한 설명은 위 링크의 github repository를 통해 확인할 수 있습니다.
- We developed a font image generation model that generates font of quality with various forms using GAN model. A detailed description of Font Style Transfer can be found in the github repository above.

