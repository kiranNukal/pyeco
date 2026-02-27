## ✅ Program : Matplotlib + ImageIO Environment Validation


### Purpose:
Validates that Matplotlib, ImageIO, Pillow, and NumPy work correctly in a headless environment by running multiple **independent**, **self‑contained** test scripts.  
Each script performs rendering, image generation, format conversion, and its own internal validations, ending with a final `[RESULT] PASS/FAIL`.

### Packages used:
matplotlib  imageio  pillow  numpy

### Functionality:
- Uses Matplotlib's **Agg** backend (no display required).  
- Generates PNG, JPEG, and GIF images without external codecs.  
- Ensures safe RGB conversion for JPEG (handles RGBA → RGB).  
- Prints detailed `[info]`, `[OK]`, `[warn]`, and final `[RESULT]` summary lines.  
- Designed so **each test is independent** and can run in any order.

### How to run the example :
```
chmod +x install_test_example.sh
./install_test_example.sh
```
### License: 
covered under Apache 2.0 licenses
