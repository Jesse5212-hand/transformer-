# transformer-
# 目录
<img width="418" height="480" alt="image" src="https://github.com/user-attachments/assets/ee046eca-8135-4cb4-a682-cbe45fb2bcf0" />

# 三类应⽤
1. 机器器翻译类应⽤用-Encoder和Decoder共同使⽤
2. 只使⽤Encoder端-⽂文本分类BERT和图⽚片分类VIT
3. 只使⽤Decoder端-⽣生成类模型
<img width="672" height="691" alt="image" src="https://github.com/user-attachments/assets/0e7e9f06-c6fd-4903-bb58-437413b6c2a2" />

<img width="769" height="736" alt="image" src="https://github.com/user-attachments/assets/4df05203-5599-465b-9037-ab7c2b4192d9" />

# 一个encoder,分为三个部分
<img width="736" height="445" alt="image" src="https://github.com/user-attachments/assets/cc5ebd26-02e1-41b9-b2bc-31c2725dda1f" />

# 输入 包括embedding，位置嵌入
<img width="624" height="420" alt="image" src="https://github.com/user-attachments/assets/2f7066f5-03fa-4da7-86e7-e84f1d24d0cf" />
<img width="751" height="468" alt="image" src="https://github.com/user-attachments/assets/22fc5b55-f59e-42b8-a17a-1c11d77131e9" />

# 有处理顺序(RNN)
<img width="850" height="541" alt="image" src="https://github.com/user-attachments/assets/59b80aed-62c0-43ca-bb5d-4a18ab9e4266" />

# 同一位置，偶数维度用sin，奇数维度用cos
<img width="891" height="415" alt="image" src="https://github.com/user-attachments/assets/7bcdda82-0ea9-43d8-9dc7-950c6b253fb1" />

# 维度相加作为整个维度
<img width="802" height="571" alt="image" src="https://github.com/user-attachments/assets/71b0c1d5-19f3-4920-9090-819b5b718143" />

# 注意力机制
<img width="570" height="102" alt="image" src="https://github.com/user-attachments/assets/686f2c81-f9d6-4a0d-a3c9-879df1e5024b" />
 <img width="705" height="526" alt="image" src="https://github.com/user-attachments/assets/316172cb-ea2a-4ccd-a9c1-7855d876f190" />
V-对应值向量，QK先做点乘，结果为一个向量在另一个向量上投影的长度，为一个标量，反应出两个向量之间的相似度
，两个向量越相似点乘结果越大，哪个QK结果越大，则越关注，最后和V矩阵相乘得到一个加权和
<img width="729" height="472" alt="image" src="https://github.com/user-attachments/assets/f63b63bb-7a85-4710-a9e9-dd6a0fdc8de0" />

# NLP中的例子
# 输入为爱，K为四个字对应向量，V为对应字向量
<img width="594" height="598" alt="image" src="https://github.com/user-attachments/assets/9a814471-bdd7-492d-9ded-989cea6adbac" />

# 如何获取QKV
<img width="820" height="570" alt="image" src="https://github.com/user-attachments/assets/820ebce8-c0ba-4fac-ba87-c30eb16bc0b8" />
和矩阵参数相乘分别得到

<img width="682" height="643" alt="image" src="https://github.com/user-attachments/assets/2e6d6cd2-e1bf-477d-9dd7-1df952f47c82" />

<img width="798" height="477" alt="image" src="https://github.com/user-attachments/assets/c4dc8444-fa99-44ed-9bff-f29a4175d108" />

<img width="711" height="472" alt="image" src="https://github.com/user-attachments/assets/6d888320-d5a7-48ae-a3f1-b2a8d23a676a" />

<img width="691" height="376" alt="image" src="https://github.com/user-attachments/assets/be872ab5-2499-4568-ad92-4717055e6bef" />

<img width="694" height="588" alt="image" src="https://github.com/user-attachments/assets/a10427b4-7710-443d-b421-87ad8e3b61f8" />

<img width="622" height="423" alt="image" src="https://github.com/user-attachments/assets/1c2d8cfe-4ef9-454c-a397-d9e0db759274" />

<img width="742" height="364" alt="image" src="https://github.com/user-attachments/assets/759eedd1-c396-4128-a56d-c9ae66a551d4" />

# 缓解梯度消失出现
<img width="459" height="325" alt="image" src="https://github.com/user-attachments/assets/24497245-95b1-4b41-8138-da13d2536f9d" />

# BN：对同一维度特征处理
<img width="489" height="250" alt="image" src="https://github.com/user-attachments/assets/07ca5c20-9362-43f9-9dac-da7caf8f164f" />

<img width="526" height="619" alt="image" src="https://github.com/user-attachments/assets/6510beee-87df-4081-bc7f-4e445d4079bd" />

<img width="613" height="625" alt="image" src="https://github.com/user-attachments/assets/f84fb9fa-55be-4854-8ac1-b4ce03c08392" />
<img width="712" height="501" alt="image" src="https://github.com/user-attachments/assets/3312f4fe-76d1-4086-bee7-c1844cdbd0cc" />
<img width="720" height="555" alt="image" src="https://github.com/user-attachments/assets/6ff7e0b9-631e-4c33-b62b-be8280f08695" />

<img width="732" height="469" alt="image" src="https://github.com/user-attachments/assets/95025376-156a-4e5b-96d3-c47fc889c0ce" />












