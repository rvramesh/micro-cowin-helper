# micro-cowin-helper Specifications

As **an association member**
I want to **enroll myself and my family members for vaccination**
so that **I can get into an organized queue and get notified when my turn for vaccine is available**

As **an association administrator**
I want to **check the interest for different vaccines**
so that **vaccinations can be planned based on demand**

As **an association member**
I want to **confirm my availability once a slot opens up** 
so that **vaccines will not go for waste**

As **an association administrator**
I want to **send notification to the member when slot opens up and look at confirmed schedules**
so that **vaccines will not go for waste**

As **an association administrator**
I want to **mark the interest as vaccinated**
so that **future reporting will exclude the vaccinated people**

As **an association member**
I want to **withdraw my interest **
so that **vaccines can be used for some one else**

As **an association member**
I want to **be prompted to schedule second dose after my first dose with my preferred week gap**
so that **i can sign up for the second dose**

As **the app developer**
I want to **incur no profit as well as no cost and develop it as open source**
so that **the project is sustainable**

# micro-cowin-helper Solution

* Build a telegram bot, which would allow a user to express their interest for vaccines. The user can express their flat number with block, how many vaccines (for 18+), vaccine preference (Covaxin, Covishield, Sputnik, Any vaccine), from which date the will be interested? (second dose).

* Based on the data collected, we can gather the interest and the demand, which will help us negotiate with private / bbmp. 

* Once a vaccine becomes available for the day, eg 100 doses a notification will be sent to first 100 users meeting the criteria (their preferred vaccine, preferred date onwards) in telegram. Once the user accepts the slot the slot gets finalized and the user can walkin for vaccination. If the user rejects the slot, the user becomes eligible for the next turn and the slot will be passed to the next in line.

* At the site of vaccination the user's Soth City ID card has to be validated. As a telegram bot will be opened up for everyone, we need a list of phone numbers which are allowed to interact with the bot. So a data collection exercise might be requied at the block level.

# micro-cowin-helper Benefits

* Avoid queuing up for getting token and revisiting again. Helps in following social distancing and avoid crowding
* Can help understand the demand plan accordingly

# micro-cowin-helper Downsides

* Data collection for apartment phone number to be white listed
* The code to be developed by volunteers in their free time. I can pitch in here. But, more help the merrier
* As this is not a for-profit initiative, the cost to run this should ideally be free or getting a sponsor would help (depending on the design choices and how the plan develops)


# micro-cowin-helper Alternatives

* Nudge Apna complext to develop this function
