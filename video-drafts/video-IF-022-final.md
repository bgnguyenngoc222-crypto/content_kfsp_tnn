---
type: video_script
campaign: IF-022
status: drafted
source: IF-022-text-user-provided
---

# Kịch bản Video 2D "Cái giá của sự miễn phí" (IF-022)

Video Short/Reels (~60 giây). Lời thoại được viết lại (chuyển thể từ bài gốc) nhằm khắc phục các phản hồi: cải thiện hook, làm rõ cái giá của lời khuyên miễn phí, giảm thời lượng quảng cáo tính năng, và xóa bỏ các câu từ gây tối nghĩa. Hình ảnh tuân thủ chặt chẽ phong cách 2D Vector Silhouette của KFSP.

---

## 1. FULL TEXT ĐỌC VOICE (Copy bỏ vào Vbee)

```text
Bạn luôn thích những lời phím hàng miễn phí vì nghĩ rằng mình đang tiết kiệm. Nhưng cái giá thực sự của chữ "miễn phí" đó là gì? Nó không đo bằng tiền ngay lúc đó. Nó đo bằng những đêm mất ngủ khi tài khoản bốc hơi, bằng dòng vốn kẹt cứng trong đống cổ phiếu rác, và bằng hàng giờ đồng hồ mỗi tối bạn lướt diễn đàn trong hoang mang tột độ để tìm cách gỡ gạc. Một lệnh mua vội vã theo đám đông chỉ mất vài giây để khớp, nhưng khoản lỗ nó để lại đắt gấp hàng trăm lần một hệ thống đầu tư bài bản. Bạn tính toán từng đồng để xây dựng tư duy độc lập, nhưng lại quá dễ dãi ném tiền vào những sai lầm mù quáng. Đã đến lúc chấm dứt chuỗi ngày đánh cược. Thay vì tự bơi giữa biển thông tin nhiễu loạn, radar AI Cơ Hội Tiềm Năng của KFSP sẽ tự động rà quét dòng tiền đi ngược bão và cung cấp sẵn kịch bản điểm mua, điểm bán kỷ luật. Trả một mức phí tối ưu để mua lại sự an tâm và bảo vệ vốn, hay tiếp tục xài đồ miễn phí để rồi mất trắng? Tải app và trải nghiệm ngay KFSP. Đưa chứng khoán về tầm tay bạn.
```

---

## 2. KỊCH BẢN HÌNH ẢNH & PROMPTS ĐÃ GỘP

*(Ghi chú: Đã ghép sẵn Negative Prompt vào cuối mỗi dòng lệnh bằng tham số `--no`)*

### Cảnh 1: Cái giá của sự miễn phí (0s - 10s)
* **Thoại:** "Bạn luôn thích những lời phím hàng miễn phí vì nghĩ rằng mình đang tiết kiệm. Nhưng cái giá thực sự của chữ "miễn phí" đó là gì? Nó không đo bằng tiền ngay lúc đó."
* **Visual:** Bóng đen của một người ôm đầu hoang mang. Phía trên là một chiếc móc câu khổng lồ có treo chữ "FREE" đang phát sáng lơ lửng, bên dưới là những mũi nhọn cạm bẫy lờ mờ trong bóng tối.
* **Prompt:**
```text
2D vector illustration, flat art style, minimalist, dark silhouette of a confused man holding his head below a giant glowing fishing hook with the word FREE, hidden trap spikes in the dark below, free advice trap concept, purple #7B3AEC and red accent colors, clean background, abstract geometry, high contrast --no 3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text-heavy, watermark
```

### Cảnh 2: Hậu quả bào mòn (10s - 25s)
* **Thoại:** "Nó đo bằng những đêm mất ngủ khi tài khoản bốc hơi, bằng dòng vốn kẹt cứng trong đống cổ phiếu rác, và bằng hàng giờ đồng hồ mỗi tối bạn lướt diễn đàn trong hoang mang tột độ để tìm cách gỡ gạc."
* **Visual:** Bóng đen nhân vật chìm trong một biển giấy tờ và những biểu đồ đứt gãy. Một chiếc đồng hồ cát khổng lồ đang chảy xuống, biến những đồng tiền xu thành cát bụi.
* **Prompt:**
```text
2D vector illustration, flat art style, minimalist, dark silhouette of a trader drowning in broken charts and papers, a giant hourglass turning coins into dust, losing money and wasting time concept, purple #7B3AEC and red accent colors, clean background, abstract geometry, high contrast --no 3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark
```

### Cảnh 3: Sự dễ dãi mù quáng (25s - 35s)
* **Thoại:** "Một lệnh mua vội vã theo đám đông chỉ mất vài giây để khớp, nhưng khoản lỗ nó để lại đắt gấp hàng trăm lần một hệ thống đầu tư bài bản. Bạn tính toán từng đồng để xây dựng tư duy độc lập, nhưng lại quá dễ dãi ném tiền vào những sai lầm mù quáng."
* **Visual:** Cán cân khổng lồ đang bị nghiêng lệch: một bên là quả tạ nợ nần màu đỏ khổng lồ đè bẹp một bên là hộp công cụ phân tích nhỏ bé màu tím.
* **Prompt:**
```text
2D vector illustration, flat art style, minimalist, dark silhouette of a massive unbalanced glowing scale, a giant red debt weight crushing a small glowing purple analytical toolbox on the other side, illogical choices concept, purple #7B3AEC and red accent colors, clean background, abstract geometry, high contrast --no 3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark
```

### Cảnh 4: Bước ngoặt & Giải pháp (35s - 45s)
* **Thoại:** "Đã đến lúc chấm dứt chuỗi ngày đánh cược. Thay vì tự bơi giữa biển thông tin nhiễu loạn, radar AI Cơ Hội Tiềm Năng của KFSP sẽ tự động rà quét dòng tiền đi ngược bão và cung cấp sẵn kịch bản điểm mua, điểm bán kỷ luật."
* **Visual:** Từ trong bóng tối, một luồng ánh sáng radar quét qua làm lộ diện những viên ngọc sáng rực rỡ nằm ẩn dưới đống gạch ngói vụn nát (thị trường ảm đạm). 
* **Prompt:**
```text
2D vector illustration, flat art style, minimalist, dark silhouette of a glowing radar beam sweeping across dark ruins and revealing bright glowing gems hidden underneath, discovering hidden opportunities concept, purple #7B3AEC and green accent colors, clean background, abstract geometry, high contrast --no 3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark
```

### Cảnh 5: Call to Action (45s - 60s)
* **Thoại:** "Trả một mức phí tối ưu để mua lại sự an tâm và bảo vệ vốn, hay tiếp tục xài đồ miễn phí để rồi mất trắng? Tải app và trải nghiệm ngay KFSP. Đưa chứng khoán về tầm tay bạn."
* **Visual:** Bóng đen của một chiếc khiên bảo vệ khổng lồ đang che chắn cho một biểu đồ tăng trưởng. Kế bên là khung điện thoại có màn hình xanh lá (để lồng video thực tế của app).
* **Prompt:**
```text
2D vector illustration, flat art style, minimalist, dark silhouette of a giant glowing shield protecting a rising chart, next to a large smartphone with a solid bright green #00FF00 screen for chroma key, protecting assets concept, purple #7B3AEC accent color, clean background, abstract geometry, high contrast --no 3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark
```
