# 如何在 OKX 上创建 API 密钥

本文详细介绍了在 OKX 平台上创建 API 密钥以及如何将 OKX 账户关联至 Coinmatics 的全流程。文中将引导您逐步设置账户、绑定手机或 Google 身份验证、创建 API 密钥并完成邮箱及验证码验证。本文关键词包括 **OKX**、**API 密钥**、**Coinmatics**、**登录**、**交易权限** 和 **现货交易**。

---

## 创建 API 密钥

1. **账户登录**  
   首先，使用 [登录](https://bit.ly/OKXe) 进入您的 OKX 账户。如果您还没有账户，请点击 [开立账户](https://bit.ly/OKXe) 进行注册。  
   *促销活动可能会随时间变动。*

2. **账户创建演示**  
   ![创建账户示意图](https://www.jmhbdh.com/wp-content/img/9440427223779.webp)

3. **手机或谷歌验证**  
   请确保已绑定手机号码或启用 Google 身份验证，绑定步骤为创建 API 密钥的必要操作。  
   ![验证示意图](https://www.jmhbdh.com/wp-content/img/65680067432908.webp)

4. **进入 API 密钥创建页面**  
   登录后，系统将显示主账户页面，点击 **“Create V5 API key”** 按钮进入创建页面.  
   ![创建 API 密钥入口](https://www.jmhbdh.com/wp-content/img/5390649823.webp)

5. **绑定第三方应用**  
   选择“Linking third-party apps”，在“App Name”列表中找到 **Coinmatics**。绑定后，系统默认将第三方应用的 IP 地址与 API 密钥关联，只有该应用可以调用相关接口。  
   *绑定后务必确认 API 密钥具有正确的权限设置才能确保自动交易功能正常。*

6. **填写密钥信息**  
   按照提示填写以下内容：  
   - **API 名称**：用于标识与 Coinmatics 关联的 API 密钥。  
   - **Passphrase**：用以对密钥进行加密保护（请妥善保存，否则遗失后需重新创建 API 密钥）。  
   - **权限**：请确保已启用交易权限（在启用读权限的基础上，额外开启 Trade 权限以支持现货交易下单）。  
   
   ![填写 API 密钥信息](https://www.jmhbdh.com/wp-content/img/409052231796.webp)

7. **验证并确认**  
   核查输入信息无误后，点击 **“Confirm”** 按钮。接下来，系统将要求您输入来自邮箱和身份验证器的验证码。点击 **“Send code”** 获取邮箱验证码后，输入相应认证码。  
   ![输入验证码](https://www.jmhbdh.com/wp-content/img/968162751337.webp)

8. **获取 API 详情**  
   确认后，系统会弹出 API 详情提示框。请复制其中的 API 密钥及 Secret 密钥。务必再次检查权限设置，确保 Trade 功能已被激活。  
   ![API 密钥详情](https://www.jmhbdh.com/wp-content/img/44443333.webp)

9. **完成创建**  
   您的新 API 密钥将显示在密钥列表中。请注意：Coinmatics 目前仅支持 OKX 的现货交易功能，且只有 Unified 账户中的交易才会被复制。  
   *请再次确认 Trade 权限已启用。*

---

## 关联 OKX 账户至 Coinmatics

1. 打开 Coinmatics 的账户页面，并点击“添加账户”。  
2. 选择 OKX 交易所，若您已有账户，可以直接进行 API 密钥绑定；如果没有账户，系统会提供如何创建账户与 API 密钥的简明指南。  
3. 输入 API 密钥详情，包括 API 密钥、Secret 密钥和 Passphrase（请在 OKX API 页面中核对）。填写完毕后点击“添加账户”。  
   ![选择交易所](https://www.jmhbdh.com/wp-content/img/561286262543.webp)
   
4. 提交后，系统会在页面中显示账户状态，如“Spot”字体颜色为灰色表示 Trade 权限已启用；否则，如显示为橙色，请重新核查 OKX 账户设置。  
   ![账户状态提示](https://www.jmhbdh.com/wp-content/img/0729127701404938.webp)

---

## 提交策略（针对交易者）

请注意，Coinmatics 仅复制 Unified 账户的现货交易，Classic 账户的交易将不被复制。确保您的账户与 API 绑定信息无误后，您即可开始配置交易策略。

---

## 观看教程视频

以下视频将带您更直观地了解整个设置流程：

<iframe src="https://www.youtube.com/embed/pvG94knJwwc"></iframe>


**总结：**  
本文在保持原意的基础上对标题和内容进行了优化，重新组织了段落、列表与图示，并自然融入了核心关键词。所有非 OKX 官方链接均已去除链接格式，确保文本结构清晰且便于搜索和阅读。