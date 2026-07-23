# Topical Authority — Kubikel.id

## Role and boundary

`Kubikel.id` should become an Indonesian-language decision and project-scoping hub for the three materially different systems currently combined on its homepage: office cubicles, toilet cubicle partitions, and electrical switchgear cubicles. Its job is to help owners, occupants, designers, procurement teams, facility teams, contractors, and electrical professionals identify which system they mean, translate needs into verifiable requirements, evaluate evidence, and understand the lifecycle from survey through replacement.

The knowledge layer does not replace product/service pages, engineering design, accessibility review, electrical calculations, protection studies, manufacturer instructions, competent installation, inspection, certification, or site-specific safety procedures. It must not promise a material, panel, electrical assembly, installation, delivery area, price, warranty, or performance without dated evidence.

`Kubikel.co.id`, `Cubicle.id`, `Cubicle.co.id`, `toilet.kubikel.id`, `toilet.cubicle.id`, `toiletcubicle.co.id`, `ToiletPhenolic.co.id`, and `Phenolic.id` are separate Syamsul-owned properties that may independently cover overlapping queries. On this domain, the evidence-backed editorial emphasis is terminology triage and multi-system project scoping. Cross-domain overlap is allowed; cannibalization controls apply only within `Kubikel.id`.

## Evidence audited

- Canonical repository: `cfpages-magangyumeko/kubikel.id`, branch `main`, non-fork, public. Portfolio inventory recorded `https://kubikel.id/` returning HTTP 200 and the repository updated 2024-11-30. The clean full-clone audit used commit `1b307b05347bca2fded51b25d5630681d93f107b`.
- The static WordPress export contains 142 tracked files and no repository-local Markdown or `AGENTS.md`.
- The sitemap index references three children. `page-sitemap.xml` has two URLs: the homepage and `/laman-contoh/`; `post-sitemap.xml` is empty; `category-sitemap.xml` has one relative URL for `/category/tak-berkategori/`. The export nevertheless contains `/2023/03/21/halo-dunia/`, so inventory and files disagree.
- The homepage is the only substantive page. Its title and H1 claim “Kontraktor Kubikel #1 Indonesia”; sections describe office cubicles, toilet cubicles, electrical cubicles, custom design, glass, phenolic, wood/multiplex, PVC, consultation, production, installation, testimonials, contact, and nationwide delivery.
- Commercial claims include “#1”, “24/7”, “kualitas terbaik”, guaranteed safety, nationwide delivery/installation, experienced team, “garansi 100%”, affordable price, a 4.8/5 rating, and two testimonials. Repository evidence does not substantiate these claims, the review population, project scope, certificates, geographic capability, or warranty terms.
- The homepage links to `https://toilet.kubikel.id` for toilet cubicles, several `#` placeholders, a map, WhatsApp, and contact details. The export contains two similar phone numbers ending `7155` and `7255`; each contact owner and current routing need verification.
- The static export retains WordPress admin/login assets, feeds, author/category archives, REST snapshots, default content, localhost URLs inside REST data, and stock-looking image filenames. These do not prove services, products, staff, projects, ratings, or experience.
- The homepage mixes furniture/partition work with electrical switchgear. Those are not interchangeable products, trades, hazards, standards, or procurement processes and require separate page owners.
- Current primary-source gates checked 2026-07-24: Indonesia’s building-accessibility regulation is recorded as in force by the BPK database at `https://peraturan.bpk.go.id/Details/104477/`; electrical-installation lifecycle safety and competency/certification duties are addressed by ESDM Regulation 10/2021 at `https://jdih.esdm.go.id/dokumen/view?id=2153`; workplace electrical K3 is recorded as in force by Kemnaker at `https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015`. Publication must recheck status and applicability rather than copying clause numbers from this plan.

Counts describe repository evidence, not live indexation, inventory, electrical competence, certification, accessibility compliance, service coverage, customer satisfaction, or commercial performance.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | One-page commercial site combines office, toilet, and electrical systems plus unsupported superlatives | expand | Homepage owns verified company/service overview; KBI-01-01 owns terminology triage | Live offer, legal entity, competencies, products, geography, projects, claims, canonical, and contact paths |
| Homepage “Kubikel Kantor” block | Thin description treats a workspace system as furniture | expand | Office commercial section plus KBI-03 and KBI-04 knowledge hubs | Actual product types, drawings, materials, furniture, acoustics, power/data scope, installation evidence |
| Homepage “Kubikel Toilet” block and links to `toilet.kubikel.id` | Thin product summary with a separate owned specialist domain | keep | Homepage provides a concise gateway; KBI-05 and KBI-06 educate; specialist domain may transact independently | Live destination, canonical intent, offered systems, access requirements, wet-area evidence |
| Homepage “Kubikel Listrik” block | A life-safety/high-energy system is described in one generic sentence beside partitions | expand | KBI-07 through KBI-10 own neutral electrical education; a verified commercial route may own qualified offer | Voltage/application scope, manufacturer authorization, design basis, test certificates, competent personnel, licenses |
| Homepage material cards | Glass, phenolic, wood/multiplex, and PVC claims are broad and sometimes presented without grade/test boundary | expand | KBI-11 material selection plus system-specific owners | Product datasheets, thickness/grade, finish, moisture/fire/impact/chemical tests, warranty, actual stock |
| “Custom”, production, installation, and nationwide claims | Process sounds universal across three incompatible systems and all Indonesia | manual review | Verified service pages by system; KBI-02, KBI-14, KBI-15, and KBI-16 own education | Capability map, factories/partners, lead times, site records, responsible parties, exclusions, delivery and installation logs |
| “#1”, best quality, safe, durable, affordable, experienced, 24/7, 100% warranty | Unsupported absolute or comparative claims | remove | Replace only with specific dated evidence and limitation statements | Source records, measurement method, warranty document, response logs, legal review |
| 4.8/5 rating and testimonials | Rating denominator/source and testimonial authenticity/consent are absent; images appear generic | manual review | KBI-18-04 owns evidence and consent method; homepage may show verified reviews | Original platform/source, population, date, consent, order/project linkage, image rights |
| `/laman-contoh/` | Default WordPress sample page is indexable and in sitemap | remove | Return 410 or redirect only if evidence shows a legitimate replacement | Backlinks, GSC queries, internal links, response behavior |
| `/2023/03/21/halo-dunia/` | Default “Hello world” post exists despite empty post sitemap | remove | Return 410; do not create an editorial replacement merely to preserve the URL | Backlinks, GSC data, internal links, response behavior |
| `/category/tak-berkategori/` | Indexable empty/default archive and relative sitemap URL | noindex | Future curated topic hubs own discovery | Live contents, internal links, sitemap generation |
| `/author/*`, feeds, comments feed | Thin archive/feeds add no current authority value | noindex | Author pages only after verified editorial governance; feeds only if intentionally supported | Response headers, robots, indexation, author identity/credentials |
| `/wp-admin/`, `/wp-login.php`, `/wp-json/*` static copies | Static WordPress operational artifacts and REST snapshots expose localhost references without useful public function | remove | Static deployment should serve only needed public assets/routes | Deployment behavior, dependencies, security review, broken links |
| `sitemap.xml`, `sitemap_index.xml`, child sitemaps | Mixed absolute/relative URLs and conflict with exported routes | canonicalize | Generate one canonical sitemap set from final indexable routes | Full crawl, status codes, canonical tags, GSC coverage |
| Placeholder `#` links and two phone-number variants | Broken/ambiguous interactions weaken task completion | manual review | Verified navigation and contact route | Current responsible contacts, form delivery, WhatsApp routing, privacy notice, conversion tests |
| Stock-looking media and generic alt text | Images do not prove products or projects; electrical image may not depict a cubicle | manual review | Original annotated diagrams/photos owned by each article and case study | Copyright/license, depicted system, date, location, consent, technical accuracy |

## Coverage matrix

| Completeness lens | Topic owners | Coverage decision |
|---|---|---|
| Definition, vocabulary, taxonomy, and history | KBI-01, KBI-07 | Separate office cubicle, toilet partition cubicle, and electrical switchgear meanings before any recommendation |
| Anatomy, components, materials, mechanisms | KBI-04, KBI-06 through KBI-12 | Cover partition panels/hardware/interfaces separately from busbars, breakers, protection, interlocks, earthing, and enclosures |
| Measurement, ratings, drawings, tolerances | KBI-08, KBI-13 | Dimensions and quantities for partitions; ratings and verified single-line/specification data for electrical assemblies |
| Need recognition and site survey | KBI-01, KBI-02 | Identify system, stakeholder, site, use, risks, existing conditions, evidence, and stop conditions |
| Requirements and design | KBI-03 through KBI-08, KBI-13 | Translate work patterns, privacy, accessibility, hygiene, environment, electrical duty, maintainability, and interfaces |
| Comparison and selection | KBI-03, KBI-05, KBI-07, KBI-11, KBI-16 | Compare real alternatives using performance and lifecycle criteria, never synonym or location swaps |
| Budget and procurement | KBI-13, KBI-16 | Quantity basis, quote normalization, scope/exclusions, documents, supplier/contractor qualification, warranty |
| Preparation, fabrication, and installation | KBI-09, KBI-14, KBI-15 | Separate factory production from site readiness and competent electrical work |
| Commissioning and handover | KBI-09, KBI-12, KBI-15 | Partition punch lists differ from electrical inspection, testing, certification, energization, and operating documents |
| Operation and normal use | KBI-04, KBI-06, KBI-10 | Workplace change, toilet cleaning/abuse, and electrical operating boundaries each have distinct owners |
| Inspection, maintenance, troubleshooting | KBI-10, KBI-17 | Electrical diagnostics require competent personnel; partition symptoms can route to cleaning, adjustment, repair, or replacement |
| Upgrade, replacement, and end-of-life | KBI-10, KBI-17, KBI-18 | Retrofit occupied sites, recover reusable parts, verify waste claims, and document decommissioning |
| Stakeholders and building types | KBI-02 through KBI-06, KBI-15 | Owners, users, cleaners, facility teams, designers, installers, electrical operators, accessibility users, and emergency responders need different paths |
| Geography and climate | KBI-06, KBI-11, KBI-15, KBI-17 | Heat, humidity, wet cleaning, coastal corrosion, transport, and site exposure change evidence; no city/province articles |
| Scale, quality, new build versus retrofit | KBI-03, KBI-05, KBI-08, KBI-13, KBI-17 | Scale by users, compartments, dimensions, electrical ratings, access, lifespan, and occupied-site constraints |
| DIY versus professional | KBI-09, KBI-10, KBI-15, KBI-17 | Readers may observe and document; electrical design, switching, testing, and energized work are professional boundaries |
| Safety, health, accessibility, and failure | KBI-04 through KBI-10, KBI-15 | Pinch/cut/fall/fire/moisture/hygiene/accessibility risks and electrical shock/arc/fire risks need explicit stop conditions |
| Standards, regulation, and evidence | KBI-05, KBI-08 through KBI-10, KBI-18 | Verify current primary sources, applicability, competency, certificates, test records, and manufacturer instructions |
| Environmental impact | KBI-11, KBI-14, KBI-17, KBI-18 | Material provenance, offcuts, cleaning, coatings, transport, service life, repairability, reuse, and disposal |
| Fundamentals, how-to, comparison, diagnosis | KBI-01 through KBI-18 | Every brief owns one task, with distinct neutral and commercial page boundaries |
| Calculators and visual references | KBI-03, KBI-05, KBI-08, KBI-12, KBI-13, KBI-15 | Layout diagrams, quantity sheets, interface matrices, checklists, test-document maps, and decision tables |
| Case studies, myths, trends | KBI-01, KBI-11, KBI-18 | Correct ambiguous terminology and marketing shortcuts; publish cases only from permissioned dated evidence |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KBI-01 | Meaning, scope, and cubicle taxonomy | Identify the intended cubicle system and the right expert path | Indonesian/English terms; office, toilet, electrical meanings; what is not a cubicle; use cases; history; glossary; triage questions; common category errors | Entity map, comparison table, glossary, sourced timeline, decision tree | Does not design or sell a system; office owners are KBI-03/04, toilet KBI-05/06, electrical KBI-07 through KBI-10 | 6 |
| KBI-02 | Need, stakeholder, survey, and project brief | Produce a system-specific brief from real site evidence | Goals; users; owner/operator/cleaner/installer roles; new build/retrofit; site photos; dimensions; utilities; access; schedule; risk; evidence gaps; change control | Survey checklist, brief template, RACI, annotated plan | Does not calculate quantities owned by KBI-13 or quote work owned by KBI-16 | 6 |
| KBI-03 | Office cubicle planning and layout | Choose a workspace layout that supports actual work patterns | Open versus enclosed; workstation modules; circulation; collaboration/focus; supervision; density; daylight; growth; furniture integration; moves/adds/changes | Layout diagrams, adjacency matrix, field measurements, user interviews | Does not own acoustics/ergonomics/cabling details in KBI-04 or transactions on commercial routes | 6 |
| KBI-04 | Office cubicle performance and interfaces | Specify usable office cubicles beyond panel appearance | Ergonomics; privacy; acoustics; lighting; glare; power/data; cable management; ventilation; storage; accessibility; fire/egress interfaces; change management | Performance matrix, ergonomic review, acoustic evidence, interface diagrams | Does not plan the overall layout owned by KBI-03 or certify building compliance | 6 |
| KBI-05 | Toilet cubicle planning and accessibility | Plan partition geometry around users, fixtures, access, and operations | Compartment types; accessible toilet; ambulant users; doors; clearances; privacy; circulation; children/family; schools/healthcare/workplaces; survey; current rules | Dimension diagrams, primary regulation review, user-path checklist, expert review | Does not choose panel chemistry owned by KBI-06/KBI-11 or approve compliance without a qualified reviewer | 6 |
| KBI-06 | Toilet cubicle durability, hygiene, and wet-area use | Select and operate a toilet partition system for its exposure | Wet/dry zones; cleaning chemicals; water and humidity; corrosion; impact/vandalism; privacy gaps; odors/mold boundary; hardware; hygiene; cleaning access; facility maintenance | Exposure matrix, cleaning protocol comparison, original defect photos, manufacturer data | Does not give medical advice, generic material selection owned by KBI-11, or accessibility geometry owned by KBI-05 | 6 |
| KBI-07 | Electrical cubicle fundamentals and system selection | Understand what an electrical cubicle does and which qualified process follows | Switchgear terminology; functions; incoming/outgoing; metering/protection; indoor/outdoor; metal enclosure; insulation medium; application; single-line context; alternatives; lifecycle | Single-line diagrams, anatomy drawings, manufacturer/standard sources, expert review | Neutral education only; no switching, design, purchase, or installation instruction | 6 |
| KBI-08 | Electrical ratings, protection, interlocks, and specification | Read a specification without treating ratings as interchangeable | Voltage/current/frequency; withstand/short-circuit ratings; insulation; IP/internal separation; busbar; breaker/switch; relay/meter; interlocks; earthing; arc risk; labels; environmental duty | Specification matrix, nameplate guide, protection concept diagrams, primary standards, qualified review | Does not calculate settings or approve equipment; competent electrical engineers and current standards own those decisions | 6 |
| KBI-09 | Electrical installation, inspection, testing, and commissioning | Understand the controlled path to safe energization | Design review; competent entities; transport/storage; room readiness; positioning; cable/earthing interfaces; manufacturer checks; inspection/testing; certificates; punch list; energization authority | Lifecycle gate diagram, document checklist, test-record map, primary regulation review | No DIY or live-work steps; only authorized competent parties perform installation, testing, certification, and energization | 6 |
| KBI-10 | Electrical operation, maintenance, faults, and decommissioning | Recognize records, warning signs, and escalation boundaries | Operating procedures; authorization; switching boundary; logs; inspection; maintenance basis; thermal/partial-discharge concepts; alarms/trips; water/fire/arc events; isolation; upgrade; end-of-life | Operator-document map, symptom/escalation table, manufacturer guidance, expert review | Does not diagnose or direct switching/live work; site procedures and competent electrical personnel own all interventions | 6 |
| KBI-11 | Partition panel materials and finishes | Compare office/toilet panel materials using declared performance | Phenolic/compact laminate; HPL-faced board; multiplex; PVC; glass; metal; cores; edges; coatings; moisture; impact; fire evidence; chemicals; UV; appearance; repairability | Material matrix, datasheets, sample tests, section diagrams | Excludes electrical enclosure materials owned by KBI-08 and product availability owned by commercial routes | 6 |
| KBI-12 | Partition components, hardware, and construction details | Understand the parts and interfaces that make partitions work | Panels; posts/pilasters; headrails; feet; hinges; locks; handles; indicator; brackets; fasteners; seals; trims; doors; furniture interfaces; substrate; corrosion pairs; spare parts | Exploded diagrams, hardware matrix, detail drawings, manufacturer comparison | Does not determine overall layout KBI-03/05, material selection KBI-11, or field installation KBI-15 | 6 |
| KBI-13 | Measurement, drawings, quantities, and tolerances | Turn a surveyed partition project into auditable information | Datum; opening/room dimensions; level/plumb; obstacles; modules; door swing; panel schedule; hardware count; wastage assumptions; shop drawings; revisions; tolerances; as-built | Measurement checklist, quantity worksheet, drawing set, worked calculation | Covers office/toilet partitions, not electrical equipment sizing/ratings owned by KBI-08 | 6 |
| KBI-14 | Partition fabrication and production quality | Understand how approved information becomes consistent components | Submittal approval; cutting; drilling; edge treatment; machining; finish; labels; dry assembly; hardware kitting; inspection; packing; nonconformance; traceability | Process map, traveler/QC sheet, defect atlas, original factory evidence | Does not claim Kubikel.id owns a factory; site installation belongs to KBI-15 | 6 |
| KBI-15 | Site readiness, partition installation, and handover | Coordinate safe installation and verify completed partition work | Substrate and room readiness; utilities; access; storage; protection; sequence; setting out; anchorage; alignment; doors/hardware; occupied-site control; punch list; cleaning; as-built/warranty handover | Readiness checklist, method sequence, hold points, acceptance form | Does not provide structural approval, electrical work, or substitute for contractor method statements and site safety plans | 6 |
| KBI-16 | Procurement, quotation, contract, and warranty | Compare offers and select a verifiable system/provider | Scope; dimensions; performance; material/grade; inclusions/exclusions; samples/submittals; price components; schedule; payment; change; warranty; supplier/contractor evidence; red flags | Quote-normalization table, procurement checklist, document register, legal-review gate | Does not publish invented prices or universal contract clauses; verified commercial routes own current offers | 6 |
| KBI-17 | Partition inspection, maintenance, repair, retrofit, and end-of-life | Diagnose partition symptoms and choose maintain, repair, or replace | Inspection intervals; cleaning; loose/sagging doors; corrosion; swelling/delamination; chips/cracks; graffiti; privacy gaps; spare parts; occupied retrofit; reuse; waste | Symptom tree, inspection log, repair/replace matrix, original defect photos | Excludes electrical maintenance owned by KBI-10 and health diagnosis | 6 |
| KBI-18 | Evidence, contractor governance, case studies, and environmental claims | Evaluate competence and publish claims that can be verified | Legal identity; role/scope; competency; certificates; project evidence; reviews/consent; QA records; complaints; warranty evidence; case method; environmental boundary; claim audit | Evidence ladder, contractor scorecard, consent form, case template, lifecycle boundary | Does not confer certification, legal compliance, or performance merely by publishing documents | 6 |

## Related-domain opportunities

| Related property | Independent useful viewpoint | Collaboration opportunity | Boundary |
|---|---|---|---|
| `Kubikel.co.id` | Indonesian cubicle system and commercial education | Share verified terminology, drawings, and evidence formats while each domain owns its own page intents | Do not suppress a Kubikel.id topic or cross-canonicalize domains merely because subjects overlap |
| `Cubicle.id` and `Cubicle.co.id` | English-term variants and independent project perspectives | Compare search language, user tasks, and product evidence | Same-domain rules remain local to each property |
| `toilet.kubikel.id`, `toilet.cubicle.id`, `toiletcubicle.co.id` | Specialist toilet-cubicle products and service journeys | Kubikel.id can route a qualified toilet reader after neutral selection and accessibility guidance | Verify each live offer; no automatic claim inheritance |
| `Phenolic.id` and `ToiletPhenolic.co.id` | Phenolic material and specialist toilet partitions | Link to deeper independently evidenced material/product explanations | Kubikel.id still owns its own material decision pages |
| `Partisi.co.id`, `Furnitur.co.id`, `Kaca.co.id`, `Kayu.co.id`, `Almini.id` | Adjacent partition, furniture, glass, wood, and aluminium systems | Use independent perspectives for interface and material research | Cross-domain overlap is not cannibalization |
| `Safety.co.id` and `Firesafety.co.id` | Safety governance and fire-system context | Coordinate evidence standards and expert-review gates | They do not approve a Kubikel.id project |

## Consolidation plan

1. Preserve the homepage URL but redraw it as a verified three-path gateway: office, toilet, and electrical.
2. Remove `/laman-contoh/` and `/2023/03/21/halo-dunia/` after checking backlinks/GSC; use 410 unless a genuine equivalent destination exists.
3. Remove default category, author, feed, comments, static admin/login, and REST snapshots from the indexable sitemap; retain only technically required public assets.
4. Build one canonical XML sitemap from final 200-status, indexable URLs; use absolute `https://kubikel.id/` locations.
5. Give every article one owner intent; commercial pages own verified offers, while knowledge pages own neutral decisions, diagnostics, calculations, and evidence.
6. Keep the three cubicle meanings in separate hubs after KBI-01 triage. Never place electrical operating instructions inside partition pages.
7. Replace placeholder links and verify the correct contact numbers, owners, form delivery, privacy handling, and specialist-domain destinations.
8. Remove unsupported rankings, universal safety/durability, 24/7, nationwide, warranty, price, rating, and testimonial claims unless dated records prove their exact scope.
9. Replace stock-looking project evidence with permissioned original photos, drawings, datasheets, certificates, inspection records, and limitations.
10. Do not create city, province, island, or “seluruh Indonesia” article variants. Geographic service claims belong only to verified commercial capability pages.

## Internal-link architecture

- KBI-01-01 is the editorial entry hub and routes readers to office KBI-03/04, toilet KBI-05/06, or electrical KBI-07 through KBI-10 before any commercial link.
- KBI-02 project briefs feed system-specific design pages, KBI-13 measurement, KBI-16 quote comparison, and KBI-18 contractor evidence.
- Office path: KBI-03 layout → KBI-04 performance/interfaces → KBI-11/12 materials/components → KBI-13 quantities → KBI-15 installation → KBI-17 maintenance.
- Toilet path: KBI-05 accessibility/layout → KBI-06 wet-area/hygiene → KBI-11/12 → KBI-13 → KBI-15 → KBI-17.
- Electrical path: KBI-07 fundamentals → KBI-08 specification → KBI-09 controlled installation/commissioning → KBI-10 operation/maintenance. Every page repeats the competent-person and current-site-procedure boundary.
- KBI-14 fabrication links backward to approved drawings and materials, forward to site installation, and laterally to KBI-18 evidence.
- KBI-16 commercial education links to a service route only when the relevant system, scope, evidence, and exclusions are clear.
- Each topic hub links to all six children; every child links upward and to only the lifecycle neighbors named in its catalog row.

## Evidence and editorial standards

1. Label repository observation, legal requirement, standard requirement, manufacturer claim, engineering judgment, measured site fact, and editorial hypothesis separately.
2. Recheck current official BPK/JDIH/BSN/Kemnaker/ESDM/PUPR sources and applicability at publication. Do not copy clause numbers, ratings, dimensions, or certificate duties from secondary summaries.
3. Electrical content requires qualified review. Never provide DIY design, relay-setting, switching, bypass, energized-work, fault-reset, arc-event approach, or energization instructions.
4. Electrical product claims require exact manufacturer/model, declared ratings, applicable edition, type/routine test evidence, environmental duty, nameplate/data sheet, and competent approval.
5. Accessibility and toilet layouts require current primary regulation, user-path review, site dimensions, fixture/door/hardware interfaces, and qualified approval. A generic diagram is not a compliance certificate.
6. Material claims require exact grade/construction, thickness, finish, edge treatment, exposure, test method, manufacturer data, and limitation. “Phenolic”, “PVC”, “glass”, “wood”, “safe”, “fireproof”, and “waterproof” are not enough.
7. Installation instructions identify drilling, cutting, dust, glass, sharp edges, lifting, work at height, hidden services, electrical proximity, occupied areas, and structural anchorage stop conditions.
8. Prices, coverage, lead times, stock, warranty, response time, and service availability are dated commercial facts with inclusions, exclusions, confirmation point, and source.
9. Reviews and case studies require consent, order/project linkage, date, scope, original evidence, constraints, changes, result, and limitations. Stock photos and anonymous copy do not prove experience.
10. Sustainability claims define lifecycle boundary, source, transport, fabrication loss, coatings/chemicals, cleaning, repair, service life, reuse, and disposal. Avoid “eco-friendly” without comparative evidence.

## First bounded publication cluster

Wave `W1-triage-and-safe-brief` contains 12 assets:

1. KBI-01-01 — central meaning and routing guide.
2. KBI-01-02 — office versus toilet versus electrical comparison.
3. KBI-02-01 — complete project-brief checklist.
4. KBI-03-01 — office-layout selection.
5. KBI-05-01 — toilet-compartment planning.
6. KBI-07-01 — electrical-cubicle fundamentals.
7. KBI-08-01 — electrical safety and professional boundary.
8. KBI-11-01 — partition-material selection framework.
9. KBI-13-01 — partition site-measurement checklist.
10. KBI-15-01 — partition site-readiness checklist.
11. KBI-16-01 — quote and scope comparison.
12. KBI-18-01 — contractor evidence checklist.

This cluster first prevents the site’s largest category error, then gives each audience a safe route and shared brief, material, measurement, readiness, quotation, and evidence tools. Publish the linked hub and spokes together. Monitor canonical indexation, impressions split by office/toilet/electrical intent, triage-path completion, checklist use, qualified inquiries by system, clarification/error rates, commercial-route clicks, and same-domain query overlap. Ranking alone is not success.

## Definition of done

- All 18 topics and 108 briefs have a published or explicitly deferred owner.
- Office, toilet, and electrical pages never equally satisfy the same query and never share unsafe generic recommendations.
- Default/utility/archive/REST routes are removed from indexation and one canonical sitemap matches live 200-status pages.
- Every accessibility, material, electrical, safety, commercial, testimonial, project, and environmental claim passes its evidence gate.
- Electrical pages are reviewed by competent specialists and never instruct unqualified switching, testing, energized work, or fault intervention.
- Product/service routes own verified current offers; educational pages own one bounded reader job.
- Publication metrics include indexation, reader task completion, qualified system-specific leads, errors/clarifications, evidence completeness, and cannibalization—not article volume alone.
