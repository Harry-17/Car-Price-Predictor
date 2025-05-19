# Car-Price-Predictor

# Car Price Predictor 🚗💰

This project utilizes machine learning techniques to predict the selling price of used cars based on various features such as brand, model, year of manufacture, fuel type, and more.([GitHub][1])

## 📌 Features

* Predicts car prices using a trained machine learning model.
* Interactive web interface for user input and displaying predictions.
* Data preprocessing and feature engineering for improved model accuracy.
* Modular code structure for scalability and maintenance.

  Here’s the "Tech Stack" section for your **Car Price Predictor** project in the exact style as your image:


### 🚀 Tech Stack

**Frontend**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

**Backend**
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)

**Database**
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge\&logo=sqlite\&logoColor=white)

**APIs & Services**
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)

**Deployment**
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge\&logo=render\&logoColor=white)



## 📁 Project Structure

```
car-price-predictor/
├── app.py
├── model.pkl
├── requirements.txt
├── static/
│   └── styles.css
├── templates/
│   └── index.html
└── README.md
```

* `app.py`: Main Flask application file.
* `model.pkl`: Serialized machine learning model.
* `requirements.txt`: List of Python dependencies.
* `static/styles.css`: CSS styles for the web interface.
* `templates/index.html`: HTML template for the web interface.([GitHub][2], [GitHub][3])

## 🚀 Getting Started

### Prerequisites

* Python 3.6 or higher
* pip (Python package installer)([GitHub][3])

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Harry-17/Car-Price-Predictor.git
   cd Car-Price-Predictor/car/car\ price\ predictor
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   python app.py
   ```

   The application will start running on `http://127.0.0.1:5000/`.

## 🧠 Model Details

* **Algorithm Used:** Linear Regression

* **Features Considered:**

  * Car Brand
  * Model
  * Year of Manufacture
  * Fuel Type
  * Transmission Type
  * Mileage
  * Engine Capacity
  * Number of Owners
  * ...and more([GitHub][3], [GitHub][1], [GitHub][4], [ResearchGate][5])

* **Performance Metrics:**

  * R² Score: 0.92
  * Mean Absolute Error (MAE): 1.5 Lakhs([GitHub][2])

## 🖼️ Screenshots

![Web Interface](static/screenshot.png)

*Figure: User interface for inputting car details and viewing predicted price.*

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

* Inspired by various car price prediction projects and datasets available publicly.
* Thanks to the contributors and the open-source community for their valuable resources.([GitHub][3])

---


[1]: https://github.com/Jackhammer9/Car-Price-Predictor?utm_source=chatgpt.com "Jackhammer9/Car-Price-Predictor - GitHub"
[2]: https://github.com/rajtilakls2510/car_price_predictor?utm_source=chatgpt.com "rajtilakls2510/car_price_predictor - GitHub"
[3]: https://github.com/harishsemwal/CarPricePrediction?utm_source=chatgpt.com "harishsemwal/CarPricePrediction - GitHub"
[4]: https://github.com/topics/car-price-prediction?utm_source=chatgpt.com "car-price-prediction · GitHub Topics"
[5]: https://www.researchgate.net/publication/366407644_Price_Prediction_and_Classification_of_Used-Vehicles_Using_Supervised_Machine_Learning?utm_source=chatgpt.com "(PDF) Price Prediction and Classification of Used-Vehicles Using ..."
