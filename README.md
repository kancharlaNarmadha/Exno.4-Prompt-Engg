# EXP 3: Scenario-Based Report on AI-Powered Chatbot using Prompting Techniques

# Register Number: 212222110016




# Aim
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries using various prompting techniques such as:

1 .Straightforward Prompts

2. Tabular Format Prompting

3. Preceding Question Prompting

## Scenario Description
A retail company wants to deploy an AI chatbot to automate customer support tasks such as:

- Product troubleshooting (e.g., device not working)

- Order tracking (e.g., delivery status)

- General inquiries (e.g., store hours, return policies)

The chatbot must provide accurate, friendly, and helpful responses while adapting to different types of user queries using multiple prompting techniques.

# 1. Straightforward Prompting
## Objective: Simple, direct questions to get concise responses.

| **User Input**                         | **AI Response**                                                                 |
|---------------------------------------|---------------------------------------------------------------------------------|
| My headphones are not turning on.     | Please ensure they are fully charged. Try holding the power button for 5 secs. |
| Where is my order?                    | Can you please provide your order ID?                                          |
| What is your return policy?           | You can return items within 30 days of purchase with the original receipt.     |

## Observation:
Straightforward prompts are effective for clear and simple queries but may need follow-up for context.



# 2. Tabular Format Prompting
## Objective: Structured data input to get organized, precise outputs.
### Prompt:
"Given the following issue details, suggest a solution."


| **Issue**         | **Product** | **Symptoms**             | **Attempted Fix**       |
|------------------|-------------|---------------------------|--------------------------|
| Not charging     | Smartwatch  | No lights, dead screen    | Used original charger    |
| Sound distorted  | Speaker     | Static noise when playing | Restarted the speaker    |

### AI Response:


| **Product**  | **Likely Cause**             | **Suggested Action**                            |
|--------------|------------------------------|--------------------------------------------------|
| Smartwatch   | Battery or charging port issue| Try a different cable. Visit service center.     |
| Speaker      | Driver damage or interference | Move away from other electronics. Reset device.  |

## Observation:
Tabular format allows efficient issue tracking and quick identification of patterns and fixes.

# 3. Preceding Question Prompting
## Objective: Using prior context to guide the chatbot’s response.
### Conversation:

User: My laptop isn't booting.
AI: Is it showing any lights or making any sounds?
User: No lights or sounds.
AI: Please check if the power adapter is plugged in and try a different outlet.

User: I placed an order last week but haven't received it.
AI: Could you please provide the order number so I can check the status?
User: It's #45321.
AI: Thank you. Your order was shipped on April 25 and is expected to arrive by May 2.

## Observation:
Preceding question prompting improves the flow of conversation and tailors responses based on context.

# Conclusion
By applying diverse prompting techniques, the chatbot effectively handles customer queries in a human-like manner. Each technique contributes uniquely:

- Straightforward prompting simplifies direct queries.

- Tabular format enhances structured issue resolution.

- Preceding questions ensure contextual and adaptive responses.

# Result

This experiment demonstrates how prompting methods influence the quality and efficiency of AI chatbot communication.

