# ShopLite – AI First Mindset Assignment (Week 2)

This folder contains all deliverables for the Week 2 AI First Mindset assignment for ShopLite.  
The goal was to pick **two near-term AI touchpoints** that move the needle, define latency and cost targets, and document feasibility.

---

## File Overview

### 1. `ai-capability-map.md`
- Contains a table of **4 candidate AI capabilities**.  
- Marks **2 selected capabilities**:  
  1. Smart Search Typeahead  
  2. Support Assistant  
- Includes a short rationale for why these were chosen (KPIs, feasibility, integration risk).

### 2. `touchpoints.md`
- Detailed specs for the **2 selected touchpoints**.  
- Sections include:  
  - Problem statement  
  - Happy path (6–10 steps)  
  - Grounding & guardrails  
  - Human-in-the-loop details  
  - Latency budgets and cache strategy  
  - Error & fallback behavior  
  - PII handling  
  - Success metrics  
  - Feasibility note  

### 3. `cost-model.md`
- Simple cost calculation for each selected touchpoint.  
- Uses concrete model/pricing assumptions (GPT-4o-mini) and cache rates.  
- Shows **cost per action** and **daily cost**, with levers to optimize if over budget.

### 4. `rfc.md`
- Minimal RFC including **AI Touchpoints section** linking to `ai-capability-map.md`.  
- Captures context, goals, and problem statement for ShopLite.

### 5. (Optional) `probe/`
- Folder for prototype screenshots or logs.  
- Can be referenced in `touchpoints.md` feasibility notes.

---

## Submission
- All files are located under `docs/ai-first/`.  
- The RFC is under `docs/rfc.md` with a direct link to the capability map.  
- This structure meets all Week 2 deliverables and requirements.
