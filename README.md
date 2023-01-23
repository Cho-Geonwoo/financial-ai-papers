# Finance-related papers from various AI conferences 세 줄 요약

> Query: Finance, Investment, Trading, Pricing, Valuation, Time Series, Time-series

## AAAI '22

- CATN: Cross Attentive Tree-Aware Network for Multivariate Time Series Forecasting ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20320))
  - Inter-series correlation과 intra-series temporal pattern을 학습하는 모델(CATN)을 제안함
  - Hierarchical grouped correlation을 학습하는 tree structure과 generalized implicit cross feature을 위한 embedding을 제안함
  - Long-range, short-range, cross dependencies를 모두 활용하는 multi-level dependency learning mechanism을 제안함
- Clustering Interval-Censored Time-Series for Disease Phenotyping ([paper](https://arxiv.org/abs/2102.07005))
  - Noise 종류에 따라 time seires pattern이 다르게 찾아질 수 있음
  - Disease phenotyping clustering 시 censorship time에 데이터를 수정하는 generative 모델을 제안함
- Conditional Loss and Deep Euler Scheme for Time Series Generation ([paper](https://arxiv.org/abs/2102.05313))
  - SDEs의 Euler discretization과 Wasserstein distance를 이용한 두 가지 GANs-based 모델을 소개함
  - Transition probability distribution 간 거리를 최소화하는 모델(CEGEN)을 제안함
- Co-promotion Predictions of Financing Market and Sales Market: A Cooperative-Competitive Attention Approach ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20888))
  - 기존 popularity prediction은 isolated market을 가정함
  - Financing market과 sales market의 interaction을 학습하는 모델(CATN)을 제안함
  - 두 시장을 연결하는 cooperative attention과 각 시장에서 item 간 관계를 계산하는 competitive attention을 제안함
- FactorVAE: A Probabilistic Dynamic Factor Model Based on Variational Autoencoder for Predicting Cross-Sectional Stock Returns ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20369))
  - Financial data의 S/N이 낮아 기존 linear factor model에서 벗어나기 어려움
  - VAE로 dynamic factor model을 학습하는 모델(FactorVAE)을 제안함
  - Return prediction과 함께 VAE latent space의 variance도 추정함
- Forecasting Asset Dependencies to Reduce Portfolio Risk ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20361))
  - Pariwise asset dependency를 측정하는 메트릭(ADM)의 sequence를 video로 간주하는 모델(ADNN)을 제안함
- I-SEA: Importance Sampling and Expected Alignment-Based Deep Distance Metric Learning for Time Series Analysis and Embedding ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20776))
  - 기존 time-series similarity measures는 distance metric로 적합하지 않음
  - MC-based expectation evaluation을 통한 distance estimates는 distribution의 high-dimensionality와 sampling inability로 인해 문제가 발생함
  - Importance sampling과 non-parametric density estimation을 사용하는 메트릭(I-SEA)을 제안함
- NumHTML: Numeric-Oriented Hierarchical Transformer Model for Multi-Task Financial Forecasting ([paper](https://arxiv.org/abs/2201.01770))
  - Financial unstructured data에 적용하는 기존 DL-based method는 숫자를 plain-text token으로 간주함
  - 숫자의 category와 magnitude를 활용하여 unstructured data를 stock return prediction에 적용하는 모델(NumHTML)을 제안함 (어닝콜)
- Reinforcement Learning Based Dynamic Model Combination for Time Series Forecasting ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/20618))
  - Ensemble learning 시 model weights를 결정하는 게 어려움
  - Non-stationary time series의 forecasting model selection을 sequential decision-making problem으로 간주하는 프레임워크(RLMC)를 제안함
  - DL을 이용하여 raw time series의 hidden feature를 학습할 수 있음
- Towards a Rigorous Evaluation of Time-Series Anomaly Detection ([paper](https://arxiv.org/abs/2109.05257))
  - 기존 time series anomaly detection에서 사용하는 point adjustment가 detection performance를 과대평가함을 보임
- Training Robust Deep Models for Time-Series Domain: Novel Algorithms and Theoretical Analysis ([paper](https://arxiv.org/abs/2207.04305))
  - Input time series에 perturbation을 넣어 parameter의 robustness를 평가하는 프레임워크(ROTS)를 제안함
  - Global alignment kernel based distance의 이동평균을 근사하여 min-max optimization을 수행하는 알고리즘(SCAGDA)을 제안함
- TS2Vec: Towards Universal Representation of Time Series ([paper](https://arxiv.org/abs/2106.10466))
  - Augmented context에 대한 hierarchical contrastive learning을 통해 time series의 representation을 학습하는 프레임워크(TS2Vec)를 제안함
  - Simple aggregation을 통해 sub-sequence의 representation을 찾을 수 있음
