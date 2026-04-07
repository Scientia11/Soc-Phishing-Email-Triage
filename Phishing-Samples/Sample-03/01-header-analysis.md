Extracted Headers

```text
Subject: Hi
To: Recipients <shore@suksapan.or.th>
From: shore@suksapan.or.th
Date: Wed, 02 Aug 2023 13:47:50 +0100
Reply-To: globalmeritexperts@gmail.com
Message-ID:
 <6e0afff7-e921-4f9b-a051-93760dc1e4ca@AM7EUR06FT021.eop-eur06.prod.protection.outlook.com>
Return-Path: shore@suksapan.or.th
Authentication-Results: spf=softfail (sender IP is 202.129.206.234)
 smtp.mailfrom=suksapan.or.th; dkim=none (message not signed)
 header.d=none;dmarc=none action=none header.from=suksapan.or.th;compauth=fail
 reason=001
X-Sender-IP: 202.129.206.234
```
## Analysis
1. The 'Reply-To' email address globalmeritexperts@gmail.com is inconsistent with the 'From' email address shore@suksapan.or.th.

2. The SPF record published on the suksapan.or.th domain has a policy that designates the IP address 202.129.206.234 as probably not permitted to send emails on behalf of suksapan.or.th domain.

3. 


Verdict: Suspicious

