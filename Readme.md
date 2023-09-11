monorepo
@service/tsconfig
@package/tsconfig

//
 pnpm init
pnpm add turbo -D

สร้างไฟล์
turbo.json
pnpm-wokrkspace.yaml

app เอาไว้เก็บ NesstJS เป็น servicesหลักๆ 
service ไฟล์เกี่ยว type service ต่างๆ
**
cd apps
cd nest-gateway
pnpm init
pnpm add @nestjs/core @nestjs/common rxjs reflect-metadata
pnpm add -D ts-node-dev
pnpm add -D typescript
**

pnpm add -D @types/node --filter @app/* 