## 3.8.2 Scoring Respiratory Events

Once Lights ON/OFF, Sleep Onset/Offset, Sleep Periods, and Wake Periods have been marked, automatic analysis can be run.  Profusion’s automatic analysis is setup to run and mark SpO2 desaturations, respiratory events and create an offline summary.  After automatic analysis manual scoring is started at Lights OUT.  The scorer will identify the following categories of discrete breathing events: obstructive apneas, central apneas and AASM Recommended and AASM Alternative Hypopneas.

The primary signal for scoring respiratory events is Nasal Pressure. If Nasal Pressure signal is unreliable, SUM should be used. If neither signal is reliable, events may be scored off of either Abdominal or Thoracic bands, but preferably the Thoracic band.

**<u>Obstructive Apneas</u>** are identified when the amplitude (peak to trough) of the thermistor signal is reduced by >90% for > 10 seconds and does not require a minimum desaturation criterion.  There is no requirement that the length of this flattening be any percentage of the overall event.  It will be classified as an obstructive event unless it meets the criteria for a central apnea (absence of effort on both bands).  Baseline breathing is defined as a period of regular breathing with stable oxygen levels. Without a reliable thermistor signal, the event will default to either an AASM Recommended or AASM Alternative Hypopnea.

**<u>Central Apnea</u>** events are scored if no displacement is noted on both thoracic and abdominal channels, a flat thermistor flow signal and a minimum duration of >10 seconds. There is no desaturation criterion.  Central Apneas will be scored when all signals are “flat” unless signal deflection is due to cardiogenic artifact. When the thermistor flow signal is absent or unreliable (“choppy”), then apneic events cannot be reliably scored.

**<u>AASM Hypopneas</u>** will be identified if ≥30% reduction of amplitude is visualized primarily in the nasal pressure signal or the respiratory SUM channel for a duration of at least 10 seconds associated with a decrease in SpO2 of >4%.  If the SUM and nasal pressure channels are not available, one of the effort bands may be used as an alternative for scoring.

**<u>AASM Alternative Hypopneas</u>** will be identified by the same criteria as AASM Recommended, with the exception that there must be ≥50% reduction of amplitude during at least 75% of the event. Identification of an AASM Alternative event does not require a minimum desaturation.

**<u>Event Exclusion</u>** applies to events that are post movement or post sigh (>150% of baseline effort) are not scored unless they are part of a clear series or events sharing similar morphology.

**<u>Duration criteria</u>** is determined by marking a respiratory event on any signal from the end of the last “normal”, baseline breath to the beginning of the first breath that exceeds the amplitude of the first reduced breath. Duration is based on a “trough to trough” marking lasting at least 10 seconds. When marking an apnea, the duration of the event should also include any reduced breaths on either side of the period of flatness.  Contiguous respiratory events that have a single respiratory effort in the middle of two periods of absent efforts, each <6 seconds, should be combined into a single event. Unless the events are in a series of three or more, there must be at least two baseline breaths between respiratory events.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/portable-sleep-monitoring/3-08-01-scoring-lights-sleep-wake.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    3.8.1 Scoring Lights and Sleep/Wake Periods
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Portable Sleep Monitoring
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring/3-08-03-scoring-ecg.md" class="btn btn-success">
    3.8.3 Scoring ECG
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
