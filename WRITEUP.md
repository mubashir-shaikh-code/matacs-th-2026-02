1. AI vs. rules

I use AI for one job only: reading each proposal and finding the main details, like licence, price, weeks and warranty. Every contractor writes in a different way, so something has to read and understand the text.
Everything else is normal code: upload, getting the text, pass/fail checks, scoring and sorting. These steps must give the same answer every time. AI can make mistakes with numbers, and it can be fooled by text hidden inside a proposal. So AI reads, and code decides.

2. Consistency and explainability

The AI only finds the details. The score is worked out by code with fixed rules, so the same details always give the same score. If I rank the same proposals twice, I should get the same list.
For every detail, the AI also copies the exact line from the proposal. Code checks that this line really is in the proposal. The reviewer can see each score, the line behind it, and a short reason for the position.

3. Human in the loop

A person checks the ranked list. They also see the proposals that were not ranked, with the reason. They can change any result, but they must write why. A person makes the final decision. The tool never does.
A log keeps a record of everything: what was uploaded, what the AI found, the scores, any warnings, any change made by the reviewer and why, and the final decision.

4. Changing criteria

Every result is saved together with the version of the criteria it used. If the admin changes the criteria later, the old results are marked "old version". They are not changed quietly. The reviewer can choose to score again. Both the old and new results are kept.

5.Risks

- The AI could read a detail wrongly or make one up. It must copy the exact line from the proposal and must not guess. Code checks the line, and a person reviews the result.
- A proposal may leave out something important. The tool does not guess. It sends that proposal to a person.
- A bidder may promise something for later, like a licence. A promise does not count, so the proposal fails the must-have check.
- Text inside a proposal may try to give orders to the tool. The tool treats it as plain text, not as an order, and sends the proposal to a person.
- The tool could be unfair to some bidders. It only scores the admin's criteria. It does not use company name or size.
- AI costs money. It is used once per proposal, for one step only.
