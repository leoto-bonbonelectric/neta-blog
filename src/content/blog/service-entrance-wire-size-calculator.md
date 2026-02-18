---
title: "Service Entrance Wire Sizing: NEC Article 230 Guide"
description: "Calculate service entrance conductor size using NEC 230. Includes load calculations, ampacity requirements, and sizing examples."
pubDate: 2026-01-23
author: "NETA. Team"
keywords: "service entrance wire size calculator, NEC article 230 conductors, service entrance conductor sizing"
---

You're bidding a service upgrade from 100 to 200 amps, and the utility line runs 180 feet from the transformer to the meter. The homeowner wants to know why you're quoting 3/0 aluminum instead of the 4/0 copper they found online. The difference? You're calculating for actual load, voltage drop, and local utility requirements—not just looking up a generic ampacity table.

This complete guide to service entrance conductor sizing covers NEC Article 230 requirements, load calculations, voltage drop considerations, and the real-world factors that determine proper service wire sizing.

## Why Service Entrance Sizing is Critical

Getting service conductors wrong isn't just a code violation—it affects everything downstream:

**Voltage regulation**: Undersized service conductors create voltage drop that affects all circuits
**Equipment protection**: Service equipment must handle available fault current
**Future expansion**: Service sizing affects ability to add loads later
**Utility requirements**: Must meet both NEC and utility company standards

## NEC 230 Service Conductor Requirements

### Basic Sizing Rules (230.42)

Service entrance conductors must be sized for:
1. **Calculated load** per Article 220
2. **Minimum size** requirements (230.42(B))
3. **Voltage drop** considerations (Informative Annex D)
4. **Available fault current** ratings

### Minimum Service Conductor Sizes

**Single-family dwellings** (230.42(B)):
- **100 ampere minimum** service for most installations
- **60 ampere minimum** for limited loads (rare, specific conditions)
- **Exception**: Loads calculated at 10 kVA or less may use 60-amp service

**Multi-family dwellings**:
- Each unit calculated separately
- Common area loads added
- Service sized for total calculated load

**Commercial/industrial**:
- No minimum size specified
- Sized based on calculated load only

## Service Load Calculation Methods

### Standard Method (220.82)

**For dwelling units**, use the standard calculation:

**Lighting and receptacles**: 3 VA per square foot
**Small appliance circuits**: 1,500 VA per circuit (minimum 2 circuits)  
**Laundry circuit**: 1,500 VA
**Fixed appliances**: Nameplate ratings
**HVAC**: Largest of heating or cooling load

**Demand factors**:
- First 3,000 VA at 100%
- 3,001-120,000 VA at 35%
- Remainder over 120,000 VA at 25%

### Optional Method (220.83)

**Alternative calculation** for dwelling units:
- Air conditioning and heating: 100% of larger load
- All other loads: 40% for first 10 kVA, then 30% for remainder
- Often results in smaller service size

### Example: 2,400 sq ft Home Calculation

**Standard method**:
- General lighting: 2,400 × 3 = 7,200 VA
- Small appliance circuits: 2 × 1,500 = 3,000 VA
- Laundry: 1,500 VA
- Range: 8,000 VA (nameplate)
- Air conditioning: 28,000 VA
- Electric heat: 15,000 VA (ignored, smaller than A/C)

**Total**: 39,700 VA
**Demand calculation**: 3,000 + (36,700 × 0.35) = 15,845 VA
**Service amperage**: 15,845 ÷ 240 = 66 amps
**Minimum service**: 100 amps (NEC requirement exceeds calculation)

## Service Conductor Sizing Tables

### Standard Service Ratings and Conductor Sizes

| Service Size | Copper THW | Aluminum THW |
|--------------|------------|--------------|
| 100A | 4 AWG | 2 AWG |
| 125A | 2 AWG | 1/0 AWG |
| 150A | 1 AWG | 2/0 AWG |
| 200A | 2/0 AWG | 4/0 AWG |
| 225A | 3/0 AWG | 250 kcmil |
| 400A | 500 kcmil | 750 kcmil |

**Note**: These are minimum sizes based on ampacity. Voltage drop may require larger conductors.

### Temperature Considerations

**Service conductor termination**: Most service equipment rated 75°C
**Conductor insulation**: Use 75°C column from Table 310.15(B)(16)
**High-temperature locations**: May require derating per 310.15(B)(2)(a)

## Voltage Drop in Service Conductors

### Service Drop vs Service Entrance

**Service drop**: Overhead conductors from utility to service point (utility responsibility)
**Service entrance**: Conductors from service point to service equipment (customer responsibility)

**Voltage drop consideration**: Total drop from transformer through service equipment

### Calculating Service Voltage Drop

Use the standard voltage drop formula with service-specific considerations:

**Single-phase**: VD = (2 × K × I × L) ÷ CM
**Three-phase**: VD = (1.732 × K × I × L) ÷ CM

**Service-specific factors**:
- Length includes service drop + service entrance
- Current based on calculated load, not breaker size
- Consider diversity factor for actual vs. calculated load

### Service Voltage Drop Example

**Installation**: 200-amp service, 150 feet total (drop + entrance)
**Load**: 160 amps calculated (80% of service rating)
**Conductor**: 4/0 aluminum (211,600 CM)

**Calculation**:
VD = (2 × 21.2 × 160 × 150) ÷ 211,600 = 4.8 volts
**Percentage**: 4.8V ÷ 240V = 2.0% ✓

**If using minimum 4/0**: Acceptable voltage drop
**If distance were 250 feet**: Would need larger conductors

## Special Service Installation Requirements

### Underground Service Entrance (230.32)

**Conductor protection**: Must be suitable for wet locations
**Conduit requirements**: Generally requires Schedule 40 PVC or RMC minimum
**Depth requirements**: Varies by location and voltage (Table 300.5)
**Conductor types**: USE, RHW, XHHW suitable for wet locations

**Common underground conductor types**:
- **USE-2**: Most common for direct burial applications
- **XHHW-2**: Suitable for wet locations, higher temperature rating
- **RHW-2**: Wet location rated, good for conduit applications

### Overhead Service Entrance (230.24)

**Clearance requirements**: Minimum heights over driveways, walkways, roofs
**Attachment height**: Minimum 10 feet above grade for up to 150V to ground
**Support requirements**: Service head, guy wires where required
**Conductor spacing**: Minimum separation between conductors

### Parallel Service Conductors (230.40 Exception)

**When allowed**: Services over 1,000 kcmil copper or 1,250 kcmil aluminum
**Requirements**:
- Minimum 1/0 copper or 2/0 aluminum per parallel set
- Same length, material, and cross-section
- Same termination method

## Service Equipment Considerations

### Service Disconnecting Means (230.70)

**Location**: Readily accessible, nearest practical point of service entrance
**Rating**: Must equal or exceed service conductor ampacity
**Grouping**: Maximum six disconnects allowed
**Emergency disconnect**: 2020 NEC requires readily accessible emergency disconnect

### Grounding and Bonding (250.24)

**Grounding electrode conductor**: Sized per Table 250.66
**Service bonding**: Main bonding jumper required
**Equipment grounding**: Service equipment must be bonded to grounded conductor

**Grounding electrode conductor sizes** (Table 250.66):

| Service Size | Copper GEC | Aluminum GEC |
|--------------|------------|--------------|
| 2 AWG or smaller | 8 AWG | 6 AWG |
| 1 AWG or 1/0 AWG | 6 AWG | 4 AWG |
| 2/0 or 3/0 AWG | 4 AWG | 2 AWG |
| Over 3/0 thru 350 kcmil | 2 AWG | 1/0 AWG |
| Over 350 thru 600 kcmil | 1/0 AWG | 3/0 AWG |

## Service Upgrade Considerations

### Existing Service Assessment

**Load analysis**: Calculate actual loads vs. available service
**Panel capacity**: Determine if main panel needs replacement
**Feeder adequacy**: Check if sub-panel feeders need upgrading
**Grounding system**: Verify compliance with current codes

### Utility Coordination

**Service application**: Submit load calculations to utility
**Equipment requirements**: Meter base, disconnect specifications
**Transformer adequacy**: Utility determines if transformer upgrade needed
**Connection scheduling**: Coordinate outage for service connection

### Common Service Upgrade Scenarios

**100A to 200A**: Most common residential upgrade
- Usually requires new panel, meter base, and service conductors
- May require utility transformer upgrade
- Often includes whole-house surge protection

**200A to 400A**: Large home or commercial upgrade
- Requires parallel conductors or larger single conductors
- Always requires utility coordination
- May need three-phase service conversion

## Material and Cost Considerations

### Copper vs Aluminum Service Conductors

**Copper advantages**:
- Smaller physical size
- Better termination characteristics
- Longer service life

**Aluminum advantages**:
- Lower material cost (typically 30-50% less)
- Lighter weight for installation
- Acceptable performance when properly installed

**Aluminum installation requirements**:
- Use only terminals rated for aluminum
- Apply proper joint compound
- Follow manufacturer torque specifications
- Consider expansion/contraction in long runs

### Service Conductor Costs (Approximate)

**200-amp service, 100 feet**:
- 2/0 copper: $800-1,200 material cost
- 4/0 aluminum: $400-600 material cost
- Installation labor: Similar for both

**Factors affecting cost**:
- Conductor length and size
- Underground vs overhead installation
- Local material availability
- Labor rates and complexity

## Troubleshooting Service Issues

### Voltage Problems

**Low voltage symptoms**:
- Lights dimming under load
- Motors running hot
- Equipment tripping breakers

**Causes**:
- Undersized service conductors
- Poor utility connections
- Overloaded transformer
- Damaged service conductors

**Solutions**:
- Measure voltage at service entrance
- Check all connections for resistance
- Contact utility for transformer issues
- Consider service conductor upgrade

### Service Equipment Problems

**Overheating main breaker**:
- Check for proper torque on connections
- Verify breaker rating matches load
- Look for signs of arcing or corrosion

**Panel capacity issues**:
- Calculate connected loads
- Consider load diversity factors
- Plan for future expansion needs

> **💡 Try this in Ask NETA.**
> 
> Planning a service upgrade? The Ask NETA. app includes a comprehensive service sizing calculator that handles load calculations, conductor sizing, and voltage drop analysis. Input your loads and installation details—the app calculates required service size and conductor specifications.

## Service Sizing Quick Reference

### Standard Residential Services
- **100 amp**: Minimum for most modern homes
- **125 amp**: Small homes with electric heat/cooling
- **150 amp**: Medium homes with multiple large appliances  
- **200 amp**: Standard for new construction
- **400 amp**: Large homes with extensive electric loads

### Load Calculation Shortcuts
- **General rule**: 200-amp service handles most residential loads
- **Electric everything**: May need 225-400 amp service
- **Future planning**: Consider EV charging, pool, workshop loads
- **Local requirements**: Some areas require minimum 200-amp service

### Voltage Drop Guidelines
- **Service conductors**: Keep under 2% if possible
- **Total system**: Service + branch circuits under 5%
- **Long runs**: Calculate voltage drop before final sizing
- **Utility coordination**: Check utility voltage regulation

## Code Compliance Checklist

### Service Installation Requirements
1. ✅ Load calculation per Article 220
2. ✅ Conductor sizing per ampacity tables
3. ✅ Voltage drop calculation and verification
4. ✅ Proper conductor insulation for location
5. ✅ Appropriate overcurrent protection
6. ✅ Grounding and bonding per Article 250
7. ✅ Clearance requirements per 230.24/230.32
8. ✅ Service disconnect location and rating
9. ✅ Emergency disconnect (2020 NEC and later)
10. ✅ Utility coordination and approval

## Frequently Asked Questions

### Can I use the same meter base when upgrading from 100 to 200 amps?
Generally no. 200-amp services require different meter bases with larger terminal capacity. The utility company will specify requirements for meter base upgrades.

### Why does my utility require larger conductors than NEC minimums?
Utilities often have more stringent voltage regulation requirements than the NEC. They may require larger conductors to maintain proper voltage at the service entrance.

### Do I need a permit for service conductor replacement?
Yes, service entrance work almost always requires permits and inspections. Contact your local electrical inspector before beginning work.

### Can I install aluminum service conductors myself?
If you're a licensed electrician, yes, but aluminum installation requires specific training and proper materials. Follow manufacturer specifications exactly to prevent connection problems.

### How do I know if my service conductors need upgrading?
Calculate your actual loads, measure service voltage under load conditions, and compare to current service capacity. Frequent tripping or low voltage symptoms indicate potential undersizing.

## Master Service Sizing Like a Pro

Service entrance conductor sizing combines electrical theory, code requirements, and real-world installation factors. Getting it right means creating an electrical system that safely delivers proper voltage and has capacity for future growth.

Every service installation affects the entire electrical system's performance. Undersized service conductors create voltage drop problems that expensive equipment and callbacks can't fix. Taking time to calculate loads properly, consider voltage drop, and coordinate with utility requirements prevents these issues.

**Key principles for service sizing**:
1. Calculate actual loads, don't just guess service size
2. Consider voltage drop over total service length
3. Plan for future load growth and code changes
4. Coordinate with utility requirements early in planning
5. Use proper materials and installation techniques for long-term reliability

**Stop guessing—get the exact NEC answer in seconds. Download Ask NETA. free on iOS and Android.**

Whether you're planning a new service installation or troubleshooting voltage problems, Ask NETA. provides instant access to load calculation methods, conductor sizing tables, and installation requirements. Get the service sizing right the first time.
