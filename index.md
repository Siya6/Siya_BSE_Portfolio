# Third Eye For the Visually Impaired
I am working on a device that can potentially help the visually impaired. This wearable innovation allows the blind to easily navigate by detecting nearby obstacles through an ultrasonic wave that then notifies the person with a buzzer sound and vibrator that both speed up as they get closer to the object. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Siya K. | Biotechnology High School | Computer Science, Biomedical Engineer |  Rising Junior 

![Relevant Name](https://cdn-shop.adafruit.com/970x728/4296-11.jpg)
  
# Third Milestone
My final milestone is putting everything together to make it a wearble device. I soldered everything as oriented on the breadboard to a perfboard and got it working. Then I attached the perfboard to a glove for people to put on. I attached it by handsewing the ultrasonic sensor to the front of the glove and hot gluing the perf board to the back of the glove. I also used a 9 volt battery as the power source, instead of connecting the arduino to my computer. This works because the arduino board has a memory library that stores the arduino sketch, so the circuit will still run correctly. This is the final result of this device, which is now ready for the visually impaired to use.

[![Siya's Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1660255103/video_to_markdown/images/youtube--6uNq9k0TgUA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=6uNq9k0TgUA "Siya's Third Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
For my second milestone I attached all the main compenents to the breadboard and wrote a new code that combined each component's code, and then refining that new code to get all the parts to work together. When running the sketch, the serial monitor shows the distance in centimeters, the toggle, and the count. For the distance shown, it changes relative to the sensor's distance to an object. Additionally, the count remains as 0, until I press on the button. The count value increases as long as I press and hold on the button, and when I release the button after pressing on it, the count will go back to 0 and the toggle count switches. Initially the toggle value will equal 0, meaning the ultrasonic sensor is working with the motor. So as the sensor gets closer to an object the motor will vibrate faster and it'll go slower as the sensor moves father away from an object. After I click on the button the toggle will switch to 1, which means the sensor switches to connect to the buzzer. The buzzer also works realtive to the sensor, so as the ultrasonic sensor gets closer to an object, the buzzer will beep faster and vice versa. I wrote a code for teh cirsuit to work as per the customer's preference of whether they would prefer a vibrating motor or a buzzer while using the device.

[![Siya's Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1660254914/video_to_markdown/images/youtube--XCoP4QesjLY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=XCoP4QesjLY "Siya's Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone
My first milestone was setting up and hooking up the ultrasonic sensor and the arduino micro to the breadboard. I did this in order to test how if the sensor was working and understand how. Using wires from the sensor to the arduino board, I connected the VCC to the 5V, the trigger pin to 6, the echo pin to 7, and finally the ground pin to the ground on the arduino. Next, I wrote a code that would display the distance of an object in centimeters, on the serial monitor, from the ultrasonic sensor. The closer the object got to the sensor the the smaller the distance is, and the farther the object got the larger the distance appeared. This works because the sensor sends out sound waves the travels to the object and then bounces off it back to the sensor, which then recevies an echo. This pulse allows it to calculate the distance of the sensor from the object.

[![Siya K First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1659706035/video_to_markdown/images/youtube--e5XEOtwXClo-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=e5XEOtwXClo "Siya K First Milestone"){:target="_blank" rel="noopener"}
