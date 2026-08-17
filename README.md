# Mohammd Benni

**Robotics engineer and full-stack web developer.** Aleppo, Syria.

I build autonomous service robots and the embedded layers underneath them, plus
the web platforms and databases that keep everything talking. Getting a machine
to behave in a crowd of thousands is a different problem from getting it to
behave in a simulation.

## Now

**Robotics Engineer at SWB AI** since January 2026, working on **Manara**, an
autonomous guidance robot deployed at the Grand Mosque in Mecca and the Prophet's
Mosque in Medina.

- **Battery management package** in ROS 2 Jazzy and C++: reads the BMS over
  RS-485 with hardware timed framing, and publishes state of charge and health
  telemetry the rest of the stack can trust.
- **IoT control dashboard with a live map**: streams only the occupancy grid
  cells that changed since the last frame instead of full grids, which keeps the
  map updating with no perceptible lag over an ordinary network link.
- **SLAM tuning** so the pose estimate stops jittering, which lets the controller
  follow a genuinely smooth path instead of correcting against its own noise.
- **Sensor integration and embedded bring-up** on Orange Pi 5 Max and Raspberry
  Pi: RPLidar C1, the ultrasonic array, and the serial devices.

## Also

Freelance full-stack web development: API, database, front-end, and deployment.
Previously **Backend Developer and Database Designer at Elkood** (2023 to 2024),
building .NET Core services with Domain-Driven Design and CQRS, and designing the
relational schemas underneath them.

## Working with

| | |
|---|---|
| **Robotics** | ROS 2 Jazzy, C++, Python, SLAM, LiDAR, sensor fusion, RS-485, ESP32, AVR, PCB design |
| **Backend** | .NET Core, C#, FastAPI, PostgreSQL, SQL Server, Docker, Linux |
| **Front-end** | SvelteKit, TypeScript, Tailwind CSS |
| **Vision** | YOLO v8 and v11, OpenCV, edge inference tuning |

## Competitive programming

Seven years of it. Contestant, then coach at Aleppo University since 2022, and
now on the technical team behind ACPC, working on the PC² 9.10 judging cluster,
the scoreboard, and the Resolver. I wrote the toolkit that imports problems
straight from Polygon into PC², tests and validators and time limits included,
which turned a full day of manual setup into a single command. Judged the Idleb
Collegiate Programming Contest.

Codeforces: [@Legends_Never_Die](https://codeforces.com/profile/Legends_Never_Die)

## Education

**BSc Electrical Engineering, University of Aleppo, 2026.** Department of
Automatic Control and Industrial Automation.

Graduation project: adaptive traffic intersection control. A traffic signal that
sets its own timing from a single camera instead of a fixed schedule, using
YOLOv11n detection, IoU tracking with EMA smoothing, and a Max-Pressure
supervisory controller, over a finite state machine that owns safety. Runs on an
ESP32 with a custom PCB.

---

**[mohammdbenni.me](https://mohammdbenni.me)** ·
[LinkedIn](https://linkedin.com/in/mohammd-benni) ·
[ORCID](https://orcid.org/0009-0004-4489-412X) ·
[Codeforces](https://codeforces.com/profile/Legends_Never_Die) ·
[ICPC](https://icpc.global/ICPCID/CFILP0WQF2R5)

Open to remote roles and relocation. Based in Aleppo, Syria, GMT+3.

<sub>Also written as Mohammad Benni, Muhammad Benni, Mohammed Benni, محمد بنّي</sub>
