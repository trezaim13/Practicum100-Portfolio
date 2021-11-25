
# **Frequentist AB Testing**

**[Project Notebook](https://github.com/trezaim13/Practicum100-Portfolio/blob/main/Frequentist-AB-Test/Frequentist-AB-Test.ipynb)**

This project is the continuation of an unachieved A/B test on 6000 users of the online store. **The goal of this A/B test is to test changes related to the introduction of an improved recommendation system with a new payment funnel.** 
    
Before we proceed to the A/B test, we will examine the data and the test results provided before we finish with conclusions about both.

The study will be conducted in two big parts : The first part will consist of prioritizing the hypotheses. The second part will consist of an A/B testing analysis. For this study we have the following datasets :
* `ab_project_marketing_events_us` : the calendar of marketing events for 2020,
* `final_ab_new_users_upd_us` : all users who signed up in the online store from 07-12-2020 to  21-12-2020, 
* `final_ab_events_upd_us` : all events of the new users within the period from 07-12-2020 to 01-01-2021, 
* `final_ab_participants_upd_us` : table containing test participants. 

### Technical description of the data

- **Test name** : recommender_system_test ;
- **Groups** : А (control), B (new payment funnel) ;
- **Launch date** : 2020-12-07 ;
- **Date when they stopped taking up new users** : 2020-12-21 ;
- **End date** : 2021-01-01 ;
- **Audience** : 15% of the new users from the EU region ;
- **Purpose of the test** : testing changes related to the introduction of an improved recommendation system 
- **Expected result** : within 14 days of signing up, users will show better conversion into product page views (the product_page event), instances of adding items to the shopping cart (product_cart), and purchases (purchase). At each stage of the -funnel product_page → product_cart → purchase, there will be at least a 10% increase.
- **Expected number of test participants** : 6000

## Please open file on nbviewer to view all the interractive graphs
