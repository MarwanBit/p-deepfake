# p-deepfake: feature extraction of deepfake images
**Project Manager:** Danica Du (ddu@g.hmc.edu)

**Project Members:** Vani Sachdev, Marwan Bit, Eshaan Lumba, Austin Zang

Check out our [Notion page](https://flat-chanter-957.notion.site/P-Deepfake-7e47a5b07edf47f9b0cf05434c216a4e) for project details and updates.

## Directory tree structure
    ├── exploration                     # Notebooks from exploratory phase
    ├── data                            # Dataset of deepfake and real face images
    │   └── real                        # Real images
    │   └── fake                        # Deepfake images
    ├── analysis                        # Folder for the two points of analysis
    │   └── feature_point_analysis      # Feature point analysis
    │   │   └── output_data             # Algorithm output data
    │   │   │   └── full                # Output data for full-face images
    │   │   │   └── ...                 # Output data for each facial region   
    │   │   └── ...                     # Other notebooks
    │   └── feature_matching_analysis   # Feature matching analysis
    │   │   └── ...                     # Other notebooks 
    └── README.md