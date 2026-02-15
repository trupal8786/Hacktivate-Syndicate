# Hacktivate-Syndicate
YOUR_FIGMA_LINK_HERE
https://www.figma.com/make/mkg8qrgKstvAlklr8NOJsl/EduVoyage-AI-PRD?t=v7d9bhuV6cDqBPjc-1

Problem Statement
Engineering students face a chaotic overseas education landscape:
1)Information Overload: Manually navigating 5,000+ global university portals and non-standardized eligibility criteria.
2)The Debt Trap: Students often take ₹40L+ loans without clear visibility into regional job market dynamics or break-even timelines.
3)Counseling Bottlenecks: A high student-to-counselor ratio leads to generic, slow, and sometimes biased advice.
4)Admission Uncertainty: Mismatch between academic profiles and university expectations resulting in high rejection rates.

Our Approach: The Human-AI Hybrid
1)We don't aim to replace counselors; we give them "superpowers." Our approach follows a three-tier intelligence model:
2)Intelligent Profiling: AI parses resumes and transcripts to build a "Technical Skill Graph" and normalize CGPA to global scales.
3)Predictive Reasoning: A RAG-based engine retrieves real-time university data and visa policies, matching them against student constraints.
4)Human-in-the-Loop: Every AI-generated shortlist is sent to a human expert for validation, ensuring high-trust and ethical oversight.

Tech Stack
1)AI Foundational Model: gemini-2.5-flash-preview-09-2025 (Multimodal Reasoning & RAG).
2)Vector Database: Pinecone (High-speed retrieval of university brochures and policy data).
3)Embeddings: text-embedding-004.
4)Backend: Node.js / FastAPI (Python).
5)Frontend: React / Next.js with Tailwind CSS.
6)Database & Auth: Firebase (Real-time Firestore sync & Anonymous Auth).
7)Deployment: Integrated Vercel/Cloud environment.

Key Features
1)ROI Predictor: A visual dashboard projecting total cost (tuition + living) vs. projected regional salary to calculate the "Time-to-Breakeven."
2)Multimodal RAG Advisor: A hallucination-proof chatbot that cites official university sources for every recommendation.
3)Counselor Dashboard: A centralized CRM for consultancies to manage large student datasets with AI-prioritized shortlists.
4)RLHF Loop: A Reinforcement Learning system where the AI improves accuracy by learning from human counselor edits.

Future Scope
1)Visa Automation: AI-assisted drafting and review of Statements of Purpose (SOP) and visa documentation.
2)FinTech Integration: Direct API links to bank loan providers for instant "Loan Eligibility" scores based on the student's ROI profile.
3)Alumni Network: An AI-matched peer-to-peer mentoring system connecting current applicants with alumni from their target universities.
4)Domain Expansion: Scaling the framework from Engineering to Medicine (MedTech) and Management (MBA) domains globally.
