budget
======

M&M budget and financial statements accounting software


Overview
========
Build up an accounting software API from scratch modeled after Capital One's eAPI framework. Design and develop one piece at a time in small, manageable chunks. Continue to add to the framework until all the pieces are put in place and any UI can be build on top of it.

Start with a simple general ledger to store transactions in a database. Call the API using curl and a swagger client. Test with unit and integration tests. The API will be a JAVARS framework.


Phase I
=======
1. Get a general ledger up and running.
2. Database has 1 table (general_ledger) with 6 columns (account, date, description, debit, credit, balance). Down the road, there can be a separate table for each account so that it can scale better. Also, may consider looking into a nosql solution such as mongodb.
3. Record and retrieve entries to and from a general ledger as a proof of concept.
4. Get account balances
5. Get a total of credits and debits to enure they balance.
6. Get a total of assets, liabilities, and equity to ensure A=L+E.


Future Development
==================
1. Fund integration & Budget allocation
2. Investments/Stocks
3. Realestate
4. Retirement accounts (ie 401k, Roths)
5. Reports & Financial Statements (ie Balance Sheet, P&L, Cashflow, etc.)


Technologies
============
1. Git
2. Nexus
3. Maven (archetypes, plugins, profiles)
4. JAXRS (jersey, spring)
5. Tomcat, Jetty
6. HQL, JDBC
7. ActiveMQ
8. Swagger 
9. JUnit, Integration Tests


Accounting Notes
================
1. A General ledger has debits on the left, and credits on the right.
2. A listing of account names is called a "Chart of Accounts."
3. There are 7 categories: assets, liabilities, owner's equity, revenue, expenses, gains?, and losses?
4. There can be a number of subcategories such as cash, accounts receivable, accounts payable, bankaf, pg condo mortgage, etc.
5. Assets = Liabilities + Equity (A=L+E)


Additional Resources
====================

I. Accounting
1. Bookkeeping tutorial: http://www.dwmbeancounter.com/BCTutorSite/Courses/ChartAccounts/Tutorial6.html
2. Accounting for subsidiaries: http://wikihow.com/Account-for-Subsidiaries
3. Google "accounting general ledger stocks"

II. Technologies
1. Nexus: http://books.sonatype.com/nexus-book/reference


