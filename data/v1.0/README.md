# **NDIS Database Analysis (2010-2025)**

## **Dataset Overview**

This dataset contains historical statistics from the **FBI's National DNA Index System (NDIS)**, parsed from archived snapshots of FBI web pages (2010–2025). It tracks the growth of DNA profiles (offender, arrestee, forensic) across U.S. jurisdictions, lab participation, and investigations aided.

## **Dataset Files**

-   **Primary Data**: **`output/ndis/ndis_fixed.csv`** (CSV format)

-   **Analysis Script**: **`analysis/ndis_scraping.qmd`**

### **Key Variables**

-   **`jurisdiction`**: U.S. state/territory (e.g., California, FBI).

-   **`offender_profiles`**: Convicted offender DNA records.

-   **`arrestee_profiles`**: Arrestee DNA records (post-2010).

-   **`forensic_profiles`**: Crime scene DNA profiles.

-   **`ndis_labs`**: Number of participating labs.

-   **`investigations_aided`**: Cases assisted by DNA matches.

-   **`year`**: Year of data collection.

## **Data Sources**

-   **Primary Source**: FBI NDIS public reports (archived via Wayback Machine).

-   **Processing**: Cleaned, standardized, and validated using Python/R pipelines.