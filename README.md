# BMI-Calculator

## Table of Contents
- [Project Overview](#project-overview)
- [Reasons for Making This Project](#reasons-for-making-this-project)
- [Tools Used](#tools-used)
- [Tasks Performed](#tasks-performed)
- [Results and Findings](#results-and-findings)

---

## Project Overview:
The BMI Calculator is a lightweight and responsive web application developed using HTML, CSS, and JavaScript. It allows users to calculate their Body Mass Index (BMI) by entering their height (in centimeters) and weight (in kilograms). The app then displays the BMI value along with a classification such as Underweight, Normal, Overweight, or Obese. The interface is designed with a clean layout, styled using modern CSS, providing an intuitive and user-friendly experience.

---

## Reasons for Making This Project:
- **Practice Core Web Technologies**: To gain hands-on experience with HTML, CSS, and JavaScript.
- **Health Awareness**: To help users quickly check their BMI and understand their weight category.
- **Interactive Learning**: To apply DOM manipulation and event handling in a real-world context.
- **Frontend Design**: To build a visually appealing interface using gradients, shadows, and responsive input fields.

---

## Tools Used:
- **HTML5**: For structuring the web page.
- **CSS3**: For styling and responsive layout.
- **JavaScript**: For implementing BMI calculations and dynamic UI updates.

---

## Tasks Performed:

### 1) Interface Design:
- A centered container was styled using CSS Flexbox and gradient backgrounds.
- Input fields for height and weight were added with placeholders and default values.

### 2) BMI Calculation Logic:
- On button click, JavaScript fetches user inputs and calculates BMI using the formula:  
  **BMI = weight / (height in meters)²**
- The BMI is displayed in a disabled input field.

### 3) Weight Classification:
- Based on the BMI value, the app determines the weight condition:
  - **< 18.5**: Underweight  
  - **18.5 – 24.9**: Normal weight  
  - **25 – 29.9**: Overweight  
  - **30 and above**: Obese  
- This result is displayed using dynamic text updates.

---

## Results and Findings:
- The BMI Calculator accurately computes and classifies user BMI.
- It offers real-time feedback with a simple click, enhancing interactivity.
- Styling gives it a polished, professional look despite its minimal structure.
- The project serves as a perfect entry-level example of combining structure, style, and logic in frontend development.
