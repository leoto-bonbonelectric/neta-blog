---
title: "Wire Size Calculator: Complete NEC Ampacity Guide"
description: "Calculate correct wire size for any electrical load. Includes NEC ampacity tables, voltage drop considerations, and step-by-step examples."
pubDate: 2026-01-10
author: "NETA. Team"
keywords: "wire size calculator, NEC ampacity table, AWG wire sizing, electrical wire calculator, conductor sizing NEC"
---

You're standing in the supply house, staring at a spool of 12 AWG wire, wondering if it'll handle that 25-amp motor you're installing. Sound familiar? Getting wire sizing wrong isn't just a code violation—it's a fire hazard that could shut down a job site and put your license on the line.

This complete wire size calculator guide walks you through NEC ampacity requirements, gives you the tools to size conductors correctly every time, and helps you avoid the costly mistakes that trip up even experienced electricians.

## Why Wire Sizing Matters (Beyond Just Passing Inspection)

Every electrician has seen the aftermath of undersized conductors: melted insulation, tripped breakers, and angry customers. But here's what many don't realize—wire sizing affects more than just safety:

- **Energy efficiency**: Undersized wires waste power through excess heat
- **Equipment lifespan**: Motors run hotter and fail sooner on undersized circuits  
- **Code compliance**: NEC Article 310 isn't just a suggestion—it's law in most jurisdictions
- **Liability protection**: Proper sizing protects you legally when something goes wrong

## NEC Wire Sizing Fundamentals

### Article 310: Your Wire Sizing Bible

NEC Article 310 covers conductors for general wiring, and it's where you'll find the ampacity tables that determine proper wire sizing. The key tables you need to know:

**Table 310.15(B)(16)** - Allowable Ampacities of Insulated Conductors (60°C, 75°C, 90°C)
**Table 310.15(B)(17)** - Allowable Ampacities for Single Insulated Conductors in Free Air

### The 80% Rule (NEC 210.20)

For continuous loads (operating 3+ hours), your conductor must handle 125% of the load current. This is where many electricians trip up.

**Example**: 20-amp continuous load requires a conductor rated for 25 amps minimum (20 × 1.25 = 25)

### Temperature Derating (NEC 310.15)

Temperature affects ampacity. Most residential work uses 75°C terminals, but industrial applications may require different calculations:

- **60°C terminals**: Use 60°C column (common in older equipment)
- **75°C terminals**: Use 75°C column (most modern equipment)  
- **90°C terminals**: Use 90°C column (high-temp applications)

## Wire Size Calculator Method

### Step 1: Determine Load Current

Start with the actual load you're feeding:
- Motor loads: Use nameplate FLA (Full Load Amperage)
- Lighting: Calculate total wattage ÷ voltage
- Mixed loads: Add all continuous and non-continuous loads

### Step 2: Apply NEC Factors

**Continuous loads**: Multiply by 125% (or 1.25)
**Multiple motors**: Use 125% of largest motor + 100% of other motors
**HVAC equipment**: Check nameplate for specific requirements

### Step 3: Check Ampacity Tables

Use Table 310.15(B)(16) for most applications:

| AWG Size | 60°C | 75°C | 90°C |
|----------|------|------|------|
| 14 | 15A | 20A | 25A |
| 12 | 20A | 25A | 30A |
| 10 | 30A | 35A | 40A |
| 8 | 40A | 50A | 55A |
| 6 | 55A | 65A | 75A |

### Step 4: Consider Voltage Drop

NEC recommends limiting voltage drop to 3% for branch circuits, 5% total for feeders and branch circuits combined. Use this formula:

**VD = (2 × K × I × L) ÷ CM**

Where:
- VD = Voltage drop (volts)
- K = 12.9 for copper, 21.2 for aluminum  
- I = Current (amps)
- L = Length (feet, one way)
- CM = Circular mils (from NEC Chapter 9, Table 8)

## Real-World Wire Sizing Examples

### Example 1: 240V Air Compressor

**Load**: 30-amp, 240V air compressor, 120 feet from panel
**Continuous**: No (intermittent use)
**Terminal rating**: 75°C

**Calculation**:
1. Load current: 30 amps
2. No continuous factor needed
3. From Table 310.15(B)(16), 75°C column: 10 AWG handles 35 amps ✓
4. Check voltage drop: VD = (2 × 12.9 × 30 × 120) ÷ 10,380 = 8.9V
5. 8.9V ÷ 240V = 3.7% voltage drop (exceeds 3% recommendation)
6. **Solution**: Use 8 AWG to reduce voltage drop to 2.3%

### Example 2: Kitchen GFCI Circuit

**Load**: 20-amp GFCI circuit, mixed lighting and receptacles, 50 feet
**Continuous**: Assume 50% continuous (lighting)  
**Terminal rating**: 75°C

**Calculation**:
1. Continuous load: 10 amps × 1.25 = 12.5 amps
2. Non-continuous load: 10 amps
3. Total: 22.5 amps required capacity
4. From Table 310.15(B)(16): 12 AWG handles 25 amps ✓
5. Voltage drop: Minimal at 50 feet for 20-amp load
6. **Solution**: 12 AWG THWN meets requirements

### Example 3: 3-Phase Motor Feed

**Load**: 460V, 3-phase motor, 42 FLA, 200 feet from panel
**Continuous**: Yes (operates > 3 hours)
**Terminal rating**: 75°C

**Calculation**:
1. Motor load: 42 amps × 1.25 = 52.5 amps
2. From Table 310.15(B)(16): 6 AWG handles 65 amps ✓
3. 3-phase voltage drop: VD = (1.732 × K × I × L) ÷ CM
4. Check if voltage drop acceptable for 6 AWG
5. **Solution**: 6 AWG meets both ampacity and voltage drop requirements

## Common Wire Sizing Mistakes to Avoid

### 1. Ignoring Continuous Loads
**Wrong**: Using 20-amp breaker for 20-amp continuous load
**Right**: Using 25-amp breaker (or larger conductor) for 20-amp continuous load

### 2. Wrong Temperature Column
**Wrong**: Using 90°C ampacity with 75°C terminals
**Right**: Matching ampacity to terminal temperature rating

### 3. Forgetting Voltage Drop
**Wrong**: Sizing only for ampacity on long runs
**Right**: Checking both ampacity AND voltage drop

### 4. Mixing Up Derating Factors
**Wrong**: Applying motor derating to lighting circuits
**Right**: Using appropriate factors for each load type

### 5. Overlooking Local Amendments
**Wrong**: Using only NEC without checking local codes
**Right**: Verifying local requirements that may be more restrictive

## Advanced Wire Sizing Considerations

### Parallel Conductors (NEC 310.10(H))

For loads exceeding 1000 kcmil copper capacity, use parallel runs:
- Minimum 1/0 AWG for parallel conductors
- Equal length, same material, same insulation
- Same termination methods

### Aluminum Conductors

When using aluminum:
- Use connections rated for aluminum
- Apply appropriate K-factor for voltage drop (21.2 vs 12.9)
- Consider thermal expansion differences
- Check local code acceptance

### High-Temperature Applications

For areas exceeding 30°C (86°F):
- Apply temperature correction factors from Table 310.15(B)(2)(a)
- Consider ventilation requirements
- May require conductor upsizing

## Wire Sizing Quick Reference

### Common Residential Loads
- **15A lighting circuits**: 14 AWG minimum
- **20A receptacle circuits**: 12 AWG minimum
- **Kitchen appliances**: 12 AWG (20A) or 10 AWG (30A)
- **Electric dryers**: 10 AWG (30A)
- **Electric ranges**: 8 AWG (40A) or 6 AWG (50A)
- **Central air units**: Size per nameplate + 125%

### Commercial/Industrial Sizing Tips
- Check for motor starting requirements
- Consider harmonics in neutral sizing
- Verify short circuit current ratings
- Plan for future load growth (25% spare capacity)

> **💡 Try this in Ask NETA.**
> 
> Need to size conductors on the job? The Ask NETA. app includes an interactive wire sizing calculator with built-in NEC tables. Just input your load, distance, and conditions—the app handles the calculations and references the exact code sections. No more flipping through the book or second-guessing your math.

## Frequently Asked Questions

### What's the difference between ampacity and amperage?
**Ampacity** is the maximum current a conductor can carry continuously without exceeding its temperature rating. **Amperage** is the actual current flowing through the conductor. Ampacity must always be greater than or equal to amperage.

### Can I use 90°C ampacity if my conductor is rated for 90°C?
Only if ALL components in the circuit are rated for 90°C, including terminals, breakers, and connections. Most equipment is rated for 75°C, so use the 75°C ampacity column.

### How do I size neutral conductors?
For linear loads, neutral carries the same current as phase conductors. For nonlinear loads (LEDs, computers), neutral may carry more current and require upsizing per NEC 310.15(B)(5)(c).

### What about wire sizing for solar installations?
Solar conductors follow NEC Article 690, which requires 125% of short circuit current. PV wire is typically rated for 90°C in wet locations and has different ampacity characteristics.

### Do I need to derate for conduit fill?
No. Conduit fill affects how many conductors you can fit (NEC Chapter 9), but doesn't directly affect ampacity unless you exceed the limits in Table 310.15(B)(3)(a).

## Master Wire Sizing Like a Pro

Getting wire sizing right isn't just about following tables—it's about understanding the complete picture: load characteristics, environmental conditions, voltage drop, and long-term reliability. Every wire you install is a reflection of your professionalism and commitment to safety.

The next time you're sizing conductors, remember these key points:
1. Calculate actual load with appropriate factors
2. Use correct temperature column for your terminals  
3. Check voltage drop on longer runs
4. Consider future load growth
5. Verify with local code requirements

**Stop guessing—get the exact NEC answer in seconds. Download Ask NETA. free on iOS and Android.**

When you need fast, accurate code answers on the job site, Ask NETA. delivers. Our AI assistant knows the current NEC, helps with calculations, and gives you the confidence to wire it right the first time.
