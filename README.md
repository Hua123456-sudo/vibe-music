# 🎵 vibe-music
原作者： Alex-LiSun
一个基于前后端分离的音乐平台项目，本项目只是提高自己项目能力，无任何其他用途。

------

## 📦 项目结构

```
vibe-music/
├── vibe-music-admin    # 后台管理端
├── vibe-music-client   # 用户前端
├── vibe-music-server   # 后端服务（Spring Boot）
```

------

## ⚙️ 技术栈

- 后端：Spring Boot + MyBatis
- 前端：admin / client
- 缓存：Redis
- 对象存储：MinIO

------

## 🚀 运行环境

请先准备：

- JDK 8+
- Node.js
- Redis
- MinIO

------

## 📥 数据文件（重要）

项目所需数据（音频、资源等）未包含在仓库中，请自行下载：

👉 下载地址：

https://pan.baidu.com/s/1Ulvs3ekpWEZEn-54kY_Inw

👉 提取码：

1234

------

## 📂 数据使用方法

1. 下载 `vibe-music-data.zip`
2. 解压到项目目录下：

```
vibe-music/minio/data/
```

------

## ▶️ 启动步骤

### 1️⃣ 启动 Redis

确保 Redis 已运行

------

### 2️⃣ 启动 MinIO

参考项目中的：

```
启动minio.txt
```

------

### 3️⃣ 启动后端

进入：

```
vibe-music-server
```

运行：

```bash
mvn spring-boot:run
```

------

### 4️⃣ 启动前端

进入：

```
vibe-music-client
```

执行：

```bash
npm install
npm run dev
```

------

## 📌 说明

- `.mp3`、数据文件未上传到 GitHub（体积过大）
- 请按说明下载并配置

------

## ⭐ 项目说明

本项目用于学习/实践音乐平台开发。
