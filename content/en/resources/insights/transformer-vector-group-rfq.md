+++
title = "Transformer Vector Group RFQ: Phase and Neutral Checks"
description = "Clarify vector group, phase displacement, neutral availability, grounding, protection, and parallel-operation limits before ordering transformers."
image = "/images/resources/insights/transformer-vector-group-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-07-22T00:00:00Z
publishDate = 2026-07-22T00:00:00Z
readingTime = "8 min"
featured = false
+++

Vector group is a short code on a transformer datasheet, but it can decide whether the transformer fits the site. A buyer may request the correct kVA, voltage ratio, frequency, and enclosure, then still face late questions about phase displacement, neutral availability, grounding, relay inputs, meter wiring, or whether the new transformer can connect beside an existing one.

The short answer is: do not treat vector group as a catalogue default. The RFQ should state the required primary and secondary winding connection, clock-hour phase displacement, neutral terminal requirements, grounding interface, existing equipment constraints, and document evidence. Final selection must be confirmed by project drawings, utility requirements, local code, protection studies, supplier datasheets, factory test reports, and qualified electrical review.

This article helps procurement teams and EPC engineers ask better questions before ordering. It is not a substitute for the project electrical designer, utility reviewer, protection engineer, AHJ, or commissioning authority.

## What vector group controls in a real installation

Vector group notation usually combines winding connection letters and a clock-hour number that describes phase displacement between windings. Names such as Dyn11, Yyn0, or YNd1 are not just labels for the nameplate. They indicate practical interfaces: whether a neutral point is available, whether the secondary voltage has a phase shift compared with the primary, and how the transformer may behave with protection, metering, grounding, harmonics, and parallel operation.

For a new standalone load, the project designer may already define the vector group in the single-line diagram or technical specification. For a replacement, expansion, generator tie, solar or storage interface, or compact substation, the vector group can become a compatibility issue. If the buyer leaves it open, suppliers may quote different assumptions that cannot be compared on price alone.

For an [oil-immersed transformer](/product/oil-immersed/) or [dry-type transformer](/product/dry-type/), the vector group should be part of the same order basis as voltage ratio, frequency, tap range, insulation level where specified, impedance target if specified, enclosure, temperature monitoring, and test documentation.

## RFQ checklist for vector group and phase interfaces

The table below is not a universal design rule. It is a procurement checklist for finding missing information before drawings are frozen.

| RFQ item | Why it matters | What the buyer should provide or request |
| --- | --- | --- |
| Required vector group | Different connection groups can create different neutral availability and phase displacement. | State the vector group from the project specification, or ask the supplier to list the quoted assumption clearly. Do not accept "standard" without a code and drawing reference. |
| Supply and load voltage basis | Line-to-line and line-to-neutral requirements affect winding connection and neutral use. | Provide the single-line diagram, nominal voltages, frequency, system earthing concept, utility service data, and whether the secondary serves three-wire or four-wire loads. |
| Neutral terminal and loading | A neutral point may be needed for LV distribution, grounding, metering, protection, or auxiliary systems. | State whether the neutral terminal must be brought out, insulated, grounded, monitored, or connected to switchgear. Neutral sizing, current duty, and grounding method must follow project design. |
| Phase displacement and rotation | Phase shift matters when connecting to existing buses, generators, UPS systems, PV inverters, meters, or parallel transformers. | Ask for the clock-hour displacement, terminal marking, phase sequence assumption, and phase-check procedure before energization. |
| Existing transformer interface | A replacement or parallel addition must match more than kVA. | Provide existing nameplate data, vector group, impedance, tap range, voltage ratio, earthing, protection settings, and switchgear ratings for engineering review. See the [parallel transformer checklist](/resources/insights/parallel-transformer-operation-checklist/) when operation on a common bus is expected. |
| Grounding and protection | Winding connection affects zero-sequence paths, earth-fault behavior, relay inputs, and neutral treatment. | Link the vector-group request to the project grounding study, relay coordination, CT location, and utility rules. Our [neutral grounding RFQ checklist](/resources/insights/transformer-neutral-grounding-rfq/) covers that interface in more detail. |
| Switchgear and metering | Breaker wiring, CT/PT arrangement, phase indication, interlocks, and utility metering may assume a specific phase relationship. | Share the [switchgear](/product/switchgear/) single-line diagram, relay list, metering boundary, auxiliary voltage needs, and cable terminal arrangement. |
| Documentation evidence | The code in the quotation must appear consistently in final documents. | Request datasheet, nameplate draft, winding connection diagram, terminal marking drawing, routine test report, and any phase relationship evidence required by the project. |

## Do not separate vector group from grounding

A vector group question often becomes a grounding question. Buyers may ask for a neutral because the LV system needs four-wire loads, because the protection scheme needs a defined reference, because the utility requires a certain grounding method, or because downstream switchgear and metering were designed around it.

The supplier can quote a transformer with the requested winding connection, terminal arrangement, and documents. The supplier should not be expected to decide the project grounding philosophy from a one-line RFQ. Grounding, bonding, earth-fault protection, neutral conductor sizing, touch-voltage concerns, and utility approval must be confirmed by the project engineer and applicable local requirements.

If the RFQ says only "with neutral," it is incomplete. Say where the neutral is required, whether it is brought to a terminal box or LV bus, who supplies the grounding connection, whether removable links or test points are needed, and what drawings will show the arrangement.

## Replacement projects need existing nameplate data

Vector group is especially important when a plant replaces an old transformer, adds capacity near an existing transformer, or keeps part of the original switchgear. A new transformer with the same kVA and voltage ratio may still be unsuitable if the phase displacement, tap relationship, impedance, neutral arrangement, or protection interface differs from the existing system.

Before requesting a quotation, collect clear photos or records of the existing transformer nameplate, terminal marking, single-line diagram, grounding method, switchgear ratings, relay settings where available, and cable arrangement. If the existing nameplate is missing or unreadable, the project team may need field verification by qualified personnel before a purchase order is released.

For a [compact substation](/product/substation/), the same check should include the MV compartment, transformer compartment, LV incomer, metering, auxiliary power, and any future extension points. A factory-built package can still fail site acceptance if the phase relationship does not match the utility or downstream distribution design.

## Standards define language, but the project decides the answer

Standards help buyers and suppliers use a shared vocabulary, but they do not make one vector group correct for every market. [IEC 60076-1](https://webstore.iec.ch/en/publication/588) is a common reference for general power-transformer requirements where IEC specifications apply, and [IEC 60076-8](https://webstore.iec.ch/en/publication/605) is an IEC application guide that may be referenced by engineering teams. In IEEE-based projects, documents such as [IEEE C57.12.00](https://standards.ieee.org/standard/C57_12_00-2021.html) may form part of the transformer specification.

Those references are not interchangeable defaults. A project may be controlled by IEC, IEEE, ANSI, NEMA, GB/GB/T, utility rules, grid code, fire code, building code, owner standards, or local AHJ requirements. The RFQ should name the applicable market and project documents. The final vector group and neutral arrangement should be approved through drawings and reviewed with protection, grounding, metering, and commissioning requirements.

## RFQ wording buyers can adapt

"Please quote the transformer with vector group [insert project requirement] based on the attached single-line diagram and utility requirements. If the quoted design differs from the project specification, state the deviation clearly before technical review."

"Submit the winding connection diagram, terminal marking, phase displacement, neutral terminal arrangement, grounding interface, and nameplate draft for approval before manufacturing. Neutral grounding and protection logic remain subject to the project electrical design, local code, utility requirements, and AHJ review."

"For replacement, expansion, or parallel operation, review the attached existing transformer nameplate, switchgear data, tap range, impedance, voltage ratio, vector group, and protection information. Do not assume compatibility from kVA and voltage ratio alone."

"Final suitability must be confirmed by approved drawings, supplier datasheet, applicable project standard, factory test report, site phase checks, protection settings, and commissioning procedures by qualified personnel."

## A practical release rule

Do not release a transformer order while vector group is hidden inside supplier default wording. The buyer should be able to point to one approved place where the winding connection, clock-hour displacement, neutral terminal, grounding interface, existing-equipment constraint, and document evidence are all stated.

That single check protects real projects. It helps procurement compare equivalent quotations, helps engineers catch phase and grounding conflicts early, and gives the commissioning team a clear basis for site verification before the transformer is energized.
