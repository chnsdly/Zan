+++
title = "Off-Circuit Tap Changer Settings: RFQ and Startup Checks"
description = "Use this buyer checklist to confirm transformer off-circuit tap settings, documents and safe handoffs before release or energization."
image = "/images/resources/insights/transformer-off-circuit-tap-settings.webp"
author = "Hengli Engineering Desk"
date = 2026-08-27T00:00:00Z
publishDate = 2026-08-27T00:00:00Z
readingTime = "7 min"
featured = false
+++

An off-circuit tap changer is often treated as a minor nameplate detail. It is not. Its selected position can affect the transformer ratio presented to the site, while the wrong assumption can leave procurement, installation and commissioning teams talking about different voltage bases.

The practical rule is simple: before manufacture release and again before first energization, identify the approved tap position, the document that defines it, the person authorized to confirm it, and the evidence that records the final position. An off-circuit tap changer must not be adjusted on an energized transformer. The exact isolation, grounding, access and verification procedure must follow the supplier manual, project switching procedure, local electrical-safety rules and qualified personnel.

This guide helps buyers turn that requirement into RFQ and handover questions. It does not select a tap position, replace a voltage study, or authorize field work. Final suitability remains subject to project drawings, utility requirements, the final datasheet and test report, applicable standards, local code and the responsible electrical engineer.

## Start with the system voltage basis

Taps give the project a defined adjustment range around a rated winding ratio. They do not prove that the supply will always remain at one voltage, nor do they replace an [on-load tap changer decision](/resources/insights/when-factory-needs-on-load-tap-changing-transformer/) where active regulation may be required. A de-energized or off-circuit tap changer is normally used only after the transformer has been isolated and made safe under the project procedure.

For a new installation, the approved single-line diagram, utility connection information and transformer data sheet should state the nominal supply and load-voltage basis. For a replacement, add the existing nameplate, recorded operating voltage where available, feeder arrangement and any approved study. Do not ask a bidder to infer the required setting from a purchase-order description such as “11/0.4 kV.”

The same discipline matters when the transformer feeds a factory with motors, a commercial LV board, a packaged substation, generator-backed loads or an inverter-based system. The selected tap can affect the voltage seen downstream, but it is only one part of a system that also includes source conditions, cable or bus voltage drop, loading, protection, earthing and operating limits. Those interactions require the project design review.

## What to state in the RFQ

Buyers do not need to prescribe a tap position without the design basis. They do need to make the decision visible and assign its owner. The table below is a procurement and handover matrix, not a universal adjustment instruction.

| Item to control | What to ask for | Why it prevents confusion |
| --- | --- | --- |
| Rated ratio and tap range | State the specified HV/LV rated voltages, frequency, tap range, step arrangement and whether the changer is off-circuit or on-load. Ask the bidder to identify every assumption. | A quoted range may look comparable while the reference voltage, number of positions or changer type differs. |
| Approved position | Identify the drawing, voltage schedule or engineering instruction that will define the initial position, plus the revision and decision owner. | “Normal tap” or “factory setting” is not an approved site setting. |
| Position reference | Request a clear position-number convention, nameplate draft and changer/terminal drawing. Confirm how the position is shown on the equipment and in documents. | Position 1, centre or “+/-” wording can be misunderstood if the reference is not stated. |
| Change authority and safety boundary | Require the supplier manual to state the equipment-specific precautions. Identify who owns isolation, grounding, access control, switching, verification and records. | A transformer supplier can explain its equipment; the project must still control the site work and energization process. |
| Factory and shipment records | Request the as-tested tap position, routine test report, nameplate data, wiring/connection information and any required release records for the exact unit. | The installation team needs a traceable starting point, not a catalogue statement. |
| Site acceptance record | Define whether the position, seals or locks, terminal condition and associated documents must be checked before energization, and who signs the record. | It prevents a late mismatch between factory paperwork, field configuration and the switching plan. |

For a package that includes [oil-immersed transformers](/product/oil-immersed/), [dry-type transformers](/product/dry-type/) or [switchgear](/product/switchgear/), make the tap-setting decision visible in the package interface list. The MV feeder, transformer ratio, LV board and metering/protection documents should use the same approved voltage basis. A panel supplier should not have to infer it from a transformer quotation, and a transformer supplier should not be expected to set protection or utility requirements.

## Four checks before a purchase order is released

### 1. Separate a design choice from a factory default

Ask the bidder to state the position used for factory tests and shipment, but do not confuse that statement with the intended final operating position. The project engineer may specify an initial position before manufacture, at installation, or after the latest network data is issued. Each case should have a controlled document and a named approver.

If the project needs options, list them as options. Ask how each option changes the voltage ratio, drawings, tap-position markings, documents, price or programme. It is safer than accepting an undefined “standard tap range” and discovering the interpretation during site work.

### 2. Keep ratio, vector group and neutral interfaces together

The tap question does not stand alone. The approved voltage ratio should agree with the connection symbol, phase relationship, neutral arrangement and terminal markings. The [vector-group RFQ guide](/resources/insights/transformer-vector-group-rfq/) explains why phase displacement and neutral assumptions need their own documented checks.

For a replacement or expansion, collect the existing transformer nameplate and the current single-line diagram. Compare the tap data, vector group, impedance where specified, neutral/earthing interface and switchgear connection against the approved project basis. Similar kVA and nominal voltages do not by themselves establish interchangeability or parallel-operation suitability.

### 3. Make the record usable at site

The handover pack should let a qualified commissioning team trace one answer: what position is installed, why it was selected, and where the equipment-specific procedure is found. At minimum, retain the final data sheet, approved position instruction, nameplate draft or photo, supplier manual, factory records required by the contract, latest single-line diagram and site inspection record.

Use the [nameplate-review checklist](/resources/insights/transformer-nameplate-review/) before shipment to make sure voltage, tap data and changer type match the approved documentation. If a later project revision changes the intended position, control it as a design change rather than annotating a packing list or sending an informal message to the site.

### 4. Treat any field adjustment as controlled electrical work

This article is not a switching procedure. The correct procedure depends on the transformer design, connected system, supplier instructions and the applicable safety framework. In the United States, for example, [OSHA’s hazardous-energy-control rules](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147) address lockout/tagout within their stated scope; they are not a global procedure or a substitute for project rules.

Before any authorized adjustment, the responsible team should confirm the approved work method, isolation and grounding requirements, stored-energy considerations, access controls, competent-person authorization, inspection requirements and return-to-service process. Never rely on a generic online sequence. The equipment manufacturer’s instructions and local requirements govern the applicable details.

## Pre-energization handoff: a decision rule

Use this short release rule after installation or a controlled setting change:

| Question | Release only when the answer is clear |
| --- | --- |
| Which tap position is intended? | It is stated in a current approved project document, with a named technical owner. |
| What position is actually installed? | Qualified personnel have checked and recorded it using the supplier’s equipment-specific documentation and project process. |
| Do the documents agree? | The data sheet, nameplate/position convention, single-line diagram, supplier records and site record have no unresolved conflict. |
| Is system readiness confirmed? | The project’s transformer, cable/bus, switchgear, protection, grounding, utility and energization prerequisites are closed by the responsible parties. |

This is not a substitute for a commissioning checklist. It is a hold point that keeps the tap-position question from being lost between procurement and startup. The broader [pre-energization checklist](/resources/insights/transformer-pre-energization-checklist/) should still be completed as applicable to the actual installation.

## Standards and manuals: use the right hierarchy

[IEC 60076-1](https://webstore.iec.ch/en/publication/588) is a general power-transformer reference for projects using the IEC framework. In North American maintenance work, [ANSI/NETA MTS](https://www.netaworld.org/standards/ansi-neta-mts) describes maintenance testing specifications within its stated scope. These resources can help procurement teams use consistent language, but neither one chooses a tap position for a particular site.

The applicable market and project specification may instead be governed by IEC, IEEE, ANSI, NEMA, GB/GB/T, utility rules, building and fire codes, or another local authority’s requirements. The final answer should come from the approved design, current system information, supplier documentation, relevant test records and qualified engineering review.

## RFQ wording buyers can adapt

> State the rated voltage ratio, frequency, tap range, step arrangement, tap-position reference and tap-changer type. Identify the factory test/shipment position and every bidder assumption. Do not treat a factory position as the approved final site setting.

> Before manufacture release, submit the data sheet, nameplate draft, winding/terminal documentation, tap-changer operating information and factory test documentation required by the contract. The purchaser will identify the approved initial tap position through controlled project documents.

> Any site adjustment, isolation, grounding, inspection and energization activity is subject to the supplier manual, approved switching procedure, applicable standards and local safety rules, utility/AHJ requirements where applicable, and qualified personnel. The supplier shall state any equipment-specific prerequisites or limitations.

The buyer’s goal is not to operate the changer from an RFQ. It is to make one small but consequential interface traceable from design through factory release to safe site commissioning.
