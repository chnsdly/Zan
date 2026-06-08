+++
title = "Transformer Impedance and Motor Starting Voltage Dip: What Factory Buyers Should Check"
description = "A practical guide for industrial buyers evaluating transformer impedance, motor starting voltage dip, and RFQ data before ordering a factory distribution transformer."
image = "/images/resources/insights/transformer-impedance-motor-starting-voltage-dip.webp"
author = "Hengli Engineering Desk"
date = 2026-06-08T00:00:00Z
publishDate = 2026-06-08T00:00:00Z
readingTime = "10 min"
featured = false
+++

A transformer can pass routine tests, match the requested kVA rating, and still create problems when a large motor starts. The symptom is familiar in many factories: lights flicker, drives trip, contactors chatter, compressors fail to restart smoothly, or a production line reports random faults during a shift change.

In these cases, the issue is often not the nameplate capacity alone. It is the interaction between **transformer impedance**, motor starting current, cable voltage drop, upstream network strength, and the sensitivity of downstream equipment.

For B2B buyers, this matters because transformer impedance is usually treated as a technical line item in a quotation. In reality, it can influence starting performance, short-circuit level, protection coordination, thermal stress, and future expansion flexibility. A better RFQ should describe the load behavior behind the kVA requirement, especially when large motors, compressors, pumps, crushers, fans, chillers, or batch-process equipment are involved.

## Why motor starting voltage dip deserves attention

Most industrial motors draw a starting current that is several times higher than their running current, unless a soft starter, VFD, or other controlled-starting method is used. This short-duration current causes voltage drop across the supply path. The transformer is only one part of that path, but it is often the most visible component in the procurement package.

A small voltage dip may be acceptable if the motor accelerates quickly and nearby equipment can tolerate the disturbance. A deeper or longer dip can cause practical problems:

- PLCs, relays, and contactors may reset or drop out.
- Variable-frequency drives may report undervoltage faults.
- A motor may fail to accelerate and remain in a high-current state for too long.
- Multiple machines may trip during a common restart sequence.
- Product quality may suffer if process control is disturbed at the wrong moment.

This is why a transformer selection for motor-heavy factories should not stop at “connected load plus margin.” It should check how the plant behaves during the worst realistic starting event.

## What transformer impedance actually changes

Transformer impedance is commonly expressed as a percentage. In simple terms, it indicates how much voltage drop occurs inside the transformer under rated current and how much fault current the transformer can deliver during a short circuit.

Lower impedance generally supports better voltage stiffness during load changes, but it can also increase available short-circuit current. Higher impedance can help limit fault current, but it may worsen voltage dip when large motors start.

That trade-off is why impedance should not be chosen casually. If the value is too high for the application, production equipment may see unacceptable voltage depression during startup. If it is too low, the downstream switchgear, cables, busbars, and protection devices must be rated and coordinated for the higher fault level.

A technically sound specification balances both sides:

- voltage performance during normal operation and motor starting;
- short-circuit withstand requirements of downstream equipment;
- protection relay and breaker coordination;
- utility or EPC requirements;
- expansion plans that may change the fault level and load profile.

For projects where voltage fluctuation continues even after starting events, online voltage regulation may also need review. Our guide on [when a factory needs an on-load tap-changing transformer](/resources/insights/when-factory-needs-on-load-tap-changing-transformer/) explains when that becomes a separate decision from basic impedance selection.

## Start with the largest starting event, not the largest load list

A common RFQ mistake is to provide only the total installed kW and requested transformer capacity. That may be enough for a preliminary budget, but it is not enough to evaluate starting voltage dip.

The better starting point is the largest realistic disturbance. Buyers should identify:

1. the largest motor or group of motors that may start together;
2. whether starting is direct-on-line, star-delta, soft starter, autotransformer starter, or VFD;
3. expected starting current multiple and acceleration time;
4. whether the motor starts under load or unloaded;
5. what other equipment is already running at the same time;
6. the minimum voltage tolerated by sensitive control systems;
7. cable length and cross-section between transformer, switchgear, and motor control center.

This information helps the supplier and electrical consultant estimate whether the transformer impedance, upstream supply, and downstream cabling can support the starting case without nuisance trips or process disruption.

## Direct-on-line starting changes the risk profile

Direct-on-line starting is simple and robust, but it can be demanding on the electrical system. It is most practical when the motor is relatively small compared with transformer capacity, the upstream network is strong, and the process can tolerate a short voltage dip.

Risk increases when a large motor represents a high percentage of transformer rating. For example, a crusher, fire pump, compressor, or chiller starting across the line can create a disturbance that is much more severe than its normal running kW suggests.

A buyer does not need to solve the calculation alone, but the RFQ should make the starting method clear. If direct-on-line starting is fixed by machine design or local practice, the transformer and switchgear package should be reviewed around that fact, not around average running load.

## Soft starters and VFDs reduce dip, but do not remove all checks

Soft starters and VFDs can reduce starting current and improve process control. However, they do not eliminate every transformer selection issue.

Soft starters still require coordination with motor torque requirements. If the process needs high breakaway torque, current reduction may be limited. VFDs introduce additional considerations such as harmonics, input protection, thermal environment, and electromagnetic compatibility.

The [IEC 61000-2-4](https://webstore.iec.ch/en/publication/65717) standard addresses compatibility levels for low-frequency conducted disturbances in industrial power distribution systems, including phenomena that matter in plants with sensitive equipment and power electronics. For buyers, the practical lesson is simple: if the site includes many drives, rectifiers, welders, or electronic controls, the transformer discussion should include power quality as well as kVA.

In some projects, a transformer with suitable capacity and impedance still needs complementary measures such as input reactors, harmonic filters, staged starting logic, or improved grounding and cabling practices.

## Cable voltage drop can be mistaken for transformer weakness

When a motor fails to start reliably, the transformer is often blamed first. Sometimes that is correct. Other times, the main problem is voltage drop between the transformer secondary terminals and the motor control center or motor terminals.

Long cable runs, undersized conductors, overloaded bus ducts, loose terminations, and poor phase balance can all deepen the voltage dip seen by equipment. The transformer may show acceptable secondary voltage while the motor terminal voltage is much lower during acceleration.

Before changing transformer specification, buyers should ask where voltage is being measured:

- at the transformer secondary terminals;
- at the low-voltage switchgear bus;
- at the motor control center;
- at the motor terminals during starting;
- at the terminals of sensitive control equipment.

This measurement discipline prevents expensive misdiagnosis. It also helps the supplier understand whether the transformer needs a different impedance, whether downstream conductors need correction, or whether starting sequence control is the more effective solution.

## When parallel transformers complicate the answer

Factories often plan parallel transformer operation for redundancy or staged expansion. Parallel operation can improve load sharing and available capacity, but it changes fault current and starting behavior.

If two transformers operate in parallel, the available short-circuit current on the low-voltage bus may rise significantly. This can benefit motor starting voltage stability, but it also increases the duty imposed on switchgear and protection devices. Matching impedance, vector group, voltage ratio, and tap settings becomes critical.

Procurement teams should avoid treating a future parallel unit as a simple copy-and-paste purchase. The second unit should be reviewed against the entire system: existing transformer data, switchgear rating, busbar capacity, relay settings, grounding arrangement, and future load sequence.

For broader planning around variable factory loads and expansion margin, see our article on [sizing a distribution transformer for a factory with variable loads](/resources/insights/insights-1/).

## What to include in a motor-heavy transformer RFQ

A stronger RFQ does not need to be overly complicated. It should give enough operating context for the supplier to avoid guessing. For a factory with significant motor loads, include:

- transformer capacity, primary voltage, secondary voltage, frequency, and phase;
- preferred transformer type and installation environment;
- largest motor ratings and starting methods;
- motors that may start simultaneously or restart after a power interruption;
- expected duty cycle by shift or production stage;
- required short-circuit level or downstream switchgear rating, if known;
- cable distance from transformer to main switchgear and major motor loads;
- sensitive equipment connected to the same bus;
- utility constraints or EPC impedance requirements;
- future expansion loads and whether parallel operation is planned.

If the project requires outdoor high-capacity service with strong thermal performance, an [oil-immersed transformer](/product/oil-immersed/) may be the practical base solution. If the transformer will be installed indoors near production areas, a [dry-type transformer](/product/dry-type/) may deserve review. The correct product family should follow site constraints and electrical behavior, not habit.

## Practical warning signs before ordering

The following signs should trigger a more detailed impedance and voltage-dip review before the purchase order is released:

- one motor is large relative to transformer capacity;
- several motors restart automatically after an outage;
- drives, PLCs, or safety systems share the same bus as heavy motor loads;
- the plant is at the end of a weak utility feeder;
- the quotation lists impedance but no one has checked starting performance;
- downstream switchgear short-circuit rating is close to the calculated fault level;
- future expansion will add chillers, compressors, pumps, crushers, or fans;
- operators already report nuisance trips during startup or shift changes.

These warning signs do not automatically mean the transformer is wrong. They mean the selection needs evidence before price comparison becomes the main discussion.

## A better transformer decision is based on system behavior

Transformer impedance is not just a factory test value. It is part of the way an industrial power system responds to starting current, faults, protection settings, and future load growth.

For procurement managers, warehouse operators, factory engineers, and EPC teams, the most reliable approach is to describe the real operating scenario early: which motors start, how they start, what else is running, where sensitive equipment is connected, and how the plant may expand.

When that information is clear, the transformer supplier can support a specification that protects both production stability and electrical safety. The result is not simply a transformer that fits the kVA calculation, but a distribution system that behaves predictably when the factory needs it most.
