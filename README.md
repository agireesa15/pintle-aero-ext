# Pintle Aero

**AI-Powered Requirements Traceability & Verification Copilot for Aerospace Engineering**

Pintle Aero is an engineering review assistant that ingests requirements documents, test procedures, and test reports — then automatically extracts structured data, suggests traceability links, detects verification gaps and cross-document inconsistencies, and produces review-ready exports.

It answers the four questions every systems engineer needs answered before a design review:

1. **What requirements are not verified?**
2. **What evidence supports each requirement?**
3. **Where do documents disagree?**
4. **Can I export something useful for a design review today?**

---

## How It Works

- **Hybrid Extraction Pipeline** — Pattern detection + LLM structured extraction + schema validation with unit normalization. Every extracted field traces to a specific page and passage in the source document.
- **Multi-Signal Link Suggestion** — Fuses explicit ID matching, keyword overlap, semantic similarity, and document category relevance into a composite confidence score with explainable recommendations.
- **Deterministic Rules Engine** — Threshold mismatches, unit conflicts, and pass/fail contradictions are caught by rules operating on structured data with zero LLM dependency.

---

## Key Results

| Metric | Value |
|--------|:-----:|
| Trace link precision (ID match) | 94.7% |
| Top-1 link precision (all types) | 80.6% |
| Planted issue detection rate | 92.9% |
| Analysis time (vs. 4-8 hrs manual) | < 15 min |
| LLM cost per workspace | < $1.00 |

---

## Tech Stack

Python · FastAPI · React · Next.js · TypeScript · Tailwind CSS · Claude API · Sentence Transformers · SQLite · Docker

---

## About

Built by **Anjana Gireesan**, Junior in Aerospace Engineering at Purdue University. Born from firsthand experience with incomplete traceability during NASA Student Launch design reviews.

> *"A pintle is the precision injector inside a rocket engine — the small part the entire system depends on. Requirements traceability is the pintle of aerospace verification. This tool makes sure none of those connections are missing."*

---

## Contact

The source code is maintained in a private repository. For access, a live demo, or to discuss the project:

📧 **Email:** gireesananjana@gmail.com

🔗 **LinkedIn:** [linkedin.com/in/anjanagireesan](https://linkedin.com/in/anjanagireesan)
