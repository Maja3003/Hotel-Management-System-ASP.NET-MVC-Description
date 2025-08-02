# Hotel-Management-System-ASP.NET-MVC-Description
A comprehensive ASP.NET Core MVC web application designed for hotel management, supporting reservations, dining, administration, and guest interaction. The system facilitates a seamless experience for guests, staff (receptionists and cleaners), and admins.

<h3 style="font-weight: bold;">Overview</h3>
<p align="center">
  <img src="https://i.imgur.com/2LbhbEX.png" width="100%">
  <img src="https://i.imgur.com/5iW1zKk.png" width="100%">
  <img src="https://i.imgur.com/QyWZ3Zi.png" width="100%">
  <img src="https://i.imgur.com/wx9ciY0.png" width="100%">
  <img src="https://i.imgur.com/aJXTm8C.png" width="100%">
  <img src="https://i.imgur.com/4Qx145D.png" width="100%">
</p>

<h3 style="font-weight: bold;">Accomodations</h3>
<p align="center">
  <img src="https://i.imgur.com/Q4fyXLH.png" width="100%">
  <img src="https://i.imgur.com/YCApDTj.png" width="100%">
</p>

<h3 style="font-weight: bold;">Learn More</h3>
<p align="center">
  <img src="https://i.imgur.com/bOLIeIs.png" width="100%">
</p>

<h3 style="font-weight: bold;">Book Room</h3>
<p align="center">
  <img src="https://i.imgur.com/vubBaTL.png" width="100%">
</p>

<h3 style="font-weight: bold;">Checkout</h3>
<p align="center">
  <img src="https://i.imgur.com/w3TW8Q1.png" width="100%">
  <img src="https://i.imgur.com/EJ8yJR0.png" width="100%">
</p>

<h3 style="font-weight: bold;">Success</h3>
<p align="center">
  <img src="https://i.imgur.com/qe47zht.png" width="100%">
</p>

...

## Features
### 🧑 User Roles
- **Guest**: 
  - View and filter available rooms.
  - Reserve rooms (with Member Rate if logged in).
  - View their own room and dining reservations.
  - Contact reception via internal messaging.
  - Modify check-out date (earlier/later).
  - Order food directly to their room.

- **Receptionist**:
  - Receive and respond to guest messages.
  - View all room and dining reservations.
  - Search reservations by guest email.
  - View and manage food orders.

- **Cleaner**:
  - Access a list of rooms scheduled for cleaning on the current day.

- **Admin**:
  - Receive messages from non-logged-in users.
  - View all reservations and details.
  - Search room bookings by guest email.
  - Manage hotel rooms (add/edit).
  - View and assign roles to hotel staff.

### 🔒 Authentication & Role Management
- Role-based access control using ASP.NET Identity.
- Auto-registration for users after booking a room (for non-logged-in users).
- Unique routing and permissions per role (Admin, Guest, Receptionist, Cleaner).
- Secure login, registration, and session management.

### 🛏 Room Booking
- Room search with filters (bed type, view, price).
- Public pricing for visitors (Flexible Rate).
- Member pricing for logged-in users (Member Rate Flexible).
- Automatic account creation and password generation during booking.

### 🍽 Dining
- Browse hotel restaurant menu.
- Table reservation system with confirmation view.
- Logged-in users can track their own table reservations.
- Guests can place food orders to their rooms.

### 📩 Messaging & Inbox
- Non-logged-in users can send messages via Contact Us.
- Logged-in guests can message reception through an internal inbox.
- Receptionists can reply to guest messages directly from their panel.

### 📊 Admin Panel
- View/manage hotel rooms and their availability.
- Browse all reservations and filter by guest email.
- Manage staff users and assign them to predefined roles.
- Review all restaurant table bookings and inbox messages.

### 📍 Public Access Features (for visitors)
- Accessible pages without login: Overview, Accommodations, Dining, Location, Contact Us, Terms, Privacy, Cookies, Accessibility.
- Public users can browse and filter available rooms.
- Restaurant menu and table booking available without login.
- Account creation and login options.
- Contact form for inquiries.

### 💡 UX & System Qualities
- Responsive, user-friendly interface.
- Clear feedback messages after operations like registration, booking, or messaging.
- Secure form handling with server-side validation (e.g., date logic for check-out changes).
- Graceful error handling and rollback for failed database operations (e.g., user registration).
- Room filtering to support user personalization and search convenience.

## Technologies Used
- **Backend**: ASP.NET Core MVC, Entity Framework Core
- **Authentication**: ASP.NET Core Identity
- **Frontend**: Razor Views, HTML5, CSS3, JavaScript
- **Database**: SQL Server (via EF Core)
- **Miscellaneous**: TempData, ViewBag/ViewData for UX feedback, responsive design placeholders

## Possible Improvements
- **Unit & Integration Tests**: Improve test coverage for models and controller logic.
- **Mobile Responsiveness**: Implement responsive layout for a better mobile experience.
- **Language**: Add multilingual support for international guests.
- **Attractions Section**: Add a dedicated attractions page with booking options.
- **Integration with External Payment Systems**:
  - Support online payments through third-party gateways.
  - Enable digital wallets as alternative payment methods.
- **Mobile Application**:
  - Develop a cross-platform app for iOS and Android.
  - Add push notifications for reservation status, promotions, and stay reminders.

