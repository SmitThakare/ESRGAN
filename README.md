# Reviving Ancestral Echoes: AI-Driven Digital Preservation of Petroglyphs

## Overview
This project focuses on the preservation of ancient petroglyphs, which are valuable cultural treasures at risk of degradation due to environmental factors and human interference. Traditional preservation methods can be invasive and are often limited in scope. To overcome these challenges, this project introduces an innovative, non-invasive approach using Artificial Intelligence (AI) and Generative Adversarial Networks (GANs) to enhance the preservation and restoration of petroglyph images. This AI-driven technique is scalable and aims to ensure that these ancient artworks are preserved for future generations, contributing to the advancement of digital archaeology.

## Problem Statement
Petroglyphs, as irreplaceable records of ancient cultures, face a significant threat from natural erosion, climate change, and vandalism. Traditional methods of preservation, such as physical restoration and replication, are often intrusive and may not be applicable across different sites. There is an urgent need for non-invasive, scalable methods to digitally preserve and restore these artifacts, ensuring their longevity without compromising their integrity.

## Project Objectives
- **Develop Non-Invasive Techniques:** Use AI to create digital restoration methods that do not interfere with the physical structure of petroglyphs.
- **Scalability:** Ensure the methods can be applied to various sites and types of petroglyphs.
- **Digital Preservation:** Create high-quality digital replicas that can be used for educational and research purposes, as well as in virtual reconstructions.
- **Enhance Restoration:** Utilize GANs to reconstruct degraded or partially lost petroglyphs, restoring them to their original state.

## Methodology
### AI and Generative Adversarial Networks (GANs)
The project leverages AI, particularly Generative Adversarial Networks (GANs), to enhance the preservation process. GANs are utilized to:

1. **Image Enhancement:** Improve the quality of petroglyph images by removing noise and restoring missing details.
2. **Restoration of Degraded Areas:** Reconstruct areas of petroglyphs that have been eroded or damaged, based on patterns learned from intact areas.
3. **Non-Invasive Processing:** Ensure that all enhancements and restorations are digital, leaving the physical petroglyphs untouched.

### Tools and Techniques
- **AI Models:** The project uses the Enhanced Super-Resolution Generative Adversarial Network (ESRGAN) model for high-quality image restoration.
- **Data Collection:** A large dataset of petroglyph images is collected, including images of both well-preserved and degraded petroglyphs.
- **Training Process:** The AI models are trained on this dataset to learn the patterns and styles of the petroglyphs, enabling them to generate restored versions of degraded images.

## Prerequisites

To run this project, ensure you have the following installed:

- Python 3.x
- `pandas`
- `numpy`
- `tensorflow`
- `keras`
- `opencv-python`
- `Pillow`
- `scikit-learn`



## Outputs

- **Restored Images:** High-resolution, digitally restored versions of the original petroglyphs.
- **Model Performance Metrics:** Metrics evaluating the accuracy and quality of the restoration process.

| Method     | Training Dataset | Set5         | Set14        | BSD100       | Urban100     | Manga109     |
|------------|------------------|--------------|--------------|--------------|--------------|--------------|
| SRCNN      | 291              | 30.48/0.8628 | 27.50/0.7513 | 26.90/0.7101 | 24.52/0.7221 | 27.58/0.8555 |
| EDSR       | DIV2K            | 32.46/0.8968 | 28.80/0.7876 | 27.71/0.7420 | 26.64/0.8033 | 31.02/0.9148 |
| RCAN       | DIV2K            | 32.63/0.9002 | 28.87/0.7889 | 27.77/0.7436 | 26.82/0.8087 | 31.22/0.9173 |
| RRDB (used)| DF2K             | 32.73/0.9011 | 28.99/0.7917 | 27.85/0.7455 | 27.03/0.8153 | 31.66/0.9196 |


## Sample Input
<img width="240" alt="Screenshot 2024-08-21 at 4 17 05 PM" src="https://github.com/user-attachments/assets/a80df9a7-9611-4bf0-82f4-7403ee9352a5">

## Output
<img width="808" alt="Screenshot 2024-08-21 at 4 17 32 PM" src="https://github.com/user-attachments/assets/693ae672-c898-48ac-b9f3-727ae0a79c03">



## Conclusion

This project presents a novel approach to preserving ancient petroglyphs through AI-driven digital restoration. By using GANs, the project offers a non-invasive and scalable solution to protect these cultural artifacts from degradation, ensuring that they remain a valuable resource for future generations. This work not only contributes to the field of digital archaeology but also opens up new possibilities for the preservation of cultural heritage worldwide.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the digital archaeology community for their inspiration and support.
- Data and images sourced from various cultural heritage databases and archives.
