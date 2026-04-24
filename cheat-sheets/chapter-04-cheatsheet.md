## Chapter 4: Giving Machines Eyes: Computer Vision on Azure — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Image Classification | Assigns labels/categories to entire images based on content |
| Object Detection | Identifies and locates multiple objects within an image with bounding boxes |
| OCR (Optical Character Recognition) | Extracts printed or handwritten text from images and documents |
| Facial Detection & Analysis | Detects faces and analyzes attributes like age, emotion, glasses |
| Azure AI Vision | Pre-built service for common vision tasks (analyze, read, detect) |
| Custom Vision | Train your own image classification or object detection models |
| Azure AI Face | Specialized service for face detection, verification, and identification |
| Spatial Analysis | Analyzes video streams to detect people movement and interactions |

### Key Syntax / Commands
```
# Azure AI Vision endpoint pattern
https://<resource-name>.cognitiveservices.azure.com/vision/v3.2/analyze

# Common API parameters
visualFeatures=Categories,Tags,Description,Objects,Faces
details=Celebrities,Landmarks
```

### Common Patterns
**Pattern 1: Pre-built vs Custom**
Use Azure AI Vision for generic tasks → Use Custom Vision when you need domain-specific recognition

**Pattern 2: Service Selection**
General analysis → AI Vision | Face-specific → AI Face | Custom needs → Custom Vision

### Things to Remember
✅ Azure AI Vision handles most common scenarios without training
✅ Custom Vision requires minimum 15 images per tag (50+ recommended)
✅ Face service requires approval for identification features (responsible AI)
❌ Don't use image classification when you need to locate objects—use object detection instead

### Quick Quiz
1. Which service for detecting products on store shelves? → **Custom Vision** (domain-specific)
2. Classification vs Detection difference? → **Classification labels whole image; Detection locates objects with coordinates**
3. Minimum images for Custom Vision training? → **15 per tag (50+ recommended)**