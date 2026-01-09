# navigation-route-monitoring-system


## Brief Overview of the Solution

This project implements a desktop-based **Integrated Navigation & Route Monitoring System** using **HTML, CSS, and JavaScript**.  
The application simulates a vessel moving along a planned route on a 2D chart-like view. It allows an operator to create, modify, and remove waypoints, observe real-time vessel movement, and view key navigation parameters such as position, speed, heading, distance to the next waypoint, and estimated time of arrival (ETA).

The system is fully client-side, runs locally in a web browser, and is designed with future extensibility in mind.

---

## Steps to Set Up the Environment

No special environment setup is required.

- A modern web browser such as **Google Chrome**, **Mozilla Firefox**, or **Microsoft Edge** is sufficient.
- No backend server, database, or cloud-based service is required.

---

## Instructions to Run and Test the Code

1. Ensure the file `index.html` is present in the project directory.
2. Open the `index.html` file directly in any modern web browser.
3. Use the on-screen controls to interact with the system:
   - **Start / Pause** to control vessel movement
   - **Speed slider** to adjust vessel speed
   - **North-Up / Heading-Up** buttons to switch orientation modes
4. Use mouse interactions on the navigation display:
   - **Left-click** to add a waypoint
   - **Drag a waypoint** to modify its position
   - **Right-click** on a waypoint to remove it
   - **Mouse wheel** to zoom in or out
   - **Drag empty space** to pan the view
5. Observe real-time updates in the information panel showing:
   - Current position
   - Speed and heading
   - Distance to the next waypoint
   - Estimated time of arrival (ETA)

---

## Assumptions, Limitations, and Dependencies

### Assumptions
- The navigation display uses a simple 2D Cartesian coordinate system.
- Vessel movement is simulated and does not represent real-world geographic navigation.

### Limitations
- Route data is not persisted and resets when the page is refreshed.
- The chart display is illustrative and not based on real nautical charts.
- The system supports a single vessel simulation.

### Dependencies
- No external libraries or frameworks are used.
- The application depends only on standard web technologies: **HTML5 Canvas**, **CSS**, and **JavaScript**.
