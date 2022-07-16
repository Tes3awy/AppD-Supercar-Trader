> **This collection was made as part of the AppDynamics Enablement program in 2022**

# Supercar Trader

Supercar Trader is a Java-based Web Application

The purpose of Supercar-Trader collection is to generate dynamic traffic (business transactions) for AppDynamics Controller.

---

## Getting Started

The Supercar Trader collection contains a total of **74** HTTP requests (**69** `GET` requests and **5** `POST` requests)

Pages: `3 requests`
Supercars Pages: `10 requests`
Search Page: `3 requests`
Car Pages: `24 requests`
Car Pages - View Enquiry: `24 requests`
Sell Page: `3 requests` (_1 POST request should throw an Error to the Controller_)
Enquire Page: `2 requests`
jsp Pages: `5 requests`

## How to use?

Import both `Supercar-Trader.postman_collection.json` and `Supercar-Trader Environment.postman_environment.json`, and select `Supercar-Trader Environment` to be in use (from the upper right corner. The `No Environment` dropdown)

Edit the `ip` variable in `Supercar-Trader Environment` with the IP address of your Supercar Trader web application and save it.

To run the entire collection at once (all 25 HTTP requests), click on `Runner` located at the bottom right corner, drag/drop the collection in the `Runner window` as instructed, then click `Start Run`.

## Notes

- All POST requests use dynamic variables that change every time the collection is started to avoid performing redundant POST requests with the same values.

- All requests are tested and passed the test to be considered successful, even for the request with error.
