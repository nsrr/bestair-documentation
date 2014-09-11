## 2.8.4 Scoring Desaturation Events

**<u>Automatic Analysis</u>** will mark desaturation events throughout the recording.  These events are generally well marked, but some editing does need to happen for accurate scoring and reporting.

**<u>SpO2 desaturations</u>** are manually marked anywhere a decrease in SpO2% associated with a respiratory event is seen, and has not already been marked by automatic analysis.  This includes any <4% desaturations associated with AASM Alternative and apneas, and all desaturations >4% that are not deemed artifact.  Desaturations that are not associated with a specific respiratory event but were marked by automatic analysis are left in unless caused by artifact.

**<u>SpO2 artifacts</u>** are marked in all areas where the oximetry signal presents unreliable data.  This includes signal drop out, periods of >100% SpO2, periods outside of Lights OFF/ON, and any periods displaying an abnormal or weak Pleth signal (also derived from ppt’s pulse oximeter.)

**<u>Breaking Desaturation Events Into Subevents</u>**  may be unnecessary since an oximeter may be variable over ranges of 1-2% (within their range of accuracy), breaking desaturation events into subevents based on 1-2% changes is too subjective of an assessment and is not encouraged unless there is a marked change in flow or effort associated with these changes in SpO2.

**<u>Editing of Long Desats</u>** (>3 min) is sometimes necessary after automatic analysis.  Auto score will sometimes mark an unusually long desaturation event that desats and resats several times throughout the marked duration.  This happens most often after a breaking breath.  These events should be shortened to the first resat.  In the event that multiple events and desats are marked in association as one desaturation or SpO2 artifact they can be remarked as separate events in the presence of a good pleth signal and effort and/or flow signals corroborating these events.

**<u>Editing Desaturation Start/Stop Times</u>** will often be required during studies with repeat short events, very long events or ppt’s with a long time to between events and their associated desaturations.  These events must have their respiratory event tags checked to see that they have properly associated with their corresponding desat.  If there is no desaturation associated with the event the SpO2 desat event tag may be shortened or extended as needed until Profusion is able to link the event markers.  This will of course cause artifactual start/stop times for these desats, but a reliable AHI has been prioritized over SpO2 desat markers.

**<u>Using Pleth</u>** to determine reliability of oximetry signal requires a baseline period of clean, reliable SpO2 and pleth data somewhere in the recording, preferably before sleep onset.  A weak signal is indicated by the amplitude of the pleth waveform. If the signal is too low, it would affect the accuracy and functioning of the pulse oximeter.  Artifact can also be verified when the morphology of the waveform changes noticeably from the ppt’s baseline period. Any periods with questionable SpO2 readings combined with a noticeably reduced or abnormally shaped pleth signal should be deleted and marked as SpO2 artifact instead.

**<u>Lag Time</u>** is set to a default of 30 seconds between the end of a respiratory event and the nadir or its associated desat.  For ppts with a longer lag time between breathing events this can be set to 45 seconds in order to ensure proper event associations.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/portable-sleep-monitoring/2-08-03-scoring-ecg.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    2.8.3 Scoring ECG
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Portable Sleep Monitoring
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring/2-08-05-signal-quality-psg-reporting.md" class="btn btn-success">
    2.8.5 Signal Quality and PSG Reporting
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
