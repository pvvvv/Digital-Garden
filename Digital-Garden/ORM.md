# ORM(Oject-Relational-Mapping)
ORM은 데이터베이스와 객체지향 프로그래밍 언어간의 호환되지 않는 데이터를 변환하는 프로그래밍 기법.(객체 관계 매핑이라고도 한다)

---
- ORM이 없을 때는 개발자가 개발을 하며 DB에 접근하기 위해서 SQL Query를 직접 만들었다. 여기서 문제점은 SQL문법을 숙지, 개발코드와 DB가 서로 종속이였고 이를 해결하기위해 ORM이 등장하였다.

## 장점
- SQL 쿼리를 직접 작성하지 않아, 생산성 향상
- ORM을 통해 작성한 객체를 재활용할 수 있다는 측면에서 재사용 및 유지보수의 편리성이 증가함
- DBMS(DataBase Management System) 종속성 하락
  
## 단점
- ORM이 모든 걸 해결해줄 수 없다.  
  -> 적절하게 SQL문을 사용할 수 있어야한다.
- 복잡한 쿼리문의 경우 오히려 SQL문으로 사용이 직관적이면서 효율적일 수 있다.


언어별 ORM의 종류
>- [Java](Java.md) - [Hybernate](Hybernate.md), JPA  
>- [Node.js](Node.js.md) - [Sequalize](Sequalize.md)
>- [TypeScript](TypeScript.md) - [TypeORM](TypeORM.md)