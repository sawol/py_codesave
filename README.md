# py_codesave


# 설치 방법
```python
pip install py-codesave==0.0.3
pip install py_codesave
```
# 주의사항
사용하는 브라우저에 맞는 [webdriver](https://www.selenium.dev/documentation/ko/webdriver/driver_requirements/#빠른-참조)를 설치해야합니다. __(크롬을 권장합니다.)__  
경로는 py_codesave를 사용하는 py 파일과 동일해야합니다.


# 사용방법
### 패키지 불러오기
```python
from py_codesave import main
```

### 도움
```python
main.help()
```

### 실행
```python
main.run('boj', '토큰값', 'repository이름')
# 예시 - 사이트는 'boj' 포지토리의 이름은 'test'라면,
# main.run('boj', '토큰값', 'sawol/test')
```
