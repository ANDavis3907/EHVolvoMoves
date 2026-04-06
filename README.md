# EHVolvoMoves
EHVolvoMoves: AI-Powered Lot Attendant Tracker
An intelligent, mobile-responsive inventory management system designed for automotive lot operations. This application replaces manual tracking with a digital-first approach, leveraging Google's Gemini AI to automate data entry and Firebase for real-time synchronization.

🚀 Key Features
AI Data Extraction: Integrates Google's Gemini 2.5 Flash model to analyze vehicle images (VIN tags, stock stickers) and automatically populate vehicle details, reducing manual entry errors.

Real-Time Inventory: Powered by Firebase Firestore, ensuring that vehicle moves, status updates, and location changes are synced across all devices instantly.

Intelligent Reporting: Custom logic to generate operational reports, including:

Location Conflict Detection: Identifies inventory data mismatches.

Maintenance Tracking: Monitors "Start-Ups" and overdue maintenance tasks.

Master Lot List: A comprehensive, searchable database of all vehicles on-site.

Mobile-Optimized UI: Built with a "mobile-first" philosophy using Tailwind CSS, ensuring lot attendants can easily update inventory from the palm of their hand while out on the lot.

🛠 Tech Stack
Frontend: HTML5, JavaScript (ES6+), Tailwind CSS

Backend/Database: Firebase (Authentication & Firestore)

AI/ML: Google Gemini API (Generative AI SDK)

Environment: Nix-based development configuration (dev.nix)

📂 Project Structure
Plaintext
├── lot_tracker.html   # Main application interface and logic
├── dev.nix            # Reproducible development environment configuration
└── (Other Assets)     # CSS and JS modules
🔧 Getting Started
Prerequisites
A Firebase project with Firestore enabled.

A Google AI (Gemini) API Key.

Installation
Clone the repository:

Bash
git clone https://github.com/ANDavis3907/EHVolvoMoves.git
Open lot_tracker.html in your browser or serve it via a local development server.

Configure your Firebase and Gemini credentials within the script tags (ensure you use environment variables or secure methods for production).

📈 Future Enhancements
Integration of a barcode/QR scanner plugin for faster stock identification.

Offline mode support for areas of the lot with poor connectivity.

Advanced analytics dashboard for lot turnover rates.
