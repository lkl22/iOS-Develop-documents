### Introduction

### 开发者账号申请成功后，登录后点击** Certificates, Identifiers & Profiles **进入证书管理界面![](/assets/user/user_certificates.png)Certificates

#### Creating a Certificate Signing Request \(CSR\)

In the Applications folder on your Mac, open the Utilities folder and launch **Keychain Access**.

Within the Keychain Access drop down menu, select _**Keychain Access &gt; Certificate Assistant &gt; Request a Certificate from a Certificate Authority.**_

* In the Certificate Information window, enter the following information:
  * In the User Email Address field, enter your **email address**.
  * In the Common Name field, create a name for your **private key** \(e.g., John Doe Dev Key\).
  * The CA Email Address field should be left empty.
  * In the "Request is" group, select the "**Saved to disk**" option.
* Click Continue within Keychain Access to complete the CSR generating process.

#### Add IOS Certificate

**Select Type**：选择需要的证书类型（按需选型）

**Request**：About Creating a Certificate Signing Request \(CSR\)，按指导生成CSR文件

**Generate**：Upload CSR file.Select certSigningRequest file saved on your Mac.点击**Continue**生成证书（证书名为：生成CSR时填的Common Name字段）

**Download**：点击 **Download **按钮下载证书，双击证书文件添加到 **Keychain **中

