📍 Safarnama: The Future of NSW Transit

Navigate NSW with electric ease. Real-time tracking, live car park occupancy, and smart trip planning—all in one electric luxury interface.

📱 About The App

Safarnama (formerly "Get Me Somewhere") is a next-generation public transport companion built for New South Wales, Australia.

While apps like Google Maps and Opal provide basic routing, Safarnama bridges the gap by offering granular, real-time data that daily commuters actually need—such as live parking spot availability, school bus tracking, and specific on-demand service visualization.

Built with Flutter, it features a modern "Electric Luxury" design language using Indigo and Rose gradients.

✨ Key Features

🚌 Advanced Real-Time Tracking

Unlike standard trackers, Safarnama utilizes specific logic to categorize and color-code vehicles based on their service type (GTFS-R data):

🟡 School Buses: Distinctly marked in yellow for easy identification by parents/students.

🟣 On-Demand & Coaches: Marked in purple (including Hillsbus and On-Demand services).

🔵 Standard Buses: Blue markers for general public transport.

🟢 Ferries & 🟠 Trains: Full support for the entire NSW network.

🅿️ Live Car Park Occupancy

Stop guessing if there's a spot at the Park & Ride.

Fetches real-time occupancy data from Transport NSW hubs.

Displays Live/Occupied counts.

Provides Zone-level breakdowns (e.g., Level 1 vs Level 2).

One-tap navigation to the car park entrance.

🗺️ Smart Trip Planning

"Arrive By" Logic: distinct routing logic compared to standard "Depart At".

Departure Monitor: Live departure boards for any stop.

Leg-by-Leg breakdown: Detailed view of interchanges and connection times.

🎨 Modern UI/UX

Electric Luxury Theme: A polished dark/light mode interface.

Fluid Animations: Smooth transitions between maps and list views.

User Preferences: Save Home, Work, and Favorited trips locally using Shared Preferences.

📸 Screenshots

Home Screen

Live Tracking

Trip Results

Car Parks

<img src="screenshots/home.png" width="200" />

<img src="screenshots/tracking.png" width="200" />

<img src="screenshots/results.png" width="200" />

<img src="screenshots/carparks.png" width="200" />

(Note: Please add your screenshots to a screenshots folder in your repo)

🛠️ Tech Stack

Framework: Flutter (Dart)

Maps: flutter_map (OpenStreetMap integration) & latlong2

State Management: setState & StatefulWidget architecture

Networking: http & protobuf (for GTFS Realtime feeds)

Location: geolocator

Persistence: shared_preferences (for saving favorites/recent trips)

API Source: Transport for NSW Open Data

🚀 Getting Started

Prerequisites

Flutter SDK

Android Studio / VS Code

An API Key from Transport for NSW Open Data

Installation

Clone the repository

git clone [https://github.com/DoomBuoy/Safarnama.git](https://github.com/DoomBuoy/Safarnama.git)
cd Safarnama


Install Dependencies

flutter pub get


Configure API Key

Open lib/api_service.dart (and realtime_service.dart)

Replace the _apiKey variable with your own Open Data Token.

Note: For production, ensure keys are secured using environment variables.

Run the App

flutter run


📥 Download

The latest Android APK is available in the Releases section or directly via the website.

Download APK

🔮 Roadmap

[ ] iOS Release: Optimization for Apple devices.

[ ] Push Notifications: Alerts for delays on favorite routes.

[ ] Widgets: Home screen widgets for "Next Trip".

[ ] Offline Mode: Cached timetables for low-signal areas.

👨‍💻 Developer

Agam Singh Saini Student at University of Technology Sydney (UTS)

I am a passionate developer and data enthusiast open to opportunities in Data Science and Software Engineering.

🌍 Portfolio: doombuoy.github.io/Portfolio

💼 LinkedIn: Agam Singh Saini

📧 Email: agamsingh.saini@students.uts.edu.au

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

Disclaimer: This app is an independent project and is not officially affiliated with Transport for NSW.