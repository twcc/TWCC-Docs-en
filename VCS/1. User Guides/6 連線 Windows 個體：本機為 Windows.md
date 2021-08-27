---
tags: Guide, VCS, TW
title: 連線 Windows：本機為 Windows | en
GA: UA-155999456-1
---

{%hackmd @docsharedstyle/default %}
{%hackmd @docsharedstyle/twccheader-en %}


# Connect to Windows instance: local machine as Windows

After finished [Preparation and Obtain connection information](https://man.twcc.ai/@twccdocs/vcs-guide-connect-prerequisite-en), please refer to the following method to connect to the Windows instance ( local machine as Windows).

:::info
{%hackmd @docsharedstyle/note-en %}
Please note that the status of the instance must be **`Ready`** before it can be used online.
:::

:::danger
{%hackmd @docsharedstyle/important-en %}
1. Due to frequent information security incidents, if your connection comes from the following countries, we will disable your remote connection to Windows instance (port: 9833): China, Germany, France, South Korea, Netherlands, Poland, Russia. If you need to connect to TWCC Windows instance, please contact customer service.
2. If you modify the network interface card settings, you will not be able to connect to the Virtual Compute Service(VCS) instance. Therefore, we strongly recommend you to not change the network interface card settings. Please pay more attention during your operation and deployment.
:::

## Connection method


- **Step 1.** Open the **Remote Desktop Connection** program ( built-in Windows operating system, or download from the official Microsoft webpage)

![](https://cos.twcc.ai/SYS-MANUAL/uploads/upload_684a5e256e0fa4a4941d16eec10433e6.png)


- **Step 2.** Enter the public IP address , Port and user name of the instance, and then click "**Connect**"
    
:::info
<i class="fa fa-paperclip fa-20" aria-hidden="true"></i> **Note:** After public IP address need to add on the port number`: 9833`,  example like: 203.145.222.23`:9833`
:::
![](https://cos.twcc.ai/SYS-MANUAL/uploads/upload_b1373c3c43427837667e57a967250fc0.png)

- **Step 3.** Enter the password and the connection is successful

![](https://cos.twcc.ai/SYS-MANUAL/uploads/upload_85a08f020c91828bcd92f5d2800af23a.png)

:::info
Account: administrator
Password: User-defined VCS instance password
:::
