# Amadeus GraphQL Schema

This document describes a conceptual GraphQL schema for the Amadeus for Developers API platform. Amadeus is the leading technology provider for the global travel and tourism industry, offering 40+ travel REST APIs across flights, hotels, destination experiences, cars and transfers, market insights, itinerary management, and AI-powered prediction services.

## Overview

The Amadeus GraphQL schema provides a unified type system that spans the full breadth of the Amadeus Self-Service catalog:

- **Flights** — search, price, book, and manage flight orders across 500+ airlines
- **Hotels** — search hotel offers and check rates and availability
- **Destination Experiences** — discover tours, activities, and points of interest
- **Cars and Transfers** — search and book ground transfers
- **Market Insights** — flight delay predictions, trip purpose detection, travel demand analytics
- **Itinerary Management** — build and manage multi-leg trip plans
- **Authentication** — OAuth2 client credentials token management

## Schema File

See [amadeus-schema.graphql](amadeus-schema.graphql) for the full type definitions.

## Core Type Groups

### Flight Types
`Flight`, `FlightDetails`, `FlightOffer`, `FlightPrice`, `FlightItinerary`, `Itinerary`, `Segment`, `SegmentDetails`, `Duration`, `Departure`, `Arrival`, `Stop`, `FlightStatus`, `FlightDelay`, `DelayPrediction`, `DelayTime`

### Aircraft and Airline Types
`Aircraft`, `AircraftType`, `Airline`, `AirlineDetails`, `AirlineCode`

### Airport and Location Types
`Airport`, `AirportDetails`, `AirportCode`, `Terminal`, `Gate`, `Location`, `Geo`

### Seating Types
`Seat`, `SeatMap`, `SeatMapDetails`, `Cabin`, `CabinClass`

### Fare and Pricing Types
`Fare`, `FareDetails`, `FareBreakdown`, `Price`, `PriceDetails`, `TaxDetails`, `PriceOptions`

### Traveler Types
`Traveler`, `TravelerDetails`, `TravelerType`, `Passenger`, `PassengerDetails`, `Document`, `DocumentType`, `Contact`, `ContactDetails`, `ContactPurpose`

### Hotel Types
`Hotel`, `HotelDetails`, `HotelOffer`, `HotelSearchArea`, `RoomDetails`, `RoomType`, `RoomCategory`, `RateCode`, `RatePlan`, `Checkin`, `Checkout`

### Transfer and Activity Types
`Transfer`, `TransferDetails`, `Activity`, `ActivityDetails`, `POI`, `POIType`

### AI Prediction Types
`TripPurpose`

### Authentication Types
`AuthToken`, `APIKey`, `Token`

### Pagination
`PageInfo`

## Authentication

The Amadeus API uses OAuth2 client credentials. Request a token via the `/v1/security/oauth2/token` endpoint with `grant_type=client_credentials`, `client_id`, and `client_secret`. The returned `access_token` (Bearer) must be included in all subsequent API requests.

## Environments

- **Test**: `https://test.api.amadeus.com` — free, rate-limited sandbox
- **Production**: `https://api.amadeus.com` — paid, higher throughput

## Reference

- Developer portal: https://developers.amadeus.com/
- API catalog: https://developers.amadeus.com/self-service
- Note: The Self-Service portal is scheduled for decommission on 17 July 2026; Enterprise customers retain equivalent access.
