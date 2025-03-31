<script setup lang="ts">
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

    <!-- 终端内文字 -->
    <div class="terminal-body">
      <span style="color: rgb(0, 190, 0);">root@WCPE</span>
      <span style="color: blue;"> ~ </span>
      <span style="color: rgb(39, 39, 39);">cat /me.txt</span>
      <div class="terminal-output">
        <p>
          <span style="color: green;">0x40FF</span> <span style="color: gray;">SYSTEM_FAILURE</span> <span
            style="color: green;">::</span> <span style="color: gray;">CORE_MODULE</span>
        </p>
        <p>
          <span style="color: green;">0x8801</span> <span style="color: gray;">MEM_ACCESS_ERR</span> <span
            style="color: green;">[</span> <span style="color: gray;">ADDR 0x1234</span> <span
            style="color: green;">]</span> <span style="color: gray;">SEGMENT_FAULT</span>
        </p>
        <p>
          <span style="color: green;">0x9E5A</span> <span style="color: gray;">LINK_DISRUPTION</span> <span
            style="color: green;">|</span> <span style="color: gray;">NETWORK_NODE</span> <span
            style="color: gray;">DOWN</span>
        </p>
        <p>
          <span style="color: green;">0xC133</span> <span style="color: gray;">DRIVER_MISMATCH</span> <span
            style="color: green;">-</span> <span style="color: gray;">HARDWARE</span> <span
            style="color: gray;">INCOMPATIBLE</span>
        </p>
        <p>
          <span style="color: green;">0x1F00</span> <span style="color: gray;">POWER_IRREGULARITY</span> <span
            style="color: green;">+++</span> <span style="color: gray;">---</span>
        </p>
      </div>


      <span style="color: rgb(0, 190, 0);">root@WCPE</span>
      <span style="color: blue;"> ~ </span>
      <span style="color: rgb(39, 39, 39);">sudo rm -rf /过去的自己/*</span>
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

.terminal-output {
  text-align: center;
}
</style>