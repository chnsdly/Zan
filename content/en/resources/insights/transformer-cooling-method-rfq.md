+++
title = "Transformer Cooling Method RFQ: Fans, Radiators, Airflow"
description = "Specify ONAN/ONAF, dry-type fan scope, radiators, airflow, alarms, noise, access, and evidence before ordering transformers."
image = "/images/resources/insights/transformer-cooling-method-rfq.webp"
author = "Hengli Engineering Desk"
date = 2026-07-28T00:00:00Z
publishDate = 2026-07-28T00:00:00Z
readingTime = "8 min"
featured = false
+++

A transformer can be correctly sized on paper and still become a site problem if the cooling method is treated as a catalogue label. Radiators may need more clearance than the layout allows. Dry-type fans may be assumed but not wired to the building system. A compact substation may have transformer capacity on the datasheet while the enclosure ventilation path is still unclear.

The short answer is: do not ask only for "1000 kVA transformer, standard cooling." A useful RFQ should state the required rating under each cooling stage, site ambient and altitude, installation layout, radiator or fan scope, control and alarm wiring, auxiliary power, noise sensitivity, maintenance access, and evidence required in the final datasheet or test report. Final suitability remains subject to project drawings, supplier documents, applicable market standards, local code, utility requirements, AHJ review, and qualified electrical or mechanical engineering confirmation.

This article helps procurement teams, EPCs, plant engineers, commercial-building owners, mines, industrial parks, and renewable-energy projects make cooling assumptions visible before ordering. It is not a loading study, thermal design, fire review, ventilation design, or commissioning procedure.

## Cooling method is a purchase boundary, not a label

Cooling language tells the buyer how heat is expected to leave the transformer under the quoted rating. For a liquid-immersed transformer, that may involve oil circulation inside the tank, radiator banks, natural air movement, forced air from fans, or other project-specific arrangements. For a dry-type transformer, the discussion often moves to enclosure airflow, room ventilation, temperature sensors, and optional forced-air fans.

The important procurement point is not to memorize every abbreviation. It is to make sure the same cooling basis appears in the quotation, datasheet, outline drawing, accessory list, control schematic, sound review, packing inspection, and commissioning file.

If one supplier quotes a continuous rating with natural cooling and another quotes a higher rating that depends on fan operation, the two prices are not technically equivalent. If the fan package is included by one supplier but treated as "by others" in another offer, the site team may discover the gap only during installation. If a transformer is placed in a small room or outdoor enclosure without confirmed airflow, the nameplate rating alone cannot prove that the installed system will operate within the project thermal assumptions.

## RFQ matrix for transformer cooling scope

Use this matrix to expose missing information before quotations are compared. It is not a universal design rule.

| RFQ item | What the buyer should state or request | Why it changes the order |
| --- | --- | --- |
| Required rating basis | State the required kVA or MVA, voltage ratio, frequency, continuous or standby duty, expected loading profile, and whether the rating must apply with natural cooling, forced cooling, or both. | A fan-assisted rating may not be equivalent to a naturally cooled continuous rating. The final basis should be confirmed by the supplier datasheet and project documents. |
| Cooling designation | Ask the supplier to state the cooling method designation used for the quoted unit and the standard or datasheet basis behind it. | IEC, IEEE, GB/GB/T, ANSI, NEMA, and utility specifications may use different language. Do not assume abbreviations are interchangeable across markets. |
| Site ambient and altitude | Provide maximum and minimum ambient temperature, altitude, indoor or outdoor location, nearby heat sources, room ventilation, dust, humidity, and corrosion notes. | Cooling margin depends on the real site, not only factory test conditions. The [site-condition RFQ checklist](/resources/insights/site-conditions-transformer-rfq/) should travel with the inquiry. |
| Radiator or duct layout | Request outline drawings that show radiator banks, fan positions, airflow direction where relevant, wall clearance, door swing, lifting route, and removal path. | A transformer may fit the foundation while its radiators, guards, or access routes do not fit the room or yard. |
| Fan and control scope | Define whether fans, temperature sensors, controllers, contactors, local/remote controls, alarm and trip contacts, and auxiliary supply are included. | Cooling accessories are frequent scope gaps. Use the [accessory and alarm contact checklist](/resources/insights/transformer-accessories-alarm-contacts/) to make contacts and wiring traceable. |
| Noise and auxiliary losses | Ask whether fan operation changes sound data or auxiliary energy use, and whether those values are included in the project evidence. | Forced cooling can change acoustic and energy assumptions. Keep this aligned with any noise-sensitive requirement. |
| Maintenance and cleaning access | State whether filters, fan guards, radiator fins, coils, louvers, heaters, and terminal boxes must remain accessible after installation. | Cooling performance can degrade if dust removal, inspection, or fan replacement is impractical. |
| Documents and hold points | Request final datasheet, cooling arrangement drawing, wiring diagram, terminal list, routine or special test scope, accessory schedule, manual, and approved-deviation list. | Procurement needs evidence that the cooling basis in the price is the same basis used for manufacturing and commissioning. |

## Oil-immersed transformer cooling: radiators need room to work

For an [oil-immersed transformer](/product/oil-immersed/), buyers often see radiator fins and fan assemblies as mechanical details after the electrical rating has been selected. In practice, those parts can decide whether the installed unit can be inspected, cleaned, cooled, and maintained.

The RFQ should identify whether the quoted rating depends on natural air movement around the tank and radiators, fan-assisted operation, or a staged cooling arrangement. If fans are included, ask how they are started, what control signals are provided, what auxiliary supply they need, and whether alarm or failure contacts are brought to a terminal box. If the site has a building management system or substation automation interface, do not assume the signals are included unless the terminal list confirms them.

Layout drawings matter. Radiator-side clearance, wall distance, sound barriers, oil containment, fire separation, fencing, cable boxes, surge arresters, lifting points, and truck access can all interact. A sound barrier that blocks airflow, or a wall that prevents radiator cleaning, may create a different problem from the one it solved. Final fire, oil containment, grounding, access, and utility clearance requirements must be confirmed by the project team and local authorities.

## Dry-type and compact-substation cooling are site-system questions

For a [dry-type transformer](/product/dry-type/), cooling is not only a transformer body question. The room, enclosure, louvers, cable trench, dust level, humidity, filters if used, temperature controller, fan operation, and alarm wiring all shape the practical result. A dry-type transformer may be selected for indoor or oil-free installation, but it still needs verified airflow and clean operating conditions.

If forced-air cooling is proposed, the buyer should ask whether the higher rating is continuous or temporary, what load basis is assumed, how fan start and stop are controlled, what happens if a fan fails, and whether the project accepts fan noise in the selected location. Any standby or overload language should be reviewed by qualified engineers against the actual load profile and applicable standard basis.

A [compact substation](/product/substation/) adds another boundary. The transformer, medium-voltage compartment, low-voltage compartment, enclosure roof, side panels, louvers, anti-condensation devices, and fans may be supplied as one package. The RFQ should ask whether the transformer cooling data applies to the bare transformer, the transformer inside the enclosure, or the complete package under a stated site condition. Foundation height, solar exposure, flood level, cable trench, and public-access controls may also affect ventilation.

## Standards help language, but evidence decides the purchase

Standards are useful because they define terms and test methods, but the applicable market and project specification decide which rules govern the order. [IEC 60076-2](https://webstore.iec.ch/en/publication/599) applies to liquid-immersed transformers and identifies power transformers according to cooling methods as part of temperature-rise practice. [IEC 60076-11](https://webstore.iec.ch/en/publication/29711) applies to dry-type power transformers within its stated scope and includes enclosure, altitude, climatic, environmental, and seismic considerations in the 2018 edition summary. [IEEE C57.12.00](https://standards.ieee.org/standard/C57_12_00-2021.html) is a general IEEE reference for liquid-immersed distribution, power, and regulating transformers where that framework is specified.

Those references do not create a global default cooling design. A project may be governed by IEC, IEEE, ANSI, NEMA, GB/GB/T, DOE, EU Ecodesign, utility rules, fire code, building code, mining rules, renewable interconnection requirements, owner standards, or local AHJ decisions. The RFQ should name the applicable market and require supplier documents for the exact quoted equipment.

## RFQ wording buyers can adapt

"Please state the cooling method designation, rated output under each cooling stage, ambient and altitude basis, radiator or fan arrangement, auxiliary power requirement, control logic, alarm/trip contacts, sound condition, and document evidence for the quoted transformer."

"The equipment will be installed in [indoor electrical room / outdoor yard / compact substation / rooftop / basement]. Cooling, ventilation, fire, access, noise, and maintenance clearances remain subject to approved drawings, local code, utility requirements, AHJ review, and qualified engineering confirmation."

"If the quoted rating depends on fans, pumps, enclosure ventilation, louvers, filters, heaters, or room ventilation by others, identify the responsibility split and submit wiring diagrams, terminal lists, and layout drawings before manufacturing is released."

"Do not assume that IEC, IEEE, ANSI, NEMA, GB/GB/T, DOE, EU, utility, or local requirements are interchangeable. The final cooling and temperature-rise basis must follow the project specification and supplier datasheet."

## A practical decision rule

Pause the order if the quotation shows only a transformer rating and a short cooling abbreviation. Before manufacturing is released, the buyer should know whether the required rating is natural or forced cooled, which accessories are included, who supplies control power and ventilation, what evidence proves the cooling basis, and whether the installed layout still gives the transformer enough air and access.

That rule does not turn procurement into thermal engineering. It simply prevents a cooling assumption from becoming a late site modification, a fan-control wiring dispute, or a commissioning delay.
