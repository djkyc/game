# ✨ 三平台架构

linux/amd64

linux/arm64

linux/arm/v7

web-hosting部署指南 （适用于所有带nodejs App功能DirectAdmin面板）

用于node环境的玩具和容器，基于node三方ws库、vless+trojan双协议，集成哪吒探针服务(v0或v1)，可自行添加环境变量。

| 变量名              | 是否必须 | 默认值                                  | 备注                                                    |
| ---------------- | ---- | ------------------------------------ | ----------------------------------------------------- |
| **UUID**         | 否    | 5efabea4-f6d4-91fd-b8f0-17e004c89c60 | 开启了哪吒v1，请修改UUID                                       |
| **PORT**         | 否    | 3000                                 | 监听端口                                                  |
| **NEZHA_SERVER** | 否    | （空）                                  | 哪吒v1填写形式：`nz.abc.com:8008` <br> 哪吒v0填写形式：`nz.abc.com` |
| **NEZHA_PORT**   | 否    | （空）                                  | 哪吒v1没有此变量，v0的agent端口                                  |
| **NEZHA_KEY**    | 否    | （空）                                  | 哪吒v1的 `NZ_CLIENT_SECRET` 或 v0 的 agent 密钥              |
| **NAME**         | 否    | （空）                                  | 节点名称前缀，例如：Glitch                                      |
| **DOMAIN**       | 是    | 项目分配的域名或反代域名                         | 不包括 `https://` 前缀                                     |
| **SUB_PATH**     | 否    | sub                                  | 订阅路径                                                  |
| **AUTO_ACCESS**  | 否    | false                                | 是否开启自动访问保活，false 为关闭；true 为开启，需要同时填写 DOMAIN           |


🔐 JS 混淆地址

https://obfuscator.io
