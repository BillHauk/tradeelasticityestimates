# Export Data Files to Accompany “U.S. Import and Export Elasticities: A Panel Data Approach”

## List and Description of Files:

*Note: All data files are available in Stata (.dta) format.*

-	**exporths10elasticities** – elasticities of demand for exports at the HS-10 digit level of aggregation (data available 1989-2001)
-	**exporths6substitution1** – elasticities of substitution amongst different varieties of exports at the HS-6 digit level of aggregation (data available 1978-1988)
-	**exporths6substitution2** – elasticities of substitution amongst different varieties of exports at the HS-6 digit level of aggregation (data available 1989-2001)
-	**exporths6elasticities** – elasticities of demand for exports at the HS-6 digit level of aggregation (data available 1978-2001)
-	**exportnaics6substitution1** – elasticities of substitution amongst different varieties of exports at the NAICS-6 digit level of aggregation (data available 1978-1988)
-	**exportnaics6substitution2** – elasticities of substitution amongst different varieties of exports at the NAICS-6 digit level of aggregation (data available 1989-2001)
-	**exportnaics6elasticities** – elasticities of demand for exports at the NAICS-6 digit level of aggregation (data available 1978-2001)
-	**exportnaics4substitution1** – elasticities of substitution amongst different varieties of exports at the NAICS-4 digit level of aggregation (data available 1978-1988)
-	**exportnaics4substitution2** – elasticities of substitution amongst different varieties of exports at the NAICS-4 digit level of aggregation (data available 1989-2001)
-	**exportnaics4elasticities** – elasticities of demand for exports at the NAICS-4 digit level of aggregation (data available 1978-2001)

## Variable Description for Export Substitution Elasticity Files

-	**Sector** – sector classification at relevant level of aggregation
-	**demandprice** – elasticity of sectoral share of exports with respect to export price
-	**demandcons** – constant from demand equation
-	**se[variablename]** – standard error of estimates
-	**groups** – number of country-sectors used in estimates
-	**obs** – number of total observations used in estimates
-	**yearmin** – first year of observations
-	**yearmax** – last year of observations
-	**time** – total years of observations
-	**impliedsigma** – implied substitution elasticity from demandprice

##	Variable Description of Export Supply and Demand Elasticity Files

-	**Sector** – sector classification at relevant level of aggregation
-	**demandprice** – elasticity of total value of exports to sector-country with respect to export price (demand equation)
-	**demandimportprice** – elasticity of total value of exports to sector-country with respect to U.S. imports in same sector; proxy for world price of goods (demand equation)
-	**demanddeflator** – elasticity of total value of exports to sector-country with respect to the GDP deflator in the importing country (demand equation)
-	**demandgdp** – elasticity of total value of exports to sector-country with respect to the per-capita GDP in the importing country (demand equation)
-	**demandpopulation** – elasticity of total value of exports to sector-country with respect to the population of the importing country (demand equation)
-	**demandexchange** – elasticity of total value of exports to sector-country with respect to the per-capita GDP in the importing country (demand equation)
-	**demandcons** – constant from the export demand equation
-	**supplyvalue** – elasticity of export price with respect to the total value of goods exported (supply equation)
-	**supplyusdeflator** – elasticity of export price with respect to the GDP deflator in the U.S. (supply equation)
-	**supplyusinterest** – elasticity of export price with respect to the real interest rate in the U.S. (supply equation)
-	**supplyuswage** – elasticity of export price with respect to the wage rate in the U.S. (supply equation)
-	**supplycons** – constant from the export supply equation
-	**se[variablename]** – standard errors from the elasticity estimates
-	**groups** – number of country-sectors used in estimates
-	**obs** – number of total observations used in estimates
-	**yearmin** – first year of observations
-	**yearmax** – last year of observations
-	**time** – total years of observations
