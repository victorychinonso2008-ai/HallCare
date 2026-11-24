# HallCare

**Hall Maintenance and Repair Tracking System**

| | |
|---|---|
| **School** | Babcock University |
| **Course code** | BU-209 |
| **Document** | Product Requirements Document (PRD) |
| **Version** | 1.0 |

---

## 1. Product Overview

### 1.1 Product Name

HallCare

### 1.2 Product Description

HallCare is a proposed system for reporting and tracking maintenance problems in Babcock University's halls. It will allow students to report problems such as faulty sockets, broken bulbs and other issues in their rooms. Students can submit complaints themselves, while porters and authorised hall staff can also report problems on their behalf.

Hall administrators will use the system to keep records of complaints and add updates when they receive information from maintenance workers and other departments. Students will also be able to check the progress of their complaints instead of repeatedly asking porters for updates. The main aim is to make reporting problems and following up on repairs easier.

### 1.3 Product Aim

HallCare aims to make it easier to report maintenance problems and follow up on repairs. It will keep repair reports and updates in one place so that students and staff can check their progress.

---

## 2. The Problem

Maintenance problems in the university halls can sometimes take a long time to fix. Our research suggests that different people and departments are involved in handling repairs, but students do not always know what happens after they report a problem.

Students currently report faults through the repair notebook at the hall reception or through hall staff. One student explained that she reported a problem to a porter, who passed the complaint to the hall administration. While waiting, she had to keep asking the porter for updates.

Getting materials can also delay repairs. The maintenance worker explained that there is no store in the hall, so materials have to be collected from the central store. The materials were available for his recent bulb repair, but he said that on another occasion he had waited for up to one week to get the materials needed for another job.

The procurement personnel also explained that requests can pass through different offices before approval. They could not give an exact timeline or identify one office that was always responsible for delays.

The Chief Female Hall Administrator also shared a case involving a burnt socket. The student reported the problem on 11 November, but it was still unresolved by 17 November. The student later complained to the Vice President's office because they had to go elsewhere to charge their devices and carry out other activities. According to the administrator, the electrician had said that materials had not been released from the central store. He had also contacted her for a signature while she was attending a conference. The fault was later found to have been caused by a faulty extension used by the student.

These examples show that repairs can be delayed for different reasons. They also show that students and staff do not always have clear information about the progress of a repair. HallCare is proposed to help by keeping repair reports and updates in one place.

### 2.1 How Repairs Are Handled Today

Students currently report faults by writing them in the repair notebook at the hall reception or by telling a porter or hall staff member. In the student example, the porter passed the complaint to the hall administration, and the student kept asking the porter for updates. The hall administrator also said that she makes phone calls and contacts supervisors to check on pending repairs. In the burnt-socket case, the student eventually wrote to the Vice President's office when the problem remained unresolved.

### 2.2 Why the Current Approach Falls Short

The repair notebook gives staff a place to record faults, but the research shows that students still have to ask staff for updates. Administrators may need to make several calls to find out what is happening with a repair. The interviews did not identify one shared record that shows the current status, who handled each step, when it happened and why a repair is waiting. Because of this, it can be hard for students and staff to see where a repair is delayed and what needs to happen next.

---

## 3. Research and Findings

### 3.1 Research Participants

We collected information from eight people.

| Participant | Number | Date | Method |
|---|---:|---|---|
| Chief Female Hall Administrator | 1 | 19 November 2026 | Recorded interview |
| Maintenance worker | 1 | 23 November 2026 | Interview; notes taken |
| Procurement personnel | 3 | 23 November 2026 | Interviews; notes taken |
| Students | 3 | 23 November 2026 | Conversations; notes taken |
| Porters | 0 | N/A | Not interviewed |
| **Total** | **8** | | |

No porters were interviewed. However, one student explained that she reported a problem through a porter. The porter's role in the proposed system is based on this account and still needs to be confirmed with porters.

### 3.2 Chief Female Hall Administrator

The Chief Female Hall Administrator explained that students report faults by writing them in a repair notebook at the hall reception. Maintenance workers check the notebook and attend to reported problems. If the required materials are available, they can carry out the repair. If not, a request has to be made.

She also explained that the process may involve Works and Physical Planning, procurement and the central store. Hall administrators sometimes make phone calls and contact supervisors to find out what is happening with pending repairs.

She mentioned that hall administrators are expected to sign for materials and monitor how they are used. According to her, some repairs can take more than one month. She suggested having a store and storekeeper in each hall to make materials easier to get.

### 3.3 Maintenance Worker

The maintenance worker spoke about a recent job where he had to repair a faulty bulb. Since the hall does not have its own store, he used a request form to collect the materials from the central store. The materials were available at the time, so procurement was not needed for that repair.

He also said that he had once waited for up to one week to get materials for another repair. He identified the availability of materials as one of the things that can delay his work.

### 3.4 Procurement Personnel

Three procurement personnel were consulted about how materials are provided for maintenance work. They explained that requests can pass through different offices and approval stages. The time taken depends on the request and whether the required materials are available.

They could not give an exact timeline or identify one office where delays always happen.

### 3.5 Students

We collected responses from three students. Two said they had not previously had maintenance work carried out in their rooms, while one had experienced a maintenance problem.

The student who experienced the problem said she reported it to the porter. The porter then passed the complaint to the hall administration, and it eventually reached the Chief Female Hall Administrator. The student estimated that the process took about three to four days. While waiting, she kept asking the porter for updates and was told that calls had been made.

This shows that students may have to depend on hall staff to find out what is happening with their complaints.

### 3.6 Summary of Findings

The research brought up three main issues:

1. **Following up on complaints:** Students may not know what is happening after reporting a problem and may have to ask hall staff for updates.
2. **Getting materials:** The maintenance worker said that he had once waited up to one week for materials needed for a repair.
3. **Knowing where delays happen:** Procurement personnel described requests passing through different offices, but could not identify one stage where delays always happen.

These findings will guide the design of HallCare.

### 3.7 Research Limits

The research involved eight people: one Chief Female Hall Administrator, one maintenance worker, three procurement personnel and three students. No porters were interviewed. The student who reported a repair gave an estimate of three to four days, not an exact recorded duration.

The full procurement process and the exact time spent at each stage are still not clear. The small number of student responses also means that the findings cannot represent the experiences of all students in the university. These limits should be considered when planning and testing the system.

---

## 4. Proposed Solution and Repair Stages

### 4.1 Proposed Solution

HallCare will provide one place where maintenance complaints can be reported, stored and followed up.

Students will be able to submit complaints directly. Porters will also be able to enter complaints on behalf of students and record complaints received through the physical repair notebook. The porter will be responsible for entering notebook complaints into HallCare.

The hall administrator will review complaints and record updates received from maintenance workers and other departments. Students will be able to check the latest recorded progress of their own complaints.

The system will also show when a repair is waiting for materials or approval. It will record the reason for the delay, but it will not replace the university's procurement process or provide materials.

### 4.2 Proposed Repair Stages

The following stages are proposed for tracking each repair:

1. **Reported:** A student submits a complaint directly, or a porter or authorised hall staff member enters it on the student's behalf. Complaints written in the physical repair notebook will be entered by a porter.
2. **Reviewed:** The hall administrator checks the complaint and makes sure the important information has been provided.
3. **Inspected:** A maintenance worker checks the problem and identifies what needs to be done and whether materials are required. The hall administrator records the information received.
4. **Waiting for Materials or Approval:** This stage is used when materials are unavailable, approval is pending, or materials are waiting to be collected or signed for. The reason must be recorded. If materials are already available, this stage can be skipped.
5. **Ready for Repair:** The required materials are available, or the repair does not need extra materials.
6. **In Progress:** The maintenance worker has started the repair. If the job needs more than one visit, the hall administrator can add updates to the same complaint. If work has to stop because materials or approval are needed, the status can be changed to the waiting stage.
7. **Completed:** The maintenance worker reports that the repair is finished, and the hall administrator records the update.

If an inspection shows that a fault was caused by misuse, that finding should be recorded. The system should not automatically reject or close the complaint. The hall administration can decide what happens next under the university's rules.

Duplicate complaints or complaints that are outside the hall's maintenance responsibility can be closed with a reason. A student can also ask for a completed complaint to be reopened if the problem has not been fixed. The hall administrator reviews the request and decides whether to reopen it.

### 4.3 Who Updates the System?

- **Students:** Submit their own complaints and can ask for a completed complaint to be reopened.
- **Porters:** Enter complaints on behalf of students and add complaints from the physical repair notebook.
- **Hall administrators:** Review complaints and enter updates received from maintenance workers and other departments. They also review requests to reopen complaints.
- **Maintenance workers:** Tell the hall administrator what they found, what materials are needed and when work starts or finishes.
- **Procurement and store personnel:** Provide information about material availability, approval and collection when needed. The hall administrator records the relevant update.

In the first version, maintenance workers will not be required to write long updates in the system themselves. The hall administrator will record the information they provide. This is intended to keep the process simple for maintenance workers.

---

## 5. Users and User Stories

### 5.1 Students

Students can report maintenance problems directly and check the progress of their own complaints.

### 5.2 Porters

Porters can enter complaints on behalf of students and transfer complaints from the physical repair notebook into HallCare. This role is proposed based on the current reporting process and still needs to be confirmed with porters.

### 5.3 Hall Administrators

Hall administrators review complaints, manage their records and enter updates received from maintenance workers and other departments.

### 5.4 Maintenance Workers

Maintenance workers inspect problems, carry out repairs and tell the hall administrator about the progress of their work.

### 5.5 Procurement and Store Personnel

These staff may provide information about material availability, approval and collection. They are not required to use HallCare directly in the first version.

### 5.6 System Administrator

The system administrator manages user accounts, access permissions and general system settings.

### 5.7 User Stories

1. **Student:** As a student, I want to report a maintenance problem so that the hall administration can know about it and take action.  
   *Basis: Students currently report faults through the repair notebook or hall staff.*

2. **Student:** As a student, I want to check the progress of my complaint so that I do not have to keep asking the porter for updates.  
   *Basis: One student said she repeatedly asked the porter about a repair.*

3. **Porter:** As a porter, I want to report a problem on behalf of a student so that the complaint can reach the hall administration.  
   *Basis: One student's account described reporting a problem through a porter. This role still needs to be checked with porters.*

4. **Porter:** As a porter, I want to enter complaints from the physical repair notebook so that they can also be tracked in HallCare.  
   *Basis: The Chief Female Hall Administrator said complaints are recorded in a repair notebook at hall reception.*

5. **Hall Administrator:** As a hall administrator, I want to see repair complaints in one place so that I can monitor outstanding repairs.  
   *Basis: The administrator currently uses repair notebooks and phone calls to follow up on repairs.*

6. **Maintenance Worker:** As a maintenance worker, I want to tell the hall administrator about the progress of a repair so that the record can be updated.  
   *Basis: The maintenance worker explained that materials are sometimes needed before a repair can be completed.*

7. **Hall Administrator:** As a hall administrator, I want to record why a repair is waiting for materials or approval so that the reason for the delay is clear.  
   *Basis: The interviews raised delays involving materials and several approval stages.*

8. **Student:** As a student, I want to ask for a completed complaint to be reopened if the problem has not been fixed so that it can be checked again.  
   *Basis: This is a proposed feature to prevent unresolved problems from staying marked as completed.*

---

## 6. Requirements

### 6.1 Functional Requirements

These are the main things HallCare must be able to do.

| ID | Requirement | Basis |
|---|---|---|
| FR-01 | The system must allow users to log in. | Needed to protect user accounts and complaints. |
| FR-02 | Students must be able to submit maintenance complaints directly. | Proposed reporting option. |
| FR-03 | Porters must be able to submit complaints on behalf of students. | Based on the student's description of the reporting route; to be confirmed with porters. |
| FR-04 | Porters must be able to enter complaints recorded in the physical repair notebook. | The administrator described the notebook as the current reporting method. |
| FR-05 | Every complaint must have a unique reference number. | Needed to identify and follow up on each complaint. |
| FR-06 | The system must record when a complaint was submitted and how it was reported. | Needed to keep a clear record of the reporting route and time. |
| FR-07 | Hall administrators must be able to view complaints for the halls they manage. | Based on the administrator's role in monitoring repairs. |
| FR-08 | Hall administrators must be able to review complaints and update their status. | The administrator is responsible for entering progress updates. |
| FR-09 | The system must allow the administrator to record updates received from maintenance workers. | The maintenance worker communicates progress to the administrator. |
| FR-10 | The system must record when a repair is waiting for materials or approval. | The interviews identified material and approval delays. |
| FR-11 | The system must allow the reason for a material delay to be recorded as unavailable, approval pending, or waiting for collection or signature. | These are the delay reasons identified for the first version. |
| FR-12 | Students must be able to check the status of their own complaints. | Students currently have to ask staff for updates. |
| FR-13 | The system must record who entered an update and when it was entered. | Needed to keep a history of changes. |
| FR-14 | The system should record both when an event happened and when the update was entered. | An administrator may enter an update after the work happened. |
| FR-15 | Students must be able to request that a completed complaint be reopened. | Proposed feature for complaints that remain unresolved. |
| FR-16 | Hall administrators must be able to review and decide on reopening requests. | The administrator manages complaint records. |
| FR-17 | Hall administrators should be able to filter complaints by date and status. | Helps staff find pending and completed complaints. |
| FR-18 | The system must keep a history of changes made to each complaint. | Needed to follow the progress of a repair. |

### 6.2 Non-Functional Requirements

- The system should be easy to use, especially on mobile phones.
- Users should only be able to access information meant for their roles.
- Students must not be able to view other students' private complaints.
- The system must save complaints and updates properly.
- Pages should load within a reasonable time.
- Passwords must be stored securely.
- The system should work on common mobile and desktop browsers.

---

## 7. Data to Store

HallCare will need to store the following information:

### 7.1 User Information

- User ID
- Full name
- Email or username
- Password hash
- User role
- Assigned hall, where necessary
- Account status

### 7.2 Hall Information

- Hall ID
- Hall name
- Hall location

### 7.3 Repair Complaint

- Complaint ID
- Reference number
- Student affected or person reporting
- Hall and room number
- Type of problem
- Description of the problem
- Current status
- How the complaint was reported (directly, through a porter, or from the notebook)
- Assigned maintenance worker or department, where applicable
- Date and time reported

### 7.4 Repair Updates

- Update ID
- Related complaint ID
- Previous status
- New status
- Update description
- Person who entered the update
- Time the event happened
- Time the update was entered into the system

Keeping both times will help show when work actually happened, even if the hall administrator enters the information later.

### 7.5 Material Information

- Material record ID
- Related repair complaint
- Materials required
- Current material status
- Reason for delay
- Date and time of the update

The material delay reasons in the first version will be:

1. Materials unavailable.
2. Approval pending.
3. Waiting for collection or signature.

### 7.6 Reopening Information

- Complaint ID
- Student who asked for it to be reopened
- Reason for the request
- Date the request was made
- Administrator who reviewed it
- Decision and date of decision

---

## 8. MVP Scope

The first version of HallCare will focus on reporting complaints and tracking their progress.

### 8.1 Included in Version 1

- User login.
- Direct complaint submission by students.
- Complaint submission by porters on behalf of students.
- Entry of physical repair notebook complaints by porters.
- A unique reference number for every complaint.
- A page where hall administrators can view complaints.
- Repair status updates entered by the hall administrator.
- Recording delays caused by unavailable materials, pending approval, or waiting for collection or signature.
- A way for students to check their own complaints.
- A history of repair updates.
- Basic filtering of complaints.
- A way for students to request that completed complaints be reopened.
- Administrator review of reopening requests.

### 8.2 Not Included in Version 1

- **Full procurement management:** The exact procurement process is not yet clear, so HallCare will only record material-related updates.
- **Automatic approval of material requests:** Approval decisions will remain with the relevant university offices.
- **Buying or releasing materials:** HallCare will not handle purchases or control the central store.
- **Full stock management:** The system will not manage all the materials in the university store.
- **GPS tracking of maintenance workers:** This is not needed for the main purpose of the first version.
- **Automatic assignment of maintenance workers:** The current process needs to be understood better before adding this feature.
- **AI-based fault detection:** This is not needed for reporting and tracking repairs.
- **A separate mobile application:** The first version will be a website designed to work on phones and computers.

These features can be considered in future versions if there is a clear need for them.

---

## 9. Success Metrics

The following checks can help show whether HallCare is working:

1. **Complaint submission:** Check whether students and authorised staff can successfully submit complaints.
2. **Complaint tracking:** Check whether students can view the current status of their own complaints.
3. **Status updates:** Check whether updates show who entered them and when they were entered. Where possible, also check the time the event happened.
4. **Pending repairs:** Check whether hall administrators can easily find complaints that are still pending.
5. **Material delays:** Check whether the system shows which repairs are waiting for materials and how long they have been waiting.
6. **Completed repairs:** Check whether completed complaints remain available for future reference.
7. **Reopened complaints:** Check whether students can request reopening and whether administrators can review those requests.

The system should make it easier to record and follow up on complaints. However, it cannot guarantee that repairs will become faster because some delays depend on materials and approvals from other offices. Any claim that repair times have improved will need to be checked against real records collected before and after the system is used.

---

## 10. Risks and Assumptions

### 10.1 Risks

| Risk | Possible response |
|---|---|
| Porters may forget to enter complaints from the physical notebook. | Make complaint entry simple and agree who is responsible for entering each notebook report. |
| Hall administrators may not have time to update every repair. | Keep updates short and record only the important information. |
| Maintenance workers may delay communicating their progress. | Agree on a simple way for them to tell the hall administrator when a repair changes stage. |
| Materials may still take a long time to arrive. | Show clearly when a repair is waiting for materials and record the reason. |
| Students may provide incomplete information. | Make important fields compulsory when a complaint is submitted. |
| The physical repair notebook may continue to be used. | Keep a clear process for porters to enter notebook complaints into HallCare. |
| Unauthorised people may access complaints. | Use user accounts and role-based access. |
| Updates may be entered later than the actual event. | Record both the event time and the time the update is entered. |

### 10.2 Assumptions

- Students will have access to phones or computers to report complaints.
- Porters will be able to enter complaints from the physical repair notebook. This role still needs to be confirmed with porters.
- Hall administrators will review complaints and enter repair updates.
- Maintenance workers will communicate progress to the hall administrator.
- Procurement and store personnel will provide information about materials when needed, even if they do not use HallCare directly.
- HallCare may be used alongside the existing repair notebook at the beginning.
- Students will be able to ask for a completed complaint to be reopened if the problem has not been fixed.
