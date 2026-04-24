## Chapter 4: Giving Machines Eyes: Computer Vision on Azure — Practice Questions

### Multiple Choice

**Q1.** Which Azure service would you use to train a model that can recognize specific products on store shelves that are unique to your business?

A) Azure AI Vision service
B) Azure AI Face service
C) Custom Vision
D) Spatial Analysis

<details>
<summary>Answer</summary>

**Correct: C**

Custom Vision allows you to train custom image classification and object detection models using your own images. Azure AI Vision provides pre-built models for general scenarios, Azure AI Face is specifically for facial analysis, and Spatial Analysis is designed for video analysis of people's movements.

</details>

---

**Q2.** A company needs to extract text from scanned receipts and invoices. Which computer vision capability should they use?

A) Image classification
B) Object detection
C) Optical Character Recognition (OCR)
D) Facial detection

<details>
<summary>Answer</summary>

**Correct: C**

Optical Character Recognition (OCR) is specifically designed to extract printed or handwritten text from images, making it ideal for reading text from scanned documents like receipts and invoices. Image classification categorizes images, object detection locates objects, and facial detection identifies faces.

</details>

---

**Q3.** What is the primary difference between image classification and object detection?

A) Image classification works only with photos, object detection works with videos
B) Image classification assigns labels to entire images, object detection locates and identifies multiple objects with bounding boxes
C) Image classification is faster than object detection
D) Object detection only works with pre-trained models

<details>
<summary>Answer</summary>

**Correct: B**

Image classification assigns one or more labels to an entire image (e.g., "beach scene"), while object detection identifies specific objects within an image and provides bounding boxes showing their exact locations. Both can work with photos or video frames, and both can use custom or pre-trained models.

</details>

---

**Q4.** Which Azure service would be most appropriate for monitoring how many people are waiting in line at a store entrance using a security camera?

A) Custom Vision
B) Azure AI Face service
C) Spatial Analysis
D) Image Classification

<details>
<summary>Answer</summary>

**Correct: C**

Spatial Analysis is designed for analyzing video streams to understand how people move through and interact with physical spaces. It can count people in areas, detect queue lengths, and monitor social distancing. The other options are designed for still images or different purposes like facial identification.

</details>

---

**Q5.** Azure AI Face service can detect which of the following attributes from a face in an image?

A) The person's name and address
B) Estimated age, emotion, and whether glasses are worn
C) The person's exact birth date
D) Medical conditions and health status

<details>
<summary>Answer</summary>

**Correct: B**

Azure AI Face service can detect facial attributes including estimated age, emotional expression, head pose, presence of glasses, and facial landmarks. It cannot determine personal identifying information like names or addresses, exact birth dates, or medical conditions without being explicitly trained and having appropriate data.

</details>

---

### True / False

**Q6.** Azure AI Vision service requires you to train a custom model before you can analyze any images. — **True / False**

<details>
<summary>Answer</summary>

**False**

Azure AI Vision service comes with pre-built models that work immediately without any training. You can analyze images for objects, tags, descriptions, and more right out of the box. Custom Vision is the service you would use when you need to train models for specific use cases not covered by the pre-built capabilities.

</details>

---

**Q7.** OCR can extract text from both printed documents and handwritten notes. — **True / False**

<details>
<summary>Answer</summary>

**True**

Optical Character Recognition (OCR) in Azure AI Vision can recognize and extract both printed text (like typed documents) and handwritten text. The service uses advanced machine learning models to handle various handwriting styles, though accuracy may vary depending on the legibility of the handwriting.

</details>

---

### Short Answer

**Q8.** Explain what a bounding box is in the context of object detection and why it is useful.

<details>
<summary>Answer</summary>

A bounding box is a rectangle drawn around a detected object in an image, defined by coordinates that specify its position and size. It is useful because it shows exactly where each object is located within the image, allows applications to understand the spatial relationship between objects, and enables tasks like counting items, measuring distances, or triggering actions when objects appear in specific areas.

</details>

---

**Q9.** Name two real-world scenarios where Azure AI Face service could be used in a business application.

<details>
<summary>Answer</summary>

Possible answers include: (1) Identity verification for secure access control or login systems, (2) Customer sentiment analysis in retail by detecting emotions, (3) Attendance tracking in workplaces or events, (4) Photo organization by grouping similar faces, (5) Age verification for restricted content or products, (6) Personalized customer experiences based on returning visitor recognition.

</details>

---

### Scenario-Based

**Q10.** A museum wants to create an interactive exhibit where visitors can point their phone camera at a painting and receive information about the artwork, including the title, artist, and historical context. The museum has 500 unique paintings in their collection. Which Azure computer vision services would you recommend, and how would they work together to create this solution?

<details>
<summary>Answer</summary>

The recommended solution would combine **Custom Vision** and potentially **Azure AI Vision** services:

1. **Custom Vision** would be the primary service. You would train a custom image classification or object detection model using images of all 500 paintings. Each painting becomes a class that the model learns to recognize.

2. When a visitor points their camera at a painting, the app sends the image to Custom Vision, which identifies which specific painting is being viewed.

3. Once identified, the app retrieves the corresponding information (title, artist, historical context) from a database and displays it to the visitor.

4. **Azure AI Vision** could optionally be used to provide additional features like generating automatic descriptions of the painting's visual content or detecting specific elements within the artwork.

This approach works because Custom Vision excels at recognizing specific items when trained with your unique dataset, while pre-built services cannot identify specific paintings from a private collection.

</details>