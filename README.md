
# AI-Powered Maritime Route Optimization with Risk Assessment and Iceberg Avoidance

## Overview
The **AI-Powered Maritime Route Optimization with Risk Assessment and Iceberg Avoidance** system aims to enhance Arctic navigation by using artificial intelligence and machine learning. The system optimizes maritime routes while considering iceberg locations, weather conditions, and oceanographic risks to ensure safe, efficient, and environmentally responsible shipping in the Arctic. The platform integrates predictive models, real-time hazard detection, and dynamic rerouting to improve Arctic shipping logistics.

The core technologies include **TensorFlow.js**, **Random Forest algorithms**, **K-Means clustering**, and **OpenLayers** for real-time data visualization. This project is intended to serve as a foundation for scalable and intelligent maritime navigation solutions, particularly in polar regions, with potential for global maritime applications.

## Key Features
- **Optimized Route Generation**: Generates safe sea-only routes between Arctic ports considering various environmental factors.
- **Hazard Alerts**: Provides real-time notifications for risks such as icebergs, storms, and shallow waters.
- **Dynamic Rerouting**: Automatically recalculates the route when new hazards are detected.
- **Risk Visualization**: Displays traffic data, iceberg density, and risk zones using interactive visualizations.
- **Real-time Risk Detection**: Classifies environmental and iceberg risks using machine learning models.
- **Port Traffic Monitoring**: Analyzes port traffic and clusters using K-Means clustering to identify optimal routing strategies.

## Technologies Used
- **Frontend**:
  - **React.js** (with TypeScript) for building the interactive web-based interface.
  - **OpenLayers** for rendering real-time navigational maps.
  - **Recharts** for creating risk and traffic visualization charts.
- **Backend**:
  - **TensorFlow.js** for implementing trajectory prediction using machine learning.
  - **Python (scikit-learn)** for implementing machine learning models like Random Forest and K-Means clustering.
  - **Zustand** for real-time state management in the frontend.
- **Database**: MongoDB or Firebase for storing traffic data, risk information, and environmental parameters.
- **Tools**:
  - **Docker** (optional) for containerization.
  - **Postman** for API testing.
  - **Git** for version control.

## Prerequisites

Before running the system, ensure you have the following tools installed:

- **Node.js**: v18+ (for React.js, TensorFlow.js, and Zustand)
- **Python**: v3.10 or higher (for machine learning models)
- **MongoDB** or **Firebase**: For storing application data (set up an instance).
- **Git**: For version control.
- **Docker** (Optional): For containerization if needed.

### Required Node.js Modules

1. **React**: For building the frontend web app.
2. **TensorFlow.js**: For machine learning model inference and prediction.
3. **Zustand**: For managing global state in the frontend.
4. **OpenLayers**: For mapping and visualizing navigational routes.
5. **Recharts**: For visualizing risks and traffic data.
6. **Axios**: For making HTTP requests to external APIs.

To install these dependencies, run the following command in the root directory:

```bash
npm install
```

### Required Python Libraries

1. **scikit-learn**:- For implementing machine learning models like Random Forest and K-Means clustering.
2. **Pandas**:- For data manipulation and handling.
3. **Numpy**:- For numerical computations.
4. **Flask or FastAPI**:- For creating the backend API server (if needed).

To install the required Python libraries, run the following command:

```bash
pip install -r requirements.txt
```

## Clone the Repository

To get started with the project, clone the repository to your local machine using Git:

```bash
git clone https://github.com/Yash22222/Arctic-Route-Optimization-System.git
```

Navigate to the project directory:

```bash
cd maritime-route-optimization
```

## Setup and Configuration

### 1. Set Up the Frontend

#### Step 1: Install Node.js Dependencies
Run the following command to install all necessary dependencies for the frontend:

```bash
npm install
```

#### Step 2: Start the Development Server

Start the React development server to run the web application locally:

```bash
npm start
```

The app should now be running at `http://localhost:3000`.

#### Step 3: Access the Application
Open a browser and go to `http://localhost:3000` to access the interactive map and dashboard where routes and risks are displayed in real time.

### 2. Set Up the Backend

#### Step 1: Install Python Dependencies
Ensure you have installed Python 3.10 or higher. Then, install the necessary Python packages:

```bash
pip install -r requirements.txt
```

#### Step 2: Start the Backend Server

If you're using Flask or FastAPI to serve the machine learning models, start the server by running:

```bash
python app.py
```

The backend server should now be running, typically at `http://localhost:5000`. You can integrate APIs or handle the machine learning logic through this server.

### 3. Database Configuration

1. **MongoDB**:
   - If you're using MongoDB, ensure MongoDB is installed locally or use a cloud-based MongoDB instance.
   - Create a `.env` file in the project root and configure the database connection URL.

```bash
MONGODB_URI=mongodb://localhost:27017/maritimeDB
```

2. **Firebase**:
   - If you're using Firebase, set up Firebase in your project and generate the credentials JSON file.
   - Save the Firebase credentials in the `.env` file.

```bash
FIREBASE_CREDENTIALS_PATH=/path/to/credentials.json
```

## How to Contribute

If you would like to contribute to this project, follow these steps:

1. Fork the repository by clicking the "Fork" button at the top of the repository page.
2. Clone your forked repository:

```bash
git clone https://github.com/your-username/maritime-route-optimization.git
```

3. Create a new branch for your feature:

```bash
git checkout -b feature-xyz
```

4. Make your changes and commit them:

```bash
git add .
git commit -m "Add new feature XYZ"
```

5. Push your changes:

```bash
git push origin feature-xyz
```

6. Open a pull request to the `main` branch.

### Code Style Guidelines

- Follow **PEP 8** for Python code style.
- Use **ESLint** for JavaScript/TypeScript linting and follow **Airbnb** style guide for React code.
- Write unit tests for new features and bug fixes.

## Future Work
1. **Satellite Remote Sensing Data Integration**: Integrating real-time satellite data sources such as Sentinel-1 (SAR) and MODIS to enhance route accuracy and iceberg detection.
2. **3D Oceanographic and Weather Modeling**: Introducing 3D modeling to simulate ocean currents, wind profiles, and underwater topography for more accurate predictions.
3. **Reinforcement Learning for Autonomous Navigation**: Implementing RL agents for adaptive route planning based on evolving Arctic conditions and historical data.
4. **Vessel-Specific Optimization**: Enhancing the platform to consider vessel parameters like size, draft, speed, and fuel consumption for customized route planning.
5. **User Feedback Loop**: Introducing a feedback system to improve model performance based on real-world user inputs.
6. **Global Maritime Route Support**: Expanding the system to support global sea routes, including tropical cyclone zones, piracy-prone areas, and coral reefs.
7. **Blockchain Integration**: Utilizing blockchain technology for secure logging of voyage data, ensuring data integrity, and compliance with maritime regulations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or inquiries, feel free to contact the project maintainers:

- **Project Lead**:- [Yash Shirsath](mailto:yashshirsath2410@gmail.com)
- **GitHub**:- [Yash22222](https://github.com/Yash22222)
```

### Key Additions:
- **How to Clone**:- Instructions to clone the repository and start working on it.
- **Setup Instructions**:- A detailed setup for both frontend and backend, including dependencies and how to run the servers.
- **How to Contribute**:- Step-by-step guide on how others can contribute to the project.
- **Database Configuration**:- Instructions for setting up MongoDB or Firebase.
- **Future Work**:- Expanded section on possible future developments.
