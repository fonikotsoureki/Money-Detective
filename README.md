# Money Detective: A Practical Savings Planner

## 1. Summary

**Money Detective** is a simple budgeting tool that helps people understand where their money is going and decide what they can realistically save. Users enter their income and fixed expenses, log daily spending, set a savings goal, and see a payday plan with warnings when their budget is tight.

The current MVP uses clear rules and calculations rather than AI. It is designed to make everyday money decisions easier to see and discuss.

## 2. Background

Many people have a general idea of their income and bills but find it harder to track small purchases, plan for savings, or tell whether they can afford to set money aside. Those decisions come up throughout the month, especially around payday and when unexpected costs appear.

The problem is relevant to anyone managing a personal or household budget. Money Detective focuses on practical questions: “How much have I spent?”, “What remains after my bills?”, and “Can I contribute to my goal this week?”

This project is interesting because small, understandable calculations may help people make more deliberate choices without requiring a complicated financial product.

## 3. Data and AI techniques

The MVP depends on data entered by the user:

- Monthly take-home income and payday
- Fixed monthly expenses and a planned savings amount
- Daily expenses, including amount, date, and category
- Savings goals, contributions, and purchases the user avoided

The app stores this information in the browser’s local storage. It does not connect to a bank or use external datasets. Sample data is included to demonstrate the features; it is illustrative, not research data.

The current version uses basic arithmetic and rule-based suggestions. For example, it subtracts fixed expenses and planned savings from income, then subtracts logged expenses to estimate the remaining flexible budget. It keeps avoided purchases separate from actual spending and savings unless the user confirms a transfer.

Possible future AI techniques could summarize spending patterns or help users set a realistic goal. Those features would need to be tested carefully, use reliable data, explain their suggestions, and avoid presenting guesses as financial advice.

## 4. How is it used?

A person using the tool enters their monthly plan, logs purchases as they happen, and reviews the dashboard to see spending, remaining budget, and goal progress. They can record an avoided purchase, but it only counts as savings if they confirm that they actually moved the money.

The main users are individuals managing their own budgets. Other people affected may include household members who share expenses or savings goals. Their needs may differ, so a shared budget should make clear who entered each item and how decisions are made. The MVP is a single-user prototype and does not yet support shared accounts.

## 5. Challenges

Money Detective relies on accurate, up-to-date information entered by the user. It cannot verify purchases, account balances, bills, or whether a planned transfer happened. It does not account for every financial situation, irregular income, debt, emergencies, or the timing of bills within a month.

Its “safe to spend” amount is a budgeting estimate, not a guarantee that money is available. Rule-based suggestions may be too general, and the prototype is not financial advice. Since data stays in one browser, it is not automatically backed up or synchronized across devices.

## 6. What next?

The next steps could include:

1. Test the prototype with people who manage different kinds of budgets and improve the wording and calculations based on their feedback.
2. Add support for irregular income, multiple goals, and bill due dates.
3. Improve privacy and backup options before considering any account or bank integrations.
4. Explore optional AI summaries that explain observed patterns, while keeping the underlying figures visible and letting users correct mistakes.
5. Evaluate whether suggestions are understandable, useful, and appropriate for people with different financial circumstances.

## 7. Acknowledgments

Money Detective MVP v0.5 was created for this project using standard HTML, CSS, and JavaScript. It does not bundle external libraries or use third-party datasets. Its sample figures are fictional and included only to demonstrate the interface.

The project is inspired by common personal-budgeting practices: tracking spending, planning for fixed costs, and saving toward a goal. Any future external data, software libraries, or research used in later versions should be credited here.
