+++
title = "Data Center Transformer RFQ: Define A/B Paths First"
description = "A practical RFQ guide for aligning data center transformer, switchgear, UPS and generator interfaces before price comparison."
image = "/images/resources/insights/data-center-transformer-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-08-17T00:00:00Z
publishDate = 2026-08-17T00:00:00Z
readingTime = "8 min"
featured = false
+++

For a data center, a transformer quotation is incomplete if it only names kVA, voltages, and a price. The buyer first needs to show how each proposed transformer fits the intended utility, generator, UPS, switchgear, and critical-load paths. Without that boundary, two apparently similar offers may support very different maintenance and outage assumptions.

The practical starting point is an approved or clearly marked preliminary single-line diagram. It should identify the utility point of supply, transformer terminals, MV and LV switchgear, bus sections, UPS input and output, generator/ATS or paralleling boundary where applicable, critical and non-critical loads, and the intended A and B distribution paths. The resulting RFQ helps suppliers quote a defined interface; it does not certify a facility topology or replace the work of the design engineer, utility, AHJ, commissioning authority, or other qualified project parties.

This guide is for owners, EPC teams, consulting engineers, and procurement groups sourcing [oil-immersed transformers](/product/oil-immersed/), [dry-type transformers](/product/dry-type/), [switchgear](/product/switchgear/), or a packaged substation for a data center or similarly critical facility.

## Start with the required service outcome

Terms such as *A/B*, *redundant*, *concurrently maintainable*, and *fault tolerant* should not be copied into an RFQ as marketing labels. They need an agreed project definition: which critical load must remain supported, under which planned maintenance or credible fault condition, and which devices, paths, controls, and operating procedures are included in that statement.

For example, two transformer rooms do not automatically create two independent critical-power paths. They might share an upstream feeder, a bus tie, a protection zone, a fuel or control dependency, or a maintenance isolation that changes the outcome. Conversely, a project may intentionally use one transformer path for non-critical building load and a different architecture for IT load. The one-line diagram and operating philosophy, not equipment count alone, should govern the quotation.

The U.S. Department of Energy's [data center design guide](https://www.energy.gov/sites/default/files/2024-07/best-practice-guide-data-center-design_0.pdf) describes the electrical distribution path as a system involving utility service, switchgear, alternate sources, UPS equipment, and other components. That is a useful procurement reminder: transformer selection has to be reviewed with its connected system. If a project uses Uptime Institute terminology, use the owner’s written target and approval route; the Institute explains that its classifications are performance-based and that certification evaluates the full facility design and operation, not an individual transformer purchase ([Uptime Institute](https://connect.uptimeinstitute.com/tier-certification)).

## RFQ matrix for A/B transformer and switchgear interfaces

Use this matrix to mark confirmed information, bidder assumptions, and items owned by another project party. It is a procurement tool, not a protection or availability study.

| Interface | What the buyer should state or request | Why it changes the quote |
| --- | --- | --- |
| Critical-load objective | Define the critical-load boundary, required operating modes, phased-load plan, and whether the request is for an owner-defined resilience objective rather than a certification claim. | Prevents a transformer arrangement being described as “redundant” without a documented system condition. |
| Utility and source boundary | Provide the available point of connection, service voltage/frequency, utility documents available to date, source fault information when released, and ownership boundary. | Transformer ratio, insulation basis, protection interfaces, metering, and switchgear scope may depend on utility conditions. |
| A and B electrical paths | Submit the controlled one-line diagram showing each path from source to intended load, normal-open/normal-closed ties, common points, and any intentional crossover. | Suppliers need to see whether equipment feeds separate boards, bus sections, UPS inputs, or shared distribution. |
| Transformer duty and interfaces | State rating basis, voltage, vector group, neutral arrangement, tap requirement, impedance basis, cooling/environment, terminal or busduct interface, and expected operating modes. | These data affect physical arrangement and compatibility, but final values require the project study and approved datasheet. |
| Switchgear, UPS, generator and transfer boundary | Identify incoming and outgoing panels, breakers, bus ties, UPS input/output, generator/ATS/paralleling equipment where applicable, and the party responsible for each control or interlock interface. | A gap can leave a transformer supplied without the required cable, bus, control, metering, or interlock scope. |
| Isolation and maintenance plan | State planned isolation points, bypasses if any, access limits, switching authority, and the intended maintenance scenario to be reviewed. | Maintainability is an installed-system and operating-procedure question, not a catalogue feature. |
| Protection, metering and controls | Provide available CT/VT, relay, breaker, trip, communications, BMS/DCIM, alarm, and time-synchronization requirements. | Ratios, terminal lists, communication ownership, and relay settings must match the final protection and controls design. |
| Evidence and approval | Request drawings, deviation list, outline/interface data, wiring and terminal lists, factory records, manuals, and named drawing-review hold points. | Lets the buyer compare evidence and assumptions before manufacturing is released. |

For the utility boundary, use the [utility-connection transformer RFQ guide](/resources/insights/utility-connection-transformer-rfq/) alongside this matrix. For transformer-to-panel data, the [short-circuit current and switchgear rating checklist](/resources/insights/transformer-short-circuit-current-switchgear-rating/) explains why transformer data must be reconciled with the project fault study rather than inferred from a product family.

## Keep equipment scope separate from topology responsibility

A transformer supplier can quote the transformer, accessories, cable box or bus interface, outline data, wiring terminals, and specified factory records. A switchgear supplier can quote the panels, breakers, bus, CTs/VTs where specified, interlocks, and panel test evidence. Those are meaningful deliverables, but neither scope alone proves that the completed site achieves its desired continuity outcome.

The RFQ should therefore identify an explicit owner for the following interfaces:

- utility or campus source data, transformer ratio and tap basis;
- final short-circuit, protection coordination, grounding, arc-flash, harmonics, and load-flow studies;
- generator, UPS, ATS, bus-tie, load-shedding, and re-transfer logic;
- BMS/DCIM signals, remote controls, cybersecurity and communications requirements where applicable;
- civil, fire, ventilation, containment, seismic, cable installation, site testing, and energization release.

This separation is particularly important when transformers, UPS systems, generators, and switchgear come from different packages. Require each bidder to state assumptions and exclusions in a deviation schedule. The [transformer quotation comparison guide](/resources/insights/transformer-quotation-comparison/) can help the procurement team compare those schedules instead of comparing a single headline price.

## Ask for an interface pack before manufacturing release

Before the equipment configuration is frozen, collect a small, controlled document pack. The aim is to expose conflicts while physical changes are still manageable.

1. Latest one-line diagram with document status and revision.
2. A/B path and load-boundary narrative, including normal, maintenance, generator, and restoration modes that the project wants reviewed.
3. Transformer and switchgear datasheets identifying values that are confirmed, preliminary, or offered as options.
4. Transformer outline drawing, terminal or cable-box drawing, busduct arrangement if relevant, shipping and installation data, and access requirements.
5. Panel single-line, GA, wiring diagrams, terminal lists, CT/VT schedule, and proposed interlock/controls boundary.
6. A named register for open utility comments, protection-study inputs, BMS/DCIM requirements, and approval hold points.

Do not ask a supplier to fill unknown system values with a typical data-center design. A legitimate option can be quoted, but it should state what changes between options and who confirms the final choice. For physical transformer interfaces, the [cable-box RFQ checklist](/resources/insights/transformer-cable-box-rfq/) is useful when cable entry, bushing arrangement, busduct, or termination access is still open.

## RFQ clauses buyers can adapt

> The purchaser will issue the available single-line diagram and identify the intended critical-load boundary, A/B distribution paths, normal and contingency operating assumptions, utility boundary, and project approval route. Any preliminary information shall be marked as preliminary.

> The bidder shall state the complete offered supply boundary for transformer equipment, associated switchgear where offered, terminals, cable or bus interfaces, accessories, controls, drawings, factory records, and all exclusions. Submit a separate deviation and assumptions schedule before order confirmation.

> The bidder shall not claim facility redundancy, concurrent maintainability, fault tolerance, Tier classification, protection coordination, or final system availability solely from equipment configuration. These outcomes remain subject to the approved project design, system studies, operating procedures, local requirements, and the responsible engineering and certification process, where applicable.

> Before manufacture release, submit the final datasheet, drawings, terminal/wiring information, interface schedule, test plan and report scope for the exact quoted configuration. Values related to fault level, protection, grounding, harmonic performance, site conditions, cable installation, fire measures, site tests, and energization shall be confirmed by the project documents and qualified parties.

## Standards and evidence: use the applicable route

[IEC 60076-1](https://webstore.iec.ch/en/publication/588) is a common general reference for power transformers when an IEC transformer standard basis is specified. It does not decide a data center’s topology, utility acceptance, protection settings, building fire rules, or site commissioning scope. Other projects may use IEEE, ANSI, local utility, national code, owner, or AHJ requirements.

The market and project documents decide the applicable standard route. Treat factory test reports as evidence for the supplied equipment under its specified test basis; they do not replace installed-system studies, cable work, commissioning tests, switching procedures, or energization authorization.

## A practical release rule

Do not award a “data center transformer” package until the bidder can show what it supplies, what A/B path or common point it connects to, which assumptions remain open, and which project party closes them. That is enough for procurement to make a fair comparison without pretending that a transformer quotation is a complete data-center design.
