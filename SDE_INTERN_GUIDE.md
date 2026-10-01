# SDE Intern Playbook — Prosperr.io & Fintech Engineering

Congratulations on joining **Prosperr.io** as an SDE Intern! As a FinTech & Tax-tech platform handling sensitive financial data, software engineering requires high precision, clean code practices, and strong communication.

Here is your essential engineering guide to excel in your internship:

---

## 1. Technical & Engineering Excellence 🛠️

- **Precise Financial Math**:
  - Never use standard floating-point numbers (`float` / `double`) for money calculations to avoid precision errors.
  - Use fixed-point representation, integer cents/paisa, or specialized decimal libraries (e.g., `Decimal.js`, `bignumber.js`, `BigDecimal`).
- **Data Privacy & Security**:
  - Never log Sensitive Personal Data (PII, PAN, Aadhaar, salary data, banking details, auth tokens).
  - Mask sensitive data in logs and strictly adhere to environment variable hygiene (never commit `.env` files).
- **Self-Review Your PRs**:
  - Before requesting a code review, read your own diff line-by-line on GitHub.
  - Ensure all lints, tests, and formatting pass. A clean PR gets reviewed and merged faster.
- **Small & Atomic Commits**:
  - Keep PRs focused on a single logical change. Smaller PRs are easier for senior engineers to review and safer to deploy.

---

## 2. Navigating the Codebase & Daily Work 💻

- **Trace End-to-End Before Editing**:
  - When assigned a feature or bug, trace the flow from UI → API Gateway → Controller/Service → DB/External Integrations.
  - Understand *why* code was written a certain way before refactoring it.
- **Write Tests Early**:
  - Add unit and integration tests for critical business logic, especially calculations and edge cases.
- **Document As You Learn**:
  - Keep a personal dev log (or update team docs) for local setup, environment configurations, and internal APIs.

---

## 3. Communication & Workplace Best Practices 🚀

- **The 20-Minute Rule**:
  - When stuck, attempt to debug for 15–20 minutes independently.
  - If still stuck, ask for help! Provide context: *What you are trying to do*, *what you tried*, *what error occurred*, and *your hypothesis*.
- **Effective Daily Standups**:
  - Keep updates concise and structured:
    1. **Completed**: What you shipped or resolved.
    2. **In Progress**: What you are working on today.
    3. **Blockers**: Anything holding you back (access, missing API spec, waiting on review).
- **Take Notes in Meetings**:
  - Always keep a notepad or doc open during 1-on-1s and technical discussions. Don't ask the same clarification twice.

---

## 4. Business & Domain Context 📑

- **Understand the Product**:
  - Prosperr.io builds tax optimization and wealth management products.
  - Learn key tax concepts (Old vs. New Tax Regime, Section 80C/80D, Form 16, HRA exemptions, CTC components, TDS).
  - Understanding the domain makes you a proactive engineer who spots logical bugs before they happen.

---

## 5. Mindset & Growth 📈

- **Focus on Impact over Lines of Code**: Quality, readability, and reliability matter far more than code volume.
- **Ask for Feedback**: Proactively ask your mentor/manager in 1-on-1s: *"What is one thing I could improve in my PRs or daily workflow?"*
- **Be Reliable**: If you promise to deliver something by a deadline, communicate early if unexpected blockers arise.
