# 🚗 智能网联汽车云控系统

> 一个基于Vue.js和Spring Boot的智能网联汽车云控系统，提供实时数据可视化、3D场景展示和数据分析功能。

## ✨ 功能特点

- 🌐 实时数据监控与可视化
- 🎮 3D场景交互展示
- 📊 数据分析与报表
- 🔄 车云数据交互
- 🛣️ 路云数据交互
- 📱  响应式设计

## 🛠️ 技术栈

### 前端 (RoadCloud)
- Vue.js 3
- Vite
- Element Plus
- Three.js (3D渲染)
- ECharts (数据可视化)

### 后端 (RoadCloudVisualizationSystem)
- Spring Boot
- Spring Security
- MyBatis
- MySQL
- Redis
- MQTT (实时数据传输)

### 3D建模
- Blender
- 实时渲染引擎

## 📁 项目结构

```
RoadCloudVisualizationSystem/
├── RoadCloud/                    # 前端项目目录
│   ├── src/                      # 源代码
│   ├── public/                   # 静态资源
│   └── package.json              # 前端依赖配置
│
├── RoadCloudVisualizationSystem/ # 后端项目目录
│   ├── src/                      # 源代码
│   ├── resources/                # 配置文件
│   └── pom.xml                   # 后端依赖配置
│
└── 3D-Models/                    # 3D建模文件目录
    ├── blender/                  # Blender源文件
    └── exports/                  # 导出模型文件
```

---