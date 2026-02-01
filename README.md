 # THE FINALS // Weapons Tracker

 A comprehensive, interactive dashboard for visualizing weapon statistics, Time-to-Kill (TTK), and meta rankings for The Finals.

 Live: https://alphonsvds.github.io/thefinals-weapon-tracker/

 ## Features

 Interactive Dashboard: View detailed stats for every weapon, including Damage, Fire Rate, DPS, Reload Speed, and Mag Size.

 TTK Analysis: Automatically calculates and ranks weapons by "Fastest Time-to-Kill" against Light, Medium, and Heavy builds.

 Meta Tier List: Dynamic S/A/B/C/D tier list based on TTK performance.

 Damage Profiles: Visualizes Body vs. Headshot damage and effective range drop-off.

 Version Control: Built-in support for different patch versions (currently defaults to v8.3.0).

 Custom Data Upload: Drag & Drop support for Zafferman's weapon data spreadsheets (.xlsx or .csv) to update stats instantly.

 ## Usage

 This project is built as a Single File Application.

 Simply download the_finals_tracker.html.

 Open the file in any modern web browser (Chrome, Edge, Firefox).

 No server, Node.js, or installation required.

 ## Updating Data

 Default: The tracker comes pre-loaded with Patch 8.3.0 data.

 Manual Update: To load newer data:

 Click the "Patch Version" dropdown in the top right.

 Select "Admin: Upload New Data".

 Drag and drop the updated "Summary" spreadsheet/CSV into the upload zone.

 ## Credits

 Data Source: Zafferman's Weapon Master Sheet

 Tech Stack: React, Tailwind CSS, SheetJS (XLSX).