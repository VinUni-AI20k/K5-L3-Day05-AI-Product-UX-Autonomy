# Ghi chú cho TA *(không bắt buộc với học viên)*

> Tài liệu phụ cho TA và giảng viên: bảng gọi tên lỗi, case sự cố thật để mở chặng 3, bối cảnh quy định Việt Nam. Không đổi điểm, không thêm việc cho nhóm. Cách chấm vẫn theo `04-rubric.md`.

## 1. Gọi tên lỗi nhanh (chặng 2–3)

Khi nhóm tìm ra một cái sai, TA có thể hỏi "nó thuộc họ nào?" để nhóm nghĩ tiếp đường lui. Không bắt học viên học thuộc thuật ngữ.

| Họ lỗi | AI sai thế nào | Ví dụ trong track | Đường lui thường gặp |
|---|---|---|---|
| **Hứa sai** | Nói đã làm / sẽ làm điều nó không làm được hoặc không có quyền | T3: "đã đổi vé cho bạn" khi mới giữ chỗ | Nói đúng trạng thái; chỉ hứa điều tool làm được |
| **Hiểu sai ý** | Đoán ý khi tin mơ hồ (lớp ②) | T4: "hoàn tiền giúp tôi" — cả đơn hay một món? | Hỏi lại một câu (HAX G10) |
| **Dữ liệu / tool** | Bịa nguồn, dùng sai tool, dữ liệu không có (lớp ①) | T2: kể nội dung buổi chưa có tài liệu | Nói rõ "chưa có"; dẫn căn cứ |
| **An toàn** | Ngoài phạm vi, bị dụ, đụng vùng cấm (lớp ③④) | T1: tư vấn thuốc kê đơn; T5: nhả giao dịch cho người đang bị lừa | Dừng, chuyển người; không có nút làm |
| **Phục hồi** | Sai rồi mà người dùng không sửa, hoàn tác, hay tìm được người | Mọi track: không có đường chuyển người | Hoàn tác, sửa, chuyển người (G8, G9) |

## 2. Case thật mở chặng 3 *(5 phút, tùy chọn)*

TA đọc 1 phút, nhóm trả lời 3 câu: tool nào trong track mình có thể gây chuyện tương tự? Mức tự chủ nhóm định đặt có chặn được không? Người dùng nên thấy gì?

| Track | Case | Tóm tắt | Móc vào lab |
|---|---|---|---|
| T3, T4 | **Moffatt v. Air Canada** (2024 BCCRT 149) | Chatbot của hãng nói sai chính sách hoàn tiền vé tang lễ. Tòa buộc hãng chịu trách nhiệm, bác lập luận "chatbot là thực thể riêng"; hãng bồi thường CAD 812,02. *(Tòa không xác định bot có phải AI tạo sinh.)* | Lớp ① nguồn sự thật; `gui_yeu_cau_hoan_ve`, `tu_choi_khieu_nai` là quyết định chính sách |
| T1 | **NEDA "Tessa"** (2023) | Chatbot hỗ trợ rối loạn ăn uống đưa lời khuyên giảm cân, đếm calo; bị gỡ xuống. | Lớp ③④: `goi_y_san_pham` phải dừng khi có dấu hiệu rủi ro → `chuyen_duoc_si` / `khuyen_di_kham` |
| T2 | **Bot hỗ trợ của Cursor** (4/2025) | Bot bịa ra "chính sách mỗi tài khoản một thiết bị"; người dùng huỷ gói, công ty phải xin lỗi. | `dang_FAQ`: câu bịa được đăng cho nhiều người đọc, tác hại nhân lên |
| T5 | **Xác thực sinh trắc** (QĐ 2345/QĐ-NHNN) | Sinh trắc chứng minh *ai* đang bấm, không chứng minh giao dịch an toàn: người bị lừa vẫn tự xác thực đúng. | Hard test "người đang bị lừa vẫn xác thực khuôn mặt đúng"; `nha_giao_dich` không đảo được |

## 3. Bối cảnh quy định Việt Nam

Chỉ để nhóm biết vì sao một số việc phải chặt. Không phải tư vấn pháp lý; không chấm điểm theo luật.

| Văn bản | Nội dung liên quan | Track |
|---|---|---|
| Luật Trí tuệ nhân tạo 134/2025/QH15 (hiệu lực 01/3/2026) | Hệ thống AI tương tác trực tiếp phải cho người dùng biết họ đang làm việc với AI; nội dung do AI tạo phải được gắn nhãn | Tất cả (gần với HAX G1) |
| QĐ 2345/QĐ-NHNN (hiệu lực 01/7/2024) | Xác thực sinh trắc khi chuyển trên 10 triệu/lần hoặc trên 20 triệu/ngày | T5 |
| Thông tư 11/2025/TT-BYT (hiệu lực 01/7/2025) | Bán thuốc qua mạng chỉ sau khi đã tư vấn, hướng dẫn người mua | T1 |

## 4. Chặng 4 — chỗ TA nên hỏi

- Tool "cần người duyệt": **ai** duyệt · người duyệt **thấy gì** · **quá hạn** thì sao? (`02-guide.md` §4.2)
- Tool không đảo lại được hoặc rất khó đảo (`doi_chuyen_bay`, `gui_yeu_cau_hoan_ve`, `tu_choi_khieu_nai`, `nha_giao_dich`, `ban_thuoc_ke_don`…) mà nhóm đặt **tự làm**: lý do có thật sự mạnh không?
- Luật thêm có **nới** mức ở đâu không? Luật chỉ nên siết.

Khung tham khảo: ba mức của lab tương ứng với vai người dùng *approver / observer / operator* trong Feng, McDonald & Zhang, "Levels of Autonomy for AI Agents" (2025).

## Nguồn

- HAX — Amershi et al., CHI 2019: <https://www.microsoft.com/en-us/research/wp-content/uploads/2019/01/Guidelines-for-Human-AI-Interaction-camera-ready.pdf>
- PAIR, Errors + Graceful Failure: <https://pair.withgoogle.com/chapter/errors-failing/>
- Levels of Autonomy for AI Agents: <https://arxiv.org/abs/2506.12469>
- Air Canada: <https://www.americanbar.org/groups/business_law/resources/business-law-today/2024-february/bc-tribunal-confirms-companies-remain-liable-information-provided-ai-chatbot/>
- NEDA Tessa: <https://www.npr.org/sections/health-shots/2023/06/08/1180838096/an-eating-disorders-chatbot-offered-dieting-advice-raising-fears-about-ai-in-health>
- Cursor: <https://winbuzzer.com/2025/04/22/cursor-ais-support-bot-hallucinates-policy-sparking-user-backlash-and-company-apology-xcxwbn/>
- Luật AI 2025: <https://baochinhphu.vn/viet-nam-chinh-thuc-co-luat-tri-tue-nhan-tao-ai-102251210164948585.htm>
- QĐ 2345/QĐ-NHNN: <https://tienphong.vn/thong-tin-moi-ve-viec-chuyen-tien-tu-10-trieu-dong-post1854353.tpo>
- TT 11/2025/TT-BYT: <https://thuvienphapluat.vn/van-ban/The-thao-Y-te/Thong-tu-11-2025-TT-BYT-sua-doi-Thong-tu-02-2018-TT-BYT-thuc-hanh-tot-co-so-ban-le-thuoc-657360.aspx>
