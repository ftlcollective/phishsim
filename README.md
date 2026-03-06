# 🎣 PhishSim — Phishing Awareness Demo
### A Cybersecurity Education Project

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Education](https://img.shields.io/badge/Purpose-Cybersecurity%20Education-blue?style=for-the-badge)

---

> ⚠️ **DISCLAIMER:** This project was created strictly for **cybersecurity education and awareness training**. All pages use a fictional brand ("PayVault") and contain no real payment processing. No real credentials, card details, or personal information are collected at any point. Do not use this for any malicious purpose.

---

## 📖 About This Project

PhishSim is a hands-on classroom exercise designed to teach students how to identify phishing websites. It simulates a convincing fake payment portal — complete with psychological manipulation tactics, visual deception techniques, and common errors found in real phishing attacks.

The project consists of **four pages**:

| File | Purpose | Audience |
|------|---------|----------|
| `payvault-payment-STUDENT.html` | Fake payment page — no hints | 👨‍🎓 Students |
| `payvault-success-STUDENT.html` | Fake success page — no hints | 👨‍🎓 Students |
| `payvault-phishing-demo.html` | Payment page with 9 annotated red flags | 👨‍🏫 Instructor reveal |
| `payvault-success-demo.html` | Success page with 7 annotated red flags | 👨‍🏫 Instructor reveal |

---

## 🧠 How the Exercise Works

**Step 1 — Student Discovery**
Students are given the two `STUDENT` pages and asked to identify as many suspicious elements as they can within a set time. No hints are provided.

**Step 2 — Class Discussion**
The instructor leads a discussion on what students noticed and what they may have missed.

**Step 3 — Instructor Reveal**
The annotated `demo` versions are shown. Students hover over the red **⚑ FLAG** markers to reveal detailed explanations of each phishing technique.

**Step 4 — Debrief**
Students compare their findings against the 16 total flags across both pages and discuss what made certain tricks hard to spot.

---

## 🚩 Red Flags Covered

### Payment Page (9 flags)
1. **Lookalike domain** — `payvault-secure.com` instead of `payvault.com`
2. **Suspicious URL parameters** — `?redirect=true&session=a7f2`
3. **Artificial urgency** — live countdown timer pressuring immediate action
4. **Vague recipient** — payment going to "Online Services Ltd"
5. **Excessive data harvesting** — asking for ID number AND bank password alongside card details
6. **Spelling & grammar errors** — "Copywright", "Polcy", "Tearms", "Contect"
7. **Fake trust badges** — SSL, Verified, and Protected icons with no real backing
8. **Hidden harmful fine print** — buried recurring charge and data-sharing consent
9. **Generic greeting** — "Dear Valued Customer" instead of your real name

### Success Page (7 flags)
1. **False reassurance** — convincing confirmation page to delay victim reporting fraud
2. **Fake transaction ID** — randomly generated in-browser, not from any real processor
3. **Post-payment data harvesting** — "confirm your email" prompt after details already stolen
4. **Persistence tactic** — push to download a malicious app
5. **Spelling error on confirmation** — "Reciept" on the download button
6. **Hidden subscription** — R149/month recurring charge buried in confirmation fine print
7. **Dead support link** — fake contact page that could harvest further information

---

## 💡 Key Learning Outcomes

By completing this exercise, students will be able to:

- Identify lookalike domains and suspicious URL structures
- Recognise psychological manipulation tactics (urgency, fear, false trust)
- Understand that SSL padlocks do **not** guarantee a site is legitimate
- Know what data phishing sites typically target and why
- Understand that the attack continues even on the "success" page
- Apply critical thinking before entering any personal or financial information online

---

## 🛠️ Built With

- **HTML5** — semantic page structure
- **CSS3** — responsive layout, animations, tooltip system
- **Vanilla JavaScript** — live countdown timer, dynamic transaction ID generation, instructor reveal modal
- No frameworks, no dependencies, no build tools — runs entirely in the browser

---

## 📂 File Structure

```
phishsim/
├── README.md
├── payvault-payment-STUDENT.html     # Student exercise — payment page
├── payvault-success-STUDENT.html     # Student exercise — success page
├── payvault-phishing-demo.html       # Instructor version — payment page with flags
└── payvault-success-demo.html        # Instructor version — success page with flags
```

---

## 🚀 How to Run

No installation required. Simply clone the repo and open any HTML file in a browser:

```bash
windows:
start payvault-payment-STUDENT.html
start payvault-success-STUDENT.html
start payvault-phishing-demo.html
start payvault-success-demo.html

mac:
open payvault-payment-STUDENT.html
open payvault-success-STUDENT.html
open payvault-phishing-demo.html
open payvault-success-demo.html

xdg-open payvault-payment-STUDENT.html
xdg-open payvault-success-STUDENT.html
xdg-open payvault-phishing-demo.html
xdg-open payvault-success-demo.html
```

Each command just opens that file in your default browser. You don't need to open them all at once — for the classroom exercise you'd typically just share the GitHub Pages links directly with students instead of running them locally.

Since your repo will be on GitHub Pages, the easiest way to share is just sending the live URLs:
```
https://ftlcollective.github.io/phishsim/payvault-payment-STUDENT.html
https://ftlcollective.github.io/phishsim/payvault-success-STUDENT.html
```

Or deploy to GitHub Pages for easy classroom sharing via URL.

---

## 📚 Suggested Classroom Use

- **Individual exercise** — each student opens the pages on their own device and writes down findings
- **Group challenge** — teams compete to find the most red flags before the reveal
- **Printed handout** — screenshot the student pages and distribute as a paper exercise
- **Assessment** — use the 16 flags as a marking rubric

---

## ⚖️ Ethical Use

This project is provided for **educational purposes only**. The fictional "PayVault" brand was deliberately created to avoid impersonating any real financial institution. Reusing or adapting this project to impersonate real brands or collect real user data would be illegal and unethical.

---

## 👤 Author

Made with 🔐 for cybersecurity awareness education.

---

*If this project helped your class, consider leaving a ⭐ on the repo!*
