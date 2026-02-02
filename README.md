#  Face Recognition Attendance System



An AI-based attendance system that uses facial recognition to automatically mark attendance.



---



##  Features



\- Face detection using OpenCV

\- Face recognition model training

\- Automatic attendance marking

\- Attendance stored in CSV file

\- Streamlit-based interactive interface



---



##   Tech Stack



\- Python

\- OpenCV

\- NumPy

\- Pandas

\- Streamlit

\- Scikit-learn



---



##   Project Structure



assets/

dataset/

model/

attendance.csv

dataset\_creator.py

recognizer.py

streamlit\_app.py

trainer.py

haarcascade\_frontalface\_default.xml

requirements.txt



---

## Note

The dataset folder is not included in this repository due to size limitations.
You can create your own dataset using dataset_creator.py 


##  Screenshots

### Home Page
![Home Page](OUTPUTS/HOME%20PAGE.png)

### Register Face
![Register Face](OUTPUTS/register%20face.png)

### Capturing Face
![Capturing Face](OUTPUTS/capturing%20face.png)

### Taking Attendance
![Taking Attendance](OUTPUTS/page%20for%20taking%20attendence.png)

### Detected Face & Attendance
![Detected Face](OUTPUTS/detected%20face_taking%20attendence.png)

### Stored Attendance Record
![Stored Attendance](OUTPUTS/stored%20attendence%20record.png)

### Dataset Gallery
![Dataset Gallery](OUTPUTS/dataset%20gallery.png)

### Deleting Student Detail
![Deleting Student Detail](OUTPUTS/deleting%20student%20detail.png)

### Face Registered
![Face Registered](OUTPUTS/face%20registered.png)

### Gallery of Selected ID
![Gallery of Selected ID](OUTPUTS/gallery%20of%20student%20of%20selected%20id.png)

### Side Navigation Panel
![Side Navigation Panel](OUTPUTS/Side%20navigation%20panel.png)

### Download Attendance CSV
![Download Attendance CSV](OUTPUTS/downloading%20attendence.csv.png)

### Train the Model
![Train the Model](OUTPUTS/train%20the%20model.png)

### Unknown / Non-Registered Face
![Unknown Face](OUTPUTS/unknown_non%20registered%20face.png)


##  How to Run



1\. Install dependencies  

&nbsp;  pip install -r requirements.txt  



2\. Train the model  

&nbsp;  python trainer.py  



3\. Run the app  

&nbsp;  streamlit run streamlit\_app.py  



---



##  Learnings



\- Practical implementation of Computer Vision

\- Real-time face detection

\- Model training workflow

\- Building interactive UI with Streamlit






