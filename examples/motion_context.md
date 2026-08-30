# Motion Context Example

## Input

```text
生成方式：MiniMax H3 Reference to Video
動画尺：10秒

Motion Context：
前のクリップで保存したMotion Contextを読み込む。

前のクリップ：
雨の夜のワンルーム。
一人暮らしの女性の部屋に、雨でびしょ濡れになった縞猫がベランダから迷い込んでくる。
猫が部屋に入ってくるとき、一度だけ小さく鳴く。
女性は猫に気づき、濡れた身体をタオルで優しく拭いてあげる。
その後、女性は猫に餌を与えるところで終了。

今回のクリップ：
前のクリップから自然につながる。
女性は食事を終えた猫のために、部屋の隅にタオルやクッションを使って簡単な寝床を用意する。
猫は女性の近くで落ち着きながら、その様子を見ている。
女性が寝床を整えると、猫はゆっくり近づいてその上に座る。
女性は猫の様子を見て安心したように微笑む。

今回のクリップではセリフを入れない。
猫は鳴かない。
ナレーションなし。

BGM：
前のクリップから、穏やかでほっこりした雰囲気の優しいインストゥルメンタルBGMを自然に継続する。

前のクリップの以下の動作や音を繰り返さない：
- 猫がベランダから部屋へ入ってくる動作
- 猫の最初の鳴き声
- 女性が猫の身体をタオルで拭く動作
- 女性が猫に餌を与える動作

Purpose

This example demonstrates the general use of Motion Context for a direct continuation between MiniMax H3 Reference-to-Video clips.

Users should replace the previous-clip and current-clip descriptions with their own video content.

The assistant should:

continue naturally from the final visual and motion state of the previous clip
preserve the intended character, environment, appearance, and motion continuity
treat completed actions from the previous clip as already finished
avoid replaying dialogue, vocalizations, sound events, or actions that were completed in the previous clip
follow the new actions specified for the current clip
preserve only the elements that should continue from the previous clip
avoid carrying over obsolete actions, dialogue, props, or scene events
maintain spatial continuity when the same environment continues
follow the user's dialogue, narration, sound, and music instructions exactly
continue previously established background music only when the user explicitly requests continuity

The generated output should follow the required six-section format.

The Purpose section does not need to be edited for each new video request.
