# Prepare the first fulfillment order

Use this checklist before inviting customers into a new private-label supplement workflow. Record evidence privately and resolve blockers before a paid production order.

## Product and presentation

- Select the exact eligible product and packaging.
- Confirm current availability for the intended destination.
- Approve the correct label version and product presentation.
- Check that the storefront describes the product and delivery terms accurately.
- Confirm quantities and any order-size limits for the selected fulfillment route.

## Channel and order mapping

- Map the storefront variant to the correct fulfillment product.
- Confirm how bundles become physical units.
- Separate test and live connections.
- Identify the payment or funding condition required before fulfillment begins.
- Confirm who can view, approve, cancel or retry an order.

## Test without accidental dispatch

First use a supported sandbox or a workflow that explicitly prevents dispatch. Confirm that the integration's test mode really prevents downstream fulfillment; the label "test" on the storefront alone is not sufficient evidence.

Check one valid order, an invalid address, an unavailable product and a repeated event. Expected outcomes should include a clear status, a visible error where appropriate and no duplicate fulfillment.

Do not fabricate a paid order, tracking number or successful shipment to make a demonstration look complete.

## Review the live-order decision

A real first order can incur product and shipping charges. Confirm the amount, destination, recipient authorization and cancellation limits before authorizing it. After authorization, check the full chain: accepted order, correct physical units, correct charges, dispatch state and carrier tracking when available.

Record which steps were actually observed. "Order accepted" does not mean "dispatched"; "tracking created" does not mean "delivered".

## Prepare exception handling

Assign an owner for stock changes, failed payments, address corrections, damaged parcels and returns. Keep the support contact and escalation path accessible. Review the first orders individually before increasing volume.

[Back to resources](../README.md). Published by Fulfillment Nutra. Product-specific terms and capabilities remain authoritative.
