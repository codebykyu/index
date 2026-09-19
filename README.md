[index.html](https://github.com/user-attachments/files/32413179/index.html)
# index
隐患举报
html = """<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#1677ff">

  <title>桃枝路泵站片区排水提标改造及入河排口治理工程隐患举报奖励</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family:
        -apple-system,
        BlinkMacSystemFont,
        "PingFang SC",
        "Microsoft YaHei",
        Arial,
        sans-serif;
      background: #f5f7fa;
      color: #1f2329;
    }

    .page {
      width: 100%;
      max-width: 520px;
      min-height: 100vh;
      margin: 0 auto;
      padding: 35px 18px;
    }

    .card {
      background: #ffffff;
      border-radius: 20px;
      padding: 35px 22px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.06);
    }

    .icon {
      text-align: center;
      font-size: 48px;
      margin-bottom: 15px;
    }

    h1 {
      margin: 0;
      text-align: center;
      font-size: 25px;
      line-height: 1.5;
      font-weight: 700;
    }

    .sub-title {
      margin-top: 12px;
      text-align: center;
      font-size: 15px;
      color: #646a73;
      line-height: 1.8;
    }

    .notice-box {
      margin-top: 28px;
      padding: 16px;
      border-radius: 12px;
      background: #f7f8fa;
      font-size: 14px;
      line-height: 1.8;
      color: #646a73;
    }

    .buttons {
      margin-top: 28px;
    }

    .btn {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 100%;
      min-height: 58px;
      margin-top: 16px;
      padding: 15px 20px;
      border-radius: 13px;
      text-decoration: none;
      font-size: 18px;
      font-weight: 600;
      transition: transform 0.1s ease;
    }

    .btn:active {
      transform: scale(0.98);
    }

    .btn-rule {
      color: #1664ff;
      background: #eef4ff;
      border: 1px solid #d6e4ff;
    }

    .btn-report {
      color: white;
      background: #1664ff;
      border: 1px solid #1664ff;
    }

    .tips {
      margin-top: 28px;
      padding-top: 22px;
      border-top: 1px solid #eeeeee;
      text-align: center;
      font-size: 13px;
      color: #8f959e;
      line-height: 1.8;
    }

    .important {
      color: #d4380d;
      font-weight: 600;
    }
  </style>
</head>

<body>

<div class="page">
  <div class="card">

    <div class="icon">🛡️</div>

    <h1>桃枝路泵站片区排水提标改造及入河排口治理工程<br>隐患举报奖励</h1>

    <div class="sub-title">
      发现施工现场安全隐患，欢迎及时反馈
    </div>

    <div class="notice-box">
      举报前可先查看《隐患举报奖励办法》。
    </div>

    <div class="buttons">

      <a
        class="btn btn-rule"
        href="./jubao-jiangli.pdf"
        target="_blank"
        rel="noopener noreferrer"
      >
        📄&nbsp;&nbsp;查看举报奖励办法
      </a>

      <a
        class="btn btn-report"
        href="https://my.feishu.cn/share/base/form/shrcneV7QPb6Bd6scy3uTIKoPcb"
      >
        🚨&nbsp;&nbsp;立即举报
      </a>

    </div>

    <div class="tips">
      举报信息将用于安全隐患核实及整改。<br>
      请勿恶意提交虚假信息。<br><br>
      <span class="important">发现隐患，及时报告。</span>
    </div>

  </div>
</div>

</body>
</html>
"""

path = "/mnt/data/index.html"
with open(path, "w", encoding="utf-8") as f:
    f.write(html)

print(path)
