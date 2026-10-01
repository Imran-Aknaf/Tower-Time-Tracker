# Tower-Time-Tracker

1. Define categories of work 
    - I have 5 categories :
        - Master Thesis — 1h30
        - School Work — 1h30
        - Roblox Dev — 1h30
        - Islam — 30 min
        - Study App — 30 min
2. Display the 5 vertical towers
    - One tower per category
    - Each tower has its own glowing edge color
    - Towers fill vertically according to time worked
    - when working on this tower ⇒ active tower has a subtle animation/glow.
    - when tower finished/completed ⇒ sound + anim of success (aesthetic style)
3. Start / pause a work session
    - Each tower has a play/pause button under it
    - Clicking play starts working on that category
    - Only one category can be active at a time
    - Clicking pause stops the session
4. Display the current timer
    - A single timer is displayed centrally ⇒ track current work session
    - Timer disappears when no session is active (how does a session is stopped ?)
5. Filling of active category
    - While the timer runs, the corresponding tower fills
    - The fill uses a color matching its category
6. Hovering effect
    - Hovering a tower displays the total time worked on that category today :
        - Master Thesis
        - Today: **1h 45m**
        - Overtime: **+15m**
7. Overtime
    - when tower is filled, timer don’t stop, can do overtime
8. Goal completion feedback
    - When a category reaches its target:
        - Play a short aesthetic sound
        - Trigger a small visual animation
        - Mark the category as completed
9. Persistence 
    - Close the application → come back → today's progress is still there.
10. Daily reset
    - At **06:00**, everything is reset
11. Storing 
    - For each work session, store for now :
        - Category
        - Start time
        - End time
        - End time
    - ⇒ will be usefull for next functionnalities