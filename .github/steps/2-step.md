## Step 2: Revise and Edit Your App

<img height="150px" align="right" src="https://octodex.github.com/images/mcefeeline.jpg">

After playing with your new app, it probably didn't take long to realize you forgot something. Or... come up with some fun new ideas to make the app even better!

Here's the good news. You can continue to improve your app just by talking to Spark, again with normal language (and that niche work/hobby jargon you taught Spark).

### 📖 Theory: Continuous Refinement

One of Spark's most powerful features is the ability to continuously submit changes to further enhance your project.

Unlike traditional software, you don't have to submit lots of "feature requests" and "bug reports" then live with the current version for another 6 months until another release happens! (and hope they fixed your problem 😒)

After just a few chats on day one, you might have something really useful, maybe even awesome! Just imagine after 6 months! 🧑‍🚀

There are 2 (and a half) primary ways to communicate ideas to Spark:

1. **Left Chat panel**: Similar to our initial application description, just describe the desired change(s).

2. **Element Selector**: Select a feature in the live preview and use the floating chat box to focus your request to a particular area.

&nbsp;&nbsp; 2.5. **Share an Image**: In either of the above chats, attach image of a mock up, or even a hand sketch, to clarify your description.

### ⌨️ Activity: Add a new feature

1. Ensure you are at the live preview screen.

1. Below are some example ideas you can ask Spark to implement. Alternately, you can make your own!.

   <details>
   <summary>Paper Plates - 🍽️ Prototype Designer</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=8250df&color=f1e5ff)

   ```prompt
   Add support for different shaped plates.
   Add a configuration option in the side panel to pick shape: Round, Triangle, Square, Pentagon, Hexagon, Octagon.
   For all options except round, add a configuration option in the side panel to set "Corner Radius". default: 0.5 inches
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=179b9b&color=c7f5ef)

   📎 Attachment: [Example Paper Plate Drawing](https://github.com/user-attachments/assets/8fbc27db-1dc8-4ef6-a85d-7e732d7f88f1)

   ```prompt
   I've attached an example drawing.
   Several dimensions are not shown on the drawings.
   Some dimensions are in the incorrect locations.
   Please change the top view and front section view to use the same dimensions, locations, and fonts as the example drawing.
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=bc4c00&color=ffe7d1)

   ```prompt
   1. Add a 3D viewer that renders the plate in a semi-realistic way.

      - It should be a solid model, not wireframe.
      - The plate should be floating in space so it can be easily rotated and viewed from different angles.

   2. Add mouse controls to pan, zoom, and rotate.

      - Rotate is controlled by clicking and dragging. Add a toggle to invert rotation.
      - Pan is controlled by holding ctrl (windows) / cmd (mac) then clicking and dragging.
      - Zoom is controlled by holding shift then clicking and dragging.
      - Add a toggle to invert

   3. Add a toggle to show a cross section view.
   ```

   </details>

   <details>
   <summary>Coffee Shop - ☕️ Secret Menu</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Ingredients Filter
   The available ingredients for the secret menu are constantly changing.
   Add an area in the side panel that shows all ingredients with checkboxes.
   If something is unchecked, those items in the menu are dimmed and the word "unavailable" is added.
   ```

   </details>

   <details>
   <summary>Lacrosse - 🥍 Stats Tracker</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Player Notes - Add the below fields for additional tracking.

   - Add a plain text field under each player for capturing notes.
   - Add a "Sparkles" button counter to give a player kudos. Increment it the same way as the other stats.
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=179b9b&color=c7f5ef)

   ```prompt
   Opponent Tracking - Add support for also tracking the opponent.

   - Add an area in the "Setup" page for also managing the opponents team members.
   - Add an option to set a color for our team. Also show this in the config panel.
   - Add an option to set a color for the opponent team. Also show this in the config panel.
   - Modify the "Track Stats" page to make the player cards the matching colors.
   - Add a setting in the config panel to filter the "Track Stats" page. (Us, Opponent, Both). This way different people can track each team.
   ```

   </details>

1. Copy your favorite feature into the left chat panel. Click the **Submit** button.

1. Monitor the left chat panel for live feedback. Wait for Spark to finish.

   <img width="350" alt="Spark chat with live progress information" src="https://github.com/user-attachments/assets/652bf9b3-9e22-4575-8980-e8841f3dece5">

1. (optional) Try testing the new features in the live preview. If they don't work like you expect, consider submitting followup feedback.

> [!NOTE]
> Some file-based features like "Download PDF" don't currently work in the live preview, but do work after publishing.

### ⌨️ Activity: Target a specific change

We've realized the side configuration panel in our app is taking up a lot of screen space. Let's have Spark fix that for us.

1. Above the live preview, find the toolbar in the top right. Click the **Select element to edit** button.

   <img width="350" alt="Select element button" src="https://github.com/user-attachments/assets/9c9dbf82-4cc8-48e8-82dc-eda14d7e6e3f">

1. Hover over the right side panel. Click on it to highlight it. A chat box will appear.

   <img width="350" alt="Select element button" src="https://github.com/user-attachments/assets/2f5a3d9a-30d1-4c8b-aa01-b208c63b65ec">

1. Enter the following text to ask Spark to make the side panel automatically hide when it isn't used:

   > ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=8250df&color=f1e5ff)
   >
   > ```prompt
   > This takes up a lot of room.
   > Can you do something to make it automatically hide and show?
   > ```

   <img width="350" alt="Floating chat box" src="https://github.com/user-attachments/assets/c6141af3-cd8c-4924-969c-a2992218dc4d">

1. Test the new functionality in the live preview to see if it operates as desired.

### ⌨️ Activity: Undo and try again

Sometimes we don't like the results, or just want to try again with a better description.

1. In the left chat panel, notice there is a vertical timeline. One entry for each requested change.

1. Find the previous task, hover over it, and click the **Restore** button.

   <img width="350" alt="Restore button" src="https://github.com/user-attachments/assets/7fadae34-2155-4fcc-89b1-fdff9d4891bd">

1. Wait a moment for the live preview to update.

1. Let's try updating the "hide panel" feature again with a more specific description. In the left chat panel, submit the below request:

> ![Static Badge](https://img.shields.io/badge/✨-Prompt-text?style=flat-square&labelColor=a830e8&color=f8e5ff)
>
> ```prompt
> The side panel takes up a lot of room.
> Can you do something to make it automatically hide and show?
> I don't want to have to click anything.
> Just show when I move my mouse near the side.
> ```

<details>
<summary>Having trouble? 🤷</summary><br/>

- Updates can take a while, especially if it is a busy time.

</details>

## Done playing?

<img width="150px" align="right" alt="Skatetocat" src="https://octodex.github.com/images/skatetocat.png">

When the app is ready, pick your favorite Spark feature, then wait a few moments for the next step to be shared.

- [ ] No technical jargon, or at least less. 🙇
- [ ] The funny messages. 😎
- [ ] The perfect length wait times so I can grab more coffee. ☕️
- [ ] Yeah... not convinced yet. 🤷
