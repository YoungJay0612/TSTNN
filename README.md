# TSTNN
This is PyTorch implementation of paper "TSTNN: Two-Stage Transformer based Neural Network for Speech Enhancement in Time Domain", which has been accepted by ICASSP 2021. More details will be showed soon!


### 2021-6-22
大概的调用流程：
1：调用gen_pair生成需要的H5数据文件，输入干净语音文件路径、带噪语音文件路径，得到相应数据对的H5文件；训练、验证集
2：将所有的H5文件读取路径写入一个list文件，然后再调用、训练
