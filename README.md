# AI-Powered Health Risk Assessment Tool 🏥 ( LINK - healthriskapp.leandrenash.com )
<img width="1463" alt="Screenshot 2025-01-02 at 19 10 12" src="https://github.com/user-attachments/assets/b83dddb4-60f4-439d-8469-f1adc7030093" />

## Description
An advanced machine learning-powered application that provides comprehensive health risk assessments based on individual lifestyle factors, medical history, and health indicators. The tool offers personalized health insights and predictive risk analysis to help users understand and manage their health risks.
## Features
- 🔍 Real-time health risk assessment
- 📊 Interactive visualization of risk factors
- 💡 Personalized health recommendations
- 📈 Feature importance analysis
- 🛡️ Privacy-focused (all processing done locally)
## Technologies Used
- Python 3.11
- Streamlit (Web Framework)
- Scikit-learn (Machine Learning)
- Plotly (Data Visualization)
- NumPy (Numerical Computing)
## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/health-risk-analyzer.git
cd health-risk-analyzer
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the application:
```bash
streamlit run main.py
```
The application will be available at `http://localhost:5000`
## Project Structure
```
├── .streamlit/
│   └── config.toml      # Streamlit configuration
├── main.py             # Main application file
├── model.py            # ML model implementation
├── utils.py            # Utility functions
└── README.md          # Documentation
```
## Usage
1. Launch the application using `streamlit run main.py`
2. Fill in the health assessment form with your information:
   - BMI
   - Exercise frequency
   - Smoking status
   - Alcohol consumption
   - Sleep patterns
   - Blood pressure
   - Cholesterol levels
   - Family medical history
   - Stress levels
3. Click "Calculate Health Risk" to get your assessment
4. Review your results, including:
   - Overall risk level
   - Risk probability distribution
   - Personalized recommendations
   - Factor importance analysis
## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
## License
This project is licensed under the MIT License - see the LICENSE file for details.
## Disclaimer
This tool provides general health risk assessment and should not be used as a substitute for professional medical advice. Always consult with healthcare professionals for medical decisions.
