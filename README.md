Translation:
- [English](README.md)
- [Indonesian](README_id.md)

## Overview
Tara aims to serve as a platform for collecting, organizing, and sharing information related to pests. Its goal is to provide information and assistance to small-scale farmers across the regions of Indonesia in effectively dealing with agricultural pests. It aspires to offer recommendations on suitable pesticides based on specific crops, thus helping farmers make informed decisions regarding pest control. Ultimately, the objective is to enhance crop yields and improve the livelihoods of farmers.

In the future, it is envisioned that Tara will gradually provide a service that offers guidance on the proper implementation of pesticides to combat pest infestations.

## Sample Data
The collected data will follow the initial format (JSON) with the following structure:
```json
{
  "pests": [
    {
      "name": "Pest 1",
      "category": "Category P1",
      "crops": [
        {
          "name": "Crop A",
          "category": "Category C1"
        }
      ],
      "pesticide": {
        "category": "Category PC1",
        "active_ingredients": ["Ingredient A", "Ingredient B"],
        "brands": [
          {
            "name": "Brand X",
            "price": "$10",
            "ecommerce_availability": {
              "platform": "E-commerce X",
              "availability": "In stock"
            }
          },
          {
            "name": "Brand Y",
            "price": "$12",
            "ecommerce_availability": {
              "platform": "E-commerce Y",
              "availability": "Out of stock"
            }
          }
        ],
        "notes": "Additional notes about the pesticide can be provided here."
      }
    },
    ...
  ]
}
```

## Note
Updates will be made periodically, without any specific timeframe or restrictions.