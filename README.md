# Amadeus (amadeus)
Amadeus for Developers provides a comprehensive set of self-service APIs for the travel industry, covering flights, hotels, destination experiences, ground transportation, market insights, and itinerary management. The platform serves developers and travel companies building search, booking, and analytics applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Airlines, Aviation, Booking, Destinations, Flights, Hospitality, Hotels, Market Insights, Tourism, Transfers, Travel

## Timestamps

- **Created:** 2024-06-07
- **Modified:** 2026-04-19

## APIs

### Amadeus Flight Offers Search API
The Amadeus Flight Offers Search API searches over 500 airlines to find the cheapest flights for a given itinerary. It lets you search flights between two cities, perform multi-city searches, and access one-way combinable fares to offer the cheapest options possible.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)

#### Tags:

 - Airlines, Booking, Flights, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search/api-reference)
- [OpenAPI](openapi/flight-offers-search-openapi.yaml)
- [JSONSchema](json-schema/flight-offers-search-additionalservicetype-schema.json)
- [JSONSchema](json-schema/flight-offers-search-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-offers-search-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-offers-search-allotmentdetails-schema.json)
- [JSONSchema](json-schema/flight-offers-search-baggageallowance-schema.json)
- [JSONStructure](json-structure/flight-offers-search-additionalservicetype-structure.json)
- [JSONStructure](json-structure/flight-offers-search-aircraftentry-structure.json)
- [JSONStructure](json-structure/flight-offers-search-aircraftequipment-structure.json)
- [JSONLD](json-ld/amadeus-flight-offers-search-context.jsonld)

### Amadeus Flight Offers Price API
The Amadeus Flight Offers Price API confirms the availability and final price of flights, including taxes and fees. It is used after a flight search to verify that the offer is still available and to get the final price before proceeding to booking.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)

#### Tags:

 - Fares, Flights, Pricing

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price/api-reference)
- [OpenAPI](openapi/flight-offers-price-openapi.yaml)
- [JSONSchema](json-schema/flight-offers-price-additionalservicetype-schema.json)
- [JSONSchema](json-schema/flight-offers-price-address-schema.json)
- [JSONSchema](json-schema/flight-offers-price-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-offers-price-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-offers-price-allotmentdetails-schema.json)
- [JSONStructure](json-structure/flight-offers-price-additionalservicetype-structure.json)
- [JSONStructure](json-structure/flight-offers-price-address-structure.json)
- [JSONStructure](json-structure/flight-offers-price-aircraftentry-structure.json)
- [JSONLD](json-ld/amadeus-flight-offers-price-context.jsonld)

### Amadeus Flight Create Orders API
The Amadeus Flight Create Orders API completes the air booking flow by creating a flight order. It provides a unique booking ID and reservation details once the reservation is completed, allowing travelers to finalize their flight bookings.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)

#### Tags:

 - Booking, Flights, Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders/api-reference)
- [OpenAPI](openapi/flight-create-orders-openapi.yaml)
- [JSONSchema](json-schema/flight-create-orders-additionalservicetype-schema.json)
- [JSONSchema](json-schema/flight-create-orders-address-schema.json)
- [JSONSchema](json-schema/flight-create-orders-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-create-orders-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-create-orders-airlineremark-schema.json)
- [JSONStructure](json-structure/flight-create-orders-additionalservicetype-structure.json)
- [JSONStructure](json-structure/flight-create-orders-address-structure.json)
- [JSONStructure](json-structure/flight-create-orders-aircraftentry-structure.json)
- [JSONLD](json-ld/amadeus-flight-create-orders-context.jsonld)

### Amadeus Flight Order Management API
The Amadeus Flight Order Management API allows you to check reservation status, view post-booking modifications, and enable cancellations for existing flight orders. It provides full lifecycle management of flight bookings after they have been created.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)

#### Tags:

 - Flights, Management, Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management/api-reference)
- [OpenAPI](openapi/flight-order-management-openapi.yaml)
- [JSONSchema](json-schema/flight-order-management-additionalservicetype-schema.json)
- [JSONSchema](json-schema/flight-order-management-address-schema.json)
- [JSONSchema](json-schema/flight-order-management-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-order-management-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-order-management-airlineremark-schema.json)
- [JSONStructure](json-structure/flight-order-management-additionalservicetype-structure.json)
- [JSONStructure](json-structure/flight-order-management-address-structure.json)
- [JSONStructure](json-structure/flight-order-management-aircraftentry-structure.json)
- [JSONLD](json-ld/amadeus-flight-order-management-context.jsonld)

### Amadeus Seatmap Display API
The Amadeus Seatmap Display API shows the airplane cabin plan from a flight offer so travelers can choose their seat during the booking process. It provides seat availability, pricing, and cabin layout information for supported flights.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)

#### Tags:

 - Cabin, Flights, Seats

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display/api-reference)
- [OpenAPI](openapi/seatmap-display-openapi.yaml)
- [JSONSchema](json-schema/seatmap-display-additionalservicetype-schema.json)
- [JSONSchema](json-schema/seatmap-display-address-schema.json)
- [JSONSchema](json-schema/seatmap-display-aircraftcabinamenities-beverage-schema.json)
- [JSONSchema](json-schema/seatmap-display-aircraftcabinamenities-entertainment-schema.json)
- [JSONSchema](json-schema/seatmap-display-aircraftcabinamenities-food-schema.json)
- [JSONStructure](json-structure/seatmap-display-additionalservicetype-structure.json)
- [JSONStructure](json-structure/seatmap-display-address-structure.json)
- [JSONStructure](json-structure/seatmap-display-aircraftcabinamenities-beverage-structure.json)
- [JSONLD](json-ld/amadeus-seatmap-display-context.jsonld)

### Amadeus Branded Fares Upsell API
The Amadeus Branded Fares Upsell API provides the branded fares available for a given flight, along with pricing and a fare description. It enables travel applications to offer travelers upgrade options and premium fare bundles with additional services.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)

#### Tags:

 - Fares, Flights, Upsell

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell/api-reference)
- [OpenAPI](openapi/branded-fares-upsell-openapi.yaml)
- [JSONSchema](json-schema/branded-fares-upsell-additionalservicetype-schema.json)
- [JSONSchema](json-schema/branded-fares-upsell-aircraftentry-schema.json)
- [JSONSchema](json-schema/branded-fares-upsell-aircraftequipment-schema.json)
- [JSONSchema](json-schema/branded-fares-upsell-allotmentdetails-schema.json)
- [JSONSchema](json-schema/branded-fares-upsell-baggageallowance-schema.json)
- [JSONStructure](json-structure/branded-fares-upsell-additionalservicetype-structure.json)
- [JSONStructure](json-structure/branded-fares-upsell-aircraftentry-structure.json)
- [JSONStructure](json-structure/branded-fares-upsell-aircraftequipment-structure.json)
- [JSONLD](json-ld/amadeus-branded-fares-upsell-context.jsonld)

### Amadeus Flight Price Analysis API
The Amadeus Flight Price Analysis API uses AI and historical fare data to determine whether a flight price is a good deal. It compares current flight prices against historical fares to help travelers decide whether to book now or wait for a better price.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)

#### Tags:

 - Analytics, Flights, Pricing

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis/api-reference)
- [OpenAPI](openapi/flight-price-analysis-openapi.yaml)
- [JSONSchema](json-schema/flight-price-analysis-error-400-schema.json)
- [JSONSchema](json-schema/flight-price-analysis-error-500-schema.json)
- [JSONSchema](json-schema/flight-price-analysis-itinerary-price-metric-schema.json)
- [JSONSchema](json-schema/flight-price-analysis-warning-schema.json)
- [JSONStructure](json-structure/flight-price-analysis-error-400-structure.json)
- [JSONStructure](json-structure/flight-price-analysis-error-500-structure.json)
- [JSONStructure](json-structure/flight-price-analysis-itinerary-price-metric-structure.json)
- [JSONLD](json-ld/amadeus-flight-price-analysis-context.jsonld)

### Amadeus Flight Choice Prediction API
The Amadeus Flight Choice Prediction API uses machine learning to identify which flight offers users are most likely to book from a list of search results. It helps travel applications sort and highlight the most relevant flight options for each traveler.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)

#### Tags:

 - Flights, Machine Learning, Prediction

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction/api-reference)
- [OpenAPI](openapi/flight-choice-prediction-openapi.yaml)
- [JSONSchema](json-schema/flight-choice-prediction-additionalservicetype-schema.json)
- [JSONSchema](json-schema/flight-choice-prediction-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-choice-prediction-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-choice-prediction-baggageallowance-schema.json)
- [JSONSchema](json-schema/flight-choice-prediction-carrierentry-schema.json)
- [JSONStructure](json-structure/flight-choice-prediction-additionalservicetype-structure.json)
- [JSONStructure](json-structure/flight-choice-prediction-aircraftentry-structure.json)
- [JSONStructure](json-structure/flight-choice-prediction-aircraftequipment-structure.json)
- [JSONLD](json-ld/amadeus-flight-choice-prediction-context.jsonld)

### Amadeus Flight Inspiration Search API
The Amadeus Flight Inspiration Search API returns a list of destinations from a given city ordered by price, helping travelers discover where they can fly for the best deals. It is designed for flexible travelers who are open to exploring new destinations based on affordability.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)

#### Tags:

 - Destinations, Flights, Inspiration, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search/api-reference)
- [OpenAPI](openapi/flight-inspiration-search-openapi.yaml)
- [JSONSchema](json-schema/flight-inspiration-search-currencydictionary-schema.json)
- [JSONSchema](json-schema/flight-inspiration-search-defaults-schema.json)
- [JSONSchema](json-schema/flight-inspiration-search-dictionaries-schema.json)
- [JSONSchema](json-schema/flight-inspiration-search-error-400-schema.json)
- [JSONSchema](json-schema/flight-inspiration-search-error-404-schema.json)
- [JSONStructure](json-structure/flight-inspiration-search-currencydictionary-structure.json)
- [JSONStructure](json-structure/flight-inspiration-search-defaults-structure.json)
- [JSONStructure](json-structure/flight-inspiration-search-dictionaries-structure.json)
- [JSONLD](json-ld/amadeus-flight-inspiration-search-context.jsonld)

### Amadeus Flight Cheapest Date Search API
The Amadeus Flight Cheapest Date Search API provides a list of flight options with dates and prices for a given route. It helps travelers find the cheapest dates to fly between two cities, enabling flexible date planning for the best fares.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)

#### Tags:

 - Dates, Flights, Pricing, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search/api-reference)
- [OpenAPI](openapi/flight-cheapest-date-search-openapi.yaml)
- [JSONSchema](json-schema/flight-cheapest-date-search-currencydictionary-schema.json)
- [JSONSchema](json-schema/flight-cheapest-date-search-defaults-schema.json)
- [JSONSchema](json-schema/flight-cheapest-date-search-dictionaries-schema.json)
- [JSONSchema](json-schema/flight-cheapest-date-search-error-400-schema.json)
- [JSONSchema](json-schema/flight-cheapest-date-search-error-404-schema.json)
- [JSONStructure](json-structure/flight-cheapest-date-search-currencydictionary-structure.json)
- [JSONStructure](json-structure/flight-cheapest-date-search-defaults-structure.json)
- [JSONStructure](json-structure/flight-cheapest-date-search-dictionaries-structure.json)
- [JSONLD](json-ld/amadeus-flight-cheapest-date-search-context.jsonld)

### Amadeus Flight Availabilities Search API
The Amadeus Flight Availabilities Search API provides a list of flights with seats for sale on a given itinerary. It checks real-time seat availability across airlines, helping travel agents and applications verify that flights have available inventory before proceeding.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)

#### Tags:

 - Availability, Flights, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search/api-reference)
- [OpenAPI](openapi/flight-availibilities-search-openapi.yaml)
- [JSONSchema](json-schema/flight-availibilities-search-aircraftentry-schema.json)
- [JSONSchema](json-schema/flight-availibilities-search-aircraftequipment-schema.json)
- [JSONSchema](json-schema/flight-availibilities-search-allotmentdetails-schema.json)
- [JSONSchema](json-schema/flight-availibilities-search-availabilityclass-schema.json)
- [JSONSchema](json-schema/flight-availibilities-search-cabinrestriction-schema.json)
- [JSONStructure](json-structure/flight-availibilities-search-aircraftentry-structure.json)
- [JSONStructure](json-structure/flight-availibilities-search-aircraftequipment-structure.json)
- [JSONStructure](json-structure/flight-availibilities-search-allotmentdetails-structure.json)
- [JSONLD](json-ld/amadeus-flight-availibilities-search-context.jsonld)

### Amadeus Travel Recommendations API
The Amadeus Travel Recommendations API uses AI to suggest destinations based on traveler profiles and past search and booking history. It helps travel applications provide personalized destination recommendations to improve user engagement and conversion.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/travel-recommendations](https://developers.amadeus.com/self-service/category/flights/api-doc/travel-recommendations)

#### Tags:

 - Destinations, Flights, Machine Learning, Recommendations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/travel-recommendations)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/travel-recommendations/api-reference)
- [OpenAPI](openapi/travel-recommendations-openapi.yaml)
- [JSONSchema](json-schema/travel-recommendations-errors-schema.json)
- [JSONSchema](json-schema/travel-recommendations-meta-schema.json)
- [JSONSchema](json-schema/travel-recommendations-recommendedlocation-schema.json)
- [JSONSchema](json-schema/travel-recommendations-response-error-schema.json)
- [JSONSchema](json-schema/travel-recommendations-response-recommendedlocation-schema.json)
- [JSONStructure](json-structure/travel-recommendations-errors-structure.json)
- [JSONStructure](json-structure/travel-recommendations-meta-structure.json)
- [JSONStructure](json-structure/travel-recommendations-recommendedlocation-structure.json)
- [JSONLD](json-ld/amadeus-travel-recommendations-context.jsonld)

### Amadeus On-Demand Flight Status API
The Amadeus On-Demand Flight Status API delivers real-time flight schedule data including delays, cancellations, gate changes, and terminal information. It helps travel applications keep travelers informed about the current status of their flights.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)

#### Tags:

 - Flights, Real-Time, Status

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status/api-reference)
- [OpenAPI](openapi/on-demand-flight-status-openapi.yaml)
- [JSONSchema](json-schema/on-demand-flight-status-aircraftequipment-schema.json)
- [JSONSchema](json-schema/on-demand-flight-status-arrival-schema.json)
- [JSONSchema](json-schema/on-demand-flight-status-collection-meta-schema.json)
- [JSONSchema](json-schema/on-demand-flight-status-datedflight-schema.json)
- [JSONSchema](json-schema/on-demand-flight-status-delay-schema.json)
- [JSONStructure](json-structure/on-demand-flight-status-aircraftequipment-structure.json)
- [JSONStructure](json-structure/on-demand-flight-status-arrival-structure.json)
- [JSONStructure](json-structure/on-demand-flight-status-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-on-demand-flight-status-context.jsonld)

### Amadeus Flight Delay Prediction API
The Amadeus Flight Delay Prediction API provides delay probabilities for four possible delay lengths using machine learning. It takes carrier, airport, and aircraft information as input to estimate the likelihood that a specific flight will be delayed.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)

#### Tags:

 - Delays, Flights, Machine Learning, Prediction

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction/api-reference)
- [OpenAPI](openapi/flight-delay-prediction-openapi.yaml)
- [JSONSchema](json-schema/flight-delay-prediction-collection-meta-link-schema.json)
- [JSONSchema](json-schema/flight-delay-prediction-delay-prediction-schema.json)
- [JSONSchema](json-schema/flight-delay-prediction-error-400-schema.json)
- [JSONSchema](json-schema/flight-delay-prediction-error-500-schema.json)
- [JSONSchema](json-schema/flight-delay-prediction-issue-schema.json)
- [JSONStructure](json-structure/flight-delay-prediction-collection-meta-link-structure.json)
- [JSONStructure](json-structure/flight-delay-prediction-delay-prediction-structure.json)
- [JSONStructure](json-structure/flight-delay-prediction-error-400-structure.json)
- [JSONLD](json-ld/amadeus-flight-delay-prediction-context.jsonld)

### Amadeus Airport and City Search API
The Amadeus Airport and City Search API finds airports and cities that match a specific word or string of letters. It powers autocomplete functionality in travel search interfaces, helping users quickly find their departure and arrival locations.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)

#### Tags:

 - Airports, Autocomplete, Cities, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search/api-reference)
- [OpenAPI](openapi/airport-city-search-openapi.yaml)
- [JSONSchema](json-schema/airport-city-search-address-schema.json)
- [JSONSchema](json-schema/airport-city-search-analytics-schema.json)
- [JSONSchema](json-schema/airport-city-search-collection-meta-schema.json)
- [JSONSchema](json-schema/airport-city-search-distance-schema.json)
- [JSONSchema](json-schema/airport-city-search-error-400-schema.json)
- [JSONStructure](json-structure/airport-city-search-address-structure.json)
- [JSONStructure](json-structure/airport-city-search-analytics-structure.json)
- [JSONStructure](json-structure/airport-city-search-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-airport-city-search-context.jsonld)

### Amadeus Airport Nearest Relevant API
The Amadeus Airport Nearest Relevant API provides a list of commercial airports within a 500km radius of a given location. It helps travelers find the most convenient airports for their journey based on geographic coordinates.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)

#### Tags:

 - Airports, Location, Proximity

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant/api-reference)
- [OpenAPI](openapi/airport-nearest-relevant-openapi.yaml)
- [JSONSchema](json-schema/airport-nearest-relevant-address-schema.json)
- [JSONSchema](json-schema/airport-nearest-relevant-analytics-schema.json)
- [JSONSchema](json-schema/airport-nearest-relevant-collection-meta-schema.json)
- [JSONSchema](json-schema/airport-nearest-relevant-distance-schema.json)
- [JSONSchema](json-schema/airport-nearest-relevant-error-400-schema.json)
- [JSONStructure](json-structure/airport-nearest-relevant-address-structure.json)
- [JSONStructure](json-structure/airport-nearest-relevant-analytics-structure.json)
- [JSONStructure](json-structure/airport-nearest-relevant-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-airport-nearest-relevant-context.jsonld)

### Amadeus Airport Routes API
The Amadeus Airport Routes API finds all destinations served by a given airport. It allows travel applications to show travelers the complete network of routes available from any airport, helping with trip planning and destination discovery.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)

#### Tags:

 - Airports, Destinations, Routes

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes/api-reference)
- [OpenAPI](openapi/airport-routes-openapi.yaml)
- [JSONSchema](json-schema/airport-routes-errors-schema.json)
- [JSONSchema](json-schema/airport-routes-locations-schema.json)
- [JSONSchema](json-schema/airport-routes-meta-schema.json)
- [JSONSchema](json-schema/airport-routes-response-airportroutes-schema.json)
- [JSONSchema](json-schema/airport-routes-response-error-schema.json)
- [JSONStructure](json-structure/airport-routes-errors-structure.json)
- [JSONStructure](json-structure/airport-routes-locations-structure.json)
- [JSONStructure](json-structure/airport-routes-meta-structure.json)
- [JSONLD](json-ld/amadeus-airport-routes-context.jsonld)

### Amadeus Airport On-Time Performance API
The Amadeus Airport On-Time Performance API predicts overall airport performance based on historical flight delay data. It estimates the probability of flights being delayed at a specific airport, helping travelers plan around potential disruptions.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)

#### Tags:

 - Airports, Analytics, Performance

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance/api-reference)
- [OpenAPI](openapi/airport-on-time-performance-openapi.yaml)
- [JSONSchema](json-schema/airport-on-time-performance-error-400-schema.json)
- [JSONSchema](json-schema/airport-on-time-performance-error-500-schema.json)
- [JSONSchema](json-schema/airport-on-time-performance-issue-schema.json)
- [JSONSchema](json-schema/airport-on-time-performance-links-schema.json)
- [JSONSchema](json-schema/airport-on-time-performance-meta-schema.json)
- [JSONStructure](json-structure/airport-on-time-performance-error-400-structure.json)
- [JSONStructure](json-structure/airport-on-time-performance-error-500-structure.json)
- [JSONStructure](json-structure/airport-on-time-performance-issue-structure.json)
- [JSONLD](json-ld/amadeus-airport-on-time-performance-context.jsonld)

### Amadeus Flight Check-in Links API
The Amadeus Flight Check-in Links API simplifies the check-in process by providing direct links to airline online check-in pages. It returns the appropriate check-in URL for a given airline, making it easy for travel applications to redirect travelers to check in for their flights.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-check-in-links](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-check-in-links)

#### Tags:

 - Airlines, Check-In, Flights

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-check-in-links)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-check-in-links/api-reference)
- [OpenAPI](openapi/flight-check-in-links-openapi.yaml)
- [JSONSchema](json-schema/flight-check-in-links-checkinlink-schema.json)
- [JSONSchema](json-schema/flight-check-in-links-collection-meta-schema.json)
- [JSONSchema](json-schema/flight-check-in-links-error-400-schema.json)
- [JSONSchema](json-schema/flight-check-in-links-error-500-schema.json)
- [JSONSchema](json-schema/flight-check-in-links-issue-schema.json)
- [JSONStructure](json-structure/flight-check-in-links-checkinlink-structure.json)
- [JSONStructure](json-structure/flight-check-in-links-collection-meta-structure.json)
- [JSONStructure](json-structure/flight-check-in-links-error-400-structure.json)
- [JSONLD](json-ld/amadeus-flight-check-in-links-context.jsonld)

### Amadeus Airline Code Lookup API
The Amadeus Airline Code Lookup API finds the name of an airline by its IATA or ICAO airline codes. It helps travel applications display human-readable airline names alongside flight data that uses industry-standard airline code identifiers.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)

#### Tags:

 - Airlines, Codes, IATA, ICAO

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup/api-reference)
- [OpenAPI](openapi/airline-code-lookup-openapi.yaml)
- [JSONSchema](json-schema/airline-code-lookup-airline-schema.json)
- [JSONSchema](json-schema/airline-code-lookup-airlinecollection-schema.json)
- [JSONSchema](json-schema/airline-code-lookup-collectionmeta-schema.json)
- [JSONSchema](json-schema/airline-code-lookup-errorresponse-schema.json)
- [JSONSchema](json-schema/airline-code-lookup-issue-schema.json)
- [JSONStructure](json-structure/airline-code-lookup-airline-structure.json)
- [JSONStructure](json-structure/airline-code-lookup-airlinecollection-structure.json)
- [JSONStructure](json-structure/airline-code-lookup-collectionmeta-structure.json)
- [JSONLD](json-ld/amadeus-airline-code-lookup-context.jsonld)

### Amadeus Airline Routes API
The Amadeus Airline Routes API finds all destinations served by a given airline. It enables travel applications to display the complete route network of any airline, useful for trip planning and understanding airline coverage in specific regions.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)

#### Tags:

 - Airlines, Destinations, Routes

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes/api-reference)
- [OpenAPI](openapi/airline-routes-openapi.yaml)
- [JSONSchema](json-schema/airline-routes-errors-schema.json)
- [JSONSchema](json-schema/airline-routes-locations-schema.json)
- [JSONSchema](json-schema/airline-routes-meta-schema.json)
- [JSONSchema](json-schema/airline-routes-response-airlineroutes-schema.json)
- [JSONSchema](json-schema/airline-routes-response-error-schema.json)
- [JSONStructure](json-structure/airline-routes-errors-structure.json)
- [JSONStructure](json-structure/airline-routes-locations-structure.json)
- [JSONStructure](json-structure/airline-routes-meta-structure.json)
- [JSONLD](json-ld/amadeus-airline-routes-context.jsonld)

### Amadeus Hotel List API
The Amadeus Hotel List API returns the name, address, geoCode, and time zone for each hotel bookable in Amadeus. It supports searching by city, geographic coordinates, or unique Amadeus hotel ID, providing the foundation for hotel search workflows.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)

#### Tags:

 - Accommodation, Hotels, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list/api-reference)
- [OpenAPI](openapi/hotel-list-openapi.yaml)
- [JSONSchema](json-schema/hotel-list-error-400-schema.json)
- [JSONSchema](json-schema/hotel-list-error-404-schema.json)
- [JSONSchema](json-schema/hotel-list-error-500-schema.json)
- [JSONSchema](json-schema/hotel-list-hotel-schema.json)
- [JSONSchema](json-schema/hotel-list-hotelsearchresponse-schema.json)
- [JSONStructure](json-structure/hotel-list-error-400-structure.json)
- [JSONStructure](json-structure/hotel-list-error-404-structure.json)
- [JSONStructure](json-structure/hotel-list-error-500-structure.json)
- [JSONLD](json-ld/amadeus-hotel-list-context.jsonld)

### Amadeus Hotel Search API
The Amadeus Hotel Search API provides a list of the cheapest hotels in a given location with detailed information on each hotel and the option to filter by category, chain, facilities, or budget range. It returns offers with room descriptions and payment policies.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)

#### Tags:

 - Accommodation, Hotels, Pricing, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search/api-reference)
- [OpenAPI](openapi/hotel-search-openapi.yaml)
- [JSONSchema](json-schema/hotel-search-boardtype-schema.json)
- [JSONSchema](json-schema/hotel-search-cancellationtype-schema.json)
- [JSONSchema](json-schema/hotel-search-error-schema.json)
- [JSONSchema](json-schema/hotel-search-error-source-schema.json)
- [JSONSchema](json-schema/hotel-search-errors-schema.json)
- [JSONStructure](json-structure/hotel-search-boardtype-structure.json)
- [JSONStructure](json-structure/hotel-search-cancellationtype-structure.json)
- [JSONStructure](json-structure/hotel-search-error-source-structure.json)
- [JSONLD](json-ld/amadeus-hotel-search-context.jsonld)

### Amadeus Hotel Booking API
The Amadeus Hotel Booking API lets you complete bookings at over 150,000 hotels and accommodations around the world. It works in conjunction with the Hotel List and Hotel Search APIs to provide an end-to-end hotel booking workflow.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)

#### Tags:

 - Accommodation, Booking, Hotels

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking/api-reference)
- [OpenAPI](openapi/hotel-booking-openapi.yaml)
- [JSONSchema](json-schema/hotel-booking-associatedrecord-schema.json)
- [JSONSchema](json-schema/hotel-booking-contact-schema.json)
- [JSONSchema](json-schema/hotel-booking-error-schema.json)
- [JSONSchema](json-schema/hotel-booking-errorresponse-schema.json)
- [JSONSchema](json-schema/hotel-booking-hotelbookinglight-schema.json)
- [JSONStructure](json-structure/hotel-booking-associatedrecord-structure.json)
- [JSONStructure](json-structure/hotel-booking-contact-structure.json)
- [JSONStructure](json-structure/hotel-booking-error-structure.json)
- [JSONLD](json-ld/amadeus-hotel-booking-context.jsonld)

### Amadeus Hotel Ratings API
The Amadeus Hotel Ratings API uses sentiment analysis of hotel reviews to provide overall hotel ratings and ratings for specific categories like location, comfort, service, staff, internet, food, facilities, pool, and sleep quality.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)

#### Tags:

 - Hotels, Ratings, Reviews, Sentiment

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings/api-reference)
- [OpenAPI](openapi/hotel-ratings-openapi.yaml)
- [JSONSchema](json-schema/hotel-ratings-collectionlinks-schema.json)
- [JSONSchema](json-schema/hotel-ratings-collectionmeta-schema.json)
- [JSONSchema](json-schema/hotel-ratings-error-schema.json)
- [JSONSchema](json-schema/hotel-ratings-error400-schema.json)
- [JSONSchema](json-schema/hotel-ratings-error401-schema.json)
- [JSONStructure](json-structure/hotel-ratings-collectionlinks-structure.json)
- [JSONStructure](json-structure/hotel-ratings-collectionmeta-structure.json)
- [JSONStructure](json-structure/hotel-ratings-error-structure.json)
- [JSONLD](json-ld/amadeus-hotel-ratings-context.jsonld)

### Amadeus Hotel Name Autocomplete API
The Amadeus Hotel Name Autocomplete API provides a list of up to 20 hotels whose names most closely match a search query string. It powers autocomplete functionality in hotel search interfaces, helping users quickly find specific hotels by name.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)

#### Tags:

 - Autocomplete, Hotels, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete/api-reference)
- [OpenAPI](openapi/hotel-name-autocomplete-openapi.yaml)

### Amadeus Tours and Activities API
The Amadeus Tours and Activities API enables you to find the best tours, activities, and tickets in any city or neighborhood. It aggregates offers from over 45 top activity platforms such as Viator, GetYourGuide, Klook, and Musement, returning photos, descriptions, prices, and booking links.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)

#### Tags:

 - Activities, Destinations, Experiences, Tours

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)
- [APIReference](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities/api-reference)
- [OpenAPI](openapi/tours-and-activities-openapi.yaml)
- [JSONSchema](json-schema/tours-and-activities-activity-schema.json)
- [JSONSchema](json-schema/tours-and-activities-collection-meta-schema.json)
- [JSONSchema](json-schema/tours-and-activities-elementaryprice-schema.json)
- [JSONSchema](json-schema/tours-and-activities-error-400-schema.json)
- [JSONSchema](json-schema/tours-and-activities-error-404-schema.json)
- [JSONStructure](json-structure/tours-and-activities-activity-structure.json)
- [JSONStructure](json-structure/tours-and-activities-collection-meta-structure.json)
- [JSONStructure](json-structure/tours-and-activities-elementaryprice-structure.json)
- [JSONLD](json-ld/amadeus-tours-and-activities-context.jsonld)

### Amadeus Points of Interest API
The Amadeus Points of Interest API returns tourist attractions and popular places in a given location. It provides data on over two million places worldwide, scored by categories such as restaurants, shopping, sightseeing, and nightlife.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)

#### Tags:

 - Attractions, Destinations, Points of Interest

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)
- [APIReference](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest/api-reference)
- [OpenAPI](openapi/points-of-interest-openapi.yaml)
- [JSONSchema](json-schema/points-of-interest-collection-meta-schema.json)
- [JSONSchema](json-schema/points-of-interest-error-400-schema.json)
- [JSONSchema](json-schema/points-of-interest-error-404-schema.json)
- [JSONSchema](json-schema/points-of-interest-error-500-schema.json)
- [JSONSchema](json-schema/points-of-interest-geocode-schema.json)
- [JSONStructure](json-structure/points-of-interest-collection-meta-structure.json)
- [JSONStructure](json-structure/points-of-interest-error-400-structure.json)
- [JSONStructure](json-structure/points-of-interest-error-404-structure.json)
- [JSONLD](json-ld/amadeus-points-of-interest-context.jsonld)

### Amadeus Safe Place API
The Amadeus Safe Place API provides safety information for over 65,000 cities and neighborhoods worldwide. It returns crime, health, and neighborhood safety ratings powered by GeoSure, helping travelers make informed decisions about their destinations.

**Human URL:** [https://developers.amadeus.com/self-service/category/covid-19-and-travel-safety/api-doc/safe-place](https://developers.amadeus.com/self-service/category/covid-19-and-travel-safety/api-doc/safe-place)

#### Tags:

 - Destinations, Safety, Travel Safety

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/covid-19-and-travel-safety/api-doc/safe-place)
- [OpenAPI](openapi/safe-place-openapi.yaml)
- [JSONSchema](json-schema/safe-place-collection-meta-schema.json)
- [JSONSchema](json-schema/safe-place-error-400-schema.json)
- [JSONSchema](json-schema/safe-place-error-404-schema.json)
- [JSONSchema](json-schema/safe-place-error-500-schema.json)
- [JSONSchema](json-schema/safe-place-geocode-schema.json)
- [JSONStructure](json-structure/safe-place-collection-meta-structure.json)
- [JSONStructure](json-structure/safe-place-error-400-structure.json)
- [JSONStructure](json-structure/safe-place-error-404-structure.json)
- [JSONLD](json-ld/amadeus-safe-place-context.jsonld)

### Amadeus City Search API
The Amadeus City Search API enables searching for cities using keywords, with optional filtering by country code and airport inclusion. It helps travel applications provide destination autocomplete and city lookup functionality.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)

#### Tags:

 - Cities, Destinations, Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)
- [OpenAPI](openapi/city-search-openapi.yaml)
- [JSONSchema](json-schema/city-search-errors-schema.json)
- [JSONSchema](json-schema/city-search-location-schema.json)
- [JSONSchema](json-schema/city-search-meta-schema.json)
- [JSONSchema](json-schema/city-search-response-citysearch-schema.json)
- [JSONSchema](json-schema/city-search-response-error-schema.json)
- [JSONStructure](json-structure/city-search-errors-structure.json)
- [JSONStructure](json-structure/city-search-location-structure.json)
- [JSONStructure](json-structure/city-search-meta-structure.json)
- [JSONLD](json-ld/amadeus-city-search-context.jsonld)

### Amadeus Transfer Search API
The Amadeus Transfer Search API provides live prices for private transfers, hourly services, taxis, shared transfers, airport express, airport buses, private jets, and helicopter transfers. It searches across multiple mobility providers to find the best options for ground transportation.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)

#### Tags:

 - Ground Transportation, Search, Transfers

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)
- [APIReference](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search/api-reference)
- [OpenAPI](openapi/transfer-search-openapi.yaml)
- [JSONSchema](json-schema/transfer-search-address-schema.json)
- [JSONSchema](json-schema/transfer-search-addresscommon-schema.json)
- [JSONSchema](json-schema/transfer-search-baggage-schema.json)
- [JSONSchema](json-schema/transfer-search-cancellationrule-schema.json)
- [JSONSchema](json-schema/transfer-search-contact-schema.json)
- [JSONStructure](json-structure/transfer-search-address-structure.json)
- [JSONStructure](json-structure/transfer-search-addresscommon-structure.json)
- [JSONStructure](json-structure/transfer-search-baggage-structure.json)
- [JSONLD](json-ld/amadeus-transfer-search-context.jsonld)

### Amadeus Transfer Booking API
The Amadeus Transfer Booking API allows you to create transfer orders by providing passenger information, contact details, and other booking parameters. It works with the Transfer Search API to complete end-to-end ground transportation bookings.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking)

#### Tags:

 - Booking, Ground Transportation, Transfers

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking)
- [APIReference](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking/api-reference)
- [OpenAPI](openapi/transfer-booking-openapi.yaml)
- [JSONSchema](json-schema/transfer-booking-address-schema.json)
- [JSONSchema](json-schema/transfer-booking-addresscommon-schema.json)
- [JSONSchema](json-schema/transfer-booking-agency-schema.json)
- [JSONSchema](json-schema/transfer-booking-baggage-schema.json)
- [JSONSchema](json-schema/transfer-booking-cancellationrule-schema.json)
- [JSONStructure](json-structure/transfer-booking-address-structure.json)
- [JSONStructure](json-structure/transfer-booking-addresscommon-structure.json)
- [JSONStructure](json-structure/transfer-booking-agency-structure.json)
- [JSONLD](json-ld/amadeus-transfer-booking-context.jsonld)

### Amadeus Transfer Management API
The Amadeus Transfer Management API allows you to cancel transfers linked with existing orders. It provides post-booking management capabilities for ground transportation reservations, including cancellation confirmation.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)

#### Tags:

 - Ground Transportation, Management, Transfers

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)
- [APIReference](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management/api-reference)
- [OpenAPI](openapi/transfer-management-openapi.yaml)
- [JSONSchema](json-schema/transfer-management-error-400-schema.json)
- [JSONSchema](json-schema/transfer-management-error-401-schema.json)
- [JSONSchema](json-schema/transfer-management-error-404-schema.json)
- [JSONSchema](json-schema/transfer-management-error-500-schema.json)
- [JSONSchema](json-schema/transfer-management-issue-schema.json)
- [JSONStructure](json-structure/transfer-management-error-400-structure.json)
- [JSONStructure](json-structure/transfer-management-error-401-structure.json)
- [JSONStructure](json-structure/transfer-management-error-404-structure.json)
- [JSONLD](json-ld/amadeus-transfer-management-context.jsonld)

### Amadeus Flight Most Traveled Destinations API
The Amadeus Flight Most Traveled Destinations API returns the most popular flight destinations from a given origin based on the number of travelers. It helps travel applications identify trending destinations and provide data- driven recommendations.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)

#### Tags:

 - Analytics, Destinations, Flights, Market Insights

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)
- [APIReference](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations/api-reference)
- [OpenAPI](openapi/flight-most-traveled-destinations-openapi.yaml)
- [JSONSchema](json-schema/flight-most-traveled-destinations-air-traffic-schema.json)
- [JSONSchema](json-schema/flight-most-traveled-destinations-analytics-schema.json)
- [JSONSchema](json-schema/flight-most-traveled-destinations-collection-meta-schema.json)
- [JSONSchema](json-schema/flight-most-traveled-destinations-error-400-schema.json)
- [JSONSchema](json-schema/flight-most-traveled-destinations-error-500-schema.json)
- [JSONStructure](json-structure/flight-most-traveled-destinations-air-traffic-structure.json)
- [JSONStructure](json-structure/flight-most-traveled-destinations-analytics-structure.json)
- [JSONStructure](json-structure/flight-most-traveled-destinations-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-flight-most-traveled-destinations-context.jsonld)

### Amadeus Flight Most Booked Destinations API
The Amadeus Flight Most Booked Destinations API returns the most frequently booked flight destinations from a given origin. It provides booking trend data as a percentage of total departures, helping travel applications understand market demand.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)

#### Tags:

 - Analytics, Booking, Flights, Market Insights

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)
- [APIReference](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations/api-reference)
- [OpenAPI](openapi/flight-most-booked-destinations-openapi.yaml)
- [JSONSchema](json-schema/flight-most-booked-destinations-air-traffic-schema.json)
- [JSONSchema](json-schema/flight-most-booked-destinations-analytics-schema.json)
- [JSONSchema](json-schema/flight-most-booked-destinations-collection-meta-schema.json)
- [JSONSchema](json-schema/flight-most-booked-destinations-error-400-schema.json)
- [JSONSchema](json-schema/flight-most-booked-destinations-error-500-schema.json)
- [JSONStructure](json-structure/flight-most-booked-destinations-air-traffic-structure.json)
- [JSONStructure](json-structure/flight-most-booked-destinations-analytics-structure.json)
- [JSONStructure](json-structure/flight-most-booked-destinations-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-flight-most-booked-destinations-context.jsonld)

### Amadeus Flight Busiest Traveling Period API
The Amadeus Flight Busiest Traveling Period API returns the peak travel periods for a specific city based on historical air traffic data. It helps travel applications identify high and low seasons, enabling better planning and pricing strategies.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)

#### Tags:

 - Analytics, Flights, Market Insights, Trends

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)
- [APIReference](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period/api-reference)
- [OpenAPI](openapi/flight-busiest-traveling-period-openapi.yaml)
- [JSONSchema](json-schema/flight-busiest-traveling-period-air-traffic-schema.json)
- [JSONSchema](json-schema/flight-busiest-traveling-period-analytics-schema.json)
- [JSONSchema](json-schema/flight-busiest-traveling-period-collection-meta-schema.json)
- [JSONSchema](json-schema/flight-busiest-traveling-period-error-400-schema.json)
- [JSONSchema](json-schema/flight-busiest-traveling-period-error-500-schema.json)
- [JSONStructure](json-structure/flight-busiest-traveling-period-air-traffic-structure.json)
- [JSONStructure](json-structure/flight-busiest-traveling-period-analytics-structure.json)
- [JSONStructure](json-structure/flight-busiest-traveling-period-collection-meta-structure.json)
- [JSONLD](json-ld/amadeus-flight-busiest-traveling-period-context.jsonld)

### Amadeus Location Score API
The Amadeus Location Score API provides travel and location intelligence scores for specific areas. It evaluates locations based on various criteria to help travel applications assess the desirability and characteristics of different neighborhoods and areas.

**Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/location-score](https://developers.amadeus.com/self-service/category/market-insights/api-doc/location-score)

#### Tags:

 - Analytics, Location, Market Insights

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/location-score)
- [APIReference](https://developers.amadeus.com/self-service/category/market-insights/api-doc/location-score/api-reference)
- [OpenAPI](openapi/location-score-openapi.yaml)
- [JSONSchema](json-schema/location-score-category-rated-areas-schema.json)
- [JSONSchema](json-schema/location-score-errors-schema.json)
- [JSONSchema](json-schema/location-score-meta-schema.json)
- [JSONSchema](json-schema/location-score-response-error-schema.json)
- [JSONSchema](json-schema/location-score-response-locationscore-schema.json)
- [JSONStructure](json-structure/location-score-category-rated-areas-structure.json)
- [JSONStructure](json-structure/location-score-errors-structure.json)
- [JSONStructure](json-structure/location-score-meta-structure.json)
- [JSONLD](json-ld/amadeus-location-score-context.jsonld)

### Amadeus Trip Purpose Prediction API
The Amadeus Trip Purpose Prediction API predicts whether a flight search is for business or leisure travel using machine learning. It analyzes patterns in departure and arrival cities, flight dates, and search dates to help travel applications personalize offers for each traveler.

**Human URL:** [https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)

#### Tags:

 - Itinerary, Machine Learning, Prediction, Trips

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)
- [APIReference](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction/api-reference)
- [OpenAPI](openapi/trip-purpose-prediction-openapi.yaml)
- [JSONSchema](json-schema/trip-purpose-prediction-defaults-schema.json)
- [JSONSchema](json-schema/trip-purpose-prediction-error-400-schema.json)
- [JSONSchema](json-schema/trip-purpose-prediction-error-500-schema.json)
- [JSONSchema](json-schema/trip-purpose-prediction-issue-schema.json)
- [JSONSchema](json-schema/trip-purpose-prediction-links-schema.json)
- [JSONStructure](json-structure/trip-purpose-prediction-defaults-structure.json)
- [JSONStructure](json-structure/trip-purpose-prediction-error-400-structure.json)
- [JSONStructure](json-structure/trip-purpose-prediction-error-500-structure.json)
- [JSONLD](json-ld/amadeus-trip-purpose-prediction-context.jsonld)

### Amadeus Trip Parser API
The Amadeus Trip Parser API parses travel booking confirmation emails and documents to extract structured itinerary data. It enables travel applications to automatically import bookings from email confirmations and build organized trip itineraries.

**Human URL:** [https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser)

#### Tags:

 - Email, Itinerary, Parsing, Trips

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser)
- [APIReference](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser/api-reference)
- [OpenAPI](openapi/trip-parser-openapi.yaml)
- [JSONSchema](json-schema/trip-parser-address-schema.json)
- [JSONSchema](json-schema/trip-parser-air-schema.json)
- [JSONSchema](json-schema/trip-parser-aircraft-schema.json)
- [JSONSchema](json-schema/trip-parser-airdata-schema.json)
- [JSONSchema](json-schema/trip-parser-arrival-schema.json)
- [JSONStructure](json-structure/trip-parser-address-structure.json)
- [JSONStructure](json-structure/trip-parser-air-structure.json)
- [JSONStructure](json-structure/trip-parser-aircraft-structure.json)
- [JSONLD](json-ld/amadeus-trip-parser-context.jsonld)

### Amadeus OAuth2 Login API
The Amadeus OAuth2 Login API provides authentication for all Amadeus self- service APIs. It implements the OAuth 2.0 client credentials grant type, allowing applications to obtain access tokens required to make authenticated requests to any Amadeus API endpoint.

**Human URL:** [https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/API-Keys/authorization](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/API-Keys/authorization)

#### Tags:

 - Authentication, OAuth, Security

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/API-Keys/authorization)
- [OpenAPI](openapi/amadeus-oauth2-login-openapi.yaml)
- [JSONSchema](json-schema/amadeus-oauth2-login-amadeusoauth2token-schema.json)
- [JSONSchema](json-schema/amadeus-oauth2-login-errorresponse-schema.json)
- [JSONStructure](json-structure/amadeus-oauth2-login-amadeusoauth2token-structure.json)
- [JSONStructure](json-structure/amadeus-oauth2-login-errorresponse-structure.json)
- [JSONLD](json-ld/amadeus-amadeus-oauth2-login-context.jsonld)

## Common Properties

- [Portal](https://developers.amadeus.com/)
- [Documentation](https://developers.amadeus.com/self-service)
- [GettingStarted](https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/API-Keys/authorization)
- [Pricing](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/pricing/)
- [DeveloperTools](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/developer-tools/)
- [APIGuides](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/)
- [Tutorials](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/resources/)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Quickstart](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/quick-start/)
- [TermsOfService](https://developers.amadeus.com/legal/terms-of-use)
- [PrivacyPolicy](https://developers.amadeus.com/legal/privacy-policy)
- [SignUp](https://developers.amadeus.com/register)
- [Support](https://developers.amadeus.com/support)
- [Blog](https://developers.amadeus.com/blog)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [SDKs](https://github.com/amadeus4dev/amadeus-python)
- [PostmanCollection](https://www.postman.com/amadeus4dev/amadeus-for-developers-s-public-workspace/collection/kquqijj/amadeus-for-developers)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amadeus)
- [Website](https://amadeus.com)
- [SpectralRules](rules/amadeus-spectral-rules.yml)
- [NaftikoCapability](capabilities/travel-booking.yaml)
- [Vocabulary](vocabulary/amadeus-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Flight Search and Booking | Search over 500 airlines, confirm pricing, and create flight bookings with the Amadeus flight APIs including offers search, price confirmation, and order creation. |
| Hotel Search and Booking | Search hotels by city, geocoordinates, or hotel ID, view room offers and pricing, and complete hotel bookings at over 150,000 properties worldwide. |
| Ground Transportation | Search and book private transfers, taxis, shared rides, airport express, and helicopter services across multiple mobility providers. |
| Destination Experiences | Discover tours, activities, tickets, points of interest, and safety scores for destinations worldwide, powered by 45+ activity platforms. |
| AI-Powered Travel Insights | Use machine learning APIs to predict flight delays, recommend destinations, identify trip purpose, analyze flight prices, and predict traveler flight choices. |

## Use Cases

| Name | Description |
|------|-------------|
| Flight Booking Engine | Build end-to-end flight booking flows using flight offers search, price confirmation, and order creation APIs. |
| Hotel Booking Platform | Create hotel booking experiences by combining hotel list, hotel search, and hotel booking APIs. |
| Trip Planning Application | Build complete trip planners that combine flights, hotels, transfers, and local activities in a unified travel experience. |
| Travel Intelligence Dashboard | Build market insights dashboards using flight analytics APIs for trending destinations, busiest periods, and price analysis. |
| Corporate Travel Management | Power corporate travel tools with flight search, trip purpose prediction, delay predictions, and itinerary parsing capabilities. |

## Integrations

| Name | Description |
|------|-------------|
| Viator | Amadeus Tours and Activities API aggregates offers from Viator for tours, experiences, and activity bookings at destinations worldwide. |
| GetYourGuide | GetYourGuide activity offers are included in the Amadeus Tours and Activities API for comprehensive activity discovery. |
| GeoSure | The Amadeus Safe Place API is powered by GeoSure neighborhood safety scores covering crime, health, and safety ratings for over 65,000 locations. |
| Leonardo | Amadeus recommends Leonardo as the trusted content partner for hotel images and property media not available through self-service APIs. |
| Postman | Amadeus provides a public Postman workspace for developers to explore and test all self-service APIs interactively. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amadeus Flight Offers Search API OpenAPI](openapi/flight-offers-search-openapi.yaml)
- [Amadeus Flight Offers Price API OpenAPI](openapi/flight-offers-price-openapi.yaml)
- [Amadeus Flight Create Orders API OpenAPI](openapi/flight-create-orders-openapi.yaml)
- [Amadeus Flight Order Management API OpenAPI](openapi/flight-order-management-openapi.yaml)
- [Amadeus Seatmap Display API OpenAPI](openapi/seatmap-display-openapi.yaml)
- [Amadeus Branded Fares Upsell API OpenAPI](openapi/branded-fares-upsell-openapi.yaml)
- [Amadeus Flight Price Analysis API OpenAPI](openapi/flight-price-analysis-openapi.yaml)
- [Amadeus Flight Choice Prediction API OpenAPI](openapi/flight-choice-prediction-openapi.yaml)
- [Amadeus Flight Inspiration Search API OpenAPI](openapi/flight-inspiration-search-openapi.yaml)
- [Amadeus Flight Cheapest Date Search API OpenAPI](openapi/flight-cheapest-date-search-openapi.yaml)
- [Amadeus Flight Availabilities Search API OpenAPI](openapi/flight-availibilities-search-openapi.yaml)
- [Amadeus Travel Recommendations API OpenAPI](openapi/travel-recommendations-openapi.yaml)
- [Amadeus On-Demand Flight Status API OpenAPI](openapi/on-demand-flight-status-openapi.yaml)
- [Amadeus Flight Delay Prediction API OpenAPI](openapi/flight-delay-prediction-openapi.yaml)
- [Amadeus Airport and City Search API OpenAPI](openapi/airport-city-search-openapi.yaml)
- [Amadeus Airport Nearest Relevant API OpenAPI](openapi/airport-nearest-relevant-openapi.yaml)
- [Amadeus Airport Routes API OpenAPI](openapi/airport-routes-openapi.yaml)
- [Amadeus Airport On-Time Performance API OpenAPI](openapi/airport-on-time-performance-openapi.yaml)
- [Amadeus Flight Check-in Links API OpenAPI](openapi/flight-check-in-links-openapi.yaml)
- [Amadeus Airline Code Lookup API OpenAPI](openapi/airline-code-lookup-openapi.yaml)
- [Amadeus Airline Routes API OpenAPI](openapi/airline-routes-openapi.yaml)
- [Amadeus Hotel List API OpenAPI](openapi/hotel-list-openapi.yaml)
- [Amadeus Hotel Search API OpenAPI](openapi/hotel-search-openapi.yaml)
- [Amadeus Hotel Booking API OpenAPI](openapi/hotel-booking-openapi.yaml)
- [Amadeus Hotel Ratings API OpenAPI](openapi/hotel-ratings-openapi.yaml)
- [Amadeus Hotel Name Autocomplete API OpenAPI](openapi/hotel-name-autocomplete-openapi.yaml)
- [Amadeus Tours and Activities API OpenAPI](openapi/tours-and-activities-openapi.yaml)
- [Amadeus Points of Interest API OpenAPI](openapi/points-of-interest-openapi.yaml)
- [Amadeus Safe Place API OpenAPI](openapi/safe-place-openapi.yaml)
- [Amadeus City Search API OpenAPI](openapi/city-search-openapi.yaml)
- [Amadeus Transfer Search API OpenAPI](openapi/transfer-search-openapi.yaml)
- [Amadeus Transfer Booking API OpenAPI](openapi/transfer-booking-openapi.yaml)
- [Amadeus Transfer Management API OpenAPI](openapi/transfer-management-openapi.yaml)
- [Amadeus Flight Most Traveled Destinations API OpenAPI](openapi/flight-most-traveled-destinations-openapi.yaml)
- [Amadeus Flight Most Booked Destinations API OpenAPI](openapi/flight-most-booked-destinations-openapi.yaml)
- [Amadeus Flight Busiest Traveling Period API OpenAPI](openapi/flight-busiest-traveling-period-openapi.yaml)
- [Amadeus Location Score API OpenAPI](openapi/location-score-openapi.yaml)
- [Amadeus Trip Purpose Prediction API OpenAPI](openapi/trip-purpose-prediction-openapi.yaml)
- [Amadeus Trip Parser API OpenAPI](openapi/trip-parser-openapi.yaml)
- [Amadeus OAuth2 Login API OpenAPI](openapi/amadeus-oauth2-login-openapi.yaml)

### JSON Schema

- [airline-code-lookup-airline-schema.json](json-schema/airline-code-lookup-airline-schema.json)
- [airline-code-lookup-airlinecollection-schema.json](json-schema/airline-code-lookup-airlinecollection-schema.json)
- [airline-code-lookup-collectionmeta-schema.json](json-schema/airline-code-lookup-collectionmeta-schema.json)
- [airline-code-lookup-errorresponse-schema.json](json-schema/airline-code-lookup-errorresponse-schema.json)
- [airline-code-lookup-issue-schema.json](json-schema/airline-code-lookup-issue-schema.json)
- [airline-routes-errors-schema.json](json-schema/airline-routes-errors-schema.json)
- [airline-routes-locations-schema.json](json-schema/airline-routes-locations-schema.json)
- [airline-routes-meta-schema.json](json-schema/airline-routes-meta-schema.json)
- [airline-routes-response-airlineroutes-schema.json](json-schema/airline-routes-response-airlineroutes-schema.json)
- [airline-routes-response-error-schema.json](json-schema/airline-routes-response-error-schema.json)
- [airline-routes-warnings-schema.json](json-schema/airline-routes-warnings-schema.json)
- [airport-city-search-address-schema.json](json-schema/airport-city-search-address-schema.json)
- [airport-city-search-analytics-schema.json](json-schema/airport-city-search-analytics-schema.json)
- [airport-city-search-collection-meta-schema.json](json-schema/airport-city-search-collection-meta-schema.json)
- [airport-city-search-distance-schema.json](json-schema/airport-city-search-distance-schema.json)
- [airport-city-search-error-400-schema.json](json-schema/airport-city-search-error-400-schema.json)
- [airport-city-search-error-404-schema.json](json-schema/airport-city-search-error-404-schema.json)
- [airport-city-search-error-500-schema.json](json-schema/airport-city-search-error-500-schema.json)
- [airport-city-search-geocode-schema.json](json-schema/airport-city-search-geocode-schema.json)
- [airport-city-search-issue-schema.json](json-schema/airport-city-search-issue-schema.json)
- ... and 830 more

### JSON-LD

- [amadeus-airline-code-lookup-context.jsonld](json-ld/amadeus-airline-code-lookup-context.jsonld)
- [amadeus-airline-routes-context.jsonld](json-ld/amadeus-airline-routes-context.jsonld)
- [amadeus-airport-city-search-context.jsonld](json-ld/amadeus-airport-city-search-context.jsonld)
- [amadeus-airport-nearest-relevant-context.jsonld](json-ld/amadeus-airport-nearest-relevant-context.jsonld)
- [amadeus-airport-on-time-performance-context.jsonld](json-ld/amadeus-airport-on-time-performance-context.jsonld)
- [amadeus-airport-routes-context.jsonld](json-ld/amadeus-airport-routes-context.jsonld)
- [amadeus-amadeus-oauth2-login-context.jsonld](json-ld/amadeus-amadeus-oauth2-login-context.jsonld)
- [amadeus-branded-fares-upsell-context.jsonld](json-ld/amadeus-branded-fares-upsell-context.jsonld)
- [amadeus-city-search-context.jsonld](json-ld/amadeus-city-search-context.jsonld)
- [amadeus-flight-availibilities-search-context.jsonld](json-ld/amadeus-flight-availibilities-search-context.jsonld)
- [amadeus-flight-busiest-traveling-period-context.jsonld](json-ld/amadeus-flight-busiest-traveling-period-context.jsonld)
- [amadeus-flight-cheapest-date-search-context.jsonld](json-ld/amadeus-flight-cheapest-date-search-context.jsonld)
- [amadeus-flight-check-in-links-context.jsonld](json-ld/amadeus-flight-check-in-links-context.jsonld)
- [amadeus-flight-choice-prediction-context.jsonld](json-ld/amadeus-flight-choice-prediction-context.jsonld)
- [amadeus-flight-create-orders-context.jsonld](json-ld/amadeus-flight-create-orders-context.jsonld)
- [amadeus-flight-delay-prediction-context.jsonld](json-ld/amadeus-flight-delay-prediction-context.jsonld)
- [amadeus-flight-inspiration-search-context.jsonld](json-ld/amadeus-flight-inspiration-search-context.jsonld)
- [amadeus-flight-most-booked-destinations-context.jsonld](json-ld/amadeus-flight-most-booked-destinations-context.jsonld)
- [amadeus-flight-most-traveled-destinations-context.jsonld](json-ld/amadeus-flight-most-traveled-destinations-context.jsonld)
- [amadeus-flight-offers-price-context.jsonld](json-ld/amadeus-flight-offers-price-context.jsonld)
- [amadeus-flight-offers-search-context.jsonld](json-ld/amadeus-flight-offers-search-context.jsonld)
- [amadeus-flight-order-management-context.jsonld](json-ld/amadeus-flight-order-management-context.jsonld)
- [amadeus-flight-price-analysis-context.jsonld](json-ld/amadeus-flight-price-analysis-context.jsonld)
- [amadeus-hotel-booking-context.jsonld](json-ld/amadeus-hotel-booking-context.jsonld)
- [amadeus-hotel-list-context.jsonld](json-ld/amadeus-hotel-list-context.jsonld)
- [amadeus-hotel-ratings-context.jsonld](json-ld/amadeus-hotel-ratings-context.jsonld)
- [amadeus-hotel-search-context.jsonld](json-ld/amadeus-hotel-search-context.jsonld)
- [amadeus-location-score-context.jsonld](json-ld/amadeus-location-score-context.jsonld)
- [amadeus-on-demand-flight-status-context.jsonld](json-ld/amadeus-on-demand-flight-status-context.jsonld)
- [amadeus-points-of-interest-context.jsonld](json-ld/amadeus-points-of-interest-context.jsonld)
- [amadeus-safe-place-context.jsonld](json-ld/amadeus-safe-place-context.jsonld)
- [amadeus-seatmap-display-context.jsonld](json-ld/amadeus-seatmap-display-context.jsonld)
- [amadeus-tours-and-activities-context.jsonld](json-ld/amadeus-tours-and-activities-context.jsonld)
- [amadeus-transfer-booking-context.jsonld](json-ld/amadeus-transfer-booking-context.jsonld)
- [amadeus-transfer-management-context.jsonld](json-ld/amadeus-transfer-management-context.jsonld)
- [amadeus-transfer-search-context.jsonld](json-ld/amadeus-transfer-search-context.jsonld)
- [amadeus-travel-recommendations-context.jsonld](json-ld/amadeus-travel-recommendations-context.jsonld)
- [amadeus-trip-parser-context.jsonld](json-ld/amadeus-trip-parser-context.jsonld)
- [amadeus-trip-purpose-prediction-context.jsonld](json-ld/amadeus-trip-purpose-prediction-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Flight Offers Search API](capabilities/shared/flight-offers-search.yaml) — 1 operation for flight search
- [Hotel Search API](capabilities/shared/hotel-search.yaml) — 1 operation for hotel search

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Full Travel Booking](capabilities/travel-booking.yaml) | Flight Offers Search API, Hotel Search API | 2 | Travel Developer, OTA Booking Team |

## Vocabulary

- [Amadeus Vocabulary](vocabulary/amadeus-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational and capability dimensions

## Rules

- [Amadeus Spectral Rules](rules/amadeus-spectral-rules.yml) — 15 rules across OpenAPI conventions enforcing Amadeus API standards

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
