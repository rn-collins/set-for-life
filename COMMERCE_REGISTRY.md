# Set for Life commerce registry

Last verified: 2026-08-18  
Control: RR-051

This file is the repository-level source of truth for current Set for Life availability and pricing. Historical plans, funnels, drafts, and product concepts do not override it.

## Live inventory

| SKU | Status | Canonical price | Delivery | Checkout |
| --- | --- | ---: | --- | --- |
| SFL-LAB-001 — Relationship-Building Lab | Live | $0 | https://set-for-life-black.vercel.app/#lab | None required |

The live lab is browser-local. It delivers target mapping, message drafting, outcome tracking, metrics, CSV export, and JSON backup/import without an account or payment.

## Not currently offered

The following are concepts, archived offers, or roadmap items. They are not purchasable and must not carry a live purchase CTA:

- Set for Life self-serve course
- live cohort
- Law Clerk Field Guide
- Aloha Framework Guide
- 90-Day calendars
- resume pack
- operating-system workbook
- Complete 0L Toolkit
- Done-for-You service
- Operator subscription

Historical figures—including $9, $12, $17, $27, $37, $47, $67, $97, $147, $197, $297, and $2,500—are not current prices.

## Commerce controls

Before any paid SKU becomes live, all of the following must exist and pass verification:

1. final deliverable with version and owner;
2. one canonical SKU and price;
3. checkout URL returning a successful product page;
4. receipt and tax/refund disclosures;
5. successful test purchase;
6. successful post-purchase delivery;
7. recovery and support instructions;
8. matching price and CTA across the website, Notion, email copy, and commerce platform;
9. updated entry in this registry.

## Verification record

- Canonical production URL returns HTTP 200.
- The website identifies the current release as free and says no paid course or cohort is offered.
- The $0 acquisition path opens the working lab.
- A local target record can be created, viewed in outcome tracking, and removed.
- The historical Gumroad path `gumroad.com/l/law-clerk-field-guide` returns 404 and is not a valid checkout.
- High-risk Notion pricing and commerce pages were marked with the RR-051 supersession notice.
