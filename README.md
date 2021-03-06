# Python Tutorial

- 이 Repository는 Python을 기초부터 다시 한 번 정리하고자 만든 것입니다.
- 해당 커리큘럼은 "점프 투 파이썬"을 이용하였습니다.
- 더이상 파이썬 기초를 다시 보지 않도록 & 나중에도 백과사전처럼 볼 수 있도록 깊게 정리할 것입니다.

<br>

## 목차

[1. 둘러보기](https://github.com/dongminleeai/Python-Tutorial/blob/master/1.%20%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%91%98%EB%9F%AC%EB%B3%B4%EA%B8%B0.ipynb)

    - 사칙연산
    - 변수에 숫자 대입하고 계산하기
    - 변수에 문자 대입하고 출력하기
    - 조건문 if
    - 반복문 for
    - 반복문 while
    - 함수

[2. 자료형](https://github.com/dongminleeai/Python-Tutorial/blob/master/2.%20%EC%9E%90%EB%A3%8C%ED%98%95.ipynb)

    - 숫자형
    - 문자열 자료형
    - 리스트 자료형
    - 튜플 자료형
    - 딕셔너리 자료형
    - 집합 자료형
    - 불 자료형
    - 자료형의 값을 저장하는 공간, 변수

[3. 제어문](https://github.com/dongminleeai/Python-Tutorial/blob/master/3.%20%EC%A0%9C%EC%96%B4%EB%AC%B8.ipynb)

    - if문
    - while문
    - for문

[4. 함수 & 입력과 출력](https://github.com/dongminleeai/Python-Tutorial/blob/master/4.%20%ED%95%A8%EC%88%98%20%26%20%EC%9E%85%EB%A0%A5%EA%B3%BC%20%EC%B6%9C%EB%A0%A5.ipynb)

    - 함수
    - 사용자의 입력과 출력
    - 파일 읽고 쓰기

[5. 클래스, 모듈, 예외 처리](https://github.com/dongminleeai/Python-Tutorial/blob/master/5.%20%ED%81%B4%EB%9E%98%EC%8A%A4%2C%20%EB%AA%A8%EB%93%88%2C%20%EC%98%88%EC%99%B8%20%EC%B2%98%EB%A6%AC.ipynb)

    - 클래스
    - 모듈
    - 패키지
    - 예외 처리

[6. 파이썬 라이브러리](https://github.com/dongminleeai/Python-Tutorial/blob/master/6.%20%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC.ipynb)

    - 내장 함수
    - 외장 함수

<br>

## 세부목차

[1. 둘러보기](https://github.com/dongminleeai/Python-Tutorial/blob/master/1.%20%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%91%98%EB%9F%AC%EB%B3%B4%EA%B8%B0.ipynb)

    - 사칙연산
        - 덧셈과 뻴셈
        - 곱셈과 나눗셈
    - 변수에 숫자 대입하고 계산하기
    - 변수에 문자 대입하고 출력하기
    - 조건문 if
    - 반복문 for
    - 반복문 while
    - 함수

[2. 자료형](https://github.com/dongminleeai/Python-Tutorial/blob/master/2.%20%EC%9E%90%EB%A3%8C%ED%98%95.ipynb)

    - 숫자형
        - 숫자형
            - 정수형
            - 실수형
            - 8진수와 16진수
        - 숫자형을 활용하기 위한 연산자
            - 사칙연산
            - **
            - %
            - //
    - 문자열 자료형
        - 여러 줄인 문자열을 변수에 대입하고 싶을 때
            - 이스케이프 코드
            - '''
            - """
        - 문자열 연산
            - 더해서 연결하기(concatenation)
            - 문자열 곱하기
            - 문자열 곱하기 응용
        - 문자열 인덱싱과 슬라이싱
            - 문자열 인덱싱
            - 문자열 슬라이싱
        - 문자열 포매팅
        - 문자열 관련 함수들
            - count
            - find
            - index
            - join
            - upper
            - lower
            - lstrip
            - rstrip
            - strip
            - replace
            - split
    - 리스트 자료형
        - 리스트 인덱싱
        - 리스트 슬라이싱
        - 리스트 연산자
            - 리스트 더하기
            - 리스트 반복하기
            - 리스트 + 문자열
        - 리스트 수정, 변경, 삭제
            - 하나의 값 수정
            - 연속된 범위의 값 수정
            - [] 리스트 요소 삭제
            - del 함수 리스트 요소 삭제
        - 리스트 관련 함수들
            - append
            - sort
            - reverse
            - index
            - insert
            - remove
            - pop
            - count
            - extend
        - 리스트 요소 제거하는 3가지 방법
            - remove
            - pop
            - del
    - 튜플 자료형
        - 튜플 인덱싱
        - 튜플 슬라이싱
        - 튜플 더하기
        - 튜플 곱하기
    - 딕셔너리 자료형
        - 딕셔너리 쌍 추가, 삭제
        - 딕셔너리를 사용하는 방법
        - 딕셔너리 만들 때 주의할 사항
            - 동일한 key 추가
            - key에 리스트는 사용불가능
        - 딕셔너리 관련 함수들
            - keys
            - values
            - items
            - clear
            - get
            - in
    - 집합 자료형
        - 집합 추가
        - 집합 특징
            - 중복 허용 X
            - Unordered(인덱싱, 슬라이싱 불가)
        - 집합 자료형 활용 방법
            - 교집합
            - 합집합
            - 차집합
        - 집합 자료형 관련 함수들
            - add
            - update
            - remove
            - defference_update
    - 불 자료형
        - 참과 거짓 구분하는 기준
        - 불 연산
    - 자료형의 값을 저장하는 공간, 변수
        - 변수 만들기
        - 변수란?
        - 리스트를 변수에 넣고 복사
            - [:]
            - copy
        - 변수를 만드는 여러 가지 방법

[3. 제어문](https://github.com/dongminleeai/Python-Tutorial/blob/master/3.%20%EC%A0%9C%EC%96%B4%EB%AC%B8.ipynb)

    - if문
        - 들여쓰기
        - 조건문
            - 비교연산자
            - and, or, not
            - x in s, x not in s
        - elif
        - 조건부 표현식
    - while문
        - while 만들기
        - break
        - continue
        - 무한 루프
    - for문
        - for문 이해하기
            - 전형적인 for문
            - 다양한 for문의 사용
            - for문의 응용
        - for문과 continue
        - range 함수
        - 리스트 안에 for문 포함하기

[4. 함수 & 입력과 출력](https://github.com/dongminleeai/Python-Tutorial/blob/master/4.%20%ED%95%A8%EC%88%98%20%26%20%EC%9E%85%EB%A0%A5%EA%B3%BC%20%EC%B6%9C%EB%A0%A5.ipynb)

    - 함수
        - 함수를 사용하는 이유
        - 함수의 구조
            - 매개변수와 인수
        - 입력값과 결과값에 따른 함수의 형태
            - 일반적인 함수
            - 입력값이 없는 함수
            - 결과값이 없는 함수
            - 입력값도 결과값도 없는 함수
        - 매개변수 지정하여 호출하기
        - 입력값이 몇 개가 될지 모를 때($*$args, $**$kargs)
        - 함수의 결과값(return값)은 하나
        - 매개변수에 초깃값 미리 설정하기
            - 함수 매개변수에 초깃값을 설정할 때 주의사항
        - 함수 안에서 선언된 변수의 효력 범위
            - return 이용하기
            - global 명령어 이용하기
        - lambda
    - 사용자의 입력과 출력
        - 사용자 입력
            - input의 사용
            - 프롬프트를 띄워서 입력 받기
        - print 자세히 알기
            - 큰따옴표(")로 둘러싸인 문자열은 + 연산과 동일
            - 문자열 띄어쓰기는 콤마
            - 한 줄에 결과값 출력
    - 파일 읽고 쓰기
        - 파일 생성
        - 파일 쓰기 모드로 열어 출력값 적기
        - readline() 함수
        - readlines() 함수
        - read() 함수
    - 파일에 새로운 내용 추가
    - with문과 함께 사용

[5. 클래스, 모듈, 예외 처리](https://github.com/dongminleeai/Python-Tutorial/blob/master/5.%20%ED%81%B4%EB%9E%98%EC%8A%A4%2C%20%EB%AA%A8%EB%93%88%2C%20%EC%98%88%EC%99%B8%20%EC%B2%98%EB%A6%AC.ipynb)

    - 클래스
        - 클래스는 왜 필요한가?
        - 클래스와 객체
            - 객체와 인스턴스의 차이
        - 사칙연산 클래스 만들기
            - 클래스를 어떻게 만들지 먼저 구상하기
            - 클래스 구조 만들기
            - 객체에 숫자 지정할 수 있게 만들기
            - 더하기 기능 만들기
            - 곱하기, 빼기, 나누기 기능 만들기
        - 생성자(Constructor) (init)
        - 클래스의 상속
            - 메서드 오버라이딩
        - 클래스 변수
        - 클래스 활용
    - 모듈
        - 모듈 만들고 불러보기(import)
            - 모듈 함수를 사용하는 또 다른 방법(from ~ import -)
        - if name == "main": 의 의미
        - 클래스나 변수 등을 포함한 모듈
            - 모듈에 포함된 변수, 클래스, 함수 사용하기
        - 새 파일 안에서 이전에 만든 모듈 불러오기
    - 패키지
        - 패키지란 무엇인가?
        - 패키지 만들기
            - 패키지 기본 구성 요소 준비하기
            - 패키지 안의 함수 실행하기
        - init.py의 용도
        - relative 패키지
    - 예외 처리
        - 오류는 어떤 때 발생하는가?
        - 오류 예외 처리 기법
            - try, except문
            - try .. else
            - try .. finally
            - 여러개의 오류처리하기
        - 오류 회피하기
        - 오류 일부러 발생시키기
        - 예외 만들기

[6. 파이썬 라이브러리](https://github.com/dongminleeai/Python-Tutorial/blob/master/6.%20%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC.ipynb) (*은 자주 쓰는 함수들이다.)

    - 내장 함수
        - 숫자
            - abs *
            - pow *
            - divmod
            - int
                - int(x)
                - int(x, radix)
            - len *
            - max
            - min
            - round *
                - round(x)
                - round(x, y)
        - 문자
            - str *
            - eval *
            - chr
            - ord
            - oct
            - hex
        - 묶는 것
            - list *
            - tuple
            - range *
                - 인수가 하나
                - 인수가 2개
                - 인수가 3개
            - enumerate *
            - filter
            - map
            - zip *
            - sorted *
                - 평범한 소트
                - key를 이용하여 소트하기
                - operator 모듈
                - 순차 정렬과 역순 정렬
                - 중첩 소트
        - bool
            - all
            - any
            - isinstance
        - 나머지
            - id
            - type
            - input *
    - 외장 함수
        - sys
            - sys.argv
            - sys.exit
            - sys.path
        - pickle
        - os
            - os.environ
            - os.chdir
            - os.getcwd
            - os.system
            - os.popen
        - shutil
            - shutil.copy(src, dst)
        - glob
            - glob(pathname)
        - tempfile
        - time
            - time.time
            - time.localtime
            - time.asctime
            - time.ctime
            - time.sleep *
        - calendar
            - calendar.weekday
            - calendar.monthrange
        - random *
        - webbrowser
        - namedtuple *
        - defaultdict *
        - threading *

(to be continue..)