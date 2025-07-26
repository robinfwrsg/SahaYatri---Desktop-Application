# 🏔SahaYatri: Tourism Management System

**SahaYatri** is a modern **JavaFX-based desktop application** for managing tourism operations in Nepal. It allows **tourists**, **guides**, and **administrators** to seamlessly interact with destination data, bookings, and user management — all within a clean and dynamic UI.

---

## Features

### Tourist
- View curated destinations across Nepal
- Book trips with available guides and dates
- View personal bookings

### Guide
- View available bookings
- Accept and manage assigned bookings

### Admin
- Add, edit, or delete:
  - Tourists
  - Guides
  - Destinations
  - Bookings
- Export booking data to `.csv`
- View chart of **most booked destinations**

---

## 🛠Built With

- **Java 17**
- **JavaFX 21**
- **Scene Builder**
- **Maven** (optional for dependency mgmt)
- **FXML** for UI structure
- **CSS** for styling

---

## Project Structure

```bash
src/
├── main/
│   ├── java/
│   │   └── tourismapp/
│   │       ├── model/               # Models like Tourist, Guide, Booking
│   │       ├── Controller/          # All JavaFX controllers
│   │       └── Main.java            # App entry point
│   └── resources/
│       ├── fxml/                    # All .fxml files for UI
│       ├── css/                     # Custom stylesheets
│       └── images/                  # Optional icons or logos
