# Worked comparison and transfer cases

## Portfolio: a recruiter needs the strongest campaign

Context: the current interface requires a 3D camera interaction to reach projects. The owner likes editorial layouts and dislikes decorative SaaS-style cards. Those preferences apply to this example only.

Task: find the strongest campaign case study and identify the designer's contribution. No participant observations are available yet.

| Direction | Hypothesis and task path | Main risk and trade-off |
|---|---|---|
| Editorial project index | Recognizable titles and short role descriptions let visitors choose directly: home → indexed project → case study. | Text must carry enough meaning. Low implementation cost; allow visible links on touch and keyboard rather than hover-only previews. |
| Featured campaign story | A visible lead project reduces choice: home → featured summary → full case study. | Visitors may miss breadth. Medium cost; keep other projects discoverable and shorten the opening on mobile. |
| Optional spatial exploration | Direct navigation plus optional camera exploration preserves identity: home → project index or spatial scene → same case study. | Two routes increase maintenance. Highest cost; direct links must work before 3D loads and with reduced motion. |

If choosing on the owner's behalf is authorized, provisionally choose the featured campaign story because it directly supports the primary task. Preserve the other wireframes. If the camera is already an explicit requirement, choose the hybrid and keep direct routes; do not silently remove it.

Next, compare two visual treatments of that structure: an oversized typographic cover and an image-led editorial cover. Both retain the same content and route so the comparison tests visual hierarchy rather than a second navigation concept.

Prototype the project link, case study, mobile layout, keyboard focus, and return path. A proposed task is “Find the campaign you would discuss in an interview and tell me what the designer contributed.” Record first action, detours, completion, and comprehension. Results remain pending until observed.

If visitors cannot find the project, revisit hierarchy or navigation. If they reach it but cannot describe the contribution, revisit content. Animation polish will not resolve either issue.

## Transfer beyond portfolios

**Analytics dashboard:** Start with “Where did conversion fall?” Compare stage-first, segment-first, and investigation-first structures. Show definitions and source lineage. Label causes as hypotheses until investigated; a change correlated with a campaign is not proof of impact.

**Ordinary settings screen:** For notification frequency, compare direct controls with a guided decision only if that choice is genuinely uncertain. Test whether someone can change a preference and understand the saved state. Do not impose cinematic motion or a full visual redesign on a small task.

**Motion explanation:** Apply [motion.md](motion.md) to an export feature. Test comprehension of the exported content and destination. The technique should work without impressive source material or invented performance statistics.
