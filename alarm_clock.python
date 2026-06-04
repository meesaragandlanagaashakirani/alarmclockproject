# alarm_clock.py

import time
from datetime import datetime
import winsound  # Works on Windows

alarm_time = input("Enter alarm time (HH:MM:SS): ")

print(f"Alarm set for {alarm_time}")

while True:
    current_time = datetime.now().strftime("%H:%M:%S")

    if current_time == alarm_time:
        print("⏰ Wake up! Alarm ringing...")
        winsound.Beep(2500, 3000)  # Frequency, Duration (ms)
        break

    time.sleep(1)
