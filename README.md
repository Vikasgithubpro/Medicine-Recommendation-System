# Medicine Recommendation System 💊

A machine learning-based system that recommends appropriate medicines based on symptoms and medical conditions. This system helps users and healthcare professionals get intelligent medicine suggestions for common ailments.

## Features ✨

- **Symptom Analysis**: Input symptoms and get relevant medicine recommendations
- **Condition-Based Search**: Find medicines for specific medical conditions
- **Dosage Information**: Get recommended dosage and usage instructions
- **Side Effects Warning**: View potential side effects and precautions
- **Drug Interactions**: Check for possible drug interactions
- **User-Friendly Interface**: Simple and intuitive web interface

## Tech Stack 🛠️

### Frontend
- HTML5, CSS3, JavaScript
- Bootstrap 5
- Responsive Web Design

### Backend
- Python 3.8+
- Flask Web Framework
- Pandas for data processing
- Scikit-learn for machine learning

### Machine Learning
- Recommendation algorithms
- Natural Language Processing for symptom analysis
- Collaborative filtering techniques

### Data
- Comprehensive medicine database
- Symptom-medicine mapping
- Drug interaction data

## Installation 🚀

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vikasgithubpro/Medicine-Recommendation-System.git
   cd Medicine-Recommendation-System
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. **Access the application**
   Open your browser and navigate to `http://localhost:5000`

## Project Structure 📁

```
Medicine-Recommendation-System/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── static/               # Static files (CSS, JS, images)
│   ├── css/
│   ├── js/
│   └── images/
├── templates/            # HTML templates
│   ├── base.html
│   ├── index.html
│   └── results.html
├── data/                 # Dataset files
│   ├── medicines.csv
│   ├── symptoms.csv
│   └── interactions.csv
├── models/               # Machine learning models
│   ├── recommendation_model.pkl
│   └── symptom_analyzer.pkl
├── utils/                # Utility functions
│   ├── data_processor.py
│   ├── recommender.py
│   └── validator.py
└── tests/                # Test cases
    ├── test_recommender.py
    └── test_validator.py
```

## Usage 💡

### Basic Usage
1. Enter symptoms in the search box
2. Select from suggested symptoms
3. View recommended medicines with details
4. Check dosage and precautions

### Advanced Features
- Filter by age group
- Specify existing medical conditions
- Check for drug allergies
- View alternative medicines

## API Endpoints 🌐

### Get Medicine Recommendations
```http
POST /api/recommend
Content-Type: application/json

{
  "symptoms": ["fever", "headache"],
  "age": 30,
  "conditions": ["hypertension"]
}
```

### Search Medicines
```http
GET /api/search?query=paracetamol
```

### Check Drug Interactions
```http
POST /api/interactions
Content-Type: application/json

{
  "medicines": ["medicine1", "medicine2"]
}
```

## Dataset Information 📊

The system uses a comprehensive dataset containing:
- 500+ common medicines
- 1000+ symptoms and conditions
- Drug interaction data
- Dosage information for different age groups
- Side effects and precautions

## Contributing 🤝

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer ⚠️

**Important**: This system is for educational and informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

- The recommendations are generated based on algorithms and may not be accurate
- Always consult healthcare professionals before taking any medication
- Do not disregard professional medical advice because of something you have read here

## Support 🆘

If you encounter any issues or have questions:

1. Check the [FAQ](docs/FAQ.md)
2. Search existing [Issues](https://github.com/Vikasgithubpro/Medicine-Recommendation-System/issues)
3. Create a new Issue with detailed information

## Acknowledgments 🙏

- Medical professionals who provided domain expertise
- Open-source communities for valuable libraries and tools
- Contributors and testers who helped improve the system

---

<div align="center">

**Made with ❤️ for better healthcare accessibility**

[Report Bug](https://github.com/Vikasgithubpro/Medicine-Recommendation-System/issues) · [Request Feature](https://github.com/Vikasgithubpro/Medicine-Recommendation-System/issues)

</div>
