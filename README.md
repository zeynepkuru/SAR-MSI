# SAR-MSI




## Model Performance Comparison

| Backbone | Encoder   | Optimizer | Loss Function      | Augmentation | Batch Size | Learning Rate | Test Loss | F1 Score | IoU   | Precision | Recall | n |
|----------|-----------|-----------|--------------------|--------------|------------|---------------|-----------|----------|-------|-----------|--------|---|
| UNet     | ResNet32  | Adam      | CrossEntropyLoss   | -----        | 8          | 1.00E-04      | 0.8556    | 0.4706   | 0.366 | 0.5013    | 0.4534 | 1 |
| UNet     | ResNet50  | Adam      | CrossEntropyLoss   | -----        | 8          | 1.00E-04      | 0.5737    | 0.5734   | 0.471 | 0.6278    | 0.5545 | 2 |
| Unet++   | ResNet50  | Adam      | CrossEntropyLoss   | -----        | 8          | 1.00E-03      | 0.2465    | 0.9232   | 0.860 | 0.9446    | 0.9045 | 4 |
| Unet++   | ResNet50  | Adam      | CrossEntropyLoss   | -----        | 16         | 0.001         | 0.2742    | 0.9535   | 0.912 | 0.9728    | 0.9368 | 5 |
| Unet++   | ResNet50  | Adam      | CrossEntropyLoss   | -----        | 32         | 1.00E-03      | 0.3166    | 0.9376   | 0.884 | 0.9575    | 0.9202 | 6 |
| Unet++   | ResNet50  | Adam      | CrossEntropyLoss   | -----        | 32         | 0.0001        | 0.5293    | 0.8613   | 0.765 | 0.9120    | 0.8242 | 7 |
| Unet++   | ResNet101 | Adam      | CrossEntropyLoss   | -----        | 16         | 1.00E-03      | 0.2616    | 0.9409   | 0.890 | 0.9592    | 0.9247 | 8 |
