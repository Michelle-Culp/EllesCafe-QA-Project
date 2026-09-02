# 🍽️ EllesCafe — My First QA Project

Hi! 👋 

This is my very first QA portfolio project. I built a complete test suite for a fictional cafe website called **EllesCafe**. 

I wanted to show that I can:
- Write clear test cases that actually make sense
- Find bugs and explain them in a way developers can fix them
- Keep track of everything so nothing gets lost
- Think about how real users would use a website

---

## 🧪 What I Tested

I tested 4 main parts of the website:

| Module | What I Tested | Tests Written | Bugs Found |
|--------|---------------|---------------|------------|
| **Home Page** | Navigation, hero section, about section, customer favorites, footer | 6 | 2 |
| **Menu Page** | Page load, categories, images, quantity selector, mini cart, badge, back to top button | 8 | 6 |
| **Cart Page** | Page load, item display, quantity updates, remove items, grand total, place order, empty state | 7 | 10 |
| **Admin Dashboard** | Login, logout, unauthorized access, session persistence, dashboard display | 6 | 1 |
| **Total** | | **27** | **19** |

---

## 🐛 Some Bugs I Found

Here are a few of the more interesting bugs I caught:

| Bug | What Was Happening | How I Found It |
|-----|-------------------|----------------|
| **Cart badge doubling** | Every time you added an item, the count went up by 2 instead of 1 | Noticed the badge didn't match the number of items in my cart |
| **Images not showing** | Placeholder icons appeared instead of actual food photos | Checked the database and saw the image paths were missing |
| **Quantity selector broken** | Clicking "+" or "−" did nothing — the number stayed at 1 | Opened the console and saw a JavaScript error |
| **Grand total wrong** | The total didn't match what I calculated manually | Added up the items on paper and compared |

---

## 🛠️ Tools I Used

| Tool | What I Used It For |
|------|-------------------|
| **Excel** | Writing all my test cases and tracking defects |
| **Chrome DevTools** | Checking for errors in the console and testing load times |
| **SQL Server** | Checking if orders were actually saving to the database |
| **GitHub** | Keeping all my work in one place and sharing it |

---

## 📁 What's Inside This Repo

| File/Folder | What It Is |
|-------------|------------|
| `EllesCafe_QA_Test_Report.xlsx` | My complete test report — all test cases, results, and notes |
| `Defects_Log.xlsx` | Every bug I found, along with severity and status |
| `Screenshots/` | Visual proof for every test I ran |

---

## 💭 What I Learned

Working on this project taught me a lot about QA testing:

- **Details matter** — Small things like a missing image path can break the whole user experience
- **Clear documentation is everything** — If you can't explain a bug, developers can't fix it
- **Test early, test often** — Catching bugs early saves a ton of time
- **The console is your best friend** — F12 on Chrome shows you exactly what's breaking

---

## 🙏 Special Thanks

A big shoutout to **DeepSeek AI** for helping me with coding guidance and walking me through the technical parts of this project. Couldn't have done it without the support!

---

## 📬 Let's Connect!

If you're a recruiter, hiring manager, or fellow QA enthusiast — feel free to reach out!

www.linkedin.com/in/michelle-cul
(https://github.com/Michelle-Culp)
Michelle82677@gmail.com
