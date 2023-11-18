# chatglm_langchain
langchain+chatglm本地知识库

# 主要用到的库
langchain, gradio, modelscope

# 部署在阿里云上，遇到主要问题有
1.模型文件下载速度，上传速度很慢，使用modelscope解决。
2.中间需要使用text2vec的中文模型进行embedding操作，所以也要用到modelscope。
3.显存爆炸的问题，主要使用quantize进行量化，

# 运行结果如下
<img width="588" alt="本地知识库回答" src="https://github.com/AdvancedBot/chatglm_langchain/assets/52905259/fb4669fd-648f-47b2-9372-600b6e023105">

<img width="518" alt="本地知识库问题" src="https://github.com/AdvancedBot/chatglm_langchain/assets/52905259/28ebee5b-b4d1-4fcf-923b-a64c1ae21777">

<img width="860" alt="部署api的chatglm" src="https://github.com/AdvancedBot/chatglm_langchain/assets/52905259/be07a039-75b6-4f97-8233-aea44d2483d0">

<img width="1161" alt="webui的运行结果" src="https://github.com/AdvancedBot/chatglm_langchain/assets/52905259/0354ebf3-573b-49d0-879a-355fbc5b31c1">

<img width="1136" alt="webui运行结果" src="https://github.com/AdvancedBot/chatglm_langchain/assets/52905259/f8086857-a665-42bc-8552-cfe04cb47893">
