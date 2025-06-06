<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Font Example</title>
    <!-- Google Fonts link -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }

        h1 {
            font-family: 'Roboto', sans-serif; /* Another font for headings */
        }
        nav a {
            display: block; /* Makes each link appear on a new line */
            margin-bottom: 10px; /* Adds spacing between links */
        }
        
        .tab-container {
            display: flex; /* Enable flexbox */
            justify-content: center; /* Center horizontally */
            align-items: center; /* Center vertically */
        }

        /* Style the clickable image */
        .tab img {
            width: 87px; /* Set the size of the image */
            height: 40px;
            border: none; /* Remove border */
            cursor: pointer; /* Show pointer on hover */
        }

        /* Optional hover effect */
        .tab img:hover {
            opacity: 0.8; /* Slight fade effect on hover */
        }

    </style>
</head>

<body>
    <header>
        <h1 style="text-align: center;">DX-Mamba: Exploring State Space Model for Dog X-ray Report Generation</h1>
    </header>

    <main>
        <p align="center">
          <img src="Rebuttal figures/validation.png" alt=" Table 1: Results comparisons of different methods on the Dog-Xray dataset validation set.">
        </p>
        <p align="center">Table 1: Results comparisons of different methods on the Dog-Xray dataset validation set.</p>
        
        <sub> Note: Normal template for Baseline 1: "THORAX: No abnormality is detected. SUMMARY: Clinically normal thoracic radiographs CONCLUSION: The results of this evaluation are negative for thoracic metastasis from reported carcinoma. The conclusions described in this report are based on the available information. If additional images (or other information) are obtained, then these conclusions might change." 
        Normal template for Baseline 2: "SUMMARY OF FINDINGS:  No abnormality is detected. IMPRESSION:  Clinically normal thoracic radiographs. The results of this evaluation are negative for thoracic metastasis. DESCRIPTION OF FINDINGS:  Both lungs are well expanded and aerated. The thoracic lymph nodes (cranial-mediastinal, sternal, and tracheobronchial) are normal. No nodule or mass is detected. No aggressive bone lesion is detected. No abnormality is detected in the cardiac silhouette, lower airway, mediastinum, and diaphragm." </sub>
        
        <p align="center">
          <img src="Rebuttal figures/test.png" alt=" Table 2: Results comparisons of different methods on the Dog-Xray dataset test set.">
        </p>
        <p align="center">Table 2: Results comparisons of different methods on the Dog-Xray dataset test set.</p>
        
        <p align="center">
          <img src="Rebuttal figures/accuracy.png" alt=" Table 3: Results comparisons (× 100) of accuracy using different methods on the Dog X-ray validation and test sets.">
        </p>
        <p align="center">Table 3: Results comparisons (× 100) of accuracy using different methods on the Dog X-ray validation and test sets.</p>
        
        <p align="center">
          <img src="Rebuttal figures/Confusion matrices.png" alt=" Figure 1: Classification accuracy confusion matrices on Dog X-ray validation and test sets.">
        </p>
        <p align="center">Figure 1: Classification accuracy confusion matrices on Dog X-ray validation and test sets.</p>
        
        
        <p align="center">
          <img src="Rebuttal figures/12550_analysis.png" alt=" Figure 2: Interpretability analysis 12550 (Abnormal).">
        </p>
        <p align="center">Figure 2: Interpretability analysis 12550 (Abnormal).</p>
        
        
        <p align="center">
          <img src="Rebuttal figures/12217_analysis.png" alt=" Figure 3: Interpretability analysis 12217 (Normal).">
        </p>
        <p align="center">Figure 3: Interpretability analysis 12217 (Normal).</p>
        
        <p align="center">
          <img src="Rebuttal figures/11389_analysis.png" alt=" Figure 4: Interpretability analysis 11389 (Abnormal).">
        </p>
        <p align="center">Figure 4: Interpretability analysis 11389 (Abnormal).</p>
        
        <p align="center">
          <img src="Rebuttal figures/11077_analysis.png" alt=" Figure 5: Interpretability analysis 11077 (Normal).">
        </p>
        <p align="center">Figure 5: Interpretability analysis 11077 (Normal).</p>

<footer>
  <p>&copy; 2025 Anonymous-ab. All rights reserved.</p>
</footer>




