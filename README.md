# AI Product & Automation Workflows

This repository presents selected workflow case studies. Proprietary source code, private data, and confidential implementation details are intentionally excluded.

## 1. Agent-Assisted 3D Asset Onboarding

### Problem
Incoming 3D models required manual comparison with manufacturer product pages, metadata verification, spreadsheet updates, and visual quality control.

### Workflow
1. New 3D assets and manufacturer URLs are added to shared storage.
2. Claude connects to Blender through Model Context Protocol.
3. The agent reviews asset structure and compares available information with manufacturer data.
4. Claude generates task-specific Python scripts.
5. Scripts support validation, file processing, and spreadsheet updates.
6. Production artists review flagged inconsistencies and correct remaining issues.

### Role
Product workflow design, requirements definition, implementation coordination, testing, and process improvement.

### Technologies
Claude, MCP, Blender, AI-assisted Python, spreadsheets, human-in-the-loop QA.

## 2. Web-Data Discovery and Enrichment

### Problem
The marketing team needed a repeatable way to discover relevant European interior-design content and prepare contextual engagement suggestions.

### Workflow
1. Apify collects public content.
2. Make.com filters results by location and engagement criteria.
3. Structured records are saved in Google Sheets.
4. AI generates three contextual comment suggestions.
5. A human reviews the suggestions before use.

### Technologies
Apify, Make.com, Google Sheets, AI-assisted text generation.

## 3. Material and Shader Naming Standardization

### Problem
Inconsistent material and shader slot naming prevented scalable asset texturing.

### Workflow
An AI-assisted process analyzes incoming assets and assigns standardized slot names, enabling downstream batch texturing and database consistency.

### Technologies
Blender, AI-assisted scripting, 3D asset metadata, production QA.
