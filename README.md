# Project Proposal

## Project Title
CardWise Automations: Smarter Finance and Rewards Management

## What and why?
**What:**
CardWise is a smart credit card management system that helps users make optimal spending decisions. It reduces the mental burden of deciding “which card to use” and provides smarter recommendations across different scenarios—ultimately saving users more money.
Key functions include:
1. Information overload management — simplifies the complex decision of “which card should I use” into a one-click recommendation, eliminating constant manual comparisons.
2. Behavioral reminders — proactively alerts users when they are about to exceed budgets or approach quarterly limits, preventing missed opportunities and overspending.

**Why:**
Consumers today often hold multiple credit cards (campus cards, no-annual-fee cards, airline co-branded cards, etc.). However, cashback rates and capping rules across merchants and categories are complex and non-transparent. This complexity often causes users to miss out on optimal cashback or reward opportunities at the point of purchase.

A single wrong card choice or overspending decision can result in significant opportunity costs. With smart recommendations and timely reminders, users can avoid waste, maximize the value of each expense, and make money management both easier and more cost-effective.

## For whom?
The problem is especially significant for:

- Students : who have limited budgets and need guidance to stretch every dollar.
- Working professionals : who manage frequent, diverse expenses such as dining, groceries, commuting, and business travel.
- Homemakers (housewives/househusbands) : who often oversee household budgets and daily spending, and benefit from maximizing rewards on routine purchases like groceries, utilities, and family needs.

As an international student managing tuition, rent, and day-to-day expenses in a high-cost city, I often found it difficult to figure out which credit card would give me the best rewards or savings for a specific purchase. If a tool like CardWise had existed back then, it would have helped me make smarter financial choices and reduced a lot of unnecessary stress. I believe many other students in similar situations would benefit from such a system.

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
