---
layout: home
permalink: index.html

# Please update this with your repository name and project title
repository-name: e18-3yp-Smart-Medicine-Dispenser
title: Smart Medicine Dispenser
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Smart Medicine Dispenser

---

## Team
-  e18030, Sathsarani Aththanayaka, [email](e18030@eng.pdn.ac.lk)
-  e18036, Mahela Bandara, [email](e18036@eng.pdn.ac.lk)
-  e18150, Yojith Sadaruwan, [email](e18150@eng.pdn.ac.lk)

<!-- Image (photo/drawing of the final hardware) should be here -->



#### Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Data flow](#data-flow)
4. [Hardware & Software Designs](#hardware-and-software-designs)
5. [Testing](#testing)
6. [Detailed budget](#detailed-budget)
7. [Conclusion](#conclusion)
8. [Links](#links)

## Introduction

<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/73664068/198972028-0f39e90b-a9e1-41f7-8ffb-b7b43dda7966.png" alt="Taking picture of food">
</p>

### Overview

The standard daily routine in a hospital ward comprises of ward rounds by doctors, medication, meals, visiting hours and bedtime. This routine may vary if patients are required to undergo laboratory tests, x-ray, or other clinical procedures.Hospital doctors treat those who have been admitted or referred to hospital. Specific responsibilities vary greatly depending on the area of specialism.Normaly it includes undertaking patient consultations and physical examinations, providing general pre- and post-operative care, monitoring and administering medication, assessing and planning treatment requirements and so on. The first concern of a doctor is patients' care, dignity and safety.

The primary role of a nurse is to be a caregiver for patients by managing physical needs, preventing illness, and treating health conditions.Nurses care for injuries, administer medications, conduct frequent medical examinations, record detailed medical histories, perform diagnostic tests and admit/discharge patients according to physician orders.

Our main focus direct towards these two characters such as doctor and nurse to make their life easier.

### Real world problem

Let’s imagine a ward in a hospital.Usually the doctor visits three times per day and goes to each and every bed by checking patients and assigning medicine to each patients.Currently it does by writing on a paper or instead of that they may add it to a patient’s profile which control by the hospital database. So, after that when the nurse is going to give medicine there can be several problems.

1. If the prescription is a handwritten one,there may be some difficulties in identifying the correct drug.

2. Even if it is done through a specific web site,there can also be some human errors.Such as the dose as well as the time can be changed  by mistake , Nurse can be read incorrect patient’s details.

3. Since drugs are highly sensitive, we should pay more attention to decrease the number of people involved when distributing medicine.If medicine goes hand by hand it can affect the chemical compound of that medicine.

4. Also we can’t guarantee that each container is in good condition which means if there is no certain process of cleaning containers once for a certain time period it would be caused to occur some problems like allegics

5. Also the workload assigned to a nurse is really huge,So it will be a great relief if we can reduce the workload on a nurse.

6. Another problem arise when manually distributing medicine person to person is , a nurse has to go through each and every prescription and select tablets according to that.it is highly time consuming, so if there is a mechanism to reduce time taken to do that ,the efficiency can be increased with less manpower.

7. If one type of medicine is over in that ward, according to the process that is following currently, it may take two to three days to fulfill that requirement. If we can give alerts to authorized persons within sometime, it may also help to increase the efficiency in the process.

### Solution

Our solution is going to solve almost every of the above mentioned problems.It is an automated container which contains tubes assigning the respective drug.There is a secured way to put drugs inside it.We plan to control it by giving permission to authorized person by introducing finger print method.Apart from that, there is a mechanism to select meal of drugs for a patient according to his or her prescription.Another feature we hope to introduce through this system is an alert system which reminds incharge of drugs when at least a tube is empty.That is the basic idea about the hardware device.

When it comes to softwares, there is a backend that contains every detail of each patient in the ward. Doctors can assign medicine using a mobile application or a web application. Also they are the only authorized group of people who can edit the prescription.The container is connected with the mobile application.So when the time comes to distribute medicine ,the only thing the nurse should do is select the particular person by clicking on the name of the patient listed down in mobile application and then simply click on “Dispense”. Automatically the cup under the hardware device will fill with relevant tablets.Then the patient’s details will be marked.There is a history according to the medicine taken by each patient.


## Solution Architecture
<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/73664068/199351698-f6015f65-2c1a-4539-a31f-022f93f913dc.png" alt="Taking picture of food">
</p>

## Data flow
<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/73664068/199351735-4c08bf61-293b-4f43-899e-b92a5c74b33d.png" alt="Taking picture of food">
</p>

## Hardware and Software Designs

Detailed designs with many sub-sections

## Testing

Testing done on hardware and software, detailed + summarized results

## Detailed budget

All items and costs

| Item          | Quantity  | Unit Cost  | Total  |
| ------------- |:---------:|:----------:|-------:|
| Sample item   | 5         | 10 LKR     | 50 LKR |

## Conclusion

What was achieved, future developments, commercialization plans

## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
