# Large-Intent-Classification-Dataset
A dataset with about 111,131 elements, includes Out-Of-Scope examples as well.

## How was this created?
I used [oos-eval](https://github.com/clinc/oos-eval) dataset and paraphrased every sentence using [Parrot](https://pythonrepo.com/repo/PrithivirajDamodaran-Parrot-python-natural-language-processing)

## Is this clean?
Unfortunately, no. We can't guarantee that every sentence matches up with its appropriate intent since we automated everything. Aside from that, some sentences have some punctuations while some don't. Also, you should note that since some sentences are the same as previous sentences but phrased in a different manner, this may cause some issues for you.


## List of Intents:
|Tag|Example|
|----|-----|
|cook_time|how long do i need to cook pot au feu for|
|distance|whats the travel time to redmond right now|
|pto_used|how many days off have i used|
|freeze_account|may you stop a paymet on my account|
|schedule_maintenance|i'd like an appointment at your earliest availability for an oil change|
|pto_request|please request pto for march 2 and 3|
|payday|when's the next time i get paid|
|what_song|whats this song|
|todo_list|repeat my to do list|
|maybe|i do not have that information|
|lost_luggage|who do i contact for lost luggage|
|tell_joke|what's the funniest thing you've got|
|vaccines|is it necessary to get a shot for travel to india|
|flip_coin|flip a normal coin|
|alarm|i'd like alarms set for 11am and 132pm|
|calculator|help me solve this math equation|
|shopping_list_update|i'm not sure if watermelon is on my shopping list, but if it isn't can you put it on there|
|next_song|i want you to skip past this song to the next track|
|order_status|was my order delivered|
|pto_request_status|will i be permitted to take my vacation|
|oil_change_when|when is it time to change your oil|
|uber|i need you to schedule an uber pickup for me and three other people at 7pm to go to abe's pizza|
|change_speed|can you speak more slowly|
|improve_credit_score|what are some ways to raise my credit score|
|next_holiday|what day is the next holiday|
|repeat|i want to hear that again|
|apr|is the apr on my card that ends 1234 what it should be based on my credit score|
|credit_limit|what is the limit on my victoria's secret card|
|change_ai_name|can i start calling you dave|
|flight_status|when is my flight going to board|
|oos|set a warning for when my bank account starts running low|
|travel_suggestion|what's the best place to visit in arizona|
|weather|what's is the current weather forecast|
|pay_bill|can you assist with my utility bill payment|
|calendar|what is tuesday's calendar like|
|accept_reservations|does spago in beverly hills allow customers to make reservations|
|pto_balance|how many vacation days have i saved up|
|meal_suggestion|can you give me a chinese meal suggestion|
|routing|what would the routing number for chase be|
|calendar_update|you can remove the field trip from my calendar for march 12, 2019|
|order_checks|i need more checks because i am out|
|ingredients_list|i need a list of ingredients required to make lamb stew|
|insurance|what is covered under my insurance|
|ingredient_substitution|would it be a problem to sub chips instead of fries|
|cancel|quit talking|
|directions|where is the closest subway entrance to me to go to brooklyn|
|international_fees|does my visa have international transaction fees|
|credit_limit_change|how do i change my credit limit|
|last_maintenance|on what day, month and year did i get new tires|
|change_user_name|will you start calling me chaz|
|direct_deposit|how do i set up direct deposit for my first national account|
|text|send a text to joe|
|reminder_update|remind me to call my mom|
|goodbye|see ya!|
|new_card|who has the best credit card offering for a college student|
|pin_change|i forgot my pin number for my credit union bank account, can you help|
|taxes|how much money a year do i spend in taxes|
|meeting_schedule|what if any meetings do i have today|
|sync_device|sync phone|
|application_status|what is the present status of my credit card application|
|reminder|please read my reminder list|
|gas_type|what is the best type of gas for this car|
|report_fraud|contact the bank about fraud activity on my card|
|international_visa|if i plan on travelling to this country, do i need a visa|
|how_old_are_you|what is your age again|
|confirm_reservation|please double check my reservations for six at mani|
|smart_home|could you tell me the temperature of the ac|
|rollover_401k|will my 401k rollover|
|income|what's my income before taxes|
|card_declined|is there a reason my card was declined|
|nutrition_info|how healthy is shepard's pie|
|traffic|is there much traffic between here and work right now|
|what_are_your_hobbies|do you have hobbies|
|tire_change|tell me when to next change my tires|
|credit_score|please lookup my experion credit score|
|current_location|talk to me about where im at right now|
|how_busy|how much to wait before dining in the jack in the box at 4 pm|
|measurement_conversion|what is the total number of pints in two quarts|
|cancel_reservation|i would like to cancel my reservation for nenuco's restaurant to x- tapas|
|do_you_have_pets|what type of pet is in your home|
|are_you_a_bot|are you secretly real|
|timer|create a new timer|
|transfer|transfer ten dollars from my wells fargo account to my bank of america account|
|w2|i need a w2 form, how do i get one|
|todo_list_update|can you cancel my todo list please|
|no|ill pass|
|user_name|do you know who i am|
|min_payment|what is the minimum amount due on my cable bill|
|restaurant_reservation|please reserve a table for 2 at lucky's under the name melissa at 7 pm|
|change_accent|will you please do the male british accent|
|update_playlist|add this song to travel|
|insurance_change|explain how do i get new insurance|
|mpg|how well is the gas mileage while i'm in the city|
|bill_balance|how much is my kill bill bill for|
|transactions|show all purchases of video games|
|make_call|call alex|
|interest_rate|what kind of interest can i expect with my chase account|
|expiration_date|what is the date that my visa card expires|
|bill_due|when do i need to pay my dte energy bill|
|recipe|i would like to learn to make cookies|
|definition|may i please have a definition for the work churlish|
|jump_start|how can i jump start my car if my battery is dead|
|reset_settings|factory settings restoration|
|whisper_mode|set up whisper mode|
|timezone|what is the timezone of saigon|
|date|give me the date|
|where_are_you_from|what place were you born at|
|who_do_you_work_for|do you work for another person|
|share_location|give my location to stan|
|meaning_of_life|i want to know what the purpose of life is|
|restaurant_reviews|does mcdonald's have good reviews|
|account_blocked|my account looks to be blocked and i have no idea why|
|what_is_your_name|what may i call you|
|restaurant_suggestion|where do you want to eat tonight|
|travel_notification|i'm going to be in canada from october 23rd to november 2nd, so can i let my bank know|
|car_rental|i need a car rental this week|
|rewards_balance|whats the reward balance for my visa|
|tire_pressure|i need you to check the air levels in my tires and let me know if i have enough in them|
|food_last|is my milk safe to drink after being in the refrigerator for a week|
|what_can_i_ask_you|what categories of questions can you answer|
|thank_you|that you so much for the help|
|damaged_card|my card was damaged by bleach|
|translate|in spanish, meet me tomorrow is said how|
|find_phone|please help me in finding my phone|
|time|what time is it in france|
|balance|do i have more than $100 in my pnc account|
|yes|that's definitely true|
|replacement_card_duration|what's the time of arrival on my new credit card|
|roll_dice|i would like you to roll a dice|
|change_language|i need new language|
|exchange_rate|how much is 100 dollars in euros|
|who_made_you|who is your designer|
|redeem_rewards|cash in my credit card rewards|
|fun_fact|tell me something interesting about lake tahoe|
|order|order more bread please|
|oil_change_how|procedure to change oil in car|
|gas|what is the gas level in my gas tank|
|spending_history|could you tell me what kind of money i've recently spent|
|carry_on|can i take more than one carry on|
|calories|what is the calorie content of lays chips|
|play_music|let me hear the song sympathy for the devil|
|shopping_list|will you please read the things on my shopping list|
|book_hotel|by chance would it be possible to reserve me a hotel in afghanistan at the zoo for the 10th to the 15th|
|travel_alert|is traveling to france safe|
|greeting|how ya doin|
|spelling|spell: dessert|
|change_volume|make your volume quieter please|
|report_lost_card|i want to report a stolen card|
|book_flight|can you find me a round trip flight from denver international to new york international on the 3rd through the 7th|
|schedule_meeting|how do i set up a meeting|
|plug_type|what kind of sockets do the us use|
