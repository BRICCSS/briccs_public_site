# BRICCSS research poster transcription

> **Source:** [`assets/images/briccs_poster.jpg`](../../assets/images/briccs_poster.jpg)  
> **Document purpose:** Internal reference and context for developing the BRICCS public website.  
> **Transcription note:** This document was transcribed from a photograph of a printed poster. Text
> that is obscured, too small, or uncertain is identified rather than silently inferred. Line breaks
> and hierarchy have been adapted to Markdown for readability. Before publishing names, funding
> language, contract numbers, or organizational claims, verify them against an original source.

## Main poster

### Title

**Biomedical Research In Contagion Control, Stewardship, and Surveillance (BRICCSS)**

The photographed poster spells the acronym **BRICCSS**, with two final S characters. The repository
and proposed website currently use **BRICCS**.

### Authors

Ariana Callahan¹˒²; Wathsala Widanagamaachchi¹˒²; Christian Dalton¹˒²; Colton Gordon¹˒²;
Nwoka Ajinwo¹˒²; JoAnn Vuong¹˒²; Lindsay Carpenter¹˒²; Jeremy Barraza¹˒²˒³;
Vanessa Stevens¹˒²˒³; Jordan Welch¹˒²; Christian Barker¹˒²; Senthil Nachimuthu¹˒²;
Makoto Jones¹˒²˒³

> Some author-name spellings and superscripts are small in the photograph and should be checked
> against the original poster or an authoritative author list.

### Affiliations

1. Informatics, Decision-Enhancement and Analytic Sciences (IDEAS) Center, VA Salt Lake City
   Health Care System
2. Division of Epidemiology, University of Utah
3. VA Clinical Assessment Reporting and Tracking (CART) program

## Who We Are

- Research program focused on developing and validating data-driven tools to address
  high-consequence public health threats.
- Collaboration of the VA Salt Lake City Health Care System, University of Utah, and federal
  partners.
- We support and extend the work of the VA's BASIC Program within the Clinical Assessment
  Reporting and Tracking (CART) Program.

## Focus Areas

The focus-area diagram shows three related research functions feeding into operational tools:

- Clinical Analytics & Surveillance
- Measure Development
- Modeling & Prediction
- Operational Tools

## Research Highlights

### Clinical Analytics & Surveillance

- Studying Shifting Epidemic Dynamics
  - Identify when epidemic patterns change.
  - Analyze high-frequency, low-lag data.
  - Use time-varying methods.
  - **Key insight:** Simpler, more adaptive models can respond more effectively.
  - **Application:** Research and operational settings.

The accompanying figure is titled **“Wavelet Power Spectrum of COVID-19 Cases.”** Its visible
labels include **Period (days)** and **Power**, with a time series below the spectrum.

### Quality Measure Development

- Develop and maintain clinical quality measures using machine learning.
- Leverage EHR data to identify patterns.
- Apply anomaly detection methods.
- **Key insight:** Non-linear methods can accelerate the measure lifecycle.
- **Application:** Supports validation, refinement, and monitoring of quality measures.
- Recent work includes measures related to:
  - Hospital-onset bacteremia (HOB)
  - Healthcare-associated *C. difficile* infection (HT-CDI)
  - Surgical Site Infection (SSI)
  - VTE

The accompanying circular lifecycle diagram includes the following legible or substantially legible
labels:

- Measure Specification
- Measure Conceptualization
- Measure Testing
- Measure Implementation
- Measure Use, Continuing Evaluation & Maintenance

### Modeling & Prediction

- Detect emerging disease signals earlier through natural language processing (NLP).
- Apply NLP methods to identify clinical patterns.
- Analyze large-scale VA clinical data to track changes over time.
- **Key insight:** Changes in clinical language can signal emerging patterns before diagnostic
  codes or terminology appear.
- **Application:** Enhances biosurveillance by enabling earlier detection of threats.

The accompanying scatterplot is titled **“Topic Comparison: Topic 1 (Model 1) vs Topic 1
(Model 2).”** Individual plotted labels and the complete axis captions are too small to transcribe
reliably from the photograph.

### Operational Tools

- Nowcasting Infectious Disease Burden
  - Estimate current disease burden in real time.
  - Integrate near real-time VA data with community data.
  - Apply machine learning models.
  - **Key insight:** Incorporating unlagged VA data substantially improves accuracy compared to
    community data alone.
  - **Application:** Supports operational reporting and decision-making.

The accompanying timeline diagram is labeled **“Training/validation timeframes.”** Legible labels
include **Training**, **Validation**, **Test set**, **cross-validation and fitting**, **predicting only**,
**practical evaluation**, and **Time**. Several smaller data-source labels are obscured or too small
to transcribe reliably.

## Why This Matters

The process diagram communicates the following progression:

1. **Integrate early stage analytic activities:**
   - Measure Development
   - Modeling
   - Operational Tools
2. **Adapt quickly as conditions change.**
3. **Move insights into real-world use.**
4. Deliver **timely, actionable information for clinical and public health partners**.

## Future Focus

### Surprise

- Build models that estimate how expected or unexpected a clinical event is.
- Use “surprise” signals to flag unusual patterns in real time.
- Test whether this improves early detection.

### Outbreak Workflow

- Combine topic modeling, exposure extraction, qualitative text metrics, and autoencoder signals
  into one workflow.
- Apply the pipeline to clinical text to detect early outbreak patterns.
- Evaluate how much earlier we could identify emerging infections.

## Acknowledgements

This work is conducted under the Biosurveillance, Antimicrobial Stewardship and Infection Control
(BASIC) Program and is supported in part by the Centers for Disease Control and Prevention's (CDC)
Safety and Healthcare Epidemiology Prevention Research Development (SHEPheRD) Program (2021
Domain 1-A015 Contract #200-2016-91799) and Center for Forecasting and Outbreak Analytics (CFA)
(CDC-RFA-23-0069), and the Department of Defense (W81XWH-22-1-0950). Data and resources were
provided by the VA COVID-19 Shared Data Resource and the Department of Veterans Affairs (VA)
Informatics and Computing Infrastructure (VINCI), VA HSR RES 13-457.

### Logos and organizations shown

- IDEAS — VA Salt Lake City Informatics, Decision-Enhancement, and Analytic Sciences Center
- U.S. Department of Veterans Affairs
- University of Utah Health
- One additional logo at the lower-right edge is obscured by the foreground poster.

## Partially visible foreground poster

A second poster overlaps the lower-right corner of the main poster. Because much of it is outside
the frame or obscured, the following is a partial transcription only.

### Partial title and attribution

**“Biosurveillance, Anti-Microbial Stewardship an…”**

The visible author line begins with **Lindsay Carpenter¹˒²** and **Tina W…**. The remaining names
and the ends of the affiliation lines are not visible enough to transcribe reliably.

### Who We Are

- The BASIC Program originated in 2015 under the VA Office of Clinical Systems Development &
  Evaluation (CSDE) as a Federal-Academic partnership.
- Reorganized in 2021 to the Clinical Assessment Reporting and Tracking (CART) Program, under
  Quality and Patient Safety (QPS) / VA Office of Analytics and Performance Integration
  (API; 17API6).
- A unique group of clinicians, epidemiologists, data scientists, data managers, technical product
  managers, informaticians, and visualization specialists.

### Partially visible biosurveillance section

The section heading begins **“BIOSURVEILLANCE — VA NATIONAL SURVEILLANCE C…”**. The visible text
indicates that the group:

- Created a single authoritative VA data source for reporting and metrics during the COVID-19
  pandemic.
- Integrated data from critical sources, including BASIC, to support surveillance tools.
- Originally generated and validated data for multiple projects that now support operational data
  feeds.
- Supports an internal “Symphony” and NST PowerBI build as the public-facing Access-to-Care
  website.

> These bullets are partly cut off by the photograph's lower and right edges. They preserve the
> readable meaning, but are not a verbatim or complete transcription.

