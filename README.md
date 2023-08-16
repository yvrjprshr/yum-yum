# YumYum - Food Ordering App 🍕🍟

YumYum is a ReactJS project that serves as a food ordering app. It utilizes Swiggy's public APIs to fetch data and incorporates React Router DOM for seamless navigation. The project extensively leverages hooks and prop drilling for efficient data management.


## Features 🧑‍💻

- Custom Hooks
- Shimmer UI made from scratch
- Search Feature
- Cart Feature using useContext + useReducer
- Lazy Loading | Code Splitting

## Tech Stack ⚙️

- React JS
- Parcel
- React Router Dom
- Tailwind CSS
- Node JS
- Express JS
- Custom React Hooks
- Context API
- Shimmer UI

## Note

I am using simple node.js web server that fetches data from a third-party (Swiggy) API and exposes it to a client (YumYum) app.This is done to avoid the CORS error while accessing the Swiggy API.

# Swiggy API Proxy Server

This server is a simple Node.js web server that acts as a proxy for fetching data from the third-party Swiggy API and exposing it to the client application, YumYum. The primary purpose of this server is to avoid CORS (Cross-Origin Resource Sharing) errors that may occur when directly accessing the Swiggy API from the client-side.

## How server Works

The Swiggy API proxy server serves as an intermediary between the YumYum client app and the Swiggy API. When the client app sends a request for data, it is sent to the proxy server. The server, in turn, fetches the requested data from the Swiggy API on behalf of the client and forwards it back as a response.

By using this proxy server, the client app can avoid any CORS-related issues that might occur due to the restrictions imposed by the Swiggy API.
