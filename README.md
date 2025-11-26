# Strategic Inventory Optimization: Push vs Pull

This project analyzes the financial impact of moving two flagship retail stores (NYC and LA) from a forecast-driven **Push** inventory model to a demand-driven **Pull** model. It was completed as part of a business analytics/supply chain learning project and implemented using Excel-based modeling and cost analysis.

## Business problem

The goal is to determine whether a Pull model reduces total weekly and annual supply‑chain cost (inventory, shipping, and pick/pack) across smartphone product categories, and to identify any cases where the legacy Push approach should be retained. 

## Data and assumptions

- Product categories: Hot-Smart, Hot-Feature, Cold-Smart, Cold-Feature phones for NYC and LA flagship stores.  
- Input assumptions include unit values, weekly holding cost per unit, shipping mode costs (overnight vs standard freight), and pick/pack labor rates. 

## Methodology

- Built an Excel cost model to compute total weekly cost under Push and Pull for each store and product category.  
- Calculated net savings, savings percentage, and annualized savings by comparing Push vs Pull totals for NYC and LA. 
- Performed SKU-level analysis to find where Pull is better and where Push remains cheaper. 

## Key results

- Full Pull adoption across both stores shows about **USD 5.4M** in annualized savings versus the baseline Push model. 
- NYC achieves around **42%** cost reduction; LA achieves around **34%** due to lower initial inventory burden. 
- For most smartphone SKUs (especially Smart and Cold segments), Pull significantly reduces holding cost and total weekly cost. 
- Hot-Feature phones are a strategic exception where Pull is 10–16% more expensive because bulk freight under Push is more efficient than frequent small shipments. 

## Recommendation

The final recommendation is a **hybrid inventory strategy**:  
- Move Smart (Hot and Cold) and Cold-Feature phones to the Pull model to capture savings from lower inventory. 
- Keep Hot-Feature phones on the Push model to preserve freight economies of scale. 

## How this was implemented

- Tools: Microsoft Excel (formulas, structured tables, and scenario calculations). 
- Skills demonstrated: cost modeling, inventory and supply-chain analysis, scenario comparison, annualization of savings, and making a business recommendation from quantitative results. 
