# Argo xray for PaaS

## 部署

* 注册任意一家 PaaS 云服务商
* 根据 PaaS 云服务商的不同绑定自己的 GitHub 账户或使用项目提供的 Actions 生成 DockerHub 镜像，严重建议小号 + 私库
* 项目可用到的变量
  | 变量名 | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 | 77ecb2a7-c3ac-4901-a033-0ca76aed0587 | 可在线生成 https://www.uuidgenerator.net/ |
  | VMESS_WSPATH  | 否 | /vmess | 以 / 开头 |
  | VLESS_WSPATH  | 否 | /vless | 以 / 开头 |
  | TROJAN_WSPATH | 否 | /trojan | 以 / 开头 |
  | SS_WSPATH     | 否 | /ss | 以 / 开头 |
  | NEZHA_SERVER  | 否 |     | 哪吒探针服务端的 IP 或域名 |
  | NEZHA_PORT    | 否 |     | 哪吒探针服务端的端口 |
  | NEZHA_KEY     | 否 |     | 哪吒探针客户端专用 Key |

* GitHub Actions 用到的变量

  |    变量名     |      备注      |
  | ------------- | -------------- |
  |DOCKER_USERNAME|Docker Hub 用户名|
  |DOCKER_PASSWORD|Docker Hub 密码  |
  |DOCKER_REPO    |Docker Hub 仓库名|

