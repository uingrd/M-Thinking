# M-Thinking  
Thinking in Machine: Notes & Ideas<br>

## 结构分类<br>
>   结构假设：有假设的结构集合，设定一个结构鉴别准则，比如2分类器C，能够识别属于结构集合H_1或者H_0<br>
>   好的结构集合：|H_1|==|H_0|<br>
>   错误率：
>>      1. e_1=|{H|C(H_1|H_0)}|/|H_1|<br>
>>      2. e_0=|{H|C(H_0|H_1)}|/|H_0|<br>
>   分类器工作模式：<br>
>>      1. 无序测试，无状态bbox：准备输入集合{x_n}，观察bbox行为，即：x_n->box->y_n，基于{y_n}的次序无关统计量的判别<br>
>>      2. 无序测试，有状态bbox：准备输入序列集合{xt_n}，观察bbox行为，即：xt_n->box->yt_n，基于{yt_n}判别(有无状态差别仅仅是把x看成标量还是向量)<br>
>>      3. 有序测试：准备测试树T，每个节点是一组测试集{x_n}，基于上述1/2测试<br>
>   好的分类器：<br>
>>      1. min(min2(e_1,e_0))<br>
>>      2. min|T|<br>
>>      3. min|{x}|<br>
<br>
<br>
## 智能体博弈——信息屏蔽<br>
>   行为目标：降低对手的决策空间，提高自身收益<br>
>   行为策略：诱导对手策略空间的学习<br>
>   对手策略：
>>      1. 更快迭代
>>      1. 基于信息建立规则
>>      2. 隐藏规则

                       
