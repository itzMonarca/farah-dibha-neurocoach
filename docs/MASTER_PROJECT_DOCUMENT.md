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

## 7. Packages and Multiple Sessions

## 8. Payment System

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