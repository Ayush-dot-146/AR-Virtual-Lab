# AR-Virtual-Lab


An Augmented Reality (AR) Virtual Lab designed to simulate digital electronics experiments right in your browser. Explore the behavior of logic gates and flip-flops in an interactive, 3D environment without the need for physical hardware.

## ✨ Features

- **Interactive 3D Simulations:** Visualize and interact with digital components like logic gates and flip-flops in a simulated AR space.
- **Browser-Based:** No additional software installation required. Works directly in modern web browsers.
- **Educational Focus:** Ideal for students and educators in computer science and electrical engineering to understand fundamental digital logic concepts.
- **Intuitive Interface:** Simple drag-and-drop and point-and-click mechanics for building and testing circuits.
- **Cross-Platform:** Accessible on various devices with a web browser.

## 🛠️ Technologies Used

This project is built using core web technologies to ensure accessibility and ease of use.

| Technology | Purpose |
| :--- | :--- |
| **HTML** | Structure and content of the virtual lab web pages. |
| **CSS** | Styling and visual presentation of the user interface. |
| **JavaScript** | Interactive logic, 3D rendering, and AR simulation functionality. |

The repository structure indicates a strong focus on frontend development for an immersive, web-based experience.

## 📁 Project Structure

Here is a high-level overview of the main files and directories in this repository:

AR-Virtual-Lab/
├── main/ # Main application directory
│ ├── GATES/ # Directory for logic gate components
│ ├── flip flops/ # Directory for flip-flop components
│ ├── index.html # Main landing page of the application
│ ├── virtual_lab.html # The core virtual lab interface
│ ├── cg.html # Page related to combinational gates (CG)
│ ├── deld-combinational-lab.html # Digital electronics lab page
│ ├── app.js # Main JavaScript logic for the application
│ ├── cg.js # JavaScript specific to combinational gates
│ ├── style.css # Global stylesheet
│ ├── start_server.bat # Batch script to start a local server (Windows)
│ └── start_server.py # Python script to start a local server
└── README.md # Project documentation (this file)


## 🚀 Getting Started

Follow these instructions to set up and run the AR Virtual Lab on your local machine.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- **(Optional)** A local web server. Some features may require a server environment to function correctly. You can use the provided scripts to start one.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ayush-dot-146/AR-Virtual-Lab.git

2. Navigate to the project directory:
   cd AR-Virtual-Lab

Running the Application
Since the project is built with static HTML, CSS, and JavaScript, you can open the index.html file directly in your browser. However, for the best experience and to avoid potential cross-origin issues, it is recommended to run it on a local server.

Option 1: Directly open index.html
Navigate to the main folder and double-click the index.html file.

Option 2: Using a local server (Recommended)
For Windows users:

Double-click the start_server.bat file in the main directory. This will open a command prompt and start a Python HTTP server.

For users with Python installed (Windows, macOS, Linux):

Open your terminal or command prompt in the main directory.

Run the following command:

bash
python start_server.py
Or, if you have Python 3 installed, you can manually start a server with:

bash
python -m http.server 8000
Once the server is running, open your web browser and navigate to http://localhost:8000 (or the port specified by the script).

📖 Usage
Open the application in your browser as described in the Running the Application section.

Explore the main dashboard to access different lab modules (e.g., Logic Gates, Flip-Flops).

Select a component from the available options.

Drag and drop components onto the workspace to build your digital circuit.

Connect components by drawing wires between their terminals.

Observe the output in real-time, and compare your results with expected truth tables or waveforms.

🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE file for more information.

🙏 Acknowledgments
This project was created to provide a free and accessible educational tool for learning digital electronics.

Inspiration for this project comes from various online virtual lab platforms and the need for hands-on experience without physical constraints.

<p align="center"> Made with ❤️ by <a href="https://github.com/Ayush-dot-146">Ayush-dot-146</a> </p> ```
