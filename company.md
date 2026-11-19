# Kinship Business Banking

- **Company:** Kinship Business Banking, a fictional business-account company in London
- **Mission:** Open a business account for a family-run business, and keep that business’s records separate from every other customer.
- **Customers:** Metalwharf Grocers and Canada Circle Lettings, whose data must never mix
- **Roles:** customer user (the business owner), customer admin (the owner’s spouse, with a separate login for that same business only), staff admin (a Kinship employee who reviews applications in the admin portal). The only security engineer is Waqas. That role is on the org chart, not one of these three product roles.
- **Product:** a public website with login, a separate admin portal, a public API for a fictional identity-check partner, and an AI chatbot on AWS Bedrock
- **Data:** structured account and application records, and unstructured identity documents and chatbot transcripts
- **Tools:** Jira KBB, Confluence KBB, draw.io, GitHub Waqas-Z/kinship-business-banking
- **Security framework:** [not set yet]
- **Current phase:** plan

## Company story

Kinship Business Banking is a fictional company in London and does not claim a real banking licence. In this story, it opens business accounts for family-run businesses. It does not open accounts for large businesses.

A business applies on the public website. The business owner is the customer user. The owner’s spouse is the customer admin and has a separate login for that same business only. A Kinship employee, the staff admin, reviews the application in a separate admin portal. The chatbot on AWS Bedrock can answer questions. It cannot approve an account. A fictional identity-check partner uses the public API and does not get a staff login.

Each business pays a monthly fee for its account. Kinship does not lend money.

The two customers are Metalwharf Grocers and Canada Circle Lettings. One must never be able to see the other’s records.

Two fictional competitors are a large high-street bank that serves big companies, and an app-only account service that is not built for family-run businesses. Neither name is a real company.

The failure Kinship will not accept is one customer seeing another customer’s data, or the chatbot approving an account. The success metric is a family-run business getting an account whose records stay separate from every other business.
