---
layout: default
title: Privacy Policy
description: How PicNum collects, uses, stores, and deletes photos and related app data.
updated: September 21, 2026
---

This policy explains how PicNum collects, uses, stores, shares, and deletes information when you use the app or contact support.

## Information PicNum Processes

**Photos you select** — PicNum uses Apple's system photo picker, so the app receives only the item you choose. The selected photo is uploaded to our server to generate a paint-by-numbers canvas.

**Generated content and job data** — our server temporarily stores the generated painting document, numbered regions, palette, previews, job status, difficulty, timestamps, and technical processing information. Your painting library, coloring progress, and color edits are saved locally on your device; they are not synchronized through an account.

**Anonymous client identifier** — the app creates a random identifier and stores it in the iOS Keychain. The backend uses it to keep jobs private to the app installation, apply rate limits, maintain the credit balance, and connect purchase events. We do not require a name, email address, Apple Account, or PicNum account, but data associated with this persistent identifier is treated as linked data for App Store privacy disclosure purposes.

**Purchases** — Apple processes App Store payments. RevenueCat sends purchase and entitlement information to PicNum so we can grant credits, prevent duplicate grants, process revocations or refunds, and troubleshoot purchase problems. PicNum does not receive your full payment-card details.

**Diagnostics and support messages** — the app writes diagnostic events to Apple's local logging system. If you choose **Report a Problem**, the message can include the app and OS versions, device model, environment, timestamp, context, and shortened client and job identifiers. It does not automatically attach your photo or painting. Email providers process anything you choose to send.

**Technical service data** — our servers and infrastructure providers may process an IP address, request time, requested endpoint, response status, and security or error information needed to operate and protect the service.

## How We Use Your Information

- To generate your paint-by-numbers painting from a photo you choose
- To deliver generated painting data to your device
- To save local painting progress on your device
- To verify purchases, grant or refund credits, and prevent duplicate grants
- To secure the service, enforce rate limits, prevent abuse, and diagnose failures
- To respond to support, privacy, and legal requests

PicNum does not sell personal information, use it for third-party advertising, or track you across other companies' apps and websites.

## Photo Handling

Your original photo is used only to generate the requested painting. After a successful conversion, the service attempts to delete it immediately. If conversion or immediate deletion fails, the upload is scheduled for deletion within seven days. Photos are not used to train machine-learning models. They are not routinely reviewed by people; access is limited to what is necessary for support, security, service operation, or legal obligations.

## Retention

- Original photos are normally deleted immediately after successful conversion; failed or undeleted uploads are scheduled for deletion within 7 days.
- Standard generated painting artifacts are scheduled for deletion after 60 days.
- Internal conversion-debug artifacts are scheduled for deletion after 14 days.
- Raw RevenueCat webhook payloads are retained for 30 days and then removed. A limited transaction summary may be retained longer to prevent duplicate grants and support financial or legal obligations.
- Local paintings, progress, and preferences remain on your device until the app and its local data are deleted. The anonymous client identifier is stored in the iOS Keychain and may persist after app deletion under normal iOS behavior.
- Database job records, the anonymous client identifier, credit ledger, summarized transaction records, security logs, and support correspondence may be retained while needed to operate the credit balance, prevent fraud, resolve disputes, satisfy accounting or legal duties, and process deletion requests. Where a record must be preserved, we delete or anonymize information that is no longer necessary when reasonably possible.

Deletion schedules depend on the production cleanup service operating correctly. If an automated deletion fails, the item remains queued for deletion and can be removed through the manual process described below.

## Third-Party Services

PicNum uses service providers only to operate the app, store and process data, deliver purchases, provide network infrastructure, and respond to support requests. They may process information in countries other than your own and are required to protect it consistently with their agreements and applicable law.

- [Apple](https://www.apple.com/legal/privacy/) — App Store distribution, in-app payments, system photo selection, and optional Apple diagnostics
- [RevenueCat](https://www.revenuecat.com/privacy/) — purchase validation, entitlement events, and credit-purchase lifecycle information
- [Cloudflare](https://www.cloudflare.com/privacypolicy/) — R2 object storage for temporary uploaded photos and generated artifacts
- [Supabase](https://supabase.com/privacy) — hosted PostgreSQL database for anonymous identifiers, jobs, credits, and transaction records
- [Google Cloud](https://cloud.google.com/terms/cloud-privacy-notice) — production application hosting and server logs
- **DuckDNS** — domain-name resolution for the production API

## Data Storage and Security

We use encrypted HTTPS connections, signed sessions, access controls, private object storage, rate limits, and operational monitoring intended to protect information from unauthorized access, alteration, loss, or disclosure. No internet service can guarantee absolute security.

## Your Rights

Depending on where you live, you may have rights to request access, correction, deletion, restriction, portability, or an objection to certain processing. You may also withdraw consent where processing relies on consent and complain to your local data-protection authority.

Because PicNum has no account or email login, we cannot find backend records from your email address alone. To request deletion, use **Report a Problem** in the app and keep the diagnostic section containing the client-ID suffix, or contact support with that suffix and an approximate conversion date. We will verify the request, delete eligible server artifacts and records, and explain any limited transaction or security records that must be retained.

To remove locally stored paintings and progress, delete the app and its local data through iOS. Keychain data can persist after app deletion according to iOS behavior; contact support if you also want associated server records removed.

## Children's Privacy

PicNum is not directed at children and does not knowingly collect personal information from children. A parent or guardian who believes a child submitted information can contact us to request deletion.

## Changes to This Policy

We may update this policy when the app, service providers, or legal requirements change. We will update the date above and provide additional notice when required.

## Contact

For privacy questions or requests, visit [Support](support.html) or email [fun-tapper-6s@icloud.com](mailto:fun-tapper-6s@icloud.com?subject=PicNum%20Privacy%20Request).
