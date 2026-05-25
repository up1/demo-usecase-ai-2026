# Create short VDO for social media using AI
* Krafie


## Create the video
* Go to video studio https://krafie.com/services/video-studio
* Select kling 3, portrait mode, 8 seconds video, do not generate audio
* Under “Reference photo (optional)” there is a section to upload a link to the photo and use it.
* Upload the avatar named `Summer`, click on avatars, wait for the upload and select `Summer`
* Click on “Generate video” and wait for the video to be generated
* Download the video and post on social media

English version of the prompt for video generation
```
[
  {
    "prompt": "Vertical mirror-selfie in a softly lit bedroom. Use the exact model and outfit from the reference photo. She holds her phone in front of her face, filming her reflection in a full-length mirror. Front-facing full-body pose, slight weight shift, light outfit adjustment. Authentic TikTok try-on style, no text, no captions, no logos.",
    "duration": 3
  },
  {
    "prompt": "Vertical mirror-selfie in the same room. Use the exact model and outfit from the reference photo. She keeps the phone raised and takes a small step toward the mirror with a subtle body sway to show the fit and movement. Handheld creator style, no text, no captions, no logos.",
    "duration": 3
  },
  {
    "prompt": "Vertical mirror-selfie side shot. Use the exact model and outfit from the reference photo. She keeps the phone in front of her face and slowly turns to a side profile, showing the outfit silhouette in the mirror. Relaxed natural posture, no text, no captions, no logos.",
    "duration": 2
  }
]
```

ภาษาไทยสำหรับการสร้างวิดีโอ
```
[
  {
    "prompt": "ภาพเซลฟี่กระจกแนวตั้งในห้องนอนที่จัดแสงไฟอย่างนุ่มนวล ใช้โมเดลและชุดเดิมจากภาพอ้างอิงอย่างถูกต้อง เธอถือโทรศัพท์ไว้ข้างหน้าใบหน้า กำลังถ่ายภาพสะท้อนของตัวเองในกระจกเงาเต็มตัว ท่าโพสหน้าตรงแบบเต็มตัว มีการทิ้งน้ำหนักตัวเล็กน้อย และปรับแต่งชุดเบา ๆ สไตล์การลองเสื้อผ้าแบบ TikTok ที่ดูสมจริง ไม่ลงข้อความ ไม่มีคำบรรยาย และไม่มีโลโก้",
    "duration": 3
  },
  {
    "prompt": "ภาพเซลฟี่กระจกแนวตั้งในห้องเดิม ใช้โมเดลและชุดเดิมจากภาพอ้างอิงอย่างถูกต้อง เธอยังคงยกโทรศัพท์ขึ้นและก้าวเท้าสั้น ๆ เข้าหากระจก พร้อมกับโยกย้ายร่างกายเบา ๆ เพื่อให้เห็นรูปทรงและการเคลื่อนไหว สไตล์ครีเอเตอร์แบบถือกล้องถ่ายเอง ไม่ลงข้อความ ไม่มีคำบรรยาย และไม่มีโลโก้",
    "duration": 3
  },
  {
    "prompt": "ภาพเซลฟี่กระจกแนวตั้งมุมข้าง ใช้โมเดลและชุดเดิมจากภาพอ้างอิงอย่างถูกต้อง เธอถือโทรศัพท์ไว้ข้างหน้าใบหน้าและค่อย ๆ หันข้าง เพื่อแสดงให้เห็นทรวดทรงของชุดในกระจก ท่าทางผ่อนคลายเป็นธรรมชาติ ไม่ลงข้อความ ไม่มีคำบรรยาย และไม่มีโลโก้",
    "duration": 2
  }
]
```

## Prompt for video generation with Kling 3
* The prompt is in English, but you can also use Thai if you want to.
* The video will be generated in 3 parts, each part has a different prompt and duration
* The total duration of the video will be 8 seconds, so you can adjust the duration of each part accordingly
* Make sure to use the exact model and outfit from the reference photo in the prompt, so that the video will look consistent with the photo
* Do not include any text, captions, or logos in the prompt, as the video will be used for social media and should look natural and authentic.  
* You can use the example prompts provided above as a reference, but feel free to modify them to better suit your needs and style.

### Example prompt for video generation with Kling 3 in english
* Walk from earth to the moon, wearing a space suit, with a rocket in the background. The video should be in portrait mode, with a duration of 8 seconds, and no audio. The style should be cinematic and realistic, with no text, captions, or logos.

```[
  {
    "prompt": "Walk from earth to the moon, wearing a space suit, with a rocket in the background. The video should be in portrait mode, with a duration of 8 seconds, and no audio. The style should be cinematic and realistic, with no text, captions, or logos.",
    "duration": 8
  }
]
```

### Example prompt for video generation with Kling 3 in Thai
* เดินจากโลกไปยังดวงจันทร์ สวมชุดอวกาศ มีจรวดอยู่ในพื้นหลัง วิดีโอควรเป็นแนวตั้ง มีความยาว 8 วินาที และไม่มีเสียง สไตล์ควรเป็นภาพยนตร์และสมจริง ไม่มีข้อความ คำบรรยาย หรือโลโก้

```[
  {
    "prompt": "เดินจากโลกไปยังดวงจันทร์ สวมชุดอวกาศ มีจรวดอยู่ในพื้นหลัง วิดีโอควรเป็นแนวตั้ง มีความยาว 8 วินาที และไม่มีเสียง สไตล์ควรเป็นภาพยนตร์และสมจริง ไม่มีข้อความ คำบรรยาย หรือโลโก้",
    "duration": 8
  }
]
``` 

Example 3 steps video generation prompt for Kling 3 in Thai
* 3 seconds
* 3 seconds
* 2 seconds

```
[
  {
    "prompt": "เดินจากโลกไปยังดวงจันทร์ สวมชุดอวกาศ มีจรวดอยู่ในพื้นหลัง วิดีโอควรเป็นแนวตั้ง มีความยาว 3 วินาที และไม่มีเสียง สไตล์ควรเป็นภาพยนตร์และสมจริง ไม่มีข้อความ คำบรรยาย หรือโลโก้",
    "duration": 3
  },
  {
    "prompt": "เดินจากโลกไปยังดวงจันทร์ สวมชุดอวกาศ มีจรวดอยู่ในพื้นหลัง วิดีโอควรเป็นแนวตั้ง มีความยาว 3 วินาที และไม่มีเสียง สไตล์ควรเป็นภาพยนตร์และสมจริง ไม่มีข้อความ คำบรรยาย หรือโลโก้",
    "duration": 3
  },
  {
    "prompt": "เดินจากโลกไปยังดวงจันทร์ สวมชุดอวกาศ มีจรวดอยู่ในพื้นหลัง วิดีโอควรเป็นแนวตั้ง มีความยาว 2 วินาที และไม่มีเสียง สไตล์ควรเป็นภาพยนตร์และสมจริง ไม่มีข้อความ คำบรรยาย หรือโลโก้",
    "duration": 2
  }
]
```

