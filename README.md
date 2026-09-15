# OMX-AI Project

ROBOTIS OMX-AIを使用した個人ロボティクス開発用リポジトリです。

OMX-AIの実機制御、ROS 2、LeRobot、NVIDIA Isaac Simを使用したシミュレーション・学習、
3D CADによるカスタムパーツの設計などを管理します。

## 目的

OMX-AIをベースに、ロボットアームの制御・認識・学習・シミュレーションを組み合わせた
Physical AIシステムの開発を行います。

主な開発内容：

- OMX-AIの実機制御
- ROS 2を使用したロボット制御
- LeRobotを使用した遠隔操作・模倣学習
- NVIDIA Isaac Simを使用したシミュレーション
- RealSenseを使用した画像・深度認識
- カメラマウントなどのカスタム3Dパーツ設計
- その他OMX-AI関連の実験・検証

## ディレクトリ構成

```text
.
├── mechanical/
│   ├── cad/
│   │   └── camera_mounts/
│   │       └── realsense_d405/
│   └── docs/
├── ros2/
├── lerobot/
├── isaac_sim/
├── firmware/
├── scripts/
├── docs/
└── README.md