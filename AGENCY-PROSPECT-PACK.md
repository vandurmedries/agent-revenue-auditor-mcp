# Agency Prospect Audit Pack

Turn a list of up to 20 company websites into a ranked sales-research queue.

## What the buyer gets

For every successfully analyzed public website:

- a 0–100 opportunity score and grade;
- visible conversion, metadata, analytics, mobile-readiness, CTA, contactability, and trust-signal gaps;
- evidence for every flagged issue;
- a recommended next sales action;
- structured JSON exportable as CSV or Excel through Apify.

The pack does not scrape private profiles, send outreach, or claim unverifiable revenue losses.

## Price

Use the `leadQualification` mode at **$0.08 per successfully analyzed domain**.

- 5-site pilot: up to **$0.40**
- 10-site batch: up to **$0.80**
- 20-site pack: up to **$1.60**

Invalid URLs and failed fetches are not charged as successful website events. Use Apify's maximum-charge control as a run guardrail.

## Buy and run

[Open Website Lead Qualification Auditor on Apify](https://apify.com/wintry_nutmeg/agent-revenue-auditor)

Paste this input and replace the example domains:

```json
{
  "analysisMode": "leadQualification",
  "urls": [
    "https://example.com",
    "https://example.org"
  ],
  "maxUrls": 20
}
```

Start with five domains. Review the evidence and ranking before scaling the batch.

## Best fit

- web-design and conversion agencies qualifying outbound accounts;
- B2B lead-generation teams prioritizing manual research;
- consultants screening a prospect list before personalized outreach;
- sales operations teams that need predictable JSON for review queues.

## Support

Questions or a reproducible issue: `capi2@agentmail.to`
