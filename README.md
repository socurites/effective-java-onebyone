# effective-java-onebyone
* 하루에 1개씩

## 핵심 기본 원칙: Clarity & SImplicity
* 컴포넌트는 사용자를 놀라게하는 동작을 해서는 안된다
  * 정해진 동작이나 예측할 수 있는 동작만 수행해야 한다
* 컴포넌트는 가능한 한 작되, 그렇다고 너무 작아서는 안된다
* 코드는 복사되는 게 아니라 재사용되어야 한다
* 컴포넌트 사이의 의존성은 최소로 유지해야 한다
* 오류는 만들어지자마자 가능한 한 빨리 (되록 컴파일타임에) 잡아야 한다

---
## 객체 생성과 파괴
- [x] 1.생성자 대신 정적 팩터리 메서드를 고려하라 (2021.07.11)
- [x] 2.생성자에 매개변수가 많다면 빌더를 고려하라 (2021.07.12)
- [x] 3.private 생성자나 열거타입으로 싱글턴임을 보증하라 (2021.07.13)
- [x] 4.인스턴스화를 막으려거든 private 생성자를 사용하라 (2021.07.14)
- [x] 5.자원을 직접 명시하지 말고 의존 객체 주입을 사용하라 (2021.07.14)
- [x] 6.불필요한 객체 생성을 피하라 (2021.07.15)
- [x] 7.다 쓴 객체 참조를 해제하라 (2021.07.15)
- [x] 8.finalizer와 cleaner 사용을 피하라 (2021.07.16)
- [x] 9.try-finally보다는 try-with-resources를 사용하라 (2021.07.16) 

---
## 모든 객체의 공통 메서드
- [x] 10.equals는 일반 규약을 지켜 재정의하라 (2021.07.17)
- [x] 11.equals를 재정의하려거든 hashCode도 재정의하라 (2021.07.19)
- [x] 12.toString을 항상 재정의하라 (2021.07.20)
- [x] 13.clone 재정의는 주의해서 진행하라 (2021.07.21)
- [x] 14.Comparable을 구현할지 고려하라 (2021.08.12)

---
## 클래스와 인터페이스
- [x] 15.클래스와 멤버의 접근 권한을 최소화하라 (2021.08.17)
- [x] 16.public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라 (2021.08.19)
- [x] 17.변경 가능성을 최소화하라 (2021.08.20)
- [x] 18.상속보다는 컴포지션을 사용하라 (2021.08.21)
- [ ] 19.상속을 고려해 설계하고 문서화화라. 그러지 않았다면 상속을 금지하라
- [ ] 20.추상 클래스보다는 인터페이스를 우선하라
- [ ] 21.인터페이스는 구현하는 쪽을 생각해 설계하라
- [ ] 22.인터페이스는 타입을 정의하는 용도로만 사용하라
- [ ] 23.태그 달린 클래스보다는 클래스 계층구조를 활용하라
- [ ] 24.멤버 클래스는 되도록 static으로 만들라
- [ ] 25.톱레벨 클래스는 한 파일에 하나만 담으라

---
## 제네릭
26. 
27. 
28.
29.
30.
31.
32.
33.

---
## 열거 타입과 어노테이션
34. 
35.
36.
37.
38.
39.
40.
41.

---
## 람다와 스트림
- [x]  42.익명 클래스보다는 람다를 사용하라 (2021.07.03)
- [x]  43.람다보다는 메서드 참조를 사용하라 (2021.07.04)
- [x]  44.표준 함수형 인터페이스를 사용하라 (2021.07.05)
- [x]  45.스트림은 주의해서 사용하라 (20210.07.06)
- [x]  46.스트림에서는 부작용 없는 함수를 사용하라 (2021.07.07)
- [x]  47.반환 타입으로는 스트림보다 컬렉션이 낫다 (2021.07.08)
- [x]  48.스트림 병렬화는 주의해서 적용하라 (2021.07.09)

---
## 메서드
49.
50.
51.
52.
53.
54.
55.
56.

---
## 일반적인 프로그래밍 원칙
57.
58.
59.
60.
61.
62.
63.
64.
65.
66.
67.
68.

---
## 에외
69.
70.
71.
72.
73.
74.
75.
76.
77.

---
## 동시성
- [x]  78.공유 중인 가변 데이터는 동기화해서 사용하라 (2020.07.10)
- [ ]  79.과도한 동기화는 피하라
- [ ]  80.Thread보다는 Executor, Task, Stream을 애용하라
- [ ]  81.wait과 notify보다는 java.util.concurrent를 애용하라
- [ ]  82.스레드 안전성 수준을 문서화하라
- [ ]  83.지연 초기화는 신중히 사용하라
- [ ]  84.프로그램의 동작을 스레드 스케줄러에 기대지 말라

---
## 직렬화
- [ ]  85.자바 직렬화의 대안을 찾으라
- [ ]  86.Serializable을 구현할지는 신중히 결정하라
- [ ]  87.커스텀 직렬화 형태를 고려해 보라
- [ ]  88.readObjecft 메서드는 방어적으로 작성하라
- [ ]  89.인스턴스 수를 통제해야 한다면 readResolve보다는 열거타입을 사용하라
- [ ]  90.직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라
