## 8.5 PWA Measurement Procedure

### 8.5.1 Enter New Patient

Before creating a new patient entry, please check that the patient does not already exist in the database, as separate patient entries cannot be merged.

* 1. Enter a new patient.
* 2. Select **Patient** button or press **F2** to open Patient Screen
* 3. Select **New** button
* 4. Enter patient details

 * First Name:  Name Code
 * Last Name: Participant ID

* 5.**Update** button.

### 8.5.2 Take a PWA Measurement

* 6. In Patient Screen, select **PWA** by clicking on the arrow on the selection box (located next to the Analysis button).
* 7. Select **Study** button or press **F3** to open Study Screen.
* 8. Enter study details.

### 8.5.3 Radial Artery Measurements

* 9. Select the **Radial** check box
* 10. Enter the diastolic and systolic blood pressure values that have been obtained from cuff sphygmomanometer or automatic blood pressure device.
* 11. Select **Capture Data**

### 8.5.4 Tonometer Placement

* 12. Place on the wrist, where the strongest radial pulse can be palpated.
* 13. Make sure the probe is placed normal to the plane of the artery (adjustments to the angle may need to be made) and adjust position until a strong, accurate, and reproducible waveform is made and displayed in the Signal Detail window.

This signal will be automatically rescaled and zoomed to fit the waveform within the signal detail window every 5 seconds.

### 8.5.5 Capturing the Waveforms

* 14. Select **OK** at the top of the screen or press the spacebar when you get a good reading.

 * There must be a minimum of 12 seconds of signal for the data to be captured.  The last 2 seconds of waveforms will be deleted, allowing sufficient time to remove the tonometer from the wrist to activate the capture of data.
 * The software analyzes the last 10 seconds of waveform.  The 10 second window of waveforms to be captured is displayed in the Signal for Processing Area immediately below the Signal Detail window in the capture screen.

### 8.5.6 Examine the Report for Quality Control

The Report Screen will be automatically displayed after data capture has been completed. Before proceeding with the interpretation of results, it is important to check the quality control to ensure that your measurement has been recorded with sufficient quality.

The Quality Indices and visual check of the over-layered waveforms should be used together when making a decision on whether to accept the measurement. Measurements that are of an unacceptable quality should be repeated.

When the figures appear in green or white, they are within the acceptable, defined limits set using the Configuration Settings.  When they appear in red, they are outside these limits.

* **Average Pulse Height** – average height of the pulses measured.
* **Pulse Height Variation** – amount of variation present in the height of the pulses measured
* **Diastolic Variation** – amount of variation present in the diastolic point of the pulse wave and indicates how constant the baseline pressure was during the measurement.
* **Operator Index** – number calculated on weighting equation using the 3 indices above.

The graph displaying the overlay of captured individual waveforms should be examined to ensure there was as little variability as possible.

As a general guide only:

| Parameter                  | Limits                              |
|:--------------------------:|:-----------------------------------:|
| **Average Pulse Height**   | > 80                                |
| **Pulse Height Variation** | < 5                                 |
| **Diastolic Variation**    | < 5                                 |
| **Operator Index**         | > 80% acceptable, 75-80% borderline |
| **Shape Variation**        | < 4%                                |

If more than one reading on a patient is performed, the studies are listed chronologically in the Study Time window and the most recent report will be at the bottom of the list.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/peripheral-arterial-tonometry/8-04-equipment.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    8.4 Equipment
  </a>

  <a href=":pages_path:/manuals/blood-collection-processing" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Peripheral Arterial Tonometry
  </a>

  <a href=":pages_path:/manuals/peripheral-arterial-tonometry/8-06-pwv-measurement-procedure.md" class="btn btn-success">
    8.6 PWV Measurement Procedure
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
