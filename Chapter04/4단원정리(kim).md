# 데이터 모델 ⇒ 데이터구조,연산,제약조건으로 구성

### 개념적 모델링 ⇒ 현실세계의 중요한 데이터를 추출하여 개념 세계로 옮기는 작업이다

### ⇒ 객체-관계 모델이 가장 많이 사용

개체(현실세계에서 구별할 수 있는 모든것),

속성(개체가 가지고 있는 특성),

관계(개체와 개체가 맺고 있는 의미있는 연관성)으로 구성

⇒관계의 유형에는 이항관계(개체타입 두개가 맺음),삼항관계(개체타입 3개가 맺음),순환단계(개체타입하나가 자기자신과 맺음)가 있다

⇒1:1의 관계,1:n의 관계,n:m의 관계가 있다

관계의 참여특성()

관계의 종속성(두 개체가 관계에 대해 종속정인 특성을 가짐)

### 논리적 모델링 ⇒ 개념 세계의 데이터를 데이터베이스에 저장할 구조를 결정하고 표현하는 작업이다 ⇒결과물은 논리적 모델

### ⇒관계 데이터 모델이 가장 많이 사용됨

⇒논리적 구조가 트리형태이다

⇒다대다의 관계를 직접적으로 표현할 수 없어서 대안으로 별도의 개체를 추가적으로 생성하여 사용한다

### ⇒ 네트워크 데이터 모델

⇒ 논리적 구조가 그래프,네트워크의 형태이다

⇒ 두 개체간의 관계를 여러개 정의할 수 있다. ⇒ 관계를 이름으로 구별

⇒관계 데이터 모델보다 개념적 구조를 논리적 구조로 좀더 자유롭게 모델링 가능 ⇒ but 데이터

삽입,삭제 수정과 같은 연산과, 데이터 검색이 더 어려워진다
