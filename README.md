# 🚀 Reinforcement Learning Project: LunarLander-v3 Continuous Control

본 프로젝트는 서강대학교 AISW 대학원 강화학습의기초 수업의 과제로 수행되었습니다.
Gymnasium의 `LunarLander-v3` (Continuous) 환경에서 PPO(Proximal Policy Optimization) 및 SAC(Soft Actor-Critic) 알고리즘을 적용하여 최적의 착륙 정책을 학습하고, 두 알고리즘의 성능 및 안정성을 비교 분석하였습니다.

## 📌 Project Overview
* Goal: 불확실한 초기 조건 하에서 달 착륙선을 지정된 패드(0,0)에 안전하고 연료 효율적으로 착륙시키는 에이전트 개발
* Environment: `LunarLander-v3` (Continuous Action Space)
* Algorithms:
    * PPO (On-policy): 안정적인 학습 및 구현 용이성
    * SAC (Off-policy): 높은 샘플 효율성 및 탐색(Exploration) 성능
* Key Features:
    * Custom Reward Function 분석 (Safety vs Efficiency)
    * TensorBoard를 활용한 학습 곡선(Reward Curve) 비교 분석
    * 학습된 모델의 시연 영상(GIF/MP4) 포함

## 📂 Repository Structure
이 저장소는 다음과 같은 파일들로 구성되어 있습니다.

* `RL Lunarland Project Code_A73023.ipynb`: 학습, 평가, 시각화, 영상 생성이 포함된 전체 소스 코드
* 학습 완료된 모델 파일 (.zip)
    * `ppo_lunarlander_final.zip`
    * `sac_lunarlander_final.zip`
* `PPO-episode-0`: 에이전트 주행 시연 영상 (.mp4 / .gif)
* `강화학습 과제 보고서_A73023 박상원.pptx`: 최종 결과 보고서 (PPT)

## 🛠 Installation & Usage
본 프로젝트는 **Google Colab** 및 **Python 3.10+** 환경에서 테스트되었습니다.

### 1. Dependencies Installation
pip install gymnasium[box2d] stable-baselines3 shimmy pyvirtualdisplay matplotlib seaborn

Name: 박상원
Student ID: A73023
