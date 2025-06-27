# PMD로 소프트웨어 보안약점 진단하고 제거하기

목차
- [LocalVariableNamingConventions(지역 변수 명명 규칙)](#localvariablenamingconventions지역-변수-명명-규칙)
- [FieldNamingConventions(필드 명명 규칙)](#fieldnamingconventions필드-명명-규칙)
- [UselessParentheses(쓸모없는 괄호)](#uselessparentheses쓸모없는-괄호)
- [AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)](#abstractclasswithoutabstractmethod추상-메서드가-없는-추상-클래스)
- [ImmutableField(불변필드)](#immutablefield불변필드)
- [UselessParentheses(쓸모없는 괄호)](#uselessparentheses쓸모없는-괄호)
- [CloseResource(리소스 닫기)](#closeresource리소스-닫기)
- [EmptyControlStatement(빈 제어문)](#emptycontrolstatement빈-제어문)
- [UnnecessarySemicolon(불필요한 세미콜론)](#uselessparentheses쓸모없는-괄호)
- [UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)](#uncommentedemptymethodbody주석-처리되지-않은-빈-메서드-본문)
- [UnusedPrivateMethod(사용되지 않는 개인 메서드)](#unusedprivatemethod사용되지-않는-개인-메서드)
- [MethodReturnsInternalArray(메서드 반환 내부 배열)](#methodreturnsinternalarray메서드-반환-내부-배열)
- [ArrayIsStoredDirectly(배열이 직접 저장됨)](#arrayisstoreddirectly배열이-직접-저장됨)

Code Inspection
- 정의된 규칙을 기반으로 개발자가 작성한 소스 코드를 검사하여, 오류 및 위험 요인을 식별하여 알려 주는 기능을 제공한다. Code Inspection 도구에 대한 개요와 설치, 업데이트 방법에 대하여 설명한다.
- https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev4.3:imp:inspection

## LocalVariableNamingConventions(지역 변수 명명 규칙)

```
LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

LocalVariableNamingConventions(지역 변수 명명 규칙)
```

## FieldNamingConventions(필드 명명 규칙)

```
FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

FieldNamingConventions(필드 명명 규칙)
```

## UselessParentheses(쓸모없는 괄호)

```
UselessParentheses 번역
- 쓸모없는 괄호
- Useless Parentheses

UselessParentheses(쓸모없는 괄호)
```

괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음

## AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)

```
AbstractClassWithoutAbstractMethod 번역
- 추상 메서드가 없는 추상 클래스
- Abstract Class Without Abstract Method

AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

## ImmutableField(불변필드)

```
ImmutableField 번역
- 불변필드
- Immutable Field
- 변경 불가능한 필드

ImmutableField(불변필드)
```

생성자에서 Assign된 변수 'type' 를 Final로 선언하지 않았음

## CloseResource(리소스 닫기)

```
CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

CloseResource(리소스 닫기)
```

리소스 'Session' 가 사용 후에 닫혔는지 확인필요

## EmptyControlStatement(빈 제어문)

```
EmptyControlStatement 번역
- Empty Control Statement
- 빈 제어문

EmptyControlStatement(빈 제어문)
```

Empty else statement

## UnnecessarySemicolon(불필요한 세미콜론)

```
UnnecessarySemicolon 번역
- 불필요한 세미콜론
- Unnecessary Semicolon

UnnecessarySemicolon(불필요한 세미콜론)
```

필요없는 문장 (;)이 있음

## UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)

```
UncommentedEmptyMethodBody 번역
- 주석 처리되지 않은 EmptyMethodBody
- Uncommented Empty Method Body
- 주석 처리되지 않은 빈 메서드 본문

UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

빈 Method Body에 주석을 추가 할 것

## UnusedPrivateMethod(사용되지 않는 개인 메서드)

```
UnusedPrivateMethod 번역
- 사용되지 않는 개인 메서드
- Unused Private Method

UnusedPrivateMethod(사용되지 않는 개인 메서드)
```

사용되지 않는 Private Method 'getEmails(OAuthUniversalUser, JsonNode)' 가 선언되었음

## MethodReturnsInternalArray(메서드 반환 내부 배열)

```
MethodReturnsInternalArray 번역
- 메서드 반환 내부 배열
- Method Returns Internal Array
- 메서드는 내부 배열을 반환합니다.

MethodReturnsInternalArray(메서드 반환 내부 배열)
```

'delYn'을 반환하면 내부 배열이 노출될 수 있음

## ArrayIsStoredDirectly(배열이 직접 저장됨)

```
ArrayIsStoredDirectly 번역
- 배열이 직접 저장됨
- Array Is Stored Directly
- 배열은 직접 저장됩니다

ArrayIsStoredDirectly(배열이 직접 저장됨)
```

배열 'delYn' 이 직접 저장되어 있음

## FormalParameterNamingConventions(변수명에 밑줄 사용)

```
FormalParameterNamingConventions 번역
- 형식 매개변수 명명 규칙
- Formal Parameter Naming Conventions
- 공식 매개변수 명명 규칙

FormalParameterNamingConventions(변수명에 밑줄 사용)
```

'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
