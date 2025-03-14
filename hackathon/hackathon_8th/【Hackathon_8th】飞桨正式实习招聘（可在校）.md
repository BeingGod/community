此文档展示 **PaddlePaddle Hackathon 第八期活动——飞桨正式实习招聘（可在校）** 项目的详细介绍

## 赛题详情

### 项目一：飞桨 3.0 多硬件方向单测/模型验证修复

#### 项目介绍：

飞桨 3.0 新的 IR 体系已完成 Paddle 主仓的验证修复工作， 相关机制需要在多硬件方向完成相应的单测/模型验证和修复工作，依托于 PaddleCustomDevice 主仓库的各硬件单测集合，在相关硬件上完成验证和修复，推动 CustomDevice 仓库 CI 切换飞桨 3.0 模式。

**工作任务：**

1. 修复 CustomDevice 仓库中 NPU 流水线下报错单测（30+）
2. 修复 CustomDevice 仓库中 MLU 流水线下报错单测（30+）
3. 将 Paddle 主仓库可共用的单测文件导入 CustomDevice 仓库中，达到修改主仓单测即可同步修改 CustomDevice 仓库对应测试文件。
4. 协助测试同学完成 Paddle3.0 模式下多硬件方向 PaddleX 仓库模型的正确性验证工作，修复相关问题。

#### 营员要求（1 人）：

- 计算机及计算机相关专业本科或本科以上学历，熟悉 C++，Python。
- 熟悉一个或多个深度学习框架，包括但不限于 PaddlePaddle，TensorFlow, PyTorch, MXNet, Caffe 等。
- 有较好的工程实践能力，能独立自主的解决工程中遇到的相关问题，并持续优化。
- 积极乐观，责任心强，工作认真细致，有良好的团队沟通和协作能力。
- 有多硬件开发和优化背景优先。
- 每周至少实习 4 天，26 年校招同学优先。
