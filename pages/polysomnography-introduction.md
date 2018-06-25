# Polysomnography introduction

Sleep studies took place either through normal clinical channels for those recruited from sleep clinics (level 1 polysomnography or level 3 home sleep tests), or administered by the investigators for those recruited from cardiology or diabetes clinics (using either Embletta Gold or Embletta X100, Embla). All studies were scored by a single registered polysomnographic technologist using the American Academy of Sleep Medicine (AASM) alternative hypopnea criteria when arousal data were available, or the AASM recommended criteria when electroencephalographic data were not recorded.

Notes:

- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/) is available for 152 randomized participants at baseline and 93 at followup. Each recording has a signal file (.EDF) and event scoring (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/tools/edf-editor-and-translator) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://sleepdata.org/community/tools/nsrr-edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Known issues

- No known issues yet

## History / changelog

*June 2018*
- Polysomnography data uploaded to sleepdata.org

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
