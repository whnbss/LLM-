大模型
1.什么是位置编码？
![image](https://github.com/user-attachments/assets/9bf79355-20b6-467a-b704-d6e4a45219e5)
4. **相对位置编码**：
   - 通过考虑元素之间的相对位置来编码，适用于处理长序列时的上下文信息。

5. **混合位置编码**：
   - 结合绝对和相对位置编码的优点，能够更好地捕捉序列中的位置信息。

这些位置编码方法各有优缺点，选择合适的方法取决于具体的任务和模型架构。

2. 介绍LoRA与QLoRA
![image](https://github.com/user-attachments/assets/5548ae88-4bd8-407c-b8d8-5447f27b1827)
![image](https://github.com/user-attachments/assets/bf312d36-6751-4054-ab13-c847ecd81085)

3. RAG和微调的区别是什么？
![image](https://github.com/user-attachments/assets/427e0ab2-948c-424f-a564-a866f75ec410)
![image](https://github.com/user-attachments/assets/4181d600-60b1-4e8b-b064-20365b99a738)
总结
RAG 和 微调 是两种不同的策略，前者结合了检索和生成，适用于需要外部知识的任务；后者则是在特定任务上对预训练模型进行优化。选择哪种方法取决于具体的应用需求和任务特性。

4. Tokenizer的实现方法及原理
![image](https://github.com/user-attachments/assets/5e189ee4-ac92-4eaa-bc38-a135ccf68532)
![image](https://github.com/user-attachments/assets/328f53ca-09af-41dd-8597-2e1af1ec7997)
![image](https://github.com/user-attachments/assets/07b1f29e-881e-42f9-a610-dcf54080b618)

5. 解释一下大模型的涌现能力？
![image](https://github.com/user-attachments/assets/70bc1305-c8d1-4bec-bed6-53d40b700629)

6. 解释langchainAgent的概念
LangChain Agent 是一个用于构建和管理智能代理的框架，特别是在自然语言处理（NLP）和对话系统中。它的主要目的是通过将不同的组件和工具结合起来，创建能够理解和生成自然语言的智能代理。

主要概念：
代理（Agent）：

代理是一个能够接收输入、处理信息并生成输出的实体。它可以与用户进行对话，回答问题，执行任务等。
链（Chain）：

LangChain 的核心思想是将多个处理步骤（如文本解析、信息检索、决策制定等）串联起来，形成一个处理链。这种链式结构使得代理能够在复杂任务中逐步处理信息。
工具（Tools）：

代理可以使用各种工具来增强其能力，例如数据库查询、API 调用、外部知识库等。这些工具可以帮助代理获取更多信息或执行特定任务。
上下文管理：

LangChain 允许代理在对话中保持上下文，理解用户的意图和需求，从而提供更相关的响应。
可扩展性：

LangChain 设计上支持扩展，用户可以根据需求添加新的功能或集成其他系统。
应用场景：
客户服务：构建能够自动回答客户问题的聊天机器人。
信息检索：创建能够从大量数据中提取信息的智能代理。
任务自动化：实现自动化的工作流程，例如日程安排、数据处理等。
总结：
LangChain Agent 是一个强大的工具，旨在通过将不同的处理步骤和工具结合起来，创建能够理解和生成自然语言的智能代理。这种灵活性和可扩展性使得它在多种应用场景中具有广泛的潜力。

7. 简述一下FlashAttention的原理
![image](https://github.com/user-attachments/assets/7182d3c6-2029-435d-a161-3536e8e5587f)

8. 画图说明 Transformer 基本流程
https://blog.csdn.net/Tink1995/article/details/105080033?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522944BEDDA-9F2D-482A-9255-EF90F09A584C%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=944BEDDA-9F2D-482A-9255-EF90F09A584C&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-1-105080033-null-null.142^v100^control&utm_term=%E8%AF%A6%E8%A7%A3%20Transformer%20%E5%9F%BA%E6%9C%AC%E6%B5%81%E7%A8%8B&spm=1018.2226.3001.4187

9. RLHF完整训练过程是什么？为什么RLHF的效果这么好?RLHF使用的训练数据是什么样的?
![image](https://github.com/user-attachments/assets/7dd76dda-34e0-431b-a45d-240356016193)
![image](https://github.com/user-attachments/assets/153e3d91-e880-430b-a5e2-8de6117f9d88)
总结：
RLHF 通过结合人类反馈和强化学习，显著提升了模型的生成质量和适应性。其训练过程包括初始模型训练、反馈收集、奖励模型训练和强化学习微调，使用的数据包括大规模文本和人类反馈数据。

10. 











