# PGA Tour Advanced Analytics
This project endeavors to revolutionize PGA Tour predictions by combining traditional machine learning techniques with cutting-edge in-context learning models, utilizing tools like ChatGPT's Advanced Data Analysis, Claude, and Microsoft Copilot. Moving beyond conventional analytics, the project aims to accurately predict player finishes and tournament outcomes, demonstrating the advanced capabilities of AI in transforming sports analytics and potentially influencing the sports betting industry.

## Project PI/Project Team 

Zach Printz, zachary.h.printz@vanderbilt.edu, printzzh, PI

## Project Proposal  

### Description of Problem/Opportunity
Predicting outcomes in professional golf, particularly on the PGA Tour, is a formidable challenge. The sport is characterized by significant week-to-week variability and a myriad of external factors that uniquely affect each player, making the task of accurately forecasting the winner of any given tournament exceptionally difficult. While predictive analysis in golf has been extensively explored, it remains an unconquered frontier, especially in the PGA Tour context. The availability of comprehensive data in the PGA Tour opens up new avenues for advanced data analysis. Traditional predictive models have made strides but often fall short in deciphering the complex patterns and nuances inherent in golf data. This presents a unique opportunity to apply more sophisticated and modern AI techniques, such as in-context learning, to not only enhance prediction accuracy but also to test these methods against established machine learning approaches. The project aims to explore these cutting-edge methodologies, assessing their potential to redefine predictive analytics in golf and potentially influence the future of sports anaytics.

### Proposed Solution/Approach
For this project, I propose a two-pronged approach to analyze data from the PGA Tour, with an emphasis on exploring both traditional machine learning models and innovative in-context learning techniques.

    1. Traditional Machine Learning Analysis: Initially, the project will utilize data directly sourced from the PGA Tour website, focusing on strokes gained and other relevant performance metrics. This phase will involve the application of established machine learning methods such as linear regression, random forest, gradient boosting, and others. The aim is to establish a baseline predictive model by leveraging these traditional approaches, analyzing the golfer's performance in comparison to the tour average.

    2. In-Context Learning Analysis: Subsequent to the traditional model, the project will shift focus to explore the capabilities of in-context learning, a cutting-edge AI methodology. This approach will involve utilizing a suite of advanced AI tools, including ChatGPT Advanced Data Analysis, Claude, and Microsoft Copilot, each offering unique capabilities in processing PGA Tour data. The key advantage here lies in their varying strengths, particularly in terms of context window and analytical depth. While Claude, known for its expanded context window, might emerge as the frontrunner, the project remains open to leveraging whichever tool demonstrates the strongest results in understanding and interpreting the data. The overarching goal is to critically assess whether this modern, multi-tool AI approach can surpass traditional methods, not only in prediction accuracy but also in the depth and relevance of insights generated.

Throughout the project, the  capabilities of AI will play a crucial role in autonomously determining the most effective analysis techniques, adapting to the nuances of the PGA Tour data. This flexible and dynamic model selection is aimed at enhancing the overall accuracy of predictions and pushing the boundaries of what is possible in sports analytics. The ultimate objective is to compare the effectiveness of these two distinct methodologies in predicting PGA Tour outcomes, potentially paving the way for a new era in predictive analytics within the realm of professional golf along with other sports down the road.


### Project Outline and Timeline
Data Collection (1/8 - 1/14): Collect and source data from the PGA Tour website for the 2023 season. Tasks include cleaning, structuring, and preparing the data, with a focus on addressing missing values, outliers, and data normalization.

Initial Model Selection (1/15 - 1/21): Introduce the cleaned data to AI tools like ChatGPT Advanced Data Analysis, Claude, and Microsoft Copilot. This phase is dedicated to determining the best initial data analysis method based on tool recommendations.

Model Refinement (1/22 - 1/28): Refine and optimize the chosen model. This involves parameter adjustments and feature experimentation to enhance predictive accuracy.

In-Context Learning Setup (1/29 - 2/11): Begin setting up the in-context learning model. This includes configuring tools like Claude for PGA Tour data analysis and calibrating the model to handle the specific complexities of the dataset.

In-Context Learning Implementation and Adjustment (2/12 - 3/10): Implement the in-context learning model, with ongoing adjustments and refinements. This period is vital for testing and fine-tuning the model based on initial outputs and performance.

Comparative Analysis and Prediction (3/11 - 3/31): Use both the traditional and in-context learning models to predict outcomes of PGA Tour events. This phase focuses on running and comparing the models side by side.

Validation and Assessment (4/1 - 4/14): Assess the effectiveness of both models by comparing their predictions with actual PGA Tour outcomes, analyzing accuracy, and model strengths.

Project Finalization and Documentation (4/15 - 4/22): Conclude the project by consolidating all findings. Finalize the models based on validation feedback, and document the project's insights, learnings, and recommendations.

## Goals of project 

    1. High Accuracy in Traditional Model Predictions: Achieve a high level of predictive accuracy using traditional machine learning methods. This goal is centered on effectively forecasting player finishes in PGA Tour events using established data analysis techniques.

    2. High Accuracy in In-Context Learning Model Predictions: Attain similar or superior predictive accuracy with the in-context learning model. This emphasizes exploring the potential of modern AI methodologies in sports predictions.

    3. Comparative Analysis for Broad Methodological Insights: Determine which method, traditional machine learning or in-context learning, is more effective for predictive analysis in golf, with an eye towards the wider applicability of these findings. The goal is not only to identify the superior approach for golf but also to provide insights that could be generalized to other sports or domains where predictive analytics play a key role.

    4. Demonstration of AI Tool Capabilities: Illustrate the capabilities of various AI tools such as ChatGPT Advanced Data Analysis, Claude, and Microsoft Copilot in handling complex sports analytics tasks. This aims to highlight the adaptability and efficiency of AI tools in providing deep, actionable insights in the field of sports analytics.
      

## Project Metrics 

### Traditional Machine Learning Approach:

    1. Accuracy in Predicting the #1 Player:

            A: Model predicts the #1 player in its top 40 4/6 times or more.

            B: Model predicts the #1 player in its top 40 3/6 times.

            C: Model predicts the #1 player in its top 40 2/6 times.

            D: Model predicts the #1 player in its top 40 1/6 times.

            F: Model never predicts the #1 player in its top 40.

    2. Accuracy in Predicting the Tournament's Top 10:

            A: For at least 4/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            B: For 3/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            C: For 2/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            D: For 1/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            F: The model never places 3 or more of the actual top 10 finishers within its top 40 predicted players.

### In-Context Learning Approach:

    1. Accuracy in Predicting the #1 Player:

            A: Model predicts the #1 player in its top 40 4/6 times or more.

            B: Model predicts the #1 player in its top 40 3/6 times.

            C: Model predicts the #1 player in its top 40 2/6 times.

            D: Model predicts the #1 player in its top 40 1/6 times.

            F: Model never predicts the #1 player in its top 40.

    2. Accuracy in Predicting the Tournament's Top 10:

            A: For at least 4/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            B: For 3/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            C: For 2/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            D: For 1/6 tournaments, the model places 3 or more of the actual top 10 finishers within its top 40 predicted players.

            F: The model never places 3 or more of the actual top 10 finishers within its top 40 predicted players.

