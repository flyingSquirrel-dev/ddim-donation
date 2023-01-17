## 프로젝트 소개

- 프로젝트 이름: ddim-donation[디딤-도네이션]
- [취약계층아동을 후원하기 위한 정부에서 운영하는 디딤씨앗통장](https://www.ncrc.or.kr/ncrc/cm/cntnts/cntntsView.do?mi=1035&cntntsId=1142) 후원신청을 쉽게
  진행할 수 있게 돕는 프로젝트입니다.
    - (as-is) 홈페이지에서 PDF 파일을 다운로드하여 신청서를 작성한 뒤, 신청서를 첨부하여 이메일(또는 문자)로 후원신청을 해야함
    - (to-be) 디딤 도네이션 사이트에서 필요한 폼을 작성하면 후원신청이 완료됨
- 왜 만들었나요?
    - 좋은 의도를 가진 정부사업인데, 신청방법이 번거롭게 느껴져서 만들게 되었습니다.

## 시작하기

- 이 프로젝트는 [pnpm 설치](https://pnpm.io/ko/installation)가 필요합니다.

```bash
# 클라이언트 개발환경: http://localhost:3000
$ cd client && pnpm install && pnpm dev

# 서버 개발환경: http://localhost:8080
$ cd ../server && pnpm install && pnpm run start:dev
```

## 기술스택

- 백엔드: Nest.js, (다른 기술스택 뭐 쓸지 고민 중)
- 프론트엔드: Next.js (다른 기술스택 뭐 쓸지 고민 중)
- [백로그 관리](https://incredible-law-a74.notion.site/aea353c98d2b4929926a101339ad8146?v=a4572d0cf6dc469eaa4cdbdb8a480af4)