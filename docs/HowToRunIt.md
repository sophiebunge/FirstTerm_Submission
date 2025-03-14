# Guide to Download and Set Up the React App with Backend

_I attempted to deploy the website online using Render.com and Vercel.com but encountered significant difficulties and errors that I couldn't resolve. As a result, the project will need to be deployed locally for now._

## Prerequisites

Ensure you have the following installed on your system:

---

- **The Code**: You can find the project in the same github repository: bunge > final submission > codeDigitalTwin. Download all foldern backend, frontend, and .gitignore and open them in Visual Studio Code.

---

- **Git**: Download Git
- **Node.js** Latest LTS version
- **Python 3.10.12**: [Download Python](https://www.python.org/downloads/release/python-31012/) The Python version is important!
- **pip** and **virtualenv** (should be included with Python)

## Backend Setup

1. In Visual Studio Code navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Create and activate a virtual environment:

   ```sh
   python3 -m venv venv      # Creates an Virtual Environment
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```

   It should look like this: **(venv) username DigitalTwin %**

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the backend server:
   ```sh
   python app.py
   ```

## Frontend Setup

1. Open a new Terminal window and navigate to the frontend folder:

   ```sh
   cd ../DigitalTwin/frontend
   ```

2. If the virtual environment is still on, deactivate it using the comand:

   ```sh
   deactivate
   ```

   _if you are using conda or zsh_

   ```sh
   zsh
   conda deactivate
   ```

3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the frontend development server:

   ```sh
   npm run dev
   ```

5. Click on the Link to open the website:

## Running the Application

- Ensure both servers are running to fully use the app.

<img src="./img/localrun.png" alt="Terminal Server" width="800">
