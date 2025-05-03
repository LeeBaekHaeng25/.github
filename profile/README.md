# 전자정부 표준프레임워크 4.3.0 컨트리뷰션

컨트리뷰션 대상
- DAO 단위 테스트
- ServiceImpl 단위 테스트
- Controller 단위 테스트
- 셀레늄(화면) 단위 테스트
- 이클립스 Problems 제거
- PMD로 소프트웨어 보안약점 진단하고 제거하기
- 시큐어코딩 일련번호 PK 파라미터 암복호화
- 검색 조건 유지
- 롬복 생성자 기반 종속성 주입
- CRUD 프로그램 자동 생생 기능 템플릿 수정

유튜브

https://www.youtube.com/playlist?list=PL6pSCmAEuNPE0vLtodu2geX-SA1YO6ALg

|날짜|제목|공유링크|
|-|-|-|
|2025-04-12 토|전자정부 표준프레임워크 4.3.0 컨트리뷰션 준비|https://youtu.be/G82xDweUsX4|
|2025-04-19 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기](#2025-04-19-토-pmd로-소프트웨어-보안약점-진단하고-제거하기)|https://youtu.be/QKyUDsitx90|
|2025-04-20 일|[test PMD-AltibaseClobStringTypeHandler](#2025-04-20-일-test-pmd-altibaseclobstringtypehandler)|https://youtu.be/_oS7O1awbA0|
|2025-04-21 월|[test PMD-EgovComCrossSiteHndlr](#2025-04-21-월-test-pmd-egovcomcrosssitehndlr)|https://youtu.be/3_07tmsmeys|
|2025-04-22 화|[test PMD-EgovWebApplicationInitializer](#2025-04-22-화-test-pmd-egovwebapplicationinitializer)|https://youtu.be/v8z63Dahg_k|
|2025-04-23 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter](#2025-04-23-수-test-pmd-htmltagfilter)|https://youtu.be/uqPuU5rEFKs|
|2025-04-24 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper](#2025-04-24-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-htmltagfilterrequestwrapper)|https://youtu.be/FB3kPtOyD6w|
|2025-04-25 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter](#2025-04-25-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-sessiontimeoutcookiefilter)|https://youtu.be/aA8nZ0QeFkM|
|2025-04-26 토|||
|2025-04-28 월|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil](#2025-04-28-월-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilemngutil)|https://youtu.be/bjEDZsm9_4Y|
|2025-04-29 화|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils](#2025-04-29-화-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-filesystemutils)|https://youtu.be/185e28SJt6o|
|2025-04-30 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO](#2025-04-30-수-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomabstractdao)|https://youtu.be/6XnOPm7HZp0|
|2025-05-01 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger](#2025-05-01-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbasiclogger)|https://youtu.be/FUG2LiU_VeQ|
|2025-05-02 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil](#2025-05-02-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmybatisutil)|https://youtu.be/8YZyzeBon44|
|2025-05-03 토|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper](#2025-05-03-토-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovresourceclosehelper)|https://youtu.be/7Cu3kZxBN4o|

<hr>

셀레늄 단위 테스트

셀레늄 화면 단위 테스트

셀레늄 화면 자동화 단위 테스트

셀레늄 웹 애플리케이션 자동화 단위 테스트

셀레늄은 웹 애플리케이션 자동화 및 테스트를 위한 포터블 프레임워크이다. 셀레늄은 테스트 스크립트 언어를 학습할 필요 없이 기능 테스트를 만들기 위한 플레이백 도구를 제공한다. 

- https://www.selenium.dev/
- https://www.selenium.dev/documentation/webdriver/
- https://www.selenium.dev/documentation/webdriver/getting_started/
- https://www.selenium.dev/documentation/webdriver/getting_started/using_selenium/

<hr>

## 셀레늄 단위 테스트-게시판관리

게시판생성관리 셀레늄 단위 테스트
- 게시판 목록조회
- 게시판 생성
- 게시판 수정

https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:com:v4.3:cop:%EA%B2%8C%EC%8B%9C%ED%8C%90%EC%83%9D%EC%84%B1%EA%B4%80%EB%A6%AC

화면
- 목록 화면
- 등록 화면
- 상세 화면
- 수정 화면

<hr>

## 2025-04-19 토 PMD로 소프트웨어 보안약점 진단하고 제거하기

### 2025-04-20 일 test PMD-AltibaseClobStringTypeHandler
1. AltibaseClobStringTypeHandler
```
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:86:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_data' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:87:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_length' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:93:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

https://github.com/LeeBaekHaeng25/egovframe-common-components-25/commits/feature/pmd/test/2025/04/20/

<hr>

### 2025-04-21 월 test PMD-EgovComCrossSiteHndlr
2. EgovComCrossSiteHndlr
```
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:48:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:49:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sArrDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:103:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:155:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:162:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:174:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:185:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
```

AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```java
w.write(IOUtils.toString((Reader) obj));

String text = IOUtils.toString((Reader) obj);
writeEscapedXml(text.toCharArray(), text.length(), w);
```

<hr>

### 2025-04-22 화 test PMD-EgovWebApplicationInitializer

feature/pmd/test/2025/04/22

feature/pmd/test/EgovWebApplicationInitializer

PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebApplicationInitializer

PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource

3. EgovWebApplicationInitializer
```
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:75:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:86:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
```

```java
 // NOPMD: CloseResource
```

<hr>

### 2025-04-23 수 test PMD-HTMLTagFilter

feature/pmd/test/HTMLTagFilter

PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter

PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody

4. HTMLTagFilter
```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilter.java:43:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

https://github.com/LeeBaekHaeng25/egovframe-common-components-25/commits/feature/pmd/test/HTMLTagFilter/

<hr>

### 2025-04-24 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper

feature/pmd/test/HTMLTagFilterRequestWrapper

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions, AvoidReassigningParameters

5. HTMLTagFilterRequestWrapper
```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:117:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:124:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:154:	AvoidReassigningParameters:	AvoidReassigningParameters: 'value' 처럼 파라미터 값을 직접 변경하지 말 것
```

```java
 *   2025.04.24  이백행              PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions, AvoidReassigningParameters
```

<hr>

### 2025-04-25 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter

feature/pmd/test/SessionTimeoutCookieFilter

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody

```
src/main/java/egovframework/com/cmm/filter/SessionTimeoutCookieFilter.java:89:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

```java
 *  2025.04.25   이백행            PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody
```

<hr>

### 2025-04-28 월 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil

feature/pmd/test/EgovFileMngUtil

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions, CloseResource, LocalVariableNamingConventions, AssignmentInOperand

```
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:75:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:147:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:219:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:220:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:227:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_flag' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:239:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:291:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:292:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:299:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:347:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:348:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:368:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:400:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
```

Java 7 이상이라면 try-with-resources를 사용해서 훨씬 깔끔하고 안전하게 리소스를 관리할 수 있습니다

```java
//IOUtils.copy(inputStream, outputStream);
FileCopyUtils.copy(in, out);
```

<hr>

### 2025-04-29 화 test PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils

feature/pmd/test/FileSystemUtils

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses, AvoidReassigningParameters, CloseResource, UnusedFormalParameter

```
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:190:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:211:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:302:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:321:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:393:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:394:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:395:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:396:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:444:	UnusedFormalParameter:	UnusedFormalParameter: 'cmdAttribs' 처럼  사용되지 않는  'method' 파라미터가 있음
```

<hr>

### 2025-04-30 수 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO

feature/pmd/test/EgovComAbstractDAO

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions

```
src/main/java/egovframework/com/cmm/service/impl/EgovComAbstractDAO.java:36:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'LOGGER' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

<hr>

### 2025-05-01 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger

feature/pmd/test/EgovBasicLogger

```
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:27:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'ignoreLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:28:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'debugLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:29:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'infoLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions

<hr>

### 2025-05-02 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil

feature/pmd/test/EgovMybatisUtil

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), UselessParentheses(쓸모없는 괄호)

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

UselessParentheses
- 쓸모없는 괄호
- Useless Parentheses
- 쓸모없는 괄호

```
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:33:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'logger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:88:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:92:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:96:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:101:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

@exception IllegalArgumentException 주석 제거

<hr>

### 2025-05-03 토 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper

#### PMD로 소프트웨어 보안약점 진단 결과
```
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:35:	CloseResource:	CloseResource: 리소스 'Closeable' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:112:	CloseResource:	CloseResource: 리소스 'Socket' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성
```
feature/pmd/test/EgovResourceCloseHelper
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

해결이 어려운 예외 상황에서 주석으로 PMD 무시하기
```java
 // NOPMD CloseResource
```

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

```
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:81:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:93:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
```

<hr>

```
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:33:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'resourcePatternResolver' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:59:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/cmm/web/EgovBindingInitializer.java:33:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/cmm/web/EgovComAbstractController.java:31:	AbstractClassWithoutAbstractMethod:	AbstractClassWithoutAbstractMethod: Abstract Class내에  Abstract Method가 존재하지 않음
src/main/java/egovframework/com/cmm/web/EgovComIndexController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'exception block parameter' 의 변수 'Nfe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovComUtlController.java:13:	UnnecessaryImport:	UnnecessaryImport: Unused import 'com.raonsecure.omnione.core.eoscommander.util.StringUtils'
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:124:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:125:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:144:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:116:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:112:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:114:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:128:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cop/bbs/web/EgovArticleController.java:428:	AvoidReassigningParameters:	AvoidReassigningParameters: 'boardVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cop/bbs/web/EgovArticleController.java:669:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/ems/service/impl/EgovSndngMailRegistServiceImpl.java:160:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailDetailController.java:158:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:103:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicReceiver.java:40:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smsDao' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicReceiver.java:42:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smeConfigPath' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:36:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smsDao' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FILE_SEPARATOR' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:40:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:41:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:42:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:145:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:146:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:147:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:220:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:221:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:285:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:286:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:325:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:326:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:327:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:387:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:388:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:389:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:440:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:441:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:480:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:481:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:106:	CloseResource:	CloseResource: 리소스 'GenericObjectPool' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:114:	AvoidSynchronizedAtMethodLevel:	AvoidSynchronizedAtMethodLevel: mothod 레벨의 synchronization 보다 block 레벨 synchronization 을 사용하는 것이 바람직함
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:115:	CloseResource:	CloseResource: 리소스 'BasicDataSource' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:613:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:621:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:629:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:630:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:677:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:678:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:718:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:268:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:277:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:286:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:287:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:396:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:397:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:130:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:131:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:153:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:154:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:155:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:183:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:197:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:198:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:199:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:203:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:204:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:296:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:305:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:314:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:315:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:385:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:386:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:427:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:692:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:701:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:709:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:710:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:823:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:824:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:620:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:629:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:638:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:639:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:756:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:757:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:307:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:316:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:325:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:326:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:373:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:374:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:414:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/app/service/impl/EgovKnoAppraisalServiceImpl.java:32:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoAppraisalDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/app/web/EgovKnoAppraisalController.java:106:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'KnoAppraisalList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/service/impl/EgovMapMaterialServiceImpl.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'MapMaterialDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:94:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:142:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:156:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/tea/service/impl/EgovMapTeamServiceImpl.java:30:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'MapTeamDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/tea/web/EgovMapTeamController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/mgm/service/impl/EgovKnoManagementServiceImpl.java:32:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoManagementDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:228:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:229:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:322:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:330:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:339:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:340:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:193:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:218:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:227:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:289:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:303:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:366:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:374:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:383:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:384:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:432:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:446:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:508:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:514:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/service/impl/EgovKnoSpecialistServiceImpl.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoSpecialistDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:105:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'KnoSpecialistList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:180:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:194:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:209:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ext/ldapumt/service/LdapObject.java:38:	AbstractClassWithoutAbstractMethod:	AbstractClassWithoutAbstractMethod: Abstract Class내에  Abstract Method가 존재하지 않음
src/main/java/egovframework/com/ext/ldapumt/service/LdapTreeObject.java:92:	FieldNamingConventions:	FieldNamingConventions: 'enum constant' 의 변수 'dept' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/ext/ldapumt/service/LdapTreeObject.java:92:	FieldNamingConventions:	FieldNamingConventions: 'enum constant' 의 변수 'user' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/ext/ldapumt/service/impl/ObjectMapper.java:57:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'type' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/ldapumt/service/impl/ObjectMapper.java:104:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:60:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'chatroomUsers' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:97:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:105:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:117:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:142:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:102:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:105:	EmptyControlStatement:	EmptyControlStatement: Empty else statement
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:124:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:132:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:166:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:180:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:184:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:211:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/config/ChatServerAppConfig.java:44:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'endpointMap' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:51:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:54:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:67:	CloseResource:	CloseResource: 리소스 'JsonReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/model/encoder/MessageEncoder.java:47:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/encoder/MessageEncoder.java:51:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:19:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'oauthService' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:20:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'oauthVO' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:22:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'mapper' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:52:	CloseResource:	CloseResource: 리소스 'Response' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:86:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEmails(OAuthUniversalUser, JsonNode)' 가 선언되었음
src/main/java/egovframework/com/ext/oauth/service/OAuthVO.java:77:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'origin' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/gmt/service/GroupManageVO.java:60:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sec/gmt/service/GroupManageVO.java:68:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/sec/rmt/service/RoleManageVO.java:55:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sec/rmt/service/RoleManageVO.java:62:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/AuthTypeEnum.java:25:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'val' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/MipErrorEnum.java:75:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'code' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/MipErrorEnum.java:77:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'msg' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/ModeEnum.java:26:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'val' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/PresentTypeEnum.java:23:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'val' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/RequestTypeEnum.java:22:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'type' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/RequestTypeEnum.java:24:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'version' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/RequestTypeEnum.java:26:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'cmd' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/RequestTypeEnum.java:28:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'request' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/TrxStsCodeEnum.java:27:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'val' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/enums/VcStatusEnum.java:27:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'val' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/service/impl/DirectServiceImpl.java:65:	UnusedFormalParameter:	UnusedFormalParameter: 'configBean' 처럼  사용되지 않는  'constructor' 파라미터가 있음
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/service/impl/DirectServiceImpl.java:328:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 't_AuthTypeEnum' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sec/rnc/mip/mva/sp/comm/service/impl/MipDidVpServiceImpl.java:482:	StringToString:	StringToString: String 객체에서 toString()함수를 사용하는 것은 불필요함
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:62:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:278:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'username' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:279:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'password' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLogoutFilter.java:43:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ssi/syi/iis/web/EgovCntcInsttController.java:394:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ims/web/EgovCntcMessageController.java:278:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/service/EgovCntcSttusService.java:33:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/service/impl/CntcSttusDAO.java:39:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/service/impl/EgovCntcSttusServiceImpl.java:46:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/web/EgovCntcSttusController.java:62:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/web/EgovCntcSttusController.java:98:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/sim/web/EgovSystemCntcController.java:292:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/sim/web/EgovSystemCntcController.java:461:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sts/bst/web/EgovBbsStatsController.java:190:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/bst/web/EgovBbsStatsController.java:193:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/cst/web/EgovConectStatsController.java:95:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/cst/web/EgovConectStatsController.java:98:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/rst/service/ReprtStatsVO.java:166:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sts/rst/service/ReprtStatsVO.java:172:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/sts/sst/web/EgovScrinStatsController.java:60:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/bat/service/BatchShellScriptJob.java:72:	UnusedFormalParameter:	UnusedFormalParameter: 'paramtr' 처럼  사용되지 않는  'method' 파라미터가 있음
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:109:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:161:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:226:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:269:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:302:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:345:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:365:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:421:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:422:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:443:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:496:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:524:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:525:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:533:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:534:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:542:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:543:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:551:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:552:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:560:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:561:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:569:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:570:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:578:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:579:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:596:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:615:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:658:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:661:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:682:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:727:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:728:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:736:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:737:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:745:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:746:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:754:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:755:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:763:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:764:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:772:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:773:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:781:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:782:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:790:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:791:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:799:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:800:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:808:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:809:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:817:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:818:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:826:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:827:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:872:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:928:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:929:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:952:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1005:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1024:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1034:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1035:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1043:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1044:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1052:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1053:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1061:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1062:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1070:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1071:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1079:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1080:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1088:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1089:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1124:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1167:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1192:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1237:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1238:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1246:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1247:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1255:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1256:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1264:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1265:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1273:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1274:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1282:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1283:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1291:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1292:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1300:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1301:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1309:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1310:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1318:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1319:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1327:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1328:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1336:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1337:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1472:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1504:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CodeVO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1513:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CodeVO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:109:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:110:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:111:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:112:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:113:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:133:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:139:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:154:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:185:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:191:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:222:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/sym/ccm/adc/web/EgovCcmAdministCodeManageController.java:170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/adc/web/EgovCcmAdministCodeManageController.java:219:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/cca/web/EgovCcmCmmnCodeManageController.java:95:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/ccc/web/EgovCcmCmmnClCodeManageController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/cde/web/EgovCcmCmmnDetailCodeManageController.java:100:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:121:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:122:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:123:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:124:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:125:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:126:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:146:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:152:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:167:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:198:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:204:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:244:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:126:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:133:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:249:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:325:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:332:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/service/EgovLoginLogAspect.java:44:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/clg/service/EgovLoginLogAspect.java:75:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:77:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:78:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:80:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/web/EgovLoginLogController.java:71:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:64:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:115:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:166:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:217:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:73:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/web/EgovSysLogController.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/plg/service/EgovPrivacyLogAspect.java:77:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/log/plg/service/EgovPrivacyLogAspect.java:157:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:96:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:103:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:104:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:132:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:163:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:169:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:174:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:180:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:181:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:211:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:69:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:70:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:72:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/web/EgovUserLogController.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/wlg/web/EgovWebLogInterceptor.java:53:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/mnu/bmm/service/EgovBkmkMenuManageservice.java:34:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'BkmkMenuManage' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:204:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:218:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Password' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:232:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Name' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:246:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UserSe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:260:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:274:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_OrgnztId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:288:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UniqId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:302:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Cmd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:317:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_rootPath' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/impl/EgovMenuCreateManageServiceImpl.java:72:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AuthorCnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/web/EgovMenuCreateManageController.java:188:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/web/EgovMenuCreateManageController.java:279:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:223:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:237:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Password' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:251:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Name' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:265:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UserSe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:279:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:293:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_OrgnztId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:321:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Cmd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:476:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:481:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:490:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:111:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:145:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:185:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:242:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:99:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'req_menuNo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:318:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_MenuNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:343:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:487:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:510:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:594:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:234:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_progrmNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:248:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_rqesterNo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:263:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/service/ProgrmManageVO.java:86:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'URL' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:80:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_progrmNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:308:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:336:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:387:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'tmp_vo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:388:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:509:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:537:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:539:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_Tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:683:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:711:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:713:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:141:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:142:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:143:	CloseResource:	CloseResource: 리소스 'ArchiveOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:200:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/sym/sym/nwk/service/NtwrkVO.java:83:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/sym/sym/nwk/service/impl/NtwrkDAO.java:41:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/sym/nwk/web/EgovNtwrkController.java:71:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/sym/srv/service/ServerEqpmnRelateVO.java:65:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sym/sym/srv/service/ServerEqpmnVO.java:58:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sym/sym/srv/service/ServerVO.java:60:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sym/sym/srv/web/EgovServerController.java:75:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/tbm/tbp/service/TroblProcessVO.java:96:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/sym/tbm/tbp/web/EgovTroblProcessController.java:66:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/tbm/tbr/service/TroblReqstVO.java:106:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/sym/tbm/tbr/web/EgovTroblReqstController.java:72:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLoginFilter.java:49:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLoginFilter.java:78:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLogoutFilter.java:38:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/uat/uap/filter/EgovLoginPolicyFilter.java:48:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/uat/uap/service/LoginPolicyVO.java:54:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uat/uap/service/LoginPolicyVO.java:60:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uat/uia/service/impl/EgovLoginServiceImpl.java:222:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uat/uia/service/impl/EgovLoginServiceImpl.java:231:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uat/uia/web/EgovLoginController.java:105:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'auth_error' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uat/uia/web/EgovLoginController.java:306:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'main_page' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/cmt/service/CmtManageVO.java:286:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'wrkt_dt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:75:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:102:	AvoidReassigningParameters:	AvoidReassigningParameters: 'cmtManageVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:104:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:138:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'result_temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:174:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'to_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:175:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:155:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'annvrsryManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:382:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'annvrsryManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:413:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'to_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:414:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnr/service/BannerVO.java:53:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/bnr/service/BannerVO.java:59:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:384:	CloseResource:	CloseResource: 리소스 'XSSFWorkbook' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:484:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:506:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:349:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtCeckManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:356:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtCeckManage_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:176:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:233:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:359:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:420:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/evt/web/EgovEventManageController.java:388:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'eventManageVO_check' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/isg/service/IntnetSvcGuidanceVO.java:48:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/isg/service/IntnetSvcGuidanceVO.java:54:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uss/ion/lsi/service/LoginScrinImageVO.java:47:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/lsi/service/LoginScrinImageVO.java:53:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uss/ion/msi/service/MainImageVO.java:47:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/msi/service/MainImageVO.java:53:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:195:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:196:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:240:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:248:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:257:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:258:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:284:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:312:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManage_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:391:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:421:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntm/service/NoteManageVO.java:235:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:191:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:192:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:208:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntr/service/NoteRecptn.java:218:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:82:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NewsList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:143:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:144:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:225:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:232:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:239:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:240:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/pwm/web/EgovPopupManageController.java:286:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/pwm/web/EgovPopupManageController.java:319:	AvoidReassigningParameters:	AvoidReassigningParameters: 'fileUrl' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/ion/rec/web/EgovRecomendSiteController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'RecomendSiteList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rmm/web/EgovRoughMapController.java:197:	AvoidReassigningParameters:	AvoidReassigningParameters: 'roughMap' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/ion/rsm/web/EgovRecentSrchwrdController.java:369:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:49:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_TITLE' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:50:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_LINK' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:51:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_DESCRIPTION' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:52:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_TAG' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:53:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_ETC' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:61:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_TITLE' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:62:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_LINK' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:63:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_DESCRIPTION' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:64:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_TAG' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:65:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_ETC' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:67:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Keys' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:54:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_NAME' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:55:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_SCHEMA' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:56:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_AND_VIEW_TYPES' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:59:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:61:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:75:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:105:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:106:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:107:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:114:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:158:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'rwardManage_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:218:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:219:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:263:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:273:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:283:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:284:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:308:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:93:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SiteList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:135:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:195:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/EgovTwitterTrnsmitService.java:6:	UnnecessaryImport:	UnnecessaryImport: Unused import 'twitter4j.Status'
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:16:	UnnecessaryImport:	UnnecessaryImport: Unused import 'twitter4j.Status'
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:56:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:57:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:83:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:84:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:101:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'userCreate_at' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'userProfile_url' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:121:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:123:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:124:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:137:	SystemPrintln:	SystemPrintln: System.out.print 가 사용됨
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:169:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:289:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:290:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:326:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:327:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:363:	AvoidReassigningParameters:	AvoidReassigningParameters: 'tID' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:366:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:367:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/uas/service/UserAbsnceVO.java:50:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/uas/service/UserAbsnceVO.java:56:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
src/main/java/egovframework/com/uss/ion/vct/service/impl/EgovVcatnManageServiceImpl.java:473:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Count' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/vct/web/EgovVcatnManageController.java:103:	AvoidReassigningParameters:	AvoidReassigningParameters: 'vcatnManageVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/ion/wik/bmk/service/impl/EgovWikiBookmarkServiceImpl.java:100:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olh/awm/web/EgovAdministrationWordController.java:191:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/awm/web/EgovAdministrationWordController.java:248:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:105:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FaqList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:176:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:177:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:269:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:297:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:96:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'HpcmList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:140:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:197:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/omm/web/EgovOnlineManualController.java:196:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/omm/web/EgovOnlineManualController.java:253:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'QnaList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:274:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:321:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:360:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'QnaAnswerList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:403:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:406:	AvoidReassigningParameters:	AvoidReassigningParameters: 'qnaVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:302:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:303:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:456:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:464:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:473:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:474:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:517:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:530:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:571:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CnsltAnswerList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:618:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/opp/web/EgovOnlinePollPartcptnController.java:196:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/opp/web/EgovOnlinePollPartcptnController.java:208:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/qri/web/EgovQustnrRespondInfoController.java:381:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ResultScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/qtm/service/QustnrTmplatManageVO.java:96:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/uss/sam/stp/web/EgovStplatManageController.java:112:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'StplatList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:79:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getPasswordHintResult(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:86:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getSexdstnCode_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:93:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEntrprsMberSttus_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:100:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getGroupId_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:107:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEntrprsSeCode_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:114:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getIndutyCode_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:119:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:150:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:153:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:156:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:191:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:194:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:197:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:200:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:241:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:245:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:249:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:253:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:406:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:409:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:119:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:150:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:153:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:156:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'insttCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:159:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'orgnztId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:162:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:229:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:232:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:235:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:238:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'insttCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:241:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'orgnztId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:244:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/cas/service/EgovMessageUtil.java:137:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:195:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:196:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:575:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SDay' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:701:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Week' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:728:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'HH' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:729:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MM' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:859:	AvoidReassigningParameters:	AvoidReassigningParameters: 'timeStr' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:81:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:82:	CloseResource:	CloseResource: 리소스 'InputStreamReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:262:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:277:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:277:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:280:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:292:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:292:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:295:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:304:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:307:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:307:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:319:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:319:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:322:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:104:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:113:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:218:	AvoidReassigningParameters:	AvoidReassigningParameters: 'original' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:225:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:226:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:234:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:297:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:298:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:306:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:235:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:237:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:239:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:241:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:243:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:434:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:482:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:503:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:504:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:505:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:506:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:35:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'IDAdd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:37:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'count_num' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:38:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'add_num' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:39:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'total_id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:157:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:638:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:677:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:767:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit conversion from char to int through Integer
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:768:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit conversion from char to int through Integer
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:22:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmVt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:25:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmVl' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:28:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmAr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmWt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:41:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:42:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:43:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:44:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:46:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:47:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:48:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:53:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:54:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:55:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:59:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:60:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:61:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:62:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:72:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:73:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:74:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:83:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:84:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:85:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:86:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:87:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:104:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:119:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:134:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:149:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/pao/service/PrntngOutptVO.java:56:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:80:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'os_info' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:81:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'os_conf' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:99:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:139:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:145:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 's_loc' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'f_loc' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:52:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:53:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:54:	CloseResource:	CloseResource: 리소스 'ZipInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:72:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:83:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:277:	CloseResource:	CloseResource: 리소스 'FileWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:278:	CloseResource:	CloseResource: 리소스 'BufferedWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:279:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:285:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:310:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:311:	CloseResource:	CloseResource: 리소스 'FileReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:321:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:72:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:73:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:84:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:114:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:115:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:126:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:250:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:259:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:45:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileName' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileName' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:78:	CloseResource:	CloseResource: 리소스 'BufferedWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:84:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:87:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:88:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:118:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:183:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'InetA' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:228:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:228:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'b_out' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:293:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:75:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'file_iter' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:141:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:142:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:162:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:63:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:90:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:94:	AvoidReassigningParameters:	AvoidReassigningParameters: 'file' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:120:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:49:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:50:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:52:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:110:	CloseResource:	CloseResource: 리소스 'FileWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:138:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:142:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:185:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:211:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:233:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:233:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'b_out' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/htm/service/HttpMntrngChecker.java:40:	AvoidUsingHardCodedIP:	AvoidUsingHardCodedIP: 하드코딩된 IP 주소 whiteListURL 사용
src/main/java/egovframework/com/utl/sys/htm/service/HttpMntrngChecker.java:65:	AvoidReassigningParameters:	AvoidReassigningParameters: 'siteUrl' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/htm/service/impl/EgovHttpMonServiceImpl.java:33:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'HttpMonDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/nsm/service/EgovNtwrkSvcMntrngScheduling.java:89:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/utl/sys/prm/service/ProcessMonChecker.java:52:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/prm/service/ProcessMonChecker.java:79:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:113:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:114:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:119:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:120:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:129:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:165:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyThread.java:22:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'client' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyThread.java:99:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/pxy/web/EgovProxySvcController.java:74:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/pxy/web/EgovProxySvcController.java:127:	AvoidReassigningParameters:	AvoidReassigningParameters: 'proxySvcVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/srm/service/EgovServerResrceMntrngScheduling.java:73:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'serverResrceMntrngVO' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/sys/srm/service/EgovServerResrceMntrngScheduling.java:84:	CloseResource:	CloseResource: 리소스 'JMXConnector' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/srm/web/EgovServerResrceMntrngController.java:151:	AvoidReassigningParameters:	AvoidReassigningParameters: 'serverResrceMntrngVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:249:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:327:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:460:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:461:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:480:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:485:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:519:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:70:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:153:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:173:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:192:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:371:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:374:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:51:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:52:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:54:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/wed/filter/CkFilter.java:55:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'log' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:68:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'log' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:72:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'imageBaseDir' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:73:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'imageDomain' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:74:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'allowFileTypeArr' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:75:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'fileSaveManager' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:87:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:90:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:95:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:185:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/wed/filter/DirectoryPathManager.java:55:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
