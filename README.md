# Spider_XHS Skills

https://github.com/cv-cat/Spider_XHS
这个仓库用于存放基于 `Spider_XHS` 封装的 Agent Skills。

## 目录结构

- `skills/xhs-apis`：封装小红书 PC 端与创作者平台 API 的 skill

## xhs-apis

`xhs-apis` 这个 skill 只保留并封装了两组核心接口：

- `xhs_pc_apis.py`
- `xhs_creator_apis.py`

运行时所需的 vendored Python 与 JS 文件位于：

- `skills/xhs-apis/scripts/runtime/spider_xhs_core`

## 安装

安装 Python 依赖：

```
pip install -r skills/xhs-apis/scripts/requirements.txt
```

安装 Node 依赖：

```
Set-Location skills/xhs-apis/scripts
npm install
```

查看当前可用方法：

```
python skills/xhs-apis/scripts/xhs_api_tool.py list
```

## 说明

- 仓库会保留 skill 所需的标准文件，例如 `SKILL.md`、`agents/openai.yaml`、`references/` 与 `scripts/`。
- vendored runtime 已裁剪为仅支持 `xhs_pc_apis.py` 和 `xhs_creator_apis.py` 所需的最小文件集合。


## 📈 Star 趋势

<a href="https://www.star-history.com/#cv-cat/XhsSkills&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=cv-cat/XhsSkills&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=cv-cat/XhsSkills&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=cv-cat/XhsSkills&type=Date" />
  </picture>
</a>

---

## 🍔 交流群

如果你对爬虫和 AI Agent 感兴趣，请加作者主页 wx 通过邀请加入群聊

ps: 请加群4、17、18，人满或者过期 issue | wx 提醒

| group14 | group17 | group18 |
|:--:|:--:|:--:|
| <img width="280" alt="group14" src="https://github.com/user-attachments/assets/4ff4e202-7fc2-42f7-910a-e12d55456bd1" /> | <img width="280" alt="group17" src="https://github.com/user-attachments/assets/6406398d-a4c7-4b08-a92c-496ea10a4440" /> | <img width="280" alt="group18" src="https://github.com/user-attachments/assets/57f6a18c-d9d0-4343-b2eb-c32e1e991115" /> |


