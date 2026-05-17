Competitive Analysis
**Based on:** First-hand app walkthroughs with real screenshots
**Apps:** Groww (26 screens), ET Money (20 screens), INDmoney (22 screens)
**Date:** May 2025

---

## Groww — Real onboarding journey

**Stats from actual experience:**
- Total screens before reaching home: 26
- Investment goal questions asked: 0
- Personalised fund recommendation: None
- Account status at end of 26 steps: "Activation in progress — cannot invest yet"

### Screen-by-screen observations

| Screen | What it shows | User impact |
|---|---|---|
| 1 | Email + OTP | Simple start |
| 2 | Set Password — complex rules | Minor friction |
| 3 | Mobile number — "needs to link to bank account" | Trust concern — bank mentioned before app seen |
| 4 | Mobile OTP + "I authorise Groww to validate my bank details" | Authorising bank access before seeing anything |
| 5 | Set Groww PIN | Another credential to remember |
| 6 | Enter PAN | Expected |
| 7 | Confirm PAN — "CANNOT be changed later" ⚠️ | Anxiety spike — fear of permanent mistake |
| 8 | Bank details auto-filled — confirm | Confusion — how did it know? |
| 9 | FATCA/CRS declaration checkbox | Legal jargon — user does not understand |
| 10 | Draw signature | Feels very formal for a first-time investor |
| 11 | Add nominee — needs PAN/Aadhaar of nominee | User skips — doesn't have this ready |
| 12 | Selfie for KYC | Starting to feel like a lot of steps |
| 13 | Enter father's name | Confusion — why is this needed for investing? |
| 14 | Trading experience — No Experience to 5+ Years | Selected "No Experience" — nothing changed |
| 15 | Occupation — 12 options including Farmer, Agriculturist | Why does this matter for a SIP? |
| 16 | Annual income — 8 brackets | Irrelevant as a student with no income |
| 17 | Marital status — Single / Married | No connection to investment explained |
| 18 | Declarations — F&O, Commodities, SEBI legal text | Checked everything without understanding |
| 19 | Aadhaar eSign prompt — "just one step away" | Step 19 and still going |
| 20 | Full account opening form — dense legal document | Cannot read all this |
| 21 | eSign legal consent — must watch video | Maximum fatigue |
| 22-23 | Aadhaar number + OTP | Finally last step it seems |
| 24 | "You're all set!" — but "verification in process" | Complete let-down — still can't invest |
| 25 | F&O onboarding prompt — "What is F&O?" link | Irrelevant for a first-time investor |
| 26 | Home screen — "Account activation: In progress" | DROP-OFF CONFIRMED — after 26 steps, still cannot invest |

### Critical insight
Groww collects trading experience (Screen 14), occupation (Screen 15),
annual income (Screen 16), and marital status (Screen 17) — four personal
profiling questions — but uses NONE of this data to personalise the home
screen or recommend a fund. A "No Experience" student sees the identical
home screen as a "5+ Years" experienced trader.

---

## ET Money — Real onboarding observations

### What they do that Groww does not

**Screen 1 (carousel):** Shows PFRDA, IRBI, RBI, IRDAI logos immediately.
Regulation as trust signal before signup even begins.

**Screen 6:** "Choose your risk profile — Conservative / Moderate / Aggressive"
Asked BEFORE showing any fund. With a "I will do it later" escape hatch.
This is the single most impactful design decision in their onboarding.

**Screen 8:** "Choose your ET Money Experience — No-fee (AMFI Registered
ARN: 112749) vs ₹499/month (SEBI Registered RIA)"
Full fee transparency + regulatory credentials shown = trust built.

**Screen 9:** "Start an SIP with top funds — Growth (5+ yrs) / Balanced
(3-5 yrs) / Stability (up to 3 yrs)"
Time horizon as the fund filter. No category jargon. Simple.

**Screen 10:** "ET Money approved" badge on each fund. Rank shown
(#1 out of 24). Return consistency 4.8 GOOD. Downside protection 4.2 GOOD.
Expert interpretation provided — user doesn't need to judge raw numbers.

**Screen 11:** "Fund recommendation — Based on your risk profile: Moderate
— Recommended for you: Fund ✓ Category ✓"
"Why should you invest? [4 personalised bullet points explaining fit]"
This is what Groww's proposed feature should replicate.

---

## INDmoney — Real onboarding observations

**Screen 1:** "Trusted by 1.5 Crore+ Indians" — social proof on
the very first sign-up screen. Groww has nothing equivalent.

**Screen 4:** "Where do you want to make your first investment?
— Indian Market / US Market / Mutual Funds"
Investment intent captured BEFORE KYC. Not after. This is key.

**Screen 12:** "How long have you been investing? — First time investor /
Less than 2 years / 2-5 Years / 5+ Years"
"First time investor" is an explicit option. The user is validated,
not assumed to be an expert. Groww has this question but ignores the answer.

**Screen 20:** "Add minimum ₹100 to invest"
Quick picks shown: ₹1000 / ₹2500 / ₹5000
Minimum ₹100 stated clearly = lowest psychological entry barrier.
Groww defaults to higher amounts without stating the minimum.

**Screens 20–22:** Persistent 3-step progress bar throughout:
"KYC completed ✓ → Add Money → Buy 1st Stock"
User always knows where they are. Groww has no progress indicator.

**Screen 21:** "WELCOME RAHUL — Begin Your Journey with Indian Stocks
— You're all set — just pick your first stock"
Personalised by name + clear immediate CTA. Groww: "Account activation
in progress — taking longer due to technical issue."

---

## Feature gap matrix (screenshot-verified)

| Feature | Groww | ET Money | INDmoney |
|---|---|---|---|
| Goal or investment intent question | ✗ | ✓ | ✓ |
| Risk profile asked before fund browsing | ✗ | ✓ | ✗ |
| Personalised fund recommendation | ✗ | ✓ | ✗ |
| Trust signal on first screen | ✗ | ✓ | ✓ |
| Fee model transparency | ✗ | ✓ | ✗ |
| Progress indicator during KYC | ✗ | ✗ | ✓ |
| Minimum ₹100 shown clearly | ✗ | ✗ | ✓ |
| Expert verdict on each fund | ✗ | ✓ | ✗ |
| Can invest immediately after KYC | ✗ | ✓ | ✓ |
| Personalised welcome by name | ✗ | ✗ | ✓ |

---

## 3 Proven gap insights

**Gap 1 — Data collected, never used**
Groww collects trading experience, occupation, income, and marital status
during KYC (4 questions) but routes all users to the same generic home
screen with the same fund list regardless of their answers.
ET Money asks one risk question and immediately uses it to filter and
label every fund recommendation.
Source: Groww screens 14–17 vs screen 26 (same home for all users)

**Gap 2 — Cannot invest after completing full KYC**
After 26 screens including PAN, bank, signature, selfie, parents' name,
and Aadhaar eSign — Groww shows "Account activation: In progress —
taking longer due to a technical issue." The user cannot invest.
INDmoney and ET Money allow investment immediately after KYC completion.
This is the confirmed activation drop-off that creates the 60-70%
never-invested statistic from our Day 3 research.
Source: Groww screen 24 and screen 26

**Gap 3 — Zero goal collection in 26 screens**
Groww asks marital status but never asks "What are you investing for?"
or "How long do you want to invest?" Both competitors ask investment
intent or goal within the first 4-6 screens and use it to shape the
entire subsequent fund browsing experience.
Source: All 26 Groww screens reviewed — zero goal question present

---

## Solution direction (evidence-based)

The proposed solution is a Goal-Based Activation Flow — a 3-screen
micro-onboarding inserted AFTER Groww's existing KYC and BEFORE the
home screen:

Screen A: "What is your goal?" (Emergency fund / Wealth growth /
          Tax saving / Child education / Home / Retirement)
Screen B: "How long can you stay invested?" (Under 1 yr / 1-3 yrs /
          3-5 yrs / 5+ yrs)
Screen C: "How do you feel about risk?" (scenario-based, not jargon)

Result: ONE fund recommendation surfaced with:
- "Recommended for you" label
- ₹100 default SIP with slider
- "Why this fund?" — 3 bullet points matching the user's answers
- SEBI registration badge + "You can stop anytime" text

This closes all 3 gaps with a single feature. It mirrors what ET Money
does most effectively at their conversion-optimised recommendation step,
applied to Groww's 50M+ user base.

---

*This part is complete. Next part — Data analysis with AMFI dataset in Python*
