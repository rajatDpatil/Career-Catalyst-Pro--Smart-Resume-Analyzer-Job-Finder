# 🚀 Career Catalyst Pro

**AI-Powered Resume Analysis & Job Recommender**

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
![AI](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-green)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

## Overview

Career Catalyst Pro leverages Google's powerful Gemini AI to analyze your resume and provide instant, actionable career insights. Simply upload your PDF resume to receive comprehensive skill analysis, personalized growth recommendations, and direct links to relevant job opportunities.

## Features

- ** AI Resume Analysis** - Extract and analyze key skills using Google Gemini AI
- ** Skill Gap Identification** - Identify areas for professional improvement
- ** Personalized Career Roadmap** - Get tailored growth suggestions
- ** Intelligent Job Matching** - Receive direct links to relevant job postings
- ** Modern UI Design** - Beautiful dark theme interface with glowing effects
- ** Fast Processing** - Quick analysis powered by Gemini 2.5 Flash
- ** Secure** - Your data is processed securely and not stored

## Quick Start

### Google Colab (Recommended)

1. **Open in Colab** - Click the badge above to open the notebook
2. **Configure API Keys** - Add your API keys to Colab secrets:
   - `GEMINI_API_KEY` - Your Google Gemini API key
   - `APIFY_API_TOKEN` - Your Apify API token
3. **Run the Application** - Execute all cells and upload your PDF resume
4. **Get Insights** - Receive instant analysis and job recommendations

### Local Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/career-catalyst-pro.git
cd career-catalyst-pro

# Install dependencies
pip install -r requirements.txt

# Create environment file
echo "GEMINI_API_KEY=your_gemini_api_key_here" > .env
echo "APIFY_API_TOKEN=your_apify_token_here" >> .env

# Run the application
python app.py
```

## API Setup

### Gemini API Key
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the key for use in your environment

### Apify API Token
1. Sign up at [Apify](https://apify.com/)
2. Navigate to Settings → Integrations
3. Copy your API token

## Project Structure

```
career-catalyst-pro/
├── app.py                 # Main Gradio application
├── requirements.txt       # Python dependencies
├── .env.example          # Environment variables template
├── README.md             # Project documentation
└── assets/               # Static assets (if any)
    └── screenshots/      # Application screenshots
```

## How to Use

1. **Upload Resume** 
   - Click the upload area
   - Select your PDF resume file
   - Wait for file processing

2. **Analyze Resume** 
   - Click the "Analyze Resume" button
   - AI will extract and analyze your skills
   - Review the comprehensive analysis

3. **Get Job Recommendations** 
   - View personalized job matches
   - Click direct application links
   - Apply to relevant positions

4. **Follow Career Roadmap** 
   - Review skill gap analysis
   - Follow improvement suggestions
   - Track your professional growth

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Google Gemini AI 2.5 Flash** | Resume analysis and skill extraction |
| **Gradio** | Web interface and user interaction |
| **Apify** | Job scraping and matching |
| **Python 3.8+** | Backend processing and logic |
| **PyPDF2** | PDF text extraction |
| **Requests** | API communication |

## Sample Output

```
 KEY SKILLS IDENTIFIED:
   • Python Programming (Advanced)
   • Machine Learning (Intermediate)
   • Data Analysis (Advanced)
   • SQL Database Management (Intermediate)

 IMPROVEMENT AREAS:
   • Cloud Computing Certifications (AWS/Azure)
   • Advanced Machine Learning Frameworks
   • Leadership and Team Management Skills

 CAREER ROADMAP:
   1. Obtain AWS Cloud Practitioner Certification
   2. Complete advanced ML course (TensorFlow/PyTorch)
   3. Attend industry networking conferences
   4. Develop portfolio projects showcasing skills

 MATCHING JOBS FOUND:
   • Senior Data Scientist at TechCorp → [Apply Now]
   • ML Engineer at StartupXYZ → [Apply Now]
   • Python Developer at BigTech → [Apply Now]
```

## Troubleshooting

### Common Issues

| Issue | Solution |
|-------|----------|
| **API Authentication Errors** | Verify API keys are correctly set in environment variables |
| **PDF Processing Errors** | Ensure PDF is not password-protected and contains readable text |
| **Connection Timeouts** | Check internet connection and API service status |
| **Missing Dependencies** | Run `pip install -r requirements.txt` again |
| **Gradio Interface Issues** | Restart the application and refresh browser |

### Getting Help

- **Issues**: Report bugs via [GitHub Issues](https://github.com/yourusername/career-catalyst-pro/issues)
- **Documentation**: Check the [Wiki](https://github.com/yourusername/career-catalyst-pro/wiki)
- **Community**: Join our [Discussions](https://github.com/yourusername/career-catalyst-pro/discussions)

##  Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on:

- Code style and standards
- Pull request process
- Issue reporting
- Feature requests

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google for the powerful Gemini AI API
- Apify for job scraping capabilities
- Gradio team for the amazing web interface framework
- Open source community for various Python libraries

## Roadmap

- [ ] Support for multiple resume formats (DOCX, TXT)
- [ ] Advanced job filtering options
- [ ] Resume optimization suggestions
- [ ] Integration with LinkedIn
- [ ] Mobile-responsive interface
- [ ] Multi-language support

---

<div align="center">

**Start your career growth journey today!** 

</div>
