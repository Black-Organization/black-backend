# black-backend



# 테스트
정확한 용어 알고 사용하기
cf) https://docs.python.org/3/library/unittest.html

애플리케이션 컴포넌트 및 모듈을 테스트하는 환경의 일부분으로, 테스트를 지원하기 위한 코드와 데이터를 테스트 하네스(Test Harness)라고 한다. 하향식 통합 방식은 메인 제어 모듈로부터 아래 방향으로 제어의 경로를 따라 이동하면서 하향식으로 통합하며 테스트를 진행하고, 아직 작성되지 않은 하위 제어 모듈 및 모든 하위 컴포넌트를 대신하여 더미 모듈인 테스트 스텁(Stub)을 사용한다. 상향식 통합 방식은 애플리케이션 구조에서 최하위 레벨의 모듈 또는 컴포넌트 위쪽 방향으로 제어의 경로를 따라 이동하면서 구축과 테스트를 시작하며, 상위의 모듈에서 데이터의 입력과 출력을 확인하기 위한 더미 모듈인 '테스트 드라이버(Driver)'를 작성한다.

- 정보처리기사 실기 2021년 2회 기출, 출제: 애플리케이션 테스트 관리 2강
- 정보처리기사를 공부해야하는 이유에 대한 답을 이 개념으로 대체한다.


- test fixture
> A test fixture represents the preparation needed to perform one or more tests, and any associated cleanup actions. This may involve, for example, creating temporary or proxy databases, directories, or starting a server process.

- test case
> A test case is the individual unit of testing. It checks for a specific response to a particular set of inputs. unittest provides a base class, TestCase, which may be used to create new test cases.

- test suite
> A test suite is a collection of test cases, test suites, or both. It is used to aggregate tests that should be executed together.

- test runner
> A test runner is a component which orchestrates the execution of tests and provides the outcome to the user. The runner may use a graphical interface, a textual interface, or return a special value to indicate the results of executing the tests.

https://github.com/getsentry/responses
> requests 라이브러리 전용 mocking 

# 타입
https://docs.python.org/3/library/stdtypes.html#type-annotation-types-generic-alias-union

# 보안
https://github.com/shieldfy/API-Security-Checklist



# materials)
- https://github.com/tiangolo/full-stack-fastapi-postgresql
- https://github.com/teamhide/fastapi-boilerplate
- https://testdriven.io/blog/topics/fastapi/
