# TypeScript 프로그래밍 연습
Node.js와 npm을 기반으로 TypeScript 문법을 학습하기 위한 레포지토리입니다.
## 준비사항
- Node.js (v22.19.0)
- npm (10.9.3)
- 코드 에디터 (VS Code)

## 프로젝트 설정
### 디렉토리 구성
```bash
npm  init -y
```
### package.json 파일 수정
```json
"author" : "<YOUR NAME>"
"license" : "MIT"
```
### 의존성 설치
```bash
npm install
```
### TypeScript 설치
```bash
npm install -D typescript jest ts-jest @types/jest @types/node
```
### TypeScript 설정
```bash
npx tsc --init
```
### Jest 설정
```bash
npx ts-jest config:init
```

## 실행 방법
### TypeScript 코드 컴파일
```bash
npm run build
```
### 실행
```bash
npm run test
```
