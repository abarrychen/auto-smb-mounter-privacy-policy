# Auto SMB Mounter Privacy Policy

Effective date: September 26, 2026

Auto SMB Mounter is a macOS utility for managing SMB connections. The app is designed to keep its settings and diagnostics on your Mac.

## Information stored on your Mac

Connection settings (such as connection names, SMB server and share paths, connection conditions, and any VPN probe host and port), language, and startup preferences are stored on your Mac. If you choose to save credentials, the SMB username and password are stored in macOS Keychain, not in the connection profile or app log.

## Network connections

The app uses macOS network monitoring and makes TCP reachability probes to the hosts and ports you configure. To mount a share, it connects directly to your SMB server through macOS NetFS. Information needed for these connections is sent to the host you selected to provide the requested connectivity and mounting features. The app developer does not receive this information.

## Diagnostics

The app keeps up to 500 recent activity entries on your Mac and also uses the macOS unified logging system. Entries cover network, probe, mount, and recovery states. The app attempts to redact URLs, host addresses, local paths, and credential-like text before writing its log. macOS controls the retention of unified logs. Avoid putting sensitive information in connection names.

## Sharing and tracking

The app has no account or cloud sync service and includes no advertising, third-party analytics, or tracking. The developer does not collect, sell, or share your connection settings, credentials, or diagnostic logs.

## Retention and deletion

You can delete a connection in the app; the app attempts to remove the Keychain credentials associated with that connection. If macOS cannot complete that deletion, the credentials may remain in Keychain. Activity logs are limited to 500 entries, with newer entries replacing older ones. Removing the app does not necessarily remove preferences, logs, or Keychain items retained by macOS.

## Changes and contact

If this policy changes, we will update the policy and its effective date. For privacy questions, use the developer contact information listed on this app’s App Store page.

---

# Auto SMB Mounter 隱私權政策

生效日期：2026 年 9 月 26 日

Auto SMB Mounter 是用來管理 SMB 連線的 macOS 工具。App 設計為將設定與診斷資料保留在你的 Mac 上。

## 本機儲存的資料

連線設定（例如連線名稱、SMB 伺服器與分享路徑、連線條件、選用的 VPN 探測主機與連接埠）、語言與啟動偏好會儲存在你的 Mac 上。若你選擇儲存帳密，SMB 使用者名稱與密碼會存放在 macOS Keychain，不會存入連線設定檔或 App 記錄檔。

## 網路連線

App 會使用 macOS 網路狀態監測功能，並依照你設定的主機與連接埠進行 TCP 可達性探測；掛載 SMB 分享時，會透過 macOS NetFS 直接連線至該 SMB 伺服器。相關連線資料會傳送到你指定的主機，以提供你要求的連線與掛載功能。App 開發者不會收到這些資料。

## 診斷記錄

App 會在你的 Mac 本機保留最近最多 500 筆活動記錄，並使用 macOS 統一記錄系統。記錄內容包括網路、探測、掛載與復原狀態。App 會嘗試在寫入前遮蔽網址、主機位址、本機路徑及類似帳密的文字；macOS 統一記錄的保留方式則由 macOS 管理。請避免在連線名稱中輸入敏感資料。

## 資料分享與追蹤

App 不提供帳號或雲端同步，也不包含廣告、第三方分析或追蹤功能。開發者不會收集、出售或分享你的連線設定、帳密或診斷記錄。

## 保留與刪除

你可以在 App 中刪除連線設定；刪除設定時，App 會嘗試移除與該設定關聯的 Keychain 帳密。若系統無法完成刪除，帳密可能仍留在 Keychain。活動記錄最多保留 500 筆，並由新記錄逐步取代。移除 App 本身不一定會刪除 macOS 保留的偏好設定、記錄或 Keychain 項目。

## 政策更新與聯絡方式

政策有變更時，我們會更新此政策及生效日期。如有隱私問題，請使用此 App App Store 頁面所列的開發者聯絡方式。

## Website hosting and visitor data

This policy page is hosted by GitHub Pages. GitHub states that it logs and stores visitors' IP addresses for security purposes. This hosting log relates to visits to this website and is separate from the app's data handling. See [GitHub Pages privacy details](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

## 本政策網站的託管與訪客資料

本政策頁由 GitHub Pages 託管。GitHub 表示會基於安全目的記錄並儲存訪客 IP 位址。這些託管記錄是網站瀏覽資料，與 App 本身的資料處理分開。詳情請參閱 [GitHub Pages 隱私說明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)及 [GitHub 隱私權聲明](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)。
