## Alice Corp. v. CLS Bank (573 U.S. 208, 2014)

![Slip Opinion – First Page](slip_opinion_alice.png)

### Case Metadata
- **Court:** U.S. Supreme Court
- **Citation:** 573 U.S. 208
- **Decision Date:** June 19, 2014
- **Issue:** Patent eligibility under 35 U.S.C. §101
- **Outcome:** Claims invalid under §101

> **Held:** Because the claims are drawn to a patent-ineligible abstract idea, they are not patent eligible under §101. *Alice Corp. v. CLS Bank Int’l*, 573 U.S. 208, 217 (2014).

**Primary Source:** [Supreme Court Slip Opinion (PDF)](case.pdf)

---

Alice Corp. v. CLS Bank is the foundational Supreme Court decision defining modern patent eligibility for software and computer-implemented inventions under 35 U.S.C. §101.

The case concerned patents directed to an intermediated settlement system implemented on generic computer infrastructure. The Supreme Court held that merely implementing an abstract financial concept on a computer does not transform the idea into patent-eligible subject matter.

The Court articulated the now-canonical two-step eligibility framework:

1. Determine whether the claims are directed to an abstract idea, law of nature, or natural phenomenon.  
2. If so, determine whether additional claim elements provide an “inventive concept” sufficient to transform the claim into patent-eligible subject matter.

Applying this test, the Court concluded that the asserted claims recited only an abstract idea implemented using conventional computer components and were therefore invalid under §101.

Alice has since become the primary doctrinal lens through which software, business-method, and many AI-related patent claims are evaluated, and it has significantly reshaped both patent prosecution strategy and litigation outcomes.

This folder collects the asserted patents, representative claims, and structured eligibility analysis to illustrate how the Court applied the two-step framework at the claim level in practice.

---

## Patent Family at Issue (Alice v. CLS Bank)

The litigation involved four related patents in a single continuation/CIP family,
all tracing back to the same 1993 parent application. The Supreme Court treated
Claim 33 of the ’479 patent as representative and applied its §101 analysis to
all asserted claims across the family.


## Patent Family at Issue (Alice v. CLS Bank)

The litigation involved four related patents. The Supreme Court treated **Claim 33 of the ’479 patent** as representative.
Two later patents (’720, ’375) are **direct continuations of the ’510 application**, and the family ultimately traces back to the ’479 parent via earlier continuation/CIP links.

| Patent | Relationship (Immediate Parent) | Relationship (Family Lineage) | Filed | Issued |
|--------|--------------------------------|-------------------------------|-------|--------|
| US 5,970,479 | Parent | Root of asserted family | May 28, 1993 | Oct. 19, 1999 |
| US 6,912,510 | Continuation of earlier application; downstream of ’479 | Family member derived from ’479 via continuation/CIP chain | May 9, 2000 | Jun. 28, 2005 |
| US 7,149,720 | Continuation of ’510 application | Same family lineage back to ’479 | Dec. 31, 2002 | Dec. 12, 2006 |
| US 7,725,375 | Continuation of ’510 application | Same family lineage back to ’479 | Jun. 27, 2005 | May 25, 2010 |


Key point: invalidation of the representative claims effectively rendered the
entire patent family ineligible under §101.


---


### Purpose of this Analysis

Most discussions of Alice focus on the legal doctrine and two-step framework.  
This repository instead examines the asserted patent claims directly, mapping the Supreme Court’s reasoning to specific claim language to show **where and why the claims failed** under §101.

The goal is to treat eligibility as a claim-structure problem rather than an abstract legal principle, enabling more concrete guidance for drafting, evaluating, and stress-testing software and AI patents.

---

## Alice Corp (US 5,970,479)

<!-- Shows the Front Page of Patent Reduced Image Size -->
<p align="center">
  <img src="Patent_Front_Page.png" width="650">
</p>

**Original USPTO front page showing inventors, assignee, filing dates, references, and abstract.*
**Primary source:** [Google Patents – US 5,970,479](https://patents.google.com/patent/US5970479A/en?oq=5970479)

---

## Patent Metadata

| Field | Value |
|-------|--------|
| **Patent Number** | US 5,970,479 |
| **Assignee** | Swychco Infrastructure Services Pty. Ltd. (Melbourne, AU); Swychco Support Services Pty. Ltd. (Sydney, AU) |
| **Inventor** | Ian K. Shepherd |
| **Filed** | May 28, 1993 |
| **Priority Date** | May 29, 1992 (Australia) |
| **Issued** | October 19, 1999 |
| **Claims** | 39 total |
| **Independent Claims** | 10 (Claims 1, 16, 18, 32, 33, 35, 36, 37, 38, 39) |
| **Drawing Sheets** | 101 |
| **US Class** | 705/37, 705/4 (financial/business methods) |
| **Status** | Expired (20-year statutory term) |
| **Title** | *Methods and apparatus relating to the formulation and trading of risk management contracts* |

This analysis focuses on the specific computational and transactional steps recited in the claims rather than the high-level ‘idea of trading risk,’ because patent eligibility and validity turn on the claimed technical implementation details, not the abstract financial concept.





MISTAKE HERE SHOULD BE CLAIM 33

### Representative Claim (Selected by Supreme Court)
The Court treated Claim 33 of the ’479 patent as representative of all asserted claims.

1. A computer-based data processing system to enable the formulation of customized multi-party risk management contracts having a future time of maturity, the system comprising:
at least one stakeholder input means by which ordering stakeholders can input contract data representing at least one offered contract in at least one predetermined phenomenon, each said phenomenon having a range of future outcomes, and said contract data specifying entitlements due at maturity for said range of future outcomes, and a consideration due to a counter-party stakeholder;
at least one counter-party stakeholder input means by which at least one counter-party stakeholder can input registering data, independent of said stakeholder entering said contract data, as to a likelihood of each outcome in said range of future outcomes for one or more of said predetermined phenomena;
a data storage means linked with each said stakeholder input means and linked with each said counter-party stakeholder input means to store said contract data and said registering data; and
data processing means, linked with the data storage means, for pricing and matching contracts from said contract data and said registering data, said pricing including calculating a counter-consideration derived from said likelihoods and said entitlements, and said matching including comparing said consideration and said counter-consideration to match an offered contract with at least one of said counter-party stakeholders.



## References

- Justia summary: https://supreme.justia.com/cases/federal/us/573/208/  
- Background overview: https://en.wikipedia.org/wiki/Alice_Corp._v._CLS_Bank_International
- Discuss of case relevance: https://www.law.cornell.edu/supct/cert/13-298














## 8) Author and Feedback

Prepared by **M. Joseph Tomlinson IV**, Registered U.S. Patent Agent (USPTO Reg. No. 83,522).

This repository reflects independent research, professional experience, and
educational analysis of software patents, claim structure, and related case law.
Portions were developed with the assistance of AI tools and refined through
human review and judgment.

Content is provided for **educational and informational purposes only** and does **not**
constitute legal advice. Patent validity and enforceability ultimately depend on
examination, licensing, and litigation outcomes.

Corrections, suggestions, or additional sources are welcome.  
Please open an issue or contact the author directly.

**Email:** mjtiv@udel.edu


