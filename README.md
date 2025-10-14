TMSD3-YOLOMD/
│
├── dataset/
│   └── TMSD-3/                         # 原始数据集 (Original dataset)
│
├── weights/
│   ├── YOLO-MD/                        # YOLO-MD 模型权重 (Detection model weights)
│   │   ├── YOLO-MD_NEU-DET_best.pt     # Model trained on NEU-DET dataset
│   │   └── YOLO-MD_TMSD-3_best.pt      # Model trained on TMSD-3 dataset
│   │
│   ├── SIPA/                           # SIPA 数据增强生成器权重 (StyleGAN3 Generators)
│   │   ├── NEU-DET/                    # NEU-DET 数据集生成器 (public dataset generators)
│   │   │   ├── crazing.pkl
│   │   │   ├── inclusion.pkl
│   │   │   ├── patches.pkl
│   │   │   ├── pitted_surface.pkl
│   │   │   ├── rolled_in_scale.pkl
│   │   │   └── scratches.pkl
│   │   │
│   │   └── TMSD-3/                     # TMSD-3 数据集生成器 (proposed dataset generators)
│   │       ├── fracture.pkl
│   │       ├── pothole.pkl
│   │       └── stick.pkl
│
└── README.md                           # 项目说明文件 (This file)
