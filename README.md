# AI Novel Video Project

AI生成小说 → 视频漫画 → 带字幕音频

## 核心流程

1. 文本生成（AI写小说）
2. 图像生成（视频漫画帧）
3. 音频生成（TTS + 背景音乐）
4. 字幕生成
5. 视频剪辑/合成

## 技术栈

- LLM: OpenAI GPT-4o / Claude
- 图像: 豆包 (doubao-seedream)
- 视频: 豆包 (doubao-seedance)
- TTS: Azure / ElevenLabs
- 字幕: OpenAI Whisper
- 视频合成: MoviePy + FFmpeg

## 安装

```bash
pip install -r requirements.txt
```

## 使用

```bash
python src/main.py
```
