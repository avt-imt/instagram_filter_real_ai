
```bash
pyiqa musiq qalign qualiclip+ maniqa nima clipiqa+ -t ../prediction/ai_images --verbose > ai_images_iqa.json
pyiqa musiq qalign qualiclip+ maniqa nima clipiqa+ -t ../prediction/real_images --verbose > real_images_iqa.json
```

manually adjustments of result jsons required

perform iqa for filtered images

```bash
pyiqa musiq qalign qualiclip+ maniqa nima clipiqa+ -t ai_images/filtered_ai/ --verbose > ai_images_filtered_iqa.json
pyiqa musiq qalign qualiclip+ maniqa nima clipiqa+ -t real_images/filtered_real/ --verbose > real_images_filtered_iqa.json
```