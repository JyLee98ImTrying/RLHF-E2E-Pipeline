**# RLHF-E2E-Pipeline**
Executable e2e demo pipeline that allows simulated ingestion of production interactions, standardization &amp; PII scrubbing, validation, quality check, annotation merge, dataset assembly with weighting, versioned export to JSONL

**#Instruction**
- This is a single-file Python script; run in a Jupyter cell or as a script.
- Files will be written to /mnt/data/rlhf_full_pipeline_exports in this environment.
- To export Arrow/Parquet for Hugging Face datasets, ensure `pyarrow` is installed.

**# PROBLEM STATEMENT**
# The deployed Bahasa Melayu LLM is actively serving user queries in production.
# To improve cultural alignment and helpfulness, we must systematically transform daily user preference signals into clean, traceable, versioned datasets for
# Supervised Fine-Tuning (SFT) and RLHF workflows. This pipeline must handle noisy/inconsistent preferences, preserve provenance, and enable Annotation & Training teams to operate efficiently.
