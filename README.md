#  Netflix Content Strategy & Intelligence Dashboard

An interactive Business Intelligence (BI) application built in Tableau analyzing a global catalog of 8,807 streaming titles. This project transitions raw content logs into an executive-level decision tool exploring asset volume, regional variations, and long-term production cycles.

 **Live Interactive Dashboard:** [View Live on Tableau Public](https://public.tableau.com/shared/SJSG7BY22?:display_count=n&:origin=viz_share_link)

---

##  Key Business Insights

* **The Movie vs. TV Show Volume Anchor:** Feature-length films heavily dominate the catalog at roughly **70% of total volume**, proving they remain the foundational library anchor compared to TV Shows (30%).
* **The Post-2019 Production Cliff:** Content additions peaked sharply in **2018–2019** before experiencing a steep decline through 2021. This data pattern directly captures the impact of global pandemic filming disruptions and industry-wide supply chain freezes.
* **Target Audience Demographics:** Mature Audiences (TV-MA) and Teens (TV-14) represent the largest content pillars. This confirms Netflix's strategic focus on adult subscriber retention over family-oriented programming.
* **Regional Market Variance:** Using the interactive filters highlights that regional hubs like India showcase an extreme strategic preference for feature films over television series compared to Western markets.

---

##  Technical Implementation Details

* **Layout & Container Design:** Built using a zero-overlap, tiled vertical container grid framework ensuring rigid UI scaling across diverse screen resolutions.
* **Typography & Hierarchy:** Cleansed default database technical naming conventions (e.g., hiding raw `.csv` field expressions) and implemented a bold, distinct font size hierarchy.
* **Brand-Aligned Palette:** Rejected software-default color schemas for an intentional, premium 2-color brand theme (Netflix Red `#E50914` vs. Dark Charcoal) for instantaneous cross-chart visual mapping.
* **Dashboard Interactivity:** Implemented dynamic country dropdown controls and global worksheet action filters allowing seamless dashboard cross-filtering on a click.

---

##  Dataset Source
Data sourced from Kaggle's public catalog tracking historical Netflix movie and television uploads.

