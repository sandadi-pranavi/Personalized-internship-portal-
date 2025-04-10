# Personalized-internship-portal-
# Personalized Internship Portal

A machine learning-powered internship portal that matches candidates with internship opportunities based on their skills, qualifications, and preferences.

## Features

- Secure user authentication and profile management
- ML-based internship matching using:
  - KNN algorithm for location matching
  - NLP for resume parsing and description matching
  - Ensemble methods (SVM, Random Forest, Decision Trees) for skills and qualification matching
- Interactive dashboard with visualizations
- Email notifications for internship matches
- Resume upload and parsing (PDF/DOC support)

## Setup Instructions

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Configure environment variables:
   - Rename `.env.example` to `.env`
   - Update email credentials and other settings

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Project Structure

- `app.py`: Main application file with Streamlit UI
- `ml_pipeline.py`: ML algorithms for internship matching
- `database.py`: Database operations and user management
- `internships.csv`: Sample internship dataset

## Usage

1. Register/Login to access the portal
2. Complete your profile with qualifications and preferences
3. Upload your resume in PDF or DOC format
4. Get matched internships based on your profile
5. Apply to internships and receive email notifications

## Technologies Used

- Frontend: Streamlit
- ML: scikit-learn, NLTK
- Database: SQLite
- File Processing: PyPDF2, python-docx

  
