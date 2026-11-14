# Finprio— Personalized Budget Prioritization

**Team Members:** Kaan, Chinmay, Zender, Elisha
**Category:** FinTech / Personal Finance

## 1. PROBLEM STATEMENT

Most budgeting apps show users where their money went, but do not help them decide where their money should go next. People with limited income often have to balance everyday spending with savings goals, making it difficult to know how much they can spend while still reaching the things they care about.

## 2. SOLUTION

Finprio is a budgeting app that helps users build a budget around their personal priorities and savings goals. Users connect their bank accounts through Plaid, see how much they spend in each category, and choose which categories matter most to them. Users can then create a savings goal and see when they are expected to reach it based on their spending. The app updates the forecast when the user's spending or priorities change.

## 3. TARGET MARKET

Finprio is designed for college students and young adults who have regular income and expenses but want help balancing everyday spending with savings goals. The U.S. market includes millions of consumers who actively manage personal finances and face difficulty building adequate savings.

## 4. WHY IT IS VALUABLE

Finprio helps users understand the tradeoff between spending today and reaching their future goals instead of only showing them their past spending. This gives users a simple way to answer questions such as, "How much can I spend and still reach my vacation goal, or how can I get to my vacation goal sooner?"

## 5. HOW YOU WILL MAKE MONEY

Finprio will use a freemium subscription model. Basic spending tracking and savings goals will be free, while advanced forecasting, recommendations, and financial planning features will be available through a premium subscription.

## 6. MVP FEATURES

- **Plaid Account Connection**
  - Connect bank accounts through Plaid.
  - Import approximately two months of transaction history.
  - Automatically organize transactions into spending categories.

- **Personalized Spending**
  - Show total and average monthly spending by category.
  - Allow users to review and correct categories.
  - Establish an initial picture of the user's spending habits.
  - Let users assign importance to spending categories.
  - Store their initial preferences and use them when creating recommendations.
  - Allow users to change their priorities.

- **Savings Goals and Forecasting**
  - Create a goal with a target amount and current savings.
  - Examples include vacations, emergency funds, or large purchases.
  - Track progress toward the goal.
  - Estimate when the user will reach their goal based on current spending and savings.
  - Show how changes in spending affect the expected goal date.
  - Update the forecast when spending patterns change.

## 7. TIMELINE AND DIVISION OF WORK

### Week 1

- **Kaan:** Plaid integration and account connection
- **Elisha:** Transaction categories and spending calculations
- **Chinmay:** Spring Boot project and PostgreSQL database setup
- **Zender:** Onboarding and account connection UI

### Week 2

- **Kaan:** Transaction retrieval and data processing
- **Elisha:** Category assignment, spending summaries, and priority weights
- **Chinmay:** Personalized spending and transaction APIs
- **Zender:** Personalized spending dashboard, category, and priorities UI

### Week 3

- **Kaan:** Plaid testing and financial-data validation
- **Elisha:** Savings-goal forecasting logic
- **Chinmay:** Savings-goal and forecasting APIs
- **Zender:** Savings-goal creation and forecast UI

### Week 4

- **Kaan:** User testing with student testers and Plaid integration fixes
- **Elisha:** Forecast updates when spending or priorities change
- **Chinmay:** Full system integration, backend testing, and concurrent load testing
- **Zender:** Final UI improvements, recommendation screen, and presentation demo

## 8. TEAM ROLES AND RESPONSIBILITIES

### Kaan — Financial Data & Plaid Integration

- Build and test the Plaid account and transaction connection.
- Process and validate financial transaction data.
- **Estimated share of the codebase: 25%**

### Elisha — Budgeting & Forecasting

- Build category spending calculations and savings forecasts.
- Build priority weights and their effect on forecasts.
- **Estimated share of the codebase: 30%**

### Chinmay— Backend Engineering

- Build database models and Spring Boot APIs.
- Connect Plaid, personalized spending, savings goals, and forecasting features.
- **Estimated share of the codebase: 25%**

### Zender — Frontend & User Experience

- Build onboarding, personalized spending, savings goal, and forecast screens.
- Make recommendations and financial information easy to understand.
- **Estimated share of the codebase: 20%**

## 9. VIABILITY: HOW WE WILL PROVE THIS WORKS

### User Testing Plan 

- Test the MVP by connecting our personal checking accounts during the four-week development period. 
- Recruit three students from our class or campus as additional testers.
- Test the full flow: connect accounts, review spending, set priorities, create a savings goal, and view their forecast.
-  Check if the recommendations are understandable and useful.
- Collect feedback on which features they would use regularly.

### Competitive Analysis

Existing budgeting apps such as Monarch Money, YNAB, Rocket Money, and Copilot provide features such as account aggregation, transaction categorization, budgeting, goals, and spending analysis.

Finprio is different because its MVP connects **spending habits, personal priorities, and savings goals**. Instead of only showing users how they spent their money, Finprio helps them understand how their spending affects when they can reach something they care about.

### Market Research

The Federal Reserve's May 2026 report found that **37% of U.S. adults could not cover a hypothetical $400 emergency expense using cash or its equivalent**, showing the difficulty many households have maintaining financial flexibility. The Federal Reserve also reported that **58% of adults said changes in prices had made their financial situation worse**.

Bankrate's 2025 research found that only **46% of Americans had enough emergency savings to cover three months of expenses**, demonstrating continued difficulty building adequate savings.

### Success Metrics

- **7+ users** complete the MVP (our team of four and three student testers).
- **70%+** of users understand their spending breakdown.
- **70%+** of users understand their savings goal forecast.
- **60%+** of users say Finprio is more useful for planning than simply viewing their spending history.
- Users successfully create a savings goal and receive a forecast.
- The forecast successfully updates when spending assumptions change.

## 10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS

### Phase 1 — This Semester

**Target: 10–50 users**

Build the MVP with:

- Plaid account connection
- Transaction categorization
- Personalized spending
- Savings goals and forecasting

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

The MVP will use Plaid, a Spring Boot backend API, a PostgreSQL database, and a forecasting service. As the user base grows, the application can add background processing, caching, scalable cloud infrastructure, stronger transaction-processing pipelines, and more advanced forecasting models.

### Revenue Model

**Phase 1:** Free MVP to maximize user testing and adoption.

**Phase 2:** Freemium model with premium forecasting and personalized recommendations.

**Phase 3:** Premium subscriptions with advanced financial planning, household features, and personalized financial tools.

## 11. SOURCES AND REFERENCES

- **Federal Reserve Board — Report on the Economic Well-Being of U.S. Households in 2025 (May 2026)**
  - https://www.federalreserve.gov/publications/2026-economic-well-being-of-us-households-in-2025-executive-summary.htm

- **Bankrate — 2025 Emergency Savings Report**
  - https://www.bankrate.com/banking/savings/emergency-savings-report/

- **Plaid — Transactions API**
  - https://plaid.com/products/transactions/

- **Monarch Money — Personal Finance and Budgeting Features**

- **YNAB — Budgeting and Personal Finance Features**

- **Rocket Money — Budgeting and Financial Management Features**

- **Copilot Money — Personal Finance Features**

## 12. TECH STACK

- **Backend:** Java 21 and Spring Boot (Spring Web, Spring Data JPA, Spring Security)
- **Database:** PostgreSQL, with Flyway for schema migrations
- **Bank data:** Plaid, using the official Java client
- **Frontend:** React and TypeScript
- **Testing:** JUnit and Testcontainers for the backend, k6 for concurrent load testing
- **Local development:** Docker Compose

## 13. RESUME BULLETS

To be filled in with measured results at the end of the semester.

- Handled 1,000+ concurrent financial operations at a [x]% success rate and [x] ms p95 latency over [x amount of time].
