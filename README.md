# THRD-clothing

# Pricing Engine

## Description

This Python script updates product prices based on inventory levels and recent sales data. It applies specific pricing rules and ensures a minimum profit margin.

## Input Files

- `products.csv`: Contains product details including current and cost prices and stock.
- `sales.csv`: Recent sales quantities per SKU.

## Output

- `updated_prices.csv`: Contains the SKU, old price, and updated price, all formatted with units (USD).

## How to Run

```bash
python pricing_engine.py
