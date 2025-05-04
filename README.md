# GalaxyERP AI Assistant

GalaxyERP is an intelligent Enterprise Resource Planning (ERP) system powered by AI, built during the Gen AI Exchange Bootcamp in Ahmedabad. It provides a modern, user-friendly interface for managing inventory, production, accounting, and GST compliance through natural language interactions.

## 🌟 Features

- **AI-Powered Assistant**: Natural language interface for ERP operations
- **Inventory Management**: Real-time tracking and automated reordering
- **Financial Management**: Automated accounting and GST compliance
- **Production Planning**: Intelligent scheduling and resource allocation
- **Modern UI**: Responsive design with beautiful animations
- **Cloud Ready**: Deployable on Google Cloud Run

## 🚀 Live Demo

The application is currently deployed at: https://erp-buddy-service-806556013178.us-central1.run.app/

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python Flask
- **AI Integration**: Google Dialogflow
- **Deployment**: Google Cloud Run
- **Containerization**: Docker

## 📁 Project Structure

```
galaxyerp-ai-assistant/
├── app.py              # Flask application
├── Dockerfile          # Container configuration
├── requirements.txt    # Python dependencies
├── templates/          # HTML templates
│   └── index.html     # Main application interface
└── inventory.txt      # Sample inventory data
```

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Google Cloud account
- Docker (for containerization)

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/galaxyerp-ai-assistant.git
cd galaxyerp-ai-assistant
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

### Deployment

1. Build the container:
```bash
gcloud builds submit --tag gcr.io/YOUR_PROJECT_ID/erp-buddy .
```

2. Deploy to Cloud Run:
```bash
gcloud run deploy --image gcr.io/YOUR_PROJECT_ID/erp-buddy --platform managed --region us-central1
```

## 📚 Documentation

- [Project Documentation](https://docs.google.com/document/d/18PcE6NOlDjCX5HWBvGbYmlmOMWacOzzcwif-q68Z7e4/edit)
- [Vertex AI Agent Builder Guide](https://codelabs.developers.google.com/devsite/codelabs/building-ai-agents-vertexai)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Built during the Gen AI Exchange Bootcamp - Ahmedabad
- Special thanks to the Google Cloud team and Hack2skill
- Inspired by the Vertex AI Agent Builder codelab 