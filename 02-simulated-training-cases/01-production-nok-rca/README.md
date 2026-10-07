# Production NOK Increase — RCA Training Case

> **Case Type:** 🟦 Simulated / Training Case  
> **Status:** Completed  
> **Focus:** Root Cause Analysis, Fishbone (6M), Hypothesis Testing, 5 Why, Corrective & Preventive Action

---

## ⚠️ Case Classification

This is a **simulated training case** created as part of practical RCA & CAPA learning.

The scenario, data and test results are simulated for educational purposes.  
This case does **not** represent real workplace experience and should not be interpreted as such.

---

## 1. Problem Statement

The production NOK rate increased from:

**2% → 8%**

The problem was observed mainly on **Machine B** and occurred more frequently during the **night shift**.

### Objective

Identify and validate potential causes using a structured Root Cause Analysis approach instead of assuming a single cause from the initial observation.

---

## 2. Initial Observation

The initial information indicated:

- increased NOK rate
- concentration of defects on Machine B
- higher occurrence during the night shift

Potential differences were considered across the **6M categories**:

- Man
- Machine
- Material
- Method
- Measurement
- Environment

---

## 3. Fishbone / 6M Analysis

### Man

Potential causes:

- incorrect execution of the standard
- fatigue or reduced concentration
- differences between operators

### Machine

Potential causes:

- incorrect machine parameters
- controller-related errors
- unstable process settings

### Material

Potential causes:

- different material behaviour
- batch / lot differences
- storage conditions
- supplier/source differences
- material age

### Method

Potential causes:

- process not performed according to the work instruction
- skipped process step
- difference between documented and actual process

### Measurement

Potential causes:

- incorrect measurement method
- measurement instrument issues
- differences between operators or shifts

### Environment

Potential causes:

- ambient temperature
- humidity
- possible night/day environmental differences

---

## 4. Hypothesis Development

Potential causes were converted into testable hypotheses.

The objective was to determine whether changing or controlling a suspected factor produced a meaningful change in the NOK rate.

Where possible, other process conditions were kept consistent.

---

## 5. Hypothesis Validation

| Hypothesis | Test Result | Assessment |
|---|---|---|
| Temperature | NOK changed only from 8% → 7.8% | ❌ Rejected as a significant cause |
| Operator | NOK changed from 8% → 8.1% after changing operator | ❌ Rejected as primary cause |
| Measurement | Two operators produced practically identical results on the same element | ❌ Rejected as primary cause |
| Machine parameters | Restoring standard parameters reduced NOK from 8% → 3% | 🟢 Strongly supported |
| Material | One batch showed 27% NOK while other batches were around 3–5% | 🟡 Strong suspect; further validation required |
| Method | A skipped instruction step was identified; restoring it reduced NOK from 8% → 3.2% | 🟢 Strongly supported |

### Interpretation

The analysis did not support temperature, operator or measurement as the primary causes.

Machine parameters and Method showed a significant relationship with the NOK result.

Material remained a strong suspect and would require additional validation before being confirmed as a root cause.

---

## 6. 5 Why Analysis

### Problem

Machine B NOK increased to 8%, mainly during the night shift.

### Why 1

**Why was the instruction step being skipped?**

→ The instruction was not correctly implemented on the night shift.

### Why 2

**Why was the instruction not correctly implemented?**

→ The person responsible did not ensure that the change was implemented.

### Why 3

**Why was implementation not ensured?**

→ The responsible person was absent/on leave and responsibility was not properly transferred.

### System-Level Interpretation

At this point the analysis moves beyond the individual operator.

The issue is not simply:

> "The operator did not follow the instruction."

The deeper issue is the lack of a reliable mechanism ensuring continuity of responsibility for implementing instruction changes during the absence of the responsible person.

---

## 7. Root Cause

### Root Cause

**Lack of a reliable mechanism ensuring continuity of responsibility for implementing work-instruction changes during the absence of the responsible person.**

This represents a system-level weakness rather than simply assigning blame to an individual operator.

---

## 8. Corrective Action

The immediate corrective action would be to:

- implement the specific work-instruction change on the night shift
- verify that the affected process follows the current instruction
- confirm that the process is producing the expected result

---

## 9. Preventive Action

To prevent recurrence:

- establish a defined backup/deputy for instruction-related responsibilities
- ensure responsibility is transferred during planned absences
- introduce a confirmation mechanism for revised work instructions
- verify that relevant changes are communicated and implemented across all shifts

---

## 10. Key Learning

This case demonstrated the complete basic RCA flow:

**Observation → 6M → Potential Causes → Hypothesis → Validation → 5 Why → Root Cause → Corrective / Preventive Action**

The most important learning was that a visible human error does not necessarily represent the true root cause.

A useful RCA should also ask:

> **Why did the system allow the condition to occur?**

The 6M structure helped organize potential causes, hypothesis testing helped separate stronger explanations from weaker ones, and 5 Why helped move from the immediate process failure toward a controllable system-level cause.

---

## 11. Limitations

This is a **simulated training case**.

- Data is simulated.
- Test results are simulated.
- No real company data was used.
- No real production investigation was performed.
- The case is intended to demonstrate analytical thinking and methodology, not professional RCA experience.

---

## Case Study

📄 **[View the full case study PDF](./Case_01_Production_NOK_RCA_case-study.pdf)**
