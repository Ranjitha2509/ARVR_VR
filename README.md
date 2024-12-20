# TredFit - Virtual Fitness App

## Overview

TredFit is a virtual fitness application designed to provide an immersive workout experience in a virtual environment. The app leverages WebXR technology to create a 3D space where users can engage in various fitness activities. The application tracks user movement, calculates calories burned, and provides a visually appealing interface to enhance the workout experience.

## Features

- **Immersive VR Experience**: Utilizes WebXR to create a virtual environment for workouts.
- **Calorie Tracking**: Calculates and displays calories burned based on user movement.
- **User Data Collection**: Collects user data such as name, weight, height, and fitness milestones.
- **Interactive UI**: Provides a user-friendly interface with welcome screens, forms, and success messages.
- **3D Models**: Loads and displays 3D models of the workout environment.

## Installation

To run TredFit locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ranjitha2509/ARVR_VR.git
   cd ARVR_VR
   ```

2. **Install Dependencies**:
   Ensure you have Node.js and npm installed. Then, install the necessary dependencies:
   ```bash
   npm install
   ```

3. **Run the Application**:
   Start a local server to run the application. You can use any HTTP server, such as `http-server`:
   ```bash
   npm run dev
   ```

4. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8080`.

## Usage

1. **Welcome Screen**:
   Upon loading the application, you will be greeted with a welcome screen. Click "Continue" to proceed.

2. **User Form**:
   Fill out the form with your name, weight, height, and fitness milestone. Click "Submit" to save your data.

3. **Success Message**:
   After submitting the form, a success message will appear. Click "I'm Ready" to enter the VR environment.

4. **VR Environment**:
   Once in the VR environment, you can start your workout. The application will track your movement, calculate calories burned, and display your score.

## Upcoming Additions : Teleportation
**Overview:**
We are currently developing the teleportation feature to enhance navigation in the VR environment. This feature allows users to move quickly by pointing their controllers and triggering a teleport action.

**Challenges:**
1. **Controller Direction Detection:** The application sometimes fails to accurately detect the controller's pointing direction due to inconsistencies in WebXR API reports.
2. **Intersection Detection:** The raycaster occasionally misses intersections with the ground or other objects, causing unexpected behavior.

**Next Steps:**
1. **Refine Raycaster Logic:** Improve accuracy in detecting the controller's pointing direction.
2. **Enhance Error Handling:** Implement robust error handling for missed intersections.
3. **Testing and Optimization:** Conduct extensive testing to fix remaining bugs and ensure a smooth teleportation experience.

Thank you for your patience and support as we work to finalize this feature! 

## Code Structure

- **`init.js`**: Contains the main initialization logic for the VR environment, including scene setup, camera configuration, and WebXR integration.
- **`index.js`**: Handles the loading of 3D models, text display, and the overall scene setup.
- **`index.html`**: The main HTML file that structures the welcome screen, form, and success message.

## Dependencies

- **Three.js**: A JavaScript 3D library used for rendering the VR environment.
- **WebXR**: Provides support for immersive VR experiences in web browsers.
- **GLTFLoader**: A loader for loading 3D models in GLTF format.

## Contributing

Contributions to TredFit are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## Acknowledgements

- **CAVE Labs:** Special thanks to CAVE (CAVE Augmented and Virtual Environments) Lab for their support.
- **Dr. Adithya Balasubraminiyam:** Grateful acknowledgment to Dr. Adithya Balasubraminiyam, course instructor and mentor, for his invaluable help and insights.
- **PES University and Department of CSE:** Special thanks to PES University and the Department of Computer Science and Engineering for their support and resources.

## Contributors

- Sharanya G S
- Shreeraksha 
- Ranjitha

---

Enjoy your virtual fitness journey with TredFit! 🚀
