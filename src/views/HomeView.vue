<script lang="ts">

</script>

<template>
  <div class="terminal-window">
    <div class="terminal-header">
      <div class="terminal-buttons">
        <div class="terminal-button red"></div>
        <div class="terminal-button yellow"></div>
        <div class="terminal-button green"></div>
      </div>
      <div class="terminal-title">
        love - bash
      </div>
    </div>
    <div class="terminal-body">
      <span style="color: rgb(0, 190, 0);">root@WCPE</span>
      <span style="color: blue;"> ~ </span>
      <span style="color: rgb(39, 39, 39);">./links.sh</span>
      <p>我的其他站点：</p>
      <ul class="ul">
        <li><a href="https://blog.wcpe.top/">博客</a></li>
        <li><a href="https://git.wcpe.top/">代码</a></li>
        <li><a href="https://github.com/wcpe/">GitHub</a></li>
      </ul>
      <span style="color: rgb(0, 190, 0);">root@WCPE</span>
      <span style="color: blue;"> ~ </span> <span id="typing-effect">shutdown</span>
    </div>
  </div>
</template>

<style scoped>
.terminal-window {
  width: 100%;
  height: 100%;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 6px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  font-family: 'Courier New', monospace;
  font-size: 14px;
}

.terminal-header {
  display: flex;
  align-items: center;
  height: 30px;
  background-color: #e0e0e0;
  border-top-left-radius: 6px;
  border-top-right-radius: 6px;
}

.terminal-buttons {
  display: flex;
  margin-left: 8px;
}

.terminal-button {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  margin-right: 4px;
}

.red {
  background-color: #ff5f56;
}

.yellow {
  background-color: #ffbd2e;
}

.green {
  background-color: #27c93f;
}

.terminal-title {
  margin-left: auto;
  margin-right: 8px;
}

.terminal-body {
  padding: 10px;
}

/* 新增的ul样式 */
.ul {
  list-style-type: none;
  margin: 0;
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 15px 0;
  border-radius: 10px;
  background-image: linear-gradient(to left, rgba(74, 76, 77, 0.055), rgba(18, 219, 192, 0.2));
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

.ul li {
  border-radius: 5px;
  transition: background-color 0.8s ease;
}

.ul li a {
  color: rgb(32, 167, 88);
  text-decoration: none;
}

.ul li:hover {
  background-color: #b2d3af;
}

</style>