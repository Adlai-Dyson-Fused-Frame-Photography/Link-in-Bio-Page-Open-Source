## A Free, Highly Customisable Link in Bio Page
#### Created by Adlai Dyson | Fused Frame Photography
Created using purely HTML and Tailwind CSS; see example here

Features:
- Ultra-Easy Global Configuration: No HTML knowledge required! Change colors, shapes, and toggle elements on and off from a single block at the top of the file.
- Animated background pulses (can be toggled off)
- Interactive Top Banner (can be toggled off)
- Modern Glassmorphism effect
- Glow when hovering over cards
- Optimised for both desktop and mobile devices; fast loading.
- Includes a profile picture and call-to-action grid structure.
- How to edit & deploy?

### The best way to start using this template is to:
Select "Use this template" on GitHub.

Edit the index.html file locally (in an app of your choice, Notepad++, CotEditor, VS Code...).

Commit and push.

Publish to a platform of your choice (Cloudflare Pages or GitHub Pages recommended)

or

You can simply download the index.html file from this repo.

Edit it in any basic text editor.

Upload/publish/host on any standard web hosting.

### ⚙️ How to Customise (The Easy Way)

We have made it incredibly easy to customise this page without needing to hunt through hundreds of lines of code. At the very top of the index.html file, you will find a Global Settings Block.

You only need to edit these lines:

1. Toggling Elements On/Off

/* Change 'flex' to 'none' to hide the top banner completely */
--show-banner: flex; 

/* Change 'block' to 'none' to turn off the background glows */
--show-pulses: block; 


2. Changing Shapes (Border Radius)

/* Change sizes: 0px = Square, 16px = Rounded, 9999px = Pill */
--radius-bento: 24px;   /* Changes the main cards */


3. Changing Colors

colors: {
  brand: {
    primary: '#94fdf8',   /* Type your main brand hex code here */
    secondary: '#3b82f6', /* Type your secondary accent color */
    bg: '#020617',        /* Change the background color */
  }
}


### Icons & Links:
To change specific links, text, and icons, simply scroll down into the HTML block and look for the clear <!-- COMMENTS --> we have left for you. The icons used are from a FontAwesome Kit. You will need to update the <script> tag in the header to your specific free kit to ensure icons load reliably.

### License
This project is Open Source and available under license for personal and commerical use. The only ask I have is to credit Adlai Dyson | Fused Frame Photography either in the source code or repo. View the full license in this repo.