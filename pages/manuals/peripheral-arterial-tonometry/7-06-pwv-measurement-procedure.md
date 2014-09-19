## 7.6 PWV Measurement Procedure

### 7.6.1 Enter New Patient

Before creating a new patient entry, please check that the patient does not already exist in the database, as separate patient entries cannot be merged.

* 1. Enter a new patient.
* 2. Select **Patient** button or press **F2** to open Patient Screen
* 3. Select **New** button
* 4. Enter patient details.

 * **First Name:** Name Code
 * **Last Name:** The Participant ID

* 5. Select **Update** button.

### 7.6.2 Take a PWV Measurement

* 6. In Patient Screen, select **PWV** by clicking on the arrow on the selection box (located next to the Analysis button).
* 7. Select **Study** button or press **F3** to open Study Screen.
* 7. Enter study details:

 * Select the box that corresponds to the site from where the measurement is to be taken for both Site A (first measurement) and Site B (second measurement).
 * The Capture Time is set to a default of 10 seconds for both the Site A and B measurement.  Alternative times can be selected for either or both sites if required.
 * The PWV algorithm has a default setting of Intersecting tangents.  To select a different algorithm, click in the circle next to the corresponding algorithm of choice.

### 7.6.3 Carotid Artery Measurement

* 9. When the carotid is selected as the first site, enter the systolic and diastolic blood pressure values that have been obtained from the cuff sphygmomanometer or automatic blood pressure device.

 * The Systolic Pressure can be obtained from the PWA report if this has been measured immediately prior to PWV measurement.
 * **Carotid – Femoral and Carotid – Radial measurements:**
  Distances directly between each artery location and the supra-sternal notch are entered in the distal and proximal boxes.
 * For the instance of Femoral – Dorsalis Pedis (distal box), the actual measurement between the sites can be entered directly into the PWV box.

### 7.6.4 Tonometer Placement

#### 7.6.4.1 Carotid Measurement

* 10. Have the participant lie on the bed with head tilted slightly to the back and to one side (either right or left).  This is best achieved without a pillow.
* 11. Stand either behind the patient’s head or to one side.
* 12. Feel for the position for the strongest pulse and place the tonometer directly on the top of the skin at this point.

A pillow may be placed across the shoulder of the patient to allow the operator to rest their forearm to ensure that the tonometer and wrist remain steady during measurement.

#### 7.6.4.2 Femoral Measurement

* 13. Have the participant lie on the bed with the thigh flexed at the hip joint, moved away from the midline of the body and rotated away from the body.
* 14. Press directly backward at a point that is midway between the anterior superior iliac spine and the front of the pubic bone.

### 7.6.5 ECG Lead Placement

* 15. Make sure skin is properly prepared (hair removed at electrode site and skin cleaned with alcohol wipe) and that electrodes are positioned correctly.
* 16. Position ECG leads in a Lead II Configuration as shown below.

_IMAGE_

* 17. Select Data Capture

### 7.6.6 Capturing the waveforms

Once the ECG trace is shown along the screen and is steady, proceed as follows:

* 17. Place the tonometer at Site A location and adjust the position until a strong, accurate, and reproducible waveform is made and displayed in the Signal Detail window. **Ensure that the R-wave is the most clear, prominent feature of the ECG signal.**

 * The signal will be automatically re-scaled and zoomed to fit the waveform within the signal detail window every 5 seconds.

* 19. Select **OK** at the top of the screen or press the spacebar, when you get a good reading.

 * There must be a minimum of 12 seconds of signal for the data to be captured.  The last 2 seconds of waveforms will be deleted, allowing sufficient time to remove the tonometer from the wrist to activate the capture of data.
 * The software analyzes the last 10 seconds of waveform.  The 10 second window of waveforms to be captured is displayed in the Signal for Processing Area immediately below the Signal Detail window in the capture screen.

* 20. Confirm that the signals have been captured successfully. If you wish to take the reading again, select **No** and repeat the reading at Site A.
* 21. Select **OK** and proceed to site B.
* 22. Place the tonometer at Site B and proceed with the capture when you have obtained a signal of satisfactory quality.
* 23. Confirm that the signals have been captured successfully.
* 24. Select **OK** and proceed to report.

### 7.6.7 Examine the report for quality control

The Report Screen will be automatically displayed after data capture has been completed. Before proceeding with the interpretation of results, it is important to check the quality control to ensure that the measurement has been recorded with sufficient quality.

The Quality Control parameters provide a guide to quality of the reading rather than provide a cut-off value to accept or reject data.  Measurements that are of an unacceptable quality should be repeated.

* It is important that the foot of the wave is easily identified.  The preferred algorithm uses this part of the waveform for locating the onset points used in calculating the time differences between the ECG and tonometer waveforms at each site.
* The software requires a minimum of 3 pairs of data to calculate the result.  If it rejects too many pairs with less than 3 left, the software will not calculate a PWV reading.
* The SD (ms) in the statistical table should be below 6% of the mean time.  If this is above 6% the number will appear in red.
* PTT SD (Pulse Transit Time Standard Deviation) should be <10%.



<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/peripheral-arterial-tonometry/7-05-pwa-measurement-procedure.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    7.5 PWA Measurement Procedure
  </a>

  <a href=":pages_path:/manuals/blood-collection-processing" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Peripheral Arterial Tonometry
  </a>
