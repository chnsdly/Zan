+++
title = "Transformer Accessories and Alarm Contacts: RFQ Checklist"
description = "Specify protection devices, temperature monitoring, enclosure interfaces, and auxiliary contacts clearly before ordering distribution transformers."
image = "/images/resources/insights/transformer-accessories-alarm-contacts.webp"
author = "Hengli Engineering Desk"
date = 2026-07-14T00:00:00Z
publishDate = 2026-07-14T00:00:00Z
readingTime = "9 min"
featured = false
+++

A transformer quotation can look complete while still missing items that determine whether the equipment is easy to install, monitor, protect, and accept on site. Temperature indicators, alarm contacts, pressure devices, fans, heaters, terminal boxes, cable boxes, CTs, surge arresters, wheels, lifting points, and communication interfaces may be treated as "accessories," but they are often critical project interfaces.

The short answer is: do not leave transformer accessories to supplier default. The RFQ should state which protection devices, monitoring points, auxiliary contacts, enclosure details, cable interfaces, and document evidence are required for the specific project. Final selection must still be confirmed by the approved datasheet, wiring diagram, protection design, local code, utility requirements, factory test report, and commissioning plan.

Use it to prepare clearer project RFQs; it does not replace a qualified electrical engineer, local AHJ, utility reviewer, or protection specialist.

## Accessories are not a decoration line item

Accessory decisions affect three practical stages: quotation comparison, factory drawing approval, and site commissioning. If one supplier includes alarm contacts, marshalling box wiring, enclosure heaters, cable boxes, and temperature relay outputs while another supplier excludes them, the cheaper offer may not be the lower-risk offer.

This is especially important when the transformer connects to a building management system, plant SCADA, protection relay, compact substation, or separately purchased switchgear lineup. The transformer may be electrically suitable, but the site team can still lose time if terminal numbering, contact type, control voltage, cable entry, or alarm logic was never agreed.

For a purchase order, the accessory schedule should be treated like part of the technical specification.

## RFQ accessory schedule buyers can adapt

This is not a universal design requirement. It is a practical schedule for asking the right questions before the order is released.

| RFQ item | Why it matters | What the buyer should state or request |
| --- | --- | --- |
| Temperature indication and alarms | Temperature is usually one of the most important operating signals, but device type and contact output vary by transformer type and specification. | State whether oil temperature indicator, winding temperature indicator, dry-type temperature controller, RTDs, alarm/trip contacts, or remote indication are required. Confirm setpoints and wiring through project documents. |
| Oil-immersed protection devices | Conservator-type, sealed, and higher-voltage oil-filled transformers may use different pressure, gas, oil-level, and breather arrangements. | For an [oil-immersed transformer](/product/oil-immersed/), specify whether Buchholz relay, pressure relief device, oil level indicator, dehydrating breather, oil sampling valve, drain valve, or gas/oil alarm contacts are required. Do not assume every device applies to every tank design. |
| Dry-type monitoring and cooling | Dry-type units often depend on room ventilation, coil temperature monitoring, and optional forced-air cooling controls. | For a [dry-type transformer](/product/dry-type/), identify temperature controller functions, sensor quantity, fan control logic if fans are specified, alarm/trip outputs, enclosure heaters if needed, and local display language. |
| Auxiliary contacts and signal wiring | A signal named "alarm" is not enough for PLC, BMS, SCADA, or protection relay integration. | Request a point list showing signal name, normal state, contact rating, AC/DC control voltage, terminal number, cable gland needs, and whether the contact is used for alarm, trip, blocking, or indication only. |
| Enclosure, cable box, and IP/NEMA interface | Enclosure details affect cooling, cable bending space, water ingress, dust, corrosion, and maintenance access. | State indoor/outdoor location, cable entry direction, gland plate, busduct interface, required IP rating, NEMA type where applicable, anti-condensation heaters, ventilation openings, and access clearance. |
| Surge protection and earthing interface | Surge arresters, neutral terminals, tank earthing, and cable shield grounding are project-specific interfaces. | Ask the engineer to define surge arrester scope, neutral treatment, earthing terminals, grounding bar, bonding points, and utility requirements. Final grounding design must follow local code and project drawings. |
| CTs, meters, and protection interfaces | Metering and protection CTs may be supplied in transformer cable boxes, switchgear, or separate panels depending on the design. | State whether CTs, meters, transducers, protection relay inputs, test links, or marshalling terminals are included in the transformer scope or provided by others. Confirm ratios and accuracy from the protection/metering design, not from a generic RFQ. |
| Tap changer accessories | Off-circuit tap switches and on-load tap changers have very different control, indication, and maintenance interfaces. | Identify tap range, tap position indicator, locking requirement, remote indication, OLTC motor drive/control cabinet if applicable, and whether voltage control is local, remote, manual, or automatic. |
| Mechanical and transport accessories | Wheels, rollers, lifting lugs, jacking pads, vibration pads, nameplates, paint system, and packing details can affect installation work. | Provide the handling route, foundation drawing, floor loading, lifting plan, corrosion environment, and storage condition. Confirm final accessories on drawings before shipment. |

## Oil-immersed and dry-type lists should not be copied blindly

It is tempting to use one standard accessory checklist for every transformer. That creates avoidable gaps.

Oil-filled equipment may need oil-level, pressure, gas, breather, valve, sampling, containment, fire, and environmental interfaces that do not apply in the same way to cast-resin dry-type units. At the same time, dry-type equipment may require more attention to room ventilation, winding sensors, enclosure airflow, fan control, dust, humidity, and alarm contacts for building systems.

Compact substations add another layer. A [compact substation](/product/substation/) may combine transformer, medium-voltage switching, low-voltage distribution, enclosure ventilation, heaters, lighting, metering, and cable compartments. In that case, the accessory schedule should define which signals are wired inside the substation and which are brought out to customer terminals.

A better procurement practice is to start from the application and site condition, then select the accessory list. Our [site-condition RFQ checklist](/resources/insights/site-conditions-transformer-rfq/) is a useful companion because enclosure, condensation, dust, corrosion, cable entry, and ventilation requirements often decide which accessories are necessary.

## Alarm contacts need a real point list

Many RFQs say "provide alarm contacts" without saying what the project needs. That phrase can lead to different assumptions between the transformer supplier, switchgear supplier, BMS contractor, and commissioning team.

A usable signal schedule should answer:

- What is the exact signal name, such as high oil temperature alarm, winding temperature trip, fan failure, pressure relief operation, oil level low, heater failure, or OLTC fault?
- Is the contact normally open or normally closed in the healthy state?
- What control voltage and contact rating does the receiving device require?
- Is the signal used for warning, trip, interlock, load shedding, remote indication, or maintenance notification?
- Where is the terminal located: transformer terminal box, marshalling box, LV panel, MV switchgear, or substation control compartment?
- Who supplies and terminates the control cable?
- Will the factory drawing show terminal numbers and wiring diagrams before production is frozen?

For critical trip functions, the project engineer should define the protection philosophy and commissioning test method. The supplier can provide devices and terminals according to the approved scope, but trip, alarm-only, or blocking logic belongs to the project protection design and applicable rules.

## Standards help define language, but the project decides scope

Standards can help align terminology and test expectations, but they do not automatically define the accessory package for every country or project. [IEC 60076-1](https://webstore.iec.ch/en/publication/588) is a common general reference where IEC transformer standards are specified. Enclosure protection may refer to [IEC 60529](https://webstore.iec.ch/en/publication/2452) for IP codes where that system applies. Some markets or project specifications may use NEMA documents such as [NEMA ST 20](https://www.nema.org/standards/view/dry-type-transformers-for-general-applications) for dry-type transformer applications, or other IEEE, ANSI, GB/GB/T, utility, DOE, EU, or local requirements.

These references are not interchangeable. The RFQ should name the applicable market, utility rule, project standard, and AHJ requirement. The final accessory scope should be controlled by approved drawings, datasheets, wiring diagrams, test documents, and local review.

## RFQ wording buyers can use

The following clauses help keep accessory scope out of the "assumed included" zone:

"Please provide a transformer accessory schedule for the exact quoted design. Identify each supplied device, function, terminal output, contact type, control voltage, mounting location, and whether it is included in the base price or optional."

"For all alarm, trip, indication, fan-control, heater, pressure, oil-level, temperature, door, and tap-position signals, submit a wiring diagram and terminal list for approval before manufacturing. Final alarm logic remains subject to the project protection and control design."

"State the enclosure, cable box, gland plate, busduct, earthing terminal, marshalling box, and anti-condensation heater scope. Confirm site conditions, cable entry, ventilation, maintenance clearance, and local code requirements."

"Do not treat IEC, IEEE, ANSI, NEMA, GB/T, DOE, EU Ecodesign, or local references as globally interchangeable. The quoted design must follow the project specification and applicable market rules, subject to final datasheet, drawings, test report, and authority review."

## Before shipment, check the document trail

Accessory problems are easier to correct during drawing approval than after the transformer reaches site. Before shipment release, the buyer should check that the approved datasheet, outline drawing, accessory schedule, wiring diagram, terminal list, nameplate, packing list, and factory test report describe the same scope.

When the unit arrives, the receiving team should verify visible accessories, labels, loose parts, terminal boxes, documents, and storage requirements. The arrival-stage checks in our [transformer receiving inspection and temporary storage checklist](/resources/insights/transformer-receiving-inspection-storage-checklist/) help protect that evidence before installation.

The practical rule is simple: if the site team needs to monitor it, wire it, trip from it, maintain it, or prove it during acceptance, it should not be hidden inside a vague accessory line. Put it in the RFQ, confirm it on the drawing, and keep it traceable through factory testing, shipment, receiving inspection, and commissioning.
