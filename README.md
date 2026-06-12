Server-side Google Tag Manager client template for Stripe Checkout purchase tracking.

This template receives a Stripe Checkout Session ID, validates the payment status through the Stripe API, retrieves complete order and customer information, and forwards a fully enriched purchase event into the server-side GTM container.

## Features

- Stripe Checkout purchase validation
- Retrieves transaction details directly from Stripe API
- Enhanced Ecommerce purchase event support
- Automatic client_id and session handling
- User Data collection for improved attribution
- Google Ads enhanced conversions support
- Meta (Facebook) Conversions API support
- TikTok, Snapchat, Microsoft Ads and other platform identifiers support
- Consent Mode parameter forwarding
- UTM parameter forwarding
- Server-side tracking architecture

## Event Data Included

- Transaction ID
- Purchase Value
- Currency
- Tax
- Shipping
- Discount
- Coupon
- Product Items
- Customer Information
- User Data
- Attribution Parameters
- Consent Signals

## Requirements

- Google Tag Manager Server Container
- Stripe Secret API Key
- Stripe Checkout Sessions

## Use Cases

- Server-side purchase tracking
- Google Ads conversion tracking
- GA4 purchase tracking
- Meta CAPI implementation
- Multi-platform attribution
- Enhanced conversion measurement

## Author

Shakil Ahmed Samim
