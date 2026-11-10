# W2-PM2 — Footprinting and Reconnaissance Using GHDB

**Networkwalks Cybersecurity Internship | Week 2 | Project Module 2**

|Project information|Details|
|-|-|
|Intern|Abdulmajid Bello|
|Intern ID|NW-084-2ST|
|Batch|B0840|
|Environment|Kali Linux and web browser|
|Assessment period|November 2026|
|Tool / resource|Google Hacking Database (GHDB), Google search|
|Project category|OSINT and search-engine reconnaissance|

## 1\. Project overview

This module investigates how Google search operators and the Google Hacking Database (GHDB) can reveal information indexed by search engines. The instructor assigned two exercises: identify ten publicly exposed camera candidates and identify ten listings containing downloadable mathematics PDF ebooks. The original worksheet has four columns: **No., Link, Relevant Dork, and Username/Password (if any)**.

This report distinguishes **search leads** from **verified findings**. Public indexing, an accessible webpage, or a visible device interface does not by itself establish an exploitable vulnerability. Evidence involving unrelated camera systems is referenced by a restricted evidence identifier rather than republishing live camera endpoints or credentials.

## 2\. Objectives and tools

* Understand GHDB search categories and Google search operators.
* Apply searches to the two categories specified by the instructor.
* Document the search method and source of each candidate.
* Review results critically and distinguish full PDF ebooks from articles or webpages.
* Preserve reproducible, appropriately redacted screenshots and report limitations accurately.

**Reference:** [Exploit Database — GHDB](https://www.exploit-db.com/google-hacking-database)

### Search operators used

|Operator|Purpose|
|-|-|
|`intitle:`|Search for a term in a webpage title|
|`inurl:`|Search for a term in a URL|
|`filetype:pdf`|Search for indexed PDF files|
|`site:`|Restrict results to a specified site or domain class|
|Quoted terms|Ask the search engine to match an exact phrase|

## 3\. Task 1 — Security camera exposure research

### Instructor requirement

Locate ten live, exposed security camera links using GHDB dorks, and document the link, relevant query, and any username/password information.

### Procedure carried out

1. Opened the GHDB website. An initial attempt returned a Sucuri HTTP 502 origin-connection error.
2. Accessed GHDB and reviewed camera-related search entries.
3. Tested Google search queries based on camera interfaces, webpage titles, and URL patterns.
4. Recorded camera-related candidate URLs and search pages in a private working note.
5. Captured screenshots for the search process and results.

### Candidate evidence table

The table below records **research candidates**, not ten independently confirmed vulnerable cameras. For privacy and authorization reasons, the operational links and any credentials of unrelated third-party devices are not reproduced in this shareable README. The full notes should be restricted to authorized assessors and handled according to the internship's data-protection requirements.

|No.|Link / evidence reference|Relevant Dork|Username / Password (if any)|
|-:|-|-|-|
|1|Camera candidate C01 — restricted notes|Camera product-title/port query A|Not collected|
|2|Camera candidate C02 — restricted notes|Camera product-title/port query A|Not collected|
|3|Camera candidate C03 — restricted notes|Camera product-title/port query A|Not collected|
|4|Camera candidate C04 — restricted notes|Camera product-title/port query A|Not collected|
|5|Camera search/listing candidate C05 — restricted notes|Camera product-title/port query A|Not collected|
|6|Camera search/listing candidate C06 — restricted notes|Camera product-title/port query A|Not collected|
|7|Camera candidate C07 — restricted notes|Camera product-title/port query A|Not collected|
|8|Camera candidate C08 — restricted notes|Camera product-title/port query A|Not collected|
|9|Camera candidate C09 — restricted notes|Camera product-title/port query A|Not collected|
|10|Indexed image-directory candidate C10 — restricted notes|Directory-title query B|Not collected|

**Interpretation:** Some entries are search/listing portals or an image directory rather than individual security cameras. The candidate list must therefore **not** be described as ten verified live or vulnerable cameras. Any live camera verification must be restricted to a device the tester owns or has explicit permission to assess. The source notes also contain examples of other camera-interface query families, but those are not evidence of confirmed access or vulnerabilities.

### Task 1 screenshots

!\[Initial GHDB HTTP 502 error](screenshots/W2-PM2-01-GHDB-502-Error.png)

!\[GHDB camera search](screenshots/W2-PM2-01-GHDB-CAM-Search.png)

!\[Camera-related dork analysis](screenshots/W2-PM2-02-Camera-Dork-Analysis-link.png)

*Do to security practice i wont include screenshots exposing identifiable third-party camera feeds or login details.*

## 4\. Task 2 — Mathematics PDF ebook discovery

### Instructor requirement

Find ten listings containing downloadable mathematics ebooks in PDF format and document their links and the Google dorks used.

### Recorded Google searches

```text
intitle:index.of "parent directory" mathematics pdf
filetype:pdf intitle:calculus site:edu
filetype:pdf "linear algebra" site:edu
filetype:pdf intitle:mathematics site:edu
```

### Candidate results table

The following entries reproduce the **links and associated search-query categories supplied in the working notes**. They are candidate mathematics resources, **not ten verified full ebooks**. Several are webpage listings, extracts, or academic papers. A URL being recorded under a dork does not independently prove it matched every Google operator.

|No.|Link|Relevant Dork (recorded search)|Username / Password (if any)|
|-:|-|-|-|
|1|https://www.unm.edu/\~megrad/Math/|`intitle:index.of "parent directory" mathematics pdf`|Not required / not tested|
|2|https://www.scribd.com/document/733209066/Primary-Maths-Dictionary-TSL|`intitle:index.of "parent directory" mathematics pdf`|Not required / not tested|
|3|https://files.smartsites.parentsquare.com/13519/calculus.pdf|`filetype:pdf intitle:calculus site:edu`|Not required / not tested|
|4|https://www.cmor-faculty.rice.edu/\~caam335/|`filetype:pdf "linear algebra" site:edu`|Not required / not tested|
|5|https://www.math.unl.edu/\~tshores1/mylinalg.html|`filetype:pdf "linear algebra" site:edu`|Not required / not tested|
|6|https://courses.aiu.edu/MATHEMATICS/1/SEC%201.pdf|`filetype:pdf intitle:mathematics site:edu`|Not required / not tested|
|7|https://www.math.iit.edu/\~fass/papers/Hersh\_Definition%20of%20mathematics.pdf|`filetype:pdf intitle:mathematics site:edu`|Not required / not tested|
|8|https://jontalle.web.engr.illinois.edu/uploads/298/HistoryMath-Burton.85.pdf|`filetype:pdf intitle:mathematics site:edu`|Not required / not tested|
|9|https://web.cortland.edu/andersmd/psy501/early.pdf|`filetype:pdf intitle:mathematics site:edu`|Not required / not tested|
|10|https://www.whitman.edu/mathematics/higher\_math\_online/higher\_math.pdf|`filetype:pdf intitle:mathematics site:edu`|Not required / not tested|

**Verification limitation:** The collection includes ten mathematics-related candidate listings, but a complete set of ten downloadable **ebooks** was not established. Items that are only papers, excerpts, or course pages need to be replaced or explicitly excluded if strict ebook-only compliance is required. A separate University of Nebraska course link was also present in the raw notes but was not included in this ten-row candidate table.

### Task 2 screenshots

!\[Mathematics PDF search](screenshots/W2-PM2-04-Mathematics-PDF-Search.png)

!\[Mathematics PDF result](screenshots/W2-PM2-05-Mathematics-PDF-Results.png)

## 5\. Challenges and limitations

* The GHDB site initially returned an HTTP 502 error; it was documented as a temporary access issue.
* Search engines may change results depending on date, location, indexing, or query interpretation.
* Public indexing does not prove the existence of a vulnerability.
* The camera evidence does not establish that all ten entries are independent, live, vulnerable security cameras.

## 6\. Learning outcomes

Through the GHDB exercises, I learned how search operators narrow information discovery, how to record a search trail, why independent validation matters, and how to separate potentially sensitive research notes from evidence suitable for a technical portfolio.

## 7\. Conclusion

W2-PM2 provided hands-on practice with GHDB and search-engine reconnaissance in two categories: camera-related exposure research and mathematics PDF resource discovery. The work produced recorded search queries, candidate results, and screenshot evidence. **The two strict ten-item verification criteria remain partially unconfirmed**, and this limitation is stated explicitly rather than presenting candidate links as proven vulnerabilities or complete textbooks.

\---

**Prepared by:** Abdulmajid Bello  
**Intern ID:** NW-084-2ST  
**Batch:** B0840  
**GitHub:** [cYBerLson](https://github.com/cYBerLson)

*For authorized cybersecurity education and defensive security research.*

