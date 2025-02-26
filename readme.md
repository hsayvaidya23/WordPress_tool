# URL Duplication Tool

This tool helps you remove duplicate URLs from a list. You can either paste the URLs directly into the text area or upload a CSV or TXT file containing the URLs.

## Features

- Paste URLs directly into the text area.
- Upload a CSV or TXT file containing URLs.
- Displays the original count, unique count, and the number of duplicates removed.
- Download the results as a text file.

## Usage

1. Open the `URLDupblication.html` file in your browser.
2. Paste your URLs into the text area or upload a CSV/TXT file.
3. Click the "Remove Duplicates" button.
4. View the results in the results section.
5. Click the "Download Results" button to download the deduplicated list.

## File Structure

- `url duplication/`
  - `sample urls.txt`
  - `sample_urls.csv`
  - `URLDupblication.html`

# Weather API Tool

This tool allows you to get the current temperature and weather conditions for a specified location using the OpenWeather API.

## Features

- Enter a city name to get weather information.
- Displays temperature, weather description, feels like temperature, humidity, and wind speed.
- Provides location suggestions as you type.

## Usage

1. Open the `WeatherAPI.html` file in your browser.
2. Enter a city name in the input field.
3. Click the "Get Weather" button.
4. View the weather information in the results section.

## Adding the API Key

To use the Weather API Tool, you need to add your OpenWeather API key. Follow these steps:

1. Open the `WeatherAPI.html` file in a text editor.
2. Locate the following line in the script section:
   ```javascript
   const OPENWEATHER_API_KEY = ''; // Replace with your API key


# Integrating Custom HTML, CSS, and JavaScript Pages into WordPress

## Prerequisites
- A WordPress website (self-hosted or WordPress.com Business plan)
- Admin access to install and manage plugins

## Step 1: Install Necessary Plugins
1. Log in to your WordPress Admin Dashboard.
2. Navigate to **Plugins > Add New**.
3. Search for the following plugins:
   - **Insert HTML Snippet** (for embedding HTML code)
   - **Custom CSS & JS** (for adding styles and scripts)
4. Click **Install Now** and then **Activate** each plugin.

## Step 2: Add Custom HTML Code
1. Go to **Insert HTML Snippet** in the WordPress Admin panel.
2. Click **Add New HTML Snippet**.
3. Paste your HTML code into the editor.
4. Click **Save** and copy the generated shortcode.
5. Open a post or page in the WordPress Editor.
6. Paste the shortcode where you want the HTML to appear.
7. Click **Update/Publish** to save changes.

## Step 3: Add Custom CSS
1. Navigate to **Appearance > Customize > Additional CSS**.
2. Paste your CSS styles.
3. Click **Publish** to apply the changes.
   
Alternatively, using the **Custom CSS & JS** plugin:
1. Navigate to **Custom CSS & JS > Add Custom CSS**.
2. Click **Add New CSS Code**.
3. Paste your CSS and save it.

## Step 4: Add Custom JavaScript
1. Go to **Custom CSS & JS > Add Custom JavaScript**.
2. Click **Add New JS Code**.
3. Paste your JavaScript code.
4. Select **Frontend** as the location.
5. Click **Save** and ensure the script is enabled.

## Step 5: Verify the Integration
1. Open the page or post where you inserted the HTML.
2. Check if the page displays correctly with the applied styles and scripts.
3. Use browser Developer Tools (`F12`) to debug if necessary.

## Step 6: Optimize Performance (Optional)
- Use a **caching plugin** like WP Rocket or W3 Total Cache for faster loading.
- Minify CSS and JS using the **Autoptimize** plugin.

---



