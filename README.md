TMSD3-YOLOMD/
│
├── dataset/
│   └── TMSD-3/                         # Original dataset
│
├── weights/
│   ├── YOLO-MD/                        # Detection model weights
│   │   ├── YOLO-MD_NEU-DET_best.pt     # Model trained on NEU-DET dataset
│   │   └── YOLO-MD_TMSD-3_best.pt      # Model trained on TMSD-3 dataset
│   │
│   ├── SIPA/                           # StyleGAN3 Generators
│   │   ├── NEU-DET/                    # NEU-DET public dataset generators
│   │   │   ├── crazing.pkl
│   │   │   ├── inclusion.pkl
│   │   │   ├── patches.pkl
│   │   │   ├── pitted_surface.pkl
│   │   │   ├── rolled_in_scale.pkl
│   │   │   └── scratches.pkl
│   │   │
│   │   └── TMSD-3/                     # TMSD-3 proposed dataset generators
│   │       ├── fracture.pkl
│   │       ├── pothole.pkl
│   │       └── stick.pkl
│
└── README.md                           # This file
