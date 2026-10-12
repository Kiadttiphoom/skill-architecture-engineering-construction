# Skill: Architecture, Engineering & Construction (AEC)

A comprehensive multidisciplinary reasoning engine for AI agents, architects, and engineers covering **Architecture, Engineering, and Construction (AEC)** with specific statutory calibration for **Thailand's Building Control Laws, National Structural Standards, and MEP Codes**.

---

## 📌 Overview & Philosophy

This skill equips AI models with the analytical capability of a coordinated **12-discipline professional consulting team**:
> *Architect · Civil Engineer · Structural Engineer · Geotechnical Engineer · Construction Engineer · Electrical Engineer · Plumbing & Sanitary Engineer · Mechanical/HVAC Engineer · Fire-Protection Engineer · Interior Architect · Materials Specialist · Quantity Surveyor*

### Core Tenet
**No Aesthetic Guesswork & No Invented Numbers:** Every architectural proposition must satisfy structural load paths, soil bearing capacities, statutory setbacks, MEP shaft access, and fire evacuation geometry before being finalized.

---

## 🏗️ Directory Architecture

```text
skill/architecture-engineering/
├── README.md                           # Master documentation & technical overview
├── SKILL.md                            # AI System prompt, non-negotiable rules & team protocol
├── RESEARCH_SOURCES.md                 # Traceable legal & engineering bibliography (S-001 to S-021+)
├── references/                         # 16 In-depth technical reference modules (All VERIFIED)
│   ├── architectural-design.md         # Tropical architecture, passive design & regional typologies
│   ├── building-materials.md           # TIS materials, fire ratings (ASTM E119) & BEC envelopes
│   ├── building-space-planning.md      # Room dimensions, stairs, universal design ramps & parking
│   ├── construction-methods.md         # 8-stage construction sequencing & critical QC checkpoints
│   ├── electrical-systems.md           # MDB, 20-sec emergency power generators, grounding & AED
│   ├── fire-and-life-safety.md         # Compartmentation, 1-3h fire ratings, travel distances & smoke control
│   ├── foundations-and-piles.md        # Shallow vs deep pile selection, tie beams & seismic dowels
│   ├── geotechnical-engineering.md     # Bangkok soft clay subsoil stratigraphy & shoring methods
│   ├── mechanical-and-hvac.md          # Air change rates (ACH), BEC chiller COP & staircase pressurization
│   ├── multidisciplinary-coordination.md # Clashing rules (beam sleeves, bathroom drops, headrooms)
│   ├── plumbing-and-sanitary.md        # Soil/waste piping, mandatory grease traps (2023) & septic tanks
│   ├── reinforced-concrete.md          # WSD 0.375f'c, SR24/SD40 rebars, concrete cover & seismic ties
│   ├── site-planning.md                # Road setbacks, parcel boundaries, FAR, OSR & 6m fire access roads
│   ├── steel-structures.md             # AISC/DPT LRFD/ASD, SS400/SM400, intumescent paint & galvanizing
│   ├── structural-engineering.md       # Ministerial Reg 6 live loads, wind loads, soil capacities
│   └── thailand-building-regulations.md# Building Control Act B.E. 2522, Sec 21/39 bis, Reg 33, 55, etc.
└── workflows/                          # 8 Structured engineering workflows (All VERIFIED)
    ├── building-renovation.md          # Alteration criteria (Section 33 change-of-use, structural thresholds)
    ├── commercial-building-design.md   # Shophouses, cafes, laundromats, parking ratios & 2h firewalls
    ├── construction-review.md          # Plan QA checklist & site inspection (concrete slump, rebar chairs)
    ├── foundation-planning.md          # Soil log analysis, shallow vs bored/driven piles, settlement control
    ├── mep-system-planning.md          # Power service sizing, pipe routing, grease management & HVAC
    ├── multi-story-building-design.md  # High-rise criteria (>=23m), pressurized stairs, fire lifts, drift limits
    ├── residential-building-design.md  # 1-2 story homes, 30% open space, room heights & septic systems
    └── structural-system-planning.md   # Structural grid selection, wind/seismic frames & ductile detailing
```

---

## 🏛️ Technical Reference Modules (`references/`)

Each reference module contains verified engineering parameters, empirical formulas, and legal thresholds:

| Module | Key Contents & Engineering Benchmarks | Source IDs |
|---|---|:---:|
| **`thailand-building-regulations.md`** | Building Control Act B.E. 2522 (as amended to 2560); Sec 21 (45-day permit), Sec 39 bis (direct notice); Ministerial Reg 55 road setbacks (6m from centerline for road <10m; 1-2m for wider roads); Property setbacks (2-3m for openings, 0.5m/0m for blind walls); Ministerial Reg 33 high-rise rules. | S-001 to S-005, S-018 |
| **`structural-engineering.md`** | Ministerial Reg 6 Live Loads: Roof 30, Residential 150, Hotel/Condo 200, Office 250, Commercial/School 300, Mall/Restaurant 400, Warehouse/Parking 500 $kg/m^2$. Wind Loads: 50–160 $kg/m^2$ across 0–40m+ heights. Presumptive Soil Bearing Capacities (2 to 100 $t/m^2$). | S-006, S-007, S-021 |
| **`fire-and-life-safety.md`** | MOI Fire Rating Notification B.E. 2567: Primary RC frames 3h, slabs 2h, fire exit walls 2h, fire doors 1–2h. Maximum travel distance 60m (dead-ends $\le 10m$). Dual fire stairs required for buildings $\ge 4$ floors or $>15m$. Internal stairs pressurized to 25–50 Pa. Portable fire extinguishers (1 per 1,000 $m^2$). | S-004, S-005, S-008, S-016 |
| **`foundations-and-piles.md`** | Foundation selection matrix: Spread footings for stiff ground ($\ge 8\text{--}10\ t/m^2$) vs Driven/Bored piles for soft Bangkok clay (1st sand layer at 20–22m). Pile cap embedment $\ge 5\text{--}10cm$, rebar dowel anchorage $\ge 40d_b$. Earthquake tie beams spanning all pile caps. | S-006, S-007, S-020, S-021 |
| **`building-space-planning.md`** | Ministerial Reg 55: Habitable rooms $\ge 8.0\ m^2$, width $\ge 2.5m$, clear height $\ge 2.60m$. Bathrooms $\ge 0.9\text{--}1.5\ m^2$, clear height $\ge 2.0m$. Residential stairs: clear width $\ge 0.90m$, riser $\le 20cm$, tread $\ge 22cm$. Ministerial Reg 7 parking spaces (2.40 x 5.00m, disabled 3.40 x 5.00m). UD Ramps 1:12. | S-004, S-010, S-011, S-019 |
| **`electrical-systems.md`** | Ministerial Reg 39: Mandatory emergency generators for high-rise, hotels, hospitals (auto transfer within 20s, runtime $\ge 2h$). Energy Conservation Act (BEC) LPD limits (Office $\le 11\ W/m^2$, Mall $\le 16\ W/m^2$). RCD/GFCI protection $\le 30mA$ in wet zones. Mandatory AED equipment. | S-005, S-008, S-017 |
| **`plumbing-and-sanitary.md`** | Ministerial Reg 44 & 71 (B.E. 2566): Strict segregation of soil, waste, storm, and grease drains. Mandatory grease traps for residences, shophouses, and food services. 24-hour domestic water storage sizing (150–200 L/person/day for residences). Floating house flexible MEP joints (DPT Plan 361). | S-009, S-020 |
| **`reinforced-concrete.md`** | WSD allowable stress: Concrete compression $0.375f'_c$. Steel yield tension: SR24 ($1,200\ kg/cm^2$), SD30 ($1,500\ kg/cm^2$), SD40 ($1,700\ kg/cm^2$). Clear covers: Footings 5.0–7.5cm, Beams/Columns 3.0–4.0cm, Slabs 2.0cm. Ductile detailing with $135^\circ$ seismic hooks for Zone 1-3. | S-006, S-007, S-021 |
| **`steel-structures.md`** | MOI Structural Steel Standard B.E. 2567: LRFD & ASD design methodologies under AISC 360 / DPT 1201. TIS 1227 / 107 hot-rolled structural steel (SS400/SM400 $F_y \ge 2,400\ kg/cm^2$). Intumescent paint fireproofing (1–3h). Hot-dip galvanizing $\ge 500\text{--}600\ g/m^2$. | S-015, S-016, S-020 |
| **`mechanical-and-hvac.md`** | Natural ventilation openings $\ge 10\%$ of floor area. Mechanical air change rates (ACH): Bathrooms $\ge 4\text{ ACH}$, Commercial kitchens $10\text{--}15\text{ ACH}$, Parking garages $\ge 6\text{ ACH}$ (CO $<50\text{ ppm}$). BEC Chiller COP benchmarks ($\ge 3.10$ air-cooled, $\ge 5.50\text{--}6.10$ water-cooled). | S-005, S-008, S-017 |
| **`building-materials.md`** | TIS specifications: TIS 15 (Type I Portland cement), TIS 20/24 (Rebars). Fire wall assemblies: 10cm solid brick / aerated block (2–4h rating), Type X gypsum board (1–2h). Envelope insulation: Building Energy Code (BEC) OTTV $\le 50\ W/m^2$ and RTTV $\le 15\ W/m^2$. | S-006, S-015, S-016, S-017 |
| **`site-planning.md`** | Statutory setbacks from public roads, natural canals, and property boundaries. Fire apparatus access roads (min. 6.00m width, turning radius 10–12m). Zoning density metrics: Floor Area Ratio (FAR) and Open Space Ratio (OSR) alignment with Comprehensive City Plans. | S-004, S-005, S-017, S-018 |
| **`construction-methods.md`** | Standard 8-stage Thai construction sequence. Structural pile testing (Sonic Integrity & Dynamic Load Tests). Formwork stripping limits: Column/beam sides 48h; Beam/slab soffits 14–21 days (or $\ge 80\% f'_c$). Critical MEP rough-in before plastering. | S-002, S-015, S-021 |
| **`geotechnical-engineering.md`** | Bangkok subsoil stratigraphy: Soft clay (0–15m, $S_u \approx 1.5\text{--}2.5\ t/m^2$), 1st sand layer (20–24m, SPT-N $>30$), 2nd sand layer (30–45m). Deep excavation shoring (sheet piles, soldier piles) and basal heave mitigation. | S-006, S-007 |
| **`architectural-design.md`** | Tropical passive architectural principles: East-West axis orientation, 1.20–1.50m roof eaves, cross-ventilation. Thai regional prototypes: Sino-Portuguese shophouses with 1.5m covered walkway (Ngo-Ka-Ki), Central gingerbread carvings, Isan solar screens, disaster-resilient floating homes. | S-019, S-020, S-021 |
| **`multidisciplinary-coordination.md`**| Inter-disciplinary clash prevention: Prohibition of beam penetrations within $2d$ of column faces; mandatory pre-pour pipe sleeves at mid-depth/mid-span; bathroom slab depressions (5–10cm drop beams); mechanical ceiling plenum allowances ($\ge 30\text{--}40cm$). | S-003, S-004, S-005, S-008 |

---

## ⚡ Engineering Workflows (`workflows/`)

Standardized, step-by-step reasoning workflows designed for AI problem solving:

1. **[`residential-building-design.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/residential-building-design.md)**
   - Inputs verification $\rightarrow$ Site setbacks & 30% open space check $\rightarrow$ Spatial zoning $\rightarrow$ Live load assignment (150 $kg/m^2$) $\rightarrow$ Foundation selection $\rightarrow$ Mandatory grease & septic drainage.
2. **[`commercial-building-design.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/commercial-building-design.md)**
   - Shophouse block limits ($\le 10$ units or $\le 40m$ between 4m passages) $\rightarrow$ 3m rear setback $\rightarrow$ 2h party firewalls $\rightarrow$ Parking stall calculations (1 stall / 60 $m^2$) $\rightarrow$ High-capacity grease/wastewater planning.
3. **[`foundation-planning.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/foundation-planning.md)**
   - Soil Boring Log appraisal $\rightarrow$ Regional geotechnical classification $\rightarrow$ Shallow vs Deep driven/bored pile selection $\rightarrow$ Vibration sensitivity for adjacent structures $\rightarrow$ Seismic tie-beam grids.
4. **[`structural-system-planning.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/structural-system-planning.md)**
   - Dead/Live load accumulation $\rightarrow$ RC vs Structural Steel framing trade-offs $\rightarrow$ Lateral wind ($50\text{--}160\ kg/m^2$) and seismic analysis (DPT 1301/1302) $\rightarrow$ Ductile joint detailing.
5. **[`mep-system-planning.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/mep-system-planning.md)**
   - Electrical service & transformer sizing $\rightarrow$ 20-second emergency generator backup $\rightarrow$ Soil/waste/grease separation $\rightarrow$ 24h domestic water storage $\rightarrow$ HVAC ventilation & ACH rates.
6. **[`multi-story-building-design.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/multi-story-building-design.md)**
   - High-rise statutory triggers ($\ge 23m$ or $\ge 10,000\ m^2$) $\rightarrow$ 6m perimeter fire road $\rightarrow$ Dual pressurized fire exits $\rightarrow$ Fire lifts $\rightarrow$ Complete automatic sprinkler protection $\rightarrow$ Lateral drift limits ($H/500$).
7. **[`building-renovation.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/building-renovation.md)**
   - Statutory alteration assessment (RC/steel alterations, $>10\%$ load additions, $>5\ m^2$ floor expansion) $\rightarrow$ Change-of-use permits (Form A.5) $\rightarrow$ As-built structural integrity review.
8. **[`construction-review.md`](file:///C:/Pond/Pond/SketchUp/skill/architecture-engineering/workflows/construction-review.md)**
   - Pre-construction statutory check (setbacks, OSR, seismic detailing, MEP compliance) $\rightarrow$ Site inspection protocol (concrete slump, rebar clearance, formwork striking times) to prevent local authority stop-work orders (Form C.3 / C.7).

---

## 📖 Research Sources Registry (`RESEARCH_SOURCES.md`)

All technical data, mathematical equations, and statutory thresholds link directly to traceable source records:

- **S-001:** Ministerial Regulation on Building Inspector Qualifications and Inspection Rules B.E. 2548
- **S-002:** DPT Building Control Law Citizen Handbook (54 pages, 2552)
- **S-003:** Building Control Act B.E. 2522 (and amendments up to Act No. 5 B.E. 2558 / 2560)
- **S-004:** Ministerial Regulation No. 55 (B.E. 2543) — Building layouts, dimensions, setbacks, and stairs
- **S-005:** Ministerial Regulation No. 33 (B.E. 2535) — High-rise and extra-large buildings
- **S-006:** Ministerial Regulation No. 6 (B.E. 2527) — Live loads, wind loads, soil capacities, and allowable stresses
- **S-007:** Ministerial Regulation on Seismic Resistance of Buildings B.E. 2564 (Zones 1, 2, 3)
- **S-008:** Ministerial Regulation No. 39 (B.E. 2537) — Fire safety, ventilation, and emergency power
- **S-009:** Ministerial Regulation No. 44 (B.E. 2538) & No. 71 (B.E. 2566) — Drainage, septic, and grease traps
- **S-010:** Ministerial Regulation No. 7 (B.E. 2517 as amended) — Parking spaces, loading berths, and driveways
- **S-011:** Ministerial Regulation on Facilities for Persons with Disabilities and Elderly B.E. 2548 (Amended 2564)
- **S-012:** Factory Act B.E. 2535 (Amended 2562) — Categories 1, 2, 3 (Rong-Ngan 4 license)
- **S-013:** Dormitory Act B.E. 2558 — Safety, management, and gender segregation
- **S-014:** Ministerial Regulation on Safety Systems for Hotel Buildings B.E. 2566
- **S-015:** MOI Notification on Structural Steel Design Standards B.E. 2567 (AISC LRFD/ASD)
- **S-016:** MOI Notification on Fire-Resistance Properties of Building Materials B.E. 2567 (ASTM E119 / ISO 834)
- **S-017:** Ministry of Energy Notification on Building Energy Code (BEC) Standards B.E. 2564
- **S-018:** Bangkok Metropolitan Administration Ordinance on Building Control B.E. 2544
- **S-019:** DPT Standard Shophouse Packages — Plan 362 (Central), Plan 368 (Isan), Plan 369–371 (Southern Sino-Portuguese)
- **S-020:** DPT Royal Initiative Disaster-Resilient Floating House Package (Plan 361) with Structural Drawings & BOQ
- **S-021:** DPT Seismic-Resistant RC Structure Packages — Contemporary House Plans 396, 397, 406, 412, and 414

---

## 🚀 How AI Agents Use This Skill

1. **Activate on AEC Tasks:**
   - Any design, structural sizing, foundation appraisal, MEP routing, permit checking, or renovation inquiry automatically loads `SKILL.md`.
2. **Selective Reference Loading:**
   - The agent reads only the relevant module under `references/` (e.g., loads `foundations-and-piles.md` when asked about soil or footings; loads `thailand-building-regulations.md` when checking setbacks).
3. **Workflow Execution:**
   - For complete project design or plan review requests, the agent executes the appropriate procedure under `workflows/`.
4. **Evidence Labeling:**
   - Conclusions are stamped with verifiable evidence tags:
     - `[STATUTE]` Binding legal requirement (citing Source ID, e.g., `[S-004]`).
     - `[CODE / STANDARD]` Recognized national/international standard (e.g., DPT, EIT, TIS, AISC, ACI).
     - `[CALCULATION]` Verified formula application with explicitly stated inputs.
     - `[ASSUMPTION]` Highlighted open parameters requiring site survey or owner confirmation.
