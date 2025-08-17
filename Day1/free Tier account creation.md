# Day-01: Introduction to Cloud and GCP

- What is Cloud Computing?
- Difference between Cloud and Traditional IT
- Why choose Google Cloud (GCP) over AWS or Azure?
- Create your Free GCP Account
- Quick Tour: GCP Console and Cloud Shell

---

## Concepts Simplified

### What is Cloud Computing?

Cloud computing means renting servers, databases, storage, and other services over the internet instead of owning them.

In simple words:  
> "You pay only for what you use. No upfront investment, no maintenance headache."

**Cloud providers**: Google Cloud (GCP), Amazon Web Services (AWS), Microsoft Azure

---

### Traditional IT vs Cloud

| Traditional IT                | Cloud (GCP)                       |
|------------------------------|-----------------------------------|
| Buy servers upfront           | Rent what you need                |
| Pay for peak capacity         | Auto-scale as needed              |
| Manual setup                  | Automated provisioning            |
| High maintenance              | Managed by Google                 |

---

### Why GCP?

- Google-level infrastructure (same as YouTube, Gmail)
- Powerful networking and AI services
- Easy to use UI + powerful CLI
- Cost-effective and beginner-friendly
- Used by gaints like META


---

## Task: Create Your Free GCP Account

1. Go to: https://cloud.google.com/free
2. Sign in with your Gmail
3. Provide PAN and card details or UPI

4. Step to create Free Tier account 

- Go to the Free Tier page and click Get started for free. Sign in with your Google account. 
  Google Cloud

- Create a Cloud Billing account / payments profile
  You’ll be guided to set up a Google payments profile (individual or business) with your name, address, and country (India). 
  Google Help
  Google Cloud

- Add a payment method (identity verification)
  Add your card or bank account. Google may place a $0.00 authorization (not a charge) to verify. If your card requires 2-factor at the     bank page to complete every online payment, it might not be accepted. 
  Google Cloud
  +1

- Accept the Free Trial terms
  The Free Trial starts when you create the billing account. It ends when you use all $300 or after 3 months (90 days)—whichever comes      first. Unused credit expires at 3 months from the start date. 
  Google Cloud

- Finish signup
  You now have a Free Trial billing account. Google says there are no automatic charges during the trial; you must explicitly upgrade to   a paid account to be billed. 
  Google Cloud

- Create your first project in the Google Cloud console and ensure it’s linked to your Free Trial billing account (Console → Billing →     “Go to linked billing account”). 
  Google Cloud

- Enable the services you need (e.g., Compute Engine, Cloud Storage, BigQuery). Many products also have “Always Free” monthly limits you     can keep using even after the trial—handy for small VMs, storage, etc. 
  Google Cloud

- Set a budget and alerts (strongly recommended)
  Console → Billing → Budgets & alerts → Create budget → add email thresholds so you’re notified as you spend trial credit. 
  Google Cloud


✅ No charges unless you upgrade manually.

---

## Task: Explore GCP Console and Cloud Shell

### GCP Console

- URL: [https://console.cloud.google.com](https://console.cloud.google.com)
- Everything you need is here: compute, storage, billing, IAM, etc.

### Cloud Shell

- Built-in terminal in your browser
- Free VM with 5GB storage
- Comes pre-installed with `gcloud` CLI

🔍 Try this:
```bash
gcloud auth list
gcloud config list
```

---
