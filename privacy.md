# 盯价宝 隐私政策 / Privacy Policy

最后更新:2026-09-01

## 中文

**盯价宝**是一款浏览器扩展,用于监控用户自行指定的网页元素(如商品价格、库存、评分)的变化。

- **不收集任何个人信息。** 扩展没有账号系统,不要求注册。
- **数据只存在本地。** 你添加的监控项、历史记录、激活码均保存在浏览器的 `chrome.storage.local` 中,不会上传到任何服务器。
- **网络请求仅指向你添加的网页。** 扩展按你设定的间隔请求这些页面以读取指定元素的文本,不访问其他站点,不发送遥测。
- **权限说明:** `host_permissions` 用于访问你自行添加的任意商品页;`storage` 保存监控项;`alarms` 定时检查;`notifications` 变动提醒;`activeTab` / `scripting` 用于在当前页选取元素;`offscreen` / `sidePanel` 用于解析页面与展示列表。
- **不出售、不共享数据。** 因为我们根本不持有你的数据。
- 卸载扩展即删除全部本地数据。

联系:通过 [GitHub Issues](https://github.com/zmg02/dingjiabao/issues) 或爱发电主页 https://ifdian.net/a/dingjiabao

## English

**盯价宝 (PriceWatch)** is a browser extension that monitors changes to page elements you choose (e.g. price, stock, rating).

- **No personal data is collected.** There is no account or sign-up.
- **All data stays on your device** in `chrome.storage.local`: monitors, history and license key are never uploaded.
- **Network requests go only to pages you added**, at the interval you set, to read the selected element's text. No telemetry.
- **Permissions:** host permissions for pages you add; `storage`, `alarms`, `notifications`, `activeTab`, `scripting`, `offscreen`, `sidePanel` for core functionality only.
- **No selling or sharing of data** — we never hold it.
- Uninstalling the extension deletes all local data.

Contact: [GitHub Issues](https://github.com/zmg02/dingjiabao/issues)
