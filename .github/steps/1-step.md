## Step 1: Getting Started with Spark

<img width="300px" align="right" alt="GitHub Spark logo" src="https://github.com/user-attachments/assets/46b8b848-28c3-4726-80d7-fb5be4ebb5f8">

You're _that person_, the one with passion and too many ideas.
You have the great ideas that could help solve problems or improve processes, but you've never had the technical skills to build them.

Today, you'll discover that with **GitHub Spark**, your ideas can become real web applications that solve real problems for you. All you need is some niche work/hobby knowledge and a little patience to write down what you want to make (the hardest part).

### 📖 Theory: What is Spark?

GitHub Spark is designed for non-coders, really! 😎

It provides everything needed to make your web application and use it, no confusing coder talk at all.
From this point on, think of _"Spark"_ as the nickname of a **new** friend/coworker.

That sounds like marketing fluff, _but we mean it! ✨_

When a new coworker joins the team, they will probably understand the common fundamentals of your field well. However, they likely don't understand internal jargon, your specific challenges, and the team's goals. Spark is the same way, just faster! 🚀 So, chat a bit, watch the preview update, try to break it, share feedback, repeat.

Also... in familiar human style, Spark will often avoid asking questions and just take creative liberty when you don't describe something well. (We all love that! 😅)

In short, Spark is:

- **No software jargon** - Collaborate like you would with another person. No special software words required (unless you want to).
- **Live preview** - See changes automatically, in minutes, for evolving fast.
- **No systems to manage** - Everything is included. Don't worry about the infrastructure.
- **Fast** - Minutes to a prototype. Not days.

> [!IMPORTANT]
> Spark's [billing](https://docs.github.com/en/billing/concepts/product-billing/github-spark) system operates using [Premium Request Units](https://docs.github.com/en/copilot/concepts/billing/copilot-requests#what-are-premium-requests) (PRUs), a quota of monthly allowed usage. Each request to Spark uses 4 PRUs. Don't feel bad about combining your ideas into fewer longer requests. 😎

### 📖 Theory: Write a good description

Assuming our friend _Spark_ is shy, likes to avoid questions, but loves to be creative and explore fun stuff (like us), the most important part of getting good results is: clear communication

We all know starting the app with "Make an app to design paper plates." is pretty generic and probably won't get us what we actually want.

Rather than describe some theories of good communication, let's focus on the fun creative flow, and just get started with an example.

> [!TIP]
> Use another AI chat tool, like [Copilot on GitHub.com](https://github.com/copilot), to brainstorm ideas for your app and build a clear plan for Spark to implement.

### ⌨️ Activity: Explore Spark and Create Your First App

1. Right-click the below link and open Spark in another browser tab.

   [![](https://img.shields.io/badge/✨%20Open%20Spark-%E2%86%92-f1e5ff?style=for-the-badge&labelColor=ce2c85&color=f8e5ff)](https://github.com/spark)

1. Read the below sample application descriptions. Decide which you like best.

   <details>
   <summary>1. Coffee Shop - ☕️ Secret Menu (short)</summary><br/>

   Sometimes, we want to get started quickly and are flexible with the outcome. Here is an example of a very open-ended prompt. If you like this one, paste it into the description text box and click the **Submit** button.

   <img width="500" alt="Screenshot of example generated app for coffee shop" src="https://github.com/user-attachments/assets/18a91fb9-5f5b-48f1-9736-e6f089b1f45b">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Create an application to help a barista build a secret menu with fellow staff.
   Add a side panel with filters to make it easy to find recipes.
   ```

   </details>

   ***

   <details>
   <summary>2. Lacrosse - 🥍 Stats Tracker (regular)</summary><br/>

   Maybe you have lots of notes and specific requirements. Here is an example of something more detailed. If you like this one, paste it into the description text box and click the **Submit** button.

   <img width="500" alt="Screenshot of example generated app for lacrosse" src="https://github.com/user-attachments/assets/c750bbf2-bccd-4147-b6fa-66bffe964674">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=bc4c00&color=ffe7d1)

   ```prompt
   # Lacrosse Statistics App

   Make an application for tracking statistics for the players of a lacrosse team. This will be used to help coaches optimize team performance.

   App Name: Lacrosse Stats Tracker
   Team Name: The Cherry Pickers

   ## Application Requirements

   There are 3 tabs for different modes, and a side panel for settings.

   - Setup - Features to manage the team.
   - Track Stats - Primary entry screen entering stats.
   - Reports - High level overview of the entire team.
   - Config Panel - Quickly access to various settings.

   ### Setup

   The Setup page is mainly used for organizing members of the team.

   - It should be easy to edit multiple names.
   - Provide an option to upload via CSV.
   - Provide an option to download via CSV.
   - Provide a "Download Sample CSV" file that provides the required format for uploading.
   - Ensure support for multiple player positions.

   - Provide a button to clear the stats but not the team.
   - Provide a button to clear everything.
   - If importing multiple times, update existing entries without deleting them or associated stats.

   ### Track Stats

   This page is the primary entry screen that allows the coach to enter scores live during the game.

   - Add a tab bar at the top to select the current quarter. Stats are stored associated to it.
   - Each player has 2 sets of buttons: offensive stats and defensive stats.
   - It should be easy to find a player and choose a statistic.
   - It should be easy to increase/decrease a statistic. Example: a `+` button and `-` button
   - Add a search field to quickly find a player.

   ### Reports

   - Basic game info like: Game Name, Opponent, Date, Location
   - List top three players for every statistic.
   - Tables to select report view: Full Game, Q1, Q2, Q3, Q4.
   - Table showing all statistics.
   - Include totals for each player and overall for the game.
   - Button to export as CSV. All reports are included.
   - Button to save as PDF. All reports are included.

   ### Config Panel

   - It should always be visible on the right side of the page, for easy access to change settings.
   - Add a dropdown toggle for display (Light, Dark, System). Default to the current phone's mode.
   - Readability - Provide 3 settings for easier viewing. (Compact, Spacious, Large Font)

   ### Other considerations

   - Make it work best on phones. This will be used live during games.
   - The page should never need refreshed to view a change.
   - A player can have multiple positions. example: SSDM / LSM
   - Use the exact names for the player details and statistics.
   - All math for the statistics needs to be 100% accurate. This cannot ever be wrong.
   - Include sample data for 20 players for easily testing the app.
   - The Readability setting adjusts the layout for accessibility.

   ## Background on lacrosse

   There are 10 players on the field per team.

   ### Positions

   - There are offensive and defensive players.
   - Attack and midfield are offense.
   - Long stick midfielder (LSM) is a cross between offensive and defensive.
   - Short stick defensive midfielders (SSDM) mostly play defense.
   - Close defense long poles mostly play defense.
   - Faceoff players are also called FOGOs.
   - Goalie

   ### Player Details

   - First Name
   - Last Name
   - Number
   - Position
   - School Year (Freshman, Sophomore, Junior, Senior)
   - Hometown (City and State)

   ### Offensive statistics

   - Goals
   - Assists
   - Shots
   - Faceoff Win
   - Faceoff Loss

   ### Defensive statistics

   - Ground balls (GBs)
   - Caused turnover (CTO)

   ### Goalie statistics

   These stats are only visible and trackable for people with the "Goalie" position.

   - Goals saved
   - Goals allowed
   ```

   </details>

   ***

   <details>
   <summary>3. Paper Plates - 🍽️ Prototype Designer (long)</summary><br/>

   Is your requirement very technically specific? Here's an example that also attaches an image. If you like this one, paste it into the description text box and click the **Submit** button.

   <img width="500" alt="Screenshot of example generated app for paper plate design" src="https://github.com/user-attachments/assets/c1b6359f-3104-4250-9e63-8ca3a9a86e3d">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=a830e8&color=f8e5ff)

   📎 Attachment: [Example Paper Plate Drawing](https://github.com/user-attachments/assets/8fbc27db-1dc8-4ef6-a85d-7e732d7f88f1) (optional)

   ```prompt
   Make an application for dynamically previewing the design of a paper plate.
   This will be used to help communicate with customers.

   ### Plate Drawing Preview

   There is a live preview on the left showing a CAD drawing of a paper plate.

   This drawing must look identical to the attached image of a real drawing.
   Below are details to understand the attached image:

   - There are 2 views: Top View and Front Section View. The top view is always directly over the front section view. The top view has a line (A) indicating the path of the section view (Section A-A).
   - The title block is in the bottom right. It includes information about the company, plate design, designer, and date.
   - Below the drawings is a disclaimer. This text must be exactly the same.
   - The front section views (Section A-A) show the dimensions.
   - In the attached example image, the plate geometry is in red and the dimensions are in black.
   - The placement of the dimensions is somewhat flexible. Just make sure they don't overlap and all clearly have leader lines pointing to the correct location.

   ### Plate Configuration Panel

   There is a configuration panel on the right that provides all configuration options for the design of the plate in the drawing.

   - It is always visible.
   - The plate design is dynamically generated from the values in the configuration panel. This is very very important.

   The parameters are the following:

   - THICK - The thickness of the paper. Default to 0.018 inches.
   - PLATE DEPTH - The distance from the top to the bottom of the plate.
   - TOP OUT DIAMETER - The maximum diameter from measuring the outside of the plate.
   - TOP IN DIAMETER - Intersection of the theoretical side wall and the top of the plate.
   - BOTTOM OUT DIAMETER - Intersection of the side wall and the bottom of the plate.
   - SIDE WALL - The angle between the plate bottom and the plate side.
   - TOP RADIUS - The transition radius between the plate top and the plate side.
   - BOTTOM RADIUS - The transition radius between the plate bottom and the plate side.
   - FLANGE DEPTH - The distance from the top of the plate to the bottom of the the flange.
   - TURN DOWN - The angle of the flange relative to the plate top.
   - TURN DOWN RADIUS - The transition radius between the plate top and the flange.

   ### Enhancements

   The following features are independent of the design but must be included.

   1. Saved Designs - Add a "designs" tab in the configuration panel for storing the current and past designs. This will allow the user to quickly switch between designs. Add 3 example plates so the history already has samples to test with.

   1. Export to PDF - A button below the drawing preview. This will open a new page formatted for printing and trigger the print dialog.

   1. Quick Add - Add a text box below the configuration options with the title "Quick Add". This will be used for copying an email into it that has all the configuration values somewhere. Use AI to scan the email text and automatically fill in the configuration values.

   ### Other considerations

   - All dimensions are in inches by default. Add a toggle for metric (millimeters).
   - The interface needs to be beautiful. This tool will be used by sales and marketing teams.
   - Make it work best for desktop. Phone does not matter.
   - Multiple users will be using this simultaneously. Make sure they can't see each others designs.

   ### Context

   - Plates are made out of paper board, not paper (like for writing).
   - You are an expert paper plate designer.
   - You are an expert computer aided drafter.
   ```

   </details>

   ***

1. You will be forward to a page with the chat interface and live preview.

   <details>
   <summary>🐛 Did you get an error message? </summary>

   Sometimes Spark can get a bit _too_ ambitious and break things. When this happens, they can usually be fixed by clicking the **Fix all** button.

   <img width="350px" alt="Screenshot of Fix All button" src="https://github.com/user-attachments/assets/7a4e5543-8d37-4d98-9da4-3e46bf8526ec" />

   </details>

   <img width="350" alt="Spark start box with example text and highlighted submit button" src="https://github.com/user-attachments/assets/0e6afb14-7791-4741-b2c1-bb788ee5bba1">

1. In the left chat panel, notice that Spark is providing live feedback about the progress of your app.

   <img width="350" alt="Spark chat with live progress information" src="https://github.com/user-attachments/assets/45ded9dc-6744-4a16-ae4f-af25836a5ae8">

1. Wait a few minutes for Spark to finish. Enjoy the playful messages while you wait!

   > 🪧**Note:** Your results will likely be different from the example screenshot shared earlier.

   <img width="350" alt="Playful messages with sparkles decoration" src="https://github.com/user-attachments/assets/46ca83de-22e0-47ca-b54c-e6acf975c7b9">

> [!TIP]
> If you start multiple Spark apps with the same or similar descriptions, you'll get different results. A great way to explore parallel ideas! But be careful, it will also use up your quota quickly too!

<details>
<summary>Having trouble? 🤷</summary><br/>

- If your app doesn't work well on the first try, don't worry! You can resubmit the same prompt to get a different result
- If it seems to be taking a while, that is normal. A well thought out application with lots of requirements can take a long time, even 20 or 30 minutes.

</details>

## App ready?

<img width="100px" align="right" alt="Nyantocat Gif" src="https://octodex.github.com/images/nyantocat.gif">

When your app seems to be ready and working, check the box of your favorite example application, then wait a few moments for the next step to be shared.

- [ ] Paper Plates - 🍽️ Prototype Designer
- [ ] Coffee Shop - ☕️ Secret Menu
- [ ] Lacrosse - 🥍 Stats Tracker
- [ ] My Own - Future Famous App! 🦄 🧙
