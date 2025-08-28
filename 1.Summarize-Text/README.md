# Summarize Text 📄✨

## 📌 Project Overview  
The **Summarize Text** project is a UiPath automation that leverages **UiPath GenAI Activities** to automatically generate a concise summary from a given input text.  
This project demonstrates how UiPath can integrate with AI services to transform lengthy passages into short, meaningful summaries.

---

## ⚙️ Workflow Steps  
1. **Manual Trigger** → Starts the automation.  
2. **Log Message** → Displays: *"Automation Started and Reading the Input"*.  
3. **Summarize Text Activity**  
   - Uses UiPath **GenAI Activities connection**.  
   - Input: A block of text (e.g., an explanation of Artificial Intelligence).  
   - Parameters:  
     - Number of summary words (optional).  
     - Format: **Paragraph**.  
   - Output: Concise summary of the input text.  
4. **Log Message** → Prints the generated summary.  

---

## 🚀 How to Run  
1. Open the project in **UiPath Studio**.  
2. Configure the **GenAI Activities connection** with your account.  
3. Replace the sample input text with your own text.  
4. Run the automation → The output summary will be logged in the console/output panel.  

---

## 🎯 Example Input & Output  
**Input Text**:  
> Artificial intelligence is a field of science concerned with building computers and machines that can reason, learn, and act in such a way that would normally require human intelligence or that involves data whose scale exceeds what humans can analyze.  

**Generated Summary**:  
> AI is the science of creating machines capable of human-like reasoning, learning, and handling large-scale data.  
