# Timeline Materials

This directory contains programmatic timeline data and supporting calendar materials for the ETHAN case.

## Files

### anchors.csv
Machine-readable timeline anchors in CSV format. Each row represents a key event with:
- **anchor_id:** Unique identifier (e.g., ETH-20211028-INC)
- **date:** Event date (YYYY-MM-DD format)
- **actor:** Who performed the action
- **event:** Short event name
- **summary:** Brief description
- **tags:** Searchable keywords (semicolon-separated)
- **exhibit_path:** Relative path to supporting evidence
- **source_type:** Type of source document (PDF, EMAIL, etc.)
- **source_ref:** Additional source reference
- **page:** Specific page number (if applicable)
- **sha256:** File hash (optional, for integrity verification)
- **importance:** Critical/high/medium/low
- **notes:** Additional context

### Usage

The CSV format enables:
- Programmatic timeline generation
- Automated cross-referencing
- Data visualization (charts, graphs, flowcharts)
- Import into legal case management software
- Filtering and sorting by date, actor, tag, importance
- Integrity verification via hashes

### Adding New Events

When adding a new timeline event:
1. Use the next sequential anchor_id: `ETH-YYYYMMDD-XXX`
2. Keep date in ISO format: YYYY-MM-DD
3. Use semicolon-separated tags for easy parsing
4. Reference exhibit with relative path from /evidence/
5. Set importance level based on legal/procedural significance
6. Add explanatory notes if needed

### Example Tools

You can process this CSV with:
- **Spreadsheet software:** Excel, Google Sheets, LibreOffice Calc
- **Programming:** Python (pandas), R, JavaScript
- **Visualization:** Timeline.js, Plotly, D3.js
- **Legal tools:** CaseMap, LexisNexis, other case management systems

### Maintaining Accuracy

- Cross-check all dates against source documents
- Update exhibit paths if files are moved or renamed
- Document any date uncertainties in notes column
- When adding exhibits, update this timeline accordingly
