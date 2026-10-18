# LinkedIn Firmographics and Company Website

**Get the website, industry, employee range, headquarters, founded year, followers, and specialties from a LinkedIn company URL. $1 per 1,000 companies.** Starting from $0.45 per 1,000
## If you need a different Mawsool Actor

| If this is what you need | Open |
| --- | --- |
| You have an email and want the LinkedIn profile. | [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup) |
| You have a name and company and want the profile URL. | [LinkedIn Profile Finder](https://apify.com/oday/mawsool-linkedin-profile-finder) |
| You have a profile URL and want the personal email. | [LinkedIn Email Finder](https://apify.com/oday/mawsool-linkedin-personal-email-finder) |
| You only need the current employer, before paying for a full profile. | [Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) |
| You want the current company and headline, and you will compare them to your CRM yourself. | [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) |
| You want an alert when the employer or headline changes. | [Job Change Tracker](https://apify.com/oday/mawsool-linkedin-job-change-watch) |
| You have a profile URL and want the full profile. | [LinkedIn Profile Scraper](https://apify.com/oday/mawsool-linkedin-profile-details) |
| You have a large file of profile URLs. | [Mass Profile Scraper](https://apify.com/oday/mawsool-mass-linkedin-profile-scraper) |
| You want the current employer's website from a profile URL. | [Profile to Company Website](https://apify.com/oday/mawsool-linkedin-profile-to-company-website) |
| You want the job history only. | [Work Experience](https://apify.com/oday/mawsool-linkedin-profile-experience) |
| You want schools and degrees only. | [Education](https://apify.com/oday/mawsool-linkedin-profile-education) |
| You want a yes or no for one certificate. | [Certification Checker](https://apify.com/oday/mawsool-linkedin-certification-checker) |
| You want certificates, patents, courses, and publications. | [Certifications and Patents](https://apify.com/oday/mawsool-linkedin-profile-credentials) |
| You want likes and comments for outreach. | [Profile Activity](https://apify.com/oday/mawsool-linkedin-profile-activity) |
| You have a company URL and want the full company record. | [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) |
| You have a large file of company URLs. | [Mass Company Scraper](https://apify.com/oday/mawsool-mass-linkedin-company-scraper) |
| You want office addresses. | [Company Locations](https://apify.com/oday/mawsool-linkedin-company-locations) |
| You want lookalike companies. | [Similar Companies](https://apify.com/oday/mawsool-linkedin-similar-companies) |
| You want the recent posts on a company page. | [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) |
| You want only new posts on the next scheduled run. | [Company Post Monitor](https://apify.com/oday/mawsool-linkedin-company-post-watch) |

The same list is on [Mawsool's Apify profile](https://apify.com/oday).

## Use with AI agents

Apify exposes this Actor to ChatGPT, Claude, Gemini, Grok, and other agents through the Apify MCP server. Tell the agent the input you have, the fields you want back, and the starting price on this page. If you already have profile URLs and only need the current company and headline, use [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) first and compare the result to your CRM yourself.

 A visitor who starts on one Actor can open the rest from that page.


One company is one row and one charge. Use this when a CRM account needs a domain and firmographics. Use [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) at $2 per 1,000 when you also need posts, offices, and similar companies.

## Who is this for?

RevOps and sales teams enriching account lists before email finding or routing. The website is the company domain shown on the LinkedIn page.

## What does a row look like?

```json
{
  "inputUrl": "https://www.linkedin.com/company/example",
  "companyName": "Example",
  "website": "https://example.com",
  "industry": "Software Development",
  "companySize": "51-200 employees",
  "companySizeMin": 51,
  "companySizeMax": 200,
  "employeesOnLinkedIn": 120,
  "headquarters": "Austin, Texas",
  "countryCode": "US",
  "organizationType": "Privately Held",
  "founded": 2014,
  "followers": 5000,
  "specialties": "Cloud; Security",
  "success": true
}
```

## FAQ

### Does this find employees?

No. `employeesOnLinkedIn` is the headcount figure on the company page. It is not a list of people.

### Is the website always present?

The row returns the website when the company page has one. An empty website is a real result, not a failed run.

### When should I pay for [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) instead?

When you need posts, office addresses, or similar companies in the same run.

## Related Actors

[Similar Companies](https://apify.com/oday/mawsool-linkedin-similar-companies) to expand the list. [Company Locations](https://apify.com/oday/mawsool-linkedin-company-locations) for every office. [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) for the social feed.
