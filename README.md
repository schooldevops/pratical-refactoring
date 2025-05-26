# Pratical Refactoring with UncleBae


## 실무 적용 단계별 접근법

### 1단계: 문제 파악

- 현재 코드의 문제점 식별 (중첩 깊이, 메서드 길이, 책임 분산 등)
- 비즈니스 요구사항과 향후 변경 가능성 분석
- 팀의 기술 수준과 프로젝트 일정 고려

### 2단계: 전략 선택

- 프로젝트 규모와 복잡도에 맞는 리팩토링 전략 선택
- 단순한 것부터 시작하여 점진적으로 개선
- 팀 내 합의를 통한 일관된 접근법 채택

### 3단계: 점진적 리팩토링

- 기존 기능을 유지하면서 작은 단위로 리팩토링
- 각 단계마다 테스트를 통한 검증
- 코드 리뷰를 통한 품질 관리

### 4단계: 지속적인 개선

- 정기적인 코드 품질 점검
- 새로운 요구사항 발생 시 설계 원칙 준수
- 팀 내 리팩토링 경험 공유 및 학습

## 실전 유즈케이스별 리팩토링 전략

### [01. Java 중첩 if 구문에 대한 Refactoring 전략](01.RefactoringOfNestedIf.md)

### [02. 메소드내 메소드가 반복되는 중첩메서드 해결전략](02.RefactoringOfNestedMethod.md)


### [03. 긴 메서드 리팩토링 전략](03.RefactoringLongMethod.md)
- 메서드 추출 (Extract Method)
- 메서드 객체로 전환 (Replace Method with Method Object)
- 알고리즘 교체 (Substitute Algorithm)

### [04. 복잡한 조건문 리팩토링 전략](04.RefactoringComplexConditionals.md)
- 조건문 분해 (Decompose Conditional)
- 가드절 도입 (Introduce Guard Clause)
- 전략 패턴 적용 (Strategy Pattern)

### [05. 데이터 클래스 리팩토링 전략](05.RefactoringDataClasses.md)
- 캡슐화 강화 (Encapsulate Field)
- 불변 객체로 전환 (Convert to Immutable)
- 빌더 패턴 적용 (Builder Pattern)

### [06. 상속 구조 리팩토링 전략](06.RefactoringInheritance.md)
- 위임으로 전환 (Replace Inheritance with Delegation)
- 인터페이스 추출 (Extract Interface)
- 컴포지션 활용 (Favor Composition)

### [07. 예외 처리 리팩토링 전략](07.RefactoringExceptionHandling.md)
- 예외 계층 구조 개선
- 커스텀 예외 도입
- 예외 처리 일관성 확보

### [08. 비동기 코드 리팩토링 전략](08.RefactoringAsyncCode.md)
- 콜백 지옥 해결
- Promise/Async-Await 패턴 적용
- 비동기 로직 모듈화