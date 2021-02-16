Calibu
======
Calibration library. Calibu is a framework to represent cameras and compute
camera geometry and photometric model parameters. It may be used in conjunction
with a calibration application e.g. vicalib (github.com/arpg/vicalib) and pcalib
(github.com/aprg/pcalib) to calibrate cameras.

SJJ NOTES
---  
Follow the Calibu instructions below. However, please use the most recent versions
of Pangolin (https://github.com/stevenlovegrove/Pangolin) and Sophus
(https://github.com/strasdat/Sophus).

Example execution:

./applications/calib/calibgrid convert:[fmt=GRAY8]//v4l:///dev/video0

Installation
---
To install calibu, please follow the installation instructions at:
https://github.com/arpg/Documentation/tree/master/Installation up to the
"Calibu" step.

Geometric calibration
---
To calibrate cameras, please follow the installation instructions above up to
the "vicalib" step. Then, follow the instructions at:
https://github.com/arpg/Documentation/tree/master/Calibration to learn how to
use vicalib.

Photometric calibration
---
To calibrate cameras, please follow the installation instructions above up to
the "pcalib" step. Then, follow the instructions at:
https://github.com/arpg/Documentation/tree/master/Calibration to learn how to
use pcalib.

