---
layout: single
title:  "20240105 과제"
categories: coding
tag: [html]
toc: true
---

# 과제 내용
아래와 같은 화면을 html로 작성해보자
![](../../images/2024-01-05-assignment/assignment1.PNG)
![](../../images/2024-01-05-assignment/assignment2.PNG)
![](../../images/2024-01-05-assignment/assignment3.PNG)
# 코드
```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>20240105과제</title>
</head>
<body>
<section id="loginSection">
    <div>
        <h1>로그인</h1>
    </div>
    <div>
        <p>아이디와 비밀번호를 입력하고 로그인하세요</p>
    </div>
    <div>
        <form action="#" method="post">
            <label>아이디</label>
            <input type="text" name="userId">
            <br>
            <label>비밀번호</label>
            <input type="password" name="password">
            <input type="checkbox" name="idSave" id="idSave">
            <br>
            <label>아이디 저장</label>
            <br>
            <button>로그인</button>
        </form>
    </div>
</section>
<section id="joinSection">
    <div>
        <h1>회원가입</h1>
    </div>
    <div>
        <p>원활한 서비스 이용을 위해 회원가입을 해주세요</p>
    </div>
    <div>
        <form action="#" method="post">
            <div>
                <label>아이디</label>
                <input type="text">
                <br>
                <label>이메일</label>
                <input type="email">
                <br>
                <label>비밀번호</label>
                <input type="password">
                <br>
                <label>닉네임</label>
                <input type="text">
            </div>
            <div>
                <fieldset>
                    <legend>성별</legend>
                    <input type="radio" name="gender" value="male" id="male">
                    <label for="male">남성</label>
                    <br>
                    <input type="radio" name="gender" value="females" id="female">
                    <label for="female">여성</label>
                    <br>
                    <input type="radio" name="gender" value="no" id="no">
                    <label for="no">선택 안함</label>
                </fieldset>
            </div>
            <div>
                <fieldset>
                    <legend>사용 기술</legend>
                    <input type="checkbox">
                    <label>HTML</label>
                    <br>
                    <input type="checkbox">
                    <label>CSS</label>
                    <br>
                    <input type="checkbox">
                    <label>JavaScript</label>
                    <br>
                    <input type="checkbox">
                    <label>Python</label>
                    <br>
                    <input type="checkbox">
                    <label>Django</label>
                    <br>
                    <input type="checkbox">
                    <label>GitHub</label>
                    <br>
                    <input type="checkbox">
                    <label>PostgreSQL</label>
                    <br>
                </fieldset>
            </div>
            <button>회원가입</button>
        </form>
    </div>
</section>
<section id="boardSection">
    <table>
        <caption><h1>글 목록</h1></caption>
        <thead>
            <td>번호</td>
            <td>제목</td>
            <td>작성자</td>
            <td>작성일</td>
            <td>조회수</td>
        </thead>
        <tbody>
            <tr>
              <td>2</td>
              <td>위니브에서 수강생분들에게 알려드립니다.</td>
              <td>홍길동</td>
              <td>2023.04.25</td>
              <td>999</td>
            </tr>
            <tr>
              <td>1</td>
              <td>이스트소프트 백엔드 개발 오르미 1기 모집</td>
              <td>홍길동</td>
              <td>2023.04.25</td>
              <td>999</td>
            </tr>
        </tbody>
    </table>
</section>
</body>
</html>
```

# 결과
[실행 결과 보기](https://fernandokang.github.io/result/2024-01-05-assignment-code.html)
