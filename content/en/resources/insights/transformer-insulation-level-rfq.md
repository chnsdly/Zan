+++
title = "Transformer Insulation Level RFQ: BIL and Withstand Checks"
description = "Clarify Um, BIL or impulse level, power-frequency withstand, neutral insulation, arrester coordination, and test evidence before ordering."
image = "/images/resources/insights/transformer-insulation-level-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-08-04T00:00:00Z
publishDate = 2026-08-04T00:00:00Z
readingTime = "8 min"
featured = false
+++

An insulation-level mistake rarely looks urgent in an early transformer RFQ. The inquiry may list "11 kV/0.4 kV," "33 kV/11 kV," or "IEC standard" and move straight to capacity, loss, impedance, and delivery. Yet the insulation level decides which overvoltages the transformer terminals and internal insulation are expected to withstand under the project standard basis.

The short answer is: a transformer RFQ should define the highest voltage for equipment, rated insulation level or BIL terminology, power-frequency withstand requirement, lightning or switching impulse requirement where applicable, neutral-terminal insulation, tap and bushing insulation assumptions, arrester and switchgear coordination boundary, and the exact test evidence required before shipment. Final values must come from the project specification, utility requirement, insulation coordination study, local code, applicable market standard, supplier datasheet, and factory test report.

This guide helps overseas buyers, EPC teams, factories, mines, renewable sites, and commercial-building projects ask better questions before ordering [oil-immersed transformers](/product/oil-immersed/) or [dry-type transformers](/product/dry-type/). It does not replace the electrical designer, utility reviewer, registered engineer, protection specialist, or local AHJ.

## Insulation level is not just the nominal voltage

Nominal voltage tells the buyer what system the transformer connects to. Insulation level tells the project what dielectric stress the transformer is specified and tested against. The two are related, but they are not the same procurement line.

For example, a quotation that only says "medium-voltage side: 11 kV" may still leave several important questions open. What is the highest system voltage used by the project? Which standard vocabulary applies? Are the high-voltage, low-voltage, and neutral terminals assigned the same insulation requirement? Are external clearances affected by altitude or installation layout? Are surge arresters included, installed elsewhere, or supplied by another party? Are routine, type, or special dielectric tests required by the project documents?

Those answers change datasheets, bushings, clearances, test reports, drawing approvals, and sometimes price or delivery. They should be clarified before comparing quotations.

## RFQ matrix for insulation-level checks

Use this matrix as a purchasing and technical clarification tool. It is not a table of design values.

| RFQ item | What the buyer should state or request | Why it matters |
| --- | --- | --- |
| Applicable market and standard basis | Name the project basis, such as IEC, IEEE/ANSI, GB/GB/T, utility specification, national energy rule, or owner standard where applicable. | IEC and North American wording are not interchangeable. The project decides which evidence and terminology are accepted. |
| Highest voltage for equipment | State the highest voltage for equipment or equivalent requirement for each winding, not only the nominal system voltage. | Insulation coordination and dielectric tests are normally tied to the equipment voltage class defined by the applicable standard. |
| Rated insulation level or BIL | Request the specified lightning impulse withstand level, BIL, power-frequency withstand, and any switching impulse requirement where applicable. | A supplier cannot safely infer the required withstand levels from a short voltage ratio alone, especially for export projects. |
| Terminal-by-terminal scope | Confirm requirements for HV line terminals, LV terminals, neutral bushing, tertiary winding if any, cable box, busduct interface, and tap-changer terminals. | Neutral and auxiliary terminals may not need the same insulation level as line terminals, but that decision belongs to the project design. |
| External clearance assumptions | Ask whether clearances in air, bushing height, phase spacing, cable termination spacing, and altitude correction are included in the supplier design basis. | A transformer can meet a factory test requirement yet still need layout review for the installed substation, room, or cable compartment. |
| Surge arrester boundary | State whether arresters are supplied on the transformer, in the MV switchgear, inside a compact substation, or by the EPC/utility. | Arrester selection and location affect insulation coordination but should be confirmed by the project study, not guessed by procurement. |
| Test evidence | Request the datasheet, nameplate data, dielectric test report, type-test evidence if required, special-test scope, and deviation list. | The RFQ should make clear what will be proven by routine factory tests and what remains a project or site responsibility. |

## Use the correct vocabulary for the market

In IEC-style projects, buyers will often see "highest voltage for equipment" and "rated insulation level" language. [IEC 60076-3](https://webstore.iec.ch/en/publication/601) addresses insulation levels, dielectric tests, and external clearances in air for power transformers within its stated scope. [IEC 60071-1](https://webstore.iec.ch/en/publication/59657) addresses insulation coordination principles for high-voltage AC systems above its stated threshold and explains that selected withstand voltages are associated with highest voltage for equipment for coordination purposes.

In IEEE/ANSI-style projects, buyers may see BIL, power-frequency withstand, low-frequency dielectric tests, and related transformer categories. [IEEE C57.12.00-2021](https://standards.ieee.org/standard/C57_12_00-2021.html) is an official IEEE reference for general requirements for liquid-immersed distribution, power, and regulating transformers within its scope.

The procurement problem starts when these vocabularies are mixed loosely. "IEC transformer with ANSI BIL" may be possible only if the project specification defines exactly what is meant, which tests apply, and which documents the supplier must provide. Do not assume that IEC, IEEE, ANSI, GB/T, DOE, EU, utility, or local terms lead to the same values.

## Coordinate insulation level with arresters and switchgear

Insulation level should not be selected in isolation from the rest of the system. The same project may include [medium-voltage switchgear](/product/switchgear/), cable terminations, overhead line exposure, cable-fed service, surge arresters, metering transformers, capacitor equipment, and a [compact substation](/product/substation/) enclosure. Each interface can affect overvoltage exposure, clearances, grounding, and documentation.

The supplier can state the transformer insulation level and test evidence for the unit it supplies. The project engineer or utility reviewer should confirm whether that level is coordinated with the system, protection devices, arrester rating and location, cable insulation, switchgear ratings, and grounding method. The [surge arrester RFQ checklist](/resources/insights/transformer-surge-arrester-rfq/) is a useful companion when arrester scope is unclear.

Avoid RFQ wording such as "standard arresters included" or "standard insulation level." Those phrases invite different assumptions. A better RFQ names the applicable standard basis, required insulation level, arrester ownership, installation position, earth connection, and evidence required for the final approval file.

## Pay attention to neutral and tap details

The neutral terminal is often treated as a small accessory until drawings are reviewed. For a star-connected winding, the project may need a brought-out neutral, an insulated neutral bushing, a neutral earthing terminal, a removable link, or no accessible neutral at all. The insulation level of that neutral terminal must follow the project grounding and protection design, not a generic catalogue note.

This also connects to vector group and earthing decisions. If the project has not yet fixed the [transformer vector group](/resources/insights/transformer-vector-group-rfq/) or neutral grounding method, the insulation-level discussion is incomplete. A buyer should not ask the factory to decide those details from the capacity and voltage ratio alone.

Tap arrangement matters too. Off-circuit taps, on-load tap changers, reconnectable windings, and auxiliary windings may introduce separate insulation or test questions. The RFQ should state the tap range, tapping side, operating method, and required test/document basis. Final treatment should be confirmed by the supplier datasheet and approved project drawings.

## What to request before release

Before manufacturing release, request a datasheet that lists the voltage ratio, highest voltage for equipment or market equivalent, rated insulation level or BIL, dielectric test basis, bushing details, neutral arrangement, tap data, arrester scope, and deviations. The outline drawing should show bushings, phase spacing, cable-box or busduct interface, and any transformer-mounted arresters.

Before shipment, the documentation package should match the approved RFQ. Typical evidence may include nameplate data, final datasheet, outline and wiring drawings, dielectric routine test report, type-test evidence where the specification requires it, accessory schedule, packing list, and unresolved-deviation log. The [transformer FAT and shipment checklist](/resources/insights/transformer-fat-shipment-checklist/) can help structure that handover.

After site installation, the insulation-level discussion is not finished. Cable testing, grounding checks, switchgear readiness, arrester installation, protection settings, and energization permission remain site responsibilities. Use the [pre-energization checklist](/resources/insights/transformer-pre-energization-checklist/) to keep those items connected.

## RFQ wording buyers can adapt

"Quotation shall state the applicable insulation-level standard basis for each transformer winding and terminal, including highest voltage for equipment or market equivalent, rated insulation level, BIL or impulse withstand terminology where applicable, power-frequency withstand requirement, and neutral-terminal insulation treatment."

"Supplier shall identify whether surge arresters, cable box, busduct interface, neutral bushing, tap-changer terminals, and auxiliary wiring insulation are included in the supplied scope. Items outside supplier scope shall be listed as project or EPC responsibilities."

"Dielectric test reports, type-test evidence where required, nameplate data, final datasheet, outline drawing, and deviation list shall be submitted according to the project specification before shipment."

"Final insulation coordination, arrester selection, grounding, clearances, protection settings, site tests, and energization approval remain subject to the project documents, local code, utility requirements, AHJ review, supplier documents, and qualified engineering judgment."

## A practical decision rule

A transformer quotation is not ready for technical comparison until the buyer can see which insulation vocabulary applies, which withstand levels are required for each terminal, what will be tested by the supplier, and which coordination decisions remain with the project engineer or utility.

If those items are missing, pause the price comparison and ask for clarification. Insulation level is not a marketing feature; it is a project-specific boundary between transformer design, system overvoltage risk, switchgear interface, arrester coordination, and final acceptance evidence.
