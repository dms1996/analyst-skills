# Finance & Business Analysis Skills

A comprehensive collection of **62 reusable skill templates** for professional analysts across multiple roles.

## Roles Covered

| Role | Skills |
|------|--------|
| Cross-Role Utilities | 8 |
| Business Analyst | 10 |
| Financial Analyst | 10 |
| Data Analyst | 10 |
| Market Research | 8 |
| Product Analyst | 6 |
| Strategy | 5 |
| Risk & Compliance | 5 |

## Installation

Clone this repo into your project or copy the `.claude/skills/` directory:

```bash
git clone https://github.com/dms1996/analyst-skills.git
cp -r analyst-skills/.claude/skills/ your-project/.claude/skills/
```

Or use as a standalone project — open the directory and use the skills directly as slash commands.

## Usage

Each skill is invoked as a slash command:

```
/executive-summary <paste your document or data here>
/compare-options Option A, Option B, Option C for <context>
/dcf-valuation <company name or ticker>
/swot <company or project>
```

## Skill Categories

### Cross-Role Utilities
Universal skills that every analyst role benefits from.

| Skill | Description |
|-------|-------------|
| `/executive-summary` | Condense any document into a structured executive summary |
| `/explain-concept` | Explain financial/business concepts adapted to audience level |
| `/compare-options` | Structured comparison of N options with weighted criteria |
| `/data-to-insight` | Transform raw data into actionable business insights |
| `/report-template` | Generate professional report templates by type and audience |
| `/presentation-outline` | Create presentation structure with storyline and talking points |
| `/email-brief` | Draft professional emails/briefs from key points |
| `/glossary` | Interactive glossary of terms by domain |

### Business Analyst
| Skill | Description |
|-------|-------------|
| `/swot` | SWOT analysis with confrontation matrix strategies |
| `/business-case` | Business case with ROI, costs, benefits, risks |
| `/requirements-doc` | Business Requirements Document (BABOK/IEEE aligned) |
| `/user-stories` | User stories with Given/When/Then acceptance criteria |
| `/process-map` | AS-IS/TO-BE process maps in Mermaid/BPMN |
| `/gap-analysis` | Current vs desired state gap analysis |
| `/stakeholder-map` | Stakeholder mapping with communication strategy |
| `/competitive-analysis` | Porter's Five Forces competitive analysis |
| `/decision-matrix` | Weighted decision matrix with recommendation |
| `/meeting-notes` | Structured meeting minutes with action items |

### Financial Analyst
| Skill | Description |
|-------|-------------|
| `/dcf-valuation` | DCF valuation with sensitivity analysis |
| `/ratio-dashboard` | Financial ratio dashboard (DuPont, liquidity, profitability) |
| `/comparable-analysis` | Trading comps with peer selection |
| `/financial-model` | 3-statement financial model |
| `/variance-analysis` | Actual vs budget vs forecast variance analysis |
| `/earnings-review` | Quarterly earnings analysis |
| `/investment-memo` | Buy-side investment memorandum |
| `/scenario-analysis` | Bull/base/bear scenario modeling |
| `/cash-flow-analysis` | Cash flow analysis (operating/investing/financing) |
| `/budget-forecast` | Rolling budget and forecast model |

### Data Analyst
| Skill | Description |
|-------|-------------|
| `/sql-query` | Natural language to optimized SQL |
| `/data-profile` | Statistical data profiling report |
| `/eda` | Automated exploratory data analysis |
| `/kpi-define` | KPI definition with AARRR/North Star/HEART frameworks |
| `/cohort-analysis` | Retention cohort analysis |
| `/ab-test` | A/B test design and analysis |
| `/dashboard-spec` | Dashboard specification document |
| `/data-clean` | Data cleaning script generation |
| `/data-dictionary` | Data dictionary generation |
| `/etl-pipeline` | ETL/ELT pipeline design |

### Market Research
| Skill | Description |
|-------|-------------|
| `/market-sizing` | TAM/SAM/SOM market sizing |
| `/trend-research` | Market trend analysis |
| `/competitor-intel` | Competitive intelligence report |
| `/customer-persona` | Data-driven customer personas |
| `/survey-design` | Survey questionnaire design |
| `/market-report` | Comprehensive market research report |
| `/pricing-analysis` | Pricing strategy analysis |
| `/industry-overview` | Industry overview with drivers and barriers |

### Product Analyst
| Skill | Description |
|-------|-------------|
| `/funnel-analysis` | Conversion funnel analysis |
| `/feature-impact` | Feature impact assessment |
| `/churn-analysis` | Churn analysis and prevention |
| `/product-metrics` | Product metrics framework (AARRR, HEART) |
| `/user-journey` | User journey mapping |
| `/prioritization` | Feature prioritization (RICE, ICE, MoSCoW) |

### Strategy
| Skill | Description |
|-------|-------------|
| `/strategy-brief` | Strategic brief with recommendation |
| `/okr-builder` | OKR creation aligned with strategy |
| `/pestel` | PESTEL macro-environmental analysis |
| `/value-chain` | Value chain analysis (Porter) |
| `/growth-model` | Growth modeling with drivers and levers |

### Risk & Compliance
| Skill | Description |
|-------|-------------|
| `/risk-assessment` | Risk matrix (probability x impact) |
| `/control-matrix` | Internal controls mapping |
| `/regulatory-check` | Regulatory requirements verification |
| `/audit-checklist` | Audit checklist by area |
| `/incident-report` | Structured incident report |

## Quality Principles

Every skill in this collection follows these principles:

1. **Anti-Hallucination** — Show calculations, cite sources, flag uncertainty
2. **Chain-of-Thought** — Step-by-step reasoning before conclusions
3. **Pyramid Principle** — Lead with the answer, then supporting evidence
4. **MECE** — Mutually exclusive, collectively exhaustive categorization
5. **Actionability** — Every insight tied to a concrete recommendation
6. **Structured Output** — Consistent Markdown templates with tables and sections

## Contributing

1. Fork this repository
2. Create a new skill in the appropriate category directory
3. Follow the skill template format in `.claude/skills/_shared/`
4. Submit a pull request

## License

MIT License — see [LICENSE](LICENSE) for details.
