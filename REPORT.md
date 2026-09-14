# A1 리포트

- 이름: 김채린
- 학번: 2025402059
- GitHub ID: KimChaeLiin

## 어디를 둘러봤는지

열어본 awesome-nodejs 카테고리, 터미널에서 써본 검색어, 링크를 따라간 경로 등을 적습니다.

---

## 선정한 패키지

### 1. `ndarray`

**선정 이유:** C에서 많이 사용했던 array가 익숙해서 선정하였다. 

**이것으로 무엇을 할 수 있을지:** 단순히 설명을 보고 생각했을 때 다차원배열을 만들 수 있을 것 같다. 더 나아가서 이미지를 [너비, 높이, RGB] 형태의 3차원 배열로 표현하여 이미지 데이터를 처리할 수 있을 것이다. 또, 다차원 배열을 통해 행렬을 구현하여 행렬의 계산, 전치 등의 연산을 수행할 수 있을 것 이다.

**확인 결과:**
``` 
$ npm view ndarray version time.modified license dependencies
version = '1.1.1'
time.modified = '2026-08-26T04:00:02.297Z'
license = 'MIT'
dependencies = { 'is-buffer': '^1.0.2', 'iota-array': '^1.0.0' }

$ npm view ndarray deprecated

```

**출력을 보고 알게 된 것:**
deprecated 경고가 없고 dependencies도 간단하여 안정적으로 관리되고 있는 패키지임을 알게되었다. time.modified를 보아 몇년째 방치되는 패키지도 아닌 것 같다.
---

### 2. `nodemailer`

**선정 이유:** 설명을 보았을 때 이메일을 빠르게 처리하는 방법이라해 궁금증이 생겼다.

**이것으로 무엇을 할 수 있을지:** 웹에서 이메일을 발송해 사용자의 계정을 보안 하는 과정에 사용할 수 있을 것 같다. 이메일업무를 효율적으로 관리할 수 있을 것 같다.

**확인 결과:**
```
$ npm view nodemailer version time.modified license dependencies
version = '10.0.9'
time.modified = '2026-09-12T09:00:02.481Z'
license = 'MIT-0'

$ npm view nodemailer deprecated

```

**출력을 보고 알게 된 것:**
deprecated 경고가 없어 안정적으로 관리되고 있는 패키지임을 알 수 있다. time.modified를 보아 몇년 째 방치되고있는 패키지가 아님도 알 수 있다.
---

### 3. `cows`

**선정 이유: 이름이 특이해서 선정했다. 

**이것으로 무엇을 할 수 있을지: 살펴보니 소 캐릭터를 출력하는 패키지이다. 따라서, 웹에서 이벤트성 문자를 출력할 때 사용할 수 있다. 또, 무작위 캐릭터를 출력해내는 프로그램에서 사용할 수 있을 것 같다. 

**확인 결과:**
```
$ npm view cows version time.modified license dependencies
version = '3.0.1'
time.modified = '2024-07-26T23:52:34.584Z'
license = 'MIT'

$ npm view cows deprecated

```

**출력을 보고 알게 된 것:**
deprecated경고가 없는 것으로 보아 패키지 지원이 계속 됨을 알 수 있다. 단, time.modified가 2년전으로 단순하거나 안정적인 패키지임을 알 수 있다. 
---

## 설치해본 패키지

```
$ npm install cows

$ node try.js
         (__)
         (oo)
  /-------\/
 / |     ||
*  ||----||
   ~~    ~~
     Cow

```

---

## 막혔던 부분 (채점하지 않음)

에러 메시지든 헷갈렸던 부분이든 하나. 두 문장이면 됩니다. 없었으면 없었다고 적습니다.

```
없었습니다.
```

---

## AI 사용

사용했다면 프롬프트와, AI의 설명이 실제와 달랐던 부분을 적습니다.
사용하지 않았다면 "사용하지 않음"이라고만 적으면 됩니다.

사용하지 않음

---

## 제출 전 확인

- [ ] 저장소 이름이 `oss2026-a1`, 공개 범위가 Public
- [ ] `git status` 결과가 `nothing to commit, working tree clean`
- [ ] `node_modules` 폴더를 지우고 `npm install` → `node try.js` 를 다시 해도 실행됨
- [ ] 마지막 커밋을 push함
