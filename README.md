<div align="center">

# GPT-Policy

**In-context robot learning, in the real world.**

<sub>Research preview · Real robot demonstrations</sub>

</div>

We explore how general-purpose multimodal agents can perform real robot tasks with visual context and live feedback. **No task-specific reinforcement learning. No DAgger.**

## Plug insertion

Grasp, align, insert, and release. A video demonstration guides the robot as it places a plug into a power strip and adjusts through contact.

<p align="center">
  <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/plug-insertion.mp4">
    <img src="assets/plug-insertion.gif" alt="A robot grasps a plug, aligns it with a power strip, inserts it, and withdraws." width="720">
  </a>
  <br>
  <sub>Video-conditioned execution · 12× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/plug-insertion.mp4">Download MP4 ↗</a></sub>
</p>

## More demos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Find the hidden goal</h3>
      <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/hidden-goal.mp4"><img src="assets/hidden-goal.gif" alt="A robot uncovers a pink plate and places a lemon on it." width="100%"></a>
      <p>Move the towel, reveal the plate, place the lemon. A visual demonstration provides the missing task context.</p>
      <sub>8× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/hidden-goal.mp4">Download MP4 ↗</a></sub>
    </td>
    <td width="50%" valign="top">
      <h3>Make the picture real</h3>
      <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/visual-goal.mp4"><img src="assets/visual-goal.gif" alt="A robot arranges five colored blocks into a T shape using reference photos." width="100%"></a>
      <p>Use reference photos to arrange five colored blocks into a T, adjusting their placement along the way.</p>
      <sub>24× playback · <a href="https://github.com/cheng-haha/GPT-Policy-Report/raw/refs/heads/main/assets/visual-goal.mp4">Download MP4 ↗</a></sub>
    </td>
  </tr>
</table>

<sub>Selected individual trials, accelerated for presentation. Broader evaluation is ongoing.</sub>

## What's next

- **Broader tasks** — more contact-rich manipulation and longer task sequences.
- **Systematic evaluation** — repeated trials, more models, and different forms of visual context.
- **Public report** — results, failure cases, and what we learn about in-context robot learning.
