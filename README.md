# BIDLens — AI-Based Tender Compliance System

An AI-powered document analysis system designed to streamline government tender compliance verification by extracting requirements from tender documents and identifying relevant evidence in bidder submissions.

BIDLens aims to make tender evaluation more structured, traceable, and efficient through intelligent document processing, Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG).

## Project Overview

Government tenders often contain lengthy documents with technical specifications, eligibility conditions, financial requirements, warranty clauses, and other compliance criteria. Manually comparing these requirements against multiple bidder submissions can be time-consuming and prone to oversight.

**BIDLens** addresses this challenge by processing tender documents, extracting structured requirements, and retrieving relevant evidence from bidder documents to support compliance verification.

The system is designed to assist procurement officers in reviewing requirements and supporting evidence while retaining human oversight over compliance decisions.

## Key Features

- **Intelligent Document Processing:** Processes tender PDFs to identify relevant clauses, sections, and requirements.
- **Requirement Extraction:** Uses LLMs to organise tender conditions into structured categories, including technical, financial, and eligibility requirements.
- **Retrieval-Augmented Generation (RAG):** Combines semantic retrieval with LLM-based processing to identify relevant information from lengthy documents.
- **Clause-Aware Retrieval:** Uses document structure and contextual information to retrieve relevant sections rather than relying exclusively on fixed-size text chunks.
- **Evidence Traceability:** Retains supporting page references to help users locate relevant information in source documents.
- **Multi-Bidder Comparison:** Supports the comparison of bidder submissions against common tender requirements.
- **Human-in-the-Loop Review:** Supports manual review of uncertain compliance findings rather than relying entirely on automated decisions.

## System Workflow

1. **Tender Upload:** The procurement officer uploads the tender document.
2. **Document Processing:** The document is processed to identify readable text, relevant sections, and page references.
3. **Requirement Extraction:** An LLM extracts and organises the tender requirements into structured categories.
4. **Bidder Document Upload:** Documents submitted by multiple bidders are provided for evaluation.
5. **Evidence Retrieval:** Semantic retrieval identifies potentially relevant evidence from the bidder documents.
6. **Compliance Assessment:** Retrieved evidence is used to support requirement-level compliance classification.
7. **Human Review:** The officer reviews supporting evidence and resolves cases requiring further verification.

## Technology Stack

| Component | Technologies |
|---|---|
| Programming Language | Python |
| Language Models | Large Language Models (LLMs), Ollama |
| Retrieval Architecture | Retrieval-Augmented Generation (RAG) |
| Semantic Search | Embeddings and semantic retrieval |
| Document Processing | PDF text extraction and clause-aware processing |

*The table highlights the principal AI/ML technologies; the complete implementation stack may include additional frontend, backend, and database technologies.*

## My Contributions

My contributions to BIDLens focused on two areas:

### LLM and RAG Development
- Worked on the AI pipeline for extracting structured requirements from tender documents.
- Worked with clause-aware document processing and semantic retrieval to identify relevant document sections.
- Contributed to organising extracted information into structured requirements using LLMs.
- Focused on improving the relevance and traceability of retrieved information through supporting page references.

### Technical Documentation
- Contributed to documenting the system's technical approach and workflow.
- Worked on technical documentation describing the AI/ML pipeline and document-processing approach.

## Project Resources

### Technical Documentation

- [Technical Report](https://drive.google.com/file/d/1NesXJnvJs7cFSjpgTYl0VXRNYNEx_3WG/view?usp=drive_link)
- [User Guide](https://drive.google.com/file/d/1wOKuE1AxTThmMuziy_BrdSk3aWciKc9n/view?usp=drive_link)

### Project Demonstration

- [Watch the BIDLens Demonstration on YouTube](https://youtu.be/i5i6qQeISlM)

### Original Project Repository

- [BIDLens — Original GitHub Repository](https://github.com/aayushreemalviya26/BIDLENS)

## Contributors

BIDLens was developed collaboratively by the following team members.

1. **[D Rasi Shree]**
2. **[Aayushree Malvia]**
3. **[Harshita Singh]**
4. **[Mehak Devang]**
5. **[Aarushi Singh]**
6. **[Aarushi]**

*Replace these placeholders with the contributors' names and, where available, their GitHub profiles.*

## Project Scope

BIDLens is intended to assist procurement officers by organising tender requirements and presenting potentially relevant bidder evidence for review. Its outputs support human decision-making and should not be treated as a substitute for independent verification or official procurement procedures.

## Acknowledgements

This project was developed collaboratively as a technology-driven approach to improving the efficiency and traceability of tender compliance review.

See the [original project repository](https://github.com/aayushreemalviya26/BIDLENS) for the project code and associated development materials.
