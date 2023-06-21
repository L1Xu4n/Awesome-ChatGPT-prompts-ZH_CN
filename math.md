# 通过简单的提示词改进LLM的数学能力 
## 模型：GPT3.5 and Claude
灵感：
> OpenAI与Anthropic员工的提示词决斗：https://zhuanlan.zhihu.com/p/634544824
- 数学问题：一百人中，70人选考化学或生物，40人选考化学，同时选考生物化学的有20人，求选考生物的人数
- 答案：50人
- 测试结果：直接上表：
![QQ截图20230621194559](https://github.com/L1Xu4n/Awesome-ChatGPT-prompts-ZH_CN/assets/106089276/c957a67d-b956-4027-889f-e10c1d6dee44)
*Claude:先发送Prompt给模型，再发送问题。给ChatGPT则直接加入Prompt* <br>
*测试平台:Poe*
- 个人感想：
  对于ChatGPT来说，使用思维链或是Python代码来处理数学问题确实能够有效提示模型的正确率，对于Claude，我不能复现Anthropic员工的成功，当然，这可能与解决的问题不同有关(在文章中，LLM需要解决为单词排序的任务)

- 可提高GPT3.5数学能力的Prompt:<br>
直接在问题后面加入
> 请逐步思考来给出python代码，然后处理代码，给出结果
