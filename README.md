# Selic Transmission to Credit and Activity

**Status:** planned

## Question
What is the dynamic response of credit, inflation and output to a Selic shock in Brazil?

## Premises
- Monetary policy transmits through credit and exchange-rate channels with lags.
- Post-Keynesian view: credit is endogenous and expectations ("animal spirits") modulate transmission.

## Method
1. Series: Selic, credit stock (BCB SGS), IPCA, IBC-Br, BRL/USD, Focus expectations.
2. Stationarity/cointegration check; choose VAR in levels/VECM vs. differences.
3. SVAR with Cholesky ordering; sensitivity to alternative orderings.
4. Impulse responses with bootstrap bands; FEVD.

## Deliverables
IRF panel, FEVD table, robustness appendix.

## Stack
Python (statsmodels `VAR`/`SVAR`) or R (`vars`).
