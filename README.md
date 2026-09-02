<div align="center">

<svg width="100%" height="220" viewBox="0 0 1000 220" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Slate Base -->
    <rect id="bg" width="1000" height="220" rx="10" fill="#2d3b55"/>
    
    <!-- Gradients for Layers -->
    <linearGradient id="cardGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="85%" stop-color="#f8fbff"/>
      <stop offset="100%" stop-color="#edf5ff"/>
    </linearGradient>

    <linearGradient id="blueBase" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#5ca9f8" stop-opacity="0.3"/>
      <stop offset="50%" stop-color="#2b7be4" stop-opacity="0.75"/>
      <stop offset="100%" stop-color="#1456bc" stop-opacity="0.95"/>
    </linearGradient>

    <linearGradient id="blueMid" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#80c3ff" stop-opacity="0.4"/>
      <stop offset="60%" stop-color="#388bfd" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#1a62d6" stop-opacity="0.9"/>
    </linearGradient>

    <linearGradient id="blueHighlight" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#b6dcfe" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#539bf5" stop-opacity="0.85"/>
    </linearGradient>

    <filter id="shadow" x="-5%" y="-5%" width="110%" height="120%" filterUnits="userSpaceOnUse">
      <feDropShadow dx="0" dy="8" stdDeviation="10" flood-color="#09101d" flood-opacity="0.4"/>
    </filter>

    <clipPath id="innerCardClip">
      <rect x="25" y="18" width="950" height="184" rx="4"/>
    </clipPath>
  </defs>

  <!-- Canvas Outer Background -->
  <rect width="1000" height="220" rx="8" fill="#2b384e"/>

  <!-- Inner Elevated White Card -->
  <g filter="url(#shadow)">
    <rect x="25" y="18" width="950" height="184" rx="4" fill="url(#cardGrad)"/>
  </g>

  <!-- Corporate Geometric Blue Waves (Clipped to Card) -->
  <g clip-path="url(#innerCardClip)">
    <!-- Top subtle light angle -->
    <path d="M600 18 L1000 18 L1000 100 L720 18 Z" fill="#ddecfe" fill-opacity="0.5"/>
    
    <!-- Background Arch -->
    <path d="M280 202 C 480 180, 680 80, 975 70 L975 202 Z" fill="url(#blueHighlight)"/>

    <!-- Mid Angular Swell -->
    <path d="M120 202 C 340 190, 520 145, 750 78 L975 140 L975 202 Z" fill="url(#blueMid)"/>

    <!-- Foreground Dynamic Ribbon -->
    <path d="M25 202 C 220 180, 480 140, 780 135 L975 180 L975 202 Z" fill="url(#blueBase)"/>
    <path d="M25 202 C 320 202, 540 168, 760 150 C 860 142, 930 162, 975 175 L975 202 Z" fill="#1b66db"/>
  </g>

  <!-- Left Header Content -->
  <g transform="translate(65, 55)">
    <!-- Overline Category -->
    <text x="0" y="24" fill="#1f6feb" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="14" font-weight="700" letter-spacing="2.5">
      KISHAN KUMAR
    </text>

    <line x1="0" y1="36" x2="48" y2="36" stroke="#218bff" stroke-width="2.5" stroke-linecap="round"/>

    <!-- Main Title -->
    <text x="0" y="70" fill="#0f1f38" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="28" font-weight="800" letter-spacing="0.2">
      Welcome to My Profile!
    </text>

    <!-- Subtitle / Meta -->
    <text x="0" y="102" fill="#4b6182" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="14.5" font-weight="500">
      Backend Engineer • FinTech and Lending Systems
    </text>
  </g>
</svg>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rdkishankumar/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/KISHANKUMAR_02/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krsh.kishankumar@gmail.com)

</div>

<br/>

## 🧭 About Me

- 🧠 **Problem Solver** — 500+ DSA problems solved on LeetCode & GeeksforGeeks, applied daily to fintech/lending backend challenges
- 📚 **Continuous Learner** — actively sharpening LLD/HLD system design, event-driven architecture (Kafka), and rules-driven workflows (Drools)
- ☕ **Java Specialist** — 4+ years building production systems in Java 17+, Spring Boot, and Hibernate

I build backend systems for lending and credit platforms — payment processing, credit assessment workflows, and transaction classification engines that can't afford to be wrong. Currently at **EPAM Systems**, working with **CoreLogic**; previously **4.5 years at Credochain** building loan-lifecycle infrastructure from the ground up.

---

## 💼 Experience Highlights

**EPAM Systems** — Software Engineer, *Client: CoreLogic* (Feb 2026 – Present)
- Collaborate with cross-functional teams to troubleshoot and resolve production issues, and proactively monitor system performance for early risk detection.

**Credochain** — Software Engineer → Intern (Jan 2021 – Jan 2026)
- Built a bank transaction classification utility (EMI, bounces, loan transactions, charges, salary, reversals, tax refunds), **cutting manual credit-team effort by 80%**
- Designed an extensible payment processing system integrated with **Razorpay**, enabling plug-and-play onboarding for multiple NBFC/banking partners
- Built a credit behavior classifier from third-party API data, **cutting analysis workload by 85%**
- Designed a pluggable **CIBIL/credit bureau integration** service supporting multiple vendors
- Revamped onboarding for **Ugro Capital** with OCR/NACH via DIGIO, **cutting manual effort by 90%**
- Built a cross-field deduplication system (bank account, PAN, ID, mobile) that **cut fraud by 75%**
- Optimized database queries on Spring Boot REST APIs, **improving response times by 20%**

---

## 🚀 Tech Stack

<table border="0">
  <tr>
    <td width="20%"><strong>Core Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Java_17+-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" />
      <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" />
      <img src="https://img.shields.io/badge/Drools-000000?style=flat-square&logo=redhat&logoColor=white" />
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Messaging</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Databases</strong></td>
    <td>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Cloud & DevOps</strong></td>
    <td>
      <img src="https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/Secrets_Manager-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/CloudWatch-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Tools & VCS</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white" />
      <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white" />
      <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white" />
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
      <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Architecture</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Microservices-6DB33F?style=flat-square&logo=spring&logoColor=white" />
    </td>
  </tr>
</table>

---

## 🏆 Coding & Problem Solving

<div align="center">
  <a href="https://leetcode.com/u/KISHANKUMAR_02/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/KISHANKUMAR_02?theme=dark&font=Ubuntu&ext=activity" alt="Kishan's LeetCode Stats" width="65%" />
  </a>
</div>

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=rdkishankumar&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=rdkishankumar&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=rdkishankumar&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="97%" />
</div>

---

<div align="center">

### 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rdkishankumar/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/KISHANKUMAR_02/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krsh.kishankumar@gmail.com)

<br/>

<img src="https://visitcount.itsvg.in/api?id=rdkishankumar&icon=0&color=0" alt="Views" />

</div>
