# Google-Data-Analytic-Capstone-Project
##Case Study: How Does a Bike-Share Navigate Speedy Success?¶
Introduction
	Welcome to the Cyclistic bike-share analysis case study! In this case study, you will perform many real-world tasks of a junior data analyst. You will work for a 		fictional company, Cyclistic, and meet different characters and team members. In order to answer the key business questions, you will follow the steps of the data 		analysis process: ask, prepare, process, analyze, share, and act. Along the way, the Case Study Roadmap tables — including guiding questions and key tasks — will help 		you stay on the right path. By the end of this lesson, you will have a portfolio-ready case study. Download the packet and reference the details of this case study 		anytime. Then, when you begin your job hunt, your case study will be a tangible way to demonstrate your knowledge and skills to potential employers.

Scenario
	You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s 	  	future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes 	differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must 		approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations. Characters and teams

	● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand 		tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt 	for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each 	day.

	● Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. 		These may include email, social media, and other channels. 

	● Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing 		strategy. You joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, 		can help Cyclistic achieve them. 

	● Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

About the company
	In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a 		network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s 		marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility 	  of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual 		riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than 		casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to 		future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into 		members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs. Moreno has set a clear goal: Design 	 marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how 		annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are 		interested in analyzing the Cyclistic historical bike trip data to identify trends

Three questions will guide the future marketing program:
	How do annual members and casual riders use Cyclistic bikes differently?
	Why would casual riders buy Cyclistic annual memberships?
	How can Cyclistic use digital media to influence casual riders to become members?
	Moreno has assigned you the first question to answer:
	How do annual members and casual riders use Cyclistic bikes differently? You will produce a report with the following deliverables:

	A clear statement of the business task
	A description of all data sources used
	Documentation of any cleaning or manipulation of data

A summary of your analysis
	Supporting visualizations and key findings
	Your top three recommendations based on your analysis

##1. Ask
Guiding questions

	● What is the problem you are trying to solve?
	To design a new marketing strategy to convert casual riders into annual members.

	● How can your insights drive business decisions? 
	The insights will help the marketing team to increase annual members.

Key tasks

	Identify the business task
	Consider key stakeholders
	Deliverable A clear statement of the business task

##2. Prepare
	Guiding questions
	● Where is your data located? 
  	   Kaggle and github

	● How is the data organized? 
   	The data is in the form of csv file .

	● Are there issues with bias or credibility in this data? Does your data ROCCC? 
	No issue with bias or credibility as the population of the dataset has it's own clients as bike riders. Yes the data is ROCCC which stands for reliable, original, 	         comprehensive, current and cited.

	● How are you addressing licensing, privacy, security, and accessibility? 
	The data has been made available by company(Motivate International Inc.) under its own license. There is no personal data about the riders as per privacy concern.

	● How did you verify the data’s integrity? 
	The data is consistent and complete with each column having correct data type.

	● How does it help you answer your question?
	It has key insights about the riders like their riding style, membership.

	● Are there any problems with the data?
	It would be good to have some updated information about the bike stations. Also more information about the riders could be useful.*

Key tasks

	Download data and store it appropriately.
	Identify how it’s organized.
	Sort and filter the data.
	Determine the credibility of the data.
	Deliverable A description of all data sources used

	The main data source is 12 months (Between oct 2020 and sep 2021) of riding data provided by the Cicylistic company.

##3. Process
Guiding questions
● What tools are you choosing and why?
	R programming because the size of the data is vast
● Have you ensured your data’s integrity?
	By formatting the data to be consistent
● What steps have you taken to ensure that your data is clean?
	With correct format datatype, removing dirty data, separating the date and time.

Key tasks
Check the data for errors.
Choose your tools.
Transform the data so you can work with it effectively.
Document the cleaning process.
Deliverable Documentation of any cleaning or manipulation of data



  **Member are 1.2 times the casual(non-member) 
        It shows weekend has more rider than the weekday (approx:1.4times). Saturday=1.4Monday 
        Bike type used by user Classic bike are 4 times the docked bike and 1.6 times the electric bike 
        Month Month of July has maximum number of rider (96834), and February has minimum number (96864)   

   **1. Based on the casual rider’s monthly total trips durations, the best odds to launch the new marketing campaign is between March to April.
       Also, consider different price strategies like seasonal passes to increase the conversion rate.
   **2. Use Digital Media to provide "weekend discount" for member, this way it will promote non-member to take membership.
