# 第二期 轻松分钟玩转书生·浦语大模型趣味 Demo

## 1.基础作业  
    
### 1.1使用 InternLM2-Chat-1.8B 模型生成 300 字的小故事  
        
![ ](images/Lesson 2/homework/1.1300WordsStory.png)
        
## 2.进阶作业
    
### 2.1 使用 huggingface_hub python 包，下载 InternLM2-Chat-7B 的 config.json 文件

#### 2.1.1使用 Hugging Face 官方提供的 huggingface-cli 命令行工具。安装依赖:

    pip install -U huggingface_hub
   ![ ](images/2.1.1InstallHuggingfaceHub.png)

#### 2.1.2新建 `python` 文件
填入代码
![ ](images/2.1.2PythonCode.png)
运行
![ ](images/2.1.2RunPyFile.png)


### 2.2 浦语·灵笔2 的 图文创作 及 视觉问答 部署

#### 2.2.1配置基础环境
![ ](images/2.2.1BasicEnvironment.png)
#### 2.2.2图文写作实战
默认主题（水墨画）：
![ ](images/2.2.2ChinesePaintingWritingAndPicture.png)

自选主题（油画）：
submit:
![ ](images/2.2.2OilpaintingWritingAndPicture_Task.png)
回复：
![ ](images/2.2.2OilpaintingWritingAndPicture_Answer.png)
#### 2.2.3图片理解实战
绘画图片：
![ ](images/2.2.3PictureExplaination.png)
数学题目图片:
![ ](images/2.2.3PictureExplaination_MathProblem.png)
    
### 2.3 完成 Lagent 工具调用 数据分析 Demo 部署
 
#### 2.3.1配置基础环境
![ ](images/2.3.1BasicEnvironment.png)
#### 2.3.2使用 Lagent 运行 InternLM2-Chat-7B 模型为内核的智能体
解方程：
![ ](images/2.3.2Equation.png)
求导：
![ ](images/2.3.2Derivative.png)

