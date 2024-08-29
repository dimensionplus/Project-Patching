# Project-Patching

AI 作為強大的主觀工具，可能抑制文化多樣性與具詮釋歷史的話語權，由上而下的文化滲透方式，使得 AI 的發展和應用不只是科技問題，更是文化問題。  

在主觀 AI 偏見所生成的資料將產生回音室效應（Echo chamber），無意識地複製或加強偏見，將擴大文化與未來敘事產生的偏見影響。  

本計畫為抵抗 AI 偏見，透過各地區域共同參與來增強資料庫的多樣性和代表性，解決 AI 的偏見問題。包括收集和整合來自不同文化背景、不同地理位置和不同社會經濟群體的資料，訓練生成，以確保 AI 系統能夠理解並適切反應的人類文化。  

AI, as a powerful subjective tool, may suppress cultural diversity and the discourse power of interpretive history. This project aims to counter AI bias by enhancing the diversity and representativeness of the database through collaborative participation from various regions. It involves collecting and integrating data from different cultural backgrounds, geographical locations, and socioeconomic groups to train the AI system, ensuring it understands and appropriately responds to human culture.


## Regional cultural themes Models

豬血糕（台灣）  
血鬆餅（芬蘭）  
血腸（芬蘭）  

Pig Blood Cake (Taiwan)  
Blood Pancake (Finland)  
Blood Sausage (Finland)  

## Introduction
本計畫希望透過各地區域共同參與來增強資料庫的多樣性和代表性，解決 AI 的偏見問題。包括收集和整合來自不同文化背景、不同地理位置和不同社會經濟群體的資料，訓練生成，以確保 AI 系統能夠理解並適應更廣泛的人類經驗。目前全球已有數個訓練據點，包含：台灣、香港、芬蘭、德國等。  

透過 [kohya_ss](https://github.com/bmaltais/kohya_ss) 訓練LoRA模型，模型可使用在 [Stable Diffusion](https://github.com/AUTOMATIC1111/stable-diffusion-webui) 、[ComfyUI](https://github.com/comfyanonymous/ComfyUI) 等開源軟體。模型訓練方式請參考下方的[訓練工具包](#how-to-train-a-new-image-model)，模型使用規範會補充在上方資料夾中。

This project aims to enhance the diversity and representativeness of the database through regional collaboration to address AI bias. It involves collecting and integrating data from various cultural backgrounds, geographic locations, and socio-economic groups to train generative models, ensuring AI systems can better understand and adapt to a broader range of human experiences. Currently, there are several training sites worldwide, including Taiwan, Hong Kong, Finland, and Germany.

The LoRA models trained through [kohya_ss](https://github.com/bmaltais/kohya_ss) can be used in open-source software like [Stable Diffusion](https://github.com/AUTOMATIC1111/stable-diffusion-webui) and [ComfyUI](https://github.com/comfyanonymous/ComfyUI). For details on how to train the models, please refer to the [training toolkit](#how-to-train-a-new-image-model) below. The model usage guidelines will be added to the top-level folder.


## How to train a new image model?
訓練工具包：Link  
Training Tool Kit：Link

## Credit

創作者：Dimension Plus  
計畫主持人：蔡宏賢  
製作人：王思雅  
技術統籌：李子臻  
技術支持：韓家俊、黃子祐  
製作團隊：蔣孟涵、黃馨慧、陳品伊、陳尊宇  
視覺設計：Milkxhake  
裝置製作：步里赫森  
此專案於 創新工作坊（TAICCA x Ars Electronica Art Thinking program）中開發  
主辦單位：文化內容策進院、林茲電子藝術中心  
協辦單位：廣達研究院  
特別感謝：  
林欣傑、莊庭瑞、魏廷宇  

Creator: Dimension Plus  
Project Host: Escher Tsai  
Producer: Szu Ya Wang  
Technical Coordinator: Tzu Chen Lee   
Technical Support: Seth Hon, Reviles Huang  
Production Team: Monique Chiang, Jessie Huang, Pingyi Chen, Zun Yu Tan  
Visual Design: Milkxhake  
Installation Production: Hozen Studio  

This project has been developed during the TAICCA x Ars Electronica Art Thinking program  
Organizer: Taiwan Creative Content Agency , Ars Electronica Center  
Co-organizer: Quanta Research Institute  

Special Thanks:  
Keith Lam, Tyng Ruey Chuang, Tim Wei  
