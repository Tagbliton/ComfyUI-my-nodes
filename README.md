# My-Nodes

AI助手

一个支持在Comfyui中使用阿里百炼模型库的插件


## 📑 说明书
- 阿里百炼大模型-技术文档

  `https://help.aliyun.com/zh/model-studio/getting-started/what-is-model-studio`


- 如何获取API

  `https://help.aliyun.com/zh/model-studio/user-guide/first-api-call-to-qwen`


- 默认base_url

  `https://dashscope.aliyuncs.com/compatible-mode/v1`


- API填写的三种方式：
  1. 直接输入节点的文本框
  2. （可选）获取的API可以填写到插件根目录下的配置文件中,以便通过节点`从配置文件获取API`调取

      `../custom_nodes/ComfyUI-My-Nodes/config.txt`

      `api_key=YourApiKey`

      将 '=' 后替换为你的**api_key**
  3. （推荐）将API写入环境变量
  
      右键此电脑>>属性>>高级系统设置>>高级-环境变量>>下方系统变量中新建
      ```
      变量名：DASHSCOPE_API_KEY
      变量值：你的API
      ```
      **重启电脑后生效**





## 📑 列表
- 多模态AI助手
- 通用AI助手
- AI图片理解
- Flux助手
- 比较分流器
- 选择输出器
- 宽高比
- 文件计数器
- 从配置文件获取API




## ✨ 功能
- **列表**
  <img src="IMG/list.png" width="800" alt="自定义宽度" />


- **多模态AI助手**

  支持输入` -文本 -图片 -音频 -视频路径`
  
  支持输出` -文本 -音频`

  <img src="IMG/1.png" width="800" alt="自定义宽度" />


- **通用AI助手**

  支持使用openai的大多数模型，**注意**不同模型的temperature值的上限不同，具体参考使用模型的`技术文档`
  
  <img src="IMG/2.png" width="800" alt="自定义宽度" />


- **AI图片理解**
  <img src="IMG/3.png" width="800" alt="自定义宽度" />


- **Flux助手**

  不使用自身电脑性能的情况下使用阿里百炼进行flux文生图。缺点：只能使用预设尺寸
  
  <img src="IMG/4.png" width="800" alt="自定义宽度" />


- **比较分流器**

  通过判断来改变输出方向
  
  <img src="IMG/5.png" width="800" alt="自定义宽度" />

  -----------------------------------------**if true**-----------------------------------------------------------------------------------**if false**-------------------------------------------

  <img src="IMG/5.1.png" width="400" alt="自定义宽度" /><img src="IMG/5.2.png" width="400" alt="自定义宽度" />


- **选择输出器**

  通过判断来选择输出结果
  
<img src="IMG/6.png" width="800" alt="自定义宽度" />


- **文件计数器**

  适用于easyuse插件for循环的索引
  
  <img src="IMG/7.png" width="800" alt="自定义宽度" />
  <img src="IMG/7.1.png" width="800" alt="自定义宽度" />


- **从配置文件获取API**

  从config.txt文件中获取API(适用于方法2)




