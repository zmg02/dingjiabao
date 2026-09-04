# 盯价宝 / 盯榜宝 隐私政策 / Privacy Policy

最后更新:2026-09-04

本政策适用于我们发布的两款浏览器扩展:**盯价宝**(网页元素变化监控)与**盯榜宝**(亚马逊关键词排名监控)。两者遵循完全相同的隐私原则。

## 中文

- **不收集任何个人信息。** 扩展没有账号系统,不要求注册。
- **数据只存在本地。** 你添加的监控/跟踪项、历史记录、激活码均保存在浏览器的 `chrome.storage.local` 中,不会上传到任何服务器。
- **不出售、不共享数据。** 因为我们根本不持有你的数据。
- **不发送遥测。** 无统计、无埋点。
- 卸载扩展即删除全部本地数据。

**各产品的网络访问范围:**

- **盯价宝**:网络请求仅指向你自行添加的网页,按你设定的间隔读取指定元素的文本,不访问其他站点。权限说明:`host_permissions` 访问你添加的任意商品页;`storage` 保存监控项;`alarms` 定时检查;`notifications` 变动提醒;`activeTab` / `scripting` 在当前页选取元素;`offscreen` / `sidePanel` 解析页面与展示列表。
- **盯榜宝**:网络请求仅指向亚马逊站点的搜索结果页(host 权限收窄至亚马逊域名),用于按你设定的关键词与 ASIN 检查排名位次,查完即关闭页面,不访问其他站点。权限说明:`storage` 保存跟踪项与排名历史;`alarms` 每日定时检查;`notifications` 位次变化提醒;`scripting` 在检查用的搜索结果页内提取位次信息;`sidePanel` 展示跟踪列表。

联系:通过 [GitHub Issues](https://github.com/zmg02/dingjiabao/issues) 或爱发电主页 https://ifdian.net/a/dingjiabao

## English

This policy covers both of our browser extensions: **盯价宝 (PriceWatch)** — monitors changes to page elements you choose (e.g. price, stock, rating) — and **盯榜宝 (RankWatch)** — monitors Amazon keyword rankings for ASINs you specify. Both follow the same privacy principles.

- **No personal data is collected.** There is no account or sign-up.
- **All data stays on your device** in `chrome.storage.local`: monitors/trackers, history and license key are never uploaded.
- **No selling or sharing of data** — we never hold it.
- **No telemetry.**
- Uninstalling the extension deletes all local data.

**Network scope per product:**

- **PriceWatch**: requests go only to pages you added, at the interval you set, to read the selected element's text. Permissions (`storage`, `alarms`, `notifications`, `activeTab`, `scripting`, `offscreen`, `sidePanel`, host permissions for pages you add) are used for core functionality only.
- **RankWatch**: requests go only to Amazon search result pages (host permissions are narrowed to Amazon domains), to check the ranking position of your specified ASINs; the page is closed right after each check. Permissions (`storage`, `alarms`, `notifications`, `scripting`, `sidePanel`) are used for core functionality only.

Contact: [GitHub Issues](https://github.com/zmg02/dingjiabao/issues)
