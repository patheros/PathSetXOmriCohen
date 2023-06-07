
# Path Set X Omri Cohen - Change Log - Premium

## v2.0.2
**Hyphae**
* Audio Inputs now sum polyphonic cables https://github.com/patheros/PathSetXOmriCohen/issues/3
* Fixing clicks on Pitch Shifter section https://github.com/patheros/PathSetXOmriCohen/issues/2
* Added 10hz to 20,000hz filter to the output of the Pitch Shifter section

**Panther Cap**
* Fixed bug with CV input for Overlap. Previous 10v only increases overlap by 1 step, now it increases it by the full range.
* Trigger inputs now sum any Polyphonic channels https://github.com/patheros/PathSetXOmriCohen/issues/5
* Removed Chorus like effect that can happen when pitch knob is returned to 0 https://github.com/patheros/PathSetXOmriCohen/issues/11
* Added right click menu to select what is randomized when Rnd is triggered. https://github.com/patheros/PathSetXOmriCohen/issues/9
* Rnd can now also randomzie Time, Pitch, Size and Overlap but these are off by default. https://github.com/patheros/PathSetXOmriCohen/issues/9
* Removed click sounds when changing Overlap https://github.com/patheros/PathSetXOmriCohen/issues/4

**Truffles**
* Clear ALL context menu now correctly clears all samples. Previously it only cleared the current sample. https://github.com/patheros/PathSetXOmriCohen/issues/12