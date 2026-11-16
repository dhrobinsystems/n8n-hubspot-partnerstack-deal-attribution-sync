# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-hubspot-partnerstack-deal-attribution-sync`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-hubspot-partnerstack-deal-attribution-sync`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, partner credit assigned to the wrong partner or not at all, incorrect commission estimates, overpaid or underpaid partners, partner or channel disputes, incorrect revenue reporting, API charges, and any record created or changed in a connected system.

* **No Warranty:** All software, n8n JSON blueprints and JavaScript modules are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. The matching rules, program and commission rates, amount units, stage names and redaction patterns are illustrative defaults and are not guaranteed to match your partner agreements or data.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, PartnerStack test keys and a test Slack channel, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot, PartnerStack or Slack credentials. Treat every commission figure as an estimate that a person must reconcile against PartnerStack before anyone is paid.

* **Not a Payout System:** This workflow doesn't calculate, approve or pay partner rewards. PartnerStack, your contracts and your finance team remain the source of truth for every payout. Never pay a partner from the estimates this workflow writes to HubSpot.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and others), partner program agreements, tax and financial reporting rules, and security policies of PartnerStack, HubSpot, Slack and any connected services. That includes telling partners and customers how their data is shared between systems, confirming a lawful basis for that sharing, keeping personal data out of logs and alerts, restricting access to n8n executions and alert channels, and reviewing every automatically updated record.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by PartnerStack Inc., HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All partner, customer and contact names, domains (under the reserved `.example` suffix), e-mail addresses, partner, customer, deal and transaction keys, record IDs, amounts, commission rates and secrets in the pinned sample data and documentation are fictional and exist only for testing. Any resemblance to real people or organisations is coincidental. Placeholder values such as `YOUR_PARTNERSTACK_WEBHOOK_SECRET`, `YOUR_PARTNERSTACK_PUBLIC_KEY`, `YOUR_PARTNERSTACK_API_KEY`, `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_HUBSPOT_PORTAL_ID`, `YOUR_PARTNER_ASSOCIATION_LABEL_ID` and `YOUR_SLACK_WEBHOOK_URL` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, tax, accounting, privacy or compliance advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
