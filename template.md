## whats new

> 1345 quote

**this is a blob text**

- one
  - tow
    - three

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>


<div >

</div>


----

<style>
    /* 全局重置与基础样式 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
    }

    body {
      /* 背景遮罩层（半透明黑） */
      background-color: rgba(0, 0, 0, 0.5);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    /* 弹窗容器 */
    .modal {
      background-color: #1E1E1E; /* 深灰背景 */
      width: 90%;
      max-width: 360px;
      border-radius: 16px;
      padding: 24px;
      color: #FFFFFF;
      position: relative; /* 用于关闭按钮绝对定位 */
    }

    /* 关闭按钮 */
    .close-btn {
      position: absolute;
      top: 12px;
      right: 12px;
      font-size: 20px;
      cursor: pointer;
      background: none;
      border: none;
      color: #FFFFFF;
    }

    /* 头部区域（版本号 + 大标题） */
    .header {
      text-align: center;
      margin-bottom: 24px;
    }
    .version {
      font-size: 16px;
      color: #4CAF50; /* 亮绿色，贴近原「App update V3.1.0」色调 */
      margin-bottom: 8px;
    }
    .main-title {
      font-size: 24px;
      font-weight: bold;
    }

    /* 信息区块（图标 + 文字） */
    .info-section {
      display: flex;
      align-items: flex-start;
      margin-bottom: 20px;
    }
    .icon {
      width: 40px;
      height: 40px;
      background-color: #333; /* 图标背景浅灰 */
      border-radius: 8px;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-right: 12px;
      flex-shrink: 0; /* 防止图标被压缩 */
    }
    .icon-content {
      font-size: 20px;
      color: #FFFFFF;
    }
    .info-text {
      flex: 1; /* 文字区占剩余宽度 */
    }
    .info-title {
      font-size: 16px;
      font-weight: bold;
      margin-bottom: 4px;
    }
    .info-desc {
      font-size: 14px;
      line-height: 1.4; /* 行高更易读 */
    }

    /* 「Read more」链接 */
    .read-more {
      display: block;
      text-align: center;
      margin: 20px 0;
      color: #4CAF50; /* 绿色强调 */
      text-decoration: none;
      font-size: 14px;
    }

    /* 「Got it」按钮 */
    .confirm-btn {
      width: 100%;
      background-color: #FFFFFF;
      color: #1E1E1E;
      border: none;
      padding: 12px;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }
  </style>


<div class="modal">
    <!-- 关闭按钮 -->
    <button class="close-btn">×</button>

    <!-- 头部：版本号 + 大标题 -->
    <div class="header">
      <div class="version">App update V3.1.0</div>
      <h1 class="main-title">What's New</h1>
    </div>

    <!-- 信息区块1：钱包导入 -->
    <div class="info-section">
      <div class="icon">
        <span class="icon-content">🪙</span> <!-- 钱包 emoji 替代图标 -->
      </div>
      <div class="info-text">
        <div class="info-title">What's new</div>
        <div class="info-desc">If you already use an Ethereum wallet like MetaMask or Rainbow, you can import those same accounts to access everything on Flow.</div>
      </div>
    </div>

    <!-- 信息区块2：Flow 原生应用 -->
    <div class="info-section">
      <div class="icon">
        <span class="icon-content">🏪</span> <!-- 商店 emoji 替代图标 -->
      </div>
      <div class="info-text">
        <div class="info-title">Flow-native apps for your accounts</div>
        <div class="info-desc">Get instant access to DeFi, marketplaces, and experiences on Flow.</div>
      </div>
    </div>

    <!-- 信息区块3：EVM 账户说明 -->
    <div class="info-section">
      <div class="icon">
        <span class="icon-content">ℰ</span> <!-- 自定义字符替代 EVM 图标（也可用 SVG/图片） -->
      </div>
      <div class="info-text">
        <div class="info-title">Already using Flow Wallet?</div>
        <div class="info-desc">You’ll see a new "EVM" account alongside your Cadence accounts and your now legacy "EVM Flow" account.</div>
      </div>
    </div>

    <!-- 信息区块4：价值说明 -->
    <div class="info-section">
      <div class="icon">
        <span class="icon-content">📊</span> <!-- 图表 emoji 替代图标 -->
      </div>
      <div class="info-text">
        <div class="info-title">Why this matters</div>
        <div class="info-desc">Your new EVM account is super-powered by Flow, unlocking gasless transactions, MEV-resilience and more.</div>
      </div>
    </div>

    <!-- 阅读更多链接 -->
    <a href="#" class="read-more">Read more</a>

    <!-- 确认按钮 -->
    <button class="confirm-btn">Got it</button>
  </div>


----


- ui
- ux
- dev
