##Key Headers Extracted

```text
From: alerts@chase.com
Date: Wed, 01 May 2024 20:04:05 +0000
Message-ID: <i7g9MMh5NtErtaOzQZEp3D-i-u3FWwdo0wY5mhD8Q1vIvv1yeLj-jMWPAn-HP3FugKsucesWSubO0Vns8GRFYG0aH4MyU2paqP6yUnRcgaU=@protonmail.com>
Subject: Your Bank Account has been blocked due to unusual activities
To: Bob Sanders <bob.sanders@corhalitech.com>
Reply-To: kellyellin426@proton.me
Return-Path: kellyellin426@proton.me
Authentication-Results: spf=pass (sender IP is 185.70.40.140)
smtp.mailfrom=protonmail.com; dkim=timeout (key query timeout)
header.d=protonmail.com;dmarc=pass action=none
header.from=protonmail.com;compauth=pass reason=100
Sender IP: 185.70.40.140
```
##My Analysis And Findings
1. The 'Reply-To' email address 'kellyellin426@proton.me' is inconsistent with the 'From' email address 'alerts@chase.com'.

2. The 'Return-Path' domain proton.me is inconsistent with the 'From' domain chase.com.

3. The IP location of the 'From' domain chase.com which is Washington, United States mismatches with the IP location of the 'Return-Path' domain proton.me which is Geneve,Switzerland.

Verdict: Malicious(Spoofed Sender)

Recommendation:
