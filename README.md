# PD-Driver
A highly compact and efficient USB C Power Delivery based stepper motor driver system developed for precise and reliable control of NEMA 17 stepper motors in robotics, automation, CNC systems, and embedded motion control applications. This project focuses on creating a fully integrated hardware solution capable of handling high current motor operation while maintaining stable power delivery, thermal efficiency, compact PCB routing, and reliable communication between subsystems. The system utilizes USB C PD negotiation to intelligently obtain higher voltage levels from modern USB C adapters, eliminating the need for bulky external power supplies and making the design more portable and practical for real world deployment. The complete design process involved extensive research into power electronics, USB C PD protocols, motor driver architecture, PCB stackup optimization, EMI reduction techniques, component placement strategies, and thermal management considerations to ensure stable and efficient operation under varying load conditions.


<img width="385" height="382" alt="image" src="https://github.com/user-attachments/assets/a41bf2fa-18c3-42cb-8154-01e7db19a01b" />


The hardware design includes custom designed power regulation circuitry, gate driver stages, filtering components, protection mechanisms, and optimized routing for high current traces to reduce voltage drops and electrical noise during motor operation. Significant effort was dedicated toward schematic validation, signal integrity analysis, decoupling optimization, and layer wise PCB planning to achieve a clean and manufacturable board layout while maintaining compact dimensions. Multiple iterations of the PCB were created and analyzed to improve routing efficiency, reduce interference between sensitive signals and power lines, and optimize the placement of passive and active components for better heat dissipation and electrical stability. The project also involved studying motor control fundamentals, current handling limitations, driver efficiency, transient response, and switching behaviour to improve the overall reliability of the system.
<img width="795" height="707" alt="Screenshot 2026-04-23 223627" src="https://github.com/user-attachments/assets/125e0d32-7914-4bb6-af15-62a4848cc6df" />
<img width="471" height="415" alt="Screenshot 2026-04-28 163719" src="https://github.com/user-attachments/assets/ec675239-8084-4553-bd4d-db2e0f4d543b" />

Mechanical integration and structural considerations were also taken into account during development to ensure the design could be easily mounted and integrated into robotic systems and automation platforms. Different connector orientations, mounting methods, and board form factors were evaluated to improve usability and accessibility while keeping the design lightweight and portable. Thermal simulations and practical testing were performed to understand heat distribution across the board and improve the placement of high power components and copper pours for better cooling performance. Additional focus was given to minimizing PCB complexity while still maintaining scalability for future upgrades such as sensor integration, closed loop feedback systems, wireless communication modules, and advanced motion control features.



<img width="520" height="424" alt="Screenshot 2026-05-09 223850" src="https://github.com/user-attachments/assets/a636cae9-aedd-4f40-b7e5-582d57e75232" />
<img width="620" height="535" alt="Screenshot 2026-05-09 223816" src="https://github.com/user-attachments/assets/494bba35-291b-48cf-987a-f8d953f1f5fb" />
This project represents a complete end to end embedded hardware development workflow involving circuit design, power electronics, USB C PD implementation, PCB layout optimization, hardware debugging, component analysis, thermal management, and system level integration. It demonstrates practical experience in designing compact high power embedded systems capable of real world deployment while balancing efficiency, reliability, manufacturability, and portability. The final system showcases a combination of modern power delivery techniques, optimized embedded hardware design practices, and efficient motor control implementation aimed at creating a robust and scalable motion control platform for advanced robotics and automation applications.
}

<img width="846" height="483" alt="Screenshot 2026-05-09 223737" src="https://github.com/user-attachments/assets/9e452208-60b8-4ecc-a4d8-7ab7af8815df" />


# BOM

| Component             | Purpose                                                                                         | Quantity | Total Cost (USD) | Distributor | Read                                                                                                              |
| --------------------- | ----------------------------------------------------------------------------------------------- | -------- | ---------------- | ----------- | ----------------------------------------------------------------------------------------------------------------- |
| Brass Inserts         | Used for secure mounting and structural assembly of the mechanical frame                        | 20       | $1.00            | OnlyScrews  | Improves durability and allows repeated assembly without damaging printed parts                                   |
| Bearings              | Provides smooth rotational motion and supports actuator movement                                | 4        | $5.30            | OnlyScrews  | Reduces friction and improves precision of the mechanism                                                          |
| NEMA 17 Stepper Motor | Main actuator used for controlled motion and positioning                                        | 2        | $10.66           | Robocraze   | Enables accurate motion control for robotics and automation applications                                          |
| Custom PCBA           | Core electronics system containing power delivery, control circuitry, and motor driver hardware | 1        | $164.48          | JLCPCB      | Integrates USB C PD, motor control, protection circuitry, and optimized PCB layout into a compact embedded system |


| Currency | Total Cost         |
| -------- | ------------------ |
| USD      | **$181.44**        |
| INR      | **₹15,600 approx** |

