# Overwhelmed by Technical Specifications, I Leveraged Data to Identify the Ideal Robot Vacuum

Have you ever tried buying new tech? The excitement fades after opening ten tabs and spending three hours lost in specs, jargon, and conflicting reviews. Suction power in "Pascals"? Battery life in "minutes"? What does it all mean? I faced this frustration while searching for a robot vacuum and decided to take a different approach.

Most reviews aim to find the "best" product, but "best" depends on the user. A student in a small apartment needs a different vacuum than a family with two dogs and a three-story house. Instead of adding more reviews, I turned to data to build a system that matches vacuums to specific needs.

## The "Vacuum Value Score" Concept

Rather than comparing raw specs, I developed the "Vacuum Value Score"—like a custom recipe where features (suction, battery, smart features) are weighted based on the user. I defined four buyer personas:

1. **Pet Owner**: Prioritizes strong suction for fur, a HEPA filter for allergens, and a large dustbin.
2. **Tech Enthusiast**: Values smart features like Lidar mapping, Wi-Fi, voice control, and a feature-rich app.
3. **Budget Buyer**: Seeks the best performance (suction, battery) for the lowest price.
4. **All-Rounder**: Wants a balanced vacuum with decent suction, battery, and maybe mopping, without overspending.

Each persona has a tailored scoring system, so a vacuum might score high for a Pet Owner but low for a Tech Enthusiast—that’s by design..

## Exploring the Market Landscape

Before scoring, I analyzed the robot vacuum market using a heatmap to identify feature correlations. Redder squares indicate stronger relationships. As expected, price increased with features like self-emptying and suction power, offering a clear view of trade-offs.

![image](https://github.com/user-attachments/assets/bc69cab2-c6d5-49f2-af51-42667a265fdc)

## Discovering Market "Tribes"

After scoring each vacuum for every persona, I used clustering to find natural market segments. The data revealed four distinct groups:

- **Budget Warriors**: Low price with solid performance.
- **Mid-Range All-Rounders**: Higher price with balanced features.
- **Niche Specialists**: Mid-priced, excelling in one area (e.g., mopping or smarts).
- **Premium Powerhouses**: High price with top scores across all categories.

![image](https://github.com/user-attachments/assets/82ac2f5d-5ad3-427e-9cbe-68768ce8a170)

This uncovered the market’s hidden structure beyond individual products.

![image](https://github.com/user-attachments/assets/03bfa7c0-831c-4232-bd79-88288e9ba995)

## Interactive Dashboard: A Tool for All

I turned my findings into an interactive dashboard. With a dropdown, you can select your persona (Pet Owner, Tech Enthusiast, Budget Buyer, or All-Rounder) to see the top 15 vacuums tailored to your needs.

![image](https://github.com/user-attachments/assets/fa7592e3-4ea5-4a36-8078-74fcc95b0537)

## Key Takeaways

This project began with the frustration of tech shopping. Using data, I cut through the confusion and learned there’s no universal "best" vacuum—only the right one for you. This highlights data’s power to simplify decisions, turning charts and algorithms into practical tools for everyday problems.

## Data Source
- [Kaggle Dataset](https://www.kaggle.com/datasets/mustafaemregk/robot-vacuum-cleaner-dataset)

## Notebook
- [Kaggle Notebook](https://www.kaggle.com/code/vikramlingam/robot-vacuum-value-score).
