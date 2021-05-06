# Abstract
 본 논문에서 연구진은 Reddit의 mental health community에 달린 comment가 자살에 관한 생각에 향후 어떻게 영향을 미치는지 측정(measure)하는 방법을 제안한다. linguistic cue를 established theoretical model of social support로 해석하고, esteem(존경)과 network support가 다가올 risk를 줄이는 데에 더 두드러진 역할을 한다는 것을 발견했다. 연구진은 online community들에서의 support provision을 개선할 수 있는 tool을 design하는 작업에 본 연구가 미치는 영향에 대해 논의, 설명한다.

 

 # Introduction
Social support는 mental well-being을 개선시켜주는 중요한 요소이다. 도움을 주는 상호작용(supportive interactions)은 부정적인 결과로부터 mental health를 지켜내는, 심리적 스트레스의 영향을 감소시키는 과정인 *buffering effect* 를 일으킬 수 있다. 그 결과 social support는 중요한 psychosocial(심리사회적) 대처 자원으로 인정된다.   

**Social media platform들이 널리 채택됨에 따라, online community는 건강 문제를 가진 사람들이 help, advice, support를 찾는 주요 메커니즘(prime mechanism)으로 부상했다.** 이러한 community에서 받는 support는 건강 문제(health challenge)로부터의 회복과 긍정적인 행동 변화를 촉진하는 것을 포함하여 self-efficacy(자기 옹호?) 및 복지(well-being) 향상(health challenge로부터의 회복을 가능케 하는)과 관련이 있는 것으로 확인이 되었다.  

Online support의 긍정적인 치료 역할에 대한 *cross-sectional study(횡단 연구)*에 주어진 증거에도 불구하고, 연구자들은 이 주장을 입증하기 위해 적절한 경험적 데이터가 아직 충분히 축적되지 않았다는 것을 인정한다. 결과적으로 online social support의 availability와 mental health 사이의 인과 관계를 확립하는 것은 어려울 수 있다. 이는 대부분의 연구가 regression, classification model과 같은 *retrospective procedures*를 채택하고 있지만, 초기 증상이 동일한 user들에 대한 subpopulation을 식별하는 것은 어렵기 때문이다. 또한, 특정 개인의 특성이 social support에 대한 접근과 위험에 처한 경향의 발생과 관련이 있을 수도 있다. 이러한 증상(symptom)과 특성(trait)은 종종 suicidal ideation(자살 충동)과 같은 well-being risk에 대한 최고의 예측 변수(predictor)이기 때문에, baseline condition에 대한 지식이 부족하면 social support와 at-risk states(위험 상태) 사이의 연관성(link)을 해석하는 데 혼란스러운 영향을 미칠 수 있다.  

Online support에 대한 cross-sectional study에서 validity(타당성)를 추가적으로 위협하는 요인은 distressed individual 사이의 social support의 retrospective measurement에서의 잠재적 편향이다. Online comuunity에 참여하는 질병이 생기기 전인 사람들의 group을 모집하기가 어렵기 때문에 문제가 가중된다.  


## Contributions
본 연구는 자살 충동에 대한 risk의 online social support의 역할을 평가하는 데에 있어서 방법론적 차이를 해결하고자 한다. 그러기 위해서 연구진은 Reddit의 유명한 mental health community들에 publicly shared된 장기적인 변화를 다룬 post와 comment를 조사했다. 그런 다음, 해당 데이터에서 나중에 Reddit suicide support forum에 post를 게시하는 사람들을 식별했다. 이러한 community들의 semi-anonymous nature로 인해 mental health 우려, suicidal ideation에 대한 고품질의 자가 보고 데이터를 얻을 수 있었다.  

이 community들에 게시된 post가 받은 comment들을 social support의 proxy로 활용하여, 연구진은 suicide support forum에 post를 게시했거나 그렇지 않은 사람들에게 comment들에 있는 언어의 효과를 modeling하고 정량화하는 **Human-machine hybrid statistical methodology**를 개발했다. **Stratified propensity score matching**을 iterative fashion(반복적 방식)으로 적용하여, significant한 효과를 보여주는 comment들의 언어적 특징을 식별했다. 연구진은 이러한 언어적 특징과 관련된 post의 suicidal ideation risk marker들의 존재에 대한 human assessment(평가)를 얻었다. 그런 다음, 유사한 subpopulation(부분 모집단?)에 해당하는 feature들을 filtering했다. 마지막으로 이렇게 나온 평가(assessment)를 local average treatment effect를 계산하는 데 포함시켜, 향후 suicidal ideation에 대한 risk에 comment의 특정 linguistic feature(언어적 특징)이 미치는 영향을 평가한다.  


## Findings
연구진의 연구 결과는 Reddit mental health community들에 post를 올린 모든 개인들이 comment를 통해 support의 영향을 똑같이 받을 가능성은 없다는 것을 보여준다. Online social support로 혜택을 받은 사람들은 더 큰 사회적 성향, 미래 지향적 성향, 그리고 낮은 인지 장애를 보이는 경향이 있다. 다음으로, 연구진은 stratified matching approach가 future risk에 상당한 영향을 미치는 것으로 식별하는 comment들의 linguistic feature들의 사용 맥락을 qualitatively(질적으로) 해석한다. 그렇게 하기 위해서 연구진은 social support를 characterizing(특성화하는) **social support behavioral code framework**를 채택했다. Esteem(존경)이나 network support를 제공하는 데 사용되는 linguistic feature가 미래에 자살 충동(suicidal ideation)을 줄이는 경향이 있다는 것을 발견했다.  

연구진들은 본인들의 method와 finding이 어떻게 online commentary가 미래의 mental well-being에 미치는 긍정적, 부정적 영향에 대한 insight를 제공할 수 있는지 설명할 것이다.  


# Related Work
## Role of Social Support in Health and Well-Being
Mental health 맥락에서 social support는 **affection(애정), approval(승인), belonging(소속감), security(안전, 보안)에 대한 요구가 중요한 타인에 의해 충족되는 정도**로 정의된다. Social support는 stressful event들의 잠재적 pathogenic(발병시키는, 병원성의) influence로부터 사람들에게 'buffer' 기능을 제공한다.  
**Social Support Behavioral Code** : Social scientist들이 social support의 role을 인식하여 개발한 유용한 categorization schema이다. 해당 스키마는 다음 5가지 범주로 나눠진다 :  

*informational support* : providing information or advice  
*instrumental support* : expression willingness(기꺼이 하는 마음) to help in a tangible(실재하는) way or actually do so  
*esteem support* : communicating respect and confidence in abilities by acts such as complimenting(칭찬하기) one
*network support* : communicating(소통) belonging to a group of people with similar experiences
*emotional support* : communicating concern(우려, 걱정), or empathy  

그러나 social support indicators의 validity(타당성)과 reliability(신뢰성)을 평가하기 위한 노력은 타 문헌에서 부족한 것으로 알려져있다. 특정 사람이 특정 support mechanism에 어떻게 반응하는지를 이해하면 질병에 대한 저항과 회복 뿐만 아니라 psychological adjustment(심리적 조정), efficacy(효능)을 향상시키는 tailored ways(맞춤형 방법)를 개발할 수 있을 것이다. 본 연구는 online mental health support community들을 연구하고, comment들을 통한 support의 type 뿐만 아니라 lignuistic attribute(속성)가 future risk나 distress(고통)과 어떻게 관련될 수 있는지를 이해함으로써 이러한 individual-level difference를 탐구하려고 노력한다.  


## Online Communities and Social Support
*Health Efficacy and Online Support*  
암에서 당뇨에 이르는 다양한 health, well-being 문제에 대한 social support를 개인이 이끌어내고, 제공할 수 있도록 online community가 수행하는 중요한 role을 조사했다. Online community는 질병별 guidance(지침) 및 feedback, emotional support, coping and management strategy(대처 및 관리 전략)을 모색할 수 있는 강력한 platform으로 확인되었다.  

Mental health 영역의 최근 meta-analysis에서는 online support가 depression을 감소시키고, self-efficacy와 quality of life를 증가시킴을 나타낸다. 다른 연구에서는 health concern을 갖는 것과 health-related social support를 찾는 것 사이의 positive relationship(양의 상관관계)를 찾기 위해 Facebook 유저들을 조사하였다. 또 다른 연구에서는 sexual abuse(성적 학대)를 당한 사람이 Reddit의 online community들에서 정서적 건강을 위해 어떻게 support를 seek(sought) 하는지에 대해 연구했다. **본 연구는 서로 다른 mental health Reddit community들에서 suicidal ideation risk와 support 사이의 연관성을 정량적으로 발견할 수 있는지로 연구를 확장했다.**  

*Causality*  
위에 언급한 연구는 online support가 health와 well-being의 증진에 잠재적으로 도움이 될 수 있는지 여부에 대한 귀중한 insight를 제공한다. 하지만 연구진은 미래의 건강 결과에 대한 influence를 정량화하고 측정하는 것 사이에 상당한 gap이 존재한다는 것에 주목한다. 이런 문제를 해결하기 위해 다른 연구진들은 유방암을 앓고 있는 사람들을 위한 online support community의 효과를 평가하는 clinical trials(임상 실험)를 수행했다. 12주 간 online support group인 BosomBuddies에 대한 접근 권한이 있는 그룹과 없는 그룹, 둘을 비교하는 연구를 진행했는데 접근했던 그룹 쪽이 depression(우울증), perceived stress, cancer-related trauma가 감소했다고 보고했다.  



# Data
## Identifying At-Risk Individuals  
데이터 수집의 시작으로, 연구진은 Reddit의 mental health post dataset에 접근했다. 이 dataset은 14개의 mental health subreddit(**MH**)과 Reddit의 저명한 suicide support community(**SW**) 44,262명의 unique user들로부터 79,833개의 post들을 모은 것이고, 해당 데이터는 2014 February 11 ~ 2014 November 11 사이의 기간에 수집되었다. 이 모든 subreddit들은 public content를 제공하며, 이전 연구에서 mental health experts에 의해 mental health 및 suicidal ideation을 support하는 community라는 것이 examine(검사)되고 validate(검증)되었다.  
De Choudhury 외 의 연구에서 개발된 방법에 따라 연구진은 두 가지의 user class를 구성했다.  

첫 번째 - 자신의 mental health concern에 대해서 MH에 먼저(t1 time period) posting한 후, 나중에(t2 time period) SW에서 suicidal ideation에 대해 posting하는 것이 관찰된 user 집단을 식별했다.  
두 번째 - t1 time period에 MH subreddit에 posting을 했지만, SW에서 t1 또는 t2에 posting한 것을 관찰할 수 없었던 두 번째 user 집단을 식별한다.  

연구진은 선행 연구에서 그랬던 것처럼 t1을 Feb 11 2014 to Aug 11 2014 로 잡았고, t2를 Aug 12 2014 to Nov 11 2014로 잡았다. 전자(첫 번째 user set)는 미래에 suicidal ideation risk에 처하게 되는 집단으로, 본 논문에서는 *MH->SW*로 표기하며, 후자는 risk(위험)에 처하지 않은 user set으로, 본 논문에서 *MH*라고 분류했다. 이러한 approach를 이용해 440명의 *MH->SW* group user들을 파악해낼 수 있었다. *MH* user들의 경우 **propensity score matching** framework에 들어가는 class 크기의 균형을 맞추기 위해 t1 시간대와 t2 시간대에 SW에 posting한 적이 없는 28,831명의 user로부터 randomly sampling해서 *MH->SW* group과 동일한 수(440명)의 user를 얻었다. De Choudhury 외 의 연구에서 언급되었듯, *MH*의 28,831명의 user 중 일부는 dataset 수집 기간(t2) 이후에 SW에 posting 했을 수 있는 점을 주의해야 하지만 dataset의 large timespan이 파생된 class들의 purity에 충분한 confidence를 준다고 판단했다.  


## Commentary Data
본 논문의 목표는 social media에서 드러나는 social support가 사람들의 suicidal ideation risk에 대해 수행할 수 있는 role을 평가하는 것이다. 위에서 언급한 440명의 *MH->SW* user들과 440명의 *MH* user들의 Reddit post에 대한 comment들을 social support의 proxy로 간주한다. 위에 언급한 두 class의 880명의 user들 각각에 대한 post를 group화한 다음 공식 Reddit API를 이용해 각 post의 전체 comment thread(the last 1000 comments?)를 얻었다. 이렇게 수집한 comment thread에는 post에 달린 각 comment들의 내용(text), 각 comment의 author(username), 그리고 UTC(협정 세계 표준시)로 된 timestamp를 포함되어 있다.  

*MH->SW* : 32,362명의 unique user들로부터 받은 62,024 comments.  
*MH* : 21,358명의 unique user들로부터 받은 41,894 comments.  
Figure 1은 두 user class들에 해당하는 comment data의 descriptive statistics를 제공하고 있다.  



# Method
Comment를 통해 social support를 받는 것이 개인의 suicidal ideation risk에(혹은 *MH->SW*에 속하게 될 가능성에) 어떻게 영향을 미치는지 연구하기 위해, 연구진은 결과에 대한 comment의 effect와 혼동할 수 있는 다른 요인을 분리하려고 한다. **Randomized controlled trial(RTC)**를 이용했는데, 물론 윤리적 혹은 현실적인 한계로 인해 RTC 시행이 항상 실현 가능한 것은 아니다. 그래서 본 논문에서는  


## Terminology and Data Preparation
연구진의 분석 단위는 개별 Reddit 사용자이며, 이 user들의 experience는 posts에 대한 다른 사용자의 comments뿐만 아니라 이들이 작성한 MH community의 posts로도 특징지어진다. 이러한 post와 comment를 타임스탬프된 언어 token 또는 n-grams(n = 2)의 사용자별 시퀀스로 특징으로 하며, 소문자 및 중지 단어가 제거된다. 분석 결과, 사용자의 타임라인에 나타나는 모든 comment token은 해당 사용자에 대한 treatment이다. 즉, user가 작성한 post에 해당 toekn이 포함된 comment를 받았으면, 일정한 treatment를 받았다고 하는 것이다. 주어진 treatment 이전에 발생하는 user timeline의 모든 posts와 comment token들은 **covariate(공변량)**으로 간주되며, user의 치료 효과 결과(user가 추후 *MH->SW*에 posting을 할 것인지, 그렇지 않을 것인지)에 대한 분석에서 혼동을 유발하는 요인으로 여겨진다.  


## Stratified Propensity Score Analysis
**Stratified Propensity Score Analysis**  
estimated propensity는 사용자의 covariates(모든 이전 post와 comment token들)를 기반으로 user가 치료를 받을 가능성에 대한 machine-learnend function이다. 일단 연구진들의 방법으로 user를 계층화한 후, common support를 가진 계층들을 분석한다. 각 계층에서 treatment effect는 treatment group과 control group의 측정된 outcomes 간의 차이를 의미한다. 이는 *MH->SW*에 참여하는 treated user들의 비율과 control user들의 percentage 차이이다. 연구진은 propensity score estimation과 stratification(계층화)를 포함한 이러한 procedure를 각 target treatment token들에 대해서 반복 수행했다.  


## Implementation
Propensity score function은 **averaged perceptron learning algorithm**에 의해서 estimate된다. Estimation은 user의 timeline에 나타나는 binary vector를 기반으로 수행이 된다. Binary vector는 H = h1, ... hn으로 구성이 되어있는데 여기서 각 hi는 treatment token을 받기 이전에 user의 타임라인에 공유된 post 및 comment에 token i가 나타난 경우 해당 건에 대해서 1이고, 그렇지 않으면 0이다. 통계적 유의성에 대한 z-score와 카이 제곱 tests를 보고했다. MH community에서 10명 이상의 user의 timeline에서 발생하는 모든 n-gram token(11,278개)에 대해서 이 분석을 수행한다.  



# Validating Comparability
향후 user가 *MH->SW* 또는 *MH*에 속할 risk에 대한 comment의 영향을 평가할 때, 연구진의 계층화 된(stratified) 분석은 특정 comment를 받은 treatment group과 그렇지 않은 user들로 이루어진 control group 사이를 비교하고 있다. RCT와는 다르게 본 연구에서는 처리가 관찰되지 않은 covariate들과 독립적이라는 것을 보장하지 않는다. (machine learning 관점에서 잘못 표현된 연구진들의 covariate set과 무관함.) 이렇게 하면 confounded result가 초래될 수 있다. 따라서 stratified group이 정확하게 균형을 이루도록 보장하는 것은 user가 *MH->SW* 또는 *MH*에 있을 가능성과 같은 결과의 정확한 추정에 중요하다.  
이 목표를 위해, 이 절에서는 **human judges**를 이용하여 treatment와 control group 사이의 comparability(또는 balance)를 질적으로 먼저 평가하는 접근법을 설명한다. Human judgement를 사용한 후, 두 group 사이의 sociolinguistic(사회 언어학의) 측정과 language model의 잠재적인 차이에 대해 정량적으로 측정한다. 이 두 접근 방식을 함께 사용하면 treatment group과 control group의 subpopluation을 식별하고, post의 comment에 영향을 받을 가능성이 높은 user를 제어할 수 있다.  


## Qualitative Analysis of Balance
연구진은 먼저 dataset에 있는 880명의 user의 MH posts와 comments에서 제안된 **propensity score matching technique**을 구현했다. 연구진은 통계적으로 유의한 치료 효과가 있는 token을 식별했다. Negative effect는 comment token을 받는 것이 *MH->SW*에 있을 가능성을 감소시켰다는 것을 의미하며, positive effect는 그 반대를 의미한다. 연구진은 150개의 most positive(or negative) z-score에 기반해 150개의 token을 randomly sampling 했다. 그 후, 각 strata(comment token 당)에 대해 treatment group에서 10명의 user, control group에서 10명의 user를 무작위로 선택한다. 이 user 각각에 대해 treatment token(control의 경우 placebo)을 받을 때까지 해당 user의 최근 post와 해당 post에 대한 모든 comment들을 선택한다.  

다음으로는 위에서 생성된 post pair의 balance를 질적으로 추정하기 위해 two rater(an expert in social media data analysis for mental health and a mental health professional)를 고용했다. Rater에게 주어진 목표는 post pair에서 suicidal ideation의 risk marker를 식별하는 것이었는데, 이는 propensity score analysis에서는 관찰할 수 없을 수 있지만 suicidal ideation의 risk가 있는 사람의 행동 관찰(observations of behaviors)과 일치한다. Post pair에서 marker가 align된 경우, 특정 comment token과 strata가 균형을 이루도록 treatment, control group을 추론할 수 있다. 그렇지 않다면, 연구진은 initial propensity score matching analysis가 더 정확하게 균형 잡힌 treatment, control group을 식별하기 위해 추가적인 조정이 필요하다고 가정할 것이다.  

이를 위해, rater들은 De Choudhury et al. 2016에서 개발된 **a codebook of suicidal ideation risk markers**을 활용하여 100개의 post pair의 random sample을 balanced(very similar : rating of 1) 또는 imbalanced(very dissimilar : rating of 0)으로 독립적으로 등급을 매겼다.  
balance, imbalance 추정을 위해 200개의 post pair의 더 큰 표본에 rating을 하였고, 두 rater들 사이의 final agreement는 코헨's kappa 계수 0.81로 유사도가 높은 것으로 나타났다.  

Post pair의 qualitative coding에서 흥미로운 pattern이 나타났다. Figure 3을 보면 알 수 있듯, 분포가 nearly mirror image이다. balance rating의 경우 higher propensity strata에 속하는 post pair 중에서 더 빈번한 경향이 있는 반면, imbalance rating의 경우, lower propensity strata에서 peak이다. 


## Quantitative Analysis of Subpopulation Differences
앞서서 언급된 balance analysis는 comment에서 token을 얻는 효과가 동일하지 않을 수 있음(not be homogeneous)을 보여주었다. 일부 user는 token을 얻을 때(low propensity strata) 거의 효과를 보지 못하는 반면, 다른 user는 큰 효과(higher propensity strata)를 볼 수 있다. 본질적으로, high propensity strata와 low에 속하는 subpopulations of users는 어떤 면에서 다른 것인가? 이는 서로 다른 characteristics(특성)를 가진 사용자가 향후 MH->SW에 있을 가능성에서 그들이 수신하는 comment에 나타나는 특정 token에 의해 영향을 덜 받을 수 있는지, 또는 어떻게 더 많이 받을 가능성이 있는지를 이해하기 위한 중요한 고려 사항(important consideration)이다. 이러한 질문에 답하고, qualitative(정성적) balance assessment에 더 많은 신빙성, 신뢰도를 주기 위해 다음과 같은 quantitative approach(정량적 접근법)를 채택했다. **LIWC 사전**을 이용하여 high propensity strata( > 3)와 low propensity strata(<= 3)의 두 subpopulation의 post에 존재하는 다양한 sociolinguistic 정도를 정량화한다. 이들을 각각 subpopulation H와 L로 부른다.  

"Diff" 지표가 주어지는 것처럼 subpopulation 전체에 걸쳐 유의한 차이를 관찰한다. "Diff"는 subpopulation H의 mental health post에서 특정 측정 값과 L의 측정값 사이의 상대적 백분율 차이이다. Subpopulation H는 그들의 post에 눈에 띄게 낮은 anger, sadness, NA를 표현하는 경향이 있다. 또한 그들의 post는 낮은 inhibition(억제율)과 높은 cognitive processing(인지 처리)를 보여준다. 어휘 밀도 및 인식의 측정에서 볼 수 있듯, H는 그들의 context와 environment에 대한 더 많은 인식을 제시한다. 흥미롭게도, H는 그들의 건강과 일에 대해 더 많이 공유하고, 사회와 가족과 관련된 관심사에 대해 더 많이 토론하는 경향이 있다. L과 비교하여 H는 1인칭 단수 대명사(1st person singular pronouns) 사용에서 언급된 낮은 자기 집중 또는 자기 선입견을 보이는 경향이 있다. 반대로, post에서 2인칭 대명사와 3인칭 대명사 사용을 통해 대인관계에 초점을 더 맞추는 경향이 있다.  



# Results
## Propensity Score Analysis
User가 작성한 post에 달린 comment에 의해 영향을 받을 가능성이 있는 reliably(신뢰할 수 있는) balanced strata(>3)를 식별하면 stratified propensity score algorithm를 조정하여 다른 계층은 무시한 다음, 나머지 strata에서 treatment와 control user들에 대한 최종 결과 효과(final outcome effect)를 계산한다. Well-balanced strata에서만 계산이 되기 때문에 local average treatment effect는 user population에 대한 적용 범위에서 제한적일 수밖에 없지만, 특정 comment token의 effect에 대해서 더 신뢰할 수 있는 추정치를 나타낸다. Table 5에서 *MH->SW* user와 *MH* user를 구별하는 데 가장 많은 negative or positive z score를 준 40개의 comment token을 보고한다. 각 token에 대하여, dataset의 absolute number of users(880명 중)가 그들의 comment들 중 token을 받은 경우(treatment count), comment에서 token을 얻은 것을 기반으로 추후 *MH->SW*에 속할 percent increase(local average treatment effect), ...  


## Exploring Context of Use of Comment Tokens
다음에는 위에서 식별된 significant comment tokens(negative or positive 40개)의 사용 상황을 살펴본다. 이 분석은 서로 다른 유형의 social support가 *MH->SW* 또는 *MH*에 있는 outcome과 어떻게 관련되는지 이해할 수 있도록 하기 위한 것이다.  
Table 6에서 발췌한 comment는 향후 *MH->SW*에 있을 가능성에 큰 영향을 미치는 것으로 확인된 token이 어떤 방식으로 social support context에서 사용되는지를 이해하는 데 도움이 된다. 



**Perceptron**  
퍼셉트론은 초기 형태의 인공 신경망으로, 다수의 입력으로부터 하나의 결과를 내보내는 알고리즘이다. 각각의 입력값 x는 각각의 가중치 W와 함께 y라는 종착지에 전달이 된다. 가중치의 값이 크면 클수록 해당 입력 값이 중요하다는 것을 의미하는 것. 