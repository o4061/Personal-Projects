# PaymentDeeplinkApp

<img width="100" src="https://github.com/user-attachments/assets/24e678d3-2687-45a9-8e82-fe5ae40c3428" />

## Description
PaymentDeeplinkApp is an Android application designed to demonstrate a universal deep link payment flow between third-party business apps (e.g., coffee kiosks, vending machines, ticketing systems) and the Castles Utility POS application.
It provides a dynamic and theme-aware deep link structure that enables any app to trigger a secure payment process — sending transaction details such as amount, currency, and business context — while automatically adapting the visual theme for a seamless and branded checkout experience.

The app acts as a bridge layer between merchant business applications and the payment engine, ensuring consistent user experience, simplified integration, and minimal setup requirements.

## Technologies Used  
- **Kotlin** – Primary programming language
- **Android Studio** – Development environment
- **MVVM** – Architecture pattern ensuring modularity and testability
- **Navigation Component** – For managing multi-step UI flows
- **ViewPager2 & DotsIndicator** – For animated and intuitive onboarding screens
- **Material Design 3** – For consistent UI and theming
- **FlexboxLayout** – Responsive layout handling for various screen sizes
- **Kotlinx Serialization** – Lightweight JSON parsing for deeplink payloads

## Features  
- Dynamic Deep Links: Generate and handle structured deep links to trigger payments in Castles Utility
- Seamless Payment Flow: Pass transaction parameters (amount, currency, theme) from any business app to initiate a unified checkout
- Thematic Adaptation: Automatically apply color schemes and assets based on the source business (e.g., coffee, laundry, fuel)
- Multi-Business Simulation: Built-in demo screens for different business types (Coffee Kiosk, Fast Food, Laundry, Fuel Station)
- Order Summary Integration: Displays detailed breakdown before redirecting to Castles Utility for payment
- Result Handling: Listen for success/failure callbacks from Castles Utility and present the final transaction outcome
- Lightweight Integration: Simple deep link structure that can be adopted by any Android business app without SDK dependency

## Screenshots<img width="5576" height="6008" alt="deepllinkFlow" src="https://github.com/user-attachments/assets/e7f59d75-239d-445a-87b0-6a4341879a90" />

### Complete Flow
<img width="8099" src="https://github.com/user-attachments/assets/e7f59d75-239d-445a-87b0-6a4341879a90" />





