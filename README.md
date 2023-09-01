# **"빅데이터를 활용한 중소형 외감기업 부실 예측 및 부실지수 제언"**
<br>



# **프로젝트 개요**
- 외감기업을 상장기업, 비상장기업으로 나누어 부실예측 모형을 만든다.
  - 전통적 통계기법, 머신러닝, 딥러닝을 다양하게 활용하여 모델링을 수행한다.
  - 사용한 분석 기법
    : Naive Bayes, Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, SVM, DNN, TabNet, Stacking
- 도출된 Feature 들을 바탕으로 사전적인 부실 지수를 산출한다.



# **목적**
- 상장기업의 부실 예측 및 등급화를 통해 주주들에게 기업에 대한 정보를 제공하고자 한다.
  - 기존에 제공되는 기업 등급들은 기업들의 채권 상환능력을 평가한 등급이기 때문에 주식 투자자들이 얻을 수 있는 기업 정보를 제공한다.
- 비상장 외감기업의 부실 예측 및 등급화를 통해 기업에게 투자를 진행하려고 하는 투자자들과 은행에게 기업 부실에 대한 위험도를 알린다.
  - 많은 은행들의 주 고객이지만, 상대적으로 분석이 많이 이루어지지 않고 있는 비상장 기업에 대한 분석을 통해 새로운 분석 시각을 제공한다.
- 기존의 기업 신용평가 등급은 신용 사건이 발생했을 때 주로 갱신되는 사후적 확률이므로, 본 분석을 통해 투자자에게 사전적인 정보를 제공하고자 한다.
  - 부실 발생 직전 년도를 Target 으로 설정하여 최초 시점의 부실을 예측하는 모델로, 사전적인 부실 탐지 모형이다.


---
# **PPT**
![image](https://github.com/iamtaewon/Project_2/assets/127276976/9727bdb1-3500-4116-8a6c-c024cedca17e)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/f8a7b64e-e315-4582-9831-329172c44160)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/adc6c3d8-937e-4dda-ba88-71868e0ab19c)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/4ac00091-b16b-4838-8396-f209d0dc3f64)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/274fcd71-354c-458d-ae1a-5a34047de2ec)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/7c7db948-8f04-4a35-84a5-a5f0825b2a81)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/c8ba415d-c431-440a-a0ba-2d24353d6621)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/72225a09-507b-4eb4-bbff-5d026b1eef02)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/c9c5b431-a9c7-49c0-acbc-e574703d47fd)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/2b41c4fb-4559-4b14-af9d-dc0fb5e6031d)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/a4d8ced9-e291-4834-874a-225549ffb9d0)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/74b09d46-061f-4b00-91cb-0053d8dcf9e2)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/b53d295f-90fc-4a3a-bba6-5f16aff5f35d)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/7c066b3a-0dee-4d48-8454-b5cfbda815dd)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/facaa6a0-8326-413d-b3ba-05329b1b7eb5)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/1dd51806-a88f-40e1-a497-00297e8cf311)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/c20af279-8f4e-4b49-8675-42cf93d882dc)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/e2faab5f-279c-4dc1-b73a-46552f148c69)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/a8c02763-d142-43ce-951c-6ca9a849551e)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/95005463-ebfe-4f18-9f2d-7b5ca48eb52b)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/1d353cf4-ec04-4ce3-9168-514687069b6a)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/f6068a95-4e64-46e5-afe7-7f49f16358da)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/2b5ff0f0-e4d0-4f89-b35a-445076ee59f4)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/f80e46f3-9d8b-4695-ad73-7a49e54e2964)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/5db266da-5309-4d6a-81ac-c1fc6efef108)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/617622a6-f905-44cd-aff8-5465b7dbd5a8)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/625f3864-da4b-4071-8cdb-4dfaf04b9fca)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/d9856b03-5760-4a14-8017-571aa5f0ed61)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/67209360-6bad-47ec-a8fc-d6c8967f7e00)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/84947598-6fb0-4ca8-8f12-a7ca40d94398)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/ce862775-09ec-4db8-8603-debf7f34e638)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/c0958d8a-6255-4886-b262-25b11de3881a)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/50c6418f-2455-4f56-8551-4f7368633c08)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/278f4326-342f-41f2-b977-449d5e36dbc0)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/189b86bc-39f5-4b1f-bc07-da561f12652c)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/1efd207f-f343-4123-91a2-66adde0213ef)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/eefe2f6c-1614-4e62-8f3e-2b782192886c)
![image](https://github.com/iamtaewon/Project_2/assets/127276976/895e148c-6f22-4779-b7af-202fabe63959)

