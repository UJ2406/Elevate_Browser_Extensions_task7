# Browser Extensions Security Audit (Task 7)

## 📋 Task Overview

Reviewed all installed browser extensions in Chrome for potential risks, privacy concerns, and security best practices. Removed or flagged any extensions with suspicious permissions, origins, or user feedback.

---

## 🎯 Objectives

- Learn to identify, evaluate, and (if needed) remove suspicious browser extensions.
- Develop awareness of browser extension security and user privacy risks.
- Answer key interview questions relating to extension security.

---

## 🛠️ Tools Used

- Google Chrome (or any Chromium-based browser)
- Chrome Web Store for extension research

---

## ⚙️ Methodology

1. **Opened Browser Extension Manager**: Navigated to `chrome://extensions/` to view all installed add-ons.
2. **Reviewed Each Extension**: Read description, permissions, and clicked "Details" for more info.
3. **Audited Permissions and Publisher**: Checked which extensions had excessive or risky permissions and whether they were published by reputable sources.
4. **Checked User Reviews & History**: Searched each extension on the Chrome Web Store to assess user ratings and any negative security news.
5. **Identified Suspicious & High-Risk Extensions**: Flagged extensions with unnecessary or high-risk permissions or unclear reputations.
6. **Removed or Analyzed Extensions for the Report**: Removed dangerous/unneeded extensions, documented safer alternatives.
7. **Documented Process and Lessons Learned**: Listed all actions, findings, screenshots, and security tips.

---

## 📝 Extensions Reviewed

| Extension                             | Publisher/Origin | Permissions (Key)                               | Review & Notes                                         | Risk Level   |
|----------------------------------------|------------------|-------------------------------------------------|--------------------------------------------------------|--------------|
| Enable right click - allow copy & select | Unknown/Third-party | Read/change data on all sites                  | Useful, but broad permissions mean audit is required.   | Moderate    |
| Google Docs Offline                    | Google           | Access offline storage for Docs/Sheets/Slides   | Official, trusted, needed for offline work.             | Low         |
| Shimeji Browser Extension              | Third-party      | Overlay content, basic tab access               | Entertaining, but check reviews; generally non-malicious| Low-Med     |
| HTTPS Everywhere                       | EFF/Trusted      | Modify web requests to enforce HTTPS            | Open-source, highly rated, proactive security           | Low         |
| PayPal Honey: Coupons & Cash Back      | PayPal           | Read shopping/browsing data on visited sites    | Reputable, but collects shopping habits for rewards     | Moderate    |
| Amazon Image Download                  | Third-party      | Access amazon.com, download images + videos     | Risk: Broad access, check reviews for privacy alerts    | Moderate-High|
| Flash Video Downloader                 | *Varies/many*    | Read/change data on all sites, download content | Many such extensions have privacy/malware incidents     | High        |
| ColorZilla                             | Trusted/WebDev   | Access page content for color picking           | Developer tool, minimal risks when from reputable source| Low         |

---

## 🚨 Suspicious or High-Risk Extensions Comment

**Flash Video Downloader**  
- Many variants flagged for excessive permissions and history of malware/adware injection.
- Recommendation: REMOVE after demo and seek safe alternatives or check publisher reputation carefully.

**Amazon Image Download - Include Photo & Video**  
- Any download tool not by Amazon can pose risk—possible adware or data harvesting.
- Recommendation: Only use officially verified publisher tools.

**Enable right click - allow copy & select and PayPal Honey**  
- Moderate risk: Useful, but monitor for privacy/policy changes or suspicious permissions updates.

---

## 👍 Safe to Keep

- **Google Docs Offline** (Official)
- **HTTPS Everywhere** (Open source)
- **ColorZilla** (Known tool for designers; safe from well-reviewed sources)
- **Shimeji Browser Extension** (Low risk, watch for unwanted behavior)

---

## 📰 Research and Best Practices

- Even popular extensions can be sold to third parties and become malicious after updates.
- Always check permissions! "Read and change all data on all websites" should rarely be needed.
- Avoid unused, low-rated, abandoned, or copycat extensions.
- Prefer open-source or well-documented tools.
- Remove anything you don’t regularly use.

---

## 💡 Key Takeaways

- Browser extensions have deep access and can become attack vectors for privacy/data theft.
- Never ignore extension permissions and always check publisher legitimacy.
- Regularly review your installed extensions—even trusted tools can become risky after updates.

---

## 📝 Interview Questions & Answers

**1. How can browser extensions pose security risks?**  
Some extensions can read/modify all webpage content, potentially stealing sensitive info, tracking users, inserting ads, or executing malware if compromised or maliciously designed.

**2. What permissions should raise suspicion?**  
- “Read and change all your data on all websites”
- Access to clipboard, download management, browsing history, keystroke or credential capture, tab management (especially for non-productivity tools).

**3. How to safely install browser extensions?**  
Only install from official stores, check reviews/user count, verify the publisher, check update history, and review permissions before enabling.

**4. What is extension supply-chain attack?**  
When a legitimate extension is sold or updated to include harmful code, affecting all users in the supply chain.

---

## 📂 Repository Structure

```
browser-extension-audit-task7/
├── README.md                    # This file
├── screenshots/                 # Supporting images
└── findings.txt                 # Extension-by-extension audit log

```
