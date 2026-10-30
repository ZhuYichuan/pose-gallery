# Pose Gallery

AI 姿态与机位参考资产库 (Multi-Perspective AI Pose Reference Gallery).

## 出处

本仓库为线稿姿态图库的本地镜像，来源：<https://ai-pose-gallery.pages.dev/>（线稿姿态图）。

相关仓库：
- 深度姿态图（depth）：<https://ai-pose-depth-gallery.pages.dev/>
- 服装姿态图：<https://ai-costume-gallery.pages.dev/>

## 资产概览

- **总图片量**: 1439 张 PNG 原图
- **单图尺寸**: 900 × 1200
- **机位视角**: 每个姿态包含 5 个连续视角机位（正面 `front`、侧面 `side`、斜向 `diag`、俯视 `high`、仰视 `low`）
- **四大核心系列**:
  1. **全身独奏·标准类型**: 73 套标准日常与站坐姿态 (365 图)
  2. **全身独奏·性感类型**: 80 套动感与曲线姿态 (399 图)
  3. **上半身独奏**: 80 套胸部、肩颈与神态特写姿态 (400 图)
  4. **双人纠缠**: 55 套双人互动与交互姿态 (275 图)

## 元数据结构

根目录下包含完整的权威元数据索引 [`metadata_index.json`](./metadata_index.json)，包含：
- `id`: 全局唯一标识（如 `full_single_P001_front`）
- `pose_num`: 姿态编号（如 `P001`）
- `line_zh` / `line_ja`: 系列分类中日文名称
- `cat_zh` / `cat_ja`: 姿态大类中日文名称（站立、坐姿、下蹲等）
- `pose_name_zh` / `pose_name_ja`: 姿态动作中日文描述
- `angle_zh` / `angle_ja`: 机位视角描述
- `local_path`: 本地文件相对路径
