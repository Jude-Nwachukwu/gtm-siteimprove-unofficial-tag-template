# Siteimprove (Unofficial) GTM Tag Template

This Google Tag Manager custom **Tag Template** is used to implement Siteimprove tracking on your website. It allows you to:
- Install the official Siteimprove analytics script.
- Send custom event data to Siteimprove.
- Trigger pseudo page view events (virtual page loads) with optional automatic or manual metadata.

---

## 🚀 Features

- 🔧 Install Siteimprove analytics tracking script.
- 📊 Trigger Siteimprove event tracking.
- 📄 Send pseudo page load events for single-page apps or dynamic content.

---

## 📦 Importing the Template into GTM

1. Download the `.tpl` file for this tag template.
2. In GTM, go to **Templates** → **Tag Templates**.
3. Click **New**, then use the 3-dot menu to **Import** the `.tpl` file.
4. Save and name the template.
5. Create a new **Tag** in GTM using this template.

---

## ⚙️ Configuration Guide

When adding a tag using this template, select the **Siteimprove Tracking Tag Type** from the dropdown. Each option will enable a different set of fields.

---

### 1. 🛠️ Install Script

**Purpose:** Adds the Siteimprove tracking script to your site.

- **Siteimprove Site ID**  
  _Enter your Siteimprove Site ID (e.g., `12345`)._  
  _You'll find this inside the embed script as `siteanalyze_12345.js`._

---

### 2. ✅ Event Tracking

**Purpose:** Send custom events to Siteimprove.

- **Siteimprove Event Category**  
  _Enter a category name for the event (e.g., `Viewed Product`)._

- **Siteimprove Event Action**  
  _Describe what happened (e.g., `Clicked Button`)._

- **Siteimprove Event Label**  
  _Add additional context (e.g., `Signup Page`)._

---

### 3. 💻 Psuedo Page Load Event

**Purpose:** Trigger virtual pageviews (used for dynamic websites or SPAs).

#### Tracking Method:
- **Siteimprove User ID**  
  Select either:
  - **Automatic**: Automatically pull URL, referrer, and title from the page.
  - **Manual**: Use custom values.

If **Manual** is selected, fill out the following:

- **Page URL**  
  _Enter the virtual page URL (e.g., `/checkout`)._

- **Page Referrer**  
  _Enter the referrer page URL._

- **Page Title**  
  _Enter the title for the virtual page._

---

### 🧩 Optional Configuration

- **Disable Console Logging**  
  _Enable this to prevent logs from being printed in the browser console._

---

> Developed by **Jude Nwachukwu Onyejekwe** for [DumbData](https://dumbdata.co)

---

## 📄 License

Apache 2.0

---

This is an unofficial tag template and not affiliated with Siteimprove. For more resources and analytics templates, visit [DumbData](https://dumbdata.co).
