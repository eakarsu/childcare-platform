# Feature status — Childcare & daycare operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 83 pages |
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
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 0 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Child Profiles | records | 1 | 0 | Native records/view |
| Development Milestones | records | 2 | 0 | Native records/view |
| Activity Planning | records | 2 | 0 | Native records/view |
| Health Records | records | 1 | 0 | Native records/view |
| Sleep Tracking | records | 1 | 0 | Native records/view |
| Feeding & Nutrition | records | 1 | 0 | Native records/view |
| Growth Tracking | records | 1 | 0 | Native records/view |
| Vaccination Records | records | 1 | 0 | Native records/view |
| Behavioral Notes | records | 1 | 0 | Native records/view |
| Daily Journal | records | 1 | 0 | Native records/view |
| Medication Tracker | records | 1 | 0 | Native records/view |
| Appointments | records | 1 | 0 | Native records/view |
| Emergency Contacts | records | 2 | 0 | Native records/view |
| Learning Resources | records | 1 | 0 | Native records/view |
| Diaper Tracker | records | 1 | 0 | Native records/view |
| Expense Tracker | records | 1 | 0 | Native records/view |
| Caregiver Log | records | 1 | 0 | Native records/view |
| Daily Routines | records | 1 | 0 | Native records/view |
| Tooth Tracker | records | 1 | 0 | Native records/view |
| Memory Book | records | 1 | 0 | Native records/view |
| Chore Chart | records | 1 | 0 | Native records/view |
| Allergy Log | records | 1 | 0 | Native records/view |
| Playdates | records | 1 | 0 | Native records/view |
| Shopping List | records | 1 | 0 | Native records/view |
| AI Parenting Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Milestone Comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sleep Pattern Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nutrition Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Behavior Pattern Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Illness & Recovery Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parental Stress Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Screen Time Manager | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sibling Harmony Coach | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Health Trend Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Results | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Screen time balance | records | 1 | 0 | Native records/view |
| Licensing Compliance | records | 1 | 0 | Native records/view |
| Staff Ratios | records | 1 | 0 | Native records/view |
| Attendance | records | 1 | 0 | Native records/view |
| Health & Safety | records | 1 | 0 | Native records/view |
| Meal Planning | records | 1 | 0 | Native records/view |
| Allergy Action Plan | records | 1 | 0 | Native records/view |
| Enrollment | records | 1 | 0 | Native records/view |
| Classrooms | records | 1 | 0 | Native records/view |
| Immunizations | records | 1 | 0 | Native records/view |
| Waiting List | records | 1 | 0 | Native records/view |
| Supply Inventory | records | 1 | 0 | Native records/view |
| Daily Reports | records | 1 | 0 | Native records/view |
| AI Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staff Scheduling | records | 1 | 0 | Native records/view |
| AI Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: PredictiveChildDevelopme | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: ParentEngagementPredicti | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: StaffBurnoutPrediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: CurriculumPersonalizatio | records | 1 | 0 | Native records/view |
| CF: NutritionOptimization | records | 1 | 0 | Native records/view |
| Gap: NoneMajorStrongAiToRoute | records | 1 | 0 | Native records/view |
| Gap: InventoryLacksAiReorderP | records | 1 | 0 | Native records/view |
| Gap: AttendanceLacksAiNoShowP | records | 1 | 0 | Native records/view |
| Gap: NoPhotoVideoSharingWithP | records | 1 | 0 | Native records/view |
| Gap: LimitedMobileAppForParen | records | 1 | 0 | Native records/view |
| Gap: LimitedIntegrationWithHe | integration | 1 | 0 | Provider request records only |
| Gap: NoStateSpecificComplianc | records | 1 | 0 | Native records/view |
| Gap: NoWebhooks | integration | 1 | 0 | Provider request records only |
| Allergy conflict check | records | 1 | 0 | Native records/view |
| Emergency drill recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sibling classroom coord | records | 1 | 0 | Native records/view |
| Tuition subsidy calc | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 83 feature pages were visited in the browser; 81 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 20 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

20 original AI entries are now grouped into **3 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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
