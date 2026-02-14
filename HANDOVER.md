# EPSTEIN SUPERGRAPH - Handover Documentation
## Project: The Greatest Heist Network Visualization (1976-2025)

**Date:** February 13, 2026
**Status:** V4 Complete - Ready for Middle Development
**Files:** `/Users/z/EPSTEIN_SUPERGRAPH_V4.html`

---

## WHAT WE BUILT

### Complete Network Visualization System
- **D3.js v7 force-directed graph** with physics-based 360-degree layout
- **133 nodes** representing key figures, entities, and events (1976-2025)
- **~220 connections** documenting relationships, financial flows, intelligence ops
- **Interactive features:** drag-and-drop, zoom, hover tooltips, color-coded types
- **Weight-based rendering:** thicker lines = smoking gun connections (weight 10)

### Data Sources Integrated
✅ **Greatest Heist manuscript** (all 26 chapters)
✅ **Epstein Archive** (83,278 documents via epstein-archive skill)
✅ **Katie Johnson case** (April 28, 2016 network mobilization)
✅ **JPMorgan documents** (China strategy memos, Jes Staley emails)
✅ **2015-2016 network** (Thiel-Epstein-Churkin-Belyakov)
✅ **Trump-Russia money laundering** (Deutsche Bank, Rybolovlev)
✅ **Robert Maxwell triple agent** (KGB/Mossad/MI6)
✅ **PayPal Mafia** (Thiel, Musk, Hoffman, Zuckerberg)
✅ **Iran-Contra network** (Khashoggi, Leese, $600M slush)

### Major Hubs (All Size 30 - Equal Visual Weight)
1. **Vladimir Putin** - KGB/FSB, oligarch network, Mogilevich power base
2. **Xi Jinping** - China connections via Li Yuanchao, Wang Qishan
3. **Jeffrey Epstein** - Central hub, intelligence ops, blackmail network
4. **Donald Trump** - Cultivation target, money laundering, political ops
5. **Peter Thiel** - PayPal Mafia, Palantir, 2015-16 coordination, Vance VP pick

### Key V4 Additions (Latest)
- **Oleg Deripaska** (size 26) - Putin oligarch, aluminum empire, $19M Manafort debt
- **Viktor Vekselberg** (size 26) - Putin oligarch, energy empire, Deutsche laundering
- **Paul Manafort** (size 22) - Campaign chairman 2016, Ukraine Russia connections
- **Direct Trump ↔ Thiel** connections (Funded Vance $15M VP + RNC 2016 speech)
- **Putin → oligarchs** network (Deripaska, Vekselberg, Rybolovlev, Dmitriev)
- **Manafort web** (Stone business partner, Trump campaign, Deripaska debt)

### Physics Tuning (Optimized for Clarity)
```javascript
Link distance: (sourceSize + targetSize) × 10  // Lots of slack, floppy strings
Link strength: 0.08                            // Very weak for organic flow
Repulsion: -size × 70                          // Larger nodes push harder
Collision: size × 3                            // Wide berth, no overlap
```

### Color Coding
- 🔴 **Hub** (red): Epstein, Robert Maxwell, Ghislaine
- 🟠 **Intelligence** (orange): KGB/FSB, Mossad, CIA, operatives
- 🟡 **Financial** (gold): Oligarchs, banks, financiers
- 🟢 **Tech** (green): Thiel, Musk, Zuckerberg, Hoffman
- 🔵 **Political** (blue): Putin, Xi, Trump, Netanyahu, politicians
- 🟣 **Legal** (purple): Acosta, Barr, Starr, Dershowitz, lawyers
- ⚪ **Entities** (gray): Banks, companies, intelligence agencies
- 🌸 **Victims** (pink): Katie Johnson, Virginia Giuffre, Tiffany Doe

---

## WHAT NEEDS DEVELOPMENT

### 🎯 PRIORITY 1: MIDDLE DEVELOPMENT

#### Les Wexner Expansion
**Current state:**
- Node exists (size 24)
- 2 connections: Epstein (power of attorney mansion), Ghislaine (Wexner Mansion 1991-2000)

**Needs:**
- [ ] Victoria's Secret trafficking pipeline
- [ ] The Limited/Abercrombie corporate structure
- [ ] Mega Group connections (Robert Maxwell, Edgar Bronfman)
- [ ] Israeli intelligence funding through Wexner Foundation
- [ ] Actual dollar amounts to Epstein (estimated $500M+)
- [ ] New Albany, Ohio compound
- [ ] Connection to Katie Johnson case (9 E 71st St = Wexner Mansion)

#### Cabinet Officials Cross-Check
**Needs systematic mapping:**
- [ ] **Trump Cabinet 2017-2021:**
  - Alexander Acosta (Labor Secretary) ✅ EXISTS - gave Epstein sweetheart deal
  - William Barr (AG) ✅ EXISTS - AG when Epstein died
  - Steve Mnuchin (Treasury) ❌ MISSING
  - Wilbur Ross (Commerce) ❌ MISSING - Rothschild connection
  - Rex Tillerson (State) ❌ MISSING - ExxonMobil Russia
  - Mike Pompeo (CIA/State) ❌ MISSING
  - Betsy DeVos (Education) ❌ MISSING - Amway/Prince family

- [ ] **Trump Cabinet 2025-present:**
  - Howard Lutnick ✅ EXISTS (size 18) - Commerce Secretary, needs expansion
  - Elon Musk ✅ EXISTS - DOGE, needs massive expansion (see below)
  - Other cabinet members TBD

- [ ] **VP and Family Members:**
  - JD Vance ❌ MISSING - Thiel protégé, $15M backing (referenced in Trump-Thiel connection)
  - Ivanka Trump ❌ MISSING - Jared's wife, Trump Org
  - Eric Trump ❌ MISSING - Trump Org
  - Don Jr ❌ MISSING - Trump Org, Kimberly Guilfoyle
  - Melania Trump ❌ MISSING
  - Barron Trump (probably skip)

#### Money Flow Cross-Check
**Needs verification and expansion:**
- [ ] **Epstein → Recipients:**
  - Leon Black: $158M ✅ EXISTS
  - Glenn Dubin: $1.4M ✅ EXISTS
  - Jamie Dimon: Project Molecule profit splits ✅ EXISTS
  - Ariane de Rothschild: ✅ EXISTS but no money flow documented
  - Bill Gates: Project Molecule ✅ EXISTS but no dollar amount
  - Prince Andrew: ✅ EXISTS but no payments documented
  - Ehud Barak: 22,911 emails ✅ EXISTS but no payments
  - MISSING: Many others from flight logs and calendars

- [ ] **JPMorgan Flows:**
  - $1.1B Southern Trust wires ✅ EXISTS
  - Highbridge $1.3B deal ✅ EXISTS
  - MISSING: Fee structure, Staley compensation, China deal money

- [ ] **Trump Money Flows:**
  - Rybolovlev $95M mansion ✅ EXISTS
  - Deutsche Bank $2B+ ✅ EXISTS
  - Bowers $330M+ loans ✅ EXISTS
  - MISSING: Casino financing, Felix Sater deals, Bayrock flows

- [ ] **Leon Black → Kushner:**
  - $185M 2017 ✅ EXISTS
  - MISSING: Apollo backstory, timing context

### 🎯 PRIORITY 2: ELON MUSK DEVELOPMENT

**Current state:**
- Node exists (size 24)
- 2 connections: Epstein (16 emails 2012-15), 2024 Election ($277M donation)

**Needs massive expansion:**
- [ ] **PayPal Mafia origins:**
  - Co-founder with Thiel ✅ EXISTS
  - X.com merger with Confinity
  - Early Palantir involvement?

- [ ] **Epstein connections:**
  - 16 emails 2012-15 ✅ EXISTS but what were they about?
  - Dinner meetings? Who introduced them?
  - Grimes connection to Epstein network?

- [ ] **2024 Election:**
  - $277M Trump donation ✅ EXISTS
  - DOGE (Department of Government Efficiency) role
  - Government contracts: SpaceX, Starlink, Tesla
  - Security clearance issues

- [ ] **Current power:**
  - Twitter/X acquisition 2022
  - Government access 2025
  - Foreign influence: China (Tesla), Russia (Starlink Ukraine)
  - Relationship with Trump, Thiel, other cabinet

- [ ] **Money flows:**
  - Net worth trajectory
  - Government contracts value
  - Foreign investments

### 🎯 PRIORITY 3: CROSS-REFERENCES TO VALIDATE

#### From Epstein Archive (83,278 docs)
Use **epstein-archive skill** to search and validate:
- [ ] `search_archive("Wexner financial", max_results=100)` → add dollar amounts
- [ ] `search_archive("Mnuchin", max_results=50)` → check connections
- [ ] `search_archive("Wilbur Ross", max_results=50)` → Rothschild connection
- [ ] `search_archive("JD Vance", max_results=50)` → Thiel backing
- [ ] `search_archive("Elon Musk emails", max_results=100)` → expand Musk web
- [ ] `search_archive("Ivanka Trump", max_results=100)` → family connections
- [ ] `search_archive("Victoria's Secret", max_results=100)` → Wexner trafficking
- [ ] `get_financial_flows()` → cross-check all money flows
- [ ] `get_timeline("2016-01-01", "2017-12-31")` → Trump transition period

#### From Greatest Heist Manuscript
- [ ] Re-read **Chapter 19-22** (2016 election, Trump cabinet formation)
- [ ] Re-read **Chapter 24-26** (2024 election, current cabinet, endgame)
- [ ] Extract Elon Musk references across all chapters
- [ ] Extract Wexner references (likely early chapters on Epstein origin story)

---

## TECHNICAL NOTES

### File Structure
```
/Users/z/EPSTEIN_SUPERGRAPH_V4.html  ← CURRENT WORKING VERSION
/Users/z/EPSTEIN_SUPERGRAPH_V3.html  ← Previous (before oligarchs)
/Users/z/EPSTEIN_SUPERGRAPH_V2.html  ← Physics fixes
/Users/z/EPSTEIN_SUPERGRAPH.html     ← V1 original
```

### Adding New Nodes
**Template:**
```javascript
{id: "node_id", label: "DISPLAY NAME", type: "category", size: 16-30},
```

**Size guide:**
- 30: Major hubs (Putin, Xi, Epstein, Trump, Thiel)
- 26-28: Major players (Dimon, Netanyahu, oligarchs)
- 22-24: Significant figures (Staley, Chinese officials, Wexner)
- 18-20: Important figures (lawyers, bankers, politicians)
- 14-16: Supporting figures (assistants, victims, minor players)

**Type categories:**
- `hub` `intelligence` `financial` `tech` `political` `legal` `entity` `victim` `event`

### Adding New Connections
**Template:**
```javascript
{source: "source_id", target: "target_id", type: "connection_type", label: "Brief description", weight: 1-10},
```

**Weight guide:**
- 10: Smoking gun (documented financial, proven relationship, legal evidence)
- 8-9: Strong evidence (emails, flight logs, photos, credible reporting)
- 6-7: Documented relationship (public record, confirmed meetings)
- 4-5: Probable connection (logical inference, circumstantial)
- 1-3: Weak/alleged (rumors, unverified)

### Known Issues / Bugs
- ✅ **FIXED:** V4 was rendering blank due to malformed kushner connection (extra string property)
- ✅ **FIXED:** Duplicate connections in V4 (lines 475-484 duplicated 462-471)
- ✅ **FIXED:** Corrupted labels ("M debt" instead of "$19M debt")
- ⚠️ **LIMITATION:** Physics simulation can take 5-10 seconds on large graphs (133 nodes × 220 connections)
- ⚠️ **UX:** No search/filter by person yet (only "ALL" button exists)
- ⚠️ **UX:** No timeline scrubber (can't filter by date range)
- ⚠️ **DATA:** Some connections lack dollar amounts (need archive research)

### Browser Compatibility
- ✅ Chrome/Edge (tested)
- ✅ Safari (tested)
- ✅ Firefox (should work, not tested)
- ❌ IE11 (D3.js v7 not supported, don't care)

---

## DEVELOPMENT WORKFLOW

### To Add Nodes and Connections:

1. **Research phase:**
   ```
   Use epstein-archive skill:
   search_archive("target_name", max_results=100)
   get_relationships("target_name")
   get_financial_flows("target_name")
   ```

2. **Edit V4 file:**
   ```
   Read /Users/z/EPSTEIN_SUPERGRAPH_V4.html

   Add nodes in appropriate section:
   - Find comment like "// TRUMP INNER CIRCLE"
   - Add: {id: "new_node", label: "NAME", type: "political", size: 20},

   Add connections before closing bracket "]":
   - Find last connection before "]"
   - Add: {source: "a", target: "b", type: "political", label: "Description", weight: 9},
   ```

3. **Test:**
   ```
   open /Users/z/EPSTEIN_SUPERGRAPH_V4.html

   Check browser console for errors (F12 → Console)
   Verify node appears and connections render
   ```

4. **Iterate:**
   - Add more connections as you find evidence
   - Update weights as evidence strengthens
   - Adjust sizes if importance changes

### JavaScript Syntax Rules:
- ✅ **ALL properties require commas** between them
- ✅ **LAST item in array should NOT have trailing comma** (best practice)
- ✅ **Strings must use double quotes** inside object literals
- ❌ **DON'T add bare strings** as properties (caused V4 blank bug)
- ❌ **DON'T duplicate connections** (causes visual clutter)

---

## GITHUB SETUP

### Repo structure:
```
epstein-supergraph/
├── README.md                          ← Project overview
├── EPSTEIN_SUPERGRAPH_V4.html         ← Current version
├── HANDOVER.md                        ← This file
├── versions/
│   ├── EPSTEIN_SUPERGRAPH_V1.html
│   ├── EPSTEIN_SUPERGRAPH_V2.html
│   └── EPSTEIN_SUPERGRAPH_V3.html
├── data/
│   └── connections_sources.md         ← Document sources for each connection
└── assets/
    └── screenshot.png                 ← Graph screenshot for README
```

### README.md preview:
```markdown
# The Greatest Heist - Network Visualization

Interactive force-directed graph mapping the $80 trillion espionage network (1976-2025) documented in *The Greatest Heist* manuscript and Epstein archive.

**Live demo:** Open `EPSTEIN_SUPERGRAPH_V4.html` in browser

## Features
- 133 nodes: Putin, Xi, Epstein, Trump, Thiel, oligarchs, intelligence agencies
- 220+ connections: money flows, intelligence ops, political relationships
- Interactive: drag nodes, zoom, hover for details
- Evidence-weighted: thicker lines = stronger evidence

## Data Sources
- The Greatest Heist manuscript (26 chapters)
- Epstein Archive (83,278 documents)
- JPMorgan documents (China strategy, Jes Staley emails)
- Court filings (Katie Johnson, Virginia Giuffre)
- Public records (Trump cabinet, Deutsche Bank)

## Usage
1. Download `EPSTEIN_SUPERGRAPH_V4.html`
2. Open in browser (Chrome/Safari/Firefox)
3. Drag nodes to explore
4. Hover for details
5. Zoom with scroll wheel

## Development
See `HANDOVER.md` for:
- How to add nodes and connections
- Data validation workflow
- Priority development areas

## License
Research and journalism purposes. Attribution required.
```

---

## NEXT STEPS

### Immediate (Next Session):
1. ✅ Complete this handover doc
2. ⏭️ Create GitHub repo
3. ⏭️ Push V1-V4 to repo
4. ⏭️ Add README and screenshot

### Short-term (This Week):
1. **Wexner deep dive:**
   - Search archive for Wexner financial flows
   - Add Mega Group connections
   - Map Victoria's Secret pipeline

2. **Cabinet officials:**
   - Add Mnuchin, Ross, Pompeo, DeVos
   - Add JD Vance, Ivanka, Eric, Don Jr
   - Connect to money flows and appointments

3. **Elon Musk expansion:**
   - Search archive for all Musk-Epstein interactions
   - Add PayPal Mafia backstory
   - Map current government power (DOGE, contracts)

### Medium-term (This Month):
1. **Archive cross-validation:**
   - Run systematic searches for all 133 nodes
   - Add missing money flows
   - Strengthen evidence weights

2. **UX improvements:**
   - Add timeline scrubber (filter by year)
   - Add search box (highlight specific person)
   - Add legend (explain colors and weights)
   - Add "smoking gun" filter (weight >= 9)

3. **Export features:**
   - PDF export for reports
   - JSON data export for analysis
   - PNG screenshot for social media

### Long-term (Ongoing):
1. **Keep current:**
   - Add new cabinet appointments as they happen
   - Add new Epstein archive revelations
   - Update Greatest Heist as chapters finalize

2. **Expand networks:**
   - Crypto endgame (Chapter 26)
   - China deeper dive (Li Yuanchao, Wang Qishan webs)
   - UK network (Prince Andrew, Mandelson, more)
   - Israel network (Netanyahu, Barak, Mossad ops)

---

## CONTACT & COLLABORATION

**Primary researcher:** z
**Data sources:** epstein-archive skill (83,278 docs), Greatest Heist manuscript
**Tools:** D3.js v7, Claude Code, epstein-archive MCP server

**For questions:**
- Check `HANDOVER.md` for technical guidance
- Use `epstein-archive` skill to validate connections
- Search Greatest Heist manuscript for narrative context

---

## CHANGELOG

### V4 (Feb 13, 2026)
- ✅ Added Oleg Deripaska, Viktor Vekselberg, Paul Manafort
- ✅ Added direct Trump ↔ Thiel connections
- ✅ Added Putin → oligarchs network
- ✅ Fixed JavaScript syntax error (kushner connection)
- ✅ Removed duplicate connections
- ✅ Fixed corrupted labels ($19M, $15M)
- **Node count:** 133
- **Connection count:** ~220

### V3 (Feb 12, 2026)
- ✅ Added Xi Jinping (size 30) as major hub
- ✅ Added Jamie Dimon, Netanyahu, Ehud Barak
- ✅ Added Li Yuanchao, Wang Qishan (Chinese officials)
- ✅ Added 100+ new connections from Greatest Heist extraction
- ✅ Added Katie Johnson network (Apr 28 2016)
- ✅ Added JPMorgan China strategy connections
- **Node count:** 130
- **Connection count:** ~210

### V2 (Feb 11, 2026)
- ✅ Fixed physics for 360-degree free space (no hierarchical layout)
- ✅ Increased slack on connections (10x distance, 0.08 strength)
- ✅ Removed double-spacing from all labels (\n → single line)
- ✅ Set major hubs to equal size (30)
- ✅ Increased repulsion for larger nodes (size × 70)

### V1 (Feb 10, 2026)
- ✅ Initial supergraph combining Greatest Heist + Epstein archive
- ✅ 80+ nodes, 200+ connections
- ✅ Basic force-directed layout
- ✅ Color-coded types, weight-based thickness

---

**🔴 THE GREATEST HEIST - $80 Trillion Network Visualization 🔴**

*"The goal is not to find the truth. The goal is to use the truth."*
