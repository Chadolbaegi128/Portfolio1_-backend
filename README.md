## 노션

[팀 페이지](https://www.notion.so/elice/13-24f6d7e6a3f44114b848bc4371413a52) <br>
[스키마 구조](https://www.notion.so/elice/DB-6069a2c216e04873bedb0ed0d87646a7) <br>
[api 문서](https://www.notion.so/elice/1905b116872943b09ed32fa5d6e7b345?v=df1de4ca958e4e91b8eb338f5ea10f03)

## 기술스택

### Backend

![nodejs](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=node.js&logoColor=ffffff) ![express](https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=ffffff) ![mongodb](https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=ffffff) ![aws-s3](https://img.shields.io/badge/aws--s3-FF9900?style=for-the-badge&logo=amazons3&logoColor=ffffff)

## 실행 방법

### 요구사항

Node 16 버전 이상 필요

.env 파일 생성 <br>
밑에 적혀있는 환경변수 설정 <br>
터미널에 밑에 있는 명령어 타이핑

### .env

```
PORT  설정 안할시 기본포트 5000번
JWT_SECRET
MONGODB_URL 
AWS_ACCESS_KEY_ID
AWS_SECRET_KEY
AWS_REGION
AWS_BUCKET_NAME
```

### 터미널
``` 
npm install 
npm run dev
```
---------------------------

#### 커밋 컨벤션
Repository for back-end of 1st project in Elice AI track 6th

##### 커밋 가이드
 - Feat : 새로운 기능 추가
 - Fix : 버그 수정
 - Build : 빌드 관련 수정
 - !BREAKING CHANGE : 커다란 API 변경의 경우
 - !HOTFIX : 급하게 치명적인 버그를 고쳐야하는 경우
 - Style : 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우
 - Refactor : 기능의 변화가 아닌 코드 리팩토링
 - Comment : 필요한 주석 추가 및 변경
 - Docs : 문서 수정
 - Test : 테스트 코드 추가, 테스트 리팩토링(프로덕션 코드 변경 X)
 - Chore : 빌드 테스트 업데이트, 패키지 매니저를 설정, 기타 변경 사항
 - Rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
 - Remove : 파일을 삭제하는 작업만 수행한 경우

###### 커밋 형식
 - `Feat: Add Login page`
 - `"커밋 유형" : "작업한 내역"`
