FROM node:20-alpine

# 安装基础工具
RUN apk add --no-cache \
    bash \
    curl \
    git \
    tzdata

ENV TZ=Asia/Shanghai

# 安装 Claude Code
RUN npm install -g @anthropic-ai/claude-code

# 工作目录（与 volume 挂载一致）
WORKDIR /workspace

