<div align="center">

# GPT-Policy-Eval

**One-Shot Video Demonstration → Real-World Robot Execution**

<sub>Research preview · Real robot demonstrations</sub>

**English** · [简体中文](README.zh-CN.md)

[![View on X](assets/x-post.svg)](https://x.com/z_code68632/status/2098401554676269236)

</div>

We use **GPT-6 Astra** to guide real robots with **one video demonstration** and live visual feedback.

<table align="center">
  <tr>
    <td align="center" valign="middle" width="240" height="80"><strong>No VLA</strong></td>
    <td align="center" valign="middle" width="240" height="80"><strong>No WAM</strong></td>
  </tr>
  <tr>
    <td align="center" valign="middle" width="240" height="80"><strong>No RL</strong></td>
    <td align="center" valign="middle" width="240" height="80"><strong>No DAgger</strong></td>
  </tr>
</table>

## One-Shot Plug Insertion

From a single video demonstration, the robot grasps a plug, aligns it with a power strip, inserts it, and releases it, adjusting through contact.

<p align="center">
  <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/plug-insertion-top-and-right-wrist.mp4">
    <img src="assets/plug-insertion-top-and-right-wrist.gif" alt="Synchronized top and right wrist views of a robot grasping a plug, aligning it with a power strip, inserting it, and releasing it." width="960">
  </a>
  <br>
  <sub>Left: top view · Right: right wrist view · 12× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/plug-insertion-top-and-right-wrist.mp4">Download MP4 ↗</a></sub>
</p>

## More demos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Find the hidden goal</h3>
      <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/hidden-goal.mp4"><img src="assets/hidden-goal.gif" alt="A robot uncovers a pink plate and places a lemon on it." width="100%"></a>
      <p>Move the towel, reveal the plate, place the lemon. A single video demonstration provides the task context.</p>
      <sub>One video demonstration · 8× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/hidden-goal.mp4">Download MP4 ↗</a></sub>
    </td>
    <td width="50%" valign="top">
      <h3>Make the picture real</h3>
      <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/visual-goal.mp4"><img src="assets/visual-goal.gif" alt="A robot arranges five colored blocks into a T shape using reference photos." width="100%"></a>
      <p>Use reference photos to arrange five colored blocks into a T, adjusting their placement along the way.</p>
      <sub>Goal-image prompting · 24× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Eval/raw/refs/heads/main/assets/visual-goal.mp4">Download MP4 ↗</a></sub>
    </td>
  </tr>
</table>

<sub>Selected individual trials, accelerated for presentation. Broader evaluation is ongoing.</sub>

## Key moments

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <a href="assets/plug-insertion-keyframe.png"><img src="assets/plug-insertion-keyframe.png" alt="Plug insertion keyframe with top and wrist camera views; the right wrist view shows the plug seated in the power strip." width="100%"></a>
      <strong>Plug insertion</strong>
    </td>
    <td width="33%" align="center" valign="top">
      <a href="assets/hidden-goal-keyframe.png"><img src="assets/hidden-goal-keyframe.png" alt="Occlusion-aware manipulation keyframe: the towel has been moved aside and the lemon is lowered into the revealed plate." width="100%"></a>
      <strong>Reveal and place</strong>
    </td>
    <td width="33%" align="center" valign="top">
      <a href="assets/visual-goal-keyframe.png"><img src="assets/visual-goal-keyframe.png" alt="Goal-image manipulation keyframe showing the reference image and five colored blocks arranged in a T on the table." width="100%"></a>
      <strong>Match the goal</strong>
    </td>
  </tr>
</table>

<sub>Keyframes from the demo overview. Click an image to enlarge.</sub>

## What we'll do next

- **Code release** — prepare and share demo and evaluation code, with usage examples.
- **Broader tasks** — more contact-rich manipulation and longer task sequences.
- **Systematic evaluation** — repeated trials, more models, and different forms of visual context.
