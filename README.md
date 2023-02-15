# 基于法律裁判文书的案情抽取及其应用

## 简介
针对交通肇事案件的裁判文书进行事件要素抽取，并在此基础上加入判决结果预测、案件相似度匹配等应用场景。

* **数据来源**：[OpenLaw](http://openlaw.cn)


* **分词**：主要基于pkuseg

* **词性标注**：基于哈工大LTP/pkuseg


* **命名实体识别**：基于BiLSTM-CRF，涉及到的实体包括人名、地名、车辆信息、各类犯罪情节、判决结果等


* **应用部分**：包括判决结果的预测、案件相似度的对比等



-------


