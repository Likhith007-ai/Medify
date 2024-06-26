# MEDIFY - Medical Center Slot Booking Platform

## Overview

MEDIFY is a React-based web application that allows users to find medical centers in a specific state and city across the USA and book appointments. The platform includes features like browsing medical centers, booking appointments, and viewing booked appointments.

## Features

1. **Landing Page:**
   - Top navigation bar with sections like Find Doctors, Hospitals, Medicines, and more.
   - Search section with dropdowns to select state and city, fetching options from an API.

2. **Search Results Page:**
   - Displays available medical centers based on selected state and city.
   - Option to book appointments.

3. **Booking Interface:**
   - Calendar interface to choose appointment dates (up to one week in advance).
   - Selection of available time slots for the chosen day.

4. **My Bookings Page:**
   - Displays all user bookings with details such as medical center name, appointment date, and time.

5. **Responsive Design:**
   - Fully responsive and adheres to provided design standards.
   - Utilizes Swiper library for carousels.

## API Endpoints

- Get a list of all states:
  `https://meddata-backend.onrender.com/states`

- Get a list of all cities of a particular state:
  `https://meddata-backend.onrender.com/cities/:state`
  Example: `https://meddata-backend.onrender.com/cities/Alaska`

- Get a list of all medical centers based on state and city:
  `https://meddata-backend.onrender.com/data?state=<state-name>&city=<city-name>`
  Example: `https://meddata-backend.onrender.com/data?state=Alaska&city=SOLDOTNA`

## Local Setup

1. Clone the repository:
   
   git clone https://github.com/Likhith007-ai/Medify.git
