# Neural Style Transfer with TensorFlow and Gradio  

This repository demonstrates a **Neural Style Transfer** application built using **TensorFlow** and **Gradio**. The application enables users to apply artistic styles to images seamlessly via an interactive web interface.  

---

## Features  
- **Pre-Trained Model**: Uses TensorFlow Hub's pre-trained model for efficient and high-quality stylizations.  
- **User-Friendly Interface**: Gradio-powered interface for quick image uploads and transformations.  
- **Downloadable Results**: Stylized images can be downloaded instantly from the interface.  
- **Efficient Processing**: Supports GPU acceleration for faster execution.  

---

## Demo  
### Steps:  
1. Upload a **content image** (e.g., a portrait or landscape).  
2. Upload a **style image** (e.g., an artwork or pattern).  
3. Stylize the content image using the style image.  
4. Download the final stylized output directly.  

---

## Installation  

### 1. Clone the Repository  
```bash  
gh repo clone Caspian4/Workshop
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```
### 3. (Optional) Configure GPU
Ensure TensorFlow is configured to utilize a GPU for faster processing.

---

## Usage

### 1. Run the Application
```bash
python app.py
```
### 2. Access the Interface
Open the **local URL** provided by Gradio in your web browser.

---

### 3. Upload Images
- **Content Image**: Upload the base image that will be stylized.
- **Style Image**: Upload an artwork or pattern to apply as the style.

---

### 4. Generate and Download
- Click the **Stylize** button to generate the output.
- Download the **stylized image** directly from the interface.

---

## Example
| **Content Image**   | **Style Image**    | **Stylized Image** |
|----------------------|--------------------|---------------------|
|![Screenshot 2024-12-06 001256](https://github.com/user-attachments/assets/4430f861-aa19-4b1a-b3a6-228c1e6426e9)|![Screenshot 2024-12-06 001224](https://github.com/user-attachments/assets/a20c9862-ceac-4502-8b2d-d579cbdae1ba)|![Screenshot 2024-12-06 001349](https://github.com/user-attachments/assets/771140c6-f40a-410a-b9e9-d582e7b1af02)|



---

## Future Improvements

- **Real-Time Stylization**: Optimize performance for faster processing, even on high-resolution images.
- **Enhanced Customization**: Add features like adjustable style intensity, multi-style blending, and automatic alignment.
- **Cloud Hosting**: Deploy the application on a scalable cloud platform (e.g., AWS, GCP) for global accessibility.

---

## Challenges Faced

- **High-Resolution Processing**: Large images required significant computational resources.
- **Style-Content Alignment**: Occasionally, mismatches between content and style images caused minor artifacts.
- **Processing Time**: While GPU acceleration improved efficiency, further optimization is needed for real-time results.

---

## References

- [TensorFlow Hub: Arbitrary Image Stylization Model](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2)
- [Gradio Documentation](https://gradio.app)
- Gatys et al., _A Neural Algorithm of Artistic Style_ ([arXiv:1508.06576](https://arxiv.org/abs/1508.06576))
- [ChatGPT by OpenAI](https://openai.com)
- [TensorFlow Documentation](https://www.tensorflow.org/)

