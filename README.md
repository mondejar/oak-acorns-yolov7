# Oak Acorns detector using YOLOv7
Description, dataset and weights to run inference of oak acorns detection using YOLOv7.

For a detailed explanation refer to the poster: https://www.researchgate.net/publication/370498503_Uso_de_deep_learning_y_deteccion_visual_para_el_conteo_automatico_en_el_aforo_de_bellota_de_encina

If you use this dataset or weights for your publications, please cite it as:
  
    @article{unknown,
    author = {Gómez-Giráldez, Pedro J. and Mondéjar-Guerra, Víctor M.},
    year = {2023},
    month = {04},
    pages = {},
    title = {Uso de deep learning y detección visual para el conteo automático en el aforo de bellota de encina}
    }

## How to run

### YOLOv7
Download YOLOv7 from: https://github.com/WongKinYiu/yolov7

### Donwload trained weights

Trained weights for YOLOv7 can be download from:
[best.pt](https://storage.googleapis.com/kaggle-data-sets/5293094/8801723/compressed/best.pt.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20240627%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240627T112155Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=067b04575cf2fb9c8a7f72e11a2453706738aacdb76eac3325e9f240994d9cdeb1ea0fde8c6cc4b935a29af3cabd2c7ebdb8178f9b0e1375abfd3f6edad8afefaf38dcebd97823b6b3d169d299badc8c577abb54c722a68ce183bd7b410a2cb68c32a864b4c89a47b2d11a2fbb0911049b2872aaa8715c1a342de99e1f17b3aafdbe71dc7a76f1e2f04c4474cc1f84f25e488d71ddf6fa34d010519c98ebc02e25d745aa8aa876c444650527c244fa8db589c3b15acbccf3a9c75dec080195be78199a39bf78da4ac08ca443e4c2de4eb8690a3d2cb140984da89402ca1e0b4344f1ead541b08d9b43420f677080ebf6fff1c6e3872bfad2fc8f1c47e119f74c)


### Dataset
The dataset and best weights can be download from: https://www.kaggle.com/datasets/mondejar/oak-acorns-detector

The dataset used in this train consist in 50 .png images with their corresponding annottation file. [Original images](https://storage.googleapis.com/kaggle-data-sets/5293094/8801723/compressed/original_img.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20240627%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240627T112411Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=75559d40da739d097df8f7689a327dd0e5e7413dcddae55dd0cccd29604017b55f93dc30e2a0321929bf058365a95ce37da4776dce9515fab7eb0f15e04a888f25ab1d32640f24485835cb92443e41d3b8d69b39cd0ec5fd49af3ffe5a0391dbf449886fd7d7ffd194e8d5e75926d361693b8b5aba11b9efffb729a250a277a5c2320164d0bbefe3c7bd4261e466e6e98adfd6790613b9ec3a965360d796bec542fb943c6fc5c9419e902d942dbc1b44bba38d668bb02554043e07c3a0c764ac5a6364ea98dba2a4f6b1563228910810d17502e1adeba18a70e67058fe1ec7bc0424289435e848c6891e2f8a4ef0c3bb867331f66f3ea8fc8091ae84d6e27f21) and [scaled images](https://storage.googleapis.com/kaggle-data-sets/5293094/8801723/compressed/img.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20240627%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240627T112347Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=851ae579c69bf4283624cb416a005c086be934b7accb758566b706126c0ca9842d18d45c538dac61dc2271f5b036cf4f0578df8fad974b0d6dc5a74763cca824b9bf4b480c390d584b90b2ad6aa3c24c72b3687c12c3c9fbb2c7c7d6638686f02f638870ecc6608b553971a715965abba9e484594743fccb6f497b55cc4afee90b807d4658f4608e3e2373db8100adfc52f2c99602ca079495ee9bc39b9d5900a6a81099de031cf75f541c70896f797206a13912a491c6750bb4717c43a2476fae0025f5af2312bf8a60a68bf4e731655073fb54dc150efddfdad72b07c8959c4261184c9659c0199e76babbd220973b38344fd3bca8664861b6845d946ae499) (1280x720) are provided.

# Results

Examples of inference tests:

![IMG_5622](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/cd14266d-14fc-4f98-b118-2c2ac5d08ab0)
![IMG_1196](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/2bfcd2e5-9c57-485d-abb3-d67819984981)
![IMG_1185](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/53493d13-d47e-47e9-bcfe-aa73051c8b75)
![IMG_1184](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/20ca9954-d14f-4765-a6f8-e6715e2819e3)
![IMG_1141](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/df825ec9-d876-4b0b-a29e-23750496b1ca)
![IMG_1122](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/37b83a00-f46d-4bae-9c89-b01708f18c01)
![IMG_1092](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/b7bad053-cbe0-4818-b84f-b5a834847e14)
![IMG_1091](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/33ebd40d-c4fd-4366-9c09-7f6295529689)
![IMG_0951](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/6bfd2389-690a-4b75-8364-deb67a3be1c9)
![IMG_0947](https://github.com/mondejar/oak-acorns-yolov7/assets/1508788/6e102e4b-803f-4a6f-85d4-270a176309f7)
