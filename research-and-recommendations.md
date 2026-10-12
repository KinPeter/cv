# CV Research & Recommendations

Working document for improving `original.md` — positioning the CV for AI-native software engineering roles. Based on research into 2026 AI-engineer and career-changer CV practices.

---

## Key research findings

1. **AI-native hiring screens for evidence of shipping, not tool lists.**
   CTOs hiring "AI-native engineers" look for: agent orchestration, MCP literacy, context engineering, output evaluation, and failure-mode debugging. Evaluation design ("how do you know it works?") is cited as the single biggest signal of real LLM experience.

2. **Every strong bullet = Verb + system + named stack + outcome with numbers.**
   "Numbers travel between hiring managers; adjectives don't." A strong bullet names a model/tool, a metric, and a magnitude.

3. **Two gates to clear:**
   - **ATS:** single-column layout, standard headers, exact keywords, spell out acronyms once ("Model Context Protocol (MCP)"), text-based PDF.
   - **Human:** currency of stack, seniority, results. Avoid "responsible for" language and generic soft-skill lists.

4. **Senior + career change:**
   - Last 8–10 years carry the weight; older roles get 1–2 lines each.
   - The pivot is mentioned once, framed as deliberate — never repeated in every bullet.
   - Delivered results replace "responsible for" language.
   - **No date of birth** — pure age signal, invites bias.

5. **Public artifacts are the strongest proof.**
   GitHub repos, deployed demos, and documented projects carry more weight than any certificate. An empty/fork-only GitHub is worse than no link.

6. **Flat skills lists read junior.**
   Group tools into functional categories and name one primary tool per category with a shipped context. A long list reads as breadth without depth.

---

## Current strengths of the CV

- The overall theme (frontend focus + AI-native direction) is clear and genuine.
- EPAM bullet mentions the exact things AI-native employers screen for (agentic tooling, multi-agent workflows, MCP).
- GitHub already contains real AI-native artifacts (MCP server, AI-powered code-review CLI) — currently undersold.
- Career-change story is present and honest.

---

## Concrete recommendations

### 1. Header

- Remove "Date of birth: 16 Sep 1985" (age signal, invites bias).
- Keep contact lines; consider adding LinkedIn: https://www.linkedin.com/in/peter-kin/.

### 2. Title line

- Sharpen: e.g. "Senior Frontend / Full-stack Engineer | AI-Native Development" with the AI-native term pointing at agents + MCP.

### 3. Profile

- Cut from 4 paragraphs to 3–5 lines.
- Must do three things: name the target role, quantify years + stack, and pre-empt the career change in one phrase.
- Optionally lead with a shipped AI-native artifact.
- Draft:
  > Senior software engineer with 7+ years building full-stack web applications (React, Angular, TypeScript) and 1+ year shipping AI-native tooling — multi-agent workflows, MCP servers, AI-assisted code review — in production. Career-switched from 10 years in tourism; now focused on AI-native engineering.

### 4. EPAM bullets (the crown jewel)

- Add the named stack: which agent harness (Claude Code? Copilot? custom skills/sub-agents?), what the assistants do end-to-end, and how output is validated/evaluated.
- Right now it reads "contributing to" with no outcome and no named tools.
- The evaluation/verification angle is what separates a demo from production experience — lean into it.

### 5. All experience bullets — add numbers

Currently zero numbers anywhere. Add scope/outcome per role:

- Team size led / mentored (count).
- User base or scale of platform (Genesys platform serves millions of users).
- Test coverage or defect-finding results.
- Release-cycle or delivery impact.
- Make each bullet outcome-first.

### 6. Skills — restructure by function

Replace flat lists + giant "familiar with" wall with functional groups:

- Languages
- Frontend
- Backend
- AI / LLM Tooling (agents, MCP, Claude Code, etc.)
- Testing / QA
- Infra / DevOps
  Keep it honest: list what you've actually shipped with.

### 7. New "Selected Projects / Open Source" section (highest leverage)

GitHub already has genuine AI-native proof. Describe each as what/stack/why:

- `pk-central-mcp` — MCP server exposing the PK-Central API (TypeScript). Direct proof of MCP fluency.
- `review-agents` — AI-powered CLI for local and PR code reviews (JavaScript). Direct proof of agentic tooling in SDK.
- `pk-central-v2` — FastAPI backend services for hobby projects (Python).
- `Pit-CLI` — CLI supporting Git/Docker/Jira workflows (TypeScript).
  This is the public-artifact evidence employers say they trust most.

### 8. Strengths & Goals

- Cut "Goals" entirely ("Perfect AI Native Engineering" reads naive).
- Fold 1–2 best strengths into the profile as evidence-backed claims, not a generic list.

### 9. Tourism history

- Keep (explains the pivot, adds intercultural + leadership signal).
- Compress each role to ~1 line, reframed as transferable.

### 10. ATS hygiene

- Single column (already true).
- Standard headers.
- Spell out acronyms once: "Model Context Protocol (MCP)", "End-to-end (E2E)".
- Export as text-based PDF.

### 11. Positioning notes

- Apply to AI-native roles → **lead with the AI bullets**.
- Apply to frontend roles → **keep frontend first**.
- Tailor each posting; the AI-native term belongs in the title line + summary + first bullet of the current role.

---

## Open questions to fill bullet points (need real data from you)

Below is what only you know. These become the numbers/outcomes that make the CV credible.

1. **EPAM AI toolkit:** What tools/harness do you actually use? (Claude Code, Copilot, custom skills/sub-agents, LangGraph, etc.) What exactly do the assistants do, and how do you verify their output? Any measurable impact (faster releases, time saved, fewer review rounds)?
2. **Genesys:** Scale of the platform (user numbers), your team size, number of interns/juniors mentored, any features you led end-to-end with an outcome.
3. **MOON42:** One or two project outcomes (launched feature, number of users, greenfield delivery).
4. **Numbers generally:** Any metric you can honestly attach — team size, test coverage %, platform users, mentoring count, delivery speed-ups.

---

## Proposed next steps

1. Fill in the open questions above (highest priority: EPAM AI detail + any real numbers).
2. Restructure into a revised CV (`revised.md`) using the structure below:
   - Header (no DOB)
   - Profile (3–5 lines, target-role framed)
   - Work Experience (outcome-first bullets with numbers, AI-lead)
   - Selected Projects / Open Source (GitHub proof)
   - Skills (functional groups)
   - Education
   - Previous experience (compressed, transferable framing)
   - Languages
3. Keep `original.md` untouched as reference.
