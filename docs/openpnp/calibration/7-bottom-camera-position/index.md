# Bottom Camera Position ([Video Guide](https://youtu.be/h3mtEQfGMlM?si=uyDBUttihPh80EQv&t=1580))

Now that we know the offset from the top camera to the nozzle, we can use the nozzle to set our bottom camera position.

1. Navigate to `Machine Setup > Cameras > OpenPnpCaptureCamera Bottom`.
  
    ![Select the bottom camera](images/select-bottom-camera-2.png)

1. Click on the `Position` tab.
  
    ![Select the position tab](images/bottom-camera-position.png)

2. Select the `Nozzle: N1` from the machine controls dropdown.
  
    ![Select nozzle from machine control dropdown](images/select-n1-machine-control-bottom.png)

3. Click the "Position tool over location" button to bring the left nozzle roughly above the bottom camera.
  
    ![Position the toolhead over the bottom camera](images/position-over-bottom-cam.png)

4.  Jog the toolhead until the left nozzle is directly in the center of the bottom camera's vision.
  
    ![Position the toolhead over the bottom camera precisely](images/position-over-bottom-cam-precise.png)

5.  Click the "Capture Toolhead Location" button to calculate the correct position for the bottom camera. **Make sure your Z height is at 31.5.** If it isn't, manually enter `31.5` into the Z field.
  
    ![Store the camera location](images/store-nozzle-location-bottom.png)

6.  Click the `Apply` button to save the new camera position.
  
    ![Save the camera location](images/apply-bottom-cam-pos.png)

## Next Steps

Next is [Nozzle Tip Calibration](../8-nozzle-tip-calibration/nozzle-tip-calibration.md).
