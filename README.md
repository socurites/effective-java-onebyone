# effective-java-onebyone
* 하루에 1개씩

## 핵심 기본 원칙: Clarity & SImplicity
* 컴포넌트는 사용자를 놀라게하는 동작을 해서는 안된다
  * 정해진 동작이나 예측할 수 있는 동작만 수행해야 한다
* 컴포넌트는 가능한 한 작되, 그렇다고 너무 작아서는 안된다
* 코드는 복사되는 게 아니라 재사용되어야 한다
* 컴포넌트 사이의 의존성은 최소로 유지해야 한다
* 오류는 만들어지자마자 가능한 한 빨리 (되조록 컴파일타임에) 잡아야 한다

---
## 객체 생성과 파괴
1. 
2. 
3. 
4. 
5.
6. 
7. 
8. 
9. 

---
## 모든 객체의 공통 메서드
10. 
11. 
12. 
13. 
14.

---
## 클래스와 인터페이스
15. 
16.
17.
18.
19.
20.
21.
22.
23.
24.
25.

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
- [x]  42.익명 클래스보다는 람다를 사용하라 (2020.07.02)
- [ ]  43.람다보다는 메서드 참조를 사용하라
- [ ]  44.표준 함수형 인터페이스를 사용하라
- [ ]  45.스트림은 주의해서 사용하라
- [ ]  46.스트림에서는 부작용 없는 함수를 사용하라
- [ ]  47.반환 타입으로는 스트림보다 컬렉션이 낫다
- [ ]  48.스트림 병렬화는 주의해서 적용하라

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
- [ ]  78.공유 중인 가변 데이터는 동기화해서 사용하라
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