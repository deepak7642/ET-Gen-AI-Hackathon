# ***ET-Gen-AI-Hackathon***
---

<img width="1279" height="371" alt="image" src="https://github.com/user-attachments/assets/09b65e96-5b78-4e74-9eb8-fe025b12f1d2" />

-----
### **Problem Statement :- 9 (AI Money Mentor)**

*95% of Indians don't have a financial plan. **Financial advisors charge ₹25,000+ per year** and serve only High Net-worth Individuals (HNIs). Build an AI-powered **personal finance mentor** that lives inside ET, turns confused savers into confident investors, and makes financial planning as accessible as **checking WhatsApp**.*


* **WHAT YOU MAY BUILD**


  • Financial Independence, Retire Early (FIRE) Path Planner — User inputs age, income, expenses, existing investments, and life goals. AI builds a complete, month-by-month financial roadmap: Systematic Investment Plan (SIP) amounts per goal, asset allocation shifts, insurance gaps, tax-saving moves, and emergency fund targets.


#### **Prototype built-up by :- AI Devilops**
*Team Lead and member - Deepak Kaura*


### **How the Input and Output works (Step-wise Flow)**

*1. User provides financial inputs such as age, income, expenses, investments, and goals.*

*2. System calculates key metrics:*

   *- Savings rate*
   
   *- Target FIRE corpus (25× annual expenses)*
   
   *- Investment shortfall*
   
*3. A FIRE score is computed based on savings rate, returns, inflation, and shortfall.*

*4. The score is mapped to a category: Critical, Weak, Moderate, Strong, or Optimized.*

*5. Based on the category, a predefined prompt template is selected.*

*6. User financial data is formatted into structured inputs.*

*7. The prompt is passed to the LLM (Gemma 2B via txtai).*

*8. LLM generates:*

  *- Personalized financial advice*
   
  *- Strategic roadmap*
   
  *- Risk assessment*
   
*9. System also calculates:*

   *- Goal-based SIP recommendations*
   
   *- Suggested asset allocation (Equity vs Debt)*
   
*10. Final output is displayed to the user.*


#### **Prerequisite (libraries) to install before run the core AI prototype :-**

- LangChain (Prompt orchestration)
  
- txtai (LLM inference engine) 


### **Limitations**

- Assumes constant income, expenses, and savings behavior
  
- Uses fixed return and inflation assumptions
  
- LLM responses may vary slightly due to generative nature
  
- Simplified retirement model (does not include dynamic withdrawal strategies)
  
  
#### **Future Improvements -**

- Implement time-series based simulations to evaluate FIRE probability under different market conditions, including visual insights and trend analysis.
  
- Enhance prompt engineering and upgrade to more advanced LLM/GenAI models for improved accuracy, personalization, and financial reasoning.
  
- Develop personalized investment optimization strategies based on user risk profile, goals, and market assumptions.
  
- Integration with real-time financial and market data APIs for dynamic and up-to-date analysis.
  
- Development of an interactive user interface (e.g., web dashboard) for better user experience and visualization.
  
- Scenario-based planning (e.g., job loss, salary growth, inflation spikes) to test financial resilience.
  
- Automated portfolio tracking and rebalancing recommendations.
  
- Multi-user profile support with comparative financial insights.
  
- Explainable AI (XAI) layer to justify recommendations and improve user trust.
  
- Mobile-friendly or app-based deployment for wider accessibility. (like ET’s Whatsapp feature)
