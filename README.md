# gpt_fine-tuning

***
## GPT3.5 Turbo ChatGPT Fine Tuning 장점
* 프롬프트처리 보다 더 높은 품질의 결과
* 프롬프트에 넣는 것보다 더 많은 데이터를 학습할 수 있는 능력
* 짧은 프롬프트로 인한 토큰 절약
* 대기 시간 단축 요청
***
GPT-3는 인터넷의 방대한 양의 텍스트로 사전 훈련되어있다. 몇 가지 몌제만 제공하면 GPT-3는 종종 어떤 작업을 수행하려고 하는지 직관적으로 파악하고 타당한 완성을 생성할 수 있다. 이를 종종 few-shot learning이라고 한다.
파인 튜닝은 프로프트에 맞지 않는 예제를 포함한 훨씬 많은 예제로 학습함으로써 다양한 작업에서 더 나은 결과를 얻을 수 있다. 모델을 파인튜닝한 후에는 더 이상 프롬프트에서 예제를 제공할 필요가 없다. 이로써 비용을 절감하고 지연시간이 낮은 요청을 가능하게 한다.

***
## 처리 단계
1. 훈련 데이터 준비 및 업로드
2. 새로운 파인튜닝 모델 훈련
3. 파인튜닝한 모델 사용

***
> # 실질적인 파인튜닝 비용
> 실질적으로 파인튜닝 비용은 일반적으로 훈련 epochs 수로 인해 훈련에 사용되는 토큰의 4배가 측정이 된다.
>   > 훈련 토큰의 수는 훈련 데이터셋의 토큰 수와 선택한 훈련 epochs 수에 따라 달라진다.
>   > 
>   > 기본 epochs 수는 4이다.
>   > 
>   > (훈련 파인의 토큰 수 * 훈련 epochs 수) = 총 훈련 토큰
