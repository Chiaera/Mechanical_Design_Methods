# Three-Finger Adaptive Gripper

## Project Overview
The objective of the project is to design a robotic gripper able to pick up a **front upper motor mount**. The component has a central cylindrical body, a top threaded screw and three radial flanges, also referred to as “petals”.

The main goal of the design is to create a gripper that is:
* functional;
* simple to assemble;
* adaptable to different component diameters;
* able to avoid damaging restricted areas of the component;
* suitable for integration with a Jodell motor.

## Target Component
The target component is a front upper motor mount with the following main characteristics:
* central cylindrical body;
* upper threaded screw;
* three radial flanges/petals: willing to 120°;
* diameter range: approximately 35 mm to 45 mm;
* maximum height: approximately 85 mm.

The gripper must avoid contact with sensitive or restricted areas, such as:
* the threaded screw;
* the bolt sections;
* the flanges parts.

For this reason, the selected safe grasping area is the lower cylindrical surface of the component.

## Design Requirements
The gripper was designed according to the following requirements:
| Requirement   | Description                                                                      |
| ------------- | -------------------------------------------------------------------------------- |
| Safe grasping | The gripper must avoid the threaded screw, bolt sections and painted surfaces.   |
| Adaptability  | The gripper must be able to grasp components with different diameters.           |
| Stability     | The component must remain stable during the pick-up operation.                   |
| Easy assembly | The design should be simple and feasible to assemble.                            |
| Maintenance   | Wearable parts should be easy to replace.                                        |
| Compatibility | The mechanism should be compatible with the Jodell motor and its linear sliders. |

## Final Design

The final design is based on a **three-finger architecture**.

One finger is connected to one of the motor sliders and performs a linear movement. The other two fingers are guided through rigid bars and slots, allowing them to move while maintaining the correct angular configuration around the component.

The design is based on the angular distribution of the component petals. Since the petals are considered equidistant, the gripper uses a 120° configuration to reach the safe contact areas between them.

## Fingers Design

The fingers are designed with two main parts:

1. **External metal structure**
   This part supports the weight of the component and provides mechanical resistance.

2. **Internal silicone/elastomer layer**
   This part improves compliance and allows a softer contact with the component.

The finger height was defined considering the tallest version of the component. Shorter components do not create critical issues, since they only generate additional clearance between the top part of the component and the gripper.

## Finger Tips and Rubber Attachments

Each finger includes a snap-fit system at the end, used to insert a replaceable rubber attachment.

The rubber attachments are used to:

* protect the component surface;
* reduce direct metal contact;
* improve grip stability;
* allow easier maintenance.

Two types of rubber attachments were designed:

* spherical attachments, to provide point contact;
* one cylindrical attachment, to improve stability and reduce tilting or bending movements.

The rubber parts can be replaced when worn out, without disassembling the whole gripper.
