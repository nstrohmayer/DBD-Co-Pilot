# DBD Co-Pilot
DBD Co-Pilot: Your Dead by Daylight personalized AI Buddy. Craft, manage, and conquer with AI optimization, Steam integration, and analytics for unmatched gameplay mastery


## Mission Statement:
DBD Co-Pilot aims to empower both new and veteran Dead by Daylight players by providing an intuitive, AI-driven loadout management tool integrated with Steam achievements and comprehensive match analytics. Our mission is to assist players in enhancing their gaming experience by offering strategic insights and streamlined tools.


## Highlights
### Steam Integration:
- Utilizing Steamworks API for seamless integration, enabling retrieval of achievements and player statistics directly into the application.
- See your game statistics in various customizable dashboards and share achievements or funny pictures/clips with friends.


### AI-driven Bloodnet Prioritization:
- Tell the AI which add-ons to prioritize or let it learn from your builds (add-on and offering usage).
- Decision to implement machine learning algorithms for smart Bloodnet spending, enhancing user experience and optimizing resource allocation.


### Match Result Analytics:
- Data extraction from screenshots of the after match screen. Providing statistics of commonly used perks on both sides and their effect on "winning". Analysis and visualization through Pandas and Matplotlib to derive insights, providing users with comprehensive match statistics and trends.


## Tasks & Epics
1. Loadout Creation
2. Loadout Management
3. Winstreak Counter
4. Automatic Loadout Selector
5. Loadout Sharing (Future Enhancement)
6. Material Design & UI Consistency
7. Personalized Bloodnet Priorities for Smart Spending (AI-Driven)
8. Match Result Analytics
9. Steam Achievement Integration & Progress Tracker


## Technical Decisions Summary:

1. **Python**: 
   - *Purpose*: Chosen for simplicity, extensive libraries, and readability.
   - *Use*: Rapid development and seamless integration with other tools.

2. **PyAutoGUI**:
   - *Purpose*: Controls mouse movements and keyboard inputs programmatically.
   - *Use Cases*:
     - Simulating mouse clicks and movements within the game.
     - Emulating keyboard inputs for in-game interactions.

3. **OpenCV (Open Source Computer Vision Library)**:
   - *Purpose*: Provides tools for image recognition and manipulation.
   - *Use Cases*:
     - Image detection on the game screen.
     - Pattern recognition for identifying game elements.
     - Processing screenshots/live feed for decision-making.

Combining Python for scripting, PyAutoGUI for user input control, and OpenCV for image recognition offers a versatile toolkit for automating game interactions, from simulating user actions to recognizing and responding to in-game visual elements.


## Feature Requests & UI Assistance

We value your feedback and ideas to enhance DBD Co-Pilot! If you have feature requests, suggestions, or need assistance with UI development or design, there are two ways to reach out:

### Feature Requests:
Feel free to open an issue on our GitHub repository detailing your feature request or suggestion. We appreciate any insights you have to improve Loadout Legends. Your contributions help us tailor the tool to better suit your needs and preferences.

[Open an Issue](https://github.com/nstrohmayer/DBD-Co-Pilot/issues)

### UI Development/Design Assistance:
If you need help or advice regarding UI development or design aspects, whether it's about implementing specific features or aligning with Material Design principles, don't hesitate to reach out via email.

**Email:** noah.han.aio@gmail.com

We welcome your input and look forward to collaborating to make DBD Co-Pilot the ultimate companion for Dead by Daylight players!
