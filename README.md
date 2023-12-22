# Mechanical_Inchworm
Experience robotics in action with our Mechanical Inchworm project! Using 3D-printed parts and Arduino control, this setup replicates the unique movement of an inchworm. The repository includes CAD files, Arduino code, and a demo video. Explore servo control and mechanics through this engaging project! This project features a mechanical inchworm powered by three servo motors, designed to mimic the crawling motion of an inchworm. Utilizing a combination of 3D-printed parts, basic hardware, and Arduino control, this system imitates the distinctive movement of an inchworm through a series of coordinated actions.

## Components

- **3D Printed Parts**: Consisting of four body parts and one spool, crucial for the structure and functioning.
- **Nails and Wooden Ice Cream Sticks**: Supporting elements for stability and movement.
- **3 Servo Motors**: Responsible for lifting, pulling, and releasing actions.
- **Arduino**: Controls and orchestrates the movement sequence.
- **String and Rubber**: Integral components aiding in the inchworm's motion.

## How It Works

The project operates through a step-by-step sequence:

1. **Rear Servo Action**: The rear servo lifts the trailing part of the worm using an ice cream stick, leveraging the rubberized bottom for grip.
  
2. **Spool Rotation**: Another servo rotates the spool, pulling the inchworm inwards.
  
3. **Release and Touchdown**: The servo releases the trailing part, allowing it to touch the ground again.
  
4. **String Relaxation**: The spool rotates in the opposite direction, relaxing the string for the next movement.
  
5. **Forward Motion**: The forward servo raises the front, and the inchworm's weight propels its front end forward.
  
6. **Release and Repeat**: The servo releases the front, allowing it to meet the ground, and the process repeats itself to create the inchworm's crawling motion.

## Implementation Notes

- **Mechanical Design**: The 3D printed parts and assembly play a critical role in ensuring smooth movement and stability.
  
- **Programming**: The Arduino code orchestrates the servo movements in a precise sequence to simulate the inchworm motion.
  
- **Adjustments**: Calibration of servo angles and timings might be necessary for optimal performance.

## Usage

1. **Assembly**: Construct the inchworm structure using the 3D-printed parts, nails, and ice cream sticks.
  
2. **Wiring**: Connect the servo motors to the Arduino board following the specified pin configurations.
  
3. **Upload Code**: Upload the provided code to the Arduino for controlling the servo movements.
  
4. **Operation**: Power the system and observe the inchworm's crawling motion.

## Included Files and Resources

- **CAD Files**: Contains designs for the 3D-printed parts required for the inchworm assembly.
- **Arduino Program**: Code for controlling the servo motors to enact the inchworm motion.
- **Physical Working Video**: Demonstrates the functionality and movement of the inchworm.


## Experimentation and Learning

This project serves not only as an engaging mechanical experiment but also as a learning opportunity for understanding servo control, sequential movements, and basic mechanics.

---
