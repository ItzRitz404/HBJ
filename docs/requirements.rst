Jale at Highgate Hair and Beauty
================================

Overview
--------

Jale at Highgate Hair and Beauty requires a web application that displays available treatments and allows customers to book appointments online.

Customers will be able to register for an account, log in, or continue as a guest. They can select one or more treatments, view available appointment times based on the total treatment duration, and confirm their booking.

Once a booking has been made, the customer and owner will receive an email confirmation. The booking will also automatically appear in the web application's calendar.

The owner will be able to manage both online bookings and appointments made by telephone using the application's calendar.

Payments will not be processed through the website. Customers will pay at the salon using either cash or card.


Project Goals
-------------

The main goals of the project are:

* Make treatments, prices, durations, and booking information easy for customers to browse.
* Display available appointment times based on the selected treatments and existing appointments.
* Prevent appointments from overlapping.
* Ensure there is at least a 15-minute gap between appointments.
* Provide the owner with a clear and simple calendar for viewing and managing bookings.
* Provide customers with useful information such as contact details and the salon's location.
* Allow the owner to add, edit, and remove treatments without needing to modify the application code.


Functional Requirements
-----------------------

.. list-table:: Functional Requirements
   :widths: 10 90
   :header-rows: 1

   * - ID
     - Requirement
   * - FR1
     - The system shall display a list of treatments showing the treatment name, description, duration, and price.
   * - FR2
     - The system shall allow the owner to add, edit, and remove treatments.
   * - FR3
     - The system shall allow customers to register, log in, and log out of their account.
   * - FR4
     - The system shall allow customers to continue as a guest without creating an account.
   * - FR5
     - The system shall allow customers to select more than one treatment and automatically calculate the combined treatment duration and total price.
   * - FR6
     - The system shall display available appointment dates and start times based on the selected treatments, salon working hours, and existing appointments.
   * - FR7
     - The system shall prevent overlapping appointments and ensure there is a minimum 15-minute gap between appointments.
   * - FR8
     - The system shall allow customers to review their selected treatments, appointment time, total duration, and total price before confirming their booking.
   * - FR9
     - The system shall automatically add confirmed customer bookings to the application's calendar.
   * - FR10
     - The system shall send a booking confirmation email to both the customer and the owner.
   * - FR11
     - The system shall provide a calendar that allows the owner to view appointments by day, month, and year and view appointment details.
   * - FR12
     - The system shall allow the owner to manually add, edit, and delete appointments, including bookings received by telephone.
   * - FR13
     - The system shall display the salon's contact information, location, and a map showing the salon's location.
   * - FR14
     - The system shall clearly state that payments are made in person at the salon using cash or card.