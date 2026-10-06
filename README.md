# Finprio— Personalized Budget Prioritization

**Team Members:** Kaan, Chinmay, Zender, Elisha
**Category:** FinTech / Personal Finance

## 1. PROBLEM STATEMENT

Most budgeting apps show users where their money went, but do not help them decide where their money should go next. People with limited income often have to balance everyday spending with savings goals, making it difficult to know how much they can spend while still reaching the things they care about.

## 2. SOLUTION

Finpriois a budgeting app that helps users build a budget around their personal priorities and savings goals. Users connect their bank accounts through Plaid, see how much they spend in each category, and choose which categories matter most to them. Users can then create a savings goal and see when they are expected to reach it based on their spending. The app can update the forecast and priorities when the user's spending habits change.

## 3. TARGET MARKET

Finpriois designed for college students and young adults who have regular income and expenses but want help balancing everyday spending with savings goals. The U.S. market includes millions of consumers who actively manage personal finances and face difficulty building adequate savings.

## 4. WHY IT IS VALUABLE

Finpriohelps users understand the tradeoff between spending today and reaching their future goals instead of only showing them their past spending. This gives users a simple way to answer questions such as, "How much can I spend and still reach my vacation goal, or how can I get to my vacation goal sooner?"

## 5. HOW YOU WILL MAKE MONEY

Finpriowill use a freemium subscription model. Basic spending tracking and savings goals will be free, while advanced forecasting, recommendations, and financial planning features will be available through a premium subscription.

## 6. MVP FEATURES

- **Plaid Account Connection**
  - Connect bank accounts through Plaid.
  - Import approximately two months of transaction history.
  - Automatically organize transactions into spending categories.

- **Spending by Category**
  - Show total and average monthly spending by category.
  - Allow users to review and correct categories.
  - Establish an initial picture of the user's spending habits.

- **Personal Priorities**
  - Let users assign importance to spending categories.
  - Store their initial preferences and use them when creating recommendations.
  - Allow users to change their priorities.

- **Savings Goals**
  - Create a goal with a target amount and current savings.
  - Examples include vacations, emergency funds, or large purchases.
  - Track progress toward the goal.

- **Savings Goal Forecasting**
  - Estimate when the user will reach their goal based on current spending and savings.
  - Show how changes in spending affect the expected goal date.
  - Update the forecast when spending patterns change.

- **Dynamic Spending and Priorities**
  - Compare recent spending with the user's previous spending.
  - Identify meaningful changes in spending habits.
  - Allow users to confirm whether a change is temporary or represents a new priority.

## 7. TIMELINE AND DIVISION OF WORK

### Week 1

- **Kaan:** Plaid integration and account connection
- **Elisha:** Transaction categories and spending calculations
- **Chinmay:** Backend and database setup
- **Zender:** Onboarding and account connection UI

### Week 2

- **Kaan:** Transaction retrieval and data processing
- **Elisha:** Category assignment and spending summaries
- **Chinmay:** Spending and transaction APIs
- **Zender:** Spending dashboard and category UI

### Week 3

- **Kaan:** Plaid testing and financial-data validation
- **Elisha:** Savings-goal forecasting and priority logic
- **Chinmay:** Savings-goal and forecasting APIs
- **Zender:** Savings-goal creation and forecast UI

### Week 4

- **Kaan:** User testing and Plaid integration fixes
- **Elisha:** Dynamic spending changes and priority updates
- **Chinmay:** Full system integration and backend testing
- **Zender:** Final UI improvements, recommendation screen, and presentation demo

## 8. TEAM ROLES AND RESPONSIBILITIES

### Kaan — Financial Data & Plaid Integration

- Build and test the Plaid account and transaction connection.
- Process and validate financial transaction data.
- **Estimated share of the codebase: 25%**

### Elisha — Budgeting & Forecasting

- Build category spending calculations and savings forecasts.
- Build priority weights and dynamic spending logic.
- **Estimated share of the codebase: 30%**

### Chinmay— Backend Engineering

- Build database models and backend APIs.
- Connect Plaid, spending, priorities, goals, and forecasting features.
- **Estimated share of the codebase: 25%**

### Zender — Frontend & User Experience

- Build onboarding, spending, priorities, goals, and forecast screens.
- Make recommendations and financial information easy to understand.
- **Estimated share of the codebase: 20%**

## 9. VIABILITY: HOW WE WILL PROVE THIS WORKS

### User Testing Plan 

- Test the MVP by connecting our personal checking accounts during the four-week development period. 
- Test the full flow: connect accounts, review spending, set priorities, create a savings goal, and view their forecast.
-  Check if the recommendations are understandable and useful.
- Collect feedback on which features they would use regularly.

### Competitive Analysis

Existing budgeting apps such as Monarch Money, YNAB, Rocket Money, and Copilot provide features such as account aggregation, transaction categorization, budgeting, goals, and spending analysis.

Finpriois different because its MVP connects **spending habits, personal priorities, and savings goals**. Instead of only showing users how they spent their money, Finpriohelps them understand how their spending affects when they can reach something they care about.

### Market Research

The Federal Reserve reported that **37% of U.S. adults could not cover a hypothetical $400 emergency expense using cash or its equivalent**, showing the difficulty many households have maintaining financial flexibility. The Federal Reserve also reported that **58% of adults said changes in prices had made their financial situation worse**.

Bankrate's 2025 research found that only **46% of Americans had enough emergency savings to cover three months of expenses**, demonstrating continued difficulty building adequate savings.

### Success Metrics

- **10+ users** complete the MVP.
- **70%+** of users understand their spending breakdown.
- **70%+** of users understand their savings goal forecast.
- **60%+** of users say Finpriois more useful for planning than simply viewing their spending history.
- Users successfully create a savings goal and receive a forecast.
- The forecast successfully updates when spending assumptions change.

## 10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS

### Phase 1 — This Semester

**Target: 10–50 users**

Build the MVP with:

- Plaid account connection
- Transaction categorization
- Spending by category
- Personal priorities
- Savings goals
- Basic forecasting
- Dynamic spending updates

The goal is to validate whether users value a budgeting experience based on their priorities and future goals.

### Phase 2 — 6 Months Out

**Target: 5,000 users**

Add:

- Multiple savings goals
- Improved price forecasting
- Recurring income and expense detection
- Better transaction categorization
- More personalized budget recommendations
- Automatic priority updates
- AI explanations for recommendations

### Phase 3 — 12 Months Out

**Target: 100,000 users**

Add:

- Advanced financial forecasting
- Household budgeting
- Debt payoff planning
- Investment and savings planning
- More personalized financial recommendations
- Automated financial planning

### Technical Progression

The MVP will use Plaid, a backend API, a relational database, and a forecasting service. As the user base grows, the application can add background processing, caching, scalable cloud infrastructure, stronger transaction-processing pipelines, and more advanced forecasting models.

### Revenue Model

**Phase 1:** Free MVP to maximize user testing and adoption.

**Phase 2:** Freemium model with premium forecasting and personalized recommendations.

**Phase 3:** Premium subscriptions with advanced financial planning, household features, and personalized financial tools.

## 11. SOURCES AND REFERENCES

- **Federal Reserve Board — Economic Well-Being of U.S. Households**
  - https://www.federalreserve.gov/publications/2025-report-economic-well-being-us-households-in-2024-savings-and-investments.htm

- **Bankrate — 2025 Emergency Savings Report**
  - https://www.bankrate.com/banking/savings/emergency-savings-report/

- **Plaid — Transactions API**
  - https://plaid.com/products/transactions/

- **Monarch Money — Personal Finance and Budgeting Features**

- **YNAB — Budgeting and Personal Finance Features**

- **Rocket Money — Budgeting and Financial Management Features**

- **Copilot Money — Personal Finance Features**



