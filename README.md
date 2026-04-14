# Awesome Stripe [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of Stripe SDKs, tools, libraries, integrations, dashboards, starter kits, API utilities, payment flows, subscription systems, fraud tools, and learning resources for building with **Stripe**.

## Contents

- [Official Resources](#official-resources)
- [API Clients & SDKs](#api-clients--sdks)
- [Starter Kits & Boilerplates](#starter-kits--boilerplates)
- [Payments, Checkout & Billing](#payments-checkout--billing)
- [Subscriptions & SaaS](#subscriptions--saas)
- [E-commerce Integrations](#e-commerce-integrations)
- [Webhooks & Event Handling](#webhooks--event-handling)
- [Fraud, Risk & Compliance](#fraud-risk--compliance)
- [CLI & Developer Tools](#cli--developer-tools)
- [Open-Source Tools & Libraries](#open-source-tools--libraries)
- [UI Components](#ui-components)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Stripe Docs](https://stripe.com/docs) – Official Stripe documentation covering payments, APIs, and integrations.
- [Stripe API Reference](https://stripe.com/docs/api) – Complete API reference for all Stripe resources and methods.
- [Stripe Samples](https://github.com/stripe-samples) – Official sample applications demonstrating real-world Stripe integrations.
- [Stripe Dashboard](https://dashboard.stripe.com/) – Main platform for managing payments, customers, billing, and settings.
- [Stripe CLI](https://stripe.com/docs/stripe-cli) – Developer tool for testing webhooks, making API calls, and managing Stripe resources.
- [Stripe Status](https://status.stripe.com/) – Real-time status updates for all Stripe services.

## API Clients & SDKs

### Official SDKs

- [Stripe.js](https://stripe.com/docs/js) – JavaScript SDK for secure payment elements, authentication, and client-side flows.
- [Stripe PHP](https://github.com/stripe/stripe-php) – Official PHP SDK for making API calls and integrating backend payment features.
- [Stripe Python](https://github.com/stripe/stripe-python) – Python SDK for managing payments, webhooks, subscriptions, and API operations.
- [Stripe Node](https://github.com/stripe/stripe-node) – Node.js client library for building server-side Stripe integrations.
- [Stripe Ruby](https://github.com/stripe/stripe-ruby) – Ruby SDK for accessing all Stripe API endpoints.
- [Stripe Java](https://github.com/stripe/stripe-java) – Java client library supporting synchronous and asynchronous API usage.
- [Stripe Go](https://github.com/stripe/stripe-go) – Go SDK for secure, typed, backend API integrations.
- [Stripe .NET](https://github.com/stripe/stripe-dotnet) – .NET SDK for C# applications working with Stripe APIs.
- [Stripe iOS](https://github.com/stripe/stripe-ios) – iOS SDK for adding secure in-app payments and Apple Pay.
- [Stripe Android](https://github.com/stripe/stripe-android) – Android SDK for native card entry and Google Pay support.

### Third-Party Integrations

- [Laravel Cashier](https://laravel.com/docs/cashier) – Laravel billing layer providing subscription management with Stripe.
- [Django DJ-Stripe](https://github.com/dj-stripe/dj-stripe) – Django integration syncing Stripe objects into local models.
- [StripeEvent (Ruby)](https://github.com/integrallis/stripe_event) – Ruby gem for secure webhook processing.

## Starter Kits & Boilerplates

- [Stripe Sample Apps](https://github.com/stripe-samples) – Official end-to-end examples for payments, SaaS, subscriptions, and marketplaces.
- [Next.js Subscriptions Starter](https://github.com/vercel/nextjs-subscription-payments) – Full-featured subscription boilerplate using Next.js and Stripe Billing.
- [Node SaaS Boilerplate](https://github.com/stripe-samples/nextjs-subscriptions) – Stripe-supported sample for creating SaaS apps with usage billing.
- [Laravel Cashier Starter Kits](https://github.com/laravel/cashier) – Ready-made scaffolding for Laravel subscription applications.
- [DJ-Stripe Example Project](https://github.com/dj-stripe/dj-stripe) – Boilerplate for Django subscription and billing applications.

## Payments, Checkout & Billing

- [Stripe Checkout](https://stripe.com/docs/payments/checkout) – Hosted payment page that supports cards, wallets, and bank payment methods.
- [Payment Links](https://stripe.com/docs/payments/payment-links) – Shareable buy links for accepting payments without writing backend code.
- [Stripe Elements](https://stripe.com/docs/elements) – Customizable payment interface components for secure card and wallet entry.
- [Payment Intents API](https://stripe.com/docs/payments/payment-intents) – Core API for handling dynamic authentication and real-time payment states.
- [Stripe Billing](https://stripe.com/billing) – Billing engine for subscriptions, invoicing, proration, and metered billing.
- [Customer Portal](https://stripe.com/docs/customer-management) – Hosted self-service portal for subscription management.
- [Stripe Terminal](https://stripe.com/terminal) – SDK and hardware for in-person card payments.

## Subscriptions & SaaS

- [Stripe Billing Subscriptions](https://stripe.com/docs/billing/subscriptions/overview) – Tools for creating, managing, and upgrading recurring subscriptions.
- [Metered Billing](https://stripe.com/docs/billing/subscriptions/metered) – Usage-based billing system for consumption-driven SaaS products.
- [Usage Records API](https://stripe.com/docs/billing/subscriptions/usage-records) – API for tracking customer usage in near real time.
- [Coupons & Trials](https://stripe.com/docs/billing/subscriptions/trials) – Features for promotions, trial periods, and onboarding offers.
- [Stripe Migration Tools](https://github.com/stripe/stripe-migrate) – Utilities for migrating subscription data from external platforms.
- [SaveMyChurn](https://savemychurn.com) – AI-powered churn recovery for Stripe subscriptions. Detects at-risk subscribers and sends personalized retention offers automatically. (savemychurn.com)

## E-commerce Integrations

- [WooCommerce Stripe](https://woocommerce.com/products/woocommerce-gateway-stripe/) – Official plugin enabling Stripe payments within WooCommerce stores.
- [Shopify + Stripe](https://stripe.com/partners/shopify) – Native integration powering Shopify merchant payment processing.
- [Magento Stripe Module](https://github.com/stripe/stripe-payments) – Official Magento extension supporting multiple payment methods.
- [Ghost Payments](https://ghost.org/) – Built-in Ghost CMS membership and payment system powered by Stripe.
- [PrestaShop Stripe](https://addons.prestashop.com/en/payment-card-wallet/24922-stripe-official.html) – Official Stripe module for PrestaShop storefronts.

## Webhooks & Event Handling

- [Stripe Webhooks](https://stripe.com/docs/webhooks) – Event-driven webhook system for receiving payment and subscription updates.
- [stripe-node Webhook Helpers](https://github.com/stripe/stripe-node#webhook-signing) – Node utilities for validating webhook signatures.
- [DJ-Stripe Webhook Dispatcher](https://github.com/dj-stripe/dj-stripe) – Django integration providing secure webhook parsing.
- [Serverless Webhooks Sample](https://github.com/stripe-samples/webhooks-node) – Example for building resilient serverless webhook handlers.

## Fraud, Risk & Compliance

- [Stripe Radar](https://stripe.com/radar) – Machine-learning fraud prevention system integrated with Stripe.
- [3D Secure / SCA](https://stripe.com/docs/strong-customer-authentication) – Authentication requirements for European payment regulations.
- [Stripe Disputes](https://stripe.com/docs/disputes) – Tools for responding to chargebacks and evidence submission.
- [PCI Compliance Guide](https://stripe.com/guides/pci-compliance) – Stripe-managed compliance model simplifying card security obligations.

## CLI & Developer Tools

- [Stripe CLI](https://stripe.com/docs/stripe-cli) – Command-line tool for triggering webhooks, interacting with the API, and managing test data.
- [Stripe VSCode Extension](https://marketplace.visualstudio.com/items?itemName=Stripe.stripe-vscode) – VSCode plugin for testing payments, logs, and webhooks.
- [Stripe Postman Collection](https://github.com/stripe/postman) – Collection for exploring and testing the Stripe API using Postman.
- [Stripe Terraform Provider](https://registry.terraform.io/providers/stripe/stripe/latest) – Infrastructure-as-code provider for managing Stripe resources declaratively.

## Open-Source Tools & Libraries

- [Cashier for Laravel](https://laravel.com/docs/cashier) – Laravel package providing subscription and billing features powered by Stripe.
- [DJ-Stripe](https://github.com/dj-stripe/dj-stripe) – Django app mirroring Stripe objects locally for subscription and billing logic.
- [Cartalyst Stripe](https://github.com/cartalyst/stripe) – PHP wrapper offering simplified Stripe API interactions.
- [Flask-Stripe](https://github.com/unt-lfc/flask-stripe) – Lightweight Flask extension for integrating Stripe payments.
- [nestjs-stripe](https://github.com/anchan828/nestjs-stripe) – NestJS module for building backend services with Stripe.

## UI Components

- [Stripe Elements](https://stripe.com/docs/elements) – Pre-built UI components for secure card entry and wallet payments.
- [React Stripe.js](https://github.com/stripe/react-stripe-js) – React bindings for Stripe.js to build secure hosted payment fields.
- [Vue Stripe Elements](https://github.com/vue-stripe/vue-stripe) – Vue components wrapping Stripe Elements and payment flows.
- [Svelte Stripe](https://github.com/beyonk-adventures/svelte-stripe) – Svelte integration for embedding Stripe Elements in apps.
- [Payment Request Button](https://stripe.com/docs/stripe-js/elements/payment-request-button) – Unified UI for Apple Pay, Google Pay, and browser-native wallets.

## Learning Resources

### Tutorials
- [Stripe Developers YouTube](https://www.youtube.com/c/StripeDevelopers) – Official Stripe tutorials and live coding demos.
- [Stripe Docs Tutorials](https://stripe.com/docs/development) – Guided walkthroughs for payments, checkout, and subscriptions.
- [Traversy Media Stripe Guide](https://www.youtube.com/results?search_query=stripe+traversy+media) – Practical Stripe integration tutorials.

### Guides
- [Stripe API Best Practices](https://stripe.com/docs/best-practices) – Recommendations for building safe and scalable integrations.
- [Scaling SaaS with Stripe](https://stripe.com/resources) – Guides and case studies for SaaS product growth.
- [Subscription Billing Tour](https://stripe.com/docs/billing/subscriptions/overview) – Overview of subscription capabilities and workflows.

### Courses
- *Build SaaS with Stripe* – Courses covering subscription workflows and API usage.
- *Node.js Stripe Mastery* – Full-stack Stripe training for Node developers.
- *Laravel Cashier Deep Dive* – Subscription migrations, proration, and billing automation.

## Related Awesome Lists

- [Awesome Laravel](https://github.com/awesomelistsio/awesome-laravel)
- [Awesome APIs](https://github.com/awesomelistsio/awesome-apis)
- [Awesome SaaS](https://github.com/awesomelistsio/awesome-saas)
- [Awesome Web Development](https://github.com/awesomelistsio/awesome-web-development)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
