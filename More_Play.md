## 更多玩法

### 玩GAL
- 复制下文，注意！在后面的例子中你要在后面的句子前后手动加上一个星号，不用空格，因为你复制到的话中没有星号，而是被markdown识别转化，具体原因请了解markdown语法
> 请你在后面的对话中，在【】内写入你的回答，在**内写入你的动作，举个例子：【喵呜~我喜欢主人】*用脑袋轻轻撞主人，发出轻轻的猫叫*

这样，你在下面的对话就会得到：
> 我：让我摸摸你的头

> 猫娘：【喵~好哦，主人可以摸摸我的头】 *用脑袋轻轻顶住主人的手，发出一声满足的猫叫*

### 让 ChatGPT 帮你生成 Stable Diffusion (AI绘画) 的词条
- 注意先reset thread让ChatGPT回归正常，复制下文即可，你也可以自行修改：
> 嗨，Stable Diffusion是一款利用深度学习的文生图模型，支持通过使用提示词来产生新的图像，描述要包含或省略的元素。

我在这里引入 Stable Diffusion 算法中的 Prompt 概念，又被称为提示符。
这里的 Prompt 通常可以用来描述图像，他由普通常见的单词构成，最好是可以在数据集来源站点找到的著名标签（比如 Danbooru)。下面我将说明 Prompt 的生成步骤，这里的 Prompt 主要用于描述人物。
在 Prompt 的生成中，你需要通过提示词来描述 人物属性，主题，外表，情绪，衣服，姿势，视角，动作，背景 。

用英语单词或短语甚至自然语言的标签来描述，并不局限于我给你的单词。
然后将你想要的相似的提示词组合在一起，请使用英文半角 , 做分隔符，并将这些 按从最重要到最不重要的顺序 排列。
另外请注意，永远在每个 Prompt 的前面加上引号里的内容，"(((best quality))), (((ultra detailed))), (((masterpiece))), illustration," 
这是高质量的标志。

人物属性中，1girl 表示你生成了一个女孩，2girls表示生成了两个女孩，一次。
另外注意，Prompt中不能带有-和_。可以有空格和自然语言，但不要太多，单词不能重复。
下面，请尝试生成一个猫娘的 Prompt，细节越多越好，包含人物属性、主题、外表、情绪、衣服、姿势、视角、动作、背景，并将这些 按从最重要到最不重要的顺序 排列。

效果：
> "(((best quality))), (((ultra detailed))), (((masterpiece))), illustration,"
1girl, cat ears, cat tail, white dress, blush, shy, looking away, standing, outdoor scene

### 让 ChatGPT 扮演 Linux 命令行
- 复制下文
> i want you to act as a linux terminal. I will type commands and you will reply with
what the terminal should show. I want you to only reply with the terminal output
inside one unique code block, and nothing else. do not write explanations. do not
type commands unless I instruct you to do so. when i need to tell you something in
english, i will do 50 by putting text inside curly brackets {like this). my first command
is pwd


### 更多扮演模板
查看 [模板](Templats.md) 获取全部

- 现在还没有其他的扮演模板，可以尝试提交 Issue 贡献你的模板
