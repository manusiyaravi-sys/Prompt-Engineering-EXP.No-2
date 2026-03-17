EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

ZERO SHOT PROMPTING
Question: “Explain the concept of cloud computing in simple words.”
CHAT GPT
Cloud computing is a technology that allows people to use computing services like storage, software, and processing power through the internet instead of using their own computer or local servers. Instead of saving files or running programs on your personal device, the data and applications are stored on remote servers that are accessed online. These servers are maintained by cloud service providers.
For example, when you use Google Drive to store files or Gmail to send emails, your data is not stored only on your device but on remote servers connected through the internet. This allows users to access their files and applications from anywhere and from different devices.
Cloud computing is useful because it provides easy access to resources, reduces the need for expensive hardware, and allows users to scale services according to their needs. Businesses and individuals can store large amounts of data, run applications, and collaborate with others using the internet. Therefore, cloud computing makes computing services more flexible, cost-effective, and accessible.
GEMINI 
Think of Cloud Computing as switching from owning a generator to using the power grid. Instead of buying, housing, and maintaining your own heavy computer hardware, you simply plug into the internet to use someone else’s.
In the "old days," if a company wanted to run a website or store files, they had to buy physical servers, keep them in a cool room, and hire experts to fix them when they broke. With the cloud, companies like Google, Amazon, or Microsoft handle all the hardware, and you just rent what you need.
________________________________________
How It Works (The "Three Big Ideas")
•	On-Demand Access: You can get more storage or computing power instantly. It’s like turning on a faucet; you get water immediately without building a well.
•	Pay-as-You-Go: You only pay for the "electricity" you use. If your website gets quiet at night, you pay less.
•	Access Anywhere: Since the data isn't trapped on your specific hard drive, you can access your files from a laptop in New York or a phone in Tokyo, as long as you have a connection.
Common Examples You Already Use
You’re likely using the cloud every day without realizing it:
•	Google Drive/iCloud: Your photos and docs aren't just on your phone; they live on remote servers so you don't lose them if you drop your phone in a lake.
•	Netflix: Instead of owning a DVD (physical hardware), you stream the movie from the cloud.
•	Gmail: Your emails aren't stored on your computer's hard drive; they live on Google's "cloud" servers.
________________________________________
The "Pizza as a Service" Analogy
To understand the different types of cloud computing, imagine you want pizza:
1.	On-Premises (Traditional): You make the dough, toppings, and bake it in your own oven. You own everything.
2.	IaaS (Infrastructure): You rent the kitchen and oven, but you bring your own ingredients and chef.
3.	PaaS (Platform): You order a pizza for delivery. They provide the pizza; you just provide the table and plates.
4.	SaaS (Software): You go to a restaurant. Everything is provided for you; you just sit down and eat.
Co-pilot
Cloud computing is like renting a computer that lives on the internet instead of owning one yourself.
💡 Imagine you need a powerful computer to store files, run apps, or process data. Instead of buying expensive machines, you can use services from companies like Microsoft, Google, or Amazon. They have huge data centers full of computers, and they let you access them through the internet whenever you need.
Key ideas in simple words:
•	Storage: Keep your files online (like Google Drive or OneDrive) instead of on your personal computer.
•	Software: Use apps directly in your browser (like Office 365 or Gmail) without installing them.
•	Power: Run heavy tasks (like analyzing big data or training AI) on remote servers instead of your own device.
•	Pay-as-you-go: You only pay for what you use, just like electricity or water.
So, cloud computing is basically using someone else’s computer over the internet to make your life easier and cheaper.
Few-Shot Prompt
Question: Email Classification
CHAT GPT 
Example 1
Email: Congratulations! You have won a free iPhone. Click here to claim.
Category: Spam
Example 2
Email: Your bank account statement is attached.
Category: Important
Example 3
Email: Limited time offer! Buy now and get 50% discount.
Category: Spam

Email: Your electricity bill payment is due tomorrow.
Category:
Answer: Important
GEMINI
Example 1:Email: Congratulations! You have won a free iPhone. Click here to claim.
Category: Spam
Example 2
Email: Your bank account statement is attached.
Category: Important
Example 3
Email: Limited time offer! Buy now and get 50% discount.
Category: Spam
Email: Your electricity bill payment is due tomorrow.
Category:
This is a time-sensitive notification regarding a personal utility service. Unlike spam, which is unsolicited and sent to mass audiences
Co-pilot 
Example 1
Email: Congratulations! You have won a free iPhone. Click here to claim
Category: Spam
Example 2
Email: Your bank account statement is attached.
Category: Important
Example 3
Email: Limited time offer! Buy now and get 50% discount.
Category: Spam
Email: Your electricity bill payment is due tomorrow.
Category:
This email falls under the Reminder/Payment Due category.
It’s essentially a billing reminder — notifying you that your electricity bill needs to be paid by tomorrow.
Chain-of-Thought Prompt
Question: Ravi has 5 apples. He buys 3 more apples from the shop. Then he gives 2 apples to his friend.
How many apples does Ravi have now?
CHAT GPT 
First, Ravi has 5 apples.
He buys 3 more apples, so 5 + 3 = 8 apples.
Then he gives 2 apples to his friend, so 8 − 2 = 6 apples.
Final Answer: 6 apples
GEMINI
Ravi has 6 apples now.
Here is the breakdown:
1.	Initial amount: 5 apples
2.	Bought: +3 apples (Total = 8)
3.	Gave away: -2 apples (Total = 6)
Co-pilot 
Let’s break it down step by step:
•	Ravi starts with 5 apples.
•	He buys 3 more, so now he has 5+3=8.
•	He gives 2 apples to his friend, so 8-2=6.
✅ Ravi has 6 apples now.
Role-Based Prompt
Question: You are a science teacher.
Explain the concept of photosynthesis in simple words to a school student.
CHAT GPT
Photosynthesis is the process by which green plants make their own food using sunlight, water, and carbon dioxide. The green pigment called chlorophyll in the leaves helps capture sunlight. This energy is used to convert carbon dioxide and water into glucose (food) and oxygen.
GEMINI
Think of photosynthesis as the way plants "cook" their own food. Since plants can't go to the grocery store, they use a bit of natural magic to turn sunlight into energy.
Here is the simple "recipe" plants use:
The Ingredients
To make their food, plants need three main things:
1.	Sunlight: This is the energy or "heat" for the oven.
2.	Water: Collected by the roots from the soil.
3.	Carbon Dioxide ($CO_2$): A gas that plants breathe in from the air (the same gas we breathe out!).
________________________________________
How the Magic Happens
Inside the leaves of a plant are tiny green "factories" called chloroplasts. These contain something called chlorophyll, which is what makes leaves green and helps catch the sunlight.
The plant uses the energy from the sun to mix the water and carbon dioxide together. This chemical reaction creates two things:
•	Sugar (Glucose): This is the plant's food. It helps the plant grow tall and stay healthy.
•	Oxygen: This is a "waste product" for the plant, so it breathes it out into the air.
Why it Matters to Us
Photosynthesis is one of the most important things on Earth! Without it, we wouldn't have:
•	Air to breathe: Plants provide the oxygen that humans and animals need.
•	Food to eat: Almost everything we eat comes from plants, or from animals that ate plants.
Co-pilot
Photosynthesis is how plants make their own food using sunlight.
🌱 Think of a plant like a little chef:
•	It takes sunlight as energy.
•	It uses water from the soil.
•	It breathes in carbon dioxide from the air.
•	Then, inside its leaves, it mixes all these ingredients together.
The result? The plant makes sugar (its food) and releases oxygen into the air — which is what we breathe!
So in simple words: plants eat sunlight and air, drink water, and give us oxygen in return.
~~~
![P2](https://github.com/user-attachments/assets/4df2bbbf-8b6f-43f8-9a9a-bcd1e46e9427)

RESULT:
~~~
The experiment was conducted to evaluate and compare different prompting
techniques such as zero-shot prompting, few-shot prompting,
chain-of-thought prompting, and role-based prompting across various AI
platforms including ChatGPT, Gemini and Copilot for the task of text
summarization.
From the observations, it was found that zero-shot prompting produced quick
summaries but sometimes lacked depth and missed important details from the
original text. Few-shot prompting performed better because the examples
provided in the prompt helped the AI understand the expected format and style
of the summary.
Chain-of-thought prompting generated more structured summaries by
breaking down the information step by step before presenting the final
summary. This improved clarity and logical flow, especially when the input text
was complex.
Role-based prompting also produced good results. When the AI was assigned
roles such as teacher, journalist, or editor, the summaries became more focused
and well-organized according to the perspective of the assigned role.
Among the AI platforms tested, ChatGPT produced more coherent and detailed
summaries, while Gemini and Copilot also performed well but occasionally
generated shorter summaries.
Overall, the results show that few-shot and chain-of-thought prompting
techniques provide more accurate and structured summaries compared to zero-shot prompting, while role-based prompting improves the style and
clarity of the summary. Therefore, choosing the appropriate prompting
technique can significantly improve the quality of AI-generated text
summarization.

