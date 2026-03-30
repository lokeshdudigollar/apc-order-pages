```
image-service/
│
├── src/
│ ├── handlers/
│ │ ├── upload_image.py
│ │ ├── list_images.py
│ │ ├── get_image.py
│ │ └── delete_image.py
│ │
│ ├── services/
│ │ └── image_service.py
│ │
│ ├── repositories/
│ │ ├── dynamodb_repository.py
│ │ └── s3_repository.py
│ │
│ ├── models/
│ │ └── image_model.py
│ │
│ └── utils/
│ └── pagination.py
│ └── image_service_factory.py
│ 
|
├── scripts/
│ ├── package.ps1
│ ├── build-layer.ps1
│ └── setup_localstack.ps1
│ └── start.ps1
│ └── watch.ps1
|
├── requirements.txt
├── docker-compose.yml
└── README.md
```
