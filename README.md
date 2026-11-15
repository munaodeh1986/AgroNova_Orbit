# AgroNova Orbit

**Connecting the field to space, and data to decisions.**

AgroNova Orbit is a community-driven smart farming decision-support system that helps farmers adapt crop rotations and protect soil health under a changing climate. It combines local field measurements from an ESP32-based sensor node with open NASA Earth-observation data to turn complex environmental information into clear, practical, and transparent decision support.

This project was developed for the **NASA Space Apps Challenge 2026 — Riyadh**, for the challenge **Adapting Farms with NASA Data**.

---

## Live Demo

Open `index.html` directly in any modern web browser.

No installation, build step, or server is required.

---

## What It Does

AgroNova Orbit combines:

- Local field-node measurements
- NASA Earth-observation data
- Farmer priorities
- Crop-rotation traits
- Community knowledge

to support decisions related to:

- Drought stress
- Heat stress
- Nutrient imbalance
- Abnormal crop growth
- Soil protection
- Erosion risk
- Climate-resilient crop rotation

The system is designed as a decision-support tool, not a replacement for farmer knowledge, local expertise, or on-the-ground judgment.

---

## Key Features

- ESP32-style field-node dashboard
- Simulated sensor data with optional live ESP32 JSON endpoint
- NASA POWER live integration
- NASA Earth-observation data framework
- Rule-based early-warning engine
- Soil-protection and erosion-risk indicator
- Climate scenario controls for rainfall and warming
- Interactive SVG field map with multiple layers
- Crop-rotation explorer with farmer priority weights
- Side-by-side rotation comparison
- Printable farmer brief export
- Farmer Voice feed with tagged experiences
- Community voting and resilience summary
- Long-term NASA POWER trend panel
- Glossary and data-source status table
- Beginner and expert modes
- Accessible, responsive, single-file interface

---

## NASA Data Used

AgroNova Orbit integrates open NASA Earth-observation data sources, including:

- NASA POWER
- NASA SMAP
- NASA GPM IMERG
- NASA Landsat
- NASA MODIS
- NASA ECOSTRESS
- NASA SRTM
- NASA Earthdata
- NASA Open Data

NASA POWER is connected live through its API. Other NASA datasets are integrated within the platform’s open-data framework and are clearly labeled according to their current status.

---

## How It Works

1. The ESP32 field node measures soil moisture, air temperature and humidity, NPK nutrients, soil temperature, GPS location, rainfall, light, and crop height.
2. NASA Earth-observation data provides regional climate, soil-moisture, rainfall, vegetation, heat, and terrain context.
3. The system detects early signs of drought stress, heat stress, nutrient imbalance, and abnormal crop growth.
4. A soil-protection and erosion-risk indicator is computed from terrain slope, rainfall intensity, vegetation cover, soil moisture, and heat stress.
5. Farmers set priorities for water savings, soil health, erosion control, income, forage value, nitrogen fixation, and organic-matter improvement.
6. The rotation explorer compares the current rotation with climate-resilient alternatives.
7. The farmer receives transparent recommendations with uncertainty, risks, and local-validation reminders.

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Inline SVG icons and charts
- Fetch API
- NASA POWER API
- ESP32 hardware concept
- VL53L0X laser distance sensor
- Responsive web design
- Web accessibility best practices
- Print-ready export

---

## Hardware Concept

The ESP32-based field node is designed to measure:

- Soil moisture
- Air temperature
- Relative humidity
- NPK nutrients
- Soil temperature
- GPS location
- Rainfall
- Light intensity
- Crop height using a VL53L0X laser distance sensor

The dashboard can operate in simulated mode or connect to a live ESP32 JSON endpoint.

---

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Use the dashboard in simulated mode, or connect a live ESP32 JSON endpoint if available.
4. Explore the field node, NASA data, early warnings, erosion risk, field map, rotation explorer, community features, and long-term trends.

No additional dependencies or build tools are required.

---

## Data Integrity

AgroNova Orbit clearly labels data as:

- Live
- Open NASA data
- Simulated
- Farmer input
- Planned

The platform emphasizes transparency, responsible data use, and the importance of local agronomic validation.

---

## Future Work

- Connect more NASA datasets live, especially SMAP or GPM IMERG
- Add soil-type and crop-calendar layers
- Improve yield-risk and irrigation recommendations
- Pilot the system with real farms and local agronomists
- Expand community features and offline support
- Support multiple languages for wider farmer access

---

## Team

Future Force
Muna Salah Odeh
Tala Hussein ABUZAYYAD 
RoKAIA Mohammed AMMAR 
Lulu Faisal alneim 
Vasiliki Saloustrou


---

## License

This project is provided for educational and challenge purposes.

---

## NASA Attribution

NASA does not endorse any non-U.S. Government entity and is not responsible for information on non-U.S. Government websites. Users must comply with the data use terms of each website.

---

AgroNova Orbit — Connecting the field to space, and data to decisions.
