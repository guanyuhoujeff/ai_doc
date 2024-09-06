# 智慧公文系統架構分享

## 聲明

本講座所使用的所有公文範例皆為教育用途，並由人工智慧（如 ChatGPT）生成，非基於任何現實情境或實際公文。這些範例旨在展示如何運用 LLM（大型語言模型）及 LangChain 技術撰寫公文，內容純屬虛構，與實際的公文流程或任何特定事件無關。

本次分享的重點在於公文架構的設計，範例中的用詞及表述方式尚未經過正式的修訂，僅供學習和參考。若需撰寫正式的公文，請勿直接使用本教學中的內容，並建議根據實際需求進行專業審核與修改，以符合正式公文的規範及要求。

## 參考資料

- [公文撰作解析](https://ws.csptc.gov.tw/001/upload/ebook/%E5%85%AC%E6%96%87%E6%92%B0%E4%BD%9C%E8%A7%A3%E6%9E%90/odbook/index.html)
- [臺中市政府公文程式及寫作技巧](https://www.secretariat.taichung.gov.tw/media/520769/%E5%85%AC%E6%96%87%E7%A8%8B%E5%BC%8F%E4%BB%8B%E7%B4%B9%E5%8F%8A%E5%AF%A6%E5%8B%99%E5%AF%AB%E4%BD%9C%E6%8A%80%E5%B7%A7.pdf)
- [函的概念與範例](https://secret.nchu.edu.tw/file-manager/04_ddf/07doc-writing/han.pdf)

## 分享簡報

[智慧公文系統架構分享簡報](https://drive.google.com/file/d/1RrEUIL_aXiRhaQhreFW7VBwVi_tSenIn/view?usp=sharing)

## Google Colab Demo

| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guanyuhoujeff/ai_doc/blob/main/20240907-%E5%BE%AE%E5%85%89%E6%97%A9%E9%A4%90%E6%9C%83-%E6%99%BA%E6%85%A7%E5%85%AC%E6%96%87%E7%B3%BB%E7%B5%B1%E6%9E%B6%E6%A7%8B%E5%88%86%E4%BA%AB.ipynb)

## 在本地端運行

若想在本地端執行本系統，請依照以下步驟：

```bash
conda create -n ai-doc python=3.11 -y
conda activate ai-doc
conda install -c conda-forge jupyter -y
conda activate ai-doc && jupyter notebook
