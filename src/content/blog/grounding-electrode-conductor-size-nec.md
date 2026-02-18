---
title: "Grounding Electrode Conductor Sizing: NEC Table 250.66"
description: "Size grounding electrode conductors using NEC Table 250.66. Includes sizing charts, installation requirements, and common applications."
pubDate: 2026-02-03
author: "NETA. Team"
keywords: "grounding electrode conductor size NEC, NEC table 250.66, GEC sizing chart, service grounding conductor"
---

You're installing a 200-amp service upgrade and grab a roll of 6 AWG bare copper for the grounding electrode conductor. The inspector takes one look and shakes his head: "That's too small." You double-check Table 250.66 and realize your mistake—2/0 aluminum service conductors require a 4 AWG grounding electrode conductor, not 6 AWG. One table lookup error just cost you time and material.

This complete guide to grounding electrode conductor (GEC) sizing covers NEC Table 250.66, proper installation methods, and the critical safety role these conductors play in electrical systems.

## Why Grounding Electrode Conductor Sizing Matters

The grounding electrode conductor provides the connection between your electrical system and the earth, serving multiple critical functions:

**Fault current return path**: Provides path for ground faults back to the source
**Lightning protection**: Dissipates lightning energy safely into the earth  
**System stabilization**: Maintains system voltage stability during fault conditions
**Personnel protection**: Limits voltage rise during ground fault events

Undersizing the GEC can create dangerous voltage conditions during fault events and fail to provide adequate system protection.

## Understanding NEC 250.66

### What Table 250.66 Covers

**Purpose**: Size grounding electrode conductors for AC systems
**Application**: Service entrance, separately derived systems, buildings with multiple occupancy
**Basis**: Sized according to largest ungrounded service entrance conductor

### How to Use Table 250.66

**Step 1**: Identify largest ungrounded service conductor size
**Step 2**: Find conductor size in left column of Table 250.66
**Step 3**: Read corresponding GEC size for copper or aluminum
**Step 4**: Apply any applicable limitations or exceptions

### Table 250.66 - Grounding Electrode Conductor Sizing

| Size of Largest Service Entrance Conductor | Copper GEC | Aluminum GEC |
|--------------------------------------------|------------|--------------|
| 2 AWG or smaller | 8 AWG | 6 AWG |
| 1 AWG or 1/0 AWG | 6 AWG | 4 AWG |
| 2/0 or 3/0 AWG | 4 AWG | 2 AWG |
| Over 3/0 thru 350 kcmil | 2 AWG | 1/0 AWG |
| Over 350 thru 600 kcmil | 1/0 AWG | 3/0 AWG |
| Over 600 thru 1100 kcmil | 2/0 AWG | 4/0 AWG |
| Over 1100 kcmil | 3/0 AWG | 250 kcmil |

**Key points**:
- Based on largest single ungrounded conductor
- For parallel conductors, add individual conductor sizes
- Different requirements for copper vs aluminum GECs

## GEC Sizing Examples

### Example 1: Residential 200A Service

**Service conductors**: 2/0 aluminum (per Table 310.15(B)(16))
**Table lookup**: 2/0 falls in "2/0 or 3/0 AWG" row
**Required GEC**: 
- Copper GEC: 4 AWG minimum
- Aluminum GEC: 2 AWG minimum

### Example 2: Commercial 400A Service

**Service conductors**: 500 kcmil copper
**Table lookup**: 500 kcmil falls in "Over 350 thru 600 kcmil" row  
**Required GEC**:
- Copper GEC: 1/0 AWG minimum
- Aluminum GEC: 3/0 AWG minimum

### Example 3: Parallel Service Conductors

**Service conductors**: Two 3/0 copper conductors per phase (parallel)
**Calculation**: 3/0 + 3/0 = equivalent to 600 kcmil
**Table lookup**: 600 kcmil falls in "Over 350 thru 600 kcmil" row
**Required GEC**: 1/0 copper or 3/0 aluminum

### Example 4: Small Service Installation

**Service conductors**: 4 AWG copper (100A service)
**Table lookup**: 4 AWG falls in "2 AWG or smaller" row
**Required GEC**: 8 AWG copper or 6 AWG aluminum

## GEC Installation Requirements

### Physical Protection (250.64(B))

**Protection required**: GEC must be protected from physical damage

**8 AWG and larger**: Protected where subject to physical damage
**6 AWG and smaller**: Protected for entire length

**Protection methods**:
- Installed in conduit (RMC, IMC, PVC)
- Guard strips where exposed
- Installed in protected locations

### Installation Methods (250.64(C))

**Continuous conductor**: GEC must be continuous from service equipment to grounding electrode
**Splices allowed**: Only by irreversible compression connectors, exothermic welding, or machine bolts
**Connections**: Must be accessible except for exothermic welds or concrete encasement

### Multiple Electrode Systems (250.64(D))

**Common GEC**: Single GEC can connect to multiple electrodes
**Grounding electrode conductor taps**: Allowed under specific conditions
**Sizing**: Size based on largest electrode served by each segment

**Tap conductor sizing**: Each tap conductor sized per Table 250.66 based on service conductors it serves

## Grounding Electrode Types and Requirements

### Metal Water Pipe (250.52(A)(1))

**Requirements**: 10 feet or more of buried metal water pipe
**Limitations**: Must supplement with additional electrode per 250.53(D)(2)
**Connection point**: Within 5 feet of water pipe entrance to building
**GEC sizing**: Full size per Table 250.66

### Concrete-Encased Electrode (250.52(A)(3))

**Ufer ground**: 20 feet of rebar or 4 AWG copper in concrete
**Installation**: Must be encased by at least 2 inches of concrete
**GEC connection**: Connect to reinforcing bar or copper conductor
**GEC sizing**: Limited to 4 AWG copper maximum per 250.66(A)

### Ground Rod Electrodes (250.52(A)(5))

**Requirements**: 8 feet long minimum, driven to 8-foot depth
**Resistance**: If single rod exceeds 25 ohms, install second rod
**Spacing**: Multiple rods spaced at least 6 feet apart
**GEC sizing**: Limited to 6 AWG copper maximum per 250.66(A)

### Plate Electrodes (250.52(A)(6))

**Requirements**: Minimum 2 square feet contact with earth
**Material**: Iron or steel plates ¼-inch thick, or nonferrous plates 0.06-inch thick
**Installation**: Buried at least 30 inches below grade
**GEC sizing**: Per Table 250.66 without limitation

## Special GEC Sizing Situations

### Separately Derived Systems (250.30)

**GEC sizing**: Based on derived conductor size, not service conductor size
**Table application**: Use Table 250.66 with derived system conductors
**Multiple systems**: Each system requires separate GEC sizing calculation

**Example**: 100A generator with 3 AWG conductors
- Table 250.66 lookup: 3 AWG = 8 AWG copper GEC required

### Buildings with Multiple Services (250.32)

**Each service**: Requires GEC sized per Table 250.66
**Common electrode**: Multiple GECs can connect to common grounding electrode
**Sizing**: Each GEC sized for its respective service

### High-Resistance Grounded Systems

**Special requirements**: Industrial systems with resistance grounding
**GEC sizing**: May require engineering analysis beyond Table 250.66
**Code reference**: 250.36 for high-resistance grounded systems

## Common GEC Sizing Mistakes

### 1. Wrong Conductor Reference
**Wrong**: Using main breaker size instead of conductor size
**Right**: Using actual service entrance conductor size per Table 250.66

### 2. Parallel Conductor Confusion
**Wrong**: Using individual parallel conductor size
**Right**: Adding parallel conductors together for table lookup

### 3. Electrode Limitations Ignored
**Wrong**: Installing 2 AWG GEC to ground rod
**Right**: Maximum 6 AWG to ground rod per 250.66(A)

### 4. Multiple Electrodes Incorrectly Sized
**Wrong**: Sizing GEC for smallest electrode
**Right**: Sizing for largest electrode, with taps sized appropriately

### 5. Aluminum vs Copper Confusion
**Wrong**: Using copper GEC size with aluminum GEC
**Right**: Using appropriate column from Table 250.66

## GEC Material and Installation Details

### Conductor Materials (250.62)

**Copper**: Most common, corrosion resistant, easy to work with
**Aluminum**: Acceptable but requires special connection methods
**Copper-clad aluminum**: Same requirements as aluminum
**Other materials**: Must be listed for grounding applications

### Connection Requirements (250.70)

**Grounding electrode connections**: Must be made with listed connectors
**Exothermic welding**: Permanent connection method for some applications
**Compression connectors**: Must be listed for specific application
**Bolted connections**: Machine bolts for some connections

### Corrosion Protection

**Dissimilar metals**: Avoid galvanic corrosion between different metals
**Underground connections**: Use appropriate materials for soil conditions
**Inspection access**: Connections must remain accessible for inspection

## Testing and Verification

### Ground Resistance Testing

**25-ohm rule**: Ground rod electrodes exceeding 25 ohms require supplemental electrode
**Testing methods**: Fall-of-potential, clamp-on meters, three-point testing
**When required**: New installations, troubleshooting, periodic maintenance

### Installation Verification

**Continuity testing**: Verify continuous path from service equipment to electrode
**Connection tightness**: Check all connections for proper torque
**Physical inspection**: Verify protection and routing compliance

### Documentation Requirements

**Installation records**: Keep records of GEC sizing calculations
**Test results**: Document ground resistance measurements
**Inspection reports**: Maintain inspection documentation for future reference

> **💡 Try this in Ask NETA.**
> 
> Need to size a grounding electrode conductor? The Ask NETA. app includes Table 250.66 with automatic sizing calculations. Just input your service conductor size and material—the app instantly tells you the required GEC size and any applicable limitations.

## GEC Quick Reference

### Common Service Sizes and Required GECs

**100A Service (4 AWG copper)**:
- Copper GEC: 8 AWG
- Aluminum GEC: 6 AWG

**200A Service (2/0 aluminum)**:
- Copper GEC: 4 AWG  
- Aluminum GEC: 2 AWG

**400A Service (500 kcmil copper)**:
- Copper GEC: 1/0 AWG
- Aluminum GEC: 3/0 AWG

### Electrode Limitations
- **Ground rods**: Maximum 6 AWG copper GEC
- **Concrete-encased**: Maximum 4 AWG copper GEC
- **Water pipe**: No GEC size limitation
- **Plate electrodes**: No GEC size limitation

### Installation Reminders
1. ✅ Protect 6 AWG and smaller GECs entirely
2. ✅ Protect larger GECs where subject to damage
3. ✅ Make connections accessible (except welded/encased)
4. ✅ Use irreversible connections for splices
5. ✅ Connect water pipe GEC within 5 feet of building entry

## Advanced GEC Applications

### Building Steel as Electrode (250.52(A)(2))

**Requirements**: Building steel effectively grounded to earth
**GEC sizing**: Per Table 250.66 without limitation
**Connection**: Direct connection to structural steel acceptable

### Ring Ground Systems

**Multiple electrodes**: Connected in continuous loop around building
**GEC connections**: Can connect to ring at multiple points
**Sizing**: Based on total system requirements

### Lightning Protection Coordination

**Bonding requirements**: Lightning protection systems must bond to electrical grounding
**Common electrodes**: Use same electrodes where possible
**Separation**: Maintain required separations between systems

## Frequently Asked Questions

### Can I use a larger GEC than Table 250.66 requires?
Yes, you can always use a larger conductor than the minimum required. This is often done for mechanical protection or future expansion considerations.

### Why are there maximum sizes for ground rods and concrete-encased electrodes?
These limitations exist because larger GECs don't significantly improve the grounding effectiveness of these electrode types. The 25-ohm ground resistance is the real limitation.

### Do I need to upsize the GEC if I upsize service conductors for voltage drop?
Yes, if you increase service conductor size beyond what's required for ampacity, you must also increase the GEC size accordingly per Table 250.66.

### Can I splice the GEC between the panel and grounding electrode?
Yes, but only with irreversible compression connectors, exothermic welding, or machine bolts. The connection must be accessible unless it's an exothermic weld or encased in concrete.

### What's the difference between GEC and equipment grounding conductor (EGC) sizing?
GECs are sized per Table 250.66 based on service conductors. EGCs are sized per Table 250.122 based on overcurrent protection device rating. They serve different functions and have different sizing rules.

## Master GEC Sizing Like a Pro

Grounding electrode conductor sizing is fundamental to electrical system safety and performance. While Table 250.66 provides the sizing requirements, understanding the underlying principles helps you make the right decisions for complex installations.

The grounding electrode system provides the connection between your electrical installation and the earth itself. Getting this connection right affects everything from voltage stability to personnel safety during fault conditions. Every properly sized GEC contributes to a safer, more reliable electrical system.

**Key principles for GEC sizing**:
1. Always base sizing on largest ungrounded service conductor
2. For parallel conductors, add individual sizes together
3. Apply electrode-specific limitations where applicable  
4. Provide proper physical protection per conductor size
5. Make all connections accessible unless specifically exempted

**Stop guessing—get the exact NEC answer in seconds. Download Ask NETA. free on iOS and Android.**

Whether you're sizing GECs for a simple residential service or complex commercial installation, Ask NETA. provides instant access to Table 250.66, sizing calculations, and installation requirements. Get your grounding systems right every time.
