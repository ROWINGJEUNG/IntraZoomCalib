# Intraoperative Zoom Lens Calibration for High Magnification Surgical Microscope
Pseudo-code to calibrate the high-magnification zoom lens with a single pattern image

<img width="605" alt="Fig1" src="https://user-images.githubusercontent.com/31835663/213969949-1e8205a5-72c8-4851-a6fc-2e6c9c6e5354.PNG">

To optimize intrinsic and hand-eye parameters in 'Intraoperative estimation', the 'Preoperative calculation' should be done beforehand.

In 'Preoperative calculation, first, calibrate the lowest three magnification levels of the zoom lens with Zhang's calibration method.
Then use first-order least square methods to determine the relationship between hand-eye parameters and focal length.
The high-magnification zoom lens can be calibrated with a non-tilted single calibration pattern image using the above relationship with included pseudo-code.
The prism calibration tool is not considered in this pseudo-code for easy implementation.
