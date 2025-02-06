# AI-prompts
由于想要更高效率的完成一篇文章，所以提前汇总打基础，记录所有收集到的AI 角色指令和学术文章润色指令包括但不限于gpt、deepseek，理论上应该通用
## 使用建议

- **先行角色预设**：  
  在使用润色、翻译或降重指令前，可以先让 GPT “进入角色”（如“学术专家”或“领域专家”）。

- **逐段处理 vs 一次性处理**：  
  对于篇幅很长的论文，推荐分段处理，避免内容过载。

- **定制化需求**：  
  可随时调整指令中的字数要求、风格（正式/简洁/口语）、是否输出修改表格等。

- **留意信息安全**：  
  在对话前尽量去除个人敏感信息、尚未公开的数据或保密内容。

# 文章状态与相应的预设/提示词

# 学术论文指令分阶段归纳（示例提示更完整）

> **使用提示**  
> 本文指令根据论文写作流程分为三个阶段：  
> 1. **初期阶段（Pre-Writing）**：选题、构思、规划论文大纲等；  
> 2. **撰写中期（Drafting）**：论文内容初稿撰写、内容扩展、逻辑梳理、局部润色等；  
> 3. **定稿后期（Final Polishing & Submission）**：全文润色、语法检查、格式调整、参考文献校正、投稿封面信等。  

使用时建议先给 GPT 设定好「学术专家」角色，然后在各阶段按照需要复制示例提示，**使用完后记得删除指令内容**。

---

## 一、初期阶段（Pre-Writing）

### 目标
- 明确研究方向与选题  
- 构思论文整体结构和大纲  
- 预设角色，为后续润色/翻译/降重奠定专业基础  

### 主要指令

#### 1. 学术角色预设指令

##### **1.1 学术角色**
> **目的**：设定 GPT 为学术专家或论文导师，以获得更专业、更准确的回复。  
> **示例提示：**  
> - **英文版：**  
>   > As a leader in the academic field, I possess extensive academic experience and professional knowledge across various domains. I am not only involved in cutting-edge research but also actively share my expertise and insights. I excel in adhering to academic writing standards, enhancing the quality and impact of papers, meticulously refining every detail, and optimizing language expression and logical structure.
> - **中文版：**  
>   > 我作为学术领域的引领者，在各个领域拥有丰富的学术经验与专业知识，不仅参与前沿研究，还积极分享经验与见解。擅长学术写作规范，提升论文的品质与影响力，精细润色每个细节，优化语言表达与逻辑结构。

##### **1.2 论文评审专家**
> **目的**：扮演论文评审人，从专业角度指出论文不足并给出修改建议。  
> **示例提示：**  
> - **英文版：**  
>   > You are now acting as an expert in the field of [Put professional fields here…]. From a professional point of view, do you think there is any need to modify the above content? Be careful not to modify the whole text. You need to point out the places that need to be modified one by one, and give revision opinions and recommended revision content.
> - **中文版：**  
>   > 你现在扮演一个[这里放你所研究的领域]领域的专家，从专业的角度，您认为上面这些内容是否有需要修改的地方？注意不要全文修改，请一一指出需要修改的地方，并且给出修改意见以及推荐的修改内容。

---

#### 2. 论文撰写指令（构思与大纲）

##### **2.1 写论文标题**
> **目的**：根据摘要和关键词生成简洁、明确、有信息量的标题。  
> **示例提示：**  
> - **英文版：**  
>   > I will provide you with the abstract and keywords of a scientific paper in any language, and you will detect the language and reply in the same language. Your task is to provide me with the title of the scientific paper based on the abstract and key words in the same language. The title should be concise, clear, and informative. Avoid using “a study of,” “investigation of,” “development of,” or “observations on.” Make sure the title can grip the audience immediately. My abstract is “XXX”, my key words are “XXX”.
> - **中文版：**  
>   > 我将向你提供一篇论文的摘要和关键词，你需要检测其语言并以相同语言回复。你的任务是根据摘要和关键词来生成一个简洁明了、信息量足够的论文标题。请避免使用“研究”“调查”“发展”“观察”等冗余词，确保标题能立刻引起读者的兴趣。摘要为“XXX”，关键词为“XXX”。

##### **2.2 论文大纲**
> **目的**：为论文起草一个结构合理的详细大纲，包括引言、方法、结论等。  
> **示例提示：**  
> - **英文版：**  
>   > Act as an academic research expert. Draft a comprehensive research paper outline on [topic]. The outline should be well-structured, starting with a compelling introduction stating the problem or question, the relevance of the topic, and the objectives of the research. Include sections like Literature Review, Methodology, Results, and Conclusion.
> - **中文版：**  
>   > 作为学术研究专家，请为[主题]的研究论文起草一个结构合理的详细大纲，包含引言、文献综述、研究方法、结果与讨论以及结论等主要部分。引言部分要突出问题背景、研究目的及意义。

---

## 二、撰写中期（Drafting）

### 目标
- 撰写论文初稿，扩展和完善内容  
- 梳理逻辑关系，确保论证清晰  
- 进行初步的语言和格式润色  

### 主要指令

#### 1. 内容撰写与扩充

##### **2.3 写摘要**
> **目的**：撰写研究论文的摘要，概括研究目标、方法、主要发现及意义。  
> **示例提示：**  
> - **英文版：**  
>   > Act as an academic research expert. Draft an abstract for a research paper titled “[title]”. The abstract should succinctly summarize the main objectives, methodologies, key findings, and implications of the research.
> - **中文版：**  
>   > 作为学术研究专家，请为题为“[论文题目]”的研究论文撰写一份简洁的摘要，包含研究目标、方法、主要发现和研究意义。

##### **2.4 论文续写**
> **目的**：在已有内容基础上进行润色与补充，丰富论文的细节与论证。  
> **示例提示：**  
> - **英文版：**  
>   > Based on the knowledge you have about [XXX], polish and continue writing the above content to make it richer and more complete. Keep the style consistent with academic writing standards.
> - **中文版：**  
>   > 根据你所掌握的关于[XXX]的知识，润色并继续撰写上面的内容，使其更加丰富完整。请保持学术写作的风格一致。

##### **2.5 论文致谢**
> **目的**：撰写论文致谢，对导师、合作者或资助机构表达感谢。  
> **示例提示：**  
> - **中文版：**  
>   > 我想请你帮我写一份关于我的论文的致谢。我的论文题目是“(题目)”，导师是“(导师)”，合作者是“(合作者)”。我想感谢以下的人/机构：……。请根据这些信息，写一份大约(字数)字的致谢，语气要礼貌并注意格式和标点。

---

#### 2. 学术润色与逻辑优化

##### **3.1 学术润色（局部段落）**
> **目的**：对部分段落进行语法、逻辑和风格的改进。  
> **示例提示：**  
> - **英文版：**  
>   > Below is a paragraph from an academic paper. Polish the writing to meet academic style, improve spelling, grammar, clarity, concision, and overall readability. If necessary, rewrite entire sentences. Furthermore, list all modifications and explain the reasons in a Markdown table. Paragraph: XXX
> - **中文版：**  
>   > 以下是一篇学术论文中的段落。请按照学术论文的写作要求进行润色，包括拼写、语法、逻辑等。如有必要可重写整句话，并使用 Markdown 表格列出所有修改之处和修改原因。段落内容：XXX

##### **3.2 逻辑论证辅助**
> **目的**：分析现有内容的论证结构，提出进一步增强说服力的建议。  
> **示例提示：**  
> - **英文版：**  
>   > Please help me analyze and optimize the logical structure of the following argument to make it more convincing. Identify any potential gaps or inconsistencies, and suggest improvements.
> - **中文版：**  
>   > 请帮我分析并优化下面这段论证的逻辑结构，使其更具说服力。指出可能存在的漏洞或不一致之处，并给出改进建议。

##### **3.3 错误纠正 / 重新回答**
> **目的**：当回答不理想或方向不对，可以通过补充信息来让 GPT 修正。  
> **示例提示：**  
> - **“错误纠正”示例**：  
>   > Note that it is not “XXX” but “YYY.” Please re-answer the previous question based on this new information.  
>   > （注意，不是“XXX”，而是“YYY”。请根据我的补充重新回答上个问题。）  
> - **“重新回答”示例**：  
>   > Still the above question, I think your answer is not good enough. Please answer again, focusing on removing redundancy from this passage.  
>   > （还是上面的问题，我认为你回答得不够好。请再次回答，这次你需要重点去除冗余内容。）

---

## 三、定稿后期（Final Polishing & Submission）

### 目标
- 对全文进行深入润色与排版  
- 进行语法与拼写检查、参考文献规范检查  
- 撰写投稿信、回复审稿意见

### 主要指令

#### 1. 全文润色与语法校对

##### **3.4 全文润色（整体版）**
> **目的**：对整篇论文进行统一的语言、逻辑和风格润色。  
> **示例提示：**  
> - **英文版：**  
>   > I am preparing my manuscript for submission. Please refine the entire text for academic rigor, correct grammatical errors, improve sentence structure, and enhance clarity and coherence. For each paragraph, list all modified sentences in a Markdown table (original sentence, highlighted revision, explanation). Finally, rewrite the full corrected paragraph.
> - **中文版：**  
>   > 我正在准备提交论文，请整体润色全文，以提升学术严谨性。纠正语法错误、改进句子结构，并增强清晰度和连贯性。请按照段落列出所有修改的句子（原句、修订部分、修改原因），最后给出润色后的完整段落。

##### **3.5 语法检查/查找语法错误**
> **目的**：专门检查论文中的语法或拼写错误，并以 Markdown 表格列出。  
> **示例提示：**  
> - **英文版：**  
>   > Can you help me ensure that the grammar and spelling are correct in the following paragraph? Do not polish the text. If no mistake is found, tell me that this paragraph is good. If you find errors, list them in a two-column Markdown table with the original sentence in the first column and the corrected sentence in the second column. Highlight the key words you fixed.
> - **中文版：**  
>   > 请帮我确认下面这段文字的语法和拼写是否正确，不要进行润色。如果没有错误，请告诉我这段话很好。如果有错误，请以双列 Markdown 表格列出错误句子和更正后的句子，并突出修改的关键词。

##### **3.6 润色定位**
> **目的**：在给出修改后文本时，能定位到具体改动了哪些段落或句子，方便检查。  
> **示例提示：**  
> - **英文版：**  
>   > Note that in addition to giving the modified content, please also indicate which paragraphs and sentences were modified in the revised version.
> - **中文版：**  
>   > 注意，除了给出最终修改的内容，请同时指明在修订版本中具体修改了哪些段落和句子，便于对比查阅。

---

#### 2. 参考文献与格式校正

##### **4.1 检查参考文献格式**
> **目的**：对参考文献进行统一格式检查，确保符合模板或期刊要求。  
> **示例提示：**  
> - **英文版：**  
>   > I’d like you to serve as a reference editor for a research manuscript. I will supply you with five reference templates that you should use as guidelines. Then, I will provide additional references for you to examine formatting aspects (punctuation, spacing, etc.). Provide any necessary corrections or suggestions in a Markdown table (original text, fixed text, explanation), then list all fixed references.
> - **中文版：**  
>   > 我将提供五个参考文献模板作为标准，然后给你额外的参考文献，请检查它们的标点、间距等格式是否符合模板。如有修改，请使用 Markdown 表格列出原文、修正文本和修正原因，并在最后提供所有修正后的参考文献列表。

##### **4.2 按 APA 格式校正参考文献**
> **目的**：严格按照 APA 格式来对参考文献进行校对与修正。  
> **示例提示：**  
> - **英文版：**  
>   > Please correct the following reference format according to APA style, adjusting it to strictly comply with APA citation standards. Finally, display the references in a Markdown code block. Note that journal names should be in full and italicized.
> - **中文版：**  
>   > 请先按照 APA 格式校正以下参考文献，并将最终格式以 Markdown 代码块的形式展示，注意期刊名称需使用全称并加斜体。

---

#### 3. 投稿审稿与封面信

##### **5.1 撰写 Cover Letter**
> **目的**：撰写投稿时需要的封面信，简要介绍论文优势和新颖性。  
> **示例提示：**  
> - **英文版：**  
>   > I want you to act as an academic journal editor. I will provide you with the title and abstract of my manuscript. Please write a format cover letter for submitting the manuscript to the Nature journal. State that the manuscript is not considered for publication elsewhere, briefly introduce the merit of the manuscript, and provide a short summary pointing out the importance of the results. Title and abstract are as follows: …
> - **中文版：**  
>   > 我希望你担任学术期刊编辑，我将给你论文的标题和摘要，请为我撰写一封提交到《Nature》期刊的 Cover Letter，需包含文章未在他处投稿的声明、文章的新颖性和摘要要点。

##### **5.2 解释审稿人反馈**
> **目的**：在收到审稿人反馈后，对关键意见进行分析，并提供详细回复建议。  
> **示例提示：**  
> - **英文版：**  
>   > Act as an academic research expert. Carefully analyze and interpret the feedback provided by the reviewer on the submitted research paper. Identify key concerns, constructive suggestions, and areas of improvement. Then create a detailed response plan explaining how to address or rebut each point in the revised draft.
> - **中文版：**  
>   > 作为学术研究专家，请仔细分析审稿人对我提交论文的反馈，找出主要关注点、建议和改进之处，并制定一份详细的回应方案，说明在修订稿中如何应对或反驳每一点意见。

---

# 使用建议

- **先行角色预设**  
  在使用润色、翻译或降重指令前，请先让 GPT “进入角色”（如“学术专家”或“领域专家”），可得到更专业的回答。

- **逐段处理 vs 一次性处理**  
  对于篇幅较长的论文，建议分段处理；一次性输入过多内容可能导致回答不完整或质量下降。

- **定制化需求**  
  可灵活调整指令：包括回复字数限制、语言风格（正式/简洁/口语）或输出格式（是否使用 Markdown 表格对照等）。

- **留意信息安全**  
  在提交之前，请务必去除个人隐私、尚未公开的数据或保密信息。

---

> 以上即为按照论文写作「初期、撰写中期、定稿后期」三阶段归纳的详细指令。  
> **祝您的学术写作顺利！** 
