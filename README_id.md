# Tara
Terjemahan:
- [Inggris](README.md)
- [Bahasa Indonesia](README_id.md)

## Gambaran
Tara bertujuan sebagai tempat pengumpulan, pengorganisasian, dan berbagi informasi terkait hama. Tujuannya adalah memberi bantuan informasi untuk petani skala kecil di seluruh wilayah Indonesia dalam mengatasi hama pertanian secara efektif. Harapanya dapat memberikan saran tentang pestisida yang cocok berdasarkan tanaman tertentu sehingga dapat membantu dalam mengambil keputusan yang tepat terkait pengendalian hama. Dan akhirnya meningkatkan hasil panen dan penghidupan petani.

Di masa mendatang, harapanya secara bertahap dapat menyediakan layanan yang menawarkan panduan dalam mengimplementasikan pestisida dengan benar untuk mengatasi serangan hama.

## Contoh Data
Struktur data yang akan dikumpulkan dengan format awal (json) sebagai berikut:
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

## Catatan
Pembaharuan akan dilakukan secara berkala, tidak ada batasan dan ketentuan waktu.