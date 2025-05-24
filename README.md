# Anki Flashcards – Wirtschaftsinformatik Bachelor @ University of Münster
Welcome to this repository containing Anki flashcards for the Bachelor in Wirtschaftsinformatik at the University of Münster.

## Table of Contents
1. [Purpose of This Repository](#purpose-of-this-repository)
2. [Included Modules](#included-modules)
3. [How to Use](#how-to-use)
4. [Important Notice on Maintenance](#important-notice-on-maintenance)
5. [Contact & Support](#contact--support)
6. [Support This Project](#support-this-project)
7. [How to Contribute Corrections or Improvements](#how-to-contribute)

## Purpose of This Repository
This repository provides a comprehensive set of Anki flashcards that include:
- Definitions and key concepts from official lecture scripts
- Examples, explanations, and application-based tasks
- Past exam questions with solutions
- Additional material from textbooks and other academic sources

## Included Modules
- **BWL1:** Introduction to Business Admin (WS 22/23) – Klein, Branger, Schneider
- **BWL2:** Managerial Accounting (SS 23) – Kajüter
- **BWL3:** Operations Management (WS 23/24) – Hellingrath
- **BWL4:** Marketing Fundamentals (WS 22/23) – Wiesel
- **INFO2:** Data Structures & Algorithms (SS 23) – Linsen
- **QM4-1:** Data Analysis (SS 24) – Terveer
- **QM4-2:** Simulation (SS 23) – Schönberger
- **VWL:** Introduction to Economics (WS 22/23) – Sieg
- **WI6:** Digital Business (WS 22/23) – Stockinger

## How to Use
1. Download and install [Anki](https://apps.ankiweb.net/)
2. Download the relevant `.apkg` file(s) from this repository
3. Import the deck into Anki via *File → Import* or drag and drop

## Important Notice on Maintenance
This repository is not actively maintained. While contributions are welcome, this repository will remain partially maintained by me only.
If you spot errors or have improvements, please feel free to submit corrections via pull requests. I will review and merge fixes, but do not guarantee active development or ongoing support.

## Contact & Support
For questions, suggestions, or corrections: Open an [issue](https://github.com/jasonhaak/wi-uni-muenster-flashcards/issues) or submit a Pull Request.

## Donations
If you find these flashcards helpful and want to buy me a coffee, you can donate me via PayPal:

<a href="https://www.paypal.com/paypalme/jasonhaak01">
  <img src="https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png" alt="Donate with PayPal" height="120"/>
</a>

## How to Contribute
If you want to contribute flashcards, corrections or improvements, please follow this workflow to ensure consistency.

### Prerequisites
- Use [CrowdAnki](https://github.com/Stvad/CrowdAnki) to export/import decks as JSON for version control
- Enables export/import of decks as JSON, making them suitable for version control
- Install via Anki Add-On menu using the plugin code from the CrowdAnki GitHub page
- Export: Use *CrowdAnki → Export deck*
- Import: Use *CrowdAnki → Import JSON deck*

### Step-by-Step Contribution Guide
1. Fork this repository
2. Clone your fork locally
3. Install CrowdAnki in your Anki desktop app
4. Create or update flashcards in Anki as needed
5. Export your updated deck as JSON using CrowdAnki
6. Export your updated deck as APKG using Anki without scheduling informations but with media
7. Create a new folder named as `MODULE-SEMESTER` (e.g., `BWL3-WS-23-24`)
8. Place your exported CrowdAnki files and the APKG file in this folder
9. Edit this README.md and add your lecture
10. Commit your changes with a clear message
11. Push to your fork and open a Pull Request against this repository

### Version Control and File Format
- Do not commit `.apkg` files (binary, not diff-friendly) without using CrowdAnki for version control
- Use CrowdAnki JSON export as the primary source tracked in Git
- Track only text-based or JSON files and media assets for clear version history and easy review

---
**Good luck with your studies! 🎓**
