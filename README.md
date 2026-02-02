\# Face Recognition Attendance System



An AI-based attendance system that uses facial recognition to automatically mark attendance.



---



\##  Features



\- Face detection using OpenCV

\- Face recognition model training

\- Automatic attendance marking

\- Attendance stored in CSV file

\- Streamlit-based interactive interface



---



\##  Tech Stack



\- Python

\- OpenCV

\- NumPy

\- Pandas

\- Streamlit

\- Scikit-learn



---



\##  Project Structure



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




\## ▶️ How to Run



1\. Install dependencies  

&nbsp;  pip install -r requirements.txt  



2\. Train the model  

&nbsp;  python trainer.py  



3\. Run the app  

&nbsp;  streamlit run streamlit\_app.py  



---



\## 📚 Learnings



\- Practical implementation of Computer Vision

\- Real-time face detection

\- Model training workflow

\- Building interactive UI with Streamlit


