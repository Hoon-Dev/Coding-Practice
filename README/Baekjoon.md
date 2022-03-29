# Baekjoon

백준을 자바스크립트(Node.js)로 이용할 경우에 공식 예제는 다음과 같다.

- 언어 번호: 17
- 실행: `node --stack-size=65536 Main.js`
- 버전: [v16.13.1](https://nodejs.org/)
- 시간 제한: ×3+2 초
- 메모리 제한: ×2 MB

```jsx
var fs = require('fs');
var input = fs.readFileSync('/dev/stdin').toString().split(' ');
var a = parseInt(input[0]);
var b = parseInt(input[1]);
console.log(a+b);
```

공식 가이드 - [https://help.acmicpc.net/language/info](https://help.acmicpc.net/language/info#node.js)