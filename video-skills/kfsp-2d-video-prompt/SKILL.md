---
name: kfsp-2d-video-prompt
description: Tạo prompt Text-to-Video chuẩn phong cách 2D Vector Animation của KFSP (Flat Art, Silhouette). Sử dụng skill này khi người dùng yêu cầu tạo prompt hoặc mô tả cảnh để gen video/ảnh minh họa 2D cho KFSP.
---

# Tạo Prompt Text-to-Video / Ảnh minh hoạ chuẩn KFSP

Mọi video hoặc ảnh minh họa trong chuỗi nội dung của KFSP đều phải tuân thủ nghiêm ngặt phong cách thiết kế **2D Vector Flat Art** và **Silhouette** (Bóng đen bóng người mờ ảo). 

Tuyệt đối KHÔNG sử dụng phong cách 3D, tả thực (realistic), hay cinematic.

## Công thức Prompt chuẩn

Khi người dùng yêu cầu tạo prompt mô tả một cảnh (ví dụ: cảnh sụp đổ thị trường, cảnh người ngồi phân tích biểu đồ...), hãy áp dụng công thức sau:

**Cấu trúc Prompt (Positive):**
`2D vector illustration, flat art style, minimalist, dark silhouette of [MÔ TẢ CHI TIẾT NHÂN VẬT VÀ HÀNH ĐỘNG BẰNG TIẾNG ANH], [MÔ TẢ BỐI CẢNH/ÁNH SÁNG BẰNG TIẾNG ANH], purple #7B3AEC accent color, clean background, abstract geometry, high contrast`

**Negative Prompt (Bắt buộc phải kèm theo):**
`3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark, text-heavy`

## Ví dụ

**Yêu cầu của user:** "Tạo prompt cho cảnh một người đàn ông đối diện với bảng điện đỏ rực lúc thị trường sụp đổ năm 1915."

**Output của AI:**
**Positive Prompt:** `2D vector illustration, flat art style, minimalist, dark silhouette of a faceless man standing in front of a glowing red stock ticker board falling down, panic atmosphere 1915 wall street, purple #7B3AEC and red accent colors, clean background, abstract geometry, high contrast`
**Negative Prompt:** `3d, realistic, cinematic, detailed face, photorealistic, photography, shading, messy, complex background, text, watermark, text-heavy`

## Quy trình thao tác
1. Phân tích yêu cầu của người dùng xem họ muốn nhân vật làm gì, bối cảnh ra sao.
2. Dịch ý tưởng đó sang tiếng Anh để điền vào phần `[MÔ TẢ...]`.
3. Lắp ghép thành 1 đoạn Prompt và 1 đoạn Negative Prompt hoàn chỉnh.
4. Trả kết quả dưới dạng text copy-paste để người dùng mang đi gen (Runway, Midjourney, v.v.).
