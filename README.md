This is the Pulse Youth Empowerment Platform, a minimalist application designed to support and motivate young students.

## Hosting the Website Locally

To host the website on your local device, follow these steps:

1. **Clone the Repository**
   
   Open your terminal and run the following command to clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**

   Change into the project directory:
   ```bash
   cd <directory-name>
   ```

3. **Set Up a Virtual Environment** (Optional but recommended)

   Create a virtual environment to manage dependencies:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

4. **Install Dependencies**

   Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Flask Application**

   Start the Flask development server:
   ```bash
   set FLASK_APP=app.py
   flask run
   ```

   By default, the website will be accessible at `http://127.0.0.1:5000/`.

6. **Access the Website**

   Open your web browser and go to `http://127.0.0.1:5000/` to view the website.
