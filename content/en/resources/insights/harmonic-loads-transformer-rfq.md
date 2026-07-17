+++
title = "Harmonic Loads and Transformer RFQs: What Buyers Should Specify"
description = "Use this RFQ checklist to define nonlinear loads, harmonic data, neutral current, temperature rise, and power-quality studies before ordering transformers."
image = "/images/resources/insights/harmonic-loads-transformer-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-07-17T00:00:00Z
publishDate = 2026-07-17T00:00:00Z
readingTime = "8 min"
featured = false
+++

Nonlinear loads are easy to hide inside a transformer RFQ. A factory may state the total kVA and voltage correctly, but omit the drives, rectifiers, UPS systems, chargers, welding equipment, LED power supplies, or inverter-based process equipment that shape the real current waveform.

The short answer is: when a meaningful share of the load is nonlinear, the RFQ should identify the equipment type, duty cycle, harmonic data if available, neutral-current concern, capacitor or filter interface, utility power-quality requirement, and the expected engineering basis for transformer loading. The final selection still depends on the project load study, supplier datasheet, factory test report, local code, utility requirements, applicable standards, and review by qualified electrical engineers.

This article is for procurement teams, EPCs, facility engineers, and commercial building project teams preparing transformer inquiries. It helps organize questions for suppliers; it does not replace harmonic studies, protection coordination, grounding review, utility approval, AHJ requirements, or commissioning by qualified personnel.

## Total kVA is not enough for nonlinear loads

A transformer nameplate kVA assumes a defined rating basis, but a nonlinear load does not draw current as a clean sine wave. Variable-frequency drives, rectifiers, UPS front ends, chargers, electronic power supplies, and some welding or process loads can inject harmonic currents into the distribution system. Those currents may increase winding stray losses, extra heating, neutral current, nuisance trips, capacitor stress, or voltage distortion elsewhere in the facility.

This does not mean every project needs a special transformer. A small share of nonlinear load may be handled within normal engineering margins, while a high or concentrated share may need a harmonic study, transformer derating, different winding or connection decisions, filters, reactors, detuned capacitor banks, or a separate transformer. The correct answer is project-specific.

If the RFQ also compares operating losses, keep the harmonic question separate from the standard loss schedule. Our guide on [transformer losses and efficiency](/resources/insights/transformer-losses-efficiency-rfq/) explains how to request no-load and load-loss data, but harmonic loading can change the thermal and application review around those values. Site details also matter: ventilation, ambient temperature, altitude, enclosure, dust, and humidity should be stated using a [site-condition RFQ checklist](/resources/insights/site-conditions-transformer-rfq/).

## RFQ data schedule for harmonic-sensitive projects

Use the following table to make quotations more comparable. It is not a universal design standard, and it should be adapted to the project specification, applicable market, and utility requirements.

| RFQ item | What the buyer should provide or request | Why it matters |
| --- | --- | --- |
| Nonlinear equipment list | List major VFDs, rectifiers, UPS systems, chargers, inverters, welding loads, electronic process equipment, and large lighting power supplies connected to the transformer. | A total load schedule can look ordinary while one feeder or process area creates the main harmonic concern. |
| Load share and duty cycle | State estimated kVA or kW share, simultaneous operation, continuous or intermittent duty, standby operation, and future expansion. | Transformer heating depends on both magnitude and duration. A short test load is different from a continuous production line. |
| Harmonic information | If available, attach measured or calculated current spectrum, THDi, expected voltage distortion, study assumptions, and the point where limits are evaluated. | Suppliers and engineers need the waveform basis, not only the words "nonlinear load." Missing data may require conservative assumptions or a formal study. |
| Utility or project limit | Identify whether IEEE, IEC, local utility, grid code, building code, mine specification, data-center rule, or owner standard applies. | Harmonic limits are usually evaluated at a defined point in the system, not automatically at the transformer terminals. |
| Transformer application | State whether the unit is new or existing, dry-type or oil-immersed, indoor or outdoor, isolated to nonlinear loads or shared with general loads, and whether derating, K-rated language, electrostatic shielding, or special thermal review is requested. | The same load may lead to different transformer decisions depending on cooling, insulation system, location, and the information the manufacturer can verify. |
| Neutral and grounding interface | For four-wire systems and single-phase electronic loads, ask the engineer to review neutral current, neutral conductor sizing, bonding, grounding, and protection assumptions. | Triplen harmonics and zero-sequence current concerns are not solved by transformer kVA alone and must follow project design rules. |
| Switchgear, cables, and capacitors | Include downstream [switchgear](/product/switchgear/) data, cable routes, protection devices, capacitor banks, power-factor correction equipment, filters, reactors, and monitoring points. | Harmonics can interact with capacitor banks and protection equipment. A capacitor cabinet should not be assumed to fix harmonics unless it is designed for that duty. |
| Documentation and acceptance | Request the supplier's stated load assumptions, datasheet limits, temperature or loading review basis, accessory list, test report scope, and any open exclusions. | The quotation should say what was assumed. A vague "suitable for harmonics" statement is not enough for procurement or commissioning. |

## When to pause and request engineering review

Buyers should slow down before purchase when the nonlinear load is a large share of transformer loading, when a plant is adding many drives to an existing transformer, when a utility or landlord asks for harmonic compliance, or when the site already has unexplained transformer heating, neutral conductor heating, capacitor failures, nuisance trips, relay alarms, or sensitive equipment complaints.

The same caution applies to expansion projects. A facility may install new production drives, EV charging, UPS-backed rooms, solar inverters, or welding bays after the transformer was originally selected. In that case, the question is not only "Do we have spare kVA?" It is also "Can the existing transformer, neutral, switchgear, cables, capacitors, ventilation, and protection system operate under the new current waveform?"

A practical rule is to treat total kVA as a budget input and harmonic information as a purchase input. If the nonlinear load is material, do not release the order until the project team has documented the assumed waveform, duty cycle, point of compliance, and transformer loading basis.

## Dry-type and oil-immersed transformers face different checks

[Dry-type transformers](/product/dry-type/) are often selected for indoor electrical rooms, commercial buildings, data centers, hospitals, transit facilities, and factories that prefer oil-free installation. In those projects, nonlinear loads may be close to the transformer: UPS systems, drives, elevators, HVAC equipment, lighting supplies, chargers, and IT power supplies. The RFQ should connect harmonic assumptions with enclosure airflow, room ventilation, temperature monitoring, fan control if specified, dust, condensation, and acoustic requirements.

[Oil-immersed transformers](/product/oil-immersed/) may serve outdoor industrial yards, utilities, renewable collection systems, mines, process plants, or compact substations. Their harmonic review may involve oil and winding thermal behavior, tank accessories, protection signals, upstream utility fault level, downstream switchgear, and any power-quality study required at the point of common coupling. The liquid-filled format does not remove the need to define nonlinear load data.

Neither format is automatically the better answer for harmonics. The right choice depends on installation environment, fire and containment rules, maintenance model, load profile, thermal design, utility rules, and the final supplier documentation.

## Standards are references, not interchangeable answers

Standards can help the buyer and supplier use the same technical language. [IEEE C57.110-2018](https://standards.ieee.org/ieee/C57.110/5948/) is a relevant IEEE reference for evaluating liquid-immersed and dry-type transformer capability when supplying nonsinusoidal load currents. [IEEE 519-2022](https://standards.ieee.org/ieee/519/10677/) addresses harmonic control in electric power systems and uses the point of common coupling concept for system distortion goals. Where IEC-based public network connection studies apply, [IEC TR 61000-3-6:2008](https://webstore.iec.ch/en/publication/4155) provides informative guidance for distorting installations connected to MV, HV, and EHV public power systems.

Those references should not be treated as global default requirements. Some projects may use IEEE, IEC, ANSI, NEMA, GB/GB/T, utility, DOE, EU, local grid code, fire, seismic, mining, or owner specifications. The RFQ should name the applicable market and project documents. Final acceptance should be based on approved drawings, final datasheets, test reports, utility review, site inspection, and commissioning procedures.

## RFQ wording buyers can adapt

"Please identify whether the quoted transformer is suitable for the nonlinear load schedule attached to this RFQ. State the harmonic assumptions, loading basis, temperature-rise basis if reviewed, and any derating, K-rated language, filter, reactor, neutral, or separate-transformer recommendation."

"The quotation shall not assume that total kVA alone defines the duty. The supplier should review the attached drive, UPS, rectifier, charger, inverter, and electronic load information and list any missing data required for final confirmation."

"Power-factor correction capacitors, harmonic filters, detuned reactors, protection settings, grounding, neutral sizing, and utility compliance remain subject to the project electrical design, local code, utility requirements, and AHJ review."

"Final suitability must be confirmed by the approved datasheet, project load study, supplier documents, factory test report where applicable, site measurements if required, and commissioning by qualified personnel."

## A practical decision rule

Do not order a transformer for a harmonic-sensitive facility using only total kVA and voltage ratio. First confirm what nonlinear equipment will connect, how often it operates, what harmonic data or study basis exists, where utility compliance is measured, and how the transformer, neutral, switchgear, capacitors, cables, ventilation, and monitoring will be reviewed together.

That process does not make the RFQ more complicated for its own sake. It prevents a transformer that looks correct on a load schedule from becoming the weak point in a real factory, commercial building, mine, utility, or renewable power distribution system.
