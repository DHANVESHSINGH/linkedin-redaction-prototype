# linkedin-redaction-prototype
Problem Statement

When users post certificates, identity records, or official documents on LinkedIn, sensitive Personally Identifiable Information (PII)—such as identity numbers, personal photos, contact details, and signatures—frequently leaks online, creating serious privacy risks.

Solution

An active, DPDPA-compliant frontend interface that automatically renders red canvas masking blocks over sensitive document regions, enforcing a secure, privacy-first workflow before platform sharing.

Tech Stack

HTML5: Semantic structure and interactive canvas framework

CSS3: Responsive UI layout, modern styling, and component workflows

JavaScript (Vanilla JS): Dynamic event handling and interactive multi-step interface flow

HTML5 Canvas API: Precise document rendering and non-reversible pixel-level redaction

Future Roadmap (Backend Integration)

Python & FastAPI Service: High-performance, zero-retention backend API processing

OCR & Computer Vision (Tesseract OCR / OpenCV): Automated text extraction, dynamic bounding box detection, and pattern recognition for names, phone numbers, signatures, and ID fields

LinkedIn OAuth 2.0 API: Direct API pipeline for publishing redacted documents without local file downloads
