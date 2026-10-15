# Endometriosis Resources

**A free, public educational website that makes trustworthy information about endometriosis easy to find and understand.**

<!-- If the site is live, add its link here: 🌐 **[Visit the site](https://your-site-url)** -->

---

## Why I Built It

Endometriosis affects roughly 1 in 10 women and people assigned female at birth, yet diagnosis often takes years, and many people struggle to find clear, reliable information about their symptoms and options. I built this site as a public good: a free, ad-free resource where anyone can learn about the condition, understand what to ask their doctor, and find research, without a paywall or sign-up.

The site has reached **600+ professionals**, helping raise awareness of a condition that is widely underdiagnosed.

## What's on the Site

| Page | Content |
|---|---|
| **Home** (`index.html`) | An overview of endometriosis and how to navigate the site |
| **Details** (`details.html`) | Symptoms, diagnosis, and treatment options |
| **Home Remedies** (`home-remedies.html`) | Everyday approaches people use alongside medical care to manage symptoms |
| **Medical Studies** (`medical-studies.html`) | Research on endometriosis for readers who want to go deeper |

I researched and wrote all of the site's content myself.

## Design Process

I refined the site through **10 iterative design cycles**, incorporating feedback from **5 users** to improve readability, navigation, and accessibility. The goal was for someone overwhelmed by a new diagnosis or unexplained symptoms to find what they need quickly.

## How It's Built and Hosted

- **Front end:** HTML and CSS, with no frameworks, so pages load fast on any device
- **Hosting:** Deployed on AWS, using **EC2** running an **Apache** web server, with assets stored in **S3**
- **Security:** Served over HTTPS with SSL certificates I configured

## Run It Locally

```bash
git clone https://github.com/userxyc123/EndoResources.git
cd EndoResources
```

Open `index.html` in any browser. No build step or dependencies are needed.

## Disclaimer

This site is for educational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment. If you think you may have endometriosis, please talk to a healthcare provider.

## Author

Built by **Sakshi Verma**, University of Washington, Computer Science.
