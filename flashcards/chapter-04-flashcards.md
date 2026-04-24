## Chapter 4: Giving Machines Eyes: Computer Vision on Azure — Flashcards

| # | Front (Question) | Back (Answer) |
|---|-----------------|---------------|
| 1 | What is image classification in computer vision? | The process of categorizing an entire image into predefined classes or labels (e.g., "cat", "dog", "car") |
| 2 | How does object detection differ from image classification? | Object detection identifies AND locates multiple objects within an image using bounding boxes, while classification only labels the entire image |
| 3 | What is Optical Character Recognition (OCR)? | Technology that extracts printed or handwritten text from images and documents, converting it into machine-readable text |
| 4 | What capabilities does Azure AI Vision service provide? | Pre-built image analysis including tagging, captioning, object detection, OCR, smart cropping, and adult content detection |
| 5 | When should you use Custom Vision instead of Azure AI Vision? | When you need to recognize domain-specific objects or scenarios not covered by pre-built models (e.g., specific product defects) |
| 6 | What two project types can you create in Custom Vision? | Image Classification (categorize whole images) and Object Detection (locate and identify objects within images) |
| 7 | What does Azure AI Face service detect? | Faces in images including attributes like age, emotion, glasses, facial hair, and head pose |
| 8 | What is spatial analysis in Azure AI Vision? | Video analytics capability that analyzes real-time video to detect people's presence and movement in physical spaces |
| 9 | What are common use cases for spatial analysis? | Occupancy counting, social distancing monitoring, queue management, and zone entry/exit detection |
| 10 | What minimum number of training images does Custom Vision recommend per class? | At least 15 images per class, though 50+ images provide better results |
| 11 | What does Azure AI Vision's "Read" API do? | Extracts text from images and documents using advanced OCR, supporting both printed and handwritten text |
| 12 | What is facial verification in Azure AI Face? | Comparing two faces to determine if they belong to the same person (1:1 matching) |
| 13 | What responsible AI consideration applies to Face service? | Limited Access policy requires approval for facial recognition features; some features like emotion detection are retired |
| 14 | What output does object detection provide for each detected object? | A bounding box (coordinates), a label/class name, and a confidence score |
| 15 | What are the two phases in building a Custom Vision model? | Training phase (upload and label images, train model) and Publishing phase (deploy model for predictions) |

### Key Terms

| Term | Definition |
|------|-----------|
| Image Classification | Assigning a single category label to an entire image based on its content |
| Object Detection | Identifying and locating multiple objects within an image with bounding boxes and labels |
| OCR (Optical Character Recognition) | Technology that converts images of text into machine-encoded text |
| Azure AI Vision | Pre-built Azure service providing image analysis, OCR, and spatial analysis capabilities |
| Custom Vision | Azure service for training custom image classification and object detection models with your own data |
| Azure AI Face | Service for detecting, recognizing, and analyzing human faces in images |
| Bounding Box | A rectangle defined by coordinates that outlines where an object is located in an image |
| Spatial Analysis | Computer vision capability that analyzes video streams to understand people's movement in physical spaces |

### Memory Tricks
- **"CLASS vs DETECT"**: Classification gives one CLASS to the whole image; Detection DETECTS multiple objects with boxes
- **"OCR = Oh, Characters Recognized!"**: Remember OCR turns image text into readable characters
- **"Pre-built = Vision, Custom = You-sion"**: Azure AI Vision is pre-built; Custom Vision is built by YOU for your needs
- **"FACE the Facts"**: Face service handles Faces, Age, Characteristics, and Emotions (with restrictions)
- **"Spatial = Space + People"**: Spatial analysis monitors SPACE and how PEOPLE move through it