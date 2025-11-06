# チュートリアル用のCoinプロジェクト

## ビルド

```bash
sui move build
```

## テスト

```bash
sui move test
```

## デプロイ

```bash
sui client publish --gas-budget 100000000
```

以下はテストネットに試験的にデプロイしたコントラクト

```bash
 Published Objects:                                                                                       │
│  ┌──                                                                                                     │
│  │ PackageID: 0x47626759610c7f83d801ede6bd041ebf9181e85b2b1a7c7535f9ca419bd82184                         │
│  │ Version: 1                                                                                            │
│  │ Digest: 418iWALPvAgXQBjbK7AZ2HAErR3gBKaqVQcMXUr3xuhj                                                  │
│  │ Modules: house_data     
```