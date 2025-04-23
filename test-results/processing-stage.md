
# 🧠 Processing Stage – Test Results

---

## ✅ PROC01 – Load and classify input using CNN
**Result**: ✅ Pass  
**Tool**: cnnCat2.h5 (Keras CNN model)  
**Confidence Example**: 99% (Label: Closed)  
**Setup**: Loaded in TensorFlow 2.10 environment with GPU.

---

## ✅ PROC02 – Detect closed eyes >2s
**Result**: ✅ Pass  
**Logic**: Alert is triggered after 56 consecutive frames labeled "Closed".  
**Frame Rate Assumed**: ~28 FPS  
**Detection Pipeline**: OpenCV → Grayscale → Resize → CNN → Temporal Logic

---

## ❌ PROC03 – Head posture adaptation
**Result**: ❌ Fail  
**Issue**: With slight head turns or tilted posture, CNN misclassified eye state or lost confidence.  
**Improvement Needed**: Introduce head position normalization or multi-angle training.

---

## ✅ PROC04 – Blink suppression logic
**Result**: ✅ Pass  
**Logic**: Alerts ignored for <10 consecutive "Closed" frames to allow normal blinks.  
**Evaluation**: Effective blink tolerance demonstrated during live testing.
