# Tonia-vuln-scanner

A web vulnerability scanner with a React frontend and Python Flask backend. This application allows users to scan websites for common security vulnerabilities including XSS, SQL Injection, security header configurations, and open ports.

## Features

- URL validation
- XSS vulnerability detection
- SQL Injection vulnerability detection
- Security headers analysis
- Open ports scanning
- Informational pages about different vulnerabilities

## Project Structure

```
tonia-vuln-scanner/
├── frontend/               # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── App.js          # Main React component
│   │   ├── App.css         # Styles
│   │   └── index.js        # Entry point
│   ├── package.json
│   └── README.md
└── backend/                # Python Flask backend
    ├── app.py              # Main Flask application
    └── requirements.txt    # Python dependencies
```

## Setup and Installation

### Backend (Flask)

1. Navigate to the backend directory:
   ```
   cd tonia-vuln-scanner/backend
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

5. Run the Flask application:
   ```
   python app.py
   ```

### Frontend (React)

1. Navigate to the frontend directory:
   ```
   cd tonia-vuln-scanner/frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## Usage

1. Enter the URL of the website you want to scan in the provided input field
2. Click the "Scan" button to start the scanning process
3. View the results of the scan, which will show:
   - XSS vulnerabilities
   - SQL Injection vulnerabilities
   - Security headers analysis
4. You can also navigate to the "Open ports scan" page to check for open ports on the target website
5. The information pages provide educational content about different vulnerabilities

## Security Considerations

This tool is designed for educational purposes and security testing on websites you own or have permission to test. Do not use this tool to scan websites without proper authorization, as this may be illegal depending on your jurisdiction.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
