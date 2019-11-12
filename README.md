# Hyperledger-study-50

하이퍼레져 앱 만들기 실습 50일차 - jquery 클릭 시 value 넘기기

1.  onClick

        <!DOCTYPE html>
        <html>
        <head>
        <meta charset="UTF-8">
        <title>Insert title here</title>
        </head>
        <body>


        ​<input type="text" id="input"><br>
        <textarea id="output"></textarea>
        <button onclick="input()">입력받기</button>
        <button onclick="output()">출력하기</button>


        <!-- 아래부터 자바스크립트 -->
        <script type="text/javascript">
        var temp;

        function input(){
        var input = document.getElementById("input").value;
        temp = input;
        }

        function output(){
        document.getElementById("output").value = temp;
        }

        </script>

        </body>
        </html>
