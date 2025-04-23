
# 📷 Capture Stage – Test Results

---

## ✅ CAP01 – Camera initializes and streams frames
**Result**: ✅ Pass  
**Notes**: Camera initialized successfully using OpenCV. Frame stream was stable with no dropped frames during testing.

---

## ✅ CAP02 – Frame rate ≥15 FPS
**Result**: ✅ Pass  
**Measured FPS**: 28.61  
**Method**: Captured using Python and OpenCV with real-time FPS calculation. Tested on GPU-enabled environment.

---

## ⏳ CAP03 – Low-light image handling
**Result**: ⏳ Pending  
**Planned Test**: Evaluate frame quality under night-time/low-light conditions using webcam in dim environment.

---

## ⚠️ CAP04 – Face and Eye Region Alignment
**Result**: ⚠️ Partial  
**Tool**: MediaPipe Face Mesh  
**Issue**: Mesh generally tracks the face well, but under head tilt or varied distance, eye region may shift or misalign.

---

## ✅ CAP05 – Grayscale + Resize for ML
**Result**: ✅ Pass  
**Input Shape**: (24, 24, 1)  
**Method**: Preprocessing pipeline (OpenCV) converts to grayscale, resizes, and normalizes before inference.
