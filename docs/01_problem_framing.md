# Problem Statements

## Stakeholders' concerns

### From:
VP OF Marketplace Operations & Head of Customer Experience

### Context:
Olist connects thousands of small Brazillian merchants to major online marketplaces (such as Mercado Livre), managing payments, logistics, and customer service.

### The Trigger: 
"Order volume has been growing rapidly, which is great but our customer support queue is getting slammed with 1-star reviews, and almost none of our buyers seem to come back for a second purchase. Leadership is debating whether we should start penalizing slow sellers and pouring budget into faster shipping to fix retention. Before we make major operational changes next quarter, dig into the data and tell us what is actually breaking and where we should focus first."


## Problem formulation:


### Situation:
Olist operates a B2B2C marketplace aggragator model across Brazil, scaling transaction volume rapidly across thousands of small merchants and dozens of product categories.

### Complication:
Despite strong top-line order growth, customer satisfaction is being dragged down by a visible tail of 1-star reviews, and customer repeat purchase rates appear critically low.

### Core Business Problem:
What are the primary operational drivers of 1-star reviews across the marketplace, is poor delivery performance causing our low repeat-purchase rate, and which specific levers (sellers, carriers, delivery estimates, regions, or categories) should leadership prioritize first?

### Concrete decision this analysis will inform:
Decide how to allocate Q3/Q4 operational and growth resources across four competing options:
1. Enforcing stricter SLAs or penalties on underperforming sellers
2. Renegotiating carrier routes or recalibrating checkout delivery estimates in specific regions
3. Building proactive pre-delivery intervention workflows
4. Funding a separate customer retention / lifecycle program versus relying on logistics fixes to lift repeat orders

### Primary audience and decision owners:
* VP of Marketplace Operations (owns seller SLAs, carrier mix, regional priorities)
* Head of Product / Checkout (owns displayed delivery estimates)
* Head of Growth / CRM (owns post-purchase retention and category focus)

## Clarifying questions and assumptions

### Definition of "Order" & "Revenue"
Should headline commercial performance measure all placed orders (gross demand) or strictly delivered orders and should revenue separate merchandise value from freight charges? (Working assumption: Report both gross demand and delivered merchandise revenue separately, with freight tracked explicitly as a logistics cost burden.)

### Definition of "Late Delivery"
Are we measuring total transit speed (purchase to delivery) or promise reliability (actual delivery date vs. estimated delivery date promised at checkout)? (Working assumption: Track both, and decompose delays into Seller Handoff vs. Carrier Transit.)

### Definition of a "Repeat Customer"
How does our database distinguish a returning individual from a checkout session, and do multi-seller baskets placed on the same day count as repeat purchases? (To be audited in Step 3.)

### Time window & Scope boundries
Are there incomplete launch or cutoff months at the edges of the dataset that could distort year-over-year growth or cohort return windows? (To be audited in Step 3.)

### Known business model constraint (Out of Data Scope)
Because Olist sells through larger third-party marketplaces (like Mercado Livre), many shoppers may not realize they bought from Olist an external brand-attribution factor we must keep in mind when interpreting retention.