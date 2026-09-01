# Résumé feedback — Krupa Patel, EIT

Overall: strong, relevant content — ISRO + industrial automation + Canadian manufacturing is a rare and valuable combination. The main gaps are **quantification**, **formatting/consistency**, and a few **missing sections** that Canadian recruiters and ATS systems look for.

## 1. Fix first (these cost you interviews)

1. **Education has no school, no location, no dates.** Right now it reads: "B.Tech – Electronics and Communication Engineering" and nothing else. Add university name, city/country, and graduation year. A missing institution looks like an omission, and for EGM/P.Eng. tracking employers want to see it.
2. **No location on the résumé.** Add "Winnipeg, MB" under your name. Canadian employers filter hard on local candidates; without it recruiters assume you need relocation or sponsorship.
3. **"LinkedIn" is plain text, not a link.** Paste the full URL (`linkedin.com/in/…`) so it survives printing and ATS parsing. Add GitHub or a portfolio URL — and now, your website URL.
4. **Bullets are visually broken.** The bullet characters render *after* the text in the PDF (each `●` lands at the start of the following line). Whatever template/font is doing this, rebuild in a clean Word/Google Docs template — recruiters will see this as sloppiness, and ATS parsers choke on it.
5. **Inconsistent verb tense.** Current role mixes present and past ("Program and validate…", "Conduct Streamlined…", "Translated engineering concepts…"). Use present tense for HeatMasterSS, past tense everywhere else. Also fix "Conduct Streamlined mechanical component creation" — that's a grammatical error; make it "Streamlined mechanical component creation by building reusable Inventor iParts and iAssemblies."

## 2. Quantify everything

There is not a single number in your experience section. Numbers are what separate a technologist résumé from an engineer résumé. Add whichever of these you can honestly estimate:

- How many furnace/control product lines do you own PLC/HMI code for?
- Test/defect turnaround: "reduced validation cycle from X days to Y."
- Six Sigma/Lean results: "cut rework on control board assembly by X%."
- OTA project: "deployed to X units in the field", "eliminated ~X service visits/year."
- Drafting throughput: "produced X schematics/drawings per release."
- ISRO: number of boards bring-up'd, data rates, frequency bands (UHF 406 MHz for COSPAS-SARSAT), test coverage.

**Before:** "Analyze test data using Python, Excel, Power BI, and LabVIEW to identify trends and improve product quality."
**After:** "Built Power BI dashboards over LabVIEW/Python test logs covering 12 furnace models, cutting failure-mode triage time from 2 days to under 4 hours."

## 3. Structural changes

- **Merge the Projects section into the roles it belongs to.** Right now GAGANYAAN/ELT/DAT (ISRO) and the OTA control boards / myHeatMaster app (HeatMasterSS) sit at the bottom, disconnected from your jobs — they're your strongest achievements and they read as side hobbies. Move them up as achievement bullets under the relevant employer, and keep only 2–3 genuinely personal/academic projects (FPGA filter, solar tracker, Pi security) in a short "Academic & Personal Projects" section.
- **Trim the academic projects.** Bluetooth home automation, solar tracker, motion detection, FPGA filter and Pi security is five undergrad projects for someone with 4+ years of industry experience. Keep the two most technically impressive.
- **Cut "Relevant Coursework" down or remove it.** With 4 years of experience, 11 courses is filler. Keep 3–4 (Embedded Systems, DSP, VLSI, Digital Communication) or drop the line.
- **Group the 8 certifications by weight.** Lead with "Engineer-in-Training (EIT), Engineers Geoscientists Manitoba" — that's the one Canadian hiring managers scan for — then the rest, with issuers and years.
- **Add a "Selected Achievements" or keep the summary tighter.** Your summary is 4 lines and lists 8 skill areas; cut it to 2–3 lines with one differentiator (satellite beacon firmware at ISRO → industrial controls in Canada).

## 4. Wording and accuracy

- "FPGA Basics" and "SCADA basics" under skills — the word "basics" invites doubt. Either move them to a "Familiar with" line or drop them. Never advertise weakness in a skills list.
- "etc." appears twice in Technical Skills. Remove it; it reads as padding.
- "Canva" and "MS Office Suite" don't belong on an engineering résumé unless you're applying to a role that asks. Replace with things you clearly do: Git, VS Code, Modbus/CAN (if applicable), Excel (data analysis), requirements/ECO management.
- Specify the **PLC brands and HMI platforms** you actually use (Allen-Bradley/Studio 5000, Siemens TIA Portal, Codesys, Automation Direct…). "PLC programming" alone will lose keyword matches against job postings that name a brand.
- Same for protocols: Modbus RTU/TCP, CANbus, Ethernet/IP — these are high-value ATS keywords in controls roles.
- "Worked on SATCOM terminal systems" — replace "Worked on" with a real verb (Developed / Characterized / Integrated).

## 5. Nice-to-haves

- One-page vs. two-page: with your experience two pages is fine, but only if page 2 is dense with substance. After merging projects into roles, aim for a tight two pages.
- Add **work authorization** if you're a PR/citizen ("Permanent Resident" or "Eligible to work in Canada") — this removes a very common screening question.
- Tailor the summary line per application (controls role vs. embedded/firmware role vs. test engineering); the three read very differently to hiring managers and your background supports all three.
- Keep a plain-text/ATS version with no icons or emoji glyphs (the 📧/📞 symbols can garble in some parsers).

## 6. Where the website helps

The site fills the gaps the résumé can't: project detail, tags for keyword discovery, and a downloadable PDF. Once you host it, add the URL to your résumé header and LinkedIn.

**Still needed from you to finish the site:**
- Your LinkedIn URL (currently a placeholder link).
- University name and graduation year.
- Optional: a headshot, and any photos/diagrams of boards or panels you're allowed to share publicly.
