# 🔴 THE GREATEST HEIST - Network Visualization

Interactive force-directed graph mapping the $80 trillion espionage network (1976-2025) documented in *The Greatest Heist* manuscript and Epstein archive.

**[→ OPEN VISUALIZATION](EPSTEIN_SUPERGRAPH_V4.html)** ← Download and open in browser

![Network Graph](https://img.shields.io/badge/Nodes-136-red) ![Connections](https://img.shields.io/badge/Connections-227-orange) ![Status](https://img.shields.io/badge/Status-Active-green)

---

## 🎯 What This Is

A comprehensive interactive network visualization showing the connections between:
- **Vladimir Putin** and Russian intelligence/oligarch network
- **Xi Jinping** and Chinese Communist Party officials
- **Jeffrey Epstein** and global blackmail operations
- **Donald Trump** and money laundering networks
- **Peter Thiel** and PayPal Mafia / Palantir operations
- **Elon Musk** and Russian intelligence connections (NEW!)
- Intelligence agencies (KGB/FSB, Mossad, CIA, MI6)
- Financial networks (JPMorgan, Deutsche Bank, Bear Stearns)
- Political figures (Netanyahu, Ehud Barak, cabinet officials)
- Tech billionaires (Zuckerberg, Gates, Hoffman)

## 📊 Network Statistics

- **136 nodes**: People, entities, events (1976-2025)
- **227 connections**: Money flows, intelligence ops, relationships
- **Weight-based evidence**: Thicker lines = stronger evidence (1-10 scale)
- **Color-coded types**:
  - 🔴 Red: Central hubs (Epstein, Robert Maxwell, Ghislaine)
  - 🟠 Orange: Intelligence operatives
  - 🟡 Gold: Financial players
  - 🟢 Green: Tech billionaires
  - 🔵 Blue: Political figures
  - 🟣 Purple: Legal team
  - ⚪ Gray: Entities/organizations
  - 🌸 Pink: Victims

## 🔥 Latest Additions (V4)

### Musk-Putin Connections (Feb 14, 2026)
- **Elon Musk** upgraded to size 28 (major player)
- **Musk → Putin**: "Russian party within Trumpist movement"
- **Starlink → Putin**: Russian breach of US data "direct to Russia via Starlink"
- **DOGE → Putin**: Russian IPs accessing US government data (whistleblower testimony)
- **Musk → Trump**: DOGE 2025 enabling Russian access

### Putin's Oligarch Network
- **Oleg Deripaska** (aluminum empire, $19M Manafort debt)
- **Viktor Vekselberg** (energy empire, Deutsche Bank laundering)
- **Paul Manafort** (Trump campaign chairman 2016, Ukraine Russia)
- Direct Putin → oligarchs → Manafort → Trump chain

### Trump-Thiel Direct Connection
- Thiel funded JD Vance $15M for VP pick
- RNC 2016 speech major donor
- Strengthened Kushner connection ($2B Saudi)

## 📚 Data Sources

### Primary Sources
- **The Greatest Heist** manuscript (26 chapters, 1976-2025)
- **Epstein Archive** (110,484 documents via MCP server)
  - House Oversight documents: 25,816
  - Court filings: 835
  - Depositions: 664
  - Flight logs: 218
  - FBI documents: 282
  - Emails: 117

### Key Document Evidence
- JPMorgan internal emails (Jes Staley-Epstein China strategy)
- Katie Johnson lawsuit (April 28, 2016 network mobilization)
- Deutsche Bank records (Trump-Russia money laundering)
- Bear Stearns files (Liquid Funding $4B+ bailout)
- Cambridge Analytica (87M users breach)
- Whistleblower testimony (Russian DOGE breach via Starlink)

## 🚀 Usage

### Quick Start
1. Download `EPSTEIN_SUPERGRAPH_V4.html`
2. Open in any modern browser (Chrome, Safari, Firefox)
3. **Drag nodes** to explore connections
4. **Hover over nodes** for details
5. **Scroll to zoom** in/out
6. **Drag background** to pan

### Tips
- Larger nodes = more important figures
- Thicker connections = stronger evidence (weight 8-10)
- Color indicates type (political, financial, intelligence, tech)
- 360-degree physics layout - no hierarchy, free exploration

## 🛠️ Technical Details

### Built With
- **D3.js v7** - Force-directed graph visualization
- **Pure JavaScript** - No build process, just open HTML
- **Physics simulation**:
  - Link distance: `(sourceSize + targetSize) × 10` (lots of slack)
  - Link strength: `0.08` (very weak, floppy strings)
  - Repulsion: `-size × 70` (larger nodes push harder)
  - Collision: `size × 3` (wide berth, no overlap)

### Browser Compatibility
- ✅ Chrome/Edge (tested)
- ✅ Safari (tested)
- ✅ Firefox (should work)
- ❌ IE11 (not supported, don't care)

## 📖 Development Guide

See **[HANDOVER.md](HANDOVER.md)** for:
- How to add nodes and connections
- Data validation workflow with epstein-archive skill
- Priority development areas:
  - Les Wexner expansion (Victoria's Secret, Mega Group)
  - Cabinet officials (Mnuchin, Ross, Pompeo, DeVos)
  - VP and family (JD Vance, Ivanka, Eric, Don Jr)
  - Elon Musk deeper dive (PayPal origins, government contracts)
  - Money flow cross-validation
- JavaScript syntax rules
- Testing procedures

## 🎯 Upcoming Development

### Priority 1: Middle Development
- [ ] **Les Wexner** - Victoria's Secret trafficking, Mega Group, $500M+ to Epstein
- [ ] **Cabinet Officials** - Mnuchin, Ross, Pompeo, DeVos, full Trump cabinet
- [ ] **VP & Family** - JD Vance (Thiel protégé), Ivanka, Eric, Don Jr
- [ ] **Money Flows** - Cross-validate all financial connections with archive

### Priority 2: Elon Musk Expansion
- [ ] PayPal Mafia origins and Palantir involvement
- [ ] 16 emails with Epstein 2012-15 (what were they about?)
- [ ] Government contracts (SpaceX, Starlink, Tesla)
- [ ] China connections (Tesla Gigafactory Shanghai)
- [ ] Ukraine Starlink control/manipulation

### Priority 3: Cross-References
- [ ] Search archive: `search_archive("Wexner financial", max_results=100)`
- [ ] Validate all money flows: `get_financial_flows()`
- [ ] Timeline Trump transition: `get_timeline("2016-01-01", "2017-12-31")`
- [ ] Re-read Greatest Heist chapters 19-26 (2016-2025)

## 📜 Version History

### V4 (Feb 14, 2026) - CURRENT
- ✅ Musk-Putin connections + Starlink/DOGE Russian breach
- ✅ Upgraded Musk to size 28 (major player)
- ✅ Added Deripaska, Vekselberg, Manafort
- ✅ Added direct Trump ↔ Thiel connections
- ✅ Fixed JavaScript syntax errors
- **136 nodes, 227 connections**

### V3 (Feb 12, 2026)
- Xi Jinping as major hub + Chinese officials
- Jamie Dimon, Netanyahu, Ehud Barak
- 100+ new connections from Greatest Heist extraction
- Katie Johnson network, JPMorgan China strategy
- **130 nodes, ~210 connections**

### V2 (Feb 11, 2026)
- Fixed physics for 360-degree free space
- Increased slack on connections
- Removed double-spacing from labels
- Equal sizing for major hubs

### V1 (Feb 10, 2026)
- Initial supergraph combining Greatest Heist + Epstein archive
- **80+ nodes, 200+ connections**

## 🔬 Evidence Weight Scale

Connections are weighted 1-10 based on evidence strength:

- **10**: Smoking gun (documented financial, legal evidence, whistleblower)
  - Example: "$19M Manafort debt to Deripaska"
  - Example: "Russian data breach via Starlink direct to Russia"

- **8-9**: Strong evidence (emails, flight logs, photos, credible reporting)
  - Example: "Epstein-Staley 93 emails"
  - Example: "Putin-oligarch networks"

- **6-7**: Documented relationship (public record, confirmed meetings)
  - Example: "PayPal co-founders"

- **4-5**: Probable connection (logical inference, circumstantial)

- **1-3**: Weak/alleged (rumors, unverified)

## 🔐 Research Ethics

This visualization is for:
- ✅ Investigative journalism
- ✅ Academic research
- ✅ Public accountability
- ✅ Historical documentation

**Attribution required** when using this work.

All data sourced from:
- Public court filings
- Congressional documents
- Whistleblower testimony
- Investigative reporting
- Declassified intelligence

## 🤝 Contributing

To expand this network:

1. Search the archive: Use `epstein-archive` MCP skill
2. Validate evidence: Check source documents
3. Add nodes/connections: Follow HANDOVER.md guide
4. Weight appropriately: Use evidence scale (1-10)
5. Test in browser: Ensure no JavaScript errors
6. Document sources: Track provenance

## 📧 Contact

**Primary researcher:** z
**Data sources:** Epstein Archive (83,278 docs), Greatest Heist manuscript
**Tools:** D3.js v7, Claude Code, epstein-archive MCP server

## ⚖️ License

Research and journalism purposes. Attribution required.

---

**🔴 THE GREATEST HEIST 🔴**

*"The goal is not to find the truth. The goal is to use the truth."*

---

### 🔗 Quick Links

- **[Open Visualization](EPSTEIN_SUPERGRAPH_V4.html)** - Main interactive graph
- **[The Trump Take](trump-take.html)** - Live counter: $ flowing to Trump & family ($107.74/sec)
- **[Development Guide](HANDOVER.md)** - How to expand the network
- **[Version History](versions/)** - Previous iterations (V1-V3)

Last updated: February 14, 2026
