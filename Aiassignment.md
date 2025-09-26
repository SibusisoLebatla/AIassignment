```mermaid 

Chatbot Flow
AI Chatbot- “MossCo Bot”

Welcome Message:

“Hi Welcome to Moses Coffee at Makers landing. I am MossCo Bot, I am here to assist 
you. How can I assist you you?”

Flow:
1. Greeting and Emotions Check:
- Bot: “How are you today?”

- Customer: “I am good” → Bot: “Glad to hear that! Let’s make your day even better with 
a coffee.”

- Customer: “Not so good” → Bot: “I’m sorry to hear that. A warm cup of coffee might 
cheer you up!”

2. Customer Identification:

- Bot: “Can I please know your name so that I can assist you better?”
- Customer: “ [Customer Name]” → Bot: “Great to meet you, [Customer Name]! What 
would you like help with today?”
3. Options Menu
- Bot: “ Okay [Customer Name], Please choose an option that you would like me to 
assist you with”

1. Opening Hours

2. Make an Order

3. View Menu

4. Speak to Moses

5. Directions

6. Book for an event

4. Branches Paths


If Opening Hours is selected
Bot : “We are located at Makers Landing , V&A waterfront, Cape Town. [Sends an 
embedded Google Maps link or button].”

If Make an order is selected
Bot: “ Alright, Let’s start with getting your order”

Bot will send the menu again. “Please type the name of the item you’d like to order”

Customer specifies.

Bot: “How many items would you like to have?”

Customer specifies the quantity.
Bot: “Would you like to add something else to your order? (Yes/No)”
If Yes, Loop back to item selection. 

If No, the Bot will summarize the full order and provide total. “For what time would you 
like to pick your order?”

Customer provides time
Bot: “Thank you! This is your order [order summary] to be picked at [time]. Please see 
Moses by the counter to pay upon collection”

If View Menu is selected: 
Bot will provide detailed list of available items like coffee (e.g., Cortado, Flat-white, 
Cappuccino) and coffee beans (e.g., Naturally fermented, Fully washed)

If Speak to Moses is selected
Bot: “I’ll let Moses know you’d like to chat! He may be busy with customers, but he will 
get back to you as soon as possible. Could you please briefly describe what you need 
help with?”

Customer provides reasons.

Bot: “ Thank you. I have notified Moses he will get back to you shortly”

If Directions is selected
Bot: “We’re located at Makers Landing, V&A Waterfront, Cape Town. [Sends an 
embedded Google Maps link or button].”



If View Menu is selected
Bot will provide a detailed description of menu of available items.

If Book an Event is selected
Bot: “ Wonderful news! Moses loves catering for events . Can you please help me with 
providing a few details if you’d like to book for an event”

Bot: “What type of event is it? (e.g., Function, Birthday, Conference, Office Meeting)”

Customer responds.
Bot: “ How many guests plus or minus will be attending?”

Customer provides number.

Bot: “ Can you please share your contact number so that Moses can call you?”

Customer provides number.
Bot: “ Thank you! We have received your request for an event on [date] for [number] 
guests. Moses will call you at [number] within 24 hours to confirm availability and 
discuss the menu and pricing.”

Closure 

After any path, the bot concludes with 
Bot: “ Is there anything else can I help you with today? (Yes/No)”

If Yes, returns to the option Menu.
If No, Bot: “ Thank you for chatting with Moses I hope I was able to assist you. Have a 
wonderful day
