# MediSafe AI – Medication Safety and Dosage Recommendation System

MediSafe AI is a healthcare-focused web application developed using Python and Flask to help users understand medication safety based on their personal information and medication details. The system provides personalized safety checks, dosage recommendations, drug interaction warnings, allergy alerts, and medication-related precautions.

## Features

* User registration and login
* Personalized medication safety checking
* Age and weight-based dosage recommendations
* Drug-drug interaction checking
* Allergy conflict detection
* Contraindication checking
* Medication side-effect information
* Food and medication precaution guidance
* Safety score generation
* Explainable safety recommendations
* Prescription generation
* Medication chatbot
* External drug information using FDA Drug Label API
* Unit testing using Pytest

## Technologies Used

* Python
* Flask
* Pandas
* MySQL / SQL
* HTML5
* CSS3
* JavaScript
* REST API
* FDA Drug Label API
* JSON
* CSV
* Pytest

## Project Structure

```text
MediSafe AI/
│
├── app.py
├── requirements.txt
├── medicines.csv
│
├── routes/
├── services/
├── models/
├── utils/
├── config/
├── database/
│
├── templates/
├── static/
├── tests/
├── docs/
└── assets/
```

## How It Works

1. The user registers or logs into the application.
2. The user provides relevant information such as age, weight, medical condition, allergies, and medication details.
3. The system processes the entered information.
4. It checks medication interactions, allergies, contraindications, dosage suitability, and other safety conditions.
5. A safety score is generated based on the identified risks.
6. The system provides a recommendation along with understandable reasons for the result.
7. Users can also access medication information and interact with the medication chatbot.

## Medication Safety

The system evaluates medication safety using multiple factors, including:

* Patient age
* Patient weight
* Existing medical conditions
* Current medications
* Known allergies
* Drug interactions
* Contraindications
* Food and medication precautions

The results are presented in an understandable format to help users identify potential medication-related risks.

## API Integration

The application can retrieve additional medication information through the FDA Drug Label API. This provides access to publicly available drug labeling information.

## Testing

The project includes automated tests using Pytest to verify important application functionality.

Current test result:

```text
22 tests passed
```

## Installation

Clone the repository:

```bash
git clone <your-github-repository-url>
cd MediSafe-AI
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open the application in your browser using the local Flask address displayed in the terminal.

## Future Enhancements

* Integration with machine learning models
* Improved personalized medication recommendations
* Advanced patient history management
* Doctor and pharmacist dashboards
* Online prescription management
* Cloud database integration
* Mobile application support

## Disclaimer

MediSafe AI is an educational software project and should not be used as a replacement for professional medical advice. Users should consult a qualified healthcare professional before making decisions regarding medications or dosage.


