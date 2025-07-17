# Location-Getter
#It will just Fetch the location and other details  of the User.


# 🌍 Location Tracker via Web Permission

This is a simple web-based project that allows you to capture the location (latitude and longitude) of a user who grants location access through their browser. Once the user consents, their location is retrieved and sent to a Google Apps Script endpoint.

## 🚀 Features

- Requests user's location via browser permission.
- Captures accurate latitude and longitude.
- Sends the data to a Google Apps Script web app endpoint.
- Lightweight and simple to deploy.

## 📂 Project Structure

- `index.html` – Front-end interface that prompts location access.
- JavaScript embedded in the HTML to fetch geolocation and send it via HTTP request.
- Google Apps Script Web App to receive and store the data.

## 🔗 Live Deployment

Google Script Web App URL (Receiver Endpoint):

```
https://script.google.com/macros/s/AKfycby5uKaq9cLOfw387GiZJYTMJ_3Unk5J2YRm9HscjHoMngkB7i9XkuxLLdeHAIL9hlyQDQ/exec
```

## 🛠️ How It Works

1. User opens your webpage.
2. The browser asks for location permission.
3. If accepted, the user's location is fetched using the `navigator.geolocation` API.
4. The coordinates are sent via a `GET` request to the Google Script endpoint.
5. The server-side script can then log, store, or process the location data as needed.

## 📦 How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Raktim-GH/Location-Getter.git
   ```

2. **Edit the Google Apps Script**  
   Use the provided endpoint or deploy your own Apps Script to handle incoming location data.

3. **Open `index.html` in a browser**  
   Share this HTML file or host it on any platform (GitHub Pages, Netlify, Vercel, etc.).

4. **View Results**  
   Check your Apps Script backend or spreadsheet to view received coordinates.

## ⚠️ Disclaimer

This tool only works if the user **manually consents** to share their location. It **does not bypass** browser permissions or privacy controls.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

