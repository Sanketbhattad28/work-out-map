# work-out-map

![image](https://github.com/user-attachments/assets/49e84c9a-1b23-4071-9840-96c20e5bd4a8)

This application renders workouts based on the user's location.

A workout that could be chosen:

- Running
- Cycling

The app gets the current location from the browser and passes those cords into a library which renders a map on the position where the user can then initialize workouts by simple click events.

As soon as a workout gets submitted mapty will process the user data makes several ajax calls in the background and show the user the corresponding information for

- the weather
- the location
- calculations (pace, speed)

The UI can be manipulated from the user by:

- Editing workouts
- Deleting workouts
- Deleting all workouts
- Sorting workouts
- Navigating the map on the corresponding workouts on the map
- Overview of all workouts
