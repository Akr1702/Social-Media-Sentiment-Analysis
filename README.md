
# Social Media Sentiment Analysis Web App  

[Social Media Sentiment Analysis Web App]


![54bcc95b-043b-428a-9570-12e1409877b7](https://github.com/user-attachments/assets/065a14e6-b02c-465c-89aa-55fed3451f78)

## Overview  

This repository contains a Shiny-based web application designed to analyze and predict sentiment trends in social media content. Social media sentiment analysis helps businesses, researchers, and policymakers understand public opinion, monitor brand reputation, and detect emerging trends. Our web application offers an interactive platform for users to upload data, analyze sentiment, and visualize results dynamically.  

## Features  

- **Sentiment Prediction Model**: Classifies text data into positive, negative, or neutral sentiment based on advanced Machine Learning(ML) techniques.  
- **Interactive Visualization**:  
  - 3D Graphs, bar graphs, and time-series plots for sentiment trends.  
  - Dynamic visuals to gain actionable insights.  
- **User Authentication**:  
  - Secure Google-based login and logout system.  
- **Data Insights**: Provides historical and real-time analysis of social media data trends across platforms.  

## Parameters Used in Prediction  

The application uses the following parameters for sentiment analysis:  

- **ID**   
- **Text Content**  
- **Post Timestamp**  
- **Platform (e.g., Twitter, Instagram, Reddit)**  
- **Number of Likes/Reactions**  
- **Number of Shares/Retweets**  
- **Hashtags Used**  
- **Language**  
- **Geographical Location (Optional)**  

## Files in the Repository  

1. **app.R**: Core RShiny application code, including user interface and server logic.  
2. **cleaned_social_media_dataset.csv**: Preprocessed dataset of social media posts with attributes required for sentiment analysis.  
3. **sentiment_analysis.pbix**: Power BI file containing detailed sentiment analysis and visual reports for insights.  

## How to Use  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/social-media-sentiment-analysis.git  
   cd social-media-sentiment-analysis  
   ```  
2. **Install Required Libraries**:  
   Ensure you have the following R packages installed:  
   - shiny  
   - ggplot2  
   - plotly  
   - shinythemes  
   - tidytext  
   - dplyr  
3. **Run the Application**:  
   Open `app.R` in RStudio and click on the `Run App` button. Alternatively, use:  
   ```R  
   shiny::runApp('app.R')  
   ```  
4. **Access the Web App**:  
   Navigate to the provided localhost URL to interact with the app.  

## Key Functionalities  

- **Sentiment Prediction**: Upload a CSV of social media posts to predict sentiment categories (positive, negative, or neutral).  
- **Data Visualization**:  
  - Explore 3D Graphs and sentiment trends with interactive visualizations.  
  - Identify spikes in sentiment over time or across platforms.  
- **Secure Access**: Google login ensures secure user authentication for app usage.

  ## ER Diagram
   
  
![image-Photoroom](https://github.com/user-attachments/assets/21941cea-2beb-41c2-a623-871977307f6e)



## WEBSITE :


![WhatsApp Image 2025-01-03 at 22 33 07_6984d542](https://github.com/user-attachments/assets/77340577-2f77-4888-a423-05f6d191a275)

## POWER_BI :

![WhatsApp Image 2025-01-03 at 20 08 36_c60e2791](https://github.com/user-attachments/assets/c0ac1963-f37f-494a-a5f7-43a9c6bbed90)

## Future Work  

- Integration of real-time social media APIs (e.g., Twitter API, Facebook Graph API).  
- Improved sentiment models with context-aware ML frameworks. 
- Mobile-responsive web app design for broader accessibility.  

## Acknowledgments  

This project was developed to empower organizations and individuals in understanding public sentiment and trends on social media. Special thanks to all contributors and data providers.  

## Contact  

For any queries or contributions, please contact:  
- **Ankit Kumar Khimaram Luhar**
- Email : [ankitluhar123@gmail.com](mailto:ankitluhar123@gmail.com)
- **Ankit Kumar Rai**  
- Email: [ankitkumarrai1702@gmail.com](mailto:ankitkumarrai1702@gmail.com)
