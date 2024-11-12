
# Online Shopping Intention Analysis


## Overview
In the rapidly evolving landscape of e-commerce, understanding user behavior during online sessions is crucial for optimizing marketing strategies and improving conversion rates. This project focuses on analyzing a dataset consisting of 12,330 online shopping sessions, each representing unique user interactions over the course of a year

## Dataset
The dataset used in this project is accessible [here](https://drive.google.com/file/d/1XuA-c22c5MOFKMo9fe5h0t2inGDVjl14/view?usp=drive_link). It contains a collection of text samples labeled with corresponding emotions.

## Key Components
1. **Loading and Preprocessing**: 
   - Loaded the dataset and performed necessary preprocessing steps, including text cleaning, tokenization, and stopword removal.
   - Techniques such as stemming and lemmatization were applied to refine the text data.

2. **Basic EDAS**:
   - Adopted Basic EDA Techniques to provide an overall information and the statistical overview of the data set.

3. **Visualization and trend analysis**:
   - Various Visualization Tecniques used:
     - Count Plot
     - boxplot
     - pairplot
     -histogram

4. **Outlier Removal**:
   - Cleaned Data for better performance.

5. **Feature Engineering**:
   - Converted all object and boolean columns to int and fload using label encoding

## Requirements
- Python 3.x
- NLTK
- Scikit-learn
- Pandas
- NumPy

## GOAL
 Analysis Goals
Our goal is to:

Identify key patterns and relationships within the data.
Inform the development of predictive models.
Evaluate the effectiveness of different features in driving conversions.
Provide actionable recommendations for e-commerce platforms.

- **Administrative**: Number of pages visited in the "Administrative" category during a session (e.g., account management, support pages).

- **Administrative Duration**: Total time spent on "Administrative" pages during the sessionHelps assess user engagement with administrative or support-related content. A longer duration could indicate issues with user navigation or problem resolution.

- **Informational**: Number of pages visited in the "Informational" category (e.g., FAQ, blog, product descriptions)

- **Informational Duration**: Total time spent on "Informational" pages during the session.ndicates the level of interest in learning more about the products or services offered. Longer duration could suggest deeper engagement or confusion.

- **Product Related**: Number of product-related pages visited during a session (e.g., product listings, individual product pages).

- **Product Related Duration**: Total time spent on product-related pages during the session.Reflects how much time users spend exploring products. Higher values might indicate serious interest in purchasing or extensive browsing.

- **Bounce Rate**: Percentage of visitors who land on a particular page and leave without navigating to another page within the session.A high bounce rate suggests that users are not finding what they expected or the page isn’t engaging enough. This could negatively affect conversion rates.

- **Exit Rate**: Percentage of users who leave the site after visiting a particular page. It’s measured relative to all pageviews on that specific page. Identifies the pages from which users most frequently exit. A high exit rate could point to issues like confusing layout or poor user experience, especially near the checkout process.

- **Page Value**: The average value of a page that users visit before completing an e-commerce transaction. Typically based on the monetary value attributed to that page in a session leading to a conversion.Helps assess the importance of specific pages (product, category, or landing pages) in driving conversions. High page values are indicative of pages that play a significant role in transaction completion

- **Special Day**: Indicates the proximity of a visit to a special shopping day (e.g., Mother's Day, Black Friday, Valentine's Day).Accounts for increased purchase likelihood during special days. A higher value (closer to the special day) suggests that the user is more likely to make a purchase. This feature helps identify trends and patterns around seasonal buying behaviors.

- **Operating System**: The type of operating system used by the visitor (e.g., Windows, macOS, iOS, Android).Useful for optimizing the website’s user experience across different platforms and detecting system-related issues.

- **Browser**: The browser used by the visitor (e.g., Chrome, Firefox, Safari). Helps assess compatibility with different browsers and identify potential issues affecting user experience on specific browsers.

- **Region**: The geographical location of the visitor (could be by country, state, or city).Useful for regional market analysis and tailoring promotions. Understanding where users come from helps optimize marketing strategies and content localization.

- **Traffic Type**: The source of the website’s traffic (e.g., direct, organic search, referral, paid search).Helps assess the effectiveness of different marketing channels and campaigns. Allows for targeted optimization of traffic acquisition strategies.

- **Visitor Type (Returning or New)**: Indicates whether the visitor is a returning customer or a new visitor.Returning visitors are typically more valuable, as they are more likely to convert. New visitors may require different engagement strategies, such as offering promotions or improving the first-time user experience.

- **Weekend (Boolean)**: Whether the visit occurred during the weekend (Friday, Saturday, Sunday).Weekend visits might show different patterns of behavior, such as longer browsing times or higher conversion rates. Analyzing this can help optimize for peak shopping times.

- **Month of the Year**: The specific month in which the session occurred.Identifies seasonality and trends in consumer behavior, helping to adjust marketing and inventory management strategies accordingly

