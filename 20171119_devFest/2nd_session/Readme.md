# 2. 음성인식 기반 인공지능 챗봇 빠르게 만들어보기

### 서론
현재 챗봇은 관심이 조금 줄은 상태이다  
챗봇은 **어린이** 와 같다고 보아도 무방

example ) 사과에 대한 이야기  
Q : 사과 좀 주세요
A : 죄송합니다 (???)  
  
**사람이 대화를 할 때에는 정해진 규칙, 정해진 장소, 대화의 분위기 파악, 눈치 등 고려해야 할 요소가 많다**
  
그럼 저 사과한 어린이(?)는 어떻게 발전할 수 있을까?
- 언어적인 이해와 경험 향상 (사람에게 사과를 받고 싶을 때는 좋아한다고 말하지 않는구나!!)
- 스스로 패턴을 확인 (국어 공부를 열심히하며 해당 언어를 이해!!)

(정리) 챗봇을 위해 필요한 기술
- 패턴인식 / 자연어 처리 / 데이터마이닝 / 지능엔진 / 자동추론 / 시멘틱웹  (많다....)
  
그러면 사람의 대화에 입각하여 가장 중요하게 생각해야 할 3요소는?
- 대화의 ‘의도’ (Intent)
- 대화의 ‘재료’ (Entity)
- 대화의 ‘분위기’ (Context)
- 대화의 경험을 쌓고 '응용' (Training)
  
### 지금부터 쇼핑몰 챗봇으로 이야기를 해보겠습니다.

아까 말했던 3~4요소를 쇼핑몰과 연계하여 생각하면?
- 대화의 ‘의도’ (Intent)  
  쇼핑몰이 가지고 있는 **상품 목록**  
- 대화의 ‘재료’ (Entity)  
  쇼핑몰 **상담목록** / 쇼핑몰 직원의 **대화록**  
- 대화의 ‘분위기’ (Context)  
  기존 대화에 대한 **분석, 직관, 상황 설정**  
- 대화의 경험을 쌓고 응용 (Training)  
  대화록 입력 또는 실제 대화의 내용을 보고 **교육**  
  
DialogFlow  
- 대화의 Intent  
  기본 인사법 (Small Talk) - 기본 재공  
	문장을 입력하면 어느정도 엔티티를 뽑아냄  
  
- 대화의 재료 Entity  
  Google Natural Language API (완벽하진 않지만 효과를 낼 수 있다)	 
  CSV로 바로 올림
  
- 대화의 분위기 Context  
  대화의 기술 가르치기, 분위기