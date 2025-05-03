---
date: 2024-10-09
tags:
  - AdML
  - uris
  - polyu
---
## A natural role for machine learning techniques is detection
- A common way to numerically represent a document is ***by using a bag-of-words representation***
- ***create a feature vector*** for a given email by considering how often each word in the dictionary has appeared in the email text
### for large enough data
- with respect to an evaluation using past data.
- **对抗性设置**：恶意邮件的生成是有目的的，恶意行为者不希望邮件被检测，从而影响邮件到达用户邮箱的可能性。
- **发送者的选择**：垃圾邮件发送者可能选择：
        - 放弃发送垃圾邮件
        - 修改邮件模板以绕过检测
- **对抗性机器学习的例子**：垃圾邮件发送者的行为直接影响检测系统的策略，体现了对抗性机器学习的典型应用。
- 邮件文本经过修改，足够不同以避免被检测为恶意邮件，通常通过去除“垃圾词”，并可能添加检测系统认为无害的词汇（称为“好词攻击”）。

## **书籍结构**：

- **第2章**：标准机器学习方法概述及其在对抗性环境中的应用。
- **第3章**：机器学习方法攻击的分类，为后续详细内容提供框架。
- **第4章**：讨论对学习模型决策的攻击。
- **第5章**：介绍增强学习算法鲁棒性的方法。
- **第6章**：探讨训练数据污染问题。
- **第7章**：讨论增强算法对抗污染数据的鲁棒性。
- **第8章**：集中讨论计算机视觉中深度神经网络的对抗性学习及其攻击与防范方法。