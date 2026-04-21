# Slughook

**See, debug, and replay webhooks instantly.**

Slughook is a high-performance webhook gateway that lets you capture, inspect, and replay events in real time — without losing a single request.

---

## What is Slughook?

Debugging webhooks is painful.

You don’t know what was sent. Logs are incomplete. And reproducing failures means waiting for events to happen again.

Slughook solves this by acting as a gateway between your webhook providers and your backend — capturing every event, streaming it live, and letting you replay it anytime.

```
Stripe / GitHub / Slack / Shopify
           │
           ▼
     ┌─────────────┐
     │  Slughook   │  ← capture · inspect · replay
     └─────────────┘
           │
           ▼
      Your Backend
```

---

## Core Capabilities

* **Full visibility** — Inspect headers, payloads, and responses in one place
* **Instant replay** — Replay any webhook with one click (edit payloads, test edge cases)
* **Real-time stream** — Watch events arrive live, no refresh needed
* **Reliable delivery** — Queue-based architecture ensures zero data loss
* **Signature verification** — Validate webhook signatures out of the box
* **Metrics & alerts** — Track delivery rates and get notified when things break

---

## Use Cases

* Debug webhooks from Stripe, GitHub, Slack, Shopify, and more
* Replay failed events without waiting for retries
* Monitor production webhook traffic in real time
* Validate payloads and safely test edge cases
* Reduce downtime by catching failures early

---

## Getting Started

Create your first endpoint in seconds:

```bash
slughook create endpoint
```

Stream incoming events:

```bash
slughook tail
```

Replay any failed event:

```bash
slughook replay <event_id>
```

---

## Platform

Slughook is a fully managed, hosted service designed for reliability and scale:

* High-availability event processing
* Secure webhook ingestion and delivery
* Built-in observability and replay tooling
* Designed for both solo developers and teams

---

## Links

* 🌐 Website — https://slughook.com
* 📚 Documentation — https://docs.slughook.com
* 📊 Status — https://status.slughook.com
* 💬 Support — [support@slughook.com](mailto:support@slughook.com)

---

## Notes

Slughook is a proprietary platform.
This organization hosts supporting tools, SDKs, and public resources related to the product.

---

<sub>Built for developers who move fast.</sub>
