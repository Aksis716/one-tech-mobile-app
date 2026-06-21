# One-Tech

**One-Tech** is a cross-platform service and commerce app for connectivity products and support. It brings together a customer storefront, order management, support conversations, and field-oriented tools for Starlink and MikroTik equipment.

The app is designed around the real customer journey: discover services, buy products, follow an order, request help, and access practical connection diagnostics from one mobile experience.

## Highlights

- Product catalogue, cart, checkout, order tracking, and invoice access.
- Customer authentication, profiles, and password recovery.
- Support requests and threaded conversations.
- Starlink diagnostic and debugging flows.
- MikroTik router connection guidance and local-network tooling.
- Notifications and a polished home experience with promotional content.
- Role-based administration for the shop, products, services, requests, users, analytics, platform data, and promotional content.
- Boutique operations features for inventory, cash movements, daily reporting, printing, and sharing.

## Built with

- **Expo** and **React Native** for Android, iOS, and web
- **Firebase** for authentication, cloud data, and storage-backed content
- Local network integrations for **MikroTik** and **Starlink** workflows
- Expo modules for notifications, secure storage, media, printing, sharing, and device capabilities
- React Navigation and custom reusable components for the application shell

## Screens

The repository includes sample screens in [`Screenshots/`](./Screenshots): Home, Market, Starlink, and Settings.

## Run locally

### Prerequisites

- Node.js 18 or later
- npm
- Expo Go or an Android/iOS simulator for mobile testing

### Installation

```bash
git clone https://github.com/Aksis716/one-tech-mobile-app.git
cd one-tech-mobile-app
npm install
npx expo start
```

Useful commands:

```bash
npm run android
npm run ios
npm run web
npm run lint
```

## Configuration

Set up your own Firebase project and supply the appropriate Android/iOS configuration files and environment values before building or deploying. Starlink and MikroTik functions require compatible equipment on the local network and the relevant device credentials.

## Portfolio note

This project demonstrates an end-to-end customer application rather than a single-purpose screen set: commerce, support, operations, device-aware workflows, and administrator tooling are all connected in one coherent product.

## License

All rights reserved. The source is provided for portfolio review; reuse or redistribution requires permission.
