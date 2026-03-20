# Guidewire_Hackathon
AI-Powered Parametric Insurance for Gig Workers

---

## Problem Statement

India’s gig workers such as delivery partners from Swiggy, Zomato, Zepto, and Amazon depend on daily work to earn their income. However, external factors like heavy rain, extreme heat, air pollution, and sudden curfews can directly affect their ability to work.

During such situations, they often lose around 20–30% of their income. Currently, there is no system that protects them from this type of income loss.

---

## Our Idea

GigShield AI is a simple platform that provides income protection to gig workers.

Instead of traditional insurance, it uses a parametric model where payouts are triggered automatically when certain real-world conditions are met.

The system:
- Calculates weekly premiums based on risk
- Monitors real-time data like weather and pollution
- Automatically sends payouts when disruptions occur
- Removes the need for manual claims

---

## Who This Is For

This solution is designed for urban delivery workers who:
- Work across multiple platforms like Swiggy and Zepto
- Earn daily income (around ₹700–₹900 per day)
- Depend on peak hours for most of their earnings
- Are affected by weather and city conditions

---

## Example Scenario

A delivery partner subscribes to a weekly plan for ₹40.

On a particular day, heavy rainfall occurs (above 50mm). Because of this, deliveries are reduced and movement becomes difficult.

The system detects this using weather data and automatically triggers a payout of ₹300.

The worker receives the money without needing to apply for a claim.

---

## How the System Works

1. The user registers on the platform  
2. The system evaluates risk based on location and conditions  
3. A weekly premium is generated  
4. The user purchases a policy  
5. The system continuously monitors environmental data  
6. If a trigger condition is met, a payout is automatically processed  

---

## Weekly Pricing Model

The premium is calculated based on risk factors such as weather and pollution.

Example:

- Low risk → ₹25 per week  
- Medium risk → ₹40 per week  
- High risk → ₹60 per week  

Each plan provides fixed coverage for that week.

This model matches the weekly earning cycle of gig workers.

---

## Parametric Triggers

Payouts are triggered automatically when specific conditions are met:

- Heavy rain when rainfall is greater than 50mm  
- Extreme heat when temperature exceeds 45°C  
- High pollution when AQI goes above 350  
- Curfew or restriction when an area becomes inaccessible  

---

## Use of AI

AI is used to:
- Estimate risk and calculate weekly premiums  
- Detect suspicious or duplicate claims  
- Validate user location and activity  

This helps in making the system fair and reliable.

---

## Platform Approach

The final product is designed as a mobile-first solution since gig workers primarily use smartphones.

For Phase 1, a web-based prototype is used for demonstration.

---

## Tech Stack

Frontend: React  
Backend: Spring Boot  
AI/ML: Python  
Database: MySQL  
APIs: Weather API, AQI API  
Payments: Mock or sandbox integration  

---

## Development Plan

Phase 1:
- Idea design and documentation  
- Basic workflow and prototype  

Phase 2:
- Backend and API integration  
- AI model implementation  

Phase 3:
- Mobile application  
- Full system deployment  

---

## Conclusion

GigShield AI provides a simple way to protect gig workers from income loss caused by external disruptions. It ensures fast and automatic compensation without complicated processes.
