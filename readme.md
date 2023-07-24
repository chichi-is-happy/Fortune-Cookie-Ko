
Fortune Cookie의 한국어 버전입니다.

35가지 포츈 쿠키 문장과 행운의 숫자(0~100)로 오늘 운세를 확인해 보세요.

npm을 학습하기 위해 제작되었습니다. [NPM Link](https://www.npmjs.com/package/fortune-cookie-ko)

<br>

### 🥠 사용 방법

- 프로젝트 폴더에 `package.json` 파일이 있어야 합니다. (없는 경우 `npm init`으로 생성)
- 아래 명령어를 실행하여 패키지를 설치합니다.

```bash
npm i fortune-cookie-ko
```

<br>

- package.json 파일의 dependencies 항목에 fortune-cookie-ko가 추가됩니다

```json
"dependencies": {
    "fortune-cookie-ko": "^1.0.1"
  }
```

<br>

- 사용하고자 하는 파일에서 다음과 같이 모듈을 가져와서 사용합니다. (JavaScript 파일 기준)

```jsx
// example.js
const randomCookie = require("fortune-cookie-ko");
console.log(randomCookie.pickOneCookie());
```

<br>

- 터미널에서 아래 명령어를 실행하여 위에서 작성한 **`example.js`** 파일을 실행합니다.

```jsx
// node 파일이름
node example.js
```

<br>

### 🥠 실행 예시

위 명령어를 실행하면 오늘의 포츈 쿠키 문장과 행운의 숫자가 함께 출력됩니다.

```bash
➜  폴더명 node example.js
{ '행운의 숫자': 30, '포츈 쿠키': '새로운 시작을 위한 기회가 찾아올 것입니다.' }
➜  폴더명 node example.js
{ '행운의 숫자': 77, '포츈 쿠키': '당신은 할 수 있습니다. 자신을 믿으세요.' }
➜  폴더명 node example.js
{ '행운의 숫자': 22, '포츈 쿠키': '주변의 사람들과 함께 행복한 시간을 보낼 수 있을 것입니다.' }
➜  폴더명 node example.js
{
  '행운의 숫자': 94,
  '포츈 쿠키': '코드 리뷰는 발전의 기회입니다. 더 나은 코드를 위한 도전이 될 수 있습니다.'
}
➜  폴더명 node example.js
{ '행운의 숫자': 56, '포츈 쿠키': '운명의 흐름을 따라가보세요. 좋은 결과가 있을 거에요.' }
```
