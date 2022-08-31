# Practice SQL

## Install

```
// for macOS
$ brew install postgresql pgadmin4
$ brew services restart postgresql

//for windows
$ scoop install postgresql
$ pg_ctl stop
$ del /s /f /q $HOME\apps\postgresql\current\data\
$ initdb -U postgres
$ pg_ctl start
```

## [Essential SQLAlchemy 2nd](https://www.oreilly.com/library/view/essential-sqlalchemy/9780596516147/)
- `SQLAlchemy`의 [`문서`](https://docs.sqlalchemy.org/en/14/)도 훌륭하다. 해당 문서를 기반으로 코드 연습이 필요하신 분들에게 적합한 책이다. `SQLAlchemy`에 처음 접하는 분이나 Python 코드로 ORM 관련 코드를 연습하셔야 된다면 추천한다.

## [SQL로 시작하는 데이터 분석](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=298955770)

* 예제는 [이곳](https://github.com/sql-for-data-analysis-kr/book)에서 확인하시고, RDBMS 관련 설정은 교재를 참고하세요.
