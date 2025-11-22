#  Project Proposal  
## **Solution to Campus Parking: Live Parking-Bay Availability System**

### **Team Members**  
- Liu Annuo  
- Chua Gin Wu  
- Yu Shao Fan  
- Ryan Lee  

### **Project Duration**  
**Week 10 – Week 26**  
(Weeks 27 & 28: Final Submission & Awards)

### **Project Leader**  
**Liu Annuo**

---

## 1.  Project Background  
Daily commuting to the University of Nottingham Malaysia (UNM) often presents a recurring challenge: finding available parking.  
Students and staff frequently experience:

- Long searching time  
- Uncertain parking availability  
- Delays during peak hours  

We asked ourselves:

> **“What if we could know where to park before even entering campus?”**

This motivated our team to design an **intelligent, real-time parking monitoring system** that improves campus mobility, reduces stress, and enhances overall traffic flow.

---

## 2.  Objectives  
The Live Parking-Bay Availability System aims to:

- Provide **real-time updates** of available parking spaces.  
- Notify users during **peak hours** when availability is low.  
- Enable drivers to **plan ahead** and select alternative parking if needed.  
- Improve **traffic flow** and reduce lateness for classes/events.  
- Demonstrate a **practical and feasible engineering solution** integrating IoT, sensors, and software.

---

## 3.  Scope and Target Users  
The system focuses on **UNM students and staff**, addressing:

- Time wasted searching for parking  
- Stress from uncertain availability  
- Delays in attending classes or campus events  

By offering real-time, accurate information, the system helps users locate available bays or make informed decisions to park off-campus.

---

## 4.  Technical Approach  

### **4.1 System Architecture**  
The system consists of:

- **Hardware**  
  - ESP32-S3 microcontroller  
  - Inductive Coil Module  

- **Data Processing**  
  - Sensors detect vehicle presence and send data to ESP32-S3  

- **Communication**  
  - ESP32-S3 transmits data via Wi-Fi to it's server side  

- **Display & UI**  
  - Web dashboard  
  - Physical monitor at campus entrance  

Both interfaces provide **live parking availability**.

---

### **4.2 Workflow**

1. Sensors detect whether a parking space is occupied  
2. ESP32-S3 processes & aggregates data  
3. Real-time information is uploaded to the server  
4. Users access live parking data through:  
   - Web interface  
   - Entrance display monitor  

This ensures **accurate detection**, **efficient communication**, and **clear visualization**.

---

## 5.  Project Timeline & Methodology  

### **Week Breakdown**

| Week | Activities |
|------|------------|
| **Week 10** | Initial proposal preparation and planning |
| **Weeks 11–12** | Proposal refinement, Gantt chart, BOM, task allocation, feasibility |
| **Weeks 13–14** | Component procurement (Cytron), FOSE equipment rental |
| **Weeks 15–26** | Project execution (excluding exams/holidays) |
| **Working Weeks** | 15, 21, 22, 23, 24, 26 |

---

### **Workflow Details**

- **Week 15**  
  Component procurement, equipment rental, preliminary testing  

- **Week 21**  
  Circuit design, power system planning, PCB design, wiring  

- **Weeks 22–23**  
  Coding, computer vision development, web interface creation  

- **Week 24**  
  3D modeling & printing of supporting structures  

- **Week 26**  
  Demonstration video & final presentation preparation  

---

### **Team Workload**

- Total estimated project hours: **~80 hours**  
- Minimum contribution per member:  
  - **13 hours/week**  
  - Breakdown: 1 hour/day (weekdays) + 4 hours/day (weekends)  

Work is collaborative:  
2–3 members work on coding/algorithm tasks  
Remaining members support planning, tracking, and documentation.

---

## 6.  Resource Management  

- **Components & Sensors**  
  Procured from Cytron  

- **Special Equipment**  
  MCU and sensors rented from FOSE  

- **Documentation & Code**  
  Hosted on **GitHub** for sharing and version control  

- **Proposal Writing**  
  Managed in **Google Docs** for real-time collaboration  

---

## 7.  Roles & Responsibilities  

### **Project Leader — Liu Annuo**  
- Lead proposal preparation  
- Coordinate tasks  
- Provide technical guidance  
- Solve system-level problems  

### **Team Members**

- Power & supply system design  
- PCB design & circuitry  
- Code development & algorithm implementation  
- 3D modeling & prototype construction  

All members collaborate to maintain project continuity and progress.

---

## 8.  Expected Outcomes  
- Functional **real-time parking monitoring system**  
- Reduced searching time for parking  
- Improved campus traffic flow  
- Demonstration of IoT-based smart-parking feasibility  
- A complete prototype integrating hardware + software  

---

## 9.  Innovation & Significance  
This project allows the team to experience the **full engineering design cycle**, integrating:

- Hardware development  
- Sensor interfacing  
- Embedded programming  
- Networking  
- Web development  
- Visualization  

It presents a **practical, impactful solution** to a real on-campus issue.

---

## 10.  Conclusion  
The **Live Parking-Bay Availability System** is a user-focused IoT solution designed to improve campus parking efficiency at UNM.  
By delivering real-time availability, reducing search time, and supporting punctual arrival, the project:

- Enhances user convenience  
- Reduces congestion  
- Demonstrates engineering problem-solving  
- Provides meaningful experience in hardware, software, and teamwork  

This project exemplifies innovation, practicality, and the real value of engineering for daily life.

