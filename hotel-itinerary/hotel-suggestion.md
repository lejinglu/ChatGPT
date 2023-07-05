# Hotel Itinerary with ChatGPT
I am using web version of ChatGPT

## 1st Attempt with pdf
[Click Here to See 1st Attempt ChatGPT Conversation](https://chat.openai.com/share/8c4c59a1-b4c7-41ea-8ccd-c96822fcab4c)

[Pdf Used:travel calender](/assets/pdf/travel calender.pdf)


Step 1: Create Google calender with your travel schedule, click right top corner three dots drop down button and click print 
  ![three dots](/assets/images/three-dots.JPG), save as pdf. 

Step 2: Find an ChatGPT file uploader extension, [The one I used](https://chrome.google.com/webstore/detail/chatgpt-file-uploader-ext/becfinhbfclcgokjlobojlnldbfillpf). This will add a green upload button when you open ChatGPT. 


Step 3: On [ChatGPT](https://chat.openai.com) Upload the pdf from step 1 by clicking the green upload button 

Step 4: My Input to Ask ChatGPT:
<ol>
  <li>Can you look up reviews of hotels around this area?</li>
  <li>Could you give me a rating from 1-5 and explain why? </li>
  <li>Can  you put together a hotel booking for this trip, I wish the hotel to be closer to where I travel that day</li>
  <li>yes, I have written the location for each day already on the plan, can you just tell me which city I am going each day</li>
  <li>Yes and could you put together an itinerary of hotel bookings for this schedule in the city mentioned</li>
  <li>Please choose it for me the hotel in that location that has the best review, and closest to the last place I visited</li>
  <li>Great, Can you put together a complete itinerary of hotels bookings for this trip, linking to the website of each hotel</li>
</ol>

[Attempt 1 Result itinerary](Attempt1-result.txt)

## 2nd Attemp with text
[Click Here to See 2nd Attempt ChatGPT Conversation](https://chat.openai.com/share/fe5c9f89-e22c-44ee-8e2e-b85ac7a661b8)

Step 1: Summerize date and location of travel to ChatGPT and ask ChatGPT to.
Here is my Text Prompt: 
<ol>
  <li>Hi, I am going on a trip, here is my plan: 7/2 from LAX to Bellevue, WA. 7/3 Seattle Space Needle, Pike Place Market, and Gum Wall. 7/4 Visit Friends in Bellevue, 7/5 visit University of Washington. I am leaving to travel elsewhere on 7/6, can you search up hotels nearby for each day of my travel and put together an itinerary for my hotels and travel plan？</li>
 <li>Could you list the suggested hotel for each day? Why you would suggest them, also give me a review from 1-5 and the reason. </li>
 <li>I prefer hotels that is closest to the last place I visit that day, could you list which hotel I will be staying in each day.</li>
 <li>Awesome, could you schedule my tour suggesting which time slot I should visit each place, and if you have any recommended tourist attraction, please also put that in the schedule</li>
 <li>That looks good, could you add day 1 and day 3 in the schedule as well? Also include the hotels I will be staying in each day</li>
 <li>Which City should I go next? I am thinking about: Portland Oregon, Las Vegas, Idaho, Rainer Mountain. Could you suggest a pattern for my visit</li>
 <li>Can you give me the same schedule itinerary with your suggested tourist attraction and hotel bookings?</li>
 <li>I prefer the hotel with cheaper price</li>
 <li>Could you update my schedule</li>
 <li>Could you also link the hotel's official website and wiki for each spot</li>
 <li>Yes, but do that in the itinerary format</li>
</ol>

[Attempt 2 Result Itinerary](Attempt2-result.txt)

## Findings
<ol>
  <li>ChatGPT may not get everything correct, user must remind ChatGPT for misunderstanding and miscommunication</li>
  <li>Input format is important, I find that text > pdf > image, with text being the most accurate reading, and image get misinterpreted the most. Since ChatGPT is a LLM, clarity of language is preferred.</li>
  <li>Could breakdown tasks to ask ChatGPT, and ask ChatGPT to join answers together to make complete answer. </li>
  <li>Give feedback on ChatGPT's response, yes or no, what is missing, and give personal preference for ChatGPT to choose.</li>
  <li>ChatGPT will give smaller answer based on the latest user prompt, user need to indicate format the completeness of response.</li>
  <li>Very Expensive to do on the API</li>
</ol>



