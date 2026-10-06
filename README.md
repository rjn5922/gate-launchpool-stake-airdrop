# gate launchpool là gì: cách stake BTC, ETH, GT, USDT nhận airdrop token mới, mức tối thiểu và ngưỡng khối lượng 60 ngày

Ai mới nghe "Launchpool" thường tưởng đây là một kiểu gửi tiết kiệm lấy lãi cố định. Không phải. Gate Launchpool là chỗ bạn đem tài sản đang nằm im (BTC, ETH, GT, USDT, GUSD hoặc chính token của dự án) bỏ vào một pool có thời hạn, rồi mỗi giờ nhận về token của dự án mới theo tỷ lệ phần stake của mình.

Hiểu sai chỗ này là dễ mất tiền: APR hiển thị chỉ là con số ước tính theo dữ liệu giờ trước, không phải lợi nhuận cam kết. Phần dưới đây gỡ từng mảnh — cơ chế tính thưởng, các bước tham gia, những điều kiện dễ bị bỏ qua, và cách đọc bảng cấp VIP vì cấp VIP quyết định bạn được stake tối đa bao nhiêu trong nhiều kỳ.

## Gate Launchpool là gì?

Gate Launchpool là sản phẩm stake nhận airdrop của sàn Gate. Người dùng đem tài sản ký gửi vào pool của một dự án cụ thể, và nhận token của dự án đó theo tỷ lệ đóng góp, thưởng trả về tài khoản spot theo từng giờ.

Sản phẩm này không mới. Nó là phiên bản đổi tên của Startup Mining — Gate nâng cấp và đổi tên thành Launchpool từ tháng 1/2025 để mô tả đúng bản chất "stake tài sản, nhận token dự án".

Điểm cần nắm: Launchpool vận hành theo **từng kỳ (campaign)**, không phải một sản phẩm cố định. Mỗi kỳ có tài sản stake riêng, tổng thưởng riêng, thời gian riêng, mức stake tối thiểu và tối đa riêng. Có kỳ chỉ mở pool USDT và GT, có kỳ mở pool BTC, ETH, GUSD, và cả pool token của chính dự án.

Một dự án thường mở nhiều pool song song cùng lúc, mỗi pool chia một phần thưởng khác nhau. Ví dụ kỳ 363 với dự án Citrea (CTR) chia 16.000.000 CTR cho ba pool: BTC nhận 4.000.000 CTR, GUSD nhận 5.600.000 CTR, pool CTR nhận 6.400.000 CTR, thời gian khai thác từ 26/5 đến 16/6/2026, mở khóa 100%.

Điều đó nghĩa là bạn stake pool nào thì chỉ ăn thưởng pool đó. Bỏ tiền vào pool A không tự động được chia phần ở pool B.

## Thưởng được tính mỗi giờ như thế nào

Công thức Gate đang dùng:

> Thưởng mỗi giờ = (số stake hợp lệ của bạn trong 1 giờ gần nhất ÷ tổng stake hợp lệ của cả pool) × quỹ thưởng mỗi giờ của pool

Hệ thống chụp snapshot số dư stake nhiều lần trong mỗi giờ rồi lấy trung bình, nên con số "hợp lệ" có thể khác số dư bạn nhìn thấy tại một thời điểm. Thưởng đủ điều kiện được trả về tài khoản spot mỗi giờ, không cần chờ kỳ kết thúc.

Vài hệ quả thực tế:

- **Không phải giành trước được trước.** Vào sau vẫn có thưởng, miễn kỳ còn chạy và bạn đủ điều kiện. Nhưng tỷ lệ của bạn loãng dần khi tổng stake trong pool tăng.
- **APR nhảy theo giờ.** Càng nhiều tiền vào pool mà tốc độ phát thưởng không đổi, APR càng tụt. Ngược lại, khi vốn rút ra, APR có thể tăng trở lại. Số APR bạn thấy lúc 9 giờ sáng không đảm bảo gì cho buổi chiều.
- **Có trần thưởng mỗi giờ cho mỗi người.** Chạm trần thì stake thêm không tăng thưởng nữa. Trần này khác nhau theo từng kỳ, phải đọc公告 (thông báo) của kỳ đó.

Một điểm nữa: APR được tính khác nhau tùy loại pool. Nếu token thưởng và token stake là cùng một loại (stake FOLD ăn FOLD), APR chủ yếu dựa trên tỷ lệ thưởng/stake của giờ trước. Nếu hai loại khác nhau (stake USDT ăn token dự án), hệ thống còn quy đổi giá thị trường của cả hai.

## Tham gia Gate Launchpool: 4 bước

1. **Xác minh danh tính (KYC) trước.** Bước này là điều kiện bắt buộc, không làm sau cũng được nhưng stake sẽ không hợp lệ.
2. **Vào Launchpool.** Trên web: mục **Kiếm tiền → Launchpool**. Trên app: **Trang chủ → Kiếm tiền → Launch → Launchpool**.
3. **Chọn pool và bấm tham gia**, nhập số lượng muốn stake, xác nhận. Bạn có thể stake sớm trước khi kỳ chính thức chạy để bắt thưởng từ giờ đầu tiên.
4. **Theo dõi trong Lịch sử Airdrop / Lịch sử Launchpool.** Có thể tăng stake bất cứ lúc nào trong kỳ.

Một chi tiết nhỏ nhưng dễ gây khó chịu: khi bạn rút hoặc khi kỳ kết thúc, tài sản mặc định được chuyển sang Simple Earn (ví kiếm lãi linh hoạt). Nếu bạn bỏ tick tùy chọn đó, tiền quay về ví spot. Trường hợp số dư quá nhỏ so với mức tối thiểu của Simple Earn, hoặc Simple Earn không hỗ trợ loại token đó, hệ thống cũng tự trả về spot.

👉 [Tạo tài khoản Gate và mở mục Launchpool](https://bit.ly/GateVIP)

## Vài con số thật để dễ hình dung

Số liệu APR dưới đây là ảnh chụp tại thời điểm công bố, không phải mức cố định — nhưng chúng cho thấy khoảng cách rất lớn giữa các loại pool.

**Kỳ 380 (30/9 – 21/10/2026):** tổng thưởng 18.400 GT, chia đôi cho hai pool. Pool ETH nhận 9.200 GT, APR ghi nhận 12,64%, tổng stake 5.459,85 ETH. Pool BTC nhận 9.200 GT, APR 7,91%, tổng stake 265,75 BTC. Mức tối thiểu chỉ 0,000001 BTC hoặc 0,00003 ETH.

**Kỳ SNDKG (dữ liệu ngày 10/8/2026):** pool ETH 25.677,34 ETH với APR 3,45%; pool BTC 1.443,01 BTC với APR 1,23%; pool GT 1.174.131,24 GT với APR 4,13%; pool USDT khoảng 92 triệu USDT với APR 5,59%.

**Nhóm kỳ FOLD / LAPTOP / XAUT:** LAPTOP có tổng thưởng 1.289.608 LAPTOP, chạy từ 18/9 đến 9/10/2026, chia cho pool BTC và pool LAPTOP (mỗi pool 644.804 LAPTOP). Pool LAPTOP có lúc ghi APR 263,05%, còn pool BTC chỉ 2,39%.

Sự chênh lệch đó không phải lỗi hiển thị. Pool dùng chính token dự án (stake LAPTOP ăn LAPTOP, stake FOLD ăn FOLD) thường có APR rất cao, vì phần thưởng tính bằng chính đồng tiền đang được phát hành thêm, và pool nhỏ thì tỷ lệ chia của bạn trông to. Pool dùng BTC, ETH, USDT — loại tài sản người ta muốn giữ lâu dài — có APR khiêm tốn hơn nhiều.

## Ba điều kiện dễ bị bỏ qua

### Ngưỡng khối lượng giao dịch 60 ngày

Gate đã siết điều kiện ở nhiều kỳ. Giới hạn stake của bạn được xác định theo tổng khối lượng giao dịch 60 ngày:

> Khối lượng 60 ngày = khối lượng spot 60 ngày + (khối lượng futures 60 ngày × 40%) + (khối lượng options 60 ngày × 5%, với một số kỳ)

Giao dịch nhiều hơn mở được trần stake cao hơn. Và quan trọng hơn: khi hệ thống phát airdrop theo giờ, tài khoản phải đạt mức khối lượng tối thiểu của kỳ đó, nếu không sẽ mất phần thưởng của giờ đó.

Ở kỳ Citrea, pool BTC và GUSD yêu cầu tối thiểu 6.000.000 USD khối lượng 60 ngày mới được nhận phân phối theo giờ, kèm bảng trần stake leo dần theo khối lượng. Đây là lý do nhiều người stake xong vẫn không thấy thưởng về.

Không đạt ngưỡng không chặn bạn rút tiền — chỉ chặn phần thưởng.

### Trần stake theo cấp VIP

Từ một số kỳ, người dùng VIP 5 trở lên được hưởng trần stake cao hơn. Ví dụ kỳ IKA (1–16/8/2025) với pool GT:

| Cấp VIP | Trần stake pool GT |
| --- | --- |
| VIP 0 – VIP 4 | 2.000 GT |
| VIP 5 | 3.000 GT (+50%) |
| VIP 6 | 4.000 GT (+100%) |
| VIP 7 | 5.200 GT (+160%) |
| VIP 8 | 6.800 GT (+240%) |
| VIP 9 | 9.000 GT (+350%) |
| VIP 10 – VIP 16 | 12.000 GT (+500%) |

Nếu bạn định bỏ vào pool một khoản lớn, hãy kiểm tra trần stake của kỳ đó trước, thay vì nạp vào rồi phát hiện phần vượt trần không sinh thưởng.

### Mức tối thiểu khá thấp, nhưng lãi mỗi giờ cũng có thể dưới ngưỡng chi trả

Mức tối thiểu thường rất nhỏ: 0,000001 BTC, 0,05 GUSD, 1 CTR, 5.000 USDT hay 100 GT tùy kỳ. Ngược lại, nếu phần thưởng tính ra cho một giờ nhỏ hơn ngưỡng chi trả tối thiểu, bạn có thể không nhận được gì trong giờ đó. Stake quá ít trong pool lớn thì thực tế gần như không có thưởng.

👉 [Mở tài khoản Gate để xem trần stake và pool đang mở](https://bit.ly/GateVIP)

## Launchpool khác gì Launchpad, CandyDrop và HODLer Airdrop

Cả bốn đều nằm trong mục Launch của Gate, nhưng cơ chế khác nhau khá rõ:

| Sản phẩm | Cách tham gia | Dạng thưởng |
| --- | --- | --- |
| CandyDrop | Hoàn thành nhiệm vụ (giao dịch, nạp, mời bạn…) | Chia pool Candy/khối lượng, hoặc thưởng cố định |
| Launchpool | Stake tài sản vào pool của kỳ đang chạy | Token mới của dự án, trả theo giờ |
| Launchpad | Mua token giai đoạn sớm theo suất | Phân bổ token theo đăng ký |
| HODLer Airdrop | Nắm giữ GT theo quy tắc từng kỳ | Airdrop theo số GT nắm giữ |

Khác biệt cốt lõi: Launchpool là stake để chia thưởng, không phải mua token, cũng không phải làm nhiệm vụ. Điều này hợp với người đã có sẵn BTC, ETH, GT hoặc stablecoin và không muốn bán ra để đổi lấy cơ hội.

Cần lưu ý thêm: Launchpad là mô hình mua/phân bổ suất, hoàn toàn tách khỏi Launchpool. Nhiều người mới gộp hai thứ làm một rồi kỳ vọng sai về cách nhận token.

## APR cao có thật sự ngon?

Ba điểm cần nhớ trước khi nhìn vào ô APR:

**APR bị pha loãng nhanh.** Con số cao thường xuất hiện lúc kỳ mới mở, tổng stake còn nhỏ. Khi dòng tiền đổ vào, tỷ lệ của bạn giảm và APR tụt theo, đôi khi chỉ sau vài giờ.

**Token thưởng có giá thị trường riêng.** Nhận 100 token không có nghĩa là nhận tài sản trị giá 100 USD. Token mới có thể tăng, có thể giảm mạnh sau khi niêm yết. Nếu tốc độ mất giá của token nhanh hơn tốc độ bạn tích lũy thưởng, bạn lỗ ròng dù APR hiển thị đẹp.

**Stake tài sản biến động để ăn APR của chính nó là vòng tròn rủi ro.** Trường hợp điển hình là các pool stake token dự án để nhận lại token dự án. Bạn đang giữ một tài sản chưa có lịch sử giá, với thanh khoản có thể mỏng.

Thêm nữa, Launchpool không phải sản phẩm lợi suất cố định. Không có cam kết lợi nhuận, không bảo đảm giá, và tài sản stake có thể bị ảnh hưởng nếu dự án gặp vấn đề — kể cả rủi ro không rút được toàn bộ token ở một số trường hợp.

## Bảng cấp VIP và phí giao dịch: phần "bảng giá" thật của người chơi Launchpool

Launchpool không có phí tham gia, cũng không có gói mua. Thứ quyết định chi phí và trần stake của bạn là cấp VIP trên tài khoản. Dưới đây là các cấp VIP cùng ngưỡng nâng cấp và phí spot theo bảng phí chính thức của Gate.

Cấp VIP được xét tự động theo ba hướng: khối lượng giao dịch 30 ngày, số dư GT trung bình 14 ngày, và giá trị tài sản dùng để nâng VIP. Đạt bất kỳ hướng nào cũng lên cấp. Hệ thống cập nhật định kỳ, không cần gửi yêu cầu.

| Cấp VIP | Khối lượng spot 30 ngày | Giá trị tài sản để nâng VIP | Phí spot Maker/Taker | Đăng ký |
| --- | --- | --- | --- | --- |
| VIP 0 | 0 | 0 | 0,100% / 0,100% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 1 | 60.000 | 2.000 | 0,099% / 0,099% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 2 | 120.000 | 4.000 | 0,098% / 0,098% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 3 | 240.000 | 10.000 | 0,097% / 0,097% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 4 | 500.000 | 20.000 | 0,095% / 0,096% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 5 | 1.000.000 | 40.000 | 0,090% / 0,095% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 6 | 3.000.000 | 100.000 | 0,085% / 0,090% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 7 | 8.000.000 | 200.000 | 0,080% / 0,085% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 8 | 20.000.000 | 400.000 | 0,075% / 0,080% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 9 | 50.000.000 | 1.000.000 | 0,070% / 0,075% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 10 | 100.000.000 | 2.000.000 | 0% / 0,058% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 11 | 120.000.000 | 4.000.000 | 0% / 0,045% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 12 | 240.000.000 | 8.000.000 | 0% / 0,037% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 13 | 440.000.000 | 16.000.000 | 0% / 0,030% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 14 | 800.000.000 | 30.000.000 | 0% / 0,025% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 15 | 1.600.000.000 | 60.000.000 | 0% / 0,022% | [Đăng ký Gate](https://bit.ly/GateVIP) |
| VIP 16 | 3.000.000.000 | 100.000.000 | 0% / 0,020% | [Đăng ký Gate](https://bit.ly/GateVIP) |

Hai ghi chú quan trọng khi đọc bảng này:

**Chu kỳ xét cấp là theo tháng và theo cửa sổ trượt.** Khối lượng 30 ngày và GT trung bình 14 ngày được cập nhật liên tục, nên cấp VIP có thể lên xuống. Người lần đầu lên cấp bằng khối lượng 30 ngày được giữ cấp 60 ngày; sau đó không duy trì được thì mỗi 15 ngày tụt một bậc.

**Phí có thể thấp hơn nữa nếu trả bằng GT.** Ở phần lớn cấp, mức phí khi thanh toán bằng GT thấp hơn mức phí chuẩn cùng cấp — ví dụ VIP 0 là 0,09% thay vì 0,10%. Gate cũng đã điều chỉnh lại cơ cấu phí spot và futures từ ngày 9/4/2026, nên nếu bạn nhớ bảng phí cũ thì nên xem lại.

Ngưỡng và phí có thể thay đổi theo thời gian và khác nhau theo khu vực. Hãy tra bảng phí theo đúng tài khoản của bạn.

👉 [Tra cấp VIP và phí thực tế của tài khoản bạn](https://bit.ly/GateVIP)

## Stake Launchpool có ảnh hưởng cấp VIP không?

Không. Tài sản đang stake trong Launchpool vẫn được tính vào số dư dùng cho HODLer Airdrop, Launchpad và quyền lợi VIP. Nói cách khác, bạn không bị mất suất ở các chương trình khác chỉ vì đang stake để ăn airdrop.

Một điểm liên quan: GT đang nằm trong các sản phẩm kiếm lãi vẫn được tính vào snapshot GT. Nên nếu bạn đang giữ GT và muốn lên cấp VIP, việc stake GT ở Launchpool hoặc để GT trong sản phẩm linh hoạt không làm ảnh hưởng tới thống kê số dư.

## Những câu hỏi người mới hay hỏi

**Có thể stake nhiều pool cùng lúc không?**
Được, miễn mỗi pool bạn stake riêng. Stake ở pool A không mang lại thưởng pool B.

**Rút tiền giữa kỳ có sao không?**
Rút được. Nhưng hệ thống lấy trung bình snapshot trong giờ, nên rút sớm có thể làm giảm stake hợp lệ và mất phần thưởng của giờ đó. Kỳ kết thúc sớm thì vốn được hoàn ở thời điểm kết thúc, phần thưởng của các giờ trước đó vẫn nguyên.

**Có dùng tiền vay để stake không?**
Không. Các kỳ đều loại trừ việc dùng vốn vay. Một số kỳ cũng giới hạn tài khoản tổ chức và tài khoản phụ, nên cần đọc điều khoản của chính kỳ đó.

**Người ở Việt Nam tham gia được không?**
Cần hoàn tất KYC và tuân theo danh sách khu vực bị hạn chế. Một số quốc gia — ví dụ Anh — không dùng được toàn bộ hoặc một phần dịch vụ, bao gồm các chương trình như thế này. Kiểm tra thỏa thuận người dùng trước khi nạp tiền.

**Nhận thưởng ở đâu?**
Tài khoản spot, trả theo giờ. Phần chưa nhận và tài sản stake sẽ tự động chuyển về ví sau khi kỳ kết thúc.

## Nên tham gia theo cách nào

Nếu bạn đã giữ BTC hoặc ETH dài hạn và không có ý định bán, đem stake vào pool BTC/ETH của kỳ đang chạy là cách dùng tài sản nhàn rỗi mà không phải đổi khẩu vị đầu tư. APR không cao, nhưng cũng không phải chịu thêm rủi ro từ một token chưa ai biết.

Nếu bạn đang có USDT hoặc GUSD nằm chờ cơ hội, pool stablecoin thường dễ tính hơn về biến động, đổi lại phải để mắt đến ngưỡng khối lượng 60 ngày — đây là bẫy phổ biến nhất khiến người ta stake mà không nhận được thưởng.

Còn những pool có APR ba con số: chỉ nên xem là khoản đặt cược nhỏ vào token dự án, với số vốn bạn sẵn sàng mất. Con số 263% hay 590% xuất hiện trên màn hình chủ yếu vì pool nhỏ và token phát hành nhanh, chứ không phải vì đó là nguồn thu nhập đều đặn.

Một lời khuyên mang tính quy trình: mỗi kỳ mở, đọc bốn thứ theo đúng thứ tự — tài sản stake được chấp nhận, trần stake của bạn, ngưỡng khối lượng tối thiểu, và hard cap thưởng mỗi giờ. APR xem sau cùng. Xong bốn bước đó, bạn đã tránh được gần hết các cú "stake rồi mà không có gì".

👉 [Đăng ký Gate và bắt đầu từ pool phù hợp với tài sản bạn đang giữ](https://bit.ly/GateVIP)
