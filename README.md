# Omkar Bhalsing

Computer science undergraduate at SVKM's Mithibai College, Mumbai (GPA 8.93).

I build full-stack products end to end: the React interface, the Node and Express API, and the database underneath. My recent work centres on access control, real-time updates and Shopify storefronts.

[Portfolio](https://omkar-portfolio-cyan.vercel.app/) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/omkar-bhalsing-7aa44a2b4) &nbsp;|&nbsp; [Email](mailto:bhalsingom04@gmail.com)

---

## Projects

### SeatDrop: ticket booking that never sells a seat twice
A booking platform for movies and live events with a real-time seat map, a 5-minute seat hold and server-side checkout.

- In a load test, **50 users race for the same seat: exactly one succeeds, 49 are rejected, and there are no double bookings.**
- Seat holds are atomic in Redis (one Lua script claims all requested seats or none). A partial unique index in PostgreSQL rejects a double booking even if a hold expires at the worst moment.
- Seats update live for every viewer over Server-Sent Events. Checkout uses idempotency keys, so a retried payment is never charged twice.

**Stack:** React 19, Node.js, Express 5, PostgreSQL, Redis, JWT &nbsp;|&nbsp; [Repository](https://github.com/omkargitcs/seatdrop)

### CampusShare: a private notes library for college classes
A platform where students share notes, books and past papers, publicly or privately inside a class team.

- Three roles (student, teacher, admin) with permissions enforced on the server and re-checked against the database on every request.
- Teachers create class teams with invite codes and review student uploads before classmates can see them. Users get in-app notifications for approvals and flags.
- Files stay private and open through short-lived signed links. Uploads are checked for a real PDF signature, and sign-in and uploads are rate limited.

**Stack:** React, Vite, Tailwind CSS, Node.js, Express 5, PostgreSQL, Prisma, AWS S3, JWT &nbsp;|&nbsp; [Repository](https://github.com/omkargitcs/campus-share)

### TokenCare: keeping patients and doctors in sync
A Flutter app built around a denormalized NoSQL data model.

- The schema design cut multi-node read latency by **95%** and gives O(1) reads.
- Email-based two-factor sign-in with OTP reached **100% verified sign-ups** in a 14-user pilot.
- Flutter Streams keep patient and doctor views in sync in under a second.

**Stack:** Flutter, NoSQL, EmailJS &nbsp;|&nbsp; [Repository](https://github.com/omkargitcs/TokenCare)

---

## Experience

### Developer Intern, Scentivia Perfumes (Shopify)
- Built and shipped e-commerce features on the live storefront.
- Improved store workflows, page layout and performance-critical elements for a faster customer journey.

**Tools:** Liquid, Storefront API, theme customization

---

## Skills

| | |
| --- | --- |
| **Languages** | JavaScript, Python, Java, C++, SQL, HTML and CSS |
| **Frontend** | React, Tailwind CSS, Flutter |
| **Backend** | Node.js, Express, REST APIs, JWT authentication and role-based access control |
| **Data and tools** | PostgreSQL, MySQL, Redis, Firebase, Prisma, AWS S3, Git |

---

## Certifications

- **OCI 2025 AI Foundations Associate**, Oracle, October 2025. Neural network architectures and OCI generative AI services. [Credential](https://lnkd.in/dpjiuN55)
- **React.js course completion**, Scaler, July 2025. Component architecture, hooks and state management. [Credential](https://moonshot.scaler.com/s/li/t-mrEst-Cp)
- **Cybersecurity and IAM engagement**, Tata Group, April 2025. Access controls and identity governance. [Credential](https://www.linkedin.com/posts/omkar-bhalsing-7aa44a2b4_cybersecurity-iam-tata)

---

## Get in touch

I'm happy to talk about internships, projects or anything I've built. The quickest way is [email](mailto:bhalsingom04@gmail.com) or [LinkedIn](https://linkedin.com/in/omkar-bhalsing-7aa44a2b4).
