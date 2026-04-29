# 📍 Detroit Family Resource Map

An interactive, mobile-friendly map built for **Cycle Families** to connect Detroiters with essential resources. This map pulls real-time data from Google Sheets and organizes it into 21 searchable categories.

## 🚀 Live Link
[View the Live Map](https://cyclefamilies.github.io/map/)

## 🛠 Features
- **Dynamic Filtering:** A horizontal category bar for easy navigation between Food, Health, Housing, etc.
- **Smart URL Parameters:** Ability to load the map with a specific category pre-filtered (e.g., `?cat=Food`).
- **Mobile Optimized:** Large touch targets and action-oriented popups with one-tap calling and GPS directions.
- **Auto-Sync:** Updates automatically whenever the connected Google Sheet is modified.

## 📂 Project Structure
- `index.html`: The main application (HTML5, CSS3, and JavaScript).
- `README.md`: Project documentation and setup guide.

## 🔄 How to Update the Map
1. **Edit the Spreadsheet:** Add or edit rows in your connected Google Sheet.
2. **Coordinates are Key:** Ensure every entry has a **Latitude** and **Longitude**. The map will not display pins without these numbers.
3. **Category Matching:** The map uses a "Logic Engine" to sort pins. Ensure your categories or descriptions include keywords like "Food," "Clinic," "Legal," or "Housing."

## 🔗 Embedding on WordPress
To embed this map on your WordPress pages, use a **Custom HTML** block and the following code:

```html
<iframe 
    src="[https://cyclefamilies.github.io/map/](https://cyclefamilies.github.io/map/)" 
    width="100%" 
    height="650px" 
    style="border:none;" 
    title="Detroit Family Resource Map">
</iframe>
