# AI-Powered Clinical Research Intelligence Hub

## Purpose

This project implements an advanced automated pipeline that discovers, analyzes, and curates cutting-edge AI applications in clinical research. It utilizes Qwen LLM (via OpenRouter) to monitor trusted sources like PubMed, Clinical Trials gov, and specialized journals, intelligently filtering content related to AI applications and generating comprehensive briefs with premium web interfaces featuring glassmorphism design and full mobile optimization.

## Details

- **Core Features**
  - Automated Content Discovery: Monitors 12+ trusted sources (PubMed, Clinical Trials gov, Nature Medicine, etc.)
  - AI-Powered Analysis: Uses Qwen LLM to categorize articles by 6 specific AI technology types (Generative AI, NLP, Machine Learning, Digital Health, Trial Optimization, AI Ethics)
  - Smart Filtering: Intelligent identification of content specifically related to AI applications in clinical research
  - Premium Web Interface: Glassmorphism design with interactive filtering, advanced search, and responsive mobile layout
  - Automated Scheduling: Runs automatically Monday-Friday at 5:00 AM CET via GitHub Actions

- **AI Technology Categories**
  - Generative AI: LLMs, ChatGPT, text generation applications
  - Natural Language Processing: Text analysis, clinical notes processing
  - Machine Learning: Predictive models, algorithms, ML techniques
  - Digital Health: Health apps, digital therapeutics, connected devices
  - Trial Optimization: Clinical trial design, patient recruitment, protocol optimization
  - AI Ethics: Bias, fairness, transparency, responsible AI implementation

- **Technology Stack**
  - Backend: Python 3.8+, Qwen LLM via OpenRouter, Beautiful Soup, Requests
  - Frontend: Alpine.js, Tailwind CSS, Custom CSS for glassmorphism effects
  - Output: JSON briefs, premium HTML presentations, detailed logs

- **UI/UX Features**
  - Interactive filtering by AI categories with visual filter pills
  - Debounced search with highlighting and XSS protection
  - Keyboard navigation (/ to focus, Escape to clear)
  - Mobile-first responsive design with iOS safe-area support
  - Accessibility: WCAG compliance, screen reader support, semantic HTML

- **Production Features**
  - Daily automation via GitHub Actions with timezone awareness (CET/CEST)
  - Rate limiting with token bucket and exponential backoff
  - Atomic file writes and schema validation for data integrity
  - Comprehensive error handling and detailed logging

- **Data Sources**
  - PubMed Central, Clinical Trials Database, Nature Medicine, NEJM AI
  - The Lancet Digital Health, JMIR Medical Informatics, Journal of Medical Internet Research
  - NPJ Digital Medicine, specialized publications, Google Scholar API integration

- **Deployment and Automation**
  - Automated weekday runs at 5:00 AM CET/CEST
  - GitHub Pages deployment with gh-pages branch
  - Optional analytics via GoatCounter
  - Manual trigger capability alongside automated scheduling

- **Performance Metrics**
  - Processes 180+ articles daily with 8.9% precision rate
  - Cost efficiency: $0.10 per comprehensive content curation run
  - Multi-format output: JSON data, premium HTML, detailed processing logs

## Links

- [GitHub Repository](https://github.com/albertoclemente/ai-clinicalresearch-hub)
- [Live Site](https://albertoclemente.github.io/ai-clinicalresearch-hub/)