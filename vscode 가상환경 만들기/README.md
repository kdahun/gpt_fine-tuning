## 1. cmd terminal 열기 : 단축키는 Ctrl + Shift + `

## 2. 가상환경 생성
2-1. venv를 사용하는 경우
```
venv는 Python의 표준 라이브러리 중 하나로, 별도의 패키지나 모듈 환경을 제공하는 가상환경을 만들기 위해 사용
```
python -m venv 가상환경 이름

2-2. virtualenv를 사용하는 경우
```
virtualenv는 글로벌 Python영역과 별개로 독립된 가상환경을 제공
사용자는 이를 사용하여 프로젝트 별 Python의 버전, 사용되는 라이브러리의 버전을 특정할 수 있다.
물론 같은 프로젝트에서도 여러 가상환경을 만들어 버전을 관리할 수 있다.

1. install virtualenv
python -m pip install --upgrade pip
python -m pip install virtualenv
```

virtualenv 가상환경이름 --python=3.9
