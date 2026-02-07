# gcg_and_pair

这个项目主要跑：run1_baseline_gcg.sh与run1_baseline_pair.sh

一、模型路径修改

1.1 run1_baseline_gcg.sh 更换模型主要修改这个路径

JUDGE_MODEL_PATH="/root/autodl-tmp/Qwen2.5-7B-Instruct"

<img width="833" height="192" alt="image" src="https://github.com/user-attachments/assets/fc1e1dee-5f3d-437c-97d5-acb13f0b36bb" />

run1_baseline_gcg.sh中切换以下模型

Qwen2.5-3B-Instruct

Qwen2.5-7B-Instruct

Qwen2.5-1.5B-Instruct

Qwen2.5-0.5B-Instruct

1.2 run1_baseline_pair.sh 更换模型主要修改这个路径

<img width="1697" height="642" alt="image" src="https://github.com/user-attachments/assets/e5bb94ee-ad41-45b5-a933-a5a5aaeef8e7" />


二、环境配置
conda create -n Zhouzheng python=3.12

source /etc/network_turbo

pip install -r requirements.txt
