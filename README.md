# Record Shop — Frontend

A Blazor frontend application for a record shop inventory system, connected to an ASP.NET Core REST API.

The app allows users to browse the record catalogue, view album details, manage inventory data, and interact with an in-progress AI catalogue assistant.

## Features

- Browse all records in the catalogue
- Search records by title, artist, genre, year, price, or stock
- View individual album details
- Add new records to the catalogue
- Update existing album details
- Delete records from the catalogue
- Display album cover images
- Navigate between home, catalogue, detail, add-record, about, and AI assistant pages
- Show user-friendly loading, success, error, and empty-state messages
- Connect to the Record Shop Backend API using `HttpClient`
- In-progress AI assistant page using a mock response service while Azure AI integration is being developed

## Tech Stack

- Blazor
- C#
- HTML
- CSS
- Bulma CSS
- REST API integration
- ASP.NET Core backend integration
- Azure AI prototype integration

## Backend API

This frontend connects to the Record Shop Backend API.

Backend repository:

```text
https://github.com/YeeMonAung17/Record-Shop-API
