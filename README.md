# True Teamwork: Human-AI Partnership Activities for K-12 Cybersecurity Education

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fryanstraight.github.io%2Fnicek12-2025-materials)](https://ryanstraight.github.io/nicek12-2025-materials)
[![NICE K12 2025](https://img.shields.io/badge/NICE%20K12-2025-blue)](https://www.k12cybersecurityconference.org/)

Classroom-ready activities designed to teach K-12 students that humans and AI work best as **collaborative partners** in cybersecurity, not as tool and user, but as genuine teammates.

**[View the Materials Site →](https://ryanstraight.github.io/nicek12-2025-materials)**

## About This Project

These materials were developed for the **NICE K12 Cybersecurity Education Conference 2025** (December 7-9, Nashville, TN) as part of the Multidisciplinary & Innovative Approaches track.

### The Core Shift

| Old Thinking | New Thinking |
|--------------|--------------|
| Humans **use** AI tools | Humans **and** AI as teammates |
| AI is either adversary or tool | AI is collaborative partner |
| Individual competency matters | Partnership capability matters |

## What's Included

### Three Complete Activities

| Activity | Focus | Key Learning |
|----------|-------|--------------|
| **Security Detective Teams** | Investigation with AI partner | Pattern recognition + contextual judgment |
| **Ethics in Automated Security** | AI governance policy design | Value trade-offs in automation |
| **AI-Assisted Incident Response** | Team-based incident handling | Role coordination under pressure |

### Four Grade Bands

Each activity includes developmentally-appropriate versions:

- **K-2**: Story-based scenarios with simple choices
- **Grades 3-5**: Mystery-solving with guided AI interaction
- **Grades 6-8**: School-based realistic scenarios
- **Grades 9-12**: Enterprise SOC simulations

### Supporting Materials

- **Assessment Rubrics**: Human-AI collaboration, decision-making quality, NICE Framework application
- **Implementation Guides**: AI platform setup, low-resource alternatives
- **Printable Resources**: Worksheets, role cards, evidence packets, scenario briefings
- **Career Connections**: Direct mapping to NICE Workforce Framework roles
- **Annotated Bibliography**: Research foundations and further reading

## Quick Start

### For Teachers

1. Visit the [Materials Site](https://ryanstraight.github.io/nicek12-2025-materials)
2. Choose an activity and grade band
3. Download the Quick Start guide and student worksheets
4. Review the AI Setup Guide (or Low-Resource Implementation guide if needed)

### For Developers

```bash
# Clone the repository
git clone https://github.com/ryanstraight/nicek12-2025-materials.git
cd nicek12-2025-materials

# Install Quarto (if not already installed)
# https://quarto.org/docs/get-started/

# Preview locally
quarto preview

# Build the site
quarto render
```

## Project Structure

```
nicek12-2025-materials/
├── activities/                    # Three activities, each with 4 grade bands
│   ├── 01-security-detective-teams/
│   ├── 02-ethics-automated-security/
│   └── 03-ai-incident-response/
├── assessments/                   # Rubrics and self-reflection tools
├── career-connections/            # NICE Framework work role mappings
├── guides/                        # Implementation and setup guides
├── presentation/                  # RevealJS conference slides
├── printables/                    # Print-optimized worksheets and cards
├── resources/                     # Annotated bibliography
├── docs/                          # Rendered site (GitHub Pages)
├── _quarto.yml                    # Site configuration
└── ua-style.scss                  # University of Arizona branding
```

## Low-Resource Implementation

These activities work at **any technology level**:

| Access Level | Implementation |
|--------------|----------------|
| **Full AI access** | Students interact directly with ChatGPT, Claude, etc. |
| **Limited access** | Rotation stations, shared accounts, teacher demonstration |
| **No AI access** | Pre-generated AI Response Cards, teacher as "AI voice" |

The low-resource options often create *better* learning—students must think critically about what AI might contribute rather than simply asking.

## NICE Framework Alignment

All activities map to authentic cybersecurity careers:

| Activity | Primary Work Roles |
|----------|-------------------|
| Security Detective Teams | Cyber Defense Analyst, Vulnerability Assessment Analyst |
| Ethics in Automated Security | Cyber Policy & Strategy Planner, Privacy Officer |
| AI-Assisted Incident Response | Cyber Defense Incident Responder, SOC Analyst |

## Citation

```bibtex
@misc{straight2025trueteamwork,
  author       = {Straight, Ryan},
  title        = {True Teamwork: Human-AI Partnership Activities for K-12 Cybersecurity Education},
  year         = {2025},
  howpublished = {Presented at NICE K12 Cybersecurity Education Conference},
  url          = {https://ryanstraight.github.io/nicek12-2025-materials},
  note         = {December 7-9, 2025, Nashville, TN}
}
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

## Author

**Dr. Ryan Straight**
University of Arizona
College of Information Science

- Website: [ryanstraight.com](https://ryanstraight.com)
- Email: ryanstraight@arizona.edu
- ORCID: [0000-0002-6251-5662](https://orcid.org/0000-0002-6251-5662)

## Acknowledgments

- **NICE K12 Cybersecurity Education Conference** for the platform to share this work
- **University of Arizona College of Information Science** for institutional support
- The broader **posthuman pedagogy** research community for theoretical foundations

---

*Built with [Quarto](https://quarto.org/) and a lot of ☕*
