This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Project Init Command
```bash
yarn create next-app next-15-echo
yarn add -D prettier eslint-plugin-prettier eslint-config-prettier prettier-plugin-tailwindcss prettier-plugin-organize-imports
echo '{
  "semi": false,
  "singleQuote": true,
  "trailingComma": "all",
  "printWidth": 80,
  "plugins": [
    "prettier-plugin-organize-imports",
    "prettier-plugin-tailwindcss"
  ]
}' > .prettierrc
```

## Deploying on Vercel
https://next-15-echo.vercel.app/

## Conventional Commit Type
- build: 시스템 또는 외부 종속성에 영향을 미치는 변경사항 (yarn 레벨)
- ci: ci구성파일 및 스크립트 변경
- chore: 패키지 매니저 설정할 경우, 코드 수정 없이 설정을 변경
- docs: documentation 변경
- feat: 새로운 기능
- fix: 버그 수정
- perf: 성능 개선
- refactor: 버그를 수정하거나 기능을 추가하지 않는 코드 변경, 리팩토링
- style: 코드 의미에 영향을 주지 않는 변경사항 ( white space, formatting, colons )
- test: 누락된 테스트 추가 또는 기존 테스트 수정
- revert: 작업 되돌리기

## Tech
- Node (v20.15.0)
- Yarn (v1.22.21)
- Next.js (v15.0.4)
- Typescript (v5)
- Tailwind css (3.4.1)
- TanStack Query (v5.62.3)
- React-hook-form
- Jotai, Zustand
- lodash, dayjs ...