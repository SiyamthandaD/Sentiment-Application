# 📊 Sentiment Analysis Tool
A powerful web application that analyzes text sentiment in real-time, providing deep insights into emotional tone, polarity, and emotional characteristics.
Built with modern web technologies for accurate and instant sentiment detection.

## 🖥️ Home Page Preview
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/176b3fc4-a36a-4e21-aaff-ebd19dd9ab87" />

## 🌐 Live Demo
Access the live application at: https://sentimentv1.netlify.app/

## ✨ Features
### ⚡ Real-time sentiment analysis
   - Instant Sentiment Detection: Get immediate feedback as you type.
   - Live Polarity Scoring: Dynamic positive/negative/neutral scoring.
   - Continuous Emotion Tracking: Real-time emotion detection updates.
### 📊 Comprehensive Insights
   - Detailed Polarity Breakdown: Percentage-based sentiment scoring.
   - Emotion Classification: Identify specific emotions (joy, anger, sadness, etc.)
   - Visual Analytics: Interactive charts and graphs for data visualization.
### 💾 Data Management
   - Analysis History: Automatic logging of previous sentiment analyses.
   - Session Persistence: Maintain your analysis history across sessions.
   - Export Capabilities: Save or export results for further analysis.
### 📱 User Experience
   - Responsive Design: Optimized for desktop, tablet, and mobile devices.
   - Intuitive Interface: Clean, modern, and user-friendly design.
   - Accessibility Focused: Built with accessibility best practices.

## 🛠️ Technology Stack
### Frontend Development
   - ⚡ JavaScript (ES6+) - Core programming language.
   - 🎨 HTML5 & CSS3 - Modern web standards and styling.
   - ⚛️ React - Component-based UI library.
   - 💨 Tailwind CSS - Utility-first CSS framework.
### APIs & Services
   - 🧠 Gemini API - Advanced Natural Language Processing.
   - ☁️ Netlify - Cloud hosting and deployment platform.
### Data Visualization
   - 📈 Chart.js - Interactive charts and data visualization.
   - 📊 Custom Visualizations - Tailored sentiment display components.

## 🚀 Getting Started
### Prerequisites
- ⚙️ Node.js (version 16.0 or higher).
- 📦 npm (version 8.0 or higher)/yarn.

### Installation
* Clone the repository:
   ```bash
   git clone https://github.com/SiyamthandaD/Sentiment-Application.git
   cd Sentiment-Application
* Install dependencies:
  ```bash
   npm install
   # or
   yarn install
* Set up environment variables (if required)
   ```bash
   # Create a .env file in the root directory
   # Add your API keys and configuration
   REACT_APP_GEMINI_API_KEY=your_api_key_here
* Run the development server:
   ```bash
   npm start
   # or
   yarn start
* Open your browser
Navigate to *http://localhost:3000* to view the application

## Available Scripts
* npm start - Runs the app in development mode.
* npm run build - Builds the app for production.
* npm test - Launches the test runner.
* npm run eject - Ejects from Create React App (one-way operation)

## 💡 Usage Guide
* Basic Text Analysis
   - Enter your text in the input field.
   - View real-time sentiment results.
   - Analyze polarity scores and emotional tone.
* Advanced Features
   - Explore detailed emotion breakdowns.
   - Review historical analysis data.
   - Export results for reporting.
* API Integration
   - Connect with Google Cloud Natural Language API.
   - Customize analysis parameters.
   - Scale for high-volume text processing.

## 📁 Project Structure
* Sentiment Application
   ```bash
   Sentiment-Application/
   ├── public/                     # Static assets
   │   ├── index.html              # Main HTML template
   │   ├── favicon.ico             # Application favicon
   │   └── manifest.json           # PWA manifest
   ├── src/                        # Source code
   │   ├── components/             # React components
   │   │   ├── AnalysisChart/      # Data visualization components
   │   │   ├── EmotionDisplay/     # Emotion visualization
   │   │   ├── HistoryPanel/       # Analysis history
   │   │   ├── InputArea/          # Text input components
   │   │   └── ResultsPanel/       # Results display
   │   ├── services/               # API and external services
   │   │   ├── geminiAPI.js        # Gemini API integration
   │   │   └── sentimentService.js # Sentiment analysis logic
   │   ├── utils/                  # Utility functions
   │   │   ├── textProcessor.js    # Text preprocessing
   │   │   └── formatters.js       # Data formatting
   │   ├── hooks/                  # Custom React hooks
   │   │   ├── useSentiment.js     # Sentiment analysis hook
   │   │   └── useHistory.js       # History management
   │   ├── styles/                 # Styling files
   │   │   ├── tailwind.css        # Tailwind imports
   │   │   └── components.css      # Component-specific styles
   │   ├── App.js                  # Root application component
   │   ├── App.css                 # Main application styles
   │   └── index.js                # Application entry point
   ├── package.json                # Project dependencies and scripts
   └── netlify.toml                # Netlify deployment configuration

## Key Components
* InputArea - Text input and real-time processing.
* ResultsPanel - Display sentiment scores and analysis.
* AnalysisChart - Visual representation of sentiment data.
* EmotionDisplay - Detailed emotion classification.
* HistoryPanel - Previous analysis tracking.

## 🔌 API Integration
### Gemini API Configuration
* The application integrates with Google's Gemini API for advanced natural language processing:
   ```bash
   // Example API integration
   const analyzeSentiment = async (text) => {
     const response = await fetch('https://api.gemini.google.com/v1/analyze', {
       method: 'POST',
       headers: {
         'Authorization': `Bearer ${apiKey}`,
         'Content-Type': 'application/json'
       },
       body: JSON.stringify({ text: text })
     });
     return await response.json();
   };

## 🚀 Deployment
### Netlify Deployment
* The application is configured for seamless deployment on Netlify:
   - Automatic Deployments: Connected to GitHub for CI/CD.
   - Environment Variables: Secure API key management.
   - Performance Optimization: Built-in caching and CDN.
### Build for Production
* This creates an optimized production build in the build folder.
   ```bash
   npm run build

## 🤝 Contributing
We welcome contributions from the community! Whether you're fixing bugs, adding new features, or improving documentation, your help is appreciated.
## Contribution Workflow
* Fork the repository.
* Create a feature branch
   ```bash
   git checkout -b feature/amazing-feature
* Commit your changes
   ```bash
   git commit -m 'Add some amazing feature'
* Push to the branch
   ```bash
   git push origin feature/amazing-feature
* Open a Pull Request

## Development Guidelines
* Follow React best practices and component patterns.
* Ensure responsive design for all components.
* Maintain accessibility standards.
* Write clear commit messages.
* Update documentation for new features.

## 📄 License
* This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
* Technologies & Services
   - Google Gemini API - For powerful natural language processing capabilities.
   - React Community - For excellent documentation and ecosystem.
   - Chart.js - For beautiful and accessible data visualizations.
   - Tailwind CSS - For efficient and consistent styling.
   - Netlify - For seamless deployment and hosting.
* Inspiration
   - Natural Language Processing research and applications.
   - User experience design principles for data visualization.
   - Open-source sentiment analysis tools and libraries.
 
<div align="center">
💫 Support This Project
If you find this sentiment analysis tool helpful, please consider giving it a ⭐️ on GitHub!

Built with ❤️ by Siyamthanda Dlakavu

Understanding emotions through technology, one analysis at a time.

</div>
