# Slughook

**The fastest way to inspect, debug, and replay webhooks — in real time.**

Slughook is a high-performance webhook gateway built for developers who need full visibility and control over event-driven systems — without losing a single request.

---

## Overview

Webhook debugging shouldn’t feel like guesswork.

Missing logs. Incomplete payloads. Non-reproducible failures.

Slughook eliminates all of that by acting as a reliable gateway between your webhook providers and your backend — capturing every event, streaming it live, and enabling instant replay on demand.

```
Stripe / GitHub / Slack / Shopify
           │
           ▼
     ┌─────────────┐
     │  Slughook   │  ← Observe · Debug · Replay
     └─────────────┘
           │
           ▼
      Your Backend
```

---

## Key Features

### **Complete Observability**

Inspect headers, payloads, and responses in a single unified interface — no more fragmented logs.

### **One-Click Replay**

Replay any event instantly. Modify payloads, simulate edge cases, and debug failures without waiting.

### **Live Event Streaming**

Watch webhook traffic in real time with zero refresh. Stay in sync with your system as events happen.

### **Guaranteed Delivery**

Queue-based architecture ensures durability and zero data loss, even under heavy load.

### **Built-in Signature Verification**

Automatically validate incoming webhook signatures from supported providers.

### **Metrics & Alerting**

Monitor delivery performance and get notified when failures occur — before they impact users.

---

## Use Cases

* Debug integrations with Stripe, GitHub, Slack, Shopify, and more
* Replay failed events without relying on provider retries
* Monitor production webhook traffic in real time
* Validate payloads and test edge cases safely
* Reduce downtime by detecting and fixing issues early

---

## Quick Start

Get up and running in seconds:

```bash
slughook create endpoint
```

Stream events live:

```bash
slughook tail
```

Replay any event:

```bash
slughook replay <event_id>
```

---

## Platform

Slughook is a fully managed platform designed for scale, reliability, and developer productivity:

* High-availability event ingestion and processing
* Secure, scalable webhook delivery
* Built-in observability and replay tooling
* Designed for individuals, startups, and teams

---

## Resources

* 🌐 Website — [https://slughook.com](https://slughook.com)
* 📚 Documentation — [https://docs.slughook.com](https://docs.slughook.com)
* 📊 Status — [https://status.slughook.com](https://status.slughook.com)
* 💬 Support — [support@slughook.com](mailto:support@slughook.com)

---

## Notes

Slughook is a proprietary platform.
This repository contains supporting tools, SDKs, and public resources.

---

<sub>Built for developers who ship fast — and debug faster.</sub>
