# Airline_anlaytics_app
Airlines Analytics Dashboard — A Python + Tkinter app for analyzing airline data. Visualizes sector-wise traffic, market share, delays, and demand forecasts using Pandas and Matplotlib. Features a modern two-tone GUI for interactive aviation data insights.



Airlines Data Analytics Dashboard📊 Built with Python, Tkinter & Matplotlib
An interactive desktop application that performs data analytics and visualization on Indigo Airlines’ business model and operations.
This project combines data science and GUI development to make insights visually accessible through a modern Tkinter-based dashboard.
🧠 Overview
The application analyzes Indigo Airlines’ operational data — including passenger traffic, route performance, delay patterns, and market share.
It is designed with a Tkinter Designer–style interface (modern blue-white layout) and follows a modular, object-oriented structure.
🎯 Key Features

🧩 Modular structure (Data Loader, Analysis, Visualization, GUI)


📈 Sector-wise passenger traffic visualization


🥧 Airline market share analysis


⏰ Delay and punctuality insights


📉 Passenger demand forecasting


🎨 Modern two-tone GUI (Blue sidebar + White main panel)


🖼️ Embedded matplotlib charts
🏗️ Architecture

User
  ↓
GUI Layer (Tkinter)
  ↓
Visualization Module (Matplotlib)
  ↓
Analysis Engine (Pandas, Numpy)
  ↓
Data Loader (CSV / Kaggle Dataset)
🧩 Modules
ModuleFileDescriptionData Loaderdataloader.pyReads and cleans dataset (CSV)Analysis Engineanalysis.pyPerforms data analysis (traffic, share, delay, forecast)Visualizationvisualization.pyCreates charts (bar, pie, line)GUIgui.pyInteractive dashboard using TkinterMain Entrymain.pyRuns the application
📁 Project Structure

Indigo_Analytics_App/
│
├── dataloader.py          # Loads and cleans raw data
├── analysis.py            # Performs calculations & analytics
├── visualization.py       # Handles plotting with matplotlib
├── gui.py                 # Modern Tkinter UI
├── main.py                # Entry point to run the app
└── indigo_dataset_500.csv # Sample dataset (500 records)
📂 Dataset Structure
The app reads a .csv file with airline data.
The following columns are required for analysis.

Column NameDescriptionExampleSectorFlight route (Origin–Destination).DEL-BLR, BOM-HYDAirlineAirline name.IndiGo, Vistara, Air IndiaPassengersNumber of passengers (or passenger volume).178, 165DelayAverage delay (in minutes).12, 8, 0DateDate of flight or record (YYYY-MM-DD).2022-01-15
📊 Sample Data Preview
SectorAirlinePassengersDelayDateDEL-BLRIndiGo178122022-01-15BOM-HYDVistara15082022-01-15MAA-BLRAir India165152022-01-16DEL-MAAIndiGo182102022-01-17BLR-PNQSpiceJet16052022-01-18
📁 Dataset Source
You can use either:


🧾 The provided indigo_dataset_500.csv


📦 Or a Kaggle dataset such as:
Indian Airlines Performance Dataset

🚀 How to Run

Clone this repository:
git clone https://github.com/yourusername/Indigo-Analytics-App.gitcd Indigo-Analytics-App


Install dependencies:
pip install pandas matplotlib


Run the application:
python main.py


Load your dataset (.csv) using the “📂 Load Dataset” button in the GUI.
🖥️ User Interface💻 Modern Tkinter-Designer Look

Blue sidebar with action buttons


White main panel with charts


Embedded matplotlib graphs


Title and footer branding

Interface Layout:

+--------------------------------------------------------------+| Indigo Airlines — Analytics Dashboard                        || ┌──────────────┐  ┌────────────────────────────────────────┐ || │  Sidebar     │  │       Graph & Insights Area            │ || │  📂 Load Data │  │  [Matplotlib Chart Canvas]            │ || │  📊 Market    │  │                                       │ || │  ⏰ Delay     │  │                                       │ || └──────────────┘  └────────────────────────────────────────┘ |+--------------------------------------------------------------+
🧩 Technologies Used
PurposeTools/LibrariesGUITkinter, ttkData HandlingpandasVisualizationmatplotlibDesignCustom Tkinter Layout (Blue/White Theme)
🌟 Future Enhancements

Live data integration from DGCA or APIs


Real-time delay prediction using ML


Export reports to Excel/PDF


Dark/Light theme toggle


Airline logos and icons in sidebar
👨‍💻 Author
Sanmith Tejaswini
📧 Developed as part of a Data Analytics & GUI Development project.
✨ “Turning data into decisions — with code, clarity, and creativity.”
