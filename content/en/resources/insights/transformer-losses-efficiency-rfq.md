+++
title = "Transformer Losses and Efficiency: RFQ Checks for Buyers"
description = "Compare no-load loss, load loss, efficiency rules, test reports, and lifecycle assumptions before ordering a distribution transformer."
image = "/images/resources/insights/transformer-losses-efficiency-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-07-13T00:00:00Z
publishDate = 2026-07-13T00:00:00Z
readingTime = "9 min"
featured = false
+++

A transformer with a lower purchase price is not always the lower-cost purchase. A transformer advertised as "high efficiency" is not automatically the right purchase either. For factories, commercial buildings, EPC projects, mines, industrial parks, and renewable-energy facilities, the useful question is more specific: what loss values, efficiency rules, test evidence, and operating assumptions should be compared before the order is released?

The short answer is: ask for the no-load loss, load loss, reference temperature or test basis, applicable market efficiency requirement, test report evidence, and the load profile used for any lifecycle-cost comparison. Final acceptance still depends on the approved datasheet, factory test report, project specification, applicable local regulation, utility requirement, and qualified engineering review.

This article does not publish universal loss values. Losses vary by rating, voltage, insulation system, impedance, cooling method, material choice, energy-efficiency class, and applicable standard. The goal is to help buyers write a clearer RFQ and avoid comparing quotations that are not technically equivalent.

## Start with the two losses that drive most comparisons

Transformer loss discussions often become vague because "efficiency" is used as a shortcut. In procurement, it is better to separate the main loss items.

No-load loss is present whenever the transformer is energized, even when downstream load is low. It is closely linked to the magnetic core and is important for equipment that remains energized for long hours, backup systems with light average loading, building distribution, and sites where standby consumption matters.

Load loss increases with load current and is affected by winding design, conductor material, reference temperature, stray losses, and the actual loading pattern. It matters in heavily loaded industrial plants, process lines, mines, pumping systems, and projects where the transformer operates near a high utilization level for long periods.

Neither value should be accepted as a slogan. A buyer comparing an [oil-immersed transformer](/product/oil-immersed/), a [dry-type transformer](/product/dry-type/), or a [compact substation](/product/substation/) should request model-specific data for the exact rating and voltage ratio being quoted. Series labels can help with early screening, but the order should be controlled by the final datasheet and required test evidence.

## Loss and efficiency schedule for the RFQ

The following schedule is not a design calculation. It is a procurement checklist that helps the buyer, engineer, and supplier compare the same technical basis.

| RFQ item | What to ask for | Why it matters |
| --- | --- | --- |
| Applicable market and project rule | State the country or market, utility requirement, project specification, and whether IEC, IEEE, ANSI, GB/GB/T, DOE, EU Ecodesign, or another rule applies. | Efficiency requirements are not global. A compliant offer in one market may not satisfy another market's regulation or utility specification. |
| Exact transformer scope | Confirm kVA/MVA, voltage ratio, frequency, phase, vector group, impedance target, tap range, cooling method, enclosure, accessories, and installation environment. | Losses cannot be compared fairly if one supplier includes a different impedance, cooling arrangement, enclosure, or accessory package. |
| No-load loss | Request the guaranteed or declared no-load loss for the exact rating, with the test basis and tolerance or acceptance rule stated. | This loss is present whenever the transformer is energized, so it can dominate lightly loaded or continuous standby applications. |
| Load loss | Request load loss at the specified reference condition and identify whether auxiliary losses are included or separate. | This value affects high-utilization projects and lifecycle-cost calculations. It should match the specification's test and temperature basis. |
| Efficiency or MEPS evidence | Ask how the quoted design meets the applicable minimum energy performance standard, if one applies. | A general "high-efficiency" claim is weaker than a documented design basis tied to the target market and project rule. |
| Operating load profile | Provide measured demand data if available, or at least expected average load, peak load, duty cycle, seasonal variation, and expansion plan. | The same loss split can perform differently in a lightly loaded building and a heavily loaded industrial line. |
| Test report and acceptance | Define the required routine tests, optional witnessed test, language of documents, and how deviations will be handled before shipment. | Loss claims need traceable evidence. Receiving-stage checks are easier when the datasheet, nameplate, and report format were agreed before manufacturing. |
| Commercial evaluation method | If evaluating lifecycle cost, state the energy price, evaluation period, loading assumption, discount method, and responsibility for the calculation. | Without a written method, bidders may use different assumptions and make lifecycle savings appear more certain than they are. |

For projects where site conditions may affect cooling or loading assumptions, send the loss schedule together with the [site-condition RFQ checklist](/resources/insights/site-conditions-transformer-rfq/). Efficiency data alone cannot correct an RFQ that omits ambient temperature, altitude, ventilation, dust, moisture, enclosure requirements, or access constraints.

## Efficiency rules depend on the market

Standards and regulations are useful only when they are applied to the correct project. In the United States, distribution transformer efficiency requirements are addressed through [10 CFR Part 431, Subpart K](https://www.ecfr.gov/current/title-10/chapter-II/subchapter-D/part-431/subpart-K) where that regulation applies. In the European Union, transformer ecodesign requirements are associated with [Commission Regulation (EU) No 548/2014](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32014R0548) and later amendments where applicable. Projects that specify IEC practice may also reference documents such as [IEC 60076-1](https://webstore.iec.ch/en/publication/588) for general power transformer requirements, together with other parts or project-specific clauses.

These references should not be treated as interchangeable. A buyer importing equipment into a specific country should ask the EPC, local consultant, utility, customs adviser, or AHJ which rule applies to that installation. If the project specification names a standard, the RFQ should quote that exact requirement rather than using broad phrases such as "international standard" or "high efficiency."

## Match the loss split to the operating pattern

Two transformers can have similar headline efficiency but different loss behavior. One design may reduce no-load loss more aggressively; another may prioritize lower load loss. Which design is better depends on how the site operates.

For a commercial building, public facility, or standby-fed area that remains energized around the clock but carries modest average load, no-load loss may deserve close attention. For a factory production line, mine, pumping station, or process plant with long periods of high load, load loss may have a larger commercial impact. For a project with future expansion, today's average load may not represent the intended service life, so the evaluation should document both the initial and planned operating cases.

The safest procurement practice is to give suppliers the real operating context and ask them to identify the loss basis in the quotation. Do not rely on a single efficiency percentage unless the load point, test method, and compliance basis are clear.

## Product type changes the questions, not the need for evidence

Oil-immersed transformers are often considered for outdoor yards, industrial power distribution, utility interfaces, and larger capacity projects. Buyers should confirm the quoted loss values together with cooling arrangement, radiator clearance, oil containment, fire separation, noise requirement, and maintenance access as required by the project.

Dry-type transformers are often considered for indoor electrical rooms, commercial buildings, data centers, hospitals, transit, and other oil-free indoor applications. Their loss and efficiency comparison should be reviewed together with room ventilation, enclosure protection, ambient temperature, dust, humidity, acoustic limits, and fire rules. The article on [temperature rise and service life](/resources/insights/insights-2/) is a useful companion because thermal behavior and loss evaluation are connected, but they are not the same review.

Compact substations combine transformer, enclosure, medium-voltage switching, low-voltage distribution, ventilation, cable interfaces, and sometimes metering. A compact layout may be efficient from a civil-work and installation standpoint, but the transformer loss values still need to be identifiable in the datasheet. Switchgear auxiliary power, anti-condensation heaters, fans, meters, and control devices should be stated separately where they affect the project energy review.

## Bid comparison mistakes to avoid

Pause for clarification when any of these points are unclear:

- one quotation lists no-load and load loss, while another only says "low loss";
- the loss value is given without the exact rating, voltage ratio, or reference basis;
- one supplier includes enclosure fans, temperature controllers, surge arresters, or monitoring devices and another does not;
- the project requires a specific DOE, EU Ecodesign, IEC, IEEE, GB/T, ANSI, utility, or local rule, but the quotation only says "standard";
- the lifecycle-cost saving is calculated from assumptions that the buyer did not provide or approve;
- the test report format, witnessed test requirement, or acceptance tolerance is left until after production.

These are procurement risks, not just engineering details. They can affect bid evaluation, shipping approval, commissioning, and commercial acceptance.

## RFQ wording buyers can adapt

Use wording that separates confirmed requirements from open assumptions:

"Please quote the transformer based on the attached rating, site conditions, and applicable project specification. Provide no-load loss and load loss for the exact quoted rating, voltage ratio, frequency, impedance, cooling method, and enclosure arrangement. Identify the test basis, reference condition, acceptance tolerance, and whether auxiliary losses are included."

"State whether the quoted design is intended to satisfy [applicable market regulation / utility requirement / project standard], subject to final datasheet, approved drawings, factory test report, and local authority review. Do not assume that one market's efficiency rule applies unless it is named in the project documents."

"If lifecycle cost is included, show the load profile, energy price, evaluation period, and calculation method used. Treat the result as a bid-comparison aid, not as a guaranteed site operating cost."

"Submit the datasheet, drawing, nameplate information, and factory test report in the agreed format before shipment release. The receiving team will check documents and visible condition on arrival; see our [receiving inspection and temporary storage checklist](/resources/insights/transformer-receiving-inspection-storage-checklist/) for the handover stage."

The practical rule is simple: compare loss values only when the technical basis is the same, and compare lifecycle claims only when the operating assumptions are written down. A useful RFQ does not force every supplier into the same marketing phrase. It asks for the evidence that lets engineers and buyers decide whether the transformer is suitable for the specific project.
