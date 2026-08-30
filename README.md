````markdown
# MiniMax H3 R2V Prompt Guide

A prompt guide and GPT configuration for generating structured English prompts for MiniMax H3 Reference-to-Video (R2V).

This repository is designed to help users build consistent MiniMax H3 prompts from Japanese scene descriptions, reference images, and Motion Context.

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
│  ├─ H3_R2V_Master_Instructions
│  └─ VIDEO_PROMPT_WRITING_GUIDE_ref_en.md
├─ examples/
│  ├─ basic_r2v.md
│  ├─ motion_context.md
│  └─ multi_subject.md
└─ CHANGELOG.md
````

## How to Use

1. Create a custom GPT or a ChatGPT Project.
2. Copy the contents of `instructions/GPT_Instructions.txt` into the GPT or Project instructions.
3. Upload the files in the `knowledge` folder as Knowledge / Project files.
4. Enter your MiniMax H3 R2V scene description in Japanese.
5. The assistant will generate a structured English prompt for MiniMax H3.

## Recommended Model

For complex Reference-to-Video prompts, Motion Context, and multi-subject scenes, a reasoning-capable model is recommended.

## Example Input

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
