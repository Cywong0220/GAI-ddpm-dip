# GAI-ddpm-dip
113下學期 生成式AI導論與實作 project4\
目標：結合DDPM和DIP技術\
Accelerating DDPM with DIP-based Initial Priors：使用DIP來加速DDPM

## 目標
DIP：載入噪音或者損壞的圖像，生成高質量（修復）的圖片\
DDPM：分爲兩個部分 forward和backward\
      forward的部分將原本的圖像增加noise，最後變成一個gauss分佈的圖像\
      backward的部分將noise的圖像還原成原本的圖像\
      
Goal:使用DIP來生成先驗圖片，然後輸入到DDPM中以加速DDPM

## 參考資料
[ddpm導讀](https://adam-study-note.medium.com/diffusion-model-denoising-diffusion-probabilistic-models-ddpm-%E8%A9%B3%E7%B4%B0%E4%BB%8B%E7%B4%B9-5ce77b6b64d4)\
[dip導讀](https://xiaosean5408.medium.com/deep-image-prior-%E7%B0%A1%E4%BB%8B-%E4%B8%8D%E9%9C%80%E8%B3%87%E6%96%99%E9%9B%86%E5%8D%B3%E5%8F%AF%E4%BD%BF%E7%94%A8%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92%E9%80%B2%E8%A1%8C%E5%9C%96%E5%83%8F%E4%BF%AE%E5%BE%A9-%E5%8E%BB%E9%9B%9C%E8%A8%8A%E7%AD%89%E4%BB%BB%E5%8B%99-4098d0bf235e)
