---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Micromouse"
date: 2015
published: true
labels:
  - Robotics
  - Arduino
  - C++
summary: "My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition."
---

<div class="text-center p-4">
  <img width="1000px" src="../img/micromouse/genshinwebsite1.png" class="img-thumbnail" >
  <img width="1000px" src="../img/micromouse/genshinwebsite2.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>



```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
