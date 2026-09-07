# Feature status — Cybersecurity & digital trust

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 248 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Triage | records | 1 | 0 | Native records/view |
| Enrich cve | records | 1 | 0 | Native records/view |
| Alerts | records | 2 | 0 | Native records/view |
| Incidents | records | 5 | 0 | Native records/view |
| Assets | records | 1 | 0 | Native records/view |
| Playbooks | records | 1 | 0 | Native records/view |
| Iocs | records | 1 | 0 | Native records/view |
| Threat intel feed | records | 1 | 0 | Native records/view |
| Shift roster | records | 1 | 0 | Native records/view |
| Vulnerabilities | records | 1 | 0 | Native records/view |
| Exceptions | records | 1 | 0 | Native records/view |
| Change requests | records | 1 | 0 | Native records/view |
| Vendor risk | records | 1 | 0 | Native records/view |
| Certificates | records | 1 | 0 | Native records/view |
| Runbooks | records | 1 | 0 | Native records/view |
| Evidence library | records | 1 | 0 | Native records/view |
| Allowlists | records | 1 | 0 | Native records/view |
| Blocklists | records | 1 | 0 | Native records/view |
| Triage alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Build hunt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrich ioc | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Executive brief | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Draft playbook | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shift handover | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Red team | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Phishing classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy diff | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mitre mapper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compromise assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remediation estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Log anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Identity risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain scan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Breach narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| False positive reducer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Playbook recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post incident report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Log query copilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tabletop exercise | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| On call | records | 1 | 0 | Native records/view |
| Production gaps | records | 2 | 0 | Native records/view |
| Production controls | records | 2 | 0 | Native records/view |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Users | records | 1 | 0 | Native records/view |
| Stats | records | 1 | 0 | Native records/view |
| Bookmarks | records | 1 | 0 | Native records/view |
| Real time media authentication | records | 1 | 0 | Native records/view |
| Social media monitoring | records | 1 | 0 | Native records/view |
| Media provenance tracking | records | 1 | 0 | Native records/view |
| Explainability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing detect deepfake analyze media detect face swapping d | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No media processing pipeline wired upload stubs only | records | 1 | 0 | Native records/view |
| No detection results database schema | records | 1 | 0 | Native records/view |
| Limited analytics endpoint coverage beyond plumbing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited social platform integration for automated detection | integration | 1 | 0 | Provider request records only |
| No calendar integration | integration | 1 | 0 | Provider request records only |
| Claims Monitor | records | 1 | 0 | Native records/view |
| Fact Checks | records | 1 | 0 | Native records/view |
| Sources | records | 1 | 0 | Native records/view |
| Categories | records | 1 | 0 | Native records/view |
| Trending Topics | records | 1 | 0 | Native records/view |
| Narrative Clusters | records | 1 | 0 | Native records/view |
| Claim Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source Checker | records | 1 | 0 | Native records/view |
| Pattern Detector | records | 1 | 0 | Native records/view |
| Summary Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto-Categorize | records | 1 | 0 | Native records/view |
| Trend Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source Tracing | records | 1 | 0 | Native records/view |
| Personalized Debunk | records | 1 | 0 | Native records/view |
| Real-Time Monitor | records | 1 | 0 | Native records/view |
| Team | records | 1 | 0 | Native records/view |
| Viral misinformation early warning | records | 1 | 0 | Native records/view |
| Misinformation source tracing | records | 1 | 0 | Native records/view |
| Predictive claim verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debunking personalization | records | 1 | 0 | Native records/view |
| Fact check seo optimization | records | 1 | 0 | Native records/view |
| Trending categories lack ai endpoints for trend prediction a | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sources lacks ai credibility scoring endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited social platform integration no twitter facebook tikt | integration | 1 | 0 | Provider request records only |
| No real time spread monitoring engine | records | 1 | 0 | Native records/view |
| Limited fact check network integration snopes factcheck | integration | 1 | 0 | Provider request records only |
| No verdict explainability surface | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No notifications system | records | 1 | 0 | Native records/view |
| AI Identity Verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Credential Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Compliance Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI DID Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Trust Score Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Credential Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Schema Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Privacy Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Anomaly Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Dashboard Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Compliance Report Export | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Batch Credential Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Identity Risk Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Revocation Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Credential Chain Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Issuer Workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verifier Workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Selective Disclosure (simulated) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Blockchain Anchor (simulated) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Status-List Check (simulated) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver Monitoring | records | 1 | 0 | Native records/view |
| Fleet Management | records | 1 | 0 | Native records/view |
| GPS Tracking | records | 2 | 0 | Native records/view |
| Emergency Response | records | 3 | 0 | Native records/view |
| Threat Assessment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Behavior Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fatigue Detection | records | 1 | 0 | Native records/view |
| Speed Monitoring | records | 1 | 0 | Native records/view |
| Route Safety | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Passenger Safety | records | 1 | 0 | Native records/view |
| Maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Weather Alerts | records | 2 | 0 | Native records/view |
| Compliance | records | 4 | 0 | Native records/view |
| Passenger Safety Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Road Hazard Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distraction Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Premium Adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver coaching escalation | records | 1 | 0 | Native records/view |
| OT Assets | records | 1 | 0 | Native records/view |
| PLCs | records | 1 | 0 | Native records/view |
| HMIs | records | 1 | 0 | Native records/view |
| SCADA Servers | records | 1 | 0 | Native records/view |
| Safety Systems | records | 1 | 0 | Native records/view |
| Control Loops | records | 1 | 0 | Native records/view |
| ICS Alerts | records | 1 | 0 | Native records/view |
| ICS Incidents | records | 1 | 0 | Native records/view |
| ICS Runbooks | records | 1 | 0 | Native records/view |
| ICS IOCs | records | 1 | 0 | Native records/view |
| Operator Actions | records | 1 | 0 | Native records/view |
| Network Zones | records | 1 | 0 | Native records/view |
| Protocol Anomalies | records | 1 | 0 | Native records/view |
| Network Baselines | records | 1 | 0 | Native records/view |
| Firmware Versions | records | 1 | 0 | Native records/view |
| Vendor Patches | records | 1 | 0 | Native records/view |
| Change Windows | records | 1 | 0 | Native records/view |
| AI · Triage ICS Alert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Baseline Protocol | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Classify Incident | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Suggest Isolation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Draft Change Procedure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Patch Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Control Loop Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Safety Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Hunt Attack Path | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Asset Criticality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Network Segmentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Malicious Firmware Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Operator Action Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · MITRE ATT&CK ICS Mapper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Supply-Chain Firmware | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parse protocol payload | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify asset | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lateral movement narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prioritize vulns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network conduits | records | 1 | 0 | Native records/view |
| Change window approvals | records | 1 | 0 | Native records/view |
| Sis audit | records | 1 | 0 | Native records/view |
| Vendor advisories | records | 1 | 0 | Native records/view |
| Workers | records | 1 | 0 | Native records/view |
| Check-ins | records | 1 | 0 | Native records/view |
| Check-In Dashboard | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |
| Heartbeat Map | records | 1 | 0 | Native records/view |
| Geofences | records | 1 | 0 | Native records/view |
| Agentic safety orchestration | records | 1 | 0 | Native records/view |
| Computer vision incident detection | records | 1 | 0 | Native records/view |
| Behavioral risk profiling | records | 1 | 0 | Native records/view |
| Environmental hazard sensing | records | 1 | 0 | Native records/view |
| Peer safety networks | records | 1 | 0 | Native records/view |
| Equipment without `/equipment | records | 1 | 0 | Native records/view |
| Compliance without `/audit | records | 1 | 0 | Native records/view |
| Shifts without `/burnout | records | 1 | 0 | Native records/view |
| No wearable device integration (smartwatch, beacon) | integration | 1 | 0 | Provider request records only |
| No integration with emergency services (911 auto | integration | 1 | 0 | Provider request records only |
| No real | records | 1 | 0 | Native records/view |
| Limited multi | records | 1 | 0 | Native records/view |
| No notifications module dedicated route (relies on SOS/emergency only) | records | 1 | 0 | Native records/view |
| No webhooks for external dispatch systems | integration | 1 | 0 | Provider request records only |
| No native mobile app despite field | records | 1 | 0 | Native records/view |
| Hazards | records | 1 | 0 | Native records/view |
| Shifts | records | 1 | 0 | Native records/view |
| Training | records | 1 | 0 | Native records/view |
| Equipment | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detection | records | 1 | 0 | Native records/view |
| Compliance Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shift Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazard Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety Report | records | 1 | 0 | Native records/view |
| AI History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assess Tool | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Display | records | 1 | 0 | Native records/view |
| Safety Briefing | records | 1 | 0 | Native records/view |
| Incident Report Builder | records | 1 | 0 | Native records/view |
| Predictive Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Failure Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Readiness Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Burnout Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Operations | records | 1 | 0 | Native records/view |
| Countermeasures | records | 1 | 0 | Native records/view |
| Deployments | records | 1 | 0 | Native records/view |
| Sensors | records | 1 | 0 | Native records/view |
| Defense Zones | records | 1 | 0 | Native records/view |
| Threat signatures | records | 1 | 0 | Native records/view |
| Fusion tracks | records | 1 | 0 | Native records/view |
| Engagements | records | 1 | 0 | Native records/view |
| Effector magazines | records | 1 | 0 | Native records/view |
| Roe | records | 1 | 0 | Native records/view |
| High capacity interceptors | records | 1 | 0 | Native records/view |
| Non kinetic effectors | records | 1 | 0 | Native records/view |
| Autonomy attack vectors | records | 1 | 0 | Native records/view |
| Cost advantage | records | 1 | 0 | Native records/view |
| Extras | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export | records | 1 | 0 | Native records/view |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Threat intel | records | 1 | 0 | Native records/view |
| Siem | records | 1 | 0 | Native records/view |
| Hunting | records | 1 | 0 | Native records/view |
| Mitre | records | 1 | 0 | Native records/view |
| Kill chain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detection rules | records | 1 | 0 | Native records/view |
| Soc analyst | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Threat intel feeds | records | 1 | 0 | Native records/view |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 248 feature pages were visited in the browser; 246 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 101 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

101 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
