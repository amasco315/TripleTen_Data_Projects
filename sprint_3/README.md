# Sprint 3 Statistical Data Analysis Project 

In this project I will be looking at data on 500 customers of Megaline, a telecom operator. The data provided includes who the clients are, where they're from, which plan they use, the number of calls they made, text messages they sent, and internet data they used in 2018. Megaline has 2 different plans that they offer, Surf and Ultimate. I will be comparing the tendencies of Surf customers to Ultimate customers, as well as comparing the revenue brought in by each plan. This includes comparing amounts of messages sent, calls made, duration of calls, and internet usage. The purpose of this research is to determine which plan brings in more revenue, and report back to the commercial department at Megaline. This information will help them decide where to properly allocate their advertising budget. 

## The Data
The data used was compiled from 5 separate datasets:
**megaline_users.csv:**
- user_id — unique user identifier
- first_name — user's name
- last_name — user's last name
- age — user's age (years)
- reg_date — subscription date (dd, mm, yy)
- churn_date — the date the user stopped using the service (if the value is missing, the calling plan was being used when this database was extracted)
- city — user's city of residence
- plan — calling plan name

**megaline_calls.csv:**
- id — unique call identifier
- call_date — call date
- duration — call duration (in minutes)
- user_id — the identifier of the user making the call

**megaline_messages.csv:**
- id — unique text message identifier
- message_date — text message date
- user_id — the identifier of the user sending the text

**megaline_internet.csv:**
- id — unique session identifier
- mb_used — the volume of data spent during the session (in megabytes)
- session_date — web session date
- user_id — user identifier

**megaline_plans.csv:**
- plan_name — calling plan name
- usd_monthly_fee — monthly charge in US dollars
- minutes_included — monthly minute allowance
- messages_included — monthly text allowance
- mb_per_month_included — data volume allowance (in megabytes)
- usd_per_minute — price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)
- usd_per_message — price per text after exceeding the package limits
- usd_per_gb — price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)

The data is provided by TripleTen

## The Process 
I first explored the various datasets and cleaned it, ensuring that there were no duplicates or missing values, and adding any columns I thought would be helpful to them. I then used data visualization to perform SDA. Lastly I tested statistical hypotheses. 