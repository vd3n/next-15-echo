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
