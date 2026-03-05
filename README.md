# PostOp Sentinel AI

### Agentic AI for Early Detection of Post-Surgical Complications

PostOp Sentinel AI is an intelligent post-operative monitoring system that uses generative AI to help detect early signs of surgical complications after patients leave the hospital.

The system allows patients to submit daily recovery check-ins including symptoms and optional wound images. An AI agent analyzes this information, reasons about recovery patterns, and classifies the patient's risk level. When potential complications are detected, the system alerts clinicians with a clear summary so they can intervene earlier.

This project demonstrates how **agentic AI systems built with Amazon Nova foundation models** can help extend healthcare monitoring beyond hospital walls, especially in resource-constrained environments.

---

# The Problem

Many surgical complications occur **after patients are discharged from the hospital**.

Common challenges include:

- Patients ignore early warning signs
- Doctors cannot continuously monitor recovery
- Complications like infection or bleeding are detected too late
- Hospitals in many regions face **limited staff and resources**

These delays can lead to preventable suffering and, in severe cases, death.

Early detection is critical.

---

# Our Solution

PostOp Sentinel AI acts as a **post-surgery monitoring assistant**.

Patients perform simple daily check-ins through a web interface where they can:

- Describe symptoms
- Upload wound images
- Report how they feel

The AI agent then:

1. Analyzes the symptoms
2. Considers the timeline since surgery
3. Evaluates wound appearance (if image provided)
4. Compares patterns with normal recovery behavior
5. Classifies risk level

The system outputs:

- 🟢 **Normal Recovery**
- 🟡 **Needs Attention**
- 🔴 **High Risk – Alert Clinician**

If a high-risk signal is detected, the system generates a structured alert for clinicians.

This allows doctors to identify complications **before they become life-threatening.**

---

# How Amazon Nova Is Used

This project is powered by **Amazon Nova foundation models** available through AWS.

Nova models provide the reasoning capabilities that enable the system to act as an **AI agent instead of a simple chatbot**.

### Nova 2 Lite

Used for:

- reasoning about patient symptoms
- understanding recovery timelines
- classifying complication risk
- generating clinical summaries

### Multimodal Embeddings

Used for:

- representing uploaded wound images
- comparing visual signals against healing patterns

These models enable the system to combine **structured medical reasoning with multimodal inputs**.

---
