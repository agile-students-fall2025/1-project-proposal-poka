# Project Proposal

## Project Title
CardWise Automations: Smarter Finance and Rewards Management

## What and why?
**What:**
CardWise is a smart credit card management system designed to help users maximize rewards and control spending. From an end-user’s perspective, CardWise Automations will work as follows:
1. Sign in & import — Users can log in, upload a CSV statement (e.g., from Chase or BoA), or manually record purchases.
2. Automatic categorization & dashboard — Transactions are categorized (dining, groceries, travel, etc.) and displayed in a clear dashboard with top merchants, spending summaries, and estimated rewards.
3. Card recommendation — Before paying, users can tap “Which card should I use?” to see the recommended card, expected rewards, and a brief explanation.
4. Create automations — Users can set up custom rules:
- Trigger: budget threshold (e.g., groceries > $300) or schedule (e.g., weekly).
- Action: email/Discord reminder, pinned notification, or auto-generated report.
- Once saved, CardWise automatically delivers reminders or reports.
5. Reports & reflection — Each month, users receive a “Spending & Rewards Report Card” summarizing top categories, best/worst card usage, and suggestions for optimization.

**Why:**



## For whom?


## How?
From an end-user's perspective, CardWise Automations will work like this:
1. **Sign in & import**: Log in, upload a CSV statement (e.g., from Chase/BoA) or manually record a purchase.  
2. **Automatic categorization & dashboard**: Instantly view a summary dashboard with category breakdowns (dining, groceries, travel), top merchants, and estimated rewards.  
3. **Card recommendation**: Before paying at a store, tap “Which card should I use?” → instantly see the recommended card, expected rewards, and a short reason.  
4. **Create automations**:  
   - Select a trigger (budget threshold or scheduled time).  
   - Select an action (email/Discord reminder, pinned notification, auto-generate report).  
   - Save → the system now automatically reminds or generates reports.  
5. **Reports & reflection**: Receive a monthly “Spending & Rewards Report Card” showing top categories, best/worst card usage, and suggestions for next month.  

**Minimum viable features (MVP):**  
- User accounts (sign in/out).  
- Transaction import (CSV + manual).  
- Spending categorization (rule-based).  
- Rewards calculation (static table of card multipliers).  
- Real-time “best card” recommendation.  
- Automation rules:  
  - **Trigger**: threshold (e.g., category > $300) or schedule (e.g., weekly).  
  - **Action**: email or Discord notification.  
- Dashboard with charts and a monthly report.  

**Stretch goals:** OCR receipt scanning, sharing reports with roommates, or advanced automation actions.

## Scope
This project is well-scoped for **a team of 4–6 programmers over one semester**:  

- **Not too easy:** goes beyond simple expense tracking by adding automation triggers, reward logic, and proactive notifications.
- **Not too ambitious:** does not require machine learning or third-party banking integrations—rules and multipliers are pre-configured, and automations are limited to simple threshold/schedule triggers.
- **Web app only:** we are building a responsive web application (MERN). It will be accessible from both desktop and mobile browsers. No native iOS/Android apps are required.  

**Team division of work (clear roles):**
- **Frontend**: responsive web UI and charts (usable on desktop and mobile browsers).  
- **Backend**: API design, rules engine, authentication.  
- **Data & async tasks**: transaction import/parsing, monthly report generation, scheduled triggers.  
- **Integration & testing**: seed data, usability testing with real students, system integration.

## Credit
- [Polaris Wu](https://github.com/Polaris-Wu450)
- [Kate Zhou](https://github.com/XiaohanZhou711)
