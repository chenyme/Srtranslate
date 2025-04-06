<div align="center">
  <h1 style="display: inline-block; vertical-align: middle;"><img src="https://github.com/user-attachments/assets/5c4e6194-617e-4c97-935e-1728bdfe630d" alt="Srtranslate Logo" style="vertical-align: middle;">Srtranslate</h1>
  官网：<a href="https://srt.chenyme.com/">Srtranslate - srt.chenyme.com</a>
</div>

<br>

🚀 专业级 AI 字幕翻译引擎 | 多语言无缝互译 | 智能语境识别 | 专业术语库支持 | 高效翻译记忆 | 基于 Next.js + Tailwind CSS + Flask 构建的全栈应用

A professional AI-powered subtitle translation engine featuring seamless multi-language translation, intelligent context recognition, terminology management, and efficient translation memory. Built with Next.js + Tailwind CSS + Flask.



<br>

![image](https://github.com/user-attachments/assets/691fa1bd-d22f-4d36-954f-742b02ff5776)

<br>

## 快速部署

- **前端：Next.js 15 + Shadcn/UI + Tailwindcss**

```bash
# cd frontend

npm install

npm run build

pm2 start npm --name "srtranslate-frontend" --max-memory-restart 200M --restart-delay 3000 --max-restarts 3 --time -- start
```

- **后端：Python 3.11 + Poetry + Flask**

```bash
# cd backend

poetry install

poetry run pro
```

<br>

## 简单三步，完成翻译

#### **01. 上传字幕文件**
支持 SRT 格式字幕导入，自动识别编码并解析时间轴，每条字幕序号、时间戳精准保留。

#### **02. 预处理和编辑**
检查字幕内容，添加专业术语表确保名词翻译一致性，支持手动编辑优化原文。

#### **03. 设置并翻译**
配置 AI 翻译模型与语言参数，支持批量翻译和翻译记忆，可导出双语或纯译文字幕文件。

<br>

![image](https://github.com/user-attachments/assets/572f3759-b811-421d-9a3f-2e8ff45a6052)

<br>

## 多种场景，轻松应对

#### 📹 **视频创作**
为您的 YouTube、Bilibili 等平台视频添加专业多语言字幕，提升国际观众的观看体验，扩大全球受众范围，增加视频推荐曝光率。

#### 🎬 **影视后期**
快速处理电影、剧集、纪录片等专业影视内容的字幕翻译，保持专业术语一致性，确保情感表达准确，符合各地区文化习惯。

#### 🎓 **教育培训**
为在线课程、教学视频等添加多语言字幕，精确翻译专业术语和学术概念，提升学习效果，降低语言障碍，让知识无国界传播。

#### 🏢 **企业宣传**
助力企业视频内容出海，打造国际化品牌形象，规范统一产品术语翻译，确保市场推广和品牌宣传在全球范围内保持一致性和专业性。

<br>

## 常见问题，快速解答

<details>
<summary><strong>需要付费使用吗？</strong></summary>
<p>本工具需要您提供自己的 API 密钥，按照实际 API 使用量计费，我们不额外收取服务费用，让您完全掌控成本。如果需要大批量使用，建议设置合理的 API 使用限额，以控制预算支出，同时使用 GPT-4o-mini 模型性价比最高。</p>
</details>

<details>
<summary><strong>支持哪些字幕格式？</strong></summary>
<p>目前仅支持 SRT 主流字幕格式，能自动识别文件编码并正确处理。我们计划在未来版本中支持 ASS、SSA、LRC 等更多专业字幕格式，以及自动识别内嵌字幕并提取。对于非标准格式，您可以先使用第三方工具转换后再导入。</p>
</details>

<details>
<summary><strong>如何提高翻译质量？</strong></summary>
<p>使用较小的批量大小和较低的创造性设置可以提高翻译准确性，启用翻译记忆功能能保持上下文连贯性。推荐合理使用翻译记忆和专业术语列表，这有助于 AI 更准确地理解内容语境并生成专业且高质量的翻译内容。</p>
</details>

<details>
<summary><strong>字幕时间轴会受影响吗？</strong></summary>
<p>完全不会。我们的翻译过程仅替换字幕文本内容，所有时间轴信息将被完整保留。您可以放心地将翻译后的字幕文件直接应用到原视频上，无需任何时间轴调整。如果您需要微调原文或者翻译后的字幕，可以滑动表格在操作列中编辑。</p>
</details>

<details>
<summary><strong>批量处理是什么意思？</strong></summary>
<p>批量翻译会根据您设置的批量大小，将字幕文件分成多个批次进行翻译，这样您可以更快地获得翻译结果并且可以节省 API 使用量。请不必担心模型幻觉，我们的后端算法会自动优化翻译结果，在必要的时候进行智能匹配或重新翻译，确保翻译质量。</p>
</details>

<details>
<summary><strong>如何导出翻译后的字幕？</strong></summary>
<p>翻译完成后，系统自动提供下载选项，支持多种导出样式。您可以选择仅保留翻译文本，或生成双语字幕文件。如果需要精准校对，您可以导出翻译记忆，使用翻译记忆功能进行一对一精准校对。</p>
</details>
