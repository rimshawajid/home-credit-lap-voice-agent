1. Normal Successful Qualification
Customer:
Yes, this is me. I'm interested. I have a residential house, and I own it myself. The original documents are available. I need around ₹50 lakh. I'm salaried and my salary comes directly into my bank account. The property is worth around ₹90 lakh, and I'd prefer 10 years.

Expected agent behavior:
- Capture all 7 variables even though they were provided together.
- Do not repeat questions.
- Confirm eligibility.
- Handoff to senior loan expert.
Expected final response:
Thank you. Based on the information you've provided, you've completed the preliminary eligibility check. A senior loan expert will contact you shortly to discuss the next steps and provide the exact interest rate and loan terms.

2. Agricultural Property — Immediate Disqualification
Customer:
Yes, I'm interested. It's agricultural land that I own.

Expected:
Thank you for the information. Based on the property type, this specific offer isn't applicable at this time. I appreciate your time.

Important:
The agent must END immediately. It should not ask about documents, income, tenure, etc.
3. Cash Income — Immediate Disqualification
Agent:
Could you tell me about your occupation and how you receive your income?

Customer:
I run my own business. Most of my income is received in cash.

Expected:
Thank you for clarifying. Based on the income mode, this specific offer isn't applicable at this time. I appreciate your time.

Important:
Self-employed is eligible. Cash income is the disqualifying factor.
4. Existing Loan / EMI Reduction
Customer:
Actually, I already have a loan on this property. I'm mainly looking to reduce my EMI.

Expected:
Thank you for clarifying. Since you already have an existing loan on the property, this would need to be handled by our loan-transfer specialist. A specialist will contact you shortly regarding this. Thank you for your time.

Important:
Do not continue the 7-question qualification.
5. Out-of-Order Information
Agent:
What type of property do you have?

Customer:
It's a residential house. It's jointly owned with my wife, the original documents are at home, and I'd need about ₹40 lakh.

Agent should internally capture:
- Property → Residential
- Ownership → Joint
- Documents → Available
- Loan amount → ₹40 lakh
Then ask:
Thank you, that's helpful. Could you tell me whether you're salaried or self-employed, and whether your income is received through your bank or in cash?

Important:
It must not ask again about property, ownership, documents, or loan amount.
6. Customer Diversion / Interest Rate
Agent:
Approximately what is the current market value of the property?

Customer:
It's around ₹1 crore. But before we continue, what interest rate are you offering?

Expected:
The exact interest rate and final loan terms will be provided by our senior loan expert after the preliminary qualification. For now, I'd like to complete a few basic eligibility questions.

Then continue with the first missing question.
Important:
Never invent an interest rate.
7. Busy Customer / Callback
Agent:
Hello, may I speak with {{customer_name}}?

Customer:
Yes, that's me, but I'm actually in a meeting right now.

Expected:
Of course, I understand. What would be a convenient time for us to call you back?

Customer:
Tomorrow around 11 AM.

Expected:
Certainly. We'll arrange a callback around that time. Thank you, and have a great day.
