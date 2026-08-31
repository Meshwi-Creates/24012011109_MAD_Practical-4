# Practical-4: Android Alarm Application

## Aim
Create an Android Alarm Application using **Service** and **BroadcastReceiver**.

## Description
This practical demonstrates how to create an alarm application in Android using:

- Android Service
- BroadcastReceiver
- AlarmManager
- TimePicker
- Notification
- `setExactAndAllowWhileIdle()`

The application allows the user to set an alarm at a selected time and cancel the alarm when required.

## Features

- Create an alarm by selecting a specific time.
- Display the selected alarm time.
- Trigger the alarm using `AlarmManager`.
- Use `BroadcastReceiver` to receive the alarm event.
- Use a Service to handle the alarm.
- Cancel the active alarm.
- Support exact alarm scheduling.

## Technologies Used

- **Language:** Kotlin
- **IDE:** Android Studio
- **Platform:** Android
- **UI:** XML
- **Components:** Service, BroadcastReceiver, AlarmManager, TimePicker

## Application Screens

### 1. Create Alarm

The user can select a time and create an alarm.

### 2. Time Picker

The user can select the required hour and minute using the Android TimePicker.

### 3. Alarm Created

After creating an alarm, the selected alarm time is displayed on the screen.

### 4. Cancel Alarm

The user can cancel the created alarm using the **Cancel Alarm** button.

## Output

### Application Screenshots

![Alarm Application Output](output.png)

The above screenshots show:

1. Alarm application home screen
2. Time picker for selecting alarm time
3. Alarm created successfully
4. Alarm cancellation option
5. Dark mode output

## Conclusion

Thus, an Android Alarm Application was successfully created using **Service, BroadcastReceiver, and AlarmManager** in Kotlin.
