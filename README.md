# ⚡ Dynamic Energy Optimizer

A **Flask-based web application** that helps users analyze and optimize household or office energy usage. Users can input appliance details, usage hours, and costs, then get **smart insights, optimization suggestions, and visualizations** to reduce energy consumption and save money.

---

## **Features**

- **Dynamic Appliance Management**
  - Add or remove multiple appliances with a user-friendly form.
  - Input estimated **daily usage hours** and **daily cost** for each appliance.

- **Real-Time Pop-up Notification**
  - Confirms appliances added before displaying optimization results.

- **Energy Optimization Results**
  - Displays per-appliance summary:
    - Hours used
    - Daily cost
    - Estimated monthly cost
    - Predicted peak usage hours
    - Optimization suggestions

- **Summary Cards**
  - Total appliances added
  - Total estimated monthly cost

- **Visual Representation**
  - **Bar chart** showing usage hours for all appliances.
  - Styled with a **light purple theme** for a modern look.

- **Responsive UI Design**
  - Mobile-friendly and easy to navigate.

- **Backend**
  - Powered by **Flask**
  - Handles input and calculates usage insights.
  - Returns structured JSON for frontend visualization.

---

## **Tech Stack**

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask)  
- **Visualization:** Chart.js  
- **Cross-Origin Support:** Flask-CORS  
- **Deployment:** Can be hosted on Replit, Render, PythonAnywhere, or any Flask-supported platform.

---

## **How It Works**

1. Open the web page.
2. Add appliances and set daily usage hours and costs using interactive sliders.
3. Click **Optimize Energy**; a **notification pop-up** confirms appliance addition.
4. Optimization results are displayed along with a **bar chart**.
5. View insights, suggestions, and monthly cost summary to adjust usage patterns.
