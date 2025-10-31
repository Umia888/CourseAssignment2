# laws90286-ID1737854-assignment2
# 🧾 AI Contract Clause Builder

A Streamlit application that **automatically drafts, reviews, and refines legal contract clauses** based on user-defined objectives, jurisdiction, and uploaded legal references.

👉 **Live Demo:** [Streamlit Cloud App](https://laws90286-id1737854-assignment2-82h3tviqeftuepzqbpa5ru.streamlit.app/)

---

## 🚀 Application Overview

This app allows users to:
- Input a **contract clause drafting objective**
- Select a **jurisdiction and drafting style**
- Upload **reference documents** (e.g., legal notes, precedents)
- Automatically generate, review, and improve legal clauses
- Download the final clause as a **Word document**

---

## 🧪 Demonstration Test Cases

Below are four test cases to demonstrate the application’s functionality.

---

### **Test Case 1: Liability Limitation (Basic Test – No Documents)**

**Objective:**  
Limit liability for indirect, special, or consequential damages to a maximum of 20% of the total contract amount, and specify exclusions from liability.

**Jurisdiction:**  
United States

**Uploaded Documents:**  
_None_

**Drafting Style:**  
Balanced (Legal but Readable)

---

### **Test Case 2: Liquidated Damages (With Documents)**

**Objective:**  
Establish a liquidated damages provision with daily calculation, capped at a 24% annual rate, and clear payment deadlines.

**Jurisdiction:**  
England and Wales

**Uploaded Document:**  
[`liquidated_damages_reference.txt`](./liquidated_damages_reference.txt)

**Reference Highlights:**  
- Damages must be a **genuine pre-estimate of loss**  
- Cannot be **punitive**  
- Must include **clear triggers, methodology, and maximum caps**:contentReference[oaicite:0]{index=0}

**Drafting Style:**  
Legal Formal

---

### **Test Case 3: Confidentiality Obligations (Complex Test)**

**Objective:**  
Define scope, obligations, exceptions, duration (3 years post-termination), and remedies (including injunctive relief).

**Jurisdiction:**  
Singapore

**Uploaded Documents:**  
- [`confidentiality_guide.txt`](./confidentiality_guide.txt)  
- [`singapore_law_notes.txt`](./singapore_law_notes.txt)

**Drafting Style:**  
Balanced (Legal but Readable)

---

### **Test Case 4: Confidentiality + Liquidated Damages Hybrid (Demonstration Extension)**

**Objective:**  
Combine confidentiality and liquidated damages provisions—apply damages of up to 10% of contract value for breach of confidentiality.

**Jurisdiction:**  
Singapore

**Uploaded Documents:**  
- [`confidentiality_guide.txt`](./confidentiality_guide.txt)  
- [`liquidated_damages_reference.txt`](./liquidated_damages_reference.txt)

**Drafting Style:**  
Legal Formal
