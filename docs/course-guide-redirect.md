---
hide:
  - navigation
  - toc
  - footer
---

# 选课导引

<div style="width:100%; background:#fff; position:relative; padding:0 0 0 0;">
  <button id="toggle-mode-btn" style="position:absolute; top:-30px; right:0; z-index:10; padding:0.18rem 0.6rem; font-size:0.82rem; border-radius:4px; border:1px solid #3498db; background:#fff; color:#3498db; cursor:pointer;">切换为3D版</button>
  <iframe id="course-iframe" src="https://nrdstudio.cn/view/link/c1391dc9223dce9a69c2a4629c542dee" style="border:none; width:100%; min-height:72vh; margin-top:-30px;" allowfullscreen></iframe>
</div>

<script>
const btn = document.getElementById('toggle-mode-btn');
const iframe = document.getElementById('course-iframe');
let is2D = true;
btn.onclick = function() {
  if (is2D) {
    iframe.src = 'https://nrdstudio.cn/view/link/f533c66425e9acdeb63c6bae94e993af';
    btn.textContent = '切换为2D版';
    is2D = false;
  } else {
    iframe.src = 'https://nrdstudio.cn/view/link/c1391dc9223dce9a69c2a4629c542dee';
    btn.textContent = '切换为3D版';
    is2D = true;
  }
}
</script>

<style>
/* 隐藏页面标题和导航 */
.md-typeset h1:first-child {
  display: none;
}

</style>