출처 : <https://www.youtube.com/watch?v=918zdSxBxTA>, <https://www.youtube.com/watch?v=Mj0XciyAE8w>

## Fine-Tuning을 위한 Prompt 구성
* role : system -> chat봇의 특성을 정의한다.
* role : user -> 사용자가 입력할 프롬프트를 설정한다.
* role : assistant -> 챗봇의 대답을 설정한다.

* 

# 1. Flask 웹 어플리케이션 설정
* app = Flask(__name__) :  Flask 애플리케이션을 생성한다.
* @app.route('/') : 기본 경로에 대한 랜더링 함수를 설정
* @app.rout('/gpt4', methods = ['GET', 'POST']) : /gpt4 경로에 대한 함수를 설정.(이 함수는 GET 및 POST 메서드를 허용
* index 함수 : '/' 경로로 들어왔을 때 index.html을 렌더링
* gpt4 함수
```
* GET 또는 POST 메서드로 /gpt4 경로에 대한 요청을 처리한다.
* 사용자 입력을 가져온다.
* 사용자 입력을 포함하는 메서드를 생성한다.
* OpenAI의 GPT-3.5 모델을 사용하여 대화를 생성하고 반환한다.
* 만약 RateLimitError(요청 제한 오류)가 발생하면, 오류 메시지를 반환한다.
```
