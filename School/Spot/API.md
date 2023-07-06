- SDK = Language-specific implementation on Spot API
	- Add custom functionality to robot

# Customization
## Control Spot's movement
- Follow a path
- Walk to a certain point
- Pose/Sit/Stand
- Arm manipulation

## Custom Payloads
- Control Spot from your own devices as well

## Enhance Autons
- Manage missions from custom applications
- Use the GraphNav and Autonomy services to customize mission behavior
- Create custom area callbacks
	- When you reach a certain area, the robot can do something
- Custom mission actions
- Combine with AI to interact w/ environment

## Capture and Use data
- Query Spot's state
	- Metrics, data, etc
- Audio/Video
- Images from acmera
- Export data to system for analysis or testing
	- ML, trends

# Using the Spot SDK
- https://dev.bostondynamics.com
- Deploy SDK on CORE+IO (onboard payload computer)

# Running code on Spot

# Abstract System Architecture
- Secure network exposed API services receives protocol buffer commands from applications via gRPC
- Protocol buffer = Language-independent protocol through an IDL (interface definition language)
- gPRC = Open source remote procedure call framework

# Proto Use
- Protos format commands in a way that the robot can receive and understand

# Message Specs
- Similar to a Class
- Definition/framework of a message

## Services
- **Service** uses messages to receive RPCs
- Takes a message as input and sends a message as output

## Commands and Protos