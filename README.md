# OCR-Image-to-Text---TessorOCR

This package contains an OCR engine - libtesseract and a command line program - **Tesseract**.

Tesseract 4 adds a new neural net (LSTM) based OCR engine which is focused on line recognition, but also still supports the legacy Tesseract OCR engine of Tesseract 3 which works by recognizing character patterns. Compatibility with Tesseract 3 is enabled by using the Legacy OCR Engine mode (--oem 0). It also needs traineddata files which support the legacy engine, for example those from the tessdata repository.

Stefan Weil is the current lead developer. Ray Smith was the lead developer until 2018. The maintainer is Zdenko Podobny. For a list of contributors see AUTHORS and GitHub's log of contributors.

Tesseract has unicode (UTF-8) support, and can recognize more than 100 languages "out of the box".

Tesseract supports various image formats including PNG, JPEG and TIFF.

Tesseract supports various output formats: plain text, hOCR (HTML), PDF, invisible-text-only PDF, TSV and ALTO (the last one - since version 4.1.0).

You should note that in many cases, in order to get better OCR results, you'll need to improve the quality of the image you are giving Tesseract.


Tesseract can be trained to recognize other languages. See Tesseract Training for more information.


# OCR RestAPI for Image to Text

**1) Home UI**

![1) Home UI](https://github.com/sohel-jagirdar/OCR-Image-to-Text---TessorOCR/assets/52422511/2b139f44-4c51-4217-9db1-1d2cd9963eec)

**2) send for prediction**

![2) send for prediction](https://github.com/sohel-jagirdar/OCR-Image-to-Text---TessorOCR/assets/52422511/933c7296-2419-45c3-8f9a-edea68845cf2)

**3) Prediction Output Result**

![3) Prediction Output Result](https://github.com/sohel-jagirdar/OCR-Image-to-Text---TessorOCR/assets/52422511/c5c8eb36-ca19-4fb2-84a4-3ed5436786da)
