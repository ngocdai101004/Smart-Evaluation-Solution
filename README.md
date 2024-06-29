<p align="center">
  <img src="https://i.ibb.co/hR2kbXD/icon22.png" width="180" >
</p>
<h1 align="center">Smart Evaluation Solution</h1>

<p align="center">
  <em>This project is a collaborative effort to integrate cutting-edge AI technologies into Heineken Vietnam's operations, enhancing efficiency, customer experience, and strategic decision-makin</em>
</p>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>

- [📍 Overview](#-overview)
- [Workflow](#-workflow)
- [👾 Demo](#-demo)
- [🧩 Features](#-features)
- [🤖Technologies Used](#-technologies-used)
- [🚀 Usage](#-getting-started)
- [🧑‍💻 Contributing](#-contributing)
</details>

## 📍 Overview

HEINEKEN Vietnam, the leading beer producer in Vietnam, aims to revolutionize brand experience for consumers. From local retail stores to favorite hangout spots with friends, you can easily spot Heineken's advertising materials (banners, posters, LED signs, etc.). These elements contribute to an engaging and memorable experience for customers. However, manually inspecting and evaluating these setups through images is time-consuming and costly for the company.

Our mission is to develop an image analysis tool that can automatically detect the following elements:

1. **Brand Logos**: Detect logos of Heineken, Tiger, Bia Viet, Larue, Bivina, Edelweiss, and Strongbow.
2. **Products**: Recognize beer cases and bottles.
3. **Consumers**: Evaluate the number, activities, and emotions of customers.
4. **Advertising Materials**: Identify posters, banners, and brand advertisements.
5. **Image Context**: Analyze the location—restaurant, bar, grocery store, or supermarket, etc.

This project leverages advanced AI technologies, including Optical Character Recognition (OCR) and Large Language Models (LLMs), to process and analyze data collected from various retail settings. The workflow ensures data accuracy, extracts meaningful features, and generates predictive insights that guide strategic adjustments.
## Workfow
![image](https://github.com/ngocdai101004/Smart-Evaluation-Solution/assets/121254456/6e17b750-6220-4606-84d2-fdff5b056ce1)


## 🤖Technologies Used

- _Optical Character Recognition (OCR)_
- _Large Language Models (LLMs)_
- _Machine Learning and AI Algorithms_
- _Data Analysis and Visualization Tools_

## 👾 Demo

## 🧩 Features

### 1. Object Detection: Accurately identifies objects within images using advanced GenAI models.

### 2. Insight Generation: Offers suggestions based on detected objects and user-provided context.

### 3. User-Friendly Interface: Easy to use and understand, allowing for quick and efficient analysis.

## 🚀 Usage

### 1. Installation:

```Python
git clone https://github.com/What-s-behind/UTI
cd /UTI
pip install -r requirements.txt
```

### 2. Setup the environment

Then, you are required to get the API key from Gemini and Groq:

- [Gemini's API key](https://aistudio.google.com/app/apikey)
- [Groq's API key](https://console.groq.com/keys)

After that, let's create a `.env` file and follow this format:

```
GEMINI_API_KEY="GEMINI_API_KEY"
GROQ_API_KEY="GROQ_API_KEY"
```

> We leave the `.env.examples` as a template for implementing our environment.

### 3. Running the Application:

Navigate to the project directory in your terminal. Run the following command:

```
streamlit run app.py
```

## 🧑‍💻 Contributing

- _Lê Đức Minh_ | **LinkedIn:** [/in/minh-le-duc/](https://www.linkedin.com/in/minh-le-duc-a62863172/) | **Gmail:** minh.leduc.0210@gmail.com
- _Lê Nguyễn Đăng Khoa_ | **LinkedIn:** [/in/khoale-maiu/](https://www.linkedin.com/in/khoale-maiu/) | **Gmail:** khoale.maiu@gmail.com
- _Trần Ngọc Đại_ | **LinkedIn:** [/in/ngoc-dai-tran/](https://www.linkedin.com/in/ngoc-dai-tran-621b62292/) | **Gmail:** ngocdai101004@gmail.com
- _Phạm Minh Mẫn_ | **LinkedIn:** [/in/man-pham/](https://www.linkedin.com/in/m%E1%BA%ABn-ph%E1%BA%A1m-47b493311/) | **Gmail:** phamminhman1312005@gmail.com
