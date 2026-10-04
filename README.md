# Chhotu
Digital Companion for Field Drug Testing – AI-powered colorimetric assay analysis, secure evidence generation, GPS-tagged test records, and tamper-evident audit logging.
VeriField Diagnostics
Digital Companion for Field Drug Testing
Smart India Hackathon 2026 – Problem Statement ID 26231
Overview

VeriField Diagnostics is a digital companion platform designed to modernize and standardize field drug testing procedures using existing colorimetric reagent kits.

Current field drug-testing methods rely heavily on visual interpretation of color reactions, leading to inconsistent results, human error, and lack of verifiable documentation. VeriField Diagnostics addresses these challenges by combining image analysis, automated classification, secure digital record generation, and audit trail management into a single platform.

The system works alongside existing field test kits without requiring any additional hardware.

Problem Statement
Problem Statement ID

26231

Title

Digital Companion for Field Drug Testing

Key Objectives
Standardize interpretation of colorimetric drug tests
Reduce subjective human judgement
Generate tamper-evident digital evidence
Capture metadata including:
Timestamp
GPS Location
Operator ID
Create searchable field records
Improve transparency and accountability
Support law enforcement and forensic workflows
Features
Camera-Based Test Capture
Live camera access
Automatic image acquisition
Reaction-zone alignment guide
Capture assay reaction images
Color Calibration
Reference color card detection
Lighting normalization
White-balance correction
Consistent color interpretation
Automated Classification

Supported outcomes:

Positive
Negative
Inconclusive
Invalid / Optical Interference
AI-Assisted Result Analysis
HSV color extraction
Color matching
Confidence scoring
Reaction intensity analysis
Tamper-Evident Digital Evidence

Each record contains:

Test image
SHA-256 image hash
GPS coordinates
Timestamp
Operator identifier
Device information
Assay type
Classification result
Secure Audit Trail
Searchable test history
Case management
Export records
CSV reporting
Evidence preservation
Dashboard

The prototype dashboard includes:

Subject / Case profile management
Assay selection
Optical Reaction Window (ROI)
Diagnostic outcome panel
HSV analysis metrics
Confidence score
Field Audit Log
Technology Stack
Frontend
HTML5
CSS3
JavaScript
Mobile
Progressive Web App (PWA)
Android Support
iOS Support
Imaging
OpenCV
Image Processing Pipeline
Color Calibration Algorithms
Security
SHA-256 Hashing
Digital Signatures
Tamper Detection
Storage
SQLite
IndexedDB
Cloud Synchronization (Optional)
Workflow
Officer Opens Application
            ↓
Selects Assay Type
            ↓
Captures Test Image
            ↓
Reference Card Calibration
            ↓
Automated Analysis
            ↓
Classification Result
            ↓
Digital Evidence Record Generated
            ↓
Hash Created
            ↓
Stored in Audit Log
Example Output
{
  "case_id": "CASE-8842",
  "assay": "Scott Reagent",
  "result": "POSITIVE",
  "confidence": "98.4%",
  "gps": "28.6139,77.2090",
  "timestamp": "2026-09-30T14:30:00Z",
  "image_hash": "SHA256_HASH",
  "operator_id": "OFFICER_001"
}
Disclaimer

This application provides a presumptive field-test result based on image analysis of colorimetric reactions.

The application:

Does not replace laboratory testing.
Does not constitute definitive forensic evidence.
Must be used alongside approved field testing procedures.
Requires confirmatory laboratory analysis for legal and forensic conclusions.
Future Enhancements
AI/ML model training
Blockchain evidence verification
Multi-agency synchronization
Offline-first deployment
QR-coded case management
NFC evidence tagging
Cloud forensic dashboard
Team

Smart India Hackathon 2026

Problem Statement ID: 26231

Category: Digital Companion for Field Drug Testing
