# 🛒 E-commerce Support Agent

## 📌 Project Overview  
The **E-commerce Support Agent** is an AI-powered assistant built using **UiPath GenAI Activities**.  
It helps automate **customer queries** in an online retail/e-commerce context such as:  
- Order tracking  
- Refunds and cancellations  
- Shipping and delivery status  
- Product availability  

The agent is powered by a **System Prompt** and **User Prompts** defined in UiPath.  

---

## ⚙️ Workflow Logic  
1. **System Prompt** initializes the agent as a polite, concise, e-commerce support assistant.  
   - Provides rules on what information can be shared (e.g., never personal data, only product/order info).  
   - Defines scope: tracking, returns, cancellations, product availability.  
   - Ensures the assistant responds clearly and professionally.  

2. **User Prompt** accepts customer queries such as:  
   - *“Where is my order #OB1027?”*  
   - *“I want to cancel my order.”*  
   - *“Do you have stock of product #55001?”*  

3. **Agent Response** → The bot uses **GenAI Activities** to generate an appropriate response following the defined rules.  

---

## 🚀 How to Run  
1. Open project in **UiPath Studio**.  
2. Set up **UiPath GenAI Activities connection**.  
3. Configure the **System Prompt** with the provided template.  
4. Trigger the automation and input a customer query.  
5. The AI responds with a **professional and rule-based answer**.  

---

## 📝 Example Queries & Responses  

**Query 1**:  
> Can you tell me the tracking ID for order OB1027?  

**Response**:  
> Your tracking ID for order OB1027 is **TX8923**. You’ll receive a confirmation email shortly.  

---

**Query 2**:  
> I want to cancel my order OB1027.  

**Response**:  
> Your order OB1027 has already been shipped. Cancellation is not possible at this stage. You can initiate a return within **30 days after delivery**.  

---

**Query 3**:  
> Do you have availability of product #55001?  

**Response**:  
> Yes, product #55001 is currently available and can be shipped immediately.
