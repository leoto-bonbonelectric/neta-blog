---
title: "Voltage Drop Formula: Calculate Like a Pro"
description: "Learn the NEC voltage drop formula with practical examples. Calculate voltage drop for any circuit and ensure code compliance."
pubDate: 2026-01-17
author: "NETA. Team"
keywords: "voltage drop calculation formula electrician, voltage drop formula NEC, circuit voltage drop calculator"
---

You're running a 240V circuit to a workshop 150 feet from the panel, and the customer complains that their table saw keeps tripping the breaker. You check the connections, the breaker, even the saw itself—everything looks fine. Then you measure the voltage at the outlet: 210 volts. That's your problem right there: excessive voltage drop that's starving the motor and causing nuisance trips.

This complete guide to voltage drop calculations will teach you the formulas, show you real-world examples, and help you size conductors that deliver proper voltage to every load—preventing callbacks and keeping equipment running smoothly.

## Why Voltage Drop Matters More Than You Think

Voltage drop isn't just a code guideline—it directly affects how equipment performs and how long it lasts:

**Motor performance**: Motors draw higher current at lower voltages, generating excess heat
**Equipment lifespan**: Undervoltage conditions shorten motor life significantly
**Energy efficiency**: Voltage drop wastes power as heat in conductors
**Code compliance**: NEC recommends limiting voltage drop to prevent these problems

## NEC Voltage Drop Recommendations

### The 3% and 5% Rules

While not mandatory, NEC Informative Annex D recommends:
- **3% maximum** for branch circuits
- **5% maximum** total for feeders plus branch circuits combined
- **2% for feeders** + 3% for branch circuits = 5% total

### Why These Limits?

These percentages represent the point where voltage drop starts affecting equipment performance:
- **120V branch circuit**: 3% = 3.6V drop (116.4V delivered)
- **240V branch circuit**: 3% = 7.2V drop (232.8V delivered)
- **480V feeder**: 2% = 9.6V drop (470.4V delivered)

Most equipment can handle these minor variations without performance degradation.

## The Voltage Drop Formula

### Basic Formula (Single-Phase)

**VD = (2 × K × I × L) ÷ CM**

Where:
- **VD** = Voltage drop (volts)
- **K** = Resistance constant (12.9 for copper, 21.2 for aluminum)
- **I** = Current (amps)
- **L** = Length (feet, one-way distance)
- **CM** = Circular mils (from NEC Chapter 9, Table 8)

### Three-Phase Formula

**VD = (1.732 × K × I × L) ÷ CM**

The 1.732 factor (√3) accounts for the phase relationship in balanced three-phase systems.

### DC Circuit Formula

**VD = (K × I × L) ÷ CM**

No "2" multiplier since current flows one way only (positive to negative).

## Resistance Constants and Circular Mils

### K-Factor Values

| Material | Resistance Constant (K) |
|----------|-------------------------|
| Copper | 12.9 |
| Aluminum | 21.2 |
| Copper-clad aluminum | 21.2 |

### Common Conductor Circular Mils (Table 8)

| AWG Size | Circular Mils |
|----------|---------------|
| 14 | 4,107 |
| 12 | 6,530 |
| 10 | 10,380 |
| 8 | 16,510 |
| 6 | 26,240 |
| 4 | 41,740 |
| 2 | 66,360 |
| 1/0 | 105,600 |
| 2/0 | 133,100 |
| 3/0 | 167,800 |
| 4/0 | 211,600 |

## Real-World Voltage Drop Calculations

### Example 1: Residential Air Conditioner

**Load**: 240V central air unit, 30 amps, 80 feet from panel
**Conductor**: 10 AWG copper
**Circuit type**: Single-phase

**Calculation**:
VD = (2 × 12.9 × 30 × 80) ÷ 10,380
VD = 61,920 ÷ 10,380 = 5.96 volts

**Percentage**: 5.96V ÷ 240V = 2.48% ✓ (under 3% limit)

### Example 2: Workshop Circuit (Excessive Drop)

**Load**: 240V table saw, 25 amps, 150 feet from panel
**Conductor**: 12 AWG copper
**Circuit type**: Single-phase

**Calculation**:
VD = (2 × 12.9 × 25 × 150) ÷ 6,530
VD = 96,750 ÷ 6,530 = 14.8 volts

**Percentage**: 14.8V ÷ 240V = 6.17% ✗ (exceeds 3% limit)

**Solution**: Upgrade to 8 AWG copper
VD = (2 × 12.9 × 25 × 150) ÷ 16,510 = 5.86 volts = 2.44% ✓

### Example 3: Three-Phase Motor Feeder

**Load**: 480V motor, 50 amps, 200 feet from panel
**Conductor**: 6 AWG copper
**Circuit type**: Three-phase

**Calculation**:
VD = (1.732 × 12.9 × 50 × 200) ÷ 26,240
VD = 223,636 ÷ 26,240 = 8.52 volts

**Percentage**: 8.52V ÷ 480V = 1.78% ✓ (under 2% feeder limit)

### Example 4: Long Aluminum Service

**Load**: 200-amp service, 300 feet underground
**Conductor**: 4/0 aluminum
**Circuit type**: Single-phase equivalent (240V)

**Calculation**:
VD = (2 × 21.2 × 200 × 300) ÷ 211,600
VD = 2,544,000 ÷ 211,600 = 12.02 volts

**Percentage**: 12.02V ÷ 240V = 5.01% ✗ (slightly over 5% total)

**Solution**: Consider parallel conductors or upgrade to larger size

## Solving for Other Variables

### Finding Required Conductor Size

Rearrange the formula to solve for CM:

**CM = (2 × K × I × L) ÷ VD**

**Example**: What conductor size for 30A, 120V, 100 feet, 3% drop?
- Allowable VD = 120V × 0.03 = 3.6V
- CM = (2 × 12.9 × 30 × 100) ÷ 3.6 = 21,500 CM
- From Table 8: 6 AWG (26,240 CM) required

### Finding Maximum Circuit Length

Rearrange to solve for L:

**L = (VD × CM) ÷ (2 × K × I)**

**Example**: How far can you run 12 AWG for 20A, 120V, 3% drop?
- Allowable VD = 120V × 0.03 = 3.6V
- L = (3.6 × 6,530) ÷ (2 × 12.9 × 20) = 45.5 feet

### Finding Maximum Load Current

Rearrange to solve for I:

**I = (VD × CM) ÷ (2 × K × L)**

**Example**: Maximum current for 10 AWG, 120V, 80 feet, 3% drop?
- Allowable VD = 120V × 0.03 = 3.6V  
- I = (3.6 × 10,380) ÷ (2 × 12.9 × 80) = 18.1 amps

## Voltage Drop in Different Wiring Methods

### Conduit vs. Cable Installations

**Metal conduit**: Use individual conductor values from Table 8
**NM cable**: Same as conduit (individual conductors)
**MC cable**: Check manufacturer data for actual resistance
**Armored cable**: May have higher resistance due to construction

### Parallel Conductor Installations

When using parallel conductors:
1. Calculate voltage drop for single conductor
2. Divide by number of parallel paths
3. All parallel conductors must be identical and equal length

**Example**: Two 2/0 copper conductors in parallel
- Single 2/0 CM = 133,100
- Parallel CM = 133,100 × 2 = 266,200 CM equivalent

### Underground Installations

**Direct burial**: Use standard calculations
**Conduit underground**: Add derating for high temperatures if applicable
**Aluminum conductors**: More sensitive to temperature—consider larger sizes

## Common Voltage Drop Mistakes

### 1. Using Wrong Circuit Length
**Wrong**: Using total conduit run length
**Right**: Using one-way distance from source to load

### 2. Forgetting the "2" Factor
**Wrong**: VD = (K × I × L) ÷ CM for single-phase
**Right**: VD = (2 × K × I × L) ÷ CM for single-phase

### 3. Wrong Resistance Constant
**Wrong**: Using copper K-factor for aluminum conductors  
**Right**: K = 12.9 for copper, K = 21.2 for aluminum

### 4. Mixing Voltage Levels
**Wrong**: Calculating 120V drop, applying to 240V circuit
**Right**: Using actual circuit voltage for percentage calculations

### 5. Ignoring Load Growth
**Wrong**: Calculating for nameplate load only
**Right**: Consider future load increases and motor starting currents

## Advanced Voltage Drop Considerations

### Motor Starting Requirements

**Starting current**: Can be 6-8 times running current
**Voltage drop during starting**: May require larger conductors
**Soft starters**: Reduce starting current and voltage drop
**Variable frequency drives**: Consider harmonic effects on resistance

### Harmonics and Voltage Drop

**Nonlinear loads**: LEDs, computers, VFDs create harmonics
**Increased resistance**: Harmonics increase effective conductor resistance
**Neutral conductors**: May carry more current than anticipated
**Consideration**: Use 125% of calculated current for harmonic loads

### Temperature Effects

**High-temperature locations**: Increase conductor resistance
**Underground installations**: Consider soil temperature
**Ambient correction**: May require larger conductors beyond voltage drop needs

### Aluminum Conductor Special Considerations

**Higher resistance**: Use 21.2 K-factor instead of 12.9
**Thermal expansion**: More sensitive to temperature changes
**Connection quality**: Critical for long-term reliability
**Sizing**: Often requires one size larger than copper equivalent

> **💡 Try this in Ask NETA.**
> 
> Calculating voltage drop on the job? The Ask NETA. app includes an advanced voltage drop calculator that handles single-phase, three-phase, and DC circuits. Input your load, distance, and conductor—the app calculates voltage drop and recommends conductor upgrades if needed.

## Voltage Drop Quick Reference

### Maximum Recommended Distances (3% Drop)

**120V, 15A, 14 AWG**: 45 feet
**120V, 20A, 12 AWG**: 45 feet  
**240V, 30A, 10 AWG**: 80 feet
**240V, 40A, 8 AWG**: 75 feet
**480V, 50A, 6 AWG**: 225 feet

### Conductor Upgrade Guidelines

**Excessive voltage drop symptoms**:
- Motors running hot
- Lights dimming under load
- Equipment tripping prematurely
- Reduced equipment performance

**Quick fixes**:
- Upgrade conductor size (most common)
- Reduce circuit length (if possible)
- Split load into multiple circuits
- Use higher voltage (240V vs 120V)

### Planning Guidelines

**New installations**: Calculate voltage drop before rough-in
**Service upgrades**: Check voltage drop to existing loads
**Motor circuits**: Consider starting current requirements
**Long runs**: Always calculate—don't estimate

## Voltage Drop Calculation Tools

### Manual Calculation Steps

1. Identify load current (nameplate or calculated)
2. Measure one-way distance accurately
3. Select appropriate formula (single-phase, three-phase, DC)
4. Use correct K-factor and CM values
5. Calculate voltage drop in volts
6. Convert to percentage of nominal voltage
7. Compare to NEC recommended limits

### Digital Tools and Apps

**Benefits of calculator apps**:
- Eliminate calculation errors
- Include comprehensive conductor databases
- Handle complex installations quickly
- Provide conductor upgrade recommendations

**Field measurement verification**:
- Measure actual voltage at load
- Compare to calculated values
- Identify connection resistance issues
- Verify calculations accuracy

## Frequently Asked Questions

### Why does the NEC recommend 3% instead of requiring it?
The NEC focuses on safety, not performance. 3% drop rarely creates safety hazards but can affect equipment performance. Local codes may make these requirements mandatory.

### Can I exceed 3% voltage drop if the equipment works fine?
Technically yes, since it's a recommendation not a requirement. However, you may face liability issues if equipment problems arise later due to voltage drop.

### Do I need to calculate voltage drop for every circuit?
Not necessarily. Short circuits with appropriate conductor sizes rarely have voltage drop issues. Focus on long runs, large loads, and critical equipment.

### How do I handle circuits with multiple loads?
Calculate using the total circuit current and the distance to the farthest load. This gives you the worst-case scenario for voltage drop.

### What if I can't upgrade the conductor size?
Consider splitting the load into multiple circuits, using higher voltage if possible, or relocating the power source closer to the load.

## Master Voltage Drop Like a Pro

Understanding voltage drop calculation isn't just about following NEC recommendations—it's about delivering reliable power that keeps equipment running efficiently for years. Every time you properly size conductors for voltage drop, you're preventing future service calls and protecting equipment investments.

The physics of electricity doesn't compromise, and neither should your calculations. Voltage drop affects every electrical installation, from the smallest branch circuit to the largest industrial feeder. Getting it right means equipment runs cooler, more efficiently, and with fewer problems.

**Key principles to remember**:
1. Calculate voltage drop for all significant loads and long runs
2. Use actual load current, not breaker size
3. Consider future load growth and motor starting requirements
4. Verify calculations with field measurements when possible
5. When in doubt, go larger—the small additional cost prevents big problems later

**Stop guessing—get the exact NEC answer in seconds. Download Ask NETA. free on iOS and Android.**

Whether you're sizing service entrance conductors or troubleshooting equipment performance issues, Ask NETA. provides instant voltage drop calculations with step-by-step breakdowns. Get the math right every time, and keep your installations running at peak performance.
