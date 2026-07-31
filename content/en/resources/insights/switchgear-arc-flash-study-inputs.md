+++
title = "Switchgear Arc-Flash Study Inputs Buyers Should Request"
description = "Know which transformer, switchgear, protection, cable, and document data to request before an arc-flash study or safety label review."
image = "/images/resources/insights/switchgear-arc-flash-study-inputs.webp"
author = "Hengli Engineering Desk"
date = 2026-07-31T00:00:00Z
publishDate = 2026-07-31T00:00:00Z
readingTime = "8 min"
featured = false
+++

An arc-flash label cannot be ordered from a switchgear catalogue. The result depends on the utility source, transformer impedance, protective-device clearing time, cable or busway routes, equipment arrangement, operating mode, and the safety rules that apply at the site. A supplier can provide important input data, but final incident-energy analysis and labeling must be handled by qualified people under the project safety program.

The short answer is: when a buyer orders [switchgear](/product/switchgear/), a transformer, or a compact substation, the RFQ should request the electrical data, drawings, protection information, and document evidence needed for a future arc-flash study. The supplier should not be asked to guess PPE categories, approve energized work, or replace the facility owner, EPC, electrical engineer, utility, local code, or AHJ.

This article is for procurement teams, EPCs, factory engineers, commercial-building teams, mines, industrial parks, and renewable-energy projects that need cleaner handover data. It does not calculate incident energy, set protection settings, issue labels, choose PPE, define live-work procedures, or approve commissioning.

## Why arc-flash data belongs in the RFQ

Arc-flash studies are often requested late, after the [transformer short-circuit current and switchgear rating](/resources/insights/transformer-short-circuit-current-switchgear-rating/) review, protection coordination, and panel drawings are already frozen. That timing creates avoidable gaps. The study team may ask for transformer impedance, upstream breaker curves, relay settings, cable lengths, enclosure details, operating modes, or tie-breaker arrangements, only to find that some information was never included in the order package.

Procurement does not need to solve the arc-flash study. Its job is to make sure the future study is not blocked by missing supplier data. For a transformer order, the final impedance, tap arrangement, grounding interface, cooling method, and nameplate data should be traceable to the approved datasheet and test report. For a switchgear order, protective-device data, CT ratios, relay or trip-unit information, compartment arrangement, and drawing revisions need to be visible before shipment.

That is especially important when equipment is supplied as separate lots. A transformer supplier may provide only the transformer datasheet. A switchgear supplier may provide only the breaker schedule. The EPC or facility owner still needs one coordinated system model.

## RFQ data matrix for arc-flash study inputs

Use this matrix to request data for engineering review. It is not a calculation method and does not replace the project study.

| RFQ data item | What the buyer should request | Why it matters |
| --- | --- | --- |
| Utility or source basis | Available fault-current information, service voltage, supply configuration, utility transformer or feeder data if provided by the utility, generator contribution if applicable, and the date or revision of the source data. | Incident-energy results can change when the source fault current or operating mode changes. Utility data should be confirmed by the utility or project documents. |
| Transformer data | Rated power, voltage ratio, frequency, vector group or connection, impedance value or guaranteed tolerance if specified, tap positions, neutral or grounding arrangement, cooling method, and final nameplate/test-report values. | Transformer impedance and grounding assumptions affect fault-current calculations. Final values remain subject to the approved datasheet and factory test report. |
| Upstream protection | Breaker, fuse, relay, recloser, or trip-unit type; CT ratios; trip settings; time-current curves; current-limiting data if specified; maintenance mode or energy-reduction function if required. | Arc-flash energy is strongly affected by how fast upstream devices clear a fault. Use the [protection CT and relay RFQ checklist](/resources/insights/protection-cts-relays-switchgear-rfq/) to close these interfaces. |
| Switchgear assembly | Rated voltage, rated current, short-time withstand, bus arrangement, incomer/tie/feeder layout, compartment drawings, door and cover arrangement, access sides, and any arc-resistant construction requirement. | A catalogue description may not give enough information for modeling or label placement. Final use depends on approved drawings and applicable standards. |
| LV breakers and feeders | Breaker frame, sensor or plug, trip unit, settings range, instantaneous function, zone-selective interlocking if specified, feeder schedule, spare feeders, and downstream panel data available at order time. | Downstream labels and clearing times may depend on actual breaker configuration, not only nominal current rating. |
| Cables, busway, and terminations | Cable length, conductor material, number of parallel runs, installation route, busway or busduct interface, termination type, and whether the final field route is by others. | The study model should reflect the installed circuit. Use assumptions clearly where final site routing is not yet known. |
| Operating modes | Normal source, emergency generator, transformer parallel operation, bus-tie open/closed states, automatic transfer scheme, future expansion, and any modes that are prohibited by procedure. | The worst case may not be the normal case. Parallel or alternate sources should be reviewed before labels are finalized. |
| Label and handover scope | Who performs the study, who supplies labels, required label language, facility safety procedure, owner acceptance, local code basis, and update responsibility after setting changes. | The equipment supplier may provide data, but the owner or EPC normally controls the safety program and final labeling. |
| Evidence package | Final datasheet, single-line diagram, protection schedule, breaker/relay datasheets, settings file if available, wiring diagrams, outline drawings, test reports, nameplate photos, and deviation log. | The study team needs traceable data, not only sales descriptions. Keep the package aligned through FAT, receiving, and [pre-energization checks](/resources/insights/transformer-pre-energization-checklist/). |

## What suppliers can and cannot confirm

A transformer supplier can state the transformer data being quoted and later provide final nameplate and test-report data. That does not mean the supplier has approved the site's incident energy. A switchgear supplier can provide breaker, relay, CT, bus, compartment, and drawing information. That does not mean the supplier has approved the facility's PPE, working distance, energized-work permit, lockout/tagout practice, or maintenance procedure.

Buyers should keep that boundary clear in the RFQ. Ask for data and evidence, not a broad safety promise. If the project requires the supplier to perform or subcontract an arc-flash study, define the scope separately: software basis if specified, data responsibility, site measurements, label format, revision control, language, professional qualification, local compliance path, and who approves the final report.

For a [compact substation](/product/substation/), the same discipline is needed because medium-voltage switching, transformer, low-voltage distribution, metering, enclosure, and auxiliary circuits may be inside one package. Ask whether the study data covers the whole package or only the equipment supplied by one party.

## Arc-resistant equipment is a separate question

Arc-flash study data and arc-resistant switchgear are related, but they are not the same purchase requirement. An arc-flash study estimates exposure for workers under defined calculation assumptions. Arc-resistant or internal-arc tested equipment refers to a construction and test claim under a specific standard, accessibility condition, fault location, current, duration, pressure-relief arrangement, and door/cover condition.

Do not assume that standard switchgear is arc-resistant because it has a high short-circuit rating. If arc-resistant construction is required, the RFQ should ask the supplier to state whether it is included, which standard or technical report is used, which sides are protected, whether doors and covers must remain closed, where pressure is vented, what installation clearances are required, and what documents prove the quoted design.

[IEC TR 61641:2014](https://webstore.iec.ch/en/publication/5680) is one reference for low-voltage assemblies tested under internal arcing-fault conditions where that IEC route is specified. Other markets may use different IEC, IEEE, ANSI, UL, GB/GB/T, utility, or local requirements. The project specification decides the final path.

## Standards set methods, not a global answer

[IEEE 1584-2018](https://standards.ieee.org/ieee/1584/5802/) is a major reference for arc-flash hazard calculations within its stated scope. [OSHA's electric-arc flash resources](https://www.osha.gov/electrical/flash-hazards) are useful for understanding why workplace safety, deenergization, training, labels, and PPE cannot be treated as a catalogue note. These references help define vocabulary and responsibilities, but they do not make one market's rule automatically valid in another.

A project may require NFPA 70E, IEEE, IEC, ANSI, GB/GB/T, utility rules, mining rules, local occupational-safety law, national electrical code, owner standards, insurer requirements, or AHJ review. The RFQ should name the applicable basis and ask the supplier to provide data that matches it. Final conclusions should come from the approved study, final settings, installed field conditions, and qualified safety review.

## RFQ wording buyers can adapt

"Please provide transformer, switchgear, protection, cable interface, and document data required for the owner's arc-flash study. Supplier shall identify assumptions, exclusions, and data that must be confirmed by utility, EPC, field installation, or final test report."

"Do not provide PPE category, incident-energy value, arc-flash boundary, energized-work approval, or final label unless that study scope is explicitly included and approved by the project safety authority."

"Submit final datasheets, single-line diagram, protection schedule, breaker/relay information, CT ratios, settings basis, compartment drawings, test reports, nameplate data, and deviation log before shipment release."

"If arc-resistant or internal-arc tested switchgear is required, state the quoted standard, accessibility condition, protected sides, door/cover condition, pressure-relief path, installation clearances, and document evidence. Standard short-circuit rating alone shall not be treated as arc-resistant construction."

## A practical release rule

Do not wait until commissioning to ask for arc-flash study inputs. Before the transformer, switchgear, or substation leaves the factory, the project team should know which data is final, which data is assumed, which data belongs to the utility or EPC, and which party will approve the arc-flash report and labels.

That rule keeps procurement in its proper role. It helps the safety engineer work with better evidence, without turning the supplier's quotation into a substitute for the project's electrical safety program.
