# budget-spreadsheet
Excel-based monthly spending planner

## Introduction
When my wife and I took Dave Ramsey's "Financial Peace University" course in late 2012 we created this spreadsheet to plan and track our spending.
I think it is a good compromise between a full-blown accounting system (I had been using (GnuCash)(http://www.gnucash.org/) for years)
and pencil and paper (if you do this by hand, props to you for your patience and organization!).
DISCLAIMER: Although it works great for my purposes, I'm an engineer and enjoy numbers, spreadsheets, formulas, source code, etc.
If you're not comfortable working with an Excel spreadsheet and aren't interested in learning that, I recommend using a budgeting app like (EveryDollar)(https://www.everydollar.com/) instead. They're designed to be hard / impossible to mess up and usually include free technical support.
Although I've tried to make this spreadsheet pretty robust (shouldn't be able to get wrong answers without intentionally disabling the worksheet protection feature) and easy to tailor to your needs, I make no guarantees about the accuracy of its calcuations, its reliability, or any other concern. I use it and find it helpful so I've shared it with the public for you to do with as you please.

## How do I use it?
Download the [`Financial Plan.xlsx`](./Financial Plan.xlsx) file and open it using Microsoft Excel.
(It does not contain any VBA scripting so might work in other spreadsheet software, but I have not tested this.)
Read the instructions in the blue text boxes and try it out. If you get stuck feel free to post a question in the ["Issues" section of the Github repository](https://github.com/jacobq/budget-spreadsheet/issues).

## How it works
(**Note: This documentation is incomplete. If you feel like helping out please improve it and submit a pull request!**)

Before we dive in, I want to define some terms that I'll be using:
- *account*: something that can contain money/debt (e.g. checking account, wallet / envelopes, mortgage, credit card, etc.)
- *income*: money coming into an account
- *transfer*: money moving from one account to another
- *expense*: money leaving an account

In order to use this spreadsheet you'll have to decide what accounts you want to track with it and how you'd like to categorize your spending.

...

This spreadsheet is based around the idea of a (Zero-Based Budget)(http://www.daveramsey.com/blog/zero-based-budget-what-why)
(Note that this term also has another meaning, see (Wikipedia)(https://en.wikipedia.org/wiki/Zero-based_budgeting), but that's not what I'm talking about).
That is, the total amount of income must match the total amount of expenses in order for it to work.


