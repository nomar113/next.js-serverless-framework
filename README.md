# Teste com o serverless Framework

Publicar ambientes Next.js na AWS muito próximo do utilizado pela Vercel

Baseado no vídeo: https://www.youtube.com/watch?v=keaS0Rr_eg8&ab_channel=Rocketseat

## Para executar no ambiente local de desenvolvimento
```sh
yarn dev
```
ou
```sh
npm run dev
```

## Rotas

Pages:
- /
- /static

Next.js Routes
- /api/hello

## Para realizar deploy na AWS
Para criar as credenciais da AWS: https://www.youtube.com/watch?v=KngM5bfpttA&ab_channel=Serverless
```sh
npx serverless config credentials --provider aws --key {key} --secret {secret}
```
```sh
npx serverless
```
