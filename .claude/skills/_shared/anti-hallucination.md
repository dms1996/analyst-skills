# Anti-Hallucination Guidelines

These rules reduce fabrication and ensure analytical integrity across all skills.

## 1. Source Everything

- Every factual claim must reference a source (company filing, report, database, user-provided data)
- If no source is available, explicitly state: "**[Estimate]** Based on general industry knowledge, not verified data"
- Never present estimates as facts
- Use phrases like "According to [source]..." or "Based on the provided data..."

## 2. Show Your Work

For all calculations:
- Show the formula used
- Show intermediate steps
- Show the final result
- Allow the reader to verify independently

Example:
```
WACC = (E/V × Re) + (D/V × Rd × (1-T))
     = (0.70 × 10%) + (0.30 × 5% × (1-25%))
     = 7.0% + 1.125%
     = 8.125%
```

## 3. Confidence Levels

Flag uncertainty explicitly using these levels:

| Level | Label | Meaning |
|-------|-------|---------|
| High | **[High Confidence]** | Based on verified data, official sources, or direct calculation |
| Medium | **[Medium Confidence]** | Based on reasonable estimates, industry benchmarks, or partial data |
| Low | **[Low Confidence]** | Based on assumptions, analogies, or limited information |

Always state the confidence level for key conclusions and projections.

## 4. Range Validation

For numerical outputs:
- Validate that results fall within reasonable ranges
- Flag outliers: "Note: This P/E ratio of 150x is significantly above the industry average of 20-25x"
- Cross-check totals: Percentages should sum to 100%, balance sheets should balance
- If a calculation produces an unexpected result, flag it and explain possible reasons

## 5. Distinguish Data Types

Clearly separate:
- **Facts**: Verified, sourced data points
- **Calculations**: Derived from facts using stated formulas
- **Estimates**: Reasonable approximations based on available information
- **Assumptions**: Inputs that could change the analysis significantly
- **Opinions**: Subjective assessments or recommendations

## 6. Acknowledge Limitations

Every analysis should include a "Limitations" section stating:
- What data was not available
- What assumptions were made and their sensitivity
- What additional analysis would strengthen the conclusions
- Time sensitivity of the data used

## 7. No Fabricated Data

- NEVER invent specific numbers, dates, names, or statistics
- If asked to analyze without sufficient data, state what data is needed
- Use placeholders like `[INSERT ACTUAL VALUE]` when specific data is required but not provided
- When using illustrative examples, clearly label them as "Illustrative Example" or "For demonstration purposes"

## 8. Cross-Verification Prompts

When producing financial analysis, ask yourself:
- Does this number make intuitive sense?
- Is this consistent with other data points in the analysis?
- Would an expert in this domain find this reasonable?
- Have I seen contradictory information that I should address?
