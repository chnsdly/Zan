+++
title = "Power Factor Correction Cabinets: RFQ Checks With Transformers"
description = "Define kvar targets, harmonics, detuning reactors, switching stages, transformer loading, and switchgear interfaces before ordering capacitor cabinets."
image = "/images/resources/insights/power-factor-correction-cabinet-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-07-18T00:00:00Z
publishDate = 2026-07-18T00:00:00Z
readingTime = "8 min"
featured = false
+++

Power-factor correction is often added to a transformer inquiry after the main kVA, voltage ratio, and switchgear scope are already being priced. That late addition can create a procurement problem: the buyer may receive a capacitor cabinet quote, but the quotation may not explain where the power-factor target is measured, whether harmonics have been reviewed, how the stages will switch, or how the cabinet connects to the transformer and low-voltage bus.

The short answer is: a power-factor correction cabinet should be specified as part of the electrical system, not as an isolated kvar price line. The RFQ should state the target power factor, measurement point, load profile, transformer data, harmonic condition, detuning or filtering expectation, switching method, protection interface, ventilation, documents, and final project standard. Final suitability remains subject to the project drawings, load study, utility rules, local code, AHJ review, supplier datasheet, test evidence, and commissioning by qualified electrical personnel.

This article is for factories, EPC teams, commercial buildings, mines, industrial parks, and renewable-energy facilities preparing transformer and low-voltage distribution inquiries. It helps buyers ask better questions; it does not replace power-quality studies, protection coordination, grounding design, or utility approval.

## A capacitor cabinet is not a simple add-on

Low-voltage power-factor correction can reduce unnecessary reactive current in parts of the distribution system. In the right project, that may help reduce feeder current, improve power-factor billing conditions, release some capacity in cables or transformers, and support voltage behavior. Those benefits are project-specific and should be confirmed by calculation or measurement.

The mistake is treating the cabinet as a universal cure. A compensation cabinet cannot create real transformer thermal capacity, correct an undersized cable, fix severe harmonic distortion by itself, or bypass utility and protection requirements. It also can introduce risk if capacitor steps interact with nonlinear loads, utility voltage, generators, inverters, or existing capacitor banks.

For HengLi Transformer buyers reviewing a [GGJ low-voltage capacitor compensation cabinet](/product/switchgear/ggj-low-voltage-capacitor-compensation-cabinet-a/), the practical question is not only "How many kvar?" It is "What electrical problem are we solving, and what information must be frozen before the transformer, low-voltage cabinet, and capacitor cabinet are manufactured?"

## RFQ matrix for transformer and capacitor-cabinet coordination

Use this table as a procurement schedule. It is not a design calculation and should be adapted to the market, utility, and project specification.

| RFQ item | What the buyer should provide or request | Why it matters |
| --- | --- | --- |
| Power-factor target | State the required target, whether it is a utility billing target, owner target, or internal distribution target, and whether the value is average, minimum, or measured during specific operating periods. | A cabinet sized for one billing point may not solve a problem measured at another bus or feeder. |
| Measurement point | Identify the metering point, CT location, main incomer, transformer secondary bus, generator tie, solar or storage interface, and any utility point of common coupling. | Controller feedback and compliance review depend on where current and voltage are measured. |
| Transformer information | Provide transformer kVA or MVA, voltage ratio, frequency, impedance if known, tap position, expected loading, future expansion, and whether the transformer is new or existing. | Compensation can reduce reactive current, but transformer loading, temperature rise, voltage regulation, and fault level still need project review. |
| Load profile | List major motors, compressors, pumps, welding equipment, furnaces, elevators, HVAC loads, VFDs, UPS systems, chargers, rectifiers, and process loads with duty cycles where available. | Reactive demand changes by operating mode. A fixed kvar answer may over-compensate at light load or underperform at peak operation. |
| Harmonic condition | Attach measured or calculated THD, nonlinear load share, existing capacitor failures, nuisance trips, filter equipment, or power-quality complaints if available. | Capacitors may amplify resonance risk if harmonics are not reviewed. Detuned reactors or filters may be needed, subject to study. |
| Switching and control | Request the number of steps, controller logic, switching device type, discharge arrangement, response time basis, manual/automatic modes, and alarm signals. | Fast load changes, crane duty, welding duty, and generator operation can require different switching behavior from slow building loads. |
| Switchgear interface | Define the incoming protection, busbar connection, cable route, short-circuit rating basis, enclosure form, control power, CT wiring, metering, interlocks, and maintenance isolation. | The compensation cabinet is part of the low-voltage distribution assembly, not a separate box electrically. |
| Site and ventilation | State indoor or outdoor installation, ambient temperature, altitude, dust, humidity, corrosion, room ventilation, access, and maintenance clearance. | Capacitors, reactors, controllers, and contactors are sensitive to heat and environmental stress. |
| Documents and acceptance | Request single-line diagram, schematic, component list, datasheet, outline drawing, terminal list, routine verification or test documents, manuals, and open exclusions. | A clear document package prevents late disputes over CT location, control wiring, cabinet boundary, and commissioning responsibility. |

If the RFQ also includes [switchgear](/product/switchgear/), put the capacitor cabinet on the same single-line diagram as the transformer and low-voltage distribution board. If it is treated as a late commercial option, the CT position, feeder route, heat load, cabinet space, or protection assumptions may be wrong.

## Start with the problem you are trying to solve

Buyers often say "we need compensation" when the real problem is more specific. The utility may charge a penalty for poor power factor at the service meter. A factory may want to reduce current in a long low-voltage feeder. A project may be preparing for additional induction motors. A commercial building may be trying to stabilize normal operating power factor after HVAC equipment cycles.

Those are different problems. A central cabinet near the main low-voltage board may suit one case, while feeder-level correction, motor-level correction, staged automatic control, or no capacitor cabinet at all may suit another. The supplier should not be asked to guess the measurement point.

Do not use power-factor correction to hide a transformer sizing problem. Our guide on [transformer losses and efficiency](/resources/insights/transformer-losses-efficiency-rfq/) explains why real loading assumptions matter when comparing transformer performance. Compensation can reduce reactive current, but it does not remove the need to check transformer temperature rise, impedance, load loss, voltage drop, protection settings, and cable capacity under the final project design.

## Harmonics can change the answer

The highest-risk mistake is adding capacitors to a system with many drives, rectifiers, UPS systems, chargers, welders, inverters, or other nonlinear loads without a harmonic review. Capacitor banks can interact with system inductance and create resonance at certain frequencies. When that happens, a cabinet intended to improve the system may experience overheating, fuse operation, contactor stress, controller alarms, or higher voltage distortion.

This does not mean every nonlinear load blocks a capacitor cabinet. It means the RFQ should state whether the buyer expects a standard capacitor cabinet, a detuned reactor arrangement, a harmonic filter, an active power-quality device, or a separate engineering study before selection. For projects with meaningful nonlinear load share, use the checklist in [harmonic loads and transformer RFQs](/resources/insights/harmonic-loads-transformer-rfq/) together with the compensation-cabinet schedule.

The same boundary applies to generators, solar inverters, battery systems, and utility interconnection requirements. Reactive power behavior may be part of grid-code compliance, inverter control, or owner operation strategy. Do not assume a low-voltage capacitor cabinet is the correct tool until the project engineer and utility documents confirm the duty.

## Coordinate cabinet scope before manufacturing

The capacitor cabinet affects more than kvar. It can change CT wiring, control cable routing, low-voltage bus layout, ventilation, spare feeder count, protection settings, maintenance access, and commissioning sequence. If the project uses a compact substation or a packaged low-voltage room, the enclosure space and heat path should be confirmed before drawings are approved.

Site conditions also matter. The [site-condition RFQ checklist](/resources/insights/site-conditions-transformer-rfq/) is useful because capacitors and reactors may be affected by ambient temperature, dust, humidity, corrosive atmosphere, altitude, and ventilation limits. These conditions should be confirmed by project documents and supplier files rather than assumed from a product family name.

Before release for shipment, the approved drawing package should show the compensation cabinet boundary, incoming and outgoing terminals, CT and voltage sensing points, controller settings that are fixed at the factory, settings to be adjusted on site, spare parts, warning labels, and test or verification documents. Commissioning teams should still verify operation under real site load before relying on the cabinet for utility compliance.

## Standards are references, not global answers

Standards help buyers and suppliers use the same vocabulary, but they do not decide the project by themselves. [IEC 61921:2017](https://webstore.iec.ch/en/publication/26596) is a relevant IEC reference for low-voltage power-factor correction capacitor banks where that standard is specified. [IEC 60831-1:2014](https://webstore.iec.ch/en/publication/3609) covers self-healing shunt power capacitors for AC systems within its stated scope, including guidance related to performance, testing, rating, safety, installation, and operation. [IEEE 519-2022](https://standards.ieee.org/ieee/519/10677/) is a relevant IEEE reference for harmonic control in electric power systems and uses the point of common coupling concept.

The final requirement depends on the applicable market and project documents. A project may use IEC, IEEE, ANSI, NEMA, GB/GB/T, utility rules, grid codes, fire rules, seismic requirements, owner specifications, or local AHJ conditions. The RFQ should name the rules that actually apply.

## RFQ wording buyers can adapt

"Please quote the power-factor correction cabinet based on the attached single-line diagram, transformer datasheet, load schedule, utility metering point, and project specification. State the kvar rating, step arrangement, controller logic, switching method, protection devices, CT location, voltage sensing point, ventilation assumptions, and document scope."

"Do not assume that a standard capacitor bank is suitable for harmonic-sensitive loads. Review the attached nonlinear equipment list and identify whether detuned reactors, harmonic filters, a study, or additional data are required before final selection."

"Confirm which parts of the compensation system are included in the quoted low-voltage switchgear package, which items are supplied loose, which settings are factory configured, and which settings remain subject to site commissioning."

"Final suitability shall be confirmed by approved drawings, supplier datasheet, project power-quality study where required, applicable standards, local code, utility requirements, AHJ review, and commissioning test records."

## Practical decision rule

Do not order a power-factor correction cabinet only from a target kvar number. First define where the target is measured, what transformer and switchgear it connects to, how the load changes, whether harmonics or generators are present, what standards and utility rules apply, and which documents prove the final scope.

When those items are clear, a capacitor cabinet can be quoted as part of a coordinated distribution package. When they are missing, the safer answer is not a larger cabinet. It is a clearer RFQ and a qualified engineering review before purchase.
