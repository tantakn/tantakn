<h1 align="center">Hi, I'm tantakn</h1>

<p align="center">
  設計・シミュレーション・強化学習・実機製作をつなげて、小さなロボットを動かしています。<br>
  <b>Robotics</b> ・ <b>Reinforcement Learning</b> ・ <b>Sim2Real</b> ・ <b>Computer Vision</b>
</p>

## 👤 About Me

- 工学系夜間大学 3年
- 2026年2月から、エンジニアのアルバイトとしてソフトウェアを担当
- いま取り組んでいること：ロボット形状の自動設計、小型四足歩行ロボットやサッカーロボットなどの Sim2Real

## 💼 Work

**画像検査装置のソフトウェア**（エンジニアのアルバイト・2026年2月〜）

- キーポイント数を独自に設定した YOLO-pose モデルを追加学習し、Raspberry Pi AI Kit（エッジAI）で動作
- 検査装置プロジェクトのソフトウェア全体を実装

## 🚀 Projects

### 🦿 手のひらサイズの四足歩行ロボット

#### V1 (2025)

<img src="assets/quad-sim-180k.gif" alt="シミュレーション内で歩く四足ロボット" width="47%">
<img src="assets/real-quad-walk.webp" alt="実機の四足ロボットが歩く様子" width="47%">

- Fusion で設計 → 3Dプリント・サーボ×4で製作 → Isaac Lab で学習 → 実機で歩行・方向修正に成功
- 姿勢推定は ArUco + PnP を利用し、ニューラルネットワークによるリアルタイムフィードバックで制御
- 実機は重量が軽くケーブルの影響を受けてしまうことが課題
- 学内のピクトラボ成果発表会で発表

#### V2 (2026〜)

<img src="assets/quad-walk.png" alt="自作の四足ロボットがシミュレーション内で前進する様子" width="47%">

- ESP32・IMU・バッテリーを搭載し、ESP32 での Edge AI によりスタンドアロンで動作するバージョン
- 重量増加による安定した歩行を目指す

`Isaac Lab` `OpenCV` `Fusion` `KiCad` `ESP32` `IMU` `Edge AI`

### ⚽ 強化学習ロボットサッカー

#### V1 (2025)

<img src="assets/soccer-sim-2025.png" alt="シミュレーション内で学習したサッカーロボット（Isaac Sim）" width="47%">
<img src="assets/soccer-real-goal.webp" alt="実機のサッカーロボットがボールをゴールに入れる様子" width="47%">

- Raspberry Pi Mouse を使ったロボットサッカーの授業で、ルールベースではなく強化学習で制御を作り、実機でゴールを決めることに成功
- 位置推定は ArUco + PnP を利用し、ニューラルネットワークによるリアルタイムフィードバックで制御

#### V2 (2026〜)

<img src="assets/soccer-sim.gif" alt="自己対戦で学習したサッカーロボットの対戦" width="47%">

- 自己対戦による強化学習

`Isaac Lab` `OpenCV` `Fusion`

### 🧬 ロボット形状の自動設計 (2026〜)

<img src="assets/auto-design.jpg" alt="ランダムに生成したロボット形状12体" width="47%">
<img src="assets/design-walk-12.gif" alt="自動設計されたロボットが歩く様子" width="47%">

- 本体・棒・サーボの組み合わせをランダムに生成し、進化的アルゴリズムで世代交代

`Isaac Lab` `USD` `Evolutionary Algorithm`

### 🧩 Other Projects

- **ESP32-S3 開発ボード**

    <img src="assets/esp32-boards.jpg" alt="ESP32-S3 開発ボード" width="47%">

    左：初期のボード（2024）　　右：最新のボード（2026）

    `KiCad` `ESP32-S3`
- **ロケット点火装置** — 制御 PC と ATmega328P を RS-485 で接続。展覧会で展示 `ATmega328P` `RS-485`
- USB PD 電源基板・IMU 基板・サーボ試験機などのハードウェアを設計・製作
- **囲碁AI**（[TantamaGo](https://github.com/tantakn/TantamaGo)）— [TamaGo](https://github.com/kobanium/TamaGo) をフォークし、PyTorch の学習部を改造。C++ と TensorRT で合法手生成と AlphaGo 系の木探索を実装 `PyTorch` `C++` `TensorRT`

## 🛠 Tech Stack

**Robotics / ML**

![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Hardware / Embedded**

![Fusion](https://img.shields.io/badge/Fusion-F58025?style=flat-square&logo=autodesk&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![3D Printing](https://img.shields.io/badge/3D_Printing-555555?style=flat-square)

**Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
