# 📍 Detroit Family Resource Map

An interactive, mobile-friendly map designed to connect Detroit families with essential resources. This map pulls real-time data from a Google Sheet and organizes it into 21 searchable categories.

## 🚀 Live Link
[View the Live Map]([https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/](https://cyclefamilies.github.io/map/map.html))

## 🛠 Features
- **Dynamic Filtering:** Horizontal category bar allowing users to switch between Food, Housing, Health, and more.
- **Smart URL Parameters:** Link directly to a specific category (e.g., `?cat=Food`)—perfect for embedding on different website pages.
- **Action-Oriented Popups:** One-tap calling and GPS directions for every location.
- **Automated Data:** Updates automatically when the connected Google Sheet is edited.

## 📂 Project Structure
- `index.html`: The core application (HTML, CSS, and JavaScript).
- Google Sheet: The database containing names, addresses, and coordinates.

## 🔄 How to Update the Map
1. **To Add Resources:** Simply add a new row to your Google Sheet.
2. **Geocoding:** Ensure every new entry has a **Latitude** and **Longitude**. (Use the "Map Tools" script in the sheet to generate these if missing).
3. **Categories:** Use keywords like "Pantry" for Food or "Clinic" for Health in the Category column to ensure the map's logic engine sorts them correctly.

## 🔗 Embedding on WordPress
To embed this map on a WordPress page, use a **Custom HTML** block and paste the following iframe code:

```html
<iframe 
    src="https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/" 
    width="100%" 
    height="650px" 
    style="border:none;" 
    title="Detroit Family Resource Map">
</iframe>
