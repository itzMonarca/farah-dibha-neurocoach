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

### 9.1 General Architecture

The platform must include a centralized availability management system.

The system must determine which dates and times can be reserved by clients.

Availability must consider:

- Farah's configured working hours.
- Session duration.
- Existing reservations.
- Pending reservations.
- Availability blocks.
- Booking restrictions.
- Reservation type.
- Minimum and maximum booking notice.

The backend must be the final authority when determining whether a time slot is available.

### 9.2 Administrative Working Hours

Farah must be able to configure her regular working hours through the private admin dashboard.

The configuration must support:

- Different working hours for different weekdays.
- Days when Farah does not work.
- Multiple working periods within the same day.
- Temporary changes to regular working hours.

Historical working hours have included Monday to Saturday, with online sessions only after 17:00.

These historical hours must not be treated as permanent rules. The final schedule must be configurable and confirmed by Farah.

### 9.3 Session Duration

The standard individual session duration is 60 minutes.

The availability engine must use the configured session duration when generating bookable time slots.

The system must prevent overlapping reservations.

The architecture should allow session duration to be configured for future services if necessary.

### 9.4 Session Modalities

The platform must support:

- Online sessions.
- In-person sessions in Maputo.

Farah must be able to configure which modalities are available during specific working periods.

For example, a working period may allow online sessions only.

The availability engine must only display time slots compatible with the selected modality.

### 9.5 Availability Blocks

The system must allow Farah to block availability whenever she cannot receive clients.

Supported block types must include:

- Full-day blocks.
- Multiple-day blocks.
- Specific time blocks.
- Breaks.
- Holidays.
- Vacations.
- Personal commitments.
- Temporary unavailability.

Availability blocks must be stored in the database.

Proposed database table:

availability_blocks

Suggested fields:

- id
- title
- block_type
- start_at
- end_at
- reason
- created_by
- created_at
- updated_at

The final schema must be defined during database architecture design.

### 9.6 Creating Availability Blocks

Farah must be able to:

- Select a date.
- Select a start time.
- Select an end time.
- Block an entire day.
- Block multiple consecutive days.
- Create a specific break.
- Add an optional description.
- Save or remove a block.

All date and time values must be interpreted using the Africa/Maputo timezone.

### 9.7 Availability Block Validation

Before creating an availability block, the backend must check whether it overlaps with existing reservations.

If a block overlaps with confirmed or temporarily held sessions, the system must not silently cancel or modify those reservations.

The administrator must receive clear information about the conflict.

Any required changes to existing reservations must follow the applicable cancellation or rescheduling rules.

### 9.8 Temporary Availability Changes

Farah must be able to modify her working hours temporarily without changing her regular weekly schedule.

Temporary changes must have clearly defined start and end dates.

When the temporary period ends, the regular schedule must become effective again.

The system must distinguish between:

- Regular weekly availability.
- Temporary schedule changes.
- Availability blocks.
- Existing reservations.

### 9.9 Available Time Slot Generation

The backend must generate available time slots using the configured schedule.

A time slot may only be displayed as available when:

- It falls within an allowed working period.
- The selected modality is supported.
- The full session duration fits within the working period.
- It does not overlap an availability block.
- It does not overlap another active reservation.
- It satisfies the applicable booking notice rules.

The frontend must display only slots returned by the backend.

### 9.10 Individual Session Restrictions

Individual sessions must respect:

- Minimum booking notice of 3 days.
- Session duration of 60 minutes.
- Configured working hours.
- Selected modality availability.
- Existing reservations.
- Availability blocks.

The backend must reject any individual reservation that violates these restrictions.

### 9.11 Package Session Restrictions

Every session in a package must respect:

- Minimum booking notice of 7 days.
- Maximum booking horizon of 1 month.
- Session duration of 60 minutes.
- Configured working hours.
- Selected modality availability.
- Existing reservations.
- Availability blocks.

The backend must validate every selected package session independently.

All package time slots must be allocated atomically.

### 9.12 Reservation Conflicts

The availability system must prevent:

- Double bookings.
- Overlapping sessions.
- Reservations during blocked periods.
- Reservations outside working hours.
- Reservations with unsupported modalities.
- Conflicts caused by simultaneous booking requests.

Critical availability checks and reservation allocation must be performed using secure database transactions or equivalent atomic operations.

### 9.13 Availability Updates

When Farah changes her working hours or creates an availability block:

- Future availability must be recalculated.
- Newly unavailable slots must no longer be offered.
- Existing reservations must remain protected.
- Conflicts with existing reservations must be identified.
- The system must not silently remove confirmed reservations.

Changes must be recorded in the administrative audit log.

### 9.14 Calendar Interface

The admin dashboard must include a calendar where Farah can:

- View upcoming sessions.
- View confirmed reservations.
- Identify pending reservations.
- View blocked periods.
- Create availability blocks.
- Modify working hours.
- Navigate between dates.
- Identify reservation conflicts.

The calendar must distinguish clearly between reservations and unavailable periods.

### 9.15 Timezone Management

The official timezone is:

Africa/Maputo

The system must:

- Store timestamps consistently.
- Display dates and times in the business timezone.
- Calculate booking deadlines correctly.
- Calculate availability correctly.
- Avoid timezone conversion errors.
- Handle daylight-saving changes where applicable.

### 9.16 Security and Permissions

Only authorized administrators may:

- Create availability blocks.
- Modify availability blocks.
- Delete availability blocks.
- Configure working hours.
- Change modality availability.
- Modify temporary schedules.

Clients may only view available time slots and select them during the booking process.

Clients must never directly modify availability records.

All administrative availability operations must be validated by the backend and recorded in the audit log.

### 9.17 Pending Availability Decisions

The following details require confirmation from Farah:

- Final weekly working hours.
- Specific online and in-person working periods.
- Break durations, if fixed.
- Whether any days should always remain unavailable.
- Whether different services will require different session durations in the future.

## 10. Notifications and Reminders

### 10.1 General Notification Architecture

The platform must include a centralized notification system.

Notifications must inform clients and Farah about important reservation, payment and scheduling events.

The notification architecture must support:

- Email.
- SMS.
- WhatsApp.

The actual providers must be selected and configured before production deployment.

Notification processing must be independent from the main reservation transaction.

A notification delivery failure must never corrupt reservation, payment or session data.

### 10.2 Notification Recipients

The system must support two main recipient types:

1. Clients.
2. Administrator (Farah).

Both recipients must receive the relevant notifications according to the event and notification rules.

### 10.3 Individual Session Reminders

Every confirmed individual session must generate exactly three scheduled reminders for both the client and Farah.

The reminders must be sent:

1. 24 hours before the scheduled session.
2. 1 hour before the scheduled session.
3. Exactly at the scheduled session start time.

There must be no 30-minute reminder.

Each reminder must contain:

- Client name, where appropriate.
- Session date.
- Session time.
- Session modality.
- Relevant session information.

All reminder times must follow the Africa/Maputo timezone.

### 10.4 Package Session Reminders

Every confirmed session belonging to a package must have its own independent reminder schedule.

Both the client and Farah must receive reminders:

1. 24 hours before that session.
2. 1 hour before that session.
3. Exactly at that session's scheduled start time.

The reminder system must process every child session independently.

For example, a package containing 12 sessions must generate three reminders for each of its 12 sessions, for both recipients.

Reminders must never be generated only for the first session of a package.

### 10.5 Reminder Scheduling

When a session becomes confirmed, the system must schedule its three reminders.

The system must store the scheduled delivery time and associate every reminder with the correct reservation and scheduled session.

The scheduling system must support:

- Creating reminders.
- Processing reminders when they become due.
- Recording delivery results.
- Retrying eligible failures.
- Cancelling outdated reminders.
- Preventing duplicate delivery.

A scheduled reminder must not be treated as successfully delivered until the selected provider confirms the delivery result.

### 10.6 Rescheduling and Reminder Replacement

When an individual session is rescheduled:

- All pending reminders associated with the old session time must be cancelled.
- Three new reminders must be created using the updated session time.
- Both the client and Farah must receive the relevant rescheduling notification.

When a package session is rescheduled:

- Only reminders belonging to that specific child session must be replaced.
- Reminders for all other package sessions must remain unchanged.
- Both the client and Farah must be informed about the change.

The replacement operation must prevent outdated reminders from being sent.

### 10.7 Cancellation and Expiration

When a session is cancelled, all its pending reminders must be cancelled.

When an individual reservation expires, its pending reminders must be cancelled.

When a package reservation expires, all pending reminders belonging to every child session must be cancelled.

The system must never send a session reminder for a cancelled, expired or otherwise ineligible session.

### 10.8 Operational Notifications for Farah

Farah must receive operational notifications for important events, including:

- New individual reservation.
- New package reservation.
- Payment proof submitted.
- Payment confirmed.
- Payment rejected.
- Reservation expired.
- Package expired.
- Session cancelled.
- Session rescheduled.
- Institutional request submitted.
- Important notification delivery failures.

These notifications must be distinguishable from scheduled session reminders.

### 10.9 Client Notifications

Clients must receive relevant notifications for:

- Provisional reservation created.
- Payment instructions.
- Payment proof successfully submitted.
- Payment confirmed.
- Payment rejected.
- Reservation expired.
- Reservation cancelled.
- Session rescheduled.
- Package reservation confirmed.
- Other important changes affecting their reservations.

The system must not expose private information belonging to other clients.

### 10.10 Payment Deadline Notifications

Payment reminders are separate from session reminders.

The schedules for payment reminders have not yet been approved.

The architecture must allow payment reminders to be configured independently for:

- Individual reservations with a 24-hour payment deadline.
- Package reservations with a 96-hour payment deadline.

No payment reminder schedule must be assumed until Farah confirms the desired timing.

### 10.11 Notification Database Architecture

The proposed database architecture must include:

notifications

This table should store the logical notification and its relationship with the relevant reservation or scheduled session.

Suggested fields:

- id
- recipient_type
- recipient_id
- reservation_id
- reservation_session_id
- notification_type
- channel
- scheduled_at
- status
- created_at
- updated_at

A separate delivery history table is also proposed:

notification_attempts

Suggested fields:

- id
- notification_id
- provider
- provider_message_id
- attempt_number
- attempted_at
- delivery_status
- error_message
- created_at

The final database schema must be defined during database architecture design.

### 10.12 Duplicate Prevention

The system must prevent duplicate reminders and duplicate operational notifications.

Each scheduled reminder must have a unique logical identity based on:

- Reservation session.
- Recipient.
- Notification type.
- Scheduled occurrence.

The system must use database constraints or equivalent reliable mechanisms to prevent duplicate scheduling.

Retries must not create additional independent notifications.

### 10.13 Delivery Failures and Retries

If a notification provider fails:

- The attempt must be recorded.
- The error must be stored.
- The system may retry according to the configured retry policy.
- Failed notifications must be visible to the administrator.

A notification failure must not change the status of a reservation, payment or session.

Retry policies must prevent uncontrolled repeated attempts.

### 10.14 Scheduling Infrastructure

The platform must use reliable scheduled backend processing to identify and deliver notifications when they become due.

The proposed architecture may use:

- Supabase Edge Functions.
- Supabase Cron or another reliable scheduler.
- Database-backed notification queues.
- External notification providers.

The scheduling mechanism must work independently of whether a client or administrator currently has the website open.

### 10.15 Notification Time Accuracy

The official timezone is Africa/Maputo.

The system must calculate reminder times using the actual scheduled session timestamp.

For example:

- A reminder scheduled 24 hours before must be calculated as exactly 24 hours before the session.
- A reminder scheduled 1 hour before must be calculated as exactly 1 hour before the session.
- The final reminder must be scheduled for the exact session start time.

The system must not substitute approximate intervals.

### 10.16 Notification Security and Privacy

Notifications must contain only the information necessary for their purpose.

Sensitive information, payment proofs and private client records must not be included in unsecured messages.

Provider credentials and API keys must remain server-side.

All notification operations must be authorized and recorded appropriately.

### 10.17 Pending Notification Decisions

The following details must be confirmed before production:

- SMS provider.
- Email provider.
- WhatsApp Business Platform or provider.
- Preferred notification channels for clients.
- Preferred notification channels for Farah.
- Payment reminder schedules.
- Retry policy.
- Whether clients may choose notification preferences.

## 11. Authentication and Security

### 11.1 General Security Principles

The platform must follow security best practices and the principle of least privilege.

All sensitive operations must be validated by the backend.

The system must protect:

- Client personal information.
- Reservation information.
- Payment records.
- Payment proofs.
- Administrative accounts.
- Database records.
- Private application credentials.

### 11.2 Authentication Architecture

Supabase Auth will provide the authentication infrastructure.

The system must distinguish between:

1. Public visitors.
2. Clients using reservation recovery.
3. Authorized administrators.

Clients will not require permanent password-based accounts for the initial booking system.

Client reservation recovery must use SMS OTP as defined in Section 8.

### 11.3 Administrator Authentication

Farah must have a private administrator account.

Administrative access must require authentication.

The system must:

- Prevent public registration as an administrator.
- Verify administrator permissions on the server.
- Protect administrative routes.
- Reject unauthorized administrative operations.
- Expire or invalidate sessions according to secure authentication policies.

The administrator role must never be assigned automatically to a newly registered user.

### 11.4 Initial Authentication Configuration

During development and initial setup:

- Email authentication may be enabled for administrator account creation and testing.
- Email confirmation must remain enabled.
- Phone authentication through Supabase Auth must remain disabled unless a specific future requirement justifies enabling it.
- Public signups must be disabled before production launch once the administrator account has been created and verified.

The client SMS OTP reservation recovery process is separate from Supabase Auth phone authentication.

### 11.5 Role-Based Access Control

The platform must use role-based access control.

The backend must verify the user's identity and permissions before allowing access to protected resources.

Administrative permissions must be stored and validated securely.

A user must never gain administrator permissions by modifying frontend data or sending a manipulated request.

### 11.6 Supabase Row Level Security

Row Level Security (RLS) must be enabled on all tables containing private or sensitive information.

Policies must explicitly define:

- Who can read records.
- Who can insert records.
- Who can update records.
- Who can delete records.

Public access must be denied by default for sensitive tables.

Administrative operations must be restricted to authenticated and authorized administrators.

Client access must be limited to records associated with their verified identity.

### 11.7 Server-Side Authorization

All critical operations must pass through trusted server-side logic.

This includes:

- Creating reservations.
- Rescheduling sessions.
- Cancelling reservations.
- Submitting payment proofs.
- Confirming payments.
- Rejecting payments.
- Managing availability.
- Managing packages.
- Managing administrative permissions.

The backend must never trust a client-provided role, reservation status, payment status or price without independent validation.

### 11.8 Supabase API Keys

The application must distinguish between public and secret credentials.

The Supabase publishable key may be used in public frontend code according to the configured RLS policies.

The Supabase secret key or legacy service role key must remain server-side only.

Secret credentials must never be:

- Exposed in frontend JavaScript.
- Committed to GitHub.
- Included in public files.
- Sent to clients.
- Stored in browser-accessible configuration.

### 11.9 Environment Variables

Sensitive configuration must be stored in environment variables.

Proposed variables include:

- NEXT_PUBLIC_SUPABASE_URL
- NEXT_PUBLIC_SUPABASE_ANON_KEY or the appropriate Supabase publishable key.
- SUPABASE_SERVICE_ROLE_KEY or the appropriate secret key.
- SMS provider credentials.
- Email provider credentials.
- WhatsApp provider credentials.

Only values explicitly intended for public use may use the NEXT_PUBLIC_ prefix.

Production secrets must be configured securely in the hosting environment.

### 11.10 Payment Proof Protection

Payment proof files must be stored in a private Supabase Storage bucket.

Access must be authorized through secure backend validation.

Public URLs must never expose private payment proof files.

File access must verify reservation ownership or administrator authorization.

### 11.11 OTP Security

The SMS OTP recovery system must implement:

- Secure random code generation.
- Hashed OTP storage.
- Expiration.
- Maximum verification attempts.
- Rate limiting.
- Resend restrictions.
- Single-use verification.
- Previous code invalidation.
- Protection against brute-force attacks.
- Protection against phone number enumeration.

OTP codes must never be stored in plaintext.

### 11.12 Input Validation

All user-submitted data must be validated on the backend.

Validation must cover:

- Phone numbers.
- Email addresses.
- Names.
- Dates and times.
- Reservation identifiers.
- Payment amounts.
- Uploaded files.
- Institutional request forms.
- Review submissions.

The system must reject malformed, unexpected or unauthorized data.

### 11.13 Protection Against Common Attacks

The application must implement appropriate protection against:

- SQL injection.
- Cross-Site Scripting (XSS).
- Cross-Site Request Forgery (CSRF), where applicable.
- Brute-force attacks.
- Unauthorized API access.
- Insecure direct object references.
- Credential leakage.
- Malicious file uploads.
- Duplicate request submissions.
- Abuse of OTP and notification endpoints.

The application must use secure dependencies and keep them updated.

### 11.14 Administrative Session Security

Administrative sessions must follow secure session management practices.

The system must:

- Protect authentication cookies.
- Use HTTPS in production.
- Prevent unauthorized session reuse.
- Support secure logout.
- Reject expired or invalid sessions.
- Protect administrative pages against unauthorized access.

### 11.15 Audit Logging

Important security and administrative events must be recorded.

These include:

- Administrative login events.
- Payment decisions.
- Reservation modifications.
- Availability changes.
- Permission changes.
- Important configuration changes.
- Failed sensitive operations, where appropriate.

Audit logs must not be editable by ordinary clients.

### 11.16 Data Protection

The system must collect only information necessary to operate the service.

Private client information must not be exposed through public website pages or public database queries.

The platform must define appropriate data retention, deletion and privacy procedures before production launch.

### 11.17 Security Testing

Before production deployment, the system must be tested for:

- Unauthorized administrative access.
- Incorrect RLS policies.
- Unauthorized reservation access.
- Payment proof exposure.
- OTP abuse.
- Reservation manipulation.
- Payment status manipulation.
- Secret key exposure.
- Unauthorized database operations.

Critical security tests must pass before the website becomes publicly available.

### 11.18 Security Configuration Review

The final security configuration must be reviewed before launch.

This review must include:

- Supabase Auth settings.
- Database permissions.
- RLS policies.
- Storage policies.
- Server-side secrets.
- API authorization.
- Administrative access.
- Production environment variables.

## 12. Database Architecture

### 12.1 General Architecture

The platform will use PostgreSQL through Supabase as its primary database.

The database must support:

- Client information.
- Individual reservations.
- Package reservations.
- Individual scheduled sessions.
- Payment records.
- Payment proofs.
- Availability management.
- Notifications and reminders.
- SMS OTP reservation recovery.
- Client reviews.
- Institutional requests.
- Administrative permissions.
- Audit history.

The database must preserve data integrity, enforce business rules and support secure concurrent operations.

### 12.2 Database Design Principles

The database must follow these principles:

- Relational database architecture.
- Clear separation of business entities.
- Primary keys and foreign keys.
- Appropriate unique constraints.
- Appropriate indexes.
- Database-level validation.
- Transactional operations for critical processes.
- Row Level Security (RLS).
- Least-privilege access.
- Historical data preservation.

Critical business rules must not depend exclusively on frontend validation.

### 12.3 Core Database Tables

The proposed database must include the following tables.

#### A. clients

Stores client information.

Suggested fields:

- id
- full_name
- phone_number
- normalized_phone_number
- email
- created_at
- updated_at

Requirements:

- Each client must have a unique normalized phone number.
- Phone numbers must be stored in a consistent international format.
- Email must be optional.
- A client must be associated with their reservations.
- Client information must not be publicly accessible.

#### B. admin_users

Stores the administrative authorization records.

Suggested fields:

- id
- auth_user_id
- role
- is_active
- created_at
- updated_at

Requirements:

- Administrative authentication must use Supabase Auth.
- The auth_user_id must reference the corresponding authenticated user.
- Only explicitly authorized users may have administrative permissions.
- Public registration must never grant administrator access.

#### C. offers

Stores the services and packages available for purchase.

Suggested fields:

- id
- name
- description
- offer_type
- session_count
- session_duration_minutes
- price
- currency
- validity_days
- is_active
- created_at
- updated_at

Requirements:

- Must support individual sessions and packages.
- Must support the Essential, Transformation and Evolution packages.
- Package session counts must be configurable.
- Prices must use an exact numeric representation.
- Currency must be MZN.
- Package validity must be configurable.
- Historical reservations must preserve the price and package details applicable when purchased.

#### D. reservations

Stores the main reservation operation.

This is the parent table for both individual and package reservations.

Suggested fields:

- id
- client_id
- offer_id
- reservation_type
- status
- modality
- total_amount
- currency
- payment_deadline
- confirmed_at
- expires_at
- cancelled_at
- created_at
- updated_at

Requirements:

- An individual reservation represents one individual session.
- A package reservation represents one package purchase containing multiple sessions.
- Each reservation must belong to one client.
- Each reservation must preserve the applicable offer and price information.
- Package reservations must act as the parent of their scheduled sessions.
- Reservation expiration must be processed atomically.

The reservation must preserve historical commercial information even if the original offer is later modified.

#### E. reservation_sessions

Stores the individual scheduled sessions belonging to reservations.

Suggested fields:

- id
- reservation_id
- scheduled_start_at
- scheduled_end_at
- modality
- status
- completed_at
- created_at
- updated_at

Requirements:

- Every scheduled session must belong to one parent reservation.
- Individual reservations must normally contain one scheduled session.
- Essential reservations must contain four sessions.
- Transformation reservations must contain eight sessions.
- Evolution reservations must contain twelve sessions.
- Each session must have its own date, time, modality and status.
- Every package session must remain linked to its parent reservation.
- Each session must be independently reschedulable.
- Session completion must not automatically complete the entire package.

The database must enforce the required session count for each package before the reservation can become confirmed.

### 12.4 Payment Tables

#### A. payments

Stores the payment record associated with a reservation.

Suggested fields:

- id
- reservation_id
- payment_method
- expected_amount
- currency
- status
- confirmed_at
- reviewed_by
- rejection_reason
- created_at
- updated_at

Requirements:

- Every reservation must have an associated payment record.
- Payment amounts must be preserved historically.
- Payment confirmation must be performed by an authorized administrator for M-Pesa.
- Payment status changes must be validated by the backend.
- Payment history must not be silently overwritten.

#### B. payment_proofs

Stores references to submitted payment proof files.

Suggested fields:

- id
- payment_id
- storage_path
- original_filename
- mime_type
- file_size
- submitted_at
- review_status
- created_at

Requirements:

- Payment proof files must be stored in a private Supabase Storage bucket.
- The database must store the file reference, not the file itself.
- Each proof must belong to a payment.
- Access must be restricted to the associated client and authorized administrators.
- Previous proof submissions must remain traceable.
- Uploading a proof must never automatically confirm payment.

### 12.5 Availability Tables

#### A. availability_rules

Stores Farah's regular working schedule.

Suggested fields:

- id
- weekday
- start_time
- end_time
- modality
- is_active
- valid_from
- valid_until
- created_at
- updated_at

Requirements:

- Must support different working hours on different weekdays.
- Must support multiple working periods on the same day.
- Must support online and in-person availability.
- Must allow temporary schedule configurations.
- Must support future changes without destroying historical reservations.

#### B. availability_blocks

Stores periods when Farah is unavailable.

Suggested fields:

- id
- title
- block_type
- start_at
- end_at
- reason
- created_by
- created_at
- updated_at

Requirements:

- Must support full-day blocks.
- Must support multiple-day blocks.
- Must support specific time blocks.
- Must support breaks, holidays and vacations.
- Must prevent new reservations during blocked periods.
- Must detect conflicts with existing reservations before a block is created.

### 12.6 Notification Tables

#### A. notifications

Stores logical notifications and scheduled reminders.

Suggested fields:

- id
- recipient_type
- recipient_id
- reservation_id
- reservation_session_id
- notification_type
- channel
- scheduled_at
- status
- created_at
- updated_at

Requirements:

- Must support notifications for clients and Farah.
- Must support individual session reminders.
- Must support package session reminders.
- Must support operational notifications.
- Must allow cancellation of outdated reminders.
- Must prevent duplicate logical notifications.

#### B. notification_attempts

Stores the delivery history of notifications.

Suggested fields:

- id
- notification_id
- provider
- provider_message_id
- attempt_number
- attempted_at
- delivery_status
- error_message
- created_at

Requirements:

- Every delivery attempt must be traceable.
- Failed attempts must be recorded.
- Retry operations must not create duplicate logical notifications.
- Delivery failures must not change reservation or payment status.

### 12.7 Reservation Recovery Table

#### booking_recovery_codes

Stores hashed SMS OTP recovery codes.

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

Requirements:

- OTP codes must never be stored in plaintext.
- Codes must expire.
- Verification attempts must be limited.
- Resending must invalidate previous codes.
- Each code must be single-use.
- Recovery must be associated with the correct reservation and verified phone number.
- Additional rate-limiting mechanisms must protect against abuse.

### 12.8 Client Reviews Table

#### client_reviews

Stores reviews submitted by eligible clients.

Suggested fields:

- id
- client_id
- reservation_session_id
- rating
- review_text
- moderation_status
- is_public
- consent_to_publish
- created_at
- updated_at

Requirements:

- Reviews must be associated with a completed session.
- Only eligible clients may submit reviews.
- Reviews must be moderated before publication.
- Private reviews must not appear publicly.
- Publication must respect the client's consent.
- Duplicate reviews for the same session must be prevented.

### 12.9 Institutional Requests Table

#### institutional_requests

Stores requests from organizations and institutions.

Suggested fields:

- id
- organization_name
- contact_name
- contact_phone
- contact_email
- event_type
- preferred_date
- message
- status
- created_at
- updated_at

Requirements:

- Institutional requests must be stored securely.
- Farah must be able to review and manage requests.
- New submissions must generate operational notifications.
- Public users must not access other submitted requests.

### 12.10 Audit Logs Table

#### audit_logs

Stores important administrative and security actions.

Suggested fields:

- id
- actor_user_id
- action
- entity_type
- entity_id
- details
- created_at

Requirements:

- Important administrative operations must be recorded.
- Payment decisions must be traceable.
- Reservation modifications must be traceable.
- Availability changes must be traceable.
- Permission changes must be traceable.
- Ordinary clients must never modify audit records.
- Audit history must be protected against unauthorized modification.

### 12.11 Table Relationships

The database must implement the following relationships:

- One client can have multiple reservations.
- One offer can be referenced by multiple reservations.
- One reservation belongs to one client.
- One reservation can have one or multiple reservation_sessions.
- One reservation must have an associated payment.
- One payment can have multiple payment_proofs.
- One reservation can have multiple notifications.
- One reservation_session can have multiple notifications.
- One notification can have multiple notification_attempts.
- One client can have multiple reviews.
- Each review must reference an eligible completed reservation_session.
- One administrator can perform multiple audited actions.
- One administrator can create multiple availability blocks.

### 12.12 Reservation and Session Integrity

The database must preserve the distinction between parent reservations and child sessions.

Individual sessions:
- One parent reservation.
- Normally one child session.

Packages:
- One parent reservation.
- Four, eight or twelve child sessions according to the selected package.

The parent reservation must control the overall package payment and expiration lifecycle.

Each child session must maintain its own scheduling, completion, rescheduling and reminder information.

### 12.13 Concurrency and Double-Booking Protection

The database must prevent two active reservations from occupying overlapping time intervals.

The implementation must consider:

- Confirmed sessions.
- Temporarily held sessions.
- Simultaneous booking requests.
- Simultaneous rescheduling requests.
- Package reservations containing multiple sessions.

Critical booking operations must use database transactions and appropriate database-level concurrency protection.

A package reservation must allocate all its required time slots atomically.

### 12.14 Database Indexes and Constraints

The final database design must include appropriate indexes and constraints.

These must cover:

- Client phone number uniqueness.
- Reservation ownership.
- Reservation status.
- Payment status.
- Payment deadlines.
- Session date and time.
- Parent-child reservation relationships.
- Notification scheduling.
- OTP expiration and verification.
- Administrative authorization.
- Prevention of overlapping active sessions.
- Prevention of duplicate reminders.
- Required package session counts.

The exact indexes, unique constraints and exclusion constraints must be designed before implementation.

### 12.15 Database Security

Row Level Security must be enabled for all sensitive tables.

The database must enforce:

- Authorized administrative access.
- Client ownership restrictions.
- Private payment proof access.
- Protected recovery information.
- Restricted audit log access.
- No public access to sensitive records.

Administrative privileges must never be granted based only on frontend information.

### 12.16 Database Migrations

All database structure changes must be version-controlled.

SQL migrations must be stored in the GitHub repository.

Each migration must have a clear sequential name.

Proposed migration sequence:

- 001_extensions.sql
- 002_custom_types.sql
- 003_core_tables.sql
- 004_reservation_tables.sql
- 005_payment_tables.sql
- 006_availability_tables.sql
- 007_notification_tables.sql
- 008_security_functions.sql
- 009_rls_policies.sql
- 010_database_permissions.sql
- 011_indexes_and_constraints.sql

The final migration order may be adjusted after reviewing foreign-key dependencies and implementation requirements.

### 12.17 Database Testing

Before production use, the database must be tested for:

- Correct table relationships.
- Foreign-key integrity.
- Unique constraints.
- RLS protection.
- Unauthorized access.
- Double-booking prevention.
- Atomic package allocation.
- Atomic package expiration.
- Correct payment deadlines.
- Correct session completion.
- Correct remaining package session counts.
- Correct reminder relationships.
- Correct reservation recovery.

### 12.18 Important Implementation Rule

No production SQL must be executed until:

1. The complete database architecture has been reviewed.
2. All table relationships have been validated.
3. Reservation and package logic has been checked.
4. Security and RLS policies have been designed.
5. Concurrency protection has been planned.
6. Migration dependencies have been reviewed.

The final database schema must be consistent with every business rule defined in this master document.

## 13. Backend Architecture

### 13.1 General Architecture

The backend will use a server-first architecture based on:

- Next.js with TypeScript.
- Supabase PostgreSQL.
- Supabase Auth.
- Supabase Storage.
- Supabase Edge Functions.
- PostgreSQL database functions and transactions.
- Supabase Cron or an equivalent scheduled execution mechanism.

The backend must be responsible for enforcing all business rules, validating requests, protecting sensitive information and coordinating critical operations.

The frontend must never be treated as a trusted source for business-critical decisions.

### 13.2 Backend Responsibilities

The backend must manage:

- Client information.
- Reservation creation.
- Individual session scheduling.
- Package scheduling.
- Availability validation.
- Temporary slot allocation.
- Reservation expiration.
- Payment proof submissions.
- Manual payment verification.
- Reservation cancellation.
- Session rescheduling.
- Package session tracking.
- Notification scheduling.
- Reminder delivery.
- SMS OTP reservation recovery.
- Review eligibility.
- Institutional requests.
- Administrative operations.
- Audit logging.

### 13.3 Backend Architecture Layers

The system must separate responsibilities into the following layers.

#### A. Next.js Server Layer

Responsible for:

- Receiving website requests.
- Server-side validation.
- Calling authorized backend operations.
- Managing secure authentication sessions.
- Rendering protected administrative pages.
- Handling public website submissions.
- Returning appropriate responses.

Sensitive operations must never depend exclusively on browser-side code.

#### B. Supabase Database Layer

Responsible for:

- Persistent data storage.
- Relational integrity.
- Database constraints.
- Row Level Security.
- Transactional operations.
- Atomic reservation allocation.
- Atomic package expiration.
- Preventing double bookings.
- Protecting historical records.

#### C. Supabase Edge Functions Layer

Responsible for specialized backend operations such as:

- Reservation processing.
- Payment processing.
- OTP recovery.
- Notification delivery.
- Scheduled reminder processing.
- Reservation expiration.
- External service integrations.

#### D. Scheduled Jobs Layer

Responsible for executing operations at specific times, even when the website is closed.

Examples:

- Expiring unpaid reservations.
- Sending session reminders.
- Processing scheduled notifications.
- Retrying eligible failed notification attempts.
- Monitoring operational failures.

### 13.4 Critical Booking Operations

All critical booking operations must be processed securely on the backend.

The system must never trust availability information calculated only by the frontend.

Before creating a reservation, the backend must validate:

- Offer availability.
- Client information.
- Booking notice requirements.
- Session duration.
- Modality.
- Working hours.
- Availability blocks.
- Existing reservations.
- Temporary holds.
- Package session requirements.
- Client booking restrictions.

The backend must revalidate availability at the moment of allocation.

### 13.5 Reservation Creation

The system must provide separate backend workflows for individual reservations and package reservations.

#### A. Individual Reservation

The operation must:

1. Validate the client and selected offer.
2. Validate the 3-day minimum booking notice.
3. Validate the selected date and time.
4. Validate the selected modality.
5. Check existing reservations and temporary holds.
6. Check the one-active-individual-reservation restriction.
7. Atomically allocate the selected time slot.
8. Create the parent reservation.
9. Create its scheduled session.
10. Create the associated payment record.
11. Set the payment deadline to exactly 24 hours.
12. Return the provisional reservation details.
13. Schedule any applicable payment notifications.

The entire operation must either succeed or fail without leaving incomplete records or occupied slots.

#### B. Package Reservation

The operation must:

1. Validate the selected package.
2. Validate the required number of sessions.
3. Receive all selected session dates and times.
4. Validate every session individually.
5. Enforce the 7-day minimum and 1-month maximum booking window.
6. Validate all modalities.
7. Check all existing reservations and temporary holds.
8. Atomically allocate every selected time slot.
9. Create one parent package reservation.
10. Create all required child reservation sessions.
11. Create one associated package payment record.
12. Set the payment deadline to exactly 96 hours.
13. Return the complete provisional package reservation.
14. Schedule any applicable payment notifications.

If even one session cannot be allocated, the entire operation must fail.

No partial package reservation may remain.

### 13.6 Atomicity and Concurrency Protection

Critical operations must use database transactions and appropriate concurrency controls.

The following operations must be atomic:

- Individual reservation creation.
- Package reservation creation.
- Individual session rescheduling.
- Package session rescheduling.
- Reservation expiration.
- Package expiration.
- Payment confirmation when it affects reservation allocation.

The system must prevent:

- Double booking.
- Duplicate reservations from repeated requests.
- Partial package allocation.
- Simultaneous conflicting rescheduling.
- Payment confirmation after reservation expiration.
- Expiration of an already confirmed reservation.

The implementation must use appropriate database constraints, transactions, locking and idempotency mechanisms.

### 13.7 Reservation Expiration

A scheduled backend process must identify unpaid reservations whose payment deadlines have passed.

Individual reservations:

- Payment deadline: 24 hours.
- Expire if payment has not been manually confirmed.
- Release the associated session slot.

Package reservations:

- Payment deadline: 96 hours.
- Expire the entire parent reservation.
- Release every child session slot atomically.
- Cancel all pending reminders associated with the expired package sessions.

The expiration process must be safe to execute repeatedly.

It must never expire confirmed reservations.

If expiration and payment confirmation occur simultaneously, database-level concurrency protection must ensure that only one valid outcome is committed.

### 13.8 Payment Processing

The backend must support manual M-Pesa payment verification initially and allow future integration with Volet.

Payment workflow:

1. Client receives payment instructions.
2. Client makes the payment externally.
3. Client submits payment proof.
4. Backend validates the file and reservation.
5. Backend records the proof submission.
6. Farah receives an operational notification.
7. Farah reviews the payment.
8. Farah confirms or rejects the payment.
9. Backend validates the reservation status and payment deadline.
10. Backend updates the payment and reservation consistently.
11. Backend schedules or cancels relevant notifications.

Uploading payment proof must never confirm payment automatically.

Payment confirmation must be an authorized administrative operation.

A rejected payment must retain the original payment deadline.

### 13.9 Session Rescheduling

Rescheduling must be performed through a dedicated backend operation.

The backend must:

1. Authenticate and identify the requesting client.
2. Verify ownership of the reservation.
3. Verify that the session is eligible for rescheduling.
4. Enforce the 24-hour restriction.
5. Validate the new date and time.
6. Validate availability and modality.
7. Check conflicting reservations and temporary holds.
8. Atomically allocate the new slot and release the old slot.
9. Update the session schedule.
10. Cancel outdated reminders.
11. Create the three new reminders.
12. Notify the client and Farah.
13. Record the operation in the audit log.

If the new slot is unavailable, the original session must remain unchanged.

For packages, only the affected child session must be rescheduled. Other package sessions must remain unchanged.

Rescheduling must not require manual approval from Farah.

### 13.10 Cancellation

The backend must validate cancellation requests.

Requirements:

- Client cancellation is allowed only until 24 hours before the affected session.
- Cancellation inside the 24-hour window must be rejected.
- Unauthorized users cannot cancel another client's reservation.
- Cancellation must update the appropriate reservation or session records.
- Associated pending reminders must be cancelled.
- Farah must receive an operational notification.
- The operation must be recorded in the audit log.

Package cancellation and refund consequences must follow the final business policy, which remains pending confirmation.

### 13.11 Availability Calculation

A dedicated backend operation must calculate available appointment slots.

It must consider:

- Regular working schedules.
- Temporary schedule changes.
- Availability blocks.
- Existing confirmed sessions.
- Temporary reservation holds.
- Session duration.
- Modality.
- Minimum booking notice.
- Package scheduling window.
- Timezone Africa/Maputo.

The frontend must display availability returned by the backend.

The backend must always revalidate the selected slot before allocation.

### 13.12 Notification Processing

Notifications must be managed independently from reservation operations.

The backend must support:

- Email notifications.
- SMS notifications.
- WhatsApp notifications.

The actual providers will be selected later.

The system must distinguish between logical notifications and individual delivery attempts.

A notification delivery failure must never reverse a valid reservation or payment operation.

### 13.13 Reminder Scheduling

Every confirmed individual session must generate three reminders for both the client and Farah:

- 24 hours before.
- 1 hour before.
- Exactly at the scheduled start time.

Every confirmed package child session must receive its own independent reminder schedule.

The system must not create a 30-minute reminder.

When a session is rescheduled:

- Cancel its old reminders.
- Create three new reminders.
- Preserve reminders belonging to unaffected package sessions.

When a session or reservation is cancelled or expired, its pending reminders must be cancelled.

Reminder processing must be idempotent and prevent duplicate deliveries.

### 13.14 OTP Reservation Recovery

The backend must provide secure reservation recovery using SMS OTP.

The process must:

1. Receive the client's phone number.
2. Identify eligible reservations without revealing whether a number exists.
3. Generate a secure random code.
4. Store only the hashed code.
5. Send the code through the selected SMS provider.
6. Verify the submitted code.
7. Enforce expiration and attempt limits.
8. Invalidate previous codes when a new code is issued.
9. Mark successfully verified codes as consumed.
10. Grant access only to the appropriate reservation information.

OTP recovery must be protected by rate limiting and abuse prevention.

### 13.15 Review Submission

The backend must verify that:

- The client owns the referenced session.
- The session is completed.
- The client is eligible to review it.
- A duplicate review does not already exist.

Reviews must enter the moderation process before public publication.

### 13.16 Institutional Request Processing

The backend must:

- Validate submitted information.
- Protect against spam and automated abuse.
- Store requests securely.
- Notify Farah about new submissions.
- Allow authorized administrative review.
- Maintain request status and history.

### 13.17 Proposed Backend Functions

The following operations are proposed for implementation.

#### Reservation Operations

- create-individual-reservation
- create-package-reservation
- get-available-slots
- reschedule-session
- cancel-reservation
- expire-reservations

#### Payment Operations

- submit-payment-proof
- review-payment
- process-payment-expiration

#### Recovery Operations

- request-reservation-recovery
- verify-recovery-code

#### Notification Operations

- schedule-session-reminders
- process-reminders
- send-notification
- retry-failed-notifications

#### Administrative Operations

- manage-availability
- manage-offers
- manage-reservations
- manage-reviews
- manage-institutional-requests

The final implementation may use Next.js server routes, Supabase Edge Functions, PostgreSQL functions or a combination of these.

Function boundaries must be chosen according to security, transactional requirements and maintainability.

### 13.18 Idempotency and Duplicate Request Protection

Critical operations must support idempotency where appropriate.

Repeated requests caused by:

- Network interruptions.
- Browser refreshes.
- Double clicks.
- Provider retries.
- Scheduled job retries.

Must not create duplicate reservations, payments, reminders or administrative actions.

The backend must distinguish between a legitimate new operation and a repeated request.

### 13.19 Error Handling and Logging

The backend must:

- Return clear and safe error responses.
- Avoid exposing internal database errors to clients.
- Log important operational failures.
- Preserve useful debugging information.
- Avoid logging passwords, OTP plaintext or payment secrets.
- Record critical administrative operations.
- Support safe retries where appropriate.

### 13.20 Backend Security

All critical operations must enforce:

- Authentication where required.
- Authorization and role checks.
- Input validation.
- Database constraints.
- RLS.
- Rate limiting where appropriate.
- Secure secret management.
- Protection against unauthorized data access.
- Server-side verification of prices, payments and reservation status.

Supabase secret/service-role credentials must never be exposed to the browser or committed to GitHub.

### 13.21 Backend Testing

Before production deployment, the backend must be tested for:

- Individual reservation creation.
- Package reservation creation.
- Minimum booking notice.
- Package scheduling limits.
- Payment deadlines.
- Reservation expiration.
- Atomic package expiration.
- Payment confirmation and rejection.
- Double-booking prevention.
- Concurrent booking requests.
- Concurrent rescheduling.
- Session completion.
- Package remaining session counts.
- Reminder scheduling and cancellation.
- OTP recovery.
- Authorization and RLS.
- Duplicate request protection.
- Notification failures and retries.

### 13.22 Implementation Rule

No production backend code must be implemented until:

1. The master project document has been completed.
2. The database architecture has been reviewed.
3. All critical business rules have been validated.
4. Security boundaries have been designed.
5. Transactional operations have been planned.
6. External providers and integrations have been evaluated.

The backend must implement the approved business rules consistently and must never silently weaken them for frontend convenience.

## 14. Frontend Architecture

### 14.1 General Architecture

The frontend will be developed using:

- Next.js.
- TypeScript.
- React.
- Tailwind CSS.
- Reusable UI components.
- Supabase client libraries where appropriate.

The application must use a modular, maintainable and responsive architecture.

### 14.2 Design Principles

The interface must follow these principles:

- Elegant and professional visual identity.
- Minimalist layouts.
- Clear visual hierarchy.
- Generous spacing.
- Strong typography.
- High-quality imagery.
- Smooth and purposeful animations.
- Consistent interactions.
- Accessible components.
- Minimal unnecessary text.

The design must preserve the approved Farah Dibha Neurocoach identity and color palette.

### 14.3 Responsive Design

The website must support:

- iPhone and other smartphones.
- Android smartphones.
- Tablets.
- Desktop computers.
- Large screens.

Mobile-first development is required.

All important actions must remain accessible on smaller screens.

### 14.4 Public Website Structure

The frontend must include the following public pages:

- Home.
- About Farah.
- Services.
- Individual Sessions.
- Packages.
- Booking.
- Testimonials and Reviews.
- Talks and Workshops.
- Institutional Requests.
- Contact.

Each page must have a clear purpose and consistent visual identity.

### 14.5 Navigation

The navigation must provide access to the main website sections.

Requirements:

- Responsive navigation.
- Clear active section indication.
- Easy access to booking.
- Mobile navigation suitable for touch interactions.
- Consistent navigation across public pages.

A mobile bottom navigation may be considered if it improves usability.

### 14.6 Reusable Components

The frontend must use reusable components for:

- Buttons.
- Navigation.
- Headers.
- Footers.
- Cards.
- Service presentations.
- Package presentations.
- Forms.
- Modals.
- Notifications.
- Loading states.
- Error states.
- Confirmation messages.
- Calendar controls.
- Time slot selectors.

Components must remain consistent throughout the application.

### 14.7 Booking Interface

The booking interface must provide separate flows for individual sessions and packages.

Individual booking:

1. Select the individual session.
2. Select modality.
3. Enter client information.
4. Select an available date.
5. Select an available time.
6. Review reservation details.
7. Submit the reservation.
8. Display payment instructions and deadline.

Package booking:

1. Select a package.
2. Select modality.
3. Enter client information.
4. Select all required session dates.
5. Select all required session times.
6. Review every selected session.
7. Submit the complete package reservation.
8. Display payment instructions and the 96-hour deadline.

The interface must clearly distinguish provisional reservations from confirmed reservations.

The frontend must display availability returned by the backend and never independently determine whether a slot is truly available.

### 14.8 Calendar and Time Slot Interface

The booking calendar must:

- Display available dates.
- Distinguish unavailable dates.
- Respect the Africa/Maputo timezone.
- Display available time slots.
- Reflect the selected modality.
- Enforce booking notice restrictions.
- Prevent selection of invalid dates.
- Allow package clients to select multiple sessions.

The interface must remain synchronized with backend availability validation.

### 14.9 Client Reservation Area

Clients must have access to a secure reservation management interface.

The interface must support:

- Reservation recovery using SMS OTP.
- Viewing reservation details.
- Viewing payment status.
- Submitting payment proof.
- Viewing package sessions.
- Viewing remaining package sessions.
- Rescheduling eligible sessions.
- Cancelling eligible reservations or sessions.
- Viewing relevant notifications.

Clients must only access reservations associated with their verified identity.

No permanent password-based client account is required initially.

### 14.10 Payment Interface

The payment interface must display:

- Reservation amount.
- Currency in MZN.
- Payment method.
- Payment instructions.
- Payment deadline.
- Payment proof upload.
- Payment review status.
- Confirmation or rejection information.

The interface must clearly explain that submitting proof does not automatically confirm payment.

### 14.11 Administrative Dashboard

The administrative interface must be private and protected.

It must provide access to:

- Overview.
- Reservations.
- Payments.
- Calendar.
- Availability.
- Services and packages.
- Clients.
- Reviews.
- Institutional requests.
- Notifications.
- Settings.

All administrative actions must be validated by the backend.

### 14.12 Admin Calendar Interface

The calendar must allow Farah to:

- View scheduled sessions.
- Distinguish individual sessions from package sessions.
- View session status.
- View client information.
- Identify online and in-person sessions.
- Manage availability.
- Create availability blocks.
- Detect conflicts with existing reservations.

Calendar actions must not bypass backend validation.

### 14.13 Forms and Validation

All forms must provide:

- Clear labels.
- Appropriate input types.
- Required field indicators.
- Immediate user feedback.
- Server-side validation.
- Safe error messages.
- Submission loading states.
- Success and failure states.

Client-side validation must improve usability but must never replace backend validation.

### 14.14 Loading, Error and Empty States

Every major interface must support:

- Loading states.
- Empty states.
- Error states.
- Success states.
- Retry actions where appropriate.

The interface must avoid appearing broken when data is loading or unavailable.

### 14.15 Accessibility

The frontend must follow accessibility best practices.

Requirements include:

- Semantic HTML.
- Keyboard navigation.
- Visible focus states.
- Appropriate color contrast.
- Accessible form labels.
- Screen reader support.
- Touch-friendly controls.
- Reduced-motion support.

### 14.16 Performance

The application must prioritize:

- Fast initial loading.
- Optimized images.
- Appropriate image formats.
- Lazy loading where appropriate.
- Efficient component rendering.
- Minimal unnecessary JavaScript.
- Good mobile performance.

### 14.17 SEO and Metadata

Public pages must support:

- Page titles.
- Meta descriptions.
- Open Graph metadata.
- Appropriate heading hierarchy.
- Descriptive image alternative text.
- Sitemap.
- Robots configuration.
- Search engine indexing where appropriate.

Private administrative and client reservation pages must not be publicly indexed.

### 14.18 Frontend Security

The frontend must:

- Never expose secret environment variables.
- Never expose the Supabase service-role key.
- Avoid storing sensitive information unnecessarily.
- Use secure authentication flows.
- Protect private pages.
- Avoid trusting client-side roles or reservation statuses.
- Handle user-provided content safely.

### 14.19 Suggested Project Structure

The frontend should follow a modular structure similar to:

src/
  app/
    (public)/
    (client)/
    admin/
    api/
  components/
    ui/
    layout/
    forms/
  features/
    booking/
    payments/
    clients/
    packages/
    availability/
    notifications/
    reviews/
    admin/
  lib/
    supabase/
    auth/
    validation/
    utils/
  hooks/
  types/

The final structure may be adjusted as implementation progresses.

### 14.20 Frontend Testing

The frontend must be tested for:

- Mobile responsiveness.
- Navigation.
- Booking flows.
- Package selection.
- Calendar interactions.
- Form validation.
- Payment proof submission.
- Client reservation recovery.
- Rescheduling.
- Cancellation.
- Administrative permissions.
- Accessibility.
- Loading and error states.

### 14.21 Implementation Rule

The frontend must never bypass backend business rules.

All sensitive operations must be validated and authorized on the server.

The interface must reflect the approved business architecture without introducing conflicting booking, payment or scheduling rules.

## 15. Admin Dashboard

### 15.1 General Overview

The platform must provide a private administrative dashboard for Farah Dibha.

The dashboard must allow Farah to manage the entire business through a secure interface without directly accessing Supabase.

The dashboard must be responsive and optimized for mobile devices, especially iPhone.

### 15.2 Dashboard Access

Requirements:

- Private administrator authentication.
- Only explicitly authorized administrators may access the dashboard.
- No public administrator registration.
- Secure session management.
- Automatic session expiration where appropriate.
- Logout functionality.
- Server-side authorization for every administrative operation.

### 15.3 Dashboard Overview

The main dashboard must display useful business information, including:

- Today's scheduled sessions.
- Upcoming sessions.
- Pending reservations.
- Pending payment reviews.
- Confirmed payments.
- Expiring reservations.
- Active packages.
- Remaining package sessions.
- New institutional requests.
- Pending reviews.
- Notification delivery failures.

The dashboard must present information clearly without unnecessary visual clutter.

### 15.4 Reservation Management

Farah must be able to:

- View all reservations.
- Search reservations.
- Filter by date.
- Filter by client.
- Filter by reservation type.
- Filter by payment status.
- Filter by reservation status.
- View reservation details.
- View associated scheduled sessions.
- View payment information.
- View reservation history.

Farah must be able to perform authorized administrative actions.

All changes must be validated by the backend and recorded in the audit log.

### 15.5 Individual Session Management

The dashboard must allow Farah to:

- View individual sessions.
- View client details.
- View session date and time.
- View session modality.
- View session status.
- Mark sessions as completed.
- View relevant payment information.
- Review session history.

Only completed sessions may become eligible for client reviews.

### 15.6 Package Management

Farah must be able to:

- View all package reservations.
- Identify the purchased package.
- View the total number of sessions.
- View all scheduled child sessions.
- View completed sessions.
- View remaining sessions.
- View package payment status.
- View package validity.
- Review the package history.

Completing one package session must not automatically complete the entire package.

Only sessions explicitly marked as completed may reduce the remaining session count.

### 15.7 Payment Management

The payment management interface must allow Farah to:

- View pending payments.
- View submitted payment proofs.
- Open authorized private proof files.
- Review payment amounts.
- Confirm payments.
- Reject payments.
- Record rejection reasons.
- View payment history.
- Filter payments by status and date.

Payment confirmation and rejection must be processed securely by the backend.

The dashboard must not allow payment confirmation after the reservation has expired.

### 15.8 Availability Management

Farah must be able to manage her working schedule.

The interface must support:

- Weekly working hours.
- Different hours for each weekday.
- Multiple working periods per day.
- Online availability.
- In-person availability.
- Temporary schedule changes.
- Breaks.
- Holidays.
- Vacation periods.
- Full-day blocks.
- Specific time blocks.
- Multi-day blocks.

Before saving a new availability block, the system must detect conflicts with existing reservations.

Existing reservations must never be silently cancelled or moved.

### 15.9 Calendar Management

The dashboard must include a calendar interface.

Requirements:

- Daily view.
- Weekly view.
- Monthly view.
- Upcoming sessions.
- Individual session identification.
- Package session identification.
- Modality identification.
- Reservation status.
- Client information.
- Availability blocks.

The calendar must display times in Africa/Maputo timezone.

### 15.10 Services and Package Management

Farah must be able to manage available offers.

The interface must support:

- Creating offers.
- Editing descriptions.
- Changing prices.
- Activating and deactivating offers.
- Configuring session duration.
- Configuring package session counts.
- Configuring package validity.
- Managing package descriptions.
- Managing promotional labels.

Changes must not alter historical reservation prices or purchased package information.

### 15.11 Client Management

The dashboard must allow Farah to:

- View registered clients.
- Search by name or phone number.
- View client contact information.
- View reservation history.
- View package history.
- View payment history.
- View completed sessions.
- View eligible reviews.

Client information must remain private and accessible only to authorized administrators.

### 15.12 Review Management

Farah must be able to:

- View submitted reviews.
- View ratings.
- Review written feedback.
- Approve reviews.
- Reject reviews.
- Hide previously published reviews.
- Manage publication status.

Reviews must only be published when the required eligibility and consent conditions are satisfied.

### 15.13 Institutional Request Management

Farah must be able to:

- View institutional requests.
- View organization information.
- View contact information.
- View requested event details.
- Change request status.
- Add internal administrative notes.
- Track request history.

Possible statuses:

- New.
- Under review.
- Contacted.
- Proposal sent.
- Accepted.
- Rejected.
- Completed.

### 15.14 Notification Management

The dashboard must provide visibility into notification activity.

Farah must be able to:

- View scheduled notifications.
- View sent notifications.
- View failed notifications.
- Identify the recipient.
- Identify the notification channel.
- View delivery attempts.
- View failure reasons.
- Retry eligible failed notifications.

Retrying a notification must not create duplicate logical reminders.

### 15.15 Business Settings

The dashboard must support configurable business settings.

Examples:

- Business contact information.
- WhatsApp number.
- Email address.
- Payment instructions.
- M-Pesa receiving information.
- Session duration.
- Booking restrictions.
- Package validity.
- Cancellation policy.
- Working schedule.
- Supported modalities.

Changes to critical settings must be authorized and recorded in the audit log.

### 15.16 Administrative History

The dashboard must provide access to relevant administrative activity.

Examples:

- Payment confirmations.
- Payment rejections.
- Reservation cancellations.
- Administrative reservation changes.
- Session completion.
- Availability changes.
- Offer modifications.
- Permission changes.

Audit records must be protected against unauthorized modification or deletion.

### 15.17 Dashboard User Experience

The dashboard must follow these principles:

- Clean and professional interface.
- Clear navigation.
- Minimal unnecessary text.
- Consistent components.
- Easy-to-understand status indicators.
- Responsive layouts.
- Touch-friendly controls.
- Clear confirmation before sensitive actions.
- Loading, success and error feedback.

The dashboard must be practical to use on an iPhone without requiring a desktop computer.

### 15.18 Dashboard Security

All dashboard operations must enforce:

- Server-side authorization.
- Administrative role verification.
- RLS.
- Input validation.
- Secure file access.
- Audit logging.
- Protection against unauthorized modifications.

Hiding an interface button must never be considered sufficient authorization.

### 15.19 Dashboard Testing

Before launch, test:

- Administrator login.
- Unauthorized access prevention.
- Reservation management.
- Payment confirmation and rejection.
- Package management.
- Session completion.
- Availability changes.
- Conflict detection.
- Calendar accuracy.
- Review moderation.
- Institutional request management.
- Notification visibility.
- Audit history.
- Mobile usability.

### 15.20 Implementation Rule

The administrative dashboard must provide Farah with the tools necessary to operate the business securely and independently.

All business-critical operations must remain consistent with the approved database, backend and security architecture.

## 16. External Integrations

### 16.1 General Architecture

The platform must support secure integrations with external services.

Integrations must be modular and replaceable without requiring major changes to the core application.

All external API credentials must be stored securely on the server.

The frontend must never directly expose private provider credentials.

### 16.2 M-Pesa Integration

M-Pesa will be the initial payment method.

Initial implementation:

- Client receives M-Pesa payment instructions.
- Client completes payment externally.
- Client submits payment proof through the website.
- Farah manually verifies the payment.
- The backend updates the payment and reservation status.

The initial system does not require automatic M-Pesa payment confirmation.

Future implementation may support official M-Pesa API integration if suitable access is available.

Before implementing automatic payments, verify:

- Official API availability.
- Merchant eligibility.
- Registration requirements.
- API documentation.
- Transaction verification mechanisms.
- Webhook support.
- Transaction fees.
- Security requirements.

No payment must be considered confirmed based only on a frontend response or an unverified screenshot.

### 16.3 Volet Integration

Volet is a possible future payment integration.

The architecture must allow Volet to be added without redesigning the reservation and payment database.

Before implementation, evaluate:

- Official API availability.
- Merchant account requirements.
- Payment creation capabilities.
- Server-to-server payment verification.
- Webhook support.
- Refund capabilities.
- Transaction fees.
- Security and authentication requirements.

Volet integration must remain disabled until its technical capabilities and business requirements have been verified.

### 16.4 SMS Integration

SMS will initially be required for reservation recovery through OTP.

The SMS provider must support:

- Sending messages to Mozambique.
- International phone number formats.
- Reliable delivery.
- API-based message sending.
- Delivery status reporting where available.
- Secure API authentication.

The provider must be evaluated for:

- Mozambique coverage.
- Pricing.
- Delivery reliability.
- Sender ID requirements.
- API documentation.
- Rate limits.

OTP messages must never contain sensitive reservation or payment information.

The final SMS provider is pending selection.

### 16.5 WhatsApp Integration

WhatsApp is an important communication channel for the business.

Online sessions will use WhatsApp video calls.

The website must display the official business WhatsApp contact information.

Future automated WhatsApp notifications may include:

- Reservation confirmation.
- Payment status updates.
- Session reminders.
- Rescheduling information.
- Cancellation information.

Automated messaging must use an officially supported integration, such as the WhatsApp Business Platform, if selected.

Before implementation, evaluate:

- Business account requirements.
- API availability.
- Message template requirements.
- Pricing.
- Delivery status reporting.
- User consent requirements.

The system must not depend on unofficial WhatsApp automation.

### 16.6 Email Integration

Email may be used for:

- Administrative notifications.
- Institutional request notifications.
- Client confirmations.
- Payment status updates.
- Important account communications.

The system must support a configurable email provider.

The provider must be evaluated for:

- API availability.
- Delivery reliability.
- Domain verification.
- Sending limits.
- Pricing.
- Deliverability and spam protection.

The official business email is:

farah.dibha.mz@gmail.com

The final email delivery provider is pending selection.

### 16.7 Supabase Integration

Supabase will provide:

- PostgreSQL database.
- Authentication.
- Private file storage.
- Row Level Security.
- Edge Functions.
- Scheduled processing where supported.
- Secure backend communication.

Supabase credentials must follow the security rules defined in Section 11.

### 16.8 Vercel Integration

Vercel will host the Next.js application.

The integration must support:

- GitHub-based deployments.
- Environment variables.
- Preview deployments.
- Production deployments.
- Build logs.
- Deployment monitoring.
- Secure production configuration.

Production and development environments must use separate credentials and configuration where appropriate.

### 16.9 GitHub Integration

GitHub will be the source-control platform.

Requirements:

- Version-controlled source code.
- Version-controlled documentation.
- Database migration history.
- Controlled code changes.
- Commit history.
- Deployment integration with Vercel.

Private secrets and production credentials must never be committed.

### 16.10 External Integration Architecture

External integrations must be accessed through secure backend modules.

The application must separate:

- Payment providers.
- SMS providers.
- WhatsApp providers.
- Email providers.
- Hosting services.
- Database services.

Provider-specific code must not be deeply embedded into business logic.

This architecture must allow a provider to be replaced without rewriting core reservation functionality.

### 16.11 Integration Failure Handling

External service failures must not corrupt the core database.

The system must support:

- Timeouts.
- Safe retries.
- Error logging.
- Delivery attempt tracking.
- Duplicate request protection.
- Provider response validation.
- Operational alerts where appropriate.

A failed SMS, WhatsApp or email delivery must not automatically cancel a valid reservation.

### 16.12 Webhooks and External Events

Future payment integrations may use webhooks.

Webhook processing must:

- Validate authenticity.
- Verify provider signatures where supported.
- Reject unauthorized events.
- Prevent replay attacks.
- Prevent duplicate processing.
- Record relevant event identifiers.
- Validate transaction details server-side.
- Update payment records through secure backend operations.

No webhook must be trusted without proper verification.

### 16.13 Privacy and Data Sharing

Only the minimum information necessary must be shared with external providers.

Sensitive client information must not be transmitted unnecessarily.

Provider data processing and privacy practices must be reviewed before integration.

### 16.14 Integration Testing

Before production use, test:

- API authentication.
- Successful requests.
- Failed requests.
- Timeouts.
- Retry behavior.
- Duplicate events.
- Invalid webhook signatures.
- Delivery status updates.
- Provider unavailability.
- Secret protection.

### 16.15 Pending Provider Decisions

The following decisions remain open:

- Official M-Pesa API integration.
- Volet API integration.
- SMS provider.
- WhatsApp Business Platform integration.
- Email delivery provider.
- Notification channel priorities.
- Provider pricing and operational limits.

No provider must be selected based only on assumptions about availability or cost.

### 16.16 Implementation Rule

All external integrations must be implemented securely, documented and tested.

The core reservation, payment and scheduling systems must remain operational even when an external communication provider is temporarily unavailable.

## 17. Privacy and Data Protection

## 18. Testing Strategy

## 19. Deployment

## 20. Pending Decisions