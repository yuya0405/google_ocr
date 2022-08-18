# google_ocr

## 事前準備

[Google Cloud Vision APIのOCRを使ってPythonから文字認識する方法](https://valmore.work/cloud-vision-api-ocr/)

を参考に秘密鍵を取得し、以下を実行する。

```
export GOOGLE_APPLICATION_CREDENTIALS="path/to/your/credentials.json"
pip install --upgrade google-cloud-vision
```

## 2種類のAPI
- 単語を取得するならTEXT_DETECTION
- 文章を取得するならDOCUMENT_TEXT_DETECTION
