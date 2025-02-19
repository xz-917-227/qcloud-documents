本文档主要介绍企业第一次使用电子签的账号激活流程，总体流程如下：
![image-20210617101840793](https://main.qcloudimg.com/raw/e2c9ddb1986bc26e51143f7046a53a07.png)

## 操作步骤
### 步骤1：创建腾讯云企业账号
如果您已有完成实名认证的腾讯云企业账号可跳过此步骤。若未完成腾讯云企业账号，您需要 [注册腾讯云](https://cloud.tencent.com/document/product/378/17985) 账号并完成 [企业实名认证](https://cloud.tencent.com/document/product/378/10496)。

### 步骤2：登录腾讯电子签控制台
访问 [腾讯电子签控制台](https://ess.tencent.cn/)，单击腾讯云企业控制台入口进入腾讯云账号登录页面，您可使用主账号或已授权电子签策略的子账号进行登录。本文档以主账号登录为例，子账号登录指引可参见 [如何使用子用户账号登录电子签](https://cloud.tencent.com/document/product/1323/58484#Q13)。
![](https://main.qcloudimg.com/raw/a07f2987c2078de9dc7117ed5bbcbfef.png)

#### 使用主账号登录
通过已注册的腾讯云企业账号登录，支持的登录方式有微信、邮箱、QQ 和微信公众号。
>?您注册腾讯云账号的方式，即为您的腾讯云账号的登录方式。

![](https://main.qcloudimg.com/raw/a5909ec0434eb06d6d1cf594a0a2ce8a.png)



### 步骤3：应用激活流程
登录成功后进入应用激活流程，完成企业实名主体确认及超级管理员设置后，方可启用腾讯电子签的完整服务。

#### 1. 企业名称确认
确认企业名称，若信息无误可单击确认无误进入下一步。若企业名称与实际不一致，需前往腾讯云官网进行企业更名操作，更名指引可参见 [变更企业认证信息](https://cloud.tencent.com/document/product/378/43087)。

![image-20210617122036439](https://main.qcloudimg.com/raw/108517a928b405610e797283c4f2715e.png)

#### 2. 超级管理员设置[](id:smallStep2)
设置超级管理员，输入超级管理员的姓名、身份证号码以及手机号码，填写无误后单击下一步。

>?指定的超级管理员将拥有企业电子签合同管理的最高权限，请谨慎填写。

![image-20210617144718535](https://main.qcloudimg.com/raw/c29594e1a1f3442f80e50f5c31d82fdd.png)

#### 3. 授权方式设置[](id:smallStep3)
为保证企业合同数据的安全性，企业需对上一步设置的超级管理员进行相关授权，允许超级管理员代表企业行使在腾讯电子签账号下的一切权利（如申请相关账号及数字证书、印章管理、组织管理等）。目前系统支持**上传授权书**和**法定代表人授权**两种授权方式，您可选择任意一种方式完成授权即可。

<dx-tabs>
::: 通过上传授权书完成授权
单击下载超级管理员授权证书模板，按照模板要求填写相关信息签字并加盖企业公章后进行上传，资料仅供认证之用，请务必确保资料的真实性与一致性。目前仅支持 JPG / PNG / PDF 的文件格式，且文件大小不超过8M。确认企业及超级管理员信息（需与授权证书信息一致），确认无误后单击下一步完成授权操作。
![image-20210617162414902](https://main.qcloudimg.com/raw/70b01c0bc57239bec71eb434ab55808f.png)
:::
::: 通过法定代表人授权
确认企业名称，输入企业社会统一信用代码、法定代表人姓名、法定代表人身份证号码以及法定代表人手机号码。输入后确认无误单击下一步完成授权操作。

<dx-alert infotype="explain" title="说明：">
输入的法定代表人信息需与企业注册法定代表人信息一致，如不一致则无法提交成功。
</dx-alert>

![image-20210617164619350](https://main.qcloudimg.com/raw/ab8577908ea2681e3649a3f43be78cd5.png)
:::
</dx-tabs>

#### 4. 激活完成
单击下一步企业激活成功，您可进入企业管理后台。于此同时，系统会向[2](#smallStep2)、[3](#smallStep3)步中设置的超级管理员与法定代表人代表发送对应授权短信（若授权方式选择的为上传授权书，则需等待人工审核）。

只有完成超管激活和法定代表人授权才能启用腾讯电子签完整功能以及购买电子签服务，超管激活指引可参见 [超管激活流程](https://cloud.tencent.com/document/product/1323/58493)，法定代表人授权指引可参见 [法定代表人授权流程](https://cloud.tencent.com/document/product/1323/58494)。

![image-20210617173229041](https://main.qcloudimg.com/raw/dc970a9d3f8c4a068c140ab10c21114b.png)



### 步骤4：查看当前状态
在企业信息页您可查看当前超级管理员与法定代表人代表的激活状态，您也可单击催办按钮进行催办。若授权方式为授权书上传，则会显示当前的授权书审核状态，我们将会在1-3个工作日内完成审核。
![image-20210617185825274](https://main.qcloudimg.com/raw/3d634edacbee052530170844027d0c85.png)

### 步骤5：使用腾讯电子签服务
完成激活流程后，您可参见如下操作指南文档使用腾讯电子签服务。
- [创建角色](https://cloud.tencent.com/document/product/1323/61355)
- [新增员工](https://cloud.tencent.com/document/product/1323/58495)
- [配置印章](https://cloud.tencent.com/document/product/1323/59451)
- [发起合同](https://cloud.tencent.com/document/product/1323/61360)
- [创建模板](https://cloud.tencent.com/document/product/1323/61357)

## 联系我们
如您按照文档进行操作的过程中遇到问题，您可通过 e-contract@tencent.com 联系我们，我们将竭诚为您服务！
