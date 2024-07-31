# Generative-AI-Project-On-Medical-Disease-Analysis-using-GPT4-Vision
This project is a Streamlit-based web application designed for medical disease analysis using the GPT-4 vision model. Users can upload images, and the application will analyze the image to provide a detailed description or diagnosis. 

## Key Features
- Image Upload and Display: Users can upload images in JPG, JPEG, or PNG formats.
- The uploaded image is displayed in the application.
- Image Analysis: The application encodes the image to Base64 and sends it along with a prompt to the GPT-4 vision model for analysis.
- The analysis result is displayed on the application.


### How to run:

1. Create a new environment 

```bash
conda create -n llmapp python=3.10 -y
```

2. Activate the environment

```bash
conda activate llmapp
```

3. Install required packages

```bash
pip install -r requirements.txt
```


4. Run the app.py

```bash
streamlit run app.py
```



