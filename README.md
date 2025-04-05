# 🔥 Cooling Rate Optimization in Additive Manufacturing using Machine Learning

## 📌 Project Overview

This project focuses on creating a **data-driven control system** to maintain a **constant cooling rate** during the Laser-Directed Energy Deposition (L-DED) process in additive manufacturing. Using temperature data from dual pyrometers, the system uses **machine learning** to adjust **deposition velocity** in real-time, ensuring better quality and consistency of the manufactured part.

---

## 🎯 Goals

- Maintain constant cooling rate during metal additive manufacturing.
- Use temperature data (T1 and T2) to calculate cooling rate.
- Predict optimal deposition velocity using machine learning.
- Improve repeatability and part quality.
- Contribute to smart manufacturing and Industry 4.0.

---

## ⚙️ How It Works

1. **Collect data**: Readings from two pyrometers (T1 and T2).
2. **Calculate cooling rate**:  
   \[
   \text{Cooling Rate} = \frac{T1 - T2}{\text{Time Interval}}
   \]
3. **Compare** with the **desired cooling rate** set by user.
4. **ML model** (e.g. Random Forest) predicts the best velocity.
5. **Adjust deposition velocity** in real-time to maintain stability.

---

## 🧠 Tech Stack

- Python 3.x (Colab or Jupyter)
- scikit-learn
- NumPy, Pandas
- Matplotlib / Seaborn
- Google Drive (for data + model storage)
- GitHub (for code versioning)

---

## 📂 Project Structure

cooling-rate-ml-project/ │ ├── notebooks/ # Jupyter or Colab notebooks ├── data/ # Sample temperature data (T1, T2, etc.) ├── models/ # Trained ML models (.pkl files) ├── src/ # Python scripts (future modular code) └── README.md # Project summary and documentation

yaml
Copy
Edit

---

## 📈 Models Implemented

- ✅ Random Forest Regressor (working)
- 🔄 Support Vector Regressor (in progress)
- 🔄 Linear Regression (baseline)
- 🔜 Neural Network (planned)

---

## 📊 Sample Code Snippet

```python
# Calculate cooling rate
cooling_rate = (T1 - T2) / time_interval

# Predict deposition velocity
predicted_velocity = model.predict([[T1, T2, desired_cooling_rate]])
🌱 Future Work
Add real-time sensor integration

Train model with live data from L-DED machine

Deploy code on embedded systems for real-time feedback

Explore control of other AM parameters (like laser power)

✨ Impact
This project is an example of AI in manufacturing, enabling intelligent control in metal 3D printing. It reduces waste, increases precision, and helps move toward autonomous, sustainable, and consistent production systems in Industry 4.0.

📬 Contact
Aditya Manoj Madgulkar
MTech in Additive Manufacturing, IIT Hyderabad
LinkedIn
Email

