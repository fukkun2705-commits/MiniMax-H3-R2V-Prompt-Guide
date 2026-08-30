````markdown
# MiniMax H3 R2V Prompt Guide

A prompt guide and GPT configuration for generating structured English prompts for MiniMax H3 Reference-to-Video (R2V).

This repository is designed to help users build consistent MiniMax H3 prompts from Japanese scene descriptions, reference images, and Motion Context.

## 日本語ユーザー向け

このリポジトリは、MiniMax H3 Reference-to-Video（R2V）向けの英語プロンプトを、日本語のシーン説明から生成するためのChatGPT用設定・ガイドです。

利用方法は以下のどちらかです。

- Custom GPTを作成できる場合：`instructions/GPT_Instructions.txt` をGPTの「指示」に貼り付け、`knowledge` フォルダ内の2ファイルをKnowledgeとしてアップロードしてください。
- Custom GPTを利用しない場合：ChatGPT Projectを作成し、同じ指示文とKnowledgeファイルをProjectへ設定してください。

ユーザーは日本語で動画内容、参照画像の役割、Motion Context、セリフなどを入力できます。最終的なMiniMax H3用プロンプトは英語で生成されます。

詳しい入力例は `examples` フォルダを参照してください。

## Features

- MiniMax H3 Reference-to-Video prompt generation
- Japanese input to English prompt conversion
- Reference-image role separation
- Character identity consistency
- Motion Context continuation
- Scene transition handling
- Multi-subject consistency
- Explicit keep / change / remove instructions
- Japanese dialogue preservation
- Structured 6-section output

## Output Format

Generated prompts use the following structure:

1. `subject_definitions`
2. `summary`
3. `retention_analysis`
4. `detailed_description`
5. `overall_soundscape`
6. `non_diegetic_music`

## Repository Structure

```text
MiniMax-H3-R2V-Prompt-Guide/
├─ README.md
├─ LICENSE
├─ instructions/
│  └─ GPT_Instructions.txt
├─ knowledge/
│  ├─ H3_R2V_Master_Instructions.txt
│  └─ VIDEO_PROMPT_WRITING_GUIDE_ref_en.md
├─ examples/
│  ├─ basic_r2v.md
│  ├─ motion_context.md
│  └─ multi_subject.md
└─ CHANGELOG.md
````

## How to Use

There are two recommended ways to use this prompt guide with ChatGPT.

### Option 1: Custom GPT

If your ChatGPT account allows creating a custom GPT:

1. Create a new GPT.
2. Open the GPT configuration screen.
3. Copy the full contents of `instructions/GPT_Instructions.txt` into the GPT's Instructions field.
4. Upload the following files as Knowledge:
   - `knowledge/H3_R2V_Master_Instructions.txt`
   - `knowledge/VIDEO_PROMPT_WRITING_GUIDE_ref_en.md`
5. Select a reasoning-capable model when available.
6. Enter your MiniMax H3 Reference-to-Video request in Japanese.

The GPT will return a structured English prompt using the required six-section format.

### Option 2: ChatGPT Project

If custom GPT creation or sharing is unavailable, you can use a ChatGPT Project instead.

1. Create a new ChatGPT Project.
2. Copy the full contents of `instructions/GPT_Instructions.txt` into the Project Instructions.
3. Upload the following files to the Project:
   - `knowledge/H3_R2V_Master_Instructions.txt`
   - `knowledge/VIDEO_PROMPT_WRITING_GUIDE_ref_en.md`
4. Start a new chat inside the Project.
5. Enter your MiniMax H3 Reference-to-Video request in Japanese.

### Example Requests

See the `examples` folder for tested input patterns:

- `basic_r2v.md` — basic Reference-to-Video generation
- `motion_context.md` — continuation using Motion Context
- `multi_subject.md` — multiple-character identity and position consistency

```text
生成方式：MiniMax H3 Reference to Video
動画尺：10秒

参照画像1：
20代後半の日本人女性のスタイルシート

参照画像2：
雨の夜のワンルーム

シーン：
女性が濡れた縞猫をタオルで優しく拭く。

セリフ・ナレーションなし。
```

## Notes

* Explicit user instructions to preserve, change, or remove visual elements take priority.
* Japanese dialogue should remain in Japanese unless explicitly requested otherwise.
* Motion Context should preserve continuity without unnecessarily repeating completed dialogue, actions, or environments.
* Missing information may be completed conservatively when needed for natural video generation.

## License

Apache License 2.0

```

---

## 次の操作
- いまのREADME本文を全部これに置き換える
- そのあと **Preview** を押す

Previewで問題なければ、次にコミットします。
```
