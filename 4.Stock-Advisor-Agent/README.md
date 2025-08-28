# 📈 Stock Recommendation Agent

## 📌 Project Overview  
The **Stock Recommendation Agent** is an AI-powered assistant that analyzes **stock-related information** from web search results and provides a recommendation on whether to **Buy, Hold, or Don’t Buy**.  

It uses **UiPath GenAI Activities** with a **System Prompt** and **User Prompt** designed to enforce financial analysis best practices.  

---

## ⚙️ Workflow Logic  

### 🔹 System Prompt  
- Defines the assistant as a **specialist in stock recommendations**.  
- Provides structured guidelines:  
  1. Analyze both positive and negative factors.  
  2. Focus on **financial indicators, recent news, expert opinions**.  
  3. Provide clear recommendation: **Buy / Hold / Don’t Buy**.  
  4. Justify recommendation with key factors.  
  5. If insufficient data → state so and suggest what’s missing.  
- Ensures objectivity, **no financial guarantees**, only insights based on public info.  

### 🔹 User Prompt  
Users provide:  
- **Stock Symbol**  
- **Additional Context** (optional)  

The agent then:  
1. Performs a **web search** for latest stock-related data.  
2. Analyzes findings (financials, market sentiment, expert views).  
3. Outputs a **structured recommendation**:  
Recommendation: [Buy/Hold/Don’t Buy]
Justification: [Concise explanation]
Key Factors:
[Factor 1]
[Factor 2]
[Factor 3]
Additional Notes: [Any extra caveats or missing info]

---

## 🛠️ Tools Used  
- **Web Search Tool** → fetches publicly available data (news, financial indicators, expert analysis).  

---

## 🚀 How to Run  
1. Open in **UiPath Studio**.  
2. Configure **System Prompt** and **User Prompt** with given templates.  
3. Add **Web Search Tool** to enable live stock data lookup.  
4. Run automation and provide inputs like:  
- `Stock Symbol: TSLA`  
- `Additional Context: Recent Q2 earnings release`  

---

## 📝 Example Queries & Responses  

**Query 1:**  
> Analyze Tesla (TSLA) stock after Q2 earnings.  

**Response (Sample):**  
Recommendation: Hold
Justification: Tesla reported strong revenue growth, but margins are shrinking due to increased competition.

Key Factors:

Revenue up 15% YoY
Declining gross margins due to pricing cuts
Positive outlook in energy storage business
