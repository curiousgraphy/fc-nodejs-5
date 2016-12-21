# 12월 22일 강의자료


### 저번수업 셋팅
** 참고사항
DB명과 collection 명이 둘다 post라서 DB명 바꿈 (app.js 17 line)
<pre>
var connect = mongoose.connect('mongodb://127.0.0.1/fastcampus');
</pre>

#### 1. <a href="https://github.com/parkjunyoung/fc-nodejs-5/blob/ce1cb0498743f5278f82e17a9e6efc4bf5715564/models/PostModel.js" target="_blank">PostModel 작성</a>

#### 2. <a href="https://github.com/parkjunyoung/fc-nodejs-5/commit/ce1cb0498743f5278f82e17a9e6efc4bf5715564" target="_blank">게시판 작성</a>

#### 3. <a href="https://github.com/parkjunyoung/fc-nodejs-5/commit/63d2e90c0ef8e0d502461f3e08fb6cc0ac0c0404" target="_blank">댓글구현</a>

### 4. csrf 패키지다운
<pre>
npm install —save csurf
</pre>

### 5. <a href="https://github.com/parkjunyoung/fc-nodejs-5/commit/cf6650b56131dfa935b2674a925ac0fca4043d8b" target="_blank">csurf 적용</a>

### 6. <a href="https://github.com/parkjunyoung/fc-nodejs-5/commit/f51f033c92b6a3e40abc20711d784456ab215724" target="_blank">PostModel validation 작성</a>
