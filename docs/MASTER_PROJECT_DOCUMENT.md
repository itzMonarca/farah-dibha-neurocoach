# FARAH DIBHA NEUROCOACH

## Master Project Document

Version: 1.0
Status: Planning
Timezone: Africa/Maputo
Primary Language: Portuguese

---


# FARAH DIBHA NEUROCOACH

## Master Project Document

Version: 1.0
Status: Planning
Timezone: Africa/Maputo
Primary Language: Portuguese

---

## 1. Project Overview

### 1.1 Project Identity

Official Name: Farah Dibha Neurocoach

Project Slug: farah-dibha-neurocoach

Official Email: farah.dibha.mz@gmail.com

WhatsApp: +258 84 787 9208

Instagram: https://www.instagram.com/farah_dibha?rpxt=M3NlYXg5NWloeGY1

### 1.2 Project Purpose

Create a professional website and online booking platform for Farah Dibha Neurocoach.

The platform must allow clients to:

- Learn about Farah and her services.
- View individual sessions and packages.
- Check available dates and times.
- Book individual sessions or multiple-session packages.
- Submit payment proof.
- Recover pending reservations using SMS OTP.
- Reschedule or cancel reservations according to the booking rules.
- Receive booking confirmations and reminders.

Farah must have a private administration dashboard to manage clients, reservations, payments, availability, packages and notifications.

### 1.3 Professional Positioning

The website represents a non-clinical neurocoaching, psychoeducation and personal development service.

The platform must not present Farah as a clinical psychologist or promise medical diagnosis, treatment or guaranteed clinical outcomes.

All professional qualifications, certificates, service descriptions and claims must be verified before publication.

### 1.4 Technical Environment

Frontend: Next.js

Language: TypeScript

Repository: GitHub

Hosting and deployment: Vercel

Database and backend services: Supabase

Timezone: Africa/Maputo

Responsive support: iPhone, Android, tablet and desktop.

### 1.5 Design Direction

The visual identity must be elegant, minimal, professional and sophisticated.

Brand colors:

- #0B132B
- #1C2541
- #3A506B
- #5BC0DE
- #F4D6B0

The official logo must preserve its original drawing, proportions and typography.

The website should prioritize strong imagery, generous spacing, clear typography and subtle animations.

---

## 2. Business Requirements

### 2.1 Services

The website must present Farah's services and allow clients to request individual sessions.

Session duration: 60 minutes.

Available modalities:

- Online.
- In person in Maputo.

Online sessions are conducted through WhatsApp video calls.

The exact service list and professional descriptions require confirmation from Farah before publication.

### 2.2 Individual Session Pricing

Individual session price: 1,850 MZN.

### 2.3 Packages

Essential:
- 4 sessions.
- Price: 6,800 MZN.
- Description: Estratégias práticas para começar a transformar.

Transformation:
- 8 sessions.
- Price: 12,950 MZN.
- Badge: Mais escolhido.
- Description: Transformação profunda da mente, emoções e hábitos.

Evolution:
- 12 sessions.
- Price: 18,500 MZN.
- Description: Evolução contínua com foco em resultados reais e duradouros.

Package validity periods must be configurable by the administrator. Exact validity periods are pending confirmation.

### 2.4 Payment Methods

Initial payment method: M-Pesa.

Future payment method: Volet.

Clients must submit payment proof.

Payments must be manually reviewed and confirmed by Farah.

The system must never automatically mark a payment as confirmed merely because proof was uploaded.

### 2.5 Administrative Requirements

Farah must be able to:

- Manage reservations.
- Confirm or reject payments.
- Manage availability.
- Block specific dates and times.
- Configure package validity.
- Manage session prices and packages.
- View client history.
- Manage reviews.
- Receive operational notifications.
- Manage institutional requests.

### 2.6 Additional Website Sections

The website must include:

- About Farah.
- Services.
- Individual sessions.
- Packages.
- Booking system.
- Testimonials and reviews.
- Talks and workshops.
- Institutional and partnership requests.
- Contact information.

### 2.7 Pending Business Information

The following details require confirmation before publication:

- Final service list.
- Exact description and scope of Neurocientific Therapy, if offered.
- Professional qualifications and certificates.
- Exact in-person location.
- Working hours.
- Package validity periods.
- M-Pesa receiving details and payment instructions.
- Cancellation, lateness and no-show policies.
- Privacy policy and terms of service.
- Consent for publishing client photos, videos and testimonials.


## 3. Website Architecture

### 3.1 General Structure

The platform will consist of two main environments:

1. Public Website — accessible to visitors and clients.
2. Private Admin Dashboard — accessible only to authorized administrators.

The public website and admin dashboard must use the same backend and database while maintaining separate access permissions.

### 3.2 Public Website Pages

The public website must include the following pages or sections:

#### A. Home

Purpose:
Introduce Farah Dibha Neurocoach and communicate the brand's identity.

Content:
- Hero section with the official brand identity.
- Short introduction to Farah.
- Main services overview.
- Individual session and package highlights.
- Selected testimonials.
- Clear booking call to action.

#### B. About Farah

Purpose:
Present Farah's professional background and approach.

Content:
- Professional introduction.
- Biography.
- Verified qualifications and certifications.
- Coaching philosophy and approach.
- Professional photograph.

All professional information must be approved by Farah before publication.

#### C. Services

Purpose:
Present the services offered.

Content:
- Service descriptions.
- Session format.
- Online and in-person availability.
- Session duration.
- Relevant booking actions.

The final service list and descriptions must be confirmed before publication.

#### D. Individual Sessions

Purpose:
Allow clients to understand and book individual sessions.

Content:
- Session information.
- Price: 1,850 MZN.
- Duration: 60 minutes.
- Online or in-person options.
- Booking calendar and time selection.

#### E. Packages

Purpose:
Present the available multi-session packages.

Content:
- Essential: 4 sessions — 6,800 MZN.
- Transformation: 8 sessions — 12,950 MZN.
- Evolution: 12 sessions — 18,500 MZN.
- Package descriptions.
- Package validity information.
- Package booking action.

The package booking process must allow clients to select all required session dates and times before submitting the reservation.

#### F. Booking

Purpose:
Provide the complete reservation experience.

The booking process must support two distinct flows:

1. Individual session booking.
2. Package booking.

The system must display available dates and times according to the applicable booking rules.

The booking process must include:
- Client information.
- Phone number.
- Optional email address.
- Session type and modality.
- Date and time selection.
- Reservation summary.
- Payment instructions.
- Payment proof submission.

The backend must validate availability and all booking restrictions before confirming or temporarily holding any selected time.

#### G. Testimonials and Reviews

Purpose:
Display approved client feedback.

Content:
- Approved written reviews.
- Client ratings, if enabled.
- Approved photographs or videos, when consent has been obtained.

Only eligible reviews that have been approved for publication may appear publicly.

#### H. Talks and Workshops

Purpose:
Present Farah's talks, workshops and educational activities.

Content:
- Available talks and workshops.
- Descriptions.
- Photographs or videos, when available.
- Inquiry or participation request action.

#### I. Institutional and Partnership Requests

Purpose:
Allow companies, institutions and organizations to contact Farah.

The request form must collect:
- Organization name.
- Event or collaboration type.
- Preferred date.
- Contact information.
- Message.

Each submission must be stored and generate an administrative notification.

#### J. Contact

Purpose:
Provide direct contact channels.

Content:
- WhatsApp contact.
- Email address.
- Instagram profile.
- Other approved contact information.

### 3.3 Client Reservation Access

Clients must have a way to recover and access their reservations without requiring a traditional password-based account.

The recovery process must use:
- Registered phone number.
- SMS one-time password (OTP).
- Verification before displaying reservation information.

The system must only allow access to reservations associated with the verified phone number.

### 3.4 Private Admin Dashboard

The administration environment must be private and accessible only to authorized administrators.

It must include the following main areas:

#### A. Dashboard Overview
- Upcoming sessions.
- Pending reservations.
- Pending payment reviews.
- Recent activity.
- Important notifications.

#### B. Reservations
- View individual reservations.
- View package reservations.
- View all sessions belonging to each package.
- Confirm reservation status.
- Review reservation history.
- Manage cancellations and changes.

#### C. Payments
- View submitted payment proofs.
- Confirm payments manually.
- Reject payments with a recorded reason.
- View payment history.

#### D. Calendar and Availability
- View scheduled sessions.
- Configure working hours.
- Block specific dates and times.
- Block entire days.
- Manage holidays, breaks and vacations.

#### E. Services and Packages
- Manage service descriptions.
- Update individual session prices.
- Manage package prices.
- Configure package validity periods.
- Enable or disable offers.

#### F. Clients
- View client information.
- View reservation history.
- View package sessions and remaining sessions.
- Access relevant client records according to permissions.

#### G. Reviews
- View submitted reviews.
- Approve or reject reviews.
- Control which reviews are publicly displayed.

#### H. Institutional Requests
- View submitted requests.
- Update request status.
- Review organization and event information.

#### I. Notifications
- View operational notifications.
- Review notification delivery status.
- Identify failed notifications.

#### J. Settings
- Manage administrative settings.
- Configure contact information.
- Configure business hours.
- Manage other permitted platform settings.

### 3.5 Navigation

The public website must have clear and simple navigation.

Main navigation destinations:
- Home.
- About.
- Services.
- Packages.
- Talks and Workshops.
- Contact.

The booking action must remain easy to find throughout the website.

Mobile navigation must be optimized for touch interaction and smaller screens.

The admin dashboard must have its own navigation, separate from the public website.

### 3.6 Responsive Design

The website must adapt to:
- Mobile phones.
- Tablets.
- Desktop computers.

Mobile experience must be treated as a priority.

All forms, calendars, booking controls and administrative functions must remain usable on mobile devices.

### 3.7 Language

The initial website language will be Portuguese.

The architecture should allow additional languages to be introduced in the future without requiring a complete rebuild.

### 3.8 Architecture Principles

The platform must follow these principles:

- Separate public and administrative environments.
- Reusable frontend components.
- Clear separation between presentation and business logic.
- Secure communication with Supabase.
- Server-side validation of critical operations.
- Responsive design.
- Accessible forms and navigation.
- Consistent user experience.
- No sensitive administrative information exposed publicly.

The booking and payment rules must be enforced by the backend, not only by frontend interface restrictions.

## 4. User Roles and Permissions

### 4.1 General Access Model

The platform must use role-based access control (RBAC).

Every operation involving reservations, payments, client information, availability or administrative settings must be authorized by the backend.

Frontend restrictions alone are not sufficient to protect sensitive information.

The system must distinguish between:

1. Public visitors.
2. Clients.
3. Administrators.

### 4.2 Public Visitors

Public visitors do not need an account to browse the website.

They may:
- View public website pages.
- View services and packages.
- View published prices.
- View available booking options.
- Submit institutional requests.
- Start a reservation.

They must not:
- Access private client information.
- View payment proofs.
- View other clients' reservations.
- Access administrative pages.
- Modify availability or business settings.

### 4.3 Clients

Clients do not require a permanent password-based account.

They must verify their phone number through SMS OTP when recovering an existing reservation.

Clients may:
- Create individual reservations.
- Create package reservations.
- Submit payment proofs.
- Recover eligible reservations using phone verification.
- View their own reservation information.
- View their own payment status.
- Request cancellation according to the applicable rules.
- Reschedule eligible sessions according to the applicable rules.
- Submit reviews when eligible.

Clients must not:
- View another client's information.
- Access another client's reservations.
- View private payment proofs belonging to other clients.
- Confirm their own payments.
- Modify administrative settings.
- Change another client's reservation.
- Access the admin dashboard.

### 4.4 Administrator

The administrator is Farah Dibha.

The administrator must authenticate through a secure administrative login.

The administrator may:
- View and manage reservations.
- View client information.
- Review payment proofs.
- Confirm or reject payments manually.
- Manage availability.
- Create availability blocks.
- Manage services and packages.
- Configure package validity.
- Manage reviews.
- Manage institutional requests.
- View operational notifications.
- Access administrative reports.
- Manage permitted platform settings.

Administrative permissions must be verified server-side.

### 4.5 Administrative Account Protection

The administrator account must follow these security requirements:

- Public users must never be able to register as administrators.
- Administrative access must be explicitly authorized.
- Administrative permissions must be stored and validated securely.
- The administrator must not receive permissions merely by creating a normal client account.
- Administrative actions must be recorded in an audit log.
- Sensitive administrative operations must require an authenticated and authorized session.

### 4.6 Reservation Ownership

Every reservation must be associated with a client record.

Every package session must be associated with its parent package reservation.

Clients may only access reservations associated with their verified phone number.

The backend must validate ownership before allowing any client operation.

### 4.7 Payment Permissions

Clients may:
- Upload payment proof.
- View the payment status of their own reservations.

Only authorized administrators may:
- Confirm payments.
- Reject payments.
- Change payment verification status.

Uploading a payment proof must never automatically confirm a payment.

### 4.8 Availability Permissions

Only authorized administrators may:
- Configure regular working hours.
- Create or remove availability blocks.
- Block entire days.
- Configure holidays and breaks.

Clients may only select time slots returned as available by the backend.

Clients must never directly modify availability records.

### 4.9 Data Privacy

The system must follow the principle of least privilege.

Each role must only receive the information and permissions necessary to perform its intended operations.

Sensitive client information, payment proofs and administrative records must never be exposed through public database access.

### 4.10 Audit Logging

The platform must record important administrative actions, including:

- Payment confirmation or rejection.
- Reservation cancellation.
- Reservation changes.
- Availability changes.
- Package and price changes.
- Administrative permission changes.

Audit records must include:
- Administrator identifier.
- Action performed.
- Affected record.
- Date and time.
- Relevant action details.

Audit logs must not be editable by ordinary clients.

## 5. Booking System

### 5.1 General Booking Architecture

The platform must support two distinct reservation types:

1. Individual session reservations.
2. Multiple-session package reservations.

These reservation types must have separate business logic, validation rules and payment deadlines.

The system must use a centralized booking engine to manage availability, prevent scheduling conflicts and enforce all reservation rules.

### 5.2 Reservation Data Structure

The database architecture must distinguish between a reservation and its scheduled sessions.

The proposed structure is:

- reservations: stores the main reservation operation and its overall status.
- reservation_sessions: stores each individual scheduled session associated with a reservation.

An individual reservation will normally contain one scheduled session.

A package reservation will contain multiple scheduled sessions linked to the same parent reservation.

Each package session must have its own:
- Date.
- Start time.
- End time.
- Session status.
- Reminder schedule.

This structure must allow the platform to manage package sessions independently while preserving their relationship with the parent package reservation.

### 5.3 Reservation Lifecycle

The general reservation lifecycle must support the following stages:

1. Client selects a service or package.
2. Client selects the required date and time options.
3. Client submits the reservation request.
4. Backend validates the request and availability.
5. Available time slots are temporarily held.
6. Reservation is created with pending payment status.
7. Client receives payment instructions.
8. Client submits payment proof.
9. Farah manually reviews the payment.
10. Reservation is confirmed or rejected.

The system must also support automatic expiration when the applicable payment deadline is reached.

### 5.4 Temporary Slot Reservation

When a reservation is successfully created, the selected time slots must be temporarily held.

A temporary reservation must prevent another client from booking the same time slots while payment is pending.

The backend must guarantee that two clients cannot successfully reserve overlapping time slots.

Availability validation and slot allocation must be performed atomically.

If any required slot is unavailable, the backend must reject the complete reservation operation.

For package reservations, all requested sessions must be held together or none of them must be held.

### 5.5 Reservation Validation

Before creating a reservation, the backend must validate:

- Reservation type.
- Client information.
- Service or package availability.
- Session duration.
- Date and time restrictions.
- Minimum booking notice.
- Maximum booking horizon.
- Existing reservation conflicts.
- Availability blocks.
- Working hours.
- Existing active reservations where applicable.

The frontend must never be considered the final authority for booking validation.

### 5.6 Date and Time Management

The official business timezone is:

Africa/Maputo

All reservation dates, deadlines and reminders must follow this timezone.

The system must store timestamps consistently and convert them correctly when displaying dates and times.

The platform must account for:
- Day boundaries.
- Timezone conversion.
- Daylight-saving changes where applicable.
- Correct calculation of payment deadlines.
- Correct calculation of reminder times.

### 5.7 Reservation Status Management

The system must support clearly defined reservation statuses.

Proposed reservation statuses:

- pending_payment
- confirmed
- expired
- cancelled
- completed

Proposed scheduled session statuses:

- scheduled
- rescheduled
- cancelled
- completed

The final status model must be reviewed during database architecture design.

A payment being submitted must not automatically change a reservation to confirmed.

Only successful manual payment verification by Farah may confirm a reservation.

### 5.8 Payment Deadlines

The payment deadline depends on the reservation type:

Individual session:
- 24 hours after the provisional reservation is created.

Package:
- 4 days (96 hours) after the provisional package reservation is created.

If Farah does not manually confirm payment before the applicable deadline, the reservation must expire automatically.

Uploading payment proof does not stop or extend the payment deadline.

### 5.9 Expiration and Slot Release

When a pending reservation expires:

- Its reservation status must become expired.
- Its temporary time slots must be released.
- The released slots must become available for other clients.
- Pending payment verification must no longer allow confirmation of the expired reservation.
- Relevant pending notifications must be cancelled or updated.

For package reservations, expiration must release every session slot belonging to the package.

Package expiration must be an all-or-nothing operation.

The system must never leave some package sessions reserved while releasing others because of payment expiration.

### 5.10 Cancellation and Rescheduling

The platform must support client cancellation and rescheduling according to the applicable booking rules.

Clients may request cancellation or rescheduling only when at least 24 hours remain before the affected session.

Rescheduling must:
- Check the new requested time.
- Validate all applicable restrictions.
- Verify availability.
- Atomically allocate the new slot.
- Release the previous slot.
- Update the scheduled session.
- Cancel old reminders.
- Create new reminders.
- Notify Farah.

Rescheduling does not require manual approval from Farah when all backend validations succeed.

### 5.11 Booking Conflicts

The system must prevent:

- Two clients from reserving the same time slot.
- A client from booking an overlapping session.
- Reservations outside configured working hours.
- Reservations during blocked periods.
- Reservations that violate minimum or maximum booking notice.
- Duplicate reservation submissions caused by repeated clicks or network retries.

The backend must use database-level constraints and transactional operations where appropriate.

### 5.12 Notifications

Important reservation events must generate the appropriate notifications.

These include:
- New provisional reservation.
- Payment proof submitted.
- Payment confirmed.
- Payment rejected.
- Reservation expired.
- Reservation cancelled.
- Session rescheduled.
- New package reservation.
- Package expiration.

Notifications must be associated with the relevant reservation or scheduled session.

Notification delivery failures must not corrupt reservation or payment status.

### 5.13 Booking Security

The booking engine must:

- Validate every operation on the server.
- Verify client ownership.
- Prevent unauthorized status changes.
- Prevent clients from confirming payments.
- Protect against duplicate submissions.
- Prevent unauthorized access to reservation details.
- Record important administrative actions.
- Use secure database transactions for critical booking operations.

### 5.14 Booking Rules Consistency

The booking engine must apply the specific rules defined in:

- Section 6: Individual Sessions.
- Section 7: Packages and Multiple Sessions.
- Section 8: Payment System.
- Section 9: Availability Management.
- Section 10: Notifications and Reminders.

If any general booking rule conflicts with a more specific rule, the applicable reservation type's specific business rules must take precedence.

### 5.15 Pending Business Rules

The following decisions must be confirmed before implementation:

- Whether a client may have an active individual reservation and an active package simultaneously.
- Whether a client may have multiple active packages simultaneously.
- Whether any additional restriction is required for overlapping reservations belonging to the same client.

These decisions must be documented before finalizing the database constraints.

## 6. Individual Sessions

### 6.1 General Rules

Individual sessions are single-session reservations.

Each individual session must have:

- One client.
- One scheduled date.
- One start time.
- One end time.
- A duration of 60 minutes.
- One selected service.
- One payment record.

The individual session price is 1,850 MZN.

Available modalities:

- Online.
- In person in Maputo.

Online sessions are conducted through WhatsApp video calls.

### 6.2 Minimum Booking Notice

Individual sessions must be booked at least 3 days in advance.

The system must calculate the minimum booking notice from the exact moment the client submits the reservation.

Reservations with less than 72 hours of advance notice must be rejected.

The backend must enforce this rule.

### 6.3 Booking Process

The individual booking process must follow these steps:

1. Client selects an individual session.
2. Client selects the preferred modality.
3. Client provides the required personal information.
4. Client selects an available date.
5. Client selects an available time.
6. Backend validates the booking restrictions.
7. Backend checks availability.
8. The selected time slot is temporarily held.
9. A provisional reservation is created.
10. Client receives payment instructions.

The reservation must initially have pending payment status.

### 6.4 One Active Individual Reservation Per Client

Each client may have only one active individual session reservation at a time.

A client cannot create another individual session reservation while an existing individual session is still active and has not been completed.

The restriction must apply regardless of whether the client attempts to use another device or browser.

The backend must enforce this rule using the verified client identity.

Once the previous individual session is completed, the client may create another individual reservation.

An expired or cancelled reservation must not permanently prevent the client from booking again.

### 6.5 Payment Deadline

After a provisional individual reservation is created, the client has exactly 24 hours to complete payment.

The client must submit payment proof through the website.

Payment confirmation must always be performed manually by Farah.

Uploading payment proof does not confirm the reservation.

If Farah does not manually confirm the payment within 24 hours after the provisional reservation was created:

- The reservation must automatically expire.
- The selected time slot must be released.
- The client must be informed that the reservation expired.
- The slot must become available to other clients.

The deadline must not be extended merely because payment proof was submitted.

### 6.6 Payment Verification

Farah must be able to:

- View the submitted payment proof.
- Review the payment information.
- Confirm the payment.
- Reject the payment.

When payment is confirmed before the deadline:

- Reservation status changes to confirmed.
- The scheduled session becomes confirmed.
- The client receives a confirmation notification.
- Farah receives the relevant notification.
- The session reminder schedule is activated.

When payment is rejected:

- The client must be informed.
- The rejection reason should be recorded.
- The reservation must remain subject to its original payment deadline.

### 6.7 Cancellation Rules

Clients may cancel an individual session up to 24 hours before its scheduled start time.

Cancellation must be rejected when fewer than 24 hours remain before the session.

When a valid cancellation is completed:

- Reservation status changes to cancelled.
- The scheduled time slot is released.
- Pending reminders for that session are cancelled.
- The client receives a cancellation notification.
- Farah receives a cancellation notification.

Cancellation must be processed securely by the backend.

### 6.8 Rescheduling Rules

Clients may reschedule an individual session up to 24 hours before its scheduled start time.

Rescheduling must not require manual approval from Farah.

The client must select another available date and time.

The backend must:

1. Verify that the original session is eligible for rescheduling.
2. Validate the new date and time.
3. Check the applicable minimum booking notice.
4. Verify that the new slot is available.
5. Atomically allocate the new slot.
6. Release the original slot.
7. Update the scheduled session.
8. Cancel the original reminders.
9. Create new reminders.
10. Notify Farah about the change.
11. Notify the client about the updated reservation.

If the new slot is unavailable or any validation fails, the original reservation must remain unchanged.

### 6.9 Rescheduling Restrictions

A rescheduled session must still respect the minimum booking notice of 3 days.

The new date and time must be within Farah's configured working hours and must not conflict with an availability block or another reservation.

A rescheduling operation must never temporarily leave the client without the original reservation if the new slot cannot be secured.

### 6.10 Session Reminders

Both the client and Farah must receive reminders for every confirmed individual session.

The system must generate exactly three scheduled reminders:

1. 24 hours before the session.
2. 1 hour before the session.
3. Exactly at the scheduled session start time.

There must be no 30-minute reminder.

Each reminder must contain the correct session date, time and relevant information.

### 6.11 Reminder Management

When a session is rescheduled:

- All pending reminders associated with the previous schedule must be cancelled.
- Three new reminders must be scheduled using the updated date and time.

When a session is cancelled:

- All pending reminders must be cancelled.

Reminder processing must prevent duplicate notifications.

Notification delivery failures must be recorded and must not change the reservation status.

### 6.12 Session Completion

After the scheduled session has taken place, Farah must be able to mark it as completed.

The system must record:

- Completion status.
- Completion date and time.
- Relevant administrative information, when necessary.

Only completed sessions may become eligible for the client review process, subject to the review and moderation rules.

### 6.13 Administrative Management

Farah must be able to:

- View individual session reservations.
- View client information.
- Review payment status.
- Confirm or reject payments.
- View scheduled dates and times.
- View rescheduling history.
- View cancellation history.
- Mark sessions as completed.
- Review notification status.

All important administrative changes must be recorded in the audit log.

### 6.14 Security and Data Integrity

The individual booking system must guarantee:

- One active individual reservation per client.
- No overlapping confirmed or temporarily held time slots.
- No booking with less than 3 days of advance notice.
- No unauthorized cancellation or rescheduling.
- No automatic payment confirmation.
- No confirmation after the payment deadline.
- Atomic rescheduling operations.
- Correct cancellation and recreation of reminders.

All critical rules must be enforced by the backend and database.

## 7. Packages and Multiple Sessions

### 7.1 General Architecture

Packages allow clients to purchase multiple sessions through one reservation operation.

The platform must support three packages:

Essential:
- 4 sessions.
- Price: 6,800 MZN.
- Description: Estratégias práticas para começar a transformar.

Transformation:
- 8 sessions.
- Price: 12,950 MZN.
- Badge: Mais escolhido.
- Description: Transformação profunda da mente, emoções e hábitos.

Evolution:
- 12 sessions.
- Price: 18,500 MZN.
- Description: Evolução contínua com foco em resultados reais e duradouros.

Package prices apply regardless of whether sessions are online or in person.

### 7.2 Package Booking Process

The client must select the package and schedule all included sessions during the same booking process.

The booking process must follow these steps:

1. Client selects a package.
2. The system displays the number of sessions included.
3. Client selects the preferred modality.
4. Client provides the required personal information.
5. Client selects the date and time for the first session.
6. Client selects the date and time for every remaining session.
7. The system displays a complete booking summary.
8. The backend validates every selected session.
9. The backend checks availability for all selected time slots.
10. All selected slots are temporarily held together.
11. One parent package reservation is created.
12. Individual scheduled sessions are created and linked to the parent reservation.
13. Client receives the package payment instructions.

The client must not be allowed to submit a package reservation with missing session dates or times.

### 7.3 Package Session Scheduling Window

Every session included in a package must be scheduled within the following limits:

- Minimum advance booking: 7 days.
- Maximum advance booking: 1 month.

These limits apply individually to every selected session.

The backend must validate the date of each session independently.

A package must be rejected if even one selected session violates these scheduling limits.

### 7.4 All-or-Nothing Slot Allocation

All sessions included in a package must be temporarily reserved together.

The system must use an atomic database operation or transaction to guarantee that:

- Every selected time slot is available.
- Every selected time slot is held successfully.
- No other client can reserve those slots while the package is pending payment.

If any selected time slot is unavailable or invalid:

- The entire package reservation operation must fail.
- No partial package reservation may remain.
- No selected time slot may remain unnecessarily blocked.

The backend must never create a package with only some of its required sessions successfully allocated.

### 7.5 Parent Reservation and Child Sessions

Each package purchase must create:

- One parent reservation.
- Multiple child reservation sessions.
- One package payment record.

The number of child sessions must match the package:

- Essential: 4 child sessions.
- Transformation: 8 child sessions.
- Evolution: 12 child sessions.

Every child session must be linked to its parent reservation.

Each child session must have its own:

- Scheduled date.
- Start time.
- End time.
- Modality.
- Session status.
- Reminder schedule.
- Rescheduling history.

The parent reservation must maintain the overall package status.

### 7.6 Package Payment Deadline

The client has exactly 4 days (96 hours) after the provisional package reservation is created to complete payment.

The client must submit payment proof.

Farah must manually review and confirm the payment.

Uploading payment proof does not confirm the package or extend its payment deadline.

If Farah does not manually confirm the payment within 96 hours:

- The parent package reservation must expire.
- Every child session must become expired or otherwise unavailable for scheduling.
- Every temporarily held time slot must be released.
- All pending reminders associated with the package sessions must be cancelled.
- The client must receive an expiration notification.
- Farah must receive the relevant operational notification.

Expiration must be processed as one atomic operation.

### 7.7 Package Payment Confirmation

When Farah manually confirms payment before the 96-hour deadline:

- The parent reservation becomes confirmed.
- Every child session becomes confirmed.
- All selected time slots remain reserved.
- The package becomes active.
- The client receives confirmation.
- Farah receives confirmation.
- Reminder schedules are activated for every child session.

The system must never confirm only part of a package.

### 7.8 Payment Rejection

If Farah rejects the submitted payment proof:

- The rejection must be recorded.
- The client must be informed.
- The parent reservation remains subject to its original 96-hour payment deadline.
- All selected slots remain temporarily held until confirmation, cancellation or expiration.

A rejected payment must not automatically restart or extend the payment deadline.

### 7.9 Package Session Management

After package confirmation, each scheduled session must be manageable independently.

Farah must be able to:

- View all sessions belonging to a package.
- View the parent package reservation.
- View the client's package history.
- Identify completed sessions.
- Identify upcoming sessions.
- Identify cancelled or rescheduled sessions.
- Mark individual sessions as completed.

Completing one child session must not complete the entire package.

The parent package must remain active while it still has sessions that have not been completed or otherwise resolved.

### 7.10 Remaining Session Counter

The client and Farah must be able to see the number of sessions remaining in a package.

The remaining session count must be calculated from the package's confirmed sessions and their completion status.

A session must only count as consumed when it has been marked as completed.

The system must not allow the remaining session count to become negative.

### 7.11 Package Rescheduling

Clients may reschedule an individual package session up to 24 hours before that session's scheduled start time.

Rescheduling one package session must not automatically change the dates or times of the other package sessions.

The backend must:

1. Verify that the package is confirmed and eligible.
2. Verify that the selected child session belongs to the client.
3. Check that at least 24 hours remain before the original session.
4. Validate the new date and time.
5. Check availability.
6. Secure the new slot atomically.
7. Release the original slot.
8. Update the child session.
9. Cancel the old reminders.
10. Create new reminders.
11. Notify Farah.
12. Notify the client.

If any validation fails, the original session must remain unchanged.

The rescheduling operation must preserve the parent package relationship.

### 7.12 Package Validity

Each package must have a configurable validity period.

Farah must be able to configure the validity period for each package through the administration dashboard.

The exact validity periods have not yet been confirmed and must remain pending until Farah provides the final values.

The system must store the package validity information and calculate the applicable expiration date.

Package validity must be distinct from the 96-hour payment deadline.

### 7.13 Package Session Reminders

Every confirmed child session must generate its own reminder schedule.

Both the client and Farah must receive reminders:

1. 24 hours before the session.
2. 1 hour before the session.
3. Exactly at the scheduled session start time.

These reminders must be generated separately for every session in the package.

For example, a package with 8 sessions must have 8 independent session reminder schedules.

There must be no 30-minute reminder.

### 7.14 Reminder Updates

When a package session is rescheduled:

- All pending reminders for its previous schedule must be cancelled.
- Three new reminders must be created for the updated schedule.
- Reminders for the other package sessions must remain unchanged.

When a package reservation expires or is cancelled:

- All relevant pending reminders must be cancelled.

The system must prevent duplicate reminders.

### 7.15 Package History

The platform must preserve the relationship between the package and all its sessions.

The client's history must display:

- Package name.
- Purchase date.
- Payment status.
- Package status.
- Total number of sessions.
- Completed sessions.
- Remaining sessions.
- Upcoming session dates.
- Rescheduled sessions.
- Cancelled sessions.
- Package validity information.

### 7.16 Administrative Management

Farah must be able to:

- View all package reservations.
- View every child session.
- Review package payments.
- Confirm or reject package payments.
- View the package's overall status.
- View completed and remaining sessions.
- Manage package validity.
- Review rescheduling history.
- View reminder delivery status.

All important administrative actions must be recorded in the audit log.

### 7.17 Security and Data Integrity

The package system must guarantee:

- All required sessions are selected before submission.
- All selected slots are validated together.
- No partial slot allocation.
- No partial payment confirmation.
- One parent reservation per package purchase.
- Correct parent-child session relationships.
- Correct 96-hour payment expiration.
- Atomic release of every slot upon expiration.
- Independent management of each child session.
- Correct remaining session calculation.
- Independent reminders for every session.
- Secure ownership validation.

All critical operations must be enforced by the backend and database.

### 7.18 Pending Business Decisions

The following decisions still require confirmation:

- Exact validity period for each package.
- Whether a client may have an active individual reservation and an active package simultaneously.
- Whether a client may have multiple active packages simultaneously.
- Whether package payment reminders should be sent before the 96-hour deadline.
- Whether any additional rules should apply when rescheduling a package session close to its package expiration date.

## 8. Payment System

### 8.1 General Payment Architecture

The platform must support secure payment management for:

- Individual sessions.
- Essential packages.
- Transformation packages.
- Evolution packages.

Every reservation must have an associated payment record.

Payment processing must be separate from reservation management while maintaining a clear relationship between payments and reservations.

### 8.2 Supported Payment Methods

Initial payment method:

- M-Pesa.

Future payment method:

- Volet.

The architecture must allow additional payment methods to be integrated in the future without rebuilding the entire payment system.

### 8.3 Payment Amounts

Individual session:
- 1,850 MZN.

Essential:
- 6,800 MZN.

Transformation:
- 12,950 MZN.

Evolution:
- 18,500 MZN.

The amount associated with a reservation must be recorded when the reservation is created.

Later price changes must not modify historical payment amounts.

All monetary values must be stored using an appropriate exact numeric representation, never floating-point arithmetic.

The currency is MZN.

### 8.4 Payment Instructions

After creating a provisional reservation, the client must receive payment instructions.

The instructions must include:

- Payment method.
- Receiving number or account details.
- Exact amount to pay.
- Payment reference or identification instructions.
- Instructions for submitting payment proof.

The M-Pesa receiving number and final payment instructions must be configurable and require confirmation from Farah before publication.

### 8.5 Payment Proof Submission

The client must be able to upload payment proof through the website.

Supported proof formats should include:

- JPEG.
- PNG.
- PDF.

The system must validate:

- File type.
- File size.
- File integrity.
- Reservation ownership.
- Reservation payment status.
- Applicable payment deadline.

Uploading proof must not automatically confirm payment.

### 8.6 Payment Proof Storage

Payment proofs must be stored in a private Supabase Storage bucket.

Proposed bucket:

payment-proofs

The bucket must not allow public access.

Only the client associated with the reservation and authorized administrators may access the relevant proof.

Access must use secure authorization and short-lived signed URLs or an equivalent protected server-side mechanism.

Payment proof paths must not expose sensitive client information.

### 8.7 Manual Payment Verification

All payments must be manually reviewed by Farah.

Farah must be able to:

- View the payment proof.
- View the associated reservation.
- View the expected payment amount.
- View the payment method.
- Confirm the payment.
- Reject the payment.
- Record a rejection reason.
- Review previous payment decisions.

Only an authorized administrator may change a payment to confirmed.

The system must never confirm payment simply because a file was uploaded.

### 8.8 Payment Statuses

The payment system must support the following statuses:

- pending
- proof_submitted
- confirmed
- rejected
- expired
- refunded

The final status transitions must be validated by the backend.

A rejected payment must remain subject to the original reservation payment deadline.

### 8.9 Payment Deadlines

Payment deadlines depend on the reservation type.

Individual sessions:
- 24 hours after provisional reservation creation.

Packages:
- 96 hours after provisional package reservation creation.

The payment deadline must be calculated using the exact reservation creation timestamp.

Uploading payment proof must not pause, reset or extend the deadline.

### 8.10 Payment Expiration

If Farah does not confirm payment before the applicable deadline:

- The payment process must be marked expired.
- The associated reservation must expire.
- The reserved time slots must be released.
- The client must be informed.
- Pending payment verification must no longer permit confirmation.

For packages, the entire package reservation and every selected session must expire together.

The payment expiration process must be safe against simultaneous confirmation and expiration attempts.

Only one valid final outcome may be applied.

### 8.11 Reservation Recovery

The website must include a reservation recovery feature for clients who need to return to an existing reservation and submit payment proof.

The recovery process must use:

1. Client enters the registered phone number.
2. System sends an SMS one-time password (OTP).
3. Client enters the received OTP.
4. Backend validates the code.
5. System identifies eligible reservations associated with the verified phone number.
6. Client accesses the relevant reservation.
7. Client submits payment proof if the reservation is still eligible.

The recovery process must not expose reservation information before successful phone verification.

Only reservations that are still eligible for payment recovery may be accessed for this purpose.

### 8.12 OTP Security

The OTP system must implement:

- Secure code generation.
- Secure code hashing before database storage.
- Short expiration period.
- Maximum verification attempts.
- Rate limiting.
- Resend restrictions.
- Invalidation of previous codes when a new code is issued.
- Single-use verification.
- Protection against brute-force attempts.
- Protection against phone number enumeration.

Proposed database table:

booking_recovery_codes

Suggested fields:

- id
- reservation_id
- phone_number
- code_hash
- expires_at
- attempts
- max_attempts
- consumed_at
- created_at

The exact OTP expiration period and resend limits must be finalized during security architecture design.

### 8.13 Payment History

The system must preserve payment history.

Each payment record should include:

- Reservation identifier.
- Payment method.
- Expected amount.
- Currency.
- Payment status.
- Proof storage reference.
- Submission timestamp.
- Verification timestamp.
- Administrator who reviewed the payment.
- Rejection reason, when applicable.

Historical payment records must not be silently overwritten.

Important payment changes must be recorded in the audit log.

### 8.14 Payment Notifications

The system must notify the relevant parties about important payment events.

Client notifications:
- Payment instructions.
- Proof successfully received.
- Payment confirmed.
- Payment rejected.
- Reservation payment expired.

Farah notifications:
- New reservation awaiting payment.
- Payment proof submitted.
- Payment deadline approaching, if a reminder schedule is approved.
- Reservation payment expired.

Payment reminder schedules remain pending confirmation.

### 8.15 Future Volet Integration

The architecture must allow Volet to become an additional payment method.

The future integration may support:

- Payment initiation.
- Payment status verification.
- Secure transaction references.
- Payment confirmation through an authorized integration.
- Transaction history.

Before implementation, the official Volet API, payment capabilities, webhook support and integration requirements must be reviewed.

The system must never trust an unverified client-side payment response.

Any future automatic payment confirmation must rely on authenticated server-to-server verification or a verified payment webhook.

### 8.16 Refund Management

The database architecture must allow refunds to be recorded in the future.

Refund handling must include:

- Original payment reference.
- Refund amount.
- Refund status.
- Refund date.
- Reason.
- Administrator responsible.

The exact refund policy and refund process remain pending confirmation from Farah.

### 8.17 Payment Security

The payment system must guarantee:

- Private payment proof storage.
- Secure access authorization.
- Manual M-Pesa payment verification.
- No automatic confirmation after proof upload.
- Immutable historical payment information.
- Correct payment deadlines.
- Protection against duplicate payment submissions.
- Protection against unauthorized payment status changes.
- Secure OTP recovery.
- Audit logging for administrative payment decisions.

All sensitive payment operations must be enforced by the backend.

### 8.18 Pending Payment Decisions

The following details require confirmation:

- M-Pesa receiving number.
- Final payment instructions.
- OTP expiration duration.
- OTP resend limits.
- Payment reminder schedule for individual sessions.
- Payment reminder schedule for packages.
- Refund policy.
- Future Volet integration requirements.
- Whether clients may submit a replacement proof after a rejection without creating a new reservation.

## 9. Availability Management

## 10. Notifications and Reminders

## 11. Authentication and Security

## 12. Database Architecture

## 13. Backend Architecture

## 14. Frontend Architecture

## 15. Admin Dashboard

## 16. External Integrations

## 17. Privacy and Data Protection

## 18. Testing Strategy

## 19. Deployment

## 20. Pending Decisions