# DSA Transparency Database - Custom Dataset

## Overview

This repository contains a custom dataset compiled from the DSA Transparency Database. The dataset focuses on Statements of Reasons (SoRs) related to content removal due to violations of Terms of Service (ToS) across three major platforms: Booking.com, Reddit, and LinkedIn. These platforms represent diverse online environments, providing a broad view of ToS enforcement practices.

## Data Description

The dataset includes 7000 SoRs, distributed across the platforms as follows:
- **Booking.com:** 3000 SoRs
- **Reddit:** 2000 SoRs
- **LinkedIn:** 2000 SoRs

Each SoR contains the following attributes:
- **UUID:** A unique identifier for each SoR.
- **Incompatible Content Ground:** The reason provided for why the content violated the ToS.
- **Incompatible Content Explanation:** The explanation of the violation.
- **Decision Facts:** Facts relevant to the decision to remove the content.

### Platforms and Selection Criteria

- **Booking.com** (e-commerce/travel industry)
- **Reddit** (social media, user-generated content)
- **LinkedIn** (professional networking)

The dataset covers SoRs from **March 2024 to August 2024**. The selection was made to maintain balance across the three platforms and capture a representative sample of content moderation decisions over the specified period.

## Usage

1. **Data Access:** The dataset is stored in CSV files under the `/data` folder. Each file contains SoRs for the respective platform.
2. **Basic Analysis:** Use the `analysis_script.py` in the `/analysis` folder to perform basic statistical analysis or preprocessing of the dataset.

## Citation

If you use this dataset for your research, please cite the source as follows:

```
@dataset{dsa_transparency_dataset_2024,
    title={DSA Transparency Database - Custom Dataset on ToS Violations},
    year={2024},
    platforms={Booking.com, Reddit, LinkedIn},
    source={DSA Transparency Database},
    period={March-August 2024}
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue in this repository or reach out to the dataset maintainers at support@example.com.

---

