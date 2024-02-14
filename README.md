 # merge-excel
 
## 설치방법
### 파이썬 버전 확인
```shell
$ python --version
Python 3.11.8
```
- [Python 홈페이지](https://www.python.org/downloads/)에서 다운로드 받습니다.
- 2024/02/14 기준 가장 높은 버전인 3.13(prerelease)이나 3.12가 아닌 이유는 설치 시 오류를 줄이기 위함입니다.
### poetry(의존성관리도구) 설치
```shell
$ pip install poetry
$ poetry --version
Poetry (version 1.7.1)
```
### 현재 프로젝트 가져오기
- zip 파일로 다운로드 받거나
- git clone 명령어를 사용하거나

편한 방법으로 원하는 폴더 위치에 배치합니다.
### 의존성 설치
```shell
$ poetry install
...
```
### 실행
- 사용자용
  ```shell
  $ poetry run
  ```
- 개발자용
  ```shell
  $ poetry run uvicorn main.main:app --reload
  ```