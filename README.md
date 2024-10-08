# PRODCT_PRICE_MERGE

This is a Node.js project written in TypeScript that demonstrates how to merge two arrays: one containing product information and another containing pricing data. The merged data is printed to the console, providing an enriched view of the product information with associated prices.

## Table of Contents
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Output](#output)
- [License](#license)

## Project Structure
```json
├── node_modules/ # Dependencies installed by npm
├── src/ # Source folder containing TypeScript files
│ └── index.ts # Main file that merges product and pricing data
├── nodemon.json # Configuration for nodemon
├── package-lock.json # Automatically generated file for dependencies
├── package.json # Project metadata and dependencies
├── tsconfig.json # TypeScript configuration file
└── README.md # Project documentation (this file)
```

## Requirements

Before you begin, ensure you have the following installed on your machine:

- **Node.js** (version 14 or higher)
- **npm** (Node package manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AjayDumaraliya19/product_price_merge.git

2. Install the required dependencies:
    ```bash
    npm install

### Running the Project
This project uses nodemon for automatic reloading during development. To run the project, execute the following command:
```bash
npm start
```
This command will start the TypeScript application, compiling and running src/index.ts, and watching for any changes to the source files.

## Output
When you run the project, you will see the enriched product data printed to the console. The output will include product information along with the corresponding prices merged from the pricing data:

### Sample Console Output:
```json
[
  { "id": 1, "sku": "abc", "productName": "name 1", "category": 1, "price": 10 },
  { "id": 2, "sku": "def", "productName": "name 2", "category": 2, "price": 20 },
  { "id": 3, "sku": "ghi", "productName": "name 1", "category": 2, "price": 30 },
  { "id": 4, "sku": "klm", "productName": "name 1", "category": 3, "price": 40 },
  { "id": 5, "sku": "xyz", "productName": "name 1", "category": 1, "price": 50 }
]
```

This JSON output shows each product enriched with its corresponding price. If a product does not have an associated price, it will show `null` for the `price` field.
