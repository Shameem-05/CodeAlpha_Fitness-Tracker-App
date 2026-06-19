# BrainFit Tracker

BrainFit Tracker is a modern Fitness Activity Tracking Application built using HTML, CSS, JavaScript, Firebase Firestore, and Local Storage. It allows users to log workouts, monitor daily fitness goals, visualize progress through dashboards and charts, and manage activity records with real-time cloud synchronization.

## Features

- Log fitness activities and workouts
- Track calories burned
- Track daily step counts
- Track workout duration
- Dashboard with fitness metrics
- Goal progress indicators
- Weekly calorie burn chart
- Activity history management
- Edit existing activity logs
- Delete activity logs
- Firebase Firestore cloud synchronization
- Local Storage fallback mode
- Responsive design for desktop and mobile devices
- Toast notifications for user actions

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Firebase Firestore
- Browser Local Storage

## Installation

### Local Version

1. Download the project file.
2. Save the application as `index.html`.
3. Open the file in a modern web browser.

### Firebase Setup

1. Create a Firebase project.
2. Enable Firestore Database.
3. Copy your Firebase configuration.
4. Replace the existing Firebase configuration in the code.
5. Deploy or run the application.

## Usage

### Log a Fitness Activity

1. Select an activity type.
2. Enter workout duration.
3. Enter calories burned.
4. Optionally enter step count.
5. Click **Save Activity**.

### View Dashboard

The dashboard displays:

- Total Calories Burned
- Total Daily Steps
- Total Workout Time
- Goal Progress Bars

### Weekly Progress

- View weekly calorie burn statistics.
- Compare daily fitness performance.

### Edit Activity

1. Locate an activity in the Activity Logs section.
2. Click **Edit Log**.
3. Modify the details.
4. Save changes.

### Delete Activity

1. Locate an activity record.
2. Click **Delete Log**.
3. Confirm deletion.

## Data Storage

### Firebase Cloud Storage

When Firebase is configured:

- Activity logs are stored in Firestore.
- Data syncs in real time.
- Records remain available across devices.

### Local Storage Fallback

If Firebase is unavailable:

```javascript
brainfit_logs
```

The application automatically stores activity records locally in the browser.

## Dashboard Metrics

### Calories Burned

- Daily goal: 2000 kcal
- Progress bar visualization

### Daily Steps

- Daily goal: 10,000 steps
- Real-time progress tracking

### Workout Time

- Daily goal: 60 minutes
- Visual progress indicator

## Activity Types

Supported fitness activities include:

- Running
- Walking
- Cycling
- Gym Workout
- Swimming
- Other Exercises

## Project Highlights

- Firebase Firestore integration
- Local Storage fallback system
- Real-time database synchronization
- Fitness dashboard analytics
- Weekly progress visualization
- Goal tracking system
- Responsive user interface
- Lightweight single-page application

## Future Improvements

- User Authentication
- Personal Profiles
- Multiple Fitness Goals
- Weight Tracking
- BMI Calculator
- Workout Categories
- Nutrition Tracking
- Exercise Recommendations
- Export Reports
- Dark Mode
- Mobile App Version

## License

This project is free to use for educational and personal purposes.

## Author

Shameem Akthar S
