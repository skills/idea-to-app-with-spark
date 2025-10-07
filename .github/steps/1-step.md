## Step 1: Getting Started with Spark

<img width="300px" align="right" alt="GitHub Spark logo" src="https://github.com/user-attachments/assets/46b8b848-28c3-4726-80d7-fb5be4ebb5f8">

You're _that person_, the one with ideas and passion. Maybe sometimes people shake their head and laugh at the thoughts you share. You have the great ideas that could help solve problems or improve processes, but you've never had the technical skills to build them.

Today, you'll discover that with GitHub Spark, your ideas can become real web applications that solve real problems for you. All you need is some niche work/hobby knowledge and a little patience to write down what you want to make (the hardest part).

### 📖 Theory: Describing what you want

GitHub Spark is designed for non-coders, really! 😎

It provides everything needed to make your web application and use it, no confusing coder talk at all. From this point on, think of _"Spark"_ as the nickname of a **new** friend/coworker.

That sounds like marketing fluff, _but we mean it._

Like a new coworker/friend, they will understand the basics of your field well, but not any private jargon and the frustrating problems. And... in familiar human style, they will avoid asking questions and just take creative liberty when you don't describe something well. (We all love that! 😅)

Spark is the same way, just faster! 🚀 So, chat a bit, watch the preview update, try to break it, share feedback, repeat.

Spark is:

- **No technical jargon** - Build like working with another person. No special words required (unless you want to).
- **Live preview** - See changes automatically, in minutes, for evolving fast.
- **No systems to manage** - Everything is included. Don't worry about the infrastructure.
<!-- - **Prototyping pro** - You can submit the same description multiple times in parallel to get different results. -->

> [!IMPORTANT]
> Spark's [billing](https://docs.github.com/en/copilot/concepts/billing/billing-for-spark) system operates using [Premium Request Units](https://docs.github.com/en/copilot/concepts/billing/copilot-requests#what-are-premium-requests) (PRUs), a quota of monthly allowed usage. Each request to Spark uses 4 PRUs. Don't feel bad about combining your ideas into fewer longer requests. 😎

### 📖 Theory: Write a good description

Assuming our friend _Spark_ is shy, likes to avoid questions, but loves to be creative (and explore fun stuff like us), the most important part of getting good results, is clear communication.

We all know starting the app with "Make an app to design paper plates." is pretty generic and probably won't get us what we actually want.

Rather than describe some theories of good communication, let's focus on our fun creative flow, and just get started with an example.

> [!TIP]
> You can use another AI chat tool, like Copilot on GitHub.com, to brainstorm ideas for your app and combine them into a clear plan for Spark to implement.

### ⌨️ Activity: Explore Spark and Create Your First App

1. Right-click the below link and open Spark in another browser tab.

   [![](https://img.shields.io/badge/Open%20Spark-%E2%86%92-f1e5ff?style=for-the-badge&logo=github&labelColor=894ceb)](https://github.com/spark)

1. Read the below sample application descriptions and pick your favorite.

   <details>
   <summary>1. Paper Plates - 🍽️ Prototype Designer</summary><br/>

   <img width="500" alt="Screenshot of example generated app for paper plate design" src="https://github.com/user-attachments/assets/0f391330-d324-4f17-9290-3851ef3aed49">

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=a830e8&color=f8e5ff)

   ```prompt
   Make an application for dynamically previewing the design of a paper plate.
   This will be used to help communicate with customers.

   ### Plate Preview

   - The preview is on the left and is dynamically generated from the values in the configuration panel. This is very very important.
   - There are 2 views: Top View and Front Section View. The attached image shows these example views.
   - Both views should be shown on the same page.
   - The front section should show the various dimensions. In the attached example image, the plate geometry is in red and the dimensions are in black.

   ### Plate configuration panel

   - The configuration options are on the right in a panel. It is always visible.
   - The parameters are the following:
   - Top out diameter - The maximum diameter from measuring the outside of the plate.
   - Top in diameter - Intersection of the side wall and the top of the plate.
   - Bottom out diameter - Intersection of the side wall and the bottom of the plate.
   - Plate Depth - The measurement from the top to the bottom of the plate.
   - Bottom Radius - The radius of the transition between the plate bottom and the side wall.
   - Plate Thickness - Default to 0.018 inches.
   - Side Wall Angle - The angle between the bottom of the plate and the side wall.
   - Quick Add Tool - Add a text box below the configuration options with the title "Quick Add". This will be used for copying an email into it that has all the configuration values somewhere. Use AI to scan the email text and automatically fill in the configuration values.

   ### Other considerations

   - All dimensions are in inches by default. Add a toggle for metric (millimeters).
   - Add a "designs" tab for storing the current and past designs. This will allow the user to quickly switch between designs. Add 3 example plates so the history already has samples to test with.
   - The interface needs to be beautiful. This is for marketing.
   - Make it work best for desktop. Phone does not matter.
   - The drawing will need to be downloaded as a PDF.
   - Multiple users will be using this simultaneously. Make sure they can't see each others' designs.
   ```

   </details>

   <details>
   <summary>2. Coffee Shop - ☕️ Secret Menu</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Create an application to help a barista build a secret menu with fellow staff.
   Add a side panel with filters to make it easy to find recipes.
   ```

   </details>

   <details>
   <summary>3. Lacrosse Coach - 🥍 Player Improvement</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=bc4c00&color=ffe7d1)

   ```prompt
   Create an application to track player improvement stats for coaching lacrosse.
   ```

   </details>

1. Copy your favorite choice and paste it into the description text box, then click the **Submit** button. You will be forward to a page with the chat interface and live preview.

   <img width="350" alt="Spark start box with example text and highlighted submit button" src="https://github.com/user-attachments/assets/0e6afb14-7791-4741-b2c1-bb788ee5bba1">

1. In the left chat panel, notice that Spark is providing constant feedback about progress of your app.

   <img width="350" alt="Spark chat with live progress information" src="https://github.com/user-attachments/assets/45ded9dc-6744-4a16-ae4f-af25836a5ae8">

1. Wait a few minutes for Spark to finish. Enjoy the playful messages while you wait! Note: Your results will likely be different from the example screenshot shared earlier.

   <img width="350" alt="Playful messages with sparkles decoration" src="https://github.com/user-attachments/assets/46ca83de-22e0-47ca-b54c-e6acf975c7b9">

> [!TIP]
> If you start multiple Spark apps with the same or similar descriptions, you'll get different results. A great way to explore parallel ideas! But be careful, that will also use up your quota quickly too!

<details>
<summary>Having trouble? 🤷</summary><br/>

- If your app doesn't work well on the first try, don't worry! You can resubmit the same prompt to get a different result
- If it seems to be taking a while, that is normal. A well thought out application with lots of requirements can take a long time, even 20 or 30 minutes.

</details>

## App ready?

<img width="100px" align="right" alt="Nyantocat Gif" src="https://octodex.github.com/images/nyantocat.gif">

When your app seems to be ready and working, check the box of the example application you chose to create, then wait a few moments for the next step to be shared.

- [ ] Paper Plates - 🍽️ Prototype Designer
- [ ] Coffee Shop - ☕️ Secret Menu
- [ ] Lacrosse Coach - 🥍 Player Improvement
- [ ] My Own - Nice! 🦄 🧙
