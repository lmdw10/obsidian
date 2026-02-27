Mục tiêu là xây dựng website chuẩn theo yêu cầu từ Google Adsense. Với những chuẩn yêu cầu từ Adsense sẽ được chú thích^[Dấu ! tương ứng với chuẩn Adsense.]



# Setup basic

Mua domain từ [Namecheap](https://www.namecheap.com), [Cosmotown](https://www.cosmotown.com) hoặc các nhà cung cấp domain khác.

Có domain thì gán NameServers từ host của bạn sang cho domain để domain biết điều hướng đến server nào. Cách làm cụ thể thì tùy vào từng host và từng nhà cung cấp domain nhưng cơ bản là add domain trên host và nó sẽ cung cấp địa chỉ NameServers để mình gán nó vào domain trong trình quản lý domain của nhà cung cấp domain.

Sau khi gán xong thì yêu cầu chứng chỉ SSL Certificate trên host để chuyển từ http sang https^[!]

# Setup web

Cài wordpress lên host server.


# Setup wordpress

Vào setting để thiết lập ban đầu, ví dụ 1 số phần như:
+ General: thiết lập thông tin cơ bản về website.
+ Writing: thiết lập trình soạn thảo post, cài plugin Classic editor để chọn chế độ soạn thảo classic cho thân thuộc.
+ Permalink: custom lại link url post theo author/postname để sau này còn quản lý ctv.

Một số plugin cần cài như Edit Author Slug (thay đổi tên author trong link post), WP Super Cache^[!] (tăng tốc độ load web bằng cách lưu cache, nếu host hỗ trợ plugin Lite Cache thì cài thay cũng được), Rank Math SEO^[!] (giúp khai báo SEO), Site Kit^[!] (giúp khai báo và kết nối với Google),...

Sau khi viết tầm chục bài (khoảng 3 ngày) thì install plugin SEO với Google sau.

Thiết lập các trang pháp lý gồm Privacy Policy, About Us, Contract,.... tùy thuộc vào chủ đề web mà nhờ AI thêm những trang gì và viết như nào

Thiết lập theme

Tôi sẽ cung cấp 3 nguồn tin. Nhiệm vụ của bạn là đóng vai trò là một nhà phân tích chính trị độc lập. Thay vì tường thuật tin tức, hãy viết một bài phân tích chuyên sâu dựa trên những thông tin này.

Cấu trúc bài viết gồm (nhớ là các tiêu đề đều có thể linh hoạt sử dụng từ ngữ sáng tạo nhưng vẫn có hàm ý chính xác nội dung bên trong nhé):
1.LEAD / OPENING (2–3 đoạn ngắn)
**Mục tiêu:** kéo người đọc + đặt bối cảnh, KHÔNG phán xét.
**Cách viết:**
- 1–2 câu đầu: sự kiện chính
- 1 câu: vì sao đang gây chú ý
- 1 câu: bài này sẽ nói gì
Lưu ý: Không cảm xúc mạnh, không kết luận sớm.

2.BACKGROUND / CONTEXT (H2)
**Mục tiêu:** chứng minh mày hiểu chuyện, không phải lá cải rỗng.
**Viết gì:**
- Sự kiện xảy ra khi nào
- Ai liên quan
- Bối cảnh trước đó
Lưu ý: Trung lập tuyệt đối.

3.WHY IT MATTERS (H2)
**Mục tiêu:** cho người đọc lý do phải quan tâm.
**Viết gì:**
- Ảnh hưởng chính trị / xã hội
- Ai được lợi / ai bị ảnh hưởng
- Liên hệ xu hướng lớn hơn
Lưu ý: Phân tích, không cảm tính.

4.WHAT SUPPORTERS ARE SAYING (H2)
**Mục tiêu:** cho thấy **nhiều góc nhìn**.
**Viết gì:**
- Lập luận ủng hộ
- Quote (có thể paraphrase)
- Lý do họ tin là đúng
Lưu ý: Không cần bênh, chỉ trình bày.

5.WHAT CRITICS ARE SAYING (H2)
**Mục tiêu:** cân bằng, tránh bias.
**Viết gì:**
- Quan điểm phản đối
- Concerns
- Cảnh báo hậu quả
 Lưu ý: Tránh từ ngữ nặng như “dangerous”, “outrageous”.

6.BROADER IMPLICATIONS / ANALYSIS (H2)
**Viết gì:**
- Điều này nói gì về:
    - Chính trị hiện tại
    - Truyền thông
    - Chiến lược bầu cử
- So sánh với sự kiện trước
Lưu ý: Đây là phần **commentary**, nhưng phải lý trí.

7.EXPERIENCE
Viết gì: đóng vai vào một người bất kì để chia sẻ lại trải nghiệm của bản thân về chủ đề/tình huống/nội dung của bài viết, chia sẻ những cảm xúc chủ quan,
Lưu ý: Không phán xét quá gắt gao.

8.CONCLUSION / OPEN QUESTION (H2)
**Mục tiêu:** kết bài mà không kết luận độc đoán.
**Cách viết:**
- Tóm gọn tranh luận
- Đặt câu hỏi mở

Yêu cầu kỹ thuật cho bài viết:
- 1000–1.500 từ
- Ngôn ngữ Tiếng Anh, ngữ pháp phù hợp với người USA.
- H1 = title (1 cái duy nhất)
- H2 cho từng section
- Một đoạn 2–4 dòng
- Giọng văn: Phê phán, phân tích và chuyên nghiệp (tương tự như The Economist), đặc biệt phải viết như một người đang kể lại câu chuyện lẫn vừa viết báo chí, xen vào chút chủ quan lẫn khách quan.
- Không tường thuật như báo gốc, phải thay đổi góc nhìn: Đừng chỉ nói những gì đã xảy ra. Hãy giải thích TẠI SAO nó quan trọng và TÁC ĐỘNG tiềm tàng lâu dài đối với [chủ đề bị tác động] có thể là gì.
- Tránh dùng những từ ngữ sáo rỗng về AI: Tránh những từ như 'In today's fast-paced world', 'delve', 'unlock', 'unleash', 'crucial'.
- Nội dung độc đáo: Tổng hợp thông tin từ tất cả các nguồn để tạo ra một câu chuyện hoàn toàn mới.
- Đảm bảo nội dung đạt chuẩn **E-E-A-T** (Viết như người có kinh nghiệm hoặc chuyên môn hoặc có thẩm quyền và đáng tin cậy với những con số, thông tin cụ thể)

Những lỗi phải tránh:
- Opinion ngay từ đầu
- Dùng từ cảm xúc mạnh
- Kết luận, khẳng định một chiều “This proves that…”
- Gọi tên phe phái theo kiểu công kích

Yêu cầu đặc biệt cho câu trả lời của mày: Bài viết sẽ được mày viết thành 2 phần, mỗi phần dài khoảng 600-800 từ sao cho tổng 2 phần xấp xỉ 1500 từ đổ lên. Sau khi mày viết phần 1 tao sẽ nhắn "2" để mày trả nốt phần còn lại của bài viết. Không cần ghi part1, part2, cứ viết liền mạch

title:

4 TRỤC AN TOÀN ĐỂ VIẾT TITLE
TRỤC 1 – Curiosity-based (Tò mò)
Why / How / What’s Behind / What It Means
Ví dụ:
- _What’s Behind the Sudden Shift in Biden’s Strategy_
- _Why This Senate Vote Is Getting Unusual Attention_

TRỤC 2 – Analysis-based (Phân tích)
Signals / Implications / Bigger Picture
Ví dụ:
- _The Hidden Signals in Trump’s Latest Campaign Move_
- _What This Court Ruling Could Mean for the 2024 Race_

TRỤC 3 – Debate-based (Tranh luận)
Supporters vs Critics / Divided Reactions
Ví dụ:
- _Supporters Applaud the Decision, Critics Raise Concerns_
- _A Move That’s Splitting Washington_

TRỤC 4 – Contextual drama (Drama nhưng có kiểm soát)
Raising Questions / Fueling Debate / Drawing Scrutiny
Ví dụ:
- _A Decision That’s Fueling New Questions on Capitol Hill_

4 TRỤC CẦN TRÁNH KHI VIẾT TITLE
TRỤC CẤM 1 – Emotional outrage
- Shocking
- Outrageous
- Furious
- Slams / Destroys / Exposes

TRỤC CẤM 2 – Absolute certainty
- This proves
- No doubt
- Clearly shows
- The truth about

TRỤC CẤM 3 – Moral judgment
- Hypocrisy
- Corruption    
- Betrayal
- Disgrace

TRỤC CẤM 4 – Clickbait mismatch

BẢN CHẤT AN TOÀN CỦA TITLE MÀ VẪN THU HÚT LÀ: Event + Neutral tension + Analytical angle. Dù có biến tấu thêm thắt hay đảo vị trí thì nó vẫn có những thành phần này trong câu.

![](https://raw.githubusercontent.com/lmdw10/obsidian/main/img_sync/20260205T140638320Z.png)

