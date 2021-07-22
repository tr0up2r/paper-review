# ABSTRACT
언어적 수용(https://en.wikipedia.org/wiki/Communication_accommodation_theory 커뮤니케이션 수용 이론 관련 내용)이 구체적인 사회적 피드백(온라인 정신 건강 커뮤니티에서 일개인에게 받은 support) 영향을 주는지를 조사한 논문.
커뮤니티의 각 게시물에 대해 1) 언어적 수용과 2) 그것이 받은 지지의 수준(level)을 정량적으로 도출, 얻어내었다.
여러 심리적 욕구를 충족시켜주는 55가지 Reddit 커뮤니티들 사이에서 1)과 2) 사이에 일관성 있는 positive link가 있는 것을 밝혀냈음.
support 제공 메커니즘의 향상을 제공하고자 함.



# INTRODUCTION
Social support는 스트레스를 받거나 힘든 상황에 대해 buffer, 완충 작용을 제공해서 통제 불가능하고 감정적으로 파괴적이게 되는 상태를 회복할 수 있도록 돕는다. 그러나 치료적 맥락 밖에서, 몇몇 취약하고 연약한 사람들은 적절한 사회적 지원에 접근하기에 제한된 능력을 갖고 있다.
Online mental health communities(OMHCs) – 오늘 날 mental health support에 중요한 자원으로 드러나고, 부상하고 있다. 이런 사이트들이 자살 충동을 줄이는 등 정신 건강 복지 향상에 꽤 많은 도움을 주고 있다. 
거기에서 일어나는 support들은 Emotional Support(ES)와 Informational Support(IS)와 같은 범주가 있다. 거기에는 정신 질환, 위기, 중독, 학대 등과 같이 다양한 이슈들에 대한 공감, 인정, 충고, 상황에 따른 평가 등이 포함된다.
높은 수준의 support는 이런 개인들이 안전한 피난처에 있다고 생각하게 만들어, 감정을 억제하지 않고 표현할 수 있게 되고, 낙인 찍힌 경험들을 스스로 털어놓을 수 있게 되며, 다른 사람들과 신뢰할 수 있는 관계를 형성할 수 있게 된다.
정리하자면, OMHCs는 취약계층의 시기적절하고, 상황적으로 중요한 요구에 부응하는 support mechanism을 제공한다.

OMHCs를 포함한 많은 community들은 norm(규약)으로 정의된다. 이러한 규범을 준수한다는 것은 공동체에 대한 개인의 헌신을 나타내며, 이 경우 그들은 사회적 승인과 수용으로 보상을 받는다.
linguistic accommodation은 개선된 사회적 피드백, 향상된 연대, 더 나은 사회적 교류, 그리고 보답하는 친밀감과 관련이 된다.
이러한 insight들은 범용 온라인 커뮤니티들에서 어느 정도 입증이 되었으나, OMHCs에서 언어적 수용이 social support로 해석된다는 것을 나타내는 경험적 근거가 부족하다. social support를 모색하고, 제공하는 능력이 OMHCs의 전반적인 목표에서 가장 중요한 부분이므로, support와 accommodation 사이의 연관성을 찾는 것이 커뮤니티들의 근본적인 사회적 프로세스를 이해하는 데에 가치가 있다. 내재된 언어 규범에 비추어 볼 때, OMHCs가 최약계층의 중요한 심리적 요구와 요청에 어떻게 반응, 대응하는지 알 수 있다.

### Our Work
논문에서 해결하려고 한 문제 : 회원들의 linguistic accommodation 관행이 OMHCs의 support 제공에 어떤 영향을 미치는가?
이 문제를 해결하기 위해서 연구진들은 우울증(depression), 불안(anxiety), 중독(addiction), 트라우마(trauma)와 관련된 조언, 도움을 제공한 Reddit의 55개 OMHC에 있는 공개적으로 공유된 post, comment들에 있는 많은 양의 corpus(말뭉치)들을 연구했다.
연구진들은 어떤 post로 인해 받은 ES와 IS의 level을, 정도를 평가하기 위해서 Supervised Learning technique을 고안했으며, post 작성자가 표현한 linguistic accommodation을 정량화하기 위해 Linguistic Style Matching이라는 잘 입증된 method를 조정하였다. 마지막으로, Multinomial logistic regression을 이용해 게시물에서의 언어 수용 수치(정도)와 커뮤니티로부터 받은 support의 relationship에 대해서 조사한다. (linguistic accommodation과 support의 상관관계를 본 듯)

Reddit 커뮤니티에서 support는 가장 긴급하고 중요한 요청에 맞춰지도록 의도되어 있지만, 그들이 제공하는 support 유형은 그들이 다루는 문제에 따라 다를 뿐만 아니라, support의 level이 support seeker가 작성한 post에서 보여준 linguistic accommodation 정도에 따라 다르다는 것을 찾아냈다. post의 linguistic accommodation이 증가함에 따라, 받은 ES와 IS의 level 또한 증가하는 현상을 다양한 OMHCs에서 찾아낼 수 있었음. 
support seeker의 community norm(규범) 준수가 ES와 IS에 영향을 준다는 면에서 새로운 insight를 제공하는 연구 결과이다.
연구진은 제안을 design하는 개요를 작성함으로써 괴로워하는 사람들의 unique하고 중요하거나 충족되지 않는 욕구에 대한 직접적이고 향상된 support를 OHMC가 통합할 수 있도록 결론을 내린다. (?)

### Privacy, Ethics and Disclosure
공개 데이터를 이용해 작업했지만, 개인 식별 정보는 포함하지 않았으며, user들의 개인 정보를 보호하기 위해 인용문은 paraphrased(다른 말로 바꾸어 인용)되었다.



# RELATED WORK
## Social Support in Online Mental Health Communities
1970년대 이후, coping resource로서의 social support 역할을 이해하고, 심리적 적응(조정)과 질병 회복을 돕는데에 상당한 관심이 있어왔다. Kaplan은 social support를 애정, 인정, 소속감, 안전에 대한 개인의 욕구가 중요한 다른 사람들에 의해 충족되는 정도 라고 정의한다.
Cohen and Willis는 social support의 타당성, 적절성이 심리적 증상의 심각성과 직접적으로 연관되어 있고(혹은), 고통스러운 사건과 스트레스 사이의 완충 역할을 한다는 것을 증명해냈다. 또한 Goffman은 감정적인 괴로움을 겪고 있는 개인은 특히, 같은 사회적인 오명이나 경험을 공유해주며 공감해주는, 동정 어린 사람과 상호작용하고, 그들로부터 support를 받으면서 혜택을 받는다는 사실에 주목했다.
Cutrona와 Suhr는 이러한 이점을 인식하여 social support를 이해하고, 평가하기 위한 유용한 분류 스키마인 Social Support Behavioral Code를 개발했다. 이 스키마에서 제안된 두 가지 카테고리, emotional support와 informational support가 이론적, 연구적으로 많은 주목을 받았고, 본 연구에서 채택된 분류이기도 하다.

### Studies of Online Mental Health Communities
수년 간, 온라인 커뮤니티가 다양한 health challenge(건강 문제)에 대한 peer-to-peer social support의 원천이 될 수 있다는 것이 반복적으로 관찰되어 왔다. 이런 커뮤니티의 key aspect(주요 측면)는 회원들이 그와 관련된 건강 문제를 처리한 경험이 더 많은 사람들을 포함해 유사한 challenging condition에 있는 다른 사람들에게 접근할 수 있도록 해준다는 것이다.
empathetic messages -> direct ES
exposed to others having similar experiences -> indirect ES
receiving helpful information and advice related to treatment and medication / building social capital -> IS
Andalibi et al은 성적 학대를 받은 경험이 있는 사람들이 관련한 Reddit 온라인 커뮤니티에서 support를, 도움을 청하는 방법에 대해서 연구했고, 또 다른 연구에서는 이러한 커뮤니티가 임상적 질문을 해결하고, 유용한 정보 공유의 장을 구축하는 데에 중요한 역할을 한다는 것을 발견했다. De Choudhury외 연구진들은 OMHCs로부터 얻은 support가 depression(우울, 우울증)을 효과적으로 감소시키고, mental well-being(정신적 후생, 행복)을 향상, 개선시켜주는 정도를 정량화했다. 다른 연구에서는 ES와 IS, 두 가지로 지원 형태를 구분함으로써 커뮤니티에서 support가 구성원 유지에 어떤 효험을, 영향을 보였는지를 분석하였다.
본 연구에서는 OMHCs에서 공유되는 post의 ES와 IS의 수준을 automatically(자동으로) 감지한 후, 이들이 다른 type의 community들에서 어떻게 변화하는지 검토하는(examine) 컨텐츠 중심 접근법(Content-driven approach)를 제안한다.

## Community Norms and Linguistic Accommodation
신뢰할만한 assessment signals가 없는 경우, online community의 중심 신조?인 norm은 종종 그들 자신을 안정적인 linguistic practices(언어 관행)으로 나타내어 커뮤니티 구성원을 위한 common context를 확립할 수 있게 한다.
연구진들은 OMHC에서 공유되는 content(post)의 language를 그들의 근본적인 norm을 식별하는 메커니즘으로 채택하였다.
또한 member들의 linguistic practices(언어적 관행)이 community norm을 나타낼 뿐만 아니라, Speech Accommodation Theory는 사람들이 social interaction을 하는 동안 그들의 언어적 스타일을 조정한다는 것을 암시한다. 본 논문에서는 linguistic accommodation이 OMHCs들에 어떻게 존재하고 있는지 여부를 조사한다.
linguistic alignment
아일랜드 외 연구진들은 linguistic style matching(언어적 스타일 매칭)이 romantic relationships의 중심에 있는 암묵적인 대인관계 과정을 반영한다는 것을 발견했다.



# DATA
## Data Acquisition
연구진은 공개적으로 접근이 가능한 Reddit(온라인 포럼으로 널리 쓰이는)의 데이터를 사용했다. 해당 플랫폼에서 registered user는 content를 text, link, image 등으로 공유한다. 이미 존재하는 post에 새로운 post를 작성하거나, comment를 달 수 있다. 이러한 게시물들은 discussion 주제에 따라 subreddit이라고 알려진 다양한 커뮤니티로 분류된다.
최근 연구에 의하면, Reddit은 우울증(depression), 불안(anxiety), 자살하려는 생각(suicidal ideation)에 대해 다루는 subreddit들을 통해 mental health 담론(discourse)를 촉진하고, 가능하게 하는 것으로 알려져있다. 이러한 커뮤니티들은 심리적 고통을 겪고 있는(다스리고 있는) 사람들에게 ES와 IS를 제공한다.

본 연구에선 연구를 위해 Reddit OMHCs의 포괄적, 종합적인 list를 모으기? 작성하기? 위해 Snowball Sampling을 이용하였다. 먼저, support, counseling, mental health와 같은 키워드와 같은 mental health issue들을 이용해 다양한 검색 쿼리를 만들기 위해 prior work에서 도출한 subreddit 검색 기능(subreddit search functionality)을 사용했다. community descriptions에 자주 등장하는 관련 키워드를 기반으로 subreddit search functionality를 반복적으로 augment시켰다. 
연구진들의 최종적인 keyword set은 support, counseling, mental health, mental, trauma, abuse, depression, suicide, therapy, coping이었다. 이러한 keyword들을 이용해 연구진들은 55개의 OMHCs들의 list를 모았다.(작성했다)

그리고 연구진들은 Google의 BigQuery에서 사용이 가능한 Reddit data archive를 활용했다. BigQuery는 타사에서 간단한 SQL-like query들을 통해 공개적으로 사용할 수 있는 대규모 dataset에 access할 수 있도록 해주는 cloud 기반 data warehouse이다. 연구진은 55개의 OMHCs들을 대상으로 2014년 1월부터 2016년 8월까지 작성된 post와 comment들을 모두 추출했다.
358,409개의 post, 1,832,702개의 comment를 추출했음. (커뮤니티 당 6,516.53개의 post, 33,321.85개의 comment)
RedditMetrics를 탐색한 결과, 커뮤니티는 다양한 규모에 걸쳐 있으며, 평균 subscriber 수는 132~189,922명에 이른다.

## Categories of Mental Health Communities
dataset에 있는 많은 양의 community들을 고려하여(해볼 때), 후속 분석을 단순화하기 위해 그들(?)이 focus하는 광범위한 주제와 mental health issue들에 따라 그들을 분류했다. 이러한 분류를 하기 위해서 연구진은 two-step unsupervised learning based machine-human framework를 이용했다.
1) human labeling은 의미론적으로 meaningful하고, 맥락적으로 관련 있는 community category들을 추출하는 데에 도움이 되지만 확장이 어렵고, 2) 클러스터링 기술은 scalable하지만, 그 자체로 OMHCs에게 의미있는 grouping을 제공하지 못할 수 있기 때문에 위의 방법을 채택한 것 같다.

(1) k-means의 사용.  
k-means clustering algorithm을 이용하여 55개의 OMHCs에서 공유된 게시물의 n-grams(n=3) 초기 클러스터링을 수행했음. Optimal k를 largest Silhouette coefficient에 의거하여 5로 설정했다.
(2) Reddit의 OMHC에 친숙한 two annotator들은 독립적으로 machine-labeled cluster들을 정제하고, 알맞은 descriptive label을 클러스터들에 할당했다.  (semi-open coding approach를 이용) 이를 위해 subreddit landing pages들로부터 textual description들을 적극적으로 참조했고, 다양한 mental health condition들에 대한 개념적인 해석을 DSM-5로부터 차용했다. 
그 결과, 그들은 5개의 mental health community 카테고리를 확인할 수 있었다.
Trauma & Abuse / Psychosis & Anxiety / Compulsive Disorders / Coping & Therapy /     Mood Disorders



# METHODS
## Support Classification
본 논문에서는 OMHCs의 support를 정량화(quantify)하기 위한 machine learning framework를 제시한다. 저자들은 online social support에 대해서 Emotional Support(ES)와 Inforamational Suport(IS)의 two-class characterization을 하였다. 저자들이 모은 OMHCs dataset의 post들에 작성된 comment들로부터 ES와 IS의 level(척도, 수준)을 추론한다.
 1,832,702 comment들의 전체 corpus(해당 post의 작성자가 작성한 comment는 제외)부터 시작하여 400개의 random sample comment들을 선택했다. (이 중 세 개는 중복(duplication)으로 인해 제거됨.) 그리고 Reddit의 OMHCs에 익숙한 two annotator들이 각각 그 comment? Corpus에 대해 three-point Likert scale(1=제일 도움 안 됨, 3=제일 도움 됨)를 사용하여 ES 및 IS 수준에 대해 점수를 매겼다.
IS – 치료에 대한 정보나 조언의 정도
ES – 공감, 격려, 친절의 정도
주석 작업이 끝날 때, 두 annotator(주석자, 관찰자)가 만나 의견 차이를 해결했고, 두 관찰자 간 측정 범주 값에 대한 일치도를 보는 Cohen’s Kappa 계수를 측정해봤을 때, 
IS : 0.879, ES : 0.876의 결과를 보였다. (둘 다 완벽한 일치도(almost Perfect)의 범주)
전체 400개의 sample post에서 IS 점수 1, 2, 3점을 받은 게시물은 각각 185, 131, 81개였고, ES 점수 1, 2, 3점을 받은 게시물은 각각 135, 134, 128개였다. IS에는 1점을 받았지만, ES에 대해서는 3을 받은 Psychosis & Anxiety 커뮤니티 카테고리의 comment를 인용한 문구가 소개되어 있다.

Annotate된 이 comment들을 training data로 사용하여, 연구진은 support에 대한 두 형태(IS, ES)에 대한 tertiary classification model(분류하고자 하는 category가 3개인)을 build했다. 잘 검증된 심리 언어학적인 어휘, 그리고 LIWC(Linguistic Inquiry and Word Count)를 이용해 ES 또는 IS를 예측할 수 있는 comment text의 classification feature를 계산했다. 연구진은 특히 mental health 관련 소셜 미디어 컨텐츠의 특징으로 밝혀진 50개의 LIWC 범주에 초점을 맞추었다. IS classification model은 특히, URL의 존재에 해당하는 extra binar indicator(지표) feature가 포함되어 있는데, IS를 제공하는 comment는 종종 치료(treatment)와 medication(약물) 관련 정보에 대한 link를 포함하고 있기 때문이다.

Multinomial logistic regression model은 comment의 ES를 예측하는 데에 accuracy와 F-1 score 측면에서 최고의 성능을 산출하는 것으로 관찰되었고, Support Vector Machine(SVM) classifier with a polynomial kernel of degree 3는 IS 예측을 가장 잘 수행해냈다. 두 classification model 모두 k-fold cross-validation(k=10)을 통해 평가되었다. 
ES classifier는 평균 정확도 59%를 달성했는데, 이는 baseline accuracy보다 35% 우수했다. 마찬가지로 IS classifier의 경우 평균 정확도(mean accuracy)가 72%로, 기준 정확도 60%보다 향상된 것으로 나타났다. 이들은 ES, IS에 대한 인간들이 매긴 label과 machine labels의 correlation(상관관계) 모델의 결과에 의하여 더욱 강화된다. 

연구진은 이 두 classifier를 이용해서 held-out comment
한 expert annotator가 machine labeled된 dataset의 100개의 sample comment에 대해 수동으로 cross-verify를 진행했다. Cross-verify의 결과로 IS와 ES의 accuracy를 각각 66%와 73%로 산출, classifier의 performance와 일치하는 강력한 성능을 나타냈다. 최종적으로, 각 post에 대해 연구진들은 모든 comment에 대한 ES와 IS의 average를 계산했고, 뒤이어 해당 post로부터 받은 ES와 IS 점수의 총합을 내기 위해 balanced bucketing을 이용했다.


## Modeling the Link between Support and Accommodation
### Measuring Linguistic Accommodation
연구진들은 자신들의 dataset의 post들에 표현된 linguistic accommodation을 측정하는 방법을 제시한다. 개인의 linguistic style과 공동체의 linguistic style 사이의 alignment(정렬)를 평가하는 Linguistic Style Matching(LSM)을 사용했다. LSM은 개인의 연설(speech, content)에서 기능어 사용률을 언어와 social psychological state(사회심리학 상태) 사이의 관계로 식별하는 데에 도움을 주기 때문에 stylistic alignment를 위한 대용물로 간주한다. 그것들은 무의식적으로 생산되고, 사람의 언어, speech 패턴에서 조작하기가 어렵기 때문에 본 연구에 적합했다.
(1) Linguistic Accommodation은 시간이 지남에 따라 확립되며, 개인의 linguistic style(언어 스타일)이 과거에 community가 사용한 것과 얼마나 밀접하게 일치하는지에 따라 정량화된다. 연구진들은 각 community의 게시물을 Timestamp의 중앙값을 기반으로 P1과 P2 두 부분으로 나눴다. 여기서 P1과 P2는 각 community의 timestamp 중앙값 전 후에 만들어진 두 set의 post들이다. 연구진들은 P2의 post에 있는 linguistic accommodation이 P1 post들에서 나타나는 스타일에 의존할 것을 기대한다.
(2) 연구진들은 LIWC의 12개 범주를 이용하여 P1 및 P2 게시물의 function word 비율을 계산하는 것으로 시작한다.
(3) 그런 다음 community의 P2에 있는 각 post p에 대응하여, 연구진들은 일련의 historical post(역사적? 기록적?)

### Statistical Models
마지막으로, 연구진은 post의 linguistic accommodation(LSM 점수)과 community 내에서 받는 support 사이의 관계를 평가하기 위해 사용하는 일련의 통계 모델을 제시한다. 연구진은 ES와 IS에 대해 두 가지 nested multinomial logistic regression model을 만들었다. 각 모델들의 종속 변수(response variable)는 1(낮음), 2(중간), 3(높음)으로 나타나는 post의 ES와 IS support score이다.
각 model set은 (a) confounding predictor variables와 support score 사이의 관계를 정량화하는 control model(제어 모델)과 additional predictor variable(추가적인 종속 변수)인 post의 LSM score를 포함하는 LSM model로 구성된다. 이전 연구에서 도출된 것처럼, 연구진은 confounding predictor variable들을 포함했다 : post specific variables(1, 2), post author specific ones(3, 4), community-oriented(커뮤니티 지향적인) variables.

(1) Content  
연구진은 post의 주제 content가 post로부터 유발된 support의 정도에 영향을 미치기 때문에 confounding predictor로 삼았다. 이를 위해 LIWC dictionary의 모든 non-function word(비기능어) category를 사용했다. 그냥 post의 주제 파악을 위해 LIWC dictionary를 이용했다는 의미로…

(2) Post Length  
길이가 긴 게시물은 온라인 커뮤니티에서 더 많은 support를 받기 때문에 연구진은 whitespaced word(공백 문자) control variable로 포함했다.

(3) Self-Disclosure(자기폭로)  
post의 자기폭로 정도 또한 social support를 포함한 community feedback에 영향을 준다. 이전 연구의 기술을 이용하여 dataset의 post에 있는 self-disclosure 양에 대한 실제 label을 얻고 model에 포함시켰다.

(4) Author Tenure(재임 기간? community에 머문 기간?) and Familiarity  
community의 norm에 대해 개인이 알고 있는 정도 또한 그들이 community로부터 받은 support에 영향을 준다. 연구진은 community knowledge를 두 가지 방법으로 정량화했다.
첫째, 그들의 첫 번째 post(dataset에 있는)와 최근 post 사이의 timestamp 차이를 계산함으로써 커뮤니티 저자의 tenure를 알아낸다.
둘째, 최근 게시물 이전에 해당 community에서 작성한 post의 수를 파악하여 author의 community에 대한 친숙도(familiarity)를 정량화한다. 작성한 post가 많으면 community의 norm(규범)에 보다 더 친숙함을 나타낼 것이다.

(5) Throwaway Account(그냥 쓰고 버리는 계정)  
post 저자의 익명성은 social feedback과 support의 수준에 영향을 준다. Reddit에서는 throwaway account라고 불리는 임시 계정을 만듦으로써 익명성이 형성된다. 연구진은 throwaway라는 단어나 그와 사전적으로 유사한 단어들이 username, title, post의 내용에 포함되어 있으면 throwaway account로부터 공유된 post라고 간주했다.

(6) Size of the community  
규모가 큰 community는 게시물에 더 많은 comment들을 불러일으켜, 관찰된 ES와 IS를 부풀릴 수 있기 때문에 community 가입자 수를 모델에 변수로 포함시켰다.



# RESULTS
## Support Classification
먼저, 연구진은 연구에 사용한 dataset의 모든 comment들에 label한 support classifier의 결과를 분석했다. community category별로 집계된 ES와 IS의 분포를 제시한다. Figure 4는 각 type의 support를 받은 총 게시물 비율에 대한 support score의 분포를 보여준다.
Trauma & Abuse, Coping & Therapy, Mood Disorders와 관련된 community들은 높은 ES(3점)를 IS보다 더 많이 받은 것으로 확인 됐다. (각 카테고리에 대해 8%, 16%, 17%만큼) 게다가 해당 항목들은 낮은 IS(1점)을 낮은 ES보다 각 항목에 대해 11%, 30%, 31%를 더 받았다. (위 세 카테고리들은 ES로 도움된 건 되게 많은데, IS로는 도움 안 됐다고 판단한 글들이 많았나봄)
이러한 결과는 위 세 커뮤니티가 IS에 비해 ES를 더 많이 제공한다는 것을 시사하며, 이는 이런 커뮤니티들에 접근하는 개인의 needs나 커뮤니티 자체의 goal에 기인할 수 있다. Trauma & Abuse 커뮤니티 중 하나는 해당 커뮤니티를 ‘모든 학대로부터 살아남은 자들이 그들의 이야기를 공유하며 healing하는 곳’으로 소개를 하고 있다.
Compulsive Disorder와 관련된 커뮤니티의 post들은 IS 3점을 ES 3점보다 6% 더 높게 받았다. Compulsive Disorder(강박 장애) 커뮤니티 중 한 곳은 스스로를 OCD를 앓고 있는 사람들이 모여 치료에 대한 정보를 주고받는 곳이라고 설명한다. 한 게시물은 반복적으로 세어봐야 하는 강박에 시달리는 것을 묘사하고 있고, 이에 대한 조언을 요청하고 있다. 이 post의 모든 comment들은 높은 평균 IS를 기록했고, post 작성자(poster)가 원하는 type의 support들을 제공했음을 나타낸다.
Psychosis & Anxiety와 관련된 커뮤니티에서는 IS와 ES가 거의 동일한 분포를 나타냄을 관찰할 수 있었다. 이는 짐작건데, 이 category에 있는 community들이 격려와 소속감 뿐만 아니라 조언의 측면에서도 support를 해줘서 두 type의 support를 동등하게 제공한다는 것을 나타낸다. 한 예로, P&A community에 올라온 ‘다음 달에 있을 jury duty 때문에 다른 일을 할 수 없는데 팁이 있을까요?’ 라는 post는 IS와 ES에서 둘 다 2점을 받았다. 이 게시물에 대한 13개의 comment 중, IS 2점을 받은 코멘트와 ES 2점을 받은 코멘트에 대한 소개가 나와있다.

요약
Trauma & Abuse, Coping & Therapy, Mood Disorders – ES가 더 높게 측정됨.
Compulsive Disorders – IS가 더 높게 측정됨.
Psychosis & Anxiety – ES와 IS가 비슷하게 측정됨.


## Examining Support and LSM
LSM measure를 이용해서 5개의 commuity category에 속하는 post들에서 나타난 linguistic accommodation pattern을 조사했다. 그림 5는 모든 community category들에 대한 LSM score 분포를 나타낸다. 각 community category에 대해 대부분의 post가 높은 LSM score를 받은 것으로 나타났고, LSM score의 평균은 0.65였고, 표준편차는 0.1이었다. 이러한 관찰(결과)은 사람들이 community의 언어 관습을 따르고, 다른 community 사람들의 글쓰기 방식을 모방하는 경향이 있음을 나타낸다.
또한 연구진은 모든 category에 대한 평균 LSM이 0.63~0.68 사이에 있다는 것을 알아냈다. 이는 다양한 목표와 목적을 가진 서로 다른 community들에서 linguistic accommodation 정도에는 약간의 불일치성이 있지만, 이러한 community들의 post들은 community, values and identifies with에 그들의 linguistic style을 일치시키려고 하는 경향을 일관되게 보여준다. 소규모 group에서도 이와 유사한 높은 LSM이 보고된 적 있었다.

이제 연구진은 본 연구의 주 목적인 post에서 드러난 LSM과 post들이 받은 IS/ES에 대한 관계성을 분석한다. box-and-whisker plot을 이용하여 community category들에서의 IS, ES에 대한 LSM score의 분포를 조사했다. community category에 대한 box들이 거의 동일한 높이임을 관찰했으며, 이는 주어진 support value(1, 2, or 3)에 대해 대부분의 게시물이 LSM score에 동의한다(?)는 것을 의미한다. 또한 연구진은 모든 community category에서 IS와 ES가 증가함에 따라 linguistic accommodation이 작은 수치지만 일관적으로 증가한다는 것을 알게 되었다.
하지만 이러한 증가량은 Trauma & Abuse 커뮤니티와 Coping & Therapy 커뮤니티의 ES에 대해 더 두드러진다는 것을 확인할 수 있었다. Trauma & Abuse 커뮤니티와 Mood Disorders 커뮤니티의 IS에 대해서도 비슷한 증감세가 뚜렷하다. Coping & Therapy 카테고리는 정신 치료나 상담을 필요로 하는 사람들이 있는 community를 포함하기 때문에 post 내의 linguistic alignment가 높아지면 커뮤니티의 공감(empathy), 친절, 정서적 인정의 표현이 커질 가능성이 높다. 반면, Mood Disorder 커뮤니티에서 높은 linguistic accommodation은 poster가 community가 제공하는 구체적이고 직접적인 도움과 조언을 찾고 있다는 것을 나타낼 수 있다.

연구진은 LSM와 IS/ES의 관계가 가장 두드러지는 다양한 community들에서 post의 linguistic attribute(언어적 특성)을 더 나아가, 추가로 조사했다. 이를 위해 LS와 support가 둘 다 높거나 낮은 post들을 고려했다. High support & high LSM을 가지는 post들의 그룹과, low support & low LSM을 가지는 post들의 그룹으로 community category의 post들을 분류하였다. high 쪽은 LSM score가 평균보다 높은 쪽을 고려했고, low 쪽에서도 유사하게 LSM score가 평균보다 낮은 쪽을 고려했다. 또한, high support post는 support score 3을 받은 것으로 했고, low는 1점 받은 post들을 포함시켰다.
그 후, 앞서 설명한 각 group의 post들을 사용하여 각 community category에 대해 두 개의 언어 모델을 생성했다. 또한 동일한 community의 모든 post들에 대한 다른 model을 만들고, 두 group에서 자주 사용되는 vocabulary(어휘)를 추출하기 위한 기본 모델로 사용했다. 그러기 위해, 연구진은 SAGE를 사용했다. SAGE는 background distribution으로부터 log-frequency 편차 모델 class label을 부여받은 text 생성(발생) 모델이다. Table 2에서는 High LSM, Hign ES/IS 그리고 Low LSM, Low ES/IS로 grouping 된 포스트들에서 자주 사용된 단어들을 보여준다. 모든 set에서 가장 많이 등장한 단어들은 community category에 보다 더 관련이 있고, community의 goal(목표)과 norm에 더 일치하는 것으로 판명된 단어들이다. Sage Analysis의 결과는 LSM과 support score가 높은 posts, LSM과 support score가 낮은 posts에서 많이 쓰인 단어들과 덜 쓰인 단어들을 보여준다.
LSM이 높고 IS가 높은 Psychosis & Anxiety 커뮤니티의 port들에서는 ‘xanax’와 같은 의약품과 함께 ‘blood’, ‘nausea(구역질?)’, pain(통증) 등의 건강 관련 단어를 많이 사용하는 것으로 나타났다. xanax 처방을 받고 있다는 post는 LSM score 0.75, 그리고 IS score 3점을 받았다. 그 중 한 댓글은 poster가 약을 적당히 사용할 것을 조언하기도 했다. 같은 community에 올라온 poster가 의료 시술 이후 받은 Apple Watch에 관련된 post는 0.45의 낮은 LSM 점수를 받았으며, IS 점수도 1점만 받았다.
이와 유사하게 Mood Disorders 관련 커뮤니티에서는 배우자가 떠난 사람이 우울증을 겪고 있는 것을 묘사한 글이 있었고, 이 post는 LSM score 0.79점을 받았으며 55개의 comment들이 달렸다. 이 post에 대한 평균 ES는 3이었고, 대부분의 댓글은 동정적인 경향이 있었고, poster에 대한 격려(encouragement)를 제공하기 위한 목적으로 작성되었다. linguistic alignment와 ES가 높은 post는 post가 작성된 community와 관련이 있는 것으로 확인된 단어들을 사용한다.

## Nested Multinomial Logistic Regression(여러 클래스를 classification 하기 위함)
지금까지의 분석으로부터, ES, IS와 post의 LSM score 사이의 positive relationship이 존재함을 어느 정도 알 수 있었다. (LSM score가 높으면 ES/IS도 높다는 positive) 원칙적이고 통계적인 방법으로 이러한 relationship을 정량화할 수 있고, 이러한 relationship이 중요하게 작용하는가? 이를 위해, 연구진은 nested multinomial regression model의 결과를 제시한다. 이는 LSM을 response variable인 post의 ES와 IS를 예측하기 위해 활용된다. 
regression model의 예측 변수(독립 변수)가 서로 linearly(선형적으로) 독립되게 하기 위해, multicollinearity test를 시행했다. LSM model의 모든 변수에 대해 pearson’s correlation 분석을 수행하여 correlation matrix(상관 행렬)를 얻은 후, 이 correlation matrix의 Eigen Vector(고유 벡터, 선형 변환이 일어난 후에도 방향이 변하지 않는 영벡터가 아닌 벡터)를 계산한다. 행렬의 개별 고유값이 0보다 1에 더 가까웠고, 이는 독립 변수가 서로 선형적으로 독립적이란 것을 의미한다.  

### Goodness of fit(적합도, 관측된 값과 model에서 예상되는 값 사이의 불일치를 요약)
연구진은 각 community category에 대한 dataset의 post가 받은 support를 추정하는 model set(IS, ES 각각 하나씩)에 대한 몇 가지 적합도(goodness of fit)를 보고한다. 첫번째 model인 Control model은 앞서 method에서 설명한 모든 contro variable들을 포함한다. 두번째 model인 LSM model에서는 이러한 변수들 외에도 LSM score를 extra variable로 사용한다.
table 3을 이용해, 먼저 deviance metric을 기반으로 Control과 LSM multinomial logistic regression model에 대한 적합도를 평가한다. Deviance(편차)는 data에 대한 적합치 결여 정도이므로 값이 낮을수록 좋다. 연구진은 모든 community category에서 Null model과 비교하여 Control, LSM 두 모델이 deviance를 크게 개선하면서 상당한 설명력(?)을 제공한다는 것을 관찰했다. 
다음으로 control 모델과 LSM model을 상호 비교하며, LSM variable을 LSM model에 추가한 것이 model fit에 어떤 향상을 줬는지를 검사했다. 연구진은 control model과 LSM model 간의 편차 차이가 LSM model의 total number of additional parameters(총 추가 매개변수 수)의 두 배에 해당하는 자유도(degrees of freedom, df)를 갖는 카이제곱 분포를 근사적으로 따른다는 것을 발견했다. 예를 들어, Trauma & Abuse community category의 IS의 경우, LSM model 편차와 control model 편차를 비교하여 LSM score가 제공하는 추가 information이 상당한 explanatory power(설명력, 주제를 효과적으로 설명하는 가설 또는 이론의 능력)을 가지고 있음을 알 수 있다. 마찬가지로, 해당 category의 ES의 경우 또한 control model과 LSM model의 분포 차이가 카이제곱 분포를 근사적으로 따른다. 연구진은 두 support 유형 모두에 대해 다른 community category의 경우도 유사한 결과를 관찰했다.
마지막으로, IS에 대한 goodness of fit(적합도)가 Mood Disorders 관련 community에서는 가장 높은 수준인 반면, Compulsive Disorders 관련 community의 경우, 가장 낮은 수준이었다. 이는 Mood Disorders community에서는 LSM이 IS를 매우 잘 예측하고, Compulsive Disorders community에서는 예측이 가장 잘 안 됐다는 것을 나타낸다.

### Quantifying the Role of LSM
마지막으로, 연구진은 IS와 ES에 대한 LSM 모델의 logistic regression coefficients를 제시한다. IS의 multinomial log odds of IS는 LSM 점수가 단위 증가(unit increase)할 때 1.75만큼 증가할 것으로 예상되며, LSM model의 control variable은 일정하게 유지된다. 다른 community category에서도 ES, IS에 대한 LSM model에서 유사한 pattern이 나타났다.
Odds ratios는 coefficients의 exponentiation(지수화)이다. coefficient value의 odds ratio는 support score가 1일 때의 risk와 비교하여 2점, 또는 3점일 때의 support score의 risk가 LSM score 변화에 따라 어떻게 변화하는지를 나타낸다. 따라서, odds ratio가 1보다 크면 LSM이 증가할수록 support score가 1이 될 risk와 비교해 support score 2 또는 3이 될 risk가 증가함을 나타낸다. Table 4와 같이 IS와 ES에 대한 support score 2, 3의 odds ratios가 1보다 큰데, 이는 LSM score가 증가하면 post로부터 받은 support 정도가 증가한다는 것을 의미한다. 또한 5개 community category에서 IS의 경우 odds ratios가 ES의 경우보다 높다는 점에 주목했고, 이는 IS의 경우가 ES보다 LSM score가 증가했을 때 더 많은 support를 받을 가능성이 높다는 것을 의미한다. 
예를 들어, Trauma & Abuse community의 경우, support score 3에 대한 relative odds ratios가 ES에서보다 IS에서 3.71(19.72 – 16.01)의 차이로 더 높다는 것을 발견했다. 반면, Compulsive Disorders community의 경우, support score 3에 대한 relative odds ratios는 IS가 ES에 비해 10.17(16.35 – 6.18)만큼 낮다. 이는 linguistic accommodation이 증가함에 따라, 주로 높은 ES를 제공하는 Trauma & Abuse community에서 높은 IS를 받는 것이 더 쉬워진다는 것을 의미한다. 반면에, 높은 IS를 제공하는 Compulsive Disorders commuinty에서는 높은 ES를 받는 것이 쉬워진다는 것을 의미한다.



# DISCUSSION
본 연구는 다양한 심리적 needs를 충족시키는 Reddit OHMCs의 social support와 linguistic accommodation을 조사하는 first insight 증 일부를 제공했다. 이러한 결론을 통해 이론 및 design(설계) 관점에서 이러한 community들에 대한 몇 가지 영향을 식별할 수 있다. 또한, 본 연구가 OMHCs의 운영에 어떤 영향을 줄지도 검토한다.

## 이론적 시사점
### Support Matching and Provisioning
본 연구에서 주목할 만한 발견, 결과는 모든 community category가 상당한 ES와 IS를 제공하지만, 특정 커뮤니티가 더 많은 ES(e.g., Mood Disorder communities)를 지시, 제공하는 반면, 또 다른 커뮤니티는 더 많은 IS(e.g., Compulsive Disorder Communities)를 제공한다는 것이다. 이는 연구에 관련된 모든 community들이 mental health와 관련되어 있음에도 불구하고, 다른 social support goal을 충족시킨다는 것을 보여준다. 연구진의 결과는 social support가 multi-dimensional construct(다차원 구조)이며, 특정 유형의 support가 특정 요청과 match, 일치할 때 더욱 효과적일 수 있다고 주장하는 Optimal Matching Theory에서 검증을 찾는다(?).
Cutrona와 Russell은 우울증과 같은 정신질환을 다스리는 데에 더 많은 ES가 필요할 수 있다는 것을 알아냈는데, 이는 r/depression 같은 subreddit에 걸친 Mood Disorder community가 더 많은 ES를 제공하는지 설명한다고 볼 수 있다. 반면, r/OCD와 같은 Compulsive Disorder(강박 장애) community의 poster는 그들의 condition, 상태에 대한 조언을 구하려고 하는 경향이 있기 때문에 IS가 그들의 post에 더 잘 어울린다고 볼 수 있다. 요약하자면, 이는 서로 다른 OMHCs의 support 제공이 특정 주제에 초점을 맞춘다는 것을 알 수 있다.

### Conformance and Support
본 연구에서 가장 주목할 만한 점은 ES든 IS든 OMHCs의 social support가 linguistic accommodation과 positive한 연관성이 있다는 것이다. 사회언어학 이론이 linguistic norms(언어 규범) 준수(conformance)와 social feedback 사이의 positive link의 존재가 mental health 주제에 응하는 online community에도 유효하다는 것을 발견했다. 이러한 community가 다루는 문제의stigmatized, sensitive한 특성을 고려할 때, community 전체가 허심탄회하게 털어놓기에 안전한 장소로 기능할 수 있도록 linguistic convention(규약)을 개발함과 동시에, 연약한 사람들 대한 support를 제공하게 된다. 이러한 community에서 support를 받기 위해 linguistic alignment가 필요한 것도 trust, rapport, empathy에 바탕을 둔 사회적 응집(결합) 관계의 확립과 유지를 도모하려는 의도가 있기 때문일 수도 있다. 이전 연구에서는 이러한 특성들이 OMHCs의 기본이 되어야 한다고 했으며, 이를 달성하기 위해 필수적인 규범적 규정 준수에 대해 언급했다.

### The Tension Between Accommodation and Support
ES와 IS가 OMHCs의 linguistic accommodation과 positive relationship을 가지고 있다는 이러한 발견은 community의 일관성 있는 정체성을 유지하기 위해서 support seeker들이 community norm을 준수하게 하도록 계속 고집할 것인지, 또는 취약점을 표현하는 개인에게 적시에 support를 지시하는 community의 목표를 유지하게 할 것인지 여부와 같은 tension을 표면화한다. 많은 media report들은 Reddit과 유사한 OMHCs들이 unique하고 urgent한 요구를 표현하는 고통받는 사람들을 돕는 능력에 대해 찬사를 보냈다. 하지만, r/suicide에서 두 게시물이 있었는데, 두 post 모두 자신의 needs에 대한 비슷한 immediacy(즉각성)과 criticality(필요성)을 보였지만 한 쪽은 ES 2점, 한 쪽은 ES 1점을 받았다. ES 2점을 받은 post가 그렇지 않은 post보다 더 높은 accommodation을 보였던 것을 발견했다(0.73 versus 0.48).
이러한 OMHCs에 대한 관찰은 다음과 같은 질문들을 제기한다 :
linguistic alignment는 누군가가 self-injury risk와 같은 critical한 필요를 표현하면서도 도움을 받기 위해서라면 절대적으로 필요한 것일까?
poster가 정말 즉각적인 도움을 받아야 하는 상황이더라도 norm을 제대로 따르지 않았다면 충분한 support를 받지 않아야 하는가? (오히려 정말 급박한 사람들은 말을 잘 정리해서 쓸 수 있는 여력이 없지 않을까… 하는 생각이 든다)
이전 연구들에서 정신 질환을 앓고 있는 사람들이 social exchage를 하는 중 직면하는 어려움을 인정했다는 사실에 주목해야 한다. 사회적 영역(social realm)으로부터의 분리는 고통받고 있는 사람들의 속성으로 알려져있다. 삶에 대한 자율성과 통제력의 결여, 단어나 언어적 선택에 대한 의사 결정의 ‘마비(paralysis)’ 또한 anxiety와 같은 많은 mental illnesses와 연관되어 있다고 여겨진다.
그렇기는 하지만, 연구진의 결과는 많은 support seeker들이 실제로 언어학적으로 OMHCs’ norm과 일치하도록 하고 있다는 것을 보여줬다. linguistic accommodation이 전체적인 community identity를 형성하고, 신뢰와 친밀감을 구축하는 데에 자체적인 이점을 가질 수 있다는 것도 인정한다. 하지만 linguistic norm의 준수를 암시적으로든 명시적으로든 요구(requirement), 요건으로 만드는 것은 OMHCs의 광범위한 목적과 모순될 수 있다고 주장한다. 
대신, norm을 제대로 따르지 않은 support seeker가 기본 norm에 대한 명확한 인식을 얻도록 해주거나, support provider가 심각한, 중요한 심리적 needs를 가진 사람에게 쉽게 도움을 줄 수 있는 더 나은 방식을 제공함으로써 해당 platform을 더 좋게 만들 수 있을 것이다.

## 설계적 시사점
OMHCs가 non-linguistically aligning support seeker들의 needs 또한 충족할 수 있는 방법은 무엇?

### Influencing Community Design
현재 reddit을 포함한 많은 social media platform은 community(subreddit)들이 그들만의 rule과 guideline을 강조할 수 있도록 하는 설계 여건(design affordances)이 포함되어 있다. 예를 들어, subreddit의 landing page의 sidebar pane(창)은 OMHCs에서 member들에게 해당 community의 목적을 알리고, community에서 공유할 수 있는 컨텐츠의 유형을 알리는 데에 종종 사용된다. 하지만 이런 것들은 이미 critical하고 distressful한 상황을 겪고 있는 support seeker이 특정 community에서 줄 수 있는 ES와 IS의 quality와 연관된 특정한 normative behavior들을 식별해내기에 간단한 방법이 아닐 수 있다. 
따라서 연구진은 community designer들이 OMHCs의 norm, 표준을 보다 명확히 하고, interface 설계 시, community의 언어 스타일에 대한 잠재적인 학습을 할 수 있도록 하여 더 많은 support를 받을 기회를 얻을 수 있게 함을 제안한다. 연구진은 높은 linguistic accommodation과 높은 ES, IS를 모두 가진 historical post들을 식별하기 위한 향상된 statistical model(통계 모델)을 구현할 것을 제안한다. 그러고 나서 side pane이나 subreddit page의 community guideline이나 FAQ 내에 위와 같이 식별된 post들을 포함한다. 또 다른 방안으로는 community의 landing page 상단에 이러한 예시 post들을 promote할 수도 있다. Reddit에서 ‘sticky comments’라고 알려진 기능을 이용하면 된다. 이러한 post들은 점점 발전하는 OMHCs의 norm을 반영할 수 있도록 주기적으로 update될 수 있다.

### Assisting Support Providers
본 연구 결과에서 linguistic style이 community와 잘 맞지 않는 poster는 상대적으로 적은 support를 받을 가능성이 있다는 것을 암시했었다. 하지만 r/sucidewatch와 같은 subreddit에서는 poster에 대한 support와 관심이 urgent, 시급한 상황이 발생할 수 있다. 연구진은 이러한 경우엔 OMHC에서 적절한 social supporting을 받는데에 있어 필요한 암시적, 혹은 명시적 linguistic accommodation의 필요성을 무시(override)할 수 있는 설계 기능을 포함해야 한다고 생각한다. 이렇게 하기 위해서는 support provider가 본인들에게 들어오는 request의 흐름을 효율적이고 신속하게 탐색할 수 있도록 지원해야 한다.
해결책으로, 개입(intervention) tool을 제안하여 본 논문에서 연구된 LSM approach로 평가된linguistic accommodation 수준이 낮고, support classifier로 검사했을 때 지금까지 거의 support를 받지 못한 게시물에 대해 moderator들, support provider들 에게 timely, 적시에 alert를 주도록 할 수 있다. 또한 경고의 폭주를 방지하기 위해, 개입 tool은 게시물 내용을 시각적으로 요약하거나, 대화형 인터페이스를 도입할 수 있다. post들은 topic과 시급성을 기반으로 분류된다. 

## Limitations and Future Work
먼저, ES와 IS에 대한 세 가지 support class들은 서로 미묘한 차이를 보일 가능성이 있으며, 연구진들의 classifier가 만족스러운 성능을 보였고, expert annotation들 사이에서도 동의가 잘 되었지만, classifier의 성능은 greater availability를 가진 labeled data로 인해 더 개선될 수 있다.
또한 중요한 것은, OMHCs에서 공유된 post들이 적절한 support를 받는지에 영향을 미칠 수 있는 것은 linguistic accommodation 외에 여러 요인이 있을 수 있다는 것이다. 통계 모델에서 그러한 여러 요소를 식별하고, control 해서 community에서 linguistic accommodation과 support 사이의 positive link를 발견했으나, 이것이 본질적으로 인과 관계를 지니는지에 대해서는 확신할 수 없고, 이런 해석을 할 때는 주의를 해야 한다.



# CONCLUSION
본 논문에서는 online mental health communities에서 linguistic accommodation과 social support 사이의 relationship을 조사하는 포괄적인 연구를 제시하였다. 다양한 mental health topic에 초점을 맞춘 55개의 Reddit community로 구성된 대규모 dataset을 사용했다. 먼저, 이러한 community들에서 공유되는 post로부터 받은 두 가지 유형의 social support(emotional and informational)을 정량적으로 도출해냈다. 그리고 나서 심리학적 측정을 바탕으로 그 post들 사이에 나타난 linguistic accommodation을 측정했다. linguistic accommodation과 두 유형의 support 사이에 significant positive association이 있다는 것을 보여주었으며, 이는 연구진이 연구한 community들에 일관되었다. 본 작업들은 online support provisioning(제공) mechanism에 영향을 미칠 것으로 사료된다.