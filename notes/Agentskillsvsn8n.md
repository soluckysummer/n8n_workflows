## 相关网站：

1. nodejs：https://nodejs.org/en/download/
2. 智谱API：https://www.bigmodel.cn/glm-coding?ic=DH7I1QKI05
3. API接入Claude code：https://docs.bigmodel.cn/cn/coding-plan/tool/claude
4. Docker：https://www.docker.com/
5. Agent Skills介绍：https://code.claude.com/docs/zh-CN/skills

## Claude code安装指令： 

```bash
npm install -g @anthropic-ai/claude-code

查看安装结果：claude --version
```

## n8n安装指令：
```bash
docker run -d `
  --name n8n `
  -p 5678:5678 `
  -e GENERIC_TIMEZONE="Asia/Shanghai" `
  -e TZ="Asia/Shanghai" `
  -e N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=false `
  -e NODES_EXCLUDE="[]" `
  -e N8N_SKIP_AUTH_ON_OAUTH_CALLBACK=false `
  -e N8N_RESTRICT_FILE_ACCESS_TO=/home/node/n8ndata `
  -v "替换成本地目录:/home/node/.n8n" `
  -v "替换成本地目录:/home/node/n8ndata" `
  docker.n8n.io/n8nio/n8n:latest 
  ```