# Motion Context Example

## Input

```text
生成方式：MiniMax H3 Reference to Video
動画尺：8秒

Motion Context：
前のクリップで保存したMotion Contextを読み込む。

前のクリップ：
晴れた朝のワンルーム。
女性が玄関で猫に「行ってきます」と言い、
猫が一度鳴いたところで終了。

今回のクリップ：
前のクリップから自然につながる。
女性は玄関のドアを開けて外へ出る。
猫は玄関の内側に残り、女性を静かに見送る。
女性は廊下へ出たあと、ドアを静かに閉める。

今回のクリップではセリフを入れない。
猫も鳴かない。
ナレーションなし。
BGMなし。

前のクリップの「行ってきます」というセリフと
猫の鳴き声を繰り返さない。

## Purpose

This example demonstrates how to use Motion Context for a direct continuation between clips.

The generated prompt should:

- continue from the final visual and motion state of the previous clip
- preserve the intended character, environment, and motion continuity
- avoid replaying dialogue, actions, or sound events that were already completed in the previous clip
- follow the new actions specified for the current clip
- preserve only the elements that should continue from the previous clip
- avoid carrying over obsolete actions, dialogue, or scene elements
- maintain a natural transition into the next action
- follow the user's dialogue, narration, music, and sound instructions exactly

The generated output should follow the required six-section format.
