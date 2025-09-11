# Indie Hacker API Collection

8 essential business APIs for indie hackers and startups. Clone, add keys, start building.

## Why This Exists

When you're starting a new business, speed is everything. You need to ship fast to validate your ideas and iterate quickly. Hunting through API documentation shouldn't be on your to-do list.

This collection gives you the most common APIs that businesses need - payments, messaging, search, media management, and more. Each API is pre-configured and ready to test, so you can focus on building your product instead of wrestling with documentation.

Perfect for indie hackers, solopreneurs, and early-stage startups who want to move from idea to MVP as quickly as possible. More APIs will be added to this collection over time.

## Quick Start

```bash
git clone https://github.com/yourusername/indie-hacker-api-collection.git
```

1. Download [Requestly Desktop App](https://requestly.io/desktop/)
2. Create a new **Local Workspace** and select the cloned folder
3. Requestly will automatically load all API collections
4. Add your API keys to collection variables
5. Start testing

## API Collections

| Collection | Documentation | Key Requests | Free Tier |
|------------|---------------|--------------|-----------|
| **Stripe** | [Docs](https://stripe.com/docs/api) | Create Payment Intent, Create Customer, Create Refund, Get Payment Status, List Payments, Update Customer | Test mode unlimited |
| **Twilio** | [Docs](https://www.twilio.com/docs) | Send SMS, Check Message Status, Get Account Info, Get Account Balance, List Available Numbers | $15 trial credit |
| **OneSignal** | [Docs](https://documentation.onesignal.com/) | Push Notification, Create User, Subscribe User, Check User | 10K web subscribers |
| **Resend** | [Docs](https://resend.com/docs) | Send Email, Send Batch Email, Create Audience, Create Contact, Retrieve Email, Update Email | 3K emails/month |
| **Supabase** | [Docs](https://supabase.com/docs) | Signup User, Sign In, Get User, Update User, Reset Password | 500MB database |
| **Algolia** | [Docs](https://www.algolia.com/doc/) | Search Index, Add Record, Get Record, Delete Record, List Indices | 10K records |
| **Cloudinary** | [Docs](https://cloudinary.com/documentation) | Upload File, Delete File, Search Resource, Get Resource Details, Generate Text Image, Get Usage Stats, Ping Check | 25GB storage |
| **Instatus** | [Docs](https://instatus.com/help/api) | Post Incident, Update Incident, Delete Incident, Get All Incidents, Create Status Page, Get Page, Delete Page | 1 status page |

## Common Use Cases

**E-commerce**: Stripe + Algolia + Cloudinary + Twilio  
**SaaS**: Supabase + OneSignal + Resend + Instatus  
**Content Platform**: Cloudinary + Algolia + OneSignal + Stripe

## Important Notes

- **Most APIs work immediately** with just API keys added to collection variables
- **Never commit API keys** to version control - use test/sandbox keys during development
- **Rate limits apply** - Monitor usage for Twilio (1 message/second), Stripe (100 requests/second), and others
- **File upload APIs** may require content-type adjustments in some clients
- **Webhook endpoints** are recommended for production use with Stripe, OneSignal, and Supabase
- Always refer to official documentation for the most up-to-date requirements

## Contributing

Found an issue or want to add more APIs?

1. Fork this repo
2. Add new API collection JSON file
3. Update the README table with the new API details
4. Submit a PR

Each new API should include:
- Proper authentication headers and variables
- Working request examples with realistic payloads
- Clear variable names and descriptions

Built for indie hackers who want to ship fast.