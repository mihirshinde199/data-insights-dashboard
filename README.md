# 📊 Data Insights Dashboard

This is a web-based dashboard application that allows users to upload CSV data, visualize it with various charts, and receive AI-powered insights, future predictions, and actionable solutions based on the uploaded data. You can also select different machine learning model "perspectives" to guide the AI's analysis.

## ✨ Features

* **CSV File Upload:** Easily upload your data in CSV format.
* **Data Preview:** View the **first 5 rows** of your processed data in a clean table.
* **Dynamic Visualizations:** Automatically generates various charts (Line, Bar, Pie, Scatter) based on the data types detected in your CSV, providing immediate visual insights.
* **AI-Powered Insights:** Leverage a Large Language Model (LLM) to get comprehensive business insights, predictions, and solutions by simply asking a question.
* **ML Model Selection:** Choose from different machine learning model types (e.g., Linear Regression, KNN, Decision Tree, Clustering) to influence the LLM's analytical perspective for predictions and insights.
* **Aesthetically Pleasing UI:** Built with Tailwind CSS for a modern, responsive, and user-friendly experience.
* **Loading Indicators:** Visual feedback (spinner and an "analyzing" icon) during AI processing.

## 🚀 Setup & Run Instructions

To run this project locally, you'll need a web server. A simple way to do this is using `serve` (a static file serving utility).

### Prerequisites

* **Node.js** and **npm** (Node Package Manager) installed on your system.

### Installation

1.  **Create the project directory:**
    Create a folder named `your-data-dashboard` on your computer.

2.  **Create the files:**
    Inside `your-data-dashboard`, create the `src` folder and then create the `index.html`, `.env.example`, `package.json`, and `README.md` files with the content provided above.

3.  **Navigate to the project directory:**
    Open your terminal or command prompt and navigate to the `your-data-dashboard` directory:
    ```bash
    cd your-data-dashboard
    ```

4.  **Install `serve` (if you don't have it):**
    ```bash
    npm install -g serve
    # OR, if you prefer to use npx without global install:
    # npx serve src
    ```

### Running the Application

1.  **Start the local server:**
    From the `your-data-dashboard` directory, run:
    ```bash
    serve src
    ```
    This command tells `serve` to host the contents of the `src` directory.

2.  **Access the dashboard:**
    Open your web browser and navigate to the address provided by the `serve` command (usually `http://localhost:5000` or similar).

## 💡 Usage

1.  **Upload CSV:** Click on the "Drag & Drop or Click to Upload CSV" area and select your CSV file.
2.  **Process Data:** Click the "Process Data" button. The dashboard will display a preview of the first 5 rows of your data and automatically generate relevant charts.
3.  **Select ML Model (Optional):** Choose a machine learning model from the "Select Prediction Model" dropdown to influence the AI's analytical approach.
4.  **Get Insights:** Type your question or request into the input field (e.g., "What are the sales trends? Provide predictions.") and click "Get Insights." The AI will analyze your data and provide a detailed response based on the selected model's perspective.

## 🛠️ Technologies Used

* **HTML5:** For the basic structure.
* **Tailwind CSS:** For rapid and responsive styling.
* **JavaScript:** For all interactive logic, CSV parsing, and Chart.js integration.
* **Chart.js:** For dynamic data visualizations.
* **Google Gemini API:** For AI-powered insights, predictions, and solutions.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.
