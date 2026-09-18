# Refined research prompt

I am an ML engineer at a small tech company in India. I want to build credible hiring evidence through useful, merged open-source contributions, with the longer-term aim of joining an AI lab such as Anthropic or OpenAI. I am strongest in Python, Go and TypeScript, with some Rust and C++.

My GitHub is https://github.com/rohan-patnaik. Review my actual public external PR history, refresh the counts rather than assuming my earlier estimate is current, and read the discussions/reviews on closed PRs. Separate rejection, supersession, inactivity, credited replacement landings and unknown reasons.

## 1. Company and repository scope

Include only popular or semi-popular AI labs/companies, recognized specialist ML organizations, and established ecosystem projects. Include established projects such as PyTorch, vLLM, SGLang, MCP, OpenHands, Goose, Aider, Cline and SWE-agent alongside companies. Explain the editorial shortlist and distinguish company ownership, foundations, community projects and research adjacency.

Screen OpenAI, Anthropic, MCP, Google DeepMind/Gemini, xAI, Cognition/Devin, Cursor/Anysphere, Together AI, Prime Intellect, Meta/FAIR/PyTorch, Microsoft, Mistral, Hugging Face, Cohere, Ai2, EleutherAI, DeepSeek, Qwen, Unsloth, Sakana AI, Perplexity, Nous Research, NVIDIA, vLLM, SGLang and the established coding-agent projects. Treat less-recognized groups from the earlier broader request as optional; explain exclusions. Assess Continue's current maintenance before recommending it.

For each company/project, recommend three implementation repositories where defensible. Exclude cookbooks, tutorial/example or notebook collections, prompt/skill catalogs and documentation-only repositories. A reported documentation/test defect inside a real software repository can qualify. Small repositories owned by an established company can qualify; their own star counts need not be large.

Do not misrepresent an issue tracker or closed-source product wrapper as an editable codebase. If only one or two suitable repositories exist, report the missing slot. Separate viable contribution candidates from discovery-only or avoid rows; three screened repos are not automatically three recommendations.

## 2. Contribution intake and measured review behavior

Read each repo's current CONTRIBUTING guide, PR template and CI workflows. Link pinned policy sources and state:

- Whether external code PRs are accepted, restricted or refused.
- CLA/DCO/sign-off requirements, issue-first rules, assignment/approval/readiness gates, testing expectations and relevant AI-assistance policies.
- Generated or mirrored boundaries, including Stainless, Fern, Speakeasy, Castiron and Copybara; identify the editable source/generator route.
- Maintenance status and unavailable/internal CI or hardware requirements.

Identify explicit no-external-code cases, including the current policy of openai/codex; do not infer acceptance from historical merges alone.

For up to the latest 100 merged PRs per repo, sort by actual merge time, exclude bots, and classify likely external versus affiliated authors. Correct hidden membership using public profile/maintainer evidence where possible. Report cohort size/date range, external count/share, median external time-to-merge, open PR count and age/URLs of the oldest observed external open PRs. Flag incomplete samples and affiliation uncertainty. External share among merged PRs is not an outsider acceptance probability.

Use a per-company repo table with repo URL, stars, language, external share, median latency, open queue, CLA/policy and why the codebase fits my skills.

## 3. Six issue options per company—not per repository

Across each company's three repos, provide **six total choices: two LOW, two MEDIUM and two HIGH**. They need not be evenly distributed across the repos. I will choose which ones to pursue.

Every proposed PR must resolve a real reported bug, regression, broken workflow, compatibility/correctness problem or demonstrated performance defect. Do not propose random cleanup, arbitrary test coverage, unsolicited refactors or speculative features for contribution credit.

Use one comparison table per company with separate columns for:

1. LOW / MEDIUM / HIGH.
2. Repository link.
3. Issue title and URL.
4. Plain-English explanation of the failure and affected user/workflow.
5. The smallest plausible fix boundary.
6. Approximate PR LOC range: estimated additions plus deletions, including tests and necessary docs, excluding generated files, lockfiles and vendored churn.
7. Reproduction, ownership, hardware and maintainer-approval gates still outstanding.

LOC is an estimate, not a measured diff or an importance score. LOW generally means a small reported contract/test/one-line fix; MEDIUM a bounded logic/compatibility fix; HIGH deeper correctness, lifecycle, performance or substantial issue-backed implementation. Do not inflate scope to fill a HIGH slot.

Check that issues are open and unassigned and inspect full linked-PR timelines, comments, explicit intent-to-work, competing PRs, closed duplicates and already-landed fixes. An unassigned issue whose reporter already has a patch ready is not free work. Distinguish reported symptoms, source confirmation, local reproduction and accepted scope.

If fewer than two defensible issues exist in a bucket, leave the missing slots explicit and explain the bounded search. Do not fabricate bugs or describe conditional leads as ready-to-open PRs.

For otherwise suitable repos with sparse queues, search GitHub Discussions, Reddit, X and relevant forums for concrete complaints. Save the original URL/date/version/logs, check duplicates and try to reproduce on a supported release/current source. Trace ownership to the correct repo. Plausibility alone is not confirmation. An unreproduced report is only a possible explicitly unconfirmed issue when concrete evidence and project rules support it; otherwise seek more information or use a discussion. Do not file issues merely to manufacture contribution opportunities.

## 4. Select a focused six-PR portfolio

Separately from the per-company choice menus, propose six primary objectives overall: two LOW, two MEDIUM and two HIGH. Give each a fallback issue in the same repo, its explanation, estimated scope/LOC and gates. Explain the choices using maintainer demand, my skills, validation feasibility, review evidence and hiring relevance. Flag fallbacks that change the difficulty mix or have unresolved ownership; do not call them guaranteed substitutes.

## 5. Merge strategy and practical schedule

Write a merge-probability guide grounded in the actual reasons my closed PRs did not merge and the repo policies you read. Cover scope agreement, generated source ownership, reproducible tests, real native/GPU/runtime validation, small diffs, duplicate work, review follow-up, stale rules and honest credit for replacement landings.

Provide a week-by-week order of attack for the six objectives, including CLA/DCO setup, when to comment with evidence, approval gates, implementation, opening PRs, responding to reviews and productive independent work while waiting. State the assumed weekly time/hardware budget. A schedule cannot guarantee maintainer merge dates.

## 6. Deliver and publish

Write the complete result as Markdown first. Then create a self-contained HTML page with light/dark themes, restrained visual styling, readable layout, collapsible company sections, LOW/MEDIUM/HIGH badges, summary stat tiles, a simple external-share bar chart, and clickable links for every repo, issue and PR mentioned. Make the comparisons readable on phone, laptop and desktop, and actually open the page in a browser to verify them.

Publish the HTML at a free public URL, for example GitHub Pages from my account, and verify the live URL in a browser. Provide the live page, downloadable Markdown, standalone HTML, this refined prompt, and reproducible public evidence/command results.

Every factual claim must have a source URL or saved command result. Label editorial judgments, estimates, unresolved facts and incomplete research. Date the snapshots. Issue availability changes within hours: explicitly require a fresh check before claiming or coding.

This authorizes research, local artifact creation and publication of the guide. Do not post upstream issue comments, issues or PRs, sign agreements, or contact maintainers on my behalf.
