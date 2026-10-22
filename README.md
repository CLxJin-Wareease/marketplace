# WareEase Marketplace

A B2B marketplace inside the WareEase member portal. Suppliers sell stock that is already stored at a WareEase warehouse to buyers linked to that warehouse.

**Status:** In development. Not live yet.

## Overview

WareEase makes warehousing and logistics easy for food and consumer brands, restaurants and franchise groups across the US. Marketplace lets suppliers (importers and brands) sell goods that are already stored at a WareEase warehouse to buyers (retailers and restaurants) linked to that warehouse.

- WareEase collects the goods payment on the buyer's invoice.
- Fulfillment uses the normal WareEase pickup and delivery request.
- WareEase never owns the goods.

## Problem

- Buyers source by phone calls and by trading Excel files back and forth. It is slow and takes a lot of people.
- Sales between WareEase customers happen off-platform today.
- Suppliers rarely reach end buyers, and a US middleman adds cost.

## Solution

Suppliers list stock that is already in a WareEase warehouse. Buyers linked to that warehouse order it in the portal and choose pickup or delivery. The order runs through the same invoicing and pickup and delivery flow WareEase customers already use, with WareEase Ops in control of each order.

## Listing rules

Goods can be listed only after all four steps are done, in this order:

1. The importer or seller imports the goods into the US.
2. FDA, U.S. Customs and other agencies clear the permits and anything else required.
3. The goods arrive at a WareEase warehouse.
4. Only then can the goods be listed.

WareEase does not review import or permit documents itself.

## Scope of v1

### In scope

**Seller onboarding with approval**
- Required documents: Business License, EIN Letter, W-9 and Product List.
- Optional documents: FDA, USDA and Reseller Permit.
- Admin has a queue of sellers waiting for document review.

**Buying**
- Buyers see stock only at warehouses they are linked to.
- Buyers order stock and choose pickup or delivery.

**Ops control**
- 48-hour order hold
- Manual order confirmation
- Holds and recalls
- Refunds
- 7-day dispute window
- Manual payouts

**Data correctness**
- No duplicate stock
- Order snapshots can't be changed after the order is placed
- Expired lots are never shipped

### Out of scope for v1

- Store-at-source and moving stock between warehouses
- Choosing specific lots
- Finding sellers by ZIP code or distance
- Public browsing
- Stock that has not been received yet
- Buyer-specific pricing
- Promotions
- Carts with more than one seller
- Automated payouts and tax
- Restricted goods
- Warehouses buying or selling

### Future state

- Any non-warehouse account can sell.

## Rollout

Staging first, then production after leadership sign-off.
