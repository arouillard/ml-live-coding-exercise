# ml-live-coding-exercise

### Instructions
You are an ML Engineer. You have been asked to create a machine learning model to categorize products. The product owner for this project has obtained a labeled dataset for you to develop a proof-of-concept. What will you do with it?

### Dataset
ml_live_coding_data.json.gz

### Sample
```
[
    {
        "Category": "Books",
        "Price": null,
        "Title": "3 Packs Leather Journal Notebook Vintage Travel Journal for Women 6 Rings Refillable Diary Planner A6 Sketchbook Diary Planner Personal Organizer with Blank Pages Clear Bag and Card Slots, 180 Pages",
        "Features": [],
        "Description": [],
        "Details": {
            "Item Weight": "1.57 pounds"
        }
    },
    {
        "Category": "Fashion",
        "Price": null,
        "Title": "Coach Signature Slim Passcase ID Wallet Charcoal & Black",
        "Features": [],
        "Description": [],
        "Details": {
            "Brand": "COACH",
            "Special Feature": "Slim",
            "Age Range (Description)": "Adult",
            "Pocket Description": "Jetted Pocket",
            "Product Care Instructions": "Dry Cloth Clean"
        }
    },
    {
        "Category": "Books",
        "Price": 13.99,
        "Title": "High Value Women's Daily Planner And Organizer Pink Black Striped",
        "Features": [
            "100 pages. * Targeted Actions - Help keep the focus on your targets to achieve your goals* Prioritized Activities - Putting your priorities on paper makes them real* Motivational Quotes - To inspire the creative forces within* Goals Outlined - A goal unwritten is just a good idea* 7.5 inch x 9.25 inch pages to keep track of your priorities. This on-trend Daily Planner has daily spreads with plenty of space to write your to do lists, personal goals and appointments. The stylish and clean design will help you stay focused."
        ],
        "Description": [],
        "Details": {
            "Publisher": "Independently published (March 22, 2021)",
            "Language": "English",
            "Paperback": "100 pages",
            "ISBN 13": "979-8726353791",
            "Item Weight": "8.8 ounces",
            "Dimensions": "7.5 x 0.23 x 9.25 inches"
        }
    },
    {
        "Category": "Fashion",
        "Price": null,
        "Title": "Vegatos Women Push Up Underwire Bikini Polka Dot Two Piece Bathing Suit Navy M",
        "Features": [],
        "Description": [],
        "Details": {
            "Is Discontinued By Manufacturer": "No",
            "Package Dimensions": "8.1 x 7.5 x 3.2 inches; 6.24 Ounces",
            "Department": "womens",
            "Date First Available": "June 29, 2018"
        }
    },
    {
        "Category": "Camera & Photo",
        "Price": 97.8,
        "Title": "Minolta MD Tele Rokkor-X 135mm 1:3.5 Minolta Celtic Camera Lens",
        "Features": [
            "Made by Minolta",
            "135mm, 1:3.5",
            "Made in Japan",
            "Camer alens"
        ],
        "Description": [
            "Minolta MD Tele Rokkor-X 135mm 1:3.5 Minolta Celtic Camera Lens"
        ],
        "Details": {
            "Product Dimensions": "2 x 4 x 2 inches",
            "Item Weight": "1 pounds",
            "Item model number": "Minolta MD Tele Rokkor-X 135mm 1:3.5",
            "Best Sellers Rank": {
                "SLR Camera Lenses": 2940
            },
            "Is Discontinued By Manufacturer": "No",
            "Date First Available": "October 24, 2006",
            "Manufacturer": "Minolta",
            "Brand": "Minolta",
            "Focal Length Description": "135 mm",
            "Lens Type": "Telephoto",
            "Camera Lens Description": "135 millimetres",
            "Maximum Focal Length": "135"
        }
    }
]
```

### Citation
This is a very small and slightly transformed sample of data from https://amazon-reviews-2023.github.io/.
```
@article{hou2024bridging,
  title={Bridging Language and Items for Retrieval and Recommendation},
  author={Hou, Yupeng and Li, Jiacheng and He, Zhankui and Yan, An and Chen, Xiusi and McAuley, Julian},
  journal={arXiv preprint arXiv:2403.03952},
  year={2024}
}
```
