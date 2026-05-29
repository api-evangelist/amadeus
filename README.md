# Amadeus (amadeus)

Amadeus for Developers is the self-service developer program from Amadeus IT Group, the leading technology provider for the global travel and tourism industry. The Self-Service catalog offers 40+ travel REST APIs across flights, hotels, destination experiences, cars and transfers, market insights, itinerary management, and AI-powered prediction services. APIs use OAuth2 client credentials authentication and are organized into Test (free, capped) and Production (paid, higher TPS) environments. Note: Amadeus has announced the Self-Service developer portal will be decommissioned on 17 July 2026; Enterprise customers retain access to the equivalent Enterprise APIs.

**URL:** [Visit APIs.json URL](https://amadeus.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=amadeus-api-evangelist&utm_content=repo)

## Tags:

 - Travel, Travel Technology, Reservations, Flights, Hotels, Airlines, Hospitality, Tours and Activities, Cars and Transfers, Destination Content, Itinerary Management, Trip Planning, Artificial Intelligence, Market Insights

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-29

## APIs

### Flight Offers Search

Searches over 500 airlines to find the cheapest flight offers for a given itinerary. Supports one-way, round-trip, and multi-city searches with rich filtering (cabin class, max price, included/excluded airlines, non-stop preferred).

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Flights, Search, Pricing, Itinerary

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)
- [OpenAPI](openapi/amadeus-flight-offers-search-openapi.yml)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search/api-reference)
- [NaftikoCapability](capabilities/flight-offers-search-shopping.yaml)
- JSONSchema: 53 files (see `json-schema/`)
- JSONStructure: 53 files (see `json-structure/`)
- Example: 31 files (see `examples/`)

---

### Flight Offers Price

Confirms the final price and availability of a flight offer returned by Flight Offers Search, including taxes, fees, and fare rules, before booking.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Pricing, Pre-Booking

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)
- [OpenAPI](openapi/amadeus-flight-offers-price-openapi.yml)
- [NaftikoCapability](capabilities/flight-offers-price-shopping.yaml)
- JSONSchema: 65 files (see `json-schema/`)
- JSONStructure: 65 files (see `json-structure/`)
- Example: 36 files (see `examples/`)

---

### Flight Create Orders

Books a flight offer by creating a flight order (PNR) with traveler details, contact info, and payment, returning the order ID and ticketing reference.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Booking, Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)
- [OpenAPI](openapi/amadeus-flight-create-orders-openapi.yml)
- [NaftikoCapability](capabilities/flight-create-orders-booking.yaml)
- JSONSchema: 81 files (see `json-schema/`)
- JSONStructure: 81 files (see `json-structure/`)
- Example: 44 files (see `examples/`)

---

### Flight Order Management

Retrieves and cancels existing flight orders. Use after Flight Create Orders to view PNR details or cancel a booking.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Orders, Booking Management

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)
- [OpenAPI](openapi/amadeus-flight-order-management-openapi.yml)
- [NaftikoCapability](capabilities/flight-order-management-booking.yaml)
- JSONSchema: 82 files (see `json-schema/`)
- JSONStructure: 82 files (see `json-structure/`)
- Example: 45 files (see `examples/`)

---

### Flight Availabilities Search

Searches real-time flight availability and inventory between origin and destination for a given date, returning bookable flight segments with classes of service.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Availability, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)
- [OpenAPI](openapi/amadeus-flight-availabilities-search-openapi.yml)
- [NaftikoCapability](capabilities/flight-availabilities-search-availibility.yaml)
- JSONSchema: 38 files (see `json-schema/`)
- JSONStructure: 38 files (see `json-structure/`)
- Example: 24 files (see `examples/`)

---

### SeatMap Display

Returns the seat map for a specific flight, including available, occupied, and reserved seats with characteristics (window, aisle, exit row, extra legroom).

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Seats, Ancillaries

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)
- [OpenAPI](openapi/amadeus-seatmap-display-openapi.yml)
- [NaftikoCapability](capabilities/seatmap-display-display-seatmaps.yaml)
- JSONSchema: 72 files (see `json-schema/`)
- JSONStructure: 72 files (see `json-structure/`)
- Example: 46 files (see `examples/`)

---

### Branded Fares Upsell

Returns branded fares (e.g. Economy Light, Economy Flex, Business Lite) and their attributes for a given flight offer to surface upsell options to travelers.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Fares, Upsell

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)
- [OpenAPI](openapi/amadeus-branded-fares-upsell-openapi.yml)
- [NaftikoCapability](capabilities/branded-fares-upsell-shopping.yaml)
- JSONSchema: 40 files (see `json-schema/`)
- JSONStructure: 40 files (see `json-structure/`)
- Example: 22 files (see `examples/`)

---

### Flight Check-in Links

Returns direct check-in URLs for a given airline (IATA code) and language, deep-linking travelers into the carrier's check-in flow.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Flights, Check-in, Airlines

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links)
- [OpenAPI](openapi/amadeus-flight-checkin-links-openapi.yml)
- [NaftikoCapability](capabilities/flight-checkin-links-checkin-links.yaml)
- JSONSchema: 6 files (see `json-schema/`)
- JSONStructure: 6 files (see `json-structure/`)
- Example: 6 files (see `examples/`)

---

### On Demand Flight Status

Returns the real-time status (scheduled, delayed, departed, landed) and detailed itinerary of a specific flight on a specific date.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Flights, Status, Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)
- [OpenAPI](openapi/amadeus-on-demand-flight-status-openapi.yml)
- [NaftikoCapability](capabilities/on-demand-flight-status-flights.yaml)
- JSONSchema: 18 files (see `json-schema/`)
- JSONStructure: 18 files (see `json-structure/`)
- Example: 18 files (see `examples/`)

---

### Flight Inspiration Search

Suggests cheap destinations from a given origin within a budget and date range, ideal for "where can I go for X dollars?" experiences.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Inspiration, Discovery

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)
- [OpenAPI](openapi/amadeus-flight-inspiration-search-openapi.yml)
- [NaftikoCapability](capabilities/flight-inspiration-search-flight-destinations.yaml)
- JSONSchema: 14 files (see `json-schema/`)
- JSONStructure: 14 files (see `json-structure/`)
- Example: 12 files (see `examples/`)

---

### Flight Cheapest Date Search

Returns the cheapest dates to fly between two cities over a given date range to help travelers find the best fare windows.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Pricing, Discovery

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)
- [OpenAPI](openapi/amadeus-flight-cheapest-date-search-openapi.yml)
- [NaftikoCapability](capabilities/flight-cheapest-date-search-flight-dates.yaml)
- JSONSchema: 14 files (see `json-schema/`)
- JSONStructure: 14 files (see `json-structure/`)
- Example: 12 files (see `examples/`)

---

### Flight Price Analysis

Compares a current flight price to historical prices for the same route and returns a quartile-ranked "price metric" (FIRST, SECOND, THIRD, FOURTH) signalling whether the offer is a good deal.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Pricing, Analytics, Artificial Intelligence

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)
- [OpenAPI](openapi/amadeus-flight-price-analysis-openapi.yml)
- [NaftikoCapability](capabilities/flight-price-analysis-price-metrics.yaml)
- JSONSchema: 4 files (see `json-schema/`)
- JSONStructure: 4 files (see `json-structure/`)
- Example: 4 files (see `examples/`)

---

### Flight Choice Prediction

Predicts the probability that a given flight offer will be chosen by a traveler, helping merchandising and ranking decisions.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Flights, Artificial Intelligence, Prediction, Personalization

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)
- [OpenAPI](openapi/amadeus-flight-choice-prediction-openapi.yml)
- [NaftikoCapability](capabilities/flight-choice-prediction-flight-choice-prediction.yaml)
- JSONSchema: 38 files (see `json-schema/`)
- JSONStructure: 38 files (see `json-structure/`)
- Example: 22 files (see `examples/`)

---

### Flight Delay Prediction

Predicts the probability that a flight will be delayed by 30 minutes, 60 minutes, 120 minutes, or more, based on historical operational data.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Artificial Intelligence, Prediction, Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)
- [OpenAPI](openapi/amadeus-flight-delay-prediction-openapi.yml)
- [NaftikoCapability](capabilities/flight-delay-prediction-flight-delay-prediction.yaml)
- JSONSchema: 7 files (see `json-schema/`)
- JSONStructure: 7 files (see `json-structure/`)
- Example: 6 files (see `examples/`)

---

### Airport On-Time Performance

Returns the on-time performance score for an airport on a specific date, useful for operational and route planning analytics.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Airports, Analytics, Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)
- [OpenAPI](openapi/amadeus-airport-on-time-performance-openapi.yml)
- [NaftikoCapability](capabilities/airport-on-time-performance-airport-ontime-prediction.yaml)
- JSONSchema: 8 files (see `json-schema/`)
- JSONStructure: 8 files (see `json-structure/`)
- Example: 7 files (see `examples/`)

---

### Airport Routes

Returns all destinations served from a given origin airport, with carriers operating each route.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Airports, Routes, Network

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)
- [OpenAPI](openapi/amadeus-airport-routes-openapi.yml)
- [NaftikoCapability](capabilities/airport-routes-direct-destinations.yaml)
- JSONSchema: 5 files (see `json-schema/`)
- JSONStructure: 5 files (see `json-structure/`)
- Example: 5 files (see `examples/`)

---

### Airline Routes

Returns all routes operated by a given airline (IATA code), enabling network and competitive analysis.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Flights, Airlines, Routes, Network

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)
- [OpenAPI](openapi/amadeus-airline-routes-openapi.yml)
- [NaftikoCapability](capabilities/airline-routes-destinations.yaml)
- JSONSchema: 5 files (see `json-schema/`)
- JSONStructure: 5 files (see `json-structure/`)
- Example: 5 files (see `examples/`)

---

### Airport Nearest Relevant

Returns the most relevant nearby airports for a given latitude/longitude, ranked by traffic volume.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Airports, Geolocation, Reference Data

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)
- [OpenAPI](openapi/amadeus-airport-nearest-relevant-openapi.yml)
- [NaftikoCapability](capabilities/airport-nearest-relevant-location.yaml)
- JSONSchema: 11 files (see `json-schema/`)
- JSONStructure: 11 files (see `json-structure/`)
- Example: 11 files (see `examples/`)

---

### Airport and City Search

Searches airports and cities by keyword and returns IATA codes, names, geocoordinates, and country information. Backbone of any travel search UI autocomplete.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Airports, Cities, Reference Data, Autocomplete

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)
- [OpenAPI](openapi/amadeus-airport-city-search-openapi.yml)
- [NaftikoCapability](capabilities/airport-city-search-location.yaml)
- JSONSchema: 12 files (see `json-schema/`)
- JSONStructure: 12 files (see `json-structure/`)
- Example: 12 files (see `examples/`)

---

### City Search

Searches cities matching a keyword, returning city codes, country, geocoordinates, and timezone. Useful for destination and itinerary planning.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Cities, Reference Data, Autocomplete

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)
- [OpenAPI](openapi/amadeus-city-search-openapi.yml)
- [NaftikoCapability](capabilities/city-search-city.yaml)
- JSONSchema: 5 files (see `json-schema/`)
- JSONStructure: 5 files (see `json-structure/`)
- Example: 4 files (see `examples/`)

---

### Airline Code Lookup

Returns the airline name and details for a given IATA or ICAO airline code, used for translating codes into traveler-facing names.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Airlines, Reference Data, Lookup

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)
- [OpenAPI](openapi/amadeus-airline-code-lookup-openapi.yml)
- [NaftikoCapability](capabilities/airline-code-lookup-airlines.yaml)
- JSONSchema: 3 files (see `json-schema/`)
- JSONStructure: 3 files (see `json-structure/`)
- Example: 3 files (see `examples/`)

---

### Flight Most Booked Destinations

Returns the most booked destinations from a given origin city for a given period, surfacing demand patterns for marketing and merchandising.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Market Insights, Flights, Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)
- [OpenAPI](openapi/amadeus-flight-most-booked-destinations-openapi.yml)
- [NaftikoCapability](capabilities/flight-most-booked-destinations-air-traffic.yaml)
- JSONSchema: 8 files (see `json-schema/`)
- JSONStructure: 8 files (see `json-structure/`)
- Example: 8 files (see `examples/`)

---

### Flight Most Traveled Destinations

Returns the most traveled-to destinations from a given origin city for a given period, useful for trend analysis and inspiration UIs.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Market Insights, Flights, Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)
- [OpenAPI](openapi/amadeus-flight-most-traveled-destinations-openapi.yml)
- [NaftikoCapability](capabilities/flight-most-traveled-destinations-air-traffic.yaml)
- JSONSchema: 8 files (see `json-schema/`)
- JSONStructure: 8 files (see `json-structure/`)
- Example: 8 files (see `examples/`)

---

### Flight Busiest Traveling Period

Returns the busiest travel periods (months) for a given city, helping with capacity planning and pricing strategy.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Market Insights, Analytics, Seasonality

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)
- [OpenAPI](openapi/amadeus-flight-busiest-traveling-period-openapi.yml)
- [NaftikoCapability](capabilities/flight-busiest-traveling-period-air-traffic.yaml)
- JSONSchema: 7 files (see `json-schema/`)
- JSONStructure: 7 files (see `json-structure/`)
- Example: 7 files (see `examples/`)

---

### Hotel List

Returns the list of hotels in a given city, geographic area, or by hotel IDs, with property metadata. The foundation lookup for downstream hotel offers and ratings calls.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Hotels, Reference Data, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)
- [OpenAPI](openapi/amadeus-hotel-list-openapi.yml)
- [NaftikoCapability](capabilities/hotel-list-hotels.yaml)
- JSONSchema: 6 files (see `json-schema/`)
- JSONStructure: 6 files (see `json-structure/`)
- Example: 5 files (see `examples/`)

---

### Hotel Search

Returns available hotel offers (rates, room types, board, cancellation policies) for a list of hotel IDs and a stay date range.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)

**Base URL:** `https://test.api.amadeus.com/v3`

#### Tags:

 - Hotels, Search, Offers, Rates

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)
- [OpenAPI](openapi/amadeus-hotel-search-openapi.yml)
- [NaftikoCapability](capabilities/hotel-search-shopping.yaml)
- JSONSchema: 30 files (see `json-schema/`)
- JSONStructure: 30 files (see `json-structure/`)
- Example: 25 files (see `examples/`)

---

### Hotel Booking

Creates a hotel booking (reservation) from a confirmed offer, including guest information, payment, and contact details.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Hotels, Booking, Reservations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)
- [OpenAPI](openapi/amadeus-hotel-booking-openapi.yml)
- [Hotel Booking v1 (Legacy)](openapi/amadeus-hotel-booking-v1-openapi.yml)
- [NaftikoCapability](capabilities/hotel-booking-booking.yaml)
- [NaftikoCapability](capabilities/hotel-booking-v1-booking.yaml)
- JSONSchema: 25 files (see `json-schema/`)
- JSONStructure: 25 files (see `json-structure/`)
- Example: 24 files (see `examples/`)

---

### Hotel Name Autocomplete

Returns up to 20 hotels whose names match a search keyword, with full address, geocode, property type, IATA hotel code, and Amadeus hotel ID — ideal for search-as-you-type hotel pickers.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Hotels, Autocomplete, Reference Data

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)
- [OpenAPI](openapi/amadeus-hotel-name-autocomplete-openapi.yml)
- [NaftikoCapability](capabilities/hotel-name-autocomplete-search.yaml)

---

### Hotel Ratings

Returns sentiment-analyzed ratings for hotels across categories like service, room, location, and food, derived from millions of online reviews.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)

**Base URL:** `https://test.api.amadeus.com/v2`

#### Tags:

 - Hotels, Ratings, Sentiment Analysis, Reviews

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)
- [OpenAPI](openapi/amadeus-hotel-ratings-openapi.yml)
- [NaftikoCapability](capabilities/hotel-ratings-hotel-ratings.yaml)
- JSONSchema: 10 files (see `json-schema/`)
- JSONStructure: 10 files (see `json-structure/`)
- Example: 8 files (see `examples/`)

---

### Points of Interest

Returns points of interest (sights, restaurants, nightlife, shopping) for a given location with categories and rankings.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Destination Content, Points of Interest, Geolocation

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)
- [OpenAPI](openapi/amadeus-points-of-interest-openapi.yml)
- [NaftikoCapability](capabilities/points-of-interest-retrieve.yaml)
- [NaftikoCapability](capabilities/points-of-interest-search.yaml)
- JSONSchema: 8 files (see `json-schema/`)
- JSONStructure: 8 files (see `json-structure/`)
- Example: 8 files (see `examples/`)

---

### Tours and Activities

Returns bookable tours, activities, and experiences for a given location with prices, photos, and provider details.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Destination Content, Tours and Activities, Bookable Experiences

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)
- [OpenAPI](openapi/amadeus-tours-and-activities-openapi.yml)
- [NaftikoCapability](capabilities/tours-and-activities-retrieve.yaml)
- [NaftikoCapability](capabilities/tours-and-activities-search.yaml)
- JSONSchema: 9 files (see `json-schema/`)
- JSONStructure: 9 files (see `json-structure/`)
- Example: 9 files (see `examples/`)

---

### Safe Place

Returns a safety score for a location across categories like LGBTQ+, women, physical harm, and theft, helping travelers make informed destination decisions.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Destination Content, Safety, Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place)
- [OpenAPI](openapi/amadeus-safe-place-openapi.yml)
- [NaftikoCapability](capabilities/safe-place-retrieve.yaml)
- [NaftikoCapability](capabilities/safe-place-search.yaml)
- JSONSchema: 10 files (see `json-schema/`)
- JSONStructure: 10 files (see `json-structure/`)
- Example: 10 files (see `examples/`)

---

### Location Score

Returns a 0-100 score for a location across categories (sights, restaurants, shopping, nightlife, historical, beach/park), powering destination ranking experiences.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Destination Content, Analytics, Ranking

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)
- [OpenAPI](openapi/amadeus-location-score-openapi.yml)
- [NaftikoCapability](capabilities/location-score-category-rated-areas.yaml)
- JSONSchema: 5 files (see `json-schema/`)
- JSONStructure: 5 files (see `json-structure/`)
- Example: 4 files (see `examples/`)

---

### Travel Recommendations

Returns destination recommendations based on a list of seed cities and traveler country, powering "if you liked X you'll like Y" discovery experiences.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Destination Content, Recommendations, Artificial Intelligence

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)
- [OpenAPI](openapi/amadeus-travel-recommendations-openapi.yml)
- [NaftikoCapability](capabilities/travel-recommendations-recommended-locations.yaml)
- JSONSchema: 5 files (see `json-schema/`)
- JSONStructure: 5 files (see `json-structure/`)
- Example: 4 files (see `examples/`)

---

### Trip Purpose Prediction

Predicts whether a trip is for business or leisure based on the itinerary's origin, destination, dates, and search timing, helping route trip-specific merchandising.

**Human URL:** [https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Itinerary Management, Artificial Intelligence, Prediction, Personalization

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)
- [OpenAPI](openapi/amadeus-trip-purpose-prediction-openapi.yml)
- [NaftikoCapability](capabilities/trip-purpose-prediction-trip-purpose-prediction.yaml)
- JSONSchema: 9 files (see `json-schema/`)
- JSONStructure: 9 files (see `json-structure/`)
- Example: 8 files (see `examples/`)

---

### Transfer Search

Searches private and shared transfer options (taxi, limo, shuttle) between two locations with prices, vehicle types, and cancellation policies.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Cars and Transfers, Search, Ground Transport

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)
- [OpenAPI](openapi/amadeus-transfer-search-openapi.yml)
- [NaftikoCapability](capabilities/transfer-search-shopping.yaml)
- JSONSchema: 31 files (see `json-schema/`)
- JSONStructure: 31 files (see `json-structure/`)
- Example: 24 files (see `examples/`)

---

### Transfer Book

Books a transfer based on the offer returned by Transfer Search, capturing passenger details, pickup, and payment.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Cars and Transfers, Booking, Ground Transport

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book)
- [OpenAPI](openapi/amadeus-transfer-book-openapi.yml)
- [NaftikoCapability](capabilities/transfer-book-booking.yaml)
- JSONSchema: 38 files (see `json-schema/`)
- JSONStructure: 38 files (see `json-structure/`)
- Example: 31 files (see `examples/`)

---

### Transfer Management

Cancels an existing transfer booking and manages the transfer order lifecycle.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Cars and Transfers, Booking Management, Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)
- [OpenAPI](openapi/amadeus-transfer-management-openapi.yml)
- [NaftikoCapability](capabilities/transfer-management-booking.yaml)
- JSONSchema: 6 files (see `json-schema/`)
- JSONStructure: 6 files (see `json-structure/`)
- Example: 6 files (see `examples/`)

---

### Authorization

OAuth2 client credentials token endpoint used by every Self-Service API. Exchanges API key + secret for a short-lived bearer access token (~30 minute TTL).

**Human URL:** [https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)

**Base URL:** `https://test.api.amadeus.com/v1`

#### Tags:

 - Authentication, OAuth2, Security

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [OpenAPI](openapi/amadeus-authorization-openapi.yml)
- [NaftikoCapability](capabilities/authorization-oauth2-access-token.yaml)
- JSONSchema: 1 files (see `json-schema/`)
- JSONStructure: 1 files (see `json-structure/`)
- Example: 1 files (see `examples/`)

---

## Common Properties

- [Website](https://amadeus.com)
- [DeveloperPortal](https://developers.amadeus.com)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [Amadeus IT Group](https://github.com/AmadeusITGroup)
- [LinkedIn](https://www.linkedin.com/company/amadeus)
- [Twitter](https://twitter.com/AmadeusITGroup)
- [SignUp](https://developers.amadeus.com/register)
- [My Apps](https://developers.amadeus.com/my-apps)
- [Pricing](https://developers.amadeus.com/pricing)
- [TermsOfService](https://developers.amadeus.com/terms-of-use-api)
- [PrivacyPolicy](https://amadeus.com/en/policies/privacy-policy)
- [Documentation](https://developers.amadeus.com/self-service/apis-docs)
- [GettingStarted](https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335)
- [OAuth 2.0 Client Credentials](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [RateLimits](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/api-rate-limits/)
- [Blog](https://developers.amadeus.com/blog)
- [Support](https://developers.amadeus.com/support)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amadeus)
- [Discord](https://discord.gg/cVrFBqx)
- [Postman](https://www.postman.com/amadeus4dev/amadeus-for-developers-s-public-workspace)
- [TestData](https://github.com/amadeus4dev/data-collection)
- [Node.js SDK](https://www.npmjs.com/package/amadeus)
- [Python SDK](https://pypi.org/project/amadeus/)
- [Java SDK](https://central.sonatype.com/artifact/com.amadeus/amadeus-java)
- [Ruby SDK](https://github.com/amadeus4dev/amadeus-ruby)
- [Self-Contained API Examples](https://github.com/amadeus4dev/amadeus-code-examples)
- [Flight Booking Demo (Python/Django)](https://github.com/amadeus4dev/amadeus-flight-booking-django)
- [Hotel Booking Demo (Python/Django)](https://github.com/amadeus4dev/amadeus-hotel-booking-django)
- [Hotel Search with Tours Demo](https://github.com/amadeus4dev/amadeus-hotel-search-tours-django)
- [Flight Price Analysis Demo](https://github.com/amadeus4dev/amadeus-flight-price-analysis-django)
- [Developer Guides](https://github.com/amadeus4dev/developer-guides)
- [Hackathon Starter](https://github.com/amadeus4dev/hackathon-starter)
- [MCP Server (Community - donghyun-chae)](https://github.com/donghyun-chae/mcp-amadeus)
- [MCP Server (Community - PyPI mcp-amadeus)](https://pypi.org/project/mcp-amadeus/)
- [SpectralRules](rules/amadeus-rules.yml)
- [Vocabulary](vocabulary/amadeus-vocabulary.yml)
- [JSON-LD](json-ld/amadeus-context.jsonld)
- [Plans](plans/amadeus-plans-pricing.yml)
- [API Commons Rate Limits](rate-limits/amadeus-rate-limits.yml)
- [FinOps](finops/amadeus-finops.yml)

## Features

| Name | Description |
|------|-------------|
| 40+ Travel REST APIs | Comprehensive catalog spanning flights, hotels, destination experiences, cars and transfers, market insights, itinerary management, and AI-powered prediction. |
| OAuth 2.0 Client Credentials | Server-to-server authentication with short-lived bearer tokens (~30 min TTL) on a single token endpoint shared by all APIs. |
| Test and Production Environments | Free, cached test environment for development; production environment for live data with pay-as-you-go billing above monthly free tiers. |
| Multi-Language SDKs | Official SDKs for Node.js, Python, Java, and Ruby with built-in token management, retries, and pagination. |
| AI-Powered Predictions | Trip Purpose, Flight Choice, Flight Delay, Price Analysis, Travel Recommendations, and Location Score APIs powered by machine learning over Amadeus travel data. |
| Sentiment-Analyzed Hotel Ratings | Hotel ratings derived from millions of online reviews, broken down by service, room, location, and food. |
| Branded Fares and Ancillaries | Branded Fares Upsell and SeatMap Display surface merchandising opportunities at search and booking time. |
| Market Insights APIs | Most booked destinations, most traveled destinations, and busiest travel periods power demand and trend analytics. |
| Postman Public Workspace | Curated Postman collection with examples for every Self-Service API, maintained by the amadeus4dev team. |
| Open OpenAPI Specifications Repository | Canonical Swagger/OpenAPI specs published on GitHub at amadeus4dev/amadeus-open-api-specification. |

## Use Cases

| Name | Description |
|------|-------------|
| Online Travel Agency (OTA) | Build a full flight + hotel + activities OTA using Flight Offers Search, Hotel Search, Tours and Activities, Transfer Search, and the corresponding booking APIs. |
| Corporate Travel Tool | Combine Flight Offers Search, Trip Purpose Prediction, and Hotel Search to deliver policy-aware corporate booking flows. |
| Travel Inspiration App | Use Flight Inspiration Search, Flight Cheapest Date Search, Travel Recommendations, and Location Score to inspire destination choices. |
| Flight Tracking and Status Apps | Use On-Demand Flight Status, Airport On-Time Performance, and Flight Delay Prediction to build proactive disruption-aware traveler experiences. |
| Hotel Marketing and Merchandising | Combine Hotel Search, Hotel Ratings, and Points of Interest to merchandise hotels with location context and review sentiment. |
| Destination Marketing | Use Tours and Activities, Points of Interest, Safe Place, and Location Score to power destination marketing organization (DMO) experiences. |
| Travel Analytics and BI | Use the Market Insights APIs (Most Booked, Most Traveled, Busiest Period) for demand and trend dashboards. |
| Ground Transportation Booking | Use Transfer Search, Transfer Book, and Transfer Management to add airport-to-hotel ground transport to an itinerary. |
| Hackathon and MVP Travel Apps | Use the free Test environment, official SDKs, and amadeus4dev sample apps to ship a travel MVP in days. |
| AI Travel Agents | Wrap Self-Service APIs in MCP servers (community implementations exist) to give LLM agents flight, hotel, and activity search and booking capabilities. |

## Integrations

| Name | Description |
|------|-------------|
| Postman | Official Amadeus for Developers public workspace with collections for every Self-Service API. |
| Node.js | Official npm package `amadeus` with built-in OAuth handling. |
| Python | Official PyPI package `amadeus` with built-in OAuth handling and pagination. |
| Java | Official Maven Central artifact `com.amadeus:amadeus-java`. |
| Ruby | Official Ruby SDK at github.com/amadeus4dev/amadeus-ruby. |
| Django | Multiple sample Django apps demonstrating flight booking, hotel booking, and tours integration. |
| Model Context Protocol (MCP) | Several community MCP servers expose Amadeus Self-Service APIs as tools for Claude and other LLM agents. |
| Bottleneck | Community example using the Bottleneck rate-limiter to manage Amadeus TPS quotas in Node.js apps. |

## Solutions

| Name | Description |
|------|-------------|
| Amadeus for Developers Self-Service | Self-service catalog of 40+ REST APIs with free Test environment and pay-as-you-go Production environment. NOTE: scheduled for decommissioning 17 July 2026. |
| Amadeus Enterprise | Enterprise developer portal and SLA-backed access to the full Amadeus distribution, ticketing, and operations APIs, including NDC content and Margins/Discounts not available in Self-Service. |
| Amadeus Travel Platform | The underlying global distribution and travel technology platform powering airlines, hotels, ground transport, and travel agencies worldwide. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI (40 files)

- [Airline-Code-Lookup](openapi/amadeus-airline-code-lookup-openapi.yml)
- [Airline-Routes](openapi/amadeus-airline-routes-openapi.yml)
- [Airport-City-Search](openapi/amadeus-airport-city-search-openapi.yml)
- [Airport-Nearest-Relevant](openapi/amadeus-airport-nearest-relevant-openapi.yml)
- [Airport-On-Time-Performance](openapi/amadeus-airport-on-time-performance-openapi.yml)
- [Airport-Routes](openapi/amadeus-airport-routes-openapi.yml)
- [Authorization](openapi/amadeus-authorization-openapi.yml)
- [Branded-Fares-Upsell](openapi/amadeus-branded-fares-upsell-openapi.yml)
- [City-Search](openapi/amadeus-city-search-openapi.yml)
- [Flight-Availabilities-Search](openapi/amadeus-flight-availabilities-search-openapi.yml)
- [Flight-Busiest-Traveling-Period](openapi/amadeus-flight-busiest-traveling-period-openapi.yml)
- [Flight-Cheapest-Date-Search](openapi/amadeus-flight-cheapest-date-search-openapi.yml)
- [Flight-Checkin-Links](openapi/amadeus-flight-checkin-links-openapi.yml)
- [Flight-Choice-Prediction](openapi/amadeus-flight-choice-prediction-openapi.yml)
- [Flight-Create-Orders](openapi/amadeus-flight-create-orders-openapi.yml)
- [Flight-Delay-Prediction](openapi/amadeus-flight-delay-prediction-openapi.yml)
- [Flight-Inspiration-Search](openapi/amadeus-flight-inspiration-search-openapi.yml)
- [Flight-Most-Booked-Destinations](openapi/amadeus-flight-most-booked-destinations-openapi.yml)
- [Flight-Most-Traveled-Destinations](openapi/amadeus-flight-most-traveled-destinations-openapi.yml)
- [Flight-Offers-Price](openapi/amadeus-flight-offers-price-openapi.yml)
- [Flight-Offers-Search](openapi/amadeus-flight-offers-search-openapi.yml)
- [Flight-Order-Management](openapi/amadeus-flight-order-management-openapi.yml)
- [Flight-Price-Analysis](openapi/amadeus-flight-price-analysis-openapi.yml)
- [Hotel-Booking](openapi/amadeus-hotel-booking-openapi.yml)
- [Hotel-Booking-V1](openapi/amadeus-hotel-booking-v1-openapi.yml)
- [Hotel-List](openapi/amadeus-hotel-list-openapi.yml)
- [Hotel-Name-Autocomplete](openapi/amadeus-hotel-name-autocomplete-openapi.yml)
- [Hotel-Ratings](openapi/amadeus-hotel-ratings-openapi.yml)
- [Hotel-Search](openapi/amadeus-hotel-search-openapi.yml)
- [Location-Score](openapi/amadeus-location-score-openapi.yml)
- [On-Demand-Flight-Status](openapi/amadeus-on-demand-flight-status-openapi.yml)
- [Points-Of-Interest](openapi/amadeus-points-of-interest-openapi.yml)
- [Safe-Place](openapi/amadeus-safe-place-openapi.yml)
- [Seatmap-Display](openapi/amadeus-seatmap-display-openapi.yml)
- [Tours-And-Activities](openapi/amadeus-tours-and-activities-openapi.yml)
- [Transfer-Book](openapi/amadeus-transfer-book-openapi.yml)
- [Transfer-Management](openapi/amadeus-transfer-management-openapi.yml)
- [Transfer-Search](openapi/amadeus-transfer-search-openapi.yml)
- [Travel-Recommendations](openapi/amadeus-travel-recommendations-openapi.yml)
- [Trip-Purpose-Prediction](openapi/amadeus-trip-purpose-prediction-openapi.yml)

### JSON Schema (797 files)

See [json-schema/](json-schema/) — extracted from each OpenAPI `components/schemas`.

### JSON Structure (797 files)

See [json-structure/](json-structure/) — simplified structure documents per schema.

### JSON-LD

- [Context](json-ld/amadeus-context.jsonld)

### Example Payloads (565 files)

See [examples/](examples/) — generated example payloads per schema.

## Capabilities

Naftiko capabilities — one self-contained file per OpenAPI tag, each exposing a REST adapter and an MCP adapter.

| Capability | Operations | MCP Tools |
|------------|-----------:|----------:|
| [airline-code-lookup-airlines.yaml](capabilities/airline-code-lookup-airlines.yaml) | 1 | 1 |
| [airline-routes-destinations.yaml](capabilities/airline-routes-destinations.yaml) | 1 | 1 |
| [airport-city-search-location.yaml](capabilities/airport-city-search-location.yaml) | 2 | 2 |
| [airport-nearest-relevant-location.yaml](capabilities/airport-nearest-relevant-location.yaml) | 1 | 1 |
| [airport-on-time-performance-airport-ontime-prediction.yaml](capabilities/airport-on-time-performance-airport-ontime-prediction.yaml) | 1 | 1 |
| [airport-routes-direct-destinations.yaml](capabilities/airport-routes-direct-destinations.yaml) | 1 | 1 |
| [authorization-oauth2-access-token.yaml](capabilities/authorization-oauth2-access-token.yaml) | 2 | 2 |
| [branded-fares-upsell-shopping.yaml](capabilities/branded-fares-upsell-shopping.yaml) | 1 | 1 |
| [city-search-city.yaml](capabilities/city-search-city.yaml) | 1 | 1 |
| [flight-availabilities-search-availibility.yaml](capabilities/flight-availabilities-search-availibility.yaml) | 1 | 1 |
| [flight-busiest-traveling-period-air-traffic.yaml](capabilities/flight-busiest-traveling-period-air-traffic.yaml) | 1 | 1 |
| [flight-cheapest-date-search-flight-dates.yaml](capabilities/flight-cheapest-date-search-flight-dates.yaml) | 1 | 1 |
| [flight-checkin-links-checkin-links.yaml](capabilities/flight-checkin-links-checkin-links.yaml) | 1 | 1 |
| [flight-choice-prediction-flight-choice-prediction.yaml](capabilities/flight-choice-prediction-flight-choice-prediction.yaml) | 1 | 1 |
| [flight-create-orders-booking.yaml](capabilities/flight-create-orders-booking.yaml) | 1 | 1 |
| [flight-delay-prediction-flight-delay-prediction.yaml](capabilities/flight-delay-prediction-flight-delay-prediction.yaml) | 1 | 1 |
| [flight-inspiration-search-flight-destinations.yaml](capabilities/flight-inspiration-search-flight-destinations.yaml) | 1 | 1 |
| [flight-most-booked-destinations-air-traffic.yaml](capabilities/flight-most-booked-destinations-air-traffic.yaml) | 1 | 1 |
| [flight-most-traveled-destinations-air-traffic.yaml](capabilities/flight-most-traveled-destinations-air-traffic.yaml) | 1 | 1 |
| [flight-offers-price-shopping.yaml](capabilities/flight-offers-price-shopping.yaml) | 1 | 1 |
| [flight-offers-search-shopping.yaml](capabilities/flight-offers-search-shopping.yaml) | 2 | 2 |
| [flight-order-management-booking.yaml](capabilities/flight-order-management-booking.yaml) | 2 | 2 |
| [flight-price-analysis-price-metrics.yaml](capabilities/flight-price-analysis-price-metrics.yaml) | 1 | 1 |
| [hotel-booking-booking.yaml](capabilities/hotel-booking-booking.yaml) | 1 | 1 |
| [hotel-booking-v1-booking.yaml](capabilities/hotel-booking-v1-booking.yaml) | 1 | 1 |
| [hotel-list-hotels.yaml](capabilities/hotel-list-hotels.yaml) | 3 | 3 |
| [hotel-name-autocomplete-search.yaml](capabilities/hotel-name-autocomplete-search.yaml) | 1 | 1 |
| [hotel-ratings-hotel-ratings.yaml](capabilities/hotel-ratings-hotel-ratings.yaml) | 1 | 1 |
| [hotel-search-shopping.yaml](capabilities/hotel-search-shopping.yaml) | 2 | 2 |
| [location-score-category-rated-areas.yaml](capabilities/location-score-category-rated-areas.yaml) | 1 | 1 |
| [on-demand-flight-status-flights.yaml](capabilities/on-demand-flight-status-flights.yaml) | 1 | 1 |
| [points-of-interest-retrieve.yaml](capabilities/points-of-interest-retrieve.yaml) | 1 | 1 |
| [points-of-interest-search.yaml](capabilities/points-of-interest-search.yaml) | 2 | 2 |
| [safe-place-retrieve.yaml](capabilities/safe-place-retrieve.yaml) | 1 | 1 |
| [safe-place-search.yaml](capabilities/safe-place-search.yaml) | 2 | 2 |
| [seatmap-display-display-seatmaps.yaml](capabilities/seatmap-display-display-seatmaps.yaml) | 2 | 2 |
| [tours-and-activities-retrieve.yaml](capabilities/tours-and-activities-retrieve.yaml) | 1 | 1 |
| [tours-and-activities-search.yaml](capabilities/tours-and-activities-search.yaml) | 2 | 2 |
| [transfer-book-booking.yaml](capabilities/transfer-book-booking.yaml) | 1 | 1 |
| [transfer-management-booking.yaml](capabilities/transfer-management-booking.yaml) | 1 | 1 |
| [transfer-search-shopping.yaml](capabilities/transfer-search-shopping.yaml) | 1 | 1 |
| [travel-recommendations-recommended-locations.yaml](capabilities/travel-recommendations-recommended-locations.yaml) | 1 | 1 |
| [trip-purpose-prediction-trip-purpose-prediction.yaml](capabilities/trip-purpose-prediction-trip-purpose-prediction.yaml) | 1 | 1 |

## Vocabulary

- [Vocabulary](vocabulary/amadeus-vocabulary.yml)

## Rules

- [Rules](rules/amadeus-rules.yml) — 32 rules enforcing Amadeus API conventions

## Plans

- [Plans-Pricing](plans/amadeus-plans-pricing.yml)

## Rate Limits

- [Rate-Limits](rate-limits/amadeus-rate-limits.yml)

## FinOps

- [Finops](finops/amadeus-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
