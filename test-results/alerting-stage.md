
# 🚨 Alerting Stage – Test Results

---

## ✅ ALRT01 – Trigger buzzer/LED on drowsiness detection
**Result**: ✅ Pass  
**Test Method**: GPIO simulation and alert trigger functions validated in Python and prepared for ESP32-CAM.  
**Real Output**: Alert fired after >2s of eye closure.

---

## ✅ ALRT02 – Reset alert when eyes reopen
**Result**: ✅ Pass  
**Logic**: Once classified as "Open", system resets alert state immediately.  
**Evaluation**: Prevents continuous buzzer even after eyes reopen.
