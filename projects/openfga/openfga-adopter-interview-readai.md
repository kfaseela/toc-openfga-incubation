# OpenFGA Adopter Interview - Read AI
**Status:** Draft

**Meeting Time:** 2025-08-09  
**Meeting Record:** TBD  

## Attendees
- **TOC:** Faseela K, TOC Sponsor of KServe  
- **TOC Shadow:** Ricardo Aravena  
- **Adopter:** Andrew Powers, Software Engineering Manager at Read AI

---

## About the Adopter Interview
The intent of the interview is to ascertain the maturity and adoption of the OpenFGA project by adopters. Notes are recorded here for review and approval before inclusion in OpenFGA’s due diligence document.  

---

## Organization Intro
**Can you give us an overview of your organization and what it does?**  
Read AI is the fastest-growing meeting notetaker and AI assistant in the world, acting as a store of intelligence across meetings, messages, email, documents, and other workplace touchpoints. Based in Seattle and trusted by more than 100,000 organizations and 75% of the Fortune 500, the platform is adding over 1 million new customers every month. They value transparency and security based on robust, scalable authorization.

---

## Motivation
**Compared with other products in this space (proprietary and open), what drew you to the project?**  
- Considered alternatives such as Authzed.  
- Previously used a proprietary authorization solution but faced performance and scalability issues.  
- Sought a solution with stronger sharing capabilities, standard best practices, and open source flexibility.  
- OpenFGA stood out for:
  - Clear and detailed documentation.  
  - Based on Google Zanzibar, aligning with desired product functionality.  
  - Approachable, supportive, and responsive maintainers.  
  - Ability to self-host.  
  - Cost-effectiveness and high performance.  

---

## Usage Scenario
**How long has your organization used the project?**  
- Evaluation began in February 2023.  
- Running in production since April 28, 2023.  

**Main motivations to adopt and key features used today:**  
- Need for scalable, reliable authorization with strong sharing semantics.  
- Uses most core features and integrates with Postgres for persistence.  

**Current level of usage and scale:**  
- Production.  
- Handles 5,200 requests per second under peak load with 20 ms p99 latency and 1.8 ms average latency.  
- Data store currently holds 5,323,283,829 tuples, growing daily.  

**Version and update cadence:**  
- Currently using v1.8.16.  
- Internal cadence: monthly updates.  
- OpenFGA release cadence is faster than adoption, but upgrades are smooth with no backward compatibility issues.  

**Adoption and integration experience:**  
- Aligning internal data models with OpenFGA was the biggest challenge.  
- Migration from proprietary system required careful design and data import.  
- Performance at peak load has been excellent; OpenFGA never a bottleneck.  

**Documentation utility:**  
- Documentation was key, with practical examples and modeling guides being especially useful.  
- Bulk tuple import documentation was referenced during implementation.  

**Measurable value:**  
- Improved confidence in secure data authorization.  
- Adoption of best practices improved internal design decisions.  
- Cost savings: reduced compute and hosting costs.  
- Reliable system performance even at high loads.  

**Future plans:**  
- Submit a case study and potentially a conference talk.  
- Open to further upstream contributions as engineering team grows.  

---

## Perception
**Project perception:**  

- **Community openness:** Active, approachable, supportive; timely and constructive responses.  
- **Governance:** Limited visibility; appears functional but greater transparency desired.  
- **Community growth potential:** Strong growth with adoption from diverse organizations.  
- **Maintainer diversity:** Heavily concentrated in a single company; broader diversity needed for long-term sustainability.  
- **Maintainer response:** Responsive and effective; bugs fixed quickly, feature requests handled thoughtfully.  

**Participation in project community:**  
- Attend community meetings.  
- Reported bugs fixed promptly.  
- Track project progress actively.  

**Community engagement:**  
- Engagement via community channels productive.  
- Maintainers responded quickly to bugs and feature requests with high-quality outcomes.  

---

## Project Strengths
- Excellent documentation (clear, practical, example-driven).  
- Strong project focus, solving a specific problem well.  
- High performance and reliability in production.  
- Support from larger companies in the ecosystem.  
- Engaged and responsive community.  

---

## Project Improvements
**Challenges to full potential:**  
- Maintainer diversity; governance concentrated in one company.  

**Recommendations:**  
- Broaden the maintainer base and governance to improve sustainability and community trust.
