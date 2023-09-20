# 360-Degree Feedback Software for Government of India News Stories

![Project Logo](project_logo.png)

## Overview

This repository contains the code and documentation for a 360-Degree Feedback software designed to analyze news stories related to the Government of India in regional media using advanced Artificial Intelligence (AI) and Machine Learning (ML) techniques. The project leverages state-of-the-art IndicBERT models and cutting-edge Natural Language Processing (NLP) techniques to provide sentiment analysis and categorization of news stories by department. Additionally, it offers an intuitive dashboard for efficient content sorting, filtering, and inspection.

## Advanced Technologies Used

- **IndicBERT Models**: We utilize state-of-the-art IndicBERT models, incorporating research from IIT Madras, to analyze regional news in major Indian languages with high accuracy.

- **NLP Techniques**: Our system employs advanced NLP techniques, including transformers, Speech-to-Text, and Optical Character Recognition (OCR) capabilities, to extract and analyze news content.

- **Python Tools**: The project integrates Python tools for web scraping, real-time notifications, and data preprocessing.

## Frameworks and Libraries

This section lists the major frameworks and libraries used to bootstrap our project:

- **Next.js**: Used for building the user-friendly frontend of the dashboard.

- **React**: Complements Next.js for building interactive user interfaces.

- **Flask**: Powers the backend of our application, handling data processing and serving API endpoints.

- **Node.js**: Used for server-side scripting and for managing dependencies.

## Data Aggregation & Department Categorization

- **Data Sources**: Our system gathers data from diverse sources, including:
  - Web scraping of regional media websites.
  - E-paper text extraction via OCR.
  - YouTube video analysis for news content.

- **Sentiment Analysis**: We provide sentiment analysis for each news story, categorizing them as positive, neutral, or negative.

- **Categorization by Department**: News stories are categorized by the department they are related to within the Government of India.

## Dashboard

- **User-Friendly Interface**: The project features an intuitive dashboard built with Next.js for the frontend and Flask for the backend.

- **Efficient Content Management**: Users can easily sort, filter, and inspect news stories using the dashboard, ensuring quick access to relevant information.

- **AWS Hosting**: The dashboard is hosted on Amazon Web Services (AWS) for scalability and reliability.

## Machine Learning Models

- **IndicBERT Fine-Tuning**: We fine-tune a pretrained IndicBERT model to achieve high-quality predictions on regional news content.

- **Prediction Pipeline**: A streamlined pipeline is set up to preprocess new data and pass it through the model for accurate sentiment analysis and categorization.

## Installation and Usage

For detailed instructions on how to install and use the software, please refer to the [Installation Guide](docs/INSTALL.md) and [User Manual](docs/USER_MANUAL.md) in the documentation folder.

## Contributing

We welcome contributions from the community to enhance this project. Please see our [Contributing Guidelines](CONTRIBUTING.md) for more information on how to get involved.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For inquiries, support, or feedback, please contact us at [contact@example.com](mailto:contact@example.com).

---