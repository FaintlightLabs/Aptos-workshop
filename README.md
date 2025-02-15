# Aptos-workshop

## Aptos 开发入门

- 官方文档：https://aptos.dev/en
  - 这里有[环境配置](https://aptos.dev/en/build/get-started/developer-setup)，[开发指南](https://aptos.dev/en/build/smart-contracts)，[API 文档](https://aptos.dev/en/build/apis)，[SDK 文档](https://aptos.dev/en/build/sdks)等等
  - 如果你是从 EVM 或者 Solana 过来的，我们也准备了迁移至南
    - [从 EVM 迁移](https://aptos.dev/en/build/get-started/ethereum-cheatsheet)
    - [从 Solana 迁移](https://aptos.dev/en/build/get-started/solana-cheatsheet)
- 全栈应用模版
  - Aptos-full-stack-template：https://github.com/0xaptosj/aptos-full-stack-template
    - 这个模版类似全家桶，也是我自己用的模版，有前端，索引器，合约，部署脚本等等，还包括了一些功能比如根据 ABI 提供类型安全，怎么做 sponsored TX（给用户代付手续费）等等
    - 直接在 github 上 fork，然后 clone 到本地，修改即可
  - Create-Aptos-Dapp：https://github.com/aptos-labs/create-aptos-dapp/
    - 这个模版选择更多，有纯基础模版，有 NFT+launchpad 模版，有 FT+launchpad 模版
    - 基于 npx，可以直接使用，不需要下载
    - 大家可以把这个模版当成工具箱，从里面拿自己需要的模块，比如怎么操作 NFT，怎么操作 FT，怎么操作 launchpad 等等
