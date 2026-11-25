<p align="center">
  <a href="https://github.com/YuMingCorn">繁體中文</a> | <b>English</b>
</p>

<h1 align="center">Hi 👋, I'm Alan</h1>
<h3 align="center">A Software Engineer from Taiwan</h3>

## About Me

I am a software engineer from Taiwan. I am passionate about deep learning and AI, and I like to understand how things work under the hood. My current focus areas are:

- **Computer vision and image processing**: I write basic image-processing algorithms from scratch in C, so they can run on resource-limited edge devices such as the Raspberry Pi. My goal is to turn them into an easy-to-use library that developers can compile straight into their own projects.
- **Deep learning**: I train and compress small models with PyTorch, and I have deployed models to edge devices with TensorRT, ONNX, and NCNN.
- **AI agents**: I build features such as tool calling and permission control, and connect them to local or cloud-hosted large language models. I am still learning and growing in this area.
- **Personal tools and portfolio**: I build small web apps that I actually use every day.

## AI Agent Experience

| Tool | Experience |
| :--- | :--- |
| <img src="assets/claude.svg" height="20" align="center" alt="Claude Code logo"> **Claude Code** | My main daily development tool. I write and maintain my own subagents and skills (see [agent_setting](https://github.com/YuMingCorn/agent_setting)) that route each task to a suitable model such as Haiku, Sonnet, or Opus. My [llm-wiki](https://github.com/YuMingCorn/llm-wiki) knowledge base is also built around it. |
| <img src="assets/antigravity.png" height="20" align="center" alt="Google Antigravity logo"> **Google Antigravity CLI** | I use it as a helper for reviews and code review, and to use GPU resources on Google Colab. |

## Recent Projects

| Project | Description | Tech | Last Updated |
| :--- | :--- | :--- | :---: |
| [agent_setting](https://github.com/YuMingCorn/agent_setting) | My custom subagents and skills for Claude Code. The same settings also generate versions for Codex and Gemini CLI, and one command deploys them. | PowerShell, Claude Code, Codex, Gemini CLI | 2026-11-25 |
| [llm-wiki](https://github.com/YuMingCorn/llm-wiki) | A template for a personal knowledge base that an LLM maintains. Add papers and articles, and Claude Code organizes them into linked Markdown pages with page-number citations. | Python, uv, Claude Code | 2026-11-22 |
| [corn_agent](https://github.com/YuMingCorn/corn_agent) | A step-by-step AI agent tutorial that goes from connecting to a model, to tool calling, to permission control. | Python, uv, OpenAI-compatible API | 2026-11-22 |
| [torchnetaug](https://github.com/YuMingCorn/torchnetaug) | Network Augmentation (NetAug) in pure PyTorch, which improves the accuracy of small models. Only the small model is exported after training, so the inference cost stays the same. | PyTorch, torch.fx | 2026-11-21 |
| [OpenCV_For_Edge_Device](https://github.com/YuMingCorn/OpenCV_For_Edge_Device) | Basic image-processing algorithms written from scratch in C11. All math uses integer fixed-point arithmetic, so the output is byte-for-byte identical on every platform. It compiles for the Raspberry Pi, Cortex-M, and AVR. | C11, CMake | 2026-11-14 |

## Technical Notes

I keep and organize my technical notes on HackMD: [hackmd.io/@YuMingCorn](https://hackmd.io/@YuMingCorn)

## Contact

- GitHub: [YuMingCorn](https://github.com/YuMingCorn)
- Email: [yumingchang9527@gmail.com](mailto:yumingchang9527@gmail.com)
