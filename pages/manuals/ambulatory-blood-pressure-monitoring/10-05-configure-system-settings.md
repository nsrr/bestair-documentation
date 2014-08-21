## 10.5 Configure System Settings

### 10.5.1 System Settings

1. Start the Client application.
2. Select **View/Change System Settings** on the Main Menu.

### 10.5.2 Report Form Settings

The Report Form tab contains settings for printed reports.

1. Check **Use Custom Report**.
2. Check **Cover Page**, **Tabular Raw Data**, **Edit Summary**, and **Raw Data Graph**
3. Select **OK**

### 10.5.3 Statistics Settings

The Statistics tab contains settings for data analysis limits.

* 1. Click on the **New/Edit** to open the Statistical Settings dialog box
* 2. Type “BestAIR” in the Item text box
* 3. Select **Add**
* 4. Click **Close**
* 5. Define the edit limits for data analysis

| Parameters     | Limit |
|:--------------:|:-----:|
| Systolic Max   | 260   |
| Systolic Min   | 60    |
| Diastolic Max  | 200   |
| Diastolic Min  | 30    |
| MAP Max        | 230   |
| MAP Min        | 40    |
| PP Max         | 150   |
| PP Min         | 20    |
| Heart Rate Max | 200   |
| Heart Rate Min | 20    |

* 6. Define the statistical period boundaries.

|Parameters                                 | Boundary |
|:-----------------------------------------:|:--------:|
| Start Hour                                | 7        |
| Expected Average Systolic Blood Pressure  | 120      |
| Expected Average Diastolic Blood Pressure | 80       |
| Do not check Sleep Box.                   |          |
| Start Hour                                | 23       |
| Expected Average Systolic Blood Pressure  | 120      |
| Expected Average Diastolic Blood Pressure | 80       |
| Check Sleep Box.                          |          |

* 7. Select **OK** to save settings.

### 10.5.4 Initializing Settings

**The MONITOR TAB contains setting for initializing the ABP monitor.**

* 1. Create a new monitor initialization configuration.

 * Select **New/Edit**.
 * Type “BestAIR” into the Item text box.
 * Select **Add**.
 * Select **Close**.

* 2. Set the defaults.

 * Do not check any of the boxes in the upper half.
 * Check **24-hour** for the Monitor Clock Display.

* 3. Set the Wake and Sleep Configuration defaults.

| Parameters                 | Defaults |
|:--------------------------:|:--------:|
| Wake Periods               |          |
| Start Hour                 | 7        |
| Readings/Hour              | 3        |
| Check the Tone Box.        |          |
| Sleep Periods              |          |
| Start Hour                 | 23       |
| Readings/Hour              | 2        |
| Do not check the Tone Box. |          |

4.  Select **OK** to save settings.

**The SYSTEM TAB contains language, password, and time display settings.**

* 5.  Set the defaults.

 * Set the language to **English**.
 * Select the **24 hour** time display option.

* 6.  Select **OK** to save settings.

### 10.5.5 Monitor Initialization

* 1. Connect the ABP monitor to the ABP Report Management System using the monitor interface cable.
* 2. Start the Client application to display the Main Menu.
* 3. Select **Initialize Monitor** to start the Monitor.
* 4. Enter the appropriate participant information under Patient Demographic Information.

| Parameter     | Information    |
| :------------:|:--------------:|
| Patient ID    | Participant ID |
| Last Name     | Acrostic       |
| First Name    | 0, 6, or 12    |
| Date of Birth | Default        |
| Race          | Unspecified    |
| Gender        | Unspecified    |

* 5. Select **Indications**.

 * Select **New/Edit**.
 * Type “BestAIR.”

* 6. Select **Data Recorder Serial Number**.

 * Select **New/Edit**.
 * Type serial number found on the back of the Spacelab monitor.

* 7. Add the serial number for each monitor. In the future, open the drop down menu and select the correct Spacelab Monitor.
* 8. Double check the configuration settings.
* 9. Make sure that the correct USB is selected (USB3). If you are in XP mode, go to the top of the screen and click **Attach** for the USB chord that you have connected to the computer.
* 10. Click **Next**.
* 11. Make sure the time and date on your computer is correct.
* 12. Select **Initialize Monitor** to complete the initialization process.
* 13. Select **Finish** to return to the Main Menu when the system has finished initializing the monitor.
* 14. Monitor is ready for participant to wear.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/ambulatory-blood-pressure-monitoring/10-04-subject-device-accountability-log.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    10.4 Subject Device Accountability Log
  </a>

  <a href=":pages_path:/manuals/ambulatory-blood-pressure-monitoring" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    24-Hour Ambulatory Blood Pressure Monitoring
  </a>

  <a href=":pages_path:/manuals/ambulatory-blood-pressure-monitoring/10-06-cuff-size-determination.md" class="btn btn-success">
    10.6 Cuff Size Determination
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
