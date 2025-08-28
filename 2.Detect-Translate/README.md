# Detect & Translate Text 🌍🔤

## 📌 Project Overview  
The **Detect & Translate Text** project demonstrates how to use **UiPath GenAI Activities** to automatically detect the language of a given input text and then translate it into a target language (English in this case).  

---

## ⚙️ Workflow Steps  
1. **Manual Trigger** → Starts the automation.  
2. **Detect Language Activity**  
   - Input: A text in a foreign language (German in the example).  
   - Output: The detected language (e.g., *German*).  
3. **Log Message** → Displays the detected language.  
4. **Translate Activity**  
   - Input: The original text.  
   - Target Language: **English**.  
   - Output: Translated text.  
5. **Log Message** → Displays the translated text.  

---

## 🚀 How to Run  
1. Open the project in **UiPath Studio**.  
2. Configure the **GenAI Activities connection** with your account.  
3. Enter any non-English input text.  
4. Run the automation → The detected language and translated text will be shown in the console/output panel.  

---

## 🎯 Example Input & Output  

**Input Text (German)**:  
> Erfolg kommt nicht über Nacht – er entsteht täglich durch kleine, konsequente Anstrengungen, die sich zu großen Ergebnissen summieren.  

**Detected Language**:  
> German  

**Translated Text (English)**:  
> Success doesn’t come overnight – it is built daily through small, consistent efforts that compound into big results.
> 
