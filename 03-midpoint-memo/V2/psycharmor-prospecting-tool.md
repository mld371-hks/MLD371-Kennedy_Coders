# PsychArmor Prospecting Tool

Kennedy Coders, HKS MLD-371. Updated 23 October 2026.

## Direction
PsychArmor (Ramon Salazar, 19 Oct) said hiring volume was too low for the screening tool and offered three options: contract management, grant qualification, and partner and donor prospecting. The team chose **Option 3: partner and donor prospecting.** The hiring tool is retired.

## The file
- One copy only: `Desktop/PsychArmor/PsychArmor-Prospecting.html`. It is edited in place and opens by double-click in Chrome or Edge.
- No versioned copies, chat copies or claude.ai pages.
- When it's ready, this same file goes on GitHub Pages for a public web address.

## Layout
- **Top bar on every screen:** Home (far left), Back (one step), and a three-way switch: Partners (blue) | Group donors (teal) | Individual donors (purple).
- **Options banner in each section:** Prospect Map, New Prospect, Outreach Review (with a count of waiting drafts), Alignment Criteria, Approved Facts, Records, Settings.
- The map is the default page in each section. There are no bottom bars.

## Sections
| Section | Who | Fit criteria (X axis) |
|---|---|---|
| Partners | Organizations that buy or co-deliver training: health systems, employers, agencies | Veteran connection, staff training need, mental health, setting, reach, budget or buying path |
| Group donors | Foundations, corporate giving, community foundations, giving circles | Veteran focus, mental health, caregivers, education, geography, gift size, open to applicants |
| Individual donors | People who give personally | Military connection, engagement with PsychArmor, giving history, program interest, asked to help |

## Prospect Map
- **X:** mission alignment, from the section's criteria weighted 1 to 3 (Met = 1, Partial = 0.5, Missing = 0).
- **Y:** readiness. Warm intro 30, named contact 15, open to applicants / buying path / asked to help 25, existing relationship 20, documented source 10.
- **Background heat map:** quadrants labelled Pursue now, Check fit, Build the relationship and Low priority.
- **Dot size:** proportional to staff's estimate of annual value. Clicking a dot opens the full prospect page.
- **Ranked list:** a column of tiles below the map, highest priority first. Clicking a tile shows full details in the right-hand panel, which is blank until a tile is clicked. Clicking the tile again clears it.

## Agent search
- The button on each map ("Agent: find new partners / group donors") suggests new organizations, skipping anyone already listed.
- Staff tick which ones to add. Nothing is added automatically.
- Re-check all re-scores every prospect in the section.
- Real web search needs an OpenAI key in Settings. Without one it returns fictional sample results.
- **It is off for individual donors.** Searching the web to profile private people is a privacy and trust risk. Individuals are added by hand.
- The live web search has not been tested with a real key.

## Outreach Review
1. On a prospect page: generate a draft, edit it, then click **Save to Outreach Review**.
2. On the review page, each draft has four buttons:
   - **Approve:** the prospect becomes Approved for outreach.
   - **Send back for corrections:** a note is required. It shows on the prospect page, and the draft can be resubmitted.
   - **Reject:** a reason is required. The prospect goes on hold.
   - **Delete:** two clicks. The draft is removed and the prospect is kept.
3. Each draft shows its history. Every action is logged in Records. Approving does not send email; staff send from their own email.

## Guardrails
- AI suggests; staff decide every check, draft and approval.
- Drafts only use Approved Facts. Numbers not found in the facts or the research are flagged, and [placeholders] are flagged.
- Each criterion rating shows the quote it is based on, and staff can override any rating.
- Prospects who already work with PsychArmor are flagged.
- Individual donors: only public information or information they shared. No wealth screening.
- All sample prospects are fictional.

## Known limits
- Data is saved in each browser only, so the review area is not shared between people yet. A team queue needs shared storage, to be decided before or at GitHub publishing.
- OpenAI mode and agent web search are untested with a real key.
- Criteria, readiness points and value estimates are our assumptions. Confirm them with PsychArmor.

## Open items
- Decide how to share data across the team.
- Reply to Ramon confirming Option 3.
- Confirm criteria and users with PsychArmor.
- Methods note and AI adoption policy.
