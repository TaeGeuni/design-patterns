# Go Design Patterns 🧠

이 저장소는 [Go (Golang)](https://golang.org/) 언어로 구현한 디자인 패턴 예제 모음입니다.  
각 패턴은 간단한 설명과 함께 예제 코드로 구성되어 있으며, 실무에서 어떻게 활용할 수 있는지도 함께 정리하고자 합니다.

## 📌 패턴 목록

| 분류 | 패턴 | 설명 | 예제 |
|------|------|------|------|
| 생성 패턴 | Singleton | 하나의 인스턴스만 존재하도록 보장 | [예제 보기](./creational/singleton/main.go) |
| 생성 패턴 | Factory Method | 객체 생성 로직을 서브클래스로 분리 | [예제 보기](./creational/factory_method/main.go) |
| 행동 패턴 | Strategy | 알고리즘을 런타임에 교체 가능 | [예제 보기](./behavioral/strategy/main.go) |
| 행동 패턴 | Observer | 객체의 상태 변화를 구독자에게 알림 | [예제 보기](./behavioral/observer/main.go) |
| 구조 패턴 | Decorator | 기능을 동적으로 추가 | [예제 보기](./structural/decorator/main.go) |

> 📂 예제는 패턴별로 `creational/`, `structural/`, `behavioral/` 폴더에 정리되어 있습니다.

## 🚀 실행 방법

```bash
# 예: 싱글톤 패턴 실행
cd creational/singleton
go run main.go
```

## 📖 참고 자료
- [Refactoring Guru - Design Patterns in Go](https://refactoring.guru/ko/design-patterns/go)
- 공식 문서: [Go by Example](https://gobyexample.com/)