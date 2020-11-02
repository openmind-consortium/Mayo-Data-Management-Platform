# Mayo Data Management Platform and Analytical Tools
Data Management Platform
The Mayo Data Management Platform (DMP), in conjunction with the Medtronic Summit System, is an investigational neuromodulation system that provides advanced brain sensing and stimulation capabilities.

The DMP System provides a Patient facing application integrated together with Physician operating mode (physician facing application).

The DMP System connects to the Medtronic Summit System, which consists of an RC+S implantable device, commercial leads and extensions, Summit Application Programming Interface, Summit Research Lab Programmer (RLP), Continuous Telemetry Module Gateway (CTM), and Summit Patient Programmer and INS recharger. The DMP system consists of a software application hosted on a standard Microsoft Windows compatible tablet computer. Off-line analysis and management of data is possible via commercially available cloud computing resources.

The DMP Application (running on the tablet computer) will telemeter and store iEEG data from the Olympus RC+S device via the CTM Gateway. The Medtronic Summit Research Development Kit (RDK), a software interface library, is incorporated in the DMP and is used to access gateway functionality. The DMP Application receives iEEG data through an encrypted Bluetooth link with the Medtronic CTM gateway, stores the iEEG data locally on the tablet computer, and copies the iEEG data over standard wireless or cellular data connections to a remote analysis and storage system for physician review.

The DMP Application includes algorithms to identify segments of iEEG data with particular characteristics, configurable by the user. The DMP Application provides an interface to allow the patient to self-annotate events (e.g. sensory auras, medication doses) and stores these annotations with timestamps synchronized with stored iEEG data on the tablet, and copies these annotations to the remote storage and analysis system. The DMP application is also capable of providing alerts when the battery charge levels of the tablet or the RC+S implanted neurostimulator drop below a specified level.

The DMP system selects neurostimulation parameters from a physician-defined and verified safe range. In the Medtronic Summit System, there are 16 stimulation programs available in 4 selectable groups. There are 3 groups (12 programs) available for “remote” web selection, and 1 group (4 programs) set aside for embedded closed-loop operation on the RC+S device. Stimulation programs can be selected from either an external command function or an embedded algorithm function.

The DMP source code and executables are provided freely to all RC+S and Open Mind consortium investigators. The software is provided as is with no warranties or guarantees, and investigators using the code accept full responsibility for the software's use and application.

## For more details, follow the Wiki page for these tools: https://github.com/openmind-consortium/Mayo-Data-Management-Platform/wiki
