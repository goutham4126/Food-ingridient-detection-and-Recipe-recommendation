# Food-ingridient-detection-and-Recipe-recommendation
Detects ingridients using ensemble model ( faster r-cnn and yolov8 ) and gives recipe suggestions using AI


Now-a-days people find it difficult to make meals and dishes that support a healthy lifestyle. 

This project simplifies cooking with an AI-driven system that identifies ingredients through 

images and recommends personalized recipes. Users upload a photo of their available 

ingredients, and the system accurately detects them using an ensemble model that combines 

YOLOv8 and Faster R-CNN. By fusing the detections from both models using NMS Fusion and 

the IoU metric, the system ensures precise ingredient detection. It also considers dietary 

restrictions, allergies, and preparation time, tailoring recipe recommendations to individual 

preferences. Unlike traditional recipe searches, this automated approach saves time and effort, 

learning user preferences to offer even better recommendations over time. Intelligent 

ingredient pairing maximizes meal options, reduces food waste, and promotes healthier eating 

habits. Future expansions could include smart kitchen connectivity, voice assistants, and 

multilingual support, making the system even more intuitive and accessible for home cooks 

worldwide.



Entire code is available at : https://drive.google.com/drive/folders/1w_Ukh1zd9uI_1KOYMRO_FFqD5RoYFV7w?usp=sharing

First, run the backend server:

```bash
cd server
python -m venv venv
venv\Scripts\activate

pip install flask flask-cors pillow ultralytics numpy
python -m pip install --upgrade pip
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

python app.py
```
Second, run the nextjs applicatiom:

```bash
   npm run dev
   or
   pnpm run dev
```

Architecture
![image](https://github.com/user-attachments/assets/375986cf-4d56-4939-8f9e-5f832eb8f13f)

![WhatsApp Image 2025-03-28 at 12 06 49_ddd18a1c](https://github.com/user-attachments/assets/cf2f452f-3f30-45c7-9b11-a159b7f44bff)
![WhatsApp Image 2025-03-28 at 12 06 48_b3255e52](https://github.com/user-attachments/assets/cd80cf71-9bfe-441f-8bfe-6da5102ed87f)



![WhatsApp Image 2025-03-28 at 12 00 03_e00da180](https://github.com/user-attachments/assets/697e9ebc-c342-4246-85fe-8dca4ff3d4b5)
![WhatsApp Image 2025-03-28 at 12 00 04_bc251f57](https://github.com/user-attachments/assets/6454ae13-482c-4c01-99f1-b026943f81a7)
![WhatsApp Image 2025-03-28 at 12 00 04_76a3124a](https://github.com/user-attachments/assets/1df9357d-d02d-4b97-bb30-ebba0f2e8afb)
![WhatsApp Image 2025-03-28 at 12 00 04_da240b13](https://github.com/user-attachments/assets/b6ed3bc8-2f96-46f6-8e60-6ae93f0c94cf)
![WhatsApp Image 2025-03-28 at 12 00 05_1bdbb95c](https://github.com/user-attachments/assets/ae6c5f4d-2845-41d6-8e68-1726312a9001)
![WhatsApp Image 2025-03-28 at 12 00 05_e88366e2](https://github.com/user-attachments/assets/bc9baecd-e3cc-4439-a216-63e64c93c65c)
![WhatsApp Image 2025-03-28 at 12 00 05_2853ed5b](https://github.com/user-attachments/assets/42ff0e17-cfa1-46f2-80b7-b645e8b610f3)
![WhatsApp Image 2025-03-28 at 12 00 06_91522bbe](https://github.com/user-attachments/assets/661f61a5-3705-4890-b753-5efa17a6e3c3)






