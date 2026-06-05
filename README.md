# Amadeus (amadeus)

Amadeus for Developers is the self-service developer program from Amadeus IT Group, the leading technology provider for the global travel and tourism industry. The Self-Service catalog offers 40+ travel REST APIs across flights, hotels, destination experiences, cars and transfers, market insights, itinerary management, and AI-powered prediction services. APIs use OAuth2 client credentials authentication and are organized into Test (free, capped) and Production (paid, higher TPS) environments. Note: Amadeus has announced the Self-Service developer portal will be decommissioned on 17 July 2026; Enterprise customers retain access to the equivalent Enterprise APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Travel
- Travel Technology
- Reservations
- Flights
- Hotels
- Airlines
- Hospitality
- Tours and Activities
- Cars and Transfers
- Destination Content
- Itinerary Management
- Trip Planning
- Artificial Intelligence
- Market Insights

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-30

## APIs

### Flight Offers Search

Searches over 500 airlines to find the cheapest flight offers for a given itinerary. Supports one-way, round-trip, and multi-city searches with rich filtering (cabin class, max price, included/excluded airlines, non-stop preferred).

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Flights
- Search
- Pricing
- Itinerary

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)
- [OpenAPI](openapi/amadeus-flight-offers-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-offers-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-offers-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search/api-reference)
- [JSON Schema](json-schema/flight-offers-search-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-cabin-restriction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-carrier-restrictions-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-chargeable-checkd-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-chargeable-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-collection-meta-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-connection-restriction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-coverage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-date-time-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-date-time-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-extended-cabin-restriction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-extended-pricing-options-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-extended-traveler-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-filters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-get-flight-offers-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-origin-destination-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-origin-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-search-criteria-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-traveler-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-search-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-offers-search-additional-service-type-structure.json)
- [JSON Structure](json-structure/flight-offers-search-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-search-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-offers-search-allotment-details-structure.json)
- [JSON Structure](json-structure/flight-offers-search-baggage-allowance-structure.json)
- [JSON Structure](json-structure/flight-offers-search-cabin-restriction-structure.json)
- [JSON Structure](json-structure/flight-offers-search-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-search-carrier-restrictions-structure.json)
- [JSON Structure](json-structure/flight-offers-search-chargeable-checkd-bags-structure.json)
- [JSON Structure](json-structure/flight-offers-search-chargeable-seat-structure.json)
- [JSON Structure](json-structure/flight-offers-search-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-offers-search-collection-meta-link-structure.json)
- [JSON Structure](json-structure/flight-offers-search-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-offers-search-connection-restriction-structure.json)
- [JSON Structure](json-structure/flight-offers-search-coverage-structure.json)
- [JSON Structure](json-structure/flight-offers-search-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-search-date-time-range-structure.json)
- [JSON Structure](json-structure/flight-offers-search-date-time-type-structure.json)
- [JSON Structure](json-structure/flight-offers-search-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-offers-search-error-400-structure.json)
- [JSON Structure](json-structure/flight-offers-search-error-500-structure.json)
- [JSON Structure](json-structure/flight-offers-search-extended-cabin-restriction-structure.json)
- [JSON Structure](json-structure/flight-offers-search-extended-price-structure.json)
- [JSON Structure](json-structure/flight-offers-search-extended-pricing-options-structure.json)
- [JSON Structure](json-structure/flight-offers-search-extended-traveler-info-structure.json)
- [JSON Structure](json-structure/flight-offers-search-fee-structure.json)
- [JSON Structure](json-structure/flight-offers-search-fee-type-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-filters-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-offer-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-offers-search-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-offers-search-get-flight-offers-query-structure.json)
- [JSON Structure](json-structure/flight-offers-search-issue-structure.json)
- [JSON Structure](json-structure/flight-offers-search-location-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-search-location-value-structure.json)
- [JSON Structure](json-structure/flight-offers-search-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-offers-search-origin-destination-light-structure.json)
- [JSON Structure](json-structure/flight-offers-search-origin-destination-structure.json)
- [JSON Structure](json-structure/flight-offers-search-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-offers-search-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-offers-search-price-structure.json)
- [JSON Structure](json-structure/flight-offers-search-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/flight-offers-search-search-criteria-structure.json)
- [JSON Structure](json-structure/flight-offers-search-segment-structure.json)
- [JSON Structure](json-structure/flight-offers-search-service-name-structure.json)
- [JSON Structure](json-structure/flight-offers-search-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/flight-offers-search-tax-structure.json)
- [JSON Structure](json-structure/flight-offers-search-travel-class-structure.json)
- [JSON Structure](json-structure/flight-offers-search-traveler-info-structure.json)
- [JSON Structure](json-structure/flight-offers-search-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/flight-offers-search-traveler-type-structure.json)
- [Example](examples/flight-offers-search-aircraft-equipment-example.json)
- [Example](examples/flight-offers-search-allotment-details-example.json)
- [Example](examples/flight-offers-search-baggage-allowance-example.json)
- [Example](examples/flight-offers-search-cabin-restriction-example.json)
- [Example](examples/flight-offers-search-carrier-restrictions-example.json)
- [Example](examples/flight-offers-search-chargeable-seat-example.json)
- [Example](examples/flight-offers-search-co2-emission-example.json)
- [Example](examples/flight-offers-search-collection-meta-example.json)
- [Example](examples/flight-offers-search-collection-meta-link-example.json)
- [Example](examples/flight-offers-search-connection-restriction-example.json)
- [Example](examples/flight-offers-search-date-time-type-example.json)
- [Example](examples/flight-offers-search-dictionaries-example.json)
- [Example](examples/flight-offers-search-error-400-example.json)
- [Example](examples/flight-offers-search-error-500-example.json)
- [Example](examples/flight-offers-search-extended-price-example.json)
- [Example](examples/flight-offers-search-extended-pricing-options-example.json)
- [Example](examples/flight-offers-search-fee-example.json)
- [Example](examples/flight-offers-search-flight-filters-example.json)
- [Example](examples/flight-offers-search-flight-offer-example.json)
- [Example](examples/flight-offers-search-flight-segment-example.json)
- [Example](examples/flight-offers-search-get-flight-offers-query-example.json)
- [Example](examples/flight-offers-search-issue-example.json)
- [Example](examples/flight-offers-search-location-value-example.json)
- [Example](examples/flight-offers-search-operating-flight-example.json)
- [Example](examples/flight-offers-search-origin-destination-light-example.json)
- [Example](examples/flight-offers-search-original-flight-end-point-example.json)
- [Example](examples/flight-offers-search-original-flight-stop-example.json)
- [Example](examples/flight-offers-search-price-example.json)
- [Example](examples/flight-offers-search-search-criteria-example.json)
- [Example](examples/flight-offers-search-tax-example.json)
- [Example](examples/flight-offers-search-traveler-info-example.json)

### Flight Offers Price

Confirms the final price and availability of a flight offer returned by Flight Offers Search, including taxes, fees, and fare rules, before booking.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Pricing
- Pre-Booking

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)
- [OpenAPI](openapi/amadeus-flight-offers-price-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-offers-price.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-offers-price.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-offers-price-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-base-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-chargeable-checkd-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-chargeable-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-contact-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-contact-purpose-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-credit-card-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-detailed-fare-rules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-discount-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-discount-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-document-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-elementary-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-emergency-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-fare-rules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-offer-pricing-in-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-offer-pricing-out-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-identity-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-loyalty-program-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-other-services-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-payment-brand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-phone-device-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-phone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-stakeholder-gender-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-stakeholder-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-term-and-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-traveler-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-offers-price-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-offers-price-additional-service-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-address-structure.json)
- [JSON Structure](json-structure/flight-offers-price-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-price-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-offers-price-allotment-details-structure.json)
- [JSON Structure](json-structure/flight-offers-price-baggage-allowance-structure.json)
- [JSON Structure](json-structure/flight-offers-price-bags-structure.json)
- [JSON Structure](json-structure/flight-offers-price-base-name-structure.json)
- [JSON Structure](json-structure/flight-offers-price-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-price-chargeable-checkd-bags-structure.json)
- [JSON Structure](json-structure/flight-offers-price-chargeable-seat-structure.json)
- [JSON Structure](json-structure/flight-offers-price-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-offers-price-contact-dictionary-structure.json)
- [JSON Structure](json-structure/flight-offers-price-contact-purpose-structure.json)
- [JSON Structure](json-structure/flight-offers-price-contact-structure.json)
- [JSON Structure](json-structure/flight-offers-price-credit-card-fee-structure.json)
- [JSON Structure](json-structure/flight-offers-price-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-price-detailed-fare-rules-structure.json)
- [JSON Structure](json-structure/flight-offers-price-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-offers-price-discount-structure.json)
- [JSON Structure](json-structure/flight-offers-price-discount-traveler-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-discount-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-document-structure.json)
- [JSON Structure](json-structure/flight-offers-price-document-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-elementary-price-structure.json)
- [JSON Structure](json-structure/flight-offers-price-emergency-contact-structure.json)
- [JSON Structure](json-structure/flight-offers-price-error-400-structure.json)
- [JSON Structure](json-structure/flight-offers-price-error-500-structure.json)
- [JSON Structure](json-structure/flight-offers-price-extended-price-structure.json)
- [JSON Structure](json-structure/flight-offers-price-fare-rules-structure.json)
- [JSON Structure](json-structure/flight-offers-price-fee-structure.json)
- [JSON Structure](json-structure/flight-offers-price-fee-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-offer-pricing-in-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-offer-pricing-out-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-offer-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-offers-price-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-offers-price-identity-document-structure.json)
- [JSON Structure](json-structure/flight-offers-price-issue-structure.json)
- [JSON Structure](json-structure/flight-offers-price-location-entry-structure.json)
- [JSON Structure](json-structure/flight-offers-price-location-value-structure.json)
- [JSON Structure](json-structure/flight-offers-price-loyalty-program-structure.json)
- [JSON Structure](json-structure/flight-offers-price-name-structure.json)
- [JSON Structure](json-structure/flight-offers-price-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-offers-price-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-offers-price-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-offers-price-other-services-structure.json)
- [JSON Structure](json-structure/flight-offers-price-payment-brand-structure.json)
- [JSON Structure](json-structure/flight-offers-price-phone-device-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-phone-structure.json)
- [JSON Structure](json-structure/flight-offers-price-price-structure.json)
- [JSON Structure](json-structure/flight-offers-price-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/flight-offers-price-segment-structure.json)
- [JSON Structure](json-structure/flight-offers-price-service-name-structure.json)
- [JSON Structure](json-structure/flight-offers-price-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/flight-offers-price-stakeholder-gender-structure.json)
- [JSON Structure](json-structure/flight-offers-price-stakeholder-structure.json)
- [JSON Structure](json-structure/flight-offers-price-tax-structure.json)
- [JSON Structure](json-structure/flight-offers-price-term-and-condition-structure.json)
- [JSON Structure](json-structure/flight-offers-price-travel-class-structure.json)
- [JSON Structure](json-structure/flight-offers-price-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/flight-offers-price-traveler-structure.json)
- [JSON Structure](json-structure/flight-offers-price-traveler-type-structure.json)
- [Example](examples/flight-offers-price-address-example.json)
- [Example](examples/flight-offers-price-aircraft-equipment-example.json)
- [Example](examples/flight-offers-price-allotment-details-example.json)
- [Example](examples/flight-offers-price-baggage-allowance-example.json)
- [Example](examples/flight-offers-price-base-name-example.json)
- [Example](examples/flight-offers-price-chargeable-seat-example.json)
- [Example](examples/flight-offers-price-co2-emission-example.json)
- [Example](examples/flight-offers-price-contact-dictionary-example.json)
- [Example](examples/flight-offers-price-credit-card-fee-example.json)
- [Example](examples/flight-offers-price-detailed-fare-rules-example.json)
- [Example](examples/flight-offers-price-dictionaries-example.json)
- [Example](examples/flight-offers-price-discount-example.json)
- [Example](examples/flight-offers-price-document-example.json)
- [Example](examples/flight-offers-price-elementary-price-example.json)
- [Example](examples/flight-offers-price-emergency-contact-example.json)
- [Example](examples/flight-offers-price-error-400-example.json)
- [Example](examples/flight-offers-price-error-500-example.json)
- [Example](examples/flight-offers-price-extended-price-example.json)
- [Example](examples/flight-offers-price-fare-rules-example.json)
- [Example](examples/flight-offers-price-fee-example.json)
- [Example](examples/flight-offers-price-flight-offer-example.json)
- [Example](examples/flight-offers-price-flight-offer-pricing-in-example.json)
- [Example](examples/flight-offers-price-flight-offer-pricing-out-example.json)
- [Example](examples/flight-offers-price-flight-segment-example.json)
- [Example](examples/flight-offers-price-issue-example.json)
- [Example](examples/flight-offers-price-location-value-example.json)
- [Example](examples/flight-offers-price-loyalty-program-example.json)
- [Example](examples/flight-offers-price-operating-flight-example.json)
- [Example](examples/flight-offers-price-original-flight-end-point-example.json)
- [Example](examples/flight-offers-price-original-flight-stop-example.json)
- [Example](examples/flight-offers-price-other-services-example.json)
- [Example](examples/flight-offers-price-phone-example.json)
- [Example](examples/flight-offers-price-price-example.json)
- [Example](examples/flight-offers-price-stakeholder-example.json)
- [Example](examples/flight-offers-price-tax-example.json)
- [Example](examples/flight-offers-price-term-and-condition-example.json)

### Flight Create Orders

Books a flight offer by creating a flight order (PNR) with traveler details, contact info, and payment, returning the order ID and ticketing reference.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Booking
- Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)
- [OpenAPI](openapi/amadeus-flight-create-orders-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-create-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-create-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-create-orders-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-air-travel-document-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-air-travel-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-airline-remark-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-airline-remark-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-associated-record-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-associated-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-automated-process-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-automated-process-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-automated-process-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-b2b-wallet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-base-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-chargeable-checkd-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-chargeable-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-collection-meta-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-contact-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-contact-purpose-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-credit-card-brand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-credit-card-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-credit-card-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-discount-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-discount-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-document-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-elementary-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-emergency-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-form-of-identification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-form-of-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-general-remark-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-general-remark-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-identity-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-loyalty-program-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-other-method-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-other-payment-method-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-phone-device-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-phone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-remarks-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-stakeholder-gender-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-stakeholder-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-ticketing-agreement-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-ticketing-agreement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-traveler-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-create-orders-virtual-credit-card-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-create-orders-additional-service-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-address-structure.json)
- [JSON Structure](json-structure/flight-create-orders-air-travel-document-common-structure.json)
- [JSON Structure](json-structure/flight-create-orders-air-travel-document-structure.json)
- [JSON Structure](json-structure/flight-create-orders-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-create-orders-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-create-orders-airline-remark-structure.json)
- [JSON Structure](json-structure/flight-create-orders-airline-remark-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-allotment-details-structure.json)
- [JSON Structure](json-structure/flight-create-orders-associated-record-common-structure.json)
- [JSON Structure](json-structure/flight-create-orders-associated-record-structure.json)
- [JSON Structure](json-structure/flight-create-orders-automated-process-code-structure.json)
- [JSON Structure](json-structure/flight-create-orders-automated-process-common-structure.json)
- [JSON Structure](json-structure/flight-create-orders-automated-process-structure.json)
- [JSON Structure](json-structure/flight-create-orders-b2b-wallet-structure.json)
- [JSON Structure](json-structure/flight-create-orders-baggage-allowance-structure.json)
- [JSON Structure](json-structure/flight-create-orders-base-name-structure.json)
- [JSON Structure](json-structure/flight-create-orders-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-create-orders-chargeable-checkd-bags-structure.json)
- [JSON Structure](json-structure/flight-create-orders-chargeable-seat-structure.json)
- [JSON Structure](json-structure/flight-create-orders-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-create-orders-collection-meta-link-structure.json)
- [JSON Structure](json-structure/flight-create-orders-contact-dictionary-structure.json)
- [JSON Structure](json-structure/flight-create-orders-contact-purpose-structure.json)
- [JSON Structure](json-structure/flight-create-orders-contact-structure.json)
- [JSON Structure](json-structure/flight-create-orders-credit-card-brand-structure.json)
- [JSON Structure](json-structure/flight-create-orders-credit-card-common-structure.json)
- [JSON Structure](json-structure/flight-create-orders-credit-card-structure.json)
- [JSON Structure](json-structure/flight-create-orders-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-create-orders-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-create-orders-discount-structure.json)
- [JSON Structure](json-structure/flight-create-orders-discount-traveler-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-discount-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-document-structure.json)
- [JSON Structure](json-structure/flight-create-orders-document-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-elementary-price-structure.json)
- [JSON Structure](json-structure/flight-create-orders-emergency-contact-structure.json)
- [JSON Structure](json-structure/flight-create-orders-error-400-structure.json)
- [JSON Structure](json-structure/flight-create-orders-error-500-structure.json)
- [JSON Structure](json-structure/flight-create-orders-extended-price-structure.json)
- [JSON Structure](json-structure/flight-create-orders-fee-structure.json)
- [JSON Structure](json-structure/flight-create-orders-fee-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-offer-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-order-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-create-orders-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-create-orders-form-of-identification-structure.json)
- [JSON Structure](json-structure/flight-create-orders-form-of-payment-structure.json)
- [JSON Structure](json-structure/flight-create-orders-general-remark-structure.json)
- [JSON Structure](json-structure/flight-create-orders-general-remark-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-identity-document-structure.json)
- [JSON Structure](json-structure/flight-create-orders-issue-structure.json)
- [JSON Structure](json-structure/flight-create-orders-location-entry-structure.json)
- [JSON Structure](json-structure/flight-create-orders-location-value-structure.json)
- [JSON Structure](json-structure/flight-create-orders-loyalty-program-structure.json)
- [JSON Structure](json-structure/flight-create-orders-name-structure.json)
- [JSON Structure](json-structure/flight-create-orders-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-create-orders-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-create-orders-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-create-orders-other-method-structure.json)
- [JSON Structure](json-structure/flight-create-orders-other-payment-method-structure.json)
- [JSON Structure](json-structure/flight-create-orders-phone-device-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-phone-structure.json)
- [JSON Structure](json-structure/flight-create-orders-price-structure.json)
- [JSON Structure](json-structure/flight-create-orders-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-remarks-structure.json)
- [JSON Structure](json-structure/flight-create-orders-segment-structure.json)
- [JSON Structure](json-structure/flight-create-orders-service-name-structure.json)
- [JSON Structure](json-structure/flight-create-orders-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/flight-create-orders-stakeholder-gender-structure.json)
- [JSON Structure](json-structure/flight-create-orders-stakeholder-structure.json)
- [JSON Structure](json-structure/flight-create-orders-tax-structure.json)
- [JSON Structure](json-structure/flight-create-orders-ticketing-agreement-option-structure.json)
- [JSON Structure](json-structure/flight-create-orders-ticketing-agreement-structure.json)
- [JSON Structure](json-structure/flight-create-orders-travel-class-structure.json)
- [JSON Structure](json-structure/flight-create-orders-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/flight-create-orders-traveler-structure.json)
- [JSON Structure](json-structure/flight-create-orders-traveler-type-structure.json)
- [JSON Structure](json-structure/flight-create-orders-virtual-credit-card-details-structure.json)
- [Example](examples/flight-create-orders-address-example.json)
- [Example](examples/flight-create-orders-air-travel-document-common-example.json)
- [Example](examples/flight-create-orders-aircraft-equipment-example.json)
- [Example](examples/flight-create-orders-airline-remark-example.json)
- [Example](examples/flight-create-orders-allotment-details-example.json)
- [Example](examples/flight-create-orders-associated-record-common-example.json)
- [Example](examples/flight-create-orders-automated-process-common-example.json)
- [Example](examples/flight-create-orders-b2b-wallet-example.json)
- [Example](examples/flight-create-orders-baggage-allowance-example.json)
- [Example](examples/flight-create-orders-base-name-example.json)
- [Example](examples/flight-create-orders-chargeable-seat-example.json)
- [Example](examples/flight-create-orders-co2-emission-example.json)
- [Example](examples/flight-create-orders-collection-meta-link-example.json)
- [Example](examples/flight-create-orders-contact-dictionary-example.json)
- [Example](examples/flight-create-orders-credit-card-common-example.json)
- [Example](examples/flight-create-orders-credit-card-example.json)
- [Example](examples/flight-create-orders-dictionaries-example.json)
- [Example](examples/flight-create-orders-discount-example.json)
- [Example](examples/flight-create-orders-document-example.json)
- [Example](examples/flight-create-orders-elementary-price-example.json)
- [Example](examples/flight-create-orders-emergency-contact-example.json)
- [Example](examples/flight-create-orders-error-400-example.json)
- [Example](examples/flight-create-orders-error-500-example.json)
- [Example](examples/flight-create-orders-extended-price-example.json)
- [Example](examples/flight-create-orders-fee-example.json)
- [Example](examples/flight-create-orders-flight-offer-example.json)
- [Example](examples/flight-create-orders-flight-order-example.json)
- [Example](examples/flight-create-orders-flight-segment-example.json)
- [Example](examples/flight-create-orders-form-of-identification-example.json)
- [Example](examples/flight-create-orders-form-of-payment-example.json)
- [Example](examples/flight-create-orders-general-remark-example.json)
- [Example](examples/flight-create-orders-issue-example.json)
- [Example](examples/flight-create-orders-location-value-example.json)
- [Example](examples/flight-create-orders-loyalty-program-example.json)
- [Example](examples/flight-create-orders-operating-flight-example.json)
- [Example](examples/flight-create-orders-original-flight-end-point-example.json)
- [Example](examples/flight-create-orders-original-flight-stop-example.json)
- [Example](examples/flight-create-orders-other-method-example.json)
- [Example](examples/flight-create-orders-phone-example.json)
- [Example](examples/flight-create-orders-price-example.json)
- [Example](examples/flight-create-orders-remarks-example.json)
- [Example](examples/flight-create-orders-stakeholder-example.json)
- [Example](examples/flight-create-orders-tax-example.json)
- [Example](examples/flight-create-orders-ticketing-agreement-example.json)

### Flight Order Management

Retrieves and cancels existing flight orders. Use after Flight Create Orders to view PNR details or cancel a booking.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Orders
- Booking Management

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)
- [OpenAPI](openapi/amadeus-flight-order-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-order-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-order-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-order-management-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-air-travel-document-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-air-travel-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-airline-remark-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-airline-remark-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-associated-record-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-associated-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-automated-process-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-automated-process-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-automated-process-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-b2b-wallet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-base-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-chargeable-checkd-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-chargeable-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-collection-meta-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-contact-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-contact-purpose-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-credit-card-brand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-credit-card-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-credit-card-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-discount-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-discount-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-document-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-elementary-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-emergency-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-form-of-identification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-form-of-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-general-remark-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-general-remark-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-identity-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-loyalty-program-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-other-method-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-other-payment-method-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-phone-device-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-phone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-remarks-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-stakeholder-gender-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-stakeholder-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-ticketing-agreement-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-ticketing-agreement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-traveler-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-order-management-virtual-credit-card-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-order-management-additional-service-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-address-structure.json)
- [JSON Structure](json-structure/flight-order-management-air-travel-document-common-structure.json)
- [JSON Structure](json-structure/flight-order-management-air-travel-document-structure.json)
- [JSON Structure](json-structure/flight-order-management-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-order-management-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-order-management-airline-remark-structure.json)
- [JSON Structure](json-structure/flight-order-management-airline-remark-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-allotment-details-structure.json)
- [JSON Structure](json-structure/flight-order-management-associated-record-common-structure.json)
- [JSON Structure](json-structure/flight-order-management-associated-record-structure.json)
- [JSON Structure](json-structure/flight-order-management-automated-process-code-structure.json)
- [JSON Structure](json-structure/flight-order-management-automated-process-common-structure.json)
- [JSON Structure](json-structure/flight-order-management-automated-process-structure.json)
- [JSON Structure](json-structure/flight-order-management-b2b-wallet-structure.json)
- [JSON Structure](json-structure/flight-order-management-baggage-allowance-structure.json)
- [JSON Structure](json-structure/flight-order-management-base-name-structure.json)
- [JSON Structure](json-structure/flight-order-management-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-order-management-chargeable-checkd-bags-structure.json)
- [JSON Structure](json-structure/flight-order-management-chargeable-seat-structure.json)
- [JSON Structure](json-structure/flight-order-management-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-order-management-collection-meta-link-structure.json)
- [JSON Structure](json-structure/flight-order-management-contact-dictionary-structure.json)
- [JSON Structure](json-structure/flight-order-management-contact-purpose-structure.json)
- [JSON Structure](json-structure/flight-order-management-contact-structure.json)
- [JSON Structure](json-structure/flight-order-management-credit-card-brand-structure.json)
- [JSON Structure](json-structure/flight-order-management-credit-card-common-structure.json)
- [JSON Structure](json-structure/flight-order-management-credit-card-structure.json)
- [JSON Structure](json-structure/flight-order-management-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-order-management-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-order-management-discount-structure.json)
- [JSON Structure](json-structure/flight-order-management-discount-traveler-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-discount-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-document-structure.json)
- [JSON Structure](json-structure/flight-order-management-document-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-elementary-price-structure.json)
- [JSON Structure](json-structure/flight-order-management-emergency-contact-structure.json)
- [JSON Structure](json-structure/flight-order-management-error-400-structure.json)
- [JSON Structure](json-structure/flight-order-management-error-404-structure.json)
- [JSON Structure](json-structure/flight-order-management-error-500-structure.json)
- [JSON Structure](json-structure/flight-order-management-extended-price-structure.json)
- [JSON Structure](json-structure/flight-order-management-fee-structure.json)
- [JSON Structure](json-structure/flight-order-management-fee-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-offer-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-order-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-order-management-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-order-management-form-of-identification-structure.json)
- [JSON Structure](json-structure/flight-order-management-form-of-payment-structure.json)
- [JSON Structure](json-structure/flight-order-management-general-remark-structure.json)
- [JSON Structure](json-structure/flight-order-management-general-remark-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-identity-document-structure.json)
- [JSON Structure](json-structure/flight-order-management-issue-structure.json)
- [JSON Structure](json-structure/flight-order-management-location-entry-structure.json)
- [JSON Structure](json-structure/flight-order-management-location-value-structure.json)
- [JSON Structure](json-structure/flight-order-management-loyalty-program-structure.json)
- [JSON Structure](json-structure/flight-order-management-name-structure.json)
- [JSON Structure](json-structure/flight-order-management-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-order-management-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-order-management-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-order-management-other-method-structure.json)
- [JSON Structure](json-structure/flight-order-management-other-payment-method-structure.json)
- [JSON Structure](json-structure/flight-order-management-phone-device-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-phone-structure.json)
- [JSON Structure](json-structure/flight-order-management-price-structure.json)
- [JSON Structure](json-structure/flight-order-management-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-remarks-structure.json)
- [JSON Structure](json-structure/flight-order-management-segment-structure.json)
- [JSON Structure](json-structure/flight-order-management-service-name-structure.json)
- [JSON Structure](json-structure/flight-order-management-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/flight-order-management-stakeholder-gender-structure.json)
- [JSON Structure](json-structure/flight-order-management-stakeholder-structure.json)
- [JSON Structure](json-structure/flight-order-management-tax-structure.json)
- [JSON Structure](json-structure/flight-order-management-ticketing-agreement-option-structure.json)
- [JSON Structure](json-structure/flight-order-management-ticketing-agreement-structure.json)
- [JSON Structure](json-structure/flight-order-management-travel-class-structure.json)
- [JSON Structure](json-structure/flight-order-management-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/flight-order-management-traveler-structure.json)
- [JSON Structure](json-structure/flight-order-management-traveler-type-structure.json)
- [JSON Structure](json-structure/flight-order-management-virtual-credit-card-details-structure.json)
- [Example](examples/flight-order-management-address-example.json)
- [Example](examples/flight-order-management-air-travel-document-common-example.json)
- [Example](examples/flight-order-management-aircraft-equipment-example.json)
- [Example](examples/flight-order-management-airline-remark-example.json)
- [Example](examples/flight-order-management-allotment-details-example.json)
- [Example](examples/flight-order-management-associated-record-common-example.json)
- [Example](examples/flight-order-management-automated-process-common-example.json)
- [Example](examples/flight-order-management-b2b-wallet-example.json)
- [Example](examples/flight-order-management-baggage-allowance-example.json)
- [Example](examples/flight-order-management-base-name-example.json)
- [Example](examples/flight-order-management-chargeable-seat-example.json)
- [Example](examples/flight-order-management-co2-emission-example.json)
- [Example](examples/flight-order-management-collection-meta-link-example.json)
- [Example](examples/flight-order-management-contact-dictionary-example.json)
- [Example](examples/flight-order-management-credit-card-common-example.json)
- [Example](examples/flight-order-management-credit-card-example.json)
- [Example](examples/flight-order-management-dictionaries-example.json)
- [Example](examples/flight-order-management-discount-example.json)
- [Example](examples/flight-order-management-document-example.json)
- [Example](examples/flight-order-management-elementary-price-example.json)
- [Example](examples/flight-order-management-emergency-contact-example.json)
- [Example](examples/flight-order-management-error-400-example.json)
- [Example](examples/flight-order-management-error-404-example.json)
- [Example](examples/flight-order-management-error-500-example.json)
- [Example](examples/flight-order-management-extended-price-example.json)
- [Example](examples/flight-order-management-fee-example.json)
- [Example](examples/flight-order-management-flight-offer-example.json)
- [Example](examples/flight-order-management-flight-order-example.json)
- [Example](examples/flight-order-management-flight-segment-example.json)
- [Example](examples/flight-order-management-form-of-identification-example.json)
- [Example](examples/flight-order-management-form-of-payment-example.json)
- [Example](examples/flight-order-management-general-remark-example.json)
- [Example](examples/flight-order-management-issue-example.json)
- [Example](examples/flight-order-management-location-value-example.json)
- [Example](examples/flight-order-management-loyalty-program-example.json)
- [Example](examples/flight-order-management-operating-flight-example.json)
- [Example](examples/flight-order-management-original-flight-end-point-example.json)
- [Example](examples/flight-order-management-original-flight-stop-example.json)
- [Example](examples/flight-order-management-other-method-example.json)
- [Example](examples/flight-order-management-phone-example.json)
- [Example](examples/flight-order-management-price-example.json)
- [Example](examples/flight-order-management-remarks-example.json)
- [Example](examples/flight-order-management-stakeholder-example.json)
- [Example](examples/flight-order-management-tax-example.json)
- [Example](examples/flight-order-management-ticketing-agreement-example.json)

### Flight Availabilities Search

Searches real-time flight availability and inventory between origin and destination for a given date, returning bookable flight segments with classes of service.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Availability
- Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-availabilities-search)
- [OpenAPI](openapi/amadeus-flight-availabilities-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-availabilities-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-availabilities-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-availabilities-search-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-availability-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-cabin-restriction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-carrier-restrictions-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-collection-meta-avail-search-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-connection-restriction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-date-time-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-extended-origin-destination-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-extended-search-criteria-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-extended-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-availability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-filters-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-get-flight-availabilities-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-origin-destination-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-search-criteria-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-tour-allotment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-traveler-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-availabilities-search-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-availabilities-search-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-allotment-details-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-availability-class-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-cabin-restriction-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-carrier-restrictions-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-collection-meta-avail-search-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-connection-restriction-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-date-time-type-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-error-400-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-error-500-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-extended-origin-destination-light-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-extended-search-criteria-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-extended-segment-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-availability-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-filters-light-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-get-flight-availabilities-query-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-issue-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-location-entry-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-location-value-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-origin-destination-light-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-search-criteria-light-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-segment-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-tour-allotment-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-travel-class-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-traveler-info-structure.json)
- [JSON Structure](json-structure/flight-availabilities-search-traveler-type-structure.json)
- [Example](examples/flight-availabilities-search-aircraft-equipment-example.json)
- [Example](examples/flight-availabilities-search-allotment-details-example.json)
- [Example](examples/flight-availabilities-search-availability-class-example.json)
- [Example](examples/flight-availabilities-search-cabin-restriction-example.json)
- [Example](examples/flight-availabilities-search-carrier-restrictions-example.json)
- [Example](examples/flight-availabilities-search-co2-emission-example.json)
- [Example](examples/flight-availabilities-search-collection-meta-avail-search-example.json)
- [Example](examples/flight-availabilities-search-connection-restriction-example.json)
- [Example](examples/flight-availabilities-search-date-time-type-example.json)
- [Example](examples/flight-availabilities-search-dictionaries-example.json)
- [Example](examples/flight-availabilities-search-error-400-example.json)
- [Example](examples/flight-availabilities-search-error-500-example.json)
- [Example](examples/flight-availabilities-search-flight-availability-example.json)
- [Example](examples/flight-availabilities-search-flight-filters-light-example.json)
- [Example](examples/flight-availabilities-search-flight-segment-example.json)
- [Example](examples/flight-availabilities-search-get-flight-availabilities-query-example.json)
- [Example](examples/flight-availabilities-search-issue-example.json)
- [Example](examples/flight-availabilities-search-location-value-example.json)
- [Example](examples/flight-availabilities-search-operating-flight-example.json)
- [Example](examples/flight-availabilities-search-origin-destination-light-example.json)
- [Example](examples/flight-availabilities-search-original-flight-end-point-example.json)
- [Example](examples/flight-availabilities-search-original-flight-stop-example.json)
- [Example](examples/flight-availabilities-search-search-criteria-light-example.json)
- [Example](examples/flight-availabilities-search-traveler-info-example.json)

### SeatMap Display

Returns the seat map for a specific flight, including available, occupied, and reserved seats with characteristics (window, aisle, exit row, extra legroom).

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Seats
- Ancillaries

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/seatmap-display)
- [OpenAPI](openapi/amadeus-seatmap-display-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-seatmap-display.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-seatmap-display.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/seatmap-display-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-beverage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-entertainment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-food-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-power-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-cabin-amenities-wifi-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-amenity-media-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-amenity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-amenity-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-available-seats-counter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-base-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-contact-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-contact-purpose-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-coordinates-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-deck-configuration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-deck-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-discount-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-discount-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-document-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-elementary-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-emergency-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-facility-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-facility-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-fare-rules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-identity-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-loyalty-program-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-phone-device-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-phone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-qualified-free-text-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-seat-characteristic-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-seat-map-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-seatmap-traveler-pricing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-stakeholder-gender-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-stakeholder-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-term-and-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-traveler-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/seatmap-display-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/seatmap-display-additional-service-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-address-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-beverage-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-entertainment-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-food-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-power-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-cabin-amenities-wifi-structure.json)
- [JSON Structure](json-structure/seatmap-display-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/seatmap-display-amenity-media-structure.json)
- [JSON Structure](json-structure/seatmap-display-amenity-seat-structure.json)
- [JSON Structure](json-structure/seatmap-display-amenity-structure.json)
- [JSON Structure](json-structure/seatmap-display-available-seats-counter-structure.json)
- [JSON Structure](json-structure/seatmap-display-baggage-allowance-structure.json)
- [JSON Structure](json-structure/seatmap-display-base-name-structure.json)
- [JSON Structure](json-structure/seatmap-display-co2-emission-structure.json)
- [JSON Structure](json-structure/seatmap-display-collection-meta-structure.json)
- [JSON Structure](json-structure/seatmap-display-contact-dictionary-structure.json)
- [JSON Structure](json-structure/seatmap-display-contact-purpose-structure.json)
- [JSON Structure](json-structure/seatmap-display-contact-structure.json)
- [JSON Structure](json-structure/seatmap-display-coordinates-structure.json)
- [JSON Structure](json-structure/seatmap-display-deck-configuration-structure.json)
- [JSON Structure](json-structure/seatmap-display-deck-structure.json)
- [JSON Structure](json-structure/seatmap-display-discount-structure.json)
- [JSON Structure](json-structure/seatmap-display-discount-traveler-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-discount-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-document-structure.json)
- [JSON Structure](json-structure/seatmap-display-document-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-elementary-price-structure.json)
- [JSON Structure](json-structure/seatmap-display-emergency-contact-structure.json)
- [JSON Structure](json-structure/seatmap-display-error-400-structure.json)
- [JSON Structure](json-structure/seatmap-display-error-404-structure.json)
- [JSON Structure](json-structure/seatmap-display-error-500-structure.json)
- [JSON Structure](json-structure/seatmap-display-extended-price-structure.json)
- [JSON Structure](json-structure/seatmap-display-facility-dictionary-structure.json)
- [JSON Structure](json-structure/seatmap-display-facility-structure.json)
- [JSON Structure](json-structure/seatmap-display-fare-rules-structure.json)
- [JSON Structure](json-structure/seatmap-display-fee-structure.json)
- [JSON Structure](json-structure/seatmap-display-fee-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-flight-end-point-structure.json)
- [JSON Structure](json-structure/seatmap-display-flight-offer-source-structure.json)
- [JSON Structure](json-structure/seatmap-display-flight-offer-structure.json)
- [JSON Structure](json-structure/seatmap-display-flight-segment-structure.json)
- [JSON Structure](json-structure/seatmap-display-flight-stop-structure.json)
- [JSON Structure](json-structure/seatmap-display-identity-document-structure.json)
- [JSON Structure](json-structure/seatmap-display-issue-structure.json)
- [JSON Structure](json-structure/seatmap-display-link-structure.json)
- [JSON Structure](json-structure/seatmap-display-location-entry-structure.json)
- [JSON Structure](json-structure/seatmap-display-location-value-structure.json)
- [JSON Structure](json-structure/seatmap-display-loyalty-program-structure.json)
- [JSON Structure](json-structure/seatmap-display-name-structure.json)
- [JSON Structure](json-structure/seatmap-display-operating-flight-structure.json)
- [JSON Structure](json-structure/seatmap-display-phone-device-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-phone-structure.json)
- [JSON Structure](json-structure/seatmap-display-price-structure.json)
- [JSON Structure](json-structure/seatmap-display-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/seatmap-display-qualified-free-text-structure.json)
- [JSON Structure](json-structure/seatmap-display-seat-characteristic-dictionary-structure.json)
- [JSON Structure](json-structure/seatmap-display-seat-map-structure.json)
- [JSON Structure](json-structure/seatmap-display-seat-structure.json)
- [JSON Structure](json-structure/seatmap-display-seatmap-traveler-pricing-structure.json)
- [JSON Structure](json-structure/seatmap-display-segment-structure.json)
- [JSON Structure](json-structure/seatmap-display-service-name-structure.json)
- [JSON Structure](json-structure/seatmap-display-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/seatmap-display-stakeholder-gender-structure.json)
- [JSON Structure](json-structure/seatmap-display-stakeholder-structure.json)
- [JSON Structure](json-structure/seatmap-display-tax-structure.json)
- [JSON Structure](json-structure/seatmap-display-term-and-condition-structure.json)
- [JSON Structure](json-structure/seatmap-display-travel-class-structure.json)
- [JSON Structure](json-structure/seatmap-display-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/seatmap-display-traveler-structure.json)
- [JSON Structure](json-structure/seatmap-display-traveler-type-structure.json)
- [Example](examples/seatmap-display-address-example.json)
- [Example](examples/seatmap-display-aircraft-cabin-amenities-example.json)
- [Example](examples/seatmap-display-aircraft-equipment-example.json)
- [Example](examples/seatmap-display-amenity-example.json)
- [Example](examples/seatmap-display-amenity-media-example.json)
- [Example](examples/seatmap-display-amenity-seat-example.json)
- [Example](examples/seatmap-display-available-seats-counter-example.json)
- [Example](examples/seatmap-display-baggage-allowance-example.json)
- [Example](examples/seatmap-display-base-name-example.json)
- [Example](examples/seatmap-display-co2-emission-example.json)
- [Example](examples/seatmap-display-collection-meta-example.json)
- [Example](examples/seatmap-display-contact-dictionary-example.json)
- [Example](examples/seatmap-display-coordinates-example.json)
- [Example](examples/seatmap-display-deck-configuration-example.json)
- [Example](examples/seatmap-display-deck-example.json)
- [Example](examples/seatmap-display-discount-example.json)
- [Example](examples/seatmap-display-document-example.json)
- [Example](examples/seatmap-display-elementary-price-example.json)
- [Example](examples/seatmap-display-emergency-contact-example.json)
- [Example](examples/seatmap-display-error-400-example.json)
- [Example](examples/seatmap-display-error-404-example.json)
- [Example](examples/seatmap-display-error-500-example.json)
- [Example](examples/seatmap-display-extended-price-example.json)
- [Example](examples/seatmap-display-facility-dictionary-example.json)
- [Example](examples/seatmap-display-facility-example.json)
- [Example](examples/seatmap-display-fare-rules-example.json)
- [Example](examples/seatmap-display-fee-example.json)
- [Example](examples/seatmap-display-flight-end-point-example.json)
- [Example](examples/seatmap-display-flight-offer-example.json)
- [Example](examples/seatmap-display-flight-segment-example.json)
- [Example](examples/seatmap-display-flight-stop-example.json)
- [Example](examples/seatmap-display-issue-example.json)
- [Example](examples/seatmap-display-link-example.json)
- [Example](examples/seatmap-display-location-value-example.json)
- [Example](examples/seatmap-display-loyalty-program-example.json)
- [Example](examples/seatmap-display-operating-flight-example.json)
- [Example](examples/seatmap-display-phone-example.json)
- [Example](examples/seatmap-display-price-example.json)
- [Example](examples/seatmap-display-qualified-free-text-example.json)
- [Example](examples/seatmap-display-seat-characteristic-dictionary-example.json)
- [Example](examples/seatmap-display-seat-example.json)
- [Example](examples/seatmap-display-seat-map-example.json)
- [Example](examples/seatmap-display-seatmap-traveler-pricing-example.json)
- [Example](examples/seatmap-display-stakeholder-example.json)
- [Example](examples/seatmap-display-tax-example.json)
- [Example](examples/seatmap-display-term-and-condition-example.json)

### Branded Fares Upsell

Returns branded fares (e.g. Economy Light, Economy Flex, Business Lite) and their attributes for a given flight offer to surface upsell options to travelers.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Fares
- Upsell

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)
- [OpenAPI](openapi/amadeus-branded-fares-upsell-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-branded-fares-upsell.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-branded-fares-upsell.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/branded-fares-upsell-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-allotment-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-chargeable-checkd-bags-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-chargeable-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-collection-meta-upsell-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-offer-upsell-in-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-payment-brand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/branded-fares-upsell-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/branded-fares-upsell-additional-service-type-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-aircraft-entry-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-allotment-details-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-baggage-allowance-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-carrier-entry-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-chargeable-checkd-bags-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-chargeable-seat-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-co2-emission-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-collection-meta-upsell-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-currency-entry-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-dictionaries-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-error-400-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-error-500-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-extended-price-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-fee-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-fee-type-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-end-point-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-offer-source-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-offer-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-offer-upsell-in-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-segment-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-flight-stop-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-issue-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-location-entry-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-location-value-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-operating-flight-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-original-flight-stop-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-payment-brand-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-payment-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-price-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-segment-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-service-name-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-tax-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-travel-class-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/branded-fares-upsell-traveler-type-structure.json)
- [Example](examples/branded-fares-upsell-aircraft-equipment-example.json)
- [Example](examples/branded-fares-upsell-allotment-details-example.json)
- [Example](examples/branded-fares-upsell-baggage-allowance-example.json)
- [Example](examples/branded-fares-upsell-chargeable-seat-example.json)
- [Example](examples/branded-fares-upsell-co2-emission-example.json)
- [Example](examples/branded-fares-upsell-collection-meta-upsell-example.json)
- [Example](examples/branded-fares-upsell-dictionaries-example.json)
- [Example](examples/branded-fares-upsell-error-400-example.json)
- [Example](examples/branded-fares-upsell-error-500-example.json)
- [Example](examples/branded-fares-upsell-extended-price-example.json)
- [Example](examples/branded-fares-upsell-fee-example.json)
- [Example](examples/branded-fares-upsell-flight-offer-example.json)
- [Example](examples/branded-fares-upsell-flight-offer-upsell-in-example.json)
- [Example](examples/branded-fares-upsell-flight-segment-example.json)
- [Example](examples/branded-fares-upsell-issue-example.json)
- [Example](examples/branded-fares-upsell-location-value-example.json)
- [Example](examples/branded-fares-upsell-operating-flight-example.json)
- [Example](examples/branded-fares-upsell-original-flight-end-point-example.json)
- [Example](examples/branded-fares-upsell-original-flight-stop-example.json)
- [Example](examples/branded-fares-upsell-payment-example.json)
- [Example](examples/branded-fares-upsell-price-example.json)
- [Example](examples/branded-fares-upsell-tax-example.json)

### Flight Check-in Links

Returns direct check-in URLs for a given airline (IATA code) and language, deep-linking travelers into the carrier's check-in flow.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Flights
- Check-in
- Airlines

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-checkin-links)
- [OpenAPI](openapi/amadeus-flight-checkin-links-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-checkin-links.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-checkin-links.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-checkin-links-checkin-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-checkin-links-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-checkin-links-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-checkin-links-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-checkin-links-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-checkin-links-parameter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-checkin-links-checkin-link-structure.json)
- [JSON Structure](json-structure/flight-checkin-links-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-checkin-links-error-400-structure.json)
- [JSON Structure](json-structure/flight-checkin-links-error-500-structure.json)
- [JSON Structure](json-structure/flight-checkin-links-issue-structure.json)
- [JSON Structure](json-structure/flight-checkin-links-parameter-structure.json)
- [Example](examples/flight-checkin-links-checkin-link-example.json)
- [Example](examples/flight-checkin-links-collection-meta-example.json)
- [Example](examples/flight-checkin-links-error-400-example.json)
- [Example](examples/flight-checkin-links-error-500-example.json)
- [Example](examples/flight-checkin-links-issue-example.json)
- [Example](examples/flight-checkin-links-parameter-example.json)

### On Demand Flight Status

Returns the real-time status (scheduled, delayed, departed, landed) and detailed itinerary of a specific flight on a specific date.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Flights
- Status
- Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/on-demand-flight-status)
- [OpenAPI](openapi/amadeus-on-demand-flight-status-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-on-demand-flight-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-on-demand-flight-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/on-demand-flight-status-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-arrival-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-dated-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-delay-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-departure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-error-401-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-flight-designator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-flight-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-gate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-leg-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-partnership-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-terminal-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/on-demand-flight-status-timing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/on-demand-flight-status-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-arrival-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-collection-meta-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-dated-flight-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-delay-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-departure-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-error-400-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-error-401-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-error-500-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-flight-designator-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-flight-point-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-gate-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-issue-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-leg-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-partnership-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-segment-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-terminal-structure.json)
- [JSON Structure](json-structure/on-demand-flight-status-timing-structure.json)
- [Example](examples/on-demand-flight-status-aircraft-equipment-example.json)
- [Example](examples/on-demand-flight-status-arrival-example.json)
- [Example](examples/on-demand-flight-status-collection-meta-example.json)
- [Example](examples/on-demand-flight-status-dated-flight-example.json)
- [Example](examples/on-demand-flight-status-delay-example.json)
- [Example](examples/on-demand-flight-status-departure-example.json)
- [Example](examples/on-demand-flight-status-error-400-example.json)
- [Example](examples/on-demand-flight-status-error-401-example.json)
- [Example](examples/on-demand-flight-status-error-500-example.json)
- [Example](examples/on-demand-flight-status-flight-designator-example.json)
- [Example](examples/on-demand-flight-status-flight-point-example.json)
- [Example](examples/on-demand-flight-status-gate-example.json)
- [Example](examples/on-demand-flight-status-issue-example.json)
- [Example](examples/on-demand-flight-status-leg-example.json)
- [Example](examples/on-demand-flight-status-partnership-example.json)
- [Example](examples/on-demand-flight-status-segment-example.json)
- [Example](examples/on-demand-flight-status-terminal-example.json)
- [Example](examples/on-demand-flight-status-timing-example.json)

### Flight Inspiration Search

Suggests cheap destinations from a given origin within a budget and date range, ideal for "where can I go for X dollars?" experiences.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Inspiration
- Discovery

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search)
- [OpenAPI](openapi/amadeus-flight-inspiration-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-inspiration-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-inspiration-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-inspiration-search-currency-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-defaults-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-flight-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-flight-destinations-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-location-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-inspiration-search-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-inspiration-search-currency-dictionary-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-defaults-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-error-400-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-error-404-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-error-500-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-flight-destination-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-flight-destinations-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-issue-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-links-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-location-dictionary-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-location-value-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-meta-structure.json)
- [JSON Structure](json-structure/flight-inspiration-search-price-structure.json)
- [Example](examples/flight-inspiration-search-defaults-example.json)
- [Example](examples/flight-inspiration-search-dictionaries-example.json)
- [Example](examples/flight-inspiration-search-error-400-example.json)
- [Example](examples/flight-inspiration-search-error-404-example.json)
- [Example](examples/flight-inspiration-search-error-500-example.json)
- [Example](examples/flight-inspiration-search-flight-destination-example.json)
- [Example](examples/flight-inspiration-search-flight-destinations-example.json)
- [Example](examples/flight-inspiration-search-issue-example.json)
- [Example](examples/flight-inspiration-search-links-example.json)
- [Example](examples/flight-inspiration-search-location-value-example.json)
- [Example](examples/flight-inspiration-search-meta-example.json)
- [Example](examples/flight-inspiration-search-price-example.json)

### Flight Cheapest Date Search

Returns the cheapest dates to fly between two cities over a given date range to help travelers find the best fare windows.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Pricing
- Discovery

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-cheapest-date-search)
- [OpenAPI](openapi/amadeus-flight-cheapest-date-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-cheapest-date-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-cheapest-date-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-cheapest-date-search-currency-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-defaults-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-flight-date-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-flight-dates-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-location-dictionary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-cheapest-date-search-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-cheapest-date-search-currency-dictionary-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-defaults-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-error-400-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-error-404-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-error-500-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-flight-date-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-flight-dates-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-issue-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-links-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-location-dictionary-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-location-value-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-meta-structure.json)
- [JSON Structure](json-structure/flight-cheapest-date-search-price-structure.json)
- [Example](examples/flight-cheapest-date-search-defaults-example.json)
- [Example](examples/flight-cheapest-date-search-dictionaries-example.json)
- [Example](examples/flight-cheapest-date-search-error-400-example.json)
- [Example](examples/flight-cheapest-date-search-error-404-example.json)
- [Example](examples/flight-cheapest-date-search-error-500-example.json)
- [Example](examples/flight-cheapest-date-search-flight-date-example.json)
- [Example](examples/flight-cheapest-date-search-flight-dates-example.json)
- [Example](examples/flight-cheapest-date-search-issue-example.json)
- [Example](examples/flight-cheapest-date-search-links-example.json)
- [Example](examples/flight-cheapest-date-search-location-value-example.json)
- [Example](examples/flight-cheapest-date-search-meta-example.json)
- [Example](examples/flight-cheapest-date-search-price-example.json)

### Flight Price Analysis

Compares a current flight price to historical prices for the same route and returns a quartile-ranked "price metric" (FIRST, SECOND, THIRD, FOURTH) signalling whether the offer is a good deal.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Pricing
- Analytics
- Artificial Intelligence

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-price-analysis)
- [OpenAPI](openapi/amadeus-flight-price-analysis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-price-analysis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-price-analysis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-price-analysis-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-price-analysis-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-price-analysis-itinerary-price-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-price-analysis-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-price-analysis-error-400-structure.json)
- [JSON Structure](json-structure/flight-price-analysis-error-500-structure.json)
- [JSON Structure](json-structure/flight-price-analysis-itinerary-price-metric-structure.json)
- [JSON Structure](json-structure/flight-price-analysis-warning-structure.json)
- [Example](examples/flight-price-analysis-error-400-example.json)
- [Example](examples/flight-price-analysis-error-500-example.json)
- [Example](examples/flight-price-analysis-itinerary-price-metric-example.json)
- [Example](examples/flight-price-analysis-warning-example.json)

### Flight Choice Prediction

Predicts the probability that a given flight offer will be chosen by a traveler, helping merchandising and ranking decisions.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Flights
- Artificial Intelligence
- Prediction
- Personalization

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-choice-prediction)
- [OpenAPI](openapi/amadeus-flight-choice-prediction-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-choice-prediction.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-choice-prediction.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-choice-prediction-additional-service-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-aircraft-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-aircraft-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-baggage-allowance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-carrier-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-co2-emission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-collection-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-currency-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-dictionaries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-extended-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-fare-rules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-fee-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-offer-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-offers-search-reply-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-location-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-location-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-operating-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-original-flight-end-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-original-flight-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-pricing-options-fare-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-service-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-slice-dice-indicator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-term-and-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-travel-class-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-traveler-pricing-fare-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-choice-prediction-traveler-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-choice-prediction-additional-service-type-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-aircraft-entry-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-aircraft-equipment-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-baggage-allowance-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-carrier-entry-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-co2-emission-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-collection-links-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-currency-entry-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-dictionaries-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-error-400-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-error-500-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-extended-price-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-fare-rules-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-fee-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-fee-type-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-offer-source-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-offer-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-offers-search-reply-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-segment-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-issue-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-location-entry-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-location-value-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-operating-flight-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-original-flight-end-point-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-original-flight-stop-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-price-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-pricing-options-fare-type-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-segment-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-service-name-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-slice-dice-indicator-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-tax-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-term-and-condition-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-travel-class-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-traveler-pricing-fare-option-structure.json)
- [JSON Structure](json-structure/flight-choice-prediction-traveler-type-structure.json)
- [Example](examples/flight-choice-prediction-aircraft-equipment-example.json)
- [Example](examples/flight-choice-prediction-baggage-allowance-example.json)
- [Example](examples/flight-choice-prediction-co2-emission-example.json)
- [Example](examples/flight-choice-prediction-collection-links-example.json)
- [Example](examples/flight-choice-prediction-collection-meta-example.json)
- [Example](examples/flight-choice-prediction-dictionaries-example.json)
- [Example](examples/flight-choice-prediction-error-400-example.json)
- [Example](examples/flight-choice-prediction-error-500-example.json)
- [Example](examples/flight-choice-prediction-extended-price-example.json)
- [Example](examples/flight-choice-prediction-fare-rules-example.json)
- [Example](examples/flight-choice-prediction-fee-example.json)
- [Example](examples/flight-choice-prediction-flight-offer-example.json)
- [Example](examples/flight-choice-prediction-flight-offers-search-reply-example.json)
- [Example](examples/flight-choice-prediction-flight-segment-example.json)
- [Example](examples/flight-choice-prediction-issue-example.json)
- [Example](examples/flight-choice-prediction-location-value-example.json)
- [Example](examples/flight-choice-prediction-operating-flight-example.json)
- [Example](examples/flight-choice-prediction-original-flight-end-point-example.json)
- [Example](examples/flight-choice-prediction-original-flight-stop-example.json)
- [Example](examples/flight-choice-prediction-price-example.json)
- [Example](examples/flight-choice-prediction-tax-example.json)
- [Example](examples/flight-choice-prediction-term-and-condition-example.json)

### Flight Delay Prediction

Predicts the probability that a flight will be delayed by 30 minutes, 60 minutes, 120 minutes, or more, based on historical operational data.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Artificial Intelligence
- Prediction
- Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-delay-prediction)
- [OpenAPI](openapi/amadeus-flight-delay-prediction-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-delay-prediction.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-delay-prediction.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-delay-prediction-collection-meta-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-delay-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-prediction-result-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-delay-prediction-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-delay-prediction-collection-meta-link-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-delay-prediction-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-error-400-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-error-500-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-issue-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-prediction-result-type-structure.json)
- [JSON Structure](json-structure/flight-delay-prediction-prediction-structure.json)
- [Example](examples/flight-delay-prediction-collection-meta-link-example.json)
- [Example](examples/flight-delay-prediction-delay-prediction-example.json)
- [Example](examples/flight-delay-prediction-error-400-example.json)
- [Example](examples/flight-delay-prediction-error-500-example.json)
- [Example](examples/flight-delay-prediction-issue-example.json)
- [Example](examples/flight-delay-prediction-prediction-example.json)

### Airport On-Time Performance

Returns the on-time performance score for an airport on a specific date, useful for operational and route planning analytics.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Airports
- Analytics
- Operations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-on-time-performance)
- [OpenAPI](openapi/amadeus-airport-on-time-performance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airport-on-time-performance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airport-on-time-performance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airport-on-time-performance-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-on-time-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-prediction-result-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-on-time-performance-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airport-on-time-performance-error-400-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-error-500-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-issue-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-links-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-meta-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-on-time-prediction-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-prediction-result-type-structure.json)
- [JSON Structure](json-structure/airport-on-time-performance-prediction-structure.json)
- [Example](examples/airport-on-time-performance-error-400-example.json)
- [Example](examples/airport-on-time-performance-error-500-example.json)
- [Example](examples/airport-on-time-performance-issue-example.json)
- [Example](examples/airport-on-time-performance-links-example.json)
- [Example](examples/airport-on-time-performance-meta-example.json)
- [Example](examples/airport-on-time-performance-on-time-prediction-example.json)
- [Example](examples/airport-on-time-performance-prediction-example.json)

### Airport Routes

Returns all destinations served from a given origin airport, with carriers operating each route.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Airports
- Routes
- Network

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-routes)
- [OpenAPI](openapi/amadeus-airport-routes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airport-routes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airport-routes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airport-routes-locations-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-routes-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-routes-response-airport-routes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-routes-response-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-routes-warnings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airport-routes-locations-structure.json)
- [JSON Structure](json-structure/airport-routes-meta-structure.json)
- [JSON Structure](json-structure/airport-routes-response-airport-routes-structure.json)
- [JSON Structure](json-structure/airport-routes-response-error-structure.json)
- [JSON Structure](json-structure/airport-routes-warnings-structure.json)
- [Example](examples/airport-routes-locations-example.json)
- [Example](examples/airport-routes-meta-example.json)
- [Example](examples/airport-routes-response-airport-routes-example.json)
- [Example](examples/airport-routes-response-error-example.json)
- [Example](examples/airport-routes-warnings-example.json)

### Airline Routes

Returns all routes operated by a given airline (IATA code), enabling network and competitive analysis.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Flights
- Airlines
- Routes
- Network

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-routes)
- [OpenAPI](openapi/amadeus-airline-routes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airline-routes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airline-routes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airline-routes-locations-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-routes-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-routes-response-airline-routes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-routes-response-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-routes-warnings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airline-routes-locations-structure.json)
- [JSON Structure](json-structure/airline-routes-meta-structure.json)
- [JSON Structure](json-structure/airline-routes-response-airline-routes-structure.json)
- [JSON Structure](json-structure/airline-routes-response-error-structure.json)
- [JSON Structure](json-structure/airline-routes-warnings-structure.json)
- [Example](examples/airline-routes-locations-example.json)
- [Example](examples/airline-routes-meta-example.json)
- [Example](examples/airline-routes-response-airline-routes-example.json)
- [Example](examples/airline-routes-response-error-example.json)
- [Example](examples/airline-routes-warnings-example.json)

### Airport Nearest Relevant

Returns the most relevant nearby airports for a given latitude/longitude, ranked by traffic volume.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Airports
- Geolocation
- Reference Data

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-nearest-relevant)
- [OpenAPI](openapi/amadeus-airport-nearest-relevant-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airport-nearest-relevant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airport-nearest-relevant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airport-nearest-relevant-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-distance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-flights-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-geo-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-nearest-relevant-travelers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airport-nearest-relevant-address-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-analytics-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-collection-meta-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-distance-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-error-400-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-error-500-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-flights-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-geo-code-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-issue-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-location-structure.json)
- [JSON Structure](json-structure/airport-nearest-relevant-travelers-structure.json)
- [Example](examples/airport-nearest-relevant-address-example.json)
- [Example](examples/airport-nearest-relevant-analytics-example.json)
- [Example](examples/airport-nearest-relevant-collection-meta-example.json)
- [Example](examples/airport-nearest-relevant-distance-example.json)
- [Example](examples/airport-nearest-relevant-error-400-example.json)
- [Example](examples/airport-nearest-relevant-error-500-example.json)
- [Example](examples/airport-nearest-relevant-flights-example.json)
- [Example](examples/airport-nearest-relevant-geo-code-example.json)
- [Example](examples/airport-nearest-relevant-issue-example.json)
- [Example](examples/airport-nearest-relevant-location-example.json)
- [Example](examples/airport-nearest-relevant-travelers-example.json)

### Airport and City Search

Searches airports and cities by keyword and returns IATA codes, names, geocoordinates, and country information. Backbone of any travel search UI autocomplete.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Airports
- Cities
- Reference Data
- Autocomplete

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airport-and-city-search)
- [OpenAPI](openapi/amadeus-airport-city-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airport-city-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airport-city-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airport-city-search-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-distance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-geo-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airport-city-search-travelers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airport-city-search-address-structure.json)
- [JSON Structure](json-structure/airport-city-search-analytics-structure.json)
- [JSON Structure](json-structure/airport-city-search-collection-meta-structure.json)
- [JSON Structure](json-structure/airport-city-search-distance-structure.json)
- [JSON Structure](json-structure/airport-city-search-error-400-structure.json)
- [JSON Structure](json-structure/airport-city-search-error-404-structure.json)
- [JSON Structure](json-structure/airport-city-search-error-500-structure.json)
- [JSON Structure](json-structure/airport-city-search-geo-code-structure.json)
- [JSON Structure](json-structure/airport-city-search-issue-structure.json)
- [JSON Structure](json-structure/airport-city-search-links-structure.json)
- [JSON Structure](json-structure/airport-city-search-location-structure.json)
- [JSON Structure](json-structure/airport-city-search-travelers-structure.json)
- [Example](examples/airport-city-search-address-example.json)
- [Example](examples/airport-city-search-analytics-example.json)
- [Example](examples/airport-city-search-collection-meta-example.json)
- [Example](examples/airport-city-search-distance-example.json)
- [Example](examples/airport-city-search-error-400-example.json)
- [Example](examples/airport-city-search-error-404-example.json)
- [Example](examples/airport-city-search-error-500-example.json)
- [Example](examples/airport-city-search-geo-code-example.json)
- [Example](examples/airport-city-search-issue-example.json)
- [Example](examples/airport-city-search-links-example.json)
- [Example](examples/airport-city-search-location-example.json)
- [Example](examples/airport-city-search-travelers-example.json)

### City Search

Searches cities matching a keyword, returning city codes, country, geocoordinates, and timezone. Useful for destination and itinerary planning.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Cities
- Reference Data
- Autocomplete

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/city-search)
- [OpenAPI](openapi/amadeus-city-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-city-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-city-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/city-search-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/city-search-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/city-search-response-city-search-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/city-search-response-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/city-search-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/city-search-location-structure.json)
- [JSON Structure](json-structure/city-search-meta-structure.json)
- [JSON Structure](json-structure/city-search-response-city-search-structure.json)
- [JSON Structure](json-structure/city-search-response-error-structure.json)
- [JSON Structure](json-structure/city-search-warning-structure.json)
- [Example](examples/city-search-meta-example.json)
- [Example](examples/city-search-response-city-search-example.json)
- [Example](examples/city-search-response-error-example.json)
- [Example](examples/city-search-warning-example.json)

### Airline Code Lookup

Returns the airline name and details for a given IATA or ICAO airline code, used for translating codes into traveler-facing names.

- **Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Airlines
- Reference Data
- Lookup

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/airline-code-lookup)
- [OpenAPI](openapi/amadeus-airline-code-lookup-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-airline-code-lookup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-airline-code-lookup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airline-code-lookup-airline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-code-lookup-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airline-code-lookup-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airline-code-lookup-airline-structure.json)
- [JSON Structure](json-structure/airline-code-lookup-meta-structure.json)
- [JSON Structure](json-structure/airline-code-lookup-warning-structure.json)
- [Example](examples/airline-code-lookup-airline-example.json)
- [Example](examples/airline-code-lookup-meta-example.json)
- [Example](examples/airline-code-lookup-warning-example.json)

### Flight Most Booked Destinations

Returns the most booked destinations from a given origin city for a given period, surfacing demand patterns for marketing and merchandising.

- **Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Market Insights
- Flights
- Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-booked-destinations)
- [OpenAPI](openapi/amadeus-flight-most-booked-destinations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-most-booked-destinations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-most-booked-destinations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-most-booked-destinations-air-traffic-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-flights-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-booked-destinations-travelers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-most-booked-destinations-air-traffic-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-analytics-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-error-400-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-error-500-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-flights-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-issue-structure.json)
- [JSON Structure](json-structure/flight-most-booked-destinations-travelers-structure.json)
- [Example](examples/flight-most-booked-destinations-air-traffic-example.json)
- [Example](examples/flight-most-booked-destinations-analytics-example.json)
- [Example](examples/flight-most-booked-destinations-collection-meta-example.json)
- [Example](examples/flight-most-booked-destinations-error-400-example.json)
- [Example](examples/flight-most-booked-destinations-error-500-example.json)
- [Example](examples/flight-most-booked-destinations-flights-example.json)
- [Example](examples/flight-most-booked-destinations-issue-example.json)
- [Example](examples/flight-most-booked-destinations-travelers-example.json)

### Flight Most Traveled Destinations

Returns the most traveled-to destinations from a given origin city for a given period, useful for trend analysis and inspiration UIs.

- **Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Market Insights
- Flights
- Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-most-traveled-destinations)
- [OpenAPI](openapi/amadeus-flight-most-traveled-destinations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-most-traveled-destinations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-most-traveled-destinations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-most-traveled-destinations-air-traffic-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-flights-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-most-traveled-destinations-travelers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-most-traveled-destinations-air-traffic-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-analytics-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-error-400-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-error-500-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-flights-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-issue-structure.json)
- [JSON Structure](json-structure/flight-most-traveled-destinations-travelers-structure.json)
- [Example](examples/flight-most-traveled-destinations-air-traffic-example.json)
- [Example](examples/flight-most-traveled-destinations-analytics-example.json)
- [Example](examples/flight-most-traveled-destinations-collection-meta-example.json)
- [Example](examples/flight-most-traveled-destinations-error-400-example.json)
- [Example](examples/flight-most-traveled-destinations-error-500-example.json)
- [Example](examples/flight-most-traveled-destinations-flights-example.json)
- [Example](examples/flight-most-traveled-destinations-issue-example.json)
- [Example](examples/flight-most-traveled-destinations-travelers-example.json)

### Flight Busiest Traveling Period

Returns the busiest travel periods (months) for a given city, helping with capacity planning and pricing strategy.

- **Human URL:** [https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Market Insights
- Analytics
- Seasonality

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/market-insights/api-doc/flight-busiest-traveling-period)
- [OpenAPI](openapi/amadeus-flight-busiest-traveling-period-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-flight-busiest-traveling-period.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-flight-busiest-traveling-period.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flight-busiest-traveling-period-air-traffic-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-analytics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flight-busiest-traveling-period-travelers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flight-busiest-traveling-period-air-traffic-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-analytics-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-collection-meta-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-error-400-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-error-500-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-issue-structure.json)
- [JSON Structure](json-structure/flight-busiest-traveling-period-travelers-structure.json)
- [Example](examples/flight-busiest-traveling-period-air-traffic-example.json)
- [Example](examples/flight-busiest-traveling-period-analytics-example.json)
- [Example](examples/flight-busiest-traveling-period-collection-meta-example.json)
- [Example](examples/flight-busiest-traveling-period-error-400-example.json)
- [Example](examples/flight-busiest-traveling-period-error-500-example.json)
- [Example](examples/flight-busiest-traveling-period-issue-example.json)
- [Example](examples/flight-busiest-traveling-period-travelers-example.json)

### Hotel List

Returns the list of hotels in a given city, geographic area, or by hotel IDs, with property metadata. The foundation lookup for downstream hotel offers and ratings calls.

- **Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Hotels
- Reference Data
- Search

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)
- [OpenAPI](openapi/amadeus-hotel-list-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-list.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-list.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hotel-list-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-list-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-list-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-list-hotel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-list-hotel-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-list-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hotel-list-error-400-structure.json)
- [JSON Structure](json-structure/hotel-list-error-404-structure.json)
- [JSON Structure](json-structure/hotel-list-error-500-structure.json)
- [JSON Structure](json-structure/hotel-list-hotel-search-response-structure.json)
- [JSON Structure](json-structure/hotel-list-hotel-structure.json)
- [JSON Structure](json-structure/hotel-list-meta-structure.json)
- [Example](examples/hotel-list-error-400-example.json)
- [Example](examples/hotel-list-error-404-example.json)
- [Example](examples/hotel-list-error-500-example.json)
- [Example](examples/hotel-list-hotel-search-response-example.json)
- [Example](examples/hotel-list-meta-example.json)

### Hotel Search

Returns available hotel offers (rates, room types, board, cancellation policies) for a list of hotel IDs and a stay date range.

- **Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)
- **Base URL:** `https://test.api.amadeus.com/v3`

#### Tags

- Hotels
- Search
- Offers
- Rates

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search)
- [OpenAPI](openapi/amadeus-hotel-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hotel-search-board-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-cancellation-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-error-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-offers-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-cancellation-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-check-in-out-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-commission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-deposit-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-estimated-room-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-guarantee-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-guests-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-hold-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-hotel-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-payment-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-policy-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-price-variation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-price-variations-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-rate-family-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-product-room-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-hotel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-markup-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-method-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-multi-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-payment-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-pricing-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-qualified-free-text-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-search-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hotel-search-board-type-structure.json)
- [JSON Structure](json-structure/hotel-search-cancellation-type-structure.json)
- [JSON Structure](json-structure/hotel-search-error-source-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-offer-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-offers-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-cancellation-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-check-in-out-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-commission-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-deposit-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-estimated-room-type-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-guarantee-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-guests-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-hold-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-hotel-price-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-payment-policy-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-policy-details-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-price-variation-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-price-variations-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-rate-family-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-product-room-details-structure.json)
- [JSON Structure](json-structure/hotel-search-hotel-structure.json)
- [JSON Structure](json-structure/hotel-search-markup-structure.json)
- [JSON Structure](json-structure/hotel-search-method-structure.json)
- [JSON Structure](json-structure/hotel-search-multi-response-structure.json)
- [JSON Structure](json-structure/hotel-search-payment-type-structure.json)
- [JSON Structure](json-structure/hotel-search-price-structure.json)
- [JSON Structure](json-structure/hotel-search-pricing-response-structure.json)
- [JSON Structure](json-structure/hotel-search-qualified-free-text-structure.json)
- [JSON Structure](json-structure/hotel-search-tax-structure.json)
- [JSON Structure](json-structure/hotel-search-type-structure.json)
- [Example](examples/hotel-search-error-source-example.json)
- [Example](examples/hotel-search-hotel-example.json)
- [Example](examples/hotel-search-hotel-offer-example.json)
- [Example](examples/hotel-search-hotel-offers-example.json)
- [Example](examples/hotel-search-hotel-product-cancellation-policy-example.json)
- [Example](examples/hotel-search-hotel-product-check-in-out-policy-example.json)
- [Example](examples/hotel-search-hotel-product-commission-example.json)
- [Example](examples/hotel-search-hotel-product-deposit-policy-example.json)
- [Example](examples/hotel-search-hotel-product-estimated-room-type-example.json)
- [Example](examples/hotel-search-hotel-product-guarantee-policy-example.json)
- [Example](examples/hotel-search-hotel-product-guests-example.json)
- [Example](examples/hotel-search-hotel-product-hold-policy-example.json)
- [Example](examples/hotel-search-hotel-product-hotel-price-example.json)
- [Example](examples/hotel-search-hotel-product-payment-policy-example.json)
- [Example](examples/hotel-search-hotel-product-policy-details-example.json)
- [Example](examples/hotel-search-hotel-product-price-variation-example.json)
- [Example](examples/hotel-search-hotel-product-price-variations-example.json)
- [Example](examples/hotel-search-hotel-product-rate-family-example.json)
- [Example](examples/hotel-search-hotel-product-room-details-example.json)
- [Example](examples/hotel-search-markup-example.json)
- [Example](examples/hotel-search-multi-response-example.json)
- [Example](examples/hotel-search-price-example.json)
- [Example](examples/hotel-search-pricing-response-example.json)
- [Example](examples/hotel-search-qualified-free-text-example.json)
- [Example](examples/hotel-search-tax-example.json)

### Hotel Booking

Creates a hotel booking (reservation) from a confirmed offer, including guest information, payment, and contact details.

- **Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Hotels
- Booking
- Reservations

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)
- [OpenAPI](openapi/amadeus-hotel-booking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-booking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-booking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/amadeus-hotel-booking-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-booking-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-booking-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hotel-booking-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-arrival-flight-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-create-hotel-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-guest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-guests-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-product-deposit-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-product-payment-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-hotel-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-payment-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-payment-output-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-qualified-free-text-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-room-association-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-associated-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-hotel-booking-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-stakeholder-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-v1-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-booking-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hotel-booking-address-structure.json)
- [JSON Structure](json-structure/hotel-booking-arrival-flight-details-structure.json)
- [JSON Structure](json-structure/hotel-booking-create-hotel-booking-structure.json)
- [JSON Structure](json-structure/hotel-booking-guest-structure.json)
- [JSON Structure](json-structure/hotel-booking-guests-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-booking-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-contact-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-offer-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-order-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-product-deposit-policy-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-product-payment-policy-structure.json)
- [JSON Structure](json-structure/hotel-booking-hotel-product-structure.json)
- [JSON Structure](json-structure/hotel-booking-payment-input-structure.json)
- [JSON Structure](json-structure/hotel-booking-payment-output-structure.json)
- [JSON Structure](json-structure/hotel-booking-price-structure.json)
- [JSON Structure](json-structure/hotel-booking-qualified-free-text-structure.json)
- [JSON Structure](json-structure/hotel-booking-room-association-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-associated-record-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-contact-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-hotel-booking-light-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-name-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-payment-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-stakeholder-structure.json)
- [JSON Structure](json-structure/hotel-booking-v1-warning-structure.json)
- [JSON Structure](json-structure/hotel-booking-warning-structure.json)
- [Example](examples/hotel-booking-address-example.json)
- [Example](examples/hotel-booking-arrival-flight-details-example.json)
- [Example](examples/hotel-booking-create-hotel-booking-example.json)
- [Example](examples/hotel-booking-guest-example.json)
- [Example](examples/hotel-booking-guests-example.json)
- [Example](examples/hotel-booking-hotel-booking-example.json)
- [Example](examples/hotel-booking-hotel-contact-example.json)
- [Example](examples/hotel-booking-hotel-order-example.json)
- [Example](examples/hotel-booking-hotel-product-deposit-policy-example.json)
- [Example](examples/hotel-booking-hotel-product-example.json)
- [Example](examples/hotel-booking-hotel-product-payment-policy-example.json)
- [Example](examples/hotel-booking-payment-input-example.json)
- [Example](examples/hotel-booking-payment-output-example.json)
- [Example](examples/hotel-booking-price-example.json)
- [Example](examples/hotel-booking-qualified-free-text-example.json)
- [Example](examples/hotel-booking-room-association-example.json)
- [Example](examples/hotel-booking-v1-associated-record-example.json)
- [Example](examples/hotel-booking-v1-contact-example.json)
- [Example](examples/hotel-booking-v1-hotel-booking-light-example.json)
- [Example](examples/hotel-booking-v1-name-example.json)
- [Example](examples/hotel-booking-v1-payment-example.json)
- [Example](examples/hotel-booking-v1-stakeholder-example.json)
- [Example](examples/hotel-booking-v1-warning-example.json)
- [Example](examples/hotel-booking-warning-example.json)

### Hotel Name Autocomplete

Returns up to 20 hotels whose names match a search keyword, with full address, geocode, property type, IATA hotel code, and Amadeus hotel ID — ideal for search-as-you-type hotel pickers.

- **Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Hotels
- Autocomplete
- Reference Data

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-name-autocomplete)
- [OpenAPI](openapi/amadeus-hotel-name-autocomplete-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-name-autocomplete.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-name-autocomplete.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hotel Ratings

Returns sentiment-analyzed ratings for hotels across categories like service, room, location, and food, derived from millions of online reviews.

- **Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)
- **Base URL:** `https://test.api.amadeus.com/v2`

#### Tags

- Hotels
- Ratings
- Sentiment Analysis
- Reviews

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)
- [OpenAPI](openapi/amadeus-hotel-ratings-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-hotel-ratings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-hotel-ratings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hotel-ratings-collection-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-error-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-error400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-error401-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-error500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-hotel-sentiment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-warning-not-found-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotel-ratings-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hotel-ratings-collection-links-structure.json)
- [JSON Structure](json-structure/hotel-ratings-collection-meta-structure.json)
- [JSON Structure](json-structure/hotel-ratings-error-source-structure.json)
- [JSON Structure](json-structure/hotel-ratings-error400-structure.json)
- [JSON Structure](json-structure/hotel-ratings-error401-structure.json)
- [JSON Structure](json-structure/hotel-ratings-error500-structure.json)
- [JSON Structure](json-structure/hotel-ratings-hotel-sentiment-structure.json)
- [JSON Structure](json-structure/hotel-ratings-score-structure.json)
- [JSON Structure](json-structure/hotel-ratings-warning-not-found-structure.json)
- [JSON Structure](json-structure/hotel-ratings-warning-structure.json)
- [Example](examples/hotel-ratings-collection-links-example.json)
- [Example](examples/hotel-ratings-collection-meta-example.json)
- [Example](examples/hotel-ratings-error-source-example.json)
- [Example](examples/hotel-ratings-error400-example.json)
- [Example](examples/hotel-ratings-error401-example.json)
- [Example](examples/hotel-ratings-error500-example.json)
- [Example](examples/hotel-ratings-hotel-sentiment-example.json)
- [Example](examples/hotel-ratings-warning-example.json)

### Points of Interest

Returns points of interest (sights, restaurants, nightlife, shopping) for a given location with categories and rankings.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Destination Content
- Points of Interest
- Geolocation

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)
- [OpenAPI](openapi/amadeus-points-of-interest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-points-of-interest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-points-of-interest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/points-of-interest-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-geo-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/points-of-interest-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/points-of-interest-collection-meta-structure.json)
- [JSON Structure](json-structure/points-of-interest-error-400-structure.json)
- [JSON Structure](json-structure/points-of-interest-error-404-structure.json)
- [JSON Structure](json-structure/points-of-interest-error-500-structure.json)
- [JSON Structure](json-structure/points-of-interest-geo-code-structure.json)
- [JSON Structure](json-structure/points-of-interest-issue-structure.json)
- [JSON Structure](json-structure/points-of-interest-links-structure.json)
- [JSON Structure](json-structure/points-of-interest-location-structure.json)
- [Example](examples/points-of-interest-collection-meta-example.json)
- [Example](examples/points-of-interest-error-400-example.json)
- [Example](examples/points-of-interest-error-404-example.json)
- [Example](examples/points-of-interest-error-500-example.json)
- [Example](examples/points-of-interest-geo-code-example.json)
- [Example](examples/points-of-interest-issue-example.json)
- [Example](examples/points-of-interest-links-example.json)
- [Example](examples/points-of-interest-location-example.json)

### Tours and Activities

Returns bookable tours, activities, and experiences for a given location with prices, photos, and provider details.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Destination Content
- Tours and Activities
- Bookable Experiences

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/tours-and-activities)
- [OpenAPI](openapi/amadeus-tours-and-activities-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-tours-and-activities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-tours-and-activities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tours-and-activities-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-elementary-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-geo-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tours-and-activities-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tours-and-activities-activity-structure.json)
- [JSON Structure](json-structure/tours-and-activities-collection-meta-structure.json)
- [JSON Structure](json-structure/tours-and-activities-elementary-price-structure.json)
- [JSON Structure](json-structure/tours-and-activities-error-400-structure.json)
- [JSON Structure](json-structure/tours-and-activities-error-404-structure.json)
- [JSON Structure](json-structure/tours-and-activities-error-500-structure.json)
- [JSON Structure](json-structure/tours-and-activities-geo-code-structure.json)
- [JSON Structure](json-structure/tours-and-activities-issue-structure.json)
- [JSON Structure](json-structure/tours-and-activities-link-structure.json)
- [Example](examples/tours-and-activities-activity-example.json)
- [Example](examples/tours-and-activities-collection-meta-example.json)
- [Example](examples/tours-and-activities-elementary-price-example.json)
- [Example](examples/tours-and-activities-error-400-example.json)
- [Example](examples/tours-and-activities-error-404-example.json)
- [Example](examples/tours-and-activities-error-500-example.json)
- [Example](examples/tours-and-activities-geo-code-example.json)
- [Example](examples/tours-and-activities-issue-example.json)
- [Example](examples/tours-and-activities-link-example.json)

### Safe Place

Returns a safety score for a location across categories like LGBTQ+, women, physical harm, and theft, helping travelers make informed destination decisions.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Destination Content
- Safety
- Analytics

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/safe-place)
- [OpenAPI](openapi/amadeus-safe-place-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-safe-place.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-safe-place.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/safe-place-collection-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-geo-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-safety-rated-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safe-place-safety-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/safe-place-collection-meta-structure.json)
- [JSON Structure](json-structure/safe-place-error-400-structure.json)
- [JSON Structure](json-structure/safe-place-error-404-structure.json)
- [JSON Structure](json-structure/safe-place-error-500-structure.json)
- [JSON Structure](json-structure/safe-place-geo-code-structure.json)
- [JSON Structure](json-structure/safe-place-issue-structure.json)
- [JSON Structure](json-structure/safe-place-links-structure.json)
- [JSON Structure](json-structure/safe-place-location-structure.json)
- [JSON Structure](json-structure/safe-place-safety-rated-location-structure.json)
- [JSON Structure](json-structure/safe-place-safety-score-structure.json)
- [Example](examples/safe-place-collection-meta-example.json)
- [Example](examples/safe-place-error-400-example.json)
- [Example](examples/safe-place-error-404-example.json)
- [Example](examples/safe-place-error-500-example.json)
- [Example](examples/safe-place-geo-code-example.json)
- [Example](examples/safe-place-issue-example.json)
- [Example](examples/safe-place-links-example.json)
- [Example](examples/safe-place-location-example.json)
- [Example](examples/safe-place-safety-rated-location-example.json)
- [Example](examples/safe-place-safety-score-example.json)

### Location Score

Returns a 0-100 score for a location across categories (sights, restaurants, shopping, nightlife, historical, beach/park), powering destination ranking experiences.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Destination Content
- Analytics
- Ranking

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)
- [OpenAPI](openapi/amadeus-location-score-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-location-score.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-location-score.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/location-score-category-rated-areas-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/location-score-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/location-score-response-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/location-score-response-location-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/location-score-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/location-score-category-rated-areas-structure.json)
- [JSON Structure](json-structure/location-score-meta-structure.json)
- [JSON Structure](json-structure/location-score-response-error-structure.json)
- [JSON Structure](json-structure/location-score-response-location-score-structure.json)
- [JSON Structure](json-structure/location-score-warning-structure.json)
- [Example](examples/location-score-meta-example.json)
- [Example](examples/location-score-response-error-example.json)
- [Example](examples/location-score-response-location-score-example.json)
- [Example](examples/location-score-warning-example.json)

### Travel Recommendations

Returns destination recommendations based on a list of seed cities and traveler country, powering "if you liked X you'll like Y" discovery experiences.

- **Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Destination Content
- Recommendations
- Artificial Intelligence

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)
- [OpenAPI](openapi/amadeus-travel-recommendations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-travel-recommendations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-travel-recommendations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/travel-recommendations-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/travel-recommendations-recommended-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/travel-recommendations-response-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/travel-recommendations-response-recommended-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/travel-recommendations-warning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/travel-recommendations-meta-structure.json)
- [JSON Structure](json-structure/travel-recommendations-recommended-location-structure.json)
- [JSON Structure](json-structure/travel-recommendations-response-error-structure.json)
- [JSON Structure](json-structure/travel-recommendations-response-recommended-location-structure.json)
- [JSON Structure](json-structure/travel-recommendations-warning-structure.json)
- [Example](examples/travel-recommendations-meta-example.json)
- [Example](examples/travel-recommendations-response-error-example.json)
- [Example](examples/travel-recommendations-response-recommended-location-example.json)
- [Example](examples/travel-recommendations-warning-example.json)

### Trip Purpose Prediction

Predicts whether a trip is for business or leisure based on the itinerary's origin, destination, dates, and search timing, helping route trip-specific merchandising.

- **Human URL:** [https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Itinerary Management
- Artificial Intelligence
- Prediction
- Personalization

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/itinerary-management/api-doc/trip-purpose-prediction)
- [OpenAPI](openapi/amadeus-trip-purpose-prediction-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-trip-purpose-prediction.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-trip-purpose-prediction.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/trip-purpose-prediction-defaults-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-links-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-prediction-result-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trip-purpose-prediction-purpose-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trip-purpose-prediction-defaults-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-error-400-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-error-500-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-issue-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-links-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-meta-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-prediction-result-type-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-prediction-structure.json)
- [JSON Structure](json-structure/trip-purpose-prediction-purpose-prediction-structure.json)
- [Example](examples/trip-purpose-prediction-defaults-example.json)
- [Example](examples/trip-purpose-prediction-error-400-example.json)
- [Example](examples/trip-purpose-prediction-error-500-example.json)
- [Example](examples/trip-purpose-prediction-issue-example.json)
- [Example](examples/trip-purpose-prediction-links-example.json)
- [Example](examples/trip-purpose-prediction-meta-example.json)
- [Example](examples/trip-purpose-prediction-prediction-example.json)
- [Example](examples/trip-purpose-prediction-purpose-prediction-example.json)

### Transfer Search

Searches private and shared transfer options (taxi, limo, shuttle) between two locations with prices, vehicle types, and cancellation policies.

- **Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Cars and Transfers
- Search
- Ground Transport

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-search)
- [OpenAPI](openapi/amadeus-transfer-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-transfer-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-transfer-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/transfer-search-address-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-baggage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-cancellation-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-contact-with-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-discount-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-distance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-error-401-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-extra-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-partner-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-passenger-characteristics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-points-and-cash-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-quotation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-service-provider-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-stop-over-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-stop-over-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-transfer-offer-post-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-transfer-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-transportation-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-travel-segment-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-travel-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-search-vehicle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/transfer-search-address-common-structure.json)
- [JSON Structure](json-structure/transfer-search-address-structure.json)
- [JSON Structure](json-structure/transfer-search-baggage-structure.json)
- [JSON Structure](json-structure/transfer-search-cancellation-rule-structure.json)
- [JSON Structure](json-structure/transfer-search-contact-structure.json)
- [JSON Structure](json-structure/transfer-search-contact-with-address-structure.json)
- [JSON Structure](json-structure/transfer-search-discount-code-structure.json)
- [JSON Structure](json-structure/transfer-search-distance-structure.json)
- [JSON Structure](json-structure/transfer-search-equipment-structure.json)
- [JSON Structure](json-structure/transfer-search-error-400-structure.json)
- [JSON Structure](json-structure/transfer-search-error-401-structure.json)
- [JSON Structure](json-structure/transfer-search-error-500-structure.json)
- [JSON Structure](json-structure/transfer-search-extra-service-structure.json)
- [JSON Structure](json-structure/transfer-search-fee-structure.json)
- [JSON Structure](json-structure/transfer-search-issue-structure.json)
- [JSON Structure](json-structure/transfer-search-location-structure.json)
- [JSON Structure](json-structure/transfer-search-partner-info-structure.json)
- [JSON Structure](json-structure/transfer-search-passenger-characteristics-structure.json)
- [JSON Structure](json-structure/transfer-search-points-and-cash-structure.json)
- [JSON Structure](json-structure/transfer-search-quotation-structure.json)
- [JSON Structure](json-structure/transfer-search-seat-structure.json)
- [JSON Structure](json-structure/transfer-search-service-provider-structure.json)
- [JSON Structure](json-structure/transfer-search-stop-over-request-structure.json)
- [JSON Structure](json-structure/transfer-search-stop-over-structure.json)
- [JSON Structure](json-structure/transfer-search-tax-structure.json)
- [JSON Structure](json-structure/transfer-search-transfer-offer-post-structure.json)
- [JSON Structure](json-structure/transfer-search-transfer-offer-structure.json)
- [JSON Structure](json-structure/transfer-search-transportation-type-structure.json)
- [JSON Structure](json-structure/transfer-search-travel-segment-location-structure.json)
- [JSON Structure](json-structure/transfer-search-travel-segment-structure.json)
- [JSON Structure](json-structure/transfer-search-vehicle-structure.json)
- [Example](examples/transfer-search-address-common-example.json)
- [Example](examples/transfer-search-address-example.json)
- [Example](examples/transfer-search-baggage-example.json)
- [Example](examples/transfer-search-cancellation-rule-example.json)
- [Example](examples/transfer-search-contact-example.json)
- [Example](examples/transfer-search-discount-code-example.json)
- [Example](examples/transfer-search-distance-example.json)
- [Example](examples/transfer-search-equipment-example.json)
- [Example](examples/transfer-search-error-400-example.json)
- [Example](examples/transfer-search-error-401-example.json)
- [Example](examples/transfer-search-error-500-example.json)
- [Example](examples/transfer-search-extra-service-example.json)
- [Example](examples/transfer-search-issue-example.json)
- [Example](examples/transfer-search-location-example.json)
- [Example](examples/transfer-search-partner-info-example.json)
- [Example](examples/transfer-search-passenger-characteristics-example.json)
- [Example](examples/transfer-search-points-and-cash-example.json)
- [Example](examples/transfer-search-seat-example.json)
- [Example](examples/transfer-search-service-provider-example.json)
- [Example](examples/transfer-search-stop-over-example.json)
- [Example](examples/transfer-search-stop-over-request-example.json)
- [Example](examples/transfer-search-travel-segment-example.json)
- [Example](examples/transfer-search-travel-segment-location-example.json)
- [Example](examples/transfer-search-vehicle-example.json)

### Transfer Book

Books a transfer based on the offer returned by Transfer Search, capturing passenger details, pickup, and payment.

- **Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Cars and Transfers
- Booking
- Ground Transport

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-book)
- [OpenAPI](openapi/amadeus-transfer-book-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-transfer-book.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-transfer-book.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/transfer-book-address-common-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-agency-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-baggage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-cancellation-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-contact-with-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-corporation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-credit-card-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-discount-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-distance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-error-401-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-extra-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-fee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-loyalty-number-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-partner-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-passenger-characteristics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-passenger-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-points-and-cash-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-quotation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-service-provider-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-stop-over-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-tax-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-transfer-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-transfer-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-transfer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-transportation-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-travel-segment-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-travel-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-book-vehicle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/transfer-book-address-common-structure.json)
- [JSON Structure](json-structure/transfer-book-address-structure.json)
- [JSON Structure](json-structure/transfer-book-agency-structure.json)
- [JSON Structure](json-structure/transfer-book-baggage-structure.json)
- [JSON Structure](json-structure/transfer-book-cancellation-rule-structure.json)
- [JSON Structure](json-structure/transfer-book-contact-structure.json)
- [JSON Structure](json-structure/transfer-book-contact-with-address-structure.json)
- [JSON Structure](json-structure/transfer-book-corporation-structure.json)
- [JSON Structure](json-structure/transfer-book-credit-card-structure.json)
- [JSON Structure](json-structure/transfer-book-discount-code-structure.json)
- [JSON Structure](json-structure/transfer-book-distance-structure.json)
- [JSON Structure](json-structure/transfer-book-equipment-structure.json)
- [JSON Structure](json-structure/transfer-book-error-400-structure.json)
- [JSON Structure](json-structure/transfer-book-error-401-structure.json)
- [JSON Structure](json-structure/transfer-book-error-500-structure.json)
- [JSON Structure](json-structure/transfer-book-extra-service-structure.json)
- [JSON Structure](json-structure/transfer-book-fee-structure.json)
- [JSON Structure](json-structure/transfer-book-issue-structure.json)
- [JSON Structure](json-structure/transfer-book-location-structure.json)
- [JSON Structure](json-structure/transfer-book-loyalty-number-structure.json)
- [JSON Structure](json-structure/transfer-book-name-structure.json)
- [JSON Structure](json-structure/transfer-book-partner-info-structure.json)
- [JSON Structure](json-structure/transfer-book-passenger-characteristics-structure.json)
- [JSON Structure](json-structure/transfer-book-passenger-structure.json)
- [JSON Structure](json-structure/transfer-book-payment-structure.json)
- [JSON Structure](json-structure/transfer-book-points-and-cash-structure.json)
- [JSON Structure](json-structure/transfer-book-quotation-structure.json)
- [JSON Structure](json-structure/transfer-book-seat-structure.json)
- [JSON Structure](json-structure/transfer-book-service-provider-structure.json)
- [JSON Structure](json-structure/transfer-book-stop-over-structure.json)
- [JSON Structure](json-structure/transfer-book-tax-structure.json)
- [JSON Structure](json-structure/transfer-book-transfer-order-structure.json)
- [JSON Structure](json-structure/transfer-book-transfer-reservation-structure.json)
- [JSON Structure](json-structure/transfer-book-transfer-structure.json)
- [JSON Structure](json-structure/transfer-book-transportation-type-structure.json)
- [JSON Structure](json-structure/transfer-book-travel-segment-location-structure.json)
- [JSON Structure](json-structure/transfer-book-travel-segment-structure.json)
- [JSON Structure](json-structure/transfer-book-vehicle-structure.json)
- [Example](examples/transfer-book-address-common-example.json)
- [Example](examples/transfer-book-address-example.json)
- [Example](examples/transfer-book-agency-example.json)
- [Example](examples/transfer-book-baggage-example.json)
- [Example](examples/transfer-book-cancellation-rule-example.json)
- [Example](examples/transfer-book-contact-example.json)
- [Example](examples/transfer-book-corporation-example.json)
- [Example](examples/transfer-book-credit-card-example.json)
- [Example](examples/transfer-book-discount-code-example.json)
- [Example](examples/transfer-book-distance-example.json)
- [Example](examples/transfer-book-equipment-example.json)
- [Example](examples/transfer-book-error-400-example.json)
- [Example](examples/transfer-book-error-401-example.json)
- [Example](examples/transfer-book-error-500-example.json)
- [Example](examples/transfer-book-extra-service-example.json)
- [Example](examples/transfer-book-issue-example.json)
- [Example](examples/transfer-book-location-example.json)
- [Example](examples/transfer-book-loyalty-number-example.json)
- [Example](examples/transfer-book-name-example.json)
- [Example](examples/transfer-book-partner-info-example.json)
- [Example](examples/transfer-book-passenger-characteristics-example.json)
- [Example](examples/transfer-book-payment-example.json)
- [Example](examples/transfer-book-points-and-cash-example.json)
- [Example](examples/transfer-book-seat-example.json)
- [Example](examples/transfer-book-service-provider-example.json)
- [Example](examples/transfer-book-stop-over-example.json)
- [Example](examples/transfer-book-transfer-example.json)
- [Example](examples/transfer-book-transfer-order-example.json)
- [Example](examples/transfer-book-travel-segment-example.json)
- [Example](examples/transfer-book-travel-segment-location-example.json)
- [Example](examples/transfer-book-vehicle-example.json)

### Transfer Management

Cancels an existing transfer booking and manages the transfer order lifecycle.

- **Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Cars and Transfers
- Booking Management
- Orders

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)
- [OpenAPI](openapi/amadeus-transfer-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-transfer-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-transfer-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/transfer-management-error-400-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-management-error-401-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-management-error-404-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-management-error-500-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-management-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transfer-management-transfer-cancellation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/transfer-management-error-400-structure.json)
- [JSON Structure](json-structure/transfer-management-error-401-structure.json)
- [JSON Structure](json-structure/transfer-management-error-404-structure.json)
- [JSON Structure](json-structure/transfer-management-error-500-structure.json)
- [JSON Structure](json-structure/transfer-management-issue-structure.json)
- [JSON Structure](json-structure/transfer-management-transfer-cancellation-structure.json)
- [Example](examples/transfer-management-error-400-example.json)
- [Example](examples/transfer-management-error-401-example.json)
- [Example](examples/transfer-management-error-404-example.json)
- [Example](examples/transfer-management-error-500-example.json)
- [Example](examples/transfer-management-issue-example.json)
- [Example](examples/transfer-management-transfer-cancellation-example.json)

### Authorization

OAuth2 client credentials token endpoint used by every Self-Service API. Exchanges API key + secret for a short-lived bearer access token (~30 minute TTL).

- **Human URL:** [https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- **Base URL:** `https://test.api.amadeus.com/v1`

#### Tags

- Authentication
- OAuth2
- Security

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [OpenAPI](openapi/amadeus-authorization-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amadeus-authorization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amadeus-authorization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/authorization-amadeus-oauth2-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/authorization-amadeus-oauth2-token-structure.json)
- [Example](examples/authorization-amadeus-oauth2-token-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://amadeus.com)
- [Developer Portal](https://developers.amadeus.com)
- [GitHub Organization](https://github.com/amadeus4dev)
- [GitHub Organization](https://github.com/AmadeusITGroup)
- [LinkedIn](https://www.linkedin.com/company/amadeus)
- [Twitter](https://twitter.com/AmadeusITGroup)
- [Sign Up](https://developers.amadeus.com/register)
- [Console](https://developers.amadeus.com/my-apps)
- [Pricing](https://developers.amadeus.com/pricing)
- [Terms of Service](https://developers.amadeus.com/terms-of-use-api)
- [Privacy Policy](https://amadeus.com/en/policies/privacy-policy)
- [Documentation](https://developers.amadeus.com/self-service/apis-docs)
- [Getting Started](https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [Rate Limits](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/api-rate-limits/)
- [Blog](https://developers.amadeus.com/blog)
- [Support](https://developers.amadeus.com/support)
- [F A Q](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/amadeus)
- [Discord](https://discord.gg/cVrFBqx)
- [Postman](https://www.postman.com/amadeus4dev/amadeus-for-developers-s-public-workspace) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Test Data](https://github.com/amadeus4dev/data-collection)
- [SDK](https://www.npmjs.com/package/amadeus)
- [SDK](https://pypi.org/project/amadeus/)
- [SDK](https://central.sonatype.com/artifact/com.amadeus/amadeus-java)
- [SDK](https://github.com/amadeus4dev/amadeus-ruby)
- [Code Examples](https://github.com/amadeus4dev/amadeus-code-examples)
- [Code Examples](https://github.com/amadeus4dev/amadeus-flight-booking-django)
- [Code Examples](https://github.com/amadeus4dev/amadeus-hotel-booking-django)
- [Code Examples](https://github.com/amadeus4dev/amadeus-hotel-search-tours-django)
- [Code Examples](https://github.com/amadeus4dev/amadeus-flight-price-analysis-django)
- [Tutorials](https://github.com/amadeus4dev/developer-guides)
- [Tutorials](https://github.com/amadeus4dev/hackathon-starter)
- [Tools](https://github.com/donghyun-chae/mcp-amadeus)
- [Tools](https://pypi.org/project/mcp-amadeus/)
- [Spectral Rules](rules/amadeus-rules.yml)
- [Vocabulary](vocabulary/amadeus-vocabulary.yml)
- [J S O N- L D](json-ld/amadeus-context.jsonld)
- [Plans](plans/amadeus-plans-pricing.yml)
- [Rate Limits](rate-limits/amadeus-rate-limits.yml)
- [Fin Ops](finops/amadeus-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
