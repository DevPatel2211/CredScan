# Our Project's Legal & Ethical Compliance Plan

**Project:** Credential Leakage Detection System using Dark Web Crawling
**Team:** [Your Name], Kathan Vyas
**Date:** September 2, 2025
**Version:** 1.0

## 1. Our Objective

For our project to succeed, we know it's critical to operate legally and ethically from the very beginning. This document outlines the research we've done on Indian and international law and the specific rules we will follow. Our goal is to demonstrate a clear and responsible plan for gathering intelligence from public sources for the purpose of proactive cyber defense.

## 2. Primary Indian Legislation We Are Following

We have identified two key laws in India that most directly impact our project's operations.

### a. The Information Technology Act, 2000 (IT Act)

* **Our Understanding:** This is India's primary "anti-hacking" law. It prohibits accessing any computer system or network without the owner's permission (Sections 43 & 66).
* **Our Compliance Strategy:** We have designed our project around a strict **"public access only"** policy.
    * Our crawler will **only** scrape data that is publicly visible without requiring a login.
    * We will **never** attempt to bypass authentication, brute-force logins, or exploit vulnerabilities.
    * We will programmatically respect `robots.txt` files and implement rate limiting to avoid disrupting any website.
    * Our project's honest and defensive intent—to protect an organization, not to cause harm—ensures we comply with the spirit and letter of this law.

### b. The Digital Personal Data Protection Act, 2023 (DPDPA)

* **Our Understanding:** This is India's main data privacy law. It governs how we handle personal data (like the emails and credentials we're looking for). The main challenge is that we won't have consent from the individuals whose data was leaked.
* **Our Compliance Strategy:** Our legal basis for operation hinges on the DPDPA's exemption for data that has been **"made publicly available"**.
    * **Purpose Limitation:** We will only use the data to identify leaks for our target organization and to alert them. The data will never be sold or used for other purposes.
    * **Data Minimization:** We will only collect the specific data points required (e.g., email, potential password string).
    * **Security & Deletion:** All findings will be stored securely. Once an alert is confirmed and processed, we will delete the raw personal data from our systems. We will not hoard data.

## 3. Broader Legal Context (National & International)

To be thorough, we also considered other laws that could be relevant.

* **Indian Penal Code & Copyright Act:** We recognize that digital data can be considered property and that website content can be copyrighted. Our "defensive purpose only" and "no republication" rules ensure we are not committing digital theft or copyright infringement.

* **GDPR (EU) & CFAA (USA):** We understand that the internet is global. We might scrape data of an EU citizen (triggering GDPR) or access a US-based site (implicating the CFAA).
    * **Our Global Strategy:** We will treat **all** data with the high standards of GDPR and DPDPA. Our commitment to only scraping **public data** also aligns with recent US court rulings regarding the CFAA, which generally permit scraping of information that is not behind a login wall.

## 4. Our Team's Ethical Code of Conduct

Beyond the law, we commit to these principles:

1.  **White-Hat Stance:** We are acting as defensive researchers, not attackers.
2.  **Protecting Privacy:** Our focus is on protecting the organization, not investigating the individuals whose data was exposed.
3.  **Responsible Disclosure:** Findings will only be disclosed to the designated security contact.

## 5. Conclusion

We are confident that by strictly following our "public data only" and "defensive purpose only" rules, our project will operate well within the legal and ethical boundaries required. We are ready to begin development with this framework as our guide.
