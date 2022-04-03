# 2022년 4월 3일

## 트리거 기본 내용(주형준 발표 내역)
- if new.name <> old.name then 
- end if
- concat('테스트', '입니다');
- 수정한 내역은 따로 로그 테이블을 만들어서, 내역을 쌓게 된다. 
- EDD / CDD 
- 트리거의 단점: 의존성이 강하다 | 컬럼 하나를 수정하면 나머지도 다 수정을 해야 하기 때문이다.

## 추상클래스 및 인터페이스
- 인터페이스: HAS A : ~을 할 수 잇는
- 추상클래스: IS A : ~이다.
- 추상클래스가 추상클래스를 extends를 해서 override 할 때 모든 메소드를 정의하자 않아도 된다.
- 추상클래스가 추상클래스를 상속해서 사용하는 경우는 거의 없다.
- 인터페이스를 사용할 때 일종의 모듈로 사용할 
- public class Pigeon extends Animal implements Flyable {}
- interface 안에서 abstract를 사용 
