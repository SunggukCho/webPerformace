## Lecture-1

'프론트엔드 개발자를 위한, 실전 웹 성능 최적화(feat. React) - Part. 1' 1번째 강의 소스입니다.

### 실행

1. download sources

```
$ git clone https://github.com/performance-lecture/lecture-1.git
```

2. install dependencies

```
$ npm install
or
$ yarn
```

3. start development server

```
$ npm run start
or
$ yarn start
```

4. start json-server

```
$ npm run server
or
$ yarn server
```
*3번의 dev server 와 다른 콘솔에서 띄워줍니다.

5. build + serve

```
$ npm run serve
or
$ yarn serve
```
logs
- 21/12/14: Audits(LightHouse)를 이용한 페이지 검사
- 21/12/16: 이미지 사이즈 최적화
- 21/12/17: Bottleneck 코드 탐색 (Performance)
- 21/12/19: Bottleneck 코드 최적화
- 21/12/21: code splitting
- 21/12/26: 텍스트 압축 (텍스트 인코딩) -u 제거
- 21/12/26: 애니메이션 최적화 (reflow & repaint) => 렌더링 성능 최적화
- 21/12/26: 컴포넌트 lazy loading & preloading & 이미지 preloading => 로딩 성능 최적화