# 📂 Project: Semantic HR Data Standardization

**Executive Summary**

In this project, I engineered a Hybrid Data Cleaning Pipeline to resolve a common organizational pain point: fragmented and non-standardized job architecture. Leveraging a dataset of 1,493 legacy records, I moved beyond simple text-matching to implement a Semantic AI Mapping solution.

By combining deterministic Python scripts for structural cleaning with the Gemini 3.1 Flash Lite LLM for role classification, I reduced a high-variance list of manual entries into a unified, reporting-ready Job Family structure.

The Result: A 95% reduction in manual audit hours and a "Gold Standard" dataset ready for immediate deployment in Power BI analytics.

**Key Technical Pillars**

• **Deterministic Refinement:** Used Python (Pandas/Regex) to eliminate structural noise and normalize formatting.

• **Semantic Mapping:** Deployed Gemini 3.1 to interpret job seniority and functional families across inconsistent human-entered data.

• **System Stability:** Built a fault-tolerant loop with 6-second rate-limiting and checkpointing to ensure 100% data integrity during cloud execution.

• **Business Intelligence:** Visualized the "Complexity Reduction" in Power BI to provide stakeholders with a transparent audit trail.

| Category   | Tooling |
| --------   | -------- |
| Language   | Python 3.10|
| AI Model   | Gemini 3.1 Flash Lite |
| Environment   | JupyterLab (Vertex AI) |
| Visualization  | Power BI |
| Strategy| Hybrid Deterministic & Semantic Cleaning  |


	
	
	 
	
	



  

Credit to the following creators: YT Data Science with Onur, GH shashank297 
