# Import Data Files to Accompany “U.S. Import and Export Elasticities: A Panel Data Approach”

## List and Description of Files:

*Note: All data files are available in Stata (.dta) format.*

-	**imporths10substitution** – elasticities of substitution amongst different varieties of imports at the HS-10 digit level of aggregation (data available 1989-2001)
-	**imporths10elasticities** – elasticities of demand for imports at the HS-10 digit level of aggregation (data available 1989-2001)
-	**imporths6substitution1** – elasticities of substitution amongst different varieties of imports at the HS-6 digit level of aggregation (data available 1978-1988)
-	**imporths6substitution2** – elasticities of substitution amongst different varieties of imports at the HS-6 digit level of aggregation (data available 1989-2001)
-	**imporths6elasticities** – elasticities of demand for imports at the HS-6 digit level of aggregation (data available 1978-2001)
-	**importnaics6substitution1** – elasticities of substitution amongst different varieties of imports at the NAICS-6 digit level of aggregation (data available 1978-1988)
-	**importnaics6substitution2** – elasticities of substitution amongst different varieties of imports at the NAICS-6 digit level of aggregation (data available 1989-2001)
-	**importnaics6elasticities** – elasticities of demand for imports at the NAICS-6 digit level of aggregation (data available 1978-2001)
-	**importnaics4substitution1** – elasticities of substitution amongst different varieties of imports at the NAICS-4 digit level of aggregation (data available 1978-1988)
-	**importnaics4substitution2** – elasticities of substitution amongst different varieties of imports at the NAICS-4 digit level of aggregation (data available 1989-2001)
-	**importnaics4elasticities** – elasticities of demand for imports at the NAICS-4 digit level of aggregation (data available 1978-2001)
-	**importsic3substitution1** – elasticities of substitution amongst different varieties of imports at the SIC-3 digit level of aggregation (data available 1978-1988)
-	**importsic3substitution2** – elasticities of substitution amongst different varieties of imports at the SIC-3 digit level of aggregation (data available 1989-2001)
-	**importsic3elasticities** – elasticities of demand for imports at the SIC-3 digit level of aggregation (data available 1978-2001)
-	**importisic3substitution1** – elasticities of substitution amongst different varieties of imports at the ISIC-3 digit level of aggregation (data available 1978-1988)
-	**importisic3substitution2** – elasticities of substitution amongst different varieties of imports at the ISIC-3 digit level of aggregation (data available 1989-2001)
-	**importisic3elasticities** – elasticities of demand for imports at the ISIC-3 digit level of aggregation (data available 1978-2001)

## Variable Description for Import Substitution Elasticity Files

-	**Sector** – sector classification at relevant level of aggregation
-	**demandprice** – elasticity of sectoral share of imports with respect to unit price (demand equation)
-	**demandotherprice** – elasticity of sectoral share of imports with respect to average price of other imports in sector (demand equation)
-	**demandcons** – constant from demand equation
-	**supplyshare** – elasticity of import price with respect to sectoral share of imports (supply equation)
-	**supplytariff** – elasticity of import price with respect to effective tariff rate on import (supply equation)
-	**supplygdp** – elasticity of import price with respect to per-capita GDP of exporting country (supply equation)
-	**supplydeflator** – elasticity of import price with respect to GDP deflator of exporting country (supply equation)
-	**supplyexchange** – elasticity of import price with respect to U.S. dollar exchange rate exporting country currency (supply equation)
- **supplycons** – constant from supply equation
-	**se[variablename]** – standard error of estimates
-	**demandsargan** – Sargan statistic from demand equation instruments
-	**supplysargan** – Sargan statistic from supply equation instruments
-	**groups** – number of HS-10 Digit country imports used in parameter estimation
-	**obs** – number of HS-10 digit country import years used in parameter estimation
-	**impliedsigma** – elasticity of substitution among different varieties of imports in sector as implied by demandprice estimate

## Variable Description for Import Demand Elasticity Files

-	**Sector** – sector classification at relevant level of aggregation
-	**demandprice** – elasticity of total value of imports with respect to import price index (demand equation)
-	**demandexportprice** – elasticity of value of imports with respect to U.S. export price in same sector (demand equation)
-	**demandotherexportprice** – elasticity of value of imports with respect to U.S. export price in other sectors (demand equation)
-	**demanduspop** – elasticity of value of imports with respect to U.S. population (demand equation)
-	**demandusgdp** – elasticity of value of imports with respect to U.S. per-capita GDP (demand equation)
-	**demandcons** – constant from the demand equation
-	**supplyvalue** – elasticity of import price with respect to total value of imports (supply equation)
-	**supplytariff** – elasticity of import price with respect to tariffs (supply equation)
-	**supplygdp** – elasticity of import price with respect to exporting country per-capita GDP (supply equation)
-	**supplydeflator** – elasticity of import price with respect to exporting country GDP deflator (supply equation)
-	**supplyexchange** – elasticity of import price with respect to exporting country exchange rate (supply equation)
-	**supplycons** – constant from supply equation
-	**varietypricediff** – elasticity of variety parameter with respect to price difference between new and old varieties (variety equation)
-	**varietycons** – constant from variety equation
-	**se[variablename]** – standard errors of estimates
-	**demandsargan** – Sargan statistic from demand equation instruments
-	**supplysargan** – Sargan statistic from supply equation instruments
-	**obs** – observations used in elasticity estimates
-	**sarganX** – dummy variable indicating whether we can reject the null hypothesis that the Sargan statistic in the demand equation equals zero at the X% level (No = 1; Yes = 0)
-	**impliedelasticity** – own-price elasticity of demand for imports in sector as implied by demandprice
-	**positive** – dummy variable indicating that the implied elasticity is of the correct sign (Yes = 1; No = 0)
-	**sigatXper** – dummy variable indicating that the implied elasticity is of the correct sign and significantly different from zero at the X% level (Yes = 1; No = 0)
