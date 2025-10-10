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

- It should always be visible for easy access to change settings.
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
- Hometown

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

## Future Ideas

1. Player Notes - Add the below fields for additional tracking.

   - Add a plain text field under each player for capturing notes.
   - Add a "Sparkles" button counter to give a player kudos. Increment it the same way as the other stats.

1. Opponent Tracking - Add support for also tracking the opponent.

   - Add an area in the "Setup" page for also managing the opponents team members.
   - Add an option to set a color for our team. Also show this in the config panel.
   - Add an option to set a color for the opponent team. Also show this in the config panel.
   - Modify the "Track Stats" page to make the player cards the matching colors.
   - Add a setting in the config panel to filter the "Track Stats" page. (Us, Opponent, Both). This way different people can track each team.

1. Add Team Logo - I've uploaded the following asset. Please add it to the page title, report page, and PDF downloads.

1. Easy Summary - Use AI to review all stats and provide a summary of the game.

1. Tournament/Season Support - Add support for storing and viewing stats across several games.

1. Detailed Player View - Add a view for showing the entire player's history.

   There are 3 tabs:

   - Entire history
   - History for current season.
   - History against current team.

1. Quick Add - Add a free text box for quickly entering in new data. The coach can verbally describe the player and statistics that need associated.

1. Practice Details - ???

## Followup prompts

- Let's also change the player name to be divided by first name and last name for more clarity and sorting

- If goal is increased automatically increase shot
