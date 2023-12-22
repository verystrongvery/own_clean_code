# SOLID
1) Single Responsibility Principle
    - 클래스는 하나의 책임만 가져야 함
    - 요구사항이 변경될때, 해당 부분만 변경하면 되므로 유지보수를 높여줌
2) Open Closed Principle
    - 확장에는 열려있고, 변경에는 닫혀 있어야 함
    - 요구사항이 추가될때, 기존 코드의 수정은 최소화하면서 기능을 확장하여 유지보수를 높여줌
3) Liskov Substitution Principle
    - 자식 클래스를 부모 클래스로 대체하더라도, 기존의 코드와 똑같이 동작되어야 함
    - 코드의 유연성과 확정성을 높여, 유지보수하기 쉬워짐
4) Interface Segregation Principle
    - 인터페이스를 잘 분리함으로써, 인터페이스를 구현하는 클래스는 필요한 메서드만 오버라이딩 해야함
    - 불필요한 종속성을 줄여, 유지보수하기 쉬워짐
5) Dependency Inversion Principle
    - 구현 클래스 대신, 인터페이스에 의존해야함
    - 클래스간의 결합도를 낮춰, 유지보수하기 쉬워짐
