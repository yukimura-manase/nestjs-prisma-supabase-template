# NestJS ✖️ Prisma ✖️ Supabase Template

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

## App 概要

1. NestJS で作成する BackEnd API Template

2. アーキテクチャ構成

   - BackEnd-API: NestJS

   - DB: Supabase (PostgreSQL)

   - ORM： Prisma

## 環境構築

### 0. Nest CLI をインストール

- local に NestJS CLI が Install されていない場合は、まずは CLI を install しましょう。

```bash
npm install -g @nestjs/cli
```

### 1. Package インストール

```bash
yarn install
```

### 2. Supabase 起動

```bash
cd supabase

supabase start
```

## Compile and run the project

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Run tests

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

## 参考・引用

1. [NestJS×Prisma×Supabase で爆速環境構築](https://zenn.dev/masatotezuka/articles/supabase_prisma_20230826)
