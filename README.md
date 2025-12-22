# LEI

## Datasets

### Detection (LEI-Detection)

Scanned index cards with bounding-box annotations for three object classes (stamp, etymon, content). 

- Train:
  - Stamp: 6,115 instances
  - Etymon: 12,731 instances
  - Content: 6,349 instances
- Validation:
  - Stamp: 644 instances
  - Etymon: 1,230 instances
  - Content: 663 instances
- Total:
  - Stamp: 6,759 instances
  - Etymon: 13,961 instances
  - Content: 7,012 instances

Download:  
https://next.hessenbox.de/index.php/s/75afxwmToTge2gX

---

### Recognition (LEI-Stamps)

Cropped textual stamp images used for stamp recognition. 

- Total images: 170,400
- Unique stamp classes: 3,817
- Train split:
  - 161,652 images
  - 3,817 stamp classes
- Validation split:
  - 8,748 images
  - 2,916 stamp classes (stamps with ≥4 instances)
  - 3 images per class in validation
  
Download:  
https://next.hessenbox.de/index.php/s/QFHKTqwzpwg6Tce

---

### Benchmark (LEI-Benchmark)

Full index-card images (no bounding boxes) for end-to-end benchmarking of stamp detection and recognition, including cards without stamps. 

- Total index cards: 1,369
- Cards with stamp: 1,348
- Cards without stamp: 21
- Unique stamps: 638


Download:  
https://next.hessenbox.de/index.php/s/oXjMwWSXY4w23Ra
