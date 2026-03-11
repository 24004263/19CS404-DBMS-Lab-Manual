# ER Diagram Workshop – Submission Template
# Name:p.pramisha
# Reg no:21222423203

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:
<img width="1111" height="793" alt="image" src="https://github.com/user-attachments/assets/e00430cf-ca03-4465-9d38-08aafec5db93" />


### Entities and Attributes
<img width="1139" height="300" alt="image" src="https://github.com/user-attachments/assets/ac8f9c4a-e6dc-4561-8477-fcbeb1196182" />

### Relationships and Constraints
<img width="966" height="337" alt="image" src="https://github.com/user-attachments/assets/5edd8182-d301-4cce-8763-9a73fcbb05a3" />

### Assumptions
1.A member can join multiple programs.
2.Trainers can be assigned to multiple programs.
3.Personal training sessions always involve one trainer and one member.

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
<img width="1110" height="768" alt="image" src="https://github.com/user-attachments/assets/17006564-ad82-4970-9a9f-2a59cdd5b6e5" />



### Entities and Attributes
<img width="1088" height="351" alt="image" src="https://github.com/user-attachments/assets/950f5fdf-d1ca-462c-97d2-dd2e132ab33f" />

### Relationships and Constraints
<img width="1061" height="310" alt="image" src="https://github.com/user-attachments/assets/b0dc0eb9-e6a7-4a68-bba2-aa34482bb577" />

### Assumptions
1.A member can borrow multiple books, but each loan entry is for one book at a time.
2.FineAmount is calculated separately and stored in the Loan entity.
3.A room can host many events but an event can take place in only one room.

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:
<img width="1301" height="919" alt="image" src="https://github.com/user-attachments/assets/b0e9131e-9925-4081-9b7f-b6af054af73e" />


### Entities and Attributes
<img width="1161" height="359" alt="image" src="https://github.com/user-attachments/assets/6dbe84c1-eb08-4c79-84a3-6865b4d3d278" />


### Relationships and Constraints
<img width="922" height="355" alt="image" src="https://github.com/user-attachments/assets/7f9b9d49-bc58-4dce-8433-68099ff8440e" />


### Assumptions

1.A customer may or may not make a reservation before ordering.

2.Each order contains one dish per entry (multiple dishes = multiple order entries).

3.Billing is done per reservation, not per individual order.

4.A waiter can serve multiple orders but an order is handled by exactly one waiter.

# RESULT
Those the ER DIAGRAM is implemented successfully.
