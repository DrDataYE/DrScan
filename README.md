# DrScan - Network and Device Scanning Tool

DrScan is a user-friendly tool that allows you to scan networks and connected devices. It can be used to discover devices connected to a network, check their status, and identify potential vulnerabilities. DrScan enables you to analyze and scan devices and services on the network easily and quickly.

## Features

- Scan local networks to discover connected devices.
- Determine device status and scan for potential vulnerabilities.
- User-friendly interface and simple configuration.
- Support for tool installation via the deb package.

## Installation

You can easily install DrScan using the `deb` package file. Follow these simple steps:

1. Download the `deb` package file from [here](https://github.com/DrDataYE/DrScan/blob/main/python3-drscan_1.0.0-1_all.deb).
2. Open the terminal and navigate to the folder where the file was downloaded.
3. Use the following command to install the package:

   ```bash
   sudo dpkg -i drscan-package.deb


4. بعد اكتمال التثبيت، يمكنك تشغيل DrScan باستخدام الأمر:
   
   ```bash
   drscan --help
   ```

## الاستخدام

بمجرد تشغيل DrScan، يمكنك استخدام الخيارات المختلفة لتنفيذ فحص الشبكة والأجهزة. مثال على استخدام الأمر:

```bash
drscan -A 192.168.1.0/24 -v
```

## المساهمة

إذا كنت مطورًا وترغب في المساهمة في تطوير DrScan، فنحن نرحب بالمساهمات. يمكنك المساهمة من خلال إرسال طلبات سحب (Pull Requests) إلى مستودع المشروع على GitHub.

## الترخيص

DrScan مرخصة بموجب رخصة LLM. انظر ملف `LICENSE` لمزيد من التفاصيل.

---
**ملحوظة:** قد تكون هناك بعض الاخطاء و المشاكل بلاداه لاكن سيتم حلها فيما بعد ان شاء الله.

**ملحوظة:** تأكد دائمًا من استخدام هذه الأداة بشكل قانوني وفقًا للقوانين المحلية. لا تتحمل الفريق المطور أي مسؤولية عن استخدام غير قانوني لهذه الأداة.
