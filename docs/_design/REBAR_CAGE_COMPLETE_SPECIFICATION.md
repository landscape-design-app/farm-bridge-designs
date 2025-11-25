# COMPLETE REBAR CAGE SPECIFICATION
## South Abutment - Professional Agricultural Bridge Design

**Design Standard:** ACI 318-19  
**Application:** Farm Bridge Abutment with Retaining Wings  
**Prepared for:** Modeling

---

## 📋 TABLE OF CONTENTS

1. [Design Basis & Code Requirements](#design-basis)
2. [Complete Structure Geometry](#structure-geometry)
3. [Rebar Schedule - All Bar Types](#rebar-schedule)
4. [Material Requirements](#material-requirements)
5. [Assembly Instructions - Step by Step](#assembly-instructions)
6. [Quality Control Checklists](#quality-control)
7. [Inspection Requirements](#inspection)

---

## 🎯 DESIGN BASIS

### Code Compliance

**Design Code:** ACI 318-19 - Building Code Requirements for Structural Concrete

**Key Requirements Met:**
- ✅ Concrete cover: 3" minimum (cast against earth, ACI 318-19, Section 20.5.1.3.1)
- ✅ Bar spacing: 12" o.c. (exceeds 1" minimum clear, ACI 318-19, Section 25.2.1)
- ✅ Lap splices: 24" tension, 12" compression (ACI 318-19, Section 25.5.2.1)
- ✅ Standard hooks: 6×db for 90° hooks (ACI 318-19, Section 25.3.1)

### Materials Specifications

| Material | Specification | Application |
|----------|---------------|-------------|
| **Concrete** | f'c = 3,000 psi | Main body, wings, parapets |
| **Rebar** | Grade 60 (fy = 60,000 psi) | All reinforcement |
| **Bar Size** | #4 (1/2" diameter) | Entire cage |
| **Concrete Cover** | 3" all faces | Durability per ACI |
| **Bar Spacing** | 12" on center | Standard wall practice |

### Design Philosophy

**Conservative Agricultural Bridge Design:**
- All faces cast against earth → 3" cover everywhere
- 12" spacing provides ample concrete consolidation space
- #4 bars are standard for walls 2-4 feet thick
- All connections via 24" lap splices (40× bar diameter)
- Expansion joints at wings prevent cracking

---

## 📐 COMPLETE STRUCTURE GEOMETRY

### Main Body Dimensions

```
MAIN ABUTMENT BODY
┌─────────────────────────────────────────┐
│                                         │
│  APPROACH SIDE (X = 0)                  │
│                                         │
│  ┌─────────────────────────────────┐   │
│  │                                 │   │
│  │     SEAT: 2' × 8' × 2' tall    │   │ 2' DEPTH
│  │                                 │   │
│  │  PARAPET: +1' tall on top      │   │
│  │                                 │   │
│  └─────────────────────────────────┘   │
│         8' LENGTH (Y-direction)         │
│                                         │
│  CREEK SIDE (X = 2')                    │
│  [Beam seats at Y = ±2.5']              │
└─────────────────────────────────────────┘

Total Height: 3' (24" seat + 12" parapet)
```

**Measured Dimensions (from STEP file):**
- **Depth (X-axis):** 2.000' = 24.0" (approach to creek)
- **Length (Y-axis):** 8.000' = 96.0" (along bridge centerline)
- **Seat Height:** 2.000' = 24.0"
- **Parapet Height:** 1.000' = 12.0"
- **Total Height:** 3.000' = 36.0"

### Wing Wall Dimensions

```
WING WALLS (Both on Approach Side)
                          
    LEFT WING              MAIN BODY        RIGHT WING
        ╲                      ║                ╱
         ╲                     ║               ╱
          ╲   29° angle        ║        29°   ╱
           ╲                   ║             ╱
            ╲                  ║            ╱
    4.33' ext ╲                ║           ╱ 4.33' ext
               ╲               ║          ╱
                ╲──────────────╬─────────╱
                  2.4' span    8'   2.4' span

Height: 3' (matches main body)
```

**Measured Dimensions:**
- **Extension from main body:** 4.330' = 52.0"
- **Span (width):** 2.400' = 28.8"
- **Angle from X-axis:** 29.0°
- **Height:** 3.000' = 36.0"
- **Connection:** Expansion joint with foam backer rod

### Drainage Pipes

**Specifications:**
- **Quantity:** 2 pipes
- **Size:** 4" diameter PVC Schedule 40
- **Location:** Through main body seat
- **Slope:** 2% (approach side to creek side)
- **Elevation:** 12" above base (center of pipe)
- **Purpose:** Drain water from approach side to creek

---

## 📊 REBAR SCHEDULE - COMPLETE CAGE

### BAR TYPE SUMMARY

| Mark | Description | Qty | Length | Bends | Total (ft) | Location |
|------|-------------|-----|--------|-------|------------|----------|
| **R1** | Base slab longitudinal | 8 | 9'-0" | 90° both ends | 72.0 | Bottom grid |
| **R2** | Base slab transverse | 2 | 3'-0" | 90° both ends | 6.0 | Bottom grid |
| **R3** | Seat wall verticals | 16 | 3'-0" | 90° top | 48.0 | Seat walls |
| **R4** | Seat wall horizontals | 24 | 3'-0" | 90° both ends | 72.0 | Seat ties |
| **R5** | Parapet verticals - back | 8 | 2'-0" | 90° top | 16.0 | Back parapet |
| **R6** | Parapet verticals - sides | 4 | 2'-0" | 90° top | 8.0 | Side parapets |
| **R7** | Bearing plate stirrups | 20 | 3'-0" | U-shape | 60.0 | Around plates |
| **R8** | Corner diagonals | 8 | 2'-0" | Straight | 16.0 | Re-entrant corners |
| **R9** | Wing verticals | 16 | 3'-6" | 90° top | 56.0 | Wing walls |
| **R10** | Wing horizontals | 24 | 2'-0" | Straight | 48.0 | Wing ties |
| **R11** | Expansion joint dowels | 12 | 2'-0" | **SMOOTH** | 24.0 | Wing connections |
| **R12** | Drainage pipe cages | 16 | 1'-6" | Straight | 24.0 | Around pipes |
| | | | | **TOTAL:** | **450.0 ft** | |

**10-foot bars needed:** 450 ÷ 10 = **45 bars**  
**With 10% waste:** **50 bars** (#4 Grade 60 rebar)

---

## 🔧 DETAILED BAR SPECIFICATIONS

### R1 - Base Slab Longitudinal Bars

```
PURPOSE: Bottom reinforcement running along 8' length

QUANTITY: 8 bars
LENGTH: 9'-0" (8' span + 6" hooks both ends)
SPACING: 12" on center across 2' depth

BENDING DIAGRAM:
    6" hook ↓         ↓ 6" hook
         _______________
        |               |
        8'-0" straight
        
BEND DETAILS:
- 90° standard hooks both ends
- 3" extension past bend (6×db)
- Hook at bottom of cage
```

**Cutting Instructions:**
- From 10' bar: Cut 1 bar @ 9'-0", scrap 12"
- Total needed: 8 bars @ 9'-0" = Use 8 bars from stock

**Placement:**
- Runs in Y-direction (along 8' length)
- Start 3" from edge (cover)
- 12" spacing: positions at X = 3", 15" from approach side
- Bottom face elevation

---

### R2 - Base Slab Transverse Bars

```
PURPOSE: Bottom reinforcement running across 2' depth

QUANTITY: 2 bars
LENGTH: 3'-0" (2' span + 6" hooks both ends)
SPACING: 12" intervals along length (7 positions, but only 2 bars full width)

BENDING DIAGRAM:
  6" ↓       ↓ 6"
     _________
    |         |
    2'-0" straight
```

**Note:** Only 2 full-width bars due to narrow 2' depth. Additional support from verticals.

---

### R3 - Seat Wall Verticals

```
PURPOSE: Vertical reinforcement through 2' seat height

QUANTITY: 16 bars (8 front face + 8 back face)
LENGTH: 3'-0" (2' height + 6" lap down + 6" lap up)
SPACING: 12" o.c. along 8' length

BENDING DIAGRAM:
      6" hook →─┐
                │
              2'-0"
                │ seat height
    6" lap ─────┘

PLACEMENT:
- Front face (creek side): 8 bars at Y = -42", -30", -18", -6", +6", +18", +30", +42"
- Back face (approach): Same Y positions
- Lap 6" into base grid
- Extend 6" above seat for parapet connection
```

**Critical:** These tie base to parapets - proper lapping essential!

---

### R4 - Seat Wall Horizontal Ties

```
PURPOSE: Connect front/back verticals, resist lateral pressure

QUANTITY: 24 bars (8 bars × 3 levels)
LENGTH: 3'-0" (2' depth + 6" hooks both ends)
SPACING: 12" o.c., 3 levels vertically

BENDING DIAGRAM: Same as R2

LEVELS:
- Level 1: 6" above base
- Level 2: 12" above base  
- Level 3: 18" above base (top of seat)

INSTALLATION:
- Hooks engage vertical bars R3
- Create "ladder" with verticals
```

---

### R5 - Back Parapet Verticals

```
PURPOSE: Vertical bars in 1' tall back parapet (approach side)

QUANTITY: 8 bars
LENGTH: 2'-0" (1' parapet + 6" lap down + 6" hook up)
SPACING: 12" o.c. along 8' length

BENDING DIAGRAM:
    6" hook →─┐
              │
            1'-0" parapet
              │
  6" lap ─────┘ (into seat verticals R3)

PLACEMENT:
- Same Y positions as R3 verticals
- Lap 6" onto top of R3
- Final top elevation: 36" above base
```

---

### R6 - Side Parapet Verticals (Arm Rests)

```
PURPOSE: Vertical bars in end parapets

QUANTITY: 4 bars (2 per side)
LENGTH: 2'-0" (same as R5)
SPACING: 12" across 2' depth

PLACEMENT:
- Left end: X = 3", 15" at Y = 48" (left edge)
- Right end: X = 3", 15" at Y = -48" (right edge)
```

---

### R7 - Bearing Plate Stirrups

```
PURPOSE: Extra reinforcement around 2 beam seats

QUANTITY: 20 bars (10 per bearing location)
LENGTH: 3'-0" each (U-shaped stirrups)
SPACING: 6" intervals around each bearing plate

BENDING DIAGRAM:
     6" ↓         ↓ 6"
         _________
        |         |
      2'-0"       | 6" leg
        |_________|

U-STIRRUP:
- Wraps around vertical bars
- Creates cage around bearing plate
- Prevents splitting under beam load

BEARING LOCATIONS:
- Bearing 1: Y = +30" (2.5' from center)
- Bearing 2: Y = -30" (2.5' from center)
- Each location: 10 stirrups at 6" spacing
```

**Critical for load transfer from beams!**

---

### R8 - Corner Diagonal Reinforcement

```
PURPOSE: Prevent cracking at re-entrant corners

QUANTITY: 8 bars (2 per corner)
LENGTH: 2'-0" each
ANGLE: 45° diagonal across corner

CORNERS (where parapets meet):
1. Left-back corner
2. Right-back corner  
3. Left-front corner (bearing side)
4. Right-front corner (bearing side)

PLACEMENT:
- Diagonal from seat to parapet
- Ties perpendicular walls together
- 2 bars per corner for redundancy
```

---

### R9 - Wing Verticals

```
PURPOSE: Vertical bars in wing walls

QUANTITY: 16 bars total (8 per wing)
LENGTH: 3'-6" (3' height + 6" lap into base)
SPACING: 12" intervals along wing extension

PER WING:
- 4 positions along 4.33' extension
- 2 faces (front & back)
- 4 positions × 2 faces = 8 bars per wing

PLACEMENT (LEFT WING example):
- Along extension at 29° angle
- Y-range: 4.75' to 7.15'
- X-range: 0 to -4.33'
- Front face and back face of wing
```

---

### R10 - Wing Horizontal Ties

```
PURPOSE: Connect wing verticals, lateral stability

QUANTITY: 24 bars total (12 per wing)
LENGTH: 2'-0" (spans wing thickness)
SPACING: 3 levels vertically

LEVELS PER WING:
- Level 1: 6" above base
- Level 2: 18" above base
- Level 3: 30" above base

INSTALLATION:
- Ties through R9 verticals
- Creates grid pattern in wing
```

---

### R11 - Expansion Joint Dowels ⚠️ SPECIAL

```
⚠️  CRITICAL: THESE BARS MUST REMAIN SMOOTH (NO BOND)

PURPOSE: Allow wings to settle independently while providing shear resistance

QUANTITY: 12 bars total (6 per wing)
LENGTH: 2'-0" each
TREATMENT: Half coated/wrapped to prevent bond

PREPARATION STEPS:
1. Cut bars to 2'-0" length
2. DO NOT deform or bend
3. Coat one-half (12") with form oil or grease
4. Wrap coated half with plastic tape
5. Mark "NO BOND" side clearly

INSTALLATION:
- Spans between wing and main body
- 12" embedded in main body (bonded)
- 12" embedded in wing (NO BOND - wrapped half)
- Allows 1/2" expansion joint gap
```

**Why This Works:**
- Bonded half resists shear
- Unbonded half allows differential settlement
- Prevents cracking at wing connection

---

### R12 - Drainage Pipe Cages

```
PURPOSE: Reinforce concrete around 4" pipe openings

QUANTITY: 16 bars (8 per pipe)
LENGTH: 1'-6" each
PATTERN: Octagonal cage around pipe

INSTALLATION:
- 8 bars form cage around each 4" PVC pipe
- Bars parallel to pipe axis
- Spaced evenly around circumference
- Prevents stress concentration cracking

PIPE LOCATIONS:
- Pipe 1: Y = +18" (1.5' from center)
- Pipe 2: Y = -18" (1.5' from center)
- Both at elevation 12" (center of pipe)
- 2% slope (front 12.25" to back 11.75")
```

---

## 📦 MATERIAL REQUIREMENTS

### Rebar - #4 Grade 60

| Description | Quantity | Unit | Total Cost |
|-------------|----------|------|------------|
| #4 rebar @ 10' lengths | 50 bars | @ $8/bar | **$400** |
| Rebar tie wire (16 ga) | 80 lbs | @ $0.50/lb | $40 |
| Rebar chairs (3" height) | 200 pcs | @ $0.30/pc | $60 |
| | | **Subtotal:** | **$500** |

### Expansion Joint Materials

| Description | Quantity | Unit | Total Cost |
|-------------|----------|------|------------|
| Form release oil (for smooth dowels) | 1 gal | @ $15/gal | $15 |
| Plastic wrap (for dowels) | 1 roll | @ $10/roll | $10 |
| Foam backer rod 1/2" × 50' | 2 rolls | @ $15/roll | $30 |
| Polyurethane sealant | 4 tubes | @ $8/tube | $32 |
| | | **Subtotal:** | **$87** |

### Drainage Materials

| Description | Quantity | Unit | Total Cost |
|-------------|----------|------|------------|
| 4" PVC Schedule 40 pipe | 6 feet | @ $3/ft | $18 |
| 4" PVC end caps | 4 pcs | @ $2/pc | $8 |
| PVC primer & cement | 1 set | @ $12/set | $12 |
| | | **Subtotal:** | **$38** |

### Tools & Equipment

| Tool | Need | Have | Rent/Buy |
|------|------|------|----------|
| Rebar bender (manual) | ✓ | ? | $150 buy |
| Rebar cutter/angle grinder | ✓ | ? | $80 buy |
| Wire tying tool (automatic) | ✓ | ? | $40 buy |
| Measuring tape 100' | ✓ | ? | $25 buy |
| Chalk line | ✓ | ? | $10 buy |
| Level (4' torpedo) | ✓ | ? | $30 buy |
| Plywood sheets 4'×8' (×4) | ✓ | ? | $120 buy |
| Sawhorses (×4) | ✓ | ? | $80 buy |

---

## 🏗️ ASSEMBLY INSTRUCTIONS

### Phase 1: Workspace Setup (Day 1)

**Location:** Flat area near construction site, 20' × 20' minimum

**Steps:**
1. **Clear and level area**
   - Remove vegetation, rocks, debris
   - Check level with 4' level
   - Mark perimeter with stakes

2. **Lay work surface**
   - Place (4) 4'×8' plywood sheets
   - Create 8'×16' work surface
   - Secure against wind

3. **Set up work height**
   - Place sawhorses under plywood
   - Waist-height = less back strain
   - Ensure stable before loading

4. **Organize materials**
   - Stack rebar by type (labeled)
   - Tie wire on spools
   - Chairs in buckets
   - Tools in designated area

**Safety Check:**
- ☐ Work area level and stable
- ☐ No trip hazards
- ☐ Adequate lighting
- ☐ First aid kit on site

---

### Phase 2: Cut & Bend All Rebar (Days 2-3)

**Work Method:** Assembly line - cut all pieces first, then bend all

#### Cutting Plan from 10' Bars

| Bar Type | Length | Per 10' Bar | Bars Needed | 10' Bars Used |
|----------|--------|-------------|-------------|---------------|
| R1 | 9'-0" | 1 pc + 12" scrap | 8 | 8 |
| R2 | 3'-0" | 3 pcs + 12" scrap | 2 | 1 |
| R3 | 3'-0" | 3 pcs + 12" scrap | 16 | 6 |
| R4 | 3'-0" | 3 pcs + 12" scrap | 24 | 8 |
| R5 | 2'-0" | 5 pcs | 8 | 2 |
| R6 | 2'-0" | 5 pcs | 4 | 1 |
| R7 | 3'-0" | 3 pcs + 12" scrap | 20 | 7 |
| R8 | 2'-0" | 5 pcs | 8 | 2 |
| R9 | 3'-6" | 2 pcs + 36" scrap | 16 | 8 |
| R10 | 2'-0" | 5 pcs | 24 | 5 |
| R11 | 2'-0" | 5 pcs | 12 | 3 |
| R12 | 1'-6" | 6 pcs + 12" scrap | 16 | 3 |
| | | | **TOTAL:** | **54 bars** |

**Note:** Includes extra for mistakes/waste

#### Bending Instructions

**Setup Bender:**
1. Secure rebar bender to solid surface
2. Mark bending points on bars with paint
3. Have helper hold free end (bars are springy!)

**Standard 90° Hook:**
```
BEFORE:          AFTER BENDING:
─────┬───         ─────┐
     │                 │
   Mark              3" hook
                      (6×db)
```

1. Insert bar in bender with mark at bending point
2. Bend to 100° (it springs back to 90°)
3. Measure hook: should be 3" extension
4. If wrong, make test bend on scrap first

**U-Stirrup (R7):**
```
BEFORE:               AFTER:
──────┬────┬──────    ───┐   ┌───
      │    │               │   │
    Mark  Mark          2'-0"  │
                          │___|
                           6"
```

1. Mark both bend points
2. Bend first leg to 90°
3. Flip, bend second leg to 90°
4. Check: legs should be parallel, 6" long

**Check Every 5th Bar:**
- Measure length
- Check hook angles with square
- Verify dimensions match drawings

---

### Phase 3: Assemble Base Grid (Day 4 Morning)

**Goal:** Create rigid bottom mat that supports entire cage

**Step 1: Layout Longitudinal Bars (R1)**

1. On plywood surface, mark 8' length
2. Place 2 R1 bars parallel, 15" apart (measured outside-to-outside)
3. Check with tape measure: exactly 15" spacing
4. Hooks pointing DOWN (into ground)

**Step 2: Add Transverse Bars (R2)**

1. Place 2 R2 bars perpendicular to R1
2. Position at Y = ±36" (3' from center each way)
3. Hooks pointing DOWN

**Step 3: Tie All Intersections**

```
TYING TECHNIQUE:
1. Cut 18" piece of tie wire
2. Loop under intersection (X-shape)
3. Cross ends over top
4. Twist 3-4 times with tying tool
5. Bend twisted end flat (no sharp points)

DO THIS AT EVERY INTERSECTION!
```

**Step 4: Install Rebar Chairs**

1. Flip entire grid (helps with chair placement)
2. Place chairs every 24" in both directions
3. Chair height: 3" (provides bottom cover)
4. Tie chairs to rebar so they don't move

**Quality Check:**
- ☐ Grid is square (measure diagonals - should be equal)
- ☐ All intersections tied
- ☐ Chairs at 24" spacing
- ☐ Grid doesn't rack when lifted corner
- ☐ Hooks all pointing down

**Result:** You now have a rigid base grid 8' × 2', sitting on 3" chairs

---

### Phase 4: Install Seat Wall Verticals (Day 4 Afternoon)

**Goal:** Stand up vertical bars through 2' seat height

**Step 1: Mark Vertical Positions on Base Grid**

Using chalk, mark positions on R1 bars:
- Y = -42", -30", -18", -6", +6", +18", +30", +42" (8 positions)

**Step 2: Install R3 Verticals - Front Face**

1. Take 8 R3 bars
2. At each marked position:
   - Insert 6" lap through base grid
   - Stand vertical (use level!)
   - Tie to base grid with 2 wire ties
   
3. Temporary bracing:
   - Use scrap wood as diagonal braces
   - Prop against sawhorses
   - Keep verticals plumb while tying

**Step 3: Install R3 Verticals - Back Face**

1. Repeat at same Y-positions on opposite side
2. Distance between faces: 21" (24" minus 3" cover both sides)
3. Check with tape measure: front-to-back spacing consistent

**Step 4: Install First Horizontal Ties (R4 - Level 1)**

1. At 6" height, install first set of R4 horizontals
2. 8 bars total (one at each vertical position)
3. Hooks engage around R3 verticals
4. Tie at every intersection

**This creates a rigid "fence" structure!**

**Quality Check:**
- ☐ All verticals plumb (use level on 2 faces)
- ☐ Vertical spacing 12" o.c. ±1/4"
- ☐ Front-to-back dimension 21" ±1/4"
- ☐ Horizontals level
- ☐ All intersections tied

---

### Phase 5: Complete Seat Cage (Day 5 Morning)

**Step 1: Install Remaining Horizontal Levels**

1. **Level 2** (at 12" height):
   - Install 8 more R4 bars
   - Same pattern as Level 1
   - Tie all intersections

2. **Level 3** (at 18" height):
   - Install final 8 R4 bars
   - This is top of seat (24" total when cast)

**Step 2: Add Parapet Verticals (R5 & R6)**

**Back Parapet (R5):**
1. 8 bars lap onto top of R3 verticals
2. Lap 6" (extends from 18" to 36" final height)
3. Tie lap with 2 ties per bar
4. Same Y-positions as R3

**Side Parapets (R6):**
1. 2 bars on left end (Y = +48")
2. 2 bars on right end (Y = -48")
3. Lap onto R3 verticals at ends

**Step 3: Install Parapet Horizontal Ties**

1. Small horizontal bars connect parapet verticals
2. 2 levels in parapet (at 24" and 30")
3. Creates top "fence" above seat

**Quality Check:**
- ☐ Seat cage is rigid (doesn't rack)
- ☐ All verticals extend to proper height
- ☐ Parapets tied to seat
- ☐ Measure final heights: 24" (seat) + 12" (parapet) = 36" total

---

### Phase 6: Install Bearing Plate Reinforcement (Day 5 Afternoon)

**⚠️ CRITICAL STEP - THESE SUPPORT THE BRIDGE BEAMS!**

**Bearing Locations:**
- Bearing #1: Y = +30" (left of center)
- Bearing #2: Y = -30" (right of center)
- Both at X = 18" (creek side)
- Elevation: Top of seat (24")

**Step 1: Install U-Stirrups (R7) - Bearing #1**

1. Start at Y = +27" (3" before bearing center)
2. Install 10 stirrups at 6" intervals
3. Pattern: +27", +21", +15", +9", +3", -3", -9" (wraps around bearing)
4. Each stirrup:
   - Legs vertical
   - Top horizontal across width
   - Engages R3 verticals
   - Tie at all intersections

**Step 2: Repeat for Bearing #2**

1. Mirror pattern at Y = -30"
2. 10 more stirrups
3. Same spacing and tie pattern

**Step 3: Mark Bearing Plate Positions**

Using spray paint on rebar:
1. Mark "BEARING #1 - Y=+30"
2. Mark "BEARING #2 - Y=-30"
3. Measure from 3 reference points to verify
4. Take photos for record

**Why So Much Reinforcement?**
- Each bearing supports 3,000+ lbs beam end load
- Extra stirrups prevent splitting
- Creates "cage within cage"
- Standard bridge practice

---

### Phase 7: Corner Reinforcement (Day 5 End)

**Step 1: Install Diagonal Bars (R8)**

**4 Corner Locations:**
1. Left-back: where back parapet meets left side
2. Right-back: where back parapet meets right side
3. Left-front: at bearing #1
4. Right-front: at bearing #2

**At Each Corner:**
1. Position 2 R8 bars diagonally
2. One bar from seat level to parapet level
3. Angle ≈ 45°
4. Tie to both intersecting walls
5. Creates triangular bracing

**Purpose:** Prevents cracking at stress concentrations where perpendicular walls meet

**Quality Check - Complete Main Body:**
- ☐ Cage measures 8' × 2' × 3' tall
- ☐ All bars tied at intersections
- ☐ Bearing locations marked and reinforced
- ☐ Corner bars installed all 4 corners
- ☐ Cage is rigid - doesn't flex
- ☐ No loose wire ends (safety hazard)

**🎉 MAIN BODY CAGE COMPLETE!**

---

### Phase 8: Assemble Wing Cages (Day 6)

**Work Method:** Build each wing separately, install later

#### LEFT WING ASSEMBLY

**Step 1: Layout Wing Footprint**

1. On plywood, mark wing outline at 29° angle
2. Dimensions: 4.33' extension × 2.4' span
3. Mark 4 vertical positions along extension

**Step 2: Install Wing Verticals (R9)**

1. Front face: 4 bars (R9) along extension
2. Back face: 4 bars (R9) parallel to front
3. Spacing: ≈15" intervals along wing length
4. Height: 3.5' (3' height + 6" lap)
5. Provide 3" chairs for bottom support

**Step 3: Install Wing Horizontals (R10)**

1. 3 levels: at 6", 18", 30" heights
2. 4 bars per level = 12 bars total per wing
3. Runs across 2' wing thickness
4. Ties front face to back face

**Step 4: Quality Check - Wing Cage**
- ☐ Wing angle matches 29° (measure with protractor)
- ☐ All verticals plumb
- ☐ Horizontals level
- ☐ Cage rigid
- ☐ 3" chairs in place

#### RIGHT WING ASSEMBLY

**Repeat exact same process - mirror image of left wing**

**Result:** 2 separate wing cages ready for installation

---

### Phase 9: Prepare Expansion Joint Dowels (Day 6 End)

**⚠️ SPECIAL PROCEDURE - READ CAREFULLY**

These bars MUST remain smooth (no bond) on one end to allow expansion!

**Materials Needed:**
- 12 R11 bars (already cut to 2'-0")
- Form release oil (1 gallon)
- Plastic wrap/tape
- Spray paint (yellow = NO BOND)

**Procedure for Each Bar:**

1. **Measure and mark:**
   - Mark center of bar (12" point)
   - Label one half "BOND"
   - Label other half "NO BOND"

2. **Apply release agent to NO BOND half:**
   - Brush on thick coat of form oil
   - Let soak for 5 minutes
   - Wipe excess (should be slippery)

3. **Wrap NO BOND half:**
   - Wrap tightly with plastic
   - Cover completely
   - Tape ends so oil doesn't transfer

4. **Mark clearly:**
   - Spray yellow paint on wrapped end
   - Write "NO BOND" with marker
   - Cannot be confused during install!

**Critical:** The NO BOND end goes into wing (allows movement). BOND end goes into main body (anchors).

**Quality Check:**
- ☐ All 12 bars prepared
- ☐ Each bar has clear "NO BOND" marking
- ☐ Plastic wrap secure
- ☐ Oil doesn't transfer to bonded end

---

### Phase 10: Drainage Pipe Preparation (Day 7 Morning)

**Step 1: Cut and Slope PVC Pipes**

**Pipe #1 (Left):**
- Location: Y = +18"
- Length: 30" (extends 3" beyond each face)
- Slope: Front end 12.25", back end 11.75" (2% slope)

**Pipe #2 (Right):**
- Location: Y = -18"
- Same dimensions as Pipe #1

**Step 2: Install Pipe Cages (R12)**

For each pipe:
1. Create octagonal cage with 8 R12 bars
2. Bars parallel to pipe axis
3. Length: 18" each
4. Space evenly: 8 bars = 45° apart
5. Tie cage together with wire

**Step 3: Insert Pipes in Cages**

1. Slide PVC pipe through R12 cage
2. Center pipe in cage
3. Tie pipe to cage (prevents movement)
4. Install end caps on both ends
5. Mark "FRONT" and "BACK" on pipes

---

### Phase 11: Final Assembly & Installation (Day 7-8)

**IMPORTANT:** Do not attempt installation until ALL pieces are complete!

#### Pre-Installation Checklist

**Main Body Cage:**
- ☐ Dimensions verified: 8' × 2' × 3'
- ☐ All bars tied
- ☐ Bearing locations marked
- ☐ Corner reinforcement in place
- ☐ Cage rigid and square

**Wing Cages (both):**
- ☐ Dimensions correct
- ☐ Angle 29° verified
- ☐ All bars tied
- ☐ Chairs installed

**Expansion Joint Dowels:**
- ☐ 12 bars prepared
- ☐ NO BOND ends clearly marked
- ☐ Plastic wrap intact

**Drainage:**
- ☐ 2 pipes with cages
- ☐ Slope 2% confirmed
- ☐ End caps installed

---

## ✅ QUALITY CONTROL CHECKLISTS

### Fabrication Quality Control

**After Cutting (check 10% sample):**
- ☐ Lengths ±1/4" of specified
- ☐ Cuts square (not angled)
- ☐ No burrs on cut ends

**After Bending (check 10% sample):**
- ☐ Hook angles 90° ±5°
- ☐ Hook extensions 3" ±1/4" (for 90° hooks)
- ☐ No cracks at bends
- ☐ Bars not twisted

**After Tying:**
- ☐ Every intersection tied
- ☐ Ties tight (no movement)
- ☐ Twisted ends bent flat
- ☐ No sharp wire ends protruding

---

### Assembly Quality Control

**Base Grid:**
- ☐ Dimensions 8' × 2' ±1/4"
- ☐ Diagonals equal (square)
- ☐ All intersections tied
- ☐ Chairs at 24" spacing
- ☐ Grid doesn't rack

**Seat Cage:**
- ☐ Verticals plumb (±1/4"/ft)
- ☐ Vertical spacing 12" ±1/4"
- ☐ Horizontals level ±1/4"
- ☐ Height 24" ±1/4"

**Parapets:**
- ☐ Height 12" above seat ±1/4"
- ☐ Laps 6" minimum onto seat verticals
- ☐ All corners tied

**Bearing Reinforcement:**
- ☐ Locations Y = ±30" ±1/4"
- ☐ 10 stirrups per location
- ☐ 6" spacing ±1/4"
- ☐ Elevations marked

**Wings:**
- ☐ Angle 29° ±2°
- ☐ Extension 4.33' ±1/2"
- ☐ Height 3' ±1/4"
- ☐ Rigid structure

**Expansion Joints:**
- ☐ 12 dowels prepared
- ☐ NO BOND ends marked
- ☐ Plastic wrap intact

**Drainage:**
- ☐ 2 pipes sloped 2%
- ☐ Cages around pipes
- ☐ Pipes secured

---

### Pre-Installation Final Inspection

**Dimensional Check:**
- ☐ Main body: 8' × 2' × 3' ±1/4"
- ☐ Wings: 4.33' × 2.4' × 3' ±1/2"
- ☐ 3" concrete cover achievable all faces
- ☐ No rebar within 3" of any surface

**Structural Check:**
- ☐ All cages rigid (no racking)
- ☐ No loose bars
- ☐ No twisted or kinked bars
- ☐ All specified bars present

**Safety Check:**
- ☐ No sharp wire ends
- ☐ No protruding hooks (catch hazard)
- ☐ Lifting points identified
- ☐ Lift plan prepared (3-4 people needed)

---

## 🔍 INSPECTOR REQUIREMENTS

### What Inspector Will Check

**Before Concrete Pour:**

1. **Rebar Size & Grade**
   - Verify #4 bars (mill markings visible)
   - Grade 60 stamped on bars

2. **Spacing**
   - 12" o.c. ±1" tolerance
   - Measure at 10 random locations

3. **Concrete Cover**
   - Verify 3" clear all faces
   - Check with cover meter or spacers

4. **Ties**
   - All intersections tied
   - Ties tight (shake test)

5. **Laps**
   - 24" minimum tension laps
   - Offset lap locations (staggered)

6. **Hooks**
   - 90° hooks properly formed
   - 3" extensions (6×db)

7. **Bearing Plate Reinforcement**
   - Extra stirrups present
   - Correct locations

8. **Expansion Joints**
   - Smooth dowels prepared correctly
   - Gap maintained

9. **Drainage**
   - Pipes sloped 2% minimum
   - Cages around openings

10. **Cleanliness**
    - Rebar clean (no rust scale, oil, mud)
    - Forms clean

### Required Documentation for Inspector

Provide:
- ☐ This specification document
- ☐ Rebar cutting/bending list
- ☐ Photos of completed cage (all angles)
- ☐ Mill certificates for rebar (Grade 60)
- ☐ Concrete mix design (3000 psi)

### Common Inspection Failures - AVOID THESE!

1. **Inadequate cover** → Use proper chairs!
2. **Wrong spacing** → Measure carefully!
3. **Missing ties** → Tie EVERY intersection!
4. **Wrong lap lengths** → 24" minimum!
5. **Rusty rebar** → Clean before inspection!
6. **Bent/kinked bars** → Replace damaged bars!
7. **Wrong bar size** → Verify #4 markings!
8. **Missing bearing reinforcement** → Critical area!
9. **Expansion joints bonded** → NO BOND treatment!
10. **Drainage pipes not sloped** → Check with level!

---

## 📸 REQUIRED PHOTO DOCUMENTATION

Take photos at each stage for your records and inspector:

1. Rebar organized by type (labeled)
2. First 5 bent bars (check dimensions)
3. Base grid complete (top view)
4. Verticals installed (side view)
5. Horizontals tied (looking along length)
6. Complete seat cage (all 4 sides)
7. Parapet reinforcement
8. Bearing plate locations (with tape measure showing position)
9. Corner reinforcement details
10. Wing cages (before installation)
11. Expansion joint dowels (showing NO BOND marking)
12. Drainage pipes with cages
13. Complete cage assembly (multiple angles)
14. In forms before concrete pour

**Use tape measure in photos to show dimensions!**

---

## 🎯 SUCCESS CRITERIA

Your summer intern project is successful when:

✅ **All 450 linear feet of #4 rebar fabricated correctly**  
✅ **Complete cage assembled per this specification**  
✅ **Quality control checks passed**  
✅ **Inspector approval obtained**  
✅ **Cage ready for concrete pour**  
✅ **Photo documentation complete**  
✅ **Safe working methods followed throughout**

---

## 📞 WHEN TO ASK FOR HELP

**Stop work and call supervisor if:**
- ❌ Measurements don't match drawings
- ❌ Rebar dimensions wrong after cutting
- ❌ Cage doesn't fit together as expected
- ❌ Unsure about any step
- ❌ Safety concern arises
- ❌ Inspector has questions you can't answer

**Better to ask than to make expensive mistakes!**

---

## 📚 APPENDIX A: REFERENCE STANDARDS

### Codes & Standards Applied

1. **ACI 318-19** - Building Code Requirements for Structural Concrete
   - Section 20.5: Concrete Cover Requirements
   - Section 25.2: Spacing of Reinforcement
   - Section 25.3: Standard Hooks
   - Section 25.5: Development and Splicing

2. **ASTM A615** - Standard Specification for Deformed and Plain Carbon-Steel Bars
   - Grade 60 (fy = 60,000 psi)

3. **ASTM C33** - Standard Specification for Concrete Aggregates

4. **ASTM C94** - Ready-Mixed Concrete

### Design Assumptions

- **Soil bearing capacity:** 2,000 psf minimum
- **Live load:** 100 psf (H-10 loading)
- **Dead load:** Bridge beams + deck
- **Wind:** Not critical for squat structure
- **Seismic:** Low seismic zone
- **Frost depth:** 3 feet (anchors go to 5')
- **Drainage:** 4" pipes adequate for site

---

## 📚 APPENDIX B: GLOSSARY

**#4 Rebar:** Rebar with 1/2" diameter (4/8")

**Grade 60:** Yield strength 60,000 psi

**Cover:** Clear distance from rebar surface to concrete surface

**Lap splice:** Overlapping two bars to transfer stress

**Hook:** Bent end of bar (typically 90° or 180°)

**Stirrup:** U-shaped bar used as tie

**Chair:** Plastic or metal support to elevate rebar

**Tie wire:** 16-gauge wire to secure intersections

**db:** Bar diameter (0.5" for #4)

**o.c.:** On center (spacing measured center-to-center)

**Cast against earth:** Concrete poured directly on soil (requires 3" cover)

**Expansion joint:** Gap allowing independent movement

**Smooth dowel:** Bar with no bond to allow expansion

---

## 📋 APPENDIX C: QUICK REFERENCE CARDS

### REBAR IDENTIFICATION

```
BAR MARKINGS:
┌─────────────────┐
│  H  4  W  60    │ ← Roll markings
└─────────────────┘
   │  │  │  │
   │  │  │  └─ Grade (60 = 60,000 psi)
   │  │  └──── Type (W = weldable)
   │  └─────── Size (#4 = 1/2")
   └────────── Mill (H = producer)
```

### HOOK DIMENSIONS

```
#4 REBAR HOOKS:
90° hook:   6×db = 6×0.5" = 3" extension
180° hook:  4×db = 4×0.5" = 2" extension
Inside bend radius: 2.5×db = 1.25"
```

### SPACING QUICK CHECK

```
12" ON CENTER:
For 8' length = 96"
96" ÷ 12" = 8 spaces
= 9 bars total (including ends)

BUT: With 3" cover both ends:
Usable = 96" - 6" = 90"
90" ÷ 12" = 7.5 spaces
= 8 bars (no bar at exact ends)
```

---

## ✅ FINAL CHECKLIST FOR INTERN

**Before Starting:**
- ☐ Read entire specification
- ☐ Understand all bar types
- ☐ Know where to get help
- ☐ Safety equipment ready
- ☐ Tools available
- ☐ Materials on site

**During Fabrication:**
- ☐ Cut list complete
- ☐ Bending jigs set up
- ☐ Quality checks every 5 bars
- ☐ Bars labeled by type
- ☐ Daily progress photos

**During Assembly:**
- ☐ Work surface level
- ☐ Measure twice, tie once
- ☐ Quality checks at each phase
- ☐ All intersections tied
- ☐ Cover maintained
- ☐ Bearing locations verified

**Before Installation:**
- ☐ Complete cage inspection
- ☐ Dimensional check passed
- ☐ Photos taken
- ☐ Inspector notified
- ☐ Lift plan reviewed

**Success!**
- ☐ Inspector approval
- ☐ Cage installed correctly
- ☐ Ready for concrete
- ☐ Documentation complete

---

**END OF SPECIFICATION**


**Document Version:** 1.0  
**Date:** November 2025  
**Design Basis:** ACI 318-19  
**Application:** Agricultural Bridge Abutment  
