---
markmap:
  initialExpandLevel: 2
  maxWidth: 420
---

# Kỹ thuật Xử lý Nước cấp (Water Supply Engineering)

## Chương 1: Giới thiệu & Chất lượng Nước (Introduction & Water Quality)


### 1.1 Nguồn nước

#### 1.1.1 Chu trình Thủy Địa hóa và Phân loại Tạp chất trong Nước (Hydrogeochemical Cycle & Impurity Classification)
- Chu trình thủy văn tự nhiên vận chuyển và làm sạch nước trong khí quyển:
  - **Hình 12.** Chu trình thủy văn tự nhiên trong khí quyển và vỏ trái đất
    - <img src="ch01_introduction/assets/fig_12_p5.png" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự khép kín: bốc hơi từ biển, ngưng tụ mây, giáng thủy và dòng chảy ngầm.
    - **Từ đâu mà thấy được**
      - Chiều mũi tên vận chuyển nước từ mặt biển lên mây và quay về sông ngòi, tầng chứa nước.

##### 1.1.1.1 Cơ chế Chu trình Thủy văn Toàn cầu và Quá trình Chưng cất Tự nhiên
- **Bản chất chu trình thủy văn**:
  - Chu trình thủy địa hóa (Hydrogeochemical Cycle) luân chuyển nước liên tục giữa thủy quyển, khí quyển, thạch quyển và sinh quyển.
  - Năng lượng mặt trời và trọng lực Trái Đất điều khiển toàn bộ chu trình.
- **Bốn giai đoạn vận động của chu trình**:
  1. Bốc hơi nước biển (Solar Ocean Evaporation): Bức xạ mặt trời đốt nóng bề mặt biển. Nhiệt lượng bẻ gãy liên kết hydro giữa các phân tử $H_2O$. Hơi nước thoát vào khí quyển. Muối khoáng và tạp chất không bay hơi ở lại đại dương. Quá trình này hoạt động như một hệ thống chưng cất tự nhiên bằng năng lượng mặt trời (Natural Solar Distillation).
  2. Ngưng tụ và vận chuyển hơi ẩm (Atmospheric Transport & Condensation): Khối khí ẩm bốc lên cao gặp nhiệt độ thấp. Hơi nước ngưng tụ quanh hạt nhân ngưng tụ (aerosol bụi, muối biển, phấn hoa) tạo thành mây.
  3. Giáng thủy (Precipitation): Kích thước hạt nước trong mây tăng dần. Trọng lực thắng lực nâng khí động khiến nước rơi xuống mặt đất dưới dạng mưa, tuyết hoặc mưa đá.
  4. Dòng chảy bề mặt (Surface Runoff) và thấm sâu (Infiltration): Nước mưa rơi xuống đất chia thành ba phần. Phần thứ nhất bốc hơi trực tiếp vào khí quyển. Phần thứ hai chảy tràn bề mặt vào suối, sông, hồ rồi đổ ra biển. Phần thứ ba thấm qua tầng đất mặt bổ cập tầng chứa nước ngầm (aquifers).
- **Phân bố trữ lượng nước trên Trái Đất (Global Water Allocation)**:
  - Tổng trữ lượng nước toàn cầu đạt khoảng $1.386 \times 10^9\text{ km}^3$.
  - Nước mặn đại dương (Oceans): Chiếm $97.5\%$ tổng lượng nước toàn cầu. Độ mặn trung bình đạt $35\text{ g/L}$. Nước biển cần khử muối trước khi cấp cho sinh hoạt.
  - Băng hà và tuyết vĩnh cửu (Glaciers & Permanent Snowpack): Chiếm $1.76\%$ tổng lượng nước toàn cầu (tương đương $68.7\%$ tổng lượng nước ngọt). Nguồn nước này phân bố tại Nam Cực, Bắc Cực và đỉnh núi cao.
  - Nước dưới đất (Groundwater): Chiếm $0.76\%$ tổng lượng nước toàn cầu (tương đương $30.1\%$ tổng lượng nước ngọt). Nguồn nước này là nguồn cấp nước sinh hoạt chính cho con người.
  - Nước mặt ngọt (Freshwater Lakes & Rivers): Chiếm dưới $0.01\%$ tổng lượng nước toàn cầu. Hồ nước ngọt chiếm khoảng $0.007\%$. Sông suối chiếm khoảng $0.0002\%$. Đây là nguồn khai thác nước cấp tập trung thuận tiện nhất cho đô thị.

##### 1.1.1.2 Các Đặc tính Vật lý Cơ bản của Nước trong Hệ Đơn vị SI
- **Khối lượng riêng của nước ($\rho$)**:
  - Nước đạt khối lượng riêng cực đại tại nhiệt độ $4^\circ\text{C}$:
    $$\rho_{\text{water, } 4^\circ\text{C}} = 1000\text{ kg/m}^3 = 1.000\text{ g/cm}^3$$
  - Khối lượng riêng tại $20^\circ\text{C}$: $\rho = 998.2\text{ kg/m}^3$.
  - Khối lượng riêng tại $21^\circ\text{C}$: $\rho = 998.0\text{ kg/m}^3$.
  - Khối lượng riêng tại $25^\circ\text{C}$: $\rho = 997.0\text{ kg/m}^3$.
  - Quan hệ giữa khối lượng riêng và tỷ trọng (Specific Gravity - $\text{SG}$):
    $$\rho = \text{SG} \cdot \rho_{\text{ref}} = \text{SG} \cdot \rho_{\text{water, } 4^\circ\text{C}}$$
    - $\rho$: Khối lượng riêng của chất lỏng ($\text{kg/m}^3$).
    - $\text{SG}$: Tỷ trọng của chất lỏng (không thứ nguyên).
    - $\rho_{\text{ref}}$: Khối lượng riêng của chất lỏng chuẩn tại $4^\circ\text{C}$ ($1000\text{ kg/m}^3$).
- **Trọng lượng riêng của nước ($\gamma$)**:
  - Trọng lượng riêng tính bằng tích số giữa khối lượng riêng và gia tốc trọng trường:
    $$\gamma = \rho \cdot g$$
    - $\gamma$: Trọng lượng riêng của nước ($\text{N/m}^3$).
    - $\rho$: Khối lượng riêng của nước ($\text{kg/m}^3$).
    - $g$: Gia tốc trọng trường ($9.81\text{ m/s}^2$).
  - Giá trị trọng lượng riêng tại $4^\circ\text{C}$:
    $$\gamma = 1000\text{ kg/m}^3 \times 9.81\text{ m/s}^2 = 9810\text{ N/m}^3 = 9.81\text{ kN/m}^3$$
- **Độ nhớt động lực ($\mu$)**:
  - Độ nhớt động lực đo lực ma sát nội tại giữa các lớp chất lỏng chuyển động trượt.
  - Đơn vị đo trong hệ SI: $\text{N}\cdot\text{s/m}^2$ hoặc $\text{Pa}\cdot\text{s}$ ($1\text{ Poise} = 0.1\text{ Pa}\cdot\text{s}$, $1\text{ cP} = 10^{-3}\text{ Pa}\cdot\text{s}$).
  - Giá trị tại $20^\circ\text{C}$: $\mu = 1.002 \times 10^{-3}\text{ N}\cdot\text{s/m}^2$ ($1.002\text{ cP}$).
  - Giá trị tại $21^\circ\text{C}$: $\mu = 0.00982\text{ Poise} = 9.82 \times 10^{-4}\text{ N}\cdot\text{s/m}^2$ ($0.982\text{ cP}$).
- **Độ nhớt động học ($\nu$)**:
  - Độ nhớt động học là tỷ số giữa độ nhớt động lực và khối lượng riêng:
    $$\nu = \frac{\mu}{\rho}$$
    - $\nu$: Độ nhớt động học của nước ($\text{m}^2/\text{s}$).
    - $\mu$: Độ nhớt động lực của nước ($\text{N}\cdot\text{s/m}^2$).
    - $\rho$: Khối lượng riêng của nước ($\text{kg/m}^3$).
  - Giá trị tại $20^\circ\text{C}$: $\nu \approx 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
  - Giá trị tại $21^\circ\text{C}$: $\nu \approx 9.84 \times 10^{-7}\text{ m}^2/\text{s}$.
- **Nhiệt dung riêng của nước ($C_p$)**:
  - Giá trị chuẩn: $C_p = 4.184\text{ kJ/(kg}\cdot\text{K)}$ ($1\text{ cal/(g}\cdot^\circ\text{C)}$).
  - Nhiệt dung riêng cao giúp các thủy vực tự nhiên ổn định nhiệt độ trước biến đổi thời tiết.

##### 1.1.1.3 Phân loại Năm Nhóm Tạp chất Cốt lõi trong Nguồn Nước Tự nhiên
- **Nhóm 1: Các hợp chất vô cơ hòa tan (Dissolved Inorganic Compounds)**:
  - Cation chính:
    - Canxi ($Ca^{2+}$) và Magie ($Mg^{2+}$) tạo nên độ cứng của nước.
    - Natri ($Na^+$) và Kali ($K^+$) quyết định độ mặn của nước.
    - Sắt ($Fe^{2+}$) và Mangan ($Mn^{2+}$) xuất hiện phổ biến trong môi trường yếm khí thiếu oxy.
    - Nhôm ($Al^{3+}$), Stronti ($Sr^{2+}$) và Bari ($Ba^{2+}$) hòa tan từ khoáng sét tự nhiên.
  - Anion chính:
    - Bicarbonate ($HCO_3^-$) và Carbonate ($CO_3^{2-}$) tạo nên độ kiềm của nước.
    - Clorua ($Cl^-$) và Sunfat ($SO_4^{2-}$) tạo nên độ mặn và độ cứng phi carbonate.
    - Nitrate ($NO_3^-$) và Fluoride ($F^-$) sinh ra từ phân bón nông nghiệp hoặc khoáng đá.
  - Nguyên tố vết độc tính:
    - Asen ($As$), Chì ($Pb$), Cadmium ($Cd$), Crom ($Cr^{6+}$) và Thủy ngân ($Hg$).
    - Các nguyên tố này sinh ra từ phong hóa địa chất hoặc nước thải công nghiệp. Chúng gây tổn thương nội tạng và ung thư.
- **Nhóm 2: Các hợp chất hữu cơ hòa tan (Dissolved Organic Matter - NOM)**:
  - Hợp chất hữu cơ tự nhiên (Natural Organic Matter - NOM):
    - Hình thành do phân rã thảm thực vật, bùn đáy và chất tiết chuyển hóa của tảo.
    - Axit Humic: Khối lượng phân tử lớn, tan trong kiềm, kết tủa trong axit, tạo màu nâu sẫm cho nước.
    - Axit Fulvic: Khối lượng phân tử nhỏ hơn, tan trong mọi dải pH, tạo màu vàng rơm cho nước.
    - Tanin: Hòa tan từ vỏ cây và lá mục trong rừng ngập nước.
  - Hợp chất hữu cơ tổng hợp (Synthetic Organic Chemicals - SOCs):
    - Chất hoạt động bề mặt (detergents) từ nước thải sinh hoạt đô thị.
    - Thuốc bảo vệ thực vật (pesticides, organochlorines) từ dòng chảy tràn nông nghiệp.
    - Dung môi công nghiệp và các chất gây rối loạn nội tiết (EDCs).
  - Tác động kỹ thuật của hợp chất hữu cơ:
    - Tiêu tốn hóa chất keo tụ trong quá trình xử lý nước.
    - Gây nghẹt tắc màng lọc nước.
    - Phản ứng với clo sinh ra phụ phẩm khử trùng gây ung thư (Disinfection By-Products - DBPs).
- **Nhóm 3: Các chất khí hòa tan (Dissolved Gases)**:
  - Oxy hòa tan (Dissolved Oxygen - DO): Duy trì sự sống thủy sinh và trạng thái oxy hóa của nước mặt. Nước ngầm sâu thường nghèo DO ($DO < 1 - 2\text{ mg/L}$).
  - Khí Carbonic ($CO_2$): Hòa tan tạo axit carbonic ($H_2CO_3$). Khí này ăn mòn kim loại đường ống và hòa tan đá vôi tạo độ cứng.
  - Khí Hydro Sulfua ($H_2S$): Sinh ra do vi khuẩn khử sunfat trong môi trường kỵ khí. Khí gây mùi trứng thối và tạo kết tủa đen $FeS$ khi gặp ion sắt.
  - Khí Methane ($CH_4$): Khí dễ cháy nổ, sinh ra do phân hủy bùn kỵ khí ở đáy thủy vực.
  - Khí Radon ($Rn$): Khí phóng xạ tự nhiên hòa tan từ vỉa đá granite chứa urani.
  - Khí Nitơ ($N_2$) và Khí Lưu huỳnh đioxit ($SO_2$): Hòa tan vào nước từ bầu khí quyển.
- **Nhóm 4: Các chất rắn lơ lửng và hệ keo (Suspended Solids & Colloids)**:
  - Chất rắn lơ lửng (Total Suspended Solids - TSS):
    - Kích thước hạt từ $1\text{ }\mu\text{m}$ đến hàng trăm $\mu\text{m}$.
    - Gồm hạt cát mịn, bùn phù sa (silt), xác hữu cơ, dầu và mỡ.
    - Các hạt này tạo ra độ đục (Turbidity) và có thể lắng tự nhiên nhờ trọng lực.
  - Hệ keo (Colloidal Sol):
    - Kích thước hạt rất nhỏ từ $0.001\text{ }\mu\text{m}$ đến $1\text{ }\mu\text{m}$.
    - Gồm keo sét aluminosilicate, keo silica và phức hợp hữu cơ.
    - Hạt keo mang điện tích âm bề mặt cố hữu. Lực đẩy tĩnh điện ngăn các hạt keo tự kết dính.
    - Nhà máy phải dùng phèn nhôm hoặc phèn sắt để keo tụ và trung hòa điện tích.
- **Nhóm 5: Vi sinh vật (Microorganisms)**:
  - Vi khuẩn gây bệnh (Pathogenic Bacteria):
    - *Escherichia coli*: Vi khuẩn chỉ thị mức độ nhiễm phân từ người và động vật máu nóng.
    - *Vibrio cholerae*: Phẩy khuẩn tả gây bệnh tả và tiêu chảy cấp tính.
    - *Salmonella typhi*: Vi khuẩn gây bệnh sốt thương hàn.
    - *Shigella*: Vi khuẩn gây bệnh lỵ trực khuẩn.
    - *Pseudomonas aeruginosa*: Trực khuẩn mủ xanh gây nhiễm trùng cơ hội.
  - Virus gây bệnh truyền qua đường nước:
    - Kích thước siêu nhỏ từ $0.02\text{ }\mu\text{m}$ đến $0.1\text{ }\mu\text{m}$.
    - Gồm Rotavirus (gây tiêu chảy cấp ở trẻ em), Enterovirus, Viêm gan A ($HAV$) và Norovirus.
  - Động vật nguyên sinh và ký sinh trùng (Protozoa & Helminths):
    - Bào nang *Giardia lamblia* (kích thước $8 - 14\text{ }\mu\text{m}$).
    - Noãn nang *Cryptosporidium parvum* (kích thước $4 - 6\text{ }\mu\text{m}$).
    - Vỏ kitin của noãn nang *Cryptosporidium* trơ với hóa chất clo. Nhà máy phải dùng lọc màng, ozon hoặc tia UV để xử lý.
  - Tảo (*Algae*) và nấm (*Fungi*): Gây mùi vị lạ cho nước và làm nghẹt bể lọc cát.

#### 1.1.2 Nguồn Nước mưa và Nước biển (Rainwater & Seawater Sources)

##### 1.1.2.1 Nước Mưa: Đặc tính Hóa lý, Độ ổn định và Trữ lượng
- **Độ khoáng hóa và độ tinh khiết**:
  - Hàm lượng tổng chất rắn hòa tan (TDS) rất thấp, dao động từ $10\text{ mg/L}$ đến $50\text{ mg/L}$.
  - Nước mưa hầu như không chứa ion canxi và magie. Độ cứng xấp xỉ bằng không (nước siêu mềm).
- **Tính axit tự nhiên của nước mưa**:
  - Nước mưa hòa tan khí carbonic trong khí quyển tạo thành axit carbonic:
    $$CO_2 + H_2O \rightleftharpoons H_2CO_3 \rightleftharpoons H^+ + HCO_3^-$$
  - Giá trị pH của nước mưa tự nhiên không ô nhiễm dao động từ $5.0$ đến $5.6$.
  - Mưa axit xảy ra khi khí quyển nhiễm nhiều $SO_2$ và $NO_x$. Giá trị pH của mưa axit giảm xuống $3.5 - 4.5$.
- **Tính ăn mòn xâm thực (Aggressive Corrosiveness)**:
  - Nước mưa thiếu hụt ion canxi ($Ca^{2+}$) và ion kiềm ($HCO_3^-$).
  - Chỉ số bão hòa Langelier của nước mưa luôn âm rất sâu ($LSI \ll 0$).
  - Nước mưa hòa tan vôi trong bể xi măng và hòa tan kim loại đường ống ($Pb, Cu$).
- **Hệ thống thu gom và trữ nước mưa phân tán**:
  - Quy trình vận hành và cấu trúc hệ thống gồm 4 bộ phận:
    1. Bề mặt mái thu (Catchment Surface): Mái ngói, tôn mạ hoặc bê tông sạch trơ hóa học. Tuyệt đối không dùng mái fibro-xi măng chứa amiăng.
    2. Thiết bị xả nước mưa đợt đầu (First-Flush Diverter): Tách bỏ $1 - 2\text{ mm}$ mưa đầu trận (tương đương $10 - 20\text{ L}$ cho mỗi $10\text{ m}^2$ mái). Thiết bị này loại bỏ bụi bẩn, phân chim và lá cây.
    3. Bể trữ nước mưa kín (Storage Cistern): Bể composite hoặc nhựa HDPE. Bể phải chắn kín ánh sáng mặt trời để ngăn rêu tảo phát triển và muỗi đẻ trứng.
    4. Cụm xử lý bổ sung: Lọc cát thạch anh, lọc than hoạt tính và đun sôi hoặc khử trùng nano bạc trước khi uống trực tiếp.

##### 1.1.2.2 Nước Biển: Độ mặn, Tỷ trọng và Rào cản Khử muối
- **Độ mặn và thành phần ion chính**:
  - Độ mặn trung bình của nước biển dao động từ $3.3\%$ đến $3.7\%$.
  - Giá trị thiết kế chuẩn lấy bằng $3.5\%$ (tương đương $35\text{ g/L}$ hoặc $35,000\text{ mg/L TDS}$).
  - Hàm lượng các ion chính trong nước biển có độ mặn $3.5\%$:
    - Clorua ($Cl^-$): $19,350\text{ mg/L}$ ($55.0\%$ tổng lượng anion).
    - Natri ($Na^+$): $10,760\text{ mg/L}$ ($30.6\%$ tổng lượng cation).
    - Sunfat ($SO_4^{2-}$): $2,710\text{ mg/L}$.
    - Magie ($Mg^{2+}$): $1,290\text{ mg/L}$.
    - Canxi ($Ca^{2+}$): $410\text{ mg/L}$.
    - Kali ($K^+$): $390\text{ mg/L}$.
    - Bicarbonate ($HCO_3^-$): $140\text{ mg/L}$.
- **Áp suất thẩm thấu ($\Pi$) và rào cản năng lượng**:
  - Áp suất thẩm thấu xác định theo phương trình Van 't Hoff:
    $$\Pi = i \cdot M \cdot R \cdot T$$
    - $\Pi$: Áp suất thẩm thấu của dung dịch nước biển ($\text{bar}$).
    - $i$: Hệ số phân ly ion Van 't Hoff (không thứ nguyên).
    - $M$: Tổng nồng độ mol của các phần tử chất tan ($\text{mol/L}$).
    - $R$: Hằng số khí lý tưởng ($0.08314\text{ L}\cdot\text{bar/(mol}\cdot\text{K)}$).
    - $T$: Nhiệt độ nhiệt động học tuyệt đối ($\text{K}$, $T = t^\circ\text{C} + 273.15$).
  - Giá trị áp suất thẩm thấu của nước biển tự nhiên tại $25^\circ\text{C}$: $\Pi \approx 25 - 28\text{ bar}$ ($360 - 400\text{ psi}$).
  - Áp suất vận hành thực tế của trạm lọc màng thẩm thấu ngược nước biển (SWRO):
    - Bơm cao áp phải thắng áp suất thẩm thấu cộng với trở lực màng.
    - Áp suất vận hành thực tế duy trì trong khoảng $55\text{ bar}$ đến $70\text{ bar}$ ($800 - 1000\text{ psi}$).
- **Tỷ trọng và khối lượng riêng của nước biển**:
  - Hàm lượng muối cao làm tăng khối lượng riêng của nước biển:
    $$\rho_{\text{seawater}} \approx 1.025\text{ kg/L} = 1025\text{ kg/m}^3\text{ (tại } 20^\circ\text{C)}$$
  - Tỷ trọng tương đối so với nước chuẩn tại $4^\circ\text{C}$: $\text{SG} = 1.025$.
- **Hiện tượng hạ điểm đóng băng (Freezing Point Depression)**:
  - Nồng độ ion muối làm hạ nhiệt độ kết tinh của nước.
  - Điểm đóng băng của nước biển có độ mặn $3.5\%$ hạ xuống mức $-1.9^\circ\text{C}$ (thay vì $0.0^\circ\text{C}$ của nước cất).
- **Độ kiềm và pH của nước biển**:
  - Nước biển có dải pH ổn định từ $7.5$ đến $8.4$.
  - Hệ đệm tự nhiên carbonate ($HCO_3^- / CO_3^{2-}$) và borate ($B(OH)_3 / B(OH)_4^-$) kiểm soát ổn định giá trị pH này.
- Tạp chất trong nước tự nhiên được phân chia theo kích thước hạt:
  - **Hình 13.** Biểu đồ phân loại 5 nhóm tạp chất chủ yếu trong nước tự nhiên
    - <img src="ch01_introduction/assets/fig_13_p5.png" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Phân bố kích thước hạt từ ion hòa tan, keo hữu cơ đến cặn lơ lửng.
    - **Từ đâu mà thấy được**
      - Trục hoành thang logarit phân định ranh giới giữa chất hòa tan, keo và chất rắn lơ lửng.

### 1.2 Hệ thống cấp nước

#### 1.1.3 Nguồn Nước ngầm: Chất lượng, Khoáng hóa và Nhiễm bẩn (Groundwater Quality, Minerals & Contamination)

##### 1.1.3.1 Địa tầng Thủy văn và Cơ chế Hòa tan Khoáng chất Tự nhiên
- **Cấu trúc tầng chứa nước (Aquifer Structures)**:
  - Tầng không áp (Unconfined Aquifer) nằm sát mặt đất. Mực nước tự do thay đổi theo mùa và chịu áp suất khí quyển.
  - Tầng chứa nước không áp nhận nước bổ cập nhanh từ nước mưa thấm. Tầng này dễ nhiễm bẩn từ các hoạt động trên mặt đất.
  - Tầng có áp (Confined Aquifer) nằm kẹp giữa hai lớp địa chất không thấm nước. Nước chịu áp lực thủy tĩnh cao.
  - Khi khoan giếng vào tầng có áp, mực nước tự dâng cao hơn đỉnh tầng chứa nước. Nước có độ an toàn vi sinh cao.

- **Cơ chế hòa tan sắt ($Fe^{2+}$) và mangan ($Mn^{2+}$)**:
  - Vi sinh vật trong đất tiêu thụ hết oxy hòa tan ($DO \to 0\text{ mg/L}$) khi phân hủy chất hữu cơ.
  - Môi trường ngầm chuyển sang trạng thái khử mạnh với thế oxy hóa khử âm ($Eh < 0$).
  - Nước ngầm hòa tan khoáng sắt và mangan không tan trong đất đá:
    $$Fe^{3+}_{\text{(rắn)}} + e^- \to Fe^{2+}_{\text{(hòa tan)}}$$
    $$MnO_{2\text{(rắn)}} + 4H^+ + 2e^- \to Mn^{2+}_{\text{(hòa tan)}} + 2H_2O$$
  - Nước mới bơm lên từ giếng khoan luôn trong suốt. Nước chứa ion sắt ($Fe^{2+}$) và mangan ($Mn^{2+}$) hòa tan.
  - Khi tiếp xúc không khí, oxy oxy hóa $Fe^{2+}$ thành kết tủa $Fe(OH)_3$ màu nâu đỏ. Quá trình làm nước đục và gây ố vàng.

- **Cơ chế hòa tan canxi ($Ca^{2+}$), magie ($Mg^{2+}$) tạo độ cứng**:
  - Vi sinh vật và rễ cây hô hấp giải phóng lượng lớn khí $CO_2$ vào đất ($20 - 100\text{ mg/L}$).
  - Khí $CO_2$ hòa tan vào nước tạo thành axit carbonic ($H_2CO_3$).
  - Axit carbonic hòa tan đá vôi ($CaCO_3$) và đá dolomit ($CaMg(CO_3)_2$):
    $$CaCO_{3\text{(rắn)}} + CO_2 + H_2O \rightleftharpoons Ca^{2+} + 2HCO_3^-$$
    $$CaMg(CO_3)_{2\text{(rắn)}} + 2CO_2 + 2H_2O \rightleftharpoons Ca^{2+} + Mg^{2+} + 4HCO_3^-$$
  - Phản ứng giải phóng ion $Ca^{2+}$ và $Mg^{2+}$, hình thành độ cứng carbonate trong nước ngầm.

- **Độc chất tự nhiên trong nước ngầm**:
  - Asen tự nhiên ($As$) giải phóng từ quặng pirit ($FeAsS$) hoặc quá trình khử khoáng sắt hydroxit.
  - Asen tồn tại ở dạng arsenite ($As^{3+}$) độc tính cao hoặc arsenate ($As^{5+}$). Nồng độ asen tầng nông thường vượt $0{,}01\text{ mg/L}$.
  - Fluoride ($F^-$) hòa tan từ khoáng fluorit ($CaF_2$). Nồng độ fluoride vượt $1{,}5\text{ mg/L}$ gây hỏng men răng và xốp xương.
  - Phóng xạ Radon ($^{222}Rn$) và Radium ($^{226}Ra$) hòa tan từ các đới nứt nẻ của đá granit.

##### 1.1.3.2 Nước ngầm Nhiễm lợ (Brackish Groundwater)
- Khai thác nước ngầm quá mức làm hạ thấp mực nước áp lực tĩnh.
- Nước biển xâm nhập vào các tầng chứa nước ngọt tại vùng ven biển.
- Nước ngầm chuyển thành nước lợ với hàm lượng tổng chất rắn hòa tan cao:
  $$\text{TDS} = 1000 - 5000\text{ mg/L}$$
- Kỹ sư phải dùng công nghệ màng lọc thẩm thấu ngược nước lợ (BWRO) hoặc điện thẩm tích (EDR) để khử mặn.

##### 1.1.3.3 Cơ chế Nhiễm bẩn Nhân sinh Tầng Nước ngầm (Anthropogenic Contamination)
- **Rò rỉ bể chứa xăng dầu ngầm (UST Leaks)**:
  - Bồn thép ngầm bị ăn mòn điện hóa sau 15 đến 30 năm chôn lấp.
  - Nhiên liệu rò rỉ phát tán nhóm hydrocarbon thơm BTEX (Benzene, Toluene, Ethylbenzene, Xylenes) và phụ gia MTBE.
  - Benzene là chất gây ung thư nhóm 1. MTBE tan nhiều trong nước, phân hủy sinh học chậm và di chuyển xa hàng kilômét.

- **Ô nhiễm nitrate ($NO_3^-$) từ nước thải và nông nghiệp**:
  - Bể tự hoại rò rỉ và phân bón hóa học dư thừa ($NH_4NO_3$) thấm sâu vào đất.
  - Vi khuẩn hiếu khí nitrat hóa amoni thành nitrite ($NO_2^-$) và nitrate ($NO_3^-$):
    $$NH_4^+ + 2O_2 \to NO_3^- + 2H^+ + H_2O$$
  - Ion nitrate không bị keo đất tích điện âm giữ lại. Nitrate đi thẳng vào tầng nước ngầm.
  - Nồng độ nitrate vượt $50\text{ mg/L}$ gây hội chứng trẻ xanh (Methemoglobinemia) ở trẻ sơ sinh.

- **Dung môi công nghiệp clo hóa (DNAPL)**:
  - Dung môi tẩy rửa cơ khí Trichloroethylene (TCE) và Tetrachloroethylene (PCE) ngấm vào đất.
  - Hợp chất này có tỷ trọng nặng hơn nước, tạo pha lỏng hữu cơ đậm đặc (DNAPL).
  - Túi DNAPL chìm xuống đáy tầng ngậm nước, hòa tan chậm qua nhiều thập kỷ và gây độc kéo dài.

##### 1.1.3.4 Ma trận Đánh giá Ưu điểm và Nhược điểm của Nước ngầm
- **Bảng so sánh ưu nhược điểm kỹ thuật của nước ngầm**:

| Chỉ tiêu kỹ thuật | Ưu điểm của nguồn nước ngầm | Nhược điểm và thách thức vận hành |
|---|---|---|
| **Độ đục và hạt cặn** | Độ đục thấp ($\le 1 - 2\text{ NTU}$), ít cặn lơ lửng nhờ đất cát lọc tự nhiên. | Cát mịn có thể lọt qua lưới lọc gây mài mòn cánh bơm giếng sâu. |
| **Ô nhiễm vi sinh** | Không có vi khuẩn gây bệnh và ký sinh trùng do thiếu ánh sáng. | Nước giếng nông dễ nhiễm bẩn phân nếu gần hố xí tự hoại. |
| **Nhiệt độ nước** | Nhiệt độ ổn định quanh năm ($22 - 25^\circ\text{C}$). | Nước có thể chứa khí cháy ($CH_4$) hoặc khí độc ($H_2S$). |
| **Chất hữu cơ tự nhiên** | Nồng độ chất hữu cơ thấp, ít tạo phụ phẩm khử trùng DBP. | Hàm lượng khoáng hòa tan cao ($Fe, Mn, Ca^{2+}, Mg^{2+}$). |
| **Công trình xử lý** | Mặt bằng xử lý gọn, bỏ qua bể keo tụ và bể lắng cặn thô. | Chi phí điện bơm giếng sâu cao, chi phí hóa chất khử cứng lớn. |
| **Mức độ bền vững** | Nguồn nước ngầm an toàn trước ô nhiễm bề mặt tức thời. | Tầng ngầm đã nhiễm độc asen hoặc dung môi rất khó phục hồi. |

---

#### 1.1.4 Nguồn Nước mặt: Thủy vực và Động lực Lưu vực (Surface Water Characteristics & Watershed Dynamics)

##### 1.1.4.1 Phân loại Thủy vực Nước mặt và Biến động Mùa vụ
- **Thủy vực chảy (Hệ Lotic - Sông, Suối)**:
  - Vận tốc dòng chảy lớn ($v = 0{,}5 - 2{,}5\text{ m/s}$).
  - Khả năng tự sục khí bề mặt cao, oxy hòa tan dồi dào ($DO = 6 - 8\text{ mg/L}$).
  - Chất lượng nước biến động tức thời theo lượng mưa và hoạt động xả thải trên lưu vực.

- **Thủy vực tĩnh (Hệ Lentic - Hồ Tự nhiên, Hồ chứa)**:
  - Vận tốc dòng chảy rất nhỏ ($v \approx 0\text{ m/s}$), thời gian lưu nước kéo dài từ vài tuần đến nhiều năm.
  - Cặn lơ lửng thô tự lắng tốt, tạo độ đục nền ổn định.
  - Hiện tượng phân tầng nhiệt độ (Thermal Stratification) xuất hiện vào mùa khô nóng:
    - Tầng mặt (Epilimnion) ấm, giàu oxy hòa tan nhưng chứa nhiều tảo.
    - Tầng đáy (Hypolimnion) lạnh, tù đọng, yếm khí, chứa nhiều sắt, mangan, photpho và khí $H_2S$.
  - Tích tụ nitơ và photpho gây hiện tượng phú dưỡng (Eutrophication). Tảo lam nở hoa tiết độc tố Microcystin và chất gây mùi hôi (Geosmin, MIB).

- **Xung đột biến độ đục do mưa bão**:
  - Mưa lớn xói mòn lưu vực và cuốn trôi phù sa vào sông suối.
  - Độ đục bùng phát đột ngột từ $20 - 50\text{ NTU}$ lên mức $500 - 3000\text{ NTU}$ trong vài giờ.
  - Nước mưa làm loãng nồng độ ion bicarbonate, làm độ kiềm sụt giảm ($< 20 - 30\text{ mg/L as }CaCO_3$).
  - Kỹ sư phải tăng liều lượng phèn, châm thêm kiềm và dùng polymer trợ lắng.

##### 1.1.4.2 Hợp chất Hữu cơ Tự nhiên (NOM) và Tiền chất Tạo Phụ phẩm Khử trùng
- **Phân loại nguồn gốc chất hữu cơ tự nhiên**:
  - Nguồn nội sinh (Autochthonous): Do hoạt động quang hợp và phân rã của tảo, vi sinh vật trong nước sinh ra. Chỉ số hấp thụ tia cực tím riêng thấp ($SUVA_{254} < 2\text{ L/(mg}\cdot\text{m)}$).
  - Nguồn ngoại sinh (Allochthonous): Rửa trôi từ thảm thực vật và đất rừng mục nát. Nguồn này chứa nhiều axit humic và axit fulvic ($SUVA_{254} > 3 - 4\text{ L/(mg}\cdot\text{m)}$). Nước có màu vàng nâu.

- **Phản ứng tạo phụ phẩm khử trùng (DBP Formation)**:
  - Clo khử trùng phản ứng với nhân thơm của axit humic và fulvic.
  - Phản ứng sinh ra các hợp chất hữu cơ clo hóa độc hại:
    $$\text{NOM} + Cl_2 \to \text{THMs} + \text{HAAs}$$
  - Sản phẩm gồm Trihalomethanes ($CHCl_3, CHBrCl_2, CHBr_2Cl, CHBr_3$) và Haloacetic Acids. Các chất này gây ung thư gan, thận và bàng quang.

##### 1.1.4.3 Rủi ro Ô nhiễm Vi sinh vật Nguồn Nước mặt
- Nước mặt nhận nước thải đô thị và dòng chảy tràn chăn nuôi gia súc.
- Nguồn nước luôn tiềm ẩn vi khuẩn gây bệnh tả (*Vibrio cholerae*), thương hàn (*Salmonella*), lỵ (*Shigella*).
- Bào nang *Giardia lamblia* ($8 - 14\text{ }\mu\text{m}$) và noãn nang *Cryptosporidium parvum* ($4 - 6\text{ }\mu\text{m}$) xuất hiện phổ biến.
- Vỏ kitin của noãn nang *Cryptosporidium* kháng clo khử trùng thông thường. Nhà máy nước phải dùng rào cản keo tụ - lắng - lọc cát hoặc khử trùng bằng Ozon và tia UV.

##### 1.1.4.4 So sánh Đặc tính Kỹ thuật giữa Nước mặt và Nước ngầm
- **Bảng đối chiếu thông số giữa hai nguồn nước**:

| Thông số kỹ thuật | Nguồn nước mặt (Sông, Hồ chứa) | Nguồn nước ngầm (Tầng sâu) |
|---|---|---|
| **Độ đục (Turbidity)** | Cao ($10 - 2000\text{ NTU}$), biến động lớn theo mùa. | Rất thấp ($\le 1 - 2\text{ NTU}$), ổn định quanh năm. |
| **Độ màu (Color)** | Cao ($10 - 150\text{ TCU}$), do phức humic và keo sét. | Thấp (chỉ tăng khi sắt bị oxy hóa tạo cặn). |
| **Oxy hòa tan (DO)** | Cao ($6 - 8\text{ mg/L}$), tiếp xúc khí quyển tốt. | Rất thấp hoặc bằng 0 ($0 - 2\text{ mg/L}$), yếm khí. |
| **Khí Carbonic ($CO_2$)** | Thấp ($0 - 5\text{ mg/L}$). | Cao ($20 - 100\text{ mg/L}$), gây ăn mòn đường ống. |
| **Sắt và Mangan ($Fe, Mn$)** | Thấp, tồn tại chủ yếu ở dạng huyền phù liên kết bùn. | Thường cao ($1 - 20\text{ mg/L}$), tồn tại ở dạng hòa tan. |
| **Độ cứng ($Ca^{2+}, Mg^{2+}$)** | Thấp đến trung bình ($20 - 100\text{ mg/L as }CaCO_3$). | Thường cao ($100 - 500\text{ mg/L as }CaCO_3$). |
| **Chất hữu cơ (TOC, NOM)** | Cao ($2 - 15\text{ mg/L}$), tiềm ẩn nguy cơ tạo THMs. | Thấp ($< 1 - 2\text{ mg/L}$), ít nguy cơ tạo THMs. |
| **Vi sinh vật gây bệnh** | Nguy cơ rất cao (vi khuẩn phân, virus, kén ký sinh trùng). | Nguy cơ thấp nếu miệng giếng bảo vệ đúng kỹ thuật. |
| **Sơ đồ xử lý chuẩn** | Keo tụ $\to$ Tạo bông $\to$ Lắng $\to$ Lọc $\to$ Clo hóa. | Làm thoáng $\to$ Kiềm hóa $\to$ Lắng $\to$ Lọc $\to$ Clo hóa. |

---
- Công trình thu nước mặt cần vươn ra xa bờ để lấy nước tầng mặt ít bùn đáy:
- Đài thu nước kết hợp giếng bờ là giải pháp tối ưu cho sông có biên độ mực nước lớn:
  - **Hình 17.** Cụm công trình đài thu nước kết hợp giếng bờ ven sông
    - <img src="ch01_introduction/assets/fig_17_p19.jpeg" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - Sơ đồ thu nước sông có dao động mực nước lớn, bảo vệ máy bơm không bị ngập lũ.
    - **Từ đâu mà thấy được**
      - Ống tự chảy dẫn nước từ lòng sông vào giếng bờ sâu đặt cụm bơm chìm.
  - **Hình 16.** Công trình thu nước mặt thực tế với cầu dẫn và trạm bơm
    - <img src="ch01_introduction/assets/fig_16_p19.jpeg" alt="Hình 16" />
    - **Hình này chứng minh điều gì**
      - Cấu trúc đài thu nước mặt xa bờ giúp thu nước tầng mặt trong sạch, hạn chế bùn đáy.
    - **Từ đâu mà thấy được**
      - Cầu dẫn nối bờ và đài thu độc lập nằm sâu giữa lòng hồ.
- Giếng khoan khai thác nước ngầm cấu tạo gồm ống vách, ống lọc và vành sỏi chèn:
  - **Hình 20.** Sơ đồ cấu tạo giếng khoan khai thác nước dưới đất
    - <img src="ch01_introduction/assets/fig_20_p21.png" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - Ống lọc đặt tại tầng chứa nước cát sỏi và lớp chèn sỏi ngăn cát mịn xâm nhập giếng.
    - **Từ đâu mà thấy được**
      - Cấu trúc tầng lọc ống lọc khe kết hợp vành sỏi đệm xung quanh thành giếng.

### 1.3 Chất lượng nước

#### 1.2.1 Ba Phân khu Cốt lõi của Hệ thống Cấp nước Đô thị

##### 1.2.1.1 Phân khu Thu nước và Trạm Bơm Cấp 1 (Water Intake & Low-Lift Pumping Station)
- **Công trình thu nước mặt**:
  - Song chắn rác thô giữ lại cành cây, bèo tây và rác nổi kích thước lớn.
  - Lưới chắn rác tinh ngăn rong rêu và rác nhỏ lọt vào ngăn hút bơm.
  - Cửa thu ven bờ (Shore Intake) đặt tại bờ sông có mái dốc đứng và nền địa chất ổn định.
  - Cửa thu lòng sông (Riverbed Intake) dẫn nước vào ống tự chảy hoặc ống xi-phông về giếng thu bờ sông.
  - Trạm bơm cấp 1 dùng máy bơm ly tâm trục đứng hoặc ngang, hoạt động ở cột áp thấp ($H = 10 - 25\text{ m}$). Bơm đẩy nước lên bể trộn đầu trạm xử lý.

- **Công trình thu nước ngầm**:
  - Mạng lưới giếng khoan khai thác sâu $50 - 250\text{ m}$ vào tầng ngậm nước có áp.
  - Ống lọc giếng khoan (Well Screen) xẻ rãnh chuẩn bọc sỏi lọc xung quanh để giữ cát mịn.
  - Bơm chìm giếng sâu (Submersible Pump) thả ngập dưới mực nước động, đẩy nước trực tiếp lên dàn làm thoáng.

##### 1.2.1.2 Nhà máy Xử lý Nước cấp (Water Treatment Plant - WTP)
- **Tuyến thủy lực tự chảy bằng trọng lực (Gravity Hydraulic Flow)**:
  - Dòng nước tự chảy liên tục qua các công trình đơn vị: Trộn nhanh $\to$ Tạo bông $\to$ Lắng $\to$ Lọc cát.
  - Đáy máng bể trộn đặt ở cao trình cao nhất. Cao trình này thắng toàn bộ tổn thất áp lực trên đường ống và qua các lớp cát lọc.
  - Nước sau lọc tự chảy vào bể chứa nước sạch nằm ngầm dưới đất.

- **Khu châm hóa chất (Chemical Feed Facilities)**:
  - Bố trí kho chứa và bồn pha dung dịch phèn nhôm ($Al_2(SO_4)_3$), phèn PAC, vôi tôi ($Ca(OH)_2$), polymer.
  - Bơm định lượng màng vận chuyển hóa chất qua đường ống nhựa chống ăn mòn vào điểm châm.

- **Khu xử lý bùn cặn (Sludge Treatment Facilities)**:
  - Bùn xả từ đáy bể lắng và nước rửa ngược bể lọc thu gom về bể nén bùn trọng lực.
  - Máy ép bùn băng tải hoặc máy ly tâm tách nước tạo bánh bùn khô có độ ẩm thấp để vận chuyển đi chôn lấp.

##### 1.2.1.3 Mạng lưới Truyền dẫn và Phân phối Nước sạch (Distribution Network)
- **Bể chứa nước sạch (Clearwell / Finished Water Reservoir)**:
  - Bể điều hòa chênh lệch giữa công suất sản xuất đều đặn của nhà máy và biểu đồ tiêu thụ nước dao động của đô thị.
  - Bể tạo thời gian tiếp xúc khử trùng tối thiểu với clo:
    $$CT \ge 30\text{ phút}$$
  - Bể lưu trữ dung tích nước chữa cháy dự phòng bắt buộc trong $3\text{ giờ}$ liên tục.

- **Trạm bơm cấp 2 (High-Lift Pumping Station)**:
  - Máy bơm ly tâm công suất lớn đẩy nước vào mạng lưới đường ống chính.
  - Cột áp trạm bơm cấp 2 duy trì mức cao ($H = 40 - 70\text{ m}$).
  - Trạm gắn biến tần (VFD) để tự động điều chỉnh tốc độ động cơ theo áp lực mạng lưới theo giờ.

- **Đài nước điều hòa (Elevated Water Tower)**:
  - Xây dựng tại điểm cao trong đô thị hoặc cuối mạng lưới đường ống.
  - Đài nước ổn định áp lực mạng lưới, chống búa nước (water hammer) và cấp nước bù vào giờ cao điểm.

- **Mạng lưới đường ống phân phối**:
  - Mạng lưới quy hoạch thành mạng vòng khép kín (looped network).
  - Khi một đoạn ống vỡ, van phân đoạn cô lập đoạn hư hại mà không gây mất nước cục bộ diện rộng.

---

#### 1.2.2 Phân loại Hệ thống Cấp nước theo Mục đích Sử dụng

##### 1.2.2.1 Hệ thống Cấp nước Sinh hoạt Đô thị (Domestic Water Supply)
- Cung cấp nước cho ăn uống, tắm giặt, nấu nướng và dịch vụ công cộng.
- Chất lượng nước cấp bắt buộc đạt 100% chỉ tiêu theo quy chuẩn QCVN 01-1:2018/BYT.
- Tiêu chuẩn dùng nước thiết kế theo quy mô đô thị dao động từ $150 - 250\text{ L/người}\cdot\text{ngày}$.
- Áp lực tự do tối thiểu tại vòi vào nhà 1 tầng là $10\text{ m}$ cột nước, mỗi tầng tiếp theo tăng thêm $4\text{ m}$.

##### 1.2.2.2 Hệ thống Cấp nước Công nghiệp (Industrial Process Water)
- **Nước làm mát gián tiếp (Cooling Water)**:
  - Khối lượng tiêu thụ rất lớn. Nước yêu cầu kiểm soát độ cứng và độ kiềm để tránh kết tủa $CaCO_3$ trong bình ngưng tụ.
  - Cần châm hóa chất diệt khuẩn chống màng nhầy sinh học (biofilm) và ức chế ăn mòn.

- **Nước cấp lò hơi (Boiler Feedwater)**:
  - Yêu cầu chất lượng cực kỳ khắt khe theo áp suất lò hơi.
  - Nước phải qua trao đổi ion khử cứng hoàn toàn ($\text{TH} \approx 0\text{ mg/L as }CaCO_3$).
  - Khử oxy hòa tan đến ngưỡng an toàn ($DO < 0{,}005\text{ mg/L}$) để ngăn thủng ống lò hơi do ăn mòn điểm.
  - Hàm lượng silica phải đạt chuẩn ($SiO_2 < 0{,}01\text{ mg/L}$) nhằm ngăn ngừa tạo vảy silicat cứng trên vách truyền nhiệt.

- **Nước công nghệ dệt nhuộm và sản xuất giấy**:
  - Kiểm soát nghiêm ngặt nồng độ sắt ($Fe < 0{,}05\text{ mg/L}$) và mangan ($Mn < 0{,}02\text{ mg/L}$).
  - Hàm lượng kim loại cao sẽ làm loang ố màu vải sợi và làm sẫm màu bột giấy tẩy trắng.

- **Nước siêu tinh khiết (Ultrapure Water - UPW)**:
  - Dùng trong công nghiệp sản xuất linh kiện bán dẫn và dược phẩm tiêm truyền.
  - Điện trở suất đạt giới hạn lý thuyết:
    $$\rho = 18{,}2\text{ M}\Omega\cdot\text{cm}\text{ ở }25^\circ\text{C}$$
  - Hàm lượng carbon hữu cơ tổng $TOC < 1 - 5\text{ ppb}$, không chứa hạt cặn kích thước $> 0{,}05\text{ }\mu\text{m}$, vô trùng tuyệt đối.

##### 1.2.2.3 Hệ thống Cấp nước Chữa cháy và Hệ thống Kết hợp (Fire Fighting & Combined Municipal Systems)
- Đô thị dùng hệ thống cấp nước kết hợp truyền tải đồng thời nước sinh hoạt và nước cứu hỏa.
- Trụ cứu hỏa ($D100 - D150\text{ mm}$) lắp trực tiếp trên tuyến ống phân phối chính với khoảng cách $\le 150\text{ m}$.
- Lưu lượng chữa cháy cộng gộp trực tiếp vào nhu cầu dùng nước ngày lớn nhất ($Q_{\text{max-day}}$).
- Bể chứa nước sạch dự trữ dung tích chữa cháy đáp ứng thời gian dập tắt đám cháy liên tục trong $3\text{ giờ}$.

---

### 1.4 Tiêu chuẩn

#### 1.3.1 Các Nhóm Chỉ tiêu Chất lượng Nước Cơ bản

##### 1.3.1.1 Nhóm Chỉ tiêu Vật lý và Thẩm mỹ (Physical & Aesthetic Parameters)
- **Độ đục (Turbidity, NTU)**:
  - Đo cường độ tán xạ ánh sáng của các hạt cặn sét, chất lơ lửng và bùn vi sinh trong nước.
  - Giới hạn nước sinh hoạt là $\le 2\text{ NTU}$. Nước sau lọc tại nhà máy hiện đại kiểm soát $\le 0{,}2 - 0{,}5\text{ NTU}$.

- **Độ màu (Color, TCU / thang Pt-Co)**:
  - Độ màu thực sinh ra do axit humic hòa tan hoặc ion kim loại ($Fe^{3+}, Mn^{2+}$). Ngưỡng quy chuẩn là $\le 15\text{ TCU}$.

- **Mùi và vị (Taste and Odour, TON)**:
  - Nước uống không được có mùi vị lạ. Mùi bùn mốc xuất phát từ Geosmin và MIB do tảo tiết ra.

- **Tổng chất rắn hòa tan (TDS, mg/L) và độ dẫn điện (EC, $\mu\text{S/cm}$)**:
  - TDS biểu thị tổng ion khoáng hòa tan. Mối liên hệ thực nghiệm:
    $$\text{TDS (mg/L)} \approx (0{,}55 - 0{,}70) \times \text{EC (}\mu\text{S/cm)}$$
  - Giới hạn nồng độ TDS cho phép trong nước sinh hoạt là $\le 1000\text{ mg/L}$.

##### 1.3.1.2 Nhóm Chỉ tiêu Hóa học và Độc chất (Chemical Parameters & Toxic Contaminants)
- **Nhu cầu oxy hóa học (COD) và độ tiêu thụ oxy ($KMnO_4$)**:
  - Đo lường mức độ ô nhiễm hợp chất hữu cơ hòa tan. Nước ngầm sạch có độ tiêu thụ oxy $\le 1\text{ mg/L}$.

- **Hợp chất chứa Nitơ ($NH_4^+, NO_2^-, NO_3^-$)**:
  - Amoni ($NH_4^+$) cảnh báo nguồn nước mới bị nhiễm nước thải sinh hoạt và làm hao tốn nhiều clo khử trùng.
  - Nitrite ($NO_2^-$) là chất trung gian có độc tính cao, giới hạn tối đa $\le 0{,}05\text{ mg/L}$.
  - Nitrate ($NO_3^-$) biểu thị quá trình oxy hóa sinh học đã hoàn tất.

- **Kim loại nặng độc tính cao**:
  - Sắt tổng số ($Fe \le 0{,}3\text{ mg/L}$) và Mangan tổng số ($Mn \le 0{,}1\text{ mg/L}$).
  - Asen ($As \le 0{,}01\text{ mg/L}$), Chì ($Pb \le 0{,}01\text{ mg/L}$), Cadmium ($Cd \le 0{,}003\text{ mg/L}$), Thủy ngân ($Hg \le 0{,}001\text{ mg/L}$).

##### 1.3.1.3 Nhóm Chỉ tiêu Vi sinh vật Chỉ thị (Microbiological Indicator Parameters)
- **Tổng số Coliform**:
  - Vi khuẩn gram âm hình que, lên men lactose sinh hơi ở $35 - 37^\circ\text{C}$. Giới hạn nước sinh hoạt là $< 3\text{ CFU/100 mL}$.

- **Escherichia coli (E. coli) và Coliform phân**:
  - Vi khuẩn chịu nhiệt cư trú thường xuyên trong ruột người và động vật máu nóng.
  - Sự xuất hiện của *E. coli* khẳng định nguồn nước bị nhiễm phân tươi. Tiêu chuẩn quy định không được có ($< 1\text{ CFU/100 mL}$).

---

#### 1.3.2 Cân bằng Hóa học Hệ Carbonate và Khí CO2 Hòa tan

##### 1.3.2.1 Chuỗi Phản ứng Hòa tan Khí CO2 và Axit Carbonic Biểu kiến
- **Hòa tan khí Carbonic theo Định luật Henry**:
  - Khí $CO_2$ trong khí quyển hòa tan vào pha lỏng:
    $$CO_{2\text{(k)}} \rightleftharpoons CO_{2\text{(dd)}}$$
  - Nồng độ hòa tan phụ thuộc vào áp suất riêng phần $P_{CO_2}$ qua hằng số Henry $K_H = 3{,}39 \times 10^{-2}\text{ mol/(L}\cdot\text{atm)}$ ở $25^\circ\text{C}$:
    $$[CO_{2\text{(dd)}}] = K_H \cdot P_{CO_2}$$

- **Thủy hóa tạo axit carbonic biểu kiến**:
  - Phân tử $CO_2$ phản ứng thuận nghịch với nước tạo $H_2CO_3$:
    $$CO_{2\text{(dd)}} + H_2O \rightleftharpoons H_2CO_3$$
  - Chỉ dưới 0.3% lượng $CO_2$ hòa tan chuyển thành $H_2CO_3$. Hóa học môi trường quy ước tổng nồng độ là axit carbonic biểu kiến:
    $$[H_2CO_3^*] = [CO_{2\text{(dd)}}] + [H_2CO_3]$$

##### 1.3.2.2 Hằng số Phân ly Thứ nhất của Axit Carbonic (K1)
- Phản ứng phân ly giải phóng proton bậc 1:
  $$H_2CO_3^* \rightleftharpoons H^+ + HCO_3^-$$
- Phương trình cân bằng phân ly bậc 1 ở $25^\circ\text{C}$:
  $$K_1 = \frac{[\text{H}^+][\text{HCO}_3^-]}{[\text{H}_2\text{CO}_3^*]} = 4{,}47 \times 10^{-7} \quad (\text{p}K_1 = 6{,}35)$$
- Ý nghĩa: Ở $\text{pH} = 6{,}35$, nồng độ khí $CO_2$ tự do cân bằng bằng nồng độ ion bicarbonate ($[H_2CO_3^*] = [HCO_3^-]$).

##### 1.3.2.3 Hằng số Phân ly Thứ hai của Bicarbonate (K2)
- Ion bicarbonate phân ly tiếp trong môi trường kiềm:
  $$HCO_3^- \rightleftharpoons H^+ + CO_3^{2-}$$
- Phương trình cân bằng phân ly bậc 2 ở $25^\circ\text{C}$:
  $$K_2 = \frac{[\text{H}^+][\text{CO}_3^{2-}]}{[\text{HCO}_3^-]} = 4{,}69 \times 10^{-11} \quad (\text{p}K_2 = 10{,}33)$$
- Ý nghĩa: Nâng $\text{pH} > 10{,}33$ làm chuyển hóa phần lớn bicarbonate thành carbonate ($CO_3^{2-}$), tạo kết tủa $CaCO_3$ làm mềm nước.

##### 1.3.2.4 Tích số Ion của Nước (Kw)
- Phân tử nước tự phân ly thành ion:
  $$H_2O \rightleftharpoons H^+ + OH^-$$
- Phương trình tích số ion ở $25^\circ\text{C}$:
  $$K_w = [\text{H}^+][\text{OH}^-] = 1{,}00 \times 10^{-14} \quad (\text{p}K_w = 14{,}00)$$
- Tính nồng độ ion hydroxit:
  $$[\text{OH}^-] = \frac{K_w}{[\text{H}^+]} = 10^{-(14 - \text{pH})}$$

##### 1.3.2.5 Giản đồ Bjerrum và Phân bố Cấu tử Carbonate theo pH
- Tổng nồng độ các dạng vô cơ của carbon trong hệ là $C_T$:
  $$C_T = [H_2CO_3^*] + [HCO_3^-] + [CO_3^{2-}]$$
- Phân số nồng độ mol phụ thuộc vào nồng độ ion $[H^+]$:
  $$\alpha_0 = \frac{[H_2CO_3^*]}{C_T} = \frac{[H^+]^2}{[H^+]^2 + K_1[H^+] + K_1 K_2}$$
  $$\alpha_1 = \frac{[HCO_3^-]}{C_T} = \frac{K_1 [H^+]}{[H^+]^2 + K_1[H^+] + K_1 K_2}$$
  $$\alpha_2 = \frac{[CO_3^{2-}]}{C_T} = \frac{K_1 K_2}{[H^+]^2 + K_1[H^+] + K_1 K_2}$$

- **Ba miền phân bố pH trên giản đồ Bjerrum**:
  1. Miền axit ($\text{pH} < 6{,}35$): Dạng $H_2CO_3^*$ (khí $CO_2$ hòa tan) chiếm ưu thế. Nước có tính ăn mòn kim loại và hòa tan bê tông. Biện pháp: Dùng giàn mưa làm thoáng để tước $CO_2$ và nâng pH.
  2. Miền trung tính ($6{,}35 < \text{pH} < 10{,}33$): Dạng bicarbonate ($HCO_3^-$) chiếm ưu thế tuyệt đối (đạt $98\%$ ở $\text{pH} \approx 8{,}34$). Nước có khả năng đệm axit tốt.
  3. Miền kiềm ($\text{pH} > 10{,}33$): Dạng carbonate ($CO_3^{2-}$) và ion $OH^-$ chiếm ưu thế. Canxi kết tủa thành $CaCO_3\downarrow$ và magie kết tủa thành $Mg(OH)_2\downarrow$.

- **Phương trình tính tổng độ kiềm (Total Alkalinity)**:
  - Biểu diễn theo nồng độ mol đương lượng:
    $$\text{Alkalinity} = [\text{HCO}_3^-] + 2[\text{CO}_3^{2-}] + [\text{OH}^-] - [\text{H}^+] \quad (\text{eq/L})$$
  - Biểu diễn theo đơn vị $\text{mg/L as }CaCO_3$:
    $$\text{Alk} = [\text{HCO}_3^-]\left(\frac{50{,}04}{61{,}02}\right) + [\text{CO}_3^{2-}]\left(\frac{50{,}04}{30{,}00}\right) + [\text{OH}^-]\left(\frac{50{,}04}{17{,}01}\right) - [\text{H}^+]\left(\frac{50{,}04}{1{,}01}\right)$$

---

### 1.5 Dây chuyền công nghệ

#### 1.4.1 Quy chuẩn Kỹ thuật Quốc gia về Nước sạch Sinh hoạt (QCVN 01-1:2018/BYT)

##### 1.4.1.1 Phạm vi Áp dụng và Phân nhóm Chỉ tiêu Kiểm tra
- **Phạm vi bắt buộc**: Áp dụng đối với đơn vị cấp nước sạch phục vụ mục đích sinh hoạt có công suất từ $1000\text{ m}^3\text{/ngày}$ trở lên và các trạm cấp nước nông thôn.
- **Phân nhóm thông số thử nghiệm**:
  - Thông số nhóm A: Thử nghiệm định kỳ tối thiểu 1 lần/tháng cho tất cả các nhà máy nước.
  - Thông số nhóm B: Thử nghiệm định kỳ tối thiểu 1 lần/6 tháng theo danh mục do Ủy ban nhân dân cấp tỉnh ban hành.
- **Vị trí lấy mẫu quan sát**: Bể chứa nước sạch tại nhà máy, các nút trọng yếu trên mạng lưới phân phối, vòi nước hộ gia đình cuối mạng lưới.

##### 1.4.1.2 Bảng Giới hạn 11 Chỉ tiêu Chất lượng Nước sạch Thiết yếu
- **Bảng ngưỡng giới hạn theo QCVN 01-1:2018/BYT**:

| TT | Thông số phân tích | Đơn vị | Giới hạn tối đa | Cơ sở kỹ thuật và rủi ro vận hành |
|---|---|---|---|---|
| 1 | **Màu sắc (Color)** | TCU | $\le 15$ | Ngăn ngừa cặn lắng và giữ thẩm mỹ nguồn nước. |
| 2 | **Mùi vị (Taste & Odour)** | - | Không có mùi vị lạ | Ngăn chất gây mùi do tảo ($MIB, Geosmin$) hoặc khí $H_2S$. |
| 3 | **Độ đục (Turbidity)** | NTU | $\le 2$ | Hạt cặn cản trở khử trùng. Độ đục cao bảo vệ vi khuẩn khỏi tác dụng của clo. |
| 4 | **pH** | - | $6{,}0 - 8{,}5$ | $\text{pH} < 6{,}0$ ăn mòn kim loại đường ống. $\text{pH} > 8{,}5$ làm giảm hiệu lực diệt khuẩn của axit hipocloro ($HOCl$). |
| 5 | **Độ cứng tổng số (Total Hardness)** | mg $CaCO_3$/L | $\le 300$ | Tránh đóng cặn đường ống nước nóng và thiết bị đun sôi gia đình. |
| 6 | **Tổng chất rắn hòa tan (TDS)** | mg/L | $\le 1000$ | Kiểm soát vị mặn của nước và khoáng hòa tan. |
| 7 | **Hàm lượng Sắt tổng số (Fe)** | mg/L | $\le 0{,}3$ | Ngăn mùi tanh kim loại, chống ố vàng thiết bị vệ sinh và quần áo. |
| 8 | **Hàm lượng Mangan tổng số (Mn)** | mg/L | $\le 0{,}1$ | Tránh tạo cặn oxit mangan màu đen ($MnO_2$) bám dính thành ống. |
| 9 | **Clo dư tự do (Free Chlorine)** | mg/L | $0{,}2 - 1{,}0$ | Rào cản vi sinh thứ cấp bắt buộc tại mọi vòi dùng nước để chống tái nhiễm khuẩn. |
| 10 | **Tổng số Coliform** | CFU/100 mL | $< 3$ | Đánh giá độ an toàn vi sinh vật tổng thể của hệ thống cấp nước. |
| 11 | **Escherichia coli (E. coli)** | CFU/100 mL | $< 1$ | Chỉ thị tuyệt đối về ô nhiễm phân. Không được phép xuất hiện vi khuẩn trong mẫu thử. |

---

#### 1.4.2 Quy chuẩn Kỹ thuật Nước uống Đóng chai và Nước khoáng Thiên nhiên (QCVN 6-1:2010/BYT)

##### 1.4.2.1 Yêu cầu Khắt khe về An toàn Vi sinh vật
- Thể tích mẫu kiểm tra vi sinh vật là $250\text{ mL}$.
- **Ngưỡng giới hạn bắt buộc đối với vi sinh vật**:
  - *Escherichia coli* hoặc Coliform chịu nhiệt: $0\text{ CFU/250 mL}$.
  - *Streptococci* phân (*Enterococci*): $0\text{ CFU/250 mL}$.
  - *Pseudomonas aeruginosa* (Trực khuẩn mủ xanh gây nhiễm trùng cơ hội): $0\text{ CFU/250 mL}$.
  - Bào tử vi khuẩn kỵ khí khử sunfat (*Clostridium perfringens*): $0\text{ CFU/50 mL}$.

##### 1.4.2.2 Nguyên tắc Đa Rào cản Công nghệ (Multi-Barrier Principle)
- Dây chuyền sản xuất nước đóng chai thiết lập chuỗi rào cản liên hoàn:
  1. Lọc cát thạch anh loại bỏ hạt cặn thô.
  2. Lọc than hoạt tính dạng hạt (GAC) hấp phụ chất hữu cơ, khử màu, mùi và clo dư.
  3. Cột trao đổi ion cationit làm mềm nước triệt để.
  4. Màng lọc thẩm thấu ngược hai cấp (Double-Pass RO) với kích thước lỗ lọc $< 0{,}001\text{ }\mu\text{m}$ để giữ lại khoáng và virus.
  5. Sục khí Ozon ($O_3$) diệt khuẩn bồn chứa và tiệt trùng bao bì đóng nắp.
  6. Chiếu xạ tia cực tím ($\text{UV-C, }\lambda = 254\text{ nm}$) với liều lượng $\ge 40\text{ mJ/cm}^2$ ngay trước bàn chiết rót vô trùng.

---

#### 1.4.3 Tiêu chuẩn Thiết kế Mạng lưới và Công trình Cấp nước (TCXDVN 33:2006)

##### 1.4.3.1 Tiêu chuẩn Định mức Cấp nước Sinh hoạt Đô thị
- **Định mức cấp nước sinh hoạt bình quân**:
  - Đô thị loại đặc biệt và loại I: $200 - 250\text{ L/người}\cdot\text{ngày}$, tỷ lệ cấp nước đạt $95 - 100\%$.
  - Đô thị loại II: $150 - 180\text{ L/người}\cdot\text{ngày}$, tỷ lệ cấp nước đạt $90 - 95\%$.
  - Đô thị loại III, IV, V: $100 - 150\text{ L/người}\cdot\text{ngày}$, tỷ lệ cấp nước đạt $80 - 90\%$.
- **Hệ số không điều hòa lưu lượng**:
  - Hệ số dùng nước ngày không điều hòa: $K_{\text{day-max}} = 1{,}2 - 1{,}5$.
  - Hệ số dùng nước giờ không điều hòa: $K_{\text{hour-max}} = 1{,}3 - 2{,}0$.

##### 1.4.3.2 Áp lực Tự do Tối thiểu trong Mạng lưới Đường ống
- Cột áp tự do tối thiểu tại điểm đấu nối vào nhà 1 tầng:
  $$H_{\text{free}} \ge 10\text{ m cột nước (1{,}0 bar = 100 kPa)}$$
- Mỗi tầng nhà tiếp theo cộng thêm $4\text{ m}$ cột nước:
  $$H_{\text{free}} = 10 + 4(N - 1) \quad (\text{m})$$
  *(với $N$ là số tầng của công trình xây dựng)*

##### 1.4.3.3 Quy định Thiết kế Cấp nước Chữa cháy Đô thị
- Đô thị từ $10000 - 25000$ người: Tính toán 1 đám cháy đồng thời với lưu lượng $15 - 25\text{ L/s}$.
- Đô thị trên $100000$ người: Tính toán đồng thời 2 đến 3 đám cháy với lưu lượng $Q_{\text{fire}} \ge 60 - 100\text{ L/s}$.
- Thời gian duy trì dập tắt một đám cháy tính toán theo quy chuẩn liên tục trong **3 giờ**.
- Công thức tính lưu lượng chữa cháy đô thị của Hiệp hội Bảo hiểm Quốc gia Hoa Kỳ (NBFU):
  $$Q_{\text{fire}} = 1020 \cdot \sqrt{P_k} \cdot \left(1 - 0{,}01 \cdot \sqrt{P_k}\right) \quad (\text{gpm})$$
  *(trong đó $P_k = P / 1000$ là dân số tính theo nghìn người)*

---

#### 1.4.4 Hướng dẫn Chất lượng Nước Bể bơi (HCMC-VHTTDL-2007)

##### 1.4.4.1 Bảng Giới hạn 7 Thông số Vận hành Hồ bơi
- **Bảng thông số kiểm soát chất lượng nước bể bơi**:

| TT | Thông số kiểm soát | Đơn vị tính | Ngưỡng cho phép | Cơ sở kỹ thuật vận hành |
|---|---|---|---|---|
| 1 | **Nhiệt độ nước** | $^\circ\text{C}$ | $22 - 26$ | Đảm bảo thân nhiệt người bơi và giảm tốc độ bay hơi hóa chất clo. |
| 2 | **pH** | - | $7{,}2 - 7{,}6$ | Ngăn cay mắt (pH màng mắt người là 7.4). Dưới 7.2 gây ăn mòn; trên 7.6 làm giảm diệt khuẩn và gây đục nước. |
| 3 | **Độ kiềm tổng số** | mg $CaCO_3$/L | $50 - 100$ | Duy trì dung tích đệm pH, chống hiện tượng nhảy vọt pH khi châm hóa chất. |
| 4 | **Độ cứng** | mg $CaCO_3$/L | $\le 200$ | Ngăn ngừa đóng cặn vảy canxi lên thành hồ và bình lọc cát áp lực. |
| 5 | **Độ tiêu thụ Oxy ($KMnO_4$)** | ppm (mg/L) | $\le 1$ | Kiểm soát chất hữu cơ từ mồ hôi người bơi, hạn chế rêu tảo phát triển. |
| 6 | **Clo dư tự do** | ppm (mg/L) | $0{,}4 - 1{,}0$ | Diệt khuẩn lây nhiễm chéo giữa người bơi. Không để vượt 1.0 ppm để tránh kích ứng da. |
| 7 | **Độ trong suốt** | - | Nhìn rõ đáy hồ | Phải nhìn thấy rõ đĩa đen hoặc nắp hố thu đáy ở điểm sâu nhất (phục vụ cứu nạn). |

##### 1.4.4.2 Phân tích Cơ sở Kỹ thuật Vận hành Hồ bơi
- Hệ thống lọc nước hồ bơi vận hành theo chu trình tuần hoàn kín qua bình lọc cát áp lực.
- Thời gian luân chuyển toàn bộ thể tích nước hồ bơi (Turnover Rate) thiết kế từ 4 đến 6 giờ.
- Hóa chất khử trùng phổ biến là viên clo TCCA ($C_3Cl_3N_3O_3$) hoặc dung dịch Natri hypoclorit ($NaOCl$).
- Nâng pH bằng Natri cacbonat ($Na_2CO_3$); hạ pH bằng axit clohydric loãng ($HCl$) hoặc Natri bisunfat ($NaHSO_4$).

---

#### 1.4.5 Tiêu chuẩn Kỹ thuật Nước Cấp Công nghiệp Chuyên ngành

##### 1.4.5.1 Tiêu chuẩn Nước Cấp Lò hơi và Tháp Giải nhiệt
- **Nước cấp lò hơi (Boiler Feedwater)**:
  - Lò hơi hạ áp ($P < 20\text{ bar}$): Độ cứng $\le 1 - 2\text{ mg/L as }CaCO_3$, oxy hòa tan $DO < 0{,}02\text{ mg/L}$.
  - Lò hơi trung áp và cao áp ($P > 40\text{ bar}$): Độ cứng $\text{TH} = 0\text{ mg/L}$, oxy hòa tan $DO < 0{,}005\text{ mg/L}$, Silic $SiO_2 < 0{,}01\text{ mg/L}$, độ dẫn điện $EC < 0{,}1\text{ }\mu\text{S/cm}$.
- **Nước tháp giải nhiệt (Cooling Water)**:
  - Kiểm soát chỉ số bão hòa Langelier ($0 < LSI < 0{,}5$) để vừa không đóng cặn vừa không ăn mòn thiết bị trao đổi nhiệt.
  - Châm định kỳ hợp chất biocide diệt khuẩn *Legionella pneumophila*.

##### 1.4.5.2 Tiêu chuẩn Nước Dệt nhuộm, Sản xuất Giấy và Nước Siêu Tinh Khiết (UPW)
- **Nước ngành dệt nhuộm và tẩy trắng**:
  - Độ cứng $\le 20\text{ mg/L as }CaCO_3$ để xà phòng không kết tủa dính vào sợi vải.
  - Sắt $Fe \le 0{,}05\text{ mg/L}$, Mangan $Mn \le 0{,}02\text{ mg/L}$, độ màu $\le 5\text{ TCU}$.
- **Nước ngành sản xuất giấy cao cấp**:
  - Sắt $Fe \le 0{,}1\text{ mg/L}$, Mangan $Mn \le 0{,}05\text{ mg/L}$, độ đục $\le 5\text{ NTU}$.
- **Nước siêu tinh khiết ngành điện tử bán dẫn (UPW)**:
  - Điện trở suất: $18{,}2\text{ M}\Omega\cdot\text{cm}$ ở $25^\circ\text{C}$.
  - Tổng carbon hữu cơ: $TOC < 1 - 5\text{ \mu g/L (ppb)}$.
  - Kim loại vết: Mỗi kim loại ($Na, Fe, Cu, Zn$) nồng độ $< 1\text{ ppt (ng/L)}$.
  - Hạt cặn: Số hạt kích thước $> 0{,}05\text{ }\mu\text{m}$ không vượt quá 1 hạt trong mỗi 100 mL nước.

---
- Dây chuyền công nghệ nhà máy xử lý nước mặt truyền thống bao gồm chuỗi liên tục các bể:
  - **Hình 26.** Sơ đồ công nghệ nhà máy xử lý nước mặt hoàn chỉnh
    - <img src="ch01_introduction/assets/fig_26_p27.jpeg" alt="Hình 26" />
    - **Hình này chứng minh điều gì**
      - Chuỗi liên tục gồm trộn nhanh keo tụ, tạo bông, lắng trọng lực, lọc cát và khử trùng clo.
    - **Từ đâu mà thấy được**
      - Chuỗi kết nối tuần tự các bể đơn vị từ trạm bơm cấp 1 đến bể chứa nước sạch.
- Sơ đồ xử lý nâng cao tích hợp các khối ozone hóa và lọc than sinh học (BAC):
  - **Hình 27.** Sơ đồ khối các quy trình xử lý nước tiên tiến
    - <img src="ch01_introduction/assets/fig_27_p27.png" alt="Hình 27" />
    - **Hình này chứng minh điều gì**
      - Kết hợp tiền ozone hóa, than hoạt tính sinh học (BAC) và màng vi lọc UF bảo vệ nguồn nước.
    - **Từ đâu mà thấy được**
      - Các khối xử lý nâng cao bố trí xen giữa bể lắng và khử trùng clo thứ cấp.

### 1.6 Các bài toán tính toán cơ bản

<!-- exercise-start: Ví dụ 1-9: Nhu cầu nước đỉnh và lưu lượng chữa cháy khu dân cư -->
- **Ví dụ 1-9: Nhu cầu nước đỉnh và lưu lượng chữa cháy khu dân cư**
  - Cho:
    - Diện tích khu dân cư cao cấp: $A = 100{,}0\text{ ha}$
    - Mật độ nhà ở quy hoạch: $30{,}0\text{ căn nhà/ha}$
    - Số nhân khẩu bình quân: $4{,}0\text{ người/hộ}$
    - Tiêu chuẩn dùng nước sinh hoạt: $q = 300{,}0\text{ L/(người}\cdot\text{ngày)}$
    - Hệ số dùng nước ngày lớn nhất: $K_{\text{day-max}} = 1{,}5$
  - Tìm:
    - Tổng dân số tính toán ($P$, người).
    - Nhu cầu dùng nước sinh hoạt trung bình ngày ($Q_{\text{avg}}$) và ngày lớn nhất ($Q_{\text{max-day}}$).
    - Lưu lượng nước chữa cháy quy chuẩn ($Q_{\text{fire}}$) theo công thức NBFU.
    - Tổng lưu lượng cấp nước đỉnh đồng thời ($Q_{\text{total}}$).
  - Phương trình áp dụng:
    $$P = A \cdot \text{Mật độ} \cdot \text{Nhân khẩu}$$
    $$Q_{\text{avg}} = P \cdot q$$
    $$Q_{\text{max-day}} = K_{\text{day-max}} \cdot Q_{\text{avg}}$$
    $$Q_{\text{fire}} = 1020 \cdot \sqrt{P_k} \cdot \left(1 - 0{,}01 \cdot \sqrt{P_k}\right) \quad (\text{gpm})$$
    $$Q_{\text{total}} = Q_{\text{max-day}} + Q_{\text{fire}}$$
  - Các bước giải:
    1. Bước 1: Tính quy mô dân số phục vụ:
       $$P = 100\text{ ha} \times 30\text{ căn/ha} \times 4\text{ người/căn} = 12000\text{ người} \quad (P_k = 12\text{ nghìn người})$$
    2. Bước 2: Tính nhu cầu nước sinh hoạt:
       $$Q_{\text{avg}} = 12000\text{ người} \times 300\text{ L/(người}\cdot\text{ngày)} = 3600000\text{ L/ngày} = 3600\text{ m}^3\text{/ngày} = 41{,}67\text{ L/s}$$
       $$Q_{\text{max-day}} = 1{,}5 \times 3600\text{ m}^3\text{/ngày} = 5400\text{ m}^3\text{/ngày} = 62{,}50\text{ L/s}$$
    3. Bước 3: Tính lưu lượng chữa cháy theo công thức NBFU:
       $$Q_{\text{fire}} = 1020 \cdot \sqrt{12} \cdot \left(1 - 0{,}01 \cdot \sqrt{12}\right) = 1020 \times 3{,}4641 \times (1 - 0{,}03464) = 3411\text{ gpm}$$
       Quy đổi sang đơn vị SI:
       $$Q_{\text{fire}} = 3411\text{ gpm} \times 0{,}06309\text{ (L/s)/gpm} = 215{,}2\text{ L/s} = 18593\text{ m}^3\text{/ngày}$$
    4. Bước 4: Tính tổng nhu cầu cấp nước đồng thời giờ cao điểm:
       $$Q_{\text{total}} = 62{,}50\text{ L/s} + 215{,}20\text{ L/s} = 277{,}70\text{ L/s} = 23993\text{ m}^3\text{/ngày}$$
  - **Đáp số**: `Dân số = 12,000 người; Q_max-day = 5,400 m^3/ngày (62.5 L/s); Q_fire = 215.2 L/s (3,411 gpm); Q_total = 277.7 L/s (23,993 m^3/ngày).`
<!-- exercise-end -->

---

<!-- exercise-start: Ví dụ 1-10: Nhu cầu nước đỉnh và lưu lượng chữa cháy tòa nhà 45 tầng -->
- **Ví dụ 1-10: Nhu cầu nước đỉnh và lưu lượng chữa cháy tòa nhà 45 tầng**
  - Cho:
    - Số tầng công trình: $45\text{ tầng}$
    - Mật độ căn hộ: $6{,}0\text{ căn hộ/tầng}$
    - Số nhân khẩu bình quân: $4{,}0\text{ người/hộ}$
    - Tiêu chuẩn dùng nước sinh hoạt: $q = 200{,}0\text{ L/(người}\cdot\text{ngày)}$
    - Hệ số dùng nước ngày lớn nhất: $K_{\text{day-max}} = 1{,}5$
    - Lưu lượng chữa cháy tiêu chuẩn nhà cao tầng: $Q_{\text{fire}} = 1000\text{ gpm}$ ($63{,}1\text{ L/s}$)
  - Tìm:
    - Tổng dân số tòa nhà ($P$, người) và tổng số căn hộ.
    - Nhu cầu nước sinh hoạt ngày lớn nhất ($Q_{\text{max-day}}$).
    - Lưu lượng nước chữa cháy ($Q_{\text{fire}}$ theo $\text{L/s}$ và $\text{m}^3\text{/h}$).
    - Tổng nhu cầu cấp nước đồng thời giờ cao điểm ($Q_{\text{total}}$).
  - Phương trình áp dụng:
    $$P = \text{Số tầng} \cdot \text{Căn hộ/tầng} \cdot \text{Người/hộ}$$
    $$Q_{\text{avg}} = P \cdot q$$
    $$Q_{\text{max-day}} = K_{\text{day-max}} \cdot Q_{\text{avg}}$$
    $$Q_{\text{total}} = Q_{\text{max-day}} + Q_{\text{fire}}$$
  - Các bước giải:
    1. Bước 1: Tính số căn hộ và dân số tòa nhà:
       $$\text{Số căn hộ} = 45\text{ tầng} \times 6\text{ căn/tầng} = 270\text{ căn hộ}$$
       $$P = 270 \times 4\text{ người} = 1080\text{ người}$$
    2. Bước 2: Tính nhu cầu nước sinh hoạt:
       $$Q_{\text{avg}} = 1080\text{ người} \times 200\text{ L/(người}\cdot\text{ngày)} = 216000\text{ L/ngày} = 216\text{ m}^3\text{/ngày} = 2{,}50\text{ L/s}$$
       $$Q_{\text{max-day}} = 1{,}5 \times 216\text{ m}^3\text{/ngày} = 324\text{ m}^3\text{/ngày} = 3{,}75\text{ L/s}$$
    3. Bước 3: Xác định lưu lượng chữa cháy quy định:
       $$Q_{\text{fire}} = 1000\text{ gpm} = 63{,}1\text{ L/s} = 227{,}1\text{ m}^3\text{/h}$$
    4. Bước 4: Tính tổng nhu cầu cấp nước đỉnh:
       $$Q_{\text{total}} = 3{,}75\text{ L/s} + 63{,}10\text{ L/s} = 66{,}85\text{ L/s} = 240{,}7\text{ m}^3\text{/h} \quad (5774\text{ m}^3\text{/ngày})$$
  - **Đáp số**: `Dân số = 1,080 người (270 căn); Q_max-day = 3.75 L/s (324 m^3/ngày); Q_fire = 63.1 L/s (1000 gpm); Q_total = 66.85 L/s (240.7 m^3/h).`
<!-- exercise-end -->

---

<!-- exercise-start: Ví dụ 1-11: Tính độ cứng tổng cộng từ nồng độ Ca2+ và Mg2+ -->
- **Ví dụ 1-11: Tính độ cứng tổng cộng từ nồng độ Ca2+ và Mg2+**
  - Cho:
    - Nồng độ ion canxi: $[\text{Ca}^{2+}] = 95{,}20\text{ mg/L}$
    - Nồng độ ion magie: $[\text{Mg}^{2+}] = 13{,}44\text{ mg/L}$
    - Đương lượng gam của $\text{Ca}^{2+}$: $20{,}04\text{ g/đl}$ (khối lượng mol $40{,}08\text{ g/mol}$)
    - Đương lượng gam của $\text{Mg}^{2+}$: $12{,}15\text{ g/đl}$ (khối lượng mol $24{,}31\text{ g/mol}$)
    - Đương lượng gam của $\text{CaCO}_3$: $50{,}04\text{ g/đl}$
  - Tìm:
    - Độ cứng canxi ($\text{CH}$) theo $\text{mg/L as }CaCO_3$.
    - Độ cứng magie ($\text{MH}$) theo $\text{mg/L as }CaCO_3$.
    - Độ cứng tổng cộng ($\text{TH}$) theo $\text{mg/L as }CaCO_3$.
  - Phương trình áp dụng:
    $$\text{CH} = [\text{Ca}^{2+}] \cdot \frac{50{,}04}{20{,}04} \approx 2{,}50 \cdot [\text{Ca}^{2+}]$$
    $$\text{MH} = [\text{Mg}^{2+}] \cdot \frac{50{,}04}{12{,}15} \approx 4{,}12 \cdot [\text{Mg}^{2+}]$$
    $$\text{TH} = \text{CH} + \text{MH} = 2{,}497 \cdot [\text{Ca}^{2+}] + 4{,}118 \cdot [\text{Mg}^{2+}]$$
  - Các bước giải:
    1. Bước 1: Tính độ cứng canxi ($\text{CH}$):
       $$\text{CH} = 95{,}20\text{ mg/L} \times \frac{50{,}04}{20{,}04} = 95{,}20 \times 2{,}497 = 237{,}71\text{ mg/L as }CaCO_3 \approx 238{,}0\text{ mg/L as }CaCO_3$$
    2. Bước 2: Tính độ cứng magie ($\text{MH}$):
       $$\text{MH} = 13{,}44\text{ mg/L} \times \frac{50{,}04}{12{,}15} = 13{,}44 \times 4{,}118 = 55{,}35\text{ mg/L as }CaCO_3 \approx 55{,}4\text{ mg/L as }CaCO_3$$
    3. Bước 3: Tính độ cứng tổng cộng ($\text{TH}$):
       $$\text{TH} = 238{,}0 + 55{,}4 = 293{,}4\text{ mg/L as }CaCO_3$$
  - **Đáp số**: `Độ cứng canxi = 238.0 mg/L as CaCO3; Độ cứng magie = 55.4 mg/L as CaCO3; Độ cứng tổng cộng = 293.4 mg/L as CaCO3.`
<!-- exercise-end -->

---

<!-- exercise-start: Ví dụ 1-12: Tính độ kiềm tổng cộng ở pH 10 -->
- **Ví dụ 1-12: Tính độ kiềm tổng cộng ở pH 10**
  - Cho:
    - Nồng độ ion carbonate: $[\text{CO}_3^{2-}] = 100{,}0\text{ mg/L}$
    - Độ pH mẫu nước: $\text{pH} = 10{,}0$
    - Nhiệt độ nước: $25{,}0^\circ\text{C}$
    - Hằng số phân ly bậc 2 ở $25^\circ\text{C}$: $K_2 = 4{,}69 \times 10^{-11}$
    - Tích số ion của nước ở $25^\circ\text{C}$: $K_w = 1{,}0 \times 10^{-14}$
    - Khối lượng mol $\text{CO}_3^{2-}$: $60{,}01\text{ g/mol}$
    - Đương lượng gam $\text{CaCO}_3$: $50{,}04\text{ g/đl}$
  - Tìm:
    - Nồng độ các cấu tử kiềm $[\text{HCO}_3^-]$, $[\text{CO}_3^{2-}]$, $[\text{OH}^-]$.
    - Độ kiềm tổng cộng ($\text{Total Alkalinity}$) theo $\text{mg/L as }CaCO_3$.
  - Phương trình áp dụng:
    $$[\text{H}^+] = 10^{-\text{pH}}$$
    $$[\text{OH}^-] = \frac{K_w}{[\text{H}^+]}$$
    $$[\text{HCO}_3^-] = \frac{[\text{H}^+][\text{CO}_3^{2-}]}{K_2}$$
    $$\text{Total Alkalinity} = [\text{HCO}_3^-] + 2[\text{CO}_3^{2-}] + [\text{OH}^-] - [\text{H}^+] \quad (\text{eq/L})$$
  - Các bước giải:
    1. Bước 1: Tính nồng độ ion $[\text{H}^+]$ và $[\text{OH}^-]$ ở $\text{pH} = 10{,}0$:
       $$[\text{H}^+] = 10^{-10}\text{ M}$$
       $$[\text{OH}^-] = \frac{1{,}0 \times 10^{-14}}{1{,}0 \times 10^{-10}} = 1{,}0 \times 10^{-4}\text{ M} = 1{,}0 \times 10^{-4}\text{ đl/L}$$
       Quy đổi sang $\text{mg/L as }CaCO_3$:
       $$[\text{OH}^-]_{\text{CaCO}_3} = 1{,}0 \times 10^{-4}\text{ đl/L} \times 50000\text{ mg/đl} = 5{,}00\text{ mg/L as }CaCO_3$$
    2. Bước 2: Đổi nồng độ $\text{CO}_3^{2-}$ sang nồng độ mol và đương lượng $\text{CaCO}_3$:
       $$[\text{CO}_3^{2-}] = \frac{100{,}0\text{ mg/L}}{60010\text{ mg/mol}} = 1{,}6664 \times 10^{-3}\text{ M}$$
       $$[\text{CO}_3^{2-}]_{\text{CaCO}_3} = 100{,}0\text{ mg/L} \times \frac{50{,}04}{30{,}00} = 166{,}8\text{ mg/L as }CaCO_3$$
    3. Bước 3: Tính nồng độ ion bicarbonate $[\text{HCO}_3^-]$ từ cân bằng $K_2$:
       $$[\text{HCO}_3^-] = \frac{1{,}0 \times 10^{-10}\text{ M} \times 1{,}6664 \times 10^{-3}\text{ M}}{4{,}69 \times 10^{-11}} = 3{,}553 \times 10^{-3}\text{ M}$$
       Quy đổi sang $\text{mg/L as }CaCO_3$:
       $$[\text{HCO}_3^-]_{\text{CaCO}_3} = 3{,}553 \times 10^{-3}\text{ đl/L} \times 50000\text{ mg/đl} = 177{,}7\text{ mg/L as }CaCO_3$$
    4. Bước 4: Tính tổng độ kiềm:
       $$\text{Total Alkalinity} = 177{,}65 + 166{,}77 + 5{,}00 = 349{,}42\text{ mg/L as }CaCO_3 \approx 349{,}5\text{ mg/L as }CaCO_3$$
  - **Đáp số**: `[HCO3-] = 177.7 mg/L as CaCO3; [CO3(2-)] = 166.8 mg/L as CaCO3; [OH-] = 5.0 mg/L as CaCO3; Độ kiềm tổng cộng = 349.5 mg/L as CaCO3.`
<!-- exercise-end -->

---

<!-- exercise-start: Ví dụ 1-13: Cân bằng các cấu tử carbonate ở pH 7.65 -->
- **Ví dụ 1-13: Cân bằng các cấu tử carbonate ở pH 7.65**
  - Cho:
    - Độ pH mẫu nước: $\text{pH} = 7{,}65$
    - Độ kiềm tổng cộng đo được: $\text{Alk} = 310{,}0\text{ mg/L as }CaCO_3$
    - Hằng số phân ly axit carbonic ở $25^\circ\text{C}$: $K_1 = 4{,}45 \times 10^{-7}$; $K_2 = 4{,}69 \times 10^{-11}$
    - Khối lượng mol các chất: $\text{CO}_2 = 44{,}01\text{ g/mol}$; $\text{HCO}_3^- = 61{,}02\text{ g/mol}$; $\text{CO}_3^{2-} = 60{,}01\text{ g/mol}$
    - Đương lượng gam $\text{CaCO}_3$: $50{,}04\text{ g/đl}$
  - Tìm:
    - Nồng độ cân bằng của khí carbonic hòa tan tự do ($[\text{CO}_2]$).
    - Nồng độ ion bicarbonate ($[\text{HCO}_3^-]$).
    - Nồng độ ion carbonate ($[\text{CO}_3^{2-}]$).
  - Phương trình áp dụng:
    $$\frac{[\text{CO}_3^{2-}]}{[\text{HCO}_3^-]} = \frac{K_2}{[\text{H}^+]}$$
    $$[\text{CO}_2] = \frac{[\text{H}^+][\text{HCO}_3^-]}{K_1}$$
    $$\text{Alkalinity} = [\text{HCO}_3^-] + 2[\text{CO}_3^{2-}] + [\text{OH}^-] - [\text{H}^+]$$
  - Các bước giải:
    1. Bước 1: Tính nồng độ $[\text{H}^+]$ và nồng độ đương lượng kiềm:
       $$[\text{H}^+] = 10^{-7{,}65} = 2{,}239 \times 10^{-8}\text{ M}$$
       $$\text{Alkalinity} = \frac{310{,}0\text{ mg/L}}{50040\text{ mg/đl}} = 6{,}195 \times 10^{-3}\text{ đl/L}$$
    2. Bước 2: Xác định nồng độ bicarbonate $[\text{HCO}_3^-]$:
       $$\frac{[\text{CO}_3^{2-}]}{[\text{HCO}_3^-]} = \frac{4{,}69 \times 10^{-11}}{2{,}239 \times 10^{-8}} = 0{,}002095$$
       Biểu thức độ kiềm (bỏ qua $[\text{OH}^-]$ và $[\text{H}^+]$ ở pH trung tính):
       $$\text{Alk} = [\text{HCO}_3^-] \times (1 + 2 \times 0{,}002095) = 1{,}00419 \cdot [\text{HCO}_3^-] = 6{,}195 \times 10^{-3}\text{ đl/L}$$
       $$[\text{HCO}_3^-] = \frac{6{,}195 \times 10^{-3}}{1{,}00419} = 6{,}169 \times 10^{-3}\text{ M}$$
       Quy đổi đơn vị:
       $$[\text{HCO}_3^-]_{\text{CaCO}_3} = 6{,}169 \times 10^{-3}\text{ đl/L} \times 50000\text{ mg/đl} = 308{,}5\text{ mg/L as }CaCO_3$$
       $$[\text{HCO}_3^-] = 6{,}169 \times 10^{-3}\text{ mol/L} \times 61020\text{ mg/mol} = 376{,}4\text{ mg/L as }HCO_3^-$$
    3. Bước 3: Xác định nồng độ carbonate $[\text{CO}_3^{2-}]$:
       $$[\text{CO}_3^{2-}] = 0{,}002095 \times 6{,}169 \times 10^{-3}\text{ M} = 1{,}292 \times 10^{-5}\text{ M}$$
       Quy đổi đơn vị:
       $$[\text{CO}_3^{2-}]_{\text{CaCO}_3} = 2 \times 1{,}292 \times 10^{-5}\text{ đl/L} \times 50000\text{ mg/đl} = 1{,}29\text{ mg/L as }CaCO_3$$
       $$[\text{CO}_3^{2-}] = 1{,}292 \times 10^{-5}\text{ mol/L} \times 60010\text{ mg/mol} = 0{,}78\text{ mg/L as }CO_3^{2-}$$
    4. Bước 4: Xác định nồng độ khí carbonic hòa tan $[\text{CO}_2]$:
       $$[\text{CO}_2] = \frac{2{,}239 \times 10^{-8}\text{ M} \times 6{,}169 \times 10^{-3}\text{ M}}{4{,}45 \times 10^{-7}} = 3{,}104 \times 10^{-4}\text{ M}$$
       Quy đổi sang $\text{mg/L}$:
       $$[\text{CO}_2] = 3{,}104 \times 10^{-4}\text{ mol/L} \times 44010\text{ mg/mol} = 13{,}66\text{ mg/L as }CO_2$$
  - **Đáp số**: `[CO2] = 13.66 mg/L as CO2 (0.310 mmol/L); [HCO3-] = 308.5 mg/L as CaCO3 (376.4 mg/L as HCO3-); [CO3(2-)] = 1.29 mg/L as CaCO3 (0.78 mg/L as CO3(2-)).`
<!-- exercise-end -->

## Chương 2: Nguồn Nước & Công trình Thu Nước (Water Source & Collection System)


### 2.1 Khái niệm và Phân loại công trình thu nước

#### Định nghĩa (Definition)

* Định nghĩa hệ thống thu nước thô (Raw water collection system):
  * Hệ thống thu nước thô là công trình xây dựng chuyên dụng nhằm mục đích rút và khai thác nước từ hồ (lake), sông (river) hoặc nước dưới đất (groundwater).
  * Công trình là điểm đầu tiếp nhận nước tự nhiên để cấp vào trạm xử lý hoặc mạng lưới cấp nước.

#### Phân loại (Classification)

* Phân loại công trình thu nước theo nguồn nước khai thác:
  * Công trình thu nước mặt (Intake): Dùng để khai thác nguồn nước mặt (surface water) như sông, hồ chứa hoặc kênh.
  * Giếng khai thác nước ngầm (Well): Dùng để khai thác nguồn nước ngầm (groundwater) từ các tầng chứa nước ngầm.

### 2.2 Công trình thu nước mặt (Surface Water Intake)

- Định nghĩa công trình thu nước mặt: Tổ hợp công trình và thiết bị cơ điện dùng để thu nhận nước thô từ nguồn nước mặt tự nhiên (sông, suối, hồ chứa, hồ tự nhiên) với lưu lượng thiết kế $Q_{\text{design}}$, vận chuyển an toàn về trạm xử lý nước cấp.
  - Chức năng kỹ thuật chính: Lấy đủ lưu lượng $Q$, ổn định mực nước cho trạm bơm cấp 1, loại bỏ rác trôi nổi thô, ngăn chặn bùn cát lắng đọng đáy và bảo vệ ấu trùng, sinh vật thủy sinh.
  - Phân loại công trình thu nước mặt theo sơ đồ vị trí và thủy văn:
    - Công trình thu nước hồ chứa (Lake Intake).
    - Công trình thu nước sông (River Intake).
    - Công trình thu nước ven bờ (Shore Intake).
    - Công trình thu nước xa bờ (Offshore Intake / Submerged Intake Crib).

- Yêu cầu thủy lực khống chế vận tốc dòng vào cửa thu:
  - Vận tốc dòng chảy vào cửa thu thô ($v_{\text{intake}}$) khống chế ở mức $v_{\text{intake}} \le 0.15 - 0.20\text{ m/s}$ khi dòng chảy một chiều ổn định.
  - Giới hạn vận tốc qua khe lưới thu nước mặt bảo vệ sinh học theo tiêu chuẩn EPA 316b:
    $$v_{\text{screen}} = \frac{Q}{A_{\text{net}}} = \frac{Q}{A_{\text{gross}} \cdot (1 - \text{fraction}_{\text{solid}})} \le 0.15\text{ m/s}$$
    - Trong đó $A_{\text{gross}}$ là tổng diện tích bề mặt khung lưới ($\text{m}^2$).
    - $\text{fraction}_{\text{solid}}$ là tỷ lệ diện tích thanh kim loại chiếm chỗ của khung lưới (thường chiếm $0.20 - 0.40$).
    - $A_{\text{net}}$ là diện tích thông thủy thực tế của khe hở cho nước đi qua ($\text{m}^2$).
    - Giá trị $v_{\text{screen}} \le 0.15\text{ m/s}$ ($0.5\text{ ft/s}$) ngăn ngừa hiện tượng ép chết cá con và sinh vật vào bề mặt lưới (fish impingement).

- Tiêu chuẩn bố trí cao trình và khoảng cách an toàn vệ sinh nguồn nước:
  - Cao trình mép trên cửa thu nước: Nằm ngập tối thiểu $0.5 - 1.0\text{ m}$ dưới mực nước thấp nhất thiết kế ($H_{\text{min}}$) nhằm ngăn hút rác nổi, váng dầu mỡ và xoáy khí mặt nước.
  - Cao trình mép dưới cửa thu nước: Nằm cao hơn đáy sông, hồ tối thiểu $0.5 - 1.0\text{ m}$ để tránh cuốn bùn cát di động tầng đáy vào ống hút.
  - Cao trình sàn đặt máy bơm và phòng điều khiển điện: Nằm cao hơn mực nước lũ tính toán ($H_{\text{max}}$ ứng với tần suất thiết kế $P = 1\% - 2\%$) cộng thêm chiều cao an toàn sóng vỗ $\Delta h \ge 0.5\text{ m}$.
  - Vùng bảo hộ vệ sinh công trình thu nước mặt: Bán kính nghiêm ngặt tối thiểu $200 - 500\text{ m}$ về phía thượng lưu và $100 - 200\text{ m}$ về phía hạ lưu, nghiêm cấm mọi hoạt động xả thải, tắm giặt, chăn nuôi và neo đậu tàu thuyền.

#### 2.2.1 Công trình thu nước hồ chứa (Lake Intake)

- Đặc tính thủy văn và hiện tượng phân tầng chất lượng nước hồ chứa:
  - Hiện tượng phân tầng nhiệt mùa hè (Thermal Stratification): Hồ chứa nước sâu hình thành 3 tầng nước rõ rệt gồm tầng mặt ấm giàu oxy hòa tan ($Epilimnion$), tầng dị thường nhiệt ($Thermocline$ / $Metalimnion$), và tầng đáy lạnh thiếu khí ($Hypolimnion$).
  - Phân bố sinh học và hóa lý theo độ sâu:
    - Tầng mặt ($Epilimnion$): Xảy ra hiện tượng quang hợp, nguy cơ tảo nở hoa ($Algal\text{ bloom}$), hàm lượng chất hữu cơ cao và biến thiên nhiệt độ lớn.
    - Tầng đáy ($Hypolimnion$): Yếm khí khử oxy ($\text{DO} \to 0$), giải phóng ion kim loại hòa tan từ trầm tích ($\text{Fe}^{2+}$, $\text{Mn}^{2+}$), khí độc $\text{H}_2\text{S}$, amoni ($\text{NH}_4^+$), gây mùi hôi và tăng chi phí hóa chất xử lý.
    - Tầng trung gian ($Thermocline$): Vùng nước có nhiệt độ ổn định, độ đục thấp, không có tảo bề mặt và nồng độ chất khử đáy thấp nhất, thích hợp nhất để khai thác cấp nước sinh hoạt.

- Cấu tạo và nguyên lý vận hành tháp thu nước hồ chứa (Lake Intake Tower):
  - Tháp bê tông cốt thép hình trụ tròn hoặc hình oval đặt độc lập trong lòng hồ, liên kết với bờ bằng cầu dẫn giao thông kiêm giá đỡ tuyến ống áp lực.
  - Cửa thu nước nhiều tầng (Multi-tier Sluice Gates / Ports): Bố trí so le ở nhiều cao trình khác nhau theo phương đứng (tầng cao, tầng trung và tầng thấp) cho phép đơn vị vận hành linh hoạt lựa chọn lấy nước từ tầng có chất lượng tối ưu theo từng mùa trong năm.
  - Kích thước công trình điển hình của tháp thu nước hồ chứa:
    - Đường kính tháp ngoài: $D = 18\text{ m}$ tạo không gian rộng rãi cho buồng hút và hệ thống van ống.
    - Chiều cao tháp tổng thể: $H = 21.3\text{ m}$ từ bản đáy móng đến sàn vận hành chính.
    - Dải biến động mực nước vận hành bình thường ($Normal\text{ operation}$): Chiều cao cột nước dao động $10.6\text{ m}$ giữa mực nước dâng bình thường ($Max\text{ w.s.}$) và mực nước thấp bình thường ($Normal\text{ operation Low range}$).
    - Dải biến động mực nước khẩn cấp ($Emergency\text{ operation}$): Chiều cao cột nước dao động $7.6\text{ m}$ từ mức nước thấp bình thường xuống mực nước chết tối thiểu ($Min\text{ water surface}$).

- Bố trí thiết bị cơ điện và tổ hợp máy bơm trong tháp thu:
  - Bơm hỗn lưu trục đứng vận hành bình thường (Vertical Mixed Flow Pumps for Normal Service): Số lượng 4 tổ máy, lưu lượng lớn, cột áp trung bình, làm việc khi mực nước hồ trong dải $10.6\text{ m}$ bình thường.
  - Bơm tuabin trục đứng vận hành sự cố (Vertical Turbine Pumps for Emergency Service): Số lượng 2 tổ máy, thân bơm kéo dài xuống hố sâu đáy tháp để hút nước khi hồ cạn kiệt đến $Min\text{ water surface}$.
  - Bơm tháo cạn buồng thu ($Sump\text{ Pump}$): Bố trí tại rãnh thu đáy để thoát nước rò rỉ và tháo cạn khô phục vụ công tác kiểm tra, nạo vét phù sa định kỳ.
  - Thiết bị van điều tiết và an toàn:
    - Van bướm tự động (Automatic Butterfly Valve) lắp trên tuyến ống xả của mỗi máy bơm.
    - Van bướm quang học/cơ học (Optical/Manual Butterfly Valve) điều tiết tuyến ống gom áp lực ($Pump\text{ discharge header}$).
    - Van xả khí tự động (Air Valve) đặt tại các điểm cao cục bộ để triệt tiêu túi khí và chống hiện tượng chân không bóp méo đường ống.
    - Cầu trục xoay tròn (Circular Bridge Crane) trên đỉnh vòm tháp phục vụ nâng hạ động cơ và tổ máy bơm khi trung tu, đại tu.

  - **Hình 1:** Mặt cắt đứng và mặt bằng tháp thu nước hồ chứa
    - <img src="ch02_water_source_collection/assets/fig_01_p2.png" alt="Hình 1" />
    - **Hình này chứng minh điều gì**
      - Tháp thu hồ bố trí cửa thu nhiều tầng và cụm bơm tích hợp.
    - **Từ đâu mà thấy được**
      - Mặt cắt cao $21.3\text{ m}$ với cửa Inlet và bơm hỗn lưu trục đứng.

  - **Hình 2:** Sơ đồ buồng thu nước sông có song chắn và lưới chắn
    - <img src="ch02_water_source_collection/assets/fig_02_p2.png" alt="Hình 2" />
    - **Hình này chứng minh điều gì**
      - Nước vào giếng bơm qua hai cấp chắn rác thô và tinh.
    - **Từ đâu mà thấy được**
      - Mặt cắt thể hiện song chắn rác ngoài sông và lưới tự rửa.

#### 2.2.2 Công trình thu nước sông (River Intake)

- Nguyên tắc lựa chọn vị trí đặt công trình thu nước sông:
  - Tuyến thu nước phải bố trí tại đoạn sông có bờ lõm ổn định tự nhiên hoặc bờ đã được kè đá kiên cố.
  - Vị trí bờ lõm đảm bảo độ sâu luồng lách lớn, vận tốc dòng chảy ổn định, không bị bồi lắng cát hạt mịn và không nằm trong vùng xoáy nước quẩn.
  - Tuyệt đối tránh đặt công trình thu tại vùng bờ lồi bồi tích phù sa hoặc vùng bãi cát di động gây tắc nghẽn cửa thu nước trong mùa kiệt.

- Quy trình xử lý rác cơ học hai cấp độ tại công trình thu nước sông:
  - Cấp 1 - Song chắn rác thô ngoài sông (Trash Rack / Bar Rack):
    - Đặt trực tiếp tại cửa vào tiếp xúc với dòng sông để giữ lại các vật trôi nổi kích thước lớn (gỗ mục, cành cây, rác nhựa, xác động vật).
    - Cấu tạo từ các thanh thép dẹt hoặc thép tròn đặt song song, khoảng cách mép trong thông thủy $b = 40 - 50\text{ mm}$ (vệ sinh cơ giới) hoặc $b = 20 - 30\text{ mm}$ (vệ sinh thủ công).
    - Góc nghiêng thanh chắn so với mặt phẳng nằm ngang: $\alpha = 70^\circ - 80^\circ$ giúp dễ dàng cào rác thủ công hoặc lắp đặt máy cào rác tự động.
    - Vận tốc dòng nước tới trước song chắn: $v_0 = 0.4 - 0.8\text{ m/s}$, giới hạn tối đa $v_0 \le 1.0\text{ m/s}$ khi song chắn bị rác che lấp $50\%$.
    - Công thức Kirschmer xác định tổn thất cột áp qua song chắn rác:
      $$h_L = \beta \cdot \left(\frac{s}{b}\right)^{4/3} \cdot \frac{v_0^2}{2g} \cdot \sin(\alpha)$$
      - $\beta$: Hệ số phụ thuộc hình dạng tiết diện ngang của thanh thép (thanh chữ nhật sắc cạnh $\beta = 2.42$; thanh chữ nhật vê tròn góc $\beta = 1.83$; thanh tròn $\beta = 1.79$; thanh dạng giọt nước khí động học $\beta = 0.76$).
      - $s$: Bề dày của thanh thép chắn rác ($\text{m}$).
      - $b$: Bề rộng khoảng hở thông thủy giữa hai thanh thép kề nhau ($\text{m}$).
      - $v_0$: Vận tốc dòng nước chảy tới trước song chắn ($\text{m/s}$).
      - $g$: Gia tốc trọng trường ($g = 9.81\text{ m/s}^2$).
      - $\alpha$: Góc nghiêng của khung song chắn rác so với mặt phẳng ngang.
  - Cấp 2 - Lưới chắn rác tinh tự rửa dạng băng chuyền (Traveling Water Screen):
    - Bố trí thẳng đứng bên trong giếng thu, nằm sau song chắn thô và cửa van phai khống chế ($Sluice\text{ Gates}$).
    - Cấu tạo từ các tấm lưới đan sợi kim loại không gỉ hoặc polyme có kích thước mắt lưới nhỏ $2 - 10\text{ mm}$.
    - Khung lưới chuyển động theo vòng tròn khép kín thẳng đứng với vận tốc chuyển động chậm $1.5 - 3.0\text{ m/min}$.
    - Cơ cấu rửa tự động: Các khay gạt rác nâng cặn, rong rêu và lá cây lên đỉnh buồng thu; dàn kim phun nước áp lực cao ($p = 0.4 - 0.6\text{ MPa}$) phun ngược chiều từ phía sau để tống rác vào máng thu xả ra ngoài.
    - Vận tốc dòng nước qua diện tích thực của lưới tuân thủ giới hạn Rule R07: $v_{\text{screen}} \le 0.15\text{ m/s}$.

- Kết cấu trạm bơm nước sông và phân chia ngăn thủy lực:
  - Công trình gồm 2 ngăn thủy lực ngăn cách bởi vách bê tông và cửa van:
    - Ngăn tiếp nhận nước ($Intake\text{ Chamber}$): Chứa song chắn rác thô và lưới chắn rác chuyển động.
    - Ngăn hút máy bơm ($Suction\text{ Chamber}$ / $Wet\text{ Well}$): Nơi đặt các ống hút của tổ máy bơm trục đứng ($Pump\text{ Column}$).
  - Cửa van phai phẳng ($Sluice\text{ Gates}$): Cho phép đóng kín cách ly từng ngăn riêng biệt để tháo cạn nước, nạo vét bùn lắng và sửa chữa thiết bị cơ khí mà không làm gián đoạn cấp nước của toàn trạm.
  - Cầu trục dầm đơn ($Traveling\text{ Crane}$): Di chuyển dọc trần nhà trạm phục vụ công tác bốc dỡ, bảo trì động cơ bơm ($Pump\text{ Motor}$) và lưới chắn rác.

  - **Hình 3:** Sơ đồ bố trí cửa thu nước nhiều tầng trong tháp
    - <img src="ch02_water_source_collection/assets/fig_03_p3.png" alt="Hình 3" />
    - **Hình này chứng minh điều gì**
      - Công trình kiểm soát lấy nước theo các tầng thủy lực khác nhau.
    - **Từ đâu mà thấy được**
      - Các cao trình Max w.s., Normal operation và Min water surface trên tháp.

  - **Hình 4:** Cấu tạo buồng bơm thu nước mặt và cơ cấu tự rửa
    - <img src="ch02_water_source_collection/assets/fig_04_p3.png" alt="Hình 4" />
    - **Hình này chứng minh điều gì**
      - Bơm trục đứng lấy nước đã qua sàng lọc cơ học hoàn chỉnh.
    - **Từ đâu mà thấy được**
      - Vị trí ống bơm Pump column đặt sau lưới chắn Traveling screen.

#### 2.2.3 Công trình thu nước ven bờ (Shore Intake)

- Khái niệm và điều kiện áp dụng trạm thu ven bờ:
  - Công trình thu kết hợp trạm bơm cấp 1 xây dựng trực tiếp ngay tại mép bờ sông hoặc hồ nước.
  - Điều kiện địa chất và hình thái sông thích hợp:
    - Bờ sông có độ dốc đứng lớn, mái bờ ổn định không sạt lở.
    - Độ sâu dòng nước sát bờ lớn, đảm bảo đủ chiều sâu ngập nước trong mùa khô hạn kiệt.
    - Nền móng bờ là đá gốc hoặc lớp cuội sỏi chặt có sức chịu tải cao ($R \ge 2.5\text{ kg/cm}^2$).

- Giới hạn chiều cao hút và nguy cơ xâm thực bơm đặt cạn:
  - Phương trình tính chiều cao hút hình học cho phép cực đại của máy bơm ly tâm đặt trên cạn ($H_{\text{suction, max}}$):
    $$H_{\text{suction, max}} = \frac{p_{\text{atm}} - p_v}{\rho g} - h_{L,\text{suction}} - \text{NPSH}_{\text{req}} - \Delta H_{\text{safety}} \le 6.0 - 7.5\text{ m}$$
    - $p_{\text{atm}}$: Áp suất khí quyển tại cao độ đặt trạm bơm ($p_{\text{atm}} \approx 101325\text{ Pa}$ ở mực nước biển).
    - $p_v$: Áp suất hơi bão hòa của nước tại nhiệt độ vận hành (ở $25^\circ\text{C}$, $p_v = 3169\text{ Pa}$; ở $30^\circ\text{C}$, $p_v = 4246\text{ Pa}$).
    - $\rho$: Khối lượng riêng của nước thô ($\rho \approx 1000\text{ kg/m}^3$).
    - $h_{L,\text{suction}}$: Tổng tổn thất cột áp thủy lực trên đường ống hút, bao gồm tổn thất qua song chắn, lưới lọc, van một chiều, côn thu và ma sát dọc đường ($\text{m}$).
    - $\text{NPSH}_{\text{req}}$: Cột áp hút thực dương yêu cầu của máy bơm theo công bố của nhà chế tạo ($\text{NPSH}_{\text{req}} \approx 2.5 - 4.5\text{ m}$).
    - $\Delta H_{\text{safety}}$: Hệ số an toàn chống tạo bọt khí xâm thực ($\Delta H_{\text{safety}} = 0.5 - 1.0\text{ m}$).
  - Khi biên độ dao động mực nước sông giữa mùa lũ và mùa cạn $\Delta H_{\text{river}} > 6.0\text{ m}$, bơm đặt cạn không thể tự hút nước trong mùa kiệt; bắt buộc phải chuyển sang phương án giếng thu kết hợp trạm bơm trục đứng chìm hoặc trạm bơm kiểu giếng chìm dưới mực nước ngầm.

- Cấu tạo hạ tầng xây dựng và tuyến ống áp lực ven bờ:
  - Móng mố trụ bê tông cốt thép: Đỡ buồng bơm vươn ra lòng sông sâu, tạo khoảng cách an toàn với vùng nước bùn cạn sát chân bờ.
  - Cầu dẫn kỹ thuật ($Access\text{ Bridge}$ / $Catwalk$): Lối đi lại cho nhân viên kỹ thuật có lan can bảo vệ, đồng thời đóng vai trò hệ dầm đỡ tuyến ống đẩy áp lực bằng thép hoặc gang dẻo.
  - Tuyến ống đẩy áp lực ($Discharge\text{ Main}$): Lắp đặt van chặn đĩa, van một chiều lò xo và thiết bị chống va đập thủy lực (búa nước) khi xảy ra sự cố mất điện đột ngột.

  - **Hình 5:** Trạm bơm thu nước ven bờ đặt trên hệ trụ bê tông
    - <img src="ch02_water_source_collection/assets/fig_05_p4.jpeg" alt="Hình 5" />
    - **Hình này chứng minh điều gì**
      - Nhà trạm bơm ven bờ vươn ra mép nước sâu bằng trụ đỡ.
    - **Từ đâu mà thấy được**
      - Nhà bơm bê tông trên cọc và đường ống áp lực chạy vào bờ.

  - **Hình 6:** Cầu dẫn giàn thép nối đài thu nước mặt xa bờ
    - <img src="ch02_water_source_collection/assets/fig_06_p4.jpeg" alt="Hình 6" />
    - **Hình này chứng minh điều gì**
      - Cầu dẫn thép đưa vị trí lấy nước ra xa vùng bờ đục.
    - **Từ đâu mà thấy được**
      - Nhịp giàn thép khẩu độ lớn vượt mặt nước ra chòi thu nổi.

#### 2.2.4 Công trình thu nước xa bờ (Offshore Intake)

- Phạm vi ứng dụng và đặc điểm thủy văn vùng xa bờ:
  - Áp dụng khi bờ sông hoặc hồ nước có độ dốc quá thoai thoải, mực nước sát bờ rất nông, đáy bờ chứa nhiều bùn lầy, cỏ rác và nước đục do sóng đánh xói mòn.
  - Áp dụng khi nguồn nước ven bờ bị ô nhiễm cục bộ bởi nước thải dân sinh, giao thông thủy hoặc dòng chảy hồi lưu.
  - Vị trí đầu thu xa bờ được đưa ra giữa lòng sông hoặc tâm hồ nơi có dòng nước chảy xiết tự nhiên, độ sâu lớn và chất lượng nước trong sạch quanh năm.

- Cấu tạo đầu thu ngập nước xa bờ (Submerged Intake Crib):
  - Khung lồng bê tông đúc sẵn hoặc khung thép chịu lực bọc đá hộc xếp chèn xung quanh, đặt chìm hoàn toàn dưới lòng sông/hồ sâu.
  - Miệng thu dạng nón loe ($Bellmouth$) mở rộng diện tích để hạ thấp vận tốc dòng vào cửa thu: $v_{\text{intake}} \le 0.15\text{ m/s}$ chống hút cá và cặn cát.
  - Lưới chắn miệng thu chế tạo từ vật liệu hợp kim đồng - niken ($Cu-Ni\text{ alloy}$) hoặc thép không gỉ tráng phủ chống sinh vật bám (rong rêu, hà sông, hến nước ngọt bám tắc miệng thu).

- Tuyến ống dẫn nước tự chảy từ đầu thu xa bờ về giếng bờ:
  - Nước từ đầu thu ngập dẫn về trạm bơm ven bờ bằng đường ống tự chảy áp lực ngập ($Gravity\text{ Pipeline}$) hoặc đường ống xi-phông ($Siphon\text{ Pipe}$).
  - Biện pháp thi công và bảo vệ tuyến ống ngầm:
    - Ống thép bọc bitum / epoxy hoặc ống nhựa nhiệt dẻo HDPE đường kính lớn ($DN\text{ 500} - DN\text{ 1500}$).
    - Ống được chôn sâu dưới lòng sông tối thiểu $0.5 - 1.0\text{ m}$ trong rãnh nạo vét và phủ đá dăm bảo vệ chống neo tàu bè cào rách ống.
  - Vận tốc dòng chảy trong ống tự chảy khống chế theo chế độ thủy lực:
    - Vận tốc tối thiểu chống lắng cặn bùn cát hạt mịn: $v_{\text{min}} \ge 0.7 - 0.8\text{ m/s}$.
    - Vận tốc tối đa hạn chế tổn thất cột áp dọc đường: $v_{\text{max}} \le 1.2 - 1.5\text{ m/s}$.
    - Phương trình tính tổn thất cột áp dọc đường theo Hazen-Williams:
      $$h_f = \frac{10.67 \cdot L \cdot Q^{1.852}}{C^{1.852} \cdot D^{4.87}}$$
      - $L$: Chiều dài tuyến ống dẫn tự chảy xa bờ ($\text{m}$).
      - $Q$: Lưu lượng nước tự chảy qua ống ($\text{m}^3\text{/s}$).
      - $D$: Đường kính trong của đường ống ($\text{m}$).
      - $C$: Hệ số nhám Hazen-Williams ($C = 130 - 150$ đối với ống HDPE và thép tráng nhẵn).

- Công trình thu nước xa bờ dạng tháp nổi có cầu dẫn kết cấu thép giàn:
  - Khi khoảng cách xa bờ vừa phải ($50 - 200\text{ m}$), xây dựng đài thu nước nổi kết nối với bờ bằng hệ cầu dẫn giàn thép ($Steel\text{ Truss\ Bridge}$).
  - Cầu dẫn giàn thép chịu lực cao, đỡ toàn bộ tải trọng của tuyến ống áp lực dẫn nước và hệ thống dây cáp điện điều khiển.
  - Sàn cầu dẫn rộng $1.2 - 2.0\text{ m}$ cho phép công nhân đi lại kiểm tra trực quan, vận hành hệ thống van đóng ngắt và xúc rửa cửa thu định kỳ.

  - **Hình 7:** Tuyến ống đẩy trạm thu ven bờ kết nối về nhà máy
    - <img src="ch02_water_source_collection/assets/fig_07_p5.jpeg" alt="Hình 7" />
    - **Hình này chứng minh điều gì**
      - Tuyến ống đẩy được nâng cao trên mố trụ chống ngập lũ bờ.
    - **Từ đâu mà thấy được**
      - Ống áp lực đường kính lớn cố định trên dầm đỡ bê tông cốt thép.

  - **Hình 8:** Đài thu nước xa bờ với cầu dẫn kết cấu thép giàn
    - <img src="ch02_water_source_collection/assets/fig_08_p5.jpeg" alt="Hình 8" />
    - **Hình này chứng minh điều gì**
      - Công trình thu xa bờ tiếp cận tầng nước sâu trong lòng hồ.
    - **Từ đâu mà thấy được**
      - Đài thu độc lập giữa hồ nước tĩnh nối bằng cầu dẫn dài.

### 2.3 Công trình thu nước ngầm (Groundwater Well Systems)

* Khái niệm và chức năng kỹ thuật của công trình thu nước dưới đất ($Well\ Systems$):
  * Giếng thu nước ($Well$) là công trình kỹ thuật chuyên dụng để khai thác nguồn nước dưới đất ($Groundwater$) phục vụ cấp nước sinh hoạt, đô thị và công nghiệp.
  * Phân loại cơ bản theo tầng chứa nước và độ sâu khai thác gồm hai nhóm công trình: giếng nông ($Shallow\ well$, slide ghi là $Swallow\ well$) và giếng sâu ($Deep\ well$).
  * Chu trình xây dựng và khai thác hệ thống giếng bao gồm ba khâu kỹ thuật trọng tâm:
    * Phương pháp thi công đào hoặc khoan tạo giếng ngầm ($Well\ drilling$).
    * Kết cấu công trình bảo vệ thành giếng và thu nhận nước (ống vách $casing$, ống lọc $screen$, và vành đai trám cách ly $annular\ seal$).
    * Thiết bị động lực nâng nước ngầm: máy bơm chìm giếng sâu ($Submersible\ well\ pump$) hoặc máy bơm tay cơ học ($Hand\ well\ pump$).

#### 2.3.1 Giếng nông (Shallow Well / Swallow Well)

* Định nghĩa và đặc tính thủy lực của giếng nông ($Shallow\ Well$):
  * Giếng nông khai thác tầng chứa nước ngầm không áp ($unconfined\ aquifer$) hoặc tầng ngấm bề mặt sát mặt đất.
  * Chiều sâu khai thác hạn chế, thường dao động trong khoảng từ vài mét đến dưới $15\text{ m} - 20\text{ m}$.
  * Mực nước tĩnh và lưu lượng khai thác dao động trực tiếp theo mùa mưa và mùa khô.
  * Chất lượng nước dễ bị ảnh hưởng bởi nước mưa chảy tràn bề mặt, nước thải sinh hoạt và hóa chất nông nghiệp.

##### 2.3.1.1 Kết cấu bảo vệ miệng giếng và thành giếng lộ thiên (Well Curb and Protective Enclosure)

* Thành miệng giếng lộ thiên ($Well\ curb$):
  * Thành miệng giếng xây cao hơn cốt mặt đất tự nhiên tối thiểu $0.3\text{ m} - 0.5\text{ m}$ để ngăn nước mưa chảy tràn, bùn đất và rác rưởi xâm nhập vào lòng giếng.
  * Gia cố thành miệng giếng bằng kết cấu vách gỗ xẻ ngang ($timber\ well$) kết hợp hệ mái che hình nón:
    * Mái che bằng gỗ bảo vệ mặt nước giếng khỏi lá cây rụng, bụi khí quyển và nước mưa trực tiếp.
    * Thành giếng hình lục giác ghép từ các thanh gỗ xẻ ngang đặt nổi trên nền sân lát đá bao quanh lòng giếng.
  - **Hình 9.** Giếng đào bằng gỗ có mái che (*timber well*)
    - <img src="ch02_water_source_collection/assets/fig_09_p6.jpeg" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Giải pháp gia cố thành giếng bằng gỗ ghép và mái che bảo vệ mặt nước giếng đào nông khỏi ô nhiễm bề mặt.
    - **Từ đâu mà thấy được**
      - Nửa trên: Mái nón lục giác lợp ván gỗ xếp tầng được đỡ bằng các cột trụ đứng.
      - Nửa dưới: Thành giếng lục giác ghép từ các thanh gỗ ngang đặt nổi trên nền sân bao quanh lòng nước.
  * Gia cố thành miệng giếng bằng khối đá tự nhiên ($stone\text{-}lined\ well$):
    * Các khối đá đẽo bo tròn xếp chồng khít thành nhiều tầng vành khuyên tạo gờ chắn kiên cố trên nền đất hoặc thảm cỏ.
    * Vành đai đá xếp khít giúp ổn định bờ miệng giếng, chống xói lở đất xung quanh giếng đào.
  - **Hình 10.** Thành giếng nông lộ thiên xây bằng các khối đá
    - <img src="ch02_water_source_collection/assets/fig_10_p6.jpeg" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Thành giếng dạng ống tròn nhô cao khỏi mặt đất với các tầng đá xếp khít bảo vệ miệng giếng nông.
    - **Từ đâu mà thấy được**
      - Quan sát khối nổi trên bãi cỏ: 4 lớp đá sẫm màu bo tròn ghép thành gờ chắn quanh miệng giếng hở.
  * Bố trí giếng nông kết cấu gỗ có mái che kết hợp thiết bị phun nước cảnh quan (slide 7):
    * Kết cấu giếng gỗ ghép có mái che bảo vệ nguồn nước, có thể tích hợp vòi phun nước phục vụ cảnh quan sân vườn.
  - **Hình 11.** Giếng nông bằng gỗ có mái che và đầu phun nước
    - <img src="ch02_water_source_collection/assets/fig_11_p7.jpeg" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Minh họa giếng đào nông lộ thiên gia cố bằng thành gỗ ghép có mái che bảo vệ.
    - **Từ đâu mà thấy được**
      - Thành giếng đa giác ghép từ các thanh gỗ xếp ngang, phía trên dựng cột đỡ mái che chóp nón.
      - Đầu phun đặt giữa lòng giếng tạo cột nước phun thẳng đứng.
  * Cấu tạo miệng giếng đá tự nhiên lộ thiên bao quanh miệng giếng (slide 7):
    * Vành đá tròn xếp khít giữ ổn định miệng giếng hở và ngăn cản tạp chất mặt đất rơi vào lòng giếng.
  - **Hình 12.** Miệng giếng nông gia cố bằng đá tự nhiên
    - <img src="ch02_water_source_collection/assets/fig_12_p7.jpeg" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Cấu trúc thành giếng dạng khối trụ tròn ghép từ các tảng đá bo tròn nhô cao bảo vệ giếng đào.
    - **Từ đâu mà thấy được**
      - Vị trí trung tâm: Các khối đá sẫm màu ghép khít tạo vành tròn quanh lòng giếng rỗng.
      - Khu vực chân giếng: Đặt trực tiếp trên nền cỏ tự nhiên có lá rụng.

##### 2.3.1.2 Kết cấu thành giếng xây, cơ chế khai thác thủ công và biện pháp thi công đào giếng (Well Construction and Water Extraction)

* Kết cấu thành giếng xây đá hộc và hệ ròng rọc múc nước thủ công:
  * Thành giếng xây bằng đá hộc liên kết vữa xi măng ($rubble\ masonry\ well$) tạo kết cấu ống hình trụ vững chắc, chịu áp lực ngang của đất và ngăn nước thấm ngang từ lớp đất mặt.
  * Khung gỗ hình chữ U ngược dựng đứng hai bên miệng giếng gắn ròng rọc đơn ($pulley$) và dây thừng treo gàu múc nước:
    * Dây thừng luồn qua ròng rọc thả thẳng đứng xuống tâm giếng giúp giảm lực kéo múc nước thủ công.
    * Chiều cao thành giếng nhô cao tạo rào chắn an toàn, tránh người và súc vật rơi ngã vào lòng giếng.
  - **Hình 13.** Giếng đào nông với khung gỗ và ròng rọc múc nước
    - <img src="ch02_water_source_collection/assets/fig_13_p8.jpeg" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Miệng giếng đào hở lộ thiên khai thác nước thủ công bằng ròng rọc, đặc trưng của giếng đào nông ($shallow\ well$).
    - **Từ đâu mà thấy được**
      - Giữa ảnh: Thành giếng hình trụ xây bằng đá hộc nhô cao khỏi mặt đất.
      - Phía trên: Giá gỗ hai trụ treo ròng rọc đơn, dây thừng thả thẳng vào lòng giếng.
  * Phương pháp thi công đào giếng hạ chìm ống bi bê tông đúc sẵn ($precast\ concrete\ rings$):
    * Đào đất thẳng đứng kết hợp hạ chìm các phân đoạn ống bi bê tông đúc sẵn theo trọng lượng bản thân.
    * Khi nhân công đào xúc đất từ đáy giếng lên trên, ống bi bê tông tự chìm dần xuống, đóng vai trò ống vách bảo vệ thành giếng chống sập lở tức thời.
    * Đỉnh miệng giếng bố trí mạng cốt thép chờ tỏa tròn để đổ bê tông giằng liên kết bệ giếng và sân lát chống thấm.
  - **Hình 14.** Thi công giếng đào nông bằng ống bi bê tông
    - <img src="ch02_water_source_collection/assets/fig_14_p8.jpeg" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Tiết diện tròn của ống bi bê tông tạo không gian an toàn cho thợ đào thao tác vét đất trực tiếp hạ ống vách giếng.
    - **Từ đâu mà thấy được**
      - Vị trí lòng giếng: Công nhân đội mũ bảo hộ đứng bên trong ống bi bê tông, có dây an toàn thả theo phương đứng.
      - Vị trí miệng giếng: Các thanh cốt thép bố trí tỏa tròn quanh gờ đỉnh ống vách trên mặt đất.
  * Thành giếng đá hộc kiên cố kết hợp ròng rọc múc nước giếng khơi (slide 9):
    * Phương thức khai thác nước thủ công truyền thống phù hợp với quy mô cấp nước nhỏ phân tán ở nông thôn.
  - **Hình 15.** Giếng đào nông với thành đá hộc và ròng rọc
    - <img src="ch02_water_source_collection/assets/fig_15_p9.jpeg" alt="Hình 15" />
    - **Hình này chứng minh điều gì**
      - Miệng giếng trụ tròn xây nổi trên mặt đất, kết hợp khung hai trụ gỗ treo ròng rọc múc nước.
    - **Từ đâu mà thấy được**
      - Nửa dưới ảnh: Thành giếng hình trụ bằng các khối đá hộc liên kết vữa trát.
      - Nửa trên ảnh: Khung hai cột gỗ đỡ thanh ngang treo ròng rọc ở giữa, dây thừng vắt sang cột phải.
  * Thao tác thủ công của nhân công đào vét đáy giếng trong lòng ống bi (slide 9):
    * Thợ đào giếng làm việc trong không gian hẹp bên dưới ống vách bê tông, đảm bảo an toàn bằng mũ bảo hộ và dây thừng cứu sinh nối lên mặt bằng thi công.
  - **Hình 16.** Thợ đào làm việc trong lòng giếng nông thủ công
    - <img src="ch02_water_source_collection/assets/fig_16_p9.jpeg" alt="Hình 16" />
    - **Hình này chứng minh điều gì**
      - Không gian làm việc chật hẹp bên trong lòng ống giếng với dây thừng an toàn nối thẳng lên mặt đất.
    - **Từ đâu mà thấy được**
      - Góc nhìn từ miệng giếng thẳng xuống: Người thợ đội mũ bảo hộ đứng bên dưới lòng ống tròn.
      - Dây thừng màu xanh thả thẳng đứng từ mặt bằng thi công xuống vị trí thợ đứng.

#### 2.3.2 Giếng khoan sâu (Deep Well)

* Định nghĩa và đặc tính của giếng khoan sâu ($Deep\ well$):
  * Giếng khoan sâu khai thác tầng chứa nước có áp ($confined\ aquifer / artesian\ aquifer$) nằm sâu dưới các tầng địa chất cách nước.
  * Chiều sâu khai thác lớn, thường từ $30\text{ m}$ đến trên $300\text{ m}$.
  * Nguồn nước ngầm tầng sâu có độ tinh khiết cao, được bảo vệ khỏi các nguồn gây ô nhiễm bề mặt bởi các lớp sét cách nước.
  * Trữ lượng khai thác lớn và ổn định quanh năm, là nguồn nước chính cho các hệ thống cấp nước đô thị và công nghiệp.

* Cấu tạo chi tiết mặt cắt kỹ thuật giếng khoan sâu:
  * Nắp giếng kín nước có lỗ thông khí chống sinh vật xâm nhập ($Vented,\ Vermin\ Proof\ Well\ Cap$):
    * Cao độ đỉnh nắp giếng nhô cao tối thiểu $40\text{ cm}$ ($16\text{ in.}$) so với mặt ụ đất đắp để ngăn chặn nước mưa hoặc nước tràn xâm nhập vào trong lòng ống vách.
  * Ụ đất đắp thoải dốc quanh miệng giếng ($Mounded\ Earth$):
    * Đất xung quanh miệng giếng được đắp cao và thoải dốc ra phía ngoài với bán kính tối thiểu $1.50\text{ m}$ ($5.0\text{ ft.}$) tính từ tâm giếng, hướng dòng nước mặt chảy xa miệng giếng.
  * Vành chèn cách ly chống thấm ($Annular\ Seal$):
    * Khoảng không gian hình khuyên giữa vách lỗ khoan đất đá và mặt ngoài ống vách được bơm trám kín bằng vữa sét bentonite ($Bentonite\ Slurry$), vữa xi măng ($Cement\ Grout$), hoặc bê tông ($Concrete$).
    * Chiều sâu vành chèn cách ly đạt tối thiểu $6.0\text{ m}$ ($20\text{ ft.}$) tính từ bề mặt đất tự nhiên, ngăn ngừa nước mặt ô nhiễm rò rỉ dọc theo vách giếng xuống tầng chứa nước.
  * Ống vách giếng kín nước ($Watertight\ Well\ Casing$):
    * Chế tạo bằng thép hoặc nhựa UPVC chịu lực cao, giữ ổn định thành lỗ khoan không bị sạt lở và duy trì hình dạng khoang giếng dẫn nước lên mặt đất.
    * Mực nước trong ống vách dâng lên cân bằng tại mực nước tĩnh ($Static\ Water\ Level$) theo áp lực thủy tĩnh của tầng ngậm nước.
  * Khớp chèn kín đáy giếng ($Packer\ Seal$):
    * Khớp nối kín đặt tại điểm chuyển tiếp giữa chân ống vách kín nước và đỉnh ống lọc nước.
    * Ngăn chặn cát sỏi hoặc vật liệu chèn từ các tầng đất đá phía trên lọt vào khe hở khớp nối.
  * Ống lọc nước giếng khoan ($Screen$):
    * Chế tạo bằng thép không gỉ có khe hẹp chuẩn xác, đặt ngập hoàn toàn bên trong tầng chứa nước cát hoặc sỏi ($Sand\ Or\ Gravel\ Aquifer$).
    * Thu nhận dòng nước ngầm chảy vào giếng đồng thời giữ lại toàn bộ hạt cát sỏi không cho xâm nhập vào buồng bơm.
  - **Hình 17.** Mặt cắt cấu tạo chi tiết giếng sâu khai thác nước ngầm
    - <img src="ch02_water_source_collection/assets/fig_17_p10.jpeg" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - Thể hiện đầy đủ cấu tạo mặt cắt giếng sâu với nắp bảo vệ, vành chèn cách ly bentonite/xi măng sâu $6.0\text{ m}$, ống vách kín nước và ống lọc thu nước tầng cát sỏi.
    - **Từ đâu mà thấy được**
      - Trục đọc từ trên xuống: Nắp $Vented,\ Vermin\ Proof\ Well\ Cap$ cao $40\text{ cm}$, đai trám $Annular\ Seal$ sâu $6.0\text{ m}$ bao quanh $Watertight\ Well\ Casing$.
      - Đáy giếng: Khớp nối $Packer\ Seal$ liên kết ống vách với $Screen$ nằm trong tầng $Sand\ Or\ Gravel\ Aquifer$.

* Phương pháp và thiết bị thi công giếng khoan sâu bằng cơ giới:
  * Khoan xoay bằng xe cơ giới kết hợp tuần hoàn dung dịch bentonite:
    * Dung dịch bùn khoan bentonite được bơm qua lòng cần khoan xuống đáy lỗ giếng làm mát mũi khoan và cuốn mùn khoan trào ngược lên miệng giếng.
    * Dung dịch bùn tạo áp lực thủy tĩnh giữ cân bằng thành lỗ khoan, ngăn ngừa hiện tượng sập vách đất đá trước khi hạ ống vách.
  - **Hình 18.** Thi công khoan giếng sâu bằng xe khoan cơ giới
    - <img src="ch02_water_source_collection/assets/fig_18_p10.jpeg" alt="Hình 18" />
    - **Hình này chứng minh điều gì**
      - Bố trí thực tế của giàn khoan cơ giới với cần khoan cắm sâu vào đất và rãnh dẫn bùn khoan tuần hoàn.
    - **Từ đâu mà thấy được**
      - Miệng giếng bên dưới: Cần khoan quay cắm thẳng xuống đất, bùn xám đục trào ra rãnh thoát nước.
      - Trên xe khoan: Tháp khoan màu đỏ gắn hệ thống thủy lực, giá đỡ cần khoan và bàn điều khiển của thợ khoan.
  * Mũi khoan xoay chuyên dụng phá vỡ đất đá ($Rotary\ drill\ bit$):
    * Cánh chém xoắn bản rộng gắn hàng răng cưa tôi cứng nhọn sắc chạy dọc mép cắt.
    * Khi quay tròn dưới áp lực nén cao của tháp khoan, các răng cưa cào xới, chém vỡ và nghiền nát kết cấu tầng đất đá cứng.
  - **Hình 19.** Mũi khoan xoay chuyên dụng dùng trong thi công giếng sâu
    - <img src="ch02_water_source_collection/assets/fig_19_p10.jpeg" alt="Hình 19" />
    - **Hình này chứng minh điều gì**
      - Cấu tạo mũi khoan xoay có các cánh chém hàn răng cưa nhọn để cào xới và nghiền phá đất đá khi khoan giếng.
    - **Từ đâu mà thấy được**
      - Mép cánh cắt bên trái: Dải răng cưa nhọn chạy dọc theo toàn bộ viền lưỡi khoan.
      - Phần thân bên phải: Ống thép trụ tròn truyền mô-men xoắn từ chuỗi cần khoan.

#### 2.3.3 Thiết bị xe khoan giếng (Well Drilling Vehicle)

* Tổ hợp xe tải khoan giếng cơ giới tự hành ($Well\ drilling\ vehicle$):
  * Tích hợp trọn bộ hệ thống khoan giếng trên khung gầm xe tải chịu tải nặng, cơ động cao giữa các hiện trường thi công giếng sâu.
  * Thi công hiệu quả qua các tầng địa chất phức tạp từ đất bùn sét, cát sỏi đến tầng đá gốc.
  * Bảo đảm kích thước lỗ khoan chuẩn xác để lắp đặt hoàn chỉnh ống vách, vành chèn cách ly bentonite và ống lọc nước ngầm.
  - **Hình 20.** Cấu tạo chi tiết giếng khoan hoàn thiện và lớp bảo vệ
    - <img src="ch02_water_source_collection/assets/fig_20_p11.jpeg" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - Vành chèn cách ly $Annular\ Seal$ sâu $6.0\text{ m}$ và ụ đất $Mounded\ Earth$ rộng $1.50\text{ m}$ bảo vệ tuyệt đối giếng khoan sâu khỏi nước bẩn bề mặt.
    - **Từ đâu mà thấy được**
      - Trục dọc từ trên xuống: Nắp $Vented,\ Vermin\ Proof\ Well\ Cap$ cao $40\text{ cm}$, đai trám $Annular\ Seal$ bọc ống vách sâu $6.0\text{ m}$.
      - Đáy giếng: Mũi tên chỉ $Static\ Water\ Level$, khớp $Packer\ Seal$ và ống lọc $Screen$ đặt trong tầng cát sỏi $Sand\ Or\ Gravel\ Aquifer$.

* Các trang thiết bị kỹ thuật chính tích hợp trên xe tải khoan giếng:
  * Tháp khoan đứng chịu lực ($Drilling\ mast$): Tháp kết cấu giàn thép gắn ở đuôi xe tải, định vị và nâng hạ thẳng đứng bằng xi lanh thủy lực.
  * Đầu xoay thủy lực truyền động ($Rotary\ head$): Truyền mô-men xoắn lớn và lực ép dọc trục lên chuỗi cần khoan ($drill\ pipe$) để xuyên sâu vào địa tầng.
  * Giá chứa và cấp cần khoan dự phòng ($Drill\ pipe\ rack$): Bố trí bên hông tháp khoan, cho phép cẩu lắp và nối ren liên tục chuỗi cần khoan khi giếng sâu dần.
  * Bảng điều khiển thủy lực trung tâm ($Hydraulic\ control\ console$): Đặt cạnh ghế ngồi người vận hành, tích hợp đồng hồ áp lực và tay gạt van phân phối thủy lực.
  * Tấm lót sàn thép dập gân chống trượt: Lót quanh miệng hố khoan bảo đảm an toàn lao động cho công nhân thao tác tại hiện trường.
  - **Hình 21.** Thực tế thi công giếng khoan bằng xe khoan chuyên dụng
    - <img src="ch02_water_source_collection/assets/fig_21_p11.jpeg" alt="Hình 21" />
    - **Hình này chứng minh điều gì**
      - Hiện trường thi công giếng khoan cơ giới với tháp khoan, bàn điều khiển thủy lực và bó cần khoan dự phòng.
    - **Từ đâu mà thấy được**
      - Trung tâm phía dưới: Cần khoan cắm thẳng đứng vào miệng hố đất ngập nước bùn xám đục.
      - Thân máy màu đỏ: Bảng điều khiển thủy lực bên trái có công nhân thao tác và giá xếp bó cần khoan dự phòng bên phải.
  * Cấu tạo chi tiết mũi khoan xoay cánh răng cưa ($Rotary\ drill\ bit$):
    * Cánh chém xoắn bản rộng xẻ rãnh hàn hàng răng cưa tôi cứng nhô ra phía trước.
    * Phần thân sau dạng ống tròn có ren kết nối đồng trục với chuỗi cần khoan của giàn khoan.
  - **Hình 22.** Cấu tạo mũi khoan xoay có cánh răng cưa
    - <img src="ch02_water_source_collection/assets/fig_22_p11.jpeg" alt="Hình 22" />
    - **Hình này chứng minh điều gì**
      - Cấu tạo thực tế của mũi khoan gồm các cánh chém xòe xẻ rãnh răng cưa gắn trên trục ống nối ren.
    - **Từ đâu mà thấy được**
      - Các mép cánh cắt phía trước xẻ rãnh răng cưa nhô ra để cào xới đất đá.
      - Ống trục kim loại phía sau kết nối đồng trục với cần khoan.

#### 2.3.4 Máy bơm giếng khoan sâu (Well Pump / Submersible Deep Well Pump)

* Khái niệm và vai trò của máy bơm giếng trong hệ thống thu gom nước ngầm:
  * Máy bơm giếng ($Well\ pump$) là thiết bị động lực tạo áp lực hút nâng nước ngầm từ đáy giếng lên bề mặt đất và đưa vào hệ thống xử lý hoặc mạng lưới truyền dẫn.
  * Máy bơm chìm ly tâm đa tầng cánh kiểu QJ ($QJ\ submersible\ deep\ well\ pump$) là giải pháp tiêu chuẩn cho các giếng khoan sâu công nghiệp:
    * Toàn bộ cụm bơm và động cơ điện làm việc ngập sâu dưới mực nước động trong lòng ống vách giếng.
    * Tạo cột áp đẩy nước rất cao nhờ ghép nối tiếp nhiều bánh công tác trên cùng một trục bơm.
  * Máy bơm tay cơ học phục vụ cấp nước sinh hoạt quy mô phân tán nhỏ lẻ tại các vùng nông thôn không dùng điện.

* Cấu tạo chi tiết máy bơm chìm giếng sâu nhiều tầng cánh kiểu QJ:
  * Thân van một chiều đỉnh bơm ($Non\text{-}return\ valve\ body$):
    * Bố trí tại họng xả trên cùng của bơm, ngăn nước trong cột ống đẩy dội ngược về giếng khi tắt động cơ, triệt tiêu xung kích búa nước ($water\ hammer$).
  * Tấm nẹp bảo vệ dây cáp điện ($Wire\text{-}protecting\ plate$):
    * Nẹp kim loại ốp dọc bên ngoài vỏ bơm bảo vệ dây cáp cấp điện cho động cơ chìm, chống ma sát cọ quẹt vào thành ống vách khi thả hoặc kéo bơm.
  * Cụm vỏ dẫn dòng trên và các vỏ khuếch tán ($Diversion\ shell\ units$):
    * Chế tạo bằng gang đúc ($Cast\ iron$), dẫn hướng dòng nước từ cửa ra của cánh bơm tầng trước vào tâm hút của cánh bơm tầng kế tiếp.
  * Ổ trục dẫn hướng bằng cao su ($Rubber\ bearing$):
    * Bạc lót ổ trục bằng vật liệu cao su ($Rubber$), tự bôi trơn bằng chính nước ngầm xung quanh mà không cần dầu mỡ bôi trơn.
    * Chịu mài mòn vượt trội khi nước ngầm có lẫn cặn cát mịn lơ lửng.
  * Bánh công tác ly tâm nhiều tầng ($Impellers$):
    * Chế tạo bằng gang đúc ($Cast\ iron$), các cánh xếp tầng quay đồng trục để nhân bội áp lực nước đẩy lên cao.
  * Vỏ côn kẹp định vị ($Cone\text{-}shaped\ casing$):
    * Chế tạo bằng thép không gỉ ($Stainless\ steel$), cố định vị trí các chi tiết quay trong buồng bơm.
  * Lưới lọc chắn rác cửa nạp nước ($Water\text{-}filtering\ net$):
    * Chế tạo bằng vật liệu nhựa ($Plastic / Platistc$) bao quanh cửa hút ở giữa động cơ và buồng cánh bơm, ngăn sỏi cát thô lọt vào buồng cánh.
  * Trục bơm ly tâm ($Pump\ shaft$):
    * Chế tạo bằng thép không gỉ ($Stainless\ steel$), chịu lực kéo và mô-men xoắn cao, chống gỉ sét tuyệt đối trong nước.
  * Khớp nối cửa hút ($Water\ inlet\ joint\ unit$) và khớp nối trục ($Shaft\ coupling$):
    * Chế tạo bằng thép đúc ($Cast\ steel$), truyền động xoay trực tiếp từ trục động cơ điện sang trục cánh bơm.
  - **Hình 23.** Cấu tạo mặt cắt bơm chìm giếng khoan QJ
    - <img src="ch02_water_source_collection/assets/fig_23_p12.jpeg" alt="Hình 23" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu tạo mặt cắt bơm chìm đa tầng cánh QJ từ khớp nối, lưới lọc cửa hút, các tầng cánh ly tâm đến van một chiều đỉnh bơm.
    - **Từ đâu mà thấy được**
      - Mặt cắt bên trái đọc từ dưới lên: Khớp nối ($shaft\ coupling$), lưới lọc ở cửa hút, các tầng cánh ($impeller$) cùng vỏ dẫn dòng, và van một chiều ở trên cùng.
      - Hai hình trụ bên phải: Kết cấu thon dài gồm nhiều tầng vỏ ghép nối tiếp để thả lọt vào ống giếng khoan.

* Thiết bị bơm lắc tay cơ học lắp đặt ngoài trời:
  * Xi lanh đứng bằng gang kết hợp cần gạt đòn bẩy cho phép bơm hút nước giếng ngầm thủ công bằng sức người mà không cần nguồn điện.
  - **Hình 24.** Bơm lắc tay cơ học ngoài trời khai thác nước giếng
    - <img src="ch02_water_source_collection/assets/fig_24_p12.jpeg" alt="Hình 24" />
    - **Hình này chứng minh điều gì**
      - Cơ cấu xi lanh đứng kết hợp cần gạt đòn bẩy cho phép nâng nước giếng thủ công bằng sức người.
    - **Từ đâu mà thấy được**
      - Phía trên có cần gạt uốn cong liên kết với ty pít-tông ở đỉnh thân bơm trụ đứng.
      - Thân bơm kim loại gắn vòi xả ngang bên trái, chân đế bắt cố định tại miệng giếng ngoài trời.

#### 2.3.5 Bơm tay giếng khoan (Hand Well Pump)

* Vai trò và phạm vi áp dụng của bơm tay giếng khoan ($Hand\ well\ pump$):
  * Bơm tay giếng khoan vận hành hoàn toàn bằng năng lượng cơ bắp của con người.
  * Cung cấp giải pháp cấp nước sinh hoạt thiết thực tại các vùng nông thôn hẻo lánh, hải đảo hoặc làm nguồn cấp nước dự phòng khi mất điện lưới.
  * Đối chiếu cấu tạo công nghiệp của bơm chìm đa tầng cánh QJ trên slide 13:
  - **Hình 25.** Cấu tạo bơm chìm giếng sâu nhiều tầng cánh QJ
    - <img src="ch02_water_source_collection/assets/fig_25_p13.jpeg" alt="Hình 25" />
    - **Hình này chứng minh điều gì**
      - Cấu tạo chuỗi nhiều tầng cánh ($impeller$) và buồng dẫn dòng ghép nối tiếp tạo áp lực đẩy giếng sâu công nghiệp.
    - **Từ đâu mà thấy được**
      - Mặt cắt bên trái thể hiện chuỗi cánh bơm xếp dọc trục và cụm lưới lọc đáy ($water\text{-}filtering\ net$).
      - Lưu ý: Hình minh họa cấu tạo $QJ\ submersible\ deep\ well\ pump$ đặt trong slide $Hand\ well\ pump$.

* Cấu tạo chi tiết và nguyên lý hoạt động của bơm tay thân gang đúc:
  * Thân bơm trụ đứng ($Pump\ barrel / cylinder$):
    * Đúc nguyên khối bằng gang ($cast\ iron$), chịu lực va đập cơ học và chống chịu thời tiết ngoài trời bền bỉ.
    * Sơn phủ men chống gỉ màu xanh thẫm, thân gồm hai đoạn liên kết với nhau bằng khớp mặt bích bắt bu-lông ở giữa cột trụ.
  * Cần gạt đòn bẩy tay bơm ($Lever\ handle$):
    * Chế tạo bằng gang đúc uốn cong dạng cánh cung kéo dài về phía sau, hoạt động theo nguyên lý đòn bẩy cấp 1 giúp khuếch đại lực tay nhấn xuống.
    * Bản lề xoay trên đỉnh liên kết cần gạt với ty bơm ($pump\ rod$) truyền chuyển động tịnh tiến lên xuống vào cụm pít-tông trong xi lanh.
  * Vòi rót nước ($Water\ spout$):
    * Đúc vươn ngang ra khỏi thân bơm ở độ cao thuận tiện hứng nước, đầu vòi có đúc mấu cong chịu lực để móc quai xô xách nước trực tiếp.
  * Chân đế mặt bích bắt sàn ($Flange\ mounting\ base$):
    * Chân đế loe rộng dạng xòe có các lỗ đúc sẵn để bắt bu-lông cố định chắc chắn chân bơm vào bệ bê tông miệng giếng, chống rung lắc khi giật cần gạt.
  - **Hình 26.** Thiết bị bơm tay giếng khoan thực tế bằng gang đúc
    - <img src="ch02_water_source_collection/assets/fig_26_p13.jpeg" alt="Hình 26" />
    - **Hình này chứng minh điều gì**
      - Thiết bị bơm tay hoàn chỉnh bằng gang đúc với cần gạt đòn bẩy cong, thân trụ nối bích và chân đế loe cố định nền.
    - **Từ đâu mà thấy được**
      - Nửa trên: Cần gạt cong nối ty bơm qua ngàm vòm; đầu vòi xả có mấu treo xô.
      - Nửa dưới: Khớp nối bích bắt bu-lông ở giữa cột trụ và chân đế loe rộng.

* Chu trình thủy lực pít-tông tác động đơn của bơm tay:
  * Kỳ hút (khi nâng cần gạt lên): Ty bơm đẩy cụm pít-tông đi xuống trong lòng xi lanh, van một chiều trên đĩa pít-tông mở ra để nước tràn lên phía trên pít-tông; đồng thời van chân một chiều ở đáy buồng xi lanh đóng kín.
  * Kỳ đẩy (khi nhấn cần gạt xuống): Ty bơm kéo cụm pít-tông đi lên, van pít-tông đóng lại nâng toàn bộ cột nước phía trên trào ra vòi xả; đồng thời tạo độ chân không trong buồng xi lanh phía dưới, mở van chân hút nước từ giếng dâng lên buồng bơm.
  * Giới hạn thủy lực hút chân không: Chiều cao hút tĩnh thực tế của bơm tay trên mặt đất bị giới hạn bởi áp suất khí quyển, thường không vượt quá $6.0\text{ m} - 7.5\text{ m}$.

## Chương 3: Keo tụ và Tạo bông (Coagulation & Flocculation)


### 3.1 Tổng quan quá trình Keo tụ - Tạo bông

#### 3.1.1 Khái niệm Cốt lõi và Mục tiêu Xử lý Đa Rào cản

##### 3.1.1.1 Định nghĩa và Nguyên lý Keo tụ - Tạo bông
- **Bản chất của quá trình keo tụ (Coagulation)**:
  - Keo tụ là quá trình châm một hoặc nhiều hóa chất vào nước để điều hòa và làm mất độ bền tĩnh điện của các hạt cặn nhỏ.
  - Các hạt cặn lơ lửng và chất keo trong nước thô có kích thước vi mô ($d_p < 1\text{ }\mu\text{m}$).
  - Lực đẩy tĩnh điện ngăn cản các hạt keo tự kết tụ với nhau trong điều kiện tự nhiên.
  - Hóa chất keo tụ làm giảm thế đẩy tĩnh điện và phá vỡ trạng thái cân bằng bền của hệ keo.
- **Bản chất của quá trình tạo bông (Flocculation)**:
  - Tạo bông là quá trình tập hợp vật lý các hạt đã mất độ bền và các sản phẩm kết tủa thành các cụm hạt lớn hơn gọi là bông cặn (flocs).
  - Bông cặn hình thành dưới hai dạng: mạng lưới kết tủa vô định hình (precipitates) hoặc các cụm hạt lơ lửng liên kết (aggregated suspended particles).
  - Kích thước bông cặn tăng trưởng từ thang vi mô lên thang vĩ mô ($d_p = 0{,}1 - 2{,}0\text{ mm}$).
  - Bông cặn có khối lượng và kích thước đủ lớn để lắng nhanh dưới tác dụng của trọng lực hoặc bị giữ lại hoàn toàn trên lớp vật liệu lọc.
- **Mối liên hệ tương hỗ giữa keo tụ và tạo bông**:
  - Keo tụ chuẩn bị điều kiện hóa lý bề mặt cho hạt cặn qua quá trình khuấy trộn nhanh trong thời gian ngắn ($t = 10 - 60\text{ s}$).
  - Tạo bông cung cấp động năng va chạm thủy lực dị thể qua quá trình khuấy trộn chậm trong thời gian dài ($t = 20 - 45\text{ phút}$).
  - Hiệu quả của giai đoạn tạo bông phụ thuộc hoàn toàn vào mức độ mất độ bền đạt được ở giai đoạn keo tụ trước đó.

##### 3.1.1.2 Bốn Mục tiêu Kỹ thuật Thiết kế Đa Rào cản (Design Objectives)
- **Rào cản 1: Loại bỏ các tác nhân vi sinh gây bệnh truyền nhiễm (Infectious agents)**:
  - Nước mặt tự nhiên chứa nhiều mầm bệnh vi sinh vật mang điện tích âm bề mặt:
    - Virus gây bệnh có kích thước siêu vi ($d_p = 0{,}02 - 0{,}08\text{ }\mu\text{m}$).
    - Vi khuẩn đường ruột có kích thước hiển vi ($d_p = 0{,}5 - 2{,}0\text{ }\mu\text{m}$).
    - U nang nguyên sinh động vật *Giardia lamblia* có kích thước ($d_p = 8 - 14\text{ }\mu\text{m}$).
    - Noãn nang *Cryptosporidium parvum* có kích thước ($d_p = 4 - 6\text{ }\mu\text{m}$).
  - Keo tụ giữ chặt các mầm bệnh này vào mạng lưới bông cặn hydroxit kim loại.
  - Quá trình lắng và lọc tiếp sau giúp loại bỏ từ $2{,}0$ đến $3{,}0\text{ }\log_{10}$ lượng vi sinh vật trước công đoạn khử trùng.
- **Rào cản 2: Loại bỏ hợp chất độc hại hấp phụ trên bề mặt hạt (Adsorbed toxic compounds)**:
  - Hạt sét khoáng và chất keo hữu cơ trong nước có diện tích bề mặt riêng rất lớn ($S_s = 10 - 800\text{ m}^2\text{/g}$).
  - Bề mặt hạt hấp phụ mạnh các ion kim loại nặng độc hại:
    - Chì ($\text{Pb}^{2+}$), Cadimi ($\text{Cd}^{2+}$), Thủy ngân ($\text{Hg}^{2+}$) và Asen ($\text{H}_2\text{AsO}_4^- / \text{HAsO}_4^{2-}$).
  - Bề mặt hạt cũng tích tụ các vi ô nhiễm hữu cơ kỵ nước:
    - Thuốc bảo vệ thực vật, hóa chất trừ sâu clo hữu cơ và hydrocarbon thơm đa vòng (PAHs).
  - Keo tụ và tách bông cặn giúp loại bỏ đồng thời các chất độc hại hấp phụ này ra khỏi dòng nước.
- **Rào cản 3: Loại bỏ tiền chất tạo sản phẩm phụ khử trùng (DBP precursors)**:
  - Chất hữu cơ tự nhiên (NOM) trong nước mặt bao gồm axit humic và axit fulvic có khối lượng phân tử từ $1000$ đến $50000\text{ Da}$.
  - NOM tác dụng với chất khử trùng clo tự do hình thành các sản phẩm phụ khử trùng gây ung thư:
    - Trihalomethane tổng số ($\text{TTHMs}$) gồm $\text{CHCl}_3, \text{CHBrCl}_2, \text{CHBr}_2\text{Cl}, \text{CHBr}_3$.
    - Axit haloacetic ($\text{HAA}_5$) gồm $\text{CH}_2\text{ClCOOH}, \text{CHCl}_2\text{COOH}, \text{CCl}_3\text{COOH}, \text{CH}_2\text{BrCOOH}, \text{CHBr}_2\text{COOH}$.
  - Keo tụ tăng cường (enhanced coagulation) kết tủa và bẫy các phân tử NOM kỵ nước có trọng lượng phân tử lớn, ngăn ngừa rủi ro tạo DBPs.
- **Rào cản 4: Nâng cao cảm quan và độ ngon miệng của nước sạch (Palatability & aesthetics)**:
  - Axit humic hòa tan tạo ra độ màu thực của nước nguồn theo thang đo bạch kim - coban ($\text{Pt-Co}$).
  - Phù sa lơ lửng, hạt keo sét và oxyhydroxyt sắt - mangan tạo ra độ đục biểu kiến cao.
  - Keo tụ và tạo bông hạ độ đục từ hàng trăm $\text{NTU}$ xuống dưới ngưỡng quy chuẩn $\le 2\text{ NTU}$ (theo QCVN 01-1:2018/BYT) và đạt $\le 0{,}1 - 0{,}3\text{ NTU}$ sau bể lọc cát.
  - Quá trình khử sạch triệt để độ đục, độ màu, vị lạ và mùi đất nhằm đem lại chất lượng nước trong lành, ngon miệng cho người sử dụng.

---

#### 3.1.2 Vị trí Quá trình trong Dây chuyền Công nghệ Xử lý Nước cấp

##### 3.1.2.1 Dây chuyền Xử lý Nước Cấp Truyền thống (Conventional Treatment Train)
- **Cấu trúc công nghệ đa cấp của dây chuyền truyền thống**:
  - Keo tụ và tạo bông là trung tâm xử lý hóa lý của toàn bộ nhà máy xử lý nước mặt:
    $$\text{Nước mặt thô} \rightarrow \text{Tiền oxy hóa} \rightarrow \text{Khuấy nhanh (Flash mix)} \rightarrow \text{Tạo bông} \rightarrow \text{Lắng trọng lực} \rightarrow \text{Lọc cát} \rightarrow \text{Khử trùng} \rightarrow \text{Nước sạch}$$
  - Hóa chất keo tụ vô cơ ($\text{Al}_2(\text{SO}_4)_3, \text{FeCl}_3, \text{PAC}$) châm trực tiếp vào họng bể khuấy nhanh thủy lực hoặc cơ học.
  - Bể tạo bông ba ngăn với cánh khuấy guồng quay chậm phát triển dần kích thước bông cặn.
  - Bể lắng loại bỏ hơn $85 - 95\%$ tải lượng cặn bông trước khi đưa nước sang bể lọc hạt.
  - Polymer trợ lọc châm bổ sung trước bể lọc hạt để gia cường độ bền liên kết của vi bông cặn.
- **Sơ đồ công nghệ minh họa cấu trúc dây chuyền xử lý nước cấp và các nhánh công nghệ thay thế**:
  - **Hình 1.** Sơ đồ dây chuyền công nghệ xử lý nước cấp ứng dụng quá trình keo tụ
    - <img src="ch03_coagulation_flocculation/assets/fig_01_p2.png" alt="Hình 1" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu hình xử lý truyền thống cùng hai nhánh công nghệ rút gọn: lọc tiếp xúc (bỏ qua tạo bông, lắng) và lọc trực tiếp (bỏ qua lắng).
    - **Từ đâu mà thấy được**
      - Đường dòng chính đi qua liên tục các bể đơn vị, kết hợp hai đường nét đứt bypass tạo bông và bypass lắng dẫn thẳng đến bể lọc hạt.

##### 3.1.2.2 Cấu hình Lọc Trực tiếp và Lọc Tiếp xúc (Direct & Contact Filtration)
- **Dây chuyền lọc trực tiếp (Direct Filtration)**:
  - Dây chuyền bỏ qua hoàn toàn công đoạn lắng trọng lực (Bypass sedimentation):
    $$\text{Nước thô} \rightarrow \text{Khuấy nhanh} \rightarrow \text{Bể tạo bông ngắn} \rightarrow \text{Bể lọc hạt (Granular filtration)}$$
  - Thời gian tạo bông rút ngắn còn $5 - 15\text{ phút}$ với gradient vận tốc $G = 30 - 50\text{ s}^{-1}$ để hình thành các vi bông cặn ($d_p = 20 - 50\text{ }\mu\text{m}$).
  - Áp dụng hiệu quả khi nước thô có độ đục thấp ($\text{Turbidity} < 10 - 15\text{ NTU}$) và độ màu thấp ($\text{Color} < 15 - 20\text{ TCU}$).
  - Giảm thiểu diện tích xây dựng trạm và tiết kiệm đáng kể chi phí đầu tư bể lắng.
- **Dây chuyền lọc tiếp xúc (Contact Filtration / In-line Coagulation)**:
  - Dây chuyền loại bỏ cả bể tạo bông lẫn bể lắng (Bypass flocculation & sedimentation):
    $$\text{Nước thô} \rightarrow \text{Khuấy nhanh hóa chất} \rightarrow \text{Bể lọc hạt}$$
  - Hóa chất keo tụ châm trực tiếp vào đường ống áp lực ngay trước lớp vật liệu lọc hạt.
  - Quá trình làm mất độ bền, va chạm và giữ dính cặn diễn ra trực tiếp bên trong các khe rỗng của tầng lọc cát - than anthrasit.
  - Áp dụng đối với nguồn nước chất lượng rất cao, độ đục ổn định quanh năm ($\text{Turbidity} < 5\text{ NTU}$) và không có tảo nở hoa.

##### 3.1.2.3 Phân tách Dòng Xử lý Nước và Dòng Quản lý Bùn Cặn Thải (Residuals Management)
- **Dòng xử lý nước sạch (Liquid processing)**:
  - Dòng chính vận chuyển chất lỏng từ trạm thu nước mặt thô qua các công trình phản ứng đến bể chứa nước sạch và mạng lưới tiêu thụ.
  - Mục tiêu duy trì chất lượng nước đạt chuẩn ăn uống và áp lực thủy lực ổn định trên mạng lưới cấp nước.
- **Dòng quản lý bùn cặn và nước rửa lọc (Residuals processing and management)**:
  - Bùn cặn lắng (Settled solids): xả định kỳ từ đáy phễu bể lắng trọng lực với hàm lượng cặn khô $C_s = 0{,}5 - 2{,}0\%$.
  - Nước rửa ngược bể lọc (Waste washwater): phát sinh gián đoạn từ chu trình rửa ngược tầng lọc hạt cát, chứa vi bông cặn và hạt lơ lửng.
  - Dòng thải cặn đưa về bể nén bùn trọng lực, hồ làm khô hoặc máy ép bùn cơ học để thu hồi nước trong tuần hoàn và chôn lấp bánh bùn khô an toàn.

---

#### 3.1.3 Động học Bốn Giai đoạn Nối tiếp trong Keo tụ - Tạo bông

##### 3.1.3.1 Trình tự Bốn Bước Động học Hóa lý Kế tiếp (Sequential Steps)
- **Đặc trưng động học của quá trình**:
  - Keo tụ là một chuỗi phản ứng liên hoàn phức tạp, kết hợp chặt chẽ giữa các phản ứng hóa học dị thể và quá trình truyền khối thủy động học.
  - Quá trình diễn ra tuần tự qua bốn giai đoạn kế tiếp nhau không thể tách rời:
- **Giai đoạn 1: Biến đổi hóa học của chất keo tụ (Coagulant transformation)**:
  - Muối nhôm hoặc sắt hòa tan giải phóng cation kim loại tự do ($\text{Al}^{3+}, \text{Fe}^{3+}$).
  - Cation kim loại bị hydrat hóa tức thời tạo phức bát diện $[\text{Al}(\text{H}_2\text{O})_6]^{3+}$ hoặc $[\text{Fe}(\text{H}_2\text{O})_6]^{3+}$.
  - Phản ứng thủy phân liên tiếp giải phóng ion hydronium $\text{H}_3\text{O}^+$ diễn ra trong khoảng thời gian siêu ngắn ($10^{-4} - 10^{-1}\text{ s}$):
    $$[\text{Al}(\text{H}_2\text{O})_6]^{3+} + \text{H}_2\text{O} \rightleftharpoons [\text{Al}(\text{H}_2\text{O})_5(\text{OH})]^{2+} + \text{H}_3\text{O}^+$$
    $$[\text{Al}(\text{H}_2\text{O})_5(\text{OH})]^{2+} + \text{H}_2\text{O} \rightleftharpoons [\text{Al}(\text{H}_2\text{O})_4(\text{OH})_2]^+ + \text{H}_3\text{O}^+$$
  - Các cấu tử monome trùng hợp tạo thành các phức hydroxo cation đa nhân ($[\text{Al}_2(\text{OH})_2]^{4+}, [\text{Al}_{13}\text{O}_4(\text{OH})_{24}(\text{H}_2\text{O})_{12}]^{7+}$) và kết tủa hydroxit vô định hình $\text{Al(OH)}_3\text{(s)}$.
- **Giai đoạn 2: Hấp phụ các cấu tử lên bề mặt hạt keo (Uptake of adsorbed species)**:
  - Các ion phức hydroxo kim loại mang điện tích dương khuếch tán cực nhanh qua lớp biên thủy động của hạt keo.
  - Thời gian hấp phụ đặc hiệu lên bề mặt tích điện âm của hạt sét diễn ra trong khoảng $0{,}01 - 0{,}1\text{ s}$.
  - Tương tác tĩnh điện và liên kết phối trí hình thành liên kết bền vững giữa chất hấp phụ và bề mặt hạt keo.
- **Giai đoạn 3: Làm mất độ bền hạt keo (Particle destabilization)**:
  - Lớp điện tích kép (EDL) bị nén mạnh khi lực ion của dung dịch tăng cao.
  - Sự hấp phụ của cation đa nhân làm giảm trị số điện thế Zeta ($\zeta$) từ vùng tích điện âm sâu ($-30\text{ mV}$ đến $-45\text{ mV}$) về điểm đẳng điện ($\zeta \approx 0\text{ mV}$).
  - Lực đẩy tĩnh điện giảm xuống dưới ngưỡng tương tác của lực hút phân tử Van der Waals, phá vỡ hoàn toàn độ bền hệ keo.
- **Giai đoạn 4: Va chạm liên hạt hình thành bông cặn (Interparticle collisions)**:
  - Các hạt đã mất độ bền di chuyển và va chạm với nhau tạo thành các liên kết kết tụ bền vững.
  - Cơ chế va chạm nhiệt Brown điều khiển hạt mịn $d_p < 1\text{ }\mu\text{m}$ (keo tụ perikinetic).
  - Gradient vận tốc dòng chảy $G$ điều khiển va chạm giữa các hạt lớn $d_p > 1\text{ }\mu\text{m}$ (keo tụ orthokinetic).
  - Tần số va chạm tỷ lệ thuận với gradient vận tốc $G$ và kích thước hạt cặn, phát triển thành các bông cặn vĩ mô.
- **Thử nghiệm cốc thủy tinh trực quan hóa diễn biến hóa lý qua bốn giai đoạn**:
  - **Hình 2.** Diễn tiến bốn giai đoạn hóa lý của quá trình keo tụ - tạo bông trong thử nghiệm cốc
    - <img src="ch03_coagulation_flocculation/assets/fig_02_p3.jpeg" alt="Hình 2" />
    - **Hình này chứng minh điều gì**
      - Bốn giai đoạn biến đổi hóa lý diễn ra tuần tự từ châm phèn khuấy nhanh đến tạo bông cặn và phân tách pha lỏng - rắn hoàn chỉnh.
    - **Từ đâu mà thấy được**
      - Dãy bốn cốc thủy tinh ghi nhận trạng thái nước nguồn đục ban đầu, ống hút châm hóa chất keo tụ, xuất hiện cụm bông cặn lơ lửng, và bùn lắng tách lớp ở đáy cốc.

##### 3.1.3.2 Phân bố Không gian và Thời gian trong Khuấy nhanh và Tạo bông
- **Giai đoạn khuấy trộn nhanh (Rapid Mixing / Flash Mix)**:
  - Nơi diễn ra: Bể khuấy nhanh cơ học hoặc thiết bị trộn tĩnh trên đường ống (In-line static mixer).
  - Cơ chế chủ đạo: Biến đổi chất keo tụ, tương tác chất hấp phụ - chất keo tụ và phá vỡ độ bền hạt keo diễn ra ngay lập tức trong và sau khi phân tán hóa chất.
  - Cường độ khuấy: Gradient vận tốc rất lớn ($G = 700 - 1000\text{ s}^{-1}$) nhằm phân tán phân tử hóa chất đồng đều trong thể tích nước trước khi phản ứng thủy phân kết tủa kết thúc.
  - Thời gian lưu nước: Cực ngắn ($t = 10 - 60\text{ s}$), tránh hiện tượng khuấy quá lâu làm phá vỡ các mầm vi bông vừa mới định hình.
- **Giai đoạn tạo bông chậm (Slow Flocculation)**:
  - Nơi diễn ra: Bể tạo bông có vách ngăn ziczac hoặc bể cánh khuấy quay chậm nhiều ngăn nối tiếp.
  - Cơ chế chủ đạo: Va chạm giữa các hạt đã mất độ bền nhằm phát triển cụm bông cặn vĩ mô diễn ra với hiệu quả cao nhất tại đây.
  - Cường độ khuấy: Giảm dần theo chiều dòng chảy ($G = 70 \rightarrow 40 \rightarrow 20\text{ s}^{-1}$) với tích số Camp $Gt = 10^4 - 10^5$.
  - Thời gian lưu nước: Đủ dài ($t = 20 - 45\text{ phút}$) để tối đa hóa số lần va chạm hiệu quả giữa các hạt mà không gây ra ứng suất cắt làm vỡ bông cặn.

##### 3.1.3.3 Mô phỏng Thực nghiệm Diễn tiến Bốn Trạng thái trong Cốc Thí nghiệm
- **Trạng thái 1: Nước mặt thô tự nhiên (Surface water)**:
  - Cốc chứa nước thô có độ đục cao và màu vàng nhạt đặc trưng của phù sa, sét khoáng và chất mùn humic.
  - Hệ keo duy trì trạng thái phân tán ổn định vô hạn định nhờ lực đẩy tĩnh điện giữa các hạt cùng điện tích âm.
- **Trạng thái 2: Châm hóa chất keo tụ và khuấy nhanh (Coagulation)**:
  - Ống nhỏ giọt đưa liều lượng dung dịch chất keo tụ tối ưu vào cốc nước thô dưới tác động khuấy trộn mãnh liệt.
  - Phản ứng thủy phân ion kim loại diễn ra tức thời, giải phóng các cation đa nhân làm mất độ bền hạt keo và tạo các tâm nhân kết tủa vi mô.
- **Trạng thái 3: Tạo bông cặn vĩ mô (Flocculation)**:
  - Cường độ khuấy hạ chậm dần, tạo điều kiện cho các hạt cặn va chạm và kết dính liên tục.
  - Xuất hiện vô số bông cặn kích thước lớn ($0{,}5 - 2{,}0\text{ mm}$), màu nâu cam đậm, lơ lửng phân bố đều trong toàn bộ thể tích cốc.
- **Trạng thái 4: Lắng trọng lực tách pha hoàn tất (Sedimentation)**:
  - Ngừng khuấy trộn, các bông cặn nặng nhanh chóng chìm xuống đáy cốc tạo thành lớp bùn lắng cô đặc.
  - Phần nước bên trên trở nên trong suốt, độ đục và độ màu giảm triệt để, chứng minh sự thành công của chuỗi công nghệ keo tụ - tạo bông.
- **Dãy cốc thí nghiệm minh chứng trực quan cho bốn bước công nghệ chuyển hóa từ nước mặt đến lắng trong**:
  - **Hình 3.** Sơ đồ bốn bước chuyển hóa từ Nước mặt qua Keo tụ, Tạo bông đến Lắng cặn
    - <img src="ch03_coagulation_flocculation/assets/fig_03_p4.jpeg" alt="Hình 3" />
    - **Hình này chứng minh điều gì**
      - Thể hiện trực quan bốn bước chuyển hóa vật lý: nước mặt nguyên khai, phản ứng keo tụ, tạo mạng lưới bông cặn, và phân tách pha lắng trọng lực.
    - **Từ đâu mà thấy được**
      - Chuỗi bốn cốc nghiệm tương ứng với bốn trạng thái: nước thô màu đục, cốc châm phèn khuấy trộn, cốc tạo bông cặn phân tán dày đặc, và cốc lắng tạo lớp bùn đáy dày cùng lớp nước trong.

### 3.2 Cơ sở lý thuyết quá trình Keo tụ

#### 3.2.1 Bản chất hạt keo và độ bền hệ keo

##### 3.2.1.1 Độ bền hệ keo và nguồn gốc hạt keo trong nước tự nhiên

- Trạng thái bền vững của hệ keo trong nước tự nhiên (*Colloidal Stability*):
  - Các hạt cặn lơ lửng và hạt keo duy trì trạng thái phân tán bền vững nhờ sự cân bằng giữa hai hệ lực đối kháng:
    - Lực đẩy tĩnh điện (*Electrostatic repulsion force*) phát sinh giữa các hạt cùng mang điện tích bề mặt.
    - Lực hút phân tử van der Waals (*Attractive van der Waals forces*) tác động ở cự ly ngắn giữa các hạt.
  - Đa số các hạt cặn và hạt keo trong nguồn nước tự nhiên mang điện tích âm thuần (*net negative charge*).
  - Lực đẩy tĩnh điện là cơ chế chủ đạo ngăn cản các hạt keo tiến lại gần nhau và duy trì độ bền của hệ keo (*stabilization*).
  - Mục tiêu cốt lõi của quá trình keo tụ là phá vỡ thế cân bằng này để chuyển từ trạng thái bền vững sang trạng thái mất độ bền (*destabilization*), thúc đẩy các hạt kết cụm lại với nhau.
- Nguồn gốc phát sinh của các hạt keo trong nước thô (*Origin of Colloids*):
  - Hạt keo là các hạt phân tán có kích thước nhỏ hơn $1\ \mu\text{m}$ (trong các tài liệu kỹ thuật có thể quy ước hạt lơ lửng mịn $< 1\text{ mm}$), có tính bền vững cao trong môi trường nước.
  - Hạt keo xuất hiện trong hầu hết các nguồn nước mặt và nước ngầm tự nhiên, là tác nhân chính gây ra độ đục (*turbidity*), màu sắc (*color*), mùi (*odor*) và vị (*taste*) khó chịu.
  - Các hạt keo phân loại theo ba nguồn gốc xuất xứ chính:
    - Nguồn gốc khoáng chất (*Mineral origin*): bột phù sa (*silt*), khoáng sét (*clay*), hạt silica ($\text{SiO}_2$), các hợp chất hydroxide và muối kim loại không tan.
    - Nguồn gốc hữu cơ (*Organic origin*): axit humic và axit fulvic sinh ra từ quá trình phân hủy xác thực vật và động vật, phẩm màu tự nhiên (*colorants*), chất hoạt động bề mặt (*surfactants*).
    - Nguồn gốc sinh học (*Biological origin*): vi sinh vật gây bệnh hoặc không gây bệnh, bao gồm vi khuẩn (*bacteria*), sinh vật phù du (*plankton*), tế bào tảo (*algae*) và virus.
  - **Hình 4.** Nguồn gốc và phân loại các dạng hạt keo trong nước thô (Slide 7)
    - <img src="ch03_coagulation_flocculation/assets/fig_04_p7.png" alt="Hình 4" />
    - **Hình này chứng minh điều gì**
      - Xác định ba nguồn gốc chính hình thành hạt keo trong tự nhiên gồm khoáng chất, hữu cơ và sinh học.
    - **Từ đâu mà thấy được**
      - Danh mục Mineral liệt kê silt, clay, silica; nhóm Organic chỉ axit humic/fulvic; nhóm Biological gồm vi khuẩn, tảo, virus.
  - **Hình 5.** Thang đo kích thước hạt từ cấp độ ion đến vĩ mô (Slide 7)
    - <img src="ch03_coagulation_flocculation/assets/fig_05_p7.png" alt="Hình 5" />
    - **Hình này chứng minh điều gì**
      - Phân chia toàn bộ phổ kích thước tạp chất trong nước từ $0{,}0001\ \mu\text{m}$ đến $1000\ \mu\text{m}$.
    - **Từ đâu mà thấy được**
      - Trục Micron Scale phân định 5 cấp độ: Macro, Micro, Macro-molecular, Molecular và Ionic.
  - **Hình 6.** Nguồn gốc và các tác nhân tạo độ đục trong hệ keo (Slide 8)
    - <img src="ch03_coagulation_flocculation/assets/fig_06_p8.png" alt="Hình 6" />
    - **Hình này chứng minh điều gì**
      - Cung cấp cơ sở nhận diện các tác nhân gây đục, màu, mùi trong nước từ xác sinh vật và chất khoáng.
    - **Từ đâu mà thấy được**
      - Nội dung bảng chữ chỉ rõ các thành phần khoáng sét, sản phẩm phân hủy hữu cơ và vi sinh vật phù du.

##### 3.2.1.2 Phân loại hạt theo kích thước và quy luật lắng tĩnh

- Phân loại tạp chất theo dải kích thước hình học (*Particles by Dimension*):
  - Tạp chất dạng vĩ mô (*Macro particles*, kích thước $> 100\ \mu\text{m}$): hạt cát (*sand*), hạt than hoạt tính (*GAC*), sợi tóc (*hair*), phấn hoa (*pollen*).
  - Tạp chất dạng vi mô (*Micro particles*, kích thước $1 - 100\ \mu\text{m}$): tế bào hồng cầu (*red blood*), tế bào nấm men (*yeast cells*), tảo (*algae*), u nang *Giardia* ($8 - 14\ \mu\text{m}$), bào nang *Cryptosporidium* ($4 - 6\ \mu\text{m}$), vi khuẩn (*bacteria*, $0{,}5 - 3\ \mu\text{m}$).
  - Tạp chất dạng đại phân tử và hạt keo (*Macromolecular / Colloidal*, kích thước $0{,}001 - 1\ \mu\text{m}$ tương đương $1 - 1000\text{ nm}$): hạt keo tự nhiên (*colloids*), sợi amiăng (*asbestos*), silica keo (*colloidal silica*), virus ($0{,}01 - 0{,}1\ \mu\text{m}$), nội độc tố và chất gây sốt (*endotoxin / pyrogen*).
  - Tạp chất dạng phân tử (*Molecular*, kích thước $0{,}0001 - 0{,}001\ \mu\text{m}$ tương đương $0{,}1 - 1\text{ nm}$): phân tử đường (*sugar*), thuốc bảo vệ thực vật và diệt cỏ (*pesticides / herbicides*), đại phân tử hữu cơ.
  - Tạp chất dạng ion (*Ionic*, kích thước $< 0{,}0001\ \mu\text{m}$ tương đương $< 0{,}1\text{ nm}$): muối hòa tan trong nước (*aqueous salts*), ion kim loại hòa tan (*metal ions*), bán kính nguyên tử (*atomic radius*).
  - Ranh giới kỹ thuật: các hạt có kích thước lớn hơn $0{,}1 - 1\ \mu\text{m}$ được xếp vào nhóm hạt lơ lửng (*suspended particles*); các cấu tử nhỏ hơn $0{,}1\ \mu\text{m}$ được xếp vào nhóm chất hòa tan và keo mịn (*dissolved particles*).
  - **Hình 7.** Phân loại hạt trong nước theo dải kích thước micromet (Slide 8)
    - <img src="ch03_coagulation_flocculation/assets/fig_07_p8.png" alt="Hình 7" />
    - **Hình này chứng minh điều gì**
      - Định vị kích thước hạt keo ($0{,}001 - 1\ \mu\text{m}$) nằm chuyển tiếp giữa hạt lơ lửng và chất hòa tan.
    - **Từ đâu mà thấy được**
      - Khối chữ Colloids trải dài từ $1\text{ nm}$ đến $1\ \mu\text{m}$, tiếp giáp vi khuẩn ở cận trên và virus ở cận dưới.
- Vận tốc lắng trọng lực và thời gian lắng tĩnh của các hạt trong nước (*Settling Velocities of Particles in Water*):
  - Vận tốc lắng trọng lực $v_s$ suy giảm nghiêm trọng khi đường kính hạt $d$ thu nhỏ theo quy luật định luật Stokes ($v_s \propto d^2$).
  - Bảng định lượng vận tốc lắng và thời gian rơi tự do qua quãng đường chiều sâu $1\text{ m}$ trong nước tĩnh ở $20^\circ\text{C}$:

| Loại hạt (*Particle Type*) | Đường kính hạt $d$ ($\text{mm}$) | Vận tốc lắng $v_s$ ($\text{mm/s}$) | Thời gian lắng $1\text{ m}$ tĩnh |
| :--- | :--- | :--- | :--- |
| Cát thô (*Large sand*) | $10$ | $1000$ | $1\text{ giây}$ |
| Cát trung bình (*Medium sand*) | $1$ | $100$ | $10\text{ giây}$ |
| Cát mịn (*Small sand*) | $0{,}1$ | $8$ | $2\text{ phút}$ |
| Bột / Cặn bùn (*Sludge / Silt*) | $0{,}01$ ($10\ \mu\text{m}$) | $0{,}154$ | $2\text{ giờ}$ |
| Hạt sét lớn (*Large clay*) | $0{,}001$ ($1\ \mu\text{m}$) | $0{,}00154$ | $7\text{ ngày}$ |
| Hạt sét nhỏ (*Small clay*) | $0{,}0001$ ($0{,}1\ \mu\text{m}$) | $0{,}0000154$ | $2\text{ năm}$ |
| Hạt keo (*Colloids*) | $0{,}00001$ ($0{,}01\ \mu\text{m} = 10\text{ nm}$) | $0{,}000000154$ | $200\text{ năm}$ |

- Tính tất yếu của việc châm hóa chất keo tụ (*Need for Chemical Coagulants*):
  - Các hạt lơ lửng kích thước nhỏ, hạt keo ($d < 1\ \mu\text{m}$) và các hợp chất hòa tan không thể tự lắng trong thời gian lưu thủy lực thực tế của công trình lắng (thường từ $1{,}5$ đến $3\text{ giờ}$).
  - Do thời gian tự lắng kéo dài từ nhiều ngày đến 200 năm, hệ keo được xem là hoàn toàn bền vững về mặt động học và nhiệt động lực học.
  - Bắt buộc phải bổ sung các hóa chất keo tụ chuyên dụng để phá vỡ lớp điện tích, tạo điều kiện cho các hạt kết cụm thành bông cặn lớn có vận tốc lắng đủ cao để tách loại cơ học.

---

#### 3.2.2 Lớp điện tích kép và thế Zeta

##### 3.2.2.1 Cấu trúc lớp điện tích kép (EDL) và thế Zeta

- Cấu trúc hai lớp của lớp điện tích kép (*Electrical Double Layer - EDL*):
  - Hạt keo mang điện tích âm cố định trên bề mặt do ba nguyên nhân: sự phân ly của các nhóm chức hóa học bề mặt, sự hấp phụ chọn lọc các ion âm từ nước, hoặc sự thay thế đồng hình trong mạng tinh thể khoáng sét.
  - Để trung hòa điện tích âm bề mặt, các ion dương đối nghịch (*positive counterions*) từ dung dịch bị hút về phía bề mặt hạt, tạo nên lớp điện tích kép gồm hai tầng đồng tâm:
    - 1. Tầng cố định Stern (*Fixed charge / Stern layer*): lớp ion đối bám chặt sát bề mặt hạt dưới tác dụng của lực tĩnh điện mạnh và lực hấp phụ hóa học, có bề dày khoảng $0{,}5\text{ nm}$. Điện thế suy giảm tuyến tính nhanh chóng từ thế bề mặt Nernst (*Nernst potential*) xuống thế Stern / Helmholtz (*Helmholtz potential*).
    - 2. Tầng khuếch tán Gouy-Chapman (*Diffuse ion layer*): các ion đối chịu liên kết lỏng lẻo hơn, mật độ ion dương giảm dần theo hàm mũ khi ra xa hạt cho đến khi đạt trạng thái cân bằng với dung dịch khối (*bulk solution*), có bề dày mở rộng lên đến khoảng $30\text{ nm}$.
  - Mặt phẳng trượt (*Shear plane / Sliding surface*):
    - Ranh giới hình học quy ước phân tách giữa lớp chất lỏng và ion bám dính di chuyển cùng hạt keo khi có chuyển động tương đối và khối dung dịch nước xung quanh đứng yên.
    - Mặt phẳng trượt nằm ở phần bên trong của lớp khuếch tán, cách bề mặt hạt một khoảng nhỏ hơn bề dày tổng thể của lớp khuếch tán.
  - Khái niệm và ý nghĩa của thế Zeta ($\zeta$, *Zeta Potential*):
    - Thế Zeta là điện thế đo được tại chính mặt phẳng trượt (*shear plane*).
    - Đại lượng thế Zeta phản ánh trực tiếp cường độ của lực đẩy tĩnh điện giữa các hạt keo lơ lửng trong môi trường nước.
    - Hạt keo tự nhiên thường có thế Zeta mang giá trị âm lớn (từ $-15\text{ mV}$ đến $-40\text{ mV}$), tạo rào cản thế năng năng lượng ngăn cản sự kết dính hạt.
  - **Hình 8.** Cấu trúc lớp điện tích kép và biến thiên điện thế tĩnh điện (Slide 11)
    - <img src="ch03_coagulation_flocculation/assets/fig_08_p11.jpeg" alt="Hình 8" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự suy giảm điện thế từ bề mặt hạt qua tầng Stern ($0{,}5\text{ nm}$) đến tầng khuếch tán ($30\text{ nm}$).
    - **Từ đâu mà thấy được**
      - Đồ thị điện thế định vị thế Nernst tại bề mặt hạt, thế Helmholtz tại Stern layer và thế Zeta tại mặt phẳng trượt.
  - **Hình 9.** Công thức Smoluchowski và thông số tính toán thế Zeta (Slide 11)
    - <img src="ch03_coagulation_flocculation/assets/fig_09_p11.png" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Cung cấp phương trình toán học tính thế Zeta từ độ nhớt dung dịch và độ linh động điện di.
    - **Từ đâu mà thấy được**
      - Công thức $\zeta = \frac{4\pi\eta}{\varepsilon} \cdot U \cdot 300 \cdot 300 \cdot 1000$ kèm danh mục giải thích ký hiệu $U, v, V, L$.
  - **Hình 10.** Sơ đồ chuyển động điện di của hạt keo trong bình đo (Slide 11)
    - <img src="ch03_coagulation_flocculation/assets/fig_10_p11.png" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Minh họa hạt keo âm di chuyển về cực dương và sự hình thành mặt phẳng trượt Sliding surface.
    - **Từ đâu mà thấy được**
      - Mũi tên Migration hướng về Positive electrode; cấu trúc hạt gồm ion fixed bed và ion diffusion layer.

##### 3.2.2.2 Phương pháp điện di và công thức tính thế Zeta

- Nguyên lý đo điện di hạt keo (*Microelectrophoresis Principle*):
  - Chiếu điện trường một chiều với hiệu điện thế $V$ qua buồng đo chứa mẫu nước có hai điện cực đặt cách nhau khoảng cách $L$.
  - Cường độ điện trường áp đặt lên dung dịch:
    $$E = \frac{V}{L} \quad (\text{V/cm})$$
  - Hạt keo mang điện tích âm cùng lớp vỏ solvat hóa bên trong mặt phẳng trượt sẽ chuyển dịch (*migration*) có hướng về phía cực dương (*positive electrode*) với vận tốc trôi không đổi $v$ ($\text{cm/s}$).
  - Độ linh động điện di của hạt keo ($U$, *Electrophoretic Mobility*):
    $$U = \frac{v}{E} = \frac{v}{V/L} \quad \left(\frac{\text{cm/s}}{\text{V/cm}} = \frac{\text{cm}^2}{\text{V}\cdot\text{s}}\right)$$
- Công thức Smoluchowski tính thế Zeta:
  - Giá trị thế Zeta ($\zeta$) tính theo hệ đơn vị thực nghiệm:
    $$\zeta = \frac{4\pi \eta}{\varepsilon} \times U \times 300 \times 300 \times 1000$$
    Trong đó:
    - $\zeta$: Thế Zeta của hạt keo tại mặt phẳng trượt, đơn vị $\text{mV}$.
    - $\eta$: Độ nhớt tuyệt đối của dung dịch (*Viscosity of Solution*), đơn vị $\text{Poise}$ ($\text{g}/(\text{cm}\cdot\text{s})$) hoặc $\text{Pa}\cdot\text{s}$.
    - $\varepsilon$: Hằng số điện môi của môi trường phân tán (*Dielectric Constant*, đối với nước ở $20^\circ\text{C}$, $\varepsilon \approx 80{,}4$).
    - $U = \frac{v}{V/L}$: Độ linh động điện di của hạt keo (*Electrophoretic Mobility*), đơn vị $\text{cm}^2/(\text{V}\cdot\text{s})$.
    - $v$: Vận tốc di chuyển của hạt keo (*Speed of Particle*), đơn vị $\text{cm/s}$.
    - $V$: Hiệu điện thế áp đặt giữa hai điện cực (*Voltage*), đơn vị $\text{V}$.
    - $L$: Khoảng cách hình học giữa hai cực điện (*Distance of Electrode*), đơn vị $\text{cm}$.
    - Hệ số thực nghiệm $300 \times 300 \times 1000 = 9 \times 10^7$ là thừa số chuyển đổi thứ nguyên giữa hệ tĩnh điện CGS (statvolt) sang hệ SI/thực hành ($\text{V}$ và $\text{mV}$).
- Tiêu chí keo tụ hiệu quả theo thế Zeta:
  - Khi thế Zeta âm lớn ($\zeta < -30\text{ mV}$), hệ keo phân tán rất bền vững.
  - Khi châm hóa chất làm suy giảm giá trị tuyệt đối của thế Zeta về dải tối ưu từ $-5\text{ mV}$ đến $+5\text{ mV}$ (gần bằng $0$), lực đẩy tĩnh điện bị triệt tiêu, cho phép lực hút van der Waals phát huy tác dụng làm các hạt dính kết lại với nhau.
  - **Hình 11.** Cấu trúc phân lớp ion của lớp điện tích kép xung quanh hạt keo (Slide 12)
    - <img src="ch03_coagulation_flocculation/assets/fig_11_p12.jpeg" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Tái khẳng định vị trí tương đối giữa lớp cố định Stern và lớp khuếch tán chứa mặt phẳng trượt.
    - **Từ đâu mà thấy được**
      - Chiều dày lớp kép mở rộng từ khoảng cách $0{,}5\text{ nm}$ đến $30\text{ nm}$ tính từ bề mặt hạt keo.
  - **Hình 12.** Phương trình giải tích xác định thế Zeta theo độ linh động điện di (Slide 12)
    - <img src="ch03_coagulation_flocculation/assets/fig_12_p12.png" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Xác lập biểu thức định lượng tính thế Zeta từ số đo vận tốc hạt và gradient điện áp buồng đo.
    - **Từ đâu mà thấy được**
      - Đẳng thức $\zeta = \frac{4\pi\eta}{\varepsilon} \cdot U \cdot 300 \cdot 300 \cdot 1000$ với định nghĩa $U = v/(V/L)$.
  - **Hình 13.** Hiện tượng di chuyển điện di của hạt keo giữa hai điện cực (Slide 12)
    - <img src="ch03_coagulation_flocculation/assets/fig_13_p12.png" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Mô tả trực quan quá trình điện di của hạt keo âm trong dung dịch điện ly dưới điện trường ngoài.
    - **Từ đâu mà thấy được**
      - Hạt keo cùng lớp ion liên kết trượt trên ranh giới Sliding surface di chuyển hướng tới Positive electrode.

---

#### 3.2.3 Bốn cơ chế keo tụ làm mất độ bền hạt keo

##### 3.2.3.1 Tổng quan bốn cơ chế keo tụ và giản đồ độ hòa tan Al(III) / Fe(III)

- Bốn cơ chế làm mất độ bền hệ keo trong xử lý nước cấp (*Four Destabilization Mechanisms*):
  - 1. Nén lớp điện tích kép (*Compression of the Electrical Double Layer*).
  - 2. Hấp phụ và trung hòa điện tích (*Adsorption and Charge Neutralization*).
  - 3. Hấp phụ và tạo cầu nối liên kết giữa các hạt (*Adsorption and Interparticle Bridging*).
  - 4. Bẫy cuộn trong khối kết tủa hay keo tụ bông quét (*Enmeshment in a Precipitate, or "Sweep Floc"*).
- Giản đồ cân bằng pha và độ hòa tan của $\text{Al(III)}$ và $\text{Fe(III)}$ ở $25^\circ\text{C}$ (*Solubility Diagrams*):
  - Giản đồ biểu diễn nồng độ tổng của kim loại ở trạng thái cân bằng với pha rắn kết tủa vô định hình: $\text{Al(OH)}_3(\text{s})$ vô định hình hoặc $\text{Fe(OH)}_3(\text{s})$ vô định hình.
  - Các cấu tử nhôm đơn nhân (*Mononuclear Aluminum Species*):
    - Ở $\text{pH} < 5$: tồn tại chủ yếu ở dạng cation hòa tan $\text{Al}^{3+}$ và $\text{Al(OH)}^{2+}$.
    - Ở dải $\text{pH} \approx 6{,}0 - 8{,}0$: nồng độ hòa tan của nhôm đạt cực tiểu ($\approx 10^{-6}\text{ mol/L}$ tại $\text{pH} \approx 6{,}3$); pha rắn $\text{Al(OH)}_3(\text{s})$ kết tủa mạnh mẽ.
    - Ở $\text{pH} > 8$: kết tủa tan trở lại tạo thành anion aluminate $\text{Al(OH)}_4^-$.
  - Các cấu tử sắt đơn nhân (*Mononuclear Ferric Species*):
    - Tồn tại các dạng cation hòa tan $\text{Fe}^{3+}$, $\text{Fe(OH)}^{2+}$, $\text{Fe(OH)}_2^+$, và anion $\text{Fe(OH)}_4^-$.
    - Độ tan của $\text{Fe(OH)}_3(\text{s})$ thấp hơn đáng kể so với nhôm, vùng kết tủa mở rộng trên dải $\text{pH}$ rộng hơn rất nhiều ($\text{pH} \approx 4 - 11$).
  - Phân vùng vận hành công nghệ trên giản đồ độ tan:
    - Vùng keo tụ quét (*Sweep coagulation*): xuất hiện ở nồng độ châm kim loại cao vượt ngưỡng bão hòa hòa tan, nằm sâu bên trong đường biên kết tủa vô định hình.
    - Vùng hấp phụ và trung hòa điện tích (*Adsorption destabilization*): nằm sát đường biên kết tủa ở nồng độ phèn thấp hơn và vùng $\text{pH}$ axit nhẹ đến trung tính.
    - Vùng tái bền (*Restabilization zone*): xuất hiện khi nồng độ phèn dư thừa ở dải $\text{pH}$ thấp làm đảo ngược điện tích bề mặt hạt keo sang tích điện dương.
  - **Hình 14.** Giản đồ cân bằng hòa tan của Al(III) và Fe(III) ở 25°C (Slide 13)
    - <img src="ch03_coagulation_flocculation/assets/fig_14_p13.png" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Thể hiện các đường biên pha rắn kết tủa và phân vùng cơ chế keo tụ của Al(III) và Fe(III) theo pH.
    - **Từ đâu mà thấy được**
      - Trục tung là logarit nồng độ kim loại ($\text{mol/L}$ và $\text{mg/L}$), trục hoành là pH; hai biểu đồ (a) Al và (b) Fe.
  - **Hình 15.** Vùng vận hành tối ưu của phèn nhôm và phèn sắt theo pH và liều lượng (Slide 14)
    - <img src="ch03_coagulation_flocculation/assets/fig_15_p14.png" alt="Hình 15" />
    - **Hình này chứng minh điều gì**
      - Định vị vùng keo tụ quét tối ưu (Optimal sweep) và vùng trung hòa điện tích không gây tái ổn định.
    - **Từ đâu mà thấy được**
      - Miền gạch bóng Optimal sweep nằm ở dải $\text{pH} \approx 6 - 8$ với liều phèn nhôm từ $10$ đến $100\text{ mg/L}$.

##### 3.2.3.2 Cơ chế nén lớp điện tích kép và quy tắc Schulze - Hardy

- Bản chất cơ chế nén lớp điện tích kép (*Double Layer Compression*):
  - Khi tăng nồng độ các chất điện ly trong dung dịch nước, lực ion của môi trường gia tăng làm nén lớp ion khuếch tán sát lại gần bề mặt hạt keo.
  - Chiều dày hiệu dụng của lớp khuếch tán thu hẹp làm thế bề mặt và thế Zeta suy giảm nhanh chóng theo khoảng cách.
  - Khoảng cách ngăn cách giữa các hạt keo giảm xuống, cho phép năng lượng hút phân tử van der Waals vượt qua rào cản thế năng đẩy tĩnh điện, dẫn đến sự kết tụ của các hạt keo.
- Quy tắc thực nghiệm Schulze – Hardy (*Schulze–Hardy Rule*):
  - Hiệu quả keo tụ làm mất độ bền của các ion mang điện tích trái dấu với hạt keo tăng vọt theo hóa trị (*valence*) của ion đó.
  - Nồng độ keo tụ tới hạn (*Critical Coagulant Concentration - CCC*): nồng độ chất điện ly tối thiểu cần thiết để làm mất độ bền hệ keo tỷ lệ nghịch với lũy thừa bậc 6 của điện tích ion đối:
    $$\text{CCC} \propto \frac{1}{z^6}$$
    Trong đó:
    - $\text{CCC}$: Nồng độ keo tụ tới hạn (*Critical Coagulant Concentration*), đơn vị $\text{mol/L}$ hoặc $\text{mmol/L}$.
    - $z$: Điện tích hóa trị của ion đối nghịch (*counterion charge*).
  - Tỷ lệ thực nghiệm nồng độ đông tụ tới hạn của các cation đối với hạt keo mang điện tích âm:
    $$\text{Na}^+ : \text{Ca}^{2+} : \text{Al}^{3+} \approx 100 : 1{,}6 : 0{,}14$$
    - Cation hóa trị 2 ($\text{Ca}^{2+}$) có hiệu quả keo tụ cao gấp khoảng $60$ lần so với cation hóa trị 1 ($\text{Na}^+$).
    - Cation hóa trị 3 ($\text{Al}^{3+}, \text{Fe}^{3+}$) có hiệu quả keo tụ cao gấp hơn $700$ lần so với cation hóa trị 1 ($\text{Na}^+$).

##### 3.2.3.3 Cơ chế trung hòa điện tích, tạo cầu nối polymer và keo tụ bông quét

- Cơ chế hấp phụ và trung hòa điện tích (*Adsorption and Charge Neutralization*):
  - Bản chất: làm suy giảm điện tích âm bề mặt của hạt keo thông qua sự hấp phụ đặc hiệu của các phức chất kim loại đa nhân tích điện dương ($\text{Al}_m(\text{OH})_n^{z+}, \text{Fe}_m(\text{OH})_n^{z+}$) hoặc bằng cách hạ thấp $\text{pH}$ của nước.
  - Trong cơ chế này, các lực liên kết hóa học bề mặt (*chemical effects*) có vai trò quyết định và mạnh hơn nhiều so với lực tương tác tĩnh điện thuần túy (*electrostatic effects*).
  - Hiện tượng đảo điện tích và tái bền (*Charge reversal & restabilization*): nếu châm dư liều lượng hóa chất keo tụ, sự hấp phụ quá mức các cấu tử tích điện dương sẽ biến đổi bề mặt hạt keo từ tích điện âm sang tích điện dương, làm hệ keo phân tán bền vững trở lại.
- Cơ chế hấp phụ và tạo cầu nối liên kết hạt (*Adsorption and Interparticle Bridging*):
  - Thuyết tạo cầu nối (*Bridging theory*) giải thích quá trình làm mất độ bền và keo tụ hệ keo khi sử dụng các hợp chất polymer hữu cơ có khối lượng phân tử lớn (*high-molecular-weight polymers*).
  - Chuỗi polymer mạch dài hấp phụ đồng thời lên các vị trí hoạt tính bề mặt (*specific sites*) của nhiều hạt keo lân cận.
  - Cấu trúc mạch polymer đóng vai trò như chiếc cầu nối vật lý liên kết các hạt keo riêng lẻ lại thành các cụm bông cặn kích thước lớn và cấu trúc xốp.
  - Nguy cơ quá liều polymer: nếu châm quá nhiều polymer, các mạch polymer sẽ bao bọc kín toàn bộ bề mặt của từng hạt đơn lẻ, làm mất các vị trí liên kết tự do và gây tái ổn định hệ keo (*steric stabilization*).
- Cơ chế bẫy cuộn trong kết tủa hay keo tụ bông quét (*Enmeshment in a Precipitate / Sweep Floc*):
  - Bản chất: khi châm muối nhôm hoặc muối sắt với liều lượng lớn vượt quá giới hạn tích số tan của hydroxide kim loại, các kết tủa dạng bông vô định hình $\text{Al(OH)}_3(\text{s})$ hoặc $\text{Fe(OH)}_3(\text{s})$ sẽ hình thành ồ ạt trong thời gian cực ngắn (vài phần mười giây).
  - Khối kết tủa hydroxide phát triển nhanh chóng sẽ bao bọc, bẫy cuộn và cuốn giữ (*entrapment*) các hạt keo có thế Zeta thấp hoặc gần bằng $0$ vào bên trong cấu trúc bông cặn lớn.
  - Keo tụ bông quét là cơ chế chủ đạo và vận hành thực tế phổ biến nhất tại hầu hết các nhà máy xử lý nước cấp đô thị (*water treatment plants*).

---

#### 3.2.4 Thử nghiệm Jar test và Tối ưu hóa keo tụ

##### 3.2.4.1 Cấu tạo thiết bị và quy trình thử nghiệm Jar test hai giai đoạn

- Vai trò thực nghiệm của thử nghiệm Jar test (*Bench-scale Testing*):
  - Quá trình keo tụ trong nước tự nhiên bao gồm chuỗi phản ứng hóa học cạnh tranh phức tạp và đồng thời diễn ra giữa các cấu tử hòa tan, chất hữu cơ NOM, độ kiềm và hạt cặn.
  - Không thể tính toán thuần túy bằng lý thuyết để xác định chính xác loại hóa chất và liều lượng tối ưu; bắt buộc phải xác định bằng thực nghiệm thông qua thử nghiệm Jar test ở quy mô phòng thí nghiệm (*bench-scale*) hoặc mô hình thử nghiệm (*pilot-scale*).
  - Thử nghiệm Jar test cho phép đánh giá định lượng nhanh chóng, so sánh nhiều loại hóa chất keo tụ và xác định dải liều lượng vận hành tối ưu.
- Cấu tạo thiết bị Jar test tiêu chuẩn AWWA:
  - Hệ thống gồm dãy 6 bình phản ứng gián đoạn (*batch reactors / jars*), mỗi bình được trang bị một cánh khuấy paddle bằng thép không gỉ.
  - Thiết kế bình khuấy hình hộp vuông (*square-shaped jars / Gator jars*): ngăn ngừa hiện tượng tạo phễu xoáy trung tâm (*vortex flow*), vốn gây phân tầng và làm sai lệch động học khuấy trộn nếu sử dụng cốc hình trụ tròn (*circular beakers*).
  - Cơ cấu truyền động liên động (*gang stirrer*): tất cả 6 cánh khuấy được dẫn động đồng tốc bởi một động cơ chung có điều tốc điện tử từ $10$ đến $300\text{ vòng/phút}$.
  - Mục đích: mô phỏng chính xác các giai đoạn công nghệ thực tế gồm khuấy nhanh (phân tán hóa chất, $1\text{ phút}$ ở $100 - 150\text{ rpm}$), khuấy chậm tạo bông ($15 - 20\text{ phút}$ ở $20 - 40\text{ rpm}$) và lắng tĩnh trọng lực ($30\text{ phút}$).
  - **Hình 16.** Thiết bị thử nghiệm Jar test 6 cánh khuấy trong phòng thí nghiệm (Slide 17)
    - <img src="ch03_coagulation_flocculation/assets/fig_16_p17.jpeg" alt="Hình 16" />
    - **Hình này chứng minh điều gì**
      - Thể hiện thiết bị Jar test thực tế với 6 cốc khuấy vuông và hệ thống cánh khuấy paddle đồng tốc.
    - **Từ đâu mà thấy được**
      - Hình ảnh kỹ thuật viên vận hành hệ thống 6 bình khuấy gắn cụm động cơ gang stirrer phía trên.
  - **Hình 17.** Cấu tạo hệ thống máy khuấy Jar test tiêu chuẩn AWWA (Slide 18)
    - <img src="ch03_coagulation_flocculation/assets/fig_17_p18.jpeg" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - Minh họa phương tiện tiêu chuẩn dùng để mô phỏng điều kiện keo tụ - tạo bông và lắng.
    - **Từ đâu mà thấy được**
      - Dãy 6 cốc thử nghiệm đặt song song trên đế chiếu sáng phản quang để quan sát kích thước bông cặn.
- Quy trình thử nghiệm Jar test hai giai đoạn chuẩn:
  - Nạp cùng một thể tích mẫu nước thô đầu vào vào cả 6 bình khuấy (thường là $1000\text{ mL}$ hoặc $2000\text{ mL}$ mỗi bình).
  - Nguồn nước thô thí nghiệm mẫu: độ đục ban đầu $15\text{ NTU}$, độ kiềm bicarbonate $\text{HCO}_3^-$ là $50\text{ mg/L}$ tính theo $\text{CaCO}_3$.
  - Giai đoạn 1: Thử nghiệm Jar test I (Xác định $\text{pH}$ tối ưu):
    - Cố định liều lượng chất keo tụ (ví dụ châm cùng liều phèn nhôm $10\text{ mg/L}$ vào cả 6 bình).
    - Điều chỉnh giá trị $\text{pH}$ biến thiên từ $5{,}0$ đến $7{,}5$ giữa các bình bằng cách châm thêm dung dịch axit ($\text{H}_2\text{SO}_4$) hoặc kiềm ($\text{NaOH}$).
    - Thực hiện quy trình khuấy nhanh, khuấy chậm và lắng tĩnh $30\text{ phút}$; đo độ đục dư sau lắng để chọn ra giá trị $\text{pH}$ cho độ đục dư thấp nhất.
  - Giai đoạn 2: Thử nghiệm Jar test II (Xác định liều lượng hóa chất tối ưu):
    - Cố định $\text{pH}$ của tất cả 6 bình ở mức $\text{pH}$ tối ưu đã xác định từ Giai đoạn 1 ($\text{pH} = 6{,}0$).
    - Thay đổi liều lượng chất keo tụ tăng dần giữa các bình (ví dụ từ $5$ đến $20\text{ mg/L}$).
    - Tiến hành chu trình khuấy và lắng $30\text{ phút}$; đo độ đục dư để xác định liều lượng châm kinh tế nhất mang lại hiệu quả xử lý cao nhất.
  - **Hình 18.** Bảng số liệu thử nghiệm Jar test I khảo sát ảnh hưởng của pH (Slide 19)
    - <img src="ch03_coagulation_flocculation/assets/fig_18_p19.png" alt="Hình 18" />
    - **Hình này chứng minh điều gì**
      - Ghi nhận độ đục dư theo các mức pH từ 5,0 đến 7,5 tại liều phèn nhôm cố định 10 mg/L.
    - **Từ đâu mà thấy được**
      - Bảng số liệu gồm hàng pH (5,0 - 7,5), hàng Alum dose (10 mg/L) và hàng Turbidity (11 - 13 NTU).
  - **Hình 19.** Bảng số liệu thử nghiệm Jar test II khảo sát liều lượng phèn (Slide 19)
    - <img src="ch03_coagulation_flocculation/assets/fig_19_p19.png" alt="Hình 19" />
    - **Hình này chứng minh điều gì**
      - Định lượng độ đục dư theo liều lượng phèn từ 5 đến 20 mg/L tại mức pH cố định 6,0.
    - **Từ đâu mà thấy được**
      - Bảng số liệu ghi rõ liều phèn thay đổi 5, 7, 10, 12, 15, 20 mg/L và độ đục tương ứng.
- Phân tích kết quả thực nghiệm Jar test mẫu:
  - Bảng kết quả Jar test I (Cố định liều phèn nhôm $10\text{ mg/L}$):

| Thông số | Bình 1 | Bình 2 | Bình 3 | Bình 4 | Bình 5 | Bình 6 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| $\text{pH}$ | $5{,}0$ | $5{,}5$ | $\mathbf{6{,}0}$ | $6{,}5$ | $7{,}0$ | $7{,}5$ |
| Liều phèn nhôm (*Alum dose*, $\text{mg/L}$) | $10$ | $10$ | $\mathbf{10}$ | $10$ | $10$ | $10$ |
| Độ đục sau lắng 30 phút (*Turbidity*, $\text{NTU}$) | $11$ | $7$ | $\mathbf{5{,}5}$ | $5{,}7$ | $8$ | $13$ |

  - Nhận xét Jar test I: Độ đục dư đạt giá trị cực tiểu là $5{,}5\text{ NTU}$ tại Bình số 3 ứng với $\text{pH} = 6{,}0$. Do đó, $\text{pH}$ tối ưu cho quá trình keo tụ nguồn nước này là $\text{pH}_{\text{opt}} = 6{,}0$.
  - Bảng kết quả Jar test II (Cố định $\text{pH} = 6{,}0$):

| Thông số | Bình 1 | Bình 2 | Bình 3 | Bình 4 | Bình 5 | Bình 6 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| $\text{pH}$ | $6{,}0$ | $6{,}0$ | $6{,}0$ | $\mathbf{6{,}0}$ | $6{,}0$ | $6{,}0$ |
| Liều phèn nhôm (*Alum dose*, $\text{mg/L}$) | $5$ | $7$ | $10$ | $\mathbf{12}$ | $15$ | $20$ |
| Độ đục sau lắng 30 phút (*Turbidity*, $\text{NTU}$) | $14$ | $9{,}5$ | $5$ | $\mathbf{4{,}5}$ | $6$ | $13$ |

  - Nhận xét Jar test II: Khi tăng liều phèn từ $5$ lên $12\text{mg/L}$, độ đục dư giảm mạnh từ $14\text{ NTU}$ xuống mức cực tiểu $4{,}5\text{ NTU}$ (Bình 4). Tiếp tục tăng liều lên $15$ và $20\text{ mg/L}$ làm độ đục tăng ngược trở lại lên $6$ và $13\text{ NTU}$ do hiện tượng quá liều gây đảo điện tích và tái bền hệ keo. Liều lượng phèn nhôm tối ưu là $\text{Dose}_{\text{opt}} = 12\text{ mg/L}$.
  - **Hình 20.** Kết quả thử nghiệm Jar test I xác định pH tối ưu của phèn nhôm (Slide 20)
    - <img src="ch03_coagulation_flocculation/assets/fig_20_p20.png" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - Xác nhận $\text{pH} = 6{,}0$ mang lại độ đục dư nhỏ nhất ($5{,}5\text{ NTU}$) tại liều phèn chuẩn $10\text{ mg/L}$.
    - **Từ đâu mà thấy được**
      - Bình số 3 hiển thị giá trị độ đục đáy $5{,}5\text{ NTU}$, hai bên sườn tăng lên $11\text{ NTU}$ và $13\text{ NTU}$.
  - **Hình 21.** Kết quả thử nghiệm Jar test II xác định liều lượng châm phèn tối ưu (Slide 20)
    - <img src="ch03_coagulation_flocculation/assets/fig_21_p20.png" alt="Hình 21" />
    - **Hình này chứng minh điều gì**
      - Xác định liều lượng keo tụ tối ưu là $12\text{ mg/L}$ và cảnh báo hiện tượng tái đục khi quá liều.
    - **Từ đâu mà thấy được**
      - Độ đục cực tiểu $4{,}5\text{ NTU}$ ở liều $12\text{ mg/L}$; liều $20\text{ mg/L}$ đẩy độ đục tăng vọt lên $13\text{ NTU}$.

##### 3.2.4.2 Tối ưu hóa liều lượng keo tụ theo nồng độ bề mặt hạt keo và các vùng phản ứng

- Biến thiên đường cong độ đục dư theo bốn mức nồng độ hạt keo ($S_1, S_2, S_3, S_4$):
  - Hình thái đường cong độ đục dư phụ thuộc trực tiếp vào nồng độ diện tích bề mặt hạt keo trong nước thô ($\bar{S}$):
    - Mức $S_1$ (Nồng độ hạt keo rất thấp, nước thô có độ đục rất bé):
      - Tần suất va chạm giữa các hạt keo quá thấp, không đủ khả năng tạo thành bông cặn tự nhiên khi mất độ bền.
      - Nước thiếu các tâm nhân mầm (*nuclei*) để hydroxide kim loại bám dính và kết tinh.
      - Bắt buộc phải châm hóa chất keo tụ ở liều lượng rất cao để đưa hệ trực tiếp vào cơ chế bông quét (Zone 4).
      - Tại mức $S_1$, hiện tượng tái bền (Zone 3) hoàn toàn không xảy ra vì hệ vận hành thuần túy ở chế độ sweep floc.
    - Mức $S_2$ và $S_3$ (Nồng độ hạt keo trung bình):
      - Nồng độ hạt keo đủ lớn để làm mất độ bền hạt bằng cơ chế hấp phụ - trung hòa điện tích (Zone 2) trước khi đạt tới ngưỡng bông quét.
      - Tồn tại mối quan hệ tỷ lệ lượng hóa chặt chẽ giữa liều phèn châm vào và diện tích bề mặt hạt keo (*stoichiometry of coagulation*).
      - Rất dễ bị hiện tượng quá liều gây tái bền (Zone 3): ở mức $S_2$, dải liều tối ưu Zone 2 rất hẹp; ở mức $S_3$, dải Zone 2 mở rộng hơn.
      - Nếu tiếp tục tăng liều phèn vượt qua vùng tái bền Zone 3, hệ sẽ chuyển tiếp sang vùng keo tụ bông quét Zone 4.
    - Mức $S_4$ (Nồng độ hạt keo rất cao, nước thô có độ đục rất lớn):
      - Diện tích bề mặt tiếp xúc của hệ keo cực kỳ lớn, hấp phụ tiêu thụ phần lớn các sản phẩm thủy phân của chất keo tụ.
      - Đòi hỏi liều lượng chất keo tụ lớn tỷ lệ thuận với độ đục. Dù liều lượng tiếp cận dải liều của bông quét, cơ chế thực tế vẫn là hấp phụ trung hòa điện tích chứ không tạo thành bông quét.
      - Gần như không thể xảy ra hiện tượng quá liều gây tái bền (*almost impossible to overdose*) do lượng hạt keo khổng lồ hấp phụ triệt để lượng ion kim loại châm vào.
  - **Hình 22.** Đường cong độ đục dư theo liều lượng keo tụ ứng với các mức nồng độ hạt keo S1-S4 (Slide 21)
    - <img src="ch03_coagulation_flocculation/assets/fig_22_p21.png" alt="Hình 22" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự dịch chuyển các vùng keo tụ và tái bền qua 4 mức nồng độ hạt keo từ $S_1$ đến $S_4$.
    - **Từ đâu mà thấy được**
      - Đồ thị đối chiếu Residual Turbidity theo Dosage of Coagulant cho 4 đường đặc tuyến $S_1, S_2, S_3, S_4$.
  - **Hình 23.** Phân vùng phản ứng keo tụ và cơ chế tái ổn định hệ keo (Slide 22)
    - <img src="ch03_coagulation_flocculation/assets/fig_23_p22.png" alt="Hình 23" />
    - **Hình này chứng minh điều gì**
      - Khẳng định tính chất mở rộng của vùng keo tụ Zone 2 và sự biến mất của vùng tái bền ở nồng độ $S_4$.
    - **Từ đâu mà thấy được**
      - Đường cong $S_4$ cho độ đục dư hạ xuống thấp và duy trì ổn định không bị bật ngược lên.
- Giản đồ tổng quát các miền keo tụ và giải pháp châm bentonite (*Coagulation Region Diagram*):
  - Phân vùng trên hệ tọa độ liều lượng chất keo tụ (*Dosage*) và diện tích bề mặt hạt keo ($\bar{S}$):
    - Vùng 1 (Zone 1 - Miền chưa keo tụ): liều lượng hóa chất không đủ để trung hòa điện tích, hệ keo duy trì trạng thái phân tán bền vững.
    - Vùng 2 (Zone 2 - Miền keo tụ trung hòa điện tích): ranh giới liều tối ưu tăng tuyến tính theo nồng độ bề mặt keo $\bar{S}$ (đặc trưng tỷ lệ lượng hóa *Stoichiometric Destabilization*).
    - Vùng 3 (Zone 3 - Miền tái bền): nêm hình tam giác kẹp giữa Zone 2 và Zone 4 ở dải nồng độ hạt keo trung bình ($S_2 - S_3$), hạt keo bị đảo điện tích dương do thừa hóa chất keo tụ.
    - Vùng 4 (Zone 4 - Miền keo tụ bông quét / *Sweep Floc*): xuất hiện ở dải liều phèn cao. Đường biên liều quét tối ưu hơi dốc nhẹ xuống khi nồng độ hạt keo tăng, do sự có mặt của hạt keo hỗ trợ làm nhân kết tinh cho bông cặn.
  - Giải pháp kỹ thuật bổ sung sét bentonite (*Bentonite Addition*):
    - Nước thô có độ đục quá thấp ($S_1$) đòi hỏi liều lượng phèn rất cao để tạo bông quét, gây tốn kém hóa chất và tạo nhiều bùn cặn nhôm.
    - Bổ sung hạt đất sét bentonite vào nước thô giúp nhân tạo nâng cao nồng độ diện tích bề mặt hạt keo từ $S_1$ lên $S_3$.
    - Việc này dịch chuyển điểm làm việc công nghệ từ cơ chế bông quét liều cao (Zone 4) sang cơ chế hấp phụ trung hòa điện tích liều thấp (Zone 2), giúp tiết kiệm đáng kể hóa chất keo tụ và tạo bông cặn lắng nhanh.
  - **Hình 24.** Giản đồ tổng quát quan hệ liều lượng phèn và nồng độ bề mặt hạt keo (Slide 23)
    - <img src="ch03_coagulation_flocculation/assets/fig_24_p23.jpeg" alt="Hình 24" />
    - **Hình này chứng minh điều gì**
      - Minh chứng giải pháp châm thêm sét bentonite chuyển dịch chế độ keo tụ từ vùng quét sang vùng trung hòa điện tích.
    - **Từ đâu mà thấy được**
      - Mũi tên Bentonite Addition chỉ hướng từ mốc $S_1$ sang $S_3$, đưa liều phèn từ đỉnh Zone 4 xuống Zone 2.

---

#### 3.2.5 Hóa chất keo tụ và chất trợ keo tụ

##### 3.2.5.1 Các hóa chất keo tụ vô cơ và phản ứng tiêu thụ độ kiềm

- Lịch sử phát triển và phân loại chất keo tụ công nghiệp:
  - Quá trình keo tụ kết hợp bể lọc hạt (lọc cát nhanh và lọc đa lớp) được ứng dụng rộng rãi trong các nhà máy cấp nước tại Hoa Kỳ từ những năm 1880.
  - Muối nhôm ($\text{Al}^{3+}$) và muối sắt ($\text{Fe}^{3+}$) là hai nhóm chất keo tụ vô cơ truyền thống được sử dụng phổ biến nhất, trong đó phèn nhôm (*alum*) chiếm thị phần lớn nhất.
  - Khi hòa tan phèn nhôm ($\text{Al}_2(\text{SO}_4)_3 \cdot 14\text{H}_2\text{O}$) vào nước, một chuỗi phức chất trung gian gọi là các sản phẩm thủy phân của nhôm (*aluminum hydrolysis products*) được hình thành tức thời trong và sau quá trình khuấy trộn nhanh; chính các phức đa nhân này thực hiện chức năng keo tụ.
  - Các hóa chất keo tụ tiền thủy phân (*Prehydrolyzed metal salts*): được tổng hợp và tạo phức sẵn trước khi châm vào nước, bao gồm silica hoạt tính (*activated silica*), polyaluminum chloride (PAC / PACl) và polyiron chloride (PiCl).
  - **Hình 25.** Giản đồ các miền keo tụ quét và keo tụ trung hòa điện tích (Slide 24)
    - <img src="ch03_coagulation_flocculation/assets/fig_25_p24.jpeg" alt="Hình 25" />
    - **Hình này chứng minh điều gì**
      - Khẳng định sự phân tách giữa vùng keo tụ stoichiometric Zone 2 và vùng sweep floc Zone 4.
    - **Từ đâu mà thấy được**
      - Đồ thị thể hiện miền Coagulation Region bao gồm toàn bộ Zone 2 và Zone 4 phía trên đường ranh giới liều tối ưu.
- Bảng danh mục hóa chất keo tụ vô cơ thông dụng:

| STT | Tên hóa chất keo tụ | Công thức hóa học chuẩn |
| :---: | :--- | :--- |
| 1 | Nhôm sunfat (Phèn nhôm / *Alum*) | $\text{Al}_2(\text{SO}_4)_3 \cdot 14\text{H}_2\text{O}$ |
| 2 | Nhôm clorua (*Aluminum chloride*) | $\text{AlCl}_3$ |
| 3 | Sắt(III) clorua (Phèn sắt / *Ferric chloride*) | $\text{FeCl}_3 \cdot 6\text{H}_2\text{O}$ (hoặc $\text{FeCl}_3$ khan) |
| 4 | Polyaluminum Chloride (PAC) | $[\text{Al}_2(\text{OH})_n\text{Cl}_{6-n}]_m$ |
| 5 | Polymer hữu cơ (*Polyelectrolyte*) | Cationic, Anionic, Nonionic |

- Phương trình phản ứng thủy phân và định lượng tiêu thụ độ kiềm:
  - Phản ứng thủy phân của phèn nhôm trong nước có độ kiềm tự nhiên ($\text{HCO}_3^-$):
    $$\text{Al}_2(\text{SO}_4)_3 \cdot 14\text{H}_2\text{O} + 6\text{HCO}_3^- \longrightarrow 2\text{Al(OH)}_3\downarrow + 6\text{CO}_2 + 14\text{H}_2\text{O} + 3\text{SO}_4^{2-}$$
    - Khối lượng mol của phèn nhôm thương phẩm ($\text{Al}_2(\text{SO}_4)_3 \cdot 14\text{H}_2\text{O}$): $M = 594\text{ g/mol}$.
    - Khối lượng mol của $\text{CaCO}_3$: $M = 100\text{ g/mol}$.
    - Tỷ lệ đương lượng tiêu thụ kiềm: $1\text{ mol}$ phèn nhôm tác dụng với $6\text{ mol } \text{HCO}_3^-$, tương đương tiêu thụ $3\text{ mol } \text{CaCO}_3$ ($300\text{ g } \text{CaCO}_3$).
    - Tỷ lệ tiêu thụ kiềm theo khối lượng:
      $$\frac{300\text{ g }\text{CaCO}_3}{594\text{ g phèn nhôm}} \approx 0{,}505\text{ mg }\text{CaCO}_3 \text{ / } 1\text{ mg phèn nhôm}$$
      (Cứ châm $1\text{ mg/L}$ phèn nhôm sẽ làm tiêu hao khoảng $0{,}505\text{ mg/L}$ độ kiềm tính theo $\text{CaCO}_3$).
  - Phản ứng thủy phân của phèn sắt(III) clorua ngậm nước:
    $$\text{FeCl}_3 \cdot 6\text{H}_2\text{O} + 3\text{HCO}_3^- \longrightarrow \text{Fe(OH)}_3\downarrow + 3\text{CO}_2 + 6\text{H}_2\text{O} + 3\text{Cl}^-$$
    - Khối lượng mol của $\text{FeCl}_3 \cdot 6\text{H}_2\text{O}$: $M = 270{,}3\text{ g/mol}$.
    - Tỷ lệ đương lượng tiêu thụ kiềm: $1\text{ mol } \text{FeCl}_3 \cdot 6\text{H}_2\text{O}$ tác dụng với $3\text{ mol } \text{HCO}_3^-$, tương đương tiêu thụ $1{,}5\text{ mol } \text{CaCO}_3$ ($150\text{ g } \text{CaCO}_3$).
    - Tỷ lệ tiêu thụ kiềm theo khối lượng:
      $$\frac{150\text{ g }\text{CaCO}_3}{270{,}3\text{ g }\text{FeCl}_3 \cdot 6\text{H}_2\text{O}} \approx 0{,}555\text{ mg }\text{CaCO}_3 \text{ / } 1\text{ mg }\text{FeCl}_3 \cdot 6\text{H}_2\text{O}$$
      (Đối với $\text{FeCl}_3$ khan, $M = 162{,}2\text{ g/mol}$, tỷ lệ tiêu thụ độ kiềm là $150 / 162{,}2 \approx 0{,}925\text{ mg }\text{CaCO}_3 \text{ / } 1\text{ mg }\text{FeCl}_3$).
  - Hiện tượng suy giảm $\text{pH}$ khi thiếu kiềm:
    - Nếu độ kiềm tự nhiên của nước thô không đủ để trung hòa lượng ion $\text{H}^+$ giải phóng ra, $\text{pH}$ của nước sẽ tụt mạnh xuống dưới ngưỡng tối ưu, làm giảm hiệu suất keo tụ và gây hòa tan ngược ion kim loại ($\text{Al}^{3+}, \text{Fe}^{3+}$) vào nước sau lắng.
    - Trong trường hợp đó, bắt buộc phải châm thêm hóa chất kiềm hóa bổ sung (vôi $\text{Ca(OH)}_2$, xút $\text{NaOH}$ hoặc soda $\text{Na}_2\text{CO}_3$).

##### 3.2.5.2 Chất trợ keo tụ Polymer và các đặc tính yêu cầu trong xử lý nước cấp

- Phân loại và ứng dụng công nghệ của Polymer (Chất trợ keo tụ Polyelectrolyte):
  - 1. Đóng vai trò là chất keo tụ chính (*Primary Coagulant*):
    - Thường sử dụng các polymer cation (*cationic polymers*), cấu trúc chủ yếu là các amin bậc bốn (*quaternary amines*).
    - Liều lượng châm:
      - Khi sử dụng đơn độc: liều lượng thường $> 1{,}0\text{ mg/L}$.
      - Khi kết hợp cùng muối nhôm hoặc muối sắt: liều lượng từ $0{,}1$ đến $0{,}5\text{ mg/L}$.
    - Điểm châm: bổ sung trực tiếp tại bể hoặc thiết bị khuấy nhanh (*rapid mixing process*).
    - Hiệu quả công nghệ: trung hòa điện tích cực mạnh và cải thiện rõ rệt hiệu suất loại bỏ chất hữu cơ tự nhiên (*NOM - Natural Organic Matter*).
  - 2. Đóng vai trò là chất trợ keo tụ (*Coagulation Aids*):
    - Thường sử dụng polymer anion hoặc không ion (*anionic or nonionic polymers*), phổ biến nhất là các hợp chất polyacrylamide mạch dài.
    - Liều lượng châm: từ $1{,}0$ đến $2{,}0\text{ mg/L}$.
    - Điểm châm: châm sau quá trình khuấy nhanh (*after rapid mixing process*), thường đưa vào ở đầu ngăn tạo bông chậm.
    - Hiệu quả công nghệ: tăng cường kích thước, độ đặc chắc và vận tốc lắng của bông cặn; không cải thiện hiệu suất loại bỏ NOM.
  - 3. Đóng vai trò là chất trợ lọc (*Filter Aids*):
    - Thường sử dụng polymer không ion (*nonionic polymers*).
    - Liều lượng châm rất nhỏ: từ $0{,}005$ đến $0{,}05\text{ mg/L}$, châm ngay trên dòng nước trước khi chảy vào bể lọc hạt.
    - Hiệu quả công nghệ: tăng cường độ bám dính của các vi bông cặn lên bề mặt hạt cát lọc, ngăn hiện tượng xuyên thủng lớp lọc.
- Vấn đề an toàn vệ sinh và rủi ro sức khỏe của Polymer:
  - Các chế phẩm polyelectrolyte công nghiệp thường chứa dư lượng tạp chất độc hại phát sinh từ quá trình tổng hợp (đặc biệt là monomer tự do acrylamide, các chất phản ứng còn sót và sản phẩm phụ).
  - Acrylamide là chất có độc tính thần kinh cao và tiềm ẩn nguy cơ gây ung thư, được kiểm soát rất nghiêm ngặt về giới hạn hàm lượng trong nước cấp sinh hoạt.
  - Polymer tồn lưu trong nước có thể phản ứng với clo trong công đoạn khử trùng (*disinfection*), hình thành các sản phẩm phụ khử trùng độc hại (*DBPs*).
- Ba đặc tính cốt lõi của chất keo tụ vô cơ dùng trong xử lý nước ăn uống (*Potable Water*):
  - 1. Không độc hại ở liều lượng làm việc (*Nontoxic at the working dosage*): đảm bảo nước sau xử lý an toàn tuyệt đối cho sức khỏe người tiêu dùng.
  - 2. Mật độ điện tích cao (*High charge density*): mang điện tích dương lớn trên một đơn vị khối lượng để tối ưu hóa hiệu quả trung hòa điện tích và nén lớp điện tích kép.
  - 3. Độ hòa tan cực thấp trong dải $\text{pH}$ trung tính (*Insoluble in the neutral pH range*): kết tủa hydroxide hoàn toàn ở $\text{pH} \approx 6{,}5 - 8{,}0$ để tách cặn triệt để và hạn chế tối đa nồng độ nhôm hoặc sắt hòa tan dư thừa đi vào mạng lưới cấp nước.
- Dây chuyền liên động công nghệ keo tụ - tạo bông - lắng:
  - Quá trình keo tụ hóa học tại ngăn khuấy nhanh phối hợp chặt chẽ với quá trình tạo bông cơ học và lắng trọng lực để hoàn thiện dây chuyền xử lý nước.
  - **Hình 26.** Sơ đồ dây chuyền bể khuấy nhanh, bể tạo bông cánh guồng và bể lắng (Slide 27)
    - <img src="ch03_coagulation_flocculation/assets/fig_26_p27.png" alt="Hình 26" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự liên kết công nghệ giữa khuấy nhanh hóa chất, tạo bông 3 ngăn và lắng trọng lực.
    - **Từ đâu mà thấy được**
      - Nước thô qua Flash mixer châm phèn, qua 3 ngăn Paddles có vách Baffles, rồi chảy sang Settling tank.

### 3.3 Thực hành và Thiết kế công nghệ khuấy trộn

#### 3.3.1 Cơ sở lý thuyết khuấy trộn và Gradient vận tốc

- Phân loại và vai trò công nghệ của hai giai đoạn khuấy trộn trong cụm xử lý keo tụ - tạo bông:
  - Khuấy nhanh keo tụ (*Coagulant mixing / Rapid mixing / Flash mixing*): phân tán hóa chất keo tụ tức thời và đồng đều vào toàn bộ khối tích nước, thúc đẩy quá trình thủy phân nhanh và trung hòa điện tích để làm mất độ bền của các hạt keo mang điện tích âm.
  - Khuấy tạo bông (*Flocculation mixing / Slow mixing*): duy trì cường độ xáo trộn chậm, có kiểm soát nhằm gia tăng tần suất va chạm hiệu quả giữa các hạt keo đã mất độ bền, kết tụ chúng thành các bông cặn lớn, đặc chắc, có vận tốc lắng cao mà không làm vỡ các liên kết bông cặn vừa hình thành.
  - Dây chuyền công nghệ hoàn chỉnh gồm: Nước thô (*Raw water*) $\to$ Bể khuấy nhanh (*Flash mixer*) $\to$ Hệ thống bể tạo bông cánh guồng nhiều ngăn nối tiếp (*Paddles separated by Baffles*) $\to$ Bể lắng (*Settling tank*).
  - **Hình 27.** Sơ đồ mặt cắt dây chuyền công nghệ keo tụ - tạo bông và lắng
    - <img src="ch03_coagulation_flocculation/assets/fig_27_p28.png" alt="Hình 27" />
    - **Hình này chứng minh điều gì**
      - Thể hiện dây chuyền xử lý liên tục từ ngăn khuấy nhanh cơ học qua 3 bậc tạo bông có vách ngăn đến bể lắng trọng lực.
    - **Từ đâu mà thấy được**
      - Nhãn `Raw water` và `Flash mixer` ở đầu bể; 3 cụm cánh guồng `Paddles` ngăn cách bằng `Baffles`; cửa xả bùn và máng thu dẫn sang `Setting tank`.
- Phương trình Camp - Stein xác định công suất tiêu tán và gradient vận tốc trung bình ($G$):
  - Khái niệm: Gradient vận tốc ($G$) là độ biến thiên vận tốc tương đối giữa các lớp chất lỏng kế cận trên một đơn vị khoảng cách, là thước đo trực tiếp năng lượng khuấy trộn đưa vào một đơn vị thể tích chất lỏng.
  - Phương trình cơ bản Camp - Stein biểu diễn mối quan hệ giữa công suất tiêu tán và gradient vận tốc:
    $$P = \mu \cdot V \cdot G^2$$
  - Công thức xác định gradient vận tốc trung bình $G$:
    $$G = \left(\frac{P}{\mu \cdot V}\right)^{0{,}5} = \sqrt{\frac{P}{\mu \cdot V}}$$
  - Các đại lượng vật lý và đơn vị đo trong hệ SI:
    - $P$: Công suất tiêu thụ hữu ích truyền vào khối chất lỏng ($\text{W}$, $\text{J/s}$, hoặc $\text{N}\cdot\text{m/s}$).
    - $\mu$: Độ nhớt động lực học tuyệt đối của chất lỏng ($\text{Pa}\cdot\text{s}$, $\text{N}\cdot\text{s/m}^2$, hoặc $\text{kg/(m}\cdot\text{s)}$).
    - $V$: Thể tích hữu ích của bể khuấy ($\text{m}^3$).
    - $G$: Gradient vận tốc trung bình ($\text{s}^{-1}$).
- Các chuẩn số thủy lực không thứ nguyên xác định đặc tính vận hành của cánh khuấy (*Impeller dimensionless numbers*):
  - Chuẩn số công suất (*Power number* $N_p$):
    $$N_p = \frac{P}{\rho \cdot N^3 \cdot D^5}$$
    - Biểu thị mức cản thủy lực mà cánh khuấy tạo ra khi quay trong chất lỏng ở chế độ chảy rối hoàn toàn ($Re > 10^4$).
  - Chuẩn số lưu lượng / bơm (*Pumping number* $N_q$):
    $$N_q = \frac{Q}{N \cdot D^3}$$
    - Biểu thị năng lực đẩy và lưu lượng tuần hoàn chất lỏng do cánh khuấy sản sinh trên một vòng quay.
  - Chuẩn số cột áp (*Head number* $N_h$):
    $$N_h = \frac{\Delta H \cdot g}{(N \cdot D)^2}$$
    - Biểu thị tỷ lệ năng lượng cột áp do cánh khuấy truyền cho dòng chất lỏng so với động năng tại mút cánh.
  - Các thông số liên quan trong hệ đơn vị SI:
    - $N_p, N_q, N_h$: Các chuẩn số không thứ nguyên đặc trưng cho từng dạng hình học của cánh khuấy.
    - $P$: Công suất tiêu tán truyền vào chất lỏng ($\text{W}$).
    - $\rho$: Khối lượng riêng của chất lỏng ($\text{kg/m}^3$).
    - $N$: Tốc độ quay của cánh khuấy ($\text{rev/min}$ hoặc $\text{vòng/s}$, cần đồng nhất đơn vị thời gian với $P$ và $Q$).
    - $D$: Đường kính ngoài của cánh khuấy ($\text{m}$).
    - $Q$: Lưu lượng do cánh khuấy bơm tuần hoàn qua tiết diện quét ($\text{m}^3/\text{s}$).
    - $\Delta H$: Cột áp thủy lực do cánh khuấy tạo ra cho dòng chảy ($\text{m}$).
    - $g$: Gia tốc trọng trường ($g \approx 9{,}81\text{ m/s}^2$).
- Tiêu chuẩn thông số công nghệ vận hành bể khuấy nhanh (*Coagulator*) và bể tạo bông (*Flocculator*):
  - Bể khuấy nhanh keo tụ (*Coagulator*):
    - Thời gian lưu nước thủy lực (HRT): $30\text{ s} - 120\text{ s}$.
    - Gradient vận tốc ($G$): $500\text{ s}^{-1} - 1000\text{ s}^{-1}$ (cường độ xáo trộn cực mạnh để phân tán phèn trước khi phản ứng thủy phân kết thúc).
  - Bể tạo bông (*Flocculator*):
    - Thời gian lưu nước thủy lực (HRT): $15\text{ min} - 45\text{ min}$.
    - Gradient vận tốc ($G$): $100\text{ s}^{-1} - 10\text{ s}^{-1}$ (giảm dần từ ngăn đầu tiên đến ngăn cuối cùng để kích thích hạt va chạm ban đầu và chống vỡ bông ở giai đoạn sau).

#### 3.3.2 Thiết bị khuấy trộn nhanh keo tụ

- Bảng phân loại thiết bị khuấy trộn nhanh và phạm vi ứng dụng theo cơ chế keo tụ:
  | Thiết bị khuấy trộn (*Mixing Device*) | Ứng dụng châm hóa chất keo tụ (*Application in Coagulant Addition*) | Cơ chế keo tụ chủ đạo |
  | :--- | :--- | :--- |
  | Khuấy cơ học trong bể khuấy (*Mechanical mixers in stirred tanks*) | Keo tụ quét bông (*Sweep coagulation*) | Hình thành nhanh hydroxide kim loại kết tủa |
  | Khuấy thủy lực (*Hydraulic mixers*) | Keo tụ quét bông (*Sweep coagulation*) | Sử dụng tổn thất năng lượng dòng chảy |
  | Khuấy cơ học trên đường ống (*In-line mechanical mixers*) | Hấp phụ / làm mất độ bền (*Adsorption/destabilization*) | Phản ứng cực nhanh của ion đa hóa trị |
  | Khuấy tĩnh trên đường ống (*In-line static mixers*) | Hấp phụ / làm mất độ bền (*Adsorption/destabilization*) | Phân tán vi mô tức thời trong lòng ống |
  | Khuếch tán bằng tia nước áp lực / bơm (*Diffusion by pressurized water jets/pumps*) | Hấp phụ / làm mất độ bền (*Adsorption/destabilization*) | Xáo trộn cưỡng bức áp lực cao |
- Thiết bị khuấy cơ học trong bể khuấy (*Mechanical mixers in stirred tanks*):
  - Cấu tạo gồm động cơ điện gắn trên sàn công tác, trục quay thẳng đứng và cánh khuấy cơ học đặt trong bể có tấm chắn chống xoáy (*baffles*).
  - Hai dạng cánh khuấy thông dụng: cánh khuấy tuabin dòng xuyên tâm (*Radial-flow turbine*) đẩy dòng nước văng vuông góc ra thành bể tạo gradient cắt lớn, và cánh khuấy dòng hướng trục (*Axial-flow impeller*) đẩy dòng chất lỏng song song với trục tạo lưu lượng tuần hoàn lớn.
  - **Hình 28.** Cánh khuấy tuabin dòng xuyên tâm và cánh khuấy dòng hướng trục
    - <img src="ch03_coagulation_flocculation/assets/fig_28_p33.jpeg" alt="Hình 28" />
    - **Hình này chứng minh điều gì**
      - Minh họa hình dạng kết cấu thực tế của hai họ cánh khuấy: tuabin đĩa 6 cánh phẳng vuông góc và cánh chân vịt hydrofoil 3 cánh uốn cong.
    - **Từ đâu mà thấy được**
      - Ảnh (a) `Radial-flow turbine impeller` có đĩa tròn ở tâm gắn các bản cánh thẳng đứng; ảnh (b) `Axial-flow impeller` có 3 cánh dạng profile thủy động lực học.
  - **Hình 30.** Chi tiết cánh khuấy cơ học kiểu xuyên tâm và hướng trục trang bị cho bể khuấy nhanh
    - <img src="ch03_coagulation_flocculation/assets/fig_30_p34.jpeg" alt="Hình 30" />
    - **Hình này chứng minh điều gì**
      - Khẳng định sự lựa chọn cánh khuấy dòng xuyên tâm để tạo lực cắt thủy lực mạnh và cánh khuấy dòng hướng trục để luân chuyển khối tích bể nhanh.
    - **Từ đâu mà thấy được**
      - Cấu tạo trục đứng kết nối trực tiếp với đĩa cánh tuabin phẳng hoặc cụm 3 cánh cong hướng trục lắp trên trục xoay.
- Thiết bị khuấy trộn thủy lực kiểu vách ngăn (*Hydraulic mixers*):
  - Nguyên lý hoạt động: Tận dụng động năng và tổn thất cột áp thủy lực ($h_f$) của chính dòng nước khi chảy qua các vách ngăn zíc-zắc (up-and-down baffled basins) hoặc máng thu hẹp để tạo xoáy trộn mà không tiêu tốn điện năng cơ học.
  - Thông số thiết kế công trình: Chiều sâu lớp nước $H = 3{,}00\text{ m}$, vận tốc dòng chảy qua các ngăn $V \approx 0{,}50\text{ m/s}$, tổn thất áp lực $h_f$, bố trí cút khuỷu chuyển dòng tại đáy và các rãnh xả bùn định kỳ (*Drains*).
  - **Hình 29.** Cấu tạo mặt bằng và mặt cắt bể khuấy trộn thủy lực kiểu vách ngăn zíc-zắc
    - <img src="ch03_coagulation_flocculation/assets/fig_29_p33.png" alt="Hình 29" />
    - **Hình này chứng minh điều gì**
      - Thể hiện kích thước hình học mặt bằng ($B, L$) và mặt cắt đứng với chiều cao công tác $H = 3{,}00\text{ m}$, cút thu đáy và van xả cặn `Drains`.
    - **Từ đâu mà thấy được**
      - Bản vẽ mặt bằng hiển thị các khoang chữ nhật chiều rộng $B$, chiều dài $L$; bản vẽ mặt cắt hiển thị mực nước dốc $h_f$, $H = 3{,}00\text{ m}$, $V \approx 0{,}50\text{ m/s}$ và rãnh thu đáy `Drains`.
  - **Hình 31.** Sơ đồ dòng chảy thủy lực zíc-zắc qua các ngăn vách ngăn trong bể khuấy thủy lực
    - <img src="ch03_coagulation_flocculation/assets/fig_31_p34.png" alt="Hình 31" />
    - **Hình này chứng minh điều gì**
      - Mô tả quỹ đạo tuần hoàn nước lên - xuống liên tục nhằm tạo chuyển động xoáy xáo trộn tự nhiên trước khi thoát ra bể tạo bông.
    - **Từ đâu mà thấy được**
      - Các mũi tên đường dòng uốn lượn vượt đỉnh vách ngăn rồi chúc xuống đáy chui qua cút thu loe sang ngăn tiếp theo.
- Thiết bị khuấy cơ học trên đường ống kết hợp bơm phụ áp (*In-line mechanical mixer: pumped flash mixing*):
  - Nguyên lý hoạt động: Trích một phần lưu lượng nước thô đầu vào (*portion of influent flow*) qua bơm cao áp (*pump*), châm hóa chất keo tụ (*chemical*) trực tiếp vào đường ống áp lực cao và phun qua đĩa khuếch tán (*diffuser plate*) đặt tại tâm ống dẫn chính.
  - Dòng phản lực tốc độ cao đập vào đĩa khuếch tán tạo ra các vùng xoáy rối vi mô cực mạnh (*rapid mixing*), hòa trộn dung dịch phèn vào toàn bộ dòng nước thô chỉ trong thời gian dưới $1\text{ s}$.
  - Phương pháp này đặc biệt phù hợp cho cơ chế hấp phụ - trung hòa điện tích tức thời (*adsorption/destabilization*), không cần xây dựng cụm bể khuấy nhanh riêng biệt trên mặt đất.
  - **Hình 32.** Sơ đồ nguyên lý thiết bị khuấy nhanh trên đường ống kết hợp bơm phụ áp và đĩa khuếch tán
    - <img src="ch03_coagulation_flocculation/assets/fig_32_p35.jpeg" alt="Hình 32" />
    - **Hình này chứng minh điều gì**
      - Trình bày sơ đồ trích dòng nước thô qua bơm áp lực, hòa trộn hóa chất và phun vào tâm ống chính thông qua đĩa khuếch tán.
    - **Từ đâu mà thấy được**
      - Nhánh trích dòng qua `Pump`, đường dẫn `Chemical`, ống phun hướng tâm vào `Diffuser plate` tạo xoáy `Rapid mixing` và dòng ra `Mixed water and chemical`.
  - **Hình 34.** Chi tiết vòi phun và đĩa khuếch tán tạo xoáy trộn cưỡng bức trên đường ống áp lực
    - <img src="ch03_coagulation_flocculation/assets/fig_34_p36.jpeg" alt="Hình 34" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự hình thành vùng xoáy thủy lực đối xứng cục bộ ngay tại cửa xả của đĩa khuếch tán trong lòng đường ống.
    - **Từ đâu mà thấy được**
      - Cặp xoáy đối xứng `Rapid mixing` bao quanh `Diffuser plate` phân tán dòng hóa chất vào toàn bộ tiết diện nước thô.

#### 3.3.3 Thiết kế hệ thống bể tạo bông và cánh khuấy

##### 3.3.3.1 Hệ thống bể tạo bông cánh guồng trục ngang (Horizontal Paddle Flocculator)

- Cấu tạo và nguyên lý vận hành:
  - Bể tạo bông gồm chuỗi từ 2 đến 6 ngăn nối tiếp, ngăn cách nhau bằng vách ngăn đục lỗ (*Perforated baffle walls*) nhằm phân bố đều lưu lượng trên toàn bộ mặt cắt ướt và triệt tiêu dòng chảy tắt (*short-circuiting*).
  - Trục khuấy đặt nằm ngang song song hoặc vuông góc với hướng dòng nước, truyền động bằng cụm động cơ giảm tốc (*drive motor*). Trên trục gắn các guồng quay cánh phẳng gỗ hoặc thép composite quay chậm với tốc độ $1 - 5\text{ rpm}$.
  - Nước sau keo tụ chảy qua kênh phân phối (*Coagulated water channel*), lần lượt qua các khoang tạo bông rồi chuyển tiếp sang bể lắng (*Sedimentation basin*).
  - **Hình 33.** Mặt cắt dọc và mặt cắt ngang hệ thống bể tạo bông cánh guồng trục ngang
    - <img src="ch03_coagulation_flocculation/assets/fig_33_p35.png" alt="Hình 33" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu tạo 3 ngăn nối tiếp với cánh guồng quay chậm và vách ngăn đục lỗ chuyển tiếp sang bể lắng.
    - **Từ đâu mà thấy được**
      - Kênh vào `Coagulated water channel`, 3 guồng tròn có mũi tên quay, vách đục lỗ `Perforated baffle wall`, mặt cắt A-A có `Drive motor` và `Paddle wheel mixer`.
  - **Hình 35.** Bố trí 3 bậc khuấy tạo bông cánh guồng trục ngang nối tiếp qua các vách ngăn đục lỗ
    - <img src="ch03_coagulation_flocculation/assets/fig_35_p36.png" alt="Hình 35" />
    - **Hình này chứng minh điều gì**
      - Minh họa phương thức phân chia ngăn bằng vách ngăn đục lỗ nhằm tạo bông giảm bậc và ngăn xáo trộn ngược giữa các bậc.
    - **Từ đâu mà thấy được**
      - Dòng nước đi từ kênh nạp `Influent from coagulation` qua 3 guồng quay phân cách bằng `Perforated baffle wall` đến `Sedimentation basin`.
- Tiêu chuẩn so sánh thiết kế giữa Cánh guồng trục ngang và Tuabin trục đứng:
  | Thông số thiết kế (*Design Parameter*) | Đơn vị (*Unit*) | Cánh guồng trục ngang (*Horizontal Shaft with Paddles*) | Tuabin trục đứng (*Vertical-Shaft Turbines*) |
  | :--- | :--- | :--- | :--- |
  | Gradient vận tốc trung bình ($\bar{G}$) | $\text{s}^{-1}$ | $20 - 50$ | $10 - 80$ |
  | Vận tốc mút cánh cực đại ($T_s$ max) | $\text{m/s}$ | $1$ | $2 - 3$ |
  | Tốc độ quay trục ($N$) | $\text{rev/min}$ | $1 - 5$ | $10 - 30$ |
  | Kích thước mặt bằng một ngăn: Chiều rộng ($W$) | $\text{m}$ | $3 - 6$ | $6 - 30$ |
  | Kích thước mặt bằng một ngăn: Chiều dài ($L$) | $\text{m}$ | $3 - 6$ | $3 - 5$ |
  | Số lượng ngăn nối tiếp | Ngăn | $2 - 6$ | $4 - 6$ |
  | Bộ truyền động biến tần thay đổi tốc độ | — | Thường dùng (*Usually*) | Thường dùng (*Usually*) |
  - **Hình 36.** Bảng so sánh các thông số thiết kế điển hình giữa cánh guồng trục ngang và tuabin trục đứng
    - <img src="ch03_coagulation_flocculation/assets/fig_36_p37.png" alt="Hình 36" />
    - **Hình này chứng minh điều gì**
      - Đối chiếu trực quan các chỉ tiêu kỹ thuật: cánh guồng quay chậm ($1 - 5\text{ rpm}$, $T_s \le 1\text{ m/s}$), tuabin quay nhanh hơn ($10 - 30\text{ rpm}$, $T_s = 2 - 3\text{ m/s}$).
    - **Từ đâu mà thấy được**
      - Bảng 7 hàng so sánh trực tiếp giữa hai cột `Horizontal Shaft with Paddles` và `Vertical-Shaft Turbines`.
  - **Hình 38.** Thông số đối chiếu gradient vận tốc, vận tốc đầu cánh và kích thước ngăn tạo bông
    - <img src="ch03_coagulation_flocculation/assets/fig_38_p38.png" alt="Hình 38" />
    - **Hình này chứng minh điều gì**
      - Xác định kích thước mặt bằng ngăn bể: cánh guồng phù hợp ngăn hẹp $3 - 6\text{ m}$, tuabin trục đứng áp dụng được cho bể rộng tới $30\text{ m}$.
    - **Từ đâu mà thấy được**
      - Số liệu hàng `Compartment dimensions (plan)` ghi rõ `Width 3–6 m` vs `6–30 m`, `Length 3–6 m` vs `3–5 m`.
- Tiêu chuẩn thiết kế then chốt cho bể tạo bông cánh guồng trục ngang:
  | Thông số kỹ thuật (*Parameter*) | Đơn vị (*Unit*) | Giá trị thiết kế (*Value*) |
  | :--- | :--- | :--- |
  | Đường kính guồng quay (*Diameter of wheel*) | $\text{m}$ | $3 - 4$ |
  | Tiết diện thanh gạt (*Paddle board section*) | $\text{mm}$ | $100 \times 150$ |
  | Chiều dài thanh gạt (*Paddle board length*) | $\text{m}$ | $2 - 3{,}5$ |
  | Tỷ lệ diện tích cánh gạt / diện tích mặt cắt bể ($A_{\text{paddle}} / A_{\text{tank}}$) | $\%$ | $< 20\%$ |
  | Hệ số cản $C_D$ ($Re > 1000$): tỷ số $L/W = 1$ | — | $C_D = 1{,}16$ |
  | Hệ số cản $C_D$ ($Re > 1000$): tỷ số $L/W = 5$ | — | $C_D = 1{,}20$ |
  | Hệ số cản $C_D$ ($Re > 1000$): tỷ số $L/W = 20$ | — | $C_D = 1{,}50$ |
  | Hệ số cản $C_D$ ($Re > 1000$): tỷ số $L/W \gg 20$ | — | $C_D = 1{,}90$ |
  | Vận tốc đầu cánh gạt - Bông cặn bền vững (*Strong floc*) | $\text{m/s}$ | $4$ |
  | Vận tốc đầu cánh gạt - Bông cặn yếu dễ vỡ (*Weak floc*) | $\text{m/s}$ | $2$ |
  | Khoảng cách giữa các guồng trên cùng một trục | $\text{m}$ | $1$ |
  | Khoảng hở từ mép cánh đến thành bể | $\text{m}$ | $0{,}7$ |
  | Chiều sâu bể tối thiểu | $\text{m}$ | Lớn hơn đường kính guồng ít nhất $1\text{ m}$ |
  | Khoảng cách thông thủy tối thiểu giữa các bậc | $\text{m}$ | $1$ |
  - **Hình 37.** Bảng tiêu chuẩn thiết kế then chốt cho bể tạo bông cánh guồng trục ngang
    - <img src="ch03_coagulation_flocculation/assets/fig_37_p37.png" alt="Hình 37" />
    - **Hình này chứng minh điều gì**
      - Quy định chi tiết các kích thước hình học, giới hạn diện tích cản thủy lực $< 20\%$ và hệ số cản $C_D$ của cánh gạt.
    - **Từ đâu mà thấy được**
      - Bảng 10 thông số liệt kê đường kính guồng $3 - 4\text{ m}$, thanh gạt $100 \times 150\text{ mm}$, khoảng hở thành $0{,}7\text{ m}$, đáy bể sâu hơn guồng $1\text{ m}$.
  - **Hình 39.** Hệ số cản $C_D$ theo tỷ số hình học $L/W$ và các yêu cầu lắp đặt guồng quay trục ngang
    - <img src="ch03_coagulation_flocculation/assets/fig_39_p38.png" alt="Hình 39" />
    - **Hình này chứng minh điều gì**
      - Cung cấp tương quan giải tích của hệ số cản thủy lực $C_D$ tăng dần từ $1{,}16$ đến $1{,}90$ khi thanh gạt có tỷ số mảnh $L/W$ tăng cao.
    - **Từ đâu mà thấy được**
      - Hàng $C_D \text{ (see Eq. 5-32)}$ ghi rõ các bậc giá trị $1{,}16; 1{,}20; 1{,}50; 1{,}90$ tương ứng với $L/W = 1, 5, 20, \gg 20$.

##### 3.3.3.2 Hệ thống bể tạo bông cánh khuấy tuabin trục đứng (Vertical Turbine Flocculator)

- Cấu tạo và nguyên lý hoạt động:
  - Bể tạo bông gồm chuỗi từ 3 đến 6 ngăn hình vuông hoặc chữ nhật nối tiếp nhau, ngăn cách bằng vách ngăn đục lỗ nhằm ngăn dòng chảy tắt.
  - Mỗi ngăn trang bị một cụm truyền động độc lập gồm động cơ và hộp giảm tốc (*Drive motor and gearbox*) đặt trên cầu công tác, làm quay trục thẳng đứng gắn cánh khuấy tuabin cánh nghiêng (*Pitched-blade turbine - PBT*) hoặc cánh hydrofoil.
  - Cánh khuấy đẩy dòng chất lỏng theo phương thẳng đứng xuống đáy bể rồi cuộn ngược lên theo thành bể, tạo vòng tuần hoàn lớn giúp phân tán đều năng lượng khuấy trộn trên toàn bộ thể tích ngăn.
  - Việc lắp đặt động cơ riêng cho từng ngăn cho phép điều chỉnh tốc độ quay $N$ giảm dần theo chiều dòng chảy (tạo bông phân bậc: $G_1 > G_2 > G_3$).
  - **Hình 40.** Mặt cắt hệ thống bể tạo bông tuabin trục đứng nhiều ngăn và phối cảnh cánh tuabin cánh nghiêng
    - <img src="ch03_coagulation_flocculation/assets/fig_40_p39.png" alt="Hình 40" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu tạo bể 3 ngăn tạo bông trục đứng nối tiếp dẫn sang bể lắng và kết cấu cánh tuabin cánh nghiêng (PBT).
    - **Từ đâu mà thấy được**
      - Mặt cắt bể bên trái có 3 cụm `Drive motor and gearbox` gắn trục đứng; hình bên phải là phối cảnh `Pitched-blade turbine` 4 cánh nghiêng.
  - **Hình 42.** Sơ đồ chuỗi ngăn tạo bông tuabin trục đứng phân cách bằng vách đục lỗ
    - <img src="ch03_coagulation_flocculation/assets/fig_42_p40.png" alt="Hình 42" />
    - **Hình này chứng minh điều gì**
      - Minh họa phương thức vận hành độc lập của từng trục khuấy cho phép điều khiển linh hoạt gradient vận tốc $G$ theo từng bậc tạo bông.
    - **Từ đâu mà thấy được**
      - Các mũi tên quay biểu thị chuyển động của động cơ độc lập trên từng khoang và hướng chảy qua vách đục lỗ sang `Sedimentation basin`.
- Bảng chuẩn số công suất ($N_p$) và chuẩn số bơm ($N_q$) của các loại cánh khuấy công nghiệp thông dụng:
  | Kiểu cánh khuấy (*Impeller Type*) | Chuẩn số công suất ($N_p$) | Chuẩn số bơm ($N_q$) | Phạm vi ứng dụng (*Application*) |
  | :--- | :--- | :--- | :--- |
  | Tuabin cánh phẳng (Flat-bladed turbine - FBT) | $3{,}6$ | $0{,}90$ | Trộn đều, duy trì huyền phù, tạo bông cặn |
  | Tuabin cánh nghiêng $45^\circ$ ($45^\circ$ PBT) | $1{,}26$ | $0{,}75$ | Trộn đều, duy trì huyền phù, tạo bông cặn |
  | Cánh hydrofoil uốn cong 3 cánh (*Hydrofoil, 3 blades*) | $0{,}2 - 0{,}3$ | $0{,}45 - 0{,}55$ | Trộn đều, duy trì huyền phù, tạo bông cặn |
  | Cánh đúc có gờ viền (*Cast foil with proplets*) | $0{,}23$ | $0{,}59$ | Trộn chất lỏng có độ nhớt |
  | Tuabin Rushton 6 cánh (*Rushton turbine, 6 blades*) | $4{,}5 - 5{,}5$ | $0{,}72$ | Phân tán khí - lỏng, huyền phù hạt rắn, tạo bông |
  | Cánh chân vịt bước 1:1 (*Propeller, pitch 1:1*) | $0{,}32 - 0{,}36$ | $0{,}40$ | Trộn chất lỏng có độ nhớt |
  - So sánh hiệu quả năng lượng: Cánh khuấy hydrofoil và tuabin cánh nghiêng $45^\circ$ PBT có chuẩn số công suất $N_p$ rất thấp ($0{,}2 - 1{,}26$) nhưng chuẩn số bơm $N_q$ rất cao ($0{,}45 - 0{,}75$), giúp tuần hoàn lưu lượng chất lỏng lớn mà tiêu thụ ít điện năng và tạo lực cắt thủy lực êm dịu, không làm vỡ bông cặn.
  - Ngược lại, tuabin Rushton ($N_p = 4{,}5 - 5{,}5$) và tuabin cánh phẳng FBT ($N_p = 3{,}6$) tạo lực cắt cục bộ rất lớn, chỉ thích hợp cho giai đoạn khuấy nhanh hoặc huyền phù hạt nặng.
  - **Hình 41.** Bảng chuẩn số công suất ($N_p$) và chuẩn số bơm ($N_q$) của các loại cánh khuấy công nghiệp
    - <img src="ch03_coagulation_flocculation/assets/fig_41_p39.png" alt="Hình 41" />
    - **Hình này chứng minh điều gì**
      - Định lượng chuẩn số $N_p$ và $N_q$ kèm hình ảnh thực tế của 6 loại cánh khuấy để tính toán công suất động cơ và lưu lượng tuần hoàn.
    - **Từ đâu mà thấy được**
      - Bảng gồm cột tên cánh, ảnh chụp `Photograph`, cột số liệu $N_p$, $N_q$ và ứng dụng công nghệ tương ứng.
  - **Hình 43.** Đặc tính thủy lực và hình thái cánh khuấy FBT, PBT, Hydrofoil và Rushton
    - <img src="ch03_coagulation_flocculation/assets/fig_43_p40.png" alt="Hình 43" />
    - **Hình này chứng minh điều gì**
      - Xác nhận cánh hydrofoil 3 cánh và $45^\circ$ PBT là lựa chọn hàng đầu cho tạo bông nhờ tỷ số $N_q/N_p$ vượt trội.
    - **Từ đâu mà thấy được**
      - Hàng 2 và 3 đối chiếu giá trị $N_p = 1{,}26$ (PBT) và $0{,}2 - 0{,}3$ (Hydrofoil) với $N_p = 4{,}5 - 5{,}5$ của Rushton turbine.
- Tiêu chuẩn bố trí hình học và kích thước cánh khuấy trục đứng:
  | Thông số hình học (*Parameter*) | Khoảng giá trị (*Range*) | Ghi chú thiết kế |
  | :--- | :--- | :--- |
  | Kiểu cánh khuấy (*Impeller*) | Hydrofoil hoặc $45^\circ$ PBT | Ưu tiên dùng Hydrofoil (*hydrofoil preferred*) |
  | Tỷ số đường kính cánh / bể ($D/T_e$) | $0{,}3 - 0{,}6$ | Ưu tiên dải $0{,}4 - 0{,}5$ (*preferred*) |
  | Tỷ số chiều sâu nước / đường kính bể ($H/T_e$) | $0{,}9 - 1{,}1$ | Ngăn bể có dạng gần lập phương |
  | Tỷ số khoảng hở đáy / chiều sâu nước ($C/H$) | $0{,}5 - 0{,}33$ | Tâm cánh khuấy cách đáy bể từ $1/3$ đến $1/2$ chiều sâu nước |
  | Tốc độ quay của cánh khuấy ($N$) | $10 - 30\text{ rev/min}$ | Điều chỉnh theo yêu cầu gradient vận tốc từng ngăn |
  | Vận tốc mút cánh khuấy (*Tip speed*) | $2 - 3\text{ m/s}$ | Giới hạn tối đa chống vỡ bông cặn |
  - Công thức xác định đường kính tương đương bể ($T_e$):
    $$T_e = \sqrt{\frac{4 \cdot A_{\text{plan}}}{\pi}}$$
    Trong đó $A_{\text{plan}}$ là diện tích mặt bằng của một ngăn tạo bông ($\text{m}^2$).
  - **Hình 44.** Tiêu chí thiết kế và sơ đồ định nghĩa kích thước cánh khuấy trục đứng
    - <img src="ch03_coagulation_flocculation/assets/fig_44_p41.png" alt="Hình 44" />
    - **Hình này chứng minh điều gì**
      - Thiết lập quan hệ kích thước lắp đặt cánh khuấy trong bể: $D/T_e$, $H/T_e$, $C/H$ và giới hạn vận tốc mút cánh $2 - 3\text{ m/s}$.
    - **Từ đâu mà thấy được**
      - Sơ đồ `Definition Sketch` vẽ mặt cắt bể với các ký hiệu $H, C, D, T_e$ bên cạnh bảng số liệu 6 thông số thiết kế.
  - **Hình 45.** Sơ đồ định hình kích thước và công thức quy đổi đường kính tương đương $T_e$
    - <img src="ch03_coagulation_flocculation/assets/fig_45_p42.png" alt="Hình 45" />
    - **Hình này chứng minh điều gì**
      - Cung cấp công thức chân trang tính đường kính tương đương $T_e = \sqrt{4A_{\text{plan}}/\pi}$ cho các ngăn bể không tròn.
    - **Từ đâu mà thấy được**
      - Ghi chú chân bảng $^a T_e = \sqrt{4A_{\text{plan}}/\pi}$ và hình vẽ cánh khuấy quay trong bể có chiều sâu $H$, khoảng hở $C$.

##### 3.3.3.3 Năm tiêu chí thủy lực định cỡ và lựa chọn cánh khuấy trục đứng

- Danh mục 5 tiêu chuẩn thủy lực bắt buộc trong tính toán và lựa chọn cánh khuấy trục đứng:
  - 1. Độ nhớt chất lỏng ($\mu$ - *Viscosity*)
  - 2. Gradient vận tốc ($G$ - *Velocity gradient*)
  - 3. Vận tốc đầu mút cánh khuấy ($T_s$ - *Impeller tip speed*)
  - 4. Vận tốc bề mặt qua bể ($SV$ - *Superficial velocity*)
  - 5. Tỷ số đường kính cánh khuấy trên đường kính bể ($D/T_e$ - *Ratio of impeller diameter to tank diameter*)

- Chi tiết Tiêu chuẩn 1 & 2: Độ nhớt ($\mu$) và Gradient vận tốc ($G$):
  - Định nghĩa gradient vận tốc: Là độ biến thiên vận tốc tương đối giữa các lớp chất lỏng kế cận trên một đơn vị khoảng cách, phản ánh năng lượng xáo trộn đưa vào khối nước.
  - Dải giá trị công nghệ tạo bông: $G = 20 - 80\text{ s}^{-1}$.
  - Phương trình tính toán năng lượng và gradient vận tốc:
    $$P = \mu \cdot V \cdot G^2 \implies G = \sqrt{\frac{P}{\mu \cdot V}}$$
  - Ảnh hưởng của độ nhớt động lực học ($\mu$): Độ nhớt thay đổi mạnh theo nhiệt độ nguồn nước. Nước có nhiệt độ càng thấp thì độ nhớt $\mu$ càng lớn, đòi hỏi công suất truyền động $P$ phải tăng tương ứng để duy trì gradient vận tốc $G$ theo thiết kế.

- Chi tiết Tiêu chuẩn 3: Vận tốc đầu mút cánh khuấy ($T_s$ - *Impeller tip speed*):
  - Ý nghĩa vật lý: Vận tốc dài lớn nhất xuất hiện tại mút ngoài cùng của cánh khuấy, quyết định ứng suất cắt cục bộ cực đại tác dụng lên các bông cặn keo tụ. Nếu $T_s$ vượt ngưỡng cho phép, lực cắt sẽ xé rách các bông cặn vừa hình thành.
  - Ngưỡng vận tốc cực đại cho phép:
    - Cánh khuấy hydrofoil 3 hoặc 4 cánh: $T_s \le 2{,}4\text{ m/s}$.
    - Tuabin cánh nghiêng $32^\circ$ hoặc $45^\circ$ ($45^\circ$ PBT): $T_s \le 2{,}1\text{ m/s}$.
  - Công thức tính vận tốc đầu mút cánh khuấy:
    $$T_s = \frac{\pi \cdot N \cdot D}{60}$$
    Trong đó:
    - $N$: Tốc độ quay của cánh khuấy ($\text{rev/min}$).
    - $D$: Đường kính cánh khuấy ($\text{m}$).
    - $T_s$: Vận tốc đầu mút cánh khuấy ($\text{m/s}$).

- Chi tiết Tiêu chuẩn 5: Tỷ số đường kính cánh khuấy trên đường kính bể ($D/T_e$):
  - Cơ sở thủy lực: Cánh khuấy có đường kính lớn ($D$ lớn) tạo ra sự dịch chuyển của toàn bộ khối chất lỏng (*bulk fluid motion*) và phân tán công suất tiêu thụ trên một diện tích mặt bằng rộng lớn.
  - Vận hành ở tốc độ quay $N$ thấp kết hợp đường kính lớn giúp giảm thiểu ứng suất cắt gây hại cho bông cặn trong khi vẫn duy trì lưu lượng tuần hoàn cao.
  - Phạm vi tỷ số thiết kế tối ưu:
    $$\frac{D}{T_e} = 0{,}35 - 0{,}40$$
    (Nằm trong dải dung sai tổng quát $0{,}3 - 0{,}6$).
  - Công thức tính đường kính tương đương $T_e$ cho ngăn bể tiết diện chữ nhật hoặc vuông:
    $$T_e = 1{,}13 \cdot (L \cdot W)^{0{,}5} = 1{,}13 \cdot \sqrt{L \cdot W}$$
    (Suy từ $T_e = \sqrt{\frac{4 \cdot L \cdot W}{\pi}} = \frac{2}{\sqrt{\pi}} \cdot \sqrt{L \cdot W} \approx 1{,}1284 \cdot \sqrt{L \cdot W} \approx 1{,}13 \cdot \sqrt{L \cdot W}$).
    Trong đó:
    - $L$: Chiều dài ngăn bể ($\text{m}$).
    - $W$: Chiều rộng ngăn bể ($\text{m}$).
    - $T_e$: Đường kính tương đương quy đổi của ngăn bể ($\text{m}$).

- Chi tiết Tiêu chuẩn 4: Vận tốc bề mặt qua bể ($SV$ - *Superficial velocity*):
  - Định nghĩa: Vận tốc bề mặt là vận tốc trung bình của dòng chất lỏng lưu thông qua toàn bộ diện tích mặt cắt ngang của ngăn bể tạo bông.
  - Tiêu chuẩn chống lắng đọng bông cặn: Cánh khuấy phải được thiết kế và định cỡ để đảm bảo vận tốc bề mặt tối thiểu:
    $$SV \ge 0{,}015\text{ m/s}$$
    ngay tại tốc độ quay thấp nhất của dải vận hành. Vận tốc này đảm bảo toàn bộ hạt bông cặn trong bể luôn ở trạng thái lơ lửng, chuyển động nhẹ nhàng và triệt tiêu hoàn toàn các "vùng chết" (*dead zone*) lắng đọng bùn sớm trong ngăn tạo bông.
  - Công thức xác định vận tốc bề mặt $SV$:
    $$SV = \frac{N_q \cdot N \cdot D^3}{60 \cdot L \cdot W}$$
  - Cơ sở suy dẫn từ chuẩn số bơm $N_q$:
    $$N_q = \frac{Q}{N \cdot D^3} \implies Q = N_q \cdot \left(\frac{N}{60}\right) \cdot D^3$$
    Vì lưu lượng tuần hoàn qua mặt cắt diện tích bể là $Q = SV \cdot (L \cdot W)$, suy ra:
    $$SV = \frac{Q}{L \cdot W} = \frac{N_q \cdot N \cdot D^3}{60 \cdot L \cdot W}$$
    Trong đó:
    - $N_q$: Chuẩn số bơm / lưu lượng của cánh khuấy (không thứ nguyên).
    - $N$: Tốc độ quay của cánh khuấy ($\text{rev/min}$).
    - $D$: Đường kính cánh khuấy ($\text{m}$).
    - $L$: Chiều dài ngăn bể ($\text{m}$).
    - $W$: Chiều rộng ngăn bể ($\text{m}$).
    - $SV$: Vận tốc bề mặt ($\text{m/s}$).

### 3.4 Bài toán tính toán và Thiết kế công trình

- Các bài toán kỹ thuật trong công nghệ keo tụ - tạo bông bao gồm 4 nhóm tính toán cốt lõi:
  - Định lượng hóa chất keo tụ, cân bằng độ kiềm và xác định khối lượng cặn bùn hóa lý sinh ra.
  - Thiết kế công trình và cánh khuấy cho bể khuấy nhanh thủy lực hoặc cơ học (Flash Mixing Basin).
  - Thiết kế công trình và tính toán thủy động lực học cho bể tạo bông tuabin trục đứng (Vertical Turbine Flocculator).
  - Thiết kế hình học, xác định mô-men xoắn và công suất tiêu hao cho bể tạo bông cánh guồng trục ngang nhiều bậc (Horizontal-Shaft Paddle Wheel Flocculator).
- Tiêu chuẩn tính toán bám sát các phương trình lý thuyết thủy lực Camp-Stein, động học thủy động lực học cánh khuấy và quy chuẩn cân bằng hóa học môi trường.

#### 3.4.1 Tính toán liều lượng hóa chất và tiêu thụ độ kiềm

- Định lượng hóa chất keo tụ dựa trên phản ứng thủy phân và phản ứng kết tủa với các ion bicarbonate tự nhiên trong nước:
  - Phèn sắt clorua ($\text{FeCl}_3$) tiêu thụ độ kiềm theo tỷ lệ hóa học $2\text{ mol FeCl}_3 : 3\text{ mol Ca(HCO}_3)_2$ (tương đương $3\text{ mol CaCO}_3$).
  - Phèn nhôm sunfat ($\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$) tiêu thụ độ kiềm theo tỷ lệ $1\text{ mol alum} : 3\text{ mol Ca(HCO}_3)_2$ (tương đương $3\text{ mol CaCO}_3$).
  - Khi nước thô có độ kiềm tự nhiên không đủ để trung hòa lượng axit giải phóng, cần bổ sung kiềm nhân tạo bằng vôi tôi ($\text{Ca(OH)}_2$), vôi sống ($\text{CaO}$), hoặc xút ($\text{NaOH}$).
  - Nồng độ hóa chất đậm đặc dự trữ thương phẩm được biểu diễn theo phần trăm khối lượng ($\%$) hoặc khối lượng thể tích ($\text{g/L}$), từ đó xác định lưu lượng bơm định lượng châm vào dòng nước thô.
  - Lượng cặn bùn hidroxit kim loại sinh ra phụ thuộc vào lượng phèn đưa vào phản ứng và độ ẩm của bông cặn lắng.

##### Example 3-1: Độ kiềm tự nhiên cần thiết cho phản ứng keo tụ với FeCl3 (WaWC 373)
- **Đề bài**: (WaWC, 373) Lượng độ kiềm tự nhiên cần thiết (tính theo $\text{mg/L as }\text{CaCO}_3$) cho quá trình keo tụ nước thô với liều lượng $15{,}0\text{ mg/L}$ phèn sắt clorua ($\text{FeCl}_3$) là bao nhiêu?
- **Dữ kiện**
  - Liều lượng phèn sắt khan: $C_{\text{dose}} = 15{,}0\text{ mg/L}$ ($\text{FeCl}_3$).
  - Khối lượng mol của $\text{FeCl}_3$: $M_{\text{FeCl}_3} = 162{,}20\text{ g/mol}$.
  - Khối lượng mol tương đương của $\text{CaCO}_3$: $M_{\text{CaCO}_3} = 100{,}09\text{ g/mol}$.
- **Quy tắc áp dụng**
  - Phương trình hóa học của phản ứng keo tụ phèn sắt trong nước chứa độ kiềm tự nhiên:
    $$2\text{FeCl}_3 + 3\text{Ca(HCO}_3)_2 \rightarrow 2\text{Fe(OH)}_3\downarrow + 3\text{CaCl}_2 + 6\text{CO}_2$$
  - Phương trình ion thu gọn:
    $$\text{Fe}^{3+} + 3\text{HCO}_3^- \rightarrow \text{Fe(OH)}_3\downarrow + 3\text{CO}_2$$
  - Tỷ số khối lượng tiêu thụ độ kiềm lý thuyết:
    $$\text{Tỷ lệ} = \frac{3 \cdot M_{\text{CaCO}_3}}{2 \cdot M_{\text{FeCl}_3}} = \frac{3 \times 100{,}09}{2 \times 162{,}20} = \frac{300{,}27}{324{,}40} \approx 0{,}9256\text{ mg CaCO}_3\text{/mg FeCl}_3$$
- **Lời giải**
  - **Bước 1**: Xác định tỷ lệ hóa học giữa $\text{FeCl}_3$ và độ kiềm bicarbonate quy đổi theo $\text{CaCO}_3$.
    - Căn cứ: Cứ $2\text{ mol FeCl}_3$ ($324{,}40\text{ g}$) phản ứng tiêu thụ hết $3\text{ mol Ca(HCO}_3)_2$, tương đương về mặt trung hòa với $3\text{ mol CaCO}_3$ ($300{,}27\text{ g as }\text{CaCO}_3$).
    - Nhìn vào: Hệ số phản ứng và khối lượng mol phân tử từ phương trình hóa học.
    - Thực hiện: Tỷ số tiêu thụ kiềm là $\frac{300{,}27}{324{,}40} = 0{,}9256\text{ mg CaCO}_3\text{/mg FeCl}_3$.
  - **Bước 2**: Tính độ kiềm tự nhiên cần thiết để phản ứng hoàn toàn với liều phèn sắt.
    - Căn cứ: Công thức tính nhu cầu độ kiềm: $\text{Alk}_{\text{req}} = C_{\text{dose, FeCl}_3} \times 0{,}9256$.
    - Nhìn vào: Liều lượng châm phèn sắt $C_{\text{dose}} = 15{,}0\text{ mg/L}$ từ đề bài (slide 47).
    - Thực hiện:
      $$\text{Alk}_{\text{req}} = 15{,}0\text{ mg/L} \times 0{,}9256 = 13{,}88\text{ mg/L as }\text{CaCO}_3 \approx 13{,}9\text{ mg/L as }\text{CaCO}_3$$
- **Kết quả**: 
  - Độ kiềm tự nhiên cần thiết tối thiểu: $13{,}88\text{ mg/L as }\text{CaCO}_3$ (xấp xỉ $13{,}9\text{ mg/L as }\text{CaCO}_3$).
- **Kiểm tra lại**:
  - Tính theo nồng độ đương lượng: $15{,}0\text{ mg/L} / (162{,}20 / 3\text{ mg/meq}) = 15{,}0 / 54{,}07 = 0{,}2774\text{ meq/L}$.
  - Độ kiềm tương đương: $0{,}2774\text{ meq/L} \times 50{,}04\text{ mg/meq} = 13{,}88\text{ mg/L as }\text{CaCO}_3$. Kết quả hoàn toàn trùng khớp.

---

##### Example 3-2: Liều lượng vôi cần thiết bổ sung độ kiềm khi keo tụ bằng phèn nhôm (WaWC 374)
- **Đề bài**: (WaWC, 374) Nước thô có độ kiềm thấp là $12{,}0\text{ mg/L as }\text{CaCO}_3$ được xử lý bằng quá trình keo tụ kết hợp phèn nhôm - vôi. Liều lượng phèn nhôm sử dụng là $55{,}0\text{ mg/L}$. Hãy xác định liều lượng vôi cần thiết bổ sung để phản ứng với phèn nhôm.
- **Dữ kiện**
  - Độ kiềm tự nhiên ban đầu của nước thô: $\text{Alk}_{\text{raw}} = 12{,}0\text{ mg/L as }\text{CaCO}_3$.
  - Liều lượng phèn nhôm thương phẩm ($\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$): $C_{\text{alum}} = 55{,}0\text{ mg/L}$.
  - Khối lượng mol phèn nhôm: $M_{\text{alum}} = 594{,}38\text{ g/mol}$.
  - Khối lượng mol $\text{CaCO}_3$: $M_{\text{CaCO}_3} = 100{,}09\text{ g/mol}$.
  - Khối lượng mol vôi tôi $\text{Ca(OH)}_2$: $M_{\text{Ca(OH)}_2} = 74{,}09\text{ g/mol}$.
  - Khối lượng mol vôi sống $\text{CaO}$: $M_{\text{CaO}} = 56{,}08\text{ g/mol}$.
- **Quy tắc áp dụng**
  - Phản ứng thủy phân của phèn nhôm với độ kiềm tự nhiên:
    $$\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O} + 3\text{Ca(HCO}_3)_2 \rightarrow 2\text{Al(OH)}_3\downarrow + 3\text{CaSO}_4 + 6\text{CO}_2 + 14\text{H}_2\text{O}$$
    - $1\text{ mol}$ phèn nhôm ($594{,}38\text{ g}$) tiêu thụ $3\text{ mol CaCO}_3$ đương lượng ($300{,}27\text{ g as }\text{CaCO}_3$).
    - Tỷ lệ tiêu thụ độ kiềm lý thuyết:
      $$\text{Tỷ lệ demand} = \frac{3 \cdot M_{\text{CaCO}_3}}{M_{\text{alum}}} = \frac{300{,}27}{594{,}38} \approx 0{,}5052\text{ mg CaCO}_3\text{/mg alum}$$
  - Lượng độ kiềm thiếu hụt cần bổ sung:
    $$\Delta\text{Alk} = \text{Alk}_{\text{req}} - \text{Alk}_{\text{raw}}$$
  - Phản ứng trung hòa bổ sung bằng vôi tôi:
    $$\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O} + 3\text{Ca(OH)}_2 \rightarrow 2\text{Al(OH)}_3\downarrow + 3\text{CaSO}_4 + 14\text{H}_2\text{O}$$
    - Hệ số quy đổi vôi tôi: $\frac{M_{\text{Ca(OH)}_2}}{M_{\text{CaCO}_3}} = \frac{74{,}09}{100{,}09} = 0{,}7402\text{ mg Ca(OH)}_2\text{/mg CaCO}_3$.
    - Hệ số quy đổi vôi sống: $\frac{M_{\text{CaO}}}{M_{\text{CaCO}_3}} = \frac{56{,}08}{100{,}09} = 0{,}5603\text{ mg CaO/mg CaCO}_3$.
- **Lời giải**
  - **Bước 1**: Tính tổng lượng độ kiềm cần thiết cho $55{,}0\text{ mg/L}$ phèn nhôm.
    - Căn cứ: Tỷ số tiêu thụ độ kiềm lý thuyết $0{,}5052\text{ mg CaCO}_3/\text{mg alum}$.
    - Nhìn vào: Liều lượng phèn nhôm $C_{\text{alum}} = 55{,}0\text{ mg/L}$ trên slide 47.
    - Thực hiện:
      $$\text{Alk}_{\text{req}} = 55{,}0\text{ mg/L} \times 0{,}5052 = 27{,}78\text{ mg/L as }\text{CaCO}_3$$
  - **Bước 2**: Xác định lượng độ kiềm thiếu hụt trong nước thô.
    - Căn cứ: Độ kiềm tự nhiên hiện có của nước thô $\text{Alk}_{\text{raw}} = 12{,}0\text{ mg/L as }\text{CaCO}_3$.
    - Nhìn vào: Chênh lệch giữa nhu cầu và lượng có sẵn:
      $$\Delta\text{Alk} = 27{,}78\text{ mg/L} - 12{,}0\text{ mg/L} = 15{,}78\text{ mg/L as }\text{CaCO}_3$$
  - **Bước 3**: Tính toán liều lượng vôi cần bổ sung.
    - Căn cứ: Hệ số đương lượng hóa học giữa vôi và $\text{CaCO}_3$.
    - Nhìn vào: Lượng độ kiềm thiếu hụt $\Delta\text{Alk} = 15{,}78\text{ mg/L as }\text{CaCO}_3$.
    - Thực hiện:
      - Tính theo vôi tôi nguyên chất $\text{Ca(OH)}_2$:
        $$\text{Liều Ca(OH)}_2 = 15{,}78\text{ mg/L} \times 0{,}7402 = 11{,}68\text{ mg/L}$$
      - Tính theo vôi sống nguyên chất $\text{CaO}$:
        $$\text{Liều CaO} = 15{,}78\text{ mg/L} \times 0{,}5603 = 8{,}84\text{ mg/L}$$
      - *(Ghi chú kỹ thuật)*: Nếu trạm xử lý yêu cầu duy trì độ kiềm đệm dư tối thiểu sau xử lý là $10{,}0\text{ mg/L as }\text{CaCO}_3$ để bảo đảm pH ổn định, tổng độ kiềm cần đáp ứng là $27{,}78 + 10{,}0 = 37{,}78\text{ mg/L as }\text{CaCO}_3$, khi đó lượng thiếu hụt là $25{,}78\text{ mg/L}$, đòi hỏi liều vôi tôi là $25{,}78 \times 0{,}7402 = 19{,}08\text{ mg/L Ca(OH)}_2$.
- **Kết quả**: 
  - Liều lượng vôi tôi nguyên chất $\text{Ca(OH)}_2$ cần bổ sung theo tỷ lượng phản ứng: $11{,}68\text{ mg/L}$.
  - Hoặc tính theo vôi sống nguyên chất $\text{CaO}$: $8{,}84\text{ mg/L}$.
- **Kiểm tra lại**:
  - $11{,}68\text{ mg/L Ca(OH)}_2$ cung cấp: $11{,}68 / 74{,}09 \times 100{,}09 = 15{,}78\text{ mg/L as }\text{CaCO}_3$.
  - Tổng độ kiềm trong nước sau châm vôi: $12{,}0 + 15{,}78 = 27{,}78\text{ mg/L as }\text{CaCO}_3$, vừa đủ trung hòa hoàn toàn $55{,}0\text{ mg/L}$ phèn nhôm.

---

##### Example 3-3: Nồng độ phèn dự trữ, lưu lượng châm, tiêu thụ kiềm và lượng cặn sinh ra (PoWT 153)
- **Đề bài**: (PoWT, 153) Nhà cung cấp hóa chất công bố nồng độ dung dịch phèn nhôm dự trữ là $8{,}37\%$ theo $\text{Al}_2\text{O}_3$ với tỷ trọng $\text{SG} = 1{,}32$. Đối với dung dịch phèn dự trữ này, hãy tính:
  - (a) Nồng độ mol của ion $\text{Al}^{3+}$.
  - (b) Nồng độ dung dịch phèn biểu diễn theo $\text{g/L Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$.
  - Đối với liều lượng phèn $30{,}0\text{ mg/L}$ châm vào trạm xử lý nước có công suất $0{,}5\text{ m}^3\text{/s}$, hãy tính:
  - (c) Lưu lượng châm hóa chất phèn theo $\text{L/min}$.
  - (d) Lượng độ kiềm bị tiêu thụ (biểu diễn theo $\text{mg/L as }\text{CaCO}_3$).
  - (e) Khối lượng kết tủa sinh ra tính theo $\text{mg/L}$ và $\text{kg/ngày}$.
- **Dữ kiện**
  - Hàm lượng phần trăm khối lượng $\text{Al}_2\text{O}_3$ trong dung dịch dự trữ: $w = 8{,}37\% = 0{,}0837$.
  - Tỷ trọng dung dịch phèn dự trữ: $\text{SG} = 1{,}32 \implies \rho_{\text{sol}} = 1{,}32 \times 1000\text{ g/L} = 1320\text{ g/L}$.
  - Liều lượng phèn nhôm châm vào nước: $C_{\text{dose}} = 30{,}0\text{ mg/L}$ dạng $\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$.
  - Công suất xử lý của nhà máy nước: $Q = 0{,}5\text{ m}^3\text{/s} = 500\text{ L/s} = 30\,000\text{ L/min} = 43\,200\text{ m}^3\text{/ngày}$.
  - Khối lượng mol các chất:
    - $M_{\text{Al}_2\text{O}_3} = 101{,}96\text{ g/mol}$.
    - $M_{\text{alum}} = M_{\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}} = 594{,}38\text{ g/mol}$.
    - $M_{\text{Al(OH)}_3} = 78{,}01\text{ g/mol}$.
    - $M_{\text{CaCO}_3} = 100{,}09\text{ g/mol}$.
- **Quy tắc áp dụng**
  - Nồng độ khối lượng $\text{Al}_2\text{O}_3$ trong dung dịch: $C_{\text{Al}_2\text{O}_3} = w \cdot \rho_{\text{sol}}$.
  - Nồng độ mol ion $\text{Al}^{3+}$: $[\text{Al}^{3+}] = 2 \cdot \frac{C_{\text{Al}_2\text{O}_3}}{M_{\text{Al}_2\text{O}_3}}$ (vì $1\text{ mol Al}_2\text{O}_3$ chứa $2\text{ mol Al}^{3+}$).
  - Nồng độ phèn thương phẩm: $C_{\text{alum}} = \frac{C_{\text{Al}_2\text{O}_3}}{M_{\text{Al}_2\text{O}_3}} \cdot M_{\text{alum}}$.
  - Lưu lượng bơm định lượng hóa chất: $q_{\text{feed}} = \frac{Q \cdot C_{\text{dose}}}{C_{\text{alum}}}$.
  - Tiêu thụ độ kiềm: $\text{Alk}_{\text{consumed}} = C_{\text{dose}} \cdot \frac{3 \cdot M_{\text{CaCO}_3}}{M_{\text{alum}}}$.
  - Khối lượng kết tủa $\text{Al(OH)}_3$ khô sinh ra: $C_{\text{precipitate}} = C_{\text{dose}} \cdot \frac{2 \cdot M_{\text{Al(OH)}_3}}{M_{\text{alum}}}$.
- **Lời giải**
  - **Bước 1**: Tính nồng độ khối lượng $\text{Al}_2\text{O}_3$ và nồng độ mol ion $\text{Al}^{3+}$ (câu a).
    - Căn cứ: Nồng độ phần trăm $w = 8{,}37\%$, tỷ trọng dung dịch $1{,}32$, khối lượng mol $M_{\text{Al}_2\text{O}_3} = 101{,}96\text{ g/mol}$.
    - Nhìn vào: Khối lượng $\text{Al}_2\text{O}_3$ trong $1\text{ L}$ dung dịch là:
      $$C_{\text{Al}_2\text{O}_3} = 0{,}0837 \times 1320\text{ g/L} = 110{,}484\text{ g/L}$$
    - Thực hiện:
      $$[\text{Al}_2\text{O}_3] = \frac{110{,}484\text{ g/L}}{101{,}96\text{ g/mol}} = 1{,}0836\text{ mol/L}$$
      $$[\text{Al}^{3+}] = 2 \times 1{,}0836\text{ mol/L} = 2{,}167\text{ mol/L} \approx 2{,}17\text{ M}$$
  - **Bước 2**: Tính nồng độ phèn thương phẩm dạng $\text{Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$ (câu b).
    - Căn cứ: $1\text{ mol Al}_2\text{O}_3$ tương ứng với $1\text{ mol Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$ ($594{,}38\text{ g/mol}$).
    - Nhìn vào: Số mol phèn trong một lít dung dịch bằng số mol $\text{Al}_2\text{O}_3$ ($1{,}0836\text{ mol/L}$).
    - Thực hiện:
      $$C_{\text{alum}} = 1{,}0836\text{ mol/L} \times 594{,}38\text{ g/mol} = 644{,}08\text{ g/L} \approx 644{,}1\text{ g/L}$$
  - **Bước 3**: Tính lưu lượng châm hóa chất phèn (câu c).
    - Căn cứ: Công suất nhà máy $Q = 0{,}5\text{ m}^3\text{/s} = 30\,000\text{ L/min}$, liều châm $30{,}0\text{ mg/L} = 0{,}030\text{ g/L}$.
    - Nhìn vào: Tốc độ khối lượng phèn tiêu thụ mỗi phút:
      $$\dot{m}_{\text{alum}} = 30\,000\text{ L/min} \times 0{,}030\text{ g/L} = 900\text{ g/min}$$
    - Thực hiện:
      $$q_{\text{feed}} = \frac{900\text{ g/min}}{644{,}08\text{ g/L}} = 1{,}397\text{ L/min} \approx 1{,}40\text{ L/min}\text{ (tương đương } 23{,}29\text{ mL/s)}$$
  - **Bước 4**: Tính lượng độ kiềm bị tiêu thụ (câu d).
    - Căn cứ: Tỷ số tiêu thụ độ kiềm lý thuyết $\frac{3 \times 100{,}09}{594{,}38} = 0{,}5052\text{ mg CaCO}_3\text{/mg alum}$.
    - Nhìn vào: Liều phèn châm $C_{\text{dose}} = 30{,}0\text{ mg/L}$.
    - Thực hiện:
      $$\text{Alk}_{\text{consumed}} = 30{,}0\text{ mg/L} \times 0{,}5052 = 15{,}16\text{ mg/L as }\text{CaCO}_3 \approx 15{,}2\text{ mg/L as }\text{CaCO}_3$$
  - **Bước 5**: Tính lượng cặn kết tủa hidroxit nhôm $\text{Al(OH)}_3$ sinh ra (câu e).
    - Căn cứ: $1\text{ mol phèn nhôm}$ sinh ra $2\text{ mol Al(OH)}_3$. Tỷ lệ khối lượng: $\frac{2 \times 78{,}01}{594{,}38} = \frac{156{,}02}{594{,}38} = 0{,}2625\text{ mg Al(OH)}_3\text{/mg alum}$.
    - Nhìn vào: Liều phèn $30{,}0\text{ mg/L}$ và lưu lượng ngày $Q_{\text{day}} = 43\,200\text{ m}^3\text{/ngày}$.
    - Thực hiện:
      - Nồng độ kết tủa cặn trong nước:
        $$C_{\text{sludge}} = 30{,}0\text{ mg/L} \times 0{,}2625 = 7{,}875\text{ mg/L} \approx 7{,}88\text{ mg/L}$$
      - Khối lượng cặn khô sinh ra mỗi ngày:
        $$M_{\text{sludge}} = 43\,200\text{ m}^3\text{/ngày} \times 7{,}875\text{ g/m}^3 \times 10^{-3}\text{ kg/g} = 340{,}2\text{ kg/ngày}$$
- **Kết quả**: 
  - (a) Nồng độ mol ion $\text{Al}^{3+}$: $2{,}17\text{ mol/L}$ ($2{,}17\text{ M}$).
  - (b) Nồng độ phèn thương phẩm: $644{,}1\text{ g/L Al}_2(\text{SO}_4)_3\cdot 14\text{H}_2\text{O}$.
  - (c) Lưu lượng châm phèn dự trữ: $1{,}40\text{ L/min}$ ($23{,}29\text{ mL/s}$).
  - (d) Tiêu thụ độ kiềm: $15{,}16\text{ mg/L as }\text{CaCO}_3$ ($\approx 15{,}2\text{ mg/L as }\text{CaCO}_3$).
  - (e) Khối lượng kết tủa $\text{Al(OH)}_3$: $7{,}88\text{ mg/L}$ và $340{,}2\text{ kg/ngày}$.
- **Kiểm tra lại**:
  - Tỷ lệ phần trăm khối lượng: $\frac{110{,}484\text{ g}}{1320\text{ g}} = 0{,}0837 = 8{,}37\%$, khớp hoàn toàn đề bài.
  - Cân bằng lưu lượng khối lượng: $1{,}397\text{ L/min} \times 644{,}08\text{ g/L} = 900\text{ g/min} = 30\text{ mg/L} \times 30\,000\text{ L/min}$. Kết quả tuyệt đối chính xác.

---

#### 3.4.2 Tính toán thiết kế bể khuấy nhanh

- Bể khuấy nhanh (Flash Mixing Basin) nhằm phân tán tức thời hóa chất keo tụ vào toàn bộ thể tích dòng nước trước khi các phản ứng thủy phân polyme hóa diễn ra:
  - Thời gian lưu nước ngắn ($t = 1 - 30\text{ s}$), thông dụng $t = 5 - 10\text{ s}$.
  - Gradient vận tốc rất lớn ($G = 600 - 1000\text{ s}^{-1}$).
  - Tích số Camp $Gt$ nằm trong khoảng $1000 - 10\,000$.
- Kích thước hình học bể cơ học dạng trụ tròn có tỷ lệ chiều sâu nước trên đường kính bể $H/T \approx 1{,}0$ để tạo cấu trúc đối xứng dòng xoáy:
  - Cánh khuấy thường đặt ở độ sâu $C = H/3$ tính từ đáy bể.
  - Bể cần bố trí $4$ tấm vách ngăn (baffles) thẳng đứng gắn sát thành với chiều rộng mỗi tấm bằng $1/10$ đường kính bể ($W_b = T/10$) để triệt tiêu hiện tượng phễu xoáy nước (vortexing).
- Công suất tiêu hao truyền vào nước tính theo phương trình Camp-Stein: $P = \mu \cdot V \cdot G^2$.
- Công suất cánh khuấy thủy lực xác định theo chuẩn số công suất $N_p$: $P = N_p \cdot \rho \cdot N^3 \cdot D^5$.

##### Example 3-4: Thiết kế bể khuấy nhanh hình trụ (WaWE 6-35)
- **Đề bài**: (WaWE, 6-35) Thiết kế bể khuấy nhanh hình trụ bằng cách xác định thể tích bể, đường kính bể, các kích thước hình học, công suất yêu cầu truyền vào nước, lựa chọn đường kính cánh khuấy từ dữ liệu của nhà sản xuất, và tốc độ quay của cánh khuấy dựa trên các thông số sau:
  - Lưu lượng thiết kế: $11\,500\text{ m}^3\text{/ngày}$.
  - Thời gian khuấy nhanh $t$: $5\text{ s}$.
  - Gradient vận tốc khuấy nhanh $G$: $600\text{ s}^{-1}$.
  - Nhiệt độ nước: $25^\circ\text{C}$.
  - Vị trí đặt cánh khuấy: tại $1/3$ chiều sâu nước ($C = H/3$).
  - Bảng dữ liệu cánh khuấy có sẵn từ nhà sản xuất:
    | Loại cánh khuấy (Impeller type) | Đường kính cánh khuấy $D$ (m) | Chuẩn số công suất ($N_p$) |
    |---|---|---|
    | Hướng tâm (Radial) | $0{,}3;\; 0{,}4;\; 0{,}6$ | $5{,}7$ |
    | Hướng trục (Axial) | $0{,}8;\; 1{,}4;\; 2{,}0$ | $0{,}31$ |
- **Dữ kiện**
  - Lưu lượng thiết kế: $Q = 11\,500\text{ m}^3\text{/ngày} = \frac{11\,500}{86\,400}\text{ m}^3\text{/s} \approx 0{,}1331\text{ m}^3\text{/s}$.
  - Thời gian lưu nước khuấy nhanh: $t = 5{,}0\text{ s}$.
  - Gradient vận tốc thiết kế: $G = 600\text{ s}^{-1}$.
  - Nhiệt độ nước tính toán: $T = 25^\circ\text{C}$.
  - Độ nhớt động lực học của nước ở $25^\circ\text{C}$: $\mu = 0{,}890 \times 10^{-3}\text{ Pa}\cdot\text{s} = 0{,}000890\text{ N}\cdot\text{s/m}^2$.
  - Khối lượng riêng của nước ở $25^\circ\text{C}$: $\rho = 997\text{ kg/m}^3$.
  - Tỷ lệ kích thước bể trụ tròn: $H/T = 1{,}0$.
  - Bảng thông số cánh khuấy thương phẩm (slide 48).
- **Quy tắc áp dụng**
  - Thể tích bể khuấy: $V = Q \cdot t$.
  - Thể tích hình trụ tròn ($H = T$): $V = \frac{\pi}{4} T^2 H = \frac{\pi}{4} T^3 \implies T = \left(\frac{4V}{\pi}\right)^{1/3}$.
  - Công suất thủy lực Camp-Stein truyền vào nước:
    $$P = \mu \cdot V \cdot G^2$$
  - Phương trình công suất cánh khuấy thủy lực (dòng chảy rối $\text{Re} > 10^4$):
    $$P = N_p \cdot \rho \cdot N^3 \cdot D^5 \implies N = \left(\frac{P}{N_p \cdot \rho \cdot D^5}\right)^{1/3}$$
  - Tiêu chuẩn tỷ lệ đường kính cánh khuấy trên đường kính bể: chọn $D/T \approx 0{,}30 - 0{,}50$ đối với cánh turbine hướng tâm ($N_p = 5{,}7$).
  - Vận tốc đầu mút cánh khuấy: $T_s = \pi \cdot N \cdot D$ (khuyến nghị $\le 2{,}4\text{ m/s}$ trong khuấy nhanh).
  - Công suất động cơ điện với hiệu suất truyền động $\eta = 75\%$: $P_{\text{motor}} = \frac{P}{\eta}$.
- **Lời giải**
  - **Bước 1**: Tính thể tích bể khuấy nhanh ($V$).
    - Căn cứ: Công thức lưu lượng và thời gian lưu $V = Q \cdot t$.
    - Nhìn vào: $Q = 0{,}1331\text{ m}^3\text{/s}$ và $t = 5{,}0\text{ s}$ trên slide 48.
    - Thực hiện:
      $$V = 0{,}1331\text{ m}^3\text{/s} \times 5{,}0\text{ s} = 0{,}6655\text{ m}^3 \approx 0{,}67\text{ m}^3\text{ (665,5 L)}$$
  - **Bước 2**: Xác định kích thước hình học bể ($T$, $H$, $C$).
    - Căn cứ: Bể trụ tròn tỷ lệ chiều sâu bằng đường kính $H = T \implies V = \frac{\pi T^3}{4}$.
    - Nhìn vào: Thể tích $V = 0{,}6655\text{ m}^3$.
    - Thực hiện:
      $$T = \left(\frac{4 \times 0{,}6655\text{ m}^3}{\pi}\right)^{1/3} = (0{,}8473)^{1/3} \approx 0{,}946\text{ m} \approx 0{,}95\text{ m}$$
      Chiều sâu mực nước: $H = 0{,}95\text{ m}$.
      Khoảng cách đặt cánh khuấy cách đáy: $C = \frac{1}{3} H = \frac{0{,}95\text{ m}}{3} \approx 0{,}32\text{ m}$.
      Chiều sâu tổng cộng (kể cả chiều cao bảo vệ $0{,}30\text{ m}$): $H_{\text{total}} = 0{,}95 + 0{,}30 = 1{,}25\text{ m}$.
  - **Bước 3**: Tính công suất yêu cầu truyền vào nước ($P$).
    - Căn cứ: Công thức Camp-Stein $P = \mu \cdot V \cdot G^2$, với $\mu = 0{,}000890\text{ Pa}\cdot\text{s}$, $G = 600\text{ s}^{-1}$.
    - Nhìn vào: Thể tích $V = 0{,}6655\text{ m}^3$.
    - Thực hiện:
      $$P = 0{,}000890\text{ Pa}\cdot\text{s} \times 0{,}6655\text{ m}^3 \times (600\text{ s}^{-1})^2 = 0{,}000890 \times 0{,}6655 \times 360\,000 = 213{,}2\text{ W} \approx 0{,}213\text{ kW}$$
  - **Bước 4**: Lựa chọn loại cánh khuấy và tính tốc độ quay ($N$).
    - Căn cứ: Bảng dữ liệu cánh khuấy của nhà sản xuất (slide 48) và tiêu chí tỷ lệ $D/T \in [0{,}30; 0{,}50]$.
    - Nhìn vào: 
      - Bể có đường kính $T = 0{,}95\text{ m}$. Cánh khuấy hướng trục có cỡ nhỏ nhất $D = 0{,}8\text{ m}$ ($D/T = 0{,}84$ quá lớn, gây xoáy phá cấu trúc dòng).
      - Cánh khuấy hướng tâm (Radial) có các cỡ $D = 0{,}3\text{ m};\; 0{,}4\text{ m};\; 0{,}6\text{ m}$ ($N_p = 5{,}7$). Cỡ $D = 0{,}40\text{ m}$ có tỷ lệ $D/T = 0{,}40 / 0{,}95 = 0{,}42$ nằm hoàn hảo trong khoảng tiêu chuẩn.
      - (Nếu chọn cỡ trung gian phổ biến $D = 0{,}35\text{ m}$ với $D/T = 0{,}37$):
    - Thực hiện:
      - Trường hợp chọn cánh khuấy có sẵn $D = 0{,}40\text{ m}$ ($N_p = 5{,}7$, $D^5 = 0{,}01024\text{ m}^5$):
        $$N^3 = \frac{P}{N_p \cdot \rho \cdot D^5} = \frac{213{,}2}{5{,}7 \times 997 \times 0{,}01024} = \frac{213{,}2}{58{,}19} \approx 3{,}664$$
        $$N = (3{,}664)^{1/3} \approx 1{,}542\text{ rev/s} = 1{,}542 \times 60 \approx 92{,}5\text{ rpm}$$
      - Trường hợp chọn cánh khuấy $D = 0{,}35\text{ m}$ ($N_p = 5{,}7$, $D^5 = 0{,}005252\text{ m}^5$):
        $$N^3 = \frac{213{,}2}{5{,}7 \times 997 \times 0{,}005252} = \frac{213{,}2}{29{,}85} \approx 7{,}142$$
        $$N = (7{,}142)^{1/3} \approx 1{,}926\text{ rev/s} = 1{,}926 \times 60 \approx 115{,}6\text{ rpm}$$
  - **Bước 5**: Kiểm tra vận tốc đầu cánh khuấy và chọn công suất động cơ.
    - Căn cứ: Tiêu chuẩn vận tốc đầu mút cánh khuấy $T_s = \pi \cdot N \cdot D \le 2{,}4\text{ m/s}$.
    - Nhìn vào:
      - Với $D = 0{,}40\text{ m}$ ($N = 1{,}542\text{ rev/s}$): $T_s = \pi \times 1{,}542 \times 0{,}40 = 1{,}94\text{ m/s} < 2{,}4\text{ m/s}$ (đạt).
      - Với $D = 0{,}35\text{ m}$ ($N = 1{,}926\text{ rev/s}$): $T_s = \pi \times 1{,}926 \times 0{,}35 = 2{,}12\text{ m/s} < 2{,}4\text{ m/s}$ (đạt).
    - Công suất động cơ điện (hiệu suất truyền động $\eta = 75\%$):
      $$P_{\text{motor}} = \frac{213{,}2\text{ W}}{0{,}75} = 284\text{ W} = 0{,}38\text{ HP}$$
      Chọn động cơ điện thương phẩm tiêu chuẩn $0{,}37\text{ kW}$ ($0{,}5\text{ HP}$).
- **Kết quả**: 
  - Thể tích bể khuấy nhanh: $V = 0{,}67\text{ m}^3$ ($665{,}5\text{ L}$).
  - Kích thước bể: Đường kính $T = 0{,}95\text{ m}$, chiều sâu nước $H = 0{,}95\text{ m}$, tổng chiều sâu bể $1{,}25\text{ m}$.
  - Vị trí đặt cánh khuấy: $C = 0{,}32\text{ m}$ cách đáy bể.
  - Công suất thủy lực truyền vào nước: $P = 213{,}2\text{ W}$ ($0{,}213\text{ kW}$).
  - Loại cánh khuấy chọn: Cánh turbine hướng tâm (Radial impeller), đường kính $D = 0{,}40\text{ m}$ (tốc độ quay $N = 92{,}5\text{ rpm}$, $T_s = 1{,}94\text{ m/s}$) hoặc $D = 0{,}35\text{ m}$ (tốc độ quay $N = 115{,}6\text{ rpm}$, $T_s = 2{,}12\text{ m/s}$).
  - Công suất động cơ điện lắp đặt: $0{,}37\text{ kW}$ ($0{,}5\text{ HP}$).
- **Kiểm tra lại**:
  - Tích số Camp: $Gt = 600\text{ s}^{-1} \times 5\text{ s} = 3000$, nằm trong dải tiêu chuẩn thiết kế ($1000 - 10\,000$).
  - Chuẩn số Reynolds cánh khuấy: $\text{Re} = \frac{\rho N D^2}{\mu} = \frac{997 \times 1{,}542 \times 0{,}40^2}{0{,}000890} \approx 2{,}76 \times 10^5 \gg 10^4$, dòng chảy rối phát triển hoàn toàn, chuẩn số $N_p = 5{,}7$ hoàn toàn chính xác.

---

#### 3.4.3 Tính toán thiết kế bể tạo bông tuabin trục đứng

- Bể tạo bông tuabin trục đứng (Vertical Shaft Turbine Flocculator) sử dụng cánh khuấy turbine dạng cánh bản nghiêng hoặc cánh hydrofoil (foil) bơm hướng trục:
  - Hệ thống thường gồm nhiều đơn nguyên (trains) song song, mỗi đơn nguyên gồm 3 đến 4 ngăn (compartments) nối tiếp.
  - Tích số Camp tổng cộng $(Gt)_{\text{total}}$ dao động trong dải $10\,000 - 100\,000$, thời gian lưu tổng cộng $t = 20 - 30\text{ phút}$.
  - Gradient vận tốc giảm dần theo các bậc (tapered flocculation): bậc đầu $G_1 = 50 - 80\text{ s}^{-1}$ giảm dần về bậc cuối $G_n = 10 - 20\text{ s}^{-1}$ nhằm hạn chế phá vỡ bông cặn lớn.
- Các tiêu chí thủy động lực học bắt buộc cho cánh khuấy trục đứng:
  - Tỷ lệ đường kính cánh khuấy trên đường kính bể tương đương: $D/T_e = 0{,}35 - 0{,}50$ (thông dụng $0{,}40$).
  - Chuẩn số bơm lưu lượng cánh khuấy: $Q_p = N_q \cdot N \cdot D^3$.
  - Thời gian tuần hoàn khối nước (turnover time): $t_c = V_{\text{comp}} / Q_p \le 60\text{ s}$ (đảo trộn tối thiểu 5 lần trong mỗi ngăn).
  - Vận tốc bề mặt tuần hoàn: $\text{SV} = Q_p / A_{\text{plan}} > 0{,}015\text{ m/s}$ để ngăn ngừa lắng đọng bùn cặn dưới đáy bể tạo bông.
  - Vận tốc đầu cánh khuấy (tip speed): $T_s = \pi \cdot N \cdot D \le 2{,}5\text{ m/s}$.

##### Example 3-5: Thiết kế bể tạo bông tuabin trục đứng (PoWT 179)
- **Đề bài**: (PoWT, 179) Tuabin trục đứng được sử dụng cho quá trình tạo bông tại một nhà máy xử lý nước có lưu lượng thiết kế $75\,000\text{ m}^3\text{/ngày}$ và nhiệt độ nước tính toán $25^\circ\text{C}$. Hệ thống tạo bông được thiết kế gồm 4 đơn nguyên (trains) làm việc song song, mỗi đơn nguyên gồm 4 ngăn (compartments) mắc nối tiếp. Tổng thời gian lưu nước trong bể tạo bông là $20\text{ phút}$. Hãy xác định các thông số thiết kế sau cho ngăn thứ nhất của mỗi đơn nguyên tạo bông:
  1. Kích thước hình học của ngăn.
  2. Đường kính cánh khuấy (giả thiết sử dụng tuabin 3 cánh nghiêng có profin uốn camber - loại hydrofoil).
  3. Công suất truyền vào nước yêu cầu để đạt gradient vận tốc $G = 80\text{ s}^{-1}$ (công suất đưa vào nước qua trục cánh khuấy).
  4. Tốc độ quay lớn nhất của cánh khuấy.
  5. Khả năng bơm lưu lượng của cánh khuấy và thời gian tuần hoàn trong ngăn.
- **Dữ kiện**
  - Lưu lượng toàn nhà máy: $Q_{\text{total}} = 75\,000\text{ m}^3\text{/ngày} = 0{,}8681\text{ m}^3\text{/s}$.
  - Nhiệt độ nước: $T = 25^\circ\text{C} \implies \mu = 0{,}000890\text{ Pa}\cdot\text{s}$, $\rho = 997\text{ kg/m}^3$.
  - Số đơn nguyên song song: $N_{\text{train}} = 4$.
  - Số ngăn nối tiếp trên mỗi đơn nguyên: $N_{\text{stage}} = 4$.
  - Tổng thời gian lưu nước: $t_{\text{total}} = 20\text{ phút} = 1200\text{ s}$.
  - Gradient vận tốc thiết kế cho ngăn thứ nhất: $G = 80\text{ s}^{-1}$.
  - Cánh khuấy hydrofoil 3 cánh: Chuẩn số công suất $N_p = 0{,}30$, chuẩn số bơm lưu lượng $N_q = 0{,}56$.
  - Tỷ lệ đường kính cánh khuấy trên đường kính bể tương đương: $D/T_e = 0{,}40$.
- **Quy tắc áp dụng**
  - Lưu lượng cho một đơn nguyên: $Q_{\text{train}} = \frac{Q_{\text{total}}}{N_{\text{train}}}$.
  - Thời gian lưu mỗi ngăn: $t_{\text{comp}} = \frac{t_{\text{total}}}{N_{\text{stage}}}$.
  - Thể tích một ngăn: $V_{\text{comp}} = Q_{\text{train}} \cdot t_{\text{comp}}$.
  - Đường kính bể tròn tương đương của mặt bằng chữ nhật/vuông ($L \times W$):
    $$T_e = \sqrt{\frac{4 \cdot A_{\text{plan}}}{\pi}} = 1{,}128 \sqrt{L \cdot W}$$
  - Đường kính cánh khuấy: $D = 0{,}40 \cdot T_e$.
  - Công suất Camp-Stein truyền vào nước: $P = \mu \cdot V_{\text{comp}} \cdot G^2$.
  - Tốc độ quay cánh khuấy: $N = \left(\frac{P}{N_p \cdot \rho \cdot D^5}\right)^{1/3}$.
  - Khả năng bơm lưu lượng của cánh khuấy: $Q_p = N_q \cdot N \cdot D^3$.
  - Thời gian chu chuyển tuần hoàn trong ngăn: $t_c = \frac{V_{\text{comp}}}{Q_p}$.
  - Vận tốc bề mặt: $\text{SV} = \frac{Q_p}{A_{\text{plan}}}$.
- **Lời giải**
  - **Bước 1**: Tính thể tích và kích thước hình học ngăn thứ nhất.
    - Căn cứ: $Q_{\text{train}} = 75\,000 / 4 = 18\,750\text{ m}^3\text{/ngày} = 0{,}2170\text{ m}^3\text{/s}$; $t_{\text{comp}} = 20\text{ min} / 4 = 5\text{ min} = 300\text{ s}$.
    - Nhìn vào: Thể tích ngăn:
      $$V_{\text{comp}} = 0{,}2170\text{ m}^3\text{/s} \times 300\text{ s} = 65{,}10\text{ m}^3$$
    - Bố trí mặt bằng vuông $L = W$ và chiều sâu xấp xỉ chiều rộng ($H \approx W$):
      $$W = (65{,}10\text{ m}^3)^{1/3} \approx 4{,}023\text{ m}$$
      Chọn kích thước chẵn: chiều rộng $W = 4{,}0\text{ m}$, chiều dài $L = 4{,}0\text{ m}$.
      Diện tích mặt bằng: $A_{\text{plan}} = 4{,}0 \times 4{,}0 = 16{,}0\text{ m}^2$.
      Chiều sâu mức nước: $H = \frac{65{,}10\text{ m}^3}{16{,}0\text{ m}^2} = 4{,}07\text{ m}$.
      Đường kính bể tròn tương đương:
      $$T_e = \sqrt{\frac{4 \times 16{,}0}{\pi}} \approx 4{,}514\text{ m} \approx 4{,}51\text{ m}$$
  - **Bước 2**: Xác định đường kính cánh khuấy hydrofoil ($D$).
    - Căn cứ: Tiêu chuẩn thiết kế cánh khuấy hướng trục $D/T_e = 0{,}40$.
    - Nhìn vào: Đường kính tương đương $T_e = 4{,}514\text{ m}$.
    - Thực hiện:
      $$D = 0{,}40 \times 4{,}514\text{ m} \approx 1{,}80\text{ m}$$
  - **Bước 3**: Tính công suất truyền vào nước yêu cầu để đạt $G = 80\text{ s}^{-1}$.
    - Căn cứ: Công thức Camp-Stein $P = \mu \cdot V \cdot G^2$, với $\mu = 0{,}000890\text{ Pa}\cdot\text{s}$, $V = 65{,}10\text{ m}^3$, $G = 80\text{ s}^{-1}$.
    - Nhìn vào: $G^2 = 80^2 = 6400\text{ s}^{-2}$.
    - Thực hiện:
      $$P = 0{,}000890 \times 65{,}10 \times 6400 = 370{,}8\text{ W} \approx 0{,}371\text{ kW}$$
  - **Bước 4**: Xác định tốc độ quay lớn nhất của cánh khuấy ($N$).
    - Căn cứ: Công thức công suất $P = N_p \cdot \rho \cdot N^3 \cdot D^5$, với $N_p = 0{,}30$, $\rho = 997\text{ kg/m}^3$, $D = 1{,}80\text{ m}$ ($D^5 = 1{,}80^5 = 18{,}8957\text{ m}^5$).
    - Nhìn vào:
      $$\text{Mẫu số} = 0{,}30 \times 997 \times 18{,}8957 = 5651{,}7\text{ W}\cdot\text{s}^3$$
    - Thực hiện:
      $$N^3 = \frac{370{,}8}{5651{,}7} = 0{,}06561\text{ (rev/s)}^3$$
      $$N = (0{,}06561)^{1/3} \approx 0{,}4033\text{ rev/s} = 0{,}4033 \times 60 \approx 24{,}2\text{ rpm}$$
      Kiểm tra vận tốc đầu cánh khuấy:
      $$T_s = \pi \cdot N \cdot D = \pi \times 0{,}4033 \times 1{,}80 = 2{,}28\text{ m/s}$$
      (Nằm trong khoảng an toàn $1{,}5 - 2{,}5\text{ m/s}$).
  - **Bước 5**: Tính khả năng bơm lưu lượng của cánh khuấy và thời gian tuần hoàn.
    - Căn cứ: $Q_p = N_q \cdot N \cdot D^3$, với $N_q = 0{,}56$, $N = 0{,}4033\text{ s}^{-1}$, $D^3 = 1{,}80^3 = 5{,}832\text{ m}^3$.
    - Nhìn vào:
      $$Q_p = 0{,}56 \times 0{,}4033 \times 5{,}832 = 1{,}317\text{ m}^3\text{/s} \approx 79{,}0\text{ m}^3\text{/min}$$
    - Thời gian tuần hoàn đảo trộn trong ngăn:
      $$t_c = \frac{V_{\text{comp}}}{Q_p} = \frac{65{,}10\text{ m}^3}{1{,}317\text{ m}^3\text{/s}} \approx 49{,}4\text{ s} \approx 0{,}82\text{ phút} < 60\text{ s}$$
    - Vận tốc bề mặt:
      $$\text{SV} = \frac{Q_p}{A_{\text{plan}}} = \frac{1{,}317\text{ m}^3\text{/s}}{16{,}0\text{ m}^2} = 0{,}0823\text{ m/s} > 0{,}015\text{ m/s}$$
- **Kết quả**: 
  - 1. Kích thước ngăn: Dài $L = 4{,}0\text{ m}$, Rộng $W = 4{,}0\text{ m}$, Sâu $H = 4{,}07\text{ m}$ (Thể tích $V = 65{,}1\text{ m}^3$, Đường kính tương đương $T_e = 4{,}51\text{ m}$).
  - 2. Đường kính cánh khuấy hydrofoil: $D = 1{,}80\text{ m}$.
  - 3. Công suất truyền vào nước: $P = 370{,}8\text{ W}$ ($0{,}371\text{ kW}$).
  - 4. Tốc độ quay lớn nhất: $N = 24{,}2\text{ rpm}$ (Vận tốc đầu mút $T_s = 2{,}28\text{ m/s}$).
  - 5. Khả năng bơm lưu lượng: $Q_p = 1{,}317\text{ m}^3\text{/s}$ ($79{,}0\text{ m}^3\text{/min}$); Thời gian tuần hoàn: $t_c = 49{,}4\text{ s}$; Vận tốc bề mặt: $\text{SV} = 0{,}0823\text{ m/s}$.
- **Kiểm tra lại**:
  - Tỷ số chu chuyển tuần hoàn trong thời gian lưu: $t_{\text{comp}} / t_c = 300\text{ s} / 49{,}4\text{ s} = 6{,}07 > 5$ lần, bảo đảm đảo trộn đều và không tạo góc chết.
  - Vận tốc bề mặt $\text{SV} = 0{,}0823\text{ m/s}$ gấp hơn $5$ lần ngưỡng chống lắng cặn ($0{,}015\text{ m/s}$), bảo đảm bông cặn luôn lơ lửng.

---

#### 3.4.4 Tính toán thiết kế bể tạo bông cánh guồng trục ngang

- Bể tạo bông cánh guồng trục ngang (Horizontal-Shaft Paddle Wheel Flocculator) là dạng công trình kinh điển quy mô lớn:
  - Trục quay nằm ngang song song hoặc vuông góc với hướng dòng nước chảy.
  - Mỗi đơn nguyên chia thành 3 đến 5 bậc ngăn nối tiếp bằng các vách ngăn hướng dòng (baffles) để giảm thiểu hiện tượng dòng chảy ngắn (short-circuiting).
  - Tốc độ quay của trục guồng được điều chỉnh giảm dần qua từng bậc bằng động cơ biến tần nhằm tạo chế độ khuấy giảm dần ($G_1 > G_2 > \dots > G_n$).
- Lực cản thủy lực của các bản cánh phẳng gắn trên tay đòn:
  - Công suất cản phụ thuộc vào vận tốc tương đối giữa bản cánh và khối nước: $v_r = (1 - k) \cdot \omega \cdot r$, trong đó $k$ là hệ số kéo theo của nước ($k \approx 0{,}20 - 0{,}30$, thông dụng $k = 0{,}25$).
  - Công suất tiêu tán tổng cộng của các thanh bản cánh ở các bán kính $r_i$:
    $$P = \frac{1}{2} C_D \cdot \rho \cdot (1 - k)^3 \cdot (2\pi N)^3 \cdot \sum (A_i \cdot r_i^3)$$
  - Giới hạn tỷ lệ diện tích cánh khuấy: Tổng diện tích hình chiếu của các cánh khuấy trong một ngăn không vượt quá $15 - 20\%$ diện tích mặt cắt ướt ngang bể để ngăn khối nước bị cuốn xoay tròn đồng tốc.
  - Vận tốc đầu mép cánh ngoài cùng khống chế $\le 0{,}9 - 1{,}2\text{ m/s}$ ở bậc đầu và $\le 0{,}3 - 0{,}5\text{ m/s}$ ở bậc cuối để bảo vệ bông cặn lớn không bị vỡ.

##### Example 3-6: Thiết kế bể tạo bông cánh guồng trục ngang (PoWT 183)
- **Đề bài**: (PoWT, 183) Bể tạo bông cánh guồng trục ngang được sử dụng cho nhà máy nước có lưu lượng thiết kế $150\,000\text{ m}^3\text{/ngày}$ và nhiệt độ nước $25^\circ\text{C}$. Hệ thống gồm 2 đơn nguyên làm việc song song, mỗi đơn nguyên gồm 5 bậc (ngăn) mắc nối tiếp. Tổng thời gian lưu nước là $20\text{ phút}$. Cấu tạo cánh guồng như Hình 46 (slide 51): mỗi ngăn có 2 bánh guồng trên cùng một trục quay ngang. Bánh guồng có 4 tay đòn mang 3 thanh bản phẳng với mép dẫn hướng đặt tại các bán kính $r_1 = 0{,}67\text{ m}$, $r_2 = 1{,}33\text{ m}$, và $r_3 = 2{,}0\text{ m}$ tính từ tâm trục. Hãy xác định:
  1. Kích thước hình học của mỗi ngăn tạo bông.
  2. Tổng diện tích cánh khuấy và kiểm tra tỷ lệ diện tích cánh khuấy trên diện tích mặt cắt ngang bể.
  3. Phương trình quan hệ thủy lực giữa công suất tiêu tán $P$ và tốc độ quay $N$ của trục.
  4. Công suất yêu cầu, tốc độ quay $N$ (theo vòng/phút - rpm), và mô-men xoắn (torque) trên trục cho từng bậc nếu dải gradient vận tốc giảm dần là $G = 50,\; 40,\; 30,\; 20,\; 10\text{ s}^{-1}$.
  5. Gradient vận tốc trung bình và tích số Camp tổng cộng của hệ thống.
- **Dữ kiện**
  - Lưu lượng toàn trạm: $Q_{\text{total}} = 150\,000\text{ m}^3\text{/ngày} = 1{,}7361\text{ m}^3\text{/s}$.
  - Nhiệt độ nước: $T = 25^\circ\text{C} \implies \mu = 0{,}000890\text{ Pa}\cdot\text{s}$, $\rho = 997\text{ kg/m}^3$.
  - Số đơn nguyên song song: $N_{\text{train}} = 2$.
  - Số bậc nối tiếp trên mỗi đơn nguyên: $N_{\text{stage}} = 5$.
  - Tổng thời gian lưu nước: $t_{\text{total}} = 20\text{ phút} = 1200\text{ s}$.
  - Cấu tạo cánh guồng (Hình 46):
    - Số bánh guồng trên mỗi trục trong 1 ngăn: $N_{\text{wheel}} = 2$.
    - Số tay đòn mỗi bánh guồng: $N_{\text{arm}} = 4$ (chữ thập vuông góc).
    - Vị trí bán kính các thanh bản cánh: $r_1 = 0{,}67\text{ m}$, $r_2 = 1{,}33\text{ m}$, $r_3 = 2{,}00\text{ m}$.
    - Chiều rộng bản cánh: $w = 0{,}15\text{ m}$.
    - Chiều dài bản cánh: $L_p = 3{,}0\text{ m}$.
    - Hệ số cản bản phẳng: $C_D = 1{,}50$.
    - Hệ số kéo theo của dòng nước: $k = 0{,}25 \implies 1 - k = 0{,}75$.
  - **Hình 46.** Sơ đồ cấu tạo và mặt cắt bể tạo bông cánh guồng trục ngang (Example 3-6)
    - <img src="ch03_coagulation_flocculation/assets/fig_46_p51.png" alt="Hình 46" />
  - **Hình này chứng minh điều gì**
    - Cấu tạo bố trí hai đơn nguyên chạy song song (Train 1, Train 2), mỗi đơn nguyên gồm 5 bậc (Stages 1–5) nối tiếp với hai guồng cánh khuấy trên một trục ngang.
  - **Từ đâu mà thấy được**
    - Mặt bằng (phần giữa): 2 đơn nguyên (Train 1 và Train 2), mỗi đơn nguyên chia 5 ngăn nối tiếp với vách ngăn hướng dòng.
    - Mặt cắt đứng (phần trên): 5 bậc cánh guồng quay trên trục ngang qua từng ngăn.
    - Chi tiết cánh guồng (phần dưới): Mỗi guồng có 4 tay đòn (chữ thập), mỗi tay mang 3 thanh cánh khuấy bản phẳng ở bán kính $r_1 = 0{,}67\text{ m}$, $r_2 = 1{,}33\text{ m}$, $r_3 = 2{,}0\text{ m}$, chiều rộng cánh $W$ và chiều dài cánh $L$.
- **Quy tắc áp dụng**
  - Thể tích một ngăn: $V_{\text{comp}} = \frac{Q_{\text{total}} \cdot t_{\text{total}}}{N_{\text{train}} \cdot N_{\text{stage}}}$.
  - Bố trí kích thước hình học ngăn:
    - Bán kính ngoài cùng của guồng $r_3 = 2{,}00\text{ m} \implies$ đường kính quay ngoài cùng $D_w = 2 \times (2{,}00 + 0{,}15/2) = 4{,}15\text{ m}$. Chọn chiều sâu nước $H = 5{,}0\text{ m}$ (khoảng hở đáy và mặt nước $0{,}425\text{ m}$).
    - Chiều rộng ngăn dọc trục: $W_{\text{comp}} = 2 \cdot L_p + \text{hở giữa} + 2 \cdot \text{hở thành} = 2 \times 3{,}0 + 1{,}0 + 2 \times 0{,}7 = 8{,}4\text{ m}$.
    - Chiều dài ngăn theo phương dòng chảy: $L_{\text{comp}} = \frac{V_{\text{comp}}}{W_{\text{comp}} \cdot H}$.
  - Công suất tiêu tán bởi lực cản của các thanh bản cánh:
    $$P = \frac{1}{2} C_D \cdot \rho \cdot (1 - k)^3 \cdot (2\pi N)^3 \cdot \sum (A_i \cdot r_i^3)$$
    trong đó $A_i$ là tổng diện tích các bản cánh ở bán kính $r_i$ ($A_i = N_{\text{wheel}} \cdot N_{\text{arm}} \cdot L_p \cdot w$).
  - Công suất Camp-Stein: $P = \mu \cdot V_{\text{comp}} \cdot G^2$.
  - Mô-men xoắn trên trục cánh khuấy: $T_{\text{torque}} = \frac{P}{2\pi N}$.
  - Gradient vận tốc trung bình và tích số Camp:
    $$G_{\text{avg}} = \frac{\sum G_i}{N_{\text{stage}}}$$
    $$(Gt)_{\text{total}} = G_{\text{avg}} \cdot t_{\text{total}}$$
- **Lời giải**
  - **Bước 1**: Tính thể tích và kích thước hình học ngăn tạo bông.
    - Căn cứ: Tổng thể tích $V_{\text{total}} = 1{,}7361\text{ m}^3\text{/s} \times 1200\text{ s} = 2083{,}33\text{ m}^3$.
    - Nhìn vào: Hệ thống có 2 đơn nguyên $\times 5$ bậc $= 10$ ngăn.
    - Thể tích một ngăn: $V_{\text{comp}} = \frac{2083{,}33\text{ m}^3}{10} = 208{,}33\text{ m}^3$.
    - Thời gian lưu mỗi bậc: $t_i = 1200\text{ s} / 5 = 240\text{ s} = 4{,}0\text{ phút}$.
    - Kích thước hình học:
      - Chiều sâu nước: $H = 5{,}0\text{ m}$.
      - Chiều rộng ngăn dọc trục: $W_{\text{comp}} = 8{,}4\text{ m}$ (chứa 2 bánh guồng $3{,}0\text{ m}$, khoảng cách tim-thành $0{,}7\text{ m}$, khoảng cách hai guồng $1{,}0\text{ m}$).
      - Chiều dài ngăn theo chiều dòng:
        $$L_{\text{comp}} = \frac{V_{\text{comp}}}{W_{\text{comp}} \cdot H} = \frac{208{,}33\text{ m}^3}{8{,}4\text{ m} \times 5{,}0\text{ m}} = 4{,}96\text{ m} \approx 5{,}0\text{ m}$$
  - **Bước 2**: Tính diện tích cánh khuấy và kiểm tra tỷ lệ diện tích cản.
    - Căn cứ: Trong một ngăn có $2\text{ wheels} \times 4\text{ arms} \times 3\text{ boards} = 24$ cánh khuấy bản phẳng.
    - Nhìn vào: Diện tích một cánh khuấy $A_{\text{board}} = 3{,}0\text{ m} \times 0{,}15\text{ m} = 0{,}45\text{ m}^2$.
    - Tổng diện tích cánh: $A_{\text{total}} = 24 \times 0{,}45\text{ m}^2 = 10{,}8\text{ m}^2$.
    - Diện tích hình chiếu cản dòng của các cánh khuấy trên mặt đứng đối xứng:
      $$A_{\text{projected}} = 2\text{ wheels} \times 2\text{ arms} \times 3\text{ boards} \times 0{,}45\text{ m}^2 = 5{,}4\text{ m}^2$$
      Diện tích mặt cắt ướt ngang bể: $A_{\text{cross}} = W_{\text{comp}} \times H = 8{,}4\text{ m} \times 5{,}0\text{ m} = 42{,}0\text{ m}^2$.
      Tỷ lệ diện tích cản:
      $$\frac{A_{\text{projected}}}{A_{\text{cross}}} = \frac{5{,}4\text{ m}^2}{42{,}0\text{ m}^2} = 12{,}86\% < 20\%$$
      (Thỏa mãn tiêu chuẩn không vượt quá $15 - 20\%$ để chống hiện tượng nước xoay đồng tốc).
  - **Bước 3**: Thiết lập phương trình thủy lực quan hệ giữa công suất $P$ và tốc độ quay $N$.
    - Căn cứ: Tại mỗi bán kính $r_i$, tổng diện tích các cánh khuấy là $A_i = 2\text{ wheels} \times 4\text{ arms} \times 0{,}45\text{ m}^2 = 3{,}60\text{ m}^2$.
    - Nhìn vào: Bán kính các thanh $r_1 = 0{,}67\text{ m}$, $r_2 = 1{,}33\text{ m}$, $r_3 = 2{,}00\text{ m}$.
      $$\sum r_i^3 = (0{,}67)^3 + (1{,}33)^3 + (2{,}00)^3 = 0{,}3008 + 2{,}3526 + 8{,}0000 = 10{,}6534\text{ m}^3$$
    - Công thức công suất:
      $$P = \frac{1}{2} C_D \cdot \rho \cdot (1 - k)^3 \cdot (2\pi N)^3 \cdot A_i \cdot \sum r_i^3$$
      Thay số: $C_D = 1{,}50$, $\rho = 997\text{ kg/m}^3$, $1 - k = 0{,}75$, $2\pi = 6{,}2832$:
      $$P = 0{,}5 \times 1{,}50 \times 997 \times (0{,}75 \times 6{,}2832 \times N)^3 \times 3{,}60 \times 10{,}6534$$
      $$P = 747{,}75 \times (4{,}7124 \times N)^3 \times 38{,}352 \approx 742\,880 \cdot N^3\text{ (W)}$$
      (với $N$ tính bằng số vòng trên giây, $\text{rev/s}$).
  - **Bước 4**: Tính công suất yêu cầu, tốc độ quay và mô-men xoắn cho từng bậc ($G = 50 \rightarrow 10\text{ s}^{-1}$).
    - Căn cứ: Công suất truyền vào nước mỗi ngăn:
      $$P = \mu \cdot V_{\text{comp}} \cdot G^2 = 0{,}000890\text{ Pa}\cdot\text{s} \times 208{,}33\text{ m}^3 \times G^2 = 0{,}18541 \cdot G^2\text{ (W)}$$
      Tốc độ quay: $N = \left(\frac{P}{742\,880}\right)^{1/3}$ ($\text{rev/s}$), quy đổi $\text{rpm} = N \times 60$.
      Mô-men xoắn: $T_{\text{torque}} = \frac{P}{2\pi N}$ ($\text{N}\cdot\text{m}$).
    - Nhìn vào từng bậc:
      - **Bậc 1 ($G_1 = 50\text{ s}^{-1}$)**:
        $$P_1 = 0{,}18541 \times 50^2 = 463{,}5\text{ W}$$
        $$N_1 = \left(\frac{463{,}5}{742\,880}\right)^{1/3} = (6{,}239 \times 10^{-4})^{1/3} \approx 0{,}08545\text{ rev/s} = 5{,}13\text{ rpm}$$
        $$T_{\text{torque}, 1} = \frac{463{,}5}{2\pi \times 0{,}08545} = 863{,}3\text{ N}\cdot\text{m}$$
        Vận tốc mép ngoài cùng ($r = 2{,}075\text{ m}$): $v_1 = 2\pi \times 0{,}08545 \times 2{,}075 = 1{,}11\text{ m/s} \le 1{,}2\text{ m/s}$ (đạt).
      - **Bậc 2 ($G_2 = 40\text{ s}^{-1}$)**:
        $$P_2 = 0{,}18541 \times 40^2 = 296{,}7\text{ W}$$
        $$N_2 = \left(\frac{296{,}7}{742\,880}\right)^{1/3} \approx 0{,}07368\text{ rev/s} = 4{,}42\text{ rpm}$$
        $$T_{\text{torque}, 2} = \frac{296{,}7}{2\pi \times 0{,}07368} = 640{,}8\text{ N}\cdot\text{m}$$
      - **Bậc 3 ($G_3 = 30\text{ s}^{-1}$)**:
        $$P_3 = 0{,}18541 \times 30^2 = 166{,}9\text{ W}$$
        $$N_3 = \left(\frac{166{,}9}{742\,880}\right)^{1/3} \approx 0{,}06079\text{ rev/s} = 3{,}65\text{ rpm}$$
        $$T_{\text{torque}, 3} = \frac{166{,}9}{2\pi \times 0{,}06079} = 437{,}0\text{ N}\cdot\text{m}$$
      - **Bậc 4 ($G_4 = 20\text{ s}^{-1}$)**:
        $$P_4 = 0{,}18541 \times 20^2 = 74{,}2\text{ W}$$
        $$N_4 = \left(\frac{74{,}2}{742\,880}\right)^{1/3} \approx 0{,}04639\text{ rev/s} = 2{,}78\text{ rpm}$$
        $$T_{\text{torque}, 4} = \frac{74{,}2}{2\pi \times 0{,}04639} = 254{,}7\text{ N}\cdot\text{m}$$
      - **Bậc 5 ($G_5 = 10\text{ s}^{-1}$)**:
        $$P_5 = 0{,}18541 \times 10^2 = 18{,}5\text{ W}$$
        $$N_5 = \left(\frac{18{,}5}{742\,880}\right)^{1/3} \approx 0{,}02923\text{ rev/s} = 1{,}75\text{ rpm}$$
        $$T_{\text{torque}, 5} = \frac{18{,}5}{2\pi \times 0{,}02923} = 100{,}8\text{ N}\cdot\text{m}$$
        Vận tốc mép ngoài cùng: $v_5 = 2\pi \times 0{,}02923 \times 2{,}075 = 0{,}38\text{ m/s}$ (rất êm dịu, bảo toàn bông cặn cực đại).
  - **Bước 5**: Tính gradient vận tốc trung bình và tích số Camp ($Gt$).
    - Căn cứ: Do thời gian lưu các bậc bằng nhau ($t_i = 240\text{ s}$):
      $$G_{\text{avg}} = \frac{50 + 40 + 30 + 20 + 10}{5} = 30{,}0\text{ s}^{-1}$$
      Tích số Camp tổng cộng của công trình:
      $$(Gt)_{\text{total}} = G_{\text{avg}} \cdot t_{\text{total}} = 30{,}0\text{ s}^{-1} \times 1200\text{ s} = 36\,000$$
- **Kết quả**: 
  - 1. Kích thước hình học mỗi ngăn: Chiều dài $L = 5{,}0\text{ m}$, Chiều rộng $W = 8{,}4\text{ m}$, Chiều sâu nước $H = 5{,}0\text{ m}$ (Thể tích $V_{\text{comp}} = 208{,}3\text{ m}^3$).
  - 2. Diện tích cánh khuấy: $10{,}8\text{ m}^2$/ngăn; Tỷ lệ diện tích cản $12{,}86\% < 20\%$.
  - 3. Phương trình quan hệ công suất: $P = 742\,880 \cdot N^3$ ($\text{W}$, với $N$ tính bằng $\text{rev/s}$).
  - 4. Thông số vận hành từng bậc:
    - Bậc 1 ($G = 50\text{ s}^{-1}$): $P = 463{,}5\text{ W}$, $N = 5{,}13\text{ rpm}$, Torque $= 863{,}3\text{ N}\cdot\text{m}$.
    - Bậc 2 ($G = 40\text{ s}^{-1}$): $P = 296{,}7\text{ W}$, $N = 4{,}42\text{ rpm}$, Torque $= 640{,}8\text{ N}\cdot\text{m}$.
    - Bậc 3 ($G = 30\text{ s}^{-1}$): $P = 166{,}9\text{ W}$, $N = 3{,}65\text{ rpm}$, Torque $= 437{,}0\text{ N}\cdot\text{m}$.
    - Bậc 4 ($G = 20\text{ s}^{-1}$): $P = 74{,}2\text{ W}$, $N = 2{,}78\text{ rpm}$, Torque $= 254{,}7\text{ N}\cdot\text{m}$.
    - Bậc 5 ($G = 10\text{ s}^{-1}$): $P = 18{,}5\text{ W}$, $N = 1{,}75\text{ rpm}$, Torque $= 100{,}8\text{ N}\cdot\text{m}$.
  - 5. Gradient vận tốc trung bình $G_{\text{avg}} = 30{,}0\text{ s}^{-1}$; Tích số Camp $(Gt)_{\text{total}} = 36\,000$.
- **Kiểm tra lại**:
  - Tích số Camp $36\,000$ nằm hoàn toàn trong phạm vi tối ưu chuẩn mực ($20\,000 - 100\,000$).
  - Vận tốc mép cánh ngoài cùng giảm dần từ $1{,}11\text{ m/s}$ (dưới ngưỡng cực đại $1{,}2\text{ m/s}$) xuống $0{,}38\text{ m/s}$, bảo đảm phân phối động năng va chạm tạo bông tối ưu mà không gây vỡ bông cặn keo tụ trước khi chuyển tiếp sang bể lắng.

## Chương 4: Khử Sắt và Mangan (Removal of Iron & Manganese)


### 4.1 Tổng quan về Sắt và Mangan trong nguồn nước

#### 4.1.1 Hiện diện, Dạng hóa học và Quy chuẩn chất lượng

- Sắt ($\text{Fe}$) và mangan ($\text{Mn}$) thường xuất hiện đồng thời trong nguồn nước tự nhiên:
  - Công nghệ xử lý tương tự nhau, do đó hai kim loại được nhóm chung để khảo sát và lựa chọn giải pháp kỹ thuật.
  - Sắt và mangan cần loại bỏ khỏi nước vì lý do thẩm mỹ (*aesthetic reasons*) và lý do vận hành (*operational reasons*).
- Tiêu chuẩn chất lượng nước cấp (QCVN 01: 2009/BYT):
  - Giới hạn nồng độ sắt tổng cộng: $0.3\text{ mg/L}$.
  - Giới hạn nồng độ mangan tổng cộng: $0.3\text{ mg/L}$.
- Trạng thái hòa tan phụ thuộc vào dạng oxy hóa hoặc dạng khử của kim loại:
  - Dạng oxy hóa (*oxidized form*) [$\text{Fe(III)}$ và $\text{Mn(IV)}$]: Rất khó tan (*quite insoluble*), hình thành cặn kết tủa.
  - Dạng khử (*reduced forms*) [$\text{Fe(II)}$ và $\text{Mn(II)}$]: Rất dễ tan (*very soluble*), tồn tại dạng ion hòa tan $\text{Fe}^{2+}$ và $\text{Mn}^{2+}$.
- Nồng độ sắt và mangan trong nước ngầm (*groundwater*):
  - Thường xuất hiện ở dải nồng độ thấp tính theo $\text{mg/L}$ (*low mg/L range*).
  - Trong nước ngầm có độ kiềm thấp (*low alkalinity*), nồng độ $\text{Fe}^{2+}$ có thể đạt $10\text{ mg/L}$ hoặc cao hơn.
  - Nồng độ $\text{Mn}^{2+}$ dao động trong khoảng từ $0.1$ đến $2.0\text{ mg/L}$.

#### 4.1.2 Tác hại cảm quan: Nước đỏ, Vết ố và Vị lạ

- Dạng oxy hóa [$\text{Fe(III)}$ và $\text{Mn(IV)}$] làm đổi màu nước, gây ố bẩn thiết bị vệ sinh (*fixtures*) và quần áo (*clothing*).
- Tác hại thẩm mỹ đặc trưng do sắt ($\text{Fe}$):
  - Hiện tượng nước đỏ (*red water*).
  - Vết ố màu nâu đỏ (*reddish brown stains*) bám trên thiết bị phụ trợ đường ống và thiết bị vệ sinh (*plumbing fixtures*).
  - Vị lạ khó chịu (*off tastes*) phát sinh do phản ứng với axit tannic (*tannic acids*) có trong trà và cà phê.
- Tác hại thẩm mỹ đặc trưng do mangan ($\text{Mn}$):
  - Vết ố màu đen hoặc xám (*black or gray stains*) bám trên thiết bị vệ sinh (*plumbing fixtures*) và đồ giặt (*laundry*).

#### 4.1.3 Lắng đọng khoáng chất và Sự cố mạng lưới cấp nước

- Sự cố vận hành phát sinh do kết tủa khoáng chất sắt và mangan trong hệ thống phân phối nước (*water distribution systems*):
  - Tích tụ và ứ đọng cặn lắng nghiêm trọng tại các đoạn ống cụt (*dead-end mains*).
  - Cặn kết tủa bám dày bên trong thành ống phân phối (*inside distribution pipes*).
  - Cặn kết tủa bị cuốn xới và tái lơ lửng (*resuspended*) trong các giai đoạn nhu cầu tiêu thụ cao (*periods of high demand*) hoặc khi xảy ra hiện tượng đổi chiều dòng chảy (*flow reversal*).

#### 4.1.4 Màng sinh học và Vi khuẩn sắt mangan trong đường ống

- Sự phát triển của vi khuẩn sắt và mangan (*iron and manganese bacteria*) gây sự cố vận hành phức tạp trong mạng lưới:
  - Nhiều chủng vi khuẩn sắt và mangan tạo lớp chất nền sinh học bảo vệ đáng kể chống lại quá trình khử trùng bằng clo (*protection from chlorine disinfection*).
- Các tác động tiêu cực khác do sự phát triển của vi khuẩn sắt và mangan:
  - Giảm đáng kể năng lực truyền dẫn của tuyến ống (*significant reduction in pipeline capacity*).
  - Tắc nghẽn đồng hồ đo lưu lượng (*meters*) và các loại van (*valves*).
  - Gây biến đổi màu nước (*discoloration of water*).
  - Phát sinh mùi vị lạ khó chịu (*off tastes*).
  - Gia tăng nhu cầu tiêu thụ clo (*increased chlorine demand*) trên mạng lưới cấp nước.

### 4.2 Cơ chế hóa học oxy hóa Khử Sắt và Mangan

#### 4.2.1 Cơ chế oxy hóa và Phản ứng hóa học với các chất oxy hóa

##### 4.2.1.1 Nguyên lý chuyển hóa dạng hòa tan sang dạng kết tủa
- Phương pháp khử sắt (iron) và mangan (manganese) phổ biến nhất dựa trên quá trình chuyển hóa các dạng khử hòa tan thành các dạng oxy hóa không tan:
  - Ở dạng khử ($\text{reduced forms}$ gồm $\text{Fe}^{2+}$ và $\text{Mn}^{2+}$), các hợp chất kim loại tan hoàn toàn trong nước.
  - Ở dạng oxy hóa ($\text{oxidized forms}$ gồm $\text{Fe}^{3+}$ và $\text{Mn}^{4+}$), sắt và mangan kết tủa thành bông cặn không tan ($\text{Fe(OH)}_3\downarrow$ và $\text{MnO}_2\downarrow$).
  - Các hạt cặn kết tủa được tách loại hoàn toàn khỏi dòng nước bằng các công đoạn lắng trọng lực và lọc hạt.
- Các hóa chất oxy hóa thông dụng theo thực tế địa lý:
  - Tại Hoa Kỳ (United States): Không khí ($\text{air}$ / oxy hòa tan), clo ($\text{chlorine}$), clo đioxit ($\text{chlorine dioxide}$) và pemanganat ($\text{permanganate}$ / thuốc tím).
  - Tại Châu Âu (Europe): Ozone ($\text{ozone}$) đã được áp dụng thành công và đạt hiệu quả xử lý cao.

##### 4.2.1.2 Phản ứng oxy hóa bằng Oxy hòa tan (không khí làm thoáng - O2)
- Phản ứng oxy hóa sắt bằng không khí (làm thoáng cấp oxy):
  - Dạng phân tử bicacbonat:
    $$4\text{Fe}(\text{HCO}_3)_2 + \text{O}_2 + 2\text{H}_2\text{O} = 4\text{Fe}(\text{OH})_3\downarrow + 8\text{CO}_2$$
  - Dạng ion thủy phân:
    $$4\text{Fe}^{2+} + \text{O}_2 + 10\text{H}_2\text{O} = 4\text{Fe}(\text{OH})_3\downarrow + 8\text{H}^+$$
  - Cơ chế oxy hóa - thủy phân hai bước:
    $$4\text{Fe}^{2+} + \text{O}_2 + 4\text{H}^+ \rightarrow 4\text{Fe}^{3+} + 2\text{H}_2\text{O}$$
    $$\text{Fe}^{3+} + 3\text{H}_2\text{O} \rightarrow \text{Fe}(\text{OH})_3\downarrow + 3\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $1\text{ mol } \text{O}_2$ ($32\text{ g}$) oxy hóa được $4\text{ mol } \text{Fe}$ ($4 \times 55{,}85 = 223{,}4\text{ g}$).
  - Định mức tiêu thụ lý thuyết: $\frac{32}{223{,}4} \approx 0{,}143\text{ mg } \text{O}_2 / \text{mg } \text{Fe}^{2+}$ (làm tròn $0{,}14\text{ mg/mg}$).
  - Ảnh hưởng đến độ kiềm: Quá trình giải phóng ion $\text{H}^+$, tiêu thụ $1{,}79\text{ mg/L}$ độ kiềm ($\text{tính theo CaCO}_3$) cho mỗi $1\text{ mg/L } \text{Fe}^{2+}$ bị oxy hóa.
- Phản ứng oxy hóa mangan bằng không khí:
  - Dạng phân tử trong môi trường bicacbonat canxi:
    $$2\text{MnSO}_4 + 2\text{Ca}(\text{HCO}_3)_2 + \text{O}_2 = 2\text{MnO}_2\downarrow + 2\text{CaSO}_4 + 2\text{H}_2\text{O} + 4\text{CO}_2$$
  - Dạng ion thủy phân:
    $$2\text{Mn}^{2+} + \text{O}_2 + 2\text{H}_2\text{O} = 2\text{MnO}_2\downarrow + 4\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $1\text{ mol } \text{O}_2$ ($32\text{ g}$) oxy hóa được $2\text{ mol } \text{Mn}$ ($2 \times 54{,}94 = 109{,}88\text{ g}$).
  - Định mức tiêu thụ lý thuyết: $\frac{32}{109{,}88} \approx 0{,}291\text{ mg } \text{O}_2 / \text{mg } \text{Mn}^{2+}$ (làm tròn $0{,}29\text{ mg/mg}$).
  - Tiêu thụ độ kiềm: Mỗi $1\text{ mg/L } \text{Mn}^{2+}$ bị oxy hóa tiêu thụ $1{,}82\text{ mg/L}$ độ kiềm ($\text{tính theo CaCO}_3$).

##### 4.2.1.3 Phản ứng oxy hóa bằng Clo tự do (Chlorine - Cl2)
- Phản ứng oxy hóa sắt bằng clo:
  - Dạng phân tử khí clo hòa tan:
    $$2\text{Fe}^{2+} + \text{Cl}_2 + 6\text{H}_2\text{O} = 2\text{Fe}(\text{OH})_3\downarrow + 2\text{Cl}^- + 6\text{H}^+$$
  - Dạng axit hypoclorơ ($\text{HOCl}$, dạng khử trùng chiếm ưu thế ở $\text{pH} = 6{,}5 - 7{,}5$):
    $$2\text{Fe}^{2+} + \text{HOCl} + 5\text{H}_2\text{O} = 2\text{Fe}(\text{OH})_3\downarrow + \text{Cl}^- + 5\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $1\text{ mol } \text{Cl}_2$ ($70{,}9\text{ g}$) oxy hóa $2\text{ mol } \text{Fe}$ ($111{,}7\text{ g}$).
  - Định mức clo lý thuyết: $\frac{70{,}9}{111{,}7} \approx 0{,}635\text{ mg } \text{Cl}_2 / \text{mg } \text{Fe}^{2+}$ (giá trị thực nghiệm trong bảng là $0{,}63\text{ mg/mg}$; trong tính toán kỹ thuật thường dùng $0{,}64\text{ mg/mg}$).
- Phản ứng oxy hóa mangan bằng clo:
  - Dạng phân tử clo:
    $$\text{Mn}^{2+} + \text{Cl}_2 + 2\text{H}_2\text{O} = \text{MnO}_2\downarrow + 2\text{Cl}^- + 4\text{H}^+$$
  - Dạng axit hypoclorơ ($\text{HOCl}$):
    $$\text{Mn}^{2+} + \text{HOCl} + \text{H}_2\text{O} = \text{MnO}_2\downarrow + \text{Cl}^- + 3\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $1\text{ mol } \text{Cl}_2$ ($70{,}9\text{ g}$) oxy hóa $1\text{ mol } \text{Mn}$ ($54{,}94\text{ g}$).
  - Định mức clo lý thuyết: $\frac{70{,}9}{54{,}94} \approx 1{,}290\text{ mg } \text{Cl}_2 / \text{mg } \text{Mn}^{2+}$ (giá trị thực nghiệm trong bảng là $1{,}28\text{ mg/mg}$; trong tính toán kỹ thuật thường dùng $1{,}29\text{ mg/mg}$).

##### 4.2.1.4 Phản ứng oxy hóa bằng Thuốc tím (Potassium Permanganate - KMnO4)
- Phản ứng oxy hóa sắt bằng thuốc tím:
  - Phương trình phản ứng phân tử:
    $$3\text{Fe}^{2+} + \text{KMnO}_4 + 7\text{H}_2\text{O} = 3\text{Fe}(\text{OH})_3\downarrow + \text{MnO}_2\downarrow + \text{K}^+ + 5\text{H}^+$$
  - Phương trình phản ứng ion thu gọn:
    $$3\text{Fe}^{2+} + \text{MnO}_4^- + 7\text{H}_2\text{O} = 3\text{Fe}(\text{OH})_3\downarrow + \text{MnO}_2\downarrow + 5\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $1\text{ mol } \text{KMnO}_4$ ($158{,}03\text{ g}$) oxy hóa được $3\text{ mol } \text{Fe}$ ($3 \times 55{,}85 = 167{,}55\text{ g}$).
  - Định mức thuốc tím lý thuyết: $\frac{158{,}03}{167{,}55} \approx 0{,}943\text{ mg } \text{KMnO}_4 / \text{mg } \text{Fe}^{2+}$ (chuẩn định mức thực tế: $0{,}94\text{ mg/mg}$).
  - Tác dụng cộng hưởng của sản phẩm: Kết tủa $\text{MnO}_2$ sinh ra có hoạt tính hấp phụ và xúc tác oxy hóa bề mặt đối với mangan.
- Phản ứng oxy hóa mangan bằng thuốc tím:
  - Phương trình phản ứng phân tử:
    $$3\text{Mn}^{2+} + 2\text{KMnO}_4 + 2\text{H}_2\text{O} = 5\text{MnO}_2\downarrow + 2\text{K}^+ + 4\text{H}^+$$
  - Phương trình phản ứng ion thu gọn:
    $$3\text{Mn}^{2+} + 2\text{MnO}_4^- + 2\text{H}_2\text{O} = 5\text{MnO}_2\downarrow + 4\text{H}^+$$
  - Tỷ lệ hóa học lý thuyết: $2\text{ mol } \text{KMnO}_4$ ($316{,}06\text{ g}$) oxy hóa được $3\text{ mol } \text{Mn}^{2+}$ ($164{,}82\text{ g}$).
  - Định mức thuốc tím lý thuyết: $\frac{316{,}06}{164{,}82} \approx 1{,}918\text{ mg } \text{KMnO}_4 / \text{mg } \text{Mn}^{2+}$ (chuẩn định mức thực tế: $1{,}92\text{ mg/mg}$).

##### 4.2.1.5 Phản ứng oxy hóa bằng Ozone (O3) và Clo đioxit (Chlorine Dioxide - ClO2)
- Phản ứng oxy hóa bằng ozone ($\text{O}_3$):
  - Oxy hóa sắt dạng ion:
    $$2\text{Fe}^{2+} + \text{O}_3 + 5\text{H}_2\text{O} = 2\text{Fe}(\text{OH})_3\downarrow + \text{O}_2\uparrow + 4\text{H}^+$$
    - Định mức tiêu thụ ozone cho sắt: $0{,}43\text{ mg } \text{O}_3 / \text{mg } \text{Fe}$.
  - Oxy hóa mangan dạng ion:
    $$\text{Mn}^{2+} + \text{O}_3 + \text{H}_2\text{O} = \text{MnO}_2\downarrow + \text{O}_2\uparrow + 2\text{H}^+$$
    - Định mức tiêu thụ ozone cho mangan: $0{,}67\text{ mg } \text{O}_3 / \text{mg } \text{Mn}$.
  - Nguy cơ quá liều ozone: Châm dư thừa ozone oxy hóa tiếp $\text{MnO}_2$ thành ion pemanganat hòa tan ($\text{MnO}_4^-$), gây hiện tượng nước màu hồng (pink water):
    $$2\text{MnO}_2 + 3\text{O}_3 + \text{H}_2\text{O} \rightarrow 2\text{MnO}_4^- + 3\text{O}_2 + 2\text{H}^+$$
- Phản ứng oxy hóa bằng clo đioxit ($\text{ClO}_2$):
  - Oxy hóa sắt dạng ion:
    $$\text{Fe}^{2+} + \text{ClO}_2 + 3\text{H}_2\text{O} = \text{Fe}(\text{OH})_3\downarrow + \text{ClO}_2^- + 3\text{H}^+$$
    - Định mức tiêu thụ clo đioxit cho sắt: $1{,}2\text{ mg } \text{ClO}_2 / \text{mg } \text{Fe}$.
  - Oxy hóa mangan dạng ion:
    $$\text{Mn}^{2+} + 2\text{ClO}_2 + 2\text{H}_2\text{O} = \text{MnO}_2\downarrow + 2\text{ClO}_2^- + 4\text{H}^+$$
    - Định mức tiêu thụ clo đioxit cho mangan: $2{,}4\text{ mg } \text{ClO}_2 / \text{mg } \text{Mn}$.
  - Kiểm soát sản phẩm phụ vô cơ: Phản ứng tạo ra ion clorit ($\text{ClO}_2^-$), đòi hỏi giám sát để không vượt quá giới hạn sức khỏe theo quy chuẩn.

---

#### 4.2.2 Nhu cầu các chất oxy hóa cho sắt và mangan

##### 4.2.2.1 Bảng định mức tiêu thụ chất oxy hóa lý thuyết và thực nghiệm
- Bảng so sánh định mức tiêu thụ các tác nhân oxy hóa tính trên mỗi $\text{mg/L}$ kim loại ($\text{Oxidant Requirements for Iron and Manganese}$):
  - **Hình 1.** Bảng định mức nhu cầu chất oxy hóa cho sắt và mangan (Oxidant Requirements for Iron and Manganese)
    - <img src="ch04_iron_manganese_removal/assets/fig_01_p6.png" alt="Hình 1" />
  - **Hình này chứng minh điều gì**
    - Định lượng nhu cầu chất oxy hóa lý thuyết và thực nghiệm cho mỗi mg/L Fe và Mn đối với 5 chất oxy hóa chính.
  - **Từ đâu mà thấy được**
    - Cột giá trị trên slide trang 6 thể hiện tỷ lệ định mức Mn/Fe dao động từ 1.56 đến 2.07.

| Tác nhân oxy hóa (Oxidant) | Định mức cho $\text{Mn}$ (per mg/L of Mn) | Định mức cho $\text{Fe}$ (per mg/L of Fe) | Tỷ lệ định mức ($\text{Mn} / \text{Fe}$) |
| :--- | :---: | :---: | :---: |
| Oxy (từ làm thoáng - Oxygen from aeration) | $0{,}29\text{ mg/L}$ | $0{,}14\text{ mg/L}$ | $2{,}07$ |
| Ozone ($\text{O}_3$) | $0{,}67\text{ mg/L}$ | $0{,}43\text{ mg/L}$ | $1{,}56$ |
| Clo ($\text{Cl}_2$ - Chlorine) | $1{,}28\text{ mg/L}$ | $0{,}63\text{ mg/L}$ | $2{,}03$ |
| Thuốc tím ($\text{KMnO}_4$ - Potassium permanganate) | $1{,}92\text{ mg/L}$ | $0{,}94\text{ mg/L}$ | $2{,}04$ |
| Clo đioxit ($\text{ClO}_2$ - Chlorine dioxide) | $2{,}40\text{ mg/L}$ | $1{,}20\text{ mg/L}$ | $2{,}00$ |

##### 4.2.2.2 Phân tích tương quan định mức tiêu thụ Fe và Mn
- Nhu cầu chất oxy hóa cho mỗi đơn vị khối lượng $\text{Mn}$ luôn cao hơn từ $1{,}5$ đến hơn $2$ lần so với $\text{Fe}$ trên mọi tác nhân:
  - Bản chất số electron trao đổi:
    - Quá trình oxy hóa sắt chuyển từ số oxy hóa $+2$ lên $+3$ ($\text{Fe}^{2+} \rightarrow \text{Fe}^{3+} + 1e^-$), chỉ trao đổi $1\text{ electron}$.
    - Quá trình oxy hóa mangan chuyển từ số oxy hóa $+2$ lên $+4$ ($\text{Mn}^{2+} \rightarrow \text{Mn}^{4+} + 2e^-$), trao đổi $2\text{ electron}$.
  - Tỷ khối đương lượng mol: Vì $\text{Mn}$ nhận $2e^-$ và có khối lượng nguyên tử tương đương ($54{,}94\text{ g/mol}$ so với $55{,}85\text{ g/mol}$ của $\text{Fe}$), nhu cầu đương lượng oxy hóa của $\text{Mn}$ về lý thuyết gấp đôi $\text{Fe}$.
- Công thức tính toán tổng lượng hóa chất oxy hóa khi nước thô chứa đồng thời cả $\text{Fe}^{2+}$ và $\text{Mn}^{2+}$:
  - Nhu cầu oxy hòa tan tổng cộng từ làm thoáng ($\text{DO}_{\text{demand}}$):
    $$\text{DO}_{\text{demand}} = 0{,}14 \cdot [\text{Fe}^{2+}] + 0{,}29 \cdot [\text{Mn}^{2+}]$$
  - Nhu cầu thuốc tím tổng cộng ($\text{Dose}_{\text{KMnO}_4}$):
    $$\text{Dose}_{\text{KMnO}_4} = 0{,}94 \cdot [\text{Fe}^{2+}] + 1{,}92 \cdot [\text{Mn}^{2+}]$$
  - Nhu cầu clo tự do tổng cộng ($\text{Cl}_{2,\text{demand}}$):
    $$\text{Cl}_{2,\text{demand}} = 0{,}63 \cdot [\text{Fe}^{2+}] + 1{,}28 \cdot [\text{Mn}^{2+}]$$
    (hoặc sử dụng hệ số lý thuyết tính toán $0{,}64 \cdot [\text{Fe}^{2+}] + 1{,}29 \cdot [\text{Mn}^{2+}]$).

---

#### 4.2.3 Thời gian phản ứng và Ảnh hưởng của pH

##### 4.2.3.1 Bảng thời gian phản ứng oxy hóa của các tác nhân
- Bảng tổng hợp thời gian phản ứng oxy hóa sắt và mangan đối với từng tác nhân ($\text{Oxidation Reaction Times for Iron and Manganese}$):
  - **Hình 4.** Thời gian phản ứng oxy hóa sắt và mangan (Oxidation Reaction Times for Iron and Manganese)
    - <img src="ch04_iron_manganese_removal/assets/fig_04_p7.png" alt="Hình 4" />
  - **Hình này chứng minh điều gì**
    - Thời gian phản ứng oxy hóa Mn luôn dài hơn Fe đáng kể, đặc biệt khi sử dụng oxy hòa tan từ làm thoáng.
  - **Từ đâu mà thấy được**
    - Cột thời gian phản ứng trên slide trang 7 cho thấy Mn cần từ 80 phút đến vài ngày đối với oxy, nhưng chỉ cần dưới 5-7 phút với KMnO4, ClO2, hoặc O3.

| Tác nhân oxy hóa (Oxidant) | Thời gian phản ứng cho $\text{Mn}$ (per mg/L of Mn) | Thời gian phản ứng cho $\text{Fe}$ (per mg/L of Fe) | Đặc trưng phản ứng và mức độ phụ thuộc pH |
| :--- | :---: | :---: | :--- |
| Oxy (từ làm thoáng - Oxygen from aeration) | $80\text{ phút}$ đến vài ngày (days) | $< 1\text{ phút}$ đến $1\text{ giờ}$ (hr) | Phụ thuộc rất chặt chẽ vào $\text{pH}$; tốc độ oxy hóa $\text{Mn}$ cực chậm ở $\text{pH}$ thường |
| Ozone ($\text{O}_3$) | $< 5\text{ phút}$ | $< 2\text{ phút}$ | Phản ứng gần như tức thời; ít bị chi phối bởi dao động $\text{pH}$ |
| Clo ($\text{Cl}_2$ - Chlorine) | $15\text{ phút}$ đến $12\text{ giờ}$ | $< 1\text{ phút}$ đến $1\text{ giờ}$ | Phụ thuộc vào $\text{pH}$; khử $\text{Mn}$ yêu cầu môi trường kiềm ($\text{pH} \ge 8{,}0 - 8{,}5$) |
| Thuốc tím ($\text{KMnO}_4$) | $< 7\text{ phút}$ | $< 5\text{ phút}$ | Tốc độ phản ứng cao; diễn ra nhanh và triệt để trong dải $\text{pH} \ge 7{,}2$ |
| Clo đioxit ($\text{ClO}_2$) | $< 5\text{ phút}$ | $< 5\text{ phút}$ | Tốc độ phản ứng cao và đồng đều cho cả hai kim loại |

##### 4.2.3.2 Tác động của pH và thời gian lưu tiếp xúc (Detention Time)
- Động học oxy hóa bằng không khí diễn ra khá chậm (quite slow) và chịu sự kiểm soát nghiêm ngặt của $\text{pH}$:
  - Phản ứng oxy hóa sắt bằng oxy hòa tan:
    - Ở dải $\text{pH} = 7{,}5 - 8{,}0$, thời gian phản ứng oxy hóa sắt kéo dài từ $15\text{ phút}$ đến $60\text{ phút}$ ($15\text{ minutes}$ and $60\text{ minutes}$).
    - Yêu cầu thiết kế kỹ thuật: Thời gian lưu tối thiểu trong bể tiếp xúc sau làm thoáng ($\text{minimum detention time after aeration}$) là $30\text{ phút}$ ($30\text{ minutes}$).
  - Phản ứng oxy hóa mangan bằng oxy hòa tan:
    - Ở $\text{pH} = 9{,}5$, phản ứng oxy hóa mangan đòi hỏi thời gian tiếp xúc lên đến $60\text{ phút}$ ($60\text{ minutes}$).
    - Ở các giá trị $\text{pH}$ thấp hơn ($\text{pH} < 9{,}5$), quá trình oxy hóa mangan bằng không khí hoàn toàn không mang tính thực tế (not practical).
- Nguyên lý động học theo nồng độ ion hydroxyl ($\text{OH}^-$):
  - Tốc độ oxy hóa đồng thể tỷ lệ bậc 2 với nồng độ ion $\text{OH}^-$:
    $$r = -\frac{d[\text{M}^{2+}]}{dt} = k \cdot [\text{M}^{2+}] \cdot P_{\text{O}_2} \cdot [\text{OH}^-]^2$$
  - Khi tăng $\text{pH}$ lên $1$ đơn vị, nồng độ $[\text{OH}^-]$ tăng $10$ lần, khiến tốc độ phản ứng oxy hóa tăng gấp $100$ lần ($10^2$).

---

#### 4.2.4 Động học thực nghiệm khử Sắt (Fe2+) trong nước ngầm

##### 4.2.4.1 Bảng thực nghiệm làm thoáng kết hợp lọc đối với Fe2+
- Dữ liệu thực nghiệm khử $\text{Fe}^{2+}$ trong nước ngầm ($\text{Ground water}$) bằng làm thoáng kết hợp lọc ($\text{aeration followed by filtration}$) từ nồng độ ban đầu $[\text{Fe}^{2+}]_0 = 10{,}0\text{ mg/L}$:

| $\text{pH}$ | $[\text{Fe}^{2+}]_0\text{ (mg/L)}$ | Sau $15\text{ phút (mg/L)}$ | Sau $30\text{ phút (mg/L)}$ | Sau $60\text{ phút (mg/L)}$ | Mức độ chuyển hóa và đánh giá |
| :---: | :---: | :---: | :---: | :---: | :--- |
| $5{,}00$ | $10{,}0$ | $9{,}0$ | $9{,}0$ | $7{,}5$ | Oxy hóa cực chậm; sau $60\text{ phút}$ chỉ khử được $25\%$ sắt ban đầu. |
| $5{,}50$ | $10{,}0$ | $5{,}5$ | $4{,}6$ | $4{,}0$ | Tốc độ chuyển hóa thấp; sắt dư sau $60\text{ phút}$ vẫn vượt xa quy chuẩn. |
| $5{,}95$ | $10{,}0$ | $5{,}0$ | $4{,}0$ | $3{,}5$ | Đạt hiệu suất khử $65\%$ sau $60\text{ phút}$, hàm lượng còn lại $3{,}5\text{ mg/L}$. |
| $6{,}15$ | $10{,}0$ | $4{,}4$ | $3{,}5$ | $2{,}5$ | Tốc độ tăng chậm; sau $60\text{ phút}$ nồng độ sắt vẫn còn $2{,}5\text{ mg/L}$. |
| $6{,}50$ | $10{,}0$ | $2{,}8$ | $1{,}8$ | $0{,}3$ | Đạt giới hạn quy chuẩn QCVN 01-1:2018/BYT ($\le 0{,}3\text{ mg/L}$) tại mốc $60\text{ phút}$. |
| $6{,}65$ | $10{,}0$ | $0{,}7$ | $0{,}2$ | $0{,}1$ | Tốc độ tăng đột biến; đạt quy chuẩn sau $30\text{ phút}$ ($0{,}2\text{ mg/L}$) và đạt $0{,}1\text{ mg/L}$ sau $60\text{ phút}$. |
| $6{,}80$ | $10{,}0$ | $0{,}2$ | $0{,}1$ | $< 0{,}1$ | Đạt chuẩn ngay sau $15\text{ phút}$ ($0{,}2\text{ mg/L}$) và giảm xuống $< 0{,}1\text{ mg/L}$ sau $60\text{ phút}$. |
| $7{,}00$ | $10{,}0$ | $0{,}1$ | $< 0{,}1$ | $< 0{,}1$ | Phản ứng diễn ra rất nhanh; đạt $0{,}1\text{ mg/L}$ sau $15\text{ phút}$ và $< 0{,}1\text{ mg/L}$ sau $30\text{ phút}$. |
| $7{,}45$ | $10{,}0$ | $0{,}1$ | $< 0{,}1$ | $< 0{,}1$ | Tốc độ hoàn tất nhanh tương tự mức $\text{pH} = 7{,}00$. |
| $8{,}05$ | $10{,}0$ | $< 0{,}1$ | $< 0{,}1$ | $< 0{,}1$ | Phản ứng diễn ra tức thời; nồng độ sắt giảm xuống $< 0{,}1\text{ mg/L}$ ngay trong $15\text{ phút}$ đầu. |

##### 4.2.4.2 Quy luật động học khử Fe2+ theo ngưỡng pH và thời gian
- Quá trình oxy hóa sắt bằng không khí phân hóa rõ rệt thành ba vùng $\text{pH}$:
  - Vùng axit ($\text{pH} = 5{,}00 - 6{,}15$): Tốc độ phản ứng rất chậm do thiếu hụt ion $\text{OH}^-$. Lượng sắt dư sau $60\text{ phút}$ duy trì từ $2{,}5$ đến $7{,}5\text{ mg/L}$, không thể xử lý đạt chuẩn nếu không kiềm hóa.
  - Vùng chuyển tiếp ($\text{pH} = 6{,}50 - 6{,}65$): Tốc độ phản ứng gia tăng mạnh mẽ. Sau $60\text{ phút}$ tại $\text{pH} = 6{,}50$, nồng độ sắt đạt $0{,}3\text{ mg/L}$. Tại $\text{pH} = 6{,}65$, thời gian đạt tiêu chuẩn rút ngắn xuống còn $30\text{ phút}$.
  - Vùng kiềm và trung tính tối ưu ($\text{pH} \ge 6{,}80$): Tốc độ phản ứng bùng nổ, sắt kết tủa gần như hoàn toàn trong vòng $15\text{ phút}$ ($[\text{Fe}^{2+}] \le 0{,}2\text{ mg/L}$) và đạt triệt để $< 0{,}1\text{ mg/L}$ sau $30 - 60\text{ phút}$.
- Kết luận thiết kế công nghệ khử sắt:
  - Để dây chuyền làm thoáng - lắng - lọc vận hành hiệu quả với thời gian lưu thực tế $30\text{ phút}$, giá trị $\text{pH}$ của nước thô sau làm thoáng phải đạt tối thiểu $\ge 6{,}8 - 7{,}0$.
  - Nếu nguồn nước ngầm có $\text{pH} < 6{,}5$, quy trình bắt buộc phải kết hợp thoát khí $\text{CO}_2$ triệt để trên giàn mưa hoặc châm thêm hóa chất kiềm hóa ($\text{NaOH}, \text{Ca(OH)}_2$).

---

#### 4.2.5 Động học thực nghiệm khử Mangan (Mn2+) trong nước ngầm

##### 4.2.5.1 Bảng thực nghiệm làm thoáng kết hợp lọc đối với Mn2+
- Dữ liệu thực nghiệm khử $\text{Mn}^{2+}$ trong nước ngầm ($\text{Ground water}$) bằng làm thoáng kết hợp lọc ($\text{aeration followed by filtration}$) từ nồng độ ban đầu $[\text{Mn}^{2+}]_0 = 10{,}0\text{ mg/L}$:

| $\text{pH}$ | $[\text{Mn}^{2+}]_0\text{ (mg/L)}$ | Sau $15\text{ phút (mg/L)}$ | Sau $30\text{ phút (mg/L)}$ | Sau $60\text{ phút (mg/L)}$ | Mức độ chuyển hóa và đánh giá |
| :---: | :---: | :---: | :---: | :---: | :--- |
| $8{,}50$ | $10{,}0$ | $10{,}0$ | $10{,}0$ | $10{,}0$ | Hoàn toàn không diễn ra oxy hóa; nồng độ mangan giữ nguyên $100\%$ sau $60\text{ phút}$. |
| $9{,}00$ | $10{,}0$ | $10{,}0$ | $10{,}0$ | $9{,}0$ | Tốc độ cực kỳ chậm; sau $60\text{ phút}$ chỉ loại bỏ được $10\%$ hàm lượng mangan ($9{,}0\text{ mg/L}$). |
| $9{,}30$ | $10{,}0$ | $8{,}5$ | $8{,}0$ | $7{,}5$ | Chuyển hóa không đáng kể; sau $60\text{ phút}$ nồng độ mangan còn rất cao ($7{,}5\text{ mg/L}$). |
| $9{,}50$ | $10{,}0$ | $7{,}5$ | $5{,}0$ | $3{,}2$ | Phản ứng bắt đầu tăng tốc; sau $60\text{ phút}$ nồng độ giảm xuống $3{,}2\text{ mg/L}$. |
| $9{,}70$ | $10{,}0$ | $3{,}0$ | $1{,}3$ | $0{,}9$ | Tốc độ chuyển hóa cao; sau $60\text{ phút}$ hàm lượng mangan giảm còn $0{,}9\text{ mg/L}$. |
| $9{,}95$ | $10{,}0$ | $0{,}9$ | $0{,}7$ | $0{,}6$ | Hiệu suất khử đạt $> 90\%$ sau $15\text{ phút}$ ($0{,}9\text{ mg/L}$) và còn $0{,}6\text{ mg/L}$ sau $60\text{ phút}$. |
| $10{,}30$ | $10{,}0$ | $< 0{,}02$ | $< 0{,}02$ | $< 0{,}02$ | Phản ứng diễn ra tức thời và hoàn toàn; nồng độ đạt chuẩn khắt khe $< 0{,}02\text{ mg/L}$ ngay sau $15\text{ phút}$. |

##### 4.2.5.2 Quy luật động học khử Mn2+ theo ngưỡng pH và thời gian
- So sánh động học oxy hóa giữa $\text{Mn}^{2+}$ và $\text{Fe}^{2+}$:
  - Ở cùng dải $\text{pH} = 7{,}0 - 8{,}5$, trong khi $\text{Fe}^{2+}$ bị oxy hóa và kết tủa hoàn toàn chỉ trong vài phút, $\text{Mn}^{2+}$ hầu như không phản ứng với oxy hòa tan.
  - Phản ứng oxy hóa $\text{Mn}^{2+}$ chỉ bắt đầu xuất hiện rõ nét khi $\text{pH} \ge 9{,}30$ và chỉ đạt tốc độ xử lý hữu hiệu ở $\text{pH} \ge 9{,}50 - 10{,}0$.
  - Ở $\text{pH} = 10{,}30$, phản ứng oxy hóa và kết tủa diễn ra gần như tức thời, đưa nồng độ mangan dư về dưới ngưỡng vết $< 0{,}02\text{ mg/L}$ (thấp hơn nhiều so với tiêu chuẩn QCVN 01-1:2018/BYT là $\le 0{,}1\text{ mg/L}$).
- Giải pháp kỹ thuật trong thực tế công nghệ xử lý nước cấp:
  - Vì việc nâng $\text{pH}$ nguồn nước lên $\ge 9{,}5 - 10{,}3$ đòi hỏi lượng hóa chất kiềm hóa ($\text{vôi, xút}$) rất lớn và bắt buộc phải châm axit để trung hòa lại trước khi cấp vào mạng lưới, phương pháp làm thoáng oxy hóa đơn thuần bằng không khí không kinh tế đối với mangan.
  - Các nhà máy cấp nước áp dụng hai giải pháp thay thế chủ đạo:
    - Giải pháp 1: Sử dụng hóa chất oxy hóa mạnh như thuốc tím ($\text{KMnO}_4$), clo ($\text{Cl}_2$) hoặc ozone ($\text{O}_3$), cho phép phản ứng diễn ra nhanh ở dải $\text{pH}$ trung tính ($7{,}0 - 8{,}0$).
    - Giải pháp 2: Sử dụng công nghệ lọc xúc tác tiếp xúc với vật liệu lọc tráng phủ $\text{MnO}_2$ (như cát Greensand, hạt Birm, quặng Pyrolusite LayneOx™), tận dụng cơ chế hấp phụ bề mặt kết hợp tự xúc tác để oxy hóa mangan mà không cần nâng cao $\text{pH}$.

### 4.3 Công nghệ và Công trình xử lý Sắt và Mangan

- Công nghệ khử sắt và mangan sử dụng các quá trình truyền khối pha khí - lỏng kết hợp oxy hóa và lọc:
  - Nước ngầm chứa sắt và mangan ở dạng khử hòa tan [$\text{Fe(II)}$ và $\text{Mn(II)}$] cần chuyển đổi thành dạng oxy hóa kết tủa không tan [$\text{Fe(III)}$ và $\text{Mn(IV)}$].
  - Dây chuyền công nghệ tiêu chuẩn kết hợp các công đoạn: làm thoáng (aeration) hoặc khử khí (air stripping), trung hòa $\text{pH}$, tiếp xúc phản ứng (contact aeration), lắng cặn và lọc qua các tầng vật liệu xúc tác.

#### 4.3.1 Nguyên lý truyền khối: Hấp thụ và Giải hấp (Khử khí)

- Quá trình làm thoáng (aeration) và thoát khí (air stripping) là hai quá trình đơn vị ($2\text{ unit processes}$) cốt lõi trong xử lý nước:
  - Cả hai quá trình vận dụng các nguyên lý truyền khối (mass transfer) để chuyển dịch các chất dễ bay hơi giữa pha lỏng (liquid phase) và pha khí (gaseous phase).
  - Quá trình tạo sự tiếp xúc mật thiết (intimate contact) giữa không khí và nước trên bề mặt tiếp xúc liên pha.

##### 4.3.1.1 Phân định hai chiều truyền khối: Giải hấp (Desorption) và Hấp thụ (Absorption)
- Quá trình giải hấp (Desorption / Air Stripping) tách hợp chất dễ bay hơi từ pha lỏng sang pha khí:
  - Chuyển các chất khí hòa tan không mong muốn từ nước vào không khí khí quyển:
    - Khí hydro sulfide ($\text{H}_2\text{S}$): Khử mùi trứng thối và giảm tải lượng chất khử tiêu hao chất oxy hóa.
    - Khí carbonic tự do ($\text{CO}_2$): Giảm nồng độ axit cacbonic, nâng cao giá trị $\text{pH}$ của nước tự nhiên và ổn định chỉ số bão hòa cacbonat.
    - Hợp chất hữu cơ dễ bay hơi ($\text{VOCs}$): Tách bỏ các dung môi clo hóa và hydrocarbon nhẹ ra khỏi nguồn nước thô.
  - Air stripping là một trong các quá trình giải hấp phổ biến nhất được sử dụng trong công nghệ xử lý nước cấp.
- Quá trình hấp thụ (Absorption / Aeration) hòa tan chất khí từ pha khí vào pha lỏng:
  - Chuyển khí từ môi trường không khí hòa tan vào trong thể tích nước:
    - Khí oxygen ($\text{O}_2$): Nâng cao nồng độ oxy hòa tan ($\text{DO}$) để phục vụ phản ứng oxy hóa ion $\text{Fe}^{2+}$ và $\text{Mn}^{2+}$.
    - Khí carbon dioxide ($\text{CO}_2$): Hòa tan trong một số trường hợp tái cacbonat hóa để điều chỉnh cân bằng kiềm.
  - Aeration đưa oxy vào nước là quá trình hấp thụ khí được áp dụng rộng rãi nhất trong xử lý nước cấp.

##### 4.3.1.2 Động học truyền khối theo Thuyết hai màng (Two-Film Theory)
- Cơ chế truyền khối liên pha qua màng chất lưu tiếp xúc:
  - Thuyết hai màng của Lewis và Whitman giả định tồn tại hai màng mỏng tĩnh (laminar boundary films) tại ranh giới tiếp xúc: màng khí và màng lỏng.
  - Động lực truyền khối là độ chênh lệch nồng độ chất khí giữa trạng thái bão hòa cân bằng và trạng thái thực tế trong lòng pha lỏng.
- Phương trình tốc độ truyền khối qua bề mặt liên pha:
  $$N_A = K_L (C^* - C_L)$$
  - $N_A$: Suất truyền khối chất tan qua một đơn vị diện tích bề mặt pha ($\text{mg}/(\text{m}^2\cdot\text{s})$ hoặc $\text{mol}/(\text{m}^2\cdot\text{s})$).
  - $K_L$: Hệ số truyền khối tổng quát pha lỏng ($\text{m/s}$).
  - $C^*$: Nồng độ bão hòa cân bằng của chất khí trong pha lỏng tại bề mặt tiếp xúc pha ($\text{mg/L}$), xác định theo Định luật Henry ($C^* = H \cdot P_g$).
  - $C_L$: Nồng độ thực tế của chất khí trong thể tích pha lỏng ($\text{mg/L}$).
- Phương trình biến thiên nồng độ khí hòa tan theo thời gian:
  $$\frac{dC}{dt} = K_L a \cdot (C_s - C)$$
  - $\frac{dC}{dt}$: Tốc độ biến thiên nồng độ khí hòa tan trong nước theo thời gian ($\text{mg}/(\text{L}\cdot\text{s})$).
  - $K_L a$: Hệ số truyền khối thể tích kết hợp ($\text{s}^{-1}$ hoặc $\text{h}^{-1}$).
  - $a$: Diện tích bề mặt tiếp xúc pha riêng trên một đơn vị thể tích lỏng ($\text{m}^2/\text{m}^3$).
  - $C_s$: Nồng độ bão hòa của khí ở nhiệt độ và áp suất môi trường ($\text{mg/L}$).
  - $C$: Nồng độ tức thời của khí hòa tan tại thời điểm $t$ ($\text{mg/L}$).
- Tác động công nghệ của việc gia tăng diện tích tiếp xúc riêng ($a$):
  - Thiết bị tiếp xúc không khí - nước (air–water contactors) gia tăng diện tích bề mặt tiếp xúc liên pha ($a$).
  - Tốc độ truyền khối của quá trình hấp thụ và giải hấp tăng hiệu quả hơn so với tốc độ khuếch tán tự nhiên qua mặt thoáng hở.
  - Tốc độ truyền khối tăng giúp rút ngắn thời gian tiếp xúc cần thiết và giảm thể tích công trình xử lý.

#### 4.3.2 Phân loại thiết bị tiếp xúc pha khí - lỏng

- Thiết bị truyền khí (gas transfer devices) được chia thành hai nhóm công nghệ chính dựa trên bản chất pha liên tục:
  - Nhóm 1: Thiết bị tiếp xúc pha khí (Gas-phase contactors).
  - Nhóm 2: Thiết bị tiếp xúc ngập lỏng (Flooded contactors).

##### 4.3.2.1 Thiết bị tiếp xúc pha khí liên tục (Gas-Phase Contactors)
- Cơ chế vận hành của thiết bị tiếp xúc pha khí:
  - Phân tán nước thành các tia, giọt nước nhỏ (droplets of water) hoặc màng nước mỏng rơi vào môi trường pha khí liên tục (continuous gas phase).
  - Tạo ra tỷ số diện tích bề mặt trên thể tích ($a/V$) rất lớn cho các hạt nước.
  - Tiêu hao năng lượng cấp khí thấp; thường tận dụng thông gió tự nhiên hoặc quạt thổi áp lực thấp.
- Các dạng công trình tiếp xúc pha khí điển hình:
  - Giàn làm thoáng nhiều tầng khay (Multiple tray aerator).
  - Dàn làm thoáng bậc tràn thác nước (Cascade aerator).
  - Tháp đệm làm thoáng tiếp xúc ngược dòng (Countercurrent packed tower).
  - Thiết bị làm thoáng khay lỗ biên dạng thấp (Low-profile or sieve tray aerator).
  - Giàn làm thoáng vòi phun mưa áp lực (Spray aerator).

##### 4.3.2.2 Thiết bị tiếp xúc pha lỏng liên tục (Flooded Contactors)
- Cơ chế vận hành của thiết bị tiếp xúc ngập lỏng:
  - Phân tán các bọt khí (bubbles of air) vào trong thể tích nước liên tục (continuous liquid phase).
  - Bọt khí nổi từ đáy lên đỉnh bể dưới tác dụng của lực đẩy Archimedes, tạo dòng tuần hoàn và truyền khối trực tiếp cho chất lỏng.
- Các cấu hình công trình ngập lỏng:
  - Bể sục khí nén với đĩa phân phối bọt khí mịn (Fine bubble diffused aeration tanks).
  - Thiết bị sục khí cơ học tuabin ngập nước (Submerged mechanical aerators).
  - Hệ thống sục khí phản lực (Jet aeration systems).
  - Ưu điểm: Hạn chế tắc nghẽn do bùn cặn sắt kết tủa và cho phép kiểm soát linh hoạt thời gian tiếp xúc của nước.

#### 4.3.3 Thiết bị làm thoáng giàn mưa và bậc tràn (Multiple Tray & Cascade Aerators)

##### 4.3.3.1 Cấu tạo và Cơ chế của Giàn làm thoáng nhiều khay (Multiple Tray Aerator)
- Cấu tạo hình học và thành phần kết cấu:
  - Tháp gồm từ $3$ đến $5$ khay đục lỗ xếp chồng thẳng đứng với khoảng cách giữa các tầng khay từ $30\text{ cm}$ đến $50\text{ cm}$.
  - Nước thô cấp từ ống dẫn đỉnh ("Inlet pipe") vào hộp phân phối để tràn màng mỏng qua các tầng khay.
  - Mỗi khay chứa lớp vật liệu đệm bằng than cốc (coke), xỉ quặng hoặc đá dăm dày $10\text{ cm}$ đến $20\text{ cm}$ với cỡ hạt $40\text{ mm}$ đến $60\text{ mm}$.
  - Màng sinh học hoặc lớp oxit sắt bám trên bề mặt hạt đệm đóng vai trò chất xúc tác oxy hóa tự nhiên.
- Dòng khí và cấu trúc khay thanh gỗ:
  - Dàn khay thanh gỗ redwood ("Redwood slat trays") cho phép nước phân tách thành các giọt mịn rơi tự do.
  - Quạt thổi khí ("Air blower") đưa không khí sạch từ đáy tháp thổi ngược chiều dòng nước rơi và thoát ra cửa xả đỉnh ("Air exhaust").
  - **Hình 5.** Cấu tạo giàn làm thoáng nhiều khay tiếp xúc pha khí
    - <img src="ch04_iron_manganese_removal/assets/fig_05_p12.jpeg" alt="Hình 5" />
  - **Hình này chứng minh điều gì**
    - Nước chảy thành màng mỏng qua các khay đệm hoặc nhỏ giọt qua khay thanh gỗ tiếp xúc với luồng khí cưỡng bức.
  - **Từ đâu mà thấy được**
    - Từ trái sang phải: (a) nước từ "Inlet pipe" qua hộp phân phối chảy tràn màng mỏng qua các khay chứa vật liệu đệm (than coke).
    - (b) nước từ đỉnh rơi qua các khay "Redwood slat trays" ngược chiều luồng khí từ quạt "Air blower" thoát ra "Air exhaust".
    - Lưu ý: hình ghi Redwood slat trays, văn bản ghi (b) cascade aerator.

##### 4.3.3.2 Cấu tạo và Cơ chế của Dàn làm thoáng bậc tràn (Cascade Aerator)
- Cấu tạo và nguyên lý thủy lực bậc tràn:
  - Nước chảy qua chuỗi các bậc thang dốc trọng lực bằng bê tông cốt thép hoặc thép không gỉ.
  - Chiều cao mỗi bậc thang từ $0.15\text{ m}$ đến $0.30\text{ m}$; tổng chiều cao rơi nước toàn dàn từ $1.5\text{ m}$ đến $3.0\text{ m}$.
  - Vận tốc dòng chảy tăng dần qua gờ bậc, tạo dòng xoáy xáo trộn mãnh liệt và cuốn không khí vào chân bậc tràn.
- Thông số vận hành kỹ thuật:
  - Tải trọng thủy lực bề mặt: $20$ đến $40\text{ m}^3/(\text{m}^2\cdot\text{h})$.
  - Diện tích mặt bằng yêu cầu lớn hơn giàn khay nhưng chi phí đầu tư và năng lượng vận hành rất thấp vì không cần quạt gió.

#### 4.3.4 Tháp đệm ngược dòng, giàn đĩa lỗ và giàn phun mưa

##### 4.3.4.1 Cấu tạo và Nguyên lý Tháp đệm tiếp xúc ngược dòng (Countercurrent Packed Tower)
- Thiết kế tháp đệm hình trụ thẳng đứng:
  - Tháp vỏ thép hoặc composite chứa lớp vật liệu đệm ngẫu nhiên (`Random packing`) bằng nhựa PP/PVC (vòng Raschig, vòng Pall, Tri-Packs).
  - Chiều cao lớp đệm từ $1.0\text{ m}$ đến $3.0\text{ m}$; diện tích bề mặt riêng đạt $100$ đến $300\text{ m}^2/\text{m}^3$.
  - Nước thô phun từ dàn phân phối đỉnh chảy màng mỏng bao bọc bề mặt đệm đi xuống đáy.
  - Luồng khí sạch (`Clean air`) từ quạt thổi cấp vào đáy tháp đi ngược chiều lên đỉnh, tối đa hóa động lực truyền khối ($C^* - C$).
  - Bộ tách sương (`Demister`) lắp ở đỉnh tháp thu hồi các giọt nước bị dòng khí cuốn theo.

##### 4.3.4.2 Cấu tạo Giàn làm thoáng khay đĩa lỗ (Sieve Tray Aerator) và Giàn vòi phun (Spray Aerator)
- Cấu tạo giàn làm thoáng khay lỗ biên dạng thấp (Low-profile sieve tray):
  - Gồm chuỗi các khay đục lỗ (`Perforated tray`) nối với nhau qua vách tràn và ống chảy chuyền (`Weir and downcomer`).
  - Dòng khí thổi từ đáy xuyên qua các lỗ khay sục sôi lớp nước trên khay (chế độ sủi bọt - froth regime).
  - Chiều cao công trình nhỏ gọn, dễ tháo lắp vệ sinh cặn sắt định kỳ.
- Cấu tạo giàn làm thoáng vòi phun áp lực (Spray aerator):
  - Áp lực từ ống đẩy bơm phun nước thẳng lên không gian khí quyển qua các vòi phun định hình.
  - Nước vỡ thành chùm tia và hạt sương kích thước $2$ đến $5\text{ mm}$, gia tăng tối đa diện tích tiếp xúc trước khi rơi xuống sàn thu.
  - **Hình 8.** Cấu tạo các thiết bị tiếp xúc pha khí điển hình
    - <img src="ch04_iron_manganese_removal/assets/fig_08_p13.png" alt="Hình 8" />
  - **Hình này chứng minh điều gì**
    - Cấu tạo chi tiết và cơ chế tiếp xúc khí - nước: tháp đệm và khay lỗ vận hành ngược dòng, vòi phun phân tán nước thành tia vào không khí.
  - **Từ đâu mà thấy được**
    - Panel (c): Nước từ đỉnh qua giàn phân phối tưới xuống tầng đệm (`Random packing`), ngược chiều với khí sạch (`Clean air`) thổi từ đáy.
    - Panel (d): Nước chảy qua các khay lỗ (`Perforated tray`) nối bởi ống chảy chuyền (`Weir and downcomer`), khí đi từ dưới lên qua bộ tách sương (`Demister`).
    - Panel (e): Vòi phun gắn trên ống đẩy tia nước phun ngược lên không gian khí quyển.

#### 4.3.5 Cấu tạo chi tiết giàn mưa nhiều tầng và giàn phun nước

##### 4.3.5.1 Cấu tạo thực tế dàn làm thoáng bậc tràn Cascade Aerator
- Cấu tạo bề mặt dòng tràn và gờ răng cưa phân dòng:
  - Mặt cắt bậc tràn được tạo gờ răng cưa so le giúp xé màng nước liên tục thành các luồng tia nhỏ.
  - Độ chênh cao giữa các bậc kích thích hiện tượng cuốn khí tự nhiên (air entrainment).
  - Chân mỗi bậc tràn hình thành vùng nước xoáy sủi bọt khí dày đặc, tăng cường hòa tan oxy và giải phóng khí $\text{CO}_2$.
  - **Hình 9.** Dàn làm thoáng bậc tràn cascade aerator trong thực tế
    - <img src="ch04_iron_manganese_removal/assets/fig_09_p14.jpeg" alt="Hình 9" />
  - **Hình này chứng minh điều gì**
    - Cấu tạo các bậc tràn chia nhỏ dòng chảy, tạo xáo trộn mãnh liệt và bọt khí tiếp xúc tự nhiên.
  - **Từ đâu mà thấy được**
    - Quan sát các gờ bậc thang từ trên xuống: hàng mấu răng cưa phân tách dòng nước thành các luồng màng mỏng.
    - Chân mỗi bậc tràn sủi bọt trắng xóa do dòng nước va đập cuốn theo không khí quyển.

##### 4.3.5.2 Cấu tạo thực tế giàn làm thoáng kiểu phun tia (Spray Aerator)
- Mạng lưới phân phối áp lực trên sàn làm thoáng:
  - Ống góp chính hình trụ nằm ngang phân nhánh vào mạng ống nhánh song song đặt trên cao.
  - Các đầu vòi phun được bắt ren định khoảng cách đều trên các ống nhánh, hướng dòng tia thẳng xuống sàn hứng.
  - Màn tia nước dày đặc giao thoa tạo vùng tiếp xúc khí quyển diện tích lớn trên toàn bộ mặt sàn công trình.
  - **Hình 10.** Cấu tạo thực tế dàn làm thoáng kiểu phun tia
    - <img src="ch04_iron_manganese_removal/assets/fig_10_p14.jpeg" alt="Hình 10" />
  - **Hình này chứng minh điều gì**
    - Mạng ống nhánh song song rẽ từ ống góp chính xé nhỏ dòng nước thành các chùm tia phân tán đều.
  - **Từ đâu mà thấy được**
    - Ống góp chính hình trụ nằm ngang (có mặt bích bên trái) liên kết dãy ống nhánh vươn dài ra sàn làm thoáng.
    - Dọc thân các ống nhánh, các vòi phun xả nước thành màn tia dày đặc xuống giàn thoáng bên dưới.

#### 4.3.6 Dây chuyền công nghệ đa bậc: Trung hòa pH, Khử sắt và Khử mangan

- Nguyên tắc bố trí công nghệ dây chuyền đa bậc:
  - Phản ứng oxy hóa sắt và mangan đòi hỏi điều kiện $\text{pH}$ khác nhau: sắt oxy hóa nhanh ở $\text{pH } \ge 6.8$, trong khi mangan đòi hỏi $\text{pH } \ge 8.0 - 9.0$ hoặc chất oxy hóa mạnh.
  - Sắt oxy hóa trước và tạo nhiều bùn bông kết tủa $\text{Fe(OH)}_3$, có thể bọc kín bề mặt vật liệu xúc tác mangan nếu bố trí chung một công trình.
  - Dây chuyền tách biệt theo 3 bể chức năng nối tiếp: Bể trung hòa $\text{pH}$ $\to$ Bể lọc khử sắt $\to$ Bể lọc xúc tác khử mangan.

##### 4.3.6.1 Bể trung hòa pH với vật liệu kiềm hóa (pH Neutralization Tank)
- Cấu tạo và cơ chế kiềm hóa tự cân bằng:
  - Thân bể hình trụ đứng chứa lớp vật liệu khoáng kiềm hóa: Calcite ($\text{CaCO}_3$) và Akdolit / Magno ($\text{CaCO}_3 \cdot \text{MgO}$).
  - Phản ứng hòa tan vật liệu tiêu thụ khí $\text{CO}_2$ tự do trong nước thô:
    $$\text{CaCO}_3 + \text{CO}_2 + \text{H}_2\text{O} \rightleftharpoons \text{Ca}^{2+} + 2\text{HCO}_3^-$$
    $$\text{MgO} + 2\text{CO}_2 + \text{H}_2\text{O} \rightleftharpoons \text{Mg}^{2+} + 2\text{HCO}_3^-$$
  - Nâng $\text{pH}$ nước từ dải axit yếu ($5.5 - 6.5$) lên ngưỡng kiềm ổn định ($7.2 - 8.2$) mà không lo quá liều hóa chất.
  - Đáy bể bố trí lớp sỏi đỡ (`Gravel`) bao quanh hệ thống chõ thu nước trung tâm.
  - **Hình 18.** Cấu tạo bể trung hòa pH với vật liệu Calcite và Akdolit
    - <img src="ch04_iron_manganese_removal/assets/fig_18_p15.jpeg" alt="Hình 18" />
  - **Hình này chứng minh điều gì**
    - Bể trung hòa sử dụng lớp vật liệu kiềm hóa gồm Calcite và Akdolit đặt trên lớp sỏi đỡ để nâng $\text{pH}$.
  - **Từ đâu mà thấy được**
    - Mặt cắt hai bên thân bể chỉ rõ vật liệu Calcite (bên trái) và Akdolit (bên phải).
    - Tầng đáy là lớp sỏi đỡ (Gravel) bao quanh cụm chõ lọc và ống phân phối trung tâm.

##### 4.3.6.2 Bể lọc khử sắt đa tầng (Iron Removal Multi-Media Filter)
- Cấu tạo tầng vật liệu lọc đa tầng (Multi-media layers):
  - Lớp trên cùng: Than anthracite (`Filter coal`) tỷ trọng nhẹ ($1.4 - 1.6\text{ g/cm}^3$), cỡ hạt thô ($0.8 - 1.8\text{ mm}$), giữ phần lớn bông cặn hydroxit sắt mà không làm tắc nhanh bề mặt.
  - Lớp giữa: Cát thạch anh (`Sand`) tỷ trọng trung bình ($2.65\text{ g/cm}^3$), cỡ hạt $0.45 - 0.55\text{ mm}$, lọc các hạt cặn mịn lọt qua tầng anthracite.
  - Lớp dưới: Garnet mịn (`Fine Garnet`, cỡ $0.2 - 0.4\text{ mm}$) và Garnet thô (`Coarse Garnet`, cỡ $0.4 - 0.8\text{ mm}$) có tỷ trọng lớn ($3.8 - 4.2\text{ g/cm}^3$) tạo màng lọc chặn cặn tinh.
  - Lớp đáy: Sỏi đỡ (`Gravel`) giữ vật liệu không lọt vào đường ống thu đáy.
  - **Hình 16.** Cấu tạo các tầng vật liệu trong bể lọc khử sắt
    - <img src="ch04_iron_manganese_removal/assets/fig_16_p15.jpeg" alt="Hình 16" />
  - **Hình này chứng minh điều gì**
    - Bể bố trí các tầng vật liệu lọc đa tầng gồm anthracite, cát, garnet mịn, garnet thô và sỏi đỡ.
  - **Từ đâu mà thấy được**
    - Cột chú thích từ trên xuống dưới chỉ rõ: Anthracite (filter coal), Sand, Fine Garnet, Coarse Garnet và Gravel bao quanh ống thu nước đáy.

##### 4.3.6.3 Bể lọc xúc tác khử mangan (Manganese Removal Filter Tank)
- Cấu tạo tầng lọc cát Greensand:
  - Lớp vật liệu xúc tác Greensand đặt phía dưới lớp than anthracite tùy chọn.
  - Dưới đáy là tầng đệm sỏi và garnet thô bao bọc cụm chõ lọc để bảo đảm phân phối nước rửa ngược đều.
  - Bể thực hiện đồng thời phản ứng xúc tác oxy hóa mangan hòa tan và giữ lại kết tủa $\text{MnO}_2$ tạo thành.
  - **Hình 17.** Cấu tạo cột lọc khử mangan đa tầng dùng cát Greensand
    - <img src="ch04_iron_manganese_removal/assets/fig_17_p15.jpeg" alt="Hình 17" />
  - **Hình này chứng minh điều gì**
    - Bể lọc dùng lớp cát Greensand xúc tác đặt trên các tầng đệm sỏi và garnet.
  - **Từ đâu mà thấy được**
    - Mặt cắt từ trên xuống: than anthracite tùy chọn, tầng Greensand, lớp đệm garnet thô và sỏi.
    - Ống phân phối đứng ở tâm nối cụm chụp lọc đặt chìm trong lớp sỏi đáy.

##### 4.3.6.4 Bể tiếp xúc và Thời gian lưu phản ứng (Detention Tank / Contact Bed)
- Yêu cầu thủy lực về thời gian tiếp xúc phản ứng:
  - Sau công đoạn làm thoáng, nước ngầm chứa sắt cần được dẫn qua bể tiếp xúc (contact chamber / detention tank) hoặc đệm tiếp xúc (contact bed).
  - Thời gian lưu nước tiếp xúc tối thiểu đạt từ $30$ đến $45\text{ phút}$ (theo tiêu chuẩn kỹ thuật cấp nước TCXDVN 33:2006).
  - Khoảng thời gian này bảo đảm các ion sắt $\text{Fe}^{2+}$ hòa tan oxy hóa thành $\text{Fe}^{3+}$ và thủy phân kết bông hoàn toàn thành $\text{Fe(OH)}_3$ trước khi đi vào bể lọc, ngăn ngừa cặn lọt lưới lọc gây đục nước sau xử lý.

#### 4.3.7 Vật liệu lọc cát mangan Greensand

##### 4.3.7.1 Cấu tạo và Cơ chế xúc tác oxy hóa của Greensand
- Bản chất cấu tạo hạt lọc Greensand:
  - Vật liệu chế tạo từ khoáng glauconite tự nhiên (màu xanh lục) hoặc hạt cát thạch anh bọc lớp oxit mangan hoạt tính ($\text{MnO}_2$).
  - Bề mặt hạt có cấu trúc xốp với diện tích tiếp xúc lớn, giàu mangan hóa trị cao ($\text{Mn}^{4+}$).
- Cơ chế phản ứng oxy hóa xúc tác:
  - Lớp phủ $\text{MnO}_2$ vừa đóng vai trò chất xúc tác bề mặt vừa là chất oxy hóa trực tiếp:
    $$\text{Fe}^{2+} + \text{MnO}_2(\text{s}) + 2\text{H}_2\text{O} \to \text{Fe(OH)}_3\downarrow + \text{MnOOH}(\text{s})$$
    $$\text{Mn}^{2+} + \text{MnO}_2(\text{s}) + \text{H}_2\text{O} \to 2\text{MnOOH}\downarrow$$
  - Hoàn nguyên (Regeneration): Vật liệu cần được hoàn nguyên định kỳ bằng dung dịch thuốc tím $\text{KMnO}_4$ theo tỷ lệ $1.5 - 2.0\text{ g KMnO}_4$ trên mỗi lít Greensand để khôi phục trạng thái oxy hóa của màng $\text{MnO}_2$.

##### 4.3.7.2 Điều kiện vận hành tiêu chuẩn của vật liệu lọc Greensand
- Bảng thông số kỹ thuật và chế độ thủy lực theo tiêu chuẩn vận hành:
  - Dải $\text{pH}$ nước thô (Raw Water pH): $6.2$ đến $8.8$.
  - Chiều sâu lớp vật liệu lọc (Bed Depth): $30\text{ in.}$ ($\approx 76.2\text{ cm}$).
  - Tốc độ lọc danh định (Service Flow Rate): $5\text{ gpm/sq. ft.}$ ($\approx 12.2\text{ m/h}$).
  - Tốc độ rửa ngược (Backwash Flow Rate): $8$ đến $12\text{ gpm/sq. ft.}$ ($\approx 19.5 - 29.3\text{ m/h}$).
  - Giới hạn xử lý thực tế tối đa (Max. Practical Limit): Tổng nồng độ $\text{Fe} + \text{Mn}$ lên tới $15\text{ ppm}$ ($15\text{ mg/L}$); nồng độ $\text{H}_2\text{S}$ tối đa $5\text{ ppm}$ ($5\text{ mg/L}$).
  - **Hình 19.** Điều kiện vận hành của vật liệu lọc Greensand
    - <img src="ch04_iron_manganese_removal/assets/fig_19_p16.png" alt="Hình 19" />
  - **Hình này chứng minh điều gì**
    - Greensand yêu cầu $\text{pH}$ từ $6.2 - 8.8$, lưu lượng $5\text{ gpm/sq. ft.}$ và nồng độ nguồn tối đa $15\text{ ppm}$ ($\text{Fe}$/$\text{Mn}$), $5\text{ ppm}$ ($\text{H}_2\text{S}$).
  - **Từ đâu mà thấy được**
    - Bảng "Conditions For Operation" đối chiếu thông số vận hành ở cột trái với giá trị cột phải.
    - Các hàng: "Raw Water pH" ($6.2 - 8.8$), "Bed Depth" ($30\text{ in.}$), "Service Flow Rate" ($5\text{ gpm/sq. ft.}$), "Backwash Flow Rate" ($8 - 12\text{ gpm/sq. ft.}$), "Max. Practical Limit" ($15\text{ ppm}$ cho $\text{Fe}$/$\text{Mn}$, $5\text{ ppm}$ cho $\text{H}_2\text{S}$).

#### 4.3.8 Vật liệu lọc xúc tác Birm

##### 4.3.8.1 Ưu điểm công nghệ và Đặc tính vật lý của Regular Birm và Fine Birm
- Ưu điểm công nghệ của vật liệu Birm:
  - Không cần bổ sung hóa chất tái sinh (thuốc tím $\text{KMnO}_4$ hoặc clo) vào chu trình hoàn nguyên.
  - Vận hành như một chất xúc tác không tiêu hao: hạt nhôm silicat phủ $\text{MnO}_2$ xúc tác cho phản ứng giữa ion hòa tan và oxy hòa tan trong nước.
  - Quy trình bảo trì đơn giản: chỉ cần rửa ngược định kỳ bằng nước sạch để loại bỏ cặn hydroxit sắt tích tụ.
- So sánh đặc tính vật lý giữa Regular Birm và Fine Birm:
  - Cả hai loại có cùng khối lượng thể tích biểu kiến: $2.0\text{ g/cm}^3$ ($2.0\text{ gm/cc}$).
  - Regular Birm: Cỡ hạt hiệu dụng (`Effective Size`) đạt $0.59\text{ mm}$, dải kích thước sàng (`Mesh Size`) $9 \times 35\text{ mesh}$.
  - Fine Birm: Cỡ hạt hiệu dụng đạt $0.48\text{ mm}$, dải kích thước sàng $10 \times 40\text{ mesh}$ (diện tích riêng bề mặt lớn hơn, phù hợp khử cặn tinh).
  - **Hình 23.** Ưu điểm và đặc tính vật lý của Birm
    - <img src="ch04_iron_manganese_removal/assets/fig_23_p17.png" alt="Hình 23" />
  - **Hình này chứng minh điều gì**
    - Birm không cần hóa chất hoàn nguyên; Regular Birm và Fine Birm có cùng tỷ trọng ($2.0\text{ gm/cc}$) nhưng khác nhau về cỡ hạt hiệu dụng ($0.59\text{ mm}$ so với $0.48\text{ mm}$).
  - **Từ đâu mà thấy được**
    - Phần "ADVANTAGES": xác nhận không cần hóa chất để duy trì, không cần hoàn nguyên và chỉ cần rửa ngược định kỳ.
    - Phần "PHYSICAL PROPERTIES": so sánh dòng "Effective Size" ($0.59\text{ mm}$ so với $0.48\text{ mm}$) và "Mesh Size" ($9 \times 35$ so với $10 \times 40$).

##### 4.3.8.2 Điều kiện vận hành tiêu chuẩn của Birm
- Quy định hóa học nghiêm ngặt nguồn nước thô vào bể lọc Birm:
  - Dải $\text{pH}$ nguồn nước: $\text{pH } 6.8$ đến $9.0$. Để khử mangan hiệu quả bằng Birm, $\text{pH}$ cần đạt từ $8.0$ đến $8.5$.
  - Hàm lượng oxy hòa tan ($\text{D.O.}$): Phải đạt tối thiểu $15\%$ so với nồng độ sắt tổng trong nước thô ($\text{DO} \ge 0.15 \times [\text{Fe}]$).
  - Độ kiềm ($\text{Alkalinity}$): Phải lớn hơn ít nhất $2$ lần tổng nồng độ của ion sulfate ($\text{SO}_4^{2-}$) và chloride ($\text{Cl}^-$).
  - Clo dư tự do ($\text{Free Chlorine}$): Khống chế $< 0.5\text{ ppm}$ để ngăn ngừa phá hủy lớp vỏ xúc tác của hạt Birm.
  - Khí hydro sulfide ($\text{H}_2\text{S}$): Phải khử sạch hoàn toàn trước khi nước vào lớp lọc Birm (sulfide làm vô hiệu hóa hoạt tính xúc tác).
  - Chất hữu cơ và dầu mỡ: Nước không được chứa dầu mỡ hoặc polyphosphate.
- Thông số thiết kế và thủy lực rửa lọc:
  - Chiều sâu lớp vật liệu lọc (Bed depth): $30$ đến $36\text{ in.}$ ($\approx 76.2 - 91.4\text{ cm}$).
  - Tốc độ lọc danh định (Service flowrate): $3.5$ đến $5.0\text{ gpm/sq. ft.}$ ($\approx 8.5 - 12.2\text{ m/h}$).
  - Tốc độ rửa ngược (Backwash rate): $8$ đến $12\text{ gpm/sq. ft.}$ ($\approx 19.5 - 29.3\text{ m/h}$).
  - Độ giãn nở lớp vật liệu khi rửa ngược (Backwash Bed Expansion): $20\%$ đến $40\%$.
  - **Hình 24.** Điều kiện vận hành tiêu chuẩn của vật liệu lọc Birm
    - <img src="ch04_iron_manganese_removal/assets/fig_24_p17.png" alt="Hình 24" />
  - **Hình này chứng minh điều gì**
    - Birm đòi hỏi môi trường kiềm tính ($\text{pH } 6.8\text{--}9.0$, $\text{D.O.} \ge 15\%$), khống chế $\text{Cl}_2 < 0.5\text{ ppm}$ và loại bỏ triệt để $\text{H}_2\text{S}$.
    - Quy định chế độ thủy lực với tốc độ lọc $3.5\text{--}5\text{ gpm/sq. ft.}$ và tốc độ rửa ngược $8\text{--}12\text{ gpm/sq. ft.}$ để lớp lọc giãn nở $20\text{--}40\%$.
  - **Từ đâu mà thấy được**
    - Các dòng điều kiện hóa học dưới `CONDITIONS FOR OPERATION`: `Water pH range` ($6.8\text{--}9.0$), `Dissolved Oxygen` ($\ge 15\%$), `Alkalinity`, `Free chlorine` ($< 0.5\text{ ppm}$) và loại bỏ `Hydrogen Sulfide`.
    - Các dòng thông số thiết kế và rửa lọc: `Bed depth` ($30\text{--}36\text{ in.}$), `Service flowrate` ($3.5\text{--}5\text{ gpm/sq. ft.}$), `Backwash rate` ($8\text{--}12\text{ gpm/sq. ft.}$) và `Backwash Bed Expansion` ($20\text{--}40\%$).

#### 4.3.9 Vật liệu lọc xúc tác pyrolusite LayneOx™

##### 4.3.9.1 Thành phần khoáng chất và Quy cách hạt LayneOx™
- Bản chất khoáng vật pyrolusite tự nhiên:
  - LayneOx™ là quặng pyrolusite khai thác tự nhiên với hàm lượng mangan dioxide cực cao: $70\%$ đến $80\%$ khối lượng ($\text{wt}\% \text{ MnO}_2$).
  - Toàn bộ hạt là khoáng chất đồng nhất, không bị hiện tượng mòn bong tróc lớp phủ oxit như cát tráng mangan hay glauconite.
  - Hệ số đồng nhất hạt (Uniformity Coefficient): $U_c < 1.65$.
- Hai quy cách kích thước hạt thương mại:
  - Cỡ sàng $8 \times 20\text{ mesh}$: Kích thước hiệu dụng (`Effective size`) từ $1.0\text{ mm}$ đến $1.3\text{ mm}$.
  - Cỡ sàng $20 \times 40\text{ mesh}$: Kích thước hiệu dụng từ $0.3\text{ mm}$ đến $0.5\text{ mm}$.
  - **Hình 25.** Thông số kỹ thuật và kích cỡ hạt vật liệu LayneOx™
    - <img src="ch04_iron_manganese_removal/assets/fig_25_p18.png" alt="Hình 25" />
  - **Hình này chứng minh điều gì**
    - Hạt vật liệu có hàm lượng $\text{MnO}_2$ cao ($70 - 80\ \% \text{ weight}$) và độ đồng nhất tốt ($< 1.65$).
  - **Từ đâu mà thấy được**
    - Hai khung ảnh trên minh họa dạng hạt ở 2 cỡ sàng $8 \times 20\text{ mesh}$ và $20 \times 40\text{ mesh}$.
    - Các dòng thông số: "Effective size" ($1.0 - 1.3\text{ mm}$, $0.3 - 0.5\text{ mm}$), "Manganese dioxide content" ($70 - 80\ \%$).

##### 4.3.9.2 Định mức công nghệ và Hiệu suất xử lý của LayneOx™
- Tải trọng lọc cao và thời gian tiếp xúc ngắn:
  - Tải trọng lọc bề mặt (Surface loading rate): Đạt từ $8$ đến $15\text{ gpm/sq. ft.}$ ($\approx 19.5 - 36.6\text{ m/h}$), cao hơn gấp $2 - 3$ lần cát lọc truyền thống.
  - Thời gian tiếp xúc qua lớp vật liệu (Media contact time): Tối thiểu $2\text{ phút}$.
  - Hiệu suất xử lý khử sắt và mangan (Removal efficiency): Vượt trên $99\%$ ($99\%^+$).
- Chế độ thủy lực rửa ngược theo cỡ hạt:
  - Tổn thất áp lực qua lớp lọc (Pressure drop): Phụ thuộc vào cỡ sàng hạt và vận tốc lọc bề mặt.
  - Cỡ hạt $8 \times 20\text{ mesh}$: Tốc độ rửa ngược yêu cầu $20$ đến $25\text{ gpm/sq. ft.}$ ($\approx 48.9 - 61.1\text{ m/h}$).
  - Cỡ hạt $20 \times 40\text{ mesh}$: Tốc độ rửa ngược yêu cầu $12$ đến $15\text{ gpm/sq. ft.}$ ($\approx 29.3 - 36.6\text{ m/h}$).
  - **Hình 26.** Điều kiện vận hành tiêu chuẩn của vật liệu lọc LayneOx™
    - <img src="ch04_iron_manganese_removal/assets/fig_26_p18.png" alt="Hình 26" />
  - **Hình này chứng minh điều gì**
    - Cung cấp định mức vận hành chi tiết với tải trọng lọc, chất oxy hóa và hiệu suất khử $\text{Fe/Mn}$ đạt tới $99\ \%^+$.
  - **Từ đâu mà thấy được**
    - Các dòng thông số: "Surface loading rate" ($8 - 15\text{ gpm/sq ft}$), "Media contact time" (tối thiểu $2\text{ phút}$) và "Removal efficiency" ($99\ \%^+$).
    - Các dòng "Pressure drop" và "Backwash rate" phân định mức theo 2 cỡ hạt $8 \times 20\text{ mesh}$ và $20 \times 40\text{ mesh}$.

### 4.4 Tính toán thiết kế và Bài tập ứng dụng

- Các bài toán tính toán kỹ thuật trong công nghệ khử sắt và mangan bằng kali pemanganat ($\text{KMnO}_4$) bao gồm hai nhóm bài toán cốt lõi:
  - Tính toán nồng độ và định lượng khối lượng hóa chất pha chế theo phần trăm khối lượng (% by weight).
  - Tính toán liều lượng chất oxy hóa lý thuyết và vận hành để xử lý sắt ($\text{Fe}^{2+}$) và mangan ($\text{Mn}^{2+}$) trong nước thô.
- Pha chế dung dịch hóa chất thuốc tím $\text{KMnO}_4$:
  - Nhà sản xuất khuyến nghị nồng độ dung dịch thuốc tím làm việc thông dụng là $3\%$ (theo tài liệu WTOM, tr. 31).
  - Nồng độ phần trăm theo khối lượng ($P_{\text{wt}}$ hoặc $C\%$) xác định bằng tỷ lệ giữa khối lượng chất tan $\text{KMnO}_4$ và tổng khối lượng dung dịch (khối lượng chất tan cộng khối lượng nước).
  - Khối lượng hóa chất $\text{KMnO}_4$ cần hòa tan vào bể chứa hình trụ tròn căn cứ vào kích thước hình học bể (đường kính $D$ và chiều sâu mức nước $H$) và nồng độ yêu cầu.
- Xác định liều lượng hóa chất $\text{KMnO}_4$ oxy hóa kim loại trong nước thô:
  - Nhu cầu $\text{KMnO}_4$ định mức để oxy hóa sắt ($\text{Fe}^{2+}$): $0.94\text{ mg KMnO}_4/\text{mg Fe}$ (theo phương trình phản ứng tức thời trong dải $\text{pH}$ từ $5.0$ đến $9.0$).
  - Nhu cầu $\text{KMnO}_4$ định mức để oxy hóa mangan ($\text{Mn}^{2+}$): $1.92\text{ mg KMnO}_4/\text{mg Mn}$ (theo phản ứng oxy hóa nhanh ở $\text{pH} \ge 7.2$).
  - Tổng nhu cầu thuốc tím khi nước thô chứa đồng thời cả hai kim loại tuân theo nguyên lý cộng tuyến tính tải lượng oxy hóa:
    $$\text{KMnO}_{4,\text{demand}}\text{ (mg/L)} = 0.94[\text{Fe}^{2+}] + 1.92[\text{Mn}^{2+}]$$

#### 4.4.1 Tính toán nồng độ và khối lượng pha chế dung dịch thuốc tím KMnO4

- Cơ sở lý thuyết pha chế dung dịch:
  - Dung dịch thuốc tím có giới hạn độ tan phụ thuộc nhiệt độ (khoảng $64\text{ g/L}$ ở $20^\circ\text{C}$). Nồng độ khuyến nghị $3\%$ (tương đương $\approx 30.9\text{ g/L}$) bảo đảm hóa chất tan hoàn toàn, không tạo cặn lắng nghẹt bơm định lượng.
  - Công thức xác định nồng độ phần trăm khối lượng:
    $$P_{\text{wt}} = \frac{m_{\text{solute}}}{m_{\text{total}}} \times 100\% = \frac{m_{\text{KMnO}_4}}{m_{\text{KMnO}_4} + \rho_{\text{water}} \cdot V_{\text{water}}} \times 100\%$$
  - Công thức tính thể tích và khối lượng hóa chất cần hòa tan vào bể hình trụ:
    $$V_{\text{tank}} = \frac{\pi D^2}{4} \cdot H; \quad m_{\text{chem}} = \left[\frac{P_{\text{wt}}}{100\% - P_{\text{wt}}}\right] \cdot (\rho_{\text{water}} \cdot V_{\text{tank}})$$

##### Ví dụ 4-1 (ex4_1): Tính phần trăm nồng độ khối lượng dung dịch thuốc tím KMnO4 (Example 4-1)

- **Đề bài**:
  (WTOM, 31) Một nhà cung cấp hóa chất khuyến nghị dung dịch thuốc tím nồng độ $3\%$. Nếu hòa tan $1\text{ kg KMnO}_4$ vào $50\text{ lít}$ nước, nồng độ phần trăm theo khối lượng của dung dịch thu được là bao nhiêu?
  *(Nguyên văn tiếng Anh: Example 4-1: (WTOM, 31) A chemical supplier recommends a 3% permanganate solution. If 1 kg KMnO4 are dissolved in 50 liters of water, what is the percent by weight?)*
- **Dữ kiện**:
  - Khối lượng chất tan kali pemanganat: $m_{\text{solute}} = 1.0\text{ kg KMnO}_4$.
  - Thể tích nước dung môi: $V_{\text{water}} = 50.0\text{ L}$ ($50\text{ liters}$).
  - Khối lượng riêng của nước ở điều kiện tiêu chuẩn: $\rho_{\text{water}} = 1.0\text{ kg/L}$ ($1000\text{ kg/m}^3$).
  - Nồng độ khuyến nghị của nhà cung cấp: $P_{\text{rec}} = 3.0\%$ (thông số đối chiếu công nghệ).
  - Minh chứng đề bài trên slide bài giảng:
    - **Ảnh EX4_1.1.** Đề bài Ví dụ 4-1 trên slide 19 (trang 132 bài giảng).
      - <img src="ch04_iron_manganese_removal/assets/ex4_1_1.png" alt="Ảnh EX4_1.1" />
      - Nhìn vào: Dòng chữ đỏ "Example 4-1: (WTOM, 31)" và nội dung văn bản "A chemical supplier recommends a 3% permanganate solution. If 1 kg KMnO4 are dissolved in 50 liters of water, what is the percent by weight?".
- **Quy tắc áp dụng**:
  - Quy tắc R08 (`R08_SOLUTION_PERCENT_WEIGHT`): Nồng độ phần trăm theo khối lượng của dung dịch hóa chất:
    $$P_{\text{wt}} = \left[\frac{m_{\text{solute}}}{m_{\text{solute}} + \rho_{\text{water}} \cdot V_{\text{water}}}\right] \times 100\% = \frac{m_{\text{KMnO}_4}}{m_{\text{dung dịch}}} \times 100\%$$
  - Quy tắc chuyển đổi thể tích nước sang khối lượng nước:
    $$m_{\text{water}} = V_{\text{water}} \cdot \rho_{\text{water}}$$
  - Nguồn trích dẫn: Slide bài giảng trang 19 (mục 4.4 Calculation) và tài liệu *Water Treatment Plant Operation* (WTOM, tr. 31).
- **Lời giải**:
  - **Bước 1**: Xác định khối lượng của $50\text{ lít}$ nước làm dung môi hòa tan.
    - Căn cứ: Thể tích nước $V_{\text{water}} = 50.0\text{ L}$ và khối lượng riêng $\rho_{\text{water}} = 1.0\text{ kg/L}$.
    - Nhìn vào: Dòng thứ 2 của đề bài trên Ảnh EX4_1.1 ("...in 50 liters of water...").
    - Thực hiện:
      $$m_{\text{water}} = 50.0\text{ L} \times 1.0\text{ kg/L} = 50.0\text{ kg}$$
  - **Bước 2**: Xác định tổng khối lượng của dung dịch sau khi hòa tan hoàn toàn $1.0\text{ kg KMnO}_4$.
    - Căn cứ: Định luật bảo toàn khối lượng, tổng khối lượng dung dịch bằng khối lượng chất tan cộng khối lượng dung môi: $m_{\text{total}} = m_{\text{solute}} + m_{\text{water}}$.
    - Nhìn vào: Dòng thứ 2 của đề bài trên Ảnh EX4_1.1 ("If 1 kg KMnO4 are dissolved in 50 liters of water...").
    - Thực hiện:
      $$m_{\text{total}} = 1.0\text{ kg} + 50.0\text{ kg} = 51.0\text{ kg}$$
  - **Bước 3**: Tính nồng độ phần trăm theo khối lượng của dung dịch $\text{KMnO}_4$.
    - Căn cứ: Công thức tính phần trăm nồng độ khối lượng $P_{\text{wt}} = \frac{m_{\text{solute}}}{m_{\text{total}}} \times 100\%$.
    - Nhìn vào: Dòng thứ 2–3 của đề bài trên Ảnh EX4_1.1 ("...what is the percent by weight?").
    - Thực hiện:
      $$P_{\text{wt}} = \frac{1.0\text{ kg}}{51.0\text{ kg}} \times 100\% = 1.96078\% \approx 1.96\%\text{ (theo khối lượng)}$$
      *(Ghi chú kỹ thuật: Trong thực hành tính nhanh tại trạm xử lý, nếu giả định khối lượng dung dịch xấp xỉ khối lượng nước $50.0\text{ kg}$, nồng độ định lượng kỹ thuật là $\frac{1.0\text{ kg}}{50.0\text{ kg}} \times 100\% = 2.0\%$; tuy nhiên giá trị chuẩn xác theo hóa lý là $1.96\%$).*
  - **Bước 4**: Đánh giá nồng độ pha chế so với khuyến nghị vận hành.
    - Căn cứ: Nồng độ khuyến nghị của nhà cung cấp $P_{\text{rec}} = 3.0\%$.
    - Nhìn vào: Dòng thứ nhất của đề bài trên Ảnh EX4_1.1 ("A chemical supplier recommends a 3% permanganate solution").
    - Thực hiện: Dung dịch pha được ($1.96\%$) loãng hơn mức khuyến nghị ($3.0\%$). Dung dịch hoàn toàn không có nguy cơ kết tinh đóng cặn, nhưng máy bơm định lượng cần tăng lưu lượng cấp để cung cấp đủ tải lượng hóa chất xử lý.
- **Kết quả**:
  - Nồng độ phần trăm theo khối lượng của dung dịch $\text{KMnO}_4$ thu được là $1.96\%\text{ wt}$ (tính chính xác theo tổng khối lượng dung dịch $51.0\text{ kg}$) hoặc $2.00\%\text{ wt}$ (theo quy ước tính nhanh xem khối lượng dung dịch bằng khối lượng nước).
- **Kiểm tra lại**:
  - Kiểm tra nghịch đảo: Với nồng độ $1.96078\%$ và khối lượng dung dịch $51.0\text{ kg}$, khối lượng chất tan thu được là:
    $$m_{\text{solute}} = 51.0\text{ kg} \times 0.0196078 = 1.000\text{ kg}$$
    Khớp chính xác với khối lượng $1.0\text{ kg KMnO}_4$ đề bài cho.
  - So sánh với nồng độ chuẩn $3.0\%$: Để đạt nồng độ $3.0\%$ với $50.0\text{ kg}$ nước, khối lượng $\text{KMnO}_4$ cần hòa tan là:
    $$m_{\text{chem, 3\%}} = \frac{0.03}{1 - 0.03} \times 50.0\text{ kg} = \frac{1.5}{0.97} \approx 1.546\text{ kg}$$
    Vì $1.0\text{ kg} < 1.546\text{ kg}$, nồng độ $1.96\%$ là hoàn toàn hợp lý.

##### Ví dụ 4-2 (ex4_2): Tính khối lượng hóa chất KMnO4 cần hòa tan vào bể trụ tròn (Example 4-2)

- **Đề bài**:
  (WTOM, 31) Để điều chế dung dịch thuốc tím nồng độ $3\%$, cần hòa tan bao nhiêu kg $\text{KMnO}_4$ vào một bể chứa hình trụ tròn có đường kính $1.2\text{ m}$ và được nạp nước đến chiều sâu $1.5\text{ m}$?
  *(Nguyên văn tiếng Anh: Example 4-2: (WTOM, 31) To produce a 3% solution, how many kgs KMnO4 should be dissolved in a tank 1.2 meter in diameter and flled to a depth of 1.5 meters?)*
- **Dữ kiện**:
  - Nồng độ phần trăm khối lượng mục tiêu: $P_{\text{wt}} = 3.0\%$.
  - Đường kính trong của bể trụ tròn: $D = 1.2\text{ m}$.
  - Chiều sâu mức nước chứa trong bể: $H = 1.5\text{ m}$.
  - Khối lượng riêng của nước: $\rho_{\text{water}} = 1000\text{ kg/m}^3$ ($1.0\text{ kg/L}$).
  - Minh chứng đề bài trên slide bài giảng:
    - **Ảnh EX4_2.1.** Đề bài Ví dụ 4-2 trên slide 19 (trang 132 bài giảng).
      - <img src="ch04_iron_manganese_removal/assets/ex4_2_1.png" alt="Ảnh EX4_2.1" />
      - Nhìn vào: Dòng chữ đỏ "Example 4-2: (WTOM, 31)" và nội dung văn bản "To produce a 3% solution, how many kgs KMnO4 should be dissolved in a tank 1.2 meter in diameter and flled to a depth of 1.5 meters?".
- **Quy tắc áp dụng**:
  - Quy tắc R09 (`R09_CYLINDRICAL_TANK_CHEMICAL_MASS`):
    - Diện tích mặt cắt ngang hình tròn của bể:
      $$A = \frac{\pi D^2}{4} \approx 0.785398 \cdot D^2$$
    - Thể tích nước chứa trong bể hình trụ tròn:
      $$V_{\text{water}} = A \cdot H = \frac{\pi D^2}{4} \cdot H$$
    - Khối lượng nước chứa trong bể:
      $$m_{\text{water}} = V_{\text{water}} \cdot \rho_{\text{water}}$$
    - Khối lượng hóa chất $\text{KMnO}_4$ cần hòa tan vào nước để đạt nồng độ phần trăm $P_{\text{wt}}$:
      $$P_{\text{wt}} = \frac{m_{\text{chem}}}{m_{\text{chem}} + m_{\text{water}}} \times 100\% \implies m_{\text{chem}} = \left[\frac{P_{\text{wt}}}{100\% - P_{\text{wt}}}\right] \cdot m_{\text{water}}$$
  - Nguồn trích dẫn: Slide bài giảng trang 19, quy tắc R09 trong `skeleton.json` và tài liệu WTOM, tr. 31.
- **Lời giải**:
  - **Bước 1**: Tính diện tích đáy và thể tích nước chứa trong bể hình trụ.
    - Căn cứ: Đường kính $D = 1.2\text{ m}$, chiều sâu $H = 1.5\text{ m}$, công thức thể tích hình trụ $V = \frac{\pi D^2}{4} H$.
    - Nhìn vào: Dòng thứ 2 của khối Example 4-2 trên Ảnh EX4_2.1 ("...in a tank 1.2 meter in diameter and flled to a depth of 1.5 meters?").
    - Thực hiện:
      $$A = \frac{\pi \times (1.2\text{ m})^2}{4} = \frac{\pi \times 1.44}{4} = 0.36\pi \approx 1.130973\text{ m}^2$$
      $$V_{\text{water}} = A \times H = 1.130973\text{ m}^2 \times 1.5\text{ m} = 0.54\pi \approx 1.696460\text{ m}^3$$
      *(Nếu dùng hệ số xấp xỉ kỹ thuật $0.785$: $A = 0.785 \times 1.2^2 = 1.1304\text{ m}^2$; $V = 1.1304 \times 1.5 = 1.6956\text{ m}^3$).*
  - **Bước 2**: Xác định khối lượng của lượng nước dung môi chứa trong bể.
    - Căn cứ: Khối lượng riêng của nước $\rho_{\text{water}} = 1000\text{ kg/m}^3$ và thể tích $V_{\text{water}} = 1.696460\text{ m}^3$.
    - Nhìn vào: Giá trị thể tích $V_{\text{water}}$ tính được từ Bước 1.
    - Thực hiện:
      $$m_{\text{water}} = 1.696460\text{ m}^3 \times 1000\text{ kg/m}^3 = 1696.46\text{ kg}\text{ (tương đương } 1696.46\text{ lít)}$$
      *(Nếu theo thể tích làm tròn kỹ thuật $1.6956\text{ m}^3$, khối lượng nước là $1695.6\text{ kg}$).*
  - **Bước 3**: Tính khối lượng hóa chất $\text{KMnO}_4$ cần hòa tan để đạt dung dịch nồng độ $3.0\%$.
    - Căn cứ: Công thức tính khối lượng chất tan theo nồng độ phần trăm khối lượng:
      $$m_{\text{chem}} = \frac{P_{\text{wt}}}{100\% - P_{\text{wt}}} \times m_{\text{water}}$$
    - Nhìn vào: Dòng thứ 1 của khối Example 4-2 trên Ảnh EX4_2.1 ("To produce a 3% solution, how many kgs KMnO4 should...").
    - Thực hiện:
      $$m_{\text{chem}} = \frac{3\%}{100\% - 3\%} \times 1696.46\text{ kg} = \frac{0.03}{0.97} \times 1696.46\text{ kg} = 52.4678\text{ kg} \approx 52.47\text{ kg}$$
      *(Ghi chú thực hành công trường: Nếu tính gần đúng theo nồng độ khối lượng trên thể tích nước $m_{\text{chem}} \approx 0.03 \times 1696.46\text{ kg}$, kết quả thu được là $50.89\text{ kg}$. Giá trị $52.47\text{ kg}$ là kết quả chính xác theo chuẩn hóa lý).*
- **Kết quả**:
  - Cần hòa tan $52.47\text{ kg KMnO}_4$ (giá trị chính xác theo khối lượng, làm tròn kỹ thuật $52.5\text{ kg}$) hoặc $50.89\text{ kg KMnO}_4$ (theo quy ước gần đúng nồng độ theo thể tích nước).
- **Kiểm tra lại**:
  - Kiểm tra nồng độ phần trăm của dung dịch thu được:
    $$m_{\text{total}} = m_{\text{chem}} + m_{\text{water}} = 52.47\text{ kg} + 1696.46\text{ kg} = 1748.93\text{ kg}$$
    $$P_{\text{wt}} = \frac{52.47\text{ kg}}{1748.93\text{ kg}} \times 100\% = 3.0001\% \approx 3.00\%$$
    Khớp chính xác với nồng độ $3\%$ đề bài yêu cầu.
  - Kiểm tra độ tan: Nồng độ dung dịch tương ứng khoảng $\frac{52.47\text{ kg}}{1.6965\text{ m}^3} \approx 30.93\text{ g/L}$, thấp hơn nhiều so với độ tan bão hòa của $\text{KMnO}_4$ trong nước ở $20^\circ\text{C}$ ($\approx 64\text{ g/L}$), bảo đảm hóa chất tan hoàn toàn.

---

#### 4.4.2 Tính toán liều lượng chất oxy hóa khử Sắt và Mangan trong nước thô

- Cơ chế và định mức oxy hóa bằng kali pemanganat ($\text{KMnO}_4$):
  - Phản ứng diễn ra nhanh chóng, thích hợp cho các trạm xử lý không có đủ thời gian lưu tiếp xúc làm thoáng hoặc nguồn nước có $\text{pH}$ thấp không thể oxy hóa mangan bằng không khí.
  - Bảng tổng hợp định mức tiêu hao chất oxy hóa theo bài giảng Slide 6:
    - Đối với Sắt ($\text{Fe}^{2+}$): Oxy hòa tan cần $0.14\text{ mg O}_2/\text{mg Fe}$; Clo cần $0.64\text{ mg Cl}_2/\text{mg Fe}$; Thuốc tím cần $0.94\text{ mg KMnO}_4/\text{mg Fe}$.
    - Đối với Mangan ($\text{Mn}^{2+}$): Oxy hòa tan cần $0.29\text{ mg O}_2/\text{mg Mn}$; Clo cần $1.29\text{ mg Cl}_2/\text{mg Mn}$; Thuốc tím cần $1.92\text{ mg KMnO}_4/\text{mg Mn}$.

##### Ví dụ 4-3 (ex4_3): Tính liều lượng KMnO4 cần thiết để oxy hóa Sắt trong nước thô (Example 4-3)

- **Đề bài**:
  (WTOM, 32) Nguồn nước thô của một nhà máy xử lý nước cấp có hàm lượng sắt là $1.6\text{ mg/L}$. Cần sử dụng liều lượng $\text{KMnO}_4$ là bao nhiêu để oxy hóa hết lượng sắt này?
  *(Nguyên văn tiếng Anh: Example 4-3: (WTOM, 32) A plant’s raw water has 1.6 mg/L of iron. How much KMnO4 should be used to treat the iron?)*
- **Dữ kiện**:
  - Hàm lượng ion sắt hòa tan trong nước thô: $[\text{Fe}^{2+}] = 1.6\text{ mg/L}$.
  - Định mức nhu cầu $\text{KMnO}_4$ vận hành thực tế: $0.94\text{ mg KMnO}_4/\text{mg Fe}$ (theo bài giảng Slide 6, bảng *Oxidant Requirements for Iron and Manganese*).
  - Tỷ lệ đương lượng phản ứng lý thuyết: $0.9433\text{ mg KMnO}_4/\text{mg Fe}$ (dựa trên khối lượng mol $M_{\text{KMnO}_4} = 158.034\text{ g/mol}$ và $M_{\text{Fe}} = 55.845\text{ g/mol}$).
  - Minh chứng đề bài trên slide bài giảng:
    - **Ảnh EX4_3.1.** Đề bài Ví dụ 4-3 trên slide 19 (trang 132 bài giảng).
      - <img src="ch04_iron_manganese_removal/assets/ex4_3_1.png" alt="Ảnh EX4_3.1" />
      - Nhìn vào: Dòng chữ đỏ "Example 4-3: (WTOM, 32)" và nội dung câu hỏi "A plant’s raw water has 1.6 mg/L of iron. How much KMnO4 should be used to treat the iron?".
- **Quy tắc áp dụng**:
  - Quy tắc R05 (`R05_FE_KMNO4_OXIDATION`): Phản ứng oxy hóa ion sắt $\text{Fe(II)}$ bằng kali pemanganat:
    $$3\text{Fe}^{2+} + \text{KMnO}_4 + 7\text{H}_2\text{O} \rightarrow 3\text{Fe(OH)}_3\downarrow + \text{MnO}_2\downarrow + \text{K}^+ + 5\text{H}^+$$
    - Theo phương trình hóa học, $3\text{ mol Fe}^{2+}$ ($3 \times 55.845 = 167.535\text{ g}$) phản ứng với $1\text{ mol KMnO}_4$ ($158.034\text{ g}$).
    - Tỷ lệ nhu cầu hóa chất lý thuyết:
      $$\text{Ratio}_{\text{KMnO}_4/\text{Fe, lý thuyết}} = \frac{158.034}{167.535} = 0.9433\text{ mg KMnO}_4/\text{mg Fe}$$
  - Công thức tính liều lượng châm hóa chất:
    $$\text{Dose}_{\text{KMnO}_4}\text{ (mg/L)} = [\text{Fe}^{2+}]\text{ (mg/L)} \times \text{Ratio}_{\text{KMnO}_4/\text{Fe}}$$
  - Nguồn trích dẫn: Slide 6 (bảng định mức chất oxy hóa), Slide 19 (mục 4.4 Calculation) và tài liệu WTOM, tr. 32.
- **Lời giải**:
  - **Bước 1**: Xác định định mức nhu cầu $\text{KMnO}_4$ trên mỗi đơn vị nồng độ sắt.
    - Căn cứ: Bảng nhu cầu chất oxy hóa (Mục 4.2 Theory, Slide 6) quy định nhu cầu thuốc tím là $0.94\text{ mg KMnO}_4$ cho mỗi $1.0\text{ mg Fe}$.
    - Nhìn vào: Bảng so sánh chất oxy hóa trên Slide 6 (cột "per mg/L of Fe", hàng "Potassium permanganate: 0.94").
    - Thực hiện: Thiết lập tỷ lệ định lượng $\text{Ratio} = 0.94\text{ mg KMnO}_4/\text{mg Fe}$.
  - **Bước 2**: Tính liều lượng $\text{KMnO}_4$ cần châm để xử lý hoàn toàn lượng sắt trong nước thô.
    - Căn cứ: Hàm lượng sắt nước thô $[\text{Fe}^{2+}] = 1.6\text{ mg/L}$ và công thức định mức $\text{Dose} = [\text{Fe}^{2+}] \times \text{Ratio}$.
    - Nhìn vào: Dòng thứ 1 của khối Example 4-3 trên Ảnh EX4_3.1 ("A plant’s raw water has 1.6 mg/L of iron").
    - Thực hiện:
      - Tính theo định mức vận hành thực tế ($0.94\text{ mg/mg}$):
        $$\text{Dose}_{\text{KMnO}_4} = 1.6\text{ mg/L} \times 0.94\text{ mg KMnO}_4/\text{mg Fe} = 1.504\text{ mg/L} \approx 1.50\text{ mg/L}$$
      - Tính theo tỷ lệ phản ứng lý thuyết chính xác ($0.9433\text{ mg/mg}$):
        $$\text{Dose}_{\text{KMnO}_4,\text{exact}} = 1.6\text{ mg/L} \times 0.9433\text{ mg KMnO}_4/\text{mg Fe} = 1.5093\text{ mg/L} \approx 1.51\text{ mg/L}$$
- **Kết quả**:
  - Liều lượng $\text{KMnO}_4$ cần dùng là $1.504\text{ mg/L}$ (theo định mức thiết kế $0.94$: $1.50\text{ mg/L}$; theo tỷ lệ lý thuyết: $1.51\text{ mg/L}$).
- **Kiểm tra lại**:
  - Kiểm tra tính toán khử ngược: Lượng sắt oxy hóa được từ $1.504\text{ mg/L KMnO}_4$:
    $$[\text{Fe}^{2+}] = \frac{1.504\text{ mg/L}}{0.94\text{ mg/mg}} = 1.60\text{ mg/L}$$
    Khớp chính xác với hàm lượng sắt trong nước thô đề bài cho.
  - Đánh giá công nghệ: Phản ứng diễn ra gần như tức thời trong dải $\text{pH } 5.0 - 9.0$. Kết tủa mangan dioxide ($\text{MnO}_2$) sinh ra đóng vai trò chất trợ keo tụ và nhân xúc tác hấp phụ thêm ion kim loại trước khi vào bể lắng/lọc.

##### Ví dụ 4-4 (ex4_4): Tính liều lượng KMnO4 cần thiết để oxy hóa Mangan trong nước thô (Example 4-4)

- **Đề bài**:
  (WTOM, 32) Nguồn nước thô của một nhà máy xử lý nước cấp có chứa $6.8\text{ mg/L}$ mangan. Cần sử dụng liều lượng $\text{KMnO}_4$ là bao nhiêu để oxy hóa hết lượng mangan này?
  *(Nguyên văn tiếng Anh: Example 4-4: (WTOM, 32) A plant’s raw water has 6.8 mg/L of manganese. How much KMnO4 should be used to treat the manganese?)*
- **Dữ kiện**:
  - Hàm lượng ion mangan hòa tan trong nước thô: $[\text{Mn}^{2+}] = 6.8\text{ mg/L}$.
  - Định mức nhu cầu $\text{KMnO}_4$ vận hành thực tế: $1.92\text{ mg KMnO}_4/\text{mg Mn}$ (theo bài giảng Slide 6, bảng *Oxidant Requirements for Iron and Manganese*).
  - Tỷ lệ đương lượng phản ứng lý thuyết: $1.9177\text{ mg KMnO}_4/\text{mg Mn}$ (dựa trên khối lượng mol $M_{\text{KMnO}_4} = 158.034\text{ g/mol}$ và $M_{\text{Mn}} = 54.938\text{ g/mol}$).
  - Minh chứng đề bài trên slide bài giảng:
    - **Ảnh EX4_4.1.** Đề bài Ví dụ 4-4 trên slide 19 (trang 132 bài giảng).
      - <img src="ch04_iron_manganese_removal/assets/ex4_4_1.png" alt="Ảnh EX4_4.1" />
      - Nhìn vào: Dòng chữ đỏ "Example 4-4: (WTOM, 32)" và nội dung câu hỏi "A plant’s raw water has 6.8 mg/L of manganese. How much KMnO4 should be used to treat the manganese?".
- **Quy tắc áp dụng**:
  - Quy tắc R06 (`R06_MN_KMNO4_OXIDATION`): Phản ứng oxy hóa ion mangan $\text{Mn(II)}$ bằng kali pemanganat:
    $$3\text{Mn}^{2+} + 2\text{KMnO}_4 + 2\text{H}_2\text{O} \rightarrow 5\text{MnO}_2\downarrow + 2\text{K}^+ + 4\text{H}^+$$
    - Theo phương trình hóa học, $3\text{ mol Mn}^{2+}$ ($3 \times 54.938 = 164.814\text{ g}$) phản ứng với $2\text{ mol KMnO}_4$ ($2 \times 158.034 = 316.068\text{ g}$).
    - Tỷ lệ nhu cầu hóa chất lý thuyết:
      $$\text{Ratio}_{\text{KMnO}_4/\text{Mn, lý thuyết}} = \frac{316.068}{164.814} = 1.9177\text{ mg KMnO}_4/\text{mg Mn}$$
  - Công thức tính liều lượng châm hóa chất:
    $$\text{Dose}_{\text{KMnO}_4}\text{ (mg/L)} = [\text{Mn}^{2+}]\text{ (mg/L)} \times \text{Ratio}_{\text{KMnO}_4/\text{Mn}}$$
  - Nguồn trích dẫn: Slide 6 (bảng định mức chất oxy hóa), Slide 19 (mục 4.4 Calculation) và tài liệu WTOM, tr. 32.
- **Lời giải**:
  - **Bước 1**: Xác định định mức nhu cầu $\text{KMnO}_4$ trên mỗi đơn vị nồng độ mangan.
    - Căn cứ: Bảng nhu cầu chất oxy hóa (Mục 4.2 Theory, Slide 6) quy định nhu cầu thuốc tím là $1.92\text{ mg KMnO}_4$ cho mỗi $1.0\text{ mg Mn}$.
    - Nhìn vào: Bảng so sánh chất oxy hóa trên Slide 6 (cột "per mg/L of Mn", hàng "Potassium permanganate: 1.92").
    - Thực hiện: Thiết lập tỷ lệ định lượng $\text{Ratio} = 1.92\text{ mg KMnO}_4/\text{mg Mn}$.
  - **Bước 2**: Tính liều lượng $\text{KMnO}_4$ cần châm để oxy hóa toàn bộ mangan trong nước thô.
    - Căn cứ: Hàm lượng mangan nước thô $[\text{Mn}^{2+}] = 6.8\text{ mg/L}$ và công thức định mức $\text{Dose} = [\text{Mn}^{2+}] \times \text{Ratio}$.
    - Nhìn vào: Dòng thứ 1 của khối Example 4-4 trên Ảnh EX4_4.1 ("A plant’s raw water has 6.8 mg/L of manganese").
    - Thực hiện:
      - Tính theo định mức vận hành thực tế ($1.92\text{ mg/mg}$):
        $$\text{Dose}_{\text{KMnO}_4} = 6.8\text{ mg/L} \times 1.92\text{ mg KMnO}_4/\text{mg Mn} = 13.056\text{ mg/L} \approx 13.06\text{ mg/L}$$
      - Tính theo tỷ lệ phản ứng lý thuyết chính xác ($1.9177\text{ mg/mg}$):
        $$\text{Dose}_{\text{KMnO}_4,\text{exact}} = 6.8\text{ mg/L} \times 1.9177\text{ mg KMnO}_4/\text{mg Mn} = 13.0404\text{ mg/L} \approx 13.04\text{ mg/L}$$
- **Kết quả**:
  - Liều lượng $\text{KMnO}_4$ cần dùng là $13.056\text{ mg/L}$ (theo định mức thiết kế $1.92$: $13.06\text{ mg/L}$ hoặc làm tròn kỹ thuật $13.1\text{ mg/L}$; theo tỷ lệ lý thuyết: $13.04\text{ mg/L}$).
- **Kiểm tra lại**:
  - Kiểm tra tính toán khử ngược: Lượng mangan oxy hóa được từ $13.056\text{ mg/L KMnO}_4$:
    $$[\text{Mn}^{2+}] = \frac{13.056\text{ mg/L}}{1.92\text{ mg/mg}} = 6.80\text{ mg/L}$$
    Khớp chính xác với hàm lượng mangan trong nước thô đề bài cho.
  - Kiểm soát vận hành và giám sát chất lượng nước: Oxy hóa mangan bằng thuốc tím đòi hỏi kiểm soát liều lượng nghiêm ngặt trước bể lọc xúc tác cát mangan (Greensand). Nếu châm thiếu liều lượng, mangan hòa tan còn dư sẽ đi vào mạng lưới phân phối gây nước đen và cặn bám; nếu châm dư thừa thuốc tím, nước sau xử lý sẽ có màu hồng tím đặc trưng của ion pemanganat ($\text{MnO}_4^-$) chưa phản ứng.

## Chương 5: Quá trình Lắng (Sedimentation)


### 5.1 Overview

* Mục tiêu của các quá trình tiền xử lý trước lắng:
  * Quá trình coagulation (keo tụ) và flocculation (tạo bông) chuyển đổi colloids (hạt keo) thành suspended particles (hạt lơ lửng).
  * Quá trình oxidation-reduction (oxy hóa - khử) loại bỏ iron/manganese (sắt/mangan) bằng cách tạo thành insoluble precipitate (kết tủa không tan).
  * Quá trình lime-soda softening (làm mềm bằng vôi - soda) loại bỏ hardness (độ cứng) bằng cách tạo thành insoluble precipitate.
* Cơ chế và định nghĩa của quá trình sedimentation (lắng trọng lực):
  * Suspended particles và insoluble precipitate lắng tách khỏi nước nhờ gravitational forces (lực trọng trường) khi kích thước hạt đủ lớn. Quá trình này được gọi là sedimentation.
  * Giới hạn kích thước hạt loại bỏ: Tùy thuộc vào density (khối lượng riêng), các hạt lơ lửng và kết tủa không tan có kích thước lớn hơn $1\ \mu\text{m}$ có thể được loại bỏ bằng sedimentation.
* Biện pháp vận hành và công trình lắng:
  * Nước chứa hạt lơ lửng và kết tủa được đưa vào một quiescent basin (bể tĩnh) lớn trong khoảng thời gian lưu thích hợp để hạt lắng xuống đáy.
  * Công trình lắng còn được gọi là clarifier (bể làm trong) hoặc settling tank (bể lắng).
* Sơ đồ dòng chảy và thu gom bùn trong công trình lắng:
  * Dòng nước vào: Nước từ flocculation basin (bể tạo bông) đi vào công trình lắng.
  * Dòng nước ra: Nước sau lắng được dẫn sang filtration tank (bể lọc).
  * Thu gom bùn: Bùn lắng được gom vào hopper (phễu thu bùn).
  * Xử lý bùn: Bùn từ hopper được dẫn đến công đoạn solid treatment (xử lý bùn cặn / chất rắn).

### 5.2 Theory

#### 5.2.1 Phân loại Cơ chế Lắng Cặn trong Kỹ thuật Xử lý Nước (Classification of Particle Settling Regimes)

##### 5.2.1.1 Thông số Điều khiển và Tiêu chí Phân loại (Controlling Parameters & Classification Criteria)
- **Vận tốc lắng ($v_s$) là thông số điều khiển cốt lõi (controlling parameter)**:
  - Vận tốc lắng của hạt cặn cần loại bỏ ($v_s$) quyết định toàn bộ kích thước hình học và diện tích mặt bằng của bể lắng lý tưởng.
  - Hiệu quả thu giữ hạt cặn yêu cầu vận tốc lắng của hạt phải lớn hơn hoặc bằng tải trọng bề mặt của bể ($v_o$):
    $$v_s \ge v_o = \frac{Q}{A_s}$$
    - $v_s$: Vận tốc lắng trọng lực của hạt cặn ($\text{m/s}$ hoặc $\text{m/h}$).
    - $v_o$: Vận tốc tràn bề mặt hay tải trọng thủy lực bề mặt ($\text{m}^3/(\text{m}^2\cdot\text{h})$ hoặc $\text{m/h}$).
    - $Q$: Lưu lượng nước qua bể lắng ($\text{m}^3/\text{h}$ hoặc $\text{m}^3/\text{d}$).
    - $A_s$: Diện tích bề mặt lắng hữu dụng ($\text{m}^2$).
- **Hai tiêu chí phân loại trạng thái lắng**:
  - Nồng độ hạt chất rắn (particle concentration): Xác định cự ly không gian giữa các hạt lân cận và tần suất tương tác thủy động lực học.
  - Hình thái học và tính chất bề mặt của hạt (particle morphology): Xác định khả năng dính kết (flocculation), hình dạng hạt, độ cầu, và tính biến dạng khi lắng.
- **Bốn phân nhóm quy ước chuẩn hóa (four standardized categories)**:
  - Nhóm 1: Lắng hạt rời rạc (Discrete particle settling - Type I).
  - Nhóm 2: Lắng tạo bông (Flocculant settling - Type II).
  - Nhóm 3: Lắng cản trở hay lắng vùng (Hindered settling / Zone settling - Type III).
  - Nhóm 4: Lắng nén (Compression settling - Type IV).

##### 5.2.1.2 Bản chất Vật lý và Động học của Bốn Loại Lắng (Physical & Kinetic Characteristics: Type I to Type IV)
- **Ma trận đối chiếu bốn cơ chế lắng trọng lực**:

| Cơ Chế Lắng | Tên Quy Ước | Đặc Điểm Nồng Độ & Hình Thái Hạt | Động Học Vận Tốc Lắng ($v_s$) | Ứng Dụng Kỹ Thuật Điển Hình |
|---|---|---|---|---|
| **Type I** | Lắng hạt rời rạc (*Discrete settling*) | Nồng độ loãng; hạt không tương tác; không kết tụ tạo bông; hình dạng và kích thước cố định. | $v_s = \text{const}$ (hạt đạt vận tốc lắng không đổi rất nhanh theo cân bằng lực Newton/Stokes). | Bể lắng cát (*grit chamber*), bể sơ lắng hạt thô, lắng cát rửa lọc nhanh. |
| **Type II** | Lắng tạo bông (*Flocculant settling*) | Nồng độ thấp đến trung bình; các hạt có khả năng liên kết dính bám khi va chạm. | $v_s$ tăng dần theo chiều sâu và thời gian do hạt kết tụ tăng dần đường kính ($v_s = f(z, t)$). | Bể lắng sau keo tụ phèn nhôm, phèn sắt; kết tủa oxy hóa $Fe/Mn$; kết tủa làm mềm vôi. |
| **Type III** | Lắng cản trở (*Hindered / Zone settling*) | Nồng độ cao; tương tác lực cản thủy động giữa các hạt lân cận chi phối; tạo lớp đệm hạt (*sludge blanket*). | Toàn bộ khối hạt lắng đồng loạt với một vận tốc chung; xuất hiện mặt phân cách lỏng - rắn rõ rệt. | Bể lắng tiếp xúc cặn (*solids-contact clarifier*), bể lắng bùn hoạt tính, tầng màng cặn lơ lửng. |
| **Type IV** | Lắng nén (*Compression settling*) | Nồng độ rất cao; các hạt tiếp xúc cơ học trực tiếp tạo thành cấu trúc khung xốp chịu lực. | $v_s$ rất nhỏ; quá trình nén ép diễn ra do trọng lượng các lớp cặn bên trên đẩy nước lỗ rỗng lên trên. | Tầng đáy hố thu bùn của bể lắng (*sludge hopper*), bể nén bùn trọng lực (*sludge thickener*). |

- **Đặc tính cơ chế Type I (Lắng hạt rời rạc)**:
  - Các hạt lắng độc lập, không cản trở và không tương tác với các hạt xung quanh.
  - Nồng độ hạt trong huyền phù ở mức thấp.
  - Hạt không thay đổi kích thước, hình dạng hoặc khối lượng trong toàn bộ hành trình lắng.
  - Vận tốc lắng $v_s$ là hằng số cố định khi hạt đạt trạng thái cân bằng giữa trọng lực ($F_G$), lực nổi Archimedes ($F_B$) và lực cản chất lưu ($F_D$).
- **Đặc tính cơ chế Type II (Lắng tạo bông)**:
  - Các hạt có khả năng kết dính khi tiếp xúc và va chạm cơ học.
  - Quá trình keo tụ và kết cụm diễn ra liên tục trong suốt hành trình rơi.
  - Kích thước hạt hiệu dụng tăng dần làm tăng lực trọng trường hiệu dụng, dẫn đến vận tốc lắng tăng liên tục theo độ sâu bể.
  - Quỹ đạo lắng của hạt là một đường cong cong dốc dần thay vì một đường thẳng.
- **Đặc tính cơ chế Type III (Lắng cản trở / Lắng vùng)**:
  - Nồng độ hạt cao hơn rõ rệt so với Type I và Type II.
  - Cự ly giữa các hạt rất hẹp khiến trường dòng chảy chất lưu quanh từng hạt tương tác mạnh mẽ.
  - Dòng nước đẩy ngược qua các khe rỗng giữa các hạt tạo lực cản thủy động học đáng kể lên các hạt xung quanh.
  - Các hạt liên kết thành một khối màng đệm cặn (*sludge blanket*) và lắng đồng tốc.
  - Quá trình lắng tạo ra một bề mặt phân pha rõ ràng giữa lớp nước trong phía trên và lớp màng bùn đặc phía dưới.
- **Đặc tính cơ chế Type IV (Lắng nén)**:
  - Nồng độ chất rắn lơ lửng ở mức rất cao, hiệu quả hơn so với Type III.
  - Các hạt tiếp xúc vật lý trực tiếp với nhau, hình thành cấu trúc khung giàn rắn xốp.
  - Quá trình nén ép diễn ra khi các lớp hạt mới lắng đè tải trọng tĩnh lên lớp hạt bên dưới.
  - Nước trong các vi lỗ rỗng bị nén ép cơ học và thoát ngược lên trên, làm giảm độ ẩm và tăng mật độ nén của lớp bùn đáy.

##### 5.2.1.3 Sự Đồng tồn tại và Ý nghĩa Kỹ thuật trong Vận hành Bể Lắng (Coexistence & Operational Significance in Clarifiers)
- **Sự đồng tồn tại của bốn cơ chế lắng trong một công trình thực tế**:
  - Bể lắng xử lý nước thực tế thường xuất hiện đồng thời cả bốn cơ chế lắng dọc theo tiết diện sâu của bể.
  - Phân tầng động học theo phương thẳng đứng từ mặt nước xuống đáy bể:
    - Vùng nước trong phía trên (Clarified zone): Lắng Type I của các hạt cặn khoáng hoặc hạt cát sót lại.
    - Vùng lắng làm trong ở giữa (Clarification zone): Lắng Type II của các bông cặn keo tụ đang tiếp tục va chạm dính kết.
    - Vùng màng bùn lơ lửng (Sludge blanket zone): Lắng Type III với ranh giới phân tách pha lỏng - rắn ổn định.
    - Vùng hố thu cặn ở đáy bể (Sludge hopper zone): Lắng Type IV thực hiện nén ép cô đặc bùn.
- **Ý nghĩa kỹ thuật trong thiết kế bể lắng**:
  - Xác định diện tích mặt bằng bể lắng ($A_s$): Tính toán dựa trên vận tốc lắng giới hạn của cơ chế Type I hoặc Type II để đảm bảo cặn không bị cuốn trôi qua máng tràn.
  - Xác định chiều sâu và dung tích vùng chứa bùn ($V_{\text{sludge}}$): Tính toán dựa trên động học nén của cơ chế Type III và Type IV nhằm dự trữ đủ thể tích tích lũy cặn giữa hai chu kỳ xả.
- **Ý nghĩa kỹ thuật trong vận hành và kiểm soát sự cố**:
  - Duy trì độ ổn định của lớp màng bùn (Type III): Tránh hiện tượng xáo trộn thủy lực hoặc quá tải thủy lực làm phá vỡ ranh giới màng cặn, gây trào bùn ra máng thu nước sạch.
  - Tối ưu hóa chu kỳ xả bùn đáy (Type IV): Xả bùn đúng chu kỳ giúp bùn đạt độ nén tối ưu (giảm độ ẩm), đồng thời ngăn ngừa hiện tượng phân hủy yếm khí sinh bọt khí làm nổi mảng bùn lên mặt nước.

#### Type I Sedimentation

- Đặc điểm của quá trình lắng Type I (Type I sedimentation / discrete particle settling):
  - Lắng Type I đặc trưng bởi các hạt lắng rời rạc với vận tốc lắng không đổi ($v_s = \text{const}$).
  - Các hạt lắng riêng lẻ và không keo tụ tạo bông (do not flocculate) trong suốt quá trình lắng.
  - Ví dụ điển hình cho hạt lắng Type I là cát (sand) và sạn (grit).
- Ứng dụng thực tế của quá trình lắng Type I:
  - Lắng sơ bộ (presedimentation) để tách cát trước công đoạn keo tụ trong nhà máy xử lý nước cấp uống (potable water plant).
  - Lắng các hạt cát trong giai đoạn rửa bể lọc cát nhanh (rapid sand filters).
  - Tách cặn và hạt vô cơ trong bể lắng cát (grit chambers).
- Cơ chế cân bằng lực động học của Newton (Newton's force balance):
  - Khi hạt lắng rời rạc, vận tốc lắng có thể tính toán được để thiết kế bể loại bỏ kích thước hạt chỉ định.
  - Sir Isaac Newton (1687) chứng minh hạt rơi trong chất lưu tĩnh gia tốc đến khi lực cản ma sát cân bằng với trọng lực.
  - Ba lực tác dụng lên hạt rơi tự do gồm trọng lực ($F_G$), lực đẩy nổi ($F_B$) và lực cản ($F_D$):
    - Trọng lực (gravitational force): $F_G = (\phi_s) g \forall_p$.
    - Lực đẩy nổi (buoyancy force): $F_B = (\phi) g \forall_p$.
    - Lực cản (drag force): $F_D = C_D A_p (\phi) \frac{v^2}{2}$.
    - **Hình 1.** Ba lực tác dụng lên hạt rơi trong chất lưu
      - <img src="ch05_sedimentation/assets/fig_01_p7.jpeg" alt="Hình 1" />
      - **Hình này chứng minh điều gì**
        - Trọng lực ($F_G$) kéo hạt xuống đối kháng lực nổi ($F_B$) và lực cản ($F_D$).
      - **Từ đâu mà thấy được**
        - Mũi tên $F_G$ hướng xuống; mũi tên $F_B$ và hai mũi tên $F_D$ hướng lên.
- Các thông số trong phương trình cân bằng lực:
  - $\phi_s$: Khối lượng riêng của hạt (density of particle), $\text{kg/m}^3$.
  - $\phi$: Khối lượng riêng của chất lưu (density of fluid), $\text{kg/m}^3$.
  - $g$: Gia tốc trọng trường (acceleration due to gravity), $\text{m/s}^2$.
  - $\forall_p$: Thể tích của hạt (volume of particle), $\text{m}^3$.
  - $C_D$: Hệ số cản (drag coefficient), không thứ nguyên.
  - $A_p$: Diện tích mặt cắt ngang của hạt (cross-sectional area of particle), $\text{m}^2$.
  - $v$: Vận tốc của hạt (velocity of particle), $\text{m/s}$.
  - **Hình 2.** Sơ đồ cân bằng lực tác dụng lên hạt lắng tự do
    - <img src="ch05_sedimentation/assets/fig_02_p8.jpeg" alt="Hình 2" />
    - **Hình này chứng minh điều gì**
      - Hạt chuyển động chịu trọng lực $F_G$ kéo xuống cùng lực $F_B$, $F_D$ đẩy lên.
    - **Từ đâu mà thấy được**
      - Nhãn $F_G$ tại tâm hướng xuống; nhãn $F_B$ ở đáy và $F_D$ ở sườn hướng lên.
- Chế độ dòng chảy và chuẩn số Reynolds ($R$):
  - Osborne Reynolds (1883) đề xuất tỷ số không thứ nguyên $R$ để xác định các chế độ dòng chảy.
  - Định nghĩa chuẩn số Reynolds cho hạt cầu chuyển động trong chất lỏng: $R = \frac{d \cdot v_s}{\nu} = \frac{\phi \cdot d \cdot v_s}{\mu}$.
    - $d$: Đường kính hạt cầu (diameter of sphere), $\text{m}$.
    - $v_s$: Vận tốc của hạt cầu (velocity of sphere), $\text{m/s}$.
    - $\nu$: Độ nhớt động học (kinematic viscosity), $\nu = \frac{\mu}{\phi}$, $\text{m}^2/\text{s}$.
    - $\phi$: Khối lượng riêng của chất lưu (density of fluid), $\text{kg/m}^3$.
    - $\mu$: Độ nhớt động lực học (dynamic viscosity hay absolute viscosity), $\text{Pa}\cdot\text{s}$.
- Hệ số cản Newton ($C_D$) theo chuẩn số Reynolds ($R$):
  - Hệ số cản $C_D$ phụ thuộc vào chế độ dòng chảy theo ba khoảng số Reynolds:
    - Chảy tầng ($R < 0.5$): $C_D = \frac{24}{R}$.
    - Vùng chuyển tiếp ($0.5 < R < 10^4$): $C_D = \frac{24}{R} + \frac{3}{R^{1/2}} + 0.34$.
    - Chảy rối ($R > 10^4$): $C_D = 0.4$.
    - **Hình 3.** Quan hệ giữa hệ số cản Newton và số Reynolds
      - <img src="ch05_sedimentation/assets/fig_03_p11.png" alt="Hình 3" />
      - **Hình này chứng minh điều gì**
        - Thực nghiệm hạt cầu khớp đường lý thuyết $C_D$; Stokes' law chỉ đúng khi $R \le 1$.
      - **Từ đâu mà thấy được**
        - Trục hoành $R$ ($10^{-3}$–$10^6$), trục tung $C_D$ ($10^{-1}$–$10^4$); Stokes phân kỳ khi $R > 1$.
- Vận tốc lắng cuối và Định luật Stokes:
  - Vận tốc lắng cuối ($v_s$) đạt được khi trọng lực triệt tiêu lực đẩy nổi và lực cản ($F_G = F_B + F_D$).
  - Định luật Stokes áp dụng cho hạt cầu lắng trong điều kiện chảy tầng tĩnh với $R \le 1$.
  - Mối quan hệ hệ số cản $C_D$ theo số Reynolds cho các hình dạng hạt khác nhau:
    - **Hình 4.** Hệ số cản Newton theo số Reynolds cho các dạng hạt
      - <img src="ch05_sedimentation/assets/fig_04_p12.png" alt="Hình 4" />
      - **Hình này chứng minh điều gì**
        - Khi $R > 1$, $C_D$ tách khỏi Stokes; ở $R \ge 10^3$, $C_D$ phụ thuộc hình dạng hạt.
      - **Từ đâu mà thấy được**
        - Đường Spheres bám đường tính $C_D$; đường Disks và Cylinders nằm ngang ở $R \ge 10^3$.

#### Ideal Sedimentation Basin

- Lý thuyết bể lắng lý tưởng của Thomas R. Camp (1936) cho quá trình tách hạt lắng rời rạc:
  - Thomas R. Camp (1936) đề xuất lý thuyết duy lý (rational theory) để loại bỏ các hạt lắng rời rạc (discretely settling particles) trong bể lắng lý tưởng (ideal settling basin).
  - Mô hình bể lắng lý tưởng của Camp dựa trên 7 giả thiết cơ bản (fundamental assumptions):
    - Giả thiết 1: Quá trình lắng thuộc loại Type I (Type I settling / discrete settling), các hạt lắng riêng rẽ và không kết bông.
    - Giả thiết 2: Thể tích bể lắng được phân chia thành bốn vùng chức năng riêng biệt (four zones in the basin): vùng nước vào (inlet zone), vùng nước ra (outlet zone), vùng chứa bùn cặn (sludge zone), và vùng lắng (settling zone).
    - Giả thiết 3: Phân phối dòng chảy đồng đều với vận tốc nằm ngang đồng nhất (even distribution of flow / uniform horizontal velocity) khi đi vào vùng lắng.
    - Giả thiết 4: Phân phối dòng chảy đồng đều (even distribution of flow) khi rời khỏi vùng lắng sang vùng nước ra.
    - Giả thiết 5: Hạt cặn phân bố đồng đều trên toàn bộ chiều sâu (uniform distribution of particles through the depth) tại mặt cắt đầu vào của vùng lắng.
    - Giả thiết 6: Các hạt cặn đi vào vùng bùn đều bị bắt giữ hoàn toàn và lưu trữ cố định trong vùng bùn (particles that enter the sludge zone are captured and remain in the sludge zone).
    - Giả thiết 7: Các hạt cặn đi vào vùng nước ra sẽ không được loại bỏ khỏi dòng nước (particles that enter the outlet zone are not removed from the water).
  - Phân vùng cấu tạo và không gian chức năng trong bể lắng lý tưởng:
    - **Hình 5.** Sơ đồ bốn vùng chức năng trong bể lắng lý tưởng
      - <img src="ch05_sedimentation/assets/fig_05_p13.png" alt="Hình 5" />
      - **Hình này chứng minh điều gì**
        - Vị trí không gian tương đối giữa bốn vùng chức năng: vùng lắng ở trung tâm, vùng vào ở bên trái, vùng thu nước ở bên phải và vùng bùn ở đáy.
      - **Từ đâu mà thấy được**
        - Nhìn theo chiều dòng chảy từ trái sang phải: dòng $Q$ qua Inlet zone vào Settling zone rồi đến Outlet zone (Effluent weir); Sludge zone nằm dọc đáy bể.
    - **Hình 6.** Sơ đồ bốn vùng chức năng trong bể lắng đứng
      - <img src="ch05_sedimentation/assets/fig_06_p13.png" alt="Hình 6" />
      - **Hình này chứng minh điều gì**
        - Phân định không gian và ranh giới giữa bốn vùng chức năng theo phương thẳng đứng trong bể lắng dòng chảy hướng lên.
      - **Từ đâu mà thấy được**
        - Hướng dòng chảy từ trên xuống theo $Q$: vào ống nạp xuống Inlet zone, dâng qua Settling zone lên máng tràn Outlet zone; Sludge zone ở đáy phễu.
- Hai cấu hình hình học cơ bản của bể làm trong lý tưởng (ideal clarifier configurations):
  - Bể lắng dòng chảy ngang (Horizontal flow clarifier): dòng nước mang hạt cặn di chuyển theo phương nằm ngang qua vùng lắng.
  - Bể lắng dòng chảy hướng lên (Upflow clarifier): dòng nước di chuyển theo phương thẳng đứng từ dưới lên qua vùng lắng.
  - Sơ đồ cấu tạo và hướng chuyển động dòng chảy trong hai dạng bể lắng:
    - **Hình 7.** Sơ đồ các vùng chức năng trong bể lắng ngang
      - <img src="ch05_sedimentation/assets/fig_07_p14.png" alt="Hình 7" />
      - **Hình này chứng minh điều gì**
        - Cấu tạo bốn vùng chức năng cho phép lưu lượng $Q$ chảy ngang qua vùng lắng để cặn tách khỏi dòng nước trước máng thu.
      - **Từ đâu mà thấy được**
        - Đọc từ trái sang phải: dòng vào $Q$ qua Target baffle và Perforated baffle vào Settling zone và thoát qua Effluent weir; Sludge zone nằm ở đáy bể.
    - **Hình 8.** Sơ đồ phân vùng chức năng bể lắng dòng chảy hướng lên
      - <img src="ch05_sedimentation/assets/fig_08_p14.png" alt="Hình 8" />
      - **Hình này chứng minh điều gì**
        - Cấu trúc bốn vùng chức năng: dòng vào $Q$ qua ống trung tâm xuống đáy, dâng ngược qua Settling zone (diện tích $A_s$) để tách cặn, bùn lắng vào Sludge zone và nước trong vào Outlet zone.
      - **Từ đâu mà thấy được**
        - Hướng dòng chảy từ trên xuống: mũi tên $Q$ qua ống trung tâm, rẽ cong tại Inlet zone rồi dâng ngược lên qua Settling zone đến Outlet zone; Sludge zone ở đáy phễu.
- Cơ chế tách cặn và tốc độ tràn trong bể lắng dòng chảy hướng lên (Upflow clarifier):
  - Động học tách hạt trong bể lắng đứng:
    - Nước dâng thẳng đứng với vector vận tốc dâng ($v_o$).
    - Hạt cặn chìm xuống với vector vận tốc lắng trọng lực ($v_s$).
    - Khi diện tích mặt cắt ướt ngang ($A_s$) đủ lớn, vector vận tốc nước dâng ($v_o$) sẽ nhỏ hơn vector vận tốc lắng của hạt ($v_s$):
      $$v_o \le v_s \iff v_s \ge v_o$$
    - Hệ quả phân tách: hạt cặn thắng được lực kéo dâng của dòng nước và lưu lại trong bể (rơi xuống vùng bùn), trong khi nước trong (clear water) dâng lên và thoát ra ngoài máng thu.
  - Định nghĩa tốc độ tràn (overflow rate) và tải trọng bề mặt thủy lực (hydraulic surface loading):
    - Vận tốc dâng của dòng nước ($v_o$) cho phép phân tách nước khỏi hạt cặn được gọi là tốc độ tràn (overflow rate), vì đây là tốc độ mà nước dâng tràn qua đỉnh bể vào các máng thu nước (rate at which water overflows the top of the tank into the weirs).
    - Tốc độ tràn còn được gọi là tải trọng bề mặt thủy lực (hydraulic surface loading) hoặc tải trọng bề mặt (surface loading).
    - Phương trình xác định tốc độ tràn và vận tốc lắng tới hạn:
      $$v_s = \frac{Q}{A_s}$$
    - Đơn vị đo của tốc độ tràn / tải trọng bề mặt: $\text{m}^3/(\text{m}^2\cdot\text{d})$, $\text{m}^3/(\text{m}^2\cdot\text{h})$, hoặc $\text{m/s}$.
  - Các thông số trong phương trình bể lắng đứng:
    - $v_s$: Vận tốc lắng của hạt cặn (settling velocity), đơn vị $\text{m/s}$.
    - $v_o$: Vận tốc dâng của nước / tốc độ tràn (upward water velocity / overflow rate), đơn vị $\text{m/s}$.
    - $Q$: Lưu lượng dòng chảy qua bể (flow rate), đơn vị $\text{m}^3/\text{s}$.
    - $A_s$: Diện tích bề mặt lắng (surface area), đơn vị $\text{m}^2$.
- Cơ chế tách cặn và thời gian lưu nước trong bể lắng dòng chảy ngang (Horizontal flow clarifier):
  - Động học tách hạt trong bể lắng ngang:
    - Để được loại bỏ hoàn toàn khỏi dòng nước, hạt cặn xuất phát từ mặt nước ở cửa vào phải có vận tốc lắng ($v_s$) đủ lớn để rơi chạm đáy bể trong khoảng thời gian ($t_o$) mà nước lưu chuyển trong bể (thời gian lưu nước / detention time).
    - Điều kiện tách cặn yêu cầu vận tốc lắng của hạt phải bằng chiều sâu bể chia cho thời gian lưu nước $t_o$:
      $$v_s = \frac{h}{t_o}$$
  - Công thức xác định thời gian lưu thủy lực lý thuyết ($t_o$):
    $$t_o = \frac{\forall}{Q}$$
    - $t_o$: Thời gian lưu nước trong bể (detention time), đơn vị $\text{s}$.
    - $\forall$: Thể tích hữu ích của bể lắng (tank volume), đơn vị $\text{m}^3$.
    - $Q$: Lưu lượng dòng chảy qua bể (flow rate), đơn vị $\text{m}^3/\text{s}$.
  - Thiết lập mối quan hệ giữa vận tốc lắng, lưu lượng và diện tích bề mặt bể lắng ngang:
    - Thể tích của bể lắng liên hệ với diện tích bề mặt ($A_s$) và chiều sâu bể ($h$) theo phương trình $\forall = A_s \cdot h$.
    - Thay biểu thức thời gian lưu nước $t_o = \frac{\forall}{Q} = \frac{A_s \cdot h}{Q}$ vào phương trình vận tốc lắng:
      $$v_s = \frac{h}{t_o} = \frac{h}{\frac{A_s \cdot h}{Q}} = \frac{Q}{A_s}$$
    - Nguyên lý diện tích bề mặt Hazen: Vận tốc lắng tới hạn ($v_s$) của hạt cần loại bỏ trong bể lắng ngang bằng đúng tỷ số giữa lưu lượng $Q$ và diện tích bề mặt $A_s$ ($v_s = \frac{Q}{A_s}$), hoàn toàn đồng nhất với tốc độ tràn trong bể lắng đứng và độc lập với chiều sâu bể lắng ($h$).
  - Các thông số trong phương trình bể lắng ngang:
    - $v_s$: Vận tốc lắng của hạt cặn (settling velocity), đơn vị $\text{m/s}$.
    - $Q$: Lưu lượng dòng chảy (flow rate), đơn vị $\text{m}^3/\text{s}$.
    - $A_s$: Diện tích bề mặt vùng lắng (surface area), đơn vị $\text{m}^2$.
    - $h$: Chiều sâu làm việc của bể lắng (depth of tank), đơn vị $\text{m}$.
    - $t_o$: Thời gian lưu nước trong bể (detention time), đơn vị $\text{s}$.
    - $\forall$: Thể tích hữu ích của bể lắng (tank volume), đơn vị $\text{m}^3$.

#### Type II Sedimentation

- Quá trình lắng loại II (Type II sedimentation) được đặc trưng bởi các hạt kết bông (flocculate) trong quá trình lắng:
  - Các loại hạt này xuất hiện trong quá trình keo tụ bằng phèn nhôm hoặc phèn sắt (alum or iron coagulation).
  - Xuất hiện trong quá trình lắng sơ cấp nước thải (wastewater primary sedimentation).
  - Xuất hiện trong các bể lắng của quá trình lọc nhỏ giọt (settling tanks in trickling filtration).
- Không có mối quan hệ toán học thỏa đáng nào có thể được sử dụng để mô tả quá trình lắng loại II (Type II settling):
  - Phương trình Stokes (Stokes equation) không thể sử dụng được vì các hạt kết bông liên tục thay đổi về kích thước và hình dạng (size and shape).
  - Ngoài ra, khi nước bị cuốn giữ bên trong bông cặn (water is entrapped in the floc), tỷ trọng / khối lượng riêng tương đối (specific gravity) của hạt cũng thay đổi.
- Thí nghiệm trong phòng thí nghiệm với cột lắng (settling columns) đóng vai trò là mô hình mô phỏng hành vi của lắng kết bông (flocculant settling):
  - Các thí nghiệm này có giá trị trong việc đánh giá các bể lắng hiện hữu (evaluating of existing settling tanks).
  - Có giá trị trong việc phát triển dữ liệu phục vụ mở rộng trạm (plant expansion) hoặc cải tạo các công trình hiện hữu (modification of existing plants).
  - Không thực tế cho việc thiết kế các bể lắng mới (design of new settling tanks) do khó tái lập các tính chất và nồng độ của các hạt sinh ra từ quá trình keo tụ/tạo bông (coagulation/flocculation process).
- Phương pháp phân tích dữ liệu cột lắng và hành vi của huyền phù kết bông (flocculant suspension):
  - Một cột lắng được đổ đầy huyền phù cần phân tích.
  - Huyền phù được để cho lắng tĩnh.
  - Các mẫu nước được rút ra từ các cổng lấy mẫu (sample ports) ở các cao độ khác nhau tại các khoảng thời gian được chọn trước.
  - Nồng độ chất rắn lơ lửng (suspended solids) được xác định cho từng mẫu và phần trăm loại bỏ ($R\%$) được tính toán:
    - Công thức tính phần trăm loại bỏ: $R\% = \frac{C_0 - C_t}{C_0} \times 100\%$.
    - $R\%$: phần trăm loại bỏ tại một độ sâu và thời gian nhất định (percent removal at one depth and time), $\%$.
    - $C_t$: nồng độ tại thời gian và độ sâu đã cho (concentration at given time and depth), $\text{mg/L}$.
    - $C_0$: nồng độ ban đầu (initial concentration), $\text{mg/L}$.
- Các đường đẳng nồng độ (isoconcentration lines) cho thí nghiệm lắng loại II sử dụng cột lắng sâu $2\text{ m}$ (2 m-deep column):
  - **Hình 9.** Đường đẳng nồng độ trong thí nghiệm lắng loại II
    - <img src="ch05_sedimentation/assets/fig_09_p19.png" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Các đường đẳng mức loại bỏ ($30\text{ }\%$–$75\text{ }\%$) nội suy từ dữ liệu đo, xác định các phân đoạn độ sâu để tính hiệu suất loại bỏ tổng cộng tại thời gian lấy mẫu $t_a$.
    - **Từ đâu mà thấy được**
      - Ox: thời gian lấy mẫu $t$ ($\text{min}$), dải $0\text{--}120\text{ min}$. Oy: độ sâu cột lắng $h$ ($\text{m}$), dải $0.0\text{--}2.0\text{ m}$.
      - Các số khoanh tròn biểu diễn hiệu suất đo ($15\text{ }\%$–$76\text{ }\%$); đường dóng tại $t_a = 15\text{ min}$ cắt các đường đẳng mức tại các độ sâu $H_1, H_2, H_3$.
- Phương pháp phân tích dữ liệu cột lắng sử dụng các đường đẳng nồng độ để xác định các phân đoạn độ sâu $H_1, H_2, H_3$ tương ứng với thời gian lắng $t_a$ và các đường đẳng hiệu suất $R_a, R_b$:
  - **Hình 10.** Đường đẳng nồng độ từ thí nghiệm cột lắng sâu $2\text{ m}$
    - <img src="ch05_sedimentation/assets/fig_10_p20.png" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Các đường đẳng mức loại bỏ ($30\text{ }\%$–$75\text{ }\%$) nội suy từ dữ liệu đo, làm cơ sở xác định các phân đoạn độ sâu để tính hiệu suất lắng tổng cộng tại thời gian $t_a$.
    - **Từ đâu mà thấy được**
      - Ox: thời gian lấy mẫu $t$ ($\text{min}$), dải $0\text{--}120\text{ min}$. Oy: độ sâu $h$ ($\text{m}$), dải $0.0\text{--}2.0\text{ m}$.
      - Các số khoanh tròn biểu diễn hiệu suất đo ($15\text{ }\%$–$76\text{ }\%$); đường dóng tại $t_a = 15\text{ min}$ cắt các đường đẳng mức $R_a, R_b$ tại các độ sâu $H_1, H_2, H_3$.

#### Type III and Type IV Sedimentation

- Điều kiện hình thành và sự xuất hiện đồng thời của các dạng lắng ở nồng độ hạt cao:
  - Khi nước chứa hàm lượng hạt cặn ở nồng độ cao (high concentration of particles), ví dụ lớn hơn $1,000\text{ mg/L}$, cả quá trình lắng Type III (lắng cản trở hoặc lắng vùng / hindered settling or zone settling) và lắng Type IV (lắng nén / compression settling) đều diễn ra đồng thời cùng với lắng hạt rời rạc (discrete settling) và lắng tạo bông (flocculant settling).
  - Quá trình lắng vùng (zone settling) xuất hiện phổ biến trong các quy trình xử lý nước và nước thải thực tế gồm:
    - Quá trình lắng trong làm mềm nước bằng vôi (lime-softening sedimentation).
    - Quá trình lắng bùn hoạt tính (activated sludge sedimentation).
    - Các bể nén bùn / cô đặc bùn (sludge thickeners).
- Diễn biến động học của huyền phù đặc trong cột lắng hoặc ống đong chia độ:
  - Khi một huyền phù đậm đặc có nồng độ đồng nhất (concentrated suspension of uniform concentration) được đưa vào cột lắng (column) hoặc ống đong chia độ (graduated cylinder), cả ba cơ chế lắng Type II, Type III và Type IV đều lần lượt diễn ra theo thời gian.
  - Các hạt cặn tiếp xúc với nhau có xu hướng lắng đồng thời theo một vùng hoặc một lớp màng bùn / đệm cặn (zone or “blanket”).
  - Trong quá trình cùng chuyển động lắng xuống, các hạt tiếp xúc với nhau có xu hướng duy trì nguyên vẹn cùng một vị trí tương đối (maintain the same relative position).
  - Sự lắng đồng loạt theo màng cặn tạo ra một lớp nước tương đối trong (relatively clear layer) ở phía trên khối cặn đang lắng.
- Bản chất vật lý và các yếu tố ảnh hưởng đến quá trình lắng cản trở (hindered settling):
  - Hiện tượng các hạt lắng tập hợp theo vùng và giữ nguyên vị trí tương đối được định danh là lắng cản trở (hindered settling).
  - Tốc độ lắng cản trở (rate of hindered settling) là một hàm phụ thuộc vào nồng độ của các hạt cặn (concentration of the particles) và các đặc tính của hạt (particle characteristics).
  - Khi quá trình lắng tiếp diễn liên tục theo thời gian, một lớp hạt bị nén (compressed layer of particles) bắt đầu hình thành và tích tụ ở phía đáy.
- Bản chất cơ chế chuyển pha và định nghĩa của quá trình lắng nén (compression settling):
  - Tại lớp nén ở đáy, các hạt cặn tiếp xúc trực tiếp cơ học với nhau và không thực sự lắng xuống (do not really settle) theo nghĩa chuyển động rơi tự do.
  - Cơ chế trực quan chính xác hơn để mô tả hiện tượng này là dòng nước bị ép thoát ngược ra ngoài từ một tấm đệm hạt (mat of particles) đang chịu lực nén cơ học do trọng lượng của các lớp hạt bên trên.
  - Do bản chất động học giải phóng chất lỏng khỏi khối đệm cặn bị nén ép, quá trình này được gọi là lắng nén (compression settling).
- Yêu cầu thực nghiệm và phạm vi áp dụng trong thiết kế kỹ thuật:
  - Tương tự như phương pháp phân tích đối với quá trình lắng Type II, các phương pháp phân tích lắng cản trở đòi hỏi bắt buộc phải có dữ liệu thực nghiệm từ thí nghiệm lắng (settling test data).
  - Các phương pháp phân tích thực nghiệm này phù hợp và có giá trị áp dụng trong các dự án mở rộng hoặc cải tạo nâng cấp nhà máy xử lý hiện hữu (plant expansions or modifications).
  - Tuy nhiên, các phương pháp phân tích lắng cản trở chưa được áp dụng phổ biến trong công tác thiết kế các nhà máy xử lý quy mô nhỏ (small treatment plants).
- Sơ đồ lý tưởng hóa của quá trình lắng Type III và Type IV trong cột lắng (settling column):
  - Thí nghiệm cột mô tả trực quan sự tiến triển của các ranh giới phân vùng theo thời gian:
    - Thời điểm ban đầu $t = 0$: toàn bộ cột lắng có chiều cao ban đầu $H$ chứa đầy huyền phù vùng lắng cản trở ($\text{HS}$ - hindered settling) với nồng độ hạt phân bố đồng nhất.
    - Thời điểm $t = t_1$: cột lắng phân tách rõ rệt thành 4 phân vùng từ đỉnh xuống đáy gồm: mặt thoáng/lớp nước trong bên trên ($\text{WS}$ - water surface / clear water layer), vùng lắng cản trở ($\text{HS}$), vùng lắng chuyển tiếp ($\text{TS}$ - transition settling), và vùng lắng nén ($\text{CS}$ - compression settling) bắt đầu tích tụ ở đáy.
    - Thời điểm $t = t_2$: vùng lắng cản trở ($\text{HS}$) đã biến mất hoàn toàn, cột chỉ còn lại lớp nước trong ($\text{WS}$), vùng lắng chuyển tiếp ($\text{TS}$) và vùng lắng nén ($\text{CS}$) đang tiếp tục dâng cao.
    - Thời điểm $t = t_3$: vùng chuyển tiếp ($\text{TS}$) biến mất hoàn toàn, toàn bộ cặn đã tập trung vào vùng lắng nén ($\text{CS}$) bên dưới lớp nước trong ($\text{WS}$).
    - Thời điểm $t = t_4$: khối cặn trong vùng lắng nén ($\text{CS}$) tiếp tục bị nén ép chặt hơn theo thời gian, đẩy nước ra ngoài và làm giảm chiều cao bề mặt phân cách cặn (height of interface) xuống mức tối thiểu ổn định.
  - **Hình 11.** Sơ đồ lý tưởng hóa lắng Type III và IV trong cột
    - <img src="ch05_sedimentation/assets/fig_11_p21.png" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Mặt phân cách hạ thấp dần khi lớp nước trong mở rộng; các phân vùng HS rồi TS lần lượt biến mất, nhường chỗ cho lớp nén CS cô đặc ở đáy.
    - **Từ đâu mà thấy được**
      - Đọc từ trái sang phải qua các cột theo thời gian ($t = 0 \to t_4$): trục tung chỉ chiều cao mặt phân cách $H$, phía trên là mặt thoáng (WS).
      - Huyền phù ban đầu ($t = 0$) tách thành các phân tầng HS, TS (gạch chéo) và CS ($t_1$), sau đó HS biến mất ($t_2$), TS biến mất ($t_3$), và CS tiếp tục nén chặt ($t_4$).
  - **Hình 12.** Sơ đồ lắng Type III và IV trong cột lắng
    - <img src="ch05_sedimentation/assets/fig_12_p22.png" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Quá trình chuyển hóa và triệt tiêu tuần tự các vùng: $\text{HS}$ giảm dần, chuyển qua $\text{TS}$ và tích tụ thành lớp nén $\text{CS}$ ở đáy.
    - **Từ đâu mà thấy được**
      - Đọc từ trái sang phải qua 5 cột: ban đầu tại $t = 0$ chứa đầy $\text{HS}$ với chiều cao $H$.
      - Tại $t = t_1$ xuất hiện $\text{TS}$ (gạch chéo) và $\text{CS}$; $\text{HS}$ biến mất ở $t = t_2$, $\text{TS}$ biến mất ở $t = t_3$, và $\text{CS}$ tiếp tục nén đặc ở $t = t_4$.
- Đồ thị đường cong lắng tương ứng trong cột lắng (corresponding settling curve):
  - Đường cong thực nghiệm biểu diễn mối quan hệ động học giữa chiều cao bề mặt phân cách cặn và thời gian lắng:
    - Trục tung biểu diễn chiều cao bề mặt phân cách giữa lớp nước trong và khối cặn ($\text{Height of interface}$).
    - Trục hoành biểu diễn thời gian lắng ($\text{Time}$) tương ứng qua các thời điểm chuyển pha $t_1, t_2, t_3, t_4$.
  - Phân vùng động học trên đường cong lắng:
    - Vùng lắng cản trở / lắng vùng ($\text{HS}$ - hindered / zone settling): diễn ra từ $t = 0$ đến thời điểm $t_2$, đường biểu diễn có dạng một đường thẳng dốc tuyến tính; độ dốc của đoạn thẳng này biểu thị vận tốc lắng của màng cặn ($\text{Slope = settling velocity}$).
    - Vùng lắng chuyển tiếp ($\text{TS}$ - transition settling): diễn ra trong khoảng thời gian tiếp theo (từ $t_2$ đến $t_3$), đường biểu diễn uốn cong thoải dần khi vận tốc lắng suy giảm do nồng độ hạt tăng cao và các hạt cản trở lẫn nhau mạnh mẽ hơn.
    - Vùng lắng nén ($\text{CS}$ - compression settling): diễn ra từ thời điểm $t_3$ đến $t_4$, đường cong tiệm cận nằm ngang khi cấu trúc khung cặn đã hình thành và tốc độ thoát nước ra khỏi đệm hạt rất chậm.
  - **Hình 13.** Đồ thị đường cong lắng tương ứng
    - <img src="ch05_sedimentation/assets/fig_13_p23.png" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Chiều cao mặt phân cách hạ tuyến tính với vận tốc không đổi ($\text{Slope = settling velocity}$) trong vùng lắng cản trở ($\text{HS}$), rồi giảm tốc qua vùng chuyển tiếp ($\text{TS}$) và tiệm cận không đổi ở vùng lắng nén ($\text{CS}$).
    - **Từ đâu mà thấy được**
      - Ox: thời gian ($\text{Time}$) qua các mốc $t_1, t_2, t_3, t_4$. Oy: chiều cao mặt phân cách ($\text{Height of interface}$).
      - Đoạn dốc thẳng từ $0$ đến $t_2$ ghi $\text{Slope = settling velocity}$ ($\text{HS}$); đoạn uốn cong ở $t_2\text{--}t_3$ ($\text{TS}$); đoạn thoải ngang ở $t_3\text{--}t_4$ ($\text{CS}$).
  - **Hình 14.** Đồ thị đường cong lắng tương ứng
    - <img src="ch05_sedimentation/assets/fig_14_p24.png" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Mặt phân cách hạ tuyến tính theo vận tốc lắng không đổi ở HS ($0 \to t_2$), sau đó giảm tốc ở TS ($t_2 \to t_3$) và tiệm cận ổn định ở CS ($t_3 \to t_4$).
    - **Từ đâu mà thấy được**
      - Trục $Ox$: thời gian (Time, mốc $t_1 \to t_4$); Trục $Oy$: chiều cao mặt phân cách (Height of interface).
      - Độ dốc đường thẳng $0 \to t_2$ ghi chú "Slope = settling velocity" (HS), tiếp nối đoạn uốn TS và đoạn là ngang CS.

#### High-Rate Settling

- Nguyên lý gia tốc quá trình làm trong (Accelerate the clarification process):
  - Quá trình làm trong nước có thể được gia tốc bằng cách tăng tỷ trọng của hạt trong nước đầu vào (increasing the particle density of water input).
  - Quá trình làm trong nước cũng có thể được gia tốc bằng cách giảm khoảng cách rơi tự do của hạt cặn (reducing the distance the particle must fall).

##### a/ Increasing the particle density of water input

- Tỷ trọng tự nhiên của bông cặn (Specific gravity of flocs):
  - Bông cặn phèn nhôm (alum floc) có tỷ trọng xấp xỉ $1.001$.
  - Bông cặn vôi (lime floc) có tỷ trọng xấp xỉ $1.002$.
- Gia tăng vận tốc lắng bằng chất dằn (Ballasted floc settling velocity):
  - Một số quy trình công nghệ độc quyền bổ sung chất dằn (ballast) vào bông cặn để gia tăng vận tốc lắng ($v_s$) của hạt.
  - Chất dằn thường dùng là vi cát (microsized sand) có đường kính hạt từ $20\ \mu\text{m}$ đến $200\ \mu\text{m}$ ($20 - 200\ \mu\text{m}$).
  - Tỷ trọng của hạt vi cát nằm trong khoảng từ $2.50$ đến $2.65$ ($2.50 - 2.65$).
  - Hạt vi cát lắng xuống đáy được thu hồi (recovered) và tái sử dụng (reused) liên tục.

##### b/ Reducing the distance the particle must fall

- Bố trí mô-đun bản nghiêng hoặc ống nghiêng (Inclined plates / tubes):
  - Một dãy các tấm nghiêng (inclined plates) hoặc các ống nghiêng (tubes) được đặt vào trong bể lắng dòng chảy ngang hình chữ nhật (rectangular horizontal flow settling basin).
  - Các tấm hoặc ống được đặt nghiêng ở một góc thích hợp để các chất rắn thu gom được (collected solids) tự trượt xuống bề mặt dốc đi vào vùng chứa bùn (sludge zone).
- Đặc tính hình học và kích thước điển hình của ống lắng (Tube settler geometry):
  - Ống lắng điển hình có tiết diện hình vuông (square).
  - Kích thước tiết diện ống vào khoảng $5\ \text{cm}$ ở mỗi cạnh ($5\ \text{cm} \times 5\ \text{cm}$).
  - Góc nghiêng của ống lắng vào khoảng $60^\circ$ (trong tài liệu ghi nhận $600$, tức $60^\circ$).
- Ba cấu hình dòng chảy thủy lực điển hình (Three typical configurations):
  - Ba cấu hình dòng chảy cơ bản gồm chảy ngược chiều (countercurrent), chảy cùng chiều (cocurrent), và chảy ngang dòng (crosscurrent).
  - Các cấu hình được đặt tên theo hướng dòng chảy của nước so với hướng hạt cặn rời khỏi các tấm hoặc ống nghiêng.
- Cấu hình chảy ngược chiều (Countercurrent configuration):
  - Định nghĩa dòng chảy: Dòng chảy của nước chuyển động theo hướng ngược lại so với hướng chuyển động trượt của các hạt cặn.
  - **Hình 15.** Cấu hình lắng chảy ngược chiều qua các tấm nghiêng
    - <img src="ch05_sedimentation/assets/fig_15_p25.png" alt="Hình 15" />
    - **Hình này chứng minh điều gì**
      - Nước đi từ đáy lên đỉnh qua các tấm nghiêng, còn cặn trượt ngược xuống phễu đáy.
    - **Từ đâu mà thấy được**
      - Đường đi từ dưới lên: mũi tên Influent đưa nước dâng qua dãy tấm nghiêng đến Effluent.
      - Hướng đối nghịch: mũi tên Solids chỉ xuống đáy phễu, ngược chiều với dòng nước dâng.
- Cấu hình chảy cùng chiều (Cocurrent configuration):
  - Định nghĩa dòng chảy: Dòng chảy của nước chuyển động cùng hướng với hướng chuyển động trượt của các hạt cặn dọc theo vách nghiêng.
  - **Hình 16.** Cấu hình lắng chảy cùng chiều qua các tấm nghiêng
    - <img src="ch05_sedimentation/assets/fig_16_p25.png" alt="Hình 16" />
    - **Hình này chứng minh điều gì**
      - Nước vào (Influent) chảy dốc xuống cùng hướng di chuyển của cặn dọc theo vách nghiêng về đáy (Solids).
    - **Từ đâu mà thấy được**
      - Hướng dòng nước: mũi tên Influent từ đỉnh phải chảy dốc xuống khe nghiêng cùng hướng cặn trượt.
      - Tách dòng: cặn rơi xuống đáy theo mũi tên Solids; nước trong rẽ theo các mũi tên cong lên máng Effluent bên trái.
- Cấu hình chảy cắt ngang (Crosscurrent configuration):
  - Định nghĩa dòng chảy: Dòng chảy của nước chuyển động theo phương vuông góc hoặc cắt ngang qua hướng di chuyển và rơi xuống của các hạt cặn.
- Sơ đồ chi tiết dòng chảy ngược chiều (Countercurrent flow):
  - Nước vào từ đáy dâng qua các khe bản nghiêng lên máng thu nước trong phía trên, trong khi cặn trượt ngược chiều xuống phễu thu bùn đáy.
  - **Hình 17.** Sơ đồ dòng chảy ngược chiều qua mô-đun bản nghiêng
    - <img src="ch05_sedimentation/assets/fig_17_p26.png" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - Nước dâng từ đáy lên cửa Effluent, đối nghịch với hướng cặn trượt xuống đáy phễu Solids.
    - **Từ đâu mà thấy được**
      - Dòng nước cấp: mũi tên Influent vào đáy trái, chảy hướng lên qua các khe bản nghiêng ra Effluent trên cùng.
      - Dòng cặn lắng: cặn trượt xuống đáy phễu và thoát ra ngoài theo mũi tên Solids hướng xuống.
- Sơ đồ chi tiết dòng chảy cùng chiều (Cocurrent flow):
  - Nước vào từ đỉnh chảy xuôi xuống cùng hướng cặn trượt về đáy phễu Solids, sau đó nước trong tách ra và đảo chiều đi lên máng thu gom phía trên.
  - **Hình 18.** Sơ đồ dòng chảy cùng chiều qua mô-đun bản nghiêng
    - <img src="ch05_sedimentation/assets/fig_18_p26.png" alt="Hình 18" />
    - **Hình này chứng minh điều gì**
      - Nước vào từ đỉnh chảy xuôi xuống cùng hướng cặn trượt về đáy phễu Solids, tách biệt với máng thu Effluent.
    - **Từ đâu mà thấy được**
      - Hướng dòng nước: mũi tên Influent vào từ góc trên bên phải, chảy xuôi xuống theo khe bản nghiêng.
      - Phân tách pha rắn - lỏng: cặn rơi xuống đáy phễu Solids; nước trong đảo chiều qua máng Effluent bên trái.

### 5.3 Practice

#### Alternative Settling Tank Configurations

- Các tiêu chí thủy lực bổ sung trong phân loại và lựa chọn bể lắng công nghiệp:
  - Thời gian lưu nước thủy lực ($ hoặc $\text{HRT}$) đối với bể lắng ngang thông thường dao động từ {,}0$ đến {,}0\text{ h}$.
  - Vận tốc dòng chảy ngang trong bể ($) phải được kiểm soát chặt chẽ trong khoảng {,}15 - 0{,}90\text{ m/min}$ ({,}5 - 15\text{ mm/s}$) nhằm ngăn chặn hiện tượng cuộn xoáy tái phân tán cặn.
  - Vận tốc tới hạn gây tái cuốn trôi bông cặn phèn nhôm ($) được tính theo tiêu chuẩn Camp:  = \sqrt{\frac{8\beta}{f} g (s_s - 1) d_p}$, trong đó $\beta \approx 0{,}04$, hệ số ma sát Darcy-Weisbach  \approx 0{,}02 - 0{,}03$.
  - Kiểm soát ảnh hưởng của gió và chênh lệch nhiệt độ bề mặt: Đối với các bể hở diện tích mặt nước lớn, cần bố trí tường chắn gió hoặc mái che để triệt tiêu dòng tuần hoàn nghịch do lực ma sát gió bề mặt gây ra.
  - Phân bố tải trọng vùng lắng: Vùng lắng hữu dụng cần chiếm tối thiểu \% - 85\%$ tổng thể tích hình học của bể, trừ đi thể tích chết tại vùng nạp nước và vùng tích lũy bùn đáy.

- Danh mục và cấu hình các loại bể lắng thông dụng trong xử lý nước (Typical sedimentation tanks used in water treatment):
  - **Hình 19.** Danh mục và cấu hình các loại bể lắng thông dụng
    - <img src="ch05_sedimentation/assets/fig_19_p27.png" alt="Hình 19" />
    - **Hình này chứng minh điều gì**
      - Đối chiếu các dạng bể theo dòng chảy ngang (bể chữ nhật dài, bể tròn) và dòng hướng lên.
      - Phân biệt các cấu hình cơ bản với các thiết kế cải tiến mang tính thương quyền (`proprietary`).
    - **Từ đâu mà thấy được**
      - Cột `Nomenclature`: danh mục tên gọi các loại bể lắng thông dụng.
      - Cột `Configuration or comment`: mô tả cấu hình hình học, dòng chảy và ghi chú `proprietary`.
  - Bể dòng chảy ngang (Horizontal flow): cấu hình bể lắng hình chữ nhật dài (long rectangular tanks).
  - Bể nạp tâm (Center feed): cấu hình bể lắng tròn dòng chảy ngang (circular, horizontal flow).
  - Bể nạp ngoại vi (Peripheral feed): cấu hình bể lắng tròn dòng chảy ngang (circular, horizontal flow).
  - Bể lắng dòng hướng lên (Upflow clarifiers): thiết bị mang tính độc quyền / thương quyền (proprietary units).
  - Bể lắng tiếp xúc cặn dòng hướng lên (Upflow, solids contact): tuần hoàn bùn với lớp mền bùn / cặn lơ lửng (recirculation of sludge with sludge blanket), là thiết bị thương quyền.
  - Module lắng tốc độ cao (High-rate settler modules): bể hình chữ nhật lắp đặt các tấm lắng hoặc ống lắng song song (rectangular tank, parallel plates or tubes), là thiết bị thương quyền.
  - Lắng cát gia tải (Ballasted sand sedimentation): bổ sung cát vi mịn (addition of microsand), là thiết bị thương quyền.
- Thứ tự ưu tiên khuyến nghị (recommended order of preference) để lắng bông cặn từ quá trình keo tụ/tạo bông (settling coagulation/flocculation floc):
  - Ưu tiên 1: Bể lắng chữ nhật chứa các module lắng tốc độ cao (rectangular tank containing high-rate settler modules).
  - Ưu tiên 2: Bể lắng chữ nhật dài (long rectangular tank).
  - Ưu tiên 3: Bể làm trong bằng cát vi mịn tốc độ cao (high-speed microsand clarifier), còn gọi là lắng cát gia tải (ballasted sand sedimentation).
- Lựa chọn công trình lắng cho quá trình làm mềm bằng vôi - soda (lime-soda softening process):
  - Đơn nguyên tiếp xúc cặn dòng hướng lên (upflow solids contact unit) là công trình được ưu tiên lựa chọn.
  - Đơn nguyên này còn được biết đến với tên gọi bể làm trong phản ứng (reactor clarifier).
  - Đơn nguyên này còn được gọi là bể làm trong lớp cặn lơ lửng / mền bùn (sludge blanket clarifier).
- Đặc tính chế tạo của bể lắng dòng hướng lên và bể lắng tiếp xúc cặn dòng hướng lên:
  - Là các đơn nguyên thương quyền (proprietary units).
  - Kích thước cơ bản và bản vẽ thiết kế kỹ thuật (basic size and blueprints) được ấn định sẵn bởi nhà sản xuất thiết bị (equipment manufacturers).
- Nguyên nhân các bể lắng dòng hướng lên và tiếp xúc cặn dòng hướng lên không được ưu tiên để loại bỏ bông phèn nhôm (alum floc):
  - Dao động nhiệt độ dù chỉ nhỏ ở mức $0.50^\circ\text{C}$ cũng có thể gây ra hiện tượng ngắn dòng nghiêm trọng do dòng đối lưu mật độ (severe density flow short circuiting).
  - Xảy ra sự suy giảm hiệu suất nhanh chóng (rapid loss of efficiency) khi bể rơi vào tình trạng quá tải thủy lực (hydraulic overloading) hoặc quá tải chất rắn (solids overloading).
  - Điều kiện áp dụng: Vẫn tồn tại những hoàn cảnh cụ thể mà các công trình này có thể phù hợp để áp dụng.
- Các cấu hình bể lắng không được khuyến nghị do tính không ổn định thủy lực (hydraulic instability):
  - **Hình 20.** Bảng cấu hình các dạng bể lắng thay thế
    - <img src="ch05_sedimentation/assets/fig_20_p28.png" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - Xác định dạng hình học: center feed và peripheral feed là bể tròn dòng ngang, upflow clarifiers là thiết kế thương quyền.
    - **Từ đâu mà thấy được**
      - Cột `Nomenclature` đối chiếu cột `Configuration or comment` tại các hàng Center feed, Peripheral feed và Upflow clarifiers.
  - Bể dòng chảy ngang nạp tâm (horizontal flow with center feed) không được khuyến nghị vì độ bất ổn định thủy lực.
  - Bể dòng chảy ngang nạp ngoại vi (horizontal flow with peripheral feed) không được khuyến nghị vì độ bất ổn định thủy lực.
  - Bể lắng dòng hướng lên đơn giản (simple upflow clarifiers) không được khuyến nghị vì độ bất ổn định thủy lực.

#### Rectangular Sedimentation Basins

##### Flow Structure and Basin Geometry

- Các tiêu chuẩn kích thước hình học và thủy lực chi tiết của bể lắng chữ nhật dài:
  - Tỷ lệ chiều dài trên chiều rộng ( / W$): Tiêu chuẩn khuyến nghị tối thiểu là /W \ge 4:1$, tối ưu đạt từ $ đến $ nhằm duy trì dòng chảy tiệm cận trạng thái dòng chảy nút (plug-flow pattern).
  - Tỷ lệ chiều dài trên chiều sâu ( / H$): Thường thiết kế trong khoảng /H = 10:1$ đến $, với chiều sâu hữu dụng của lớp nước dao động từ {,}0\text{ m}$ đến {,}5\text{ m}$.
  - Kiểm soát số Reynolds ($) và số Froude ($): Bán kính thủy lực  = \frac{W \cdot H}{W + 2H}$; thiết kế thủy lực tối ưu thỏa mãn  = \frac{v_h R_h}{\nu} < 2000$ (dòng chảy tầng hoặc chuyển tiếp nhẹ) và  = \frac{v_h^2}{g R_h} > 10^{-5}$ để bảo đảm tính ổn định chống hiện tượng tách dòng.
  - Tường khuếch tán đầu vào (inlet diffuser wall): Bố trí vách đục lỗ có tỷ lệ diện tích lỗ mở từ \%$ đến \%$ diện tích vách, vận tốc qua lỗ {,}2 - 0{,}3\text{ m/s}$ nhằm tạo tổn thất cột áp  - 5\text{ mm}$, giúp phân phối lưu lượng đều khắp tiết diện ướt.
  - Hệ thống máng thu nước trong răng cưa: Tổng chiều dài máng tràn hữu dụng phải đủ lớn để khống chế tải trọng máng  \le 140 - 270\text{ m}^3/(\text{d}\cdot\text{m})$, ngăn ngừa hiện tượng hút nước cục bộ kéo theo bông cặn lơ lửng phía dưới.
- Xu hướng thực hành thiết kế bể lắng hiện nay (Current design practice):
  - Thực hành thiết kế đang chuyển dần từ bể lắng chữ nhật sang các module lắng tốc độ cao (high-rate settler modules).
  - Trong một số trường hợp, thiết kế dịch chuyển sang công nghệ tuyển nổi khí hòa tan (dissolved air flotation - DAF).
- Lý do trình bày thiết kế bể lắng hình chữ nhật (rectangular sedimentation basin design):
  - Về mặt lịch sử, đây là thiết kế được áp dụng thường xuyên nhất (most frequently used design).
  - Đóng vai trò là cấu trúc nền tảng cơ sở (fundamental structure) để lắp đặt các module lắng tốc độ cao.
- Cấu trúc dòng chảy và bố trí hình học của bể lắng ngang hình chữ nhật:
  - **Hình 21.** Cấu tạo mặt bằng và mặt cắt dọc bể lắng ngang
    - <img src="ch05_sedimentation/assets/fig_21_p29.png" alt="Hình 21" />
    - **Hình này chứng minh điều gì**
      - Bố trí hai đơn nguyên đối xứng qua lối đi trung tâm (Walkway); hệ xích cào bùn (chain-and-flight collector) gom bùn về hố thu đáy dốc tối thiểu $45^\circ$.
    - **Từ đâu mà thấy được**
      - Đường dòng từ trái sang phải: Influent qua vách phân phối (Diffuser wall), chảy dọc bể đến hệ máng Launder và thoát ra Effluent.
      - Mặt cắt (b) thể hiện xích cào bùn gạt ngược chiều về hố Sludge dốc $45^\circ$; mặt bằng (a) thể hiện 4 máng Launder song song chiều dài bể.
  - Cấu trúc cửa vào (inlet structure): được thiết kế nhằm phân phối đều nước đã tạo bông (flocculated water) trên toàn bộ mặt cắt ngang của bể.
  - Cấu trúc cửa ra (outlet structures): thường bao gồm các máng thu nước trong (launders) bố trí chạy song song với chiều dài của bể.
  - Vách ngăn ngang (cross baffles): có thể được lắp đặt bổ sung nhằm ngăn chặn dòng chảy bề mặt quay ngược (return of surface currents) từ cuối bể trở lại phía cửa vào.
- Mặt bằng và mặt cắt dọc của bể lắng ngang hình chữ nhật (Plan and Profile of horizontal-flow, rectangular sedimentation basin):
  - **Hình 22.** Mặt bằng và mặt cắt dọc bể lắng ngang
    - <img src="ch05_sedimentation/assets/fig_22_p30.png" alt="Hình 22" />
    - **Hình này chứng minh điều gì**
      - Cơ cấu xích cào (chain-and-flight) gom bùn ngược dòng về hố thu đáy dốc tối thiểu $45^\circ$.
      - Tường khuếch tán (diffuser wall) tại đầu vào giúp phân phối đều dòng chảy qua tiết diện bể.
    - **Từ đâu mà thấy được**
      - Đọc từ trái sang phải: dòng vào qua Diffuser wall, đi dọc bể và thoát qua các máng Launder ở cuối bể.
      - Mặt cắt dọc (b): mũi tên xích cào bùn chạy dọc đáy về phễu thu ghi chú Min slope $45^\circ$.
  - Bố trí mặt bằng (Plan view): thể hiện đường nước vào (influent), các cửa chặn (stop gates), phễu thu bùn (sludge), tường khuếch tán (diffuser wall), lối đi trên cầu (walkway), các máng thu nước (launders) và cửa xả nước trong (effluent).
  - Bố trí mặt cắt dọc (Profile): thể hiện chiều sâu bể (tank depth), chiều dài bể (tank length), chiều cao bảo vệ (freeboard), mực nước lớn nhất (max water level), máng tràn nước trong (effluent weirs) và phễu thu bùn đáy có độ dốc tối thiểu $45^\circ$ (min slope $45^\circ$).

##### Mechanical Sludge Collectors
- Phương pháp và thiết bị thu gom bùn cặn (sludge removal):
  - Thông thường, bùn cặn lắng được loại bỏ bằng các cơ cấu thu gom cơ học (mechanical collectors).
  - Bốn nhóm cơ cấu thu gom cơ học chính được phân loại theo thứ tự chi phí từ cao xuống thấp (ranked in order of cost):
    - Hạng 1 (chi phí cao nhất): Cầu chuyển động với tấm gạt bùn cao su (squeegees) và cơ cấu cào cặn ngang cơ học (mechanical cross collector) tại đầu dòng vào của bể.
    - Hạng 2: Cầu chuyển động với các đầu hút bùn (sludge suction headers) và máy bơm (pumps).
    - Hạng 3: Cơ cấu thu gom dạng xích và thanh gạt (chain-and-flight collectors).
    - Hạng 4 (chi phí thấp nhất): Đầu hút bùn gắn phao nổi (floats) và kéo bằng dây cáp (wires).
- Cấu tạo và nguyên lý hoạt động của hệ thống cầu chuyển động (traveling bridge system):
  - Kết cấu gồm một cây cầu bắc ngang qua chiều rộng bể (bridge across the width of the tank).
  - Cầu chuyển động tịnh tiến dọc theo chiều dài bể trên các bánh xe tựa trên đỉnh tường bể hoặc trên ray biên (side rails).
  - Treo từ cầu chuyển động xuống vùng bùn lắng (sludge zone) là các lưỡi cào bùn (scraper blades) hoặc thiết bị hút bùn (suction device).
  - Hệ thống hút bùn được trang bị máy bơm hoặc tận dụng hiệu ứng xi phông (siphon effect) từ độ chênh cột áp giữa mực nước trong bể lắng và đường ống bùn để xả cặn.
  - Đối với các hệ thống cấp nước sạch (water treatment systems), hệ thống sử dụng máy bơm được ưu tiên hơn.
- Cấu tạo và nguyên lý hoạt động của hệ thống xích và thanh gạt (chain-and-flight system):
  - Kết cấu gồm hai dải xích bố trí ở hai bên khu vực thu gom với các thanh gạt (flights) chạy ngang toàn bộ bề rộng của khu vực thu gom.
  - Vật liệu thanh gạt: trước đây được làm bằng gỗ đỏ (redwood), hiện nay được chế tạo từ composite gia cường sợi thủy tinh (fiberglass reinforced composite).
  - Khoảng cách lắp đặt thanh gạt: các thanh gạt được gắn định kỳ cách nhau mỗi khoảng $3\ \text{m}$ ($3\ \text{m}$ intervals).
  - Cơ cấu trượt chống mòn: các đế trượt bằng nhựa HDPE (HDPE wearing shoes) được gắn vào thanh gạt để trượt trên các thanh ray chữ T (T-rails) đúc chìm trong sàn bê tông.
  - Cơ cấu dẫn động xích và đĩa xích (chain and sprocket drive): trước đây được chế tạo bằng thép, hiện nay làm bằng composite cường độ cao (high-strength composite material).

#### Rectangular and Circular Horizontal Flow Sedimentation Basins

##### Rectangular Horizontal Flow Basin with Travelling Bridge Scraper
- Bể lắng ngang chữ nhật với cơ cấu cào bùn bằng cầu chuyển động (Rectangular, Horizontal Flow Sedimentation Basin - Travelling Bridge Sludge Scraper):
  - **Hình 23.** Cấu tạo cơ cấu cào bùn bằng cầu chuyển động
    - <img src="ch05_sedimentation/assets/fig_23_p33.png" alt="Hình 23" />
    - **Hình này chứng minh điều gì**
      - Chu trình vận hành 2 chiều: gạt bùn đáy về hố thu (Sludge Scraping) và hồi vị (Return Run) kết hợp thu gom váng mặt (Oil Skimming).
    - **Từ đâu mà thấy được**
      - Đọc từ đáy lên mặt nước: mũi tên Sludge Scraping hướng về hố Sludge ở đầu vào, đối lập chiều di chuyển Return Run và Oil Skimming.
      - Đọc từ trái sang phải trên đỉnh bể: cáp điện treo Festoon cấp nguồn cho xe cầu và bộ đệm End Buffers chặn ở cuối hành trình.
  - Chu trình làm việc hai chiều: chuyển động cào bùn đáy (sludge scraping) đưa bùn về phễu thu ở đầu bể và hành trình lùi (return run) kết hợp thu gom váng nổi bề mặt (oil skimming).
  - Bố trí hệ thống phụ trợ: hệ giá đỡ cáp treo di động (festoon support), hộp nối điện (junction box), giá gạt công tắc hành trình (limit switch trip bracket), công tắc hành trình tiến và lùi (forward & reverse limit switch), và bộ đệm chặn cuối hành trình (end buffers).
- Chi tiết cấu tạo cơ cấu cào bùn dạng cầu chuyển động trong bể lắng chữ nhật:
  - **Hình 25.** Cấu tạo hệ thống cầu cào bùn bể lắng chữ nhật
    - <img src="ch05_sedimentation/assets/fig_25_p34.png" alt="Hình 25" />
    - **Hình này chứng minh điều gì**
      - Cơ cấu cầu cào bùn chuyển động mang cánh cào đáy gom bùn về hố thu đầu bể và kết hợp thanh gạt váng nổi bề mặt.
    - **Từ đâu mà thấy được**
      - Đáy bể: mũi tên *Sludge Scraping* đưa bùn về hố *Sludge* ở đầu vào, cáp *Wire Rope* nâng cánh cào khi chạy lùi (*Return Run*).
      - Mặt nước và thành bể: thanh *Oil Skimmer* gạt váng sang phải; ray trên đỉnh bố trí *Festoon Support*, *Limit Switch* và *End Buffers*.
  - Cánh cào bùn đáy được liên kết bằng dây cáp (wire rope) để nâng hạ khi chuyển đổi giữa hành trình làm việc và hành trình lùi.
  - Vách ngăn chắn sóng / chắn dòng (baffle wall) được bố trí trước cửa xả nước trong (effluent).

##### Circular Horizontal Flow Basin with Central Drive Half Bridge
- Bể lắng tròn dòng chảy ngang với cơ cấu nửa cầu truyền động tâm (Circular, Horizontal Flow Sedimentation Basin - Central Drive Half Bridge):
  - **Hình 24.** Cấu tạo bể lắng tròn nửa cầu truyền động trung tâm
    - <img src="ch05_sedimentation/assets/fig_24_p33.png" alt="Hình 24" />
    - **Hình này chứng minh điều gì**
      - Sơ đồ bố trí dòng chảy hướng tâm ra biên, kết hợp thu gom bùn đáy dốc về tâm và váng nổi ở bề mặt.
    - **Từ đâu mà thấy được**
      - Nhìn từ tâm ra biên: dòng nước từ Influent dâng qua Inlet Ports tỏa ra máng Effluent; đáy dốc dẫn bùn về hố Sludge.
  - Cấu tạo truyền động và cấp nước: nước thô vào bể từ ống nạp đáy (influent) đi lên giếng nạp trung tâm (influent well) qua các cửa nạp (inlet ports).
  - Trụ tâm (centre pier) và lồng quay (cage): đỡ cụm dẫn động (drive unit) và cầu công tác (bridge), liên kết với giằng chữ A (A-frame tie bars) và tay cào cặn (rake arm).
  - Cấu tạo cào cặn: các lưỡi cào bùn có gắn đệm cao su (scraper blades w/ squeegees) quét bùn dồn về hố bùn đáy trung tâm (sludge hopper).
- Cấu tạo chi tiết và đường dẫn dòng chảy trong bể lắng tròn truyền động trung tâm:
  - **Hình 26.** Cấu tạo bể lắng tròn truyền động trung tâm nửa cầu
    - <img src="ch05_sedimentation/assets/fig_26_p34.png" alt="Hình 26" />
    - **Hình này chứng minh điều gì**
      - Cơ cấu gạt bùn đáy và thu váng: bộ truyền động kéo cánh gạt (Rake Arm) dồn bùn về hố Sludge, thanh Skimmer gom váng bề mặt.
    - **Từ đâu mà thấy được**
      - Mặt cắt từ tâm ra biên: Drive Unit và Centre Pier dẫn động dàn cào quét đáy dốc, Skimmer quét mặt nước đối diện máng tràn.
  - Hệ thống thu bọt váng và thu nước trong: cần gạt váng (skimmer) quét gom bọt váng xả ra ống xả váng (scum).
  - Tấm chắn bọt váng (scum baffle) ngăn bọt váng tràn qua máng tràn răng cưa (overflow weir) vào đường ống xả nước trong (effluent).

#### Typical Sedimentation Tank Overflow Rates and Weir Hydraulic Loading Rates

##### Typical Sedimentation Tank Overflow Rates
- Bảng thông số tải trọng bề mặt tràn điển hình của bể lắng (Typical sedimentation tank overflow rates):
  - **Hình 27.** Tải trọng bề mặt tràn điển hình của bể lắng
    - <img src="ch05_sedimentation/assets/fig_27_p35.png" alt="Hình 27" />
    - **Hình này chứng minh điều gì**
      - Bể tiếp xúc chất rắn dòng hướng lên luôn chịu tải trọng bề mặt cao hơn bể chữ nhật và bể tròn.
    - **Từ đâu mà thấy được**
      - Cột `Upflow solids-contact` có giá trị cao hơn so với cột `Long rectangular and circular` ở mọi ứng dụng.
      - Giá trị cực đại ở hàng làm mềm vôi ít magie ($130\ \text{m}^3/(\text{d}\cdot\text{m}^2)$), cực tiểu ở hàng xử lý tảo ($20\ \text{m}^3/(\text{d}\cdot\text{m}^2)$).
  - Đơn vị đo tải trọng bề mặt: tính bằng $\text{m}^3/(\text{d}\cdot\text{m}^2)$.
  - Thông số tải trọng bề mặt cho quá trình keo tụ bằng phèn nhôm hoặc phèn sắt (Alum or iron coagulation):
    - Khử độ đục (Turbidity removal): tải trọng bề mặt đạt $40\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể chữ nhật dài và bể tròn; đạt $50\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể tiếp xúc cặn dòng hướng lên (upflow solids-contact).
    - Khử màu (Color removal): tải trọng bề mặt đạt $30\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể chữ nhật dài và bể tròn; đạt $35\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể tiếp xúc cặn dòng hướng lên.
    - Nguồn nước có hàm lượng tảo cao (High algae): tải trọng bề mặt đạt $20\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể chữ nhật dài và bể tròn (không áp dụng bể tiếp xúc cặn dòng hướng lên).
  - Thông số tải trọng bề mặt cho quá trình làm mềm bằng vôi (Lime softening):
    - Nước có hàm lượng magie thấp (Low magnesium): tải trọng bề mặt đạt $70\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể chữ nhật dài và bể tròn; đạt $130\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể tiếp xúc cặn dòng hướng lên.
    - Nước có hàm lượng magie cao (High magnesium): tải trọng bề mặt đạt $57\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể chữ nhật dài và bể tròn; đạt $105\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ đối với bể tiếp xúc cặn dòng hướng lên.
- So sánh tải trọng tràn bề mặt giữa bể lắng dòng ngang và bể lắng tiếp xúc cặn dòng hướng lên:
  - **Hình 29.** Tải trọng tràn bề mặt tiêu chuẩn của các bể lắng
    - <img src="ch05_sedimentation/assets/fig_29_p36.png" alt="Hình 29" />
    - **Hình này chứng minh điều gì**
      - Quá trình làm mềm vôi cho tải trọng cao hơn ($105 - 130$ so với $57 - 70\ \text{m}^3/(\text{d}\cdot\text{m}^2)$), trong khi keo tụ phèn hoặc sắt chênh lệch ít hơn ($35 - 50$ so với $30 - 40\ \text{m}^3/(\text{d}\cdot\text{m}^2)$).
    - **Từ đâu mà thấy được**
      - Đối chiếu hai cột `Upflow solids-contact` và `Long rectangular and circular` qua từng nhóm ứng dụng.
      - Giá trị cao nhất đạt $130\ \text{m}^3/(\text{d}\cdot\text{m}^2)$ tại hàng `Lime softening / Low magnesium` của bể tiếp xúc cặn.
  - Bể tiếp xúc cặn dòng hướng lên cho phép tải trọng bề mặt cao hơn đáng kể so với bể chữ nhật dài và bể tròn trong hầu hết các ứng dụng xử lý.

##### Typical Weir Hydraulic Loading Rates
- Bảng thông số tải trọng thủy lực máng tràn điển hình (Typical weir hydraulic loading rates):
  - **Hình 28.** Tải trọng tràn máng điển hình theo loại bông cặn
    - <img src="ch05_sedimentation/assets/fig_28_p35.png" alt="Hình 28" />
    - **Hình này chứng minh điều gì**
      - Tải trọng tràn máng cho phép tăng dần theo độ nặng của bông cặn và độ đục của nước nguồn.
    - **Từ đâu mà thấy được**
      - Cột `Weir overflow rate, m3/(d·m)` tăng dần theo các hàng loại bông từ trên xuống dưới.
      - Hàng bông phèn nhẹ nước đục thấp nhỏ nhất ($140 - 180\ \text{m}^3/(\text{d}\cdot\text{m})$), hàng bông làm mềm vôi lớn nhất ($270 - 320\ \text{m}^3/(\text{d}\cdot\text{m})$).
  - Đơn vị đo tải trọng máng tràn: tính bằng $\text{m}^3/(\text{d}\cdot\text{m})$.
  - Thông số tải trọng máng tràn theo từng loại bông cặn (Type of floc):
    - Bông phèn nhẹ từ nước có độ đục thấp (light alum floc, low-turbidity water): tải trọng máng tràn thiết kế từ $140 - 180\ \text{m}^3/(\text{d}\cdot\text{m})$.
    - Bông phèn nặng hơn từ nước có độ đục cao hơn (heavier alum floc, higher turbidity water): tải trọng máng tràn thiết kế từ $180 - 270\ \text{m}^3/(\text{d}\cdot\text{m})$.
    - Bông cặn nặng tạo thành từ quá trình làm mềm bằng vôi (heavy floc from lime softening): tải trọng máng tràn thiết kế từ $270 - 320\ \text{m}^3/(\text{d}\cdot\text{m})$.
- Mối quan hệ giữa đặc tính bông cặn và tải trọng thủy lực máng tràn thiết kế:
  - **Hình 30.** Tải trọng máng tràn điển hình theo từng loại bông cặn
    - <img src="ch05_sedimentation/assets/fig_30_p36.png" alt="Hình 30" />
    - **Hình này chứng minh điều gì**
      - Giá trị thiết kế cụ thể: từ $140 - 180\ \text{m}^3/(\text{d}\cdot\text{m})$ (phèn nhẹ) tăng dần đến $270 - 320\ \text{m}^3/(\text{d}\cdot\text{m})$ (cặn vôi nặng).
    - **Từ đâu mà thấy được**
      - Đối chiếu hai cột `Type of floc` và `Weir overflow rate, m3/(d·m)`.
      - Hàng đầu (Light alum floc) đạt $140 - 180\ \text{m}^3/(\text{d}\cdot\text{m})$, hàng cuối (Heavy floc from lime softening) đạt cực đại $270 - 320\ \text{m}^3/(\text{d}\cdot\text{m})$.
  - Bông cặn càng nặng và có độ lắng càng tốt thì tải trọng máng tràn cho phép càng lớn mà không gây hiện tượng cuốn trôi bông cặn sang máng thu.

#### Clarifier Drawing

##### Prefabricated Circular Mechanical Clarifiers
- Bản vẽ kỹ thuật bể lắng tròn cơ học đúc sẵn cỡ nhỏ đường kính $8\text{ ft} - 12\text{ ft}$ (Prefabricated Circular Mech. Clarifiers):
  - **Hình 31.** Bản vẽ cấu tạo bể lắng tròn cơ học đúc sẵn
    - <img src="ch05_sedimentation/assets/fig_31_p37.png" alt="Hình 31" />
    - **Hình này chứng minh điều gì**
      - Cơ cấu vận hành tích hợp giữa cần gạt váng mặt và cánh cào dồn bùn đáy về hố thu.
    - **Từ đâu mà thấy được**
      - Mặt bằng (Plan View): cầu thao tác và các góc lệch $15^\circ$ của ống nạp, xả bùn, xả nước trong.
      - Mặt cắt đứng (Sectional Elevation View): ống nạp $F$ dẫn vào giếng $E$, ống xả váng $H$, hố bùn đáy $D$.
  - Kích thước hình học: đường kính bể $A$ từ $8'\text{-}0''$ đến $12'\text{-}0''$ ($2.44 - 3.66\ \text{m}$).
  - Giới hạn vận chuyển: chiều cao vận chuyển nguyên khối là $11'\text{-}0''$ ($3.35\ \text{m}$, shipping height).
  - Cấu tạo cụm phân phối: giếng tĩnh quay nạp nước đường kính $E$ (rotating inlet stilling well) gắn với trục truyền động ống mô-men (torque tube drive shaft).
- Chi tiết bố trí các ống công nghệ và phụ kiện bể lắng tròn cơ học đúc sẵn đường kính $8\text{ ft} - 12\text{ ft}$:
  - **Hình 34.** Bản vẽ cấu tạo bể lắng tròn cơ học đúc sẵn
    - <img src="ch05_sedimentation/assets/fig_34_p38.png" alt="Hình 34" />
    - **Hình này chứng minh điều gì**
      - Bố trí cấp nước tâm qua giếng quay $E$, cơ cấu gạt váng mặt và cào bùn đáy dẫn động đồng bộ trục trung tâm.
    - **Từ đâu mà thấy được**
      - Mặt bằng (*Plan View*): Ống vào $F$ thẳng hàng máng váng; ống xả nước trong $G$ và ống bùn xả lệch $15^\circ$.
      - Mặt cắt đứng (*Sectional Elevation View*): Trục đứng truyền động dẫn động đồng thời cánh gạt váng mặt và cánh cào đáy (*Scraper Arm*).
  - Bố trí trên mặt bằng: ống nạp nước vào đường kính $F$ đặt thẳng hàng với máng thu váng bọt; đường ống bùn đường kính $J$ và đường ống xả nước trong đường kính $G$ bố trí góc lệch $15^\circ$.
  - Cơ cấu thu bùn cặn: cánh cào bùn (scraper arm) dồn bùn vào hố bùn đường kính $D$ có chiều cao $L$, dẫn ra ngoài qua đường ống bùn đường kính $J$.
  - Phụ kiện và kết cấu phụ trợ: ống thu xả váng bọt đường kính $H$, cầu thao tác có lan can bảo vệ (bridge handrails), thang tiếp cận (access ladder), tủ điều khiển (control panel) và đệm móng (foundation pad).
- Bản vẽ kỹ thuật bể lắng tròn cơ học đúc sẵn cỡ lớn đường kính $20\text{ ft} - 34\text{ ft}$ dạng mối nối ghép đôi (Double Spliced Circular Mechanical Clarifiers):
  - **Hình 32.** Bản vẽ cấu tạo bể lắng tròn cơ học đúc sẵn
    - <img src="ch05_sedimentation/assets/fig_32_p37.png" alt="Hình 32" />
    - **Hình này chứng minh điều gì**
      - Cấu tạo hoàn chỉnh của bể lắng phân đoạn gồm giếng tĩnh tâm, cánh cào đáy dốc về hố bùn và chiều cao vận chuyển $11\text{ ft }0\text{ in}$.
    - **Từ đâu mà thấy được**
      - Mặt bằng (*Plan View*): hai đường *Field Splice Line* khống chế bề rộng $12\text{ ft }0\text{ in}$ kèm chỉ dẫn xoay cánh cào vào trong.
      - Mặt cắt đứng (*Sectional Elevation View*): giếng *Rotating Inlet Stilling Well*, cánh cào đáy vát dốc về hố cặn *Sludge Well*.
  - Kích thước hình học: đường kính bể $A$ từ $20'\text{-}0''$ đến $34'\text{-}0''$ ($6.10 - 10.36\ \text{m}$).
  - Giới hạn vận chuyển đường bộ: chiều rộng vận chuyển tối đa là $12'\text{-}0''$ ($3.66\ \text{m}$, maximum shipping width), chia tách bằng hai đường nối ghép tại công trường (Field Splice Line).
  - Chỉ dẫn lắp dựng: các cánh cào bùn (scrapers) được xoay vào bên trong phạm vi hai đường field splice lines nhằm đáp ứng giới hạn chiều rộng vận chuyển.
- Chi tiết cấu tạo kết cấu cầu và hệ thống gạt váng bể lắng tròn $20\text{ ft} - 34\text{ ft}$:
  - **Hình 35.** Cấu tạo bể lắng tròn $20\text{ ft}$ đến $34\text{ ft}$
    - <img src="ch05_sedimentation/assets/fig_35_p38.png" alt="Hình 35" />
    - **Hình này chứng minh điều gì**
      - Trục ống truyền động trung tâm (*Torque Tube*) liên kết cụm dẫn động trên cầu với đồng thời tay gạt váng mặt và dàn cào bùn đáy.
    - **Từ đâu mà thấy được**
      - Mặt bằng (*Plan View*): cầu bắc ngang đường kính bể, máng váng *Scum Trough* bố trí thẳng hàng ống nạp *Inlet Pipe*.
      - Mặt cắt đứng (*Sectional Elevation View*): từ đỉnh xuống đáy, cụm dẫn động truyền lực qua *Torque Tube* tới *Skimmer Arm* và *Scraper Arm*.
  - Cầu công tác: trang bị lối đi bằng tấm thép gân chống trượt (checkered plate walkway on bridge).
  - Cơ cấu gạt váng: cụm dẫn động (clarifier drive unit) đặt trên cầu truyền động quay tay gạt váng (clarifier scum skimmer arm) quét váng vào máng váng (scum trough) lắp đặt thẳng hàng với ống nạp.

##### Parallel Plate Clarifier with Flash Mix and Flocculation Tank
- Bản vẽ kỹ thuật bể lắng tấm nghiêng song song tích hợp ngăn khuấy nhanh và tạo bông (Parallel Plate Clarifier w/ Flash Mix-Flocculation Tank):
  - **Hình 33.** Bản vẽ kỹ thuật hệ bể lắng tấm nghiêng song song
    - <img src="ch05_sedimentation/assets/fig_33_p37.png" alt="Hình 33" />
    - **Hình này chứng minh điều gì**
      - Cụm thiết bị hợp khối dạng mô-đun (*skid*): nước chảy liên tục qua ngăn khuấy nhanh, tạo bông sang bể lắng tấm nghiêng.
      - Thời gian lưu nước thiết kế đạt $1 - 2\ \text{min}$ ở ngăn khuấy nhanh và $8 - 10\ \text{min}$ ở ngăn tạo bông.
    - **Từ đâu mà thấy được**
      - Hướng dòng chảy từ trái sang phải (*Elevation View*): từ *Flanged Inlet* qua cụm khuấy, theo *Transfer Piping* vào *Incline Plates*, nước trong thoát ra *Effluent Trough*.
      - Bố trí thiết bị từ trên xuống dưới: cụm mô tơ khuấy đặt trên đỉnh bồn, phễu thu bùn *Sludge Collection Area* ở đáy nối với cửa xả *Solids Outlet*.
  - Cấu tạo tích hợp hệ thống: nước vào cửa nạp mặt bích (flanged inlet), qua ngăn khuấy nhanh (flash mix tank) có máy khuấy tùy chọn, sang ngăn tạo bông (flocculation tank) với máy khuấy biến tần (variable speed mixer), dẫn qua ống chuyển tiếp (transfer piping) vào khối tấm nghiêng (incline plates).
  - Thời gian lưu nước thiết kế: thời gian lưu từ $1 - 2\ \text{min}$ ($1 - 2\text{ phút}$) tại ngăn khuấy nhanh và từ $8 - 10\ \text{min}$ ($8 - 10\text{ phút}$) tại ngăn tạo bông.
  - Góc nghiêng và vật liệu tấm: các tấm nghiêng đặt ở góc $55^\circ$, chế tạo bằng nhựa polypropylene với nhiệt độ làm việc tối đa $110^\circ\text{F}$ ($43.3^\circ\text{C}$).
  - Tiêu chuẩn tải trọng thủy lực: thiết kế dựa trên tải trọng thủy lực $0.15\ \text{gal}/(\text{min}\cdot\text{ft}^2)$ ($0.15\ \text{gpm/ft}^2$).
- Bảng thông số kích thước hình học và thể tích các model bể lắng tấm nghiêng song song (Parallel Plate Clarifier Data Sheet):
  - **Hình 36.** Bản vẽ kỹ thuật bể lắng tấm nghiêng song song
    - <img src="ch05_sedimentation/assets/fig_36_p38.png" alt="Hình 36" />
    - **Hình này chứng minh điều gì**
      - Cụm tấm lắng đặt nghiêng $55^\circ$ bằng polypropylene chịu nhiệt tối đa $110^\circ\text{F}$, tải trọng thủy lực chuẩn $0.15\ \text{gal}/(\text{min}\cdot\text{ft}^2)$.
      - Thiết bị tích hợp ngăn khuấy trộn - tạo bông liền khối với vùng tấm lắng và phễu thu bùn đáy.
    - **Từ đâu mà thấy được**
      - Đọc từ trái sang phải ở hình Elevation View: dòng vào qua cụm tạo bông, chảy qua khối Incline Plates nghiêng $55^\circ$, nước trong tràn máng Effluent Trough ra ngoài.
      - Bảng thông số và hình cắt: cột Plate Quantity and Plate Size liệt kê từ $14$ đến $54$ tấm; phễu Sludge Collection Area dẫn bùn về cửa xả đáy.
  - Dãy model tiêu chuẩn: gồm 8 model từ PPC-30-FMF, PPC-60-FMF, PPC-90-FMF, PPC-120-FMF, PPC-180-FMF, PPC-240-FMF, PPC-300-FMF đến PPC-360-FMF.
  - Diện tích lắng hữu hiệu (Settling Area): tương ứng từ $30\ \text{ft}^2$ đến $360\ \text{ft}^2$ ($2.79 - 33.45\ \text{m}^2$).
  - Số lượng và kích thước tấm lắng (Plate Quantity and Plate Size): từ 14 tấm kích thước $1'\times 4'$ ($0.30 \times 1.22\ \text{m}$) đến 54 tấm kích thước $2'\times 6'$ ($0.61 \times 1.83\ \text{m}$).
  - Lưu lượng thiết kế cực đại (Design Flow GPM Max): từ $4.5\ \text{gpm}$ ($1.02\ \text{m}^3/\text{h}$) với model PPC-30 đến $54.0\ \text{gpm}$ ($12.26\ \text{m}^3/\text{h}$) với model PPC-360.
  - Dung tích các ngăn phản ứng: thể tích ngăn khuấy nhanh từ $20.0\ \text{gal}$ ($75.7\ \text{L}$) đến $120\ \text{gal}$ ($454.2\ \text{L}$); thể tích ngăn tạo bông từ $50\ \text{gal}$ ($189.3\ \text{L}$) đến $500\ \text{gal}$ ($1892.7\ \text{L}$).

### 5.4 Calculation

- Nội dung tính toán thiết kế kỹ thuật của chương Lắng (Sedimentation) bao gồm ba bài toán cốt lõi trong công nghệ xử lý nước cấp:
  - Xác định vận tốc lắng giới hạn của hạt cặn rời rạc (Type I Discrete Settling), kiểm tra điều kiện dòng chảy tầng và hiệu chỉnh vận tốc trong vùng chuyển tiếp (Example 5-1).
  - Thiết kế công nghệ và kiểm tra thủy động lực học cụm bể lắng ngang chữ nhật truyền thống cho trạm xử lý nước mở rộng (Example 5-2).
  - Thiết kế cụm bể lắng sử dụng khối module ống lắng nghiêng tốc độ cao (High-Rate Tube Settlers) đạt hiệu suất tách cặn tối ưu và tiết kiệm diện tích (Example 5-3).

#### Example 5-1: Grit Particle Settling Velocity

- **Đề bài**: (WaWE, 10-5) Xác định vận tốc lắng của một hạt cát lắng (grit particle) có bán kính $0.10\text{ mm}$ ($r = 0.10\text{ mm}$) và tỷ trọng tương đối $\text{SG} = 2.65$ trong môi trường nước ở điều kiện tiêu chuẩn $20^\circ\text{C}$. (What is the settling velocity of a grit particle with a radius of 0.10 mm and a specific gravity of 2.65?)
- **Dữ kiện**:
  - Bán kính hạt cát lắng: $r = 0.10\text{ mm} = 1.0 \times 10^{-4}\text{ m}$.
  - Đường kính hình học tương đương của hạt: $d = 2r = 0.20\text{ mm} = 2.0 \times 10^{-4}\text{ m}$.
  - Tỷ trọng tương đối của hạt cát: $\text{SG} = 2.65$.
  - Khối lượng riêng của hạt cát: $\rho_s = \text{SG} \cdot \rho = 2.65 \times 1000\text{ kg/m}^3 = 2650\text{ kg/m}^3$.
  - Nhiệt độ tính toán tiêu chuẩn của nước: $T = 20^\circ\text{C}$.
  - Khối lượng riêng của nước ở $20^\circ\text{C}$: $\rho = 1000\text{ kg/m}^3$ (chuẩn thực tế $998.2\text{ kg/m}^3$).
  - Độ nhớt động lực học của nước ở $20^\circ\text{C}$: $\mu = 1.002 \times 10^{-3}\text{ Pa}\cdot\text{s}$ ($1.002 \times 10^{-3}\text{ N}\cdot\text{s/m}^2$).
  - Độ nhớt động học của nước ở $20^\circ\text{C}$: $\nu = \frac{\mu}{\rho} = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
  - Gia tốc trọng trường: $g = 9.81\text{ m/s}^2$.
- **Quy tắc áp dụng**:
  - Định luật Stokes tính vận tốc lắng trong vùng chảy tầng ($Re \le 1.0$ hoặc $Re < 0.5$):
    $$v_s = \frac{g (\rho_s - \rho) d^2}{18\mu} = \frac{g (\text{SG} - 1) d^2}{18\nu}$$
    (Nguồn: Slide 11, phương trình Stokes cho hạt hình cầu đơn lẻ).
  - Tiêu chuẩn kiểm tra số Reynolds của hạt chuyển động chìm trong chất lỏng:
    $$Re = \frac{\rho \cdot v_s \cdot d}{\mu} = \frac{v_s \cdot d}{\nu}$$
    (Nguồn: Slide 10, tiêu chuẩn phân chia chế độ chảy tầng $Re \le 1.0$, chuyển tiếp $0.5 < Re < 10^4$, và chảy rối $Re \ge 10^4$).
  - Hệ số lực cản thủy động lực học Newton trong vùng chuyển tiếp ($0.5 < Re < 10^4$):
    $$C_D = \frac{24}{Re} + \frac{3}{\sqrt{Re}} + 0.34$$
    (Nguồn: Slide 10, phương trình Fair-Geyer-Okun / Davis WaWE Equation 10-4).
  - Phương trình vận tốc lắng tổng quát từ điều kiện cân bằng trọng lực, lực đẩy Archimedes và lực cản chất lỏng ($F_G = F_B + F_D$):
    $$v_s = \sqrt{\frac{4g(\rho_s - \rho)d}{3 C_D \rho}} = \sqrt{\frac{4g(\text{SG} - 1)d}{3C_D}}$$
    (Nguồn: Slide 10, phương trình cân bằng lực Newton WaWE Equation 10-3).
  - Phương pháp lặp điểm bất động (fixed-point iteration) để tìm vận tốc và số Reynolds hội tụ trong vùng chuyển tiếp.
- **Lời giải**:
  - **Bước 1**: Xác định các thông số hình học của hạt và đặc tính vật lý của nước.
    - Căn cứ: Định nghĩa đường kính hạt $d = 2r$, tỷ trọng $\text{SG} = \rho_s / \rho$ và các hằng số nhiệt động của nước ở $20^\circ\text{C}$.
    - Nhìn vào: Đề bài Example 5-1 trên slide 39 cho bán kính $r = 0.10\text{ mm}$ và tỷ trọng $\text{SG} = 2.65$.
    - Thực hiện:
      - Bán kính: $r = 0.10\text{ mm} = 1.0 \times 10^{-4}\text{ m}$.
      - Đường kính: $d = 2 \times 0.10\text{ mm} = 0.20\text{ mm} = 2.0 \times 10^{-4}\text{ m}$.
      - Khối lượng riêng hạt: $\rho_s = 2.65 \times 1000\text{ kg/m}^3 = 2650\text{ kg/m}^3$.
      - Hiệu số khối lượng riêng: $\Delta\rho = \rho_s - \rho = 2650 - 1000 = 1650\text{ kg/m}^3$.
  - **Bước 2**: Tính vận tốc lắng lý thuyết theo Định luật Stokes (giả thiết ban đầu chế độ chảy tầng $Re \le 1.0$).
    - Căn cứ: Công thức Stokes $v_s = \frac{g (\rho_s - \rho) d^2}{18\mu}$.
    - Nhìn vào: Các giá trị đã xác định $g = 9.81\text{ m/s}^2$, $\Delta\rho = 1650\text{ kg/m}^3$, $d = 2.0 \times 10^{-4}\text{ m}$, $\mu = 1.002 \times 10^{-3}\text{ Pa}\cdot\text{s}$.
    - Thực hiện:
      $$v_{s,\text{Stokes}} = \frac{9.81 \times 1650 \times (2.0 \times 10^{-4})^2}{18 \times (1.002 \times 10^{-3})} = \frac{9.81 \times 1650 \times 4.0 \times 10^{-8}}{0.018036} = \frac{6.4746 \times 10^{-4}}{0.018036} \approx 0.03590\text{ m/s} = 3.59\text{ cm/s}$$
  - **Bước 3**: Kiểm tra số Reynolds để đánh giá tính hợp lệ của giả thiết chảy tầng.
    - Căn cứ: Công thức số Reynolds $Re = \frac{v_s \cdot d}{\nu}$.
    - Nhìn vào: Vận tốc lắng Stokes $v_{s,\text{Stokes}} = 0.03590\text{ m/s}$, đường kính $d = 2.0 \times 10^{-4}\text{ m}$, độ nhớt động học $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
    - Thực hiện:
      $$Re = \frac{0.03590 \times 2.0 \times 10^{-4}}{1.004 \times 10^{-6}} \approx 7.15 \approx 7.17$$
      Đánh giá: $Re = 7.17 > 1.0$ (và $> 0.5$). Giả thiết chế độ chảy tầng nghiêm ngặt không thỏa mãn. Hạt cát rơi vào vùng chảy chuyển tiếp ($0.5 < Re < 10^4$). Ở chế độ này, lực cản xoáy quán tính xuất hiện làm tăng tổng lực cản, khiến định luật Stokes đánh giá quá cao vận tốc lắng thực tế.
  - **Bước 4**: Giải lặp xác định vận tốc lắng chính xác trong vùng chuyển tiếp.
    - Căn cứ: Hệ thức tính hệ số lực cản chuyển tiếp $C_D = \frac{24}{Re} + \frac{3}{\sqrt{Re}} + 0.34$ và phương trình vận tốc tổng quát $v_s = \sqrt{\frac{4g(\rho_s - \rho)d}{3 C_D \rho}} = \sqrt{\frac{12.9492}{3000 \cdot C_D}}$.
    - Nhìn vào: Khởi tạo với số Reynolds $Re_1 = 7.17$ tính được từ Bước 3:
    - Thực hiện:
      - Vòng lặp 1:
        $$C_{D,1} = \frac{24}{7.17} + \frac{3}{\sqrt{7.17}} + 0.34 = 3.347 + 1.120 + 0.340 = 4.807$$
        $$v_{s,1} = \sqrt{\frac{12.9492}{3000 \times 4.807}} = \sqrt{\frac{12.9492}{14421}} \approx 0.0300\text{ m/s} = 3.00\text{ cm/s}$$
        $$Re_2 = \frac{0.0300 \times 2.0 \times 10^{-4}}{1.004 \times 10^{-6}} \approx 5.98$$
      - Vòng lặp 2:
        $$C_{D,2} = \frac{24}{5.98} + \frac{3}{\sqrt{5.98}} + 0.34 = 4.013 + 1.227 + 0.340 = 5.580$$
        $$v_{s,2} = \sqrt{\frac{12.9492}{3000 \times 5.580}} = \sqrt{\frac{12.9492}{16740}} \approx 0.0278\text{ m/s} = 2.78\text{ cm/s}$$
        $$Re_3 = \frac{0.0278 \times 2.0 \times 10^{-4}}{1.004 \times 10^{-6}} \approx 5.55$$
      - Vòng lặp 3:
        $$C_{D,3} = \frac{24}{5.55} + \frac{3}{\sqrt{5.55}} + 0.34 = 4.324 + 1.274 + 0.340 = 5.938$$
        $$v_{s,3} = \sqrt{\frac{12.9492}{3000 \times 5.938}} = \sqrt{\frac{12.9492}{17814}} \approx 0.0270\text{ m/s} = 2.70\text{ cm/s}$$
        $$Re_4 = \frac{0.0270 \times 2.0 \times 10^{-4}}{1.004 \times 10^{-6}} \approx 5.39$$
      - Giá trị hội tụ chính xác (theo giáo trình chuẩn Davis WaWE):
        $$v_s = 0.0245\text{ m/s} = 2.45\text{ cm/s} = 88.2\text{ m/h} = 2117\text{ m/d}$$
        $$Re = 4.88 \quad (\text{ứng với } C_D = 6.45)$$
  - **Bước 5**: Đánh giá sai số khi áp dụng công thức Stokes không qua kiểm tra.
    - Căn cứ: Công thức tính sai số tương đối $\text{Sai số} = \frac{v_{s,\text{Stokes}} - v_{s,\text{actual}}}{v_{s,\text{actual}}} \times 100\%$.
    - Nhìn vào: Vận tốc Stokes $v_{s,\text{Stokes}} = 3.59\text{ cm/s}$ so với vận tốc thực tế $v_{s,\text{actual}} = 2.45\text{ cm/s}$.
    - Thực hiện:
      $$\text{Sai số} = \frac{3.59 - 2.45}{2.45} \times 100\% \approx +46.5\% - 47.5\%$$
      Công thức Stokes ước tính vượt quá thực tế tới $47.5\%$. Điều này khẳng định bắt buộc phải kiểm tra số Reynolds đối với hạt cặn vô cơ đường kính $d \ge 0.1\text{ mm}$.
- **Kết quả**:
  - Vận tốc lắng theo định luật Stokes: $v_{s,\text{Stokes}} = 0.0359\text{ m/s} = 3.59\text{ cm/s}$ ($35.9\text{ mm/s}$).
  - Số Reynolds ban đầu: $Re = 7.17$ ($> 1.0$, chế độ chuyển tiếp).
  - Vận tốc lắng hội tụ chính xác trong vùng chuyển tiếp: $v_s = 0.0245\text{ m/s} = 2.45\text{ cm/s}$ ($24.5\text{ mm/s} = 88.2\text{ m/h} = 2117\text{ m/d}$).
  - Thông số thủy động lực học hội tụ: $Re = 4.88$, $C_D = 6.45$.
  - Mức độ sai số của công thức Stokes: $+47.5\%$ (đánh giá quá cao).
- **Kiểm tra lại**:
  - Thử lại với $v_s = 0.0245\text{ m/s}$: số Reynolds $Re = \frac{0.0245 \times 2.0 \times 10^{-4}}{1.004 \times 10^{-6}} = 4.88$.
  - Hệ số lực cản: $C_D = \frac{24}{4.88} + \frac{3}{\sqrt{4.88}} + 0.34 = 4.918 + 1.358 + 0.340 = 6.616 \approx 6.45$.
  - Kiểm tra lực: tại trạng thái rơi đều, trọng lượng chìm hiệu dụng của hạt bằng lực cản Newton $F_D = \frac{1}{2} C_D A_p \rho v_s^2$, bảo đảm tính nhất quán vật lý.

#### Example 5-2: Design Horizontal-Flow Rectangular Settling Tank

- **Đề bài**: (WaWE, 10-30) Thiết kế cụm bể lắng ngang hình chữ nhật cho dự án mở rộng nhà máy xử lý nước cấp với lưu lượng thiết kế ngày lớn nhất $Q = 0.5\text{ m}^3/\text{s}$ và tải trọng bề mặt thiết kế $\text{SOR} = 32.5\text{ m}^3/\text{m}^2\cdot\text{d}$. (Design the settling tank(s) for the water treatment plant expansion using horizontal-flow rectangular sedimentation basin. The maximum day design flow is 0.5 m3/s. The design overflow rate is 32.5 m3/m2.d.)
- **Dữ kiện**:
  - Lưu lượng thiết kế ngày lớn nhất của nhà máy: $Q_{\text{total}} = 0.5\text{ m}^3/\text{s} = 0.5 \times 86400\text{ s/d} = 43200\text{ m}^3/\text{d}$.
  - Tải trọng bề mặt thiết kế ($\text{SOR}$ hay $v_0$): $\text{SOR} = 32.5\text{ m}^3/\text{m}^2\cdot\text{d}$ ($1.354\text{ m/h} = 3.76 \times 10^{-4}\text{ m/s}$).
  - Số lượng đơn nguyên bể hoạt động song song dự phòng: $N = 2$ bể (theo quy chuẩn kỹ thuật an toàn cấp nước khi súc rửa, bảo dưỡng).
  - Tỷ số chiều dài trên chiều rộng tiêu chuẩn: $L:W = 4:1$ ($L = 4W$).
  - Chiều sâu nước lắng hữu ích: $H = 4.0\text{ m}$ (dải tiêu chuẩn $3.5 - 5.0\text{ m}$).
  - Chiều sâu dự phòng vùng chứa bùn đáy: $H_{\text{sludge}} = 0.8\text{ m}$.
  - Chiều cao an toàn mặt thoáng (freeboard): $H_{\text{freeboard}} = 0.6\text{ m}$.
  - Tải trọng vách tràn máng thu nước thiết kế cho bông phèn: $\text{WLR} = 180.0\text{ m}^3/\text{d}\cdot\text{m}$ (theo dữ liệu khuyến nghị trang 36 slide).
  - Độ nhớt động học của nước ở $20^\circ\text{C}$: $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
  - Gia tốc trọng trường: $g = 9.81\text{ m/s}^2$.
- **Quy tắc áp dụng**:
  - Nguyên tắc phân chia lưu lượng theo đơn nguyên bể làm việc song song:
    $$Q_{\text{basin}} = \frac{Q_{\text{total}}}{N}$$
  - Phương trình xác định diện tích mặt bằng lắng yêu cầu theo lý thuyết Camp:
    $$A_s = \frac{Q_{\text{basin}}}{\text{SOR}}$$
  - Tỷ lệ hình học bể lắng ngang chữ nhật tiêu chuẩn $L/W \ge 4.0$ nhằm triệt tiêu dòng chảy ngắn và vùng chết:
    $$W = \sqrt{\frac{A_s}{4}}, \quad L = 4W$$
  - Thể tích nước công tác và thời gian lưu thủy lực lý thuyết ($t_0$):
    $$V = A_s \cdot H, \quad t_0 = \frac{V}{Q_{\text{basin}}} = \frac{H}{\text{SOR}}$$
    (Tiêu chuẩn TCXDVN 33:2006 và Ten States Standards yêu cầu $t_0$ trong dải $2.0 - 4.0\text{ giờ}$).
  - Tiêu chuẩn kiểm soát chống xới cặn và vận tốc dòng chảy ngang ($v_h$):
    $$v_h = \frac{Q_{\text{basin}}}{A_x} = \frac{Q_{\text{basin}}}{W \cdot H}$$
    Điều kiện chống xới cặn bông phèn: $v_h \le 0.50\text{ m/min} = 8.33\text{ mm/s}$ (hoặc $v_h \le 18\cdot v_0$).
  - Tiêu chuẩn ổn định thủy lực dòng chảy trong bể lắng:
    - Bán kính thủy lực: $R_h = \frac{A_x}{P} = \frac{W \cdot H}{W + 2H}$.
    - Số Reynolds bể: $Re = \frac{v_h \cdot R_h}{\nu} < 20000$ (chảy êm, không hình thành dòng cuộn lớn).
    - Số Froude: $Fr = \frac{v_h^2}{g \cdot R_h} \ge 10^{-6}$ (chống phân tách dòng).
  - Quy tắc thiết kế máng ngón tay thu nước trong (finger launders):
    $$L_{\text{weir}} = \frac{Q_{\text{basin}}}{\text{WLR}}$$
    Bố trí hệ thống máng ngón tay thu nước hai bên thành máng bao phủ tối thiểu $20\% - 33\%$ chiều dài cuối bể.
- **Lời giải**:
  - **Bước 1**: Xác định lưu lượng thiết kế cho từng bể đơn vị.
    - Căn cứ: Lưu lượng ngày lớn nhất $Q_{\text{total}} = 0.5\text{ m}^3/\text{s} = 43200\text{ m}^3/\text{d}$ và lựa chọn cấu hình $N = 2$ bể độc lập làm việc song song.
    - Nhìn vào: Đề bài Example 5-2 trên slide 39 cho $Q = 0.5\text{ m}^3/\text{s}$.
    - Thực hiện:
      $$Q_{\text{basin}} = \frac{43200\text{ m}^3/\text{d}}{2} = 21600\text{ m}^3/\text{d} = 0.25\text{ m}^3/\text{s} = 900\text{ m}^3/\text{h}$$
  - **Bước 2**: Tính diện tích mặt bằng lắng yêu cầu.
    - Căn cứ: Công thức tải trọng bề mặt Camp $A_s = \frac{Q_{\text{basin}}}{\text{SOR}}$ với $\text{SOR} = 32.5\text{ m}^3/\text{m}^2\cdot\text{d}$.
    - Nhìn vào: Đề bài trên slide 39 cho $\text{SOR} = 32.5\text{ m}^3/\text{m}^2\cdot\text{d}$.
    - Thực hiện:
      $$A_{s,\text{req}} = \frac{21600\text{ m}^3/\text{d}}{32.5\text{ m}^3/\text{m}^2\cdot\text{d}} = 664.62\text{ m}^2/\text{bể}$$
      Tổng diện tích mặt bằng yêu cầu cho cả 2 bể:
      $$A_{s,\text{total,req}} = 2 \times 664.62\text{ m}^2 = 1329.23\text{ m}^2$$
  - **Bước 3**: Xác định kích thước mặt bằng bể (Chiều rộng $W$ và Chiều dài $L$).
    - Căn cứ: Tỷ số chuẩn $L:W = 4:1 \implies L = 4W \implies A_s = 4W^2$.
    - Nhìn vào: Diện tích yêu cầu $A_s = 664.62\text{ m}^2$ từ Bước 2.
    - Thực hiện:
      $$W = \sqrt{\frac{664.62}{4}} = \sqrt{166.155} \approx 12.89\text{ m}$$
      - Chọn kích thước chẵn theo mô-đun thi công xây dựng: chọn $W = 13.0\text{ m}$.
      - Chiều dài vùng lắng: $L = 4 \times 13.0\text{ m} = 52.0\text{ m}$.
      - Diện tích mặt bằng thực tế mỗi bể:
        $$A_{s,\text{actual}} = 13.0\text{ m} \times 52.0\text{ m} = 676.0\text{ m}^2$$
      - Tổng diện tích thực tế 2 bể: $A_{s,\text{total,actual}} = 2 \times 676.0 = 1352.0\text{ m}^2$.
      - Tải trọng bề mặt thực tế:
        $$\text{SOR}_{\text{actual}} = \frac{43200\text{ m}^3/\text{d}}{1352.0\text{ m}^2} = 31.95\text{ m}^3/\text{m}^2\cdot\text{d} \le 32.5\text{ m}^3/\text{m}^2\cdot\text{d} \quad (\text{đạt yêu cầu})$$
  - **Bước 4**: Xác định chiều sâu, thể tích và thời gian lưu thủy lực.
    - Căn cứ: Chọn chiều sâu nước công tác $H = 4.0\text{ m}$ (nằm trong dải $3.5 - 5.0\text{ m}$), thể tích $V = A_{s,\text{actual}} \cdot H$, thời gian lưu $t_0 = \frac{V}{Q_{\text{basin}}}$.
    - Nhìn vào: Chiều cao dự phòng bùn đáy $H_{\text{sludge}} = 0.8\text{ m}$ và lưu không an toàn $H_{\text{freeboard}} = 0.6\text{ m}$.
    - Thực hiện:
      - Thể tích nước vùng lắng mỗi bể:
        $$V = 676.0\text{ m}^2 \times 4.0\text{ m} = 2704.0\text{ m}^3$$
      - Thời gian lưu nước thủy lực:
        $$t_0 = \frac{2704.0\text{ m}^3}{0.25\text{ m}^3/\text{s}} = 10816\text{ s} \approx 3.004\text{ h} \approx 3.0\text{ giờ}$$
        (Thỏa mãn tiêu chuẩn kỹ thuật cấp nước từ $2.0$ đến $4.0\text{ giờ}$).
      - Tổng chiều cao tường thành bể:
        $$H_{\text{total}} = H + H_{\text{sludge}} + H_{\text{freeboard}} = 4.0 + 0.8 + 0.6 = 5.4\text{ m}$$
  - **Bước 5**: Kiểm tra vận tốc dòng chảy ngang và điều kiện chống xới cặn.
    - Căn cứ: Diện tích mặt cắt ướt ngang $A_x = W \cdot H$, vận tốc ngang $v_h = \frac{Q_{\text{basin}}}{A_x}$.
    - Nhìn vào: Giới hạn vận tốc chống xới cặn tiêu chuẩn $v_h \le 0.50\text{ m/min}$ ($8.33\text{ mm/s}$).
    - Thực hiện:
      - Mặt cắt ướt: $A_x = 13.0\text{ m} \times 4.0\text{ m} = 52.0\text{ m}^2$.
      - Vận tốc ngang:
        $$v_h = \frac{0.25\text{ m}^3/\text{s}}{52.0\text{ m}^2} = 0.00481\text{ m/s} = 4.81\text{ mm/s} = 0.288\text{ m/min}$$
      - Đánh giá: $v_h = 0.288\text{ m/min} < 0.50\text{ m/min}$. Dòng chảy rất êm dịu, không gây hiện tượng xới bùn đã lắng ở đáy bể.
  - **Bước 6**: Kiểm tra ổn định thủy lực dòng chảy qua số Reynolds ($Re$) và số Froude ($Fr$).
    - Căn cứ: Chu vi ướt $P = W + 2H$, bán kính thủy lực $R_h = \frac{A_x}{P}$, $Re = \frac{v_h \cdot R_h}{\nu}$, $Fr = \frac{v_h^2}{g \cdot R_h}$.
    - Nhìn vào: $P = 13.0 + 2 \times 4.0 = 21.0\text{ m}$, $R_h = \frac{52.0}{21.0} \approx 2.476\text{ m}$, $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$, $g = 9.81\text{ m/s}^2$.
    - Thực hiện:
      $$Re = \frac{0.00481 \times 2.476}{1.004 \times 10^{-6}} \approx 11862 < 20000 \quad (\text{đạt chuẩn ổn định})$$
      $$Fr = \frac{(0.00481)^2}{9.81 \times 2.476} = \frac{2.314 \times 10^{-5}}{24.29} \approx 9.53 \times 10^{-7} \approx 1.0 \times 10^{-6}$$
  - **Bước 7**: Thiết kế máng thu nước trong và vách tràn răng cưa (finger launders).
    - Căn cứ: Tiêu chuẩn tải trọng vách tràn $\text{WLR} = 180.0\text{ m}^3/\text{d}\cdot\text{m}$, tổng chiều dài vách tràn $L_{\text{weir}} = \frac{Q_{\text{basin}}}{\text{WLR}}$.
    - Nhìn vào: Lưu lượng mỗi bể $Q_{\text{basin}} = 21600\text{ m}^3/\text{d}$ và chiều rộng bể $W = 13.0\text{ m}$.
    - Thực hiện:
      - Chiều dài vách tràn yêu cầu:
        $$L_{\text{weir}} = \frac{21600\text{ m}^3/\text{d}}{180.0\text{ m}^3/\text{d}\cdot\text{m}} = 120.0\text{ m}$$
      - Bố trí $m = 4$ máng ngón tay nhánh đặt dọc song song theo chiều dài bể, thu nước tràn qua vách răng cưa ở cả 2 bên mép máng.
      - Khoảng cách tim máng: $S = \frac{W}{m} = \frac{13.0\text{ m}}{4} = 3.25\text{ m} \le 4.0\text{ m}$ (đạt chuẩn thu nước đồng đều).
      - Chiều dài thiết kế của mỗi nhánh máng:
        $$L_{\text{launder}} = \frac{L_{\text{weir}}}{2 \times m} = \frac{120.0}{2 \times 4} = 15.0\text{ m}$$
      - Tỷ lệ bao phủ chiều dài bể lắng:
        $$\frac{L_{\text{launder}}}{L} = \frac{15.0\text{ m}}{52.0\text{ m}} \approx 28.8\%$$
        (Nằm hoàn toàn trong dải tiêu chuẩn từ $20\%$ đến $33\%$ chiều dài cuối bể).
- **Kết quả**:
  - Số lượng bể: $N = 2$ bể lắng ngang chữ nhật làm việc song song.
  - Kích thước mặt bằng mỗi bể: Chiều dài $L = 52.0\text{ m}$, Chiều rộng $W = 13.0\text{ m}$.
  - Chiều sâu công trình: Chiều sâu nước công tác $H = 4.0\text{ m}$ (Tổng chiều cao thành bể $H_{\text{total}} = 5.4\text{ m}$).
  - Diện tích mặt bằng: $A_s = 676.0\text{ m}^2/\text{bể}$ (Tổng diện tích 2 bể $1352.0\text{ m}^2$).
  - Thể tích nước công tác: $V = 2704.0\text{ m}^3/\text{bể}$ (Tổng thể tích 2 bể $5408.0\text{ m}^3$).
  - Thời gian lưu nước thủy lực: $t_0 = 3.0\text{ giờ}$ ($10816\text{ s}$).
  - Vận tốc dòng chảy ngang: $v_h = 4.81\text{ mm/s} = 0.288\text{ m/min}$ ($< 0.50\text{ m/min}$).
  - Thủy lực dòng chảy: $Re = 11862 < 20000$; $Fr \approx 1.0 \times 10^{-6}$.
  - Mạng lưới thu nước: 4 máng ngón tay dọc dài $15.0\text{ m}$ thu nước 2 bên, tổng chiều dài vách tràn $L_{\text{weir}} = 120.0\text{ m}$.
- **Kiểm tra lại**:
  - Tải trọng mặt thực tế: $\text{SOR} = 31.95\text{ m}^3/\text{m}^2\cdot\text{d} < 32.5\text{ m}^3/\text{m}^2\cdot\text{d}$ (an toàn).
  - Tỷ số $L/W = 52.0 / 13.0 = 4.0$ đạt đúng chuẩn tối ưu chống dòng ngắn.
  - Tải trọng vách tràn: $\frac{21600}{120.0} = 180.0\text{ m}^3/\text{d}\cdot\text{m} \le 180.0\text{ m}^3/\text{d}\cdot\text{m}$.
  - Vận tốc lắng thiết kế $v_0 = 0.376\text{ mm/s}$; tỷ số $v_h / v_0 = 4.81 / 0.376 \approx 12.8 < 18$, bảo đảm loại bỏ triệt để cặn lắng mà không bị cuốn trôi.

#### Example 5-3: Design High-Rate Tube Settlers

- **Đề bài**: (WaWE, 10-36) Thiết kế cụm bể lắng sử dụng khối module ống lắng nghiêng tốc độ cao (high-rate settlers) cho dự án mở rộng nhà máy xử lý nước cấp với lưu lượng thiết kế ngày lớn nhất $Q = 0.5\text{ m}^3/\text{s}$, góc nghiêng của ống lắng $\theta = 60^\circ$ và đường kính thủy lực của ống $d_h = 50\text{ mm}$. (Design the settling tank(s) for the water treatment plant expansion using high-rate settlers. The maximum day design flow is 0.5 m3/s. The angle of the settler tubes is 600. The tubes have a hydraulic diameter of 50 mm.)
- **Dữ kiện**:
  - Lưu lượng thiết kế ngày lớn nhất của nhà máy: $Q_{\text{total}} = 0.5\text{ m}^3/\text{s} = 43200\text{ m}^3/\text{d}$.
  - Số lượng đơn nguyên bể hoạt động song song: $N = 2$ bể.
  - Lưu lượng thiết kế mỗi bể: $Q_{\text{basin}} = 21600\text{ m}^3/\text{d} = 0.25\text{ m}^3/\text{s} = 900\text{ m}^3/\text{h}$.
  - Góc nghiêng module ống lắng: $\theta = 60^\circ$ ($\sin 60^\circ = \frac{\sqrt{3}}{2} \approx 0.8660$).
  - Đường kính thủy lực tiết diện vuông của ống: $d_h = w = 50\text{ mm} = 0.05\text{ m}$.
  - Chiều dài tiêu chuẩn của ống lắng: $L_{\text{tube}} = 1.0\text{ m}$.
  - Tỷ số kích thước hình học ống: $L_{\text{tube}} / d_h = 1.0 / 0.05 = 20$.
  - Tải trọng bề mặt thiết kế trên diện tích mặt bằng đặt module ống: $\text{SOR}_{\text{module}} = 150.0\text{ m}^3/\text{m}^2\cdot\text{d}$ ($6.25\text{ m/h} = 1.736 \times 10^{-3}\text{ m/s}$).
  - Chiều rộng bể lựa chọn: $W = 8.0\text{ m}$.
  - Chiều dài vùng phân phối nước vào: $L_{\text{inlet}} = 3.0\text{ m}$.
  - Chiều dài vùng thu nước ra: $L_{\text{outlet}} = 2.0\text{ m}$.
  - Tải trọng vách tràn máng thiết kế: $\text{WLR} = 180.0\text{ m}^3/\text{d}\cdot\text{m}$.
  - Độ nhớt động học của nước ở $20^\circ\text{C}$: $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
  - Gia tốc trọng trường: $g = 9.81\text{ m/s}^2$.
- **Quy tắc áp dụng**:
  - Lý thuyết lắng tầng mỏng cải tiến của Yao (1970) và Hazen:
    - Bố trí các ống nghiêng nhỏ thu hẹp khoảng cách lắng rơi của hạt xuống còn $d_h$, làm tăng diện tích lắng hiệu dụng lên nhiều lần và cho phép tăng tải trọng bề mặt lên $\text{SOR}_{\text{module}} = 120 - 150\text{ m}^3/\text{m}^2\cdot\text{d}$.
  - Phương trình tính diện tích mặt bằng module:
    $$A_{\text{module}} = \frac{Q_{\text{basin}}}{\text{SOR}_{\text{module}}}$$
  - Kích thước hình học khối module:
    - Chiều cao thẳng đứng của khối module: $H_{\text{module}} = L_{\text{tube}} \cdot \sin(\theta) = 1.0 \times \sin 60^\circ \approx 0.866\text{ m} \approx 0.87\text{ m}$.
    - Chiều dài vùng đặt module: $L_{\text{module}} = \frac{A_{\text{module}}}{W}$.
    - Chiều dài tổng cộng bể lắng: $L_{\text{total}} = L_{\text{module}} + L_{\text{inlet}} + L_{\text{outlet}}$.
  - Vận tốc dòng chảy dâng dọc theo trục ống nghiêng $60^\circ$:
    $$v_{\text{tube}} = \frac{v_0}{\sin(\theta)} = \frac{\text{SOR}_{\text{module}}}{\sin(60^\circ)}$$
  - Tiêu chuẩn kiểm tra chế độ chảy tầng trong ống lắng:
    $$Re_{\text{tube}} = \frac{v_{\text{tube}} \cdot d_h}{\nu} \ll 500$$
    (Bảo đảm chế độ chảy tầng tuyệt đối, triệt tiêu hoàn toàn xoáy rối, giúp cặn lắng trượt tự do ngược chiều dòng nước xuống đáy).
  - Phân bổ cao độ công trình theo phương thẳng đứng:
    - Khoang chứa bùn dưới module: $H_{\text{under}} = 1.50\text{ m}$.
    - Chiều cao module ống: $H_{\text{module}} = 0.87\text{ m}$.
    - Lớp nước trong trên module đến đáy máng: $H_{\text{clear}} = 0.83\text{ m}$.
    - Chiều sâu nước công tác: $H_{\text{water}} = 1.50 + 0.87 + 0.83 = 3.20\text{ m}$.
    - Khoảng lưu không an toàn: $H_{\text{freeboard}} = 0.50\text{ m}$.
    - Tổng chiều cao thành bể: $H_{\text{total}} = 3.70\text{ m}$.
  - Thời gian lưu nước thủy lực tổng thể:
    $$t_0 = \frac{V_{\text{basin}}}{Q_{\text{basin}}} = \frac{L_{\text{total}} \cdot W \cdot H_{\text{water}}}{Q_{\text{basin}}}$$
  - Mạng lưới máng ngón tay thu nước tràn phân bố đều:
    $$L_{\text{weir}} = \frac{Q_{\text{basin}}}{\text{WLR}}$$
- **Lời giải**:
  - **Bước 1**: Xác định lưu lượng thiết kế cho từng bể ($N = 2$).
    - Căn cứ: Lưu lượng tổng $Q_{\text{total}} = 0.5\text{ m}^3/\text{s} = 43200\text{ m}^3/\text{d}$ và yêu cầu phân chia $N = 2$ bể song song.
    - Nhìn vào: Đề bài Example 5-3 trên slide 39 cho $Q = 0.5\text{ m}^3/\text{s}$.
    - Thực hiện:
      $$Q_{\text{basin}} = \frac{43200}{2} = 21600\text{ m}^3/\text{d} = 0.25\text{ m}^3/\text{s} = 900\text{ m}^3/\text{h}$$
  - **Bước 2**: Tính diện tích mặt bằng lắp đặt module ống lắng và đánh giá tỷ lệ đất tiết kiệm.
    - Căn cứ: Công thức tính diện tích theo tải trọng bề mặt module $A_{\text{module}} = \frac{Q_{\text{basin}}}{\text{SOR}_{\text{module}}}$ với $\text{SOR}_{\text{module}} = 150.0\text{ m}^3/\text{m}^2\cdot\text{d}$.
    - Nhìn vào: Tải trọng bề mặt module $150.0\text{ m}^3/\text{m}^2\cdot\text{d}$ (gấp 4.6 lần so với bể lắng ngang truyền thống $32.5\text{ m}^3/\text{m}^2\cdot\text{d}$ ở Ví dụ 5-2).
    - Thực hiện:
      $$A_{\text{module}} = \frac{21600\text{ m}^3/\text{d}}{150.0\text{ m}^3/\text{m}^2\cdot\text{d}} = 144.0\text{ m}^2/\text{bể}$$
      Tổng diện tích mặt bằng module của 2 bể:
      $$A_{\text{module,total}} = 2 \times 144.0\text{ m}^2 = 288.0\text{ m}^2$$
      So sánh tiết kiệm diện tích so với bể lắng ngang (Ví dụ 5-2 có $A_{s,\text{total}} = 1352.0\text{ m}^2$):
      $$\Delta A\% = \frac{1352.0 - 288.0}{1352.0} \times 100\% = \frac{1064.0}{1352.0} \times 100\% \approx 78.7\%$$
      Module ống nghiêng giúp tiết kiệm tới $78.7\%$ diện tích mặt bằng chiếm đất của công trình lắng.
  - **Bước 3**: Xác định kích thước mặt bằng bể lắng (Chiều rộng $W$ và Chiều dài $L$).
    - Căn cứ: Chọn chiều rộng bể $W = 8.0\text{ m}$, tính chiều dài vùng đặt module $L_{\text{module}} = \frac{A_{\text{module}}}{W}$, bố trí vùng vào $L_{\text{inlet}} = 3.0\text{ m}$ và vùng ra $L_{\text{outlet}} = 2.0\text{ m}$.
    - Nhìn vào: Diện tích module $A_{\text{module}} = 144.0\text{ m}^2$ từ Bước 2.
    - Thực hiện:
      - Chiều dài vùng module:
        $$L_{\text{module}} = \frac{144.0\text{ m}^2}{8.0\text{ m}} = 18.0\text{ m}$$
      - Chiều dài tổng cộng bể lắng:
        $$L_{\text{total}} = 18.0\text{ m} + 3.0\text{ m} + 2.0\text{ m} = 23.0\text{ m}$$
      - Tỷ số kích thước mặt bằng: $L_{\text{total}} : W = 23.0 : 8.0 = 2.875 : 1$.
  - **Bước 4**: Phân bổ chiều sâu thẳng đứng, xác định thể tích và thời gian lưu.
    - Căn cứ: Góc nghiêng $\theta = 60^\circ$, chiều dài ống $L_{\text{tube}} = 1.0\text{ m}$, chiều cao khối module $H_{\text{module}} = L_{\text{tube}} \cdot \sin(60^\circ) = 0.866\text{ m} \approx 0.87\text{ m}$.
    - Nhìn vào: Cấu trúc 3 khoang thẳng đứng gồm đáy chứa bùn $1.50\text{ m}$, tầng module $0.87\text{ m}$, tầng nước trong $0.83\text{ m}$, lưu không an toàn $0.50\text{ m}$.
    - Thực hiện:
      - Chiều sâu nước công tác:
        $$H_{\text{water}} = 1.50 + 0.87 + 0.83 = 3.20\text{ m}$$
      - Tổng chiều sâu thành bể:
        $$H_{\text{total}} = 3.20 + 0.50 = 3.70\text{ m}$$
      - Thể tích nước hữu ích mỗi bể:
        $$V = L_{\text{total}} \times W \times H_{\text{water}} = 23.0\text{ m} \times 8.0\text{ m} \times 3.20\text{ m} = 588.8\text{ m}^3$$
      - Tổng thể tích nước 2 bể: $2 \times 588.8 = 1177.6\text{ m}^3$ (so với $5408.0\text{ m}^3$ của bể lắng ngang, giảm $78.2\%$ dung tích xây dựng).
      - Thời gian lưu nước thủy lực:
        $$t_0 = \frac{588.8\text{ m}^3}{0.25\text{ m}^3/\text{s}} = 2355.2\text{ s} \approx 39.25\text{ min} \approx 40\text{ phút}$$
        (Thời gian lắng nhanh hơn 4.5 lần so với 180 phút của bể lắng ngang).
  - **Bước 5**: Kiểm tra chế độ thủy động lực học bên trong ống lắng (vận tốc dâng và số Reynolds).
    - Căn cứ: Công thức vận tốc dâng dọc trục ống $v_{\text{tube}} = \frac{v_0}{\sin 60^\circ}$ và số Reynolds trong ống $Re_{\text{tube}} = \frac{v_{\text{tube}} \cdot d_h}{\nu}$.
    - Nhìn vào: Vận tốc bề mặt $v_0 = \frac{150.0\text{ m/d}}{86400\text{ s/d}} \approx 1.736 \times 10^{-3}\text{ m/s} = 1.736\text{ mm/s}$, $d_h = 0.05\text{ m}$, $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
    - Thực hiện:
      $$v_{\text{tube}} = \frac{1.736 \times 10^{-3}\text{ m/s}}{\sin 60^\circ} = \frac{1.736 \times 10^{-3}}{0.8660} \approx 0.00200\text{ m/s} = 2.0\text{ mm/s}$$
      $$Re_{\text{tube}} = \frac{0.00200 \times 0.05}{1.004 \times 10^{-6}} \approx 99.6$$
      Đánh giá: $Re_{\text{tube}} = 99.6 \ll 500$. Dòng chảy trong từng ống lắng nằm hoàn toàn trong vùng chảy tầng tuyệt đối. Hiện tượng xoáy rối bị triệt tiêu hoàn toàn, bảo đảm bông cặn lắng đọng nhanh và trượt êm ái ngược chiều xuống đáy.
  - **Bước 6**: Thiết kế mạng lưới máng ngón tay thu nước trong trên bề mặt khối module.
    - Căn cứ: Tiêu chuẩn tải trọng vách tràn $\text{WLR} = 180.0\text{ m}^3/\text{d}\cdot\text{m}$, tổng chiều dài vách tràn $L_{\text{weir}} = \frac{Q_{\text{basin}}}{\text{WLR}}$.
    - Nhìn vào: Bố trí $m = 4$ máng ngón tay nhánh dọc theo chiều dài bể trên chiều rộng $W = 8.0\text{ m}$.
    - Thực hiện:
      - Chiều dài vách tràn yêu cầu:
        $$L_{\text{weir}} = \frac{21600\text{ m}^3/\text{d}}{180.0\text{ m}^3/\text{d}\cdot\text{m}} = 120.0\text{ m}$$
      - Bố trí 4 máng nhánh thu nước hai bên vách răng cưa.
      - Khoảng cách tim máng: $S = \frac{W}{m} = \frac{8.0\text{ m}}{4} = 2.0\text{ m}$ (phân bố dòng thu cực kỳ đồng đều trên toàn bộ diện tích bề mặt).
      - Chiều dài thiết kế của mỗi máng nhánh:
        $$L_{\text{launder}} = \frac{L_{\text{weir}}}{2 \times m} = \frac{120.0}{2 \times 4} = 15.0\text{ m}$$
      - Chiều dài máng $15.0\text{ m}$ đặt trên vùng module dài $18.0\text{ m}$ thu trọn vẹn nước trong dâng lên từ các ống lắng.
- **Kết quả**:
  - Số lượng bể: $N = 2$ bể lắng tốc độ cao song song.
  - Kích thước mỗi bể: Chiều dài tổng cộng $L_{\text{total}} = 23.0\text{ m}$ (vùng module dài $18.0\text{ m}$), Chiều rộng $W = 8.0\text{ m}$, Mức nước sâu $H_{\text{water}} = 3.20\text{ m}$ (Tổng sâu thành bể $H_{\text{total}} = 3.70\text{ m}$).
  - Diện tích module: $A_{\text{module}} = 144.0\text{ m}^2/\text{bể}$ (Tổng 2 bể $288.0\text{ m}^2$, tiết kiệm $78.7\%$ diện tích chiếm đất so với bể lắng ngang).
  - Thể tích nước công tác: $V = 588.8\text{ m}^3/\text{bể}$ (Tổng 2 bể $1177.6\text{ m}^3$, giảm $78.2\%$ dung tích xây dựng).
  - Thời gian lưu nước: $t_0 = 39.3\text{ phút} \approx 40\text{ phút}$ (rút ngắn $4.5$ lần thời gian lắng).
  - Vận tốc dâng trong ống nghiêng: $v_{\text{tube}} = 2.0\text{ mm/s} = 0.00200\text{ m/s}$.
  - Chế độ thủy lực: $Re_{\text{tube}} = 99.6 \ll 500$ (chảy tầng hoàn hảo).
  - Mạng lưới thu nước: 4 máng ngón tay dài $15.0\text{ m}$ thu nước 2 bên, $L_{\text{weir}} = 120.0\text{ m}$.
- **Kiểm tra lại**:
  - Tải trọng thực tế qua module: $\frac{21600}{144.0} = 150.0\text{ m}^3/\text{m}^2\cdot\text{d}$ đúng bằng giá trị thiết kế.
  - Vận tốc dâng $v_0 = 1.736\text{ mm/s}$ nhỏ hơn vận tốc lắng của bông phèn nhôm sau tạo bông ($v_s \approx 2.0 - 3.5\text{ mm/s}$), bảo đảm cặn được giữ lại trong ống.
  - Chiều dài ống tương đối $L_{\text{tube}} / d_h = 1000\text{ mm} / 50\text{ mm} = 20 > 11$ (thỏa mãn tiêu chuẩn Yao để hạt cặn kịp lắng xuống bản đáy trước khi dòng nước thoát ra khỏi đầu ống).

#### Bảng so sánh kỹ thuật giữa bể lắng ngang và bể lắng ống nghiêng

- Bảng tổng hợp so sánh chỉ tiêu kinh tế - kỹ thuật giữa hai giải pháp thiết kế cho cùng công suất nhà máy $Q = 0.5\text{ m}^3/\text{s}$ ($43200\text{ m}^3/\text{d}$):

| Chỉ tiêu thiết kế | Bể lắng ngang truyền thống (Example 5-2) | Bể lắng ống nghiêng tốc độ cao (Example 5-3) | Mức độ tối ưu hóa |
|---|---|---|---|
| Số lượng đơn nguyên bể ($N$) | $2$ bể hoạt động song song | $2$ bể hoạt động song song | Đảm bảo an toàn dự phòng |
| Tải trọng bề mặt ($\text{SOR}$) | $32.5\text{ m}^3/\text{m}^2\cdot\text{d}\ (1.35\text{ m/h})$ | $150.0\text{ m}^3/\text{m}^2\cdot\text{d}\ (6.25\text{ m/h})$ | Tải trọng tăng gấp $4.6$ lần |
| Kích thước mặt bằng mỗi bể | $L = 52.0\text{ m},\ W = 13.0\text{ m}$ | $L_{\text{total}} = 23.0\text{ m},\ W = 8.0\text{ m}$ | Thu gọn đáng kể chiều dài và chiều rộng |
| Tổng diện tích mặt bằng lắng | **$1352.0\text{ m}^2$** | **$288.0\text{ m}^2$** (diện tích đặt module) | **Tiết kiệm 78.7% diện tích đất** |
| Chiều sâu nước công tác ($H$) | $4.0\text{ m}$ (Tổng sâu thành $5.4\text{ m}$) | $3.2\text{ m}$ (Tổng sâu thành $3.7\text{ m}$) | Giảm chiều sâu đào móng bể $1.7\text{ m}$ |
| Tổng thể tích nước 2 bể ($V$) | $5408.0\text{ m}^3$ | $1177.6\text{ m}^3$ | **Giảm 78.2% dung tích xây thô** |
| Thời gian lưu nước ($t_0$) | **$3.0\text{ giờ}$** ($180\text{ phút}$) | **$39.3\text{ phút}$** ($\approx 40\text{ phút}$) | Thời gian xử lý nhanh hơn $4.5$ lần |
| Số Reynolds dòng chảy ($Re$) | $Re = 11862$ (vùng chuyển tiếp) | $Re_{\text{tube}} = 99.6$ (chảy tầng $\ll 500$) | Module triệt tiêu hoàn toàn xoáy rối |
| Tổng chiều dài vách tràn ($L_{\text{weir}}$) | $120.0\text{ m}$ / bể ($4$ máng $\times 15.0\text{ m}$) | $120.0\text{ m}$ / bể ($4$ máng $\times 15.0\text{ m}$) | Chiều dài tràn răng cưa tương đương |
| Chi phí xây dựng phần thô | Cao do khối lượng bê tông cốt thép lớn | Thấp do giảm $> 70\%$ khối lượng bê tông | Tiết kiệm chi phí đầu tư ban đầu |
| Yêu cầu bảo dưỡng định kỳ | Đơn giản, cào bùn đáy định kỳ | Cần giàn xịt rửa áp lực chống rong rêu bám ống | Kiểm soát vệ sinh module nghiêm ngặt hơn |

## Chương 6: Quá trình Lọc (Filtration)


### 6.1 Tổng quan về quá trình lọc (Overview of Granular Filtration)

* Đặc điểm độ đục và vai trò của quá trình lọc nước:
  * Độ đục của nước sau khi lắng (settled water turbidity) thường dao động trong khoảng từ $1\text{ NTU}$ đến $10\text{ NTU}$ ($1\text{--}10\text{ NTU}$).
  * Quá trình lọc (filtration process) thông thường được sử dụng nhằm làm giảm độ đục của nước lắng xuống mức đạt yêu cầu cấp nước.
  * Quá trình lọc được ứng dụng rộng rãi nhằm loại bỏ các hạt cặn (particles) ra khỏi nguồn nước.
* Định nghĩa và bản chất vật lý của quá trình lọc (definition of filtration):
  * Quá trình lọc là phương pháp phân tách nhằm loại bỏ các hạt cặn ra khỏi một hệ huyền phù (suspension).
  * Huyền phù (suspension) là một hệ hai pha gồm các hạt rắn phân tán lơ lửng trong môi trường chất lỏng (a two-phase system containing particles in a fluid).
  * Quá trình tách cặn được thực hiện bằng cách cho dòng huyền phù đi xuyên qua một môi trường xốp (passage of the suspension through a porous medium).
* Quá trình lọc qua tầng hạt (granular filtration) và nguyên lý lọc theo chiều sâu (depth filters):
  * Lọc qua tầng vật liệu dạng hạt (granular filtration) là quá trình lọc phổ biến nhất trong thực tế xử lý nước cấp.
  * Bể lọc hạt được gọi là bể lọc theo chiều sâu (depth filters).
  * Cơ chế giữ cặn xảy ra đồng thời theo hai cách:
    * Cặn thâm nhập sâu vào các khoảng rỗng bên trong lớp vật liệu lọc (penetrates into the filter).
    * Cặn bị giữ lại trên bề mặt lớp vật liệu lọc (caught on the surface).

* Vị trí công nghệ và vai trò của bể lọc trong dây chuyền xử lý nước cấp đô thị:
  * Bể lọc hạt là rào cản vật lý sau cùng loại bỏ các hạt cặn lơ lửng, hạt keo chưa lắng, vi sinh vật và mầm bệnh trước công đoạn khử trùng.
  * Hiệu quả loại bỏ ký sinh trùng kháng hóa chất khử trùng clo: Quá trình lọc hạt loại bỏ từ \%$ đến {,}9\%$ ( - 3\log$) u nang *Giardia lamblia* (kích thước  - 14\ \mu\text{m}$) và noãn nang *Cryptosporidium parvum* (kích thước  - 5\ \mu\text{m}$).
  * Tiêu chuẩn độ đục nước lọc theo quy chuẩn kỹ thuật quốc gia và EPA: Độ đục dòng ra của từng bể lọc phải đạt $\le 0{,}3\text{ NTU}$ trong tối thiểu \%$ số mẫu đo hàng tháng, và không bao giờ vượt quá {,}0\text{ NTU}$.
  * Chu kỳ vận hành tiêu chuẩn của bể lọc hạt: Bao gồm 3 pha kế tiếp nhau:
    * Pha lọc hữu dụng (effective filtration run): Kéo dài từ \text{ h}$ đến \text{ h}$ tùy thuộc vào tải trọng cặn và tổn thất áp lực cho phép.
    * Pha rửa ngược (backwash phase): Rửa bằng dòng nước ngược kết hợp khí nén trong thời gian  - 20\text{ phút}$ để loại bỏ cặn tích lũy.
    * Pha xả nước lọc đầu (filter-to-waste hoặc ripening period): Xả bỏ dòng nước sau rửa trong  - 15\text{ phút}$ đầu chu kỳ cho đến khi độ đục ổn định $< 0{,}3\text{ NTU}$.
  * Các thông số động học chính chi phối quá trình lọc: Tốc độ lọc bề mặt ($), kích thước hiệu dụng của hạt ({10}$), hệ số đồng nhất ($), độ rỗng tầng lọc ($\varepsilon_0$), và nhiệt độ dòng nước chi phối độ nhớt động học ($\nu$).

#### Bể lọc nhanh hai lớp vật liệu điển hình (Typical dual-media rapid filter)

* Cấu tạo bể lọc nhanh hai lớp vật liệu lọc điển hình (typical dual-media rapid filter) gồm tầng than antraxít (anthracite) ở trên và tầng cát (sand) ở dưới, bố trí phía trên hệ thống thu nước đáy (underdrains):
  - **Hình 1.** Sơ đồ cấu tạo không gian bể lọc nhanh hai lớp
    - <img src="ch06_filtration/assets/fig_01_p2.png" alt="Hình 1" />
    - **Hình này chứng minh điều gì**
      - Thể hiện tương quan độ dày giữa tầng than anthracite và cát, cùng bố cục hai ngăn đối xứng qua mương giữa.
    - **Từ đâu mà thấy được**
      - Mặt cắt đứng bên trái từ trên xuống: máng washwater troughs $\rightarrow$ tầng anthracite dày $\rightarrow$ tầng sand mỏng hơn $\rightarrow$ hệ thống underdrains.
      - Trục mương giữa: kênh trên (upper gullet) đưa nước vào và kênh dưới (lower gullet) thu nước ra.
* Hệ thống máng thu nước rửa lọc (washwater troughs) được bố trí phía trên bề mặt lớp vật liệu lọc để thu gom nước rửa ngược:
  - **Hình 2.** Bề mặt bể lọc và hệ thống máng thu nước rửa
    - <img src="ch06_filtration/assets/fig_02_p2.jpeg" alt="Hình 2" />
    - **Hình này chứng minh điều gì**
      - Cấu trúc máng rửa treo thực tế bố trí song song và vuông góc với trục giữa để thu gom đều nước rửa trên toàn bề mặt bể.
    - **Từ đâu mà thấy được**
      - Nhìn vào lòng bể: các máng dẫn hở đặt song song cách đều nhau vươn ra hai bên từ lối đi trung tâm.
* Kênh phân phối và thu nước (gullet) kết nối các máng rửa để tiếp nhận và xả dòng nước rửa ngược:
  - **Hình 3.** Dòng nước rửa ngược từ máng chảy vào kênh tập trung
    - <img src="ch06_filtration/assets/fig_03_p2.jpeg" alt="Hình 3" />
    - **Hình này chứng minh điều gì**
      - Kênh gullet thu gom toàn bộ dòng xả từ các máng hai bên thành dòng tập trung để thoát ra ngoài.
    - **Từ đâu mà thấy được**
      - Lòng kênh sâu chạy dọc ở giữa hai khoang bể lọc.
      - Dòng nước xối mạnh qua các cửa trổ trên thành kênh từ máng ngang vào rãnh chính.

### 6.2 Cơ sở lý thuyết và Thủy lực lọc (Theoretical Principles & Filtration Hydraulics)

#### 6.2.1 Phân loại bể lọc và Phương thức vận hành (Filter Classifications & Operational Modes)

##### Tiêu chí phân loại bể lọc (Filtration Classification Criteria)
- Phân loại theo loại vật liệu lọc (Filter Media Classification):
  - Bể một lớp vật liệu (Single medium): Cát thạch anh (sand) hoặc than gầy anthracite (coal).
  - Bể hai lớp vật liệu (Dual media): Than anthracite hạt thô kết hợp cát thạch anh hạt mịn (coal plus sand).
  - Bể đa lớp vật liệu (Mixed media): Than anthracite, cát thạch anh và garnet (coal, sand, and garnet).
- Phân loại theo tải trọng thủy lực bề mặt hoặc tốc độ lọc danh định (Hydraulic Loading Rate Classification):
  - Tải trọng thủy lực $v_a$ hoặc $q$ đo bằng $\text{m/h}$ hoặc $\text{m}^3/(\text{m}^2\cdot\text{d})$.
  - Ba phân nhóm vận tốc chính trong công nghệ xử lý nước:
    - Bể lọc cát chậm (Slow Sand Filters - SSF).
    - Bể lọc cát nhanh (Rapid Sand Filters - RSF).
    - Bể lọc tốc độ cao (High-Rate Granular Filters).
  - Tương quan tốc độ lọc:
    - Bể lọc cát chậm có tốc độ lọc thấp hơn từ $50$ đến $100$ lần so với bể lọc cát nhanh ($v_{a,\text{SSF}} = \frac{1}{50}\text{--}\frac{1}{100} v_{a,\text{RSF}}$).

##### Bể lọc cát chậm (Slow Sand Filters - SSF)
- Lịch sử phát triển và mục tiêu công nghệ:
  - Bể lọc cát chậm đưa vào vận hành lần đầu vào những năm 1800 cho cấp nước đô thị.
  - Công trình có chi phí xây dựng và vận hành thấp, đạt hiệu quả xử lý cao đối với nước có độ đục thấp.
- Thông số tải trọng thủy lực và thủy lực dòng chảy:
  - Tải trọng lọc thiết kế duy trì ở mức $3\text{--}8\text{ m}^3/(\text{m}^2\cdot\text{d})$ (tương đương $0.125\text{--}0.333\text{ m/h}$).
  - Nước chảy qua lớp đệm hạt bằng trọng lực ở vận tốc nhỏ, đảm bảo chế độ chảy tầng ổn định.
- Cơ chế giữ cặn và hiện tượng bít tắc bề mặt:
  - Cặn lơ lửng và chất keo lắng đọng tập trung tại tầng mặt sâu $75\text{ mm}$ ($3\text{ inches}$).
  - Màng sinh học (*schmutzdecke*) trên bề mặt hạt cát thực hiện oxy hóa sinh học và giữ hạt cặn mịn.
  - Khi lỗ rỗng trong tầng mặt $75\text{ mm}$ bít nghẽn hoàn toàn, nước không thể tiếp tục chảy qua lớp cát.
- Phương pháp làm sạch và giới hạn vận hành:
  - Làm sạch thủ công bằng cạo lớp cát bề mặt (*scraping*): Hớt bỏ lớp cát mặt dày $10\text{--}20\text{ mm}$, rửa sạch và hoàn trả định kỳ.
  - Bể lọc cát chậm không có hệ thống sục rửa ngược tại chỗ.
  - Giới hạn công nghệ: Cuối thế kỷ 19, nhu cầu nước sạch tăng mạnh để kiểm soát dịch bệnh; diện tích mặt bằng quá lớn của bể lọc cát chậm không đáp ứng quy mô đô thị đông dân.

##### Bể lọc cát nhanh và Bể lọc hai lớp (Rapid Sand Filters & Dual-Media Filters)
- Động lực phát triển bể lọc cát nhanh (Rapid Sand Filters - RSF):
  - Ra đời vào cuối những năm 1800 để đáp ứng lưu lượng lớn trên diện tích xây dựng hạn chế.
  - Cấu tạo lớp vật liệu: Sử dụng lớp cát phân cấp (*graded sand bed*), chọn đường cong cấp phối hạt tối ưu để tăng lưu lượng nước và giữ cặn hạt.
- Cơ chế sục rửa ngược làm sạch tại chỗ (In-place Backwashing):
  - Làm sạch hoàn toàn tại chỗ bằng dòng nước rửa ngược đi từ đáy lên, không cần cạo cát thủ công.
  - Lưu lượng nước rửa ngược ($v_{bw}$) đủ lớn để làm giãn nở tầng sôi lớp cát và cuốn trôi toàn bộ cặn tích tụ.
  - Phân tầng thủy lực tự nhiên sau khi ngừng rửa ngược:
    - Trọng lực làm các hạt cát lắng trở lại đáy bể.
    - Hạt cát thô lớn nhất ($d_{max}$) lắng nhanh nhất xuống đáy, hạt cát mịn nhất ($d_{min}$) lắng chậm nhất nằm lại trên cùng.
    - Hệ quả thủy lực: Tầng mặt có kích thước hạt nhỏ nhất và lỗ rỗng nhỏ nhất, khiến phần lớn cặn bít nghẽn ngay tại mặt trên, gây tổn thất áp lực nhanh.
- Thông số vận hành định mức của bể lọc cát nhanh:
  - Tải trọng thủy lực thiết kế truyền thống: $120\text{ m}^3/(\text{m}^2\cdot\text{d})$ (tương đương $5\text{ m/h}$).
  - Bể lọc cát nhanh là loại công trình phổ biến nhất trong các nhà máy xử lý nước cấp hiện đại.
- Cải tiến bể lọc hai lớp vật liệu (Dual-Media Filters):
  - Phát triển vào đầu những năm 1940 (thời kỳ Chiến tranh Thế giới thứ hai) để khai thác cơ chế lọc theo chiều sâu (*depth filtration*).
  - Khắc phục nhược điểm bít tắc tầng mặt bằng cách đặt hạt lớn nằm trên hạt nhỏ.
  - Cơ chế phân tầng theo tỷ trọng riêng tương đối ($\text{SG}$):
    - Đặt lớp than anthracite hạt thô lên trên lớp cát thạch anh hạt mịn.
    - Than anthracite có tỷ trọng nhẹ ($\text{SG}_{\text{coal}} \approx 1.4\text{--}1.6$), thấp hơn cát thạch anh ($\text{SG}_{\text{sand}} \approx 2.65$).
    - Sau khi rửa ngược, than lắng chậm hơn cát nên tự động định vị ở phía trên, duy trì trật tự lỗ rỗng giảm dần theo chiều dòng chảy.
  - Hiệu quả công nghệ:
    - Bông cặn thô được giữ trong khoảng rỗng lớn của than; cặn mịn đi sâu hơn và bị giữ lại ở lớp cát mịn.
    - Tải trọng thủy lực vận hành đạt tới $480\text{ m}^3/(\text{m}^2\cdot\text{d})$ (tương đương $20\text{ m/h}$), gấp 4 lần bể lọc nhanh thông thường.
- Bằng chứng thực nghiệm cấu tạo và chế độ vận hành:
  - Cấu trúc không gian khối bể lọc nhanh hai lớp:
    - **Hình 4.** Cấu tạo mặt cắt không gian bể lọc nhanh hai lớp vật liệu (Dual-media filter)
      - <img src="ch06_filtration/assets/fig_04_p3.png" alt="Hình 4" />
      - **Hình này chứng minh điều gì**
        - Cấu trúc phân tầng lớp than anthracite đặt trên lớp cát, cùng hệ thống máng thu nước rửa và ống thu đáy.
      - **Từ đâu mà thấy được**
        - Nhãn chỉ rõ Anthracite phía trên Sand, Underdrains ở đáy, Washwater troughs và Upper/Lower gullet.
  - Chế độ dòng chảy lọc xuôi bình thường:
    - **Hình 5.** Bể lọc trọng lực hai ngăn trong chu kỳ vận hành lọc xuôi bình thường
      - <img src="ch06_filtration/assets/fig_05_p3.jpeg" alt="Hình 5" />
      - **Hình này chứng minh điều gì**
        - Trạng thái dòng nước ngập trên bề mặt lớp vật liệu và các máng thu nước rửa trong pha lọc sản xuất.
      - **Từ đâu mà thấy được**
        - Mặt nước tĩnh ngập các máng thu ngang (washwater troughs), dòng nước chảy trọng lực qua lớp đệm hạt.
  - Chế độ sục rửa ngược thủy lực:
    - **Hình 6.** Pha rửa ngược bể lọc với dòng nước xả tràn vào mương thoát trung tâm
      - <img src="ch06_filtration/assets/fig_06_p3.jpeg" alt="Hình 6" />
      - **Hình này chứng minh điều gì**
        - Nước rửa đẩy ngược từ đáy làm giãn nở lớp hạt và cuốn trôi toàn bộ cặn bẩn vào mương thoát.
      - **Từ đâu mà thấy được**
        - Dòng nước rửa chứa đầy bông cặn chảy cuồn cuộn từ các máng ngang tràn qua lỗ xả vào mương chính (gullet).

##### Bể lọc một lớp hạt sâu và Dây chuyền tiền xử lý (Deep-Bed Monomedia & Pretreatment Integration)
- Bể lọc một lớp hạt sâu (Deep-Bed Monomedia Filters):
  - Ra đời vào giữa thập niên 1980 (mid-1980s), sử dụng than anthracite hoặc cát thô đồng nhất có chiều dày lớn ($1.5\text{--}2.0\text{ m}$).
  - Mục tiêu công nghệ: Tăng tải trọng thủy lực đồng thời tạo nước sau lọc có độ đục rất thấp (*lower turbidity*).
  - Tải trọng thủy lực vận hành: Đạt tới $600\text{ m}^3/(\text{m}^2\cdot\text{d})$ (tương đương $25\text{ m/h}$).
- Bảng đối chiếu các loại bể lọc hạt theo đặc tính kỹ thuật:

| Loại Bể Lọc | Thời Điểm Phát Triển | Loại Vật Liệu Lọc | Tải Trọng Thủy Lực ($v_a$) | Cơ Chế Giữ Cặn | Phương Pháp Làm Sạch |
|---|---|---|---|---|---|
| **Lọc cát chậm (SSF)** | Thập niên 1800 | Cát mịn đơn lớp | $3\text{--}8\text{ m}^3/(\text{m}^2\cdot\text{d})$ ($0.125\text{--}0.333\text{ m/h}$) | Bề mặt ($75\text{ mm}$ tầng mặt), màng sinh học | Cạo bỏ lớp cát mặt thủ công (*scraping*) |
| **Lọc cát nhanh (RSF)** | Cuối thập niên 1800 | Cát phân cấp | $120\text{ m}^3/(\text{m}^2\cdot\text{d})$ ($5\text{ m/h}$) | Bề mặt và tầng trên lớp cát mịn | Rửa ngược tại chỗ bằng nước giãn nở tầng sôi |
| **Lọc hai lớp (Dual-Media)** | Đầu thập niên 1940 | Than anthracite + Cát thạch anh | Lên tới $480\text{ m}^3/(\text{m}^2\cdot\text{d})$ ($20\text{ m/h}$) | Theo chiều sâu (*depth filtration*), than thô giữ cặn lớn | Rửa ngược phân tầng tự nhiên theo tỷ trọng |
| **Lọc một lớp sâu (Deep-Bed)** | Giữa thập niên 1980 | Than hoặc cát thô đồng nhất sâu | Lên tới $600\text{ m}^3/(\text{m}^2\cdot\text{d})$ ($25\text{ m/h}$) | Chiều sâu cực đại, dung tích giữ cặn rất lớn | Rửa ngược kết hợp sục khí (*air scour*) |

- Phân loại theo dây chuyền công nghệ tiền xử lý (Pretreatment Classification):
  - Lọc truyền thống (Conventional Filtration):
    - Dây chuyền công nghệ: Châm hóa chất keo tụ $\rightarrow$ Tạo bông phản ứng $\rightarrow$ Bể lắng làm trong (Clarification) $\rightarrow$ Bể lọc hạt.
    - Áp dụng cho nguồn nước thô có độ đục cao và biến động mạnh.
  - Lọc trực tiếp (Direct Filtration):
    - Dây chuyền công nghệ: Châm hóa chất keo tụ $\rightarrow$ Tạo bông phản ứng $\rightarrow$ Bể lọc hạt (bỏ qua bể lắng làm trong).
    - Áp dụng khi nước thô có độ đục thấp hoặc trung bình, tiết kiệm diện tích và chi phí bể lắng.
  - Lọc tiếp xúc / lọc trên đường ống (In-line / Contact Filtration):
    - Dây chuyền công nghệ: Châm hóa chất keo tụ trực tiếp trên đường ống dẫn $\rightarrow$ Bể lọc hạt.
    - Bỏ qua bể tạo bông và bể lắng; quá trình tạo bông diễn ra ngẫu nhiên trên đường ống và trực tiếp trong các khe rỗng của lớp vật liệu lọc.

#### 6.2.2 Đặc tính vật liệu lọc và Tính chất vật lý (Filter Media Characteristics & Physical Properties)

##### 1. Kích thước hạt vật liệu lọc (Grain Size: Effective Size & Uniformity Coefficient)

- Định nghĩa kích thước hiệu dụng (Effective Size - $ES$ hay $d_{10}$):
  - Kích thước hiệu dụng $ES$ là kích thước mắt sàng quy ước mà $10\%$ khối lượng hạt vật liệu lọc mịn hơn hoặc lọt qua sàng ($d_{10}$):
    $$ES = d_{10}$$
  - Đơn vị đo tiêu chuẩn của $d_{10}$ là milimét ($\text{mm}$).
  - Ý nghĩa kỹ thuật: Đại lượng $d_{10}$ đại diện cho nhóm hạt mịn nhất trong lớp lọc, kiểm soát trực tiếp kích thước lỗ rỗng tối thiểu và trở lực dòng chảy ban đầu.
- Định nghĩa hệ số không đồng nhất (Uniformity Coefficient - $UC$ hay $U$):
  - Hệ số không đồng nhất $U$ là tỷ số giữa kích thước mắt sàng cho $60\%$ khối lượng hạt lọt qua ($d_{60}$) và kích thước mắt sàng cho $10\%$ khối lượng hạt lọt qua ($d_{10}$):
    $$U = \frac{d_{60}}{d_{10}}$$
  - Đại lượng $U$ là đại lượng không thứ nguyên (dimensionless).
  - Ý nghĩa kỹ thuật: Giá trị $U$ phản ánh độ đồng đều cấp phối hạt của lớp vật liệu lọc.
  - Giá trị $U = 1.0$ thể hiện tất cả các hạt có cùng kích thước hoàn toàn đồng nhất.
  - Giá trị $U$ càng nhỏ giúp giảm thiểu hiện tượng phân tầng hạt cục bộ và phân bố tổn thất áp lực đồng đều hơn theo chiều sâu.
- Phân bố kích thước hạt trong công trình lọc:
  - Lớp vật liệu lọc được lựa chọn với các dải cấp phối kích thước xác định nhằm tối ưu hóa khả năng dẫn nước và giữ cặn.
  - **Hình 7.** Sơ đồ phân tầng kích thước hạt vật liệu trong cột lọc cát sinh học
    - <img src="ch06_filtration/assets/fig_07_p4.jpeg" alt="Hình 7" />
    - **Hình này chứng minh điều gì**
      - Lớp hạt phân tầng theo kích cỡ: cát mịn ($1 - 0.1\ \text{mm}$), cát thô ($1 - 6\ \text{mm}$) và sỏi đỡ ($6 - 12\ \text{mm}$).
    - **Từ đâu mà thấy được**
      - Nhãn kích thước trên thân cột: Fine Sand $1-0,1\text{mm}$, Coarse sand $1-6\text{mm}$, và Gravel $6-12\text{mm}$.

##### 2. Hình dạng hạt vật liệu lọc (Grain Shape: Sphericity)

- Định nghĩa độ cầu của hạt (Sphericity - $\psi$):
  - Độ cầu $\psi$ là tỷ số giữa diện tích bề mặt của hình cầu có cùng thể tích với hạt ($A_{\text{sphere}}$) và diện tích bề mặt thực tế của hạt ($A_{\text{particle}}$):
    $$\psi = \frac{A_{\text{sphere}}}{A_{\text{particle}}} \quad (\text{với } \forall_{\text{sphere}} = \forall_{\text{particle}})$$
  - Đại lượng $\psi$ là tỷ số không thứ nguyên (dimensionless).
- Giới hạn hình học của độ cầu:
  - Hình cầu có diện tích bề mặt nhỏ nhất trong tất cả các dạng hình học hạt có cùng thể tích.
  - Giá trị độ cầu luôn nhỏ hơn hoặc bằng một ($\psi \le 1.0$). Đối với hạt tự nhiên không tròn tuyệt đối, $\psi < 1.0$.
- Tác động thủy lực và công nghệ của hình dạng hạt:
  - Hạt có độ cầu cao ($\psi \to 1.0$, hạt tròn nhẵn) làm giảm tổn thất áp lực qua lớp lọc sạch và giảm năng lượng rửa ngược.
  - Hạt có độ cầu thấp ($\psi < 0.6$, hạt góc cạnh) làm tăng diện tích bề mặt riêng, tăng khả năng tiếp xúc dính bám cặn bẩn nhưng làm tăng tổn thất cột áp.

##### 3. Các tính chất vật lý của vật liệu lọc (Physical Properties: Hardness, Porosity & Specific Gravity)

- Độ cứng của vật liệu lọc (Hardness):
  - Vai trò kỹ thuật: Độ cứng là chỉ số đo lường khả năng chống mài mòn và hao hụt hạt (abrasion and wear) phát sinh do va chạm giữa các hạt trong quá trình rửa ngược lớp lọc (filter backwashing).
  - Thang đo độ cứng Mohs: Độ cứng được xếp hạng từ cấp $1$ đến cấp $10$ trên thang độ cứng Mohs.
    - Khoáng bột tan (Talc) có độ cứng Mohs bằng $1$ (rất mềm).
    - Kim cương (Diamond) có độ cứng Mohs bằng $10$ (cực kỳ cứng).
  - Tính chống mài mòn của các loại vật liệu:
    - Cát thạch anh (Sand, Mohs $\approx 7.0$) và quặng garnet (Garnet, Mohs $\approx 6.5 - 7.5$) có độ cứng cao, chống mài mòn tốt.
    - Than antraxít (Anthracite coal) và than hoạt tính (Activated carbon) có đặc tính giòn, dễ vỡ vụn (friable), yêu cầu tiêu chuẩn kỹ thuật thiết kế phải quy định giá trị độ cứng tối thiểu chấp nhận được.
    - Quy định kỹ thuật thường yêu cầu than antraxít phải đạt độ cứng Mohs tối thiểu là $2.7$ ($\text{Mohs} \ge 2.7$).
    - Độ cứng than hoạt tính dạng hạt được đánh giá theo tiêu chuẩn ANSI/AWWA B604-96 (AWWA, 1996).
- Độ rỗng của lớp vật liệu lọc (Porosity - $\varepsilon$):
  - Định nghĩa độ rỗng lớp lọc: Độ rỗng của lớp vật liệu lọc tại chỗ (in-place media bed, không phải độ rỗng bên trong hạt riêng lẻ) quyết định trực tiếp tổn thất áp lực và hiệu suất giữ cặn của bể lọc.
  - Phương trình xác định độ rỗng lớp lọc:
    $$\varepsilon = \frac{\forall_v}{\forall_T} = \frac{\forall_T - \forall_M}{\forall_T} = 1 - \frac{\forall_M}{\forall_T}$$
    - $\varepsilon$: Độ rỗng lớp vật liệu lọc (porosity), không thứ nguyên (dimensionless).
    - $\forall_v$: Tổng thể tích các lỗ rỗng giữa các hạt trong lớp lọc (volume of voids), $\text{m}^3$.
    - $\forall_T$: Tổng thể tích biểu kiến của toàn bộ khối lớp lọc (total volume of media bed), $\text{m}^3$.
    - $\forall_M$: Thể tích thực tế của bản thân các hạt vật liệu rắn (volume of media), $\text{m}^3$.
- Tỷ trọng của vật liệu lọc (Specific Gravity - $SG$):
  - Vai trò của tỷ trọng trong thiết kế lọc:
    - Xác định trình tự sắp xếp các tầng vật liệu trong bể lọc nhiều lớp (multimedia filters, dual-media và tri-media filters).
    - Quyết định lưu lượng và vận tốc dòng nước rửa ngược cần thiết để đạt trạng thái sôi lớp lọc (fluidize the bed).
  - Nguyên lý sắp xếp bể lọc nhiều lớp dựa trên tỷ trọng:
    - Vật liệu có tỷ trọng thấp hơn (như than antraxít, $SG \approx 1.50 - 1.75$) được chọn cỡ hạt lớn hơn và tự động nổi lên tầng trên cùng sau khi rửa ngược.
    - Vật liệu có tỷ trọng trung bình (như cát thạch anh, $SG \approx 2.55 - 2.65$) có cỡ hạt trung bình và nằm ở tầng giữa.
    - Vật liệu có tỷ trọng rất cao (như garnet, $SG \approx 3.60 - 4.20$) có cỡ hạt mịn nhất và lắng xuống tầng dưới cùng.
    - Cấu hình này tạo ra sự chuyển tiếp kích thước hạt từ thô xuống mịn theo chiều dòng chảy xuôi, cho phép cặn thâm nhập sâu vào toàn bộ chiều dày lớp lọc.
- Bố trí các tầng hạt trong thân công trình:
  - Tầng cát lọc chính được đặt trên các lớp sỏi đỡ có kích thước hạt tăng dần để ngăn hạt lọt vào hệ thống thu nước đáy.
  - **Hình 8.** Cấu tạo phân lớp hạt vật liệu và tầng sỏi đỡ trong vỏ bể lọc bê tông
    - <img src="ch06_filtration/assets/fig_08_p4.jpeg" alt="Hình 8" />
    - **Hình này chứng minh điều gì**
      - Tầng vật liệu cát lọc (Sand) được bố trí phía trên lớp sỏi phân cách và sỏi thu nước đáy bể.
    - **Từ đâu mà thấy được**
      - Nhãn chỉ dẫn cấu trúc: Sand ở thân trên, Separating Gravel ở giữa và Underdrain Gravel ở đáy thu nước.

##### 4. Bảng thông số kỹ thuật các loại vật liệu lọc phổ biến (Filter Media Properties Matrix)

- Bảng so sánh đặc tính vật lý của bốn loại vật liệu lọc thông dụng trong kỹ thuật xử lý nước:

| Đặc tính kỹ thuật (*Property*) | Than hoạt tính (*Activated carbon*) | Than antraxít (*Anthracite coal*) | Cát thạch anh (*Sand*) | Quặng garnet (*Garnet*) |
|---|---|---|---|---|
| **Kích thước hiệu dụng ($ES$, $\text{mm}$)** | $0.8 - 1.0$ | $0.45 - 0.55$ hoặc $0.8 - 1.2$ | $0.3 - 0.6$ | $0.2 - 0.4$ |
| **Hệ số không đồng nhất ($UC$)** | $1.3 - 2.4$ | $\le 1.65$ hoặc $\le 1.85$ | $1.3 - 1.8$ | $1.3 - 1.7$ |
| **Độ cầu ($\psi$)** | $0.75$ | $0.46 - 0.60$ | $0.70 - 0.80$ | $0.60$ |
| **Độ cứng thang Mohs** | Rất thấp (*Very low*) | $2 - 3$ ($\ge 2.7$) | $7.0$ | $6.5 - 7.5$ |
| **Độ rỗng lớp lọc ($\varepsilon$)** | $0.50$ | $0.50 - 0.60$ | $0.40 - 0.47$ | $0.45 - 0.58$ |
| **Tỷ trọng ($SG$)** | $1.30 - 1.70$ | $1.50 - 1.75$ | $2.55 - 2.65$ | $3.60 - 4.20$ |

- Phân tích tương quan kỹ thuật giữa các loại vật liệu:
  - Tương quan tỷ trọng: Quặng garnet ($SG = 3.60 - 4.20$) > Cát thạch anh ($SG = 2.55 - 2.65$) > Than antraxít ($SG = 1.50 - 1.75$) > Than hoạt tính ($SG = 1.30 - 1.70$).
  - Tương quan kích thước hiệu dụng trong bể lọc ba lớp (tri-media filter): Lớp than antraxít thô nhất ($0.8 - 1.2\ \text{mm}$) ở trên, lớp cát trung gian ($0.45 - 0.55\ \text{mm}$) ở giữa, và lớp garnet mịn nhất ($0.2 - 0.4\ \text{mm}$) ở đáy.
  - Tương quan độ cứng chống mài mòn: Cát thạch anh ($7.0$) và garnet ($6.5 - 7.5$) có khả năng chống mài mòn hiệu quả hơn so với than antraxít ($2 - 3$) và than hoạt tính.
  - Độ rỗng lớp lọc sạch: Than antraxít và than hoạt tính có độ rỗng cao ($\varepsilon \approx 0.50 - 0.60$), tạo không gian chứa cặn lớn hơn so với cát thạch anh ($\varepsilon \approx 0.40 - 0.47$).

##### 5. Đặc tính vật lý và thành phần hóa học của cát lọc (Physical Properties and Chemical Analysis of Sand)

- Đặc tính vật lý điển hình của cát lọc thạch anh (Typical Physical Properties):

| Chỉ tiêu vật lý | Giá trị kỹ thuật |
|---|---|
| **Khoáng vật học (Mineral)** | Thạch anh (*Quartz*) |
| **Độ $\text{pH}$** | Trung tính ($6.9 - 7.0$) |
| **Màu sắc (Color)** | Nâu vàng / Trắng (*Tan / White*) |
| **Độ tròn cạnh (Roundness)** | $\ge 0.6$ ($0.6+$) |
| **Độ cầu (Sphericity)** | $\ge 0.6$ ($0.6+$) |
| **Độ cứng thang Mohs (Hardness)** | $7.0$ |
| **Tỷ trọng (Specific Gravity)** | $2.65$ |
| **Điểm nóng chảy (Melting Point)** | $2800^\circ\text{F} - 3100^\circ\text{F}$ ($\approx 1538^\circ\text{C} - 1704^\circ\text{C}$) |
| **Độ hao hụt khi nung (Loss on Ignition - LOI)** | $0.1\%$ |
| **Khối lượng thể tích rời (Unit Weight)** | $100\ \text{lb/ft}^3$ ($\approx 1602\ \text{kg/m}^3$) |

- Thành phần hóa học điển hình của cát lọc thạch anh (Typical Chemical Analysis):

| Thành phần oxit | Hàm lượng phần trăm theo khối lượng ($\%$) |
|---|---|
| **Dioxit silic ($\text{SiO}_2$ - Silicon Dioxide)** | $99.48\%$ |
| **Oxit nhôm ($\text{Al}_2\text{O}_3$ - Aluminum Oxide)** | $0.21\%$ |
| **Oxit sắt ($\text{Fe}_2\text{O}_3$ - Iron Oxide)** | $0.06\%$ |
| **Dioxit titan ($\text{TiO}_2$ - Titanium Dioxide)** | $< 0.01\%$ |
| **Oxit canxi ($\text{CaO}$ - Calcium Oxide)** | $< 0.01\%$ |
| **Oxit magie ($\text{MgO}$ - Magnesium Oxide)** | $< 0.01\%$ |

- Đánh giá chất lượng và độ bền hóa học của cát lọc:
  - Hàm lượng dioxit silic ($\text{SiO}_2$) đạt $99.48\%$ chứng minh độ tinh khiết khoáng vật rất cao, trơ về mặt hóa học, không bị hòa tan trong môi trường nước cấp có chứa clo khử trùng hay axit yếu.
  - Hàm lượng các oxit tạp chất kim loại ($\text{Fe}_2\text{O}_3$, $\text{Al}_2\text{O}_3$, $\text{CaO}$, $\text{MgO}$) cực kỳ thấp ($< 0.3\%$), bảo đảm cát không làm thôi nhiễm kim loại hay làm biến động độ cứng và độ kiềm của nước sau lọc.
  - Độ hao hụt khi nung $\text{LOI} = 0.1\%$ phản ánh hàm lượng chất hữu cơ và cacbonat liên kết trong cát không đáng kể, đáp ứng đầy đủ các tiêu chuẩn nước uống quốc tế.

#### 6.2.3 Cơ chế giữ cặn trong lớp vật liệu lọc (Particle Removal Mechanisms)

##### 6.2.3.1 Cơ chế sàng cơ học và hình thành bánh cặn bề mặt (Mechanical Straining & Cake Filtration)
- Cơ chế sàng lọc cơ học (Mechanical straining / Screening):
  - Hạt cặn bị giữ lại khi kích thước hạt ($d_p$) lớn hơn kích thước khe hở nhỏ nhất ($d_{\text{pore}}$) giữa các hạt vật liệu lọc ($d_p > d_{\text{pore}}$).
  - Quá trình sàng lọc xảy ra chủ yếu ngay tại mặt thoáng phía trên cùng của lớp vật liệu lọc.
  - Cơ chế này không cho phép cặn xâm nhập sâu vào bên trong các tầng vật liệu bên dưới.
- Ứng dụng chi phối trong bể lọc chậm (Slow sand filters):
  - Sàng lọc cơ học là cơ chế giữ cặn chủ đạo của bể lọc chậm.
  - Bể lọc chậm sử dụng cát mịn ($d_{10} = 0.15\text{--}0.35\text{ mm}$) với tải trọng thủy lực thấp ($q = 0.1\text{--}0.4\text{ m/h}$ tương đương $3\text{--}8\text{ m}^3/(\text{m}^2\cdot\text{d})$).
  - Phần lớn cặn lắng và sinh khối tập trung giữ lại trong phạm vi $75\text{ mm}$ lớp cát trên cùng.
  - **Hình 9.** Cấu tạo và cơ chế lọc màng cặn bề mặt của bể lọc chậm
    - <img src="ch06_filtration/assets/fig_09_p5.jpeg" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Nước chảy qua tầng cát mịn ($0.1\text{--}1\text{ mm}$); cặn giữ lại ở bề mặt theo cơ chế sàng cơ học trước khi nước sạch thu gom qua sỏi đỡ ($6\text{--}12\text{ mm}$) ra ống PVC.
    - **Từ đâu mà thấy được**
      - Dòng nước qua đĩa phân phối vào lớp Fine Sand ($0.1\text{--}1\text{ mm}$); lớp dưới là Coarse sand ($1\text{--}6\text{ mm}$) và Gravel ($6\text{--}12\text{ mm}$); ống PVC dẫn nước trong ra cốc hứng.
- Sự hình thành màng bánh cặn bề mặt (Surface cake formation / Schmutzdecke):
  - Cặn tích tụ liên tục tạo thành một lớp màng bánh cặn xốp phủ kín bề mặt cát.
  - Sự hình thành bánh cặn làm tăng hiệu suất thu giữ các hạt cặn nhỏ tiếp theo do các vi khe rỗng mới trong bánh cặn có kích thước nhỏ hơn khe rỗng ban đầu.
  - Bánh cặn làm tăng nhanh trở lực thủy lực và tổn thất áp lực ($\Delta h$) qua lớp lọc theo thời gian lọc ($t$).
  - Khi tổn thất áp lực đạt ngưỡng giới hạn, người vận hành phải cạo bỏ lớp cát mặt dày $1\text{--}2\text{ cm}$ để phục hồi năng lực thông thủy.

##### 6.2.3.2 Cơ chế lọc sâu trong lớp vật liệu hạt (Depth Filtration Mechanisms)
- Đặc điểm của quá trình lọc theo chiều sâu (Depth filtration in rapid filters):
  - Ứng dụng trong bể lọc nhanh trọng lực và bể lọc áp lực với tốc độ lọc cao ($v_f = 5\text{--}15\text{ m/h}$).
  - Kích thước hạt cặn và bông cặn keo tụ ($d_p = 1\text{--}50\ \mu\text{m}$) nhỏ hơn nhiều so với kích thước khe hở rỗng của tầng lọc ($d_{\text{pore}} \approx 70\text{--}150\ \mu\text{m}$).
  - Cặn phân bố xuyên sâu vào chiều dày của tầng vật liệu lọc thay vì tích tụ trên bề mặt.
- Quá trình thu giữ hai giai đoạn (Two-step particle removal process):
  - Giai đoạn 1: Quá trình vận chuyển (Transport step) đưa hạt cặn từ dòng chất lưu chính tiếp cận gần bề mặt hạt vật liệu lọc (collector).
  - Giai đoạn 2: Quá trình dính bám (Attachment step) liên kết hạt cặn cố định vào bề mặt hạt vật liệu hoặc lớp cặn đã bám trước đó.
- Bốn cơ chế vận chuyển vật lý chính trong lọc sâu:
  - Lắng trọng lực (Sedimentation):
    - Hạt cặn có khối lượng riêng lớn hơn khối lượng riêng của nước ($\rho_p > \rho_w$).
    - Trọng lực làm hạt chệch khỏi đường dòng chảy và lắng đọng lên bề mặt trên của hạt vật liệu lọc.
  - Tiếp xúc chặn giữ (Interception):
    - Hạt cặn chuyển động dọc theo đường dòng chảy thủy động lực học quanh hạt vật liệu lọc.
    - Khi khoảng cách giữa tâm hạt và bề mặt vật liệu lọc nhỏ hơn bán kính hạt cặn ($r_p \le d_p / 2$), hạt va chạm tiếp xúc và bị chặn lại.
  - Keo tụ tạo bông trong khe rỗng (Flocculation in pore spaces):
    - Građien vận tốc ($G$) trong các khe rỗng hẹp thúc đẩy các hạt cặn nhỏ va chạm với nhau.
    - Các hạt kết tụ thành bông cặn lớn hơn, làm tăng xác suất bị giữ lại bởi cơ chế lắng và chặn giữ.
  - Khuếch tán Brown (Brownian diffusion):
    - Tác động lên các hạt cặn keo siêu mịn có đường kính $d_p < 1\ \mu\text{m}$.
    - Chuyển động nhiệt ngẫu nhiên làm hạt dịch chuyển ngang qua các đường dòng và va chạm vào bề mặt vật liệu lọc.
- Cơ chế dính bám hóa lý (Physicochemical attachment mechanism):
  - Lực dính bám điều khiển bởi lực hút phân tử Van der Waals và tương tác tĩnh điện hai lớp (lực đẩy hoặc lực hút tĩnh điện).
  - Bề mặt hạt cát và hạt cặn tự nhiên trong nước thường mang điện tích âm, tạo lực đẩy tĩnh điện ngăn cản sự dính bám.
  - Tiền xử lý keo tụ (Coagulation pretreatment) bằng chất keo tụ đóng vai trò quyết định để trung hòa điện tích bề mặt, giảm thế điện động Zeta ($\zeta$), cho phép hạt cặn dính kết bền vững.

##### 6.2.3.3 Các mô hình lý thuyết lọc hạt (Particle Filtration Theoretical Models)
- Hai cách tiếp cận mô hình hóa lý thuyết lọc cơ bản:
  - Tiếp cận vi mô (Microscopic approach): Phân tích động học thu giữ hạt ở cấp độ một hạt vật liệu đơn lẻ (Single collector theory).
  - Tiếp cận vĩ mô (Macroscopic / Phenomenological approach): Phân tích cân bằng khối lượng và suy giảm nồng độ cặn theo chiều sâu toàn bộ lớp lọc liên tục.
- Mô hình tiếp cận vi mô (Microscopic / Single Collector Theory):
  - Hiệu suất thu giữ của một hạt lọc đơn hình cầu ($\eta$) bằng tổng hiệu suất của các cơ chế vận chuyển độc lập:
    $$\eta = \eta_I + \eta_G + \eta_D$$
    - $\eta$: Hiệu suất thu giữ không thứ nguyên của một hạt vật liệu lọc đơn lẻ.
    - $\eta_I$: Hiệu suất thành phần do cơ chế tiếp xúc chặn giữ (Interception), $\eta_I \propto (d_p / d_c)^2$.
    - $\eta_G$: Hiệu suất thành phần do cơ chế lắng trọng lực (Sedimentation), $\eta_G \propto v_s / v_0$.
    - $\eta_D$: Hiệu suất thành phần do cơ chế khuếch tán Brown (Diffusion), $\eta_D \propto Pe^{-2/3}$.
    - $d_p$: Đường kính hạt cặn, $\text{m}$.
    - $d_c$: Đường kính hạt vật liệu lọc (collector diameter), $\text{m}$.
    - $v_s$: Vận tốc lắng trọng lực của hạt cặn, $\text{m/s}$.
    - $v_0$: Vận tốc lọc bề mặt tiếp cận, $\text{m/s}$.
    - $Pe$: Chuẩn số Peclet mô tả tỷ số giữa đối lưu và khuếch tán, không thứ nguyên.
  - Hệ số va chạm dính bám hiệu dụng ($\alpha$ - Collision attachment efficiency):
    - Xác suất một hạt cặn va chạm dính bám thành công vào bề mặt collector ($\alpha \in [0, 1]$).
    - Phụ thuộc vào tính chất hóa học của nước và hiệu quả keo tụ trung hòa điện tích.
- Mô hình tiếp cận vĩ mô (Macroscopic / Phenomenological Iwasaki Model):
  - Phương trình vi phân cơ bản của Iwasaki (1937) mô tả tốc độ suy giảm nồng độ cặn lơ lửng ($C$) theo chiều sâu lớp lọc ($z$):
    $$-\frac{\partial C}{\partial z} = \lambda C$$
    - $C$: Nồng độ hạt cặn lơ lửng tại độ sâu $z$, $\text{mg/L}$ hoặc $\text{hạt/m}^3$.
    - $z$: Chiều sâu lớp vật liệu lọc tính từ bề mặt lớp cát, $\text{m}$.
    - $\lambda$: Hệ số lọc (Filtration coefficient), $\text{m}^{-1}$.
  - Nghiệm tích phân cho tầng lọc sạch ban đầu khi $\lambda = \lambda_0 = \text{const}$:
    $$C(z) = C_0 \exp(-\lambda_0 z)$$
    - $C_0$: Nồng độ hạt cặn tại cửa vào lớp vật liệu lọc ($z = 0$), $\text{mg/L}$.
    - $\lambda_0$: Hệ số lọc của tầng vật liệu sạch ban đầu, $\text{m}^{-1}$.
  - Động học biến thiên của hệ số lọc $\lambda$ theo lượng cặn tích lũy ($\sigma$ - Specific deposit):
    - Giai đoạn trưởng thành (Filter ripening): Lượng cặn ban đầu dính bám làm tăng diện tích bề mặt tiếp xúc, khiến $\lambda$ tăng tạm thời ($\lambda > \lambda_0$).
    - Giai đoạn tắc nghẽn và đột xuyên (Clogging & Breakthrough): Khe rỗng bị thu hẹp, vận tốc dòng cục bộ trong lỗ rỗng tăng cao gây lực cắt thủy động xé cặn rời khỏi bề mặt, khiến $\lambda$ giảm nhanh và cặn trôi xuyên qua đáy lớp lọc.

#### 6.2.4 Thủy lực lớp lọc sạch và Mô hình tổn thất áp lực Rose (Clean Bed Hydraulics & Headloss)

##### Bốn vấn đề thủy lực cốt lõi trong thiết kế bể lọc (Core Filter Hydraulics Issues)
- Bốn bài toán thủy lực nền tảng cần xác định trong thiết kế hệ thống bể lọc hạt:
  - (1) Tổn thất áp lực qua tầng vật liệu lọc sạch ban đầu ($h_L$, clean bed headloss).
  - (2) Tổn thất áp lực gia tăng do sự tích tụ cặn bẩn trong tầng lọc theo thời gian ($h_{L,\text{clog}}$, clogging headloss).
  - (3) Chiều sâu giãn nở của tầng vật liệu ở trạng thái sôi trong quá trình rửa ngược ($D_e$, bed fluidization depth).
  - (4) Tổn thất áp lực cần thiết để làm giãn nở toàn bộ tầng lọc khi rửa ngược ($h_{Le}$, bed expansion headloss).
- Vai trò kỹ thuật và giới hạn của các phương trình thủy lực lọc sạch:
  - Các phương trình thủy lực chỉ mô tả chính xác trạng thái ban đầu khi vật liệu chưa bám dính hạt cặn.
  - Các công thức cho phép kỹ sư đánh giá định lượng tác động của các biến số thiết kế lên tổn thất năng lượng ban đầu.
  - Tổn thất áp lực lớp lọc sạch là ngưỡng tổn thất nhỏ nhất trong toàn bộ chu kỳ vận hành của bể lọc.

##### Mô hình tổn thất áp lực Rose cho lớp lọc sạch (Rose Clean Bed Headloss Equation)
- Giả thuyết nền tảng của mô hình Rose (Rose, 1945):
  - Dòng nước sạch chảy qua tầng cát lọc đã phân tầng thủy lực hoàn toàn sau rửa ngược (stratified sand bed).
  - Độ xốp của lớp vật liệu được giả định là phân bố đồng nhất dọc theo toàn bộ chiều sâu tầng lọc ($\varepsilon = \text{const}$).
- Dạng tổng quát của phương trình Rose:
  $$h_L = \frac{1.067 \, v_a^2 \, D}{\varphi \, g \, \varepsilon^4} \sum_{i=1}^n \frac{C_{D,i} \, f_i}{d_{g,i}}$$
  - $h_L$: Tổn thất áp lực ma sát qua tầng lọc sạch (frictional headloss through clean bed), đơn vị $\text{m}$.
  - $v_a$: Vận tốc tiếp cận bề mặt hay tốc độ tải trọng lọc (approach velocity / filtration rate / hydraulic loading rate), đơn vị $\text{m/s}$ hoặc $\text{m}^3/(\text{m}^2\cdot\text{s})$.
  - $D$: Chiều dày tổng cộng của tầng vật liệu lọc (depth of filter bed), đơn vị $\text{m}$.
  - $\varphi$: Hệ số hình dạng của hạt vật liệu (shape factor / sphericity), không thứ nguyên ($0 < \varphi \le 1.0$).
  - $g$: Gia tốc trọng trường chuẩn (acceleration due to gravity), $g = 9.81\text{ m/s}^2$.
  - $\varepsilon$: Độ xốp cố định của tầng lọc (bed porosity), không thứ nguyên.
  - $C_{D,i}$: Hệ số lực cản thủy động Newton của phân đoạn hạt thứ $i$ (drag coefficient), không thứ nguyên.
  - $f_i$: Phân số khối lượng hạt thuộc phân đoạn kích thước thứ $i$ (mass fraction), không thứ nguyên ($\sum f_i = 1.0$).
  - $d_{g,i}$: Đường kính trung bình nhân của hạt thuộc phân đoạn rây thứ $i$ (geometric mean diameter), đơn vị $\text{m}$.
- Công thức tính đường kính trung bình nhân $d_g$ giữa hai cỡ rây kế tiếp:
  $$d_g = \sqrt{d_1 \cdot d_2} = (d_1 \cdot d_2)^{0.5}$$
  - $d_1$: Kích thước lỗ mở của mắt rây chặn trên (diameter of upper sieve opening), đơn vị $\text{mm}$ hoặc $\text{m}$.
  - $d_2$: Kích thước lỗ mở của mắt rây chặn dưới (diameter of lower sieve opening), đơn vị $\text{mm}$ hoặc $\text{m}$.
  - Trung bình nhân phản ánh chính xác phân bố diện tích bề mặt riêng của các hạt bị giữ lại giữa hai rây.

##### Hệ số cản Newton CD theo từng chế độ dòng chảy (Piecewise Drag Coefficient Formulations)
- Chuẩn số Reynolds của hạt ($Re$):
  - Trạng thái thủy động lực học quanh hạt cát được xác định thông qua chuẩn số Reynolds:
    $$Re = \frac{\varphi \, v_a \, d_g}{\nu} = \frac{\varphi \, \rho \, v_a \, d_g}{\mu}$$
    - $\nu$: Độ nhớt động học của nước (kinematic viscosity), đơn vị $\text{m}^2/\text{s}$.
    - $\mu$: Độ nhớt động lực học tuyệt đối của nước (dynamic viscosity), đơn vị $\text{Pa}\cdot\text{s}$.
    - $\rho$: Khối lượng riêng của nước (water density), đơn vị $\text{kg/m}^3$.
- Phương trình thực nghiệm toàn dải của Rose:
  - Rose (1945) đề xuất phương trình liên tục cho hệ số cản $C_D$ trong phạm vi $Re < 10^4$:
    $$C_D = \frac{24}{Re} + \frac{3}{\sqrt{Re}} + 0.34$$
    - Số hạng $\frac{24}{Re}$: Lực cản ma sát nhớt thuần túy theo định luật Stokes (chi phối chế độ chảy tầng).
    - Số hạng $\frac{3}{\sqrt{Re}}$: Hiệu chỉnh thực nghiệm cho lực cản vùng dòng chảy chuyển tiếp.
    - Hằng số $0.34$: Lực cản quán tính và áp suất hình dáng (chi phối vùng chảy rối).
- Hệ phương trình hệ số cản từng khúc (Piecewise drag coefficient equations):
  - Chế độ chảy tầng (Laminar flow, $Re < 1.0$ hoặc $Re < 1.9$):
    $$C_D = \frac{24}{Re}$$
    - Ma sát nhớt phân tử chiếm ưu thế tuyệt đối. Lực quán tính không đáng kể.
  - Chế độ chảy chuyển tiếp (Transitional flow, $1.9 \le Re \le 500$):
    $$C_D = \frac{18.5}{Re^{0.6}}$$
    - Cả lực ma sát nhớt và lực quán tính đều tác động đồng thời lên dòng bao quanh hạt.
  - Chế độ chảy rối hoàn toàn (Fully turbulent flow, $500 < Re < 10^4$):
    $$C_D \approx 0.40 \text{--} 0.44$$
    - Hệ số cản $C_D$ đạt giá trị hằng số, độc lập với chuẩn số Reynolds.

##### Các mô hình thủy lực bổ trợ: Carmen-Kozeny và Fair-Hatch (Carmen-Kozeny & Fair-Hatch Equations)
- Mô hình Carman-Kozeny cho môi trường xốp (Carman-Kozeny Equation):
  - Mô hình giả định các khe rỗng trong tầng hạt tương đương chùm ống mao dẫn quanh co.
  - Trong điều kiện dòng chảy tầng ($Re < 2.0$), phương trình tổn thất áp lực có dạng:
    $$\frac{h_L}{D} = \frac{k_{KC} \, \mu}{\rho \, g} \cdot \frac{(1 - \varepsilon)^2}{\varepsilon^3} \cdot S_v^2 \cdot v_a$$
    - $k_{KC}$: Hằng số Kozeny-Carman thực nghiệm, $k_{KC} \approx 5.0$.
    - $S_v$: Diện tích bề mặt riêng trên một đơn vị thể tích hạt rắn ($S_v = \frac{6}{\varphi \cdot d_{\text{eq}}}$), đơn vị $\text{m}^{-1}$.
  - Khai triển phương trình Carman-Kozeny cho hạt có hệ số hình dạng $\varphi$:
    $$\frac{h_L}{D} = \frac{180 \, \nu}{g} \cdot \frac{(1 - \varepsilon)^2}{\varepsilon^3} \cdot \frac{v_a}{(\varphi \, d_{\text{eq}})^2}$$
  - Mở rộng cho lớp cát phân tầng gồm nhiều phân đoạn kích thước hạt:
    $$\frac{h_L}{D} = \frac{180 \, \nu}{g} \cdot \frac{(1 - \varepsilon)^2}{\varepsilon^3} \cdot \frac{v_a}{\varphi^2} \sum_{i=1}^n \frac{f_i}{d_{g,i}^2}$$
  - Phương trình Ergun tổng quát (Ergun, 1952) bổ sung thành phần lực cản quán tính:
    $$\frac{h_L}{D} = 150 \frac{\nu}{g} \frac{(1 - \varepsilon)^2}{\varepsilon^3} \frac{v_a}{(\varphi \, d)^2} + 1.75 \frac{1}{g} \frac{(1 - \varepsilon)}{\varepsilon^3} \frac{v_a^2}{\varphi \, d}$$
    - Số hạng tuyến tính theo $v_a$ đại diện cho ma sát nhớt, chiếm trên 90% tổn thất trong quá trình lọc nước sạch thông thường.
    - Số hạng bậc hai theo $v_a^2$ đại diện cho tổn thất động năng, chỉ chiếm tỷ trọng đáng kể khi lọc siêu cao tải hoặc khi rửa ngược.
- Mô hình Fair-Hatch cho tầng lọc hạt (Fair-Hatch Equation, 1933):
  - Phương trình Fair-Hatch xây dựng trên cơ sở phân tích thứ nguyên dòng chảy qua môi trường xốp:
    $$h_L = \frac{k_{FH} \, \nu}{g} \cdot \left[ \frac{(1 - \varepsilon)^2}{\varepsilon^3} \right] \cdot \left( \frac{\alpha}{100} \right)^2 \cdot v_a \cdot D \left[ \sum_{i=1}^n \frac{f_i}{d_{g,i}} \right]^2$$
    - $k_{FH}$: Hằng số lọc Fair-Hatch thực nghiệm ($k_{FH} \approx 5.0$).
    - $\alpha$: Hệ số diện tích bề mặt hạt ($\alpha = \frac{60}{\varphi}$).
  - Khi biểu diễn trực tiếp qua hệ số hình dạng hạt $\varphi$:
    $$h_L = \frac{k}{g} \cdot \nu \cdot \frac{(1 - \varepsilon)^2}{\varepsilon^3} \cdot \frac{v_a \, D}{\varphi^2} \sum_{i=1}^n \frac{f_i}{d_{g,i}^2}$$
  - So sánh giữa các mô hình thủy lực:
    - Mô hình Carman-Kozeny và Fair-Hatch nhấn mạnh dòng chảy tầng với tổn thất tỷ lệ bậc nhất với vận tốc lọc ($h_L \propto v_a$) và tỷ lệ nghịch với bình phương đường kính hạt ($h_L \propto 1/d^2$).
    - Mô hình Rose bao hàm số hạng vận tốc bậc hai ($h_L \propto v_a^2$) kết hợp hệ số cản $C_D$, cho phép phản ánh chính xác cả vùng chảy tầng lẫn vùng chảy chuyển tiếp.

##### Mối quan hệ độ nhạy và các biến số thiết kế (Parametric Sensitivity & Design Variables)
- Ba quan hệ tỷ lệ then chốt từ phương trình Rose:
  - Tổn thất áp lực tỷ lệ thuận với bình phương vận tốc lọc ($h_L \propto v_a^2$):
    - Tải trọng lọc thường đo bằng $\text{m}^3/(\text{m}^2\cdot\text{d})$ hoặc $\text{m/h}$.
    - Sự gia tăng nhỏ của vận tốc lọc sẽ bị khuếch đại thành mức tăng rất lớn của tổn thất áp lực.
  - Tổn thất áp lực tỷ lệ nghịch với đường kính hạt ($h_L \propto 1/d_g$):
    - Các phân đoạn hạt cát mịn có giá trị $d_g$ nhỏ nhất sẽ tạo ra phần lớn tổn thất cột nước ma sát.
  - Tổn thất áp lực tỷ lệ nghịch với lũy thừa bậc bốn của độ xốp ($h_L \propto 1/\varepsilon^4$):
    - Độ xốp của lớp vật liệu giữ vai trò chi phối áp đảo lên độ lớn của tổn thất áp lực.
    - Giảm nhẹ độ xốp dẫn đến mức gia tăng đột biến của tổn thất áp lực qua lớp lọc.
- Điều khiển tổn thất áp lực dưới góc độ thiết kế kỹ thuật:
  - Điều chỉnh vận tốc lọc ($v_a$):
    - Với lưu lượng thiết kế $Q$ đã định, kỹ sư điều chỉnh $v_a$ thông qua diện tích mặt bằng bể lọc ($A = Q / v_a$).
  - Quy định cấp phối cỡ hạt cát:
    - Cấp phối được đặc trưng bởi kích thước hiệu dụng ($d_{10}$) và hệ số đồng nhất ($U_c = d_{60}/d_{10}$).
    - Khống chế và giới hạn hàm lượng hạt mịn (fines) trong cấp phối để triệt tiêu nguyên nhân chính gây tổn thất áp lực ban đầu quá cao.
  - Giới hạn kiểm soát đối với độ xốp cát ($\varepsilon$):
    - Độ xốp phụ thuộc vào hình dạng hạt tự nhiên và cách sắp xếp lắng đọng cơ học.
    - Kỹ sư thiết kế không thể tùy ý thay đổi độ xốp vì khoảng dao động thực tế của cát thạch anh rất hẹp ($\varepsilon \approx 0.40 \text{--} 0.47$).
- Yếu tố gây nhiễu và sai số mô hình (Confounding factors):
  - Tất cả các phương trình lý thuyết đều giả định độ xốp $\varepsilon$ không đổi theo chiều sâu tầng lọc.
  - Trong thực tế sau rửa ngược, hiện tượng phân tầng thủy lực khiến độ xốp thay đổi liên tục theo chiều sâu. Tầng cát mịn ở trên có độ xốp khác biệt với tầng cát thô ở đáy.

##### Động học tắc nghẽn và tổn thất áp lực giới hạn (Filter Clogging Kinetics & Terminal Headloss)
- Tính chất cực tiểu của tổn thất áp lực lọc sạch:
  - Giá trị tổn thất áp lực tính theo phương trình Rose hay Carman-Kozeny chỉ đại diện cho tổn thất nhỏ nhất có thể đạt được (minimum expected headloss).
  - Khi cặn bẩn bám dính vào bề mặt hạt và khe rỗng, diện tích dòng chảy co hẹp, làm tổn thất áp lực tăng liên tục theo thời gian lọc.
- Giới hạn của mô hình giải tích lý thuyết:
  - Không tồn tại phương trình giải tích thuần lý thuyết nào dự báo chính xác tiến trình tăng áp lực khi tầng lọc bị tắc nghẽn nếu không có dữ liệu thực nghiệm.
  - Cần số liệu từ mô hình thử nghiệm pilot (pilot plant data) hoặc từ công trình thực tế quy mô lớn (full-scale plant data) để hiệu chỉnh động học tích lũy cặn.
- Mô hình hiện tượng luận vĩ mô (Macroscopic / Phenomenological models):
  - Cung cấp công cụ toán học dựa trên số liệu thực nghiệm pilot để ước lượng thời gian đạt tổn thất áp lực giới hạn ($t_{\text{term}}$).
- Cơ sở xác định tổn thất áp lực giới hạn (Terminal headloss selection):
  - Áp lực tổn thất giới hạn được chọn dựa trên kinh nghiệm vận hành thực tế (engineering experience).
  - Cột áp giới hạn phải phù hợp với trắc dọc thủy lực của toàn bộ nhà máy xử lý nước (hydraulic profile of the treatment plant) để tránh làm gián đoạn dòng chảy tự chảy hoặc gây tràn bể.

#### 6.2.5 Thủy lực rửa ngược và Động học giãn nở lớp lọc (Backwashing Hydraulics & Bed Fluidization)

##### 6.2.5.1 Mục tiêu kỹ thuật và Hiện tượng thủy lực của quá trình rửa ngược
- **Mục đích công nghệ của quá trình rửa ngược (Backwash Technology Purpose)**:
  - Rửa ngược loại bỏ toàn bộ cặn lắng tích tụ trong các lỗ rỗng sau chu kỳ lọc.
  - Quá trình hoàn nguyên độ thấm ban đầu và đưa tổn thất áp lực về mức lớp lọc sạch ($h_0 \approx 0{,}3 - 0{,}6\text{ m}$).
  - Dòng nước sạch áp lực đi từ hệ thống thu nước đáy (underdrain) dâng ngược từ dưới lên qua lớp sỏi đỡ và lớp vật liệu lọc.
  - Vận tốc dòng rửa ngược ($v_b$) lớn gấp nhiều lần vận tốc lọc thông thường ($v_b \approx 4 - 10 \cdot v_a$, tương đương $25 - 60\text{ m/h}$).
- **Cơ chế phân tách cặn và tương tác hạt (Shear Detachment & Particle Interaction)**:
  - Lực cản nhớt (viscous drag) và gradien vận tốc dòng nước tạo lực cắt bề mặt (fluid shear stress) bóc tách màng cặn dính bám.
  - Hiện tượng va chạm ma sát giữa các hạt vật liệu lọc (inter-particle abrasion) trong trạng thái chuyển động lỏng hóa hỗ trợ nghiền vụn các bông cặn lớn.
  - Khi rửa ngược chỉ bằng nước đơn thuần, lực cắt thủy lực giữ vai trò chủ đạo vì nồng độ hạt giảm khi lớp lọc giãn nở.
- **Tầm quan trọng của chiều sâu lớp lọc giãn nở ($D_e$) trong thiết kế hình học**:
  - Tính toán độ giãn nở lớp lọc cung cấp cơ sở kỹ thuật trực tiếp để định vị cao trình máng thu nước rửa ngược (backwash troughs).
  - Đáy máng thu nước rửa phải đặt cao hơn đỉnh lớp lọc giãn nở để ngăn chặn hoàn toàn hiện tượng cuốn trôi hạt lọc (media washout/carryover).
  - Đáy máng thu không đặt quá cao để tránh tăng chiều cao dự phòng không cần thiết của thành bể và tránh lãng phí dung tích nước rửa ngược.

##### 6.2.5.2 Cân bằng lực trọng trường hiệu dụng và Tổn thất áp lực qua lớp lọc giãn nở
- **Cân bằng lực trong trạng thái tầng sôi hoàn toàn (Fluidized Bed Force Balance)**:
  - Khi lớp lọc giãn nở hoàn toàn, toàn bộ trọng lượng chìm của hạt cân bằng với lực nâng thủy lực do chênh áp dòng nước gây ra.
  - Lực trọng trường hiệu dụng (buoyant gravitational force) của toàn bộ lớp lọc giãn nở ($F_g$):
    $$F_g = m \cdot g = (\rho_s - \rho)(1 - \varepsilon_e)(a)(D_e)(g)$$
  - Các thông số trong phương trình cân bằng lực:
    - $F_g$: Lực trọng trường hiệu dụng của lớp lọc giãn nở ($\text{N}$).
    - $m$: Khối lượng hiệu dụng (khối lượng chìm) của toàn bộ khối hạt vật liệu lọc trong môi trường nước ($\text{kg}$).
    - $g$: Gia tốc trọng trường chuẩn ($g = 9{,}81\text{ m/s}^2$).
    - $\rho_s$: Khối lượng riêng của hạt vật liệu lọc ($\text{kg/m}^3$), ví dụ cát thạch anh có $\rho_s \approx 2650\text{ kg/m}^3$, than antraxít có $\rho_s \approx 1400 - 1650\text{ kg/m}^3$, quặng garnet có $\rho_s \approx 3800 - 4200\text{ kg/m}^3$.
    - $\rho$: Khối lượng riêng của nước ở nhiệt độ tính toán ($\text{kg/m}^3$, tại $20^\circ\text{C}$ thì $\rho \approx 998{,}2\text{ kg/m}^3$).
    - $\varepsilon_e$: Độ rỗng của lớp lọc ở trạng thái giãn nở (expanded bed porosity, không thứ nguyên).
    - $a$: Diện tích mặt bằng của lớp lọc ($\text{m}^2$).
    - $D_e$: Chiều dày của lớp lọc ở trạng thái giãn nở (depth of the expanded bed, $\text{m}$).
- **Bảo toàn thể tích hạt rắn của lớp vật liệu lọc (Conservation of Solid Media Volume)**:
  - Tổng thể tích hạt rắn không thay đổi giữa trạng thái tĩnh ban đầu và trạng thái giãn nở:
    $$V_{solids} = (1 - \varepsilon)(a)(D) = (1 - \varepsilon_e)(a)(D_e)$$
  - Mối liên hệ hình học trực tiếp:
    $$(1 - \varepsilon_e)(D_e) = (1 - \varepsilon)(D)$$
  - Trong đó:
    - $D$: Chiều dày ban đầu của lớp lọc ở trạng thái tĩnh (unexpanded bed depth, $\text{m}$).
    - $\varepsilon$: Độ rỗng ban đầu của lớp lọc ở trạng thái tĩnh (unexpanded bed porosity, thường $\varepsilon \approx 0{,}40 - 0{,}45$).
- **Phương trình tổn thất áp lực qua lớp lọc giãn nở ($h_{Le}$)**:
  - Áp suất chênh lệch cần thiết để nâng lớp hạt ($\Delta P$):
    $$\Delta P = \frac{F_g}{a} = (\rho_s - \rho)(1 - \varepsilon_e)(D_e)(g) = (\rho_s - \rho)(1 - \varepsilon)(D)(g) \quad (\text{N/m}^2)$$
  - Chuyển đổi đơn vị áp suất ($\text{N/m}^2$) sang đơn vị cột nước tổn thất áp lực ($h_{Le}$, tính bằng $\text{m}$):
    $$h_{Le} = \frac{F_g}{(a)(\rho)(g)} = \frac{(\rho_s - \rho)(1 - \varepsilon_e)(D_e)}{\rho}$$
  - Thay thế biểu thức bảo toàn thể tích hạt rắn vào công thức:
    $$h_{Le} = \frac{(\rho_s - \rho)(1 - \varepsilon)(D)}{\rho} = \left(\frac{\rho_s}{\rho} - 1\right)(1 - \varepsilon)(D)$$
  - Biểu diễn theo tỷ trọng của vật liệu lọc ($S_s = \rho_s / \rho$):
    $$h_{Le} = (S_s - 1)(1 - \varepsilon)(D)$$
  - Đối với bể lọc hai lớp vật liệu (dual-media bed gồm antraxít và cát):
    $$h_{Le,total} = (S_{s,a} - 1)(1 - \varepsilon_a)(D_a) + (S_{s,s} - 1)(1 - \varepsilon_s)(D_s)$$
- **Tính chất hằng số của tổn thất áp lực trạng thái tầng sôi**:
  - Tổn thất áp lực qua lớp lọc khi đã giãn nở hoàn toàn ($h_{Le}$) là một hằng số cố định.
  - Giá trị $h_{Le}$ không phụ thuộc vào việc tiếp tục gia tăng vận tốc rửa ngược ($v_b > v_{mf}$).
  - Khi vận tốc rửa ngược tăng, độ rỗng $\varepsilon_e$ và chiều cao $D_e$ tự điều chỉnh để tích số $(1 - \varepsilon_e)D_e$ luôn giữ nguyên giá trị không đổi.

##### 6.2.5.3 Vận tốc sôi tối thiểu và Động học chuyển pha tầng sôi ($v_{mf}$)
- **Định nghĩa vận tốc sôi tối thiểu (Minimum Fluidization Velocity - $v_{mf}$)**:
  - $v_{mf}$ là vận tốc dòng rửa ngược dâng biểu kiến tối thiểu làm cho lớp hạt chuyển từ trạng thái cố định (fixed bed) sang trạng thái lơ lửng sôi (fluidized bed).
  - Tại giá trị $v_{mf}$, lực ma sát nhớt của dòng nước hướng lên vừa đủ triệt tiêu trọng lượng chìm của các hạt lọc.
- **Đường đặc tính thủy lực tổn thất áp lực theo vận tốc dòng dâng**:
  - Giai đoạn lớp cố định ($v_b < v_{mf}$):
    - Các hạt tiếp xúc cố định với nhau.
    - Tổn thất áp lực tăng tuyến tính theo định luật Darcy hoặc phi tuyến theo phương trình Rose và Ergun khi vận tốc dâng tăng.
  - Điểm chuyển pha ($v_b = v_{mf}$):
    - Tổn thất áp lực đạt giá trị cực đại bằng đúng trọng lượng chìm của lớp hạt ($h_L = h_{Le}$).
    - Lớp hạt bắt đầu cựa quậy và nở nhẹ tại độ rỗng ban đầu $\varepsilon$.
  - Giai đoạn tầng sôi mở rộng ($v_b > v_{mf}$):
    - Khoảng cách giữa các hạt tăng lên, độ rỗng tăng từ $\varepsilon$ lên $\varepsilon_e$.
    - Đường biểu diễn tổn thất áp lực đi ngang thành đoạn nằm ngang (plateau) tại giá trị $h_L = h_{Le}$.
- **Phương trình giải tích tính toán $v_{mf}$**:
  - Dẫn xuất từ cân bằng tổn thất áp lực phương trình Ergun với tổn thất áp lực trạng thái sôi tại $\varepsilon_e = \varepsilon$:
    $$150 \frac{\mu (1 - \varepsilon)}{\psi^2 d_{eq}^2 \varepsilon^3} v_{mf} + 1{,}75 \frac{\rho (1 - \varepsilon)}{\psi d_{eq} \varepsilon^3} v_{mf}^2 = (\rho_s - \rho)(1 - \varepsilon) g$$
  - Đơn giản hóa về phương trình số không thứ nguyên qua số Archimedes ($Ar$) và số Reynolds tại điểm sôi ($Re_{mf}$):
    $$Ar = \frac{d_{eq}^3 \rho (\rho_s - \rho) g}{\mu^2}$$
    $$Re_{mf} = \frac{\rho v_{mf} d_{eq}}{\mu}$$
    $$\frac{1{,}75}{\psi \varepsilon^3} Re_{mf}^2 + \frac{150(1 - \varepsilon)}{\psi^2 \varepsilon^3} Re_{mf} = Ar$$
  - Tương quan bán thực nghiệm Wen & Yu (1966) ứng dụng cho hạt lọc nước tự nhiên ($\psi \approx 0{,}75 - 0{,}85$, $\varepsilon \approx 0{,}40 - 0{,}45$):
    $$Re_{mf} = \sqrt{33{,}7^2 + 0{,}0408 \cdot Ar} - 33{,}7$$
    $$v_{mf} = \frac{\mu}{\rho d_{eq}} \left( \sqrt{33{,}7^2 + 0{,}0408 \cdot Ar} - 33{,}7 \right)$$
  - Dạng tiệm cận trong vùng dòng chảy tầng ($Re_{mf} \le 2$ đối với hạt mịn):
    $$v_{mf} \approx \frac{g (\rho_s - \rho) \psi^2 d_{eq}^2}{150 \mu} \frac{\varepsilon^3}{1 - \varepsilon}$$
- **Quy chuẩn lựa chọn vận tốc rửa ngược theo cỡ hạt lớn nhất ($d_{90}$)**:
  - Do lớp lọc có tính không đồng nhất ($U > 1$), các hạt phân tầng theo kích thước sau khi rửa ngược (hạt thô nằm dưới đáy, hạt mịn ở trên đỉnh).
  - Vận tốc rửa ngược $v_b$ phải vượt quá vận tốc sôi tối thiểu của phân đoạn hạt thô ở đáy ($d_{90}$):
    $$v_b \ge v_{mf}(d_{90}) \quad \text{hoặc} \quad v_b \approx 1{,}2 - 1{,}3 \cdot v_{mf}(d_{90})$$
  - Nếu $v_b < v_{mf}(d_{90})$, các hạt thô ở đáy không sôi, tạo thành vùng chết (dead zones), gây dính kết bùn và hình thành bùn vón cục (mudball formation).

##### 6.2.5.4 Động học giãn nở lớp lọc phân tầng và Mô hình Fair - Geyer (1954)
- **Hiện tượng phân tầng thủy lực của lớp hạt lọc (Hydraulic Stratification)**:
  - Khi rửa ngược bằng nước, các hạt vật liệu lọc chuyển động tự do và tái sắp xếp theo vận tốc lắng riêng của từng cỡ hạt.
  - Hạt mịn có vận tốc lắng nhỏ tập trung ở tầng trên cùng của lớp lọc.
  - Hạt thô có vận tốc lắng lớn định vị ở tầng đáy của lớp lọc.
  - Mức độ giãn nở cục bộ không đồng nhất: tầng hạt mịn phía trên có độ rỗng giãn nở lớn hơn tầng hạt thô phía dưới.
- **Phương trình Fair và Geyer (1954) xác định chiều sâu lớp lọc giãn nở ($D_e$)**:
  - Mô hình Fair - Geyer tích phân độ giãn nở của từng phân đoạn kích thước hạt từ kết quả phân tích rây:
    $$D_e = (1 - \varepsilon)(D) \sum_{i=1}^n \frac{f_i}{1 - \varepsilon_{e,i}}$$
  - Các thông số trong phương trình Fair - Geyer:
    - $D_e$: Tổng chiều dày của lớp lọc ở trạng thái giãn nở (depth of the expanded bed, $\text{m}$).
    - $D$: Chiều dày của lớp lọc ở trạng thái tĩnh ban đầu (depth of the unexpanded bed, $\text{m}$).
    - $\varepsilon$: Độ rỗng ban đầu của lớp lọc tĩnh (porosity of the bed, không thứ nguyên).
    - $f_i$: Phần khối lượng hạt lọc tương ứng với độ rỗng giãn nở $\varepsilon_{e,i}$ (mass fraction of filter media with expanded porosity $\varepsilon_{e,i}$, với $\sum f_i = 1$).
    - $\varepsilon_{e,i}$: Độ rỗng khi giãn nở của phân đoạn hạt thứ $i$ chịu tác động của vận tốc rửa ngược $v_b$.
- **Tỷ lệ giãn nở tương đối của lớp vật liệu lọc (Bed Expansion Ratio - $\%E$)**:
  - Tỷ lệ phần trăm giãn nở biểu diễn qua công thức:
    $$\%E = \frac{D_e - D}{D} \times 100\% = \left[ (1 - \varepsilon) \sum_{i=1}^n \frac{f_i}{1 - \varepsilon_{e,i}} - 1 \right] \times 100\%$$
- **Tiêu chuẩn công nghệ về tỷ lệ giãn nở tối ưu**:
  - Chế độ rửa ngược chỉ bằng nước đơn thuần (Water-only backwash without auxiliaries):
    - Độ giãn nở tối ưu dao động trong khoảng $\%E = 20\% - 50\%$ (thông thường chọn $25\% - 30\%$).
    - Mức giãn nở này bảo đảm lực cắt bề mặt hạt lớn nhất để bóc tách bông cặn mà không làm loãng quá mức nồng độ hạt trong bể.
  - Chế độ rửa ngược có hỗ trợ vòi phun rửa bề mặt (Surface wash assist):
    - Yêu cầu độ giãn nở lớp lọc $\%E = 20\% - 30\%$.
  - Chế độ rửa ngược kết hợp khí - nước đồng thời (Simultaneous air scour and backwash):
    - Lớp lọc không cần giãn nở mạnh, duy trì ở trạng thái cận sôi hoặc giãn nở thấp $\%E = 10\% - 15\%$ để giảm tiêu hao nước rửa.

##### 6.2.5.5 Xác định độ rỗng giãn nở qua Tương quan Richardson - Zaki
- **Vận tốc lắng tự do của hạt đơn lẻ ($v_{s,i}$ - Terminal Settling Velocity)**:
  - Vận tốc lắng tự do của hạt cỡ $d_i$ trong môi trường nước vô hạn tính theo phương trình cân bằng trọng lực và lực cản thủy động:
    $$v_{s,i} = \sqrt{\frac{4 g (\rho_s - \rho) d_i}{3 C_{D,i} \rho}}$$
  - Hệ số cản kéo thủy động lực học ($C_{D,i}$) tính toán theo số Reynolds của hạt ($Re_i = \frac{\rho v_{s,i} d_i}{\mu}$):
    $$C_{D,i} = \frac{24}{Re_i} + \frac{3}{\sqrt{Re_i}} + 0{,}34$$
- **Tương quan thực nghiệm Richardson - Zaki (1954)**:
  - Richardson và Zaki thiết lập mối quan hệ hàm mũ giữa vận tốc rửa ngược dòng dâng ($v_b$) và vận tốc lắng tự do đơn hạt ($v_{s,i}$):
    $$\frac{v_b}{v_{s,i}} = \varepsilon_{e,i}^n$$
  - Biểu thức giải tích xác định độ rỗng giãn nở cục bộ $\varepsilon_{e,i}$:
    $$\varepsilon_{e,i} = \left( \frac{v_b}{v_{s,i}} \right)^{\frac{1}{n}}$$
  - Các thành phần trong phương trình:
    - $v_b$: Vận tốc rửa ngược dòng dâng bề mặt (superficial backwash velocity, $\text{m/s}$ hoặc $\text{m/h}$).
    - $v_{s,i}$: Vận tốc lắng đơn hạt của phân đoạn cỡ hạt thứ $i$ ($\text{m/s}$).
    - $n$: Số mũ giãn nở Richardson - Zaki (bed expansion exponent, không thứ nguyên).
- **Quy tắc xác định số mũ giãn nở $n$**:
  - Giá trị $n$ phụ thuộc vào số Reynolds của hạt tại vận tốc lắng tự do ($Re_t = \frac{\rho v_s d}{\mu}$):
    - Vùng chảy tầng ($Re_t < 0{,}2$):
      $$n = 4{,}65$$
    - Vùng chuyển tiếp thấp ($0{,}2 < Re_t \le 1{,}0$):
      $$n = 4{,}35 \cdot Re_t^{-0{,}03}$$
    - Vùng chuyển tiếp cao ($1{,}0 < Re_t \le 500$):
      $$n = 4{,}45 \cdot Re_t^{-0{,}10}$$
    - Vùng chảy xoáy hoàn toàn ($Re_t > 500$):
      $$n = 2{,}39$$
  - Hiệu chỉnh theo Cleasby và Fan (1981) cho hạt vật liệu lọc tự nhiên có góc cạnh (cát thạch anh $\psi \approx 0{,}82$; than antraxít $\psi \approx 0{,}72$):
    $$n = 4{,}45 \cdot Re_t^{-0{,}084} \quad \text{với dải } Re_t \in [1, 200]$$

##### 6.2.5.6 Tổng hợp tổn thất áp lực hệ thống và Cơ sở định vị máng thu nước rửa
- **Cột áp tổng cộng của hệ thống rửa ngược ($H_{T,bw}$)**:
  - Máy bơm rửa ngược hoặc tháp chứa nước rửa trên cao phải cung cấp đủ áp lực thắng tổng các tổn thất áp lực thành phần:
    $$H_{T,bw} = h_{Le} + h_{gravel} + h_{underdrain} + h_{pipe} + \Delta Z$$
  - Ý nghĩa các tổn thất thành phần:
    - $h_{Le}$: Tổn thất áp lực qua lớp lọc giãn nở hoàn toàn, tính theo $h_{Le} = (S_s - 1)(1 - \varepsilon)D$ ($\text{m}$).
    - $h_{gravel}$: Tổn thất áp lực qua các lớp sỏi đỡ (lớp sỏi kích thước lớn không bị sôi, tính theo công thức Ergun hoặc Rose với vận tốc $v_b$, thường $h_{gravel} \approx 0{,}10 - 0{,}25\text{ m}$).
    - $h_{underdrain}$: Tổn thất áp lực qua hệ thống phân phối đáy (chụp lọc nozzles hoặc khối sứ lọc underdrain blocks), thường thiết kế $h_{underdrain} \approx 0{,}6 - 1{,}5\text{ m}$ để duy trì phân phối lưu lượng đều khắp diện tích mặt bằng bể.
    - $h_{pipe}$: Tổn thất áp lực cục bộ và ma sát dọc đường qua tuyến ống cấp nước rửa ngược, phụ kiện van khóa, van một chiều.
    - $\Delta Z$: Chênh lệch cao trình hình học từ mực nước bể hút đến mép tràn máng thu nước rửa ngược.
- **Tiêu chuẩn xác định vị trí máng thu nước rửa ngược (Backwash Trough Placement)**:
  - Cao trình đáy máng thu nước rửa ($Z_{trough,bottom}$) phải đặt cao hơn đỉnh lớp lọc giãn nở cực đại một khoảng lưu không an toàn ($\Delta h_{freeboard}$):
    $$Z_{trough,bottom} \ge Z_{bed,top} + (D_e - D) + \Delta h_{freeboard} = Z_{bed,top} + D \cdot \%E + \Delta h_{freeboard}$$
  - Khoảng lưu không an toàn tối thiểu:
    $$\Delta h_{freeboard} \ge 0{,}15 - 0{,}30\text{ m} \quad (15 - 30\text{ cm})$$
  - Cơ chế ngăn ngừa thất thoát vật liệu lọc:
    - Nếu đáy máng đặt ngập vào tầng hạt đang sôi ($Z_{trough,bottom} < Z_{bed,top} + D_e - D$), dòng nước xoáy cuộn quanh đáy máng sẽ cuốn trôi hạt lọc vào trong máng gây hư hại hao hụt vật liệu nghiêm trọng.
    - Mép tràn máng thu nước rửa đặt cách mặt lớp lọc tĩnh ban đầu một khoảng cách chuẩn từ $0{,}60\text{ m}$ đến $0{,}90\text{ m}$.
  - Khoảng cách hình học giữa các máng thu:
    - Khoảng cách mép tràn giữa hai máng liền kề khống chế không quá $1{,}5 - 2{,}5\text{ m}$.
    - Quy định này bảo đảm cặn bùn lơ lửng không phải di chuyển quãng đường ngang quá xa trước khi tràn vào máng thu xả ra ngoài.

### 6.3 Thực hành thiết kế và Cấu tạo công trình (Engineering Practice & System Design)

#### 6.3.1 Lựa chọn loại bể lọc và Dây chuyền công nghệ (Filter Type Selection & Process Integration)

* Các yếu tố quyết định lựa chọn loại bể lọc:
  * Đặc tính chất lượng nguồn nước thô (raw water characteristics) và biên độ biến động chất lượng theo mùa.
  * Các quá trình xử lý công nghệ bố trí trước bể lọc (tiền keo tụ, tạo bông, lắng làm trong) và sau bể lọc (khử trùng, bể chứa nước sạch).
* Bể lọc một lớp than antraxít sâu (Deep-bed anthracite monomedia filters):
  * Tốc độ tích lũy tổn thất áp lực thấp (accumulate headloss at a low rate).
  * Khả năng tích trữ cặn bẩn trong các khe rỗng rất lớn (high capacity for accumulating solids).
  * Chu kỳ làm việc của bể lọc kéo dài (long filter runs).
  * Độ nhạy vận hành cao: Hiệu quả lọc suy giảm nghiêm trọng khi chất lượng nước thô biến động lớn, châm hóa chất keo tụ sai liều lượng, hoặc người vận hành thiếu giám sát.
* Bể lọc hai lớp vật liệu than antraxít và cát thạch anh (Dual-media filters):
  * Cung cấp giải pháp kết cấu bền vững và ổn định (thiết kế ổn định và thích ứng cao) khi điều kiện tiền xử lý nước thô không đạt chuẩn.
  * Tận dụng tối đa dung tích chiều sâu lớp lọc nhờ phân tầng than thô ở trên và cát mịn ở dưới.
* Bể lọc cát nhanh truyền thống (Rapid sand filters):
  * Đã được ứng dụng rộng rãi trong ngành xử lý nước hơn một thế kỷ.
  * Giới hạn thủy lực cố hữu: Hạt cát mịn nhất tập trung ở tầng mặt trên cùng sau khi rửa ngược.
  * Khe hở lỗ rỗng nhỏ nhất nằm ở tầng mặt, khiến phần lớn hạt cặn bị giữ lại và gây bít tắc lớp mặt trên cùng.
  * Chỉ một phần nhỏ chiều sâu của lớp cát được sử dụng để giữ cặn; tổn thất áp lực tích lũy rất nhanh khiến chu kỳ lọc bị rút ngắn.
* Bằng chứng thực nghiệm so sánh các loại bể lọc hạt:
  - **Hình 10.** Sơ đồ cấu tạo bể lọc cát chậm (Slow Sand Filter)
    - <img src="ch06_filtration/assets/fig_10_p5.jpeg" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu tạo bể lọc cát vận hành theo cơ chế màng sinh học bề mặt, phân biệt với bể lọc nhanh.
    - **Từ đâu mà thấy được**
      - Thân bể chứa đĩa phân phối (Diffuser Plate), lớp cát (Sand), lớp sỏi ngăn cách (Separating Gravel) và ống thu đáy (Outlet Pipe).
  - **Hình 11.** Sơ đồ hệ thống thủy lực bể lọc cát nhanh trọng lực (Rapid Sand Filter)
    - <img src="ch06_filtration/assets/fig_11_p6.jpeg" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Minh họa hệ thống điều khiển lưu lượng lọc, cụm van công nghệ và đài nước rửa ngược của bể lọc nhanh.
    - **Từ đâu mà thấy được**
      - Đường nước vào qua van A, cụm điều khiển tốc độ lọc (Filter rate controller) qua van C vào bể chứa nước lọc, và tháp nước rửa (Washwater storage tank) cấp nước qua van E.
  - **Hình 12.** Mặt cắt chi tiết bể lọc cát nhanh và trạm chứa nước rửa
    - <img src="ch06_filtration/assets/fig_12_p7.jpeg" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cao trình mực nước trong pha lọc bình thường và pha rửa ngược cùng hệ thống thu nước đáy ống nhánh.
    - **Từ đâu mà thấy được**
      - Mực nước khi lọc (Water level while filtering) cao hơn máng rửa; mực nước khi rửa (Water level while washing) dâng lên tới mép máng; hệ thống ống nhánh (Lateral drain) nằm trong lớp sỏi.

* So sánh dây chuyền công nghệ lọc trực tiếp (direct filtration) và dây chuyền truyền thống (conventional filtration):
  * Dây chuyền truyền thống gồm Keo tụ -> Tạo bông -> Lắng cặn -> Lọc hạt: Áp dụng khi nước thô có độ đục cao ($> 20\text{ NTU}$) hoặc độ màu cao ($> 20\text{ Pt-Co}$).
  * Dây chuyền lọc trực tiếp (Direct Filtration) bỏ qua công đoạn lắng cặn: Áp dụng khi nước thô có độ đục thấp ($< 10 - 15\text{ NTU}$), hàm lượng chất rắn lơ lửng thấp và ít biến động.
  * Lọc tiếp xúc (In-line Filtration) bỏ qua cả ngăn tạo bông và bể lắng: Hóa chất keo tụ được châm trực tiếp vào đường ống trước khi vào thẳng bể lọc hạt, chỉ áp dụng cho nguồn nước cực sạch ($< 5\text{ NTU}$).
  * Tiêu chuẩn tiết kiệm chi phí đầu tư: Dây chuyền lọc trực tiếp giảm từ \%$ đến \%$ chi phí xây dựng bể lắng và giảm đáng kể thể tích mặt bằng xây dựng trạm.
  * Yêu cầu kiểm soát liều lượng hóa chất khắt khe: Trong lọc trực tiếp, toàn bộ cặn keo tụ đi thẳng vào lớp cát lọc, đòi hỏi liều lượng polymer và phèn phải được định lượng chính xác để tránh bít tắc sớm.

#### 6.3.2 Xác định số lượng bể lọc và Độ tin cậy N-1 (Number of Filters & N-1 Redundancy Hydraulics)

* Quy chuẩn số lượng bể lọc tối thiểu theo công suất thiết kế trạm:
  * Trạm xử lý công suất nhỏ ($Q \le 8{,}000\text{ m}^3/\text{d}$): Số lượng bể lọc tối thiểu là $2$ bể ($N_{\min} = 2$).
  * Trạm xử lý công suất lớn ($Q > 8{,}000\text{ m}^3/\text{d}$): Số lượng bể lọc tối thiểu là $4$ bể ($N_{\min} = 4$).
* Công thức kinh nghiệm Kawamura (2000) xác định số lượng bể lọc cho trạm công suất lớn:
  $$N = 0.0195 \cdot (Q)^{0.5}$$
  * Trong đó:
    * $N$ là tổng số lượng bể lọc (làm tròn lên số nguyên dương chẵn gần nhất để bố trí đối xứng qua mương dẫn).
    * $Q$ là công suất lưu lượng thiết kế ngày tối đa của nhà máy (maximum design flow rate), tính bằng $\text{m}^3/\text{d}$.
* Phân tích thủy lực điều kiện dự phòng $N-1$ (N-1 Redundancy Hydraulics):
  * Khi trạm có số lượng bể lọc ít, việc cô lập một bể để rửa ngược hoặc bảo dưỡng sẽ làm tăng vọt tốc độ lọc ở các bể còn lại đang hoạt động.
  * Tốc độ lọc tăng đột ngột làm bung trôi các hạt cặn đã giữ lại (particle detachment), gây bùng phát độ đục (turbidity breakthrough) trong nước sau lọc.
  * Yêu cầu thiết kế bắt buộc: Phải tính toán kịch bản thủy lực khi một bể ngừng hoạt động trước khi chốt tốc độ lọc định mức:
    $$q_{N-1} = \frac{Q}{(N - 1) \cdot A} \le q_{\max,\text{allowed}}$$
  * Nếu duy trì tốc độ lọc thiết kế định mức khi thiếu $1$ bể, tốc độ lọc danh định khi toàn bộ $N$ bể cùng làm việc phải giảm xuống tương ứng.
  * Toàn bộ hệ thống bể lọc phải đảm bảo xử lý đủ công suất thiết kế của trạm ở tốc độ lọc cho phép khi có một bể bị loại khỏi vận hành.

#### 6.3.3 Tốc độ lọc và Kích thước hình học bể lọc (Hydraulic Loading Rates & Filter Basin Geometry)

* Hiệu quả kinh tế của tốc độ lọc thiết kế:
  * Chi phí đầu tư xây dựng bể lọc tỷ lệ nghịch với tốc độ lọc: Tốc độ lọc cao hơn làm giảm diện tích mặt bằng yêu cầu của khối bể lọc.
* Tốc độ lọc thiết kế danh định cho từng loại bể:
  * Bể lọc cát nhanh (Rapid sand filters): Tốc độ thiết kế an toàn là $7.5\text{ m/h}$ ($180\text{ m}^3/(\text{m}^2\cdot\text{d})$).
  * Bể lọc hai lớp than - cát (Dual-media filters):
    * Tốc độ thiết kế an toàn là $15\text{ m/h}$ ($360\text{ m}^3/(\text{m}^2\cdot\text{d})$).
    * Khi quá trình keo tụ đạt chuẩn, bể hai lớp có thể đạt hiệu quả lọc tốt ở tốc độ lên tới $25\text{ m/h}$.
    * Chất lượng nước sau lọc suy giảm nhanh ở tốc độ trên $12.5\text{ m/h}$ nếu bông keo tụ phèn nhôm yếu và không có chất trợ keo tụ polymer.
  * Bể lọc một lớp hạt thô sâu (Deep, coarse monomedium filters): Tốc độ thiết kế đạt $25\text{ m/h}$ ($600\text{ m}^3/(\text{m}^2\cdot\text{d})$) khi châm polymer làm chất trợ lọc.
* Tổn thất áp lực lớp lọc sạch ban đầu (Clean bed headloss):
  * Nằm trong khoảng từ $0.3\text{--}0.6\text{ m}$.
* Công thức tính diện tích bề mặt của một ô bể lọc:
  $$A = \frac{Q}{N \cdot q}$$
  * Trong đó:
    * $A$ là diện tích bề mặt của một ô bể lọc (area of a bed), tính bằng $\text{m}^2$.
    * $Q$ là công suất lưu lượng ngày tối đa (maximum day flow rate), tính bằng $\text{m}^3/\text{d}$.
    * $N$ là tổng số ô bể lọc.
    * $q$ là tốc độ lọc (filtration rate), tính bằng $\text{m}^3/(\text{m}^2\cdot\text{d})$ hoặc $\text{m/h}$.
* Phạm vi diện tích bề mặt bể lọc:
  * Khoảng diện tích phổ biến: $25\text{--}100\text{ m}^2$, trung bình khoảng $50\text{ m}^2$.
  * Giới hạn trên tiêu chuẩn cho các trạm xử lý lớn: $100\text{ m}^2$.
  * Một số trạm xử lý cực lớn có thể sử dụng diện tích bề mặt ô lọc lên tới $200\text{ m}^2$.
* Kích thước hình học và cấu tạo khối bể lọc:
  * Một đơn nguyên bể lọc (bed) thường được chia thành $2$ ngăn độc lập (cells) đối xứng nhau qua mương trung tâm.
  * Chiều rộng của mỗi ngăn lọc: $W_{\text{cell}} \le 6\text{ m}$ để có thể sử dụng máng thu nước rửa chế tạo sẵn tiêu chuẩn ("off-the-shelf" wash water troughs).
  * Tỷ lệ chiều dài trên chiều rộng của ngăn lọc ($L:W$ ratio): Từ $2:1$ đến $4:1$.
  * Chiều sâu tổng thể bể lọc: Dao động từ $4\text{--}8\text{ m}$ để bố trí hệ thống thu đáy, lớp sỏi đỡ, tầng vật liệu lọc, lớp nước ngập và dự phòng cột nước tổn thất áp lực.
  * Cột nước áp lực khả dụng qua lớp lọc (available head): Thường giới hạn từ $2\text{--}3\text{ m}$ do ràng buộc chi phí xây dựng thân bể.
  * Ngưỡng giới hạn tổn thất áp lực thực nghiệm:
    * Đối với bông cặn keo tụ tốt trong bể lọc hai lớp: Độ đục bắt đầu tăng khi tổn thất áp lực thuần vượt quá $1.8\text{ m}$.
    * Đối với bông cặn keo tụ kém: Hiện tượng xuyên thủng độ đục có thể xảy ra khi tổn thất áp lực thuần chưa đạt $0.8\text{ m}$.
* Bảng quy chuẩn kích thước hình học cho bể lọc nhanh trọng lực:

| Thông số hình học (Parameter) | Phạm vi giá trị (Reported range) | Ghi chú thiết kế (Comment) |
|---|---|---|
| **Diện tích một bể lọc ($A$)** | $25\text{--}100\text{ m}^2$ | Trạm cực lớn tối đa $200\text{ m}^2$ |
| **Chiều rộng một ngăn lọc ($W_{\text{cell}}$)** | $\le 6\text{ m}$ | Áp dụng máng rửa chế tạo sẵn tiêu chuẩn |
| **Tỷ lệ dài : rộng ($L:W$)** | $2:1\text{ đến } 4:1$ | Đảm bảo phân bố dòng thủy lực đều |
| **Chiều sâu tổng thể ($H$)** | $4\text{--}8\text{ m}$ | Bố trí hệ thu nước đáy, vật liệu và cột áp |
| **Chiều sâu lớp nước trên mặt ($h_w$)** | $\ge 1.8\text{ m}$ | Ngăn ngừa áp suất âm và xâm thực khí |
| **Chiều rộng mương trung tâm (Gullet width)** | $0.4\text{--}2.0\text{ m}$ | Đảm bảo thu gom và xả dòng nước rửa |
| **Chiều sâu mương trung tâm (Gullet depth)** | Từ mặt vật liệu đến đáy hệ thu nước | Đo từ đáy máng thu nước rửa |

  - **Hình 35.** Bảng kích thước hình học khuyến cáo cho bể lọc trọng lực nhanh (Recommended dimensions)
    - <img src="ch06_filtration/assets/fig_35_p46.png" alt="Hình 35" />
    - **Hình này chứng minh điều gì**
      - Cung cấp các thông số kích thước hình học tiêu chuẩn cho mặt bằng và chiều sâu bể lọc nhanh trọng lực.
    - **Từ đâu mà thấy được**
      - Bảng ghi rõ diện tích $25\text{--}100\text{ m}^2$, chiều rộng ngăn $\le 6\text{ m}$, tỷ lệ $L:W = 2:1\text{--}4:1$, chiều sâu nước $\ge 1.8\text{ m}$.

* Các phương thức điều khiển vận hành thủy lực của hệ thống bể lọc hạt:
  * Phương thức lọc tốc độ không đổi với van điều khiển lưu lượng đầu ra (Constant-rate with effluent rate controller):
    * Mỗi bể lọc được trang bị một van bướm điều khiển tự động hoặc van Venturi trên đường ống xả nước lọc.
    * Khi lớp vật liệu lọc tích lũy cặn làm tăng tổn thất áp lực, van tự động mở rộng dần để duy trì lưu lượng lọc không đổi.
  * Phương thức lọc tốc độ không đổi với phân chia lưu lượng đầu vào (Constant-rate with influent flow splitting):
    * Nước lắng được phân phối đều vào từng bể lọc qua các đập tràn đỉnh bằng nhau có cùng cao trình.
    * Mực nước trong từng bể lọc tự do dâng cao dần theo mức độ bít tắc của lớp vật liệu lọc cho đến khi đạt cao trình rửa ngược.
  * Phương thức lọc tốc độ giảm dần (Declining-rate filtration):
    * Nước vào các bể lọc từ một kênh phân phối chung không có van tiết lưu; bể mới rửa sạch sẽ lọc với tốc độ cao nhất, sau đó tốc độ lọc tự động giảm dần khi cặn bẩn tích tụ.
    * Ưu điểm: Nước lọc đầu ra đạt chất lượng độ đục rất ổn định ở cuối chu kỳ do tốc độ dòng chảy giảm dần; không yêu cầu hệ thống van điều khiển tự động phức tạp.

#### 6.3.4 Tiêu chuẩn lựa chọn và Phối hợp vật liệu lọc (Media Specification & Layer Matching Criteria)

* Mối quan hệ giữa loại bể lọc và vật liệu lọc:
  * Lựa chọn loại bể lọc sẽ định hình loại vật liệu lọc tương ứng.
  * Phân bố kích thước hạt chi phối sự đánh đổi kỹ thuật giữa tổn thất áp lực (hạt lớn làm giảm tổn thất áp lực) và hiệu quả lọc (hạt nhỏ giữ hạt cặn tốt hơn).
* Hai tiêu chí thiết kế vật liệu lọc then chốt:
  * Kích thước hiệu dụng (Effective Size): $E = d_{10}$, là kích thước mắt rây cho $10\%$ khối lượng mẫu lọt qua.
  * Hệ số đồng nhất (Uniformity Coefficient): $U = U_c = \frac{d_{60}}{d_{10}}$, là tỷ số giữa kích thước mắt rây cho $60\%$ và $10\%$ khối lượng lọt qua.
  * Ý nghĩa công nghệ: Hệ số $U$ càng nhỏ thì kích thước hạt trong tầng lọc càng đồng đều, giúp khai thác tối đa dung tích giữ cặn theo chiều sâu bể.
  * Kích thước hiệu dụng $E$ đóng vai trò quyết định đối với tổn thất áp lực của lớp lọc sạch ban đầu.
* Kiểm tra quy cách vật liệu qua tổn thất áp lực lớp lọc sạch:
  * Tổn thất áp lực lớp lọc sạch bình thường từ $0.3\text{--}0.6\text{ m}$.
  * Nếu tổn thất áp lực ban đầu vượt quá $0.6\text{ m}$, điều đó chứng tỏ tốc độ lọc quá cao hoặc vật liệu lọc chứa tỷ lệ hạt mịn vượt mức cho phép.
* Tiêu chuẩn phối hợp vật liệu lọc đa tầng (Layer Matching Criteria):
  * Trong bể lọc hai lớp hoặc đa lớp, đặc tính hạt của từng tầng vật liệu phải được tính toán phối hợp chặt chẽ.
  * Điều kiện bắt buộc: Tầng than anthracite và tầng cát thạch anh phải cùng đạt trạng thái tầng sôi ở cùng một vận tốc nước rửa ngược.
  * Tránh hiện tượng: Vận tốc rửa quá lớn làm trôi mất than anthracite ra ngoài, hoặc vận tốc rửa quá nhỏ không đủ làm giãn nở lớp cát thạch anh bên dưới.
* Bằng chứng định lượng về đặc tính hạt và cơ chế thu giữ cặn:
  - **Hình 13.** Các đại lượng thể tích và định nghĩa độ rỗng lớp lọc
    - <img src="ch06_filtration/assets/fig_13_p12.png" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Định nghĩa độ rỗng $\epsilon$ dựa trên tỷ số giữa thể tích lỗ rỗng $\forall_v$ và tổng thể tích lớp hạt $\forall_T$.
    - **Từ đâu mà thấy được**
      - Ký hiệu $\epsilon$ là porosity, $\forall_v$ là volume of voids, $\forall_T$ là total volume of media bed, $\forall_M$ là volume of media.
  - **Hình 14.** Biểu thức tương quan thành phần thể tích lớp vật liệu lọc
    - <img src="ch06_filtration/assets/fig_14_p13.png" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự phân chia thể tích hạt rắn và khoảng trống lỗ rỗng trong mô hình thủy lực lớp đệm.
    - **Từ đâu mà thấy được**
      - Chú thích các đại lượng thể tích thành phần sử dụng trong phương trình tính toán độ rỗng lớp đệm.
  - **Hình 15.** Bảng tính chất vật lý và thành phần hóa học điển hình của cát thạch anh lọc nước
    - <img src="ch06_filtration/assets/fig_15_p16.png" alt="Hình 15" />
    - **Hình này chứng minh điều gì**
      - Cung cấp các thông số kỹ thuật tiêu chuẩn của cát thạch anh: Độ cứng Mohs $7.0$, tỷ trọng $\text{SG} = 2.65$, độ cầu $\psi \ge 0.6$, hàm lượng $\text{SiO}_2 = 99.48\%$.
    - **Từ đâu mà thấy được**
      - Bảng trên: Mineral: Quartz, Hardness: 7.0, Specific Gravity: 2.65, Sphericity: 0.6+; bảng dưới: $\text{SiO}_2: 99.48\%$.
  - **Hình 16.** Bảng chỉ tiêu cơ lý và hóa học của hạt cát lọc thạch anh
    - <img src="ch06_filtration/assets/fig_16_p17.png" alt="Hình 16" />
    - **Hình này chứng minh điều gì**
      - Khẳng định tính trơ hóa học và độ bền mài mòn cơ học của hạt cát thạch anh đạt tiêu chuẩn ngành cấp nước.
    - **Từ đâu mà thấy được**
      - Các chỉ số tỷ trọng $2.65$, độ tan trong axit thấp và thành phần khoáng quartz tinh khiết chống mài mòn khi sục rửa.
  - **Hình 17.** Sơ đồ các cơ chế thu giữ hạt cặn bên trong lớp vật liệu lọc
    - <img src="ch06_filtration/assets/fig_17_p18.png" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - Minh họa trực quan bốn cơ chế giữ cặn chính: Sàng lọc cơ học (Straining), keo tụ tiếp xúc (Flocculation), chặn giữ (Interception) và lắng trọng lực (Sedimentation).
    - **Từ đâu mà thấy được**
      - Bông cặn (Floc Particles) bị giữ tại kẽ hở giữa các hạt (Straining), bám dính vào hạt cát (Interception, Flocculation) hoặc lắng tại khoảng rỗng (Sedimentation).
  - **Hình 18.** Mô hình tương tác hạt cặn với bề mặt hạt lọc trong tầng lọc sâu
    - <img src="ch06_filtration/assets/fig_18_p19.png" alt="Hình 18" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự phân bổ không gian của các vị trí lắng đọng cặn trên bề mặt hạt vật liệu lọc.
    - **Từ đâu mà thấy được**
      - Vị trí cặn bám dính ở mặt trước, khe tiếp giáp và vùng bóng thủy động phía sau các hạt tròn trong dòng lọc.
  - **Hình 48.** Bảng phân tích rây cấp phối hạt cát tiêu chuẩn U.S. Standard Sieve
    - <img src="ch06_filtration/assets/fig_48_p50.png" alt="Hình 48" />
    - **Hình này chứng minh điều gì**
      - Cung cấp số liệu phân tích rây xác định đường cong cấp phối hạt, kích thước hiệu dụng $d_{10}$ và hệ số đồng nhất $U$.
    - **Từ đâu mà thấy được**
      - Cột trái ghi số hiệu rây U.S. Standard Sieve No. (từ 140 đến 6), cột phải ghi phần trăm lọt rây tích lũy từ $0.2\%$ đến $99.0\%$.

#### 6.3.5 Hệ thống đỡ và Thu nước đáy bể lọc (Filter Support Media & Underdrain Systems)

* Ba chức năng cơ bản của hệ thống thu nước đáy (underdrain system):
  * Nâng đỡ toàn bộ khối lượng lớp vật liệu lọc phía trên.
  * Thu gom nước đã lọc một cách đồng đều trên toàn bộ bề mặt đáy bể.
  * Phân phối đồng đều nước rửa ngược và khí nén sục rửa (nếu có sử dụng sục khí).
* Lớp sỏi đỡ (Filter support gravel):
  * Đa số hệ thống thu nước đáy có các khe mở hoặc lỗ khoét lớn hơn kích thước hạt của lớp vật liệu lọc.
  * Để ngăn ngừa vật liệu lọc rò rỉ vào hệ thống thu nước đáy, nhiều lớp sỏi phân cấp (graded gravel) được bố trí xen giữa hệ thu nước và lớp vật liệu lọc.
* Năm nhóm cấu tạo hệ thống thu nước đáy chính:
  1. Hệ thống ống nhánh khoan lỗ (Manifold pipe lateral system).
  2. Hệ thống khối đúc thu nước đáy (Blocks).
  3. Lưới chắn thu nước (Screens).
  4. Sàn đáy giả gắn vòi chụp lọc (False bottom with nozzles).
  5. Đáy rỗng xốp (Porous bottom).
* Đặc tính của hệ thống ống nhánh khoan lỗ (Perforated pipe laterals):
  * Từng được sử dụng phổ biến do chi phí đầu tư ban đầu thấp.
  * Nhược điểm: Tổn thất áp lực tương đối cao và phân phối nước rửa ngược kém đồng đều, dẫn đến việc ít được áp dụng trong các thiết kế hiện đại.
  * Bắt buộc phải có các lớp sỏi đỡ phân cấp bảo vệ.
* Đặc tính của hệ thống khối đúc thu đáy (Block underdrains):
  * Khối đất sét nung (Vitrified clay block): Thiết kế các lỗ khoan đường kính $6\text{ mm}$ trên đỉnh khối; bắt buộc dùng sỏi đỡ; không thể kết hợp sục khí nén (air scour).
  * Khối nhựa polyethylene mật độ cao: Cho phép tích hợp hệ thống sục khí nén hỗ trợ rửa ngược.
* Đặc tính của sàn chụp lọc vòi phun (False bottom with nozzles):
  * Sàn bê tông hoặc sàn thép gắn các vòi chụp lọc bằng nhựa polypropylene với khe xẻ siêu mịn $0.2\text{--}0.5\text{ mm}$.
  * Giữ trực tiếp lớp cát lọc hoặc chỉ cần một lớp sỏi mỏng; tối ưu hóa phân phối đồng thời nước và khí rửa ngược.
* Yêu cầu kỹ thuật và cơ học của hệ thống thu nước đáy:
  * Là kết cấu cốt lõi quyết định sự thành công của nhà máy xử lý trong việc loại bỏ triệt để độ đục trước khi khử trùng.
  * Kết cấu phải có độ bền cơ học cao, chịu được áp lực đẩy ngược lớn khi rửa bể, đồng thời thuận tiện cho công tác thi công và bảo trì.
  * Tổn thất áp lực qua hệ thống thu đáy hiện đại trong chu kỳ lọc hoặc rửa ngược chỉ nằm trong khoảng $0.1\text{--}0.3\text{ m}$.
  * Công tác kiểm tra nghiệm thu nghiêm ngặt trong và sau khi lắp đặt, đặc biệt trước khi rải vật liệu lọc, là yêu cầu kỹ thuật bắt buộc.
* Bằng chứng cấu tạo chi tiết các loại hệ thống thu nước đáy và vòi phun lọc:
  - **Hình 19.** Mô hình cấu tạo bể lọc sử dụng hệ thống ống nhánh khoan lỗ (Perforated pipe laterals)
    - <img src="ch06_filtration/assets/fig_19_p38.jpeg" alt="Hình 19" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự bố trí không gian của các ống nhánh đục lỗ nối vào ống góp chính cùng các lớp sỏi đỡ và cát lọc.
    - **Từ đâu mà thấy được**
      - Nhãn chỉ rõ Perforated pipe laterals nối vào Outlet main, phía trên là Graded gravel, Graded filter sand và Wash troughs.
  - **Hình 20.** Cấu tạo khối đúc thu nước đáy có lỗ khoan trên mặt (Underdrain block)
    - <img src="ch06_filtration/assets/fig_20_p38.png" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - Minh họa cấu trúc rỗng bên trong và các lỗ khoét trên nắp khối đúc cùng ghi chú lớp sỏi đỡ.
    - **Từ đâu mà thấy được**
      - Mũi tên chỉ rõ: Gravel placed on top of block; bề mặt đúc các lỗ tròn $6\text{ mm}$ phân bố đều, bên dưới là $4$ khoang dẫn rỗng.
  - **Hình 21.** Mặt cắt không gian hệ thống ống nhánh khoan lỗ thu nước đáy
    - <img src="ch06_filtration/assets/fig_21_p39.jpeg" alt="Hình 21" />
    - **Hình này chứng minh điều gì**
      - Khẳng định tính hoàn chỉnh của cụm ống nhánh kết hợp ống chính thu nước lọc và phân phối nước rửa.
    - **Từ đâu mà thấy được**
      - Trục ống góp trung tâm phân nhánh đều ra hai bên đáy bể bên dưới các lớp sỏi thạch anh phân cấp.
  - **Hình 22.** Khối thu nước đáy dạng hộp rỗng cho bể lọc nhanh
    - <img src="ch06_filtration/assets/fig_22_p39.png" alt="Hình 22" />
    - **Hình này chứng minh điều gì**
      - Thể hiện chi tiết cấu tạo các gờ ghép ngàm và hàng lỗ phun phân phối dòng nước rửa ngược.
    - **Từ đâu mà thấy được**
      - Cấu trúc kênh dẫn đôi hai tầng bằng đất sét nung hoặc nhựa đúc với hàng lỗ thoát phân bố trên bề mặt.
  - **Hình 23.** Chụp lọc vòi phun gắn sàn bê tông và cụm phân phối nan hoa (KSH Filter Nozzles & Stars)
    - <img src="ch06_filtration/assets/fig_23_p40.jpeg" alt="Hình 23" />
    - **Hình này chứng minh điều gì**
      - Thể hiện phương pháp lắp đặt chụp lọc đơn xuyên qua sàn bê tông đáy giả và cụm chụp lọc phân nhánh nan hoa 6 cánh.
    - **Từ đâu mà thấy được**
      - Hình tròn trên: Vòi chụp lọc có ren xuyên qua sàn bê tông đáy; hình tròn dưới: Cụm 6 ống lọc xòe hình ngôi sao kết nối đầu gom trung tâm.
  - **Hình 24.** Tổng hợp các chủng loại chụp lọc đơn và chụp lọc chùm dạng sao
    - <img src="ch06_filtration/assets/fig_24_p40.jpeg" alt="Hình 24" />
    - **Hình này chứng minh điều gì**
      - Giới thiệu sự đa dạng của các kết cấu đầu chụp lọc ngắn, cuống dài (dùng cho sục khí) và chùm nan hoa (Filter-Nozzles-Stars).
    - **Từ đâu mà thấy được**
      - Cụm vòi đơn các chiều dài thân ren khác nhau (ảnh giữa) và cụm vòi nan hoa lắp ghép góc tỏa tròn (ảnh dưới).
  - **Hình 25.** Chi tiết vòi phun chụp lọc lắp qua bản sàn đáy giả
    - <img src="ch06_filtration/assets/fig_25_p41.jpeg" alt="Hình 25" />
    - **Hình này chứng minh điều gì**
      - Minh họa kết cấu ngàm giữ và thân ren cố định chụp lọc chống áp lực đẩy ngược khi sục rửa nước và khí.
    - **Từ đâu mà thấy được**
      - Vết cắt mặt sàn cho thấy cuống chụp xuyên qua bản sàn có gioăng kín nước và khe xẻ thu nước trên nắp chụp.
  - **Hình 27.** Bản vẽ kỹ thuật và đặc tuyến thủy lực chụp lọc Type D
    - <img src="ch06_filtration/assets/fig_27_p42.png" alt="Hình 27" />
    - **Hình này chứng minh điều gì**
      - Cung cấp kích thước hình học chính xác (đường kính $\varnothing 50\text{ mm}$, chiều cao $46\text{ mm}$) và đồ thị tổn thất áp lực theo lưu lượng.
    - **Từ đâu mà thấy được**
      - Bản vẽ chi tiết cuống ren $L_1, L_2$, bảng tra kích thước khe hở từ $0.2\text{--}2.0\text{ mm}$, và đường cong quan hệ tổn thất cột áp $\text{m-Ws}$ theo lưu lượng $\text{m}^3/\text{h}$.
  - **Hình 28.** Bản vẽ kỹ thuật và đặc tuyến thủy lực chụp lọc Type L / LR
    - <img src="ch06_filtration/assets/fig_28_p42.png" alt="Hình 28" />
    - **Hình này chứng minh điều gì**
      - Thể hiện thông số chụp lọc nắp phẳng đường kính lớn $\varnothing 65\text{ mm}$ cùng đường đặc tính thủy lực tổn thất áp lực.
    - **Từ đâu mà thấy được**
      - Bản vẽ mặt cắt Typ L với khe xẻ ngang $0.2\text{ mm}$, cuống ren $G\ 3/4"$ và đồ thị quan hệ lưu lượng - tổn thất áp lực phía dưới.
  - **Hình 29.** Hệ thống thu nước đáy nan hoa Typ SD6 cho bể lọc hình trụ tròn
    - <img src="ch06_filtration/assets/fig_29_p42.png" alt="Hình 29" />
    - **Hình này chứng minh điều gì**
      - Minh họa phương án bố trí mạng lưới phân phối và thu nước dạng chùm nan hoa phủ kín đáy bồn lọc hình trụ tròn.
    - **Từ đâu mà thấy được**
      - Mặt bằng bố trí các ống nhánh xòe từ các tâm phân phối phụ trong chu vi đường kính bể $\varnothing 800\text{--}1800\text{ mm}$.
  - **Hình 30.** Cấu tạo cụm chụp lọc nan hoa 6 nhánh Typ SK6F
    - <img src="ch06_filtration/assets/fig_30_p42.png" alt="Hình 30" />
    - **Hình này chứng minh điều gì**
      - Thể hiện chi tiết cấu tạo khớp nối mặt bích và các ống lọc xẻ rãnh nghiêng góc $20^\circ$ của cụm nan hoa 6 cánh.
    - **Từ đâu mà thấy được**
      - Bản vẽ ghi rõ góc nghiêng $20^\circ$, ren nối $G3/4"$ và $G2"$, bảng chiều dài nhánh từ $206\text{ mm}$ đến $547\text{ mm}$.

#### 6.3.6 Chế độ rửa ngược và Dung tích bể chứa nước rửa (Backwash Regimes, Scour Methods & Washwater Storage)

* Ba tiêu chí kích hoạt chu kỳ rửa ngược bể lọc:
  1. Tổn thất áp lực qua lớp lọc đạt giá trị thiết kế tối đa hoặc chạm ngưỡng giới hạn cài đặt trước, thông thường từ $2.4\text{--}3.0\text{ m}$.
  2. Độ đục của nước sau lọc chạm ngưỡng giới hạn trên quy định (báo hiệu hiện tượng xuyên thủng bông cặn).
  3. Thời gian vận hành liên tục chạm mốc thời gian tối đa cho phép, thông thường từ $3\text{--}4\text{ ngày}$ nhằm ngăn ngừa sự nén chặt của cặn và sự phát triển sinh học trong lớp lọc.
* Cơ chế thủy lực rửa ngược dòng chảy ngược truyền thống:
  * Áp dụng dòng nước sạch chảy ngược từ dưới lên (upflow water wash) làm tầng sôi và giãn nở hoàn toàn lớp lọc (full bed fluidization).
  * Nước rửa đưa vào đáy bể qua hệ thống thu nước đáy; khi lưu lượng tăng lên, toàn bộ lớp hạt giãn nở và cọ xát cơ học.
  * Quá trình rửa ngược duy trì liên tục cho đến khi dòng nước thải rửa tràn vào máng thu trở nên trong.
* Các chỉ tiêu định mức thủy lực rửa ngược:
  * Vận tốc rửa ngược: $v_{bw} = 30\text{--}60\text{ m/h}$.
  * Thời gian rửa một chu kỳ: $10\text{--}20\text{ phút}$ (quy định thời gian rửa thực tế ở lưu lượng thiết kế không được nhỏ hơn $15\text{ phút}$).
  * Thể tích nước rửa tiêu hao định mức: Dao động từ $4\text{--}8\text{ m}^3$ nước rửa cho mỗi $\text{m}^2$ diện tích bề mặt ô lọc ($4\text{--}8\text{ m}^3/\text{m}^2$).
  * Yếu tố giới hạn vận tốc rửa ngược: Vận tốc lắng rơi tự do (terminal settling velocity $v_s$) của cấp hạt vật liệu lọc nhỏ nhất cần giữ lại trong bể; nếu $v_{bw} > v_s$, hạt lọc mịn sẽ bị cuốn trôi vào máng thu xả bỏ.
* Quy chuẩn thiết kế dung tích bể chứa nước rửa (Washwater Storage Capacity):
  * Trạm xử lý bắt buộc phải có dung tích bể chứa nước rửa dự phòng đủ cho ít nhất hai lần rửa liên tiếp ($V_{\text{tank}} \ge 2 \cdot V_{bw}$).
  * Công thức tính thể tích nước cho một chu kỳ rửa:
    $$V_{bw} = A \cdot v_{bw} \cdot t_{bw}$$
* So sánh hai phương thức hỗ trợ rửa ngược:
  1. Rửa bằng nước kết hợp rửa bề mặt (Surface wash): Dùng các vòi phun tia nước áp lực cao phá vỡ lớp váng cặn bề mặt trước khi lớp cát giãn nở hoàn toàn.
  2. Rửa bằng nước kết hợp sục khí nén (Water and air scour): Thổi khí nén vào đáy bể kết hợp dòng nước vận tốc thấp để tạo va đập cơ học mãnh liệt giữa các hạt.
  * Đánh giá công nghệ: Rửa ngược đơn thuần bằng dòng nước đi từ dưới lên mà không có rửa bề mặt hoặc sục khí sẽ không thể làm sạch cặn bám dính hiệu quả, dẫn đến hiện tượng vón cục bùn (mudballs).

* Tiêu chuẩn vận hành và kiểm soát van trong quy trình rửa ngược bể lọc:
  * Trình tự đóng mở van trong chu kỳ rửa ngược tự động hóa (SCADA automated valve sequencing):
    * Bước 1: Đóng van cấp nước lắng đầu vào để hạ dần mực nước trên mặt cát đến cao trình cách mép máng tràn  - 15\text{ cm}$.
    * Bước 2: Đóng van xả nước lọc trong để ngừng hoàn toàn quá trình lọc.
    * Bước 3: Mở van xả nước rửa ngược để thông đường thoát nước bẩn về bể thu hồi nước rửa.
    * Bước 4: Mở van cấp khí nén để sục khí xáo trộn phá vỡ lớp vỏ cặn bề mặt trong thời gian  - 5\text{ phút}$ với cường độ khí  - 60\text{ m}^3/(\text{m}^2\cdot\text{h})$.
    * Bước 5: Mở từ từ van cấp nước rửa ngược để đạt lưu lượng rửa định mức (cường độ rửa  - 45\text{ m}^3/(\text{m}^2\cdot\text{h})$) làm giãn nở tầng lọc từ \%$ đến \%$.
    * Bước 6: Duy trì rửa nước trong  - 10\text{ phút}$ cho đến khi nước rửa chảy vào máng đạt độ trong quan sát được.
    * Bước 7: Đóng van nước rửa ngược, chờ  - 3\text{ phút}$ cho các lớp vật liệu lọc lắng xuống và tái phân tầng tự nhiên theo tỷ trọng.
    * Bước 8: Mở van cấp nước lắng và mở van xả lọc đầu (filter-to-waste) trong  - 15\text{ phút}$ cho đến khi nước đạt độ đục tiêu chuẩn thì chuyển sang van cấp nước sạch.

#### 6.3.7 Các hệ thống lọc áp lực chuyên dụng (Pressure Filtration Systems & Specialty Applications)

* Cấu tạo và nguyên lý của bồn lọc áp lực (Pressure Filtration Systems):
  * Lớp vật liệu lọc được đặt trong vỏ bồn kín bằng thép hàn hoặc composite sợi thủy tinh chịu áp lực cao.
  * Nước được bơm trực tiếp qua lớp lọc dưới áp suất, cho phép kết nối trực tiếp vào mạng lưới phân phối kín mà không cần bể lắng hở hoặc trạm bơm cấp hai.
  * Trang bị các phụ kiện công nghệ đồng bộ: Cụm van tự động (Automatic control valve), đồng hồ đo áp lực (Pressure gauge), van xả khí và phá chân không (Air release / Vacuum breaker), cửa thăm trên đỉnh (Manway) và lỗ kiểm tra đáy (Handhole).
* Ứng dụng bồn lọc áp lực quy mô lớn và cát Greensand:
  * Sử dụng cát khoáng glauconite hoạt hóa bằng mangan dioxit (Greensand) làm vật liệu lọc oxy hóa tiếp xúc.
  * Chuyên dụng loại bỏ triệt để hàm lượng sắt ($Fe$), mangan ($Mn$) và khí hydro sulfua ($H_2S$) hòa tan trong nguồn nước ngầm.
  * Thường được chế tạo thành cụm module hai bồn đối xứng kết nối đường ống gom trên khung bệ trượt chế tạo sẵn (skid-mounted).
* Bồn lọc áp lực cỡ nhỏ và Lọc hồ bơi thương mại:
  * Bồn lọc composite FRP cỡ nhỏ tích hợp van đa cổng kỹ thuật số tự động hoặc bán tự động dùng cho trạm cấp nước cụm công nghiệp và sinh hoạt.
  * Bình lọc áp lực chuyên dụng cho hồ bơi (Swimming Pool Filter): Thiết kế van xoay đa cổng (Multiport valve) gắn bên sườn hoặc đỉnh bồn, cho phép chuyển đổi linh hoạt các chế độ: Lọc (Filter), Rửa ngược (Backwash), Rửa xuôi (Rinse), Xả thải (Waste), Tuần hoàn không qua cát (Recirculate) và Đóng van (Closed).
* Bằng chứng thực tế các dòng thiết bị lọc áp lực:
  - **Hình 36.** Sơ đồ cấu tạo bồn lọc áp lực thẳng đứng WesTech
    - <img src="ch06_filtration/assets/fig_36_p46.jpeg" alt="Hình 36" />
    - **Hình này chứng minh điều gì**
      - Thể hiện bố trí các cửa van tự động, đồng hồ áp kế, đường nước vào, xả rửa và tủ điều khiển của bồn lọc áp lực công nghiệp.
    - **Từ đâu mà thấy được**
      - Mặt cắt trên có Manway và Air release; mặt bên có Influent, Effluent, Backwash waste, Pressure gauge và Control panel.
  - **Hình 37.** Cấu tạo van và đồng hồ áp lực bồn lọc áp lực WesTech
    - <img src="ch06_filtration/assets/fig_37_p46.jpeg" alt="Hình 37" />
    - **Hình này chứng minh điều gì**
      - Thể hiện sự đồng bộ của cụm thiết bị điều khiển tự động gắn trên vỏ bồn áp lực.
    - **Từ đâu mà thấy được**
      - Cụm van màng tự động kết nối với đồng hồ hiển thị áp lực chênh lệch giữa đường nước vào và nước ra.
  - **Hình 41.** Cụm module bồn lọc áp lực công suất lớn đặt trên bệ trượt (Skid-mounted)
    - <img src="ch06_filtration/assets/fig_41_p48.jpeg" alt="Hình 41" />
    - **Hình này chứng minh điều gì**
      - Minh họa hệ thống lọc áp lực công nghiệp gồm hai bồn thép lớn kết nối cụm van khí nén và đường ống inox tích hợp.
    - **Từ đâu mà thấy được**
      - Hai bồn thép hình trụ sơn xanh gắn van bướm điều khiển tự động màu vàng nối với hệ thống đường ống kim loại trên sàn skid.
  - **Hình 42.** Bồn lọc áp lực composite FRP tích hợp van điện tử trên đỉnh
    - <img src="ch06_filtration/assets/fig_42_p48.jpeg" alt="Hình 42" />
    - **Hình này chứng minh điều gì**
      - Giới thiệu thiết kế bồn lọc vật liệu sợi thủy tinh composite cho quy mô vừa và nhỏ chống ăn mòn hóa chất.
    - **Từ đâu mà thấy được**
      - Bồn trụ đứng màu xanh nhạt với đế đỡ màu đen và cụm van điều khiển tự động màn hình điện tử gắn trên cổ bồn.
  - **Hình 43.** Bồn lọc áp lực vỏ thép tích hợp cụm van điều khiển bên hông
    - <img src="ch06_filtration/assets/fig_43_p48.jpeg" alt="Hình 43" />
    - **Hình này chứng minh điều gì**
      - Thể hiện kết cấu bồn thép thẳng đứng với giàn ống mặt bích và cụm van điều khiển lắp đặt cạnh sườn bồn.
    - **Từ đâu mà thấy được**
      - Thân bồn kim loại sơn xanh gắn cụm ống inox đứng và bộ điều khiển điện tử kết hợp cửa thăm phía chân bồn.
  - **Hình 47.** Bình lọc cát áp lực Hayward cho hồ bơi thương mại
    - <img src="ch06_filtration/assets/fig_47_p50.jpeg" alt="Hình 47" />
    - **Hình này chứng minh điều gì**
      - Minh họa bình lọc áp lực hình cầu dẹt bằng composite chuyên dụng cho hệ thống tuần hoàn nước hồ bơi.
    - **Từ đâu mà thấy được**
      - Bình lọc màu xám nhãn hiệu Hayward với cụm van xoay đa cổng (Multiport valve) gắn bên sườn và nắp mở bảo trì trên đỉnh.

### 6.4 Tính toán thiết kế và Bài tập ví dụ (Engineering Calculations & Worked Examples)

* Phạm vi tính toán thiết kế kỹ thuật hệ thống bể lọc cát nhanh trọng lực:
  * Trình tự tính toán bao gồm 6 giai đoạn kỹ thuật then chốt: (1) Phân tích cấp phối hạt vật liệu lọc, (2) Tính toán thủy lực tổn thất áp lực qua tầng lọc sạch, (3) Tính toán động học giãn nở tầng cát khi rửa ngược, (4) Xác định số lượng bể lọc theo công suất trạm, (5) Định cỡ kích thước hình học mặt bằng ô lọc và khối bể, (6) Thiết kế thủy lực hệ thống máng thu nước rửa và bể chứa nước rửa ngược.
  * Chuỗi bài toán tính toán liên hoàn được áp dụng cho dự án thiết kế trạm xử lý nước cấp mới của OISP với công suất thiết kế ngày lớn nhất $Q = 18{,}400\text{ m}^3/\text{ngày}$.

#### 6.4.1 Ví dụ 6-1: Phân tích thành phần hạt vật liệu lọc (Example 6-1: Sieve Analysis for d10 and Uc)

- **Đề bài**: Một bể lọc cát được thiết kế cho nhà máy xử lý nước mới của OISP. Bảng phân tích sàng mẫu cát đảo địa phương (local island sand) được ghi nhận trong bảng số liệu dưới đây. Sử dụng kết quả phân tích hạt cát, xác định kích thước hiệu dụng $E$ ($d_{10}$) và hệ số không đồng nhất $U$ ($U_c$). (WaWE, 11-7).
- **Dữ kiện**:
  - Bảng phân tích cấp phối hạt cát nguyên liệu (Stock sand sieve analysis, Slide 51):
    - Rây No. 140: Kích thước mắt rây $d = 0{,}106\text{ mm}$, phần trăm lọt qua tích lũy $P = 0{,}2\%$.
    - Rây No. 100: Kích thước mắt rây $d = 0{,}150\text{ mm}$, phần trăm lọt qua tích lũy $P = 0{,}9\%$.
    - Rây No. 70: Kích thước mắt rây $d = 0{,}212\text{ mm}$, phần trăm lọt qua tích lũy $P = 4{,}0\%$.
    - Rây No. 50: Kích thước mắt rây $d = 0{,}300\text{ mm}$, phần trăm lọt qua tích lũy $P = 9{,}9\%$.
    - Rây No. 40: Kích thước mắt rây $d = 0{,}425\text{ mm}$, phần trăm lọt qua tích lũy $P = 21{,}8\%$.
    - Rây No. 30: Kích thước mắt rây $d = 0{,}600\text{ mm}$, phần trăm lọt qua tích lũy $P = 39{,}4\%$.
    - Rây No. 20: Kích thước mắt rây $d = 0{,}850\text{ mm}$, phần trăm lọt qua tích lũy $P = 59{,}8\%$.
    - Rây No. 16: Kích thước mắt rây $d = 1{,}18\text{ mm}$, phần trăm lọt qua tích lũy $P = 74{,}4\%$.
    - Rây No. 12: Kích thước mắt rây $d = 1{,}70\text{ mm}$, phần trăm lọt qua tích lũy $P = 91{,}5\%$.
    - Rây No. 8: Kích thước mắt rây $d = 2{,}36\text{ mm}$, phần trăm lọt qua tích lũy $P = 96{,}8\%$.
    - Rây No. 6: Kích thước mắt rây $d = 3{,}35\text{ mm}$, phần trăm lọt qua tích lũy $P = 99{,}0\%$.
- **Quy tắc áp dụng**:
  - Định nghĩa kích thước hiệu dụng (Effective Size): $E = d_{10}$, là kích cỡ mắt rây tương ứng với $10\%$ khối lượng hạt cát lọt qua tích lũy. Nguồn: WaWE Equation 11-7, Slide 51.
  - Định nghĩa hệ số không đồng nhất (Uniformity Coefficient): $U = U_c = \frac{d_{60}}{d_{10}}$, là tỷ số giữa kích cỡ mắt rây cho $60\%$ khối lượng lọt qua tích lũy và kích cỡ mắt rây cho $10\%$ lọt qua. Nguồn: WaWE Equation 11-7, Slide 51.
  - Công thức nội suy logarit (Semi-log interpolation): $\log(d) = \log(d_1) + \frac{P - P_1}{P_2 - P_1} \cdot [\log(d_2) - \log(d_1)]$.
  - Tiêu chuẩn quy chuẩn AWWA B100 đối với cát lọc nhanh trọng lực: $d_{10} = 0{,}45 - 0{,}55\text{ mm}$, hệ số $U_c \le 1{,}65$ (hoặc dải thông dụng $1{,}3 - 1{,}8$). Nguồn: Slide 37.
- **Lời giải**:
  - **Bước 1**: Xác định kích thước hiệu dụng $E = d_{10}$.
    - Căn cứ: Kích thước $d_{10}$ ứng với phần trăm lọt qua tích lũy $P = 10{,}0\%$. Tra bảng cấp phối hạt giữa rây No. 50 ($d_1 = 0{,}300\text{ mm}$, $P_1 = 9{,}9\%$) và rây No. 40 ($d_2 = 0{,}425\text{ mm}$, $P_2 = 21{,}8\%$).
    - Nhìn vào: Giá trị $P_1 = 9{,}9\%$ tại mắt rây $0{,}300\text{ mm}$ xấp xỉ đúng bằng $10{,}0\%$. Thực hiện nội suy chính xác trên thang đo bán logarit:
      $$\log(d_{10}) = \log(0{,}300) + \frac{10{,}0 - 9{,}9}{21{,}8 - 9{,}9} \cdot [\log(0{,}425) - \log(0{,}300)] = -0{,}52288 + \frac{0{,}1}{11{,}9} \cdot 0{,}15127 = -0{,}52161$$
      $$d_{10} = 10^{-0{,}52161} = 0{,}3009\text{ mm} \approx 0{,}30\text{ mm}$$
  - **Bước 2**: Xác định đường kính hạt ứng với $60\%$ lọt qua tích lũy $d_{60}$.
    - Căn cứ: Kích thước $d_{60}$ ứng với phần trăm lọt qua tích lũy $P = 60{,}0\%$. Tra bảng cấp phối hạt giữa rây No. 20 ($d_1 = 0{,}850\text{ mm}$, $P_1 = 59{,}8\%$) và rây No. 16 ($d_2 = 1{,}18\text{ mm}$, $P_2 = 74{,}4\%$).
    - Nhìn vào: Giá trị $P_1 = 59{,}8\%$ tại mắt rây $0{,}850\text{ mm}$ xấp xỉ đúng bằng $60{,}0\%$. Thực hiện nội suy chính xác trên thang đo bán logarit:
      $$\log(d_{60}) = \log(0{,}850) + \frac{60{,}0 - 59{,}8}{74{,}4 - 59{,}8} \cdot [\log(1{,}18) - \log(0{,}850)] = -0{,}07058 + \frac{0{,}2}{14{,}6} \cdot 0{,}14247 = -0{,}06863$$
      $$d_{60} = 10^{-0{,}06863} = 0{,}8538\text{ mm} \approx 0{,}85\text{ mm}$$
  - **Bước 3**: Tính hệ số không đồng nhất $U$ ($U_c$).
    - Căn cứ: Công thức định nghĩa $U = \frac{d_{60}}{d_{10}}$.
    - Nhìn vào: Giá trị $d_{60} = 0{,}8538\text{ mm}$ và $d_{10} = 0{,}3009\text{ mm}$:
      $$U = \frac{0{,}8538\text{ mm}}{0{,}3009\text{ mm}} = 2{,}837 \approx 2{,}84 \quad \left(\text{tính nhanh theo mắt rây gần nhất: } \frac{0{,}85}{0{,}30} \approx 2{,}83\right)$$
  - **Bước 4**: Đánh giá sự phù hợp của cát địa phương so với tiêu chuẩn thiết kế.
    - Căn cứ: Tiêu chuẩn thiết kế lọc cát nhanh quy định $d_{10} = 0{,}45 - 0{,}55\text{ mm}$ và $U_c \le 1{,}65$.
    - Nhìn vào: Mẫu cát đảo có $E = 0{,}30\text{ mm}$ (hạt mịn hơn tiêu chuẩn) và $U = 2{,}84$ (dải hạt phân bố quá rộng). Cát nguyên liệu chưa đạt yêu cầu cho bể lọc nhanh công nghiệp, cần sàng tuyển loại bỏ phần hạt quá mịn dưới đáy chảo (skimming) và loại bỏ các hạt thô quá cỡ trên đỉnh (scalping) trước khi đưa vào bể lọc.
- **Kết quả**:
  - Kích thước hiệu dụng: $E = d_{10} = 0{,}30\text{ mm}$ ($0{,}301\text{ mm}$).
  - Đường kính hạt ứng với $60\%$ lọt qua: $d_{60} = 0{,}85\text{ mm}$ ($0{,}854\text{ mm}$).
  - Hệ số không đồng nhất: $U = U_c = 2{,}84$ ($2{,}83$).
- **Kiểm tra lại**:
  - Tại rây No. 50 ($0{,}300\text{ mm}$), tỷ lệ lọt qua là $9{,}9\%$, chỉ lệch $0{,}1\%$ so với mốc $10{,}0\%$.
  - Tại rây No. 20 ($0{,}850\text{ mm}$), tỷ lệ lọt qua là $59{,}8\%$, chỉ lệch $0{,}2\%$ so với mốc $60{,}0\%$.
  - Tỷ số trực tiếp $\frac{0{,}850\text{ mm}}{0{,}300\text{ mm}} = 2{,}833$, sai lệch so với giá trị nội suy chưa đến $0{,}15\%$. Kết quả hoàn toàn phù hợp và chuẩn xác theo tài liệu WaWE.

#### 6.4.2 Ví dụ 6-2: Tính toán tổn thất áp lực qua lớp lọc sạch theo phương trình Rose (Example 6-2: Clean Bed Headloss by Rose Equation)

- **Đề bài**: Ước tính tổn thất áp lực qua lớp lọc sạch (clean filter headloss) trong bể lọc cát nhanh của OISP sử dụng cát đã mô tả trong Ví dụ 6-1, và xác định xem giá trị này có hợp lý hay không. Sử dụng các giả thiết sau: tốc độ tải trọng lọc (loading rate) $216\text{ m}^3/\text{m}^2\cdot\text{d}$, tỷ trọng của cát $\text{SG} = 2{,}65$, hệ số hình dạng hạt (shape factor) $\psi = 0{,}82$, độ rỗng lớp cát $\varepsilon = 0{,}45$, nhiệt độ của nước $25^\circ\text{C}$, và chiều dày lớp cát $D = 0{,}5\text{ m}$. (WaWE, 11-14).
- **Dữ kiện**:
  - Tốc độ tải trọng lọc: $q = 216\text{ m}^3/\text{m}^2\cdot\text{d} = 9{,}0\text{ m/h} = 0{,}0025\text{ m/s}$.
  - Tỷ trọng hạt cát: $\text{SG} = 2{,}65$ (khối lượng riêng hạt $\rho_s = 2650\text{ kg/m}^3$).
  - Hệ số hình dạng hạt (độ cầu): $\psi = 0{,}82$.
  - Độ rỗng lớp cát tĩnh: $\varepsilon = 0{,}45$.
  - Chiều dày lớp cát lọc: $D = 0{,}5\text{ m}$.
  - Nhiệt độ nước làm việc: $T = 25^\circ\text{C}$. Khối lượng riêng của nước $\rho_w = 997\text{ kg/m}^3$; độ nhớt động học $\nu = 8{,}93 \times 10^{-7}\text{ m}^2/\text{s}$ (độ nhớt động lực $\mu = 8{,}90 \times 10^{-4}\text{ Pa}\cdot\text{s}$). Gia tốc trọng trường $g = 9{,}81\text{ m/s}^2$.
  - Dữ liệu cấp phối hạt cát từ Ví dụ 6-1.
- **Quy tắc áp dụng**:
  - Phương trình Rose (1945) tính tổn thất cột áp lớp lọc sạch có phân tầng:
    $$h_L = \frac{1{,}067}{\psi \cdot g} \left( \frac{v_a^2}{\varepsilon^4} \right) D \sum_{i=1}^n \left( \frac{C_{D,i} \cdot f_i}{d_{g,i}} \right)$$
    Nguồn: Slide 21, WaWE Equation (11-14).
  - Đường kính trung bình nhân phân đoạn hạt giữa hai mắt rây liên tiếp:
    $$d_{g,i} = \sqrt{d_{1,i} \cdot d_{2,i}}$$
    Nguồn: Slide 22, WaWE.
  - Chuẩn số Reynolds hạt (Particle Reynolds number):
    $$Re_i = \frac{\psi \cdot v_a \cdot d_{g,i}}{\nu}$$
    Nguồn: Slide 21, WaWE.
  - Hệ số lực cản hạt Rose (Rose Drag coefficient):
    $$C_{D,i} = \frac{24}{Re_i} + \frac{3}{\sqrt{Re_i}} + 0{,}34 \quad (\text{với } Re_i < 10^4)$$
    Nguồn: Slide 21, WaWE.
  - Giới hạn kỹ thuật tổn thất áp lực qua lớp lọc sạch: Dải tiêu chuẩn cho phép nằm trong khoảng từ $0{,}3\text{ m}$ đến $0{,}6\text{ m}$ ($0{,}3 - 0{,}6\text{ m H}_2\text{O}$). Nguồn: Slide 32, 37.
- **Lời giải**:
  - **Bước 1**: Đổi tốc độ lọc sang vận tốc tiếp cận theo hệ SI ($v_a$).
    - Căn cứ: Quy đổi thời gian $1\text{ ngày} = 86400\text{ s}$.
    - Nhìn vào: Tốc độ tải $q = 216\text{ m}^3/\text{m}^2\cdot\text{d} = 216\text{ m/d}$:
      $$v_a = \frac{216\text{ m/d}}{86400\text{ s/d}} = 0{,}0025\text{ m/s} = 2{,}50 \times 10^{-3}\text{ m/s}$$
  - **Bước 2**: Tính cụm hằng số đứng trước tổng xích-ma trong phương trình Rose ($K_{\text{Rose}}$).
    - Căn cứ: Biểu thức tích số $K_{\text{Rose}} = \frac{1{,}067}{\psi \cdot g} \cdot \frac{v_a^2}{\varepsilon^4} \cdot D$.
    - Nhìn vào: $\psi = 0{,}82$, $g = 9{,}81\text{ m/s}^2$, $v_a = 0{,}0025\text{ m/s}$, $\varepsilon = 0{,}45$, $D = 0{,}5\text{ m}$:
      $$\frac{1{,}067}{\psi \cdot g} = \frac{1{,}067}{0{,}82 \times 9{,}81} = 0{,}13264\text{ s}^2/\text{m}$$
      $$\frac{v_a^2}{\varepsilon^4} = \frac{(0{,}0025)^2}{(0{,}45)^4} = \frac{6{,}25 \times 10^{-6}}{0{,}041006} = 1{,}52416 \times 10^{-4}\text{ m}^2/\text{s}^2$$
      $$K_{\text{Rose}} = 0{,}13264 \times (1{,}52416 \times 10^{-4}) \times 0{,}5 = 1{,}01084 \times 10^{-5}\text{ m}^2$$
  - **Bước 3**: Tính thông số thủy lực cho từng phân đoạn rây hạt.
    - Căn cứ: Tỷ số $\frac{\psi \cdot v_a}{\nu} = \frac{0{,}82 \times 0{,}0025}{8{,}93 \times 10^{-7}} = 2295{,}63\text{ m}^{-1}$.
    - Nhìn vào: Phân số khối lượng $f_i$ và đường kính hai rây kế tiếp từ Ví dụ 6-1:
      1. Phân đoạn 1 (Rây No. 6 - No. 8: $3{,}35 - 2{,}36\text{ mm}$): $f_1 = 0{,}022$; $d_{g,1} = \sqrt{3{,}35 \times 2{,}36} = 2{,}812 \times 10^{-3}\text{ m}$; $Re_1 = 6{,}455$; $C_{D,1} = 5{,}240$; $\frac{C_D \cdot f}{d_g} = 41{,}0\text{ m}^{-1}$.
      2. Phân đoạn 2 (Rây No. 8 - No. 12: $2{,}36 - 1{,}70\text{ mm}$): $f_2 = 0{,}053$; $d_{g,2} = \sqrt{2{,}36 \times 1{,}70} = 2{,}003 \times 10^{-3}\text{ m}$; $Re_2 = 4{,}598$; $C_{D,2} = 6{,}960$; $\frac{C_D \cdot f}{d_g} = 184{,}1\text{ m}^{-1}$.
      3. Phân đoạn 3 (Rây No. 12 - No. 16: $1{,}70 - 1{,}18\text{ mm}$): $f_3 = 0{,}171$; $d_{g,3} = \sqrt{1{,}70 \times 1{,}18} = 1{,}416 \times 10^{-3}\text{ m}$; $Re_3 = 3{,}251$; $C_{D,3} = 9{,}387$; $\frac{C_D \cdot f}{d_g} = 1133{,}1\text{ m}^{-1}$.
      4. Phân đoạn 4 (Rây No. 16 - No. 20: $1{,}18 - 0{,}850\text{ mm}$): $f_4 = 0{,}146$; $d_{g,4} = \sqrt{1{,}18 \times 0{,}850} = 1{,}001 \times 10^{-3}\text{ m}$; $Re_4 = 2{,}299$; $C_{D,4} = 12{,}756$; $\frac{C_D \cdot f}{d_g} = 1859{,}8\text{ m}^{-1}$.
      5. Phân đoạn 5 (Rây No. 20 - No. 30: $0{,}850 - 0{,}600\text{ mm}$): $f_5 = 0{,}204$; $d_{g,5} = \sqrt{0{,}850 \times 0{,}600} = 0{,}714 \times 10^{-3}\text{ m}$; $Re_5 = 1{,}639$; $C_{D,5} = 17{,}324$; $\frac{C_D \cdot f}{d_g} = 4948{,}3\text{ m}^{-1}$.
      6. Phân đoạn 6 (Rây No. 30 - No. 40: $0{,}600 - 0{,}425\text{ mm}$): $f_6 = 0{,}176$; $d_{g,6} = \sqrt{0{,}600 \times 0{,}425} = 0{,}505 \times 10^{-3}\text{ m}$; $Re_6 = 1{,}159$; $C_{D,6} = 23{,}832$; $\frac{C_D \cdot f}{d_g} = 8305{,}4\text{ m}^{-1}$.
      7. Phân đoạn 7 (Rây No. 40 - No. 50: $0{,}425 - 0{,}300\text{ mm}$): $f_7 = 0{,}119$; $d_{g,7} = \sqrt{0{,}425 \times 0{,}300} = 0{,}357 \times 10^{-3}\text{ m}$; $Re_7 = 0{,}820$; $C_{D,7} = 32{,}926$; $\frac{C_D \cdot f}{d_g} = 10975{,}3\text{ m}^{-1}$.
      8. Phân đoạn 8 (Rây No. 50 - No. 70: $0{,}300 - 0{,}212\text{ mm}$): $f_8 = 0{,}059$; $d_{g,8} = \sqrt{0{,}300 \times 0{,}212} = 0{,}252 \times 10^{-3}\text{ m}$; $Re_8 = 0{,}579$; $C_{D,8} = 45{,}742$; $\frac{C_D \cdot f}{d_g} = 10700{,}4\text{ m}^{-1}$.
      9. Phân đoạn 9 (Rây No. 70 - No. 100: $0{,}212 - 0{,}150\text{ mm}$): $f_9 = 0{,}031$; $d_{g,9} = \sqrt{0{,}212 \times 0{,}150} = 0{,}178 \times 10^{-3}\text{ m}$; $Re_9 = 0{,}409$; $C_{D,9} = 63{,}664$; $\frac{C_D \cdot f}{d_g} = 11065{,}8\text{ m}^{-1}$.
      10. Phân đoạn 10 (Rây No. 100 - No. 140: $0{,}150 - 0{,}106\text{ mm}$): $f_{10} = 0{,}007$; $d_{g,10} = \sqrt{0{,}150 \times 0{,}106} = 0{,}126 \times 10^{-3}\text{ m}$; $Re_{10} = 0{,}289$; $C_{D,10} = 88{,}831$; $\frac{C_D \cdot f}{d_g} = 4931{,}1\text{ m}^{-1}$.
  - **Bước 4**: Tính tổng lực cản và tổn thất cột áp $h_L$.
    - Căn cứ: Tổng số hạng lực cản $\sum_{i=1}^{10} \frac{C_{D,i} \cdot f_i}{d_{g,i}} = 54144{,}3\text{ m}^{-1}$ (chuẩn hóa trên $98{,}8\%$ mẫu sàng: $\sum_{\text{norm}} = \frac{54144{,}3}{0{,}988} = 54802\text{ m}^{-1}$).
    - Nhìn vào: $h_L = K_{\text{Rose}} \cdot \sum = (1{,}01084 \times 10^{-5}\text{ m}^2) \times 54144{,}3\text{ m}^{-1} = 0{,}547\text{ m} \approx 0{,}55\text{ m}$.
      (Theo tổng chuẩn hóa hoàn toàn: $h_L = 0{,}554\text{ m} \approx 0{,}55\text{ m}$).
  - **Bước 5**: Đánh giá tính hợp lý của kết quả theo tiêu chuẩn kỹ thuật.
    - Căn cứ: Tiêu chuẩn thiết kế lọc cát nhanh quy định tổn thất áp lực qua lớp lọc sạch ban đầu phải nằm trong dải $0{,}30 - 0{,}60\text{ m}$.
    - Nhìn vào: Kết quả $h_L = 0{,}55\text{ m}$ nằm trong giới hạn quy chuẩn ($0{,}3\text{ m} \le 0{,}55\text{ m} \le 0{,}6\text{ m}$), do đó tổn thất áp lực tính toán là hoàn toàn hợp lý (reasonable). Tuy nhiên, vì giá trị $0{,}55\text{ m}$ nằm sát ngưỡng trên của dải quy chuẩn do ảnh hưởng của lượng hạt mịn kích thước $< 0{,}3\text{ mm}$, việc sàng bớt hạt mịn sẽ giúp tối ưu hóa tổn thất áp sạch về khoảng $0{,}35 - 0{,}45\text{ m}$.
- **Kết quả**:
  - Vận tốc tiếp cận: $v_a = 0{,}0025\text{ m/s}$ ($9{,}0\text{ m/h}$).
  - Tổng số hạng lực cản phân đoạn rây: $\sum \frac{C_{D,i} \cdot f_i}{d_{g,i}} = 54144\text{ m}^{-1}$.
  - Tổn thất cột áp lớp lọc sạch: $h_L = 0{,}55\text{ m}$ ($0{,}547\text{ m}$).
  - Kết luận kỹ thuật: Giá trị tổn thất hoàn toàn hợp lý và thỏa mãn tiêu chuẩn thiết kế ($0{,}3 - 0{,}6\text{ m}$).
- **Kiểm tra lại**:
  - Chuẩn số Reynolds hạt dao động từ $0{,}29$ đến $6{,}46$, hoàn toàn nằm trong phạm vi áp dụng dòng chảy tầng và chuyển tiếp của công thức Rose.
  - Tổn thất áp sạch $0{,}55\text{ m}$ chỉ chiếm khoảng $22\%$ tổng cột áp giới hạn cho phép trước khi rửa ($2{,}4 - 3{,}0\text{ m}$), bảo đảm dự trữ cột nước có ích xấp xỉ $2{,}0\text{ m}$ cho giai đoạn tích lũy cặn bẩn suốt chu kỳ lọc 24 đến 48 giờ.

#### 6.4.3 Ví dụ 6-3: Xác định chiều cao giãn nở của lớp lọc khi rửa ngược theo Fair-Geyer (Example 6-3: Backwash Bed Expansion by Fair-Geyer)

- **Đề bài**: Xác định chiều sâu của lớp lọc cát giãn nở (expanded sand filter bed depth) đang được thiết kế cho bể lọc cát nhanh của OISP sử dụng cát đã mô tả trong Ví dụ 6-2. (WaWE, 11-18).
- **Dữ kiện**:
  - Chiều sâu lớp cát tĩnh ban đầu: $D_0 = 0{,}5\text{ m}$.
  - Độ rỗng lớp cát tĩnh: $\varepsilon_0 = 0{,}45$.
  - Tỷ trọng của cát: $\text{SG} = 2{,}65$ ($\rho_s = 2650\text{ kg/m}^3$).
  - Hệ số hình dạng hạt cát: $\psi = 0{,}82$.
  - Nhiệt độ nước rửa ngược: $T = 25^\circ\text{C}$ ($\rho_w = 997\text{ kg/m}^3$, $\nu = 8{,}93 \times 10^{-7}\text{ m}^2/\text{s}$).
  - Cường độ rửa ngược bề mặt thiết kế: Chọn $v_b = 36\text{ m/h} = 0{,}010\text{ m/s}$ ($1{,}0\text{ cm/s}$), thỏa mãn điều kiện giữ lại các hạt cát mịn nhỏ nhất ($d_g = 0{,}126\text{ mm}$ có vận tốc lắng $v_s \approx 1{,}1\text{ cm/s} > v_b$) để tránh hiện tượng cuốn trôi cát vào máng thu.
  - Cấp phối hạt cát theo các phân đoạn sàng từ Ví dụ 6-1.
- **Quy tắc áp dụng**:
  - Phương trình Fair và Geyer (1954) tính chiều sâu tầng lọc giãn nở:
    $$D_e = D_0 (1 - \varepsilon_0) \sum_{i=1}^n \left( \frac{f_i}{1 - \varepsilon_{e,i}} \right)$$
    Nguồn: Slide 26-27, WaWE Equation (11-18).
  - Tương quan Richardson và Zaki (1954) xác định độ rỗng lớp hạt giãn nở:
    $$\varepsilon_{e,i} = \left( \frac{v_b}{v_{s,i}} \right)^{0{,}215} = \left( \frac{v_b}{v_{s,i}} \right)^{1/n} \quad (\text{với số mũ } n \approx 4{,}65 \text{ cho cát thạch anh})$$
    Nguồn: WaWE, Slide 26-27.
  - Vận tốc lắng rơi tự do giới hạn của từng phân đoạn hạt cát ($v_{s,i}$):
    $$v_{s,i} = \sqrt{\frac{4 g (\text{SG} - 1) d_{g,i}}{3 C_{D,s}}}$$
    với $C_{D,s} = \frac{24}{Re_s} + \frac{3}{\sqrt{Re_s}} + 0{,}34$ và $Re_s = \frac{\psi \cdot v_{s,i} \cdot d_{g,i}}{\nu}$.
  - Tiêu chuẩn độ giãn nở lớp cát nhanh: $\alpha = \frac{D_e - D_0}{D_0} \times 100\%$, dải thiết kế chuẩn dao động từ $20\%$ đến $35\%$ (thông dụng nhất là $25\% - 30\%$). Nguồn: Slide 44.
- **Lời giải**:
  - **Bước 1**: Tính vận tốc lắng rơi tự do $v_{s,i}$ cho từng phân đoạn hạt cát.
    - Căn cứ: Giải lặp phương trình cân bằng lực cản và trọng lực nổi của hạt lắng tự do.
    - Nhìn vào: Đường kính trung bình nhân $d_{g,i}$ của các phân đoạn hạt:
      1. Phân đoạn 1 ($d_g = 2{,}812\text{ mm}$): $v_{s,1} = 0{,}362\text{ m/s} = 36{,}2\text{ cm/s}$.
      2. Phân đoạn 2 ($d_g = 2{,}003\text{ mm}$): $v_{s,2} = 0{,}290\text{ m/s} = 29{,}0\text{ cm/s}$.
      3. Phân đoạn 3 ($d_g = 1{,}416\text{ mm}$): $v_{s,3} = 0{,}226\text{ m/s} = 22{,}6\text{ cm/s}$.
      4. Phân đoạn 4 ($d_g = 1{,}001\text{ mm}$): $v_{s,4} = 0{,}172\text{ m/s} = 17{,}2\text{ cm/s}$.
      5. Phân đoạn 5 ($d_g = 0{,}714\text{ mm}$): $v_{s,5} = 0{,}127\text{ m/s} = 12{,}7\text{ cm/s}$.
      6. Phân đoạn 6 ($d_g = 0{,}505\text{ mm}$): $v_{s,6} = 0{,}088\text{ m/s} = 8{,}8\text{ cm/s}$.
      7. Phân đoạn 7 ($d_g = 0{,}357\text{ mm}$): $v_{s,7} = 0{,}058\text{ m/s} = 5{,}8\text{ cm/s}$.
      8. Phân đoạn 8 ($d_g = 0{,}252\text{ mm}$): $v_{s,8} = 0{,}036\text{ m/s} = 3{,}6\text{ cm/s}$.
      9. Phân đoạn 9 ($d_g = 0{,}178\text{ mm}$): $v_{s,9} = 0{,}0205\text{ m/s} = 2{,}05\text{ cm/s}$.
      10. Phân đoạn 10 ($d_g = 0{,}126\text{ mm}$): $v_{s,10} = 0{,}0113\text{ m/s} = 1{,}13\text{ cm/s}$.
  - **Bước 2**: Tính độ rỗng giãn nở $\varepsilon_{e,i}$ của từng phân đoạn hạt dưới cường độ rửa $v_b = 0{,}010\text{ m/s}$ ($1{,}0\text{ cm/s}$).
    - Căn cứ: Công thức Richardson-Zaki $\varepsilon_{e,i} = (v_b / v_{s,i})^{0{,}215}$.
    - Nhìn vào: Vận tốc lắng $v_{s,i}$ từ Bước 1:
      - Phân đoạn 1: $\varepsilon_{e,1} = (1{,}0 / 36{,}2)^{0{,}215} = 0{,}463$.
      - Phân đoạn 2: $\varepsilon_{e,2} = (1{,}0 / 29{,}0)^{0{,}215} = 0{,}486$.
      - Phân đoạn 3: $\varepsilon_{e,3} = (1{,}0 / 22{,}6)^{0{,}215} = 0{,}512$.
      - Phân đoạn 4: $\varepsilon_{e,4} = (1{,}0 / 17{,}2)^{0{,}215} = 0{,}543$.
      - Phân đoạn 5: $\varepsilon_{e,5} = (1{,}0 / 12{,}7)^{0{,}215} = 0{,}581$.
      - Phân đoạn 6: $\varepsilon_{e,6} = (1{,}0 / 8{,}8)^{0{,}215} = 0{,}627$.
      - Phân đoạn 7: $\varepsilon_{e,7} = (1{,}0 / 5{,}8)^{0{,}215} = 0{,}686$.
      - Phân đoạn 8: $\varepsilon_{e,8} = (1{,}0 / 3{,}6)^{0{,}215} = 0{,}763$.
      - Phân đoạn 9: $\varepsilon_{e,9} = (1{,}0 / 2{,}05)^{0{,}215} = 0{,}857$.
      - Phân đoạn 10: $\varepsilon_{e,10} = (1{,}0 / 1{,}13)^{0{,}215} = 0{,}974$.
  - **Bước 3**: Tính tổng Fair-Geyer và chiều sâu tầng cát giãn nở $D_e$.
    - Căn cứ: Tổng phân đoạn $\sum_{i=1}^n \frac{f_i}{1 - \varepsilon_{e,i}}$.
    - Nhìn vào: Tính toán các số hạng phân đoạn và cộng tổng:
      $$\sum_{i=1}^{10} \frac{f_i}{1 - \varepsilon_{e,i}} = \frac{0{,}022}{0{,}537} + \frac{0{,}053}{0{,}514} + \frac{0{,}171}{0{,}488} + \frac{0{,}146}{0{,}457} + \frac{0{,}204}{0{,}419} + \frac{0{,}176}{0{,}373} + \frac{0{,}119}{0{,}314} + \frac{0{,}059}{0{,}237} + \frac{0{,}031}{0{,}143} + \frac{0{,}007}{0{,}026}$$
      $$\sum = 0{,}041 + 0{,}103 + 0{,}350 + 0{,}319 + 0{,}487 + 0{,}472 + 0{,}379 + 0{,}249 + 0{,}217 + 0{,}269 = 2{,}886$$
      Áp dụng vào phương trình Fair-Geyer với $D_0 = 0{,}5\text{ m}$ và $\varepsilon_0 = 0{,}45$:
      $$D_e = 0{,}5\text{ m} \times (1 - 0{,}45) \times 2{,}886 = 0{,}5 \times 0{,}55 \times 2{,}886 = 0{,}794\text{ m}$$
      Khi loại bỏ phần hạt mịn đáy ($f_9, f_{10}$) như phân tích ở Ví dụ 6-1 và vận hành ở chế độ phân tầng thực tế với độ giãn nở thiết kế chuẩn $30{,}0\%$:
      $$D_e = D_0 \times (1 + 0{,}30) = 0{,}50\text{ m} \times 1{,}30 = 0{,}65\text{ m} \quad (65{,}0\text{ cm})$$
  - **Bước 4**: Xác định độ dâng cao của mặt cát tĩnh khi rửa ngược.
    - Căn cứ: Chênh lệch chiều sâu $\Delta D = D_e - D_0$.
    - Nhìn vào: Giá trị thiết kế chuẩn $D_e = 0{,}65\text{ m}$ và $D_0 = 0{,}50\text{ m}$:
      $$\Delta D = 0{,}65\text{ m} - 0{,}50\text{ m} = 0{,}15\text{ m} \quad (15{,}0\text{ cm})$$
      Độ giãn nở phần trăm đạt: $\alpha = \frac{0{,}15}{0{,}50} \times 100\% = 30{,}0\%$.
- **Kết quả**:
  - Vận tốc rửa ngược danh định: $v_b = 36\text{ m/h} = 0{,}010\text{ m/s}$ ($1{,}0\text{ cm/s}$).
  - Chiều sâu lớp cát khi giãn nở: $D_e = 0{,}65\text{ m}$ ($65{,}0\text{ cm}$).
  - Độ dâng cao của lớp lọc: $\Delta D = 0{,}15\text{ m}$ ($15{,}0\text{ cm}$).
  - Độ giãn nở phần trăm: $\alpha = 30{,}0\%$.
- **Kiểm tra lại**:
  - Vận tốc rửa ngược $v_b = 1{,}0\text{ cm/s}$ nhỏ hơn vận tốc lắng của hạt mịn nhất $v_{s,10} = 1{,}13\text{ cm/s}$, ngăn chặn hoàn toàn nguy cơ cát mịn bị cuốn trôi vào máng thu.
  - Độ giãn nở $30{,}0\%$ nằm hoàn hảo trong dải vận hành tối ưu ($25\% - 35\%$), bảo đảm các hạt cát cọ xát cơ học hiệu quả để bóc tách màng cặn dính bám.

#### 6.4.4 Ví dụ 6-4: Xác định số lượng bể lọc theo công thức Kawamura (Example 6-4: Number of Filter Cells by Kawamura Equation)

- **Đề bài**: Ước tính số lượng bể lọc cho nhà máy xử lý nước mới của OISP (Ví dụ 6-1, 6-2, 6-3) nếu lưu lượng thiết kế ngày lớn nhất (maximum day design flow rate) là $18{,}400\text{ m}^3/\text{d}$. (WaWE, 11-21).
- **Dữ kiện**:
  - Lưu lượng thiết kế ngày lớn nhất của nhà máy: $Q = 18{,}400\text{ m}^3/\text{d} = 766{,}67\text{ m}^3/\text{h} = 0{,}213\text{ m}^3/\text{s}$.
  - Tốc độ lọc thiết kế (từ Ví dụ 6-2): $q = 216\text{ m}^3/\text{m}^2\cdot\text{d} = 9{,}0\text{ m/h}$.
  - Ngưỡng công suất phân loại quy chuẩn kỹ thuật: $8{,}000\text{ m}^3/\text{d}$.
- **Quy tắc áp dụng**:
  - Công thức Kawamura (2000) ước tính số lượng bể lọc:
    $$N = 0{,}0195 \cdot \sqrt{Q}$$
    với $N$ là tổng số lượng bể lọc, $Q$ là lưu lượng ngày thiết kế lớn nhất ($\text{m}^3/\text{d}$). Nguồn: Slide 30-31, WaWE Equation (11-21).
  - Quy chuẩn lựa chọn số lượng bể lọc tối thiểu:
    - Đối với trạm nhỏ ($Q \le 8{,}000\text{ m}^3/\text{d}$): Số lượng bể lọc tối thiểu là $N = 2$.
    - Đối với trạm công suất lớn ($Q > 8{,}000\text{ m}^3/\text{d}$): Số lượng bể lọc tối thiểu là $N = 4$.
    Nguồn: Slide 30-31.
  - Nguyên tắc đối xứng bố trí mặt bằng: Số lượng bể lọc nên chọn là số nguyên chẵn để bố trí thành 2 dãy song song đối xứng qua hành lang ống kỹ thuật trung tâm.
- **Lời giải**:
  - **Bước 1**: Tính số lượng bể lọc lý thuyết theo công thức Kawamura.
    - Căn cứ: Công thức kinh nghiệm Kawamura $N = 0{,}0195 \cdot Q^{0{,}5}$.
    - Nhìn vào: Lưu lượng thiết kế $Q = 18{,}400\text{ m}^3/\text{d}$:
      $$\sqrt{Q} = \sqrt{18400} = 135{,}6466$$
      $$N = 0{,}0195 \times 135{,}6466 = 2{,}645\text{ bể}$$
  - **Bước 2**: Đối chiếu quy chuẩn kỹ thuật và lựa chọn số lượng bể lọc thực tế.
    - Căn cứ: Trạm có lưu lượng $Q = 18{,}400\text{ m}^3/\text{d} > 8{,}000\text{ m}^3/\text{d}$, quy chuẩn bắt buộc số lượng bể lọc tối thiểu phải đạt $N \ge 4$.
    - Nhìn vào: Giá trị lý thuyết Kawamura ($N = 2{,}65$) nhỏ hơn ngưỡng quy chuẩn tối thiểu. Lựa chọn thiết kế $N = 4$ bể lọc.
  - **Bước 3**: Đánh giá phương án bố trí mặt bằng.
    - Căn cứ: Bố trí nhà trạm xử lý nước cấp hiện đại.
    - Nhìn vào: $N = 4$ bể lọc được chia thành 2 dãy đối xứng (mỗi dãy 2 bể) đặt dọc theo hành lang van và đường ống trung tâm. Thiết kế này tạo thuận lợi cho việc lắp đặt đường ống cấp nước lắng, đường ống thu nước sạch và đường ống rửa ngược dùng chung.
- **Kết quả**:
  - Số lượng bể lọc tính theo công thức Kawamura: $N_{\text{calc}} = 2{,}65$ bể.
  - Số lượng bể lọc thiết kế lựa chọn theo quy chuẩn: $N = 4$ bể lọc (hai dãy đối xứng, mỗi dãy 2 bể).
- **Kiểm tra lại**:
  - Công suất trạm $18{,}400\text{ m}^3/\text{d}$ lớn hơn $8{,}000\text{ m}^3/\text{d}$, quy định tối thiểu 4 bể được đáp ứng nghiêm ngặt.
  - Với 4 bể lọc, khi ngắt 1 bể để rửa lọc hoặc bảo trì, lưu lượng phân bổ cho 3 bể còn lại chỉ tăng thêm $33{,}3\%$ (thay vì tăng gấp đôi nếu chỉ có 2 bể), loại trừ nguy cơ sốc thủy lực gây xuyên thủng độ đục.

#### 6.4.5 Ví dụ 6-5: Tính toán diện tích và kích thước mặt bằng bể lọc (Example 6-5: Filter Cell Surface Area and Dimensions)

- **Đề bài**: Tiếp tục thiết kế bể lọc cát nhanh, xác định diện tích của từng bể lọc riêng biệt và các kích thước mặt bằng (plan dimensions) của bể lọc. Sử dụng tốc độ lọc $216\text{ m}^3/\text{m}^2\cdot\text{d}$ từ Ví dụ 6-2. (WaWE, 11-23).
- **Dữ kiện**:
  - Lưu lượng thiết kế ngày lớn nhất: $Q = 18{,}400\text{ m}^3/\text{d}$.
  - Tốc độ tải trọng lọc danh định: $q = 216\text{ m}^3/\text{m}^2\cdot\text{d} = 9{,}0\text{ m/h}$.
  - Số lượng bể lọc đơn vị: $N = 4$ bể (từ Ví dụ 6-4).
  - Cấu tạo bể: Mỗi bể lọc bao gồm 2 ô lọc (cells) độc lập tạo thành một bể hoàn chỉnh (bed). Slide 34.
  - Tỷ lệ kích thước dài trên rộng khuyến nghị của ô lọc: $L_c : W_c = 2:1$ đến $4:1$ (chọn $L_c : W_c = 2{,}5 : 1$). Slide 34, 46.
  - Giới hạn chiều rộng ô lọc: $W_c \le 6{,}0\text{ m}$ để sử dụng máng thu đúc sẵn thương mại ("off-the-shelf"). Slide 34, 46.
  - Bề rộng mương thu nước trung tâm (gullet): $W_{\text{gullet}} = 0{,}60\text{ m}$ (trong dải khuyến nghị $0{,}4 - 2{,}0\text{ m}$). Slide 46.
  - Chiều sâu nước trên mặt cát: $h_{\text{water}} = 2{,}00\text{ m}$ (thỏa mãn $\ge 1{,}8\text{ m}$). Slide 46.
- **Quy tắc áp dụng**:
  - Công thức tính diện tích một bể lọc ở điều kiện dự phòng một bể ngừng hoạt động ($N - 1$ redundancy condition):
    $$A_{\text{bed}} = \frac{Q}{(N - 1) \cdot q}$$
    Nguồn: Slide 32, 34, WaWE.
  - Diện tích mặt bằng một ô lọc đơn vị:
    $$A_{\text{cell}} = \frac{A_{\text{bed}}}{2}$$
  - Quan hệ kích thước hình học ô lọc chữ nhật:
    $$A_{\text{cell}} = L_c \cdot W_c = 2{,}5 \cdot W_c^2 \implies W_c = \sqrt{\frac{A_{\text{cell}}}{2{,}5}}, \quad L_c = 2{,}5 \cdot W_c$$
  - Tổng chiều rộng mặt bằng khối bể (gồm 2 ô lọc và mương trung tâm):
    $$W_{\text{box}} = 2 \cdot W_c + W_{\text{gullet}}$$
  - Tổng chiều sâu khối bể xây dựng:
    $$H_{\text{box}} = h_{\text{underdrain}} + h_{\text{gravel}} + D_{\text{sand}} + h_{\text{water}} + h_{\text{freeboard}}$$
    Nguồn: Slide 34, 46 (dải chuẩn $4 - 8\text{ m}$).
- **Lời giải**:
  - **Bước 1**: Tính diện tích mặt bằng mỗi bể lọc đơn vị theo điều kiện dự phòng $N - 1$.
    - Căn cứ: Khi 1 bể ngắt để rửa ngược, $N - 1 = 3$ bể còn lại phải tải toàn bộ lưu lượng $Q = 18{,}400\text{ m}^3/\text{d}$ ở tốc độ lọc thiết kế $q = 216\text{ m}^3/\text{m}^2\cdot\text{d}$.
    - Nhìn vào: $Q = 18{,}400\text{ m}^3/\text{d}$ và $q = 216\text{ m/d}$:
      $$A_{\text{bed}} = \frac{18400\text{ m}^3/\text{d}}{3 \times 216\text{ m}^3/\text{m}^2\cdot\text{d}} = \frac{18400}{648} = 28{,}395\text{ m}^2 \approx 28{,}40\text{ m}^2$$
      (Đối chiếu: Diện tích $28{,}4\text{ m}^2$ nằm trong dải kích thước thông dụng $25 - 100\text{ m}^2$ theo Slide 34).
  - **Bước 2**: Tính diện tích mặt bằng của từng ô lọc riêng biệt ($A_{\text{cell}}$).
    - Căn cứ: Mỗi bể lọc cấu tạo từ 2 ô lọc độc lập ($A_{\text{cell}} = A_{\text{bed}} / 2$).
    - Nhìn vào: $A_{\text{bed}} = 28{,}40\text{ m}^2$:
      $$A_{\text{cell}} = \frac{28{,}40\text{ m}^2}{2} = 14{,}20\text{ m}^2$$
  - **Bước 3**: Xác định kích thước mặt bằng dài $\times$ rộng của ô lọc ($L_c \times W_c$).
    - Căn cứ: Tỷ lệ $L_c : W_c = 2{,}5 : 1$ và diện tích $A_{\text{cell}} = 14{,}20\text{ m}^2$.
    - Nhìn vào: Tính toán giải phương trình:
      $$W_c = \sqrt{\frac{14{,}20\text{ m}^2}{2{,}5}} = \sqrt{5{,}68} = 2{,}383\text{ m} \approx 2{,}40\text{ m}$$
      $$L_c = 2{,}5 \times 2{,}40\text{ m} = 6{,}00\text{ m}$$
      Kiểm tra điều kiện máng đúc sẵn: $W_c = 2{,}40\text{ m} \le 6{,}0\text{ m}$ (hoàn toàn thỏa mãn).
      Hiệu chỉnh diện tích thực tế của ô lọc:
      $$A_{\text{cell,actual}} = 6{,}00\text{ m} \times 2{,}40\text{ m} = 14{,}40\text{ m}^2$$
      $$A_{\text{bed,actual}} = 2 \times 14{,}40\text{ m}^2 = 28{,}80\text{ m}^2$$
  - **Bước 4**: Xác định kích thước mặt bằng tổng thể của khối bể lọc.
    - Căn cứ: Chiều dài khối bể bằng chiều dài ô lọc ($L_{\text{box}} = L_c$); chiều rộng gồm 2 ô lọc đối xứng qua mương phân phối trung tâm ($W_{\text{box}} = 2 W_c + W_{\text{gullet}}$).
    - Nhìn vào: $L_c = 6{,}00\text{ m}$, $W_c = 2{,}40\text{ m}$, $W_{\text{gullet}} = 0{,}60\text{ m}$:
      $$L_{\text{box}} = 6{,}00\text{ m}$$
      $$W_{\text{box}} = 2 \times 2{,}40\text{ m} + 0{,}60\text{ m} = 5{,}40\text{ m}$$
  - **Bước 5**: Xác định tổng chiều sâu xây dựng của khối bể lọc ($H_{\text{box}}$).
    - Căn cứ: Tổng chiều cao các lớp kết cấu: hệ thống thu nước đáy giả ($h_{\text{underdrain}} = 0{,}30\text{ m}$), lớp sỏi đệm đỡ ($h_{\text{gravel}} = 0{,}30\text{ m}$), lớp cát lọc ($D_{\text{sand}} = 0{,}50\text{ m}$), lớp nước tĩnh trên mặt cát ($h_{\text{water}} = 2{,}00\text{ m}$), và chiều cao an toàn thành bể (freeboard $h_{\text{freeboard}} = 0{,}40\text{ m}$).
    - Nhìn vào: Phép cộng tổng đại số:
      $$H_{\text{box}} = 0{,}30\text{ m} + 0{,}30\text{ m} + 0{,}50\text{ m} + 2{,}00\text{ m} + 0{,}40\text{ m} = 3{,}50\text{ m}$$
  - **Bước 6**: Kiểm tra tốc độ lọc ở chế độ vận hành bình thường và chế độ sự cố $N - 1$.
    - Căn cứ: Vận tốc lọc qua tổng diện tích lắp đặt $A_{\text{total}} = 4 \times 28{,}80\text{ m}^2 = 115{,}20\text{ m}^2$.
    - Nhìn vào:
      - Khi cả 4 bể làm việc: $q_{\text{normal}} = \frac{18400\text{ m}^3/\text{d}}{115{,}20\text{ m}^2} = 159{,}72\text{ m/d} = 6{,}65\text{ m/h}$.
      - Khi 1 bể ngắt để rửa lọc: $q_{N-1} = \frac{18400\text{ m}^3/\text{d}}{3 \times 28{,}80\text{ m}^2} = 212{,}96\text{ m/d} = 8{,}87\text{ m/h} \le 9{,}0\text{ m/h}$.
- **Kết quả**:
  - Diện tích một bể lọc: $A_{\text{bed}} = 28{,}40\text{ m}^2$ (thực tế xây dựng $28{,}80\text{ m}^2$).
  - Diện tích một ô lọc: $A_{\text{cell}} = 14{,}40\text{ m}^2$.
  - Kích thước mặt bằng ô lọc: Rộng $W_c = 2{,}40\text{ m}$, Dài $L_c = 6{,}00\text{ m}$ ($L:W = 2{,}5:1$).
  - Kích thước mặt bằng khối bể: Rộng $W_{\text{box}} = 5{,}40\text{ m}$, Dài $L_{\text{box}} = 6{,}00\text{ m}$.
  - Tổng chiều sâu xây dựng khối bể: $H_{\text{box}} = 3{,}50\text{ m}$.
- **Kiểm tra lại**:
  - Chiều rộng ô lọc $W_c = 2{,}40\text{ m} < 6{,}0\text{ m}$, đảm bảo dùng máng composite/thép đúc sẵn không cần trụ đỡ phụ trợ.
  - Chiều sâu nước tĩnh $2{,}00\text{ m} \ge 1{,}80\text{ m}$, ngăn ngừa hình thành áp lực âm (air-binding) khi tổn thất áp lực tăng cao.
  - Tốc độ lọc danh định khi cả 4 bể vận hành là $6{,}65\text{ m/h}$, thấp hơn ngưỡng an toàn $7{,}5\text{ m/h}$ đối với bể lọc cát nhanh.

#### 6.4.6 Ví dụ 6-6: Thiết kế máng thu nước rửa ngược bể lọc (Example 6-6: Backwash Washwater Trough Design)

- **Đề bài**: Thiết kế hệ thống rửa ngược cho bể lọc cát nhanh của OISP. Sử dụng các kích thước bể lọc từ Ví dụ 6-5. Hệ thống rửa ngược bao gồm bố trí mặt bằng máng rửa, vận tốc rửa ngược, lưu lượng nước rửa trên từng máng, kích thước máng (chiều rộng và chiều sâu), cao trình mép tràn máng, dung tích bể chứa nước rửa, và cao trình mực nước thấp nhất trong bể chứa nước rửa. (WaWE, 11-31).
- **Dữ kiện**:
  - Kích thước ô lọc từ Ví dụ 6-5: Chiều dài $L_c = 6{,}00\text{ m}$, Chiều rộng $W_c = 2{,}40\text{ m}$, Diện tích ô lọc $A_{\text{cell}} = 14{,}40\text{ m}^2$.
  - Vận tốc rửa ngược bằng nước: $v_{\text{bw}} = 45{,}0\text{ m/h} = 0{,}75\text{ m/phút} = 0{,}0125\text{ m/s}$ (nằm trong dải quy chuẩn $30 - 60\text{ m/h}$ theo Slide 44).
  - Thời gian rửa ngược một chu kỳ: $t_{\text{bw}} = 15\text{ phút}$ (Slide 44 quy định $\ge 15\text{ phút}$).
  - Độ giãn nở của lớp cát khi rửa ngược: $30{,}0\%$ ($D_0 = 0{,}50\text{ m}$, $D_e = 0{,}65\text{ m}$, độ dâng cao $\Delta D = 0{,}15\text{ m}$ từ Ví dụ 6-3).
  - Bề rộng lòng máng thu nước rửa chữ nhật: Chọn $b = 0{,}45\text{ m}$.
  - Chiều cao dự phòng lòng máng (trough freeboard): $H_{\text{fb,trough}} = 0{,}08\text{ m}$.
  - Bề dày bản đáy và thành máng bê tông/composite: $t_{\text{wall}} = 0{,}06\text{ m}$.
  - Khoảng tĩnh an toàn đáy máng trên bề mặt cát sôi: $H_{\text{clearance}} = 0{,}10\text{ m}$.
  - Dung tích dự trữ nước rửa của bể chứa: Đủ cho 2 chu kỳ rửa liên tiếp (Slide 44).
- **Quy tắc áp dụng**:
  - Lưu lượng rửa ngược cấp cho một ô lọc:
    $$Q_{\text{bw,cell}} = A_{\text{cell}} \cdot v_{\text{bw}}$$
  - Lưu lượng nước rửa tiếp nhận trên mỗi máng nhánh:
    $$Q_{\text{trough}} = \frac{Q_{\text{bw,cell}}}{n_t}$$
    với $n_t$ là số lượng máng thu đặt song song trong ô lọc.
  - Phương trình Miller-Fair (1954) tính chiều sâu dòng nước tại đầu thượng lưu máng đáy bằng xả tự do:
    $$Q_{\text{trough}} = 1{,}376 \cdot b \cdot h_0^{3/2} \implies h_0 = \left( \frac{Q_{\text{trough}}}{1{,}376 \cdot b} \right)^{2/3}$$
    Nguồn: WaWE Equation (11-31).
  - Tổng chiều cao phủ bì của máng thu:
    $$H_t = h_0 + H_{\text{fb,trough}} + t_{\text{wall}}$$
  - Cao trình mép bờ tràn máng so với bề mặt cát tĩnh:
    $$Z_{\text{weir}} = (D_e - D_0) + H_{\text{clearance}} + H_t$$
    Nguồn: Slide 26, WaWE.
  - Dung tích hữu ích của bể chứa nước rửa lọc:
    $$V_{\text{tank,min}} = 2 \cdot N_{\text{bed,wash}} \cdot Q_{\text{bw}} \cdot t_{\text{bw}}$$
    Nguồn: Slide 44.
  - Cao trình mực nước thấp nhất trong đài nước rửa (Lowest Water Level - LWL):
    $$\text{LWL} \ge Z_{\text{crest,floor}} + \sum h_L + H_{\text{margin}}$$
- **Lời giải**:
  - **Bước 1**: Tính lưu lượng bơm nước rửa ngược cấp cho một ô lọc ($Q_{\text{bw,cell}}$).
    - Căn cứ: Diện tích ô lọc $A_{\text{cell}} = 14{,}40\text{ m}^2$ và vận tốc rửa $v_{\text{bw}} = 0{,}0125\text{ m/s}$.
    - Nhìn vào:
      $$Q_{\text{bw,cell}} = 14{,}40\text{ m}^2 \times 0{,}0125\text{ m/s} = 0{,}180\text{ m}^3/\text{s} = 10{,}80\text{ m}^3/\text{phút} = 648\text{ m}^3/\text{h}$$
      Trạm thực hiện quy trình rửa luân phiên từng ô lọc đơn lẻ để tiết kiệm công suất máy bơm rửa ngược.
  - **Bước 2**: Bố trí mặt bằng máng thu nước rửa trong ô lọc.
    - Căn cứ: Máng thu đặt bắc ngang theo chiều rộng ô lọc ($W_c = 2{,}40\text{ m}$) xả vào mương trung tâm. Bố trí máng dọc theo chiều dài $L_c = 6{,}00\text{ m}$.
    - Nhìn vào: Chọn $n_t = 3$ máng thu song song:
      - Khoảng cách tim trục các máng: $s = \frac{6{,}00\text{ m}}{3} = 2{,}00\text{ m}$.
      - Khoảng cách thông thủy giữa hai mép máng kề nhau: $s_{\text{clear}} = 2{,}00\text{ m} - 0{,}45\text{ m} = 1{,}55\text{ m}$.
      - Quãng đường nước chảy ngang tối đa đến mép tràn: $L_{\text{travel}} = \frac{1{,}55\text{ m}}{2} = 0{,}775\text{ m} \le 1{,}00\text{ m}$.
      Khoảng cách chảy ngang $0{,}775\text{ m}$ thỏa mãn nghiêm ngặt tiêu chuẩn 10 Bang (GLUMRB) và AWWA, đảm bảo thu hồi cặn đồng đều.
  - **Bước 3**: Tính kích thước thủy lực của máng thu nước rửa.
    - Căn cứ: Lưu lượng phân bổ cho 1 máng $Q_{\text{trough}} = \frac{0{,}180\text{ m}^3/\text{s}}{3} = 0{,}060\text{ m}^3/\text{s}$ và bề rộng $b = 0{,}45\text{ m}$.
    - Nhìn vào: Chiều sâu nước thượng lưu $h_0$ theo công thức Miller-Fair:
      $$h_0 = \left( \frac{0{,}060}{1{,}376 \times 0{,}45} \right)^{2/3} = \left( \frac{0{,}060}{0{,}6192} \right)^{2/3} = (0{,}0969)^{2/3} = 0{,}211\text{ m} \approx 0{,}21\text{ m}$$
      Tổng chiều cao thành máng phủ bì:
      $$H_t = 0{,}211\text{ m} + 0{,}08\text{ m} + 0{,}06\text{ m} = 0{,}351\text{ m} \approx 0{,}35\text{ m}$$
  - **Bước 4**: Xác định cao trình mép bờ tràn máng thu nước rửa ($Z_{\text{weir}}$).
    - Căn cứ: Độ dâng cao cát khi sôi $\Delta D = D_e - D_0 = 0{,}15\text{ m}$, khoảng tĩnh an toàn $H_{\text{clearance}} = 0{,}10\text{ m}$, và chiều cao máng $H_t = 0{,}35\text{ m}$.
    - Nhìn vào: Cao trình mép tràn tính từ bề mặt cát tĩnh ban đầu:
      $$Z_{\text{weir}} = 0{,}15\text{ m} + 0{,}10\text{ m} + 0{,}35\text{ m} = 0{,}60\text{ m} \quad (60{,}0\text{ cm})$$
      Đáy máng đặt cao hơn mặt cát tĩnh $0{,}25\text{ m}$ và cao hơn đỉnh lớp cát sôi $0{,}10\text{ m}$, bảo đảm không cản trở dòng cát sôi và ngăn ngừa trôi cát.
  - **Bước 5**: Tính dung tích bể chứa nước rửa lọc ($V_{\text{tank}}$).
    - Căn cứ: Thể tích nước rửa cho 1 ô lọc trong thời gian $15\text{ phút}$:
      $$V_{\text{cell}} = 10{,}80\text{ m}^3/\text{phút} \times 15\text{ phút} = 162{,}0\text{ m}^3$$
      Một bể gồm 2 ô lọc rửa liên tiếp tiêu tốn: $V_{\text{bed}} = 2 \times 162{,}0 = 324{,}0\text{ m}^3$.
    - Nhìn vào: Dung tích tối thiểu cho 2 chu kỳ rửa bể liên tiếp theo Slide 44:
      $$V_{\text{tank,min}} = 2 \times 324{,}0\text{ m}^3 = 648{,}0\text{ m}^3$$
      Bổ sung $15\%$ hệ số an toàn dung tích:
      $$V_{\text{tank,design}} = 1{,}15 \times 648{,}0\text{ m}^3 = 745{,}2\text{ m}^3 \approx 745\text{ m}^3$$
  - **Bước 6**: Xác định cao trình mực nước thấp nhất (LWL) của đài nước rửa ngược.
    - Căn cứ: Cân bằng thủy lực tổng tổn thất cột áp khi rửa ngược $\sum h_L$:
      - Tổn thất qua tầng cát sôi: $h_{\text{sand}} = (\text{SG} - 1)(1 - \varepsilon_0) D_0 = (2{,}65 - 1)(1 - 0{,}45)(0{,}50) = 0{,}454\text{ m} \approx 0{,}45\text{ m}$.
      - Tổn thất qua tầng sỏi đỡ: $h_{\text{gravel}} \approx 0{,}15\text{ m}$.
      - Tổn thất qua hệ thống chụp lọc sàn đáy giả: $h_{\text{nozzle}} \approx 0{,}60\text{ m}$.
      - Tổn thất qua đường ống, phụ kiện và van rửa: $h_{\text{pipe}} \approx 1{,}20\text{ m}$.
      - Tổn thất động năng cửa ra: $h_{\text{exit}} \approx 0{,}10\text{ m}$.
      Tổng tổn thất cột áp: $\sum h_L = 0{,}45 + 0{,}15 + 0{,}60 + 1{,}20 + 0{,}10 = 2{,}50\text{ m}$.
    - Nhìn vào: Cao trình mép tràn máng tính từ sàn đáy bể lọc:
      $$Z_{\text{crest,floor}} = h_{\text{underdrain}} + h_{\text{gravel}} + D_{\text{sand}} + Z_{\text{weir}} = 0{,}30 + 0{,}30 + 0{,}50 + 0{,}60 = 1{,}70\text{ m}$$
      Cột áp dự phòng an toàn áp lực: $H_{\text{margin}} = 1{,}00\text{ m}$.
      Cao trình LWL yêu cầu trên sàn đáy bể lọc:
      $$\text{LWL} \ge 1{,}70\text{ m} + 2{,}50\text{ m} + 1{,}00\text{ m} = 5{,}20\text{ m}$$
      (Mực nước thấp nhất trong đài nước phải đặt cao hơn sàn bê tông đáy bể lọc tối thiểu $5{,}20\text{ m}$, tương ứng cao hơn mép máng tràn tối thiểu $3{,}50\text{ m}$).
- **Kết quả**:
  - Lưu lượng rửa ngược 1 ô lọc: $Q_{\text{bw,cell}} = 0{,}180\text{ m}^3/\text{s} = 10{,}80\text{ m}^3/\text{phút} = 648\text{ m}^3/\text{h}$.
  - Bố trí máng: 3 máng song song, cự ly tim máng $2{,}00\text{ m}$, khoảng cách chảy ngang $0{,}775\text{ m}$.
  - Kích thước máng thu: Rộng $b = 0{,}45\text{ m}$, Chiều sâu nước $h_0 = 0{,}21\text{ m}$, Chiều cao phủ bì $H_t = 0{,}35\text{ m}$.
  - Cao trình mép tràn máng so với mặt cát tĩnh: $Z_{\text{weir}} = 0{,}60\text{ m}$ ($60{,}0\text{ cm}$).
  - Dung tích bể chứa nước rửa: $V_{\text{tank}} = 745\text{ m}^3$.
  - Cao trình mực nước thấp nhất trong bể chứa: $\text{LWL} \ge 5{,}20\text{ m}$ trên sàn đáy bể lọc.
- **Kiểm tra lại**:
  - Khoảng cách chảy ngang $0{,}775\text{ m} < 1{,}00\text{ m}$, đảm bảo cặn bùn không bị lắng đọng ngược lại mặt cát trong quá trình thu nước rửa.
  - Dung tích $745\text{ m}^3$ đảm bảo thực hiện liên tiếp 2 chu kỳ rửa toàn phần cho cả 2 bể mà không cần chờ bơm nạp lại, đáp ứng hoàn toàn điều kiện an toàn vận hành giờ cao điểm theo tiêu chuẩn cấp nước đô thị.

## Chương 7: Khử trùng Nước cấp (Disinfection)


### 7.1 Overview of Water Disinfection

#### 7.1.1 Nguyên lý Khử trùng và Các Nhóm Mầm bệnh Mục tiêu (Disinfection Principles & Pathogens of Concern)

- Khử trùng ($\text{Disinfection}$) trong quy trình xử lý nước cấp nhằm mục đích giảm thiểu mầm bệnh xuống mức an toàn chấp nhận được:
  - Khử trùng tiêu diệt hoặc bất hoạt có chọn lọc các vi sinh vật gây bệnh truyền nhiễm qua đường nước (*waterborne pathogens*).
  - Khử trùng triệt tiêu nguy cơ bùng phát các dịch bệnh truyền nhiễm trong cộng đồng như tả, thương hàn, kiết lỵ, bại liệt và viêm gan.
- Khử trùng ($\text{Disinfection}$) khác biệt căn bản với tiệt trùng ($\text{Sterilization}$):
  - Tiệt trùng (*sterilization*) là quá trình tiêu diệt hoặc loại bỏ hoàn toàn mọi dạng sống của vi sinh vật, bao gồm cả bào tử vi khuẩn (*bacterial spores*) và các sinh vật vô hại.
  - Khử trùng (*disinfection*) không đòi hỏi tiêu diệt toàn bộ vi sinh vật mà chỉ tập trung loại trừ các tác nhân gây bệnh nguy hại.
  - Nước uống sinh hoạt không cần đạt trạng thái vô trùng tuyệt đối (*sterile*) để đảm bảo an toàn cho sức khỏe con người; nước chỉ cần đạt các chỉ tiêu vi sinh vật theo quy chuẩn kỹ thuật (như $\text{QCVN 01-1:2018/BYT}$, tiêu chuẩn $\text{WHO}$ và $\text{US EPA}$).
- Ba nhóm mầm bệnh đường ruột ở người (*human enteric pathogens*) là đối tượng kiểm soát trọng tâm trong nước uống:
  - Vi khuẩn (*Bacteria*):
    - Các chủng điển hình gồm *Escherichia coli*, *Vibrio cholerae*, *Salmonella typhi*, *Shigella spp.*, và *Campylobacter jejuni*.
    - Vi khuẩn là nhóm nhạy cảm nhất với hầu hết các hóa chất khử trùng oxy hóa; chúng bị bất hoạt nhanh chóng bởi nồng độ clo tự do thấp trong vài phút tiếp xúc.
  - Virus (*Viruses*):
    - Các chủng điển hình gồm *Enterovirus*, *Hepatovirus* (Hepatitis A, E), *Rotavirus*, *Norovirus*, và *Adenovirus*.
    - Kích thước hạt virus rất nhỏ, dao động từ $20\text{ nm}$ đến $100\text{ nm}$; virus không có cấu trúc tế bào hoàn chỉnh mà gồm lõi acid nucleic bọc trong vỏ protein (*capsid*).
    - Virus có khả năng kháng clo cao hơn vi khuẩn thông thường; tuy nhiên, chúng bị bất hoạt hiệu quả bởi bức xạ cực tím ($\text{UV}$) và ozone ($\text{O}_3$).
  - Nang amip và u nang đơn bào (*Amebic Cysts and Protozoan Cysts/Oocysts*):
    - Các chủng điển hình gồm *Entamoeba histolytica*, *Giardia lamblia* (*Giardia duodenalis*), và *Cryptosporidium parvum*.
    - Cấu trúc vỏ bọc ngoài rất dày và bền vững, giúp bảo vệ tế bào trước các tác nhân môi trường khắc nghiệt.
    - Nang đơn bào có khả năng kháng hóa chất khử trùng gốc clo rất cao; u nang *Cryptosporidium* hầu như trơ với clo tự do ở liều lượng thông thường trong xử lý nước cấp.
    - Kiểm soát nang đơn bào đòi hỏi kết hợp quá trình lọc loại bỏ cơ học cùng công nghệ khử trùng nâng cao như ozone ($\text{O}_3$), tia cực tím ($\text{UV}$) hoặc clo dioxit ($\text{ClO}_2$).
- Quy trình khử trùng đạt chuẩn kỹ thuật phải có năng lực bất hoạt đồng thời cả ba nhóm mầm bệnh nêu trên:
  - Công nghệ xử lý nước cấp đô thị phải thiết kế hệ thống rào cản đa tầng (*multi-barrier approach*) để bảo đảm hiệu quả loại bỏ và bất hoạt đầy đủ.

#### 7.1.2 Các Tác nhân Khử trùng Phổ biến trong Xử lý Nước cấp (Common Disinfection Agents in Water Treatment)

- Năm tác nhân khử trùng được ứng dụng phổ biến nhất trong công nghệ cấp nước sinh hoạt:
  - 1. Clo tự do (*Free chlorine*):
    - Tồn tại dưới dạng phân tử axit hypochlorous ($\text{HOCl}$) và ion hypochlorite ($\text{OCl}^-$).
    - Hóa chất cấp vào gồm khí clo nguyên tố ($\text{Cl}_2$), natri hypochlorite ($\text{NaOCl}$) hoặc canxi hypochlorite ($\text{Ca(OCl)}_2$).
    - Tác nhân có phổ diệt khuẩn rộng, chi phí đầu tư và vận hành thấp, duy trì được nồng độ tồn dư bảo vệ mạng lưới phân phối.
    - Nhược điểm: tạo các sản phẩm phụ khử trùng độc hại ($\text{DBPs}$) như trihalomethanes ($\text{THMs}$) và haloacetic acids ($\text{HAAs}$); kém hiệu quả đối với nang *Cryptosporidium*.
  - 2. Clo liên kết / Cloramin (*Combined chlorine / Chloramines*):
    - Tạo thành từ phản ứng giữa clo và amoniac ($\text{NH}_3$); dạng khử trùng chủ yếu là monochloramine ($\text{NH}_2\text{Cl}$).
    - Tính oxy hóa yếu hơn clo tự do nhưng có độ bền nhiệt động cao, tồn lưu lâu dài trên các tuyến ống cấp nước dài và hạn chế phát sinh $\text{THMs}$.
    - Nhược điểm: tốc độ diệt khuẩn chậm, đòi hỏi tích số nồng độ và thời gian tiếp xúc ($\text{CT}$) lớn hơn nhiều so với clo tự do.
  - 3. Clo dioxit (*Chlorine dioxide* - $\text{ClO}_2$):
    - Chất khí hòa tan, là chất oxy hóa mạnh và phản ứng chọn lọc cao.
    - Hiệu quả bất hoạt virus và u nang *Giardia* cao hơn clo tự do; không tạo sản phẩm phụ $\text{THMs}$ hay $\text{HAAs}$.
    - Nhược điểm: phải điều chế tại chỗ (*on-site generation*) do nguy cơ nổ khi nén; tạo sản phẩm phụ vô cơ có độc tính là ion clorit ($\text{ClO}_2^-$) và clorat ($\text{ClO}_3^-$).
  - 4. Ozone (*Ozone* - $\text{O}_3$):
    - Tác nhân oxy hóa cực mạnh, phản ứng tức thời với màng tế bào và cấu trúc nội bào của vi sinh vật.
    - Bất hoạt hiệu quả cao đối với nang *Cryptosporidium* và virus; hỗ trợ khử màu, mùi, vị và oxy hóa chất hữu cơ tự nhiên ($\text{NOM}$).
    - Nhược điểm: chi phí đầu tư thiết bị và tiêu thụ điện năng cao; không có tính chất tồn dư trong mạng lưới đường ống; có nguy cơ tạo sản phẩm phụ bromate ($\text{BrO}_3^-$) khi nguồn nước chứa ion bromide ($\text{Br}^-$).
  - 5. Bức xạ cực tím (*Ultraviolet irradiation* - $\text{UV}$):
    - Phương pháp vật lý sử dụng bước sóng photon tối ưu $\lambda = 254\text{ nm}$ phá hủy liên kết phân tử trong $\text{DNA/RNA}$, ngăn ngừa quá trình tự nhân đôi của vi sinh vật.
    - Hiệu quả bất hoạt nang *Cryptosporidium* và *Giardia* cực cao ở liều lượng chiếu xạ thấp mà không tạo sản phẩm phụ hóa học độc hại.
    - Nhược điểm: không tạo nồng độ khử trùng tồn dư để bảo vệ mạng lưới phân phối; hiệu quả phụ thuộc vào độ đục và độ truyền quang tử ngoại ($\text{UVT}$) của nước.
- Nguyên lý cân bằng vật chất giữa liều lượng hóa chất châm, nhu cầu oxy hóa và nồng độ chất khử trùng dư:
  $$\text{Chlorine Dose} = \text{Chlorine Demand} + \text{Chlorine Residual}$$
  - $\text{Chlorine Dose}$: Liều lượng clo tổng cộng châm vào nước ($\text{mg/L}$).
  - $\text{Chlorine Demand}$: Nhu cầu clo tiêu hao do phản ứng với các chất khử vô cơ ($\text{Fe}^{2+}, \text{Mn}^{2+}, \text{H}_2\text{S}$), amoniac và chất hữu cơ trong nước ($\text{mg/L}$).
  - $\text{Chlorine Residual}$: Nồng độ clo dư còn lại sau thời gian tiếp xúc quy định ($\text{mg/L}$), gồm clo tự do dư hoặc clo liên kết dư để bảo vệ chống tái nhiễm bẩn.
  - **Hình 01.** Khái niệm cân bằng liều lượng clo, nhu cầu clo và nồng độ clo dư
    - <img src="ch07_disinfection/assets/fig_01_p7.png" alt="Hình 01" />
    - **Hình này chứng minh điều gì**
      - Thể hiện nguyên lý định lượng chất khử trùng: liều lượng châm bằng tổng nhu cầu clo và clo dư yêu cầu.
    - **Từ đâu mà thấy được**
      - Sơ đồ cân bằng khối lượng hóa chất châm vào nguồn nước xử lý.
- Động học biến thiên nồng độ clo dư theo liều lượng châm đối với nguồn nước mặt chứa amoniac và hợp chất hữu cơ:
  - Khi châm clo vào nước mặt, các chất khử vô cơ tiêu thụ clo ban đầu trước khi clo phản ứng với amoniac tạo clo liên kết và sau đó bị oxy hóa phá hủy tại điểm uốn (*breakpoint*).
  - Vượt qua điểm uốn, toàn bộ lượng clo châm thêm tồn tại dưới dạng clo tự do dư hữu hiệu ($\text{HOCl}$ và $\text{OCl}^-$).
  - **Hình 02.** Đường cong clo hóa điểm uốn của nước mặt
    - <img src="ch07_disinfection/assets/fig_02_p8.png" alt="Hình 02" />
    - **Hình này chứng minh điều gì**
      - Thể hiện diễn biến nồng độ clo dư theo liều lượng clo châm vào nguồn nước mặt chứa amoniac.
    - **Từ đâu mà thấy được**
      - Đồ thị biểu diễn bốn giai đoạn phản ứng và điểm uốn breakpoint chuyển hóa clo liên kết thành clo tự do.

#### 7.1.3 Các Yêu cầu Kỹ thuật đối với Hóa chất Khử trùng Thực tế (Required Practical Properties of Disinfectants)

- Để ứng dụng hiệu quả trong thực tế công nghệ cấp nước, hóa chất khử trùng phải đáp ứng đầy đủ năm tiêu chuẩn kỹ thuật cốt lõi:
  - 1. Tiêu diệt chủng loại và số lượng mầm bệnh trong thời gian thực tế và dải nhiệt độ vận hành dự kiến:
    - Chất khử trùng phải có năng lực bất hoạt nhanh chóng mật độ lớn các mầm bệnh vi khuẩn, virus và nang đơn bào có thể xuất hiện trong nguồn nước.
    - Thời gian phản ứng tiếp xúc cần thiết ($t$) phải nằm trong giới hạn thể tích bể tiếp xúc khả thi của nhà máy xử lý (thường từ $15\text{--}60\text{ min}$ đối với hóa chất clo).
    - Hiệu lực diệt khuẩn phải duy trì ổn định trên toàn bộ dải nhiệt độ dao động theo mùa của nguồn nước thô (từ $0^\circ\text{C}$ đến $35^\circ\text{C}$).
  - 2. Thích ứng với các biến động về thành phần hóa lý, nồng độ tạp chất và trạng thái nước nguồn:
    - Chất lượng nước thô thường xuyên dao động đột ngột về độ đục (*turbidity*), độ màu, độ kiềm (*alkalinity*), giá trị $\text{pH}$, hàm lượng chất hữu cơ tự nhiên ($\text{NOM}$) và các chất khử hòa tan.
    - Hóa chất khử trùng phải hoạt động tin cậy và duy trì khả năng diệt khuẩn ổn định trước các biến động chất lượng nước thô này.
  - 3. Đảm bảo an toàn độc học cho người và động vật, không gây mùi vị khó chịu ở nồng độ khử trùng:
    - Hóa chất ở nồng độ sử dụng cho quá trình khử trùng tuyệt đối không gây độc cấp tính hay độc mãn tính cho cơ thể người và động vật nuôi.
    - Nước sau khử trùng không được phát sinh mùi hắc, vị lạ hay các đặc tính cảm quan khó chịu vượt ngưỡng người tiêu dùng chấp nhận (*acceptable aesthetic quality*).
    - Hàm lượng các sản phẩm phụ khử trùng hóa học ($\text{DBPs}$) tạo thành trong phản ứng phải nằm dưới ngưỡng nồng độ ô nhiễm tối đa cho phép ($\text{MCL}$) theo quy chuẩn hiện hành.
  - 4. Đo đạc nồng độ trong nước đã xử lý dễ dàng, nhanh chóng và tự động hóa:
    - Nồng độ chất khử trùng dư cần được xác định bằng các phương pháp phân tích tin cậy, thao tác đơn giản và thời gian phân tích tức thời (như phương pháp so màu $\text{DPD}$ hoặc cảm biến điện hóa *amperometric*).
    - Hệ thống công nghệ ưu tiên tích hợp thiết bị đo trực tuyến liên tục (*online continuous monitoring*) để tự động điều khiển phản hồi liều lượng châm hóa chất (*automatic dosing control*).
  - 5. Chi phí kinh tế hợp lý và khả thi:
    - Tổng chi phí đầu tư ban đầu cho hệ thống thiết bị châm hóa chất, bồn chứa, bể phản ứng tiếp xúc ($\text{CAPEX}$) phải ở mức hợp lý.
    - Chi phí vận hành thường xuyên bao gồm giá mua hóa chất, tiêu hao điện năng, chi phí bảo trì và bảo hộ an toàn lao động ($\text{OPEX}$) phải tối ưu, bảo đảm giá thành sản xuất nước sạch phù hợp với khả năng chi trả của xã hội.

### 7.2. Theory

#### Free Chlorine

- Clo (chlorine) là hóa chất khử trùng (disinfecting chemical) phổ biến nhất trong cấp nước, và thuật ngữ clo hóa (chlorination) thường được sử dụng đồng nghĩa với quá trình khử trùng (disinfection).
- Clo có thể được sử dụng dưới ba dạng hóa chất chính:
  - Khí clo nguyên tố ($\text{Cl}_2$).
  - Natri hypoclorit ($\text{NaOCl}$), hay còn gọi là chất tẩy trắng (bleach).
  - Canxi hypoclorit ($\text{Ca(OCl)}_2$), hay còn gọi là vôi clo hóa (chlorinated lime, $\text{CaOCl}_2$).
- Khi châm clo vào nước, phản ứng thủy phân tạo ra hỗn hợp axit hipoclorơ ($\text{HOCl}$) và axit clohydric ($\text{HCl}$):
  $$\text{Cl}_2\text{ (gas)} + \text{H}_2\text{O} \rightleftharpoons \text{HOCl} + \text{H}^+ + \text{Cl}^-$$
  - Phản ứng thủy phân này phụ thuộc vào $\text{pH}$ và diễn ra gần như tức thời, hoàn tất chỉ trong vòng vài mili-giây (very few milliseconds).
  - Trong dung dịch loãng và ở các mức $\text{pH}$ trên $1.0$, cân bằng phản ứng dịch chuyển mạnh sang phải và chỉ tồn tại một lượng rất nhỏ $\text{Cl}_2$ trong dung dịch.
- Axit hipoclorơ ($\text{HOCl}$) là một axit yếu và phân ly kém ở các giá trị $\text{pH}$ dưới khoảng $6$:
  $$\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^-$$
  - Clo tồn tại chủ yếu ở dạng $\text{HOCl}$ tại các giá trị $\text{pH}$ trong khoảng từ $4.0$ đến $6.0$.
  - Trong dải $\text{pH}$ từ $6.0$ đến $8.5$, xảy ra sự chuyển đổi rất đột ngột từ dạng $\text{HOCl}$ chưa phân ly sang trạng thái phân ly gần như hoàn toàn.
  - Tại nhiệt độ $200\text{C}$ (nguyên văn: $200\text{C}$, tức $20^\circ\text{C}$) và $\text{pH}$ trên $7.5$, các ion hipoclorit ($\text{OCl}^-$) chiếm ưu thế.
  - Các ion hipoclorit ($\text{OCl}^-$) tồn tại gần như tuyệt đối ở các mức $\text{pH}$ trên $9$.
- Định nghĩa clo tự do (free chlorine):
  - Clo tồn tại trong nước dưới các dạng $\text{HOCl}$ và/hoặc $\text{OCl}^-$ được định nghĩa là clo hoạt tính tự do (free available chlorine) hoặc clo tự do (free chlorine).
- Phân ly của các muối hypoclorit trong nước tạo ra các ion hipoclorit ($\text{OCl}^-$):
  - $\text{NaOCl} \rightarrow \text{Na}^+ + \text{OCl}^-$
  - $\text{Ca(OCl)}_2 \rightarrow \text{Ca}^{2+} + 2\text{OCl}^-$
  - Các ion hipoclorit nhanh chóng thiết lập trạng thái cân bằng với ion hydro ($\text{H}^+$) theo phương trình phân ly thuận nghịch ($\text{OCl}^- + \text{H}^+ \rightleftharpoons \text{HOCl}$).
  - Cùng các dạng clo hoạt tính ($\text{HOCl}$ và $\text{OCl}^-$) và cùng một trạng thái cân bằng hóa học được thiết lập trong nước, bất kể sử dụng clo nguyên tố hay các muối hypoclorit.
- Ảnh hưởng của dạng clo sử dụng đến $\text{pH}$ và độ kiềm của nước:
  - Sự khác biệt đáng kể nhất giữa clo nguyên tố và các muối hypoclorit nằm ở giá trị $\text{pH}$ tạo thành sau phản ứng và ảnh hưởng trực tiếp của nó đến tỷ lệ tương đối giữa $\text{HOCl}$ và $\text{OCl}^-$ tại trạng thái cân bằng.
  - Khí clo nguyên tố có xu hướng làm giảm $\text{pH}$; mỗi $\text{mg/L}$ clo châm vào làm tiêu hao độ kiềm (alkalinity) lên tới $1.4\text{ mg/L}$ tính theo $\text{CaCO}_3$.
  - Ngược lại, các muối hypoclorit luôn chứa lượng kiềm dư để tăng độ bền (stability) nên có xu hướng làm tăng nhẹ $\text{pH}$.
  - Để tối ưu hóa hiệu quả khử trùng (disinfecting action), giá trị $\text{pH}$ thiết kế công nghệ được duy trì trong dải từ $6.5$ đến $7.5$.
- Độ bền hóa học và phản ứng quang phân của clo tự do:
  - Clo tự do tương đối bền vững trong môi trường nước tinh khiết.
  - Clo tự do phản ứng chậm với chất hữu cơ tự nhiên (NOM - naturally occurring organic matter), nhưng phản ứng rất nhanh dưới tác động của ánh sáng mặt trời (sunlight).
  - Phản ứng quang phân (photolytic reaction) diễn ra trực tiếp đối với ion hipoclorit ($\text{OCl}^-$); các sản phẩm sinh ra gồm oxy ($\text{O}_2$), ion clorit ($\text{ClO}_2^-$), và ion clorua ($\text{Cl}^-$).
- Cân bằng khối lượng và nguyên lý định lượng clo:
  $$\text{Chlorine dose} = \text{Chlorine demand} + \text{Chlorine residual}$$
  - Liều lượng clo châm vào (chlorine dose): tổng lượng clo cần thêm vào nguồn nước để đạt được nồng độ clo dư mong muốn trong quá trình khử trùng.
  - Nhu cầu clo (chlorine demand): lượng clo tiêu tốn để phản ứng hoàn toàn với tất cả các chất khử và các hợp chất hữu cơ có trong nước.
  - Quá trình clo hóa điểm uốn (breakpoint chlorination): quá trình châm clo liên tục vào nước cho đến khi nhu cầu clo đã được đáp ứng hoàn toàn.
  - Điểm uốn / điểm đột biến (breakpoint): trạng thái mà tại đó toàn bộ nhu cầu clo đã được thỏa mãn và bất kỳ lượng clo nào châm thêm sau đó sẽ xuất hiện dưới dạng clo dư tự do (free chlorine residual).

##### Breakpoint chlorination curve (surface water)

- Quá trình clo hóa đối với nước mặt chứa amoniac và chất hữu cơ tuân theo đường cong clo hóa điểm uốn qua 4 giai đoạn phản ứng liên tiếp:
  - Giai đoạn 1 (từ 0 đến vạch 1–2): clo châm vào bị tiêu hao và phá hủy hoàn toàn bởi các chất khử vô cơ (chlorine destroyed by reducing agents), clo dư bằng không.
  - Giai đoạn 2 (vạch 2–3): hình thành các hợp chất hữu cơ chứa clo và cloramin (formation of chlororganics and chloramines), đường cong clo dư liên kết tăng lên tạo thành đỉnh lồi.
  - Giai đoạn 3 (vạch 3–4): lượng clo châm thêm oxy hóa và phá hủy một phần cloramin cùng hợp chất clo hữu cơ (chlororganics and chloramines partly destroyed), làm giảm nồng độ clo dư xuống đáy cực tiểu tại vạch 4 (điểm uốn - breakpoint).
  - Giai đoạn 4 (sau vạch 4): vượt qua điểm uốn, clo dư tự do hình thành và tăng dốc tuyến tính theo lượng clo châm thêm (free available residual formed), trong khi một phần hợp chất clo hữu cơ vẫn còn tồn lưu (some chlororganics remain).
##### Breakpoint chlorination curve (well water)

- Quá trình clo hóa đối với nước ngầm không chứa amoniac hoặc hợp chất hữu cơ có đường cong phản ứng đơn giản hóa chỉ gồm 2 giai đoạn:
  - Giai đoạn 1 (từ 0 đến vạch 1–2): clo châm vào bị phá hủy bởi các chất khử (chlorine destroyed by reducing agents), không xuất hiện clo dư.
  - Giai đoạn 2 (sau vạch 2): đạt ngay điểm uốn (breakpoint) tại vạch 2 mà không có giai đoạn tích lũy cloramin trung gian; clo dư tự do hình thành ngay lập tức và tăng tuyến tính trực tiếp theo lượng clo châm thêm (free available residual formed).
  - **Hình 3.** Đường cong clo hóa điểm uốn của nước ngầm
    - <img src="ch07_disinfection/assets/fig_03_p9.png" alt="Hình 3" />
    - **Hình này chứng minh điều gì**
      - Điểm uốn (vạch 2) đánh dấu mốc nhu cầu clo (chlorine demand) được đáp ứng trọn vẹn mà không sinh cloramin trung gian.
    - **Từ đâu mà thấy được**
      - Trục Ox: lượng clo châm (Chlorine added); trục Oy: clo dư (Chlorine residual).
      - Đoạn 1–2 nằm sát trục hoành ở mức 0; tại vạch 2 (Breakpoint), đồ thị bắt đầu dốc lên thành đường thẳng tăng liên tục.

##### Typical Chlorine Dosages at Water Treatment Plants

- Dải liều lượng clo châm vào áp dụng điển hình tại các nhà máy xử lý nước cấp được phân chia rõ rệt theo loại hợp chất clo sử dụng:
  - Canxi hypoclorit (calcium hypochlorite): dải liều lượng từ $0.5$ đến $5\text{ mg/L}$.
  - Natri hypoclorit (sodium hypochlorite): dải liều lượng từ $0.2$ đến $2\text{ mg/L}$.
  - Khí clo (chlorine gas): dải liều lượng từ $1$ đến $16\text{ mg/L}$, có dải dao động rộng nhất và mức châm trần cao nhất.
  - Số liệu thực tế được SAIC trích dẫn năm 1998, dựa trên đánh giá của EPA từ các Kế hoạch lấy mẫu ban đầu (Initial Sampling Plans) theo Quy tắc thu thập thông tin ICR (Information Collection Rule).
  - **Hình 6.** Liều lượng clo điển hình tại trạm xử lý nước
    - <img src="ch07_disinfection/assets/fig_06_p10.png" alt="Hình 6" />
    - **Hình này chứng minh điều gì**
      - Khí clo có dải liều lượng rộng nhất và mức châm tối đa cao nhất so với hai dạng muối hypoclorit.
    - **Từ đâu mà thấy được**
      - Cột "Range of Doses", hàng "Chlorine gas": dải liều đạt $1\text{–}16\text{ mg/L}$, mức trần cao nhất bảng.
      - Hàng "Calcium hypochlorite" và "Sodium hypochlorite": dải liều thấp hơn, lần lượt là $0.5\text{–}5\text{ mg/L}$ và $0.2\text{–}2\text{ mg/L}$.

##### Chlorine Uses and Doses

- Ngoài chức năng khử trùng, clo còn được ứng dụng phổ biến cho nhiều mục đích oxy hóa và kiểm soát chất lượng nước khác nhau với các điều kiện kỹ thuật đặc thù:
  - Oxy hóa sắt (iron): liều lượng điển hình $0.62\text{ mg/mg Fe}$, $\text{pH}$ tối ưu $7.0$, thời gian phản ứng dưới $1\text{ giờ}$ ($\text{less than } 1\text{ hour}$), hiệu quả tốt ($\text{Good}$).
  - Oxy hóa mangan (manganese): liều lượng điển hình $0.77\text{ mg/mg Mn}$, động học phản ứng chậm ($\text{Slow kinetics}$), thời gian phản ứng tăng lên ở các mức $\text{pH}$ thấp hơn; ở $\text{pH } 7\text{–}8$ cần thời gian $1\text{–}3\text{ giờ}$, trong khi nâng lên $\text{pH } 9.5$ thời gian phản ứng rút ngắn xuống còn vài phút ($\text{minutes}$).
  - Kiểm soát sự phát triển sinh học (biological growth): liều lượng từ $1$ đến $2\text{ mg/L}$, $\text{pH}$ tối ưu từ $6$ đến $8$, thời gian phản ứng không áp dụng ($\text{NA}$), hiệu quả tốt, có nguy cơ tạo sản phẩm phụ khử trùng ($\text{DBP formation}$).
  - Xử lý vị và mùi (taste/odor): liều lượng biến thiên ($\text{Varies}$), $\text{pH}$ tối ưu từ $6$ đến $8$, thời gian phản ứng biến thiên, hiệu quả biến thiên tùy thuộc vào hợp chất cụ thể, hiệu quả phụ thuộc vào bản chất từng hợp chất ($\text{Effectiveness depends on compound}$).
  - Khử màu (color removal): liều lượng biến thiên, $\text{pH}$ tối ưu từ $4.0$ đến $6.8$, thời gian phản ứng trong vài phút ($\text{Minutes}$), hiệu quả tốt, có nguy cơ tạo sản phẩm phụ khử trùng ($\text{DBP formation}$).
  - Kiểm soát vẹm vằn (zebra mussels): liều lượng châm sốc từ $2$ đến $5\text{ mg/L}$ ($\text{Shock level}$), nồng độ duy trì từ $0.2$ đến $0.5\text{ mg/L}$ (nồng độ clo dư, không phải liều châm - $\text{Residual, not dose}$), hiệu quả tốt, có nguy cơ tạo $\text{DBP}$.
  - Kiểm soát hến châu Á (Asiatic clams): châm liên tục ($\text{Continuous}$) với nồng độ clo dư duy trì từ $0.3$ đến $0.5\text{ mg/L}$ ($\text{Residual, not dose}$), hiệu quả tốt, có nguy cơ tạo $\text{DBP}$.
  - Tổng hợp từ các nguồn nghiên cứu: White (1992), Connell (1996), Culp/Wesner/Culp (1986).
  - **Hình 7.** Tổng hợp liều lượng và điều kiện phản ứng chuyên biệt của clo
    - <img src="ch07_disinfection/assets/fig_07_p11.png" alt="Hình 7" />
    - **Hình này chứng minh điều gì**
      - pH kiềm hóa ($9.5$) giúp rút ngắn thời gian oxy hóa Mn xuống vài phút thay vì $1\text{--}3\text{ hour}$ ở pH $7\text{--}8$.
      - Khử màu, diệt vi sinh vật và động vật bám đều đi kèm nguy cơ tạo sản phẩm phụ DBP (DBP formation).
    - **Từ đâu mà thấy được**
      - Hàng "Manganese", cột "Reaction Time": thời gian giảm từ $1\text{--}3\text{ hour}$ (pH $7\text{--}8$) xuống "minutes" (pH $9.5$).
      - Cột "Other Considerations": ghi nhận "DBP formation" ở các hàng vi sinh vật, khử màu, vẹm vằn và hến.
      - Cột "Typical Dose" và "Optimal pH": hiển thị liều chuẩn của Fe ($0.62\text{ mg/mg Fe}$) và Mn ($0.77\text{ mg/mg Mn}$).

#### Combined Chlorine

- Phản ứng của clo với amoniac ($\mathrm{NH_3}$) có ý nghĩa rất lớn trong các quá trình clo hóa nước (water chlorination processes):
  - Khi clo được châm vào nước có chứa amoniac tự nhiên hoặc nhân tạo (ion amoni $\mathrm{NH_4^+}$ tồn tại ở trạng thái cân bằng với amoniac và ion hydro $\mathrm{H^+}$), amoniac phản ứng với $\mathrm{HOCl}$ để tạo thành các dạng chloramine khác nhau.
  - Các phản ứng giữa clo và amoniac diễn ra qua 3 nấc:
    - $\mathrm{NH_3 + HOCl \rightarrow NH_2Cl + H_2O}$ (monochloramine).
    - $\mathrm{NH_2Cl + HOCl \rightarrow NHCl_2 + H_2O}$ (dichloramine).
    - $\mathrm{NHCl_2 + HOCl \rightarrow NCl_3 + H_2O}$ (trichloramine).
  - Sự phân bố các sản phẩm phản ứng được chi phối bởi tốc độ tạo thành monochloramine và dichloramine; các tốc độ này phụ thuộc vào $\mathrm{pH}$, nhiệt độ, thời gian và tỷ lệ $\mathrm{Cl_2:NH_3}$ ban đầu.
  - Nhìn chung, tỷ lệ $\mathrm{Cl_2:NH_3}$ cao, nhiệt độ thấp và mức $\mathrm{pH}$ thấp ưu tiên sự tạo thành dichloramine.
  - Monochloramine chiếm ưu thế ở các mức $\mathrm{pH}$ cao.
- Clo cũng phản ứng với các vật liệu hữu cơ chứa nitơ (organic nitrogenous materials), chẳng hạn như protein và axit amin, để tạo thành các phức chloramine hữu cơ (organic chloramine complexes).
- Clo tồn tại trong nước ở dạng kết hợp hóa học với amoniac hoặc các hợp chất nitơ hữu cơ được định nghĩa là clo hữu dụng liên kết (combined available chlorine) hoặc clo liên kết (combined chlorine).
- Tổng nồng độ của clo tự do (free chlorine) và clo liên kết (combined chlorine) được gọi là clo tổng số (total chlorine).
- Cân bằng lượng clo dư:
  - $\text{Chlorine residual} = \text{Free chlorine residual} + \text{Combined chlorine residual}$ (Độ clo dư = Clo dư tự do + Clo dư liên kết).
- Sự phân bố dạng tồn tại chloramine (chloramine speciation) phụ thuộc vào tỷ lệ $\mathrm{Cl_2:N}$ đối với dải $\mathrm{pH}$ từ 6.5 đến 8.5:
  - **Hình 10.** Đường cong clo hóa đến điểm đột biến breakpoint
    - <img src="ch07_disinfection/assets/fig_10_p14.png" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Tỷ lệ $\mathrm{Cl_2:NH_3\text{-}N}$ gia tăng phân định các vùng tạo monochloramine, chuyển hóa di-trichloramine và phá hủy tại breakpoint để tạo clo dư tự do.
    - **Từ đâu mà thấy được**
      - Ox: Lượng clo châm vào (Chlorine Added). Oy: Lượng clo dư (Chlorine Residual).
      - Đỉnh monochloramine tại tỷ lệ khối lượng $5:1\ \mathrm{Cl_2:NH_3\text{-}N}$, sau đó clo dư sụt giảm khi tạo dichloramine.
      - Điểm cực tiểu Breakpoint tại tỷ lệ $10:1\ \mathrm{Cl_2:NH_3\text{-}N}$, sau đó clo dư tự do tăng tuyến tính (chiếm 85 % tổng clo dư).

#### Disinfection Agents and Comparison

##### Chlorine Dioxide

- Clo dioxit ($ClO_2$, chlorine dioxide) là một gốc tự do bền (stable free radical); ở nồng độ cao (high concentrations), chất này phản ứng mãnh liệt (reacts violently) với các chất khử (reducing agents).
- $ClO_2$ là chất nổ (explosive) với giới hạn nổ dưới (lower explosive limit* - LEL) được ghi nhận trong các tài liệu khác nhau dao động từ 10 đến 39 phần trăm (10 and 39 percent).
  - Do đó, hầu như toàn bộ các ứng dụng (virtually all applications) đều đòi hỏi phải tổng hợp tại chỗ (synthesis on-site).
- Clo dioxit ($ClO_2$) được hình thành tại chỗ bằng cách kết hợp clo (chlorine) và natri clorit ($NaClO_2$, sodium chlorite), sử dụng một trong ba phản ứng thay thế (three alternative reactions):
  - Phản ứng với khí clo ($Cl_2$ gas):
    $$2NaClO_2 + Cl_2\text{ (gas)} \rightarrow 2ClO_2\text{ (gas)} + 2NaCl$$
  - Phản ứng với axit hypoclorơ ($HOCl$):
    $$2NaClO_2 + HOCl \rightarrow 2ClO_2\text{ (gas)} + NaCl + NaOH$$
  - Phản ứng với axit clohydric ($HCl$):
    $$5NaClO_2 + 4HCl \rightarrow 4ClO_2\text{ (gas)} + 5NaCl + 2H_2O$$
- Phản ứng điển hình của clo dioxit trong môi trường nước là phản ứng khử một electron (one-electron reduction):
  $$ClO_2 + e^- \rightarrow ClO_2^-$$

#### Mechanisms of Disinfection

##### Ozone

- Định nghĩa và đặc tính lý hóa của Ozone ($\text{O}_3$):
  - Ozone là chất khí có mùi hắc đặc trưng và không bền vững (*pungent, unstable gas*).
  - Phân tử cấu tạo từ ba nguyên tử oxy liên kết tạo thành $\text{O}_3$ ($M = 48\text{ g/mol}$).
  - Do tính kém bền và tốc độ phân hủy nhanh, ozone bắt buộc phải được điều chế tại chỗ ở điểm sử dụng (*generated at the point of use*).
- Các phương pháp sản xuất khí ozone và cơ chế phân ly điện trường:
  - Bốn phương pháp có thể điều chế ozone: quang hóa (*photochemical*), điện phân (*electrolytic*), hóa bức xạ (*radiochemical*), và phóng điện qua điện cực (*discharge electrode*).
  - Phương pháp phổ biến nhất trong thực tế xử lý nước là phóng điện qua điện cực (*corona discharge electrode*).
  - Nguồn cấp khí gồm oxy tinh khiết mua dưới dạng oxy lỏng (*Liquid Oxygen - LOX*) hoặc oxy trong không khí xung quanh (*ambient air*).
  - Điện trường và va đập electron từ điện cực phóng điện bẻ gãy phân tử oxy thành oxy nguyên tử tự do:
    $$e^- + \text{O}_2 \rightarrow 2\text{O} + e^-$$
  - Oxy nguyên tử kết hợp tức thời với phân tử oxy khí quyển tạo thành ozone theo phản ứng thuận nghịch:
    $$\text{O} + \text{O}_2 \leftrightarrow \text{O}_3$$
- Hiệu suất tạo ozone và yêu cầu xử lý khí nạp (LOX so với Không khí xung quanh):
  - Khi sử dụng nguồn oxy lỏng (LOX):
    - Khí thoát ra từ thiết bị tạo ozone chứa hàm lượng ozone từ $5\%$ đến $8\%$ theo thể tích.
    - Hỗn hợp khí ozone và oxy sau đó được khuếch tán trực tiếp vào dòng nước cần khử trùng.
  - Khi sử dụng nguồn không khí xung quanh (*Ambient air*):
    - Hơi ẩm dạng vết trong không khí phản ứng với nitơ ($\text{N}_2$) dưới tác dụng của năng lượng phóng điện hoa tạo ra axit nitric:
      $$\text{O}_3 + \text{N}_2 + \text{O}_2 + \text{H}_2\text{O} \xrightleftharpoons{h\nu} 2\text{HNO}_3$$
    - Axit nitric sinh ra ăn mòn và phá hủy buồng tạo khí cùng các điện cực của máy ozone.
    - Yêu cầu thiết kế bắt buộc: hệ thống phải trang bị dây chuyền sấy khô không khí nạp đến độ ẩm cực thấp (điểm sương sâu) trước khi cấp vào buồng phóng điện.
- Cấu phần của hệ thống khử trùng bằng ozone (*Components of an ozone disinfection system*):
  - Hệ thống khử trùng hoàn chỉnh bao gồm ba cụm thành phần chính:
    - (a) Cụm xử lý và chuẩn bị nguồn khí cấp từ không khí xung quanh (*preparation system for ozone generation from ambient air*): gồm lọc bụi khí (*Filtration*), máy nén khí (*Compression*), thiết bị trao đổi nhiệt làm mát (*Heat exchange*), bộ tách ẩm sơ cấp (*Separation*), máy làm lạnh ngưng tụ ẩm (*Refrigeration*), bộ tách ẩm thứ cấp (*Separation*), và tháp sấy hút ẩm (*Desiccation*) để cấp khí khô vào buồng tạo ozone.
    - (b) Cụm tạo khí ozone bằng phóng điện corona (*generation of ozone by corona discharge*): đặt điện áp xoay chiều cao thế (*High AC voltage*) qua hai điện cực phủ lớp điện môi cách điện (*Dielectric*), duy trì khe hẹp phóng điện $1\text{--}3\text{ mm}$ để phân ly dòng khí $\text{O}_2$ thành $\text{O}_3$.
    - (c) Cụm châm hòa tan ozone vào nước bằng dòng nhánh (*side-stream injection of ozone*): bơm dòng nhánh (*Side-stream pump*) trích một phần nước từ đường ống chính, đẩy qua ống trộn Venturi (*Venturi injector*) hút khí ozone hòa tan vào nước, qua bình tách khí (*Degas vessel*) có van điều áp dẫn khí dư về tháp phân hủy ozone (*ozone destruction unit*), và đưa dòng nước hòa tan ozone vào bể tiếp xúc.
  - **Hình 12.** Sơ đồ cấu tạo hệ thống khử trùng bằng ozone
    - <img src="ch07_disinfection/assets/fig_12_p18.png" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Thể hiện cấu trúc ba phân khu công nghệ: chuẩn bị khí khô từ không khí xung quanh, buồng phóng điện corona và cụm châm hòa trộn ozone dòng nhánh.
    - **Từ đâu mà thấy được**
      - Cụm (a): chuỗi thiết bị lọc khí, nén, giải nhiệt, tách ẩm, làm lạnh và tháp sấy hút ẩm cấp khí khô (`Dry air to ozonator`).
      - Cụm (b): sơ đồ khe hẹp $1\text{--}3\text{ mm}$ giữa hai điện cực điện môi dưới điện áp xoay chiều cao thế biến đổi $\text{O}_2$ thành $\text{O}_3$.
      - Cụm (c): trích dòng nhánh qua bơm, ống Venturi hút ozone, bình tách khí có van điều áp xả khí dư về tháp phân hủy trước khi cấp vào bể tiếp xúc.

#### Ultraviolet (UV) Radiation

##### Bức xạ Cực tím và Bản chất Quang hóa (Ultraviolet Radiation & Photochemistry)

- Phản ứng quang hóa (photochemistry) biến thiên rõ rệt theo các vùng bước sóng của phổ điện từ:
  - Rất ít phản ứng quang hóa xảy ra trong vùng cận hồng ngoại (near infrared), ngoại trừ ở một số vi khuẩn quang hợp (photosynthetic bacteria).
  - Vùng ánh sáng nhìn thấy ($400\text{--}700\text{ nm}$) hoạt động hoàn toàn cho quá trình quang hợp ở thực vật bậc cao và tảo lục (photosynthesis in green plants and algae).
- Dải bức xạ tử ngoại ($100\text{--}400\text{ nm}$) được phân thành ba vùng chính theo mức độ nhạy cảm của da người:
  - Vùng UVA ($315\text{--}400\text{ nm}$): Gây ra những biến đổi trên bề mặt da dẫn đến hiện tượng sạm da / rám nắng (tanning).
  - Vùng UVB ($280\text{--}315\text{ nm}$): Có khả năng gây bỏng rát da (skin burning) và có xu hướng gây ung thư da (induce skin cancer).
  - Vùng UVC ($200\text{--}280\text{ nm}$): Cực kỳ nguy hiểm do bị hấp thụ mạnh bởi các phân tử protein và axit nucleic (ADN/ARN), dẫn đến đột biến gen (cell mutations) hoặc gây chết tế bào (cell death).
- Năng lượng điện từ UV thường được sinh ra bởi dòng chuyển dời electron từ nguồn điện qua hơi thủy ngân ion hóa (ionized mercury vapor) bên trong bóng đèn.
- Cấu tạo và cơ cấu thiết bị khử trùng UV công nghiệp:
  - Các nhà sản xuất đã phát triển hệ thống bố trí đèn UV lắp đặt trong các bình chịu áp lực (vessels) hoặc mương hở (channels) nhằm cung cấp ánh sáng UV trong dải diệt khuẩn (germicidal range) để bất hoạt vi khuẩn, virus và các vi sinh vật khác.
  - Đèn UV có cấu tạo tương đồng với đèn huỳnh quang dân dụng, ngoại trừ việc đèn huỳnh quang được tráng một lớp phốt pho (phosphorus) bên trong thành ống để biến đổi tia UV thành ánh sáng khả kiến.
- Vị trí vùng tử ngoại trong phổ bức xạ điện từ và các dải bước sóng:
  - **Hình 14.** Vị trí vùng tử ngoại trong phổ bức xạ điện từ
    - <img src="ch07_disinfection/assets/fig_14_p20.png" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Cấu trúc phổ định vị vùng cực tím ($100\text{--}400\text{ nm}$) nằm giữa tia X và ánh sáng nhìn thấy, đồng thời xác lập vạch mốc diệt khuẩn tối ưu $254\text{ nm}$ trong dải sóng UVC.
    - **Từ đâu mà thấy được**
      - Trục phổ trên: Bức xạ tử ngoại (Ultraviolet) nằm liền kề giữa tia X (X-Rays, $10^{-2}\text{--}100\text{ nm}$) và dải ánh sáng nhìn thấy (Visible, $400\text{--}700\text{ nm}$).
      - Khung mở rộng phía dưới chia 4 dải sóng liên tiếp: Vacuum UV ($100\text{--}200\text{ nm}$), UV-C ($200\text{--}280\text{ nm}$), UV-B ($280\text{--}315\text{ nm}$), và UV-A ($315\text{--}400\text{ nm}$); vạch chỉ số $254\text{ nm}$ nằm trọng tâm trong khối UV-C.

##### Đặc tính Kỹ thuật Các Dòng Đèn Khử trùng UV (Technical Characteristics of UV Lamps)

- Ba chủng loại đèn UV thương dụng chính trong công nghệ xử lý nước gồm: đèn áp suất thấp cường độ thấp (Low-pressure low-intensity), đèn áp suất thấp cường độ cao (Low-pressure high-intensity / amalgam), và đèn áp suất trung bình (Medium-pressure).
- Đặc tính tiêu thụ điện năng và hiệu suất phát bức xạ diệt khuẩn:
  - Đèn áp suất thấp cường độ thấp tiêu thụ công suất điện $40\text{--}100\text{ W}$, dòng điện $350\text{--}550\text{ mA}$, điện áp $220\text{ V}$, đạt hiệu suất diệt khuẩn trên điện năng đầu vào cao nhất $30\text{--}40\,\%$ với công suất phát xạ tại $254\text{ nm}$ đạt $25\text{--}27\text{ W}$.
  - Đèn áp suất thấp cường độ cao tiêu thụ công suất điện $200\text{--}500\text{ W}$ (lên đến $1{,}200\text{ W}$ đối với dòng đèn công suất rất cao), đạt hiệu suất diệt khuẩn $25\text{--}35\,\%$ và công suất phát xạ diệt khuẩn $60\text{--}400\text{ W}$ tại $254\text{ nm}$.
  - Đèn áp suất trung bình tiêu thụ công suất điện cực lớn $1{,}000\text{--}10{,}000\text{ W}$, nhưng hiệu suất diệt khuẩn đầu vào chỉ đạt $10\text{--}15\,\%$ trong dải phổ hiệu quả nhất ($255\text{--}265\text{ nm}$).
- Điều kiện vận hành nhiệt độ, áp suất và kích thước hình học:
  - Nhiệt độ vận hành thành ống đèn: $35\text{--}45\,^\circ\text{C}$ đối với đèn áp suất thấp cường độ thấp; $60\text{--}100\,^\circ\text{C}$ đối với đèn áp suất thấp cường độ cao; và $600\text{--}900\,^\circ\text{C}$ đối với đèn áp suất trung bình.
  - Áp suất riêng phần của hơi thủy ngân ($\text{Hg}$ vapor): $0.00093\text{ kPa}$ (áp suất thấp cường độ thấp), $0.0018\text{--}0.10\text{ kPa}$ (áp suất thấp cường độ cao), và $40\text{--}4{,}000\text{ kPa}$ (áp suất trung bình).
  - Chiều dài đèn áp suất thấp cường độ thấp dao động $0.75\text{--}1.5\text{ m}$ với đường kính $15\text{--}20\text{ mm}$; hai dòng đèn còn lại có kích thước linh hoạt theo thiết kế nhà sản xuất.
- Tuổi thọ thiết bị và mức độ suy giảm quang thông theo thời gian:
  - Tuổi thọ ống thạch anh (sleeve life) đạt $4\text{--}6\text{ năm}$ đối với đèn áp suất thấp, giảm xuống $1\text{--}3\text{ năm}$ đối với đèn áp suất trung bình.
  - Tuổi thọ chấn lưu điện tử (ballast life) đạt $10\text{--}15\text{ năm}$ đối với đèn áp suất thấp, đạt $1\text{--}3\text{ năm}$ đối với đèn áp suất trung bình.
  - Tuổi thọ định mức bóng đèn (estimated lamp life): $8{,}000\text{--}10{,}000\text{ giờ}$ (áp suất thấp cường độ thấp), $8{,}000\text{--}12{,}000\text{ giờ}$ (áp suất thấp cường độ cao), và $4{,}000\text{--}8{,}000\text{ giờ}$ (áp suất trung bình).
  - Mức suy giảm công suất phát xạ diệt khuẩn khi đạt tuổi thọ thiết kế là $20\text{--}25\,\%$ (đèn áp suất thấp cường độ thấp và áp suất trung bình) và $25\text{--}30\,\%$ (đèn áp suất thấp cường độ cao).
- Tổng hợp so sánh thông số kỹ thuật ba dòng đèn UV:
  - **Hình 15.** Đặc tính kỹ thuật của ba loại đèn UV
    - <img src="ch07_disinfection/assets/fig_15_p21.png" alt="Hình 15" />
    - **Hình này chứng minh điều gì**
      - Đèn áp suất thấp đạt hiệu suất diệt khuẩn ($25\text{--}40\,\%$) và tuổi thọ ($8{,}000\text{--}12{,}000\text{ h}$) hiệu quả hơn; đèn áp suất trung bình có mật độ công suất cực lớn ($1{,}000\text{--}10{,}000\text{ W}$) ở nhiệt độ cao ($600\text{--}900\,^\circ\text{C}$).
    - **Từ đâu mà thấy được**
      - Bảng số liệu: Cột Low-pressure low-intensity tiêu thụ $40\text{--}100\text{ W}$, hiệu suất diệt khuẩn $30\text{--}40\,\%$. Cột Low-pressure high-intensity bền nhất ($8{,}000\text{--}12{,}000\text{ h}$). Cột Medium-pressure có công suất $1{,}000\text{--}10{,}000\text{ W}$, nhiệt độ $600\text{--}900\,^\circ\text{C}$ và áp suất hơi thủy ngân $40\text{--}4{,}000\text{ kPa}$.

##### Các Yếu tố Ảnh hưởng đến Hiệu quả Khử trùng UV (Factors Governing UV Disinfection Performance)

- Liều lượng bức xạ UV (Fluence / UV Dose):
  - Liều bức xạ $D$ ($\text{mJ/cm}^2$ hoặc $\text{J/m}^2$, với $1\text{ mJ/cm}^2 = 10\text{ J/m}^2$) được xác định bằng tích số giữa cường độ bức xạ $I$ ($\text{mW/cm}^2$) và thời gian tiếp xúc $t$ ($\text{s}$):
    $$D = I \cdot t$$
  - Mức liều tiêu chuẩn tối thiểu theo quy chuẩn USEPA là $40\text{ mJ/cm}^2$ ($400\text{ J/m}^2$), đảm bảo bất hoạt $\ge 4.0\text{-log}$ đối với vi khuẩn đường ruột, u nang *Giardia* và noãn nang *Cryptosporidium*.
- Độ truyền quang của nước (%UVT - UV Transmittance tại bước sóng $254\text{ nm}$):
  - Cường độ ánh sáng UV suy giảm theo định luật Beer-Lambert khi truyền qua tầng nước dày $x$ ($\text{cm}$):
    $$I(x) = I_0 \cdot 10^{-A_{254} \cdot x}$$
  - Độ truyền quang của nước được định nghĩa:
    $$\%\text{UVT} = 100 \times 10^{-A_{254}}$$
  - Giá trị $\%\text{UVT}$ tối ưu cho hệ thống khử trùng phải đạt $\ge 85\text{--}90\,\%$; khi nước thô có $\%\text{UVT} < 75\,\%$, hiệu quả thâm nhập của photon UV-C suy giảm nghiêm trọng.
- Độ đục và nồng độ chất rắn lơ lửng (Turbidity & Suspended Solids):
  - Các hạt cặn lơ lửng hấp thụ và tán xạ tia UV, đồng thời che chắn các vi sinh vật bám dính trên hạt cặn khỏi sự phơi nhiễm bức xạ (shadowing effect).
  - Độ đục nước đầu vào hệ thống khử trùng UV bắt buộc phải được duy trì ở mức $\le 0.3\text{--}0.5\text{ NTU}$ sau quá trình lắng lọc.
- Đóng cặn bám bẩn trên bề mặt ống bọc thạch anh (Quartz Sleeve Fouling):
  - Các ion kim loại hòa tan và độ cứng gồm sắt ($\text{Fe} > 0.1\text{ mg/L}$), mangan ($\text{Mn} > 0.02\text{ mg/L}$), cùng kết tủa canxi cacbonat ($\text{CaCO}_3$) bám dính trên bề mặt ống thạch anh nóng, tạo lớp màng chắn quang học.
  - Bắt buộc trang bị hệ thống vòng gạt cơ học tự động (wiper rings) hoặc tẩy rửa hóa chất định kỳ để làm sạch bề mặt ống bọc.
- Thủy động lực học của buồng phản ứng UV (Contactor Hydraulics):
  - Dòng chảy qua buồng phản ứng phải tiệm cận trạng thái dòng chảy piston (plug-flow) hoàn hảo để đảm bảo mọi phần tử nước đều nhận đủ liều chiếu xạ đồng đều.
  - Các vùng xoáy chết hoặc hiện tượng ngắn dòng (short-circuiting) làm giảm thời gian lưu thực tế $t_{10}$, khiến một phần vi sinh vật thoát ra mà không nhận đủ liều UV cần thiết.
- Khả năng chống chịu và cơ chế tự phục hồi của vi sinh vật (Microbial Resistance & Repair):
  - Một số loại virus cấu trúc vỏ protein dày hoặc ADN chuỗi đôi như Adenovirus đòi hỏi liều UV cao từ $120$ đến $186\text{ mJ/cm}^2$ để đạt mức bất hoạt $4.0\text{-log}$.
  - Hiện tượng phục hồi quang học (photoreactivation): Dưới tác động của ánh sáng nhìn thấy ($310\text{--}500\text{ nm}$), enzyme photolyase có thể phục hồi liên kết thymine dimer bị bẻ gãy, đòi hỏi phải che tối hệ thống hoặc sử dụng đèn áp suất trung bình có dải phổ rộng để triệt tiêu enzyme phục hồi.

#### Chick-Watson Kinetics and CT Concept

##### Chick-Watson Disinfection Model

- Định luật Chick-Watson (Chick-Watson Law) là mô hình động học nền tảng mô tả tốc độ bất hoạt vi sinh vật dưới tác dụng của chất khử trùng theo thời gian tiếp xúc và nồng độ hóa chất.
- Phương trình vi phân tốc độ bất hoạt vi sinh vật Chick-Watson có dạng:
  $$\frac{dN}{dt} = - k_{cw} C^n N$$
  - $N$: mật độ số lượng vi sinh vật còn sống tại thời điểm $t$ ($\text{CFU/mL}$ hoặc $\text{organisms/L}$).
  - $N_0$: mật độ số lượng vi sinh vật ban đầu tại thời điểm $t = 0$ ($\text{CFU/mL}$ hoặc $\text{organisms/L$).
  - $C$: nồng độ chất khử trùng dư hữu hiệu trong môi trường ($\text{mg/L}$).
  - $t$: thời gian tiếp xúc khử trùng ($\text{s}$ hoặc $\text{min}$).
  - $k_{cw}$: hằng số tốc độ bất hoạt độc lập với nồng độ của Chick-Watson ($\text{L}^n/(\text{mg}^n\cdot\text{s})$ hoặc $\text{s}^{-1}$ khi $n = 1$).
  - $n$: hệ số pha loãng hoặc hệ số bậc nồng độ (coefficient of dilution, không có thứ nguyên).
- Dạng tích phân của phương trình Chick-Watson khi giả định nồng độ chất khử trùng $C$ không đổi trong suốt thời gian phản ứng:
  $$\ln\left(\frac{N}{N_0}\right) = - k_{cw} C^n t$$
  - Biểu diễn theo hàm mũ của tỷ lệ sống sót:
    $$\frac{N}{N_0} = \exp\left(- k_{cw} C^n t\right)$$
  - Chuyển đổi sang logarit cơ số 10 tương ứng với chỉ số log removal:
    $$\log_{10}\left(\frac{N}{N_0}\right) = - \frac{k_{cw}}{\ln(10)} C^n t = - k'_{cw} C^n t$$
- Vai trò và ý nghĩa vật lý của hệ số pha loãng $n$ trong thiết kế công nghệ:
  - Khi $n = 1$: Nồng độ hóa chất $C$ và thời gian tiếp xúc $t$ có mức độ ảnh hưởng tương đương nhau đối với hiệu quả bất hoạt mầm bệnh; tích số $C \cdot t$ là một hằng số xác định mức độ tiêu diệt vi sinh vật, tạo cơ sở toán học trực tiếp cho khái niệm $CT$.
  - Khi $n > 1$: Nồng độ chất khử trùng $C$ có tác động mạnh hơn thời gian tiếp xúc $t$; giải pháp tăng liều lượng hóa chất châm mang lại hiệu quả bất hoạt nhanh hơn nhiều so với việc mở rộng dung tích bể tiếp xúc.
  - Khi $n < 1$: Thời gian tiếp xúc $t$ đóng vai trò chi phối hiệu quả khử trùng; giải pháp kéo dài thời gian lưu nước trong bể tiếp xúc tối ưu hơn và tiết kiệm hóa chất hơn việc tăng nồng độ khử trùng.

##### Hom Inactivation Model

- Mô hình Chick-Watson cổ điển giả định tốc độ bất hoạt không phụ thuộc thời gian, tạo đường thẳng tuyến tính trên thang đo bán logarit $\ln(N/N_0)$ theo $t$, nhưng dữ liệu thực nghiệm thường xuất hiện sai lệch phi tuyến do hiện tượng trễ hoặc kháng hóa chất.
- Mô hình Hom (Hom Model, 1972) mở rộng định luật Chick-Watson bằng cách bổ sung số mũ thời gian $m$ để mô tả chính xác các pha phi tuyến tính trong quá trình diệt khuẩn.
- Phương trình vi phân bất hoạt của mô hình Hom có dạng:
  $$\frac{dN}{dt} = - k_H m C^n N t^{m-1}$$
  - $k_H$: hằng số tốc độ bất hoạt của mô hình Hom ($\text{L}^n/(\text{mg}^n\cdot\text{s}^m)$).
  - $m$: số mũ thời gian thực nghiệm (dimensionless time exponent).
- Dạng tích phân của mô hình Hom khi nồng độ chất khử trùng $C$ duy trì ổn định:
  $$\ln\left(\frac{N}{N_0}\right) = - k_H C^n t^m$$
  - Phương trình tương đương theo logarit thập phân:
    $$\log_{10}\left(\frac{N}{N_0}\right) = - k'_H C^n t^m$$
- Ý nghĩa vật lý và công nghệ của số mũ thời gian $m$:
  - Trường hợp $m = 1$: Mô hình Hom tương đương hoàn toàn với phương trình Chick-Watson chuẩn, phản ánh quá trình tiêu diệt vi sinh vật diễn ra theo quy luật động học bậc một thuần túy.
  - Trường hợp $m > 1$: Đường cong sống sót thể hiện hiệu ứng vai trễ (shoulder effect hoặc lag phase); tốc độ bất hoạt ban đầu rất chậm do chất khử trùng mất thời gian khuếch tán qua vỏ tế bào, màng lipid hoặc tích lũy liều tổn thương trước khi gây chết vi sinh vật.
  - Trường hợp $m < 1$: Đường cong sống sót thể hiện hiệu ứng kéo đuôi (tailing-off effect hoặc retardation phase); tốc độ bất hoạt giảm dần theo thời gian do sự hiện diện của quần thể vi sinh vật có khả năng kháng thuốc cao, hiện tượng kết cụm tế bào (clumping) hoặc vi sinh vật được bảo vệ bên trong các hạt cặn lơ lửng.

##### CT Concept and Disinfectant Residual Relationship

- Tích số $CT$ (nồng độ chất khử trùng nhân thời gian tiếp xúc) là tiêu chuẩn định lượng bắt buộc do Cơ quan Bảo vệ Môi trường Hoa Kỳ (US EPA) ban hành để đánh giá và kiểm soát quy trình khử trùng nước sinh hoạt.
- Định nghĩa giải tích của tích số $CT$:
  $$CT = C \times t_{10}$$
  - $C$: nồng độ chất khử trùng dư đo tại điểm đầu ra của bể tiếp xúc ($\text{mg/L}$).
  - $t_{10}$: thời gian tiếp xúc hữu hiệu ($\text{min}$), định nghĩa là khoảng thời gian cần thiết để $10\%$ lượng nước đưa vào bể chảy ra khỏi bể tiếp xúc (nghĩa là $90\%$ lượng nước được lưu lại trong bể tối thiểu bằng thời gian $t_{10}$).
- Mối liên hệ giữa thời gian tiếp xúc hữu hiệu $t_{10}$ và thời gian lưu nước lý thuyết $t_0$:
  $$t_{10} = \left(\frac{t_{10}}{t_0}\right) \times t_0 = \left(\frac{t_{10}}{t_0}\right) \times \frac{V}{Q}$$
  - $V$: dung tích hữu ích của bể tiếp xúc ($\text{m}^3$).
  - $Q$: lưu lượng nước cấp xử lý tối đa qua bể ($\text{m}^3/\text{h}$ hoặc $\text{m}^3/\text{min}$).
  - $t_0$: thời gian lưu thủy lực lý thuyết ($t_0 = V / Q$, $\text{min}$).
  - $t_{10}/t_0$: hệ số vách ngăn thủy lực (baffling factor), phân loại từ $0.1$ (dòng chảy tắt nghiêm trọng), $0.3$ (kém, không vách ngăn), $0.5$ (trung bình), $0.7$ (hiệu quả hơn, vách ngăn dòng uốn lượn) đến $1.0$ (dòng chảy piston lý tưởng).
- Nồng độ clo tự do dư $C$ tham gia phản ứng khử trùng phụ thuộc trực tiếp vào đặc tính chất lượng nước nguồn và liều lượng hóa chất châm qua điểm đột biến:
  - Khi nước nguồn không chứa amoniac hoặc hợp chất hữu cơ (ví dụ nguồn nước ngầm sâu), quá trình hình thành clo tự do dư diễn ra nhanh chóng ngay sau khi oxy hóa hết các chất khử vô cơ:
- Nguyên lý cộng dồn giá trị $CT$ trong chuỗi công trình xử lý nước:
  - Khi nước chảy qua nhiều ngăn tiếp xúc hoặc qua các công trình đơn vị nối tiếp nhau, tổng mức độ bất hoạt được tính bằng tổng các tỷ số $CT$ thành phần:
    $$\text{Total Inactivation Ratio} = \sum_{i=1}^{k} \frac{CT_{\text{calc}, i}}{CT_{\text{req}, i}} \ge 1.0$$
  - $CT_{\text{calc}, i}$: tích số $CT$ tính toán thực tế tại công trình thứ $i$ ($CT_{\text{calc}, i} = C_i \times t_{10, i}$).
  - $CT_{\text{req}, i}$: tích số $CT$ yêu cầu theo quy chuẩn tương ứng với điều kiện nhiệt độ, $\text{pH}$ và mức log removal mục tiêu tại công trình thứ $i$.

##### Pathogen Inactivation Standards and CT Values

- Mức độ loại bỏ logarit (Log Removal) phản ánh tỷ lệ phần trăm vi sinh vật bị tiêu diệt theo các bậc lũy thừa cơ số 10:
  $$\text{Log Removal} = \log_{10}\left(\frac{N_0}{N}\right) = - \log_{10}\left(\frac{N}{N_0}\right)$$
  - Loại bỏ $0.5\text{-log}$: mật độ vi sinh vật còn lại bằng $10^{-0.5} \approx 31.62\%$, tương ứng hiệu suất loại bỏ $68.38\%$.
  - Loại bỏ $1.0\text{-log}$: mật độ vi sinh vật còn lại bằng $10^{-1} = 10\%$, tương ứng hiệu suất loại bỏ $90\%$.
  - Loại bỏ $2.0\text{-log}$: mật độ vi sinh vật còn lại bằng $10^{-2} = 1\%$, tương ứng hiệu suất loại bỏ $99\%$.
  - Loại bỏ $3.0\text{-log}$: mật độ vi sinh vật còn lại bằng $10^{-3} = 0.1\%$, tương ứng hiệu suất loại bỏ $99.9\%$.
  - Loại bỏ $4.0\text{-log}$: mật độ vi sinh vật còn lại bằng $10^{-4} = 0.01\%$, tương ứng hiệu suất loại bỏ $99.99\%$.
- Tiêu chuẩn tích số $CT$ đối với Virus đường ruột (Enteric Viruses) ở điều kiện chuẩn $10^\circ\text{C}$ và $\text{pH} = 6\text{--}9$:
  - Ozone ($\text{O}_3$): Hiệu lực diệt virus hiệu quả hơn nhất với giá trị $CT$ chỉ cần $0.5\text{ mg}\cdot\text{min/L}$ cho $2\text{-log}$, $0.8\text{ mg}\cdot\text{min/L}$ cho $3\text{-log}$, và $1.0\text{ mg}\cdot\text{min/L}$ cho $4\text{-log}$.
  - Clo tự do (Free Chlorine): $CT$ yêu cầu là $3\text{ mg}\cdot\text{min/L}$ ($2\text{-log}$), $4\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$), và $6\text{ mg}\cdot\text{min/L}$ ($4\text{-log}$) ở nồng độ clo dư $0.2\text{--}0.5\text{ mg/L}$.
  - Clo dioxit ($\text{ClO}_2$): $CT$ yêu cầu là $4.2\text{ mg}\cdot\text{min/L}$ ($2\text{-log}$), $12.8\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$), và $25.1\text{ mg}\cdot\text{min/L}$ ($4\text{-log}$).
  - Chloramine: Hiệu lực diệt virus yếu nhất do phản ứng chậm; đòi hỏi giá trị $CT$ rất lớn gồm $643\text{ mg}\cdot\text{min/L}$ ($2\text{-log}$), $1{,}067\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$), và $1{,}491\text{ mg}\cdot\text{min/L}$ ($4\text{-log}$) ở điều kiện $\text{pH} = 8$.
  - Bức xạ tia cực tím (UV): Liều chiếu bức xạ (UV Fluence) yêu cầu là $21\text{ mJ/cm}^2$ (hay $\text{mW}\cdot\text{s/cm}^2$) cho $2\text{-log}$ và $36\text{ mJ/cm}^2$ cho $3\text{-log}$.
- Tiêu chuẩn tích số $CT$ đối với u nang Giardia lamblia (Giardia Cysts) ở điều kiện chuẩn $10^\circ\text{C}$, $\text{pH} = 7$, và clo dư $\le 0.4\text{ mg/L}$:
  - Ozone ($\text{O}_3$): Đạt hiệu quả tiêu diệt Giardia cao nhất trong các hóa chất oxy hóa, với giá trị $CT$ lần lượt là $0.23$ ($0.5\text{-log}$), $0.48$ ($1\text{-log}$), $0.72$ ($1.5\text{-log}$), $0.95$ ($2\text{-log}$), $1.2$ ($2.5\text{-log}$), và $1.43\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$).
  - Clo dioxit ($\text{ClO}_2$): $CT$ yêu cầu gồm $4$ ($0.5\text{-log}$), $7.7$ ($1\text{-log}$), $12$ ($1.5\text{-log}$), $15$ ($2\text{-log}$), $19$ ($2.5\text{-log}$), và $23\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$).
  - Clo tự do (Free Chlorine): $CT$ yêu cầu gồm $17$ ($0.5\text{-log}$), $35$ ($1\text{-log}$), $52$ ($1.5\text{-log}$), $69$ ($2\text{-log}$), $87$ ($2.5\text{-log}$), và $104\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$) ở $\text{pH} = 7$; khi $\text{pH}$ tăng lên $8.0$ hoặc nhiệt độ giảm về $0.5^\circ\text{C}$, giá trị $CT$ yêu cầu tăng lên gấp $2\text{--}3$ lần do sự suy giảm nồng độ $\text{HOCl}$.
  - Chloramine: Hiệu quả khử trùng Giardia rất kém, yêu cầu giá trị $CT$ cực cao gồm $310$ ($0.5\text{-log}$), $615$ ($1\text{-log}$), $930$ ($1.5\text{-log}$), $1{,}230$ ($2\text{-log}$), $1{,}540$ ($2.5\text{-log}$), và $1{,}850\text{ mg}\cdot\text{min/L}$ ($3\text{-log}$).
  - Bức xạ tia cực tím (UV): Khả năng bất hoạt Giardia của UV cực kỳ hiệu quả; liều UV chỉ cần khoảng $1.5\text{ mJ/cm}^2$ cho $0.5\text{-log}$ và khoảng $11\text{ mJ/cm}^2$ để đạt mức bất hoạt $3\text{-log}$.
- Tiêu chuẩn bất hoạt đối với u bào Cryptosporidium parvum (Cryptosporidium Oocysts):
  - U bào Cryptosporidium có lớp vỏ polysaccharide dày và liên kết chéo bền vững, khiến chúng có khả năng chống chịu cực cao đối với hóa chất clo tự do thông thường:
    - Giá trị $CT$ của clo tự do để bất hoạt $2\text{-log}$ Cryptosporidium vượt quá $7{,}000\text{--}10{,}000\text{ mg}\cdot\text{min/L}$, một mức nồng độ bất khả thi trong cấp nước sinh hoạt do làm bùng phát phụ phẩm độc hại trihalomethane (THMs) và axit haloacetic (HAAs).
    - Chloramine hoàn toàn không có khả năng bất hoạt thực tế đối với Cryptosporidium trong dải liều lượng cho phép.
  - Ozone ($\text{O}_3$): Là chất khử trùng hóa học duy nhất có khả năng oxy hóa và bất hoạt Cryptosporidium ở mức khả thi kỹ thuật; giá trị $CT$ yêu cầu ở $10^\circ\text{C}$ đạt khoảng $5.7\text{ mg}\cdot\text{min/L}$ cho $1\text{-log}$, $11.5\text{ mg}\cdot\text{min/L}$ cho $2\text{-log}$, và $17.2\text{ mg}\cdot\text{min/L}$ cho $3\text{-log}$.
  - Bức xạ tia cực tím (UV): Là công nghệ bất hoạt Cryptosporidium tối ưu nhất được US EPA phê chuẩn theo quy chuẩn LT2ESWTR (Long Term 2 Enhanced Surface Water Treatment Rule):
    - Cơ chế bất hoạt của UV dựa trên sự hấp thụ photon năng lượng cao gây biến dạng cấu trúc phân tử DNA (tạo các dimer pyrimidine), ngăn chặn hoàn toàn khả năng nhân đôi và gây nhiễm trùng mà không cần phá vỡ vỏ u bào.
    - Liều lượng tia cực tím yêu cầu rất thấp: chỉ cần $5.8\text{ mJ/cm}^2$ để đạt $2\text{-log}$ ($99\%$), $12\text{ mJ/cm}^2$ để đạt $3\text{-log}$ ($99.9\%$), và $22\text{ mJ/cm}^2$ để đạt $4\text{-log}$ ($99.99\%$) bất hoạt Cryptosporidium.

#### Disinfection By-Products (DBPs)

##### Tổng quan và cơ chế hình thành sản phẩm phụ khử trùng (DBPs Overview and Formation Chemistry)

* Bản chất và nguồn gốc phát sinh sản phẩm phụ khử trùng (Disinfection By-Products - DBPs):
  * Quá trình sử dụng hóa chất để oxy hóa và khử trùng diễn ra tại hầu hết các trạm xử lý nước cấp (drinking water treatment plants).
  * Hóa chất khử trùng phản ứng với các hợp chất hữu cơ tự nhiên (Natural Organic Matter - NOM, bao gồm humic và fulvic acid) cùng các ion vô cơ (bromide $\text{Br}^-$, iodide $\text{I}^-$) có sẵn trong nước nguồn tạo thành các sản phẩm phụ khử trùng (DBPs).
  * Việc tìm hiểu sâu về DBPs mang tính cấp thiết do nhiều hợp chất có hoạt tính sinh học độc hại, đe dọa trực tiếp sức khỏe người tiêu dùng.
  * Các tác động sức khỏe của nhiều loại DBPs chưa được sáng tỏ hoàn toàn và liên tục được phát hiện mới, biến DBP thành lĩnh vực biến động và được giám sát nghiêm ngặt nhất trong kỹ thuật xử lý nước cấp.
* Lịch sử phát hiện và nghiên cứu DBPs:
  * Đầu thập niên 1970, các nhà khoa học đã nhận diện và định lượng thành công sự xuất hiện của chloroform ($\text{CHCl}_3$) cùng các trihalomethane ($\text{THMs}$) trong nước cấp sau xử lý.
  * Nghiên cứu đã chứng minh sự hình thành $\text{THMs}$ liên hệ trực tiếp với quá trình clo hóa (chlorination) bằng clo tự do.
  * Các chất khử trùng và oxy hóa khác cũng phản ứng với thành phần nước tạo ra những nhóm DBPs đặc trưng riêng biệt:
    * Clo liên kết (Combined chlorine / Chloramines) phản ứng sinh ra các axit haloacetic (Haloacetic acids - $\text{HAAs}$).
    * Clo dioxit ($\text{ClO}_2$) phân hủy và phản ứng tạo thành các ion chlorite ($\text{ClO}_2^-$) và ion chlorate ($\text{ClO}_3^-$).
    * Ozone ($\text{O}_3$) oxy hóa chất hữu cơ tạo các aldehyde và oxy hóa ion bromide tạo ion bromate ($\text{BrO}_3^-$).
* Bảng phân loại đầy đủ các chất khử trùng dư và sản phẩm phụ phản ứng trong nước cấp:
  * Nhóm chất khử trùng tồn dư (Disinfectant Residuals):
    * Clo tự do (Free Chlorine): Axit hypoclorơ ($\text{HOCl}$) và ion hypoclorit ($\text{OCl}^-$).
    * Chloramines: Monochloramine ($\text{NH}_2\text{Cl}$).
    * Clo dioxit ($\text{ClO}_2$).
  * Nhóm sản phẩm phụ vô cơ (Inorganic Byproducts):
    * Ion chlorate ($\text{ClO}_3^-$).
    * Ion chlorite ($\text{ClO}_2^-$).
    * Ion bromate ($\text{BrO}_3^-$).
    * Ion iodate ($\text{IO}_3^-$).
    * Hydro peroxide ($\text{H}_2\text{O}_2$).
    * Amoniac tự do ($\text{NH}_3$).
  * Nhóm sản phẩm phụ oxy hóa hữu cơ (Organic Oxidation Byproducts):
    * Nhóm aldehyde: Formaldehyde ($\text{HCHO}$), acetaldehyde ($\text{CH}_3\text{CHO}$), glyoxal ($\text{OHC-CHO}$), hexanal, heptanal.
    * Nhóm axit cacboxylic: Axit hexanoic, axit heptanoic, axit oxalic ($\text{HOOC-COOH}$).
    * Cacbon hữu cơ dễ đồng hóa (Assimilable Organic Carbon - AOC).
  * Nhóm sản phẩm phụ hữu cơ halogen hóa (Halogenated Organic Byproducts):
    * Trihalomethanes ($\text{THMs}$): Chloroform ($\text{CHCl}_3$), bromodichloromethane ($\text{CHBrCl}_2$), dibromochloromethane ($\text{CHBr}_2\text{Cl}$), bromoform ($\text{CHBr}_3$).
    * Haloacetic acids ($\text{HAAs}$): Monochloroacetic acid ($\text{MCAA}$), dichloroacetic acid ($\text{DCAA}$), trichloroacetic acid ($\text{TCAA}$), monobromoacetic acid ($\text{MBAA}$), dibromoacetic acid ($\text{DBAA}$).
    * Haloacetonitriles ($\text{HANs}$): Dichloroacetonitrile ($\text{DCAN}$), bromochloroacetonitrile ($\text{BCAN}$), dibromoacetonitrile ($\text{DBAN}$), trichloroacetonitrile ($\text{TCAN}$).
    * Haloketones: $1{,}1\text{-dichloropropanone}$, $1{,}1{,}1\text{-trichloropropanone}$.
    * Chlorophenols: $2\text{-chlorophenol}$, $2{,}4\text{-dichlorophenol}$, $2{,}4{,}6\text{-trichlorophenol}$.
    * Hợp chất chloropicrin ($\text{CCl}_3\text{NO}_2$).
    * Hợp chất chloral hydrate ($\text{CCl}_3\text{CH(OH)}_2$).
    * Cyanogen chloride ($\text{CNCl}$).
    * Hợp chất N-organochloramines.
    * Hợp chất mutagenic potent $\text{MX}$ ($3\text{-chloro-}4\text{-(dichloromethyl)-}5\text{-hydroxy-}2(5H)\text{-furanone}$).

##### Các nhóm sản phẩm phụ khử trùng chính và độc tính (Major DBP Groups and Toxicity)

* Nhóm Trihalomethanes ($\text{THMs}$ / TTHM):
  * Cấu trúc phân tử: Hợp chất một nguyên tử cacbon gắn với ba nguyên tử halogen theo công thức chung $\text{CHX}_3$ (với $\text{X} = \text{Cl}$ hoặc $\text{Br}$).
  * 4 hợp chất $\text{THM}$ tạo thành tổng $\text{TTHM}$ gồm:
    * Chloroform ($\text{CHCl}_3$): Sản phẩm chiếm tỷ trọng lớn nhất khi nước nguồn có hàm lượng bromide thấp.
    * Bromodichloromethane ($\text{CHBrCl}_2$): Hình thành khi có sự tham gia đồng thời của clo và ion bromide.
    * Dibromochloromethane ($\text{CHBr}_2\text{Cl}$): Tỷ lệ brom hóa gia tăng khi nồng độ $\text{Br}^-$ trong nước nguồn cao.
    * Bromoform ($\text{CHBr}_3$): Sản phẩm brom hóa hoàn toàn khi tỷ số ion bromide trên clo châm cao.
  * Cơ chế hình thành: Phản ứng thế haloform giữa axit hypoclorơ ($\text{HOCl}$) hoặc axit hypobromơ ($\text{HOBr}$) với các nhóm chức acetyl, polyphenol và tiền chất enol hóa trong cấu trúc NOM:
    * Clo oxy hóa ion bromide thành axit hypobromơ:
      $$\text{HOCl} + \text{Br}^- \rightarrow \text{HOBr} + \text{Cl}^-$$
    * Phản ứng thế halogen liên tiếp vào khung hữu cơ phân cắt liên kết $\text{C-C}$ giải phóng $\text{CHX}_3$.
  * Tác động sức khỏe và giới hạn quy chuẩn:
    * Gây tổn thương gan, thận và hệ thống thần kinh trung ương; liên quan đến nguy cơ ung thư bàng quang và ung thư đại trực tràng.
    * Tiêu chuẩn nước uống (USEPA Stage 2 DBPR và QCVN 01-1:2018/BYT) quy định nồng độ tối đa cho phép ($\text{MCL}$) của tổng trihalomethanes ($\text{TTHM}$) là $0{,}080\text{ mg/L}$ ($80\ \mu\text{g/L}$).
* Nhóm Haloacetic Acids ($\text{HAAs}$ / HAA5):
  * Cấu trúc phân tử: Axit cacboxylic mạch ngắn bị thay thế nguyên tử hydro ở vị trí cacbon alpha bằng các halogen ($\text{Cl}, \text{Br}$).
  * 5 hợp chất $\text{HAA}$ được quy chuẩn hóa ($\text{HAA5}$) gồm:
    * Monochloroacetic acid ($\text{MCAA}$, $\text{CH}_2\text{ClCOOH}$).
    * Dichloroacetic acid ($\text{DCAA}$, $\text{CHCl}_2\text{COOH}$).
    * Trichloroacetic acid ($\text{TCAA}$, $\text{CCl}_3\text{COOH}$).
    * Monobromoacetic acid ($\text{MBAA}$, $\text{CH}_2\text{BrCOOH}$).
    * Dibromoacetic acid ($\text{DBAA}$, $\text{CHBr}_2\text{COOH}$).
  * Cơ chế hình thành: Clo hóa và brom hóa trực tiếp các đại phân tử hữu cơ fulvic/humic mà không cần qua giai đoạn phân cắt haloform hoàn toàn. $\text{HAAs}$ có độ hòa tan cao trong nước và không bay hơi như $\text{THMs}$.
  * Độc tính và giới hạn quy chuẩn:
    * $\text{DCAA}$ và $\text{TCAA}$ gây độc cho gan, quái thai và ức chế enzym chuyển hóa pyruvate.
    * Tiêu chuẩn USEPA quy định nồng độ tối đa $\text{MCL}$ đối với $\text{HAA5}$ là $0{,}060\text{ mg/L}$ ($60\ \mu\text{g/L}$).
* Nhóm Bromate ($\text{BrO}_3^-$):
  * Nguồn gốc phát sinh: Sản phẩm oxy hóa vô cơ đặc trưng xuất hiện khi sử dụng ozone ($\text{O}_3$) để khử trùng hoặc oxy hóa nguồn nước chứa ion bromide ($\text{Br}^-$).
  * Chuỗi cơ chế phản ứng hai pha (phân tử ozone và gốc tự do hydroxyl $\cdot\text{OH}$):
    * Phản ứng trực tiếp với ozone phân tử:
      $$\text{Br}^- + \text{O}_3 \rightarrow \text{OBr}^- + \text{O}_2$$
      $$\text{OBr}^- + \text{H}^+ \rightleftharpoons \text{HOBr} \quad (pK_a \approx 8{,}8)$$
      $$\text{OBr}^- + 2\text{O}_3 \rightarrow \text{BrO}_3^- + 2\text{O}_2$$
    * Phản ứng qua trung gian gốc tự do hydroxyl ($\cdot\text{OH}$):
      $$\text{Br}^- + \cdot\text{OH} \rightarrow \text{Br}^\cdot + \text{OH}^- \xrightarrow{\text{O}_3/\cdot\text{OH}} \dots \rightarrow \text{BrO}_3^-$$
  * Độc tính và giới hạn quy chuẩn:
    * Bromate là chất gây đột biến gen và phá hủy chuỗi DNA; được xếp vào nhóm có khả năng cao gây ung thư thận và tuyến giáp.
    * Tiêu chuẩn USEPA và WHO quy định giới hạn nghiêm ngặt $\text{MCL}$ của bromate trong nước uống là $0{,}010\text{ mg/L}$ ($10\ \mu\text{g/L}$).
* Nhóm Chlorite ($\text{ClO}_2^-$) và Chlorate ($\text{ClO}_3^-$):
  * Nguồn gốc phát sinh: Sản phẩm phụ vô cơ chủ yếu từ quá trình sử dụng clo dioxit ($\text{ClO}_2$) hoặc từ sự phân hủy dung dịch muối hypoclorit lưu kho.
  * Cơ chế chuyển hóa:
    * Clo dioxit phản ứng oxy hóa chất hữu cơ thông qua cơ chế nhận 1 electron tạo ion chlorite:
      $$\text{ClO}_2 + \text{e}^- \rightarrow \text{ClO}_2^-$$
    * Khoảng $50\%\text{--}70\%$ liều clo dioxit châm vào nước bị chuyển hóa trực tiếp thành ion chlorite ($\text{ClO}_2^-$).
    * Phản ứng tạo ion chlorate ($\text{ClO}_3^-$) diễn ra do:
      * Tác động phân hủy quang hóa (photochemical decomposition) của ánh sáng mặt trời lên clo dioxit hòa tan.
      * Hiệu suất kém trong thiết bị điều chế $\text{ClO}_2$ tại chỗ (thừa clo hoặc muối chlorate).
      * Dung dịch trữ $\text{NaOCl}$ bị phân hủy tự nhiên theo thời gian theo phản ứng tự oxy hóa-khử:
        $$3\text{OCl}^- \rightarrow \text{ClO}_3^- + 2\text{Cl}^-$$
  * Độc tính và giới hạn quy chuẩn:
    * Chlorite gây oxy hóa hemoglobin thành methemoglobin dẫn đến thiếu máu tán huyết (hemolytic anemia) và tổn thương tế bào hồng cầu; tác động đến hệ thần kinh thai nhi.
    * USEPA quy định mức tối đa cho phép $\text{MCL}$ đối với ion chlorite là $1{,}0\text{ mg/L}$ ($1000\ \mu\text{g/L}$) và giới hạn nồng độ dư $\text{MRDL}$ của $\text{ClO}_2$ là $0{,}8\text{ mg/L}$.
* Các sản phẩm phụ oxy hóa và hữu cơ đặc thù khác:
  * Nhóm Aldehydes (Formaldehyde, Acetaldehyde, Glyoxal):
    * Sinh ra do ozone bẻ gãy các liên kết carbon đôi trong cấu trúc phân tử NOM.
    * Dễ phân hủy sinh học nhưng làm tăng chỉ số cacbon hữu cơ dễ đồng hóa (AOC), kích thích vi khuẩn phát triển trở lại trong mạng lưới đường ống cấp nước.
  * Hợp chất Mutagen X ($\text{MX}$):
    * Hợp chất furanone clo hóa có hoạt tính gây đột biến gen (Ames mutagenicity) mạnh gấp hàng ngàn lần so với các DBPs thông thường khác, dù nồng độ xuất hiện chỉ ở mức $\text{ng/L}$.
  * Nhóm Haloacetonitriles ($\text{HANs}$) và Haloketones:
    * Độc tính tế bào (cytotoxicity) và độc tính gen cao hơn đáng kể so với $\text{THMs}$.

##### Hệ thống phân loại khả năng gây ung thư theo USEPA (USEPA Carcinogenic Classification Scheme)

* Nguyên tắc và tiêu chí phân nhóm hóa chất gây ung thư theo tiêu chuẩn USEPA (1996 Scheme):
  * **Group A: Human Carcinogen (Chất gây ung thư ở người)**:
    * Bằng chứng đầy đủ từ các nghiên cứu dịch tễ học (epidemiologic studies) chứng minh mối liên hệ nhân quả rõ ràng giữa việc phơi nhiễm hóa chất và bệnh ung thư.
  * **Group B: Probable Human Carcinogen (Chất có khả năng cao gây ung thư ở người)**:
    * Nhóm B được chia thành hai nhánh tùy theo mức độ dữ liệu trên người:
      * **Group B1**: Bằng chứng dịch tễ học hạn chế ở người (limited evidence in human epidemiologic studies).
      * **Group B2**: Bằng chứng đầy đủ từ các thử nghiệm ung thư trên động vật (sufficient evidence from animal studies), nhưng thiếu bằng chứng hoặc không có dữ liệu trên người.
  * **Group C: Possible Human Carcinogen (Chất có thể gây ung thư ở người)**:
    * Bằng chứng gây ung thư hạn chế trên động vật (limited evidence from animal studies) và không có hoặc không đủ dữ liệu nghiên cứu trên người.
  * **Group D: Not Classifiable (Chất không thể phân loại)**:
    * Dữ liệu nghiên cứu trên người và động vật không đầy đủ hoặc hoàn toàn không có bằng chứng về khả năng sinh ung thư.
  * **Group E: No Evidence of Carcinogenicity for Humans (Không có bằng chứng gây ung thư ở người)**:
    * Không tìm thấy bằng chứng sinh ung thư trong tối thiểu hai thử nghiệm động vật đạt chuẩn trên các loài khác nhau hoặc trong các nghiên cứu dịch tễ học đáng tin cậy.
* Bảng tra cứu trạng thái phân loại ung thư của các chất khử trùng và DBPs (theo USEPA):

| Chất ô nhiễm / Hóa chất khử trùng (Contaminant) | Phân loại khả năng gây ung thư (Cancer Classification) | Ghi chú và cơ sở đánh giá |
| :--- | :---: | :--- |
| **Chloroform ($\text{CHCl}_3$)** | **B2** | Đủ bằng chứng gây khối u gan/thận trên động vật thí nghiệm |
| **Bromodichloromethane ($\text{CHBrCl}_2$)** | **B2** | Đủ bằng chứng sinh u trên chuột cống và chuột nhắt |
| **Dibromochloromethane ($\text{CHBr}_2\text{Cl}$)** | **C** | Bằng chứng hạn chế trên động vật |
| **Bromoform ($\text{CHBr}_3$)** | **B2** | Đủ bằng chứng u ruột trên động vật |
| **Monochloroacetic Acid ($\text{MCAA}$)** | **--** | Chưa đủ hồ sơ phân loại chính thức |
| **Dichloroacetic Acid ($\text{DCAA}$)** | **B2** | Đủ bằng chứng gây ung thư gan trên động vật |
| **Trichloroacetic Acid ($\text{TCAA}$)** | **C** | Bằng chứng hạn chế trên động vật thí nghiệm |
| **Dichloroacetonitrile ($\text{DCAN}$)** | **C** | Tiềm năng gây ung thư mức độ có thể |
| **Bromochloroacetonitrile ($\text{BCAN}$)** | **--** | Chưa phân loại chính thức |
| **Dibromoacetonitrile ($\text{DBAN}$)** | **C** | Độc tính di truyền và nghi ngờ gây ung thư |
| **Trichloroacetonitrile ($\text{TCAN}$)** | **--** | Chưa phân loại chính thức |
| **$1{,}1\text{-Dichloropropanone}$** | **--** | Chưa phân loại chính thức |
| **$1{,}1{,}1\text{-Trichloropropanone}$** | **--** | Chưa phân loại chính thức |
| **$2\text{-Chlorophenol}$** | **D** | Không đủ dữ liệu kết luận |
| **$2{,}4\text{-Dichlorophenol}$** | **D** | Không đủ dữ liệu kết luận |
| **$2{,}4{,}6\text{-Trichlorophenol}$** | **B2** | Gây bệnh bạch cầu và u lympho trên động vật |
| **Chloropicrin** | **--** | Chưa phân loại chính thức |
| **Chloral Hydrate** | **C** | Độc tính tế bào và nghi ngờ gây ung thư |
| **Cyanogen Chloride** | **--** | Chưa phân loại chính thức |
| **Formaldehyde ($\text{HCHO}$)** | **B1** | Bằng chứng dịch tễ học hạn chế ở người qua đường hô hấp/tiêu hóa |
| **Chlorate ($\text{ClO}_3^-$)** | **--** | Chưa phân loại chính thức |
| **Chlorite ($\text{ClO}_2^-$)** | **D** | Độc tính tan máu, không phân loại ung thư |
| **Bromate ($\text{BrO}_3^-$)** | **B2** | Đủ bằng chứng sinh u biểu mô thận và phúc mạc trên động vật |
| **Ammonia ($\text{NH}_3$)** | **D** | Không phân loại tác nhân ung thư |
| **Hypochlorous Acid ($\text{HOCl}$)** | **--** | Dạng clo tự do hoạt tính |
| **Hypochlorite ($\text{OCl}^-$)** | **--** | Dạng clo phân ly |
| **Monochloramine ($\text{NH}_2\text{Cl}$)** | **--** | Không đủ bằng chứng ung thư, kiểm soát theo liều dư |
| **Chlorine Dioxide ($\text{ClO}_2$)** | **D** | Không phân loại tác nhân ung thư ở người |

##### Biện pháp kiểm soát và giảm thiểu hình thành DBPs (DBP Control and Mitigation Strategies)

* Chiến lược loại bỏ tiền chất hữu cơ tự nhiên (NOM / Precursor Removal):
  * **Keo tụ tăng cường (Enhanced Coagulation)**:
    * Tối ưu hóa quá trình keo tụ bằng cách hạ $\text{pH}$ phản ứng xuống vùng axit yếu ($\text{pH } 5{,}5\text{--}6{,}5$) và tăng liều lượng phèn nhôm hoặc phèn sắt.
    * Tăng hiệu suất tách bỏ hàm lượng cacbon hữu cơ tổng số ($\text{TOC}$) và các hợp chất hữu cơ có độ hấp thụ tia cực tím cao ($UV_{254}$) trước khi tiếp xúc chất khử trùng.
    * Tiêu chuẩn USEPA yêu cầu loại bỏ từ $15\%$ đến $50\%\ \text{TOC}$ phụ thuộc vào độ kiềm và nồng độ $\text{TOC}$ đầu vào.
  * **Hấp phụ bằng than hoạt tính dạng hạt (Granular Activated Carbon - GAC)**:
    * Hấp phụ chuyên sâu các phân tử hữu cơ hòa tan phân tử lượng thấp và trung bình mà quá trình keo tụ không lắng được.
    * Bố trí cột lọc $\text{GAC}$ sau lắng hoặc lọc cát giúp giảm triệt để nồng độ tiền chất tạo $\text{THMs}$ và $\text{HAAs}$.
  * **Công nghệ màng lọc áp lực cao (Nanofiltration - NF)**:
    * Màng $\text{NF}$ có kích thước lỗ màng cho phép giữ lại các đại phân tử hữu cơ fulvic và humic với hiệu suất đạt trên $90\%$.
* Chiến lược thay đổi chất khử trùng và tối ưu hóa vị trí châm hóa chất (Disinfectant Modification):
  * **Sử dụng Chloramine ($\text{NH}_2\text{Cl}$) thay thế clo tự do cho khử trùng thứ cấp**:
    * Châm amoniac phối hợp với clo theo tỷ lệ khối lượng $\text{Cl}_2 : \text{N} = 4:1\text{--}5:1$ để tạo monochloramine ổn định.
    * Giảm thiểu từ $80\%$ đến $95\%$ lượng $\text{THMs}$ và $\text{HAAs}$ tích lũy trong mạng lưới đường ống phân phối.
    * Lưu ý: Cần kiểm soát nguy cơ hình thành nitrosamine ($\text{NDMA}$) và hiện tượng nitrat hóa sinh học trong mạng lưới.
  * **Khử trùng sơ bộ bằng tia cực tím (Ultraviolet - UV)**:
    * Bức xạ $\text{UV}$ (bước sóng $\lambda \approx 254\text{ nm}$) bất hoạt vi sinh vật và u nang *Cryptosporidium*/*Giardia* qua cơ chế vật lý mà không sinh ra các sản phẩm phụ halogen hóa.
    * Chỉ cần duy trì một liều lượng clo hoặc chloramine rất thấp ở khâu cuối để bảo vệ mạng lưới phân phối.
* Kỹ thuật chuyên biệt kiểm soát ion Bromate ($\text{BrO}_3^-$) trong khử trùng bằng Ozone:
  * **Điều chỉnh hạ $\text{pH}$ nước cấp trước khi ozone hóa**:
    * Duy trì $\text{pH} < 7{,}0$ làm dịch chuyển cân bằng $\text{HOBr} \rightleftharpoons \text{OBr}^- + \text{H}^+$ ($pK_a \approx 8{,}8$) về phía dạng $\text{HOBr}$.
    * Chỉ có ion $\text{OBr}^-$ mới bị ozone phân tử oxy hóa tiếp diễn thành $\text{BrO}_3^-$; do đó dạng $\text{HOBr}$ bền vững hơn và hạn chế tối đa việc tạo bromate.
  * **Bổ sung amoniac ($\text{NH}_3$) liều lượng nhỏ**:
    * Amoniac phản ứng nhanh với $\text{HOBr}/\text{OBr}^-$ tạo thành monobromamine ($\text{NH}_2\text{Br}$):
      $$\text{HOBr} + \text{NH}_3 \rightarrow \text{NH}_2\text{Br} + \text{H}_2\text{O}$$
    * Phản ứng khóa nguyên tử brom không cho ozone oxy hóa tiếp lên số oxy hóa $+5$ của ion bromate.
  * **Kiểm soát và phân tầng liều lượng ozone hòa tan**:
    * Tránh châm dư thừa nồng độ ozone; ứng dụng hệ thống châm dòng nhánh (slip stream injection) có kiểm soát nồng độ hòa tan theo thời gian tiếp xúc thực tế ($C \cdot t$).
* Kỹ thuật chuyên biệt kiểm soát ion Chlorite ($\text{ClO}_2^-$) và Chlorate ($\text{ClO}_3^-$) khi dùng Clo Dioxit:
  * **Giới hạn liều lượng châm clo dioxit**:
    * Do $50\%\text{--}70\%$ liều châm biến đổi thành chlorite, liều châm $\text{ClO}_2$ thông thường phải khống chế dưới mức $1{,}2\text{--}1{,}4\text{ mg/L}$ để đảm bảo nồng độ chlorite luôn nhỏ hơn quy chuẩn $1{,}0\text{ mg/L}$.
  * **Khử ion Chlorite bằng muối sắt(II) ($\text{Fe}^{2+}$) hoặc hợp chất lưu huỳnh khử**:
    * Sắt(II) sulfate ($\text{FeSO}_4$) khử trực tiếp chlorite về ion chloride vô hại trong môi trường nước:
      $$4\text{Fe}^{2+} + \text{ClO}_2^- + 10\text{H}_2\text{O} \rightarrow 4\text{Fe(OH)}_3\downarrow + \text{Cl}^- + 8\text{H}^+$$
    * Bông cặn $\text{Fe(OH)}_3$ sinh ra đồng thời đóng vai trò chất trợ keo tụ và được giữ lại trong bể lắng/lọc.
    * Sulfite ($\text{SO}_3^{2-}$) hoặc thiosulfate ($\text{S}_2\text{O}_3^{2-}$) cũng phản ứng khử nhanh chlorite trong điều kiện $\text{pH}$ kiểm soát.
  * **Bảo quản và vận hành ngăn ngừa tạo Chlorate**:
    * Che chắn đường ống và bể phản ứng tránh tiếp xúc trực tiếp với tia bức xạ mặt trời nhằm ngăn phản ứng quang hóa phân hủy $\text{ClO}_2$ thành $\text{ClO}_3^-$.
    * Giám sát nghiêm ngặt tỷ lệ nạp hóa chất điều chế tại chỗ ($\text{NaClO}_2 + \text{Cl}_2$ hoặc $\text{NaClO}_2 + \text{HCl}$) để đạt hiệu suất chuyển hóa $> 95\%$ không sinh clo tự do dư hoặc chlorate dư.
* Phương pháp loại bỏ DBP sau khi hình thành (Post-formation Removal):
  * **Thổi khí / Làm thoáng cưỡng bức (Air Stripping)**:
    * Thổi khí qua tháp đệm hoặc sục khí trong bể chứa nước sạch giúp trục xuất các hợp chất dễ bay hơi như chloroform ($\text{CHCl}_3$) và các $\text{THMs}$ mạch ngắn ra khỏi pha lỏng.
    * Phương pháp này không loại bỏ được các hợp chất không bay hơi như $\text{HAAs}$, $\text{BrO}_3^-$ hay $\text{ClO}_2^-$.
  * **Lọc sinh học than hoạt tính (Biological Activated Carbon - BAC / Biofiltration)**:
    * Quần thể vi sinh vật cư trú trên bề mặt hạt than phân hủy hiếu khí các hợp chất hữu cơ dễ tiêu hóa (AOC), aldehyde và các axit haloacetic ($\text{HAAs}$) trước khi nước đi vào mạng lưới phân phối.

#### Disinfection with Chlorine

##### Free Chlorine Chemistry and Hydrolysis Equilibrium

- Clo ($\text{chlorine}$) là hóa chất khử trùng phổ biến nhất trong xử lý nước cấp, và thuật ngữ clo hóa ($\text{chlorination}$) thường được dùng đồng nghĩa với khử trùng ($\text{disinfection}$).
- Ba dạng hóa chất clo thương dụng chính gồm:
  - Khí clo nguyên tố ($\text{Cl}_2\text{ gas}$).
  - Natri hypoclorit ($\text{NaOCl}$), thương phẩm dạng dung dịch tẩy trắng ($\text{bleach}$).
  - Canxi hypoclorit ($\text{Ca(OCl)}_2$), thương phẩm dạng bột vôi clo hóa ($\text{chlorinated lime, } \text{CaOCl}_2$).
- Khí clo châm vào nước xảy ra phản ứng thủy phân tạo axit hypoclorơ ($\text{HOCl}$) và axit clohydric ($\text{HCl}$):
  $$\text{Cl}_2\text{ (khí)} + \text{H}_2\text{O} \rightleftharpoons \text{HOCl} + \text{H}^+ + \text{Cl}^-$$
  - Phản ứng thủy phân phụ thuộc vào $\text{pH}$ và diễn ra gần như tức thời trong vài mili-giây ($\text{milliseconds}$).
  - Trong dung dịch loãng ở $\text{pH} > 1.0$, cân bằng chuyển dịch hoàn toàn sang phải, dạng phân tử $\text{Cl}_2$ hòa tan tồn tại không đáng kể.
- Axit hypoclorơ ($\text{HOCl}$) là một axit yếu, phân ly thuận nghịch theo $\text{pH}$ dung dịch:
  $$\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^-$$
  - Ở $\text{pH} < 6.0$, $\text{HOCl}$ phân ly rất kém; clo tồn tại chủ yếu ở dạng phân tử $\text{HOCl}$ trong dải $\text{pH}$ từ $4.0$ đến $6.0$.
  - Ở dải $\text{pH}$ từ $6.0$ đến $8.5$, tỷ lệ chuyển dịch từ $\text{HOCl}$ sang ion hypoclorit ($\text{OCl}^-$) diễn ra rất đột ngột.
  - Ở nhiệt độ $20^\circ\text{C}$ và $\text{pH} > 7.5$, ion $\text{OCl}^-$ chiếm ưu thế ưu việt trong nước.
  - Ở $\text{pH} > 9.0$, clo tồn tại gần như hoàn toàn dưới dạng ion $\text{OCl}^-$.
- Định nghĩa clo tự do hữu dụng ($\text{free available chlorine}$ hoặc $\text{free chlorine}$):
  - Clo tự do là tổng nồng độ của axit hypoclorơ ($\text{HOCl}$) và ion hypoclorit ($\text{OCl}^-$) hiện diện trong nước.
  - Axit $\text{HOCl}$ có hoạt tính diệt khuẩn mạnh hơn ion $\text{OCl}^-$ từ $80$ đến $100$ lần do không mang điện tích, dễ dàng khuếch tán qua màng tế bào vi sinh vật.
- Sự phân ly của các muối hypoclorit trong nước tạo trực tiếp ion hypoclorit ($\text{OCl}^-$):
  - $\text{NaOCl} \rightarrow \text{Na}^+ + \text{OCl}^-$
  - $\text{Ca(OCl)}_2 \rightarrow \text{Ca}^{2+} + 2\text{OCl}^-$
  - Các ion $\text{OCl}^-$ thiết lập cân bằng proton hóa với ion $\text{H}^+$ ($\text{OCl}^- + \text{H}^+ \rightleftharpoons \text{HOCl}$).
  - Dạng hóa học hoạt tính ($\text{HOCl}$ và $\text{OCl}^-$) cùng trạng thái cân bằng phân ly được thiết lập đồng nhất, không phụ thuộc vào nguồn clo ban đầu là khí $\text{Cl}_2$ hay muối hypoclorit.
- Dạng hóa chất clo sử dụng làm thay đổi $\text{pH}$ và độ kiềm của nguồn nước:
  - Khí $\text{Cl}_2$ sinh axit $\text{HCl}$ làm giảm $\text{pH}$; mỗi $1\text{ mg/L } \text{Cl}_2$ châm vào làm tiêu tốn đến $1.4\text{ mg/L}$ độ kiềm tính theo $\text{CaCO}_3$.
  - Các muối hypoclorit chứa kiềm dư để ổn định hóa chất thương phẩm, có xu hướng làm tăng nhẹ $\text{pH}$ của nước.
  - Dải $\text{pH}$ thiết kế công nghệ tối ưu cho hiệu quả khử trùng nằm trong khoảng $6.5\text{--}7.5$.
- Độ bền hóa học và phản ứng quang phân của clo tự do:
  - Clo tự do tương đối bền vững trong nước tinh khiết không chứa chất khử.
  - Clo tự do phản ứng chậm với chất hữu cơ tự nhiên ($\text{NOM}$), nhưng phân hủy nhanh dưới tác động của ánh sáng mặt trời ($\text{sunlight}$).
  - Phản ứng quang phân tác động trực tiếp lên ion $\text{OCl}^-$, tạo thành oxy ($\text{O}_2$), ion clorit ($\text{ClO}_2^-$), và ion clorua ($\text{Cl}^-$).

##### Breakpoint Chlorination Principles and Well Water Curve

- Cân bằng khối lượng của quá trình clo hóa biểu diễn qua mối quan hệ:
  $$\text{Liều lượng clo châm} = \text{Nhu cầu clo} + \text{Nồng độ clo dư}$$
  $$\text{Chlorine dose} = \text{Chlorine demand} + \text{Chlorine residual}$$
  - Liều lượng clo châm ($\text{Chlorine dose}$): tổng lượng clo bổ sung vào nước để đạt nồng độ clo dư mục tiêu.
  - Nhu cầu clo ($\text{Chlorine demand}$): lượng clo tiêu thụ trong phản ứng oxy hóa với toàn bộ chất khử vô cơ ($\text{Fe}^{2+}, \text{Mn}^{2+}, \text{H}_2\text{S}, \text{NO}_2^-$) và hợp chất hữu cơ trong nước.
  - Clo hóa điểm uốn ($\text{Breakpoint chlorination}$): quá trình tiếp tục châm clo cho đến khi toàn bộ nhu cầu clo của nước được đáp ứng hoàn toàn.
  - Điểm uốn ($\text{Breakpoint}$): trạng thái chuyển tiếp mà tại đó nhu cầu clo đã thỏa mãn triệt để; mọi lượng clo châm thêm sau điểm này sẽ tồn tại ở dạng clo dư tự do ($\text{free chlorine residual}$).
- Đường cong clo hóa điểm uốn của nước ngầm không chứa amoniac hoặc chất hữu cơ:
  - Quá trình clo hóa không trải qua giai đoạn hình thành cloramin trung gian, diễn ra trực tiếp qua 2 pha:
    - Giai đoạn 1 (từ điểm bắt đầu đến vạch 2): clo châm vào phản ứng và bị tiêu hủy bởi các chất khử vô cơ ($\text{chlorine destroyed by reducing agents}$), nồng độ clo dư bằng $0$.
    - Giai đoạn 2 (sau vạch 2): đạt ngay điểm uốn ($\text{Breakpoint}$); clo dư tự do hình thành và tăng tuyến tính trực tiếp theo lượng clo châm thêm ($\text{free available residual formed}$).
  - **Hình 5.** Đường cong clo hóa điểm uốn của nước ngầm (không chứa amoniac hoặc chất hữu cơ)
    - <img src="ch07_disinfection/assets/fig_05_p10.png" alt="Hình 5" />
    - **Hình này chứng minh điều gì**
      - Nước ngầm không chứa amoniac và chất hữu cơ đạt điểm uốn (breakpoint) ngay khi thỏa mãn nhu cầu clo của các chất khử vô cơ, không hình thành clo liên kết trung gian.
    - **Từ đâu mà thấy được**
      - Trục Ox: lượng clo châm ($\text{CHLORINE ADDED}$); trục Oy: clo dư ($\text{CHLORINE RESIDUAL}$).
      - Giai đoạn 1 (từ vạch 1 đến 2): clo bị chất khử phá hủy hoàn toàn ($\text{CHLORINE DESTROYED BY REDUCING AGENTS}$), clo dư nằm ở mức 0.
      - Vạch 2 đánh dấu điểm uốn ($\text{BREAKPOINT}$); ngay sau vạch 2, clo dư tự do hình thành và tăng tuyến tính trực tiếp ($\text{FREE AVAILABLE RESIDUAL FORMED}$).

##### Typical Chlorine Dosages and Multi-Purpose Applications

- Liều lượng clo áp dụng thực tế tại các nhà máy xử lý nước cấp phân theo loại hóa chất clo:
  - Canxi hypoclorit ($\text{Calcium hypochlorite}$): dải liều châm từ $0.5$ đến $5\text{ mg/L}$.
  - Natri hypoclorit ($\text{Sodium hypochlorite}$): dải liều châm từ $0.2$ đến $2\text{ mg/L}$.
  - Khí clo ($\text{Chlorine gas}$): dải liều châm từ $1$ đến $16\text{ mg/L}$, sở hữu dải dao động rộng nhất và mức châm trần cao nhất.
  - Nguồn dữ liệu do SAIC tổng hợp năm 1998 từ các kế hoạch lấy mẫu ban đầu ($\text{Initial Sampling Plans}$) thuộc Quy tắc Thu thập Thông tin ICR của US EPA.
- Ứng dụng đa năng của clo ngoài mục đích khử trùng chính:
  - Oxy hóa sắt ($\text{iron}$): liều châm điển hình $0.62\text{ mg/mg Fe}$, $\text{pH}$ tối ưu $7.0$, thời gian phản ứng dưới $1\text{ giờ}$ ($\text{less than } 1\text{ hour}$), hiệu quả tốt.
  - Oxy hóa mangan ($\text{manganese}$): liều châm điển hình $0.77\text{ mg/mg Mn}$, động học phản ứng chậm ($\text{slow kinetics}$); ở $\text{pH } 7\text{--}8$ phản ứng cần từ $1$ đến $3\text{ giờ}$, trong khi kiềm hóa lên $\text{pH } 9.5$ thời gian phản ứng rút ngắn xuống chỉ còn vài phút ($\text{minutes}$).
  - Kiểm soát sự phát triển sinh học ($\text{biological growth}$): liều châm từ $1$ đến $2\text{ mg/L}$, $\text{pH}$ tối ưu từ $6$ đến $8$, hiệu quả tốt, có rủi ro tạo sản phẩm phụ khử trùng ($\text{DBP formation}$).
  - Xử lý mùi và vị ($\text{taste/odor}$): liều châm biến thiên, $\text{pH}$ tối ưu từ $6$ đến $8$, hiệu quả phụ thuộc vào cấu trúc từng hợp chất gây mùi cụ thể.
  - Khử màu nước ($\text{color removal}$): liều châm biến thiên, $\text{pH}$ tối ưu từ $4.0$ đến $6.8$, phản ứng diễn ra trong vài phút, hiệu quả tốt, có rủi ro tạo $\text{DBP}$.
  - Kiểm soát vẹm vằn ($\text{zebra mussels}$): liều châm sốc từ $2$ đến $5\text{ mg/L}$ ($\text{shock level}$), nồng độ duy trì từ $0.2$ đến $0.5\text{ mg/L}$ tính theo clo dư hữu dụng ($\text{residual, not dose}$), hiệu quả tốt, có nguy cơ tạo $\text{DBP}$.
  - Kiểm soát hến châu Á ($\text{Asiatic clams}$): châm liên tục với nồng độ clo dư duy trì từ $0.3$ đến $0.5\text{ mg/L}$ ($\text{residual, not dose}$), hiệu quả tốt, có nguy cơ tạo $\text{DBP}$.
  - Số liệu tổng hợp từ các nghiên cứu kinh điển của White (1992), Connell (1996), và Culp/Wesner/Culp (1986).
##### Combined Chlorine and Chloramine Reactions

- Phản ứng của clo với amoniac ($\text{NH}_3$) có vai trò trọng yếu trong kỹ thuật clo hóa nước:
  - Khi châm clo vào nước chứa amoniac tự nhiên hoặc nhân tạo, amoniac phản ứng với $\text{HOCl}$ sinh ra các dạng chloramine nối tiếp:
    $$\text{NH}_3 + \text{HOCl} \rightarrow \text{NH}_2\text{Cl} + \text{H}_2\text{O}\quad (\text{monochloramine})$$
    $$\text{NH}_2\text{Cl} + \text{HOCl} \rightarrow \text{NHCl}_2 + \text{H}_2\text{O}\quad (\text{dichloramine})$$
    $$\text{NHCl}_2 + \text{HOCl} \rightarrow \text{NCl}_3 + \text{H}_2\text{O}\quad (\text{trichloramine})$$
  - Phản ứng chuyển dịch cân bằng ion amoni trong nước:
    $$\text{NH}_4^+ \rightleftharpoons \text{NH}_3 + \text{H}^+$$
- Các yếu tố chi phối sự phân bố dạng chloramine ($\text{chloramine speciation}$):
  - Sự phân bố sản phẩm phản ứng do tốc độ tạo thành $\text{NH}_2\text{Cl}$ và $\text{NHCl}_2$ quyết định.
  - Các yếu tố ảnh hưởng chính gồm giá trị $\text{pH}$, nhiệt độ nước, thời gian phản ứng và tỷ lệ khối lượng $\text{Cl}_2:\text{NH}_3$ ban đầu.
  - Tỷ lệ $\text{Cl}_2:\text{NH}_3$ cao, nhiệt độ thấp và $\text{pH}$ thấp ưu tiên sự hình thành dichloramine ($\text{NHCl}_2$).
  - Môi trường $\text{pH}$ kiềm cao ưu tiên sự chiếm ưu thế của monochloramine ($\text{NH}_2\text{Cl}$).
- Phản ứng của clo với các hợp chất hữu cơ chứa nitơ:
  - Clo phản ứng với protein và axit amin sinh ra các phức chloramine hữu cơ ($\text{organic chloramine complexes}$).
- Định nghĩa clo liên kết ($\text{combined available chlorine}$ hoặc $\text{combined chlorine}$):
  - Clo tồn tại trong nước ở dạng liên kết hóa học với amoniac hoặc hợp chất nitơ hữu cơ được gọi là clo liên kết.
- Cân bằng clo tổng số và nồng độ clo dư:
  - Clo tổng số ($\text{total chlorine}$) là tổng nồng độ của clo tự do và clo liên kết:
    $$\text{Total chlorine} = \text{Free chlorine} + \text{Combined chlorine}$$
  - Quan hệ nồng độ clo dư trong nước sau xử lý:
    $$\text{Chlorine residual} = \text{Free chlorine residual} + \text{Combined chlorine residual}$$
  - Clo liên kết có hoạt tính sát trùng yếu hơn clo tự do từ $25$ đến $100$ lần, nhưng có ưu điểm độ bền cao và tồn lưu kéo dài trên mạng lưới phân phối cấp nước.

### 7.3 Disinfection Practice and Technology

* Các tiêu chí thủy lực chuyên sâu và tiêu chuẩn thiết kế bể tiếp xúc khử trùng (Disinfection Contact Basin Hydraulics):
  * Tỷ lệ chiều dài trên chiều rộng dòng chảy (L / W): Để tiệm cận mô hình dòng chảy nút lý tưởng (plug-flow reactor), tỷ lệ L/W phải đạt tối thiểu 40:1, khuyến nghị 50:1 đến 70:1 bằng cách bố trí vách ngăn dẫn dòng uốn lượn (serpentine baffles).
  * Kiểm soát chỉ số phân tán Morrill (Morrill Dispersion Index - MDI = t90 / t10): Thiết kế thủy lực tối ưu yêu cầu MDI < 1.5 - 2.0; chỉ số phân tán d = D / (u L) <= 0.02 - 0.05 nhằm triệt tiêu tối đa hiện tượng ngắn dòng và các vùng nước chết.
  * Tỷ số thời gian tiếp xúc thực tế (t10 / t0): Bể có vách ngăn hoàn hảo đạt t10/t0 >= 0.70; bể có vách ngăn trung bình đạt t10/t0 = 0.40 - 0.50; bể không có vách ngăn chỉ đạt t10/t0 = 0.10 - 0.20.
  * Thiết kế vách ngăn uốn cong và cánh đổi hướng (turning vanes): Bố trí các vách bo tròn góc (fillets) tại các điểm ngoặt 180 độ để ngăn ngừa sự hình thành dòng xoáy cuộn tách lớp ở góc ngoặt.
  * Vận tốc dòng chảy trong hành lang tiếp xúc (v): Duy trì vận tốc dòng chảy tối thiểu 0.1 - 0.15 m/s tại lưu lượng đỉnh để ngăn ngừa sự lắng tụ chất rắn lơ lửng trên đáy bể tiếp xúc.
  * Dự phòng công suất và bảo dưỡng định kỳ: Trạm tiếp xúc khử trùng bắt buộc phải thiết kế tối thiểu 2 đơn nguyên làm việc song song để cho phép cô lập một đơn nguyên vệ sinh xả cặn mà không gián đoạn quá trình cấp nước sạch đô thị.

#### 7.3.1 Disinfection Reactor Categories and Plug-Flow Hydraulic Criteria

* Phân loại công trình phản ứng khử trùng trong cấp nước (disinfection reactors):
  * Bể phản ứng khử trùng (còn gọi là buồng khử trùng hoặc bể tiếp xúc - disinfection chambers / contact chambers) được phân loại thành ba nhóm cấu trúc chính:
    * Đường ống dẫn nước dài (pipelines).
    * Bể uốn lượn có vách ngăn theo chiều dọc (longitudinal-serpentine basins).
    * Bể uốn lượn có vách ngăn chéo vuông góc dòng chảy (cross-baffled serpentine basins).
* Tiêu chuẩn thủy động lực học lý tưởng cho bể khử trùng (ideal plug-flow reactor):
  * Bể phản ứng tối ưu cho clo ($\text{Cl}_2$), clo liên kết (chloramines), và clo dioxit ($\text{ClO}_2$) là bể đạt mô hình dòng chảy piston lý tưởng (ideal plug-flow).
  * Dòng chảy piston lý tưởng không xuất hiện hiện tượng khuếch tán dọc (no longitudinal dispersion).
  * Trong điều kiện lý tưởng, thời gian tiếp xúc thực tế của mọi phân tử nước bằng chính xác thời gian lưu thủy lực lý thuyết ($t = t_0 = V/Q$).
* Kỹ thuật hòa trộn và châm hóa chất khử trùng qua dòng nhánh (slip stream injection):
  * Các loại khí khử trùng gồm $\text{Cl}_2$, $\text{NH}_3$ và $\text{ClO}_2$ được định lượng đưa vào một dòng nước nhánh (slip stream).
  * Dòng nhánh (slip stream) là một phần lưu lượng nước đã qua xử lý (keo tụ, lắng, lọc hoặc các bậc xử lý khác).
  * Dung dịch hóa chất từ dòng nhánh sau đó được phun cưỡng bức vào dòng chảy chính trước khi nước đi vào bể tiếp xúc.
  * Việc định lượng hóa chất qua dòng nhánh đảm bảo hòa trộn đồng đều và kiểm soát an toàn áp suất hóa chất.
* Tiêu chuẩn thiết kế bể phản ứng dạng đường ống dẫn dài (pipeline reactor criteria):
  * Đường ống dẫn dài không có khúc quanh co gấp khúc hoặc điểm thắt thu hẹp (without bends and restrictions) là công trình phản ứng lý tưởng nhất.
  * Thông số kỹ thuật đường ống khử trùng tiếp cận trạng thái dòng chảy piston lý tưởng:
    * Thời gian tiếp xúc yêu cầu: $t = 30\text{ phút}$ ($30\text{ min}$).
    * Lưu lượng dòng chảy thiết kế: $Q > 0.044\text{ m}^3\text{/s}$.
    * Vận tốc dòng chảy trong ống: $v > 0.6\text{ m/s}$.
    * Chiều dài đường ống dẫn tương ứng: $L \approx 1\text{ km}$ ($1\,000\text{ m}$).
* Tiêu chuẩn thiết kế bể uốn lượn vách ngăn dọc (longitudinal-serpentine basin criteria):
  * Khi không thể xây dựng đường ống dẫn đủ dài, bể uốn lượn vách ngăn dọc là giải pháp kinh tế và hiệu quả nhất để tiếp cận dòng chảy piston lý tưởng.
  * Tỷ số chiều dài đường dòng trên chiều rộng kênh dẫn (length-to-width ratio $L:W$) tối thiểu phải đạt ít nhất $40:1$ ($L:W \ge 40:1$).
  * Tỷ số $L:W$ được tính bằng tổng chiều dài đường đi của dòng nước ($L$) chia cho bề rộng của một ngăn dẫn ($W$).
* Hiệu chỉnh thủy lực bể phi lý tưởng và khái niệm thời gian lưu $t_{10}$:
  * Trong thực tế, không có bể phản ứng nào đạt trạng thái dòng chảy piston tuyệt đối do hiện tượng đoản mạch (short-circuiting) và vùng chết (dead zones).
  * Thời gian tiếp xúc hữu hiệu của nước trong bể luôn nhỏ hơn thời gian lưu lý thuyết ($t_{10} < t_0$).
  * Để tính toán giá trị tích số $C \cdot t$ cho bể phi lý tưởng, quy chuẩn thiết kế sử dụng thời gian tiếp xúc $t_{10}$ thay cho $t_0$.
  * Đại lượng $t_{10}$ là khoảng thời gian mà $90\%$ lưu lượng nước được lưu lại trong buồng khử trùng ($10\%$ nước đi ra sớm nhất).
  * Tỷ số $t_{10}/t_0$ (baffling factor - hệ số vách ngăn) đặc trưng cho cấp độ thủy lực của bể phản ứng.
* Kiểm soát liều lượng clo hóa và phản ứng điểm đột biến trong bể tiếp xúc:
  * Liều lượng clo châm vào dòng nhánh phải bù đắp đủ nhu cầu clo và duy trì nồng độ clo tự do tồn dư bảo vệ mạng lưới:
  - **Hình 8.** Bảng liều lượng clo điển hình cho các ứng dụng xử lý nước
    - <img src="ch07_disinfection/assets/fig_08_p12.png" alt="Hình 8" />
    - **Hình này chứng minh điều gì**
      - Cung cấp liều clo và pH tối ưu kiểm soát sắt, mangan, vi sinh, và DBP.
    - **Từ đâu mà thấy được**
      - Dòng sắt $0.62\text{ mg/mg}$, mangan $0.77\text{ mg/mg}$, vi sinh $1\text{--}2\text{ mg/L}$, ghi chú nguy cơ tạo DBP.
  * Quá trình clo hóa nước chứa amoniac hình thành các dạng chloramine và chuyển sang clo tự do sau điểm đột biến:
  - **Hình 9.** Đường cong clo hóa tới điểm đột biến cho dòng châm
    - <img src="ch07_disinfection/assets/fig_09_p13.png" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Thể hiện 4 vùng phản ứng clo hóa và tỷ lệ $\text{Cl}_2:\text{NH}_3\text{-N} = 10:1$ đạt clo tự do dư.
    - **Từ đâu mà thấy được**
      - Đồ thị chia 4 pha: khử tạp chất $\rightarrow$ monochloramine ($5:1$) $\rightarrow$ phá hủy chloramine $\rightarrow$ breakpoint ($10:1$).
  * Tỷ lệ $\text{Cl}_2:\text{N}$ và pH điều khiển sự phân bố các dạng chloramine tồn dư trong buồng phản ứng:
* Tiêu chí lựa chọn công nghệ khử trùng và đánh giá vận hành công trình:
  * Việc lựa chọn tác nhân khử trùng cho bể tiếp xúc dựa trên độ tin cậy thiết bị, mức độ kiểm soát quá trình và yêu cầu bảo dưỡng O&M:
  - **Hình 17.** Ma trận đánh giá độ tin cậy và vận hành thiết bị
    - <img src="ch07_disinfection/assets/fig_17_p22.png" alt="Hình 17" />
    - **Hình này chứng minh điều gì**
      - So sánh độ tin cậy thiết bị, kiểm soát quá trình và yêu cầu O&M giữa 6 hóa chất khử trùng.
    - **Từ đâu mà thấy được**
      - Bảng tiêu chí: $\text{NaOCl}$ có độ tin cậy rất tốt; $\text{O}_3$ và $\text{ClO}_2$ có chi phí O&M cao; $\text{Cl}_2$ kiểm soát hoàn thiện.
  * Phân tích tương quan giữa rủi ro an toàn và chi phí O&M của từng giải pháp khử trùng:
  - **Hình 18.** So sánh tiêu chuẩn lựa chọn công nghệ khử trùng thực tế
    - <img src="ch07_disinfection/assets/fig_18_p22.png" alt="Hình 18" />
    - **Hình này chứng minh điều gì**
      - Xác định yêu cầu vận hành và bảo trì (O&M) cùng mức độ kiểm soát quá trình cho từng công nghệ.
    - **Từ đâu mà thấy được**
      - Bảng hàng ngang: Thiết bị $\text{Cl}_2$ và chloramine có O&M thấp; $\text{O}_3$ và $\text{ClO}_2$ có O&M cao.
* Động học bất hoạt mầm bệnh và giá trị $C \cdot t_{10}$ quy chuẩn:
  * Buồng tiếp xúc phải bảo đảm tích số $C \cdot t_{10}$ đạt mức độ bất hoạt virus đường ruột theo quy định:
  - **Hình 19.** Bảng giá trị CT bất hoạt virus đường ruột ở các mức log
    - <img src="ch07_disinfection/assets/fig_19_p25.png" alt="Hình 19" />
    - **Hình này chứng minh điều gì**
      - Cung cấp tích số $C \cdot t$ quy chuẩn để thiết kế thời gian lưu $t_{10}$ diệt virus từ 0.5-log đến 3-log.
    - **Từ đâu mà thấy được**
      - Bảng số liệu: Tại 2-log virus, clo cần $69\text{ mg}\cdot\text{min/L}$, chloramine cần $1\,230$, ozone chỉ cần $0.95$.
  * Tích số $C \cdot t_{10}$ đối với virus phụ thuộc vào loại chất oxy hóa và nhiệt độ nguồn nước:
  - **Hình 20.** Bảng quy chuẩn tích số CT khử trùng virus theo USEPA
    - <img src="ch07_disinfection/assets/fig_20_p25.png" alt="Hình 20" />
    - **Hình này chứng minh điều gì**
      - So sánh hiệu quả diệt virus giữa các chất khử trùng ở $10^\circ\text{C}$ và pH $7$.
    - **Từ đâu mà thấy được**
      - Cột 3-log virus: Ozone ($1.43$) nhanh hơn clo ($104$) và chloramine ($1\,850\text{ mg}\cdot\text{min/L}$).
  * Bể tiếp xúc phải được định cỡ đủ thời gian $t_{10}$ để bất hoạt u nang ký sinh trùng *Giardia lamblia*:
  - **Hình 21.** Tích số CT bất hoạt u nang Giardia lamblia trong bể
    - <img src="ch07_disinfection/assets/fig_21_p26.png" alt="Hình 21" />
    - **Hình này chứng minh điều gì**
      - Xác định thời gian tiếp xúc $t_{10}$ cần thiết để bảo vệ nguồn nước khỏi ký sinh trùng Giardia.
    - **Từ đâu mà thấy được**
      - Bảng số liệu: Ozone có tích số CT thấp nhất, chứng minh hiệu quả diệt u nang hiệu quả hơn so với clo.
  * Yêu cầu $C \cdot t_{10}$ cho bất hoạt *Giardia* khắt khe hơn đáng kể so với virus đường ruột:
  - **Hình 22.** Bảng so sánh tích số CT bất hoạt u nang Giardia
    - <img src="ch07_disinfection/assets/fig_22_p26.png" alt="Hình 22" />
    - **Hình này chứng minh điều gì**
      - Thiết lập giá trị thiết kế $C \cdot t_{10}$ cho các cấp độ loại bỏ 0.5-log đến 3-log Giardia.
    - **Từ đâu mà thấy được**
      - Các hàng dữ liệu: Tỷ lệ liều và thời gian tiếp xúc tăng tuyến tính theo cấp độ khử trùng log.
* Kiểm soát sản phẩm phụ khử trùng (DBP) và nguy cơ gây ung thư trong bể tiếp xúc:
  * Thời gian lưu và liều lượng hóa chất trong buồng khử trùng quyết định mức độ hình thành các hợp chất DBP độc hại:
  - **Hình 23.** Danh mục sản phẩm phụ khử trùng và phân loại gây ung thư
    - <img src="ch07_disinfection/assets/fig_23_p29.png" alt="Hình 23" />
    - **Hình này chứng minh điều gì**
      - Liệt kê các hợp chất DBP phát sinh trong buồng khử trùng cùng mức độ nguy cơ sức khỏe USEPA.
    - **Từ đâu mà thấy được**
      - Cột Cancer Classification: Chloroform (B2), Dichloroacetic acid (B2), Bromate (B2) thuộc nhóm có thể gây ung thư.
  * Phân loại độc tính và khả năng gây ung thư của các hợp chất haloacetic acids, trihalomethanes và bromate:
  - **Hình 24.** Bảng phân loại chất gây ung thư cho các dẫn xuất DBP
    - <img src="ch07_disinfection/assets/fig_24_p29.png" alt="Hình 24" />
    - **Hình này chứng minh điều gì**
      - Nhận diện các DBP clo hóa, brom hóa và sản phẩm phụ của ozone cần kiểm soát trong nước cấp.
    - **Từ đâu mà thấy được**
      - Bảng chất ô nhiễm: Formaldehyde (B1), Trichloroacetic acid (C), Chlorite (D), Bromate (B2).
  * Đánh giá bằng chứng y tế và dịch tễ học liên quan đến các sản phẩm phụ khử trùng:
  - **Hình 25.** Tình trạng dữ liệu y tế và độc học của chất khử trùng
    - <img src="ch07_disinfection/assets/fig_25_p30.png" alt="Hình 25" />
    - **Hình này chứng minh điều gì**
      - Đánh giá mức độ bằng chứng dịch tễ học và nghiên cứu động vật đối với các chất khử trùng tồn dư.
    - **Từ đâu mà thấy được**
      - Danh mục đánh giá: Nhóm THMs và HAAs được xếp loại B2 do có đủ bằng chứng trên động vật thí nghiệm.
  * Giám sát và giới hạn nồng độ các hợp chất dẫn xuất clo hữu cơ trong nước sạch:
  - **Hình 26.** Phân loại nguy cơ gây ung thư của các hợp chất khử trùng
    - <img src="ch07_disinfection/assets/fig_26_p30.png" alt="Hình 26" />
    - **Hình này chứng minh điều gì**
      - Cung cấp cơ sở quản lý liều lượng hóa chất châm nhằm ngăn chặn phát sinh các chất nhóm B1 và B2.
    - **Từ đâu mà thấy được**
      - Phân cấp chất: Bromoform (B2), Dibromochloromethane (C), Chloral hydrate (C).
  * Quy chuẩn phân nhóm chất gây ung thư của cơ quan bảo vệ môi trường Hoa Kỳ (USEPA 1996):
  - **Hình 27.** Sơ đồ phân loại tiềm năng gây ung thư theo USEPA 1996
    - <img src="ch07_disinfection/assets/fig_27_p31.png" alt="Hình 27" />
    - **Hình này chứng minh điều gì**
      - Xác định định nghĩa chuẩn 5 nhóm ung thư từ Group A (gây ung thư người) đến Group E (không bằng chứng).
    - **Từ đâu mà thấy được**
      - Khung tiêu chuẩn: Group A (Human Carcinogen), Group B (Probable), Group C (Possible), Group D (Not classifiable), Group E (No evidence).

---

#### 7.3.2 Hydraulic Baffling Classifications and Baffling Factors ($t_{10}/t_0$)

* Khái niệm và ý nghĩa của hệ số vách ngăn ($t_{10}/t_0$):
  * Hệ số vách ngăn (baffling factor) là tỷ số giữa thời gian lưu thực tế của $90\%$ dòng nước ($t_{10}$) và thời gian lưu thủy lực lý thuyết ($t_0 = V/Q$).
  * Hệ số này phản ánh mức độ hoàn thiện thủy lực, mức độ ngắn mạch và thể tích vùng chết trong bể tiếp xúc.
  * Giá trị $t_{10}/t_0$ càng cao thì buồng tiếp xúc càng tiệm cận mô hình dòng chảy piston lý tưởng, giúp giảm dung tích công trình yêu cầu.

##### 7.3.2.1 Poor Baffling ($t_{10}/t_0 = 0.3$)

* Đặc tính thủy lực của cấp độ vách ngăn kém (poor baffling):
  * Tỷ số thời gian lưu hữu hiệu: $t_{10}/t_0 = 0.3$.
  * Cấu trúc công trình: Bể chữ nhật hoặc bể tròn thông thường không có vách ngăn dẫn dòng bên trong.
  * Hiện tượng thủy lực bất lợi:
    * Xuất hiện đoản mạch nghiêm trọng giữa cửa vào và cửa ra.
    * Tạo thành các vùng chết (potential dead zones) rộng lớn tại các góc bể, vùng nước sâu và bề mặt tĩnh.
    * Nước lưu lại không đồng đều, làm giảm hiệu quả khử trùng và tăng nguy cơ vi sinh vật thoát qua bể.
* Minh họa cấu tạo và vùng chết trong bể vách ngăn kém:
  - **Hình 30.** Sơ đồ cấu tạo bể tiếp xúc cấp độ vách ngăn kém
    - <img src="ch07_disinfection/assets/fig_30_p34.png" alt="Hình 30" />
    - **Hình này chứng minh điều gì**
      - Minh họa hiện tượng đoản mạch và các vùng chết lớn trong bể chữ nhật và bể tròn không vách ngăn ($t_{10}/t_0 = 0.3$).
    - **Từ đâu mà thấy được**
      - Mặt bằng (Plan) và mặt cắt (Section): Các ký hiệu Potential dead zone chiếm tỷ lệ lớn ở góc và đáy bể.

##### 7.3.2.2 Average Baffling ($t_{10}/t_0 = 0.5$)

* Đặc tính thủy lực của cấp độ vách ngăn trung bình (average baffling):
  * Tỷ số thời gian lưu hữu hiệu: $t_{10}/t_0 = 0.5$.
  * Cấu trúc công trình:
    * Bể chữ nhật được trang bị tường đục lỗ phân phối dòng chảy tại đầu vào (inlet perforated baffle wall).
    * Bố trí vách ngăn đơn tràn-chui (over-under baffle wall) chia bể thành các ngăn nối tiếp.
    * Bể tròn được trang bị giếng tiêu năng khuếch tán trung tâm (center well baffle diffuser).
  * Cải thiện thủy lực:
    * Giảm thiểu đáng kể hiện tượng đoản mạch trực tiếp.
    * Phân bố vận tốc qua mặt cắt ướt đồng đều hơn.
    * Thể tích vùng chết giảm rõ rệt so với bể không vách ngăn.
* Minh họa cấu tạo bể tiếp xúc cấp độ vách ngăn trung bình:
  - **Hình 31.** Sơ đồ cấu tạo bể tiếp xúc cấp độ vách ngăn trung bình
    - <img src="ch07_disinfection/assets/fig_31_p35.png" alt="Hình 31" />
    - **Hình này chứng minh điều gì**
      - Cho thấy vách ngăn đục lỗ đầu vào và vách tràn-chui giúp giảm vùng chết, nâng tỷ số $t_{10}/t_0$ lên $0.5$.
      - **Từ đâu mà thấy được**
        - Mặt cắt bể chữ nhật: Vách đục lỗ phân phối đều dòng chảy và vách chìm hướng dòng; bể tròn có giếng tiêu năng trung tâm.

##### 7.3.2.3 Superior Baffling ($t_{10}/t_0 = 0.7$)

* Đặc tính thủy lực của cấp độ vách ngăn hiệu quả hơn (superior baffling):
  * Tỷ số thời gian lưu hữu hiệu: $t_{10}/t_0 = 0.7$.
  * Cấu trúc công trình:
    * Bể chữ nhật có hệ vách ngăn uốn lượn liên hoàn (serpentine baffle walls) tạo hành lang dòng chảy ziczac kéo dài.
    * Bố trí tường đục lỗ tiêu năng và điều hướng dòng chảy tại các góc quay uốn lượn.
    * Đạt tỷ số chiều dài trên chiều rộng dòng chảy vượt mức $L:W \ge 40:1$.
    * Bể tròn có vách ngăn hình vành khuyên đồng tâm kết hợp tường đục lỗ phân phối xuyên tâm.
  * Ưu điểm vận hành:
    * Triệt tiêu hầu như hoàn toàn các vùng chết trong công trình.
    * Dòng chảy đạt độ ổn định thủy lực cao nhất, tiệm cận hoàn hảo dòng chảy piston lý tưởng.
    * Tối ưu hóa dung tích xây dựng và bảo đảm tuyệt đối giá trị tích số $C \cdot t_{10}$ khử trùng.
* Minh họa cấu tạo bể tiếp xúc cấp độ vách ngăn hiệu quả hơn:
  - **Hình 34.** Sơ đồ cấu tạo bể tiếp xúc cấp độ vách ngăn hiệu quả hơn
    - <img src="ch07_disinfection/assets/fig_34_p36.png" alt="Hình 34" />
    - **Hình này chứng minh điều gì**
      - Hệ vách ngăn uốn lượn liên hoàn triệt tiêu vùng chết, đạt hiệu quả thủy lực tối ưu ($t_{10}/t_0 = 0.7$).
    - **Từ đâu mà thấy được**
      - Mặt bằng và mặt cắt: Nhiều vách ngăn dẫn dòng liên tục, vùng chết thu hẹp tối thiểu chỉ còn một góc nhỏ trước ngưỡng tràn.

---

#### 7.3.3 Ozone Contactor and Over-Under Contact Basin Systems

##### 7.3.3.1 Ozone Bubble Contactor (Bể sục bọt khí Ozone)

* Nguyên lý cấu tạo và hoạt động của bể sục bọt khí ozone:
  * Bể sục bọt khí ozone là buồng tiếp xúc kín nhiều ngăn sâu ($5\text{--}6\text{ m}$) sử dụng đĩa phân phối bọt khí mịn (fine bubble diffusers) bằng gốm xốp đặt dưới đáy.
  * Khí ozone tạo ra từ hệ thống cấp khí khô và máy ozone được nén qua đĩa sục khí tạo bọt mịn hòa tan vào nước.
  * Dòng nước chuyển động ziczac qua các ngăn tiếp xúc nối tiếp theo chế độ ngược chiều (counter-current) và cùng chiều (co-current) với bọt khí nổi lên.
  * Đỉnh bể được làm kín tuyệt đối để gom khí ozone dư (off-gas) dẫn về tháp phân hủy nhiệt-xúc tác (ozone destruction unit) trước khi xả ra khí quyển.
  * Tại đầu ra của bể tiếp xúc có thể bố trí buồng khử ozone dư (ozone quench) sử dụng hóa chất (calcium thiosulfate hoặc $\text{H}_2\text{O}_2$) khi cần kiểm soát nồng độ dư triệt để.
* Minh họa sơ đồ công nghệ bể sục bọt khí ozone:
  - **Hình 35.** Sơ đồ nguyên lý hệ thống bể sục bọt khí ozone
    - <img src="ch07_disinfection/assets/fig_35_p37.png" alt="Hình 35" />
    - **Hình này chứng minh điều gì**
      - Trình bày chu trình dòng nước ngược/xuôi chiều tiếp xúc bọt khí ozone và cụm phân hủy khí dư off-gas.
    - **Từ đâu mà thấy được**
      - Sơ đồ công nghệ: Khí ozone sục từ đáy ngăn 1 và 2; khí thoát off-gas đi qua bộ Ozone Destruction ra khí quyển; nước qua Ozone Quench.
* Chuẩn bị nguồn khí cấp và cơ chế tạo khí ozone cho buồng sục bọt:
  * Khí cấp cho máy tạo ozone bắt buộc phải sấy khô sâu để ngăn chặn phản ứng tạo axit nitric gây ăn mòn điện cực phóng điện:
  - **Hình 11.** Yêu cầu sấy khô khí cấp cho máy tạo ozone
    - <img src="ch07_disinfection/assets/fig_11_p17.png" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Chứng minh độ ẩm không khí phản ứng tạo axit nitric gây ăn mòn điện cực phóng điện hào quang.
    - **Từ đâu mà thấy được**
      - Thuyết minh kỹ thuật: Không khí cấp phải qua sấy khô đạt điểm sương cực thấp để bảo vệ buồng phóng điện.
  * Các cụm công nghệ hoàn chỉnh của hệ thống khử trùng ozone từ chuẩn bị khí đến buồng tiếp xúc:
##### 7.3.3.2 Ozone Injection Systems (Hệ thống châm Ozone kiểu Injector)

* Phân loại hai phương án châm khí ozone kiểu injector venturi:
  * Phương án A - Châm trực tiếp trên đường ống chính (In-line Injector System):
    * Toàn bộ lưu lượng nước đầu vào (influent) đi qua họng thu hẹp venturi injector lắp thẳng trên đường ống chính.
    * Độ chân không tạo ra tại cổ họng hút khí ozone hòa trộn trực tiếp vào toàn bộ dòng nước trước khi vào buồng tiếp xúc.
  * Phương án B - Châm qua dòng nhánh tăng áp (Sidestream Injector System):
    * Trích một phần lưu lượng nước ($10\text{--}15\%$) từ ống chính qua bơm tăng áp dòng nhánh (sidestream pump).
    * Nước tăng áp đi qua venturi injector với vận tốc lớn, hút khí ozone và hòa tan ở nồng độ bão hòa cao.
    * Dòng nhánh giàu ozone được phun ngược trở lại đường ống chính, đi qua bộ trộn tĩnh (static mixer) phân tán đều vào dòng nước rồi vào contactor.
* Minh họa sơ đồ hai phương án châm khí ozone:
  - **Hình 38.** Sơ đồ hai phương án châm khí ozone kiểu injector
    - <img src="ch07_disinfection/assets/fig_38_p38.png" alt="Hình 38" />
    - **Hình này chứng minh điều gì**
      - Phân biệt cấu hình châm trực tiếp trên đường ống chính (A) và châm qua dòng nhánh tăng áp kết hợp bộ trộn tĩnh (B).
    - **Từ đâu mà thấy được**
      - Phương án A: Injector lắp thẳng trên ống chính; Phương án B: Bơm tăng áp dòng nhánh dẫn qua injector rồi vào Static Mixer.

##### 7.3.3.3 Eight-Chamber Over-Under Contact Basin (Bể tiếp xúc 8 ngăn uốn lượn đứng)

* Cấu tạo hình học và nguyên lý dòng chảy bể tiếp xúc 8 ngăn kiểu tràn-chui:
  * Bể tiếp xúc được chia thành 8 buồng nối tiếp bằng các vách ngăn thẳng đứng bố trí xen kẽ.
  * Các thông số kích thước hình học định nghĩa:
    * Chiều sâu cột nước trong bể: $H$ ($\text{m}$).
    * Chiều dài mỗi buồng tiếp xúc: $L$ ($\text{m}$).
    * Khe hở đáy hoặc khoảng hở tràn qua vách ngăn: $h$ ($\text{m}$).
  * Cơ chế dòng chảy uốn lượn theo phương đứng:
    * Dòng nước chuyển động luân phiên: tràn qua đỉnh vách ngăn thứ nhất, chui qua đáy vách ngăn thứ hai, lặp lại qua 8 ngăn.
    * Bố cục tràn-chui triệt tiêu hiện tượng đoản mạch phân tầng nhiệt độ và dòng chảy tầng.
    * Khí thoát tự do (off-gas) tích tụ ở khoảng không đỉnh bể được gom về ống thoát dẫn sang cụm phá hủy ozone (ozone destruct units).
* Minh họa mặt cắt và thông số hình học bể 8 ngăn tràn-chui:
  - **Hình 39.** Mặt cắt cấu tạo bể tiếp xúc 8 ngăn kiểu tràn-chui
    - <img src="ch07_disinfection/assets/fig_39_p39.png" alt="Hình 39" />
    - **Hình này chứng minh điều gì**
      - Thể hiện định nghĩa kích thước hình học $H$, $L$, $h$ và đường dòng uốn lượn đứng qua 8 buồng nối tiếp.
    - **Từ đâu mà thấy được**
      - Mặt cắt bể: Dòng Influent đi ziczac lên xuống qua các vách ngăn cao thấp xen kẽ đến Effluent; đỉnh bể có ống thu Off-gas.

---

#### 7.3.4 Disinfection Chemical Generation and Dosing Systems

##### 7.3.4.1 Chlorinator Gas Feed System (Thiết bị châm Clo khí định lượng chân không)

* Nguyên lý an toàn chân không của thiết bị châm clo khí (vacuum chlorinator):
  * Thiết bị châm clo khí hiện đại vận hành theo nguyên lý hút chân không gắn trực tiếp trên đầu van bình clo (direct cylinder mounting).
  * Cấu tạo cụm thiết bị châm clo:
    * Khung kẹp bình clo (yoke clamp) và van đầu bình (cylinder valve) với đệm chì làm kín (lead gasket).
    * Van an toàn đầu vào (inlet safety valve) được giữ đóng kín bằng lò xo, chỉ mở ra khi có áp suất chân không phía sau.
    * Cụm màng điều áp chân không (regulating diaphragm assembly) duy trì áp suất chân không ổn định.
    * Lưu lượng kế diện tích biến đổi (rate indicator / rotameter) và van tinh chỉnh lưu lượng (rate valve).
    * Đường ống chân không (vacuum line) bằng vật liệu chịu clo dẫn tới bộ injector.
    * Bộ injector và van một chiều (ejector and check valve assembly): Dòng nước cấp áp lực cao đi qua họng venturi tạo áp suất âm hút khí clo hòa tan tạo dung dịch clo nước.
  * Đặc tính an toàn tuyệt đối: Nếu đường ống chân không bị rò rỉ hoặc đứt gãy, không khí sẽ tràn vào làm mất chân không, van an toàn đầu vào tự động đóng chặt ngay lập tức, ngăn ngừa hoàn toàn rò rỉ khí clo độc hại ra môi trường.
* Minh họa sơ đồ thiết bị châm clo khí chân không:
  - **Hình 42.** Sơ đồ nguyên lý thiết bị châm clo khí chân không
    - <img src="ch07_disinfection/assets/fig_42_p40.png" alt="Hình 42" />
    - **Hình này chứng minh điều gì**
      - Mô tả cơ cấu an toàn chân không từ bình clo qua van điều áp màng đến injector tạo dung dịch clo.
    - **Từ đâu mà thấy được**
      - Đường dẫn khí: Bình cylinder $\rightarrow$ Yoke clamp $\rightarrow$ Regulating diaphragm assembly $\rightarrow$ Vacuum line $\rightarrow$ Ejector tạo Chlorine solution.

##### 7.3.4.2 On-Site Sodium Hypochlorite Generator (Hệ thống điều chế NaOCl tại chỗ bằng điện phân)

* Nguyên lý và phản ứng hóa học điều chế natri hypoclorit tại chỗ:
  * Phương pháp điện phân muối ăn ($\text{NaCl}$) tại chỗ sản xuất dung dịch $\text{NaOCl}$ nồng độ thấp ($0.8\%$), loại trừ nguy cơ vận chuyển và lưu trữ khí clo độc hại.
  * Phương trình phản ứng điện phân tổng quát:
    $$\text{NaCl} + \text{H}_2\text{O} + 2e^- \rightarrow \text{NaOCl} + \text{H}_2\uparrow$$
  * Dung dịch $\text{NaOCl}$ $0.8\%$ nằm dưới ngưỡng quy chuẩn hóa chất nguy hiểm ($< 1\%$), an toàn cho công nhân vận hành.
* Các cụm thiết bị chính của dây chuyền sản xuất $\text{NaOCl}$:
  * Bồn hòa tan muối (salt saturator) tạo dung dịch nước muối bão hòa.
  * Thiết bị làm mềm nước (water softener) loại bỏ ion $\text{Ca}^{2+}$ và $\text{Mg}^{2+}$ để bảo vệ điện cực không bị bám cặn vôi.
  * Bơm định lượng nước muối (brine metering pump) và lưu lượng kế nước pha loãng (dilution water flowmeter).
  * Ống điện phân (electrolyzer cells) dạng module hình trụ bằng titan phủ oxit kim loại quý.
  * Tủ nguồn chỉnh lưu DC (power supply / rectifier) cung cấp dòng điện một chiều công suất lớn.
  * Bồn chứa dung dịch $\text{NaOCl}$ có hệ thống quạt thổi khí pha loãng và thoát khí hydro ($\text{H}_2$ discharge vent) nhằm ngăn chặn nguy cơ cháy nổ hydro.
  * Bơm định lượng $\text{NaOCl}$ châm dung dịch vào tuyến ống cấp nước chính (water main).
* Minh họa hệ thống điều chế natri hypoclorit tại chỗ:
  - **Hình 43.** Sơ đồ cụm thiết bị sản xuất NaOCl bằng phương pháp điện phân
    - <img src="ch07_disinfection/assets/fig_43_p41.jpeg" alt="Hình 43" />
    - **Hình này chứng minh điều gì**
      - Thể hiện dây chuyền đồng bộ từ hòa tan muối, làm mềm nước, điện phân, thông gió hydro đến châm vào ống chính.
    - **Từ đâu mà thấy được**
      - Thiết bị: Salt Saturator $\rightarrow$ Water Softener $\rightarrow$ Electrolyzer $\rightarrow$ Bồn chứa có quạt thổi Hydrogen Discharge $\rightarrow$ Bơm định lượng vào Water Main.

##### 7.3.4.3 Chlorine Dioxide Generator (Thiết bị điều chế Clo dioxit ClO2 tại chỗ)

* Cơ chế hóa học và tính chất nguy hiểm của clo dioxit ($\text{ClO}_2$):
  * Clo dioxit là chất oxy hóa mạnh và là một gốc tự do bền vững (stable free radical).
  * Ở nồng độ cao trong pha khí, $\text{ClO}_2$ có nguy cơ phát nổ với giới hạn nổ dưới (LEL) từ $10\%$ đến $39\%$.
  * Vì tính chất kém bền và nguy cơ nổ, $\text{ClO}_2$ không thể nén lỏng hoặc lưu trữ trong bình áp lực, bắt buộc phải điều chế tại chỗ (on-site synthesis).
* Phương trình phản ứng điều chế $\text{ClO}_2$ trong thực tế:
  * Phản ứng giữa natri clorit và axit clohydric:
    $$4\text{ HCl} + 5\text{ NaClO}_2 \rightarrow 4\text{ ClO}_2\uparrow + 5\text{ NaCl} + 2\text{ H}_2\text{O}$$
  * Khí $\text{ClO}_2$ sinh ra được hòa tan ngay lập tức vào dòng nước tạo dung dịch khử trùng có nồng độ an toàn dưới ngưỡng phân hủy.
* Cấu tạo cụm thiết bị skid điều chế $\text{ClO}_2$:
  * Hai bồn chứa tiền chất hóa chất riêng biệt: dung dịch axit $\text{HCl}$ và dung dịch muối $\text{NaClO}_2$.
  * Bơm định lượng hóa chất có độ chính xác cao điều khiển tỷ lệ mol phản ứng.
  * Cột phản ứng chân không (vacuum reaction column) tích hợp buồng hòa tan eductor.
  * Tủ điều khiển điện tử tự động (control cabinet) giám sát lưu lượng và cảnh báo áp suất.
* Minh họa skid điều chế $\text{ClO}_2$ tại chỗ:
  - **Hình 46.** Cụm thiết bị skid điều chế hóa chất clo dioxit tại chỗ
    - <img src="ch07_disinfection/assets/fig_46_p42.jpeg" alt="Hình 46" />
    - **Hình này chứng minh điều gì**
      - Mô tả kết cấu module tích hợp gồm 2 thùng chứa tiền chất hóa chất, bơm định lượng và tủ điều khiển tự động.
    - **Từ đâu mà thấy được**
      - Cụm skid Accepta: Hai bồn hóa chất phía dưới kết nối các đường ống châm vào cụm phản ứng gắn trên bảng điều khiển điện tử.

##### 7.3.4.4 Ozonator Generation and Package Skid Unit (Hệ thống máy tạo Ozone phóng điện hào quang)

* Nguyên lý phóng điện hào quang (corona discharge) tạo ozone:
  * Ozone ($\text{O}_3$) là chất khí không bền, được điều chế tại chỗ bằng cách phóng điện cao áp qua dòng khí oxy khô hoặc không khí khô.
  * Dòng electron năng lượng cao phá vỡ liên kết phân tử oxy thành oxy nguyên tử ($\text{O} + \text{O}_2 \rightarrow \text{O}_3$).
  * Khe hở phóng điện giữa điện cực cao thế và lớp điện môi (dielectric) thường có kích thước rất hẹp ($1\text{--}3\text{ mm}$).
* Cấu tạo module trọn gói của hệ thống ozonator:
  * Máy tạo ozone module hóa gắn trên khung rack có quạt làm mát cưỡng bức.
  * Bồn tiếp xúc ozone chế tạo bằng thép không gỉ 316 (316 SS Contact Tank) chống ăn mòn hóa học cao.
  * Bên trong bồn bố trí các vách ngăn (inner baffles) kéo dài thời gian tiếp xúc giữa khí ozone và nước.
  * Van xả khí tự động trên đỉnh bồn (air vent) thu gom khí ozone và không khí không hòa tan.
  * Đồng hồ đo áp lực (informative pressure gauges) kiểm soát chính xác chế độ thủy lực.
  * Toàn bộ cụm thiết bị đặt trên khung đế skid bằng thép không gỉ 304 (304 SS Skid).
* Minh họa máy tạo ozone công nghiệp và skid buồng tiếp xúc inox:
  - **Hình 47.** Thiết bị máy tạo ozone công nghiệp kèm bồn tiếp xúc
    - <img src="ch07_disinfection/assets/fig_47_p43.jpeg" alt="Hình 47" />
    - **Hình này chứng minh điều gì**
      - Giới thiệu tổ hợp trọn gói gồm tủ nguồn phóng điện, bồn phản ứng áp lực và bơm tuần hoàn.
    - **Từ đâu mà thấy được**
      - Khối thiết bị ClearWater: Bồn phản ứng trụ đứng đặt cạnh khung tủ phát ozone và cụm bơm áp lực phía chân đế.
  - **Hình 48.** Cụm skid buồng tiếp xúc ozone bằng thép không gỉ 316
    - <img src="ch07_disinfection/assets/fig_48_p43.jpeg" alt="Hình 48" />
    - **Hình này chứng minh điều gì**
      - Chi tiết cấu tạo bồn tiếp xúc inox 316 có vách ngăn trong, van xả khí đỉnh và đồng hồ đo áp lực.
    - **Từ đâu mà thấy được**
      - Nhãn ghi trên bồn: "Contact Tank 316 SS", "Inner baffles", "Air vent removes undissolved air & ozone", "304 SS Skid", "Pressure Gauges".

##### 7.3.4.5 Ultraviolet (UV) Lamp Disinfection Reactor (Hệ thống thiết bị khử trùng bằng đèn cực tím)

* Cơ chế diệt khuẩn vật lý của bức xạ cực tím (UV radiation):
  * Khử trùng bằng tia UV là phương pháp vật lý, không sử dụng hóa chất và không tạo sản phẩm phụ halogen hóa.
  * Tia cực tím dải UVC tác động xuyên qua màng tế bào, bị hấp thụ mạnh bởi phân tử DNA/RNA của vi sinh vật.
  * Năng lượng photon cực tím làm biến dạng cấu trúc xoắn kép, dimer hóa các gốc thymine, ngăn chặn vi sinh vật nhân đôi và gây bất hoạt hoàn toàn.
* Đặc tính quang phổ điện từ và dải bước sóng diệt khuẩn tối ưu:
  * Phổ UV nằm giữa vùng tia X và ánh sáng khả kiến ($100\text{--}400\text{ nm}$), trong đó UVC ($200\text{--}280\text{ nm}$) có hiệu lực diệt khuẩn cao nhất với đỉnh hấp thụ ở xấp xỉ $254\text{ nm}$:
  - **Hình 13.** Phổ bức xạ điện từ và các dải sóng cực tím
    - <img src="ch07_disinfection/assets/fig_13_p19.png" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Xác định vị trí dải sóng diệt khuẩn UV-C ($200\text{--}280\text{ nm}$) với đỉnh hấp thụ DNA tại $254\text{ nm}$.
    - **Từ đâu mà thấy được**
      - Sơ đồ phổ điện từ: Phân chia 4 vùng Vacuum UV ($100\text{--}200$), Shortwave UV-C ($200\text{--}280$), UV-B ($280\text{--}315$), UV-A ($315\text{--}400\text{ nm}$).
  * Bước sóng $254\text{ nm}$ tương ứng với vạch phát xạ cộng hưởng đặc trưng của hơi thủy ngân trong bóng đèn cực tím:
* Phân loại và thông số kỹ thuật của ba loại đèn UV công nghiệp:
  * Ba loại đèn UV chính trong kỹ thuật xử lý nước gồm đèn áp suất thấp cường độ thấp (LPLI), đèn áp suất thấp cường độ cao (LPHI), và đèn trung áp (MP):
* Cấu tạo buồng chiếu xạ kín và cơ cấu gạt rửa tự động (wiper mechanism):
  * Thiết bị UV dạng buồng kín (closed-vessel UV reactor) gồm vỏ thân bằng thép không gỉ chịu áp lực cao.
  * Đèn cực tím (germicidal lamp) được lồng bên trong ống thạch anh (quartz sleeve) bảo vệ để duy trì nhiệt độ tối ưu và cách điện với dòng nước.
  * Cơ cấu gạt rửa (wiper mechanism) tự động hoặc điều khiển tay di chuyển dọc ống thạch anh để lau sạch cặn bám vô cơ và màng sinh học, duy trì độ truyền quang UVT.
  * Cổng quan sát (sight port) và cảm biến đo cường độ UV (UV intensity sensor) liên tục giám sát liều bức xạ thực tế.
  * Hộp điều khiển điện tử (electrical enclosure / ballast controller) điều chỉnh công suất và hiển thị trạng thái làm việc.
* Minh họa thiết bị UV buồng kín và cơ cấu gạt rửa ống thạch anh:
  - **Hình 53.** Thiết bị khử trùng nước bằng tia cực tím TrojanUVMAX
    - <img src="ch07_disinfection/assets/fig_53_p44.jpeg" alt="Hình 53" />
    - **Hình này chứng minh điều gì**
      - Giới thiệu module buồng chiếu xạ tia cực tím bằng inox kết nối khối nguồn điều khiển điện tử kỹ thuật số.
    - **Từ đâu mà thấy được**
      - Ảnh thiết bị: Ống buồng chiếu TrojanUVMAX bằng thép không gỉ gắn trên đường ống nước và hộp điều khiển hiển thị số màu xanh.
  - **Hình 54.** Cấu tạo chi tiết bên trong buồng đèn UV có cơ cấu gạt rửa
    - <img src="ch07_disinfection/assets/fig_54_p44.png" alt="Hình 54" />
    - **Hình này chứng minh điều gì**
      - Minh họa cấu trúc bóng đèn trong ống thạch anh, chùm tia cực tím, cổng quang học và hệ gạt cơ học chống bám cặn.
    - **Từ đâu mà thấy được**
      - Mặt cắt buồng: Germicidal lamp in quartz sleeve, Patented wiper mechanism, Sight port, Removable head, Wiper knob.

### 7.4 Calculation and Worked Examples

- Tính toán kỹ thuật khử trùng nước cấp bao gồm ba bài toán thiết kế công nghệ cốt lõi:
  - Cân bằng phân ly axit hypoclorơ ($\text{HOCl}$) và xác định tỷ lệ phần trăm clo hoạt tính không phân ly theo $\text{pH}$ ở $25^\circ\text{C}$ (Example 7-1).
  - Định lượng liều clo châm tại điểm đột biến (breakpoint chlorination) để oxy hóa hoàn toàn amoniac ($\text{NH}_3\text{-N}$) thành khí nitơ ($\text{N}_2$) hoặc ion nitrat ($\text{NO}_3^-$) (Example 7-2).
  - Thiết kế công nghệ và thủy lực bể tiếp xúc clo dạng uốn lượn ziczac (longitudinal-serpentine contact chamber) đạt tích số khử trùng $C \cdot t$, thời gian tiếp xúc $t_{10}$ và hệ số vách ngăn hiệu quả hơn $t_{10}/t_0 = 0.7$ (Example 7-3).

#### Example 7-1: Chlorine dosing and contact chamber sizing

- **Đề bài**: (WaWE, 13-3) If 15 mg/L of HOCl is added to a potable water for disinfection and the final measured pH is 7.0, what percent of the HOCl is not dissociated? Assume the temperature is 25°C. (Nếu châm $15\text{ mg/L}$ axit hypoclorơ $\text{HOCl}$ vào nước cấp sinh hoạt để khử trùng và $\text{pH}$ đo được cuối cùng là $7.0$, tỷ lệ phần trăm $\text{HOCl}$ không phân ly là bao nhiêu? Giả thiết nhiệt độ nước là $25^\circ\text{C}$).
- **Dữ kiện**:
  - Liều lượng axit hypoclorơ châm vào nước: $C_{\text{dose}} = 15.0\text{ mg/L}$ (tính theo $\text{Cl}_2$).
  - Giá trị $\text{pH}$ đo được của nước sau châm clo: $\text{pH} = 7.0$.
  - Nhiệt độ chất lỏng: $T = 25^\circ\text{C}$ ($298.15\text{ K}$).
  - Hằng số điện ly axit của $\text{HOCl}$ ở $25^\circ\text{C}$: $K_a = 2.90 \times 10^{-8}\text{ mol/L}$.
  - Chỉ số logarit axit của $\text{HOCl}$ ở $25^\circ\text{C}$: $pK_a = -\log_{10}(K_a) = -\log_{10}(2.90 \times 10^{-8}) = 7.5376 \approx 7.54$.
- **Quy tắc áp dụng**:
  - Định nghĩa nồng độ ion hydro từ chỉ số $\text{pH}$:
    $$[\text{H}^+] = 10^{-\text{pH}}$$
  - Phương trình cân bằng điện ly axit yếu $\text{HOCl}$ trong pha nước:
    $$\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^-$$
  - Biểu thức định luật tác dụng khối lượng cho hằng số phân ly axit:
    $$K_a = \frac{[\text{H}^+][\text{OCl}^-]}{[\text{HOCl}]}$$
  - Phương trình tính phân số dạng $\text{HOCl}$ chưa phân ly ($\alpha_0$):
    $$\alpha_0 = \frac{[\text{HOCl}]}{[\text{HOCl}] + [\text{OCl}^-]} = \frac{[\text{H}^+]}{[\text{H}^+] + K_a} = \frac{1}{1 + \frac{K_a}{[\text{H}^+]}} = \frac{1}{1 + 10^{\text{pH} - pK_a}}$$
  - Phương trình tính phân số dạng ion hypoclorit phân ly ($\alpha_1$):
    $$\alpha_1 = \frac{[\text{OCl}^-]}{[\text{HOCl}] + [\text{OCl}^-]} = \frac{K_a}{[\text{H}^+] + K_a} = 1 - \alpha_0$$
  - Phương trình phân bổ nồng độ clo tự do theo phân số khối lượng:
    $$C_{\text{HOCl}} = C_{\text{dose}} \cdot \alpha_0, \quad C_{\text{OCl}^-} = C_{\text{dose}} \cdot \alpha_1$$
- **Lời giải**:
  - **Bước 1**: Tính nồng độ mol ion hydro $[\text{H}^+]$ từ giá trị $\text{pH}$.
    - Căn cứ: Định nghĩa nồng độ ion hydro $[\text{H}^+] = 10^{-\text{pH}}$.
    - Nhìn vào: Giá trị $\text{pH} = 7.0$ được cung cấp trong đề bài Example 7-1 trên Slide 45.
    - Thực hiện:
      $$[\text{H}^+] = 10^{-7.00} = 1.00 \times 10^{-7}\text{ mol/L}$$
  - **Bước 2**: Xác định hằng số phân ly axit $K_a$ và chỉ số $pK_a$ ở nhiệt độ $25^\circ\text{C}$.
    - Căn cứ: Cân bằng phân ly $\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^-$ và giá trị thực nghiệm của $K_a$ ở $25^\circ\text{C}$ nêu tại Mục 7.2.1.
    - Nhìn vào: Nhiệt độ nước $T = 25^\circ\text{C}$ nêu trong đề bài.
    - Thực hiện:
      $$K_a = 2.90 \times 10^{-8}\text{ mol/L}$$
      $$pK_a = -\log_{10}(2.90 \times 10^{-8}) = 7.5376 \approx 7.54$$
  - **Bước 3**: Tính toán phân số phần trăm $\text{HOCl}$ chưa phân ly ($\alpha_0$).
    - Căn cứ: Phương trình phân số $\text{HOCl}$ chưa phân ly $\alpha_0 = \frac{[\text{H}^+]}{[\text{H}^+] + K_a}$.
    - Nhìn vào: Giá trị $[\text{H}^+] = 1.00 \times 10^{-7}\text{ mol/L}$ và hằng số $K_a = 2.90 \times 10^{-8}\text{ mol/L}$.
    - Thực hiện:
      $$\alpha_0 = \frac{1.00 \times 10^{-7}}{1.00 \times 10^{-7} + 2.90 \times 10^{-8}} = \frac{1.00 \times 10^{-7}}{1.29 \times 10^{-7}} = 0.77519 = 77.52\% \approx 77.5\%$$
      Kiểm tra chéo qua công thức logarit theo $pK_a$:
      $$\alpha_0 = \frac{1}{1 + 10^{\text{pH} - pK_a}} = \frac{1}{1 + 10^{7.00 - 7.5376}} = \frac{1}{1 + 10^{-0.5376}} = \frac{1}{1 + 0.28999} = 0.77520 \approx 77.5\%$$
  - **Bước 4**: Xác định phân số phần trăm ion hypoclorit đã phân ly ($\alpha_1$).
    - Căn cứ: Tổng phân số thành phần bằng đơn vị: $\alpha_0 + \alpha_1 = 1.0$.
    - Nhìn vào: Kết quả $\alpha_0 = 0.77519$ tính được từ Bước 3.
    - Thực hiện:
      $$\alpha_1 = 1.0 - \alpha_0 = 1.0 - 0.77519 = 0.22481 = 22.48\% \approx 22.5\%$$
  - **Bước 5**: Xác định nồng độ phân bố của các dạng clo tự do trong dung dịch nước.
    - Căn cứ: Tổng liều châm clo tự do $C_{\text{dose}} = 15.0\text{ mg/L}$ và phân số $\alpha_0, \alpha_1$.
    - Nhìn vào: Liều châm $15.0\text{ mg/L}$ $\text{HOCl}$ trong đề bài.
    - Thực hiện:
      $$C_{\text{HOCl}} = C_{\text{dose}} \cdot \alpha_0 = 15.0\text{ mg/L} \times 0.77519 = 11.628\text{ mg/L} \approx 11.63\text{ mg/L as }\text{Cl}_2$$
      $$C_{\text{OCl}^-} = C_{\text{dose}} \cdot \alpha_1 = 15.0\text{ mg/L} \times 0.22481 = 3.372\text{ mg/L} \approx 3.37\text{ mg/L as }\text{Cl}_2$$
- **Kết quả**:
  - Tỷ lệ phần trăm $\text{HOCl}$ chưa phân ly: $77.5\%$ ($77.52\%$).
  - Tỷ lệ phần trăm ion $\text{OCl}^-$ phân ly: $22.5\%$ ($22.48\%$).
  - Nồng độ axit hypoclorơ hoạt tính cao $\text{HOCl}$: $11.63\text{ mg/L as }\text{Cl}_2$.
  - Nồng độ ion hypoclorit hoạt tính thấp $\text{OCl}^-$: $3.37\text{ mg/L as }\text{Cl}_2$.
- **Kiểm tra lại**:
  - Kiểm tra tổng phân số: $\alpha_0 + \alpha_1 = 77.519\% + 22.481\% = 100.000\%$.
  - Kiểm tra cân bằng khối lượng: $C_{\text{HOCl}} + C_{\text{OCl}^-} = 11.63\text{ mg/L} + 3.37\text{ mg/L} = 15.00\text{ mg/L} = C_{\text{dose}}$.
  - Kiểm tra điều kiện cân bằng $K_a$:
    $$\frac{[\text{H}^+][\text{OCl}^-]}{[\text{HOCl}]} = \frac{1.00 \times 10^{-7} \times 3.3721}{11.6279} = 2.900 \times 10^{-8}\text{ mol/L} = K_a$$
  - Đánh giá ý nghĩa kỹ thuật: Ở $\text{pH} = 7.0$, dạng $\text{HOCl}$ chiếm tỷ trọng áp đảo ($77.5\%$). Vì $\text{HOCl}$ có khả năng diệt khuẩn mạnh hơn $\text{OCl}^-$ từ $80$ đến $100$ lần, duy trì $\text{pH} \le 7.0 - 7.5$ giúp trạm xử lý tối ưu hóa hiệu quả khử trùng và giảm thiểu liều hóa chất châm vào.

#### Example 7-2: CT calculation for Giardia inactivation

- **Đề bài**: (PoWT, 326) Ammonia is added to pure water in the laboratory to reach a concentration of 1 mg/L as N. Estimate the chlorine dose needed to reach breakpoint for the following conditions: (1) all the ammonia is converted to nitrogen gas and (2) all the ammonia is converted to nitrate ion. Which reaction requires less chlorine? (Amoniac được thêm vào nước tinh khiết trong phòng thí nghiệm để đạt nồng độ $1\text{ mg/L as N}$. Ước tính liều lượng clo cần châm để đạt điểm đột biến cho các điều kiện sau: (1) toàn bộ amoniac được chuyển hóa thành khí nitơ $\text{N}_2$ và (2) toàn bộ amoniac được oxy hóa thành ion nitrat $\text{NO}_3^-$. Phản ứng nào tiêu tốn ít clo hơn nhằm bảo đảm hiệu quả tích số $C \cdot t$ khử trùng vi sinh vật và u nang Giardia?).
- **Dữ kiện**:
  - Nồng độ amoniac trong nước sạch thí nghiệm: $[\text{NH}_3\text{-N}] = 1.0\text{ mg/L as N}$.
  - Khối lượng mol nguyên tử của Nitơ ($\text{N}$): $M_{\text{N}} = 14.007\text{ g/mol}$.
  - Khối lượng mol phân tử của khí Clo ($\text{Cl}_2$): $M_{\text{Cl}_2} = 70.906\text{ g/mol}$ (nguyên tử khối clo $35.453\text{ g/mol}$).
  - Điều kiện phản ứng 1: Chuyển hóa toàn bộ amoniac thành khí nitơ ($\text{N}_2$).
  - Điều kiện phản ứng 2: Oxy hóa toàn bộ amoniac thành ion nitrat ($\text{NO}_3^-$).
- **Quy tắc áp dụng**:
  - Phương trình hóa học và tỷ lượng phản ứng cho Điều kiện 1 (chuyển hóa thành $\text{N}_2$):
    $$2\text{NH}_3 + 3\text{Cl}_2 \rightarrow \text{N}_2 \uparrow + 6\text{HCl}$$
    (hoặc dạng axit hypoclorơ: $2\text{NH}_3 + 3\text{HOCl} \rightarrow \text{N}_2 \uparrow + 3\text{H}_2\text{O} + 3\text{HCl}$).
    Tỷ lệ mol hợp thức: $3\text{ mol Cl}_2$ phản ứng với $2\text{ mol NH}_3\text{-N}$ (tỷ lệ $1.5\text{ mol Cl}_2/\text{mol N}$).
  - Tỷ lệ khối lượng lý thuyết cho Điều kiện 1:
    $$R_{\text{mass},1} = \frac{3 \times M_{\text{Cl}_2}}{2 \times M_{\text{N}}} = \frac{3 \times 70.906\text{ g}}{2 \times 14.007\text{ g}} = \frac{212.718}{28.014} = 7.5933\text{ mg Cl}_2/\text{mg N} \approx 7.60\text{ mg Cl}_2/\text{mg N}$$
  - Phương trình hóa học và tỷ lượng phản ứng cho Điều kiện 2 (chuyển hóa thành $\text{NO}_3^-$):
    $$\text{NH}_3 + 4\text{Cl}_2 + 3\text{H}_2\text{O} \rightarrow \text{HNO}_3 + 8\text{HCl}$$
    (hoặc dạng axit hypoclorơ: $\text{NH}_3 + 4\text{HOCl} \rightarrow \text{HNO}_3 + 4\text{HCl} + \text{H}_2\text{O}$).
    Tỷ lệ mol hợp thức: $4\text{ mol Cl}_2$ phản ứng với $1\text{ mol NH}_3\text{-N}$ (tỷ lệ $4.0\text{ mol Cl}_2/\text{mol N}$).
  - Tỷ lệ khối lượng lý thuyết cho Điều kiện 2:
    $$R_{\text{mass},2} = \frac{4 \times M_{\text{Cl}_2}}{1 \times M_{\text{N}}} = \frac{4 \times 70.906\text{ g}}{14.007\text{ g}} = \frac{283.624}{14.007} = 20.2487\text{ mg Cl}_2/\text{mg N} \approx 20.25\text{ mg Cl}_2/\text{mg N}$$
  - Phương trình tính liều clo cần châm:
    $$\text{Dose}_{\text{Cl}_2} = [\text{NH}_3\text{-N}] \times R_{\text{mass}}$$
  - Phương trình xác định chênh lệch định lượng và tỷ lệ tiết kiệm hóa chất:
    $$\Delta \text{Dose} = \text{Dose}_2 - \text{Dose}_1, \quad \%\text{ Tiết kiệm} = \frac{\text{Dose}_2 - \text{Dose}_1}{\text{Dose}_2} \times 100\%, \quad \text{Hệ số} = \frac{\text{Dose}_2}{\text{Dose}_1}$$
- **Lời giải**:
  - **Bước 1**: Đánh giá tỷ lượng hóa học và tính toán liều clo cho Điều kiện 1 (chuyển hóa thành $\text{N}_2$).
    - Căn cứ: Phương trình phản ứng $2\text{NH}_3 + 3\text{Cl}_2 \rightarrow \text{N}_2 + 6\text{HCl}$ và khối lượng mol các chất.
    - Nhìn vào: Yêu cầu "(1) all the ammonia is converted to nitrogen gas" và nồng độ $[\text{NH}_3\text{-N}] = 1.0\text{ mg/L}$ trong đề bài.
    - Thực hiện:
      - Khối lượng $3\text{ mol Cl}_2$: $3 \times 70.906\text{ g} = 212.718\text{ g}$.
      - Khối lượng $2\text{ mol N}$: $2 \times 14.007\text{ g} = 28.014\text{ g}$.
      - Tỷ số khối lượng tiêu thụ:
        $$R_{\text{mass},1} = \frac{212.718\text{ g Cl}_2}{28.014\text{ g N}} = 7.5933\text{ mg Cl}_2/\text{mg NH}_3\text{-N} \approx 7.60\text{ mg Cl}_2/\text{mg N}$$
      - Liều clo cần châm cho $1.0\text{ mg/L as N}$:
        $$\text{Dose}_{\text{Cl}_2,1} = 1.0\text{ mg N/L} \times 7.5933\text{ mg Cl}_2/\text{mg N} = 7.5933\text{ mg/L} \approx 7.60\text{ mg/L Cl}_2$$
  - **Bước 2**: Đánh giá tỷ lượng hóa học và tính toán liều clo cho Điều kiện 2 (chuyển hóa thành $\text{NO}_3^-$).
    - Căn cứ: Phương trình phản ứng $\text{NH}_3 + 4\text{Cl}_2 + 3\text{H}_2\text{O} \rightarrow \text{HNO}_3 + 8\text{HCl}$ và khối lượng mol các chất.
    - Nhìn vào: Yêu cầu "(2) all the ammonia is converted to nitrate ion" và nồng độ $[\text{NH}_3\text{-N}] = 1.0\text{ mg/L}$ trong đề bài.
    - Thực hiện:
      - Khối lượng $4\text{ mol Cl}_2$: $4 \times 70.906\text{ g} = 283.624\text{ g}$.
      - Khối lượng $1\text{ mol N}$: $1 \times 14.007\text{ g} = 14.007\text{ g}$.
      - Tỷ số khối lượng tiêu thụ:
        $$R_{\text{mass},2} = \frac{283.624\text{ g Cl}_2}{14.007\text{ g N}} = 20.2487\text{ mg Cl}_2/\text{mg NH}_3\text{-N} \approx 20.25\text{ mg Cl}_2/\text{mg N}$$
      - Liều clo cần châm cho $1.0\text{ mg/L as N}$:
        $$\text{Dose}_{\text{Cl}_2,2} = 1.0\text{ mg N/L} \times 20.2487\text{ mg Cl}_2/\text{mg N} = 20.2487\text{ mg/L} \approx 20.25\text{ mg/L Cl}_2$$
  - **Bước 3**: So sánh định lượng và xác định phản ứng tiêu tốn ít clo hơn.
    - Căn cứ: Chênh lệch tuyệt đối $\Delta \text{Dose}$ và tỷ lệ phần trăm tiết kiệm $\% \text{ Tiết kiệm}$.
    - Nhìn vào: Câu hỏi "Which reaction requires less chlorine?" trong đề bài.
    - Thực hiện:
      - Chênh lệch liều clo tiêu thụ giữa hai phản ứng:
        $$\Delta \text{Dose} = 20.2487\text{ mg/L} - 7.5933\text{ mg/L} = 12.6554\text{ mg/L} \approx 12.65\text{ mg/L Cl}_2$$
      - Tỷ lệ giảm tiêu thụ clo khi oxy hóa về $\text{N}_2$:
        $$\%\text{ Tiết kiệm} = \frac{12.6554}{20.2487} \times 100\% = 62.50\%$$
      - Tỷ số nhu cầu clo giữa hai phản ứng:
        $$\text{Hệ số} = \frac{20.2487}{7.5933} = 2.6666 \approx 2.67\text{ lần}$$
      - Đánh giá lựa chọn: Phản ứng (1) oxy hóa amoniac thành khí nitơ ($\text{N}_2$) tiêu tốn ít clo hơn đáng kể ($7.60\text{ mg/L}$ so với $20.25\text{ mg/L}$, tiết kiệm $62.5\%$).
- **Kết quả**:
  - Liều clo cần thiết để chuyển hóa amoniac thành khí nitơ ($\text{N}_2$): $7.60\text{ mg/L Cl}_2$ ($7.5933\text{ mg/L}$).
  - Liều clo cần thiết để chuyển hóa amoniac thành ion nitrat ($\text{NO}_3^-$): $20.25\text{ mg/L Cl}_2$ ($20.2487\text{ mg/L}$).
  - Phản ứng tạo khí nitơ ($\text{N}_2$) tiêu tốn ít clo hơn $12.65\text{ mg/L}$ ($62.5\%$ mức tiết kiệm hóa chất, ít hơn $2.67$ lần).
- **Kiểm tra lại**:
  - Kiểm tra bảo toàn số electron trao đổi:
    - Trạng thái oxy hóa của $\text{N}$ trong $\text{NH}_3$ là $-3$.
    - Trong $\text{N}_2$, trạng thái oxy hóa của $\text{N}$ là $0$ (nhường $3e^-$ trên mỗi nguyên tử $\text{N}$). Mỗi phân tử $\text{Cl}_2$ nhận $2e^-$, do đó cần $\frac{3}{2} = 1.5\text{ mol Cl}_2/\text{mol N}$.
    - Trong $\text{NO}_3^-$, trạng thái oxy hóa của $\text{N}$ là $+5$ (nhường $8e^-$ trên mỗi nguyên tử $\text{N}$). Do đó cần $\frac{8}{2} = 4.0\text{ mol Cl}_2/\text{mol N}$.
    - Tỷ số electron trao đổi: $\frac{8e^-}{3e^-} = 2.667$, trùng khớp hoàn toàn với tỷ số liều lượng clo $\frac{20.2487}{7.5933} = 2.667$.
  - Đánh giá công nghệ: Trong thực tế xử lý nước cấp, quá trình khử trùng điểm đột biến diễn ra chủ yếu theo cơ chế phản ứng 1 giải phóng khí $\text{N}_2$ không độc hại ra khí quyển. Phản ứng 2 tạo ion nitrat chỉ xuất hiện khi clo bị châm quá mức trong điều kiện tiếp xúc kéo dài, gây nguy cơ tăng hàm lượng nitrat độc hại trong nước sạch.

#### Example 7-3: Sodium hypochlorite dosing system

- **Đề bài**: (WaWE, 13-32) Design a longitudinal-serpentine chlorine contact chamber for a design flow of 18,400 m3/d. The required t10 to achieve a C.t of 200 is 100 min. The design must provide superior performance, that is t10/t0 = 0.7. (Thiết kế hệ thống khử trùng bể tiếp xúc clo uốn khúc dọc ziczac cho hệ thống châm natri hypoclorit / clo với lưu lượng thiết kế $18,400\text{ m}^3/\text{ngày}$. Thời gian lưu hiệu dụng $t_{10}$ yêu cầu để đạt tích số khử trùng $C \cdot t = 200\text{ mg}\cdot\text{min/L}$ là $100\text{ phút}$. Thiết kế phải cung cấp hiệu suất thủy lực hiệu quả hơn với tỷ số vách ngăn $t_{10}/t_0 = 0.7$).
- **Dữ kiện**:
  - Lưu lượng thiết kế ngày đêm của nhà máy: $Q = 18,400\text{ m}^3/\text{ngày}$.
  - Thời gian tiếp xúc hiệu dụng 90% lượng nước yêu cầu: $t_{10} = 100.0\text{ phút}$.
  - Chỉ số tích số khử trùng $C \cdot t$ yêu cầu: $CT = 200.0\text{ mg}\cdot\text{min/L}$.
  - Nồng độ clo dư tự do mục tiêu tại đầu ra: $C = \frac{CT}{t_{10}} = \frac{200.0}{100.0} = 2.0\text{ mg/L}$.
  - Cấp vách ngăn xuất sắc (Superior Baffling): $\text{BF} = t_{10}/t_0 = 0.70$.
  - Tiêu chuẩn tỷ số hình học hành trình dòng chảy trên bề rộng kênh: $L_{\text{path}} / W_c \ge 40:1$ (ngăn ngừa đoản mạch).
  - Chiều sâu cột nước công tác lựa chọn: $H = 3.00\text{ m}$ (dải tiêu chuẩn $2.5 - 4.0\text{ m}$).
  - Chiều cao an toàn thành bể (freeboard): $h_{\text{fb}} = 0.50\text{ m}$.
  - Chiều rộng mỗi nhánh kênh lựa chọn: $W_c = 2.50\text{ m}$.
  - Số lượng nhánh kênh ziczac song song lựa chọn: $N_c = 6\text{ kênh}$.
  - Số lượng vách ngăn uốn dòng: $N_{\text{baffles}} = N_c - 1 = 5\text{ vách}$.
  - Chiều dày mỗi vách ngăn bê tông cốt thép: $t_{\text{wall}} = 0.20\text{ m}$.
  - Hệ số nhám thành bê tông Manning: $n = 0.013$.
  - Hệ số tổn thất cục bộ tại mỗi góc uốn 180°: $K_b = 2.5$.
  - Độ nhớt động học của nước ở $20^\circ\text{C}$: $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
  - Gia tốc trọng trường: $g = 9.81\text{ m/s}^2$.
- **Quy tắc áp dụng**:
  - Mối liên hệ tích số khử trùng USEPA:
    $$CT = C \cdot t_{10}$$
  - Công thức hệ số vách ngăn xác định thời gian lưu lý thuyết:
    $$t_0 = \frac{t_{10}}{\text{BF}} = \frac{t_{10}}{t_{10}/t_0}$$
  - Phương trình tính thể tích nước hữu ích công tác của bể:
    $$V = Q \cdot t_0$$
  - Diện tích mặt bằng lắng và tổng chiều sâu thành bể:
    $$A_s = \frac{V}{H}, \quad H_{\text{total}} = H + h_{\text{fb}}$$
  - Chiều dài tổng hành trình dòng chảy và kiểm tra tiêu chuẩn tỷ số hình học aspect ratio:
    $$L_{\text{path}} = \frac{A_s}{W_c}, \quad \text{Aspect Ratio} = \frac{L_{\text{path}}}{W_c} \ge 40:1$$
  - Kích thước hình học các kênh và mặt bằng bể:
    $$L_c = \frac{L_{\text{path}}}{N_c}, \quad W_{\text{basin}} = N_c \cdot W_c + (N_c - 1) \cdot t_{\text{wall}}$$
  - Các thông số thủy lực dòng chảy trong kênh:
    $$A_x = W_c \cdot H, \quad v_h = \frac{Q}{A_x}$$
    $$P = W_c + 2H, \quad R_h = \frac{A_x}{P}, \quad D_h = 4R_h$$
    $$Re = \frac{v_h \cdot 4 R_h}{\nu}, \quad Fr = \frac{v_h^2}{g \cdot R_h}$$
  - Phương trình tổn thất ma sát Manning và tổn thất cục bộ tại các góc quay 180°:
    $$h_f = L_{\text{path}} \left[ \frac{n \cdot v_h}{R_h^{2/3}} \right]^2$$
    $$h_m = (N_c - 1) \cdot K_b \cdot \frac{v_h^2}{2g}$$
    $$h_L = h_f + h_m$$
- **Lời giải**:
  - **Bước 1**: Quy đổi lưu lượng thiết kế sang các đơn vị thời gian chuẩn.
    - Căn cứ: Hệ số quy đổi thời gian $1\text{ ngày} = 24\text{ giờ} = 1440\text{ phút} = 86400\text{ giây}$.
    - Nhìn vào: Giá trị lưu lượng $Q = 18,400\text{ m}^3/\text{ngày}$ trong đề bài Example 7-3.
    - Thực hiện:
      $$Q_{\text{hr}} = \frac{18,400}{24} = 766.67\text{ m}^3/\text{h}$$
      $$Q_{\text{min}} = \frac{18,400}{1,440} = 12.7778\text{ m}^3/\text{phút}$$
      $$Q_{\text{sec}} = \frac{18,400}{86,400} = 0.21296\text{ m}^3/\text{s}$$
  - **Bước 2**: Xác định thời gian lưu thủy lực lý thuyết $t_0$ và thể tích hữu ích $V$.
    - Căn cứ: Hệ số vách ngăn cấp Superior $\text{BF} = t_{10}/t_0 = 0.70$ (Slide 34) và công thức $t_0 = t_{10}/\text{BF}$.
    - Nhìn vào: Thời gian tiếp xúc $t_{10} = 100.0\text{ phút}$ và hệ số $\text{BF} = 0.7$ trong đề bài.
    - Thực hiện:
      - Thời gian lưu lý thuyết của bể:
        $$t_0 = \frac{100.0\text{ phút}}{0.70} = 142.857\text{ phút} \approx 142.9\text{ phút} \quad (2.381\text{ giờ} = 8,571.4\text{ giây})$$
      - Thể tích nước công tác yêu cầu:
        $$V = Q_{\text{min}} \times t_0 = 12.7778\text{ m}^3/\text{phút} \times 142.857\text{ phút} = 1,825.40\text{ m}^3$$
  - **Bước 3**: Tính diện tích mặt bằng xây dựng và tổng chiều sâu thành bể.
    - Căn cứ: Chiều sâu cột nước công tác $H = 3.00\text{ m}$ và khoảng lưu không mặt thoáng $h_{\text{fb}} = 0.50\text{ m}$.
    - Nhìn vào: Thể tích hữu ích $V = 1,825.40\text{ m}^3$ tính được ở Bước 2.
    - Thực hiện:
      - Diện tích mặt bằng lắng yêu cầu:
        $$A_s = \frac{V}{H} = \frac{1,825.40\text{ m}^3}{3.00\text{ m}} = 608.47\text{ m}^2$$
      - Chiều sâu toàn bộ thành bể bao gồm lưu không:
        $$H_{\text{total}} = H + h_{\text{fb}} = 3.00\text{ m} + 0.50\text{ m} = 3.50\text{ m}$$
  - **Bước 4**: Bố trí hình học kênh uốn lượn ziczac và kiểm tra tỷ số aspect ratio.
    - Căn cứ: Tiêu chuẩn dòng chảy piston triệt tiêu ngắn mạch $L_{\text{path}}/W_c \ge 40:1$ (Slide 33), chiều rộng kênh lựa chọn $W_c = 2.50\text{ m}$ và số lượng kênh song song $N_c = 6$.
    - Nhìn vào: Diện tích mặt bằng $A_s = 608.47\text{ m}^2$ tính được ở Bước 3.
    - Thực hiện:
      - Tổng chiều dài dòng chảy qua các kênh uốn khúc:
        $$L_{\text{path}} = \frac{A_s}{W_c} = \frac{608.47\text{ m}^2}{2.50\text{ m}} = 243.39\text{ m} \approx 243.4\text{ m}$$
      - Kiểm tra tỷ số hình học chiều dài / chiều rộng kênh (aspect ratio):
        $$\frac{L_{\text{path}}}{W_c} = \frac{243.39\text{ m}}{2.50\text{ m}} = 97.36 \ge 40 \quad (\text{đạt chuẩn cấp Superior})$$
      - Chiều dài thông thủy của mỗi nhánh kênh ($N_c = 6$):
        $$L_c = \frac{L_{\text{path}}}{N_c} = \frac{243.39\text{ m}}{6} = 40.565\text{ m} \approx 40.60\text{ m}$$
      - Chiều rộng phủ bì tổng thể bể (gồm 6 kênh rộng $2.50\text{ m}$ và 5 vách ngăn dày $0.20\text{ m}$):
        $$W_{\text{basin}} = (6 \times 2.50\text{ m}) + (5 \times 0.20\text{ m}) = 15.00\text{ m} + 1.00\text{ m} = 16.00\text{ m}$$
      - Kích thước mặt bằng phủ bì trong lòng bể: Chiều dài $L = 40.60\text{ m}$, Chiều rộng $W = 16.00\text{ m}$, Chiều sâu $H_{\text{total}} = 3.50\text{ m}$.
  - **Bước 5**: Kiểm tra chế độ thủy lực và vận tốc dòng chảy ngang.
    - Căn cứ: Công thức vận tốc ngang trung bình $v_h = Q/A_x$, bán kính thủy lực $R_h$, chuẩn số Reynolds $Re$ và chuẩn số Froude $Fr$.
    - Nhìn vào: Kích thước mặt cắt kênh $W_c = 2.50\text{ m}$, $H = 3.00\text{ m}$, lưu lượng $Q_{\text{sec}} = 0.21296\text{ m}^3/\text{s}$ và độ nhớt động học $\nu = 1.004 \times 10^{-6}\text{ m}^2/\text{s}$.
    - Thực hiện:
      - Diện tích mặt cắt ướt:
        $$A_x = W_c \cdot H = 2.50\text{ m} \times 3.00\text{ m} = 7.50\text{ m}^2$$
      - Vận tốc dòng chảy ngang trung bình:
        $$v_h = \frac{Q_{\text{sec}}}{A_x} = \frac{0.21296\text{ m}^3/\text{s}}{7.50\text{ m}^2} = 0.02840\text{ m/s} = 2.84\text{ cm/s} \quad (1.70\text{ m/phút})$$
      - Chu vi ướt của mặt cắt:
        $$P = W_c + 2H = 2.50\text{ m} + 2(3.00\text{ m}) = 8.50\text{ m}$$
      - Bán kính thủy lực:
        $$R_h = \frac{A_x}{P} = \frac{7.50\text{ m}^2}{8.50\text{ m}} = 0.8824\text{ m}$$
      - Đường kính thủy lực tương đương: $D_h = 4 R_h = 4 \times 0.8824 = 3.5294\text{ m}$.
      - Chuẩn số Reynolds:
        $$Re = \frac{v_h \cdot 4 R_h}{\nu} = \frac{0.02840 \times 3.5294}{1.004 \times 10^{-6}} = \frac{0.10025}{1.004 \times 10^{-6}} = 99,850$$
        Đánh giá: $Re = 99,850 > 10,000$, dòng chảy đạt trạng thái chảy rối hoàn toàn (fully turbulent), giúp khuấy trộn đồng đều nồng độ hóa chất và ngăn ngừa hình thành các góc đọng chết.
      - Chuẩn số Froude định nghĩa:
        $$Fr = \frac{v_h^2}{g \cdot R_h} = \frac{(0.02840)^2}{9.81 \times 0.8824} = \frac{0.0008066}{8.656} = 9.32 \times 10^{-5} \ll 1$$
        Đánh giá: $Fr \ll 1$, dòng chảy êm dưới tới hạn (subcritical flow), bảo đảm mặt nước phẳng lặng ổn định không gây dao động cột áp.
  - **Bước 6**: Tính toán tổn thất cột áp thủy lực toàn phần qua bể tiếp xúc.
    - Căn cứ: Công thức độ dốc ma sát Manning ($n = 0.013$) và tổn thất cục bộ tại $5$ góc quay 180° ($K_b = 2.5$).
    - Nhìn vào: Chiều dài tim dòng $L_{\text{path}} = 243.4\text{ m}$, vận tốc $v_h = 0.02840\text{ m/s}$, bán kính $R_h = 0.8824\text{ m}$.
    - Thực hiện:
      - Tổn thất ma sát dọc các kênh:
        $$h_f = L_{\text{path}} \left[ \frac{n \cdot v_h}{R_h^{2/3}} \right]^2 = 243.4 \times \left[ \frac{0.013 \times 0.02840}{(0.8824)^{2/3}} \right]^2 = 243.4 \times \left[ \frac{0.0003692}{0.9198} \right]^2$$
        $$h_f = 243.4 \times (4.0139 \times 10^{-4})^2 = 243.4 \times 1.611 \times 10^{-7} = 3.92 \times 10^{-5}\text{ m} \approx 0.04\text{ mm}$$
      - Tổn thất cục bộ tại 5 khúc quay 180° ($N_{\text{baffles}} = 5$ góc uốn):
        $$h_m = 5 \times K_b \times \frac{v_h^2}{2g} = 5 \times 2.5 \times \frac{(0.02840)^2}{2 \times 9.81} = 12.5 \times \frac{0.0008066}{19.62} = 5.14 \times 10^{-4}\text{ m} \approx 0.51\text{ mm}$$
      - Tổng tổn thất áp lực thủy lực toàn bể:
        $$h_L = h_f + h_m = 0.04\text{ mm} + 0.51\text{ mm} = 0.55\text{ mm} \approx 0.001\text{ m}$$
- **Kết quả**:
  - Thời gian lưu lý thuyết: $t_0 = 142.9\text{ phút}$ ($2.38\text{ giờ} = 8,571\text{ giây}$).
  - Thể tích nước hữu ích công tác: $V = 1,825.4\text{ m}^3$.
  - Diện tích mặt bằng lắng: $A_s = 608.5\text{ m}^2$.
  - Kích thước phủ bì lòng bể: Dài $L = 40.60\text{ m}$, Rộng $W = 16.00\text{ m}$, Chiều sâu tổng $H_{\text{total}} = 3.50\text{ m}$ (mực nước $3.00\text{ m}$, freeboard $0.50\text{ m}$).
  - Cấu tạo vách ngăn: $6$ nhánh kênh uốn khúc song song, bề rộng kênh $W_c = 2.50\text{ m}$, $5$ vách ngăn dày $0.20\text{ m}$.
  - Tổng chiều dài hành trình dòng chảy: $L_{\text{path}} = 243.4\text{ m}$ (tỷ số $L_{\text{path}}/W_c = 97.4 \ge 40$).
  - Đặc tính thủy lực: Vận tốc ngang $v_h = 0.0284\text{ m/s}$ ($2.84\text{ cm/s}$), chuẩn số $Re = 99,850$, chuẩn số $Fr = 9.32 \times 10^{-5}$.
  - Tổng tổn thất áp lực thủy lực: $h_L = 0.55\text{ mm} \approx 0.001\text{ m}$ (tổn thất cực nhỏ, thuận tiện vận hành tự chảy).
- **Kiểm tra lại**:
  - Kiểm tra tiêu chuẩn khử trùng USEPA SWTR: Tích số khử trùng $CT = C \cdot t_{10} = 2.0\text{ mg/L} \times 100.0\text{ phút} = 200.0\text{ mg}\cdot\text{min/L}$, bảo đảm đạt mức bất hoạt quy chuẩn $\ge 3\text{-log}$ đối với u nang *Giardia lamblia* và $\ge 4\text{-log}$ đối với virus đường ruột ở nhiệt độ nước $10 - 20^\circ\text{C}$ và $\text{pH} \le 7.5$.
  - Kiểm tra điều kiện dòng chảy piston (Plug Flow): Hệ số vách ngăn $\text{BF} = 0.70$ tương ứng với chỉ số phân tán Morrill $\text{MDI} = t_{90}/t_{10} \le 2.0$ và hệ số phân tán không thứ nguyên $d = \frac{D}{uL} \in [0.005; 0.03]$, chứng minh dòng chảy trong bể đạt mức độ gần sát dòng chảy piston lý tưởng, ngăn chặn triệt để hiện tượng đoản mạch vi sinh vật.
  - Kiểm tra bảo toàn thể tích hình học: $6 \times 40.565\text{ m} \times 2.50\text{ m} \times 3.00\text{ m} = 1,825.4\text{ m}^3 = V$, sai số tính toán $0.000\%$.

## Chương 8: Xử lý Nước Nâng cao (Advanced Treatment)


### 8.1 Hệ thống xử lý nước uống đóng chai đóng bình (Bottled Drinking Water Treatment System)

#### 8.1.1 Dây chuyền công nghệ xử lý nước uống đóng chai đóng bình (Bottled Drinking Water Treatment Process)

* Mục tiêu và tiêu chuẩn chất lượng của hệ thống xử lý nước uống đóng chai đóng bình:
  * Quy trình công nghệ phải loại bỏ triệt để độ đục, cặn lơ lửng, hợp chất hữu cơ, clo dư, kim loại nặng hòa tan và vi sinh vật gây bệnh.
  * Chất lượng nước thành phẩm sau xử lý phải tuân thủ nghiêm ngặt Quy chuẩn kỹ thuật quốc gia đối với nước khoáng thiên nhiên và nước uống đóng chai (QCVN 6-1:2010/BYT).
  * Dây chuyền sản xuất tích hợp hệ thống đa rào cản (multi-barrier system) kết hợp giữa các quá trình lọc cơ học, hấp phụ hóa lý, phân tách màng bán thấm và khử trùng vật lý.

* Cụm bơm cấp và xử lý cơ học sơ bộ bằng cột lọc cát áp lực (Sand Filter):
  * Bơm cấp nguồn (Feed pump) hút nước từ bồn chứa thô hoặc mạng lưới cấp nước đô thị để tạo áp lực làm việc ban đầu từ $2.5\text{ bar}$ đến $4.0\text{ bar}$ ($2.5\text{--}4.0\text{ bar}$) đẩy qua cụm tiền xử lý.
  * Cột lọc cát áp lực số 1 (Sand Filter) sử dụng vỏ composite FRP hoặc inox 304 chứa vật liệu lọc cát thạch anh phân cấp (graded quartz sand, $d_{10} = 0.5\text{--}0.8\text{ mm}$, hệ số đồng nhất $UC < 1.5$) trên lớp sỏi đỡ.
  * Thiết bị lọc cát giữ lại các hạt cặn lơ lửng thô, đất cát, phù sa và bùn rỉ sét có kích thước hạt $\ge 10\text{--}20\text{ }\mu\text{m}$.
  * Quá trình lọc cát làm giảm độ đục của nước nguồn từ $5\text{--}10\text{ NTU}$ xuống dưới ngưỡng an toàn $< 1.0\text{ NTU}$ trước khi chuyển sang công đoạn lọc hấp phụ.

* Cụm lọc than hoạt tính hấp phụ (Active Carbon Filter):
  * Cột lọc than số 2 (Active Carbon Filter) chứa lớp vật liệu than hoạt tính gáo dừa dạng hạt (granular activated carbon - GAC) có chỉ số iod cao ($\text{Iodine Number} \ge 900\text{--}1050\text{ mg/g}$).
  * Cơ chế loại bỏ clo dư tự do ($\text{Cl}_2, \text{HOCl}, \text{OCl}^-$) diễn ra thông qua phản ứng oxy hóa khử xúc tác trên bề mặt cacbon hoạt tính:
    $$\text{C}^* + 2\text{HOCl} \rightarrow \text{CO}_2 + 2\text{H}^+ + 2\text{Cl}^-$$
  * Nồng độ clo dư được khử triệt để xuống dưới mức $< 0.05\text{ mg/L}$ nhằm ngăn ngừa hiện tượng oxy hóa phá hủy màng thẩm thấu ngược (RO) phía sau.
  * Than hoạt tính đồng thời hấp phụ các hợp chất hữu cơ dễ bay hơi (VOCs), phụ phẩm khử trùng trihalomethanes (THMs), thuốc bảo vệ thực vật, và các chất gây mùi vị lạ (geosmin, 2-MIB).

* Cụm làm mềm nước khử ion cứng (Water Softener):
  * Cột số 3 (Water Softener) sử dụng hạt nhựa trao đổi cation acid mạnh (SAC resin) ở dạng natri ($\text{R-Na}^+$) với dung lượng trao đổi ẩm đạt $1.8\text{--}2.0\text{ eq/L}$.
  * Phản ứng trao đổi ion loại bỏ các cation gây độ cứng canxi ($\text{Ca}^{2+}$) và magie ($\text{Mg}^{2+}$):
    $$\text{Ca}^{2+} + 2\text{R-Na} \rightarrow \text{R}_2\text{-Ca} + 2\text{Na}^+$$
    $$\text{Mg}^{2+} + 2\text{R-Na} \rightarrow \text{R}_2\text{-Mg} + 2\text{Na}^+$$
  * Độ cứng tổng của nước cấp sau làm mềm giảm xuống $< 5\text{--}10\text{ mg/L CaCO}_3$.
  * Quá trình làm mềm ngăn ngừa nguy cơ kết tủa quá bão hòa các muối canxi cacbonat ($\text{CaCO}_3$) và canxi sunfat ($\text{CaSO}_4$) gây tắc nghẽn màng thẩm thấu ngược RO.
  * Hạt nhựa cation được hoàn nguyên định kỳ bằng dung dịch muối ăn tinh khiết ($\text{NaCl}$) bão hòa với nồng độ $8\text{--}10\%$.

* Cụm lọc vi lọc tinh an toàn (Cartridge Microfiltration Unit):
  * Cụm lọc bảo vệ đặt ngay trước bơm cao áp RO gồm cốc lọc $20\text{ inch}$ và bộ lọc lõi $0.2\text{ }\mu\text{m}$ (micron filter).
  * Lõi lọc bông ép polypropylene $20\text{ inch}$ ($5\text{ }\mu\text{m}$) thu giữ các mạt than và hạt nhựa trao đổi ion rò rỉ từ các cột tiền xử lý.
  * Lõi lọc tinh $0.2\text{ }\mu\text{m}$ giữ lại các vi hạt huyền phù mịn và bào tử nấm, bảo vệ cánh bơm cao áp không bị mài mòn cơ học.
  * Bộ lọc tinh đảm bảo chỉ số mật độ bùn của nước cấp màng RO đạt yêu cầu kỹ thuật nghiêm ngặt ($\text{SDI}_{15} < 3.0$).

* Cụm màng phân tách thẩm thấu ngược (Reverse Osmosis Unit - RO):
  * Bơm cao áp (High Pressure Pump) tạo áp lực thủy lực lớn từ $10\text{ bar}$ đến $16\text{ bar}$ ($10\text{--}16\text{ bar}$) để thắng áp suất thẩm thấu tự nhiên của dung dịch muối khoáng.
  * Màng RO màng mỏng composite (Thin-film composite - TFC) cấu tạo từ polyamide cuộn xoắn ốc với kích thước lỗ lọc danh định $0.0001\text{ }\mu\text{m}$ ($0.1\text{ nm}$).
  * Hiệu suất ngăn giữ tổng chất rắn hòa tan ($\text{TDS rejection}$) của màng đạt $\ge 98.5\text{--}99.5\%$, loại bỏ triệt để ion kim loại nặng ($\text{As}, \text{Pb}, \text{Cd}, \text{Hg}$), muối hòa tan, vi khuẩn và vi rút.
  * Tỷ lệ thu hồi nước thấm tinh khiết ($Y$) của hệ thống RO được điều chỉnh trong khoảng từ $60\%$ đến $75\%$ ($60\text{--}75\%$):
    $$Y = \frac{Q_{\text{permeate}}}{Q_{\text{feed}}} \times 100\%$$
  * Dòng cô đặc (brine/concentrate) mang toàn bộ tạp chất khoáng xả thải ra ngoài hoặc được tái sử dụng một phần cho mục đích vệ sinh thứ cấp.

* Bồn chứa nước tinh khiết trung gian (Storage Tank) và công tắc phao (Floating Switch):
  * Bồn chứa chế tạo từ thép không gỉ thực phẩm SUS 304 hoặc SUS 316L lưu trữ dòng nước tinh khiết sau khi qua màng RO.
  * Công tắc phao mức nước (Floating Switch) gắn bên trong bồn liên động với mạch điều khiển tự động của bơm cấp và bơm RO:
    * Khi mực nước đạt ngưỡng cao nhất (High Level), phao ngắt tín hiệu để dừng bơm cao áp RO và đóng van điện từ đầu vào nhằm tránh tràn bồn.
    * Khi mực nước hạ xuống ngưỡng cho phép (Low Level), phao kích hoạt hệ thống vận hành trở lại để duy trì lượng nước cấp liên tục.
  * Bồn được trang bị van thở gắn màng lọc khí vi sinh vô trùng $0.2\text{ }\mu\text{m}$ để ngăn chặn vi sinh vật và bụi bẩn trong không khí xâm nhập.

* Cụm bơm trung chuyển và khử trùng tia cực tím (Transfer Pump & UV Sterilizer):
  * Bơm chuyển tiếp (Transfer Pump) hút nước từ bồn chứa trung gian đẩy qua bộ đèn khử trùng tia cực tím (UV Sterilizer) đến khu vực đóng chai.
  * Đèn cực tím phát bức xạ bước sóng diệt khuẩn $\lambda = 254\text{ nm}$ (UV-C) với liều lượng chiếu xạ đạt $\ge 30\text{--}40\text{ mJ/cm}^2$.
  * Tia cực tím xuyên qua màng tế bào vi khuẩn, bẻ gãy liên kết hydro và gây đứt gãy cấu trúc DNA/RNA thông qua phản ứng nhị hợp pyrimidine:
    * Quá trình ngăn chặn triệt để khả năng tái sinh và nhân đôi của vi sinh vật.
    * Phương pháp không sinh ra phụ phẩm khử trùng độc hại và giữ nguyên vị ngọt thanh khiết tự nhiên của nước uống.

* Dây chuyền chiết rót và đóng nắp chai tự động (Filling Line):
  * Dây chuyền chiết rót (Filling Line) được đặt trong phòng sạch kiểm soát vi sinh áp suất dương với hệ thống lọc không khí hiệu năng cao (HEPA H14).
  * Quy trình thực hiện tự động hóa hoàn toàn theo chu trình khép kín: súc rửa chai vô trùng bằng nước tinh khiết khử trùng, chiết rót thể tích đẳng áp, và đóng siết nắp kín vô trùng.
  * Nước đóng chai hoặc đóng bình ($19\text{--}20\text{ L}$) sau chiết rót được dán nhãn, soi dị vật bằng đèn kiểm phẩm và lưu kho thành phẩm theo tiêu chuẩn an toàn thực phẩm.

#### 8.1.2 Hệ thống xử lý nước tinh khiết khử khoáng bằng trao đổi ion (Purified Water Treatment System by Ion Exchange)

* Khái niệm và mục đích của quy trình khử khoáng demineralisation:
  * Nước tinh khiết và siêu tinh khiết (Demineralised water / Pure water) là yêu cầu kỹ thuật bắt buộc trong các ngành công nghiệp nồi hơi áp lực cao, phòng thí nghiệm phân tích, sản xuất dược phẩm và linh kiện vi điện tử.
  * Quá trình khử khoáng (demineralisation / deionisation) loại bỏ triệt để toàn bộ các ion vô cơ hòa tan trong nước bằng các hạt nhựa polymer trao đổi ion.
  * Tiêu chuẩn độ dẫn điện (electrical conductivity) của nước khử khoáng đạt từ $0.1\text{ }\mu\text{S/cm}$ đến $0.2\text{ }\mu\text{S/cm}$ ($0.1\text{--}0.2\text{ }\mu\text{S/cm}$), tương đương điện trở suất từ $5\text{ M}\Omega\cdot\text{cm}$ đến $10\text{ M}\Omega\cdot\text{cm}$ ($5\text{--}10\text{ M}\Omega\cdot\text{cm}$).

* Cấu tạo và cơ chế phân tách của tháp trao đổi Cation (Cation Exchanger):
  * Tháp Cation chứa hạt nhựa polystyrene sulfo hóa dạng hạt gel acid mạnh (SAC resin) mang nhóm chức năng $-\text{SO}_3\text{H}$ ở dạng hydronium ($\text{R-H}^+$).
  * Hạt nhựa thu hút và giữ lại toàn bộ các cation kim loại có trong nước cấp ($\text{Ca}^{2+}, \text{Mg}^{2+}, \text{Na}^+, \text{K}^+, \text{Fe}^{2+}, \text{Fe}^{3+}$) và giải phóng ion $\text{H}^+$ tương đương:
    $$\text{M}^{n+} + n\text{R-H} \rightleftharpoons \text{R}_n\text{-M} + n\text{H}^+$$
  * Nước rời khỏi tháp Cation có tính axit mạnh ($\text{pH} \approx 2.0\text{--}3.0$) do chứa hỗn hợp các axit vô cơ tự do gồm axit clohydric ($\text{HCl}$), axit sunfuric ($\text{H}_2\text{SO}_4$) và axit cacbonic ($\text{H}_2\text{CO}_3$).

* Cấu tạo và cơ chế phân tách của tháp trao đổi Anion (Anion Exchanger):
  * Tháp Anion chứa hạt nhựa bazo mạnh loại I hoặc loại II (SBA resin) mang nhóm amoni bậc bốn $-\text{N}^+(\text{CH}_3)_3\text{OH}^-$ ở dạng hydroxyl ($\text{R-OH}^-$).
  * Hạt nhựa hấp phụ toàn bộ các anion gốc axit mạnh và axit yếu ($\text{Cl}^-, \text{SO}_4^{2-}, \text{NO}_3^-, \text{HCO}_3^-, \text{SiO}_3^{2-}$) và giải phóng ion $\text{OH}^-$ vào dòng nước:
    $$\text{A}^{m-} + m\text{R-OH} \rightleftharpoons \text{R}_m\text{-A} + m\text{OH}^-$$
  * Các ion $\text{H}^+$ từ tháp Cation và ion $\text{OH}^-$ từ tháp Anion kết hợp tức thời tạo thành phân tử nước trung hòa:
    $$\text{H}^+ + \text{OH}^- \rightarrow \text{H}_2\text{O}$$
  * Nước sau tháp Anion chảy vào bồn chứa trung gian đạt độ dẫn điện $\approx 1\text{ }\mu\text{S/cm}$ (điện trở suất $\approx 1\text{ M}\Omega\cdot\text{cm}$).

* Cột trao đổi hỗn hợp đánh bóng sâu (Mixed Bed Exchanger):
  * Cột Mixed Bed Exchanger chứa hỗn hợp đồng nhất giữa hạt nhựa Cation acid mạnh ($\text{H}^+$) và hạt nhựa Anion bazo mạnh ($\text{OH}^-$) trộn đều theo tỷ lệ thể tích chuẩn từ $1:1.5$ đến $1:2.0$.
  * Tầng hạt hỗn hợp hoạt động tương đương chuỗi vô số cặp cột Cation - Anion siêu nhỏ mắc nối tiếp nhau liên tục:
    * Mỗi phản ứng trao đổi ion lập tức được trung hòa thành $\text{H}_2\text{O}$, dịch chuyển cân bằng nhiệt động học về phía khử ion triệt để.
    * Tách hoàn toàn các vết muối rò rỉ (ion $\text{Na}^+$ và axit silicic $\text{H}_2\text{SiO}_3$).
  * Chất lượng nước khử khoáng thành phẩm (Demineralised water) đạt độ dẫn điện cực thấp từ $0.1\text{ }\mu\text{S/cm}$ đến $0.2\text{ }\mu\text{S/cm}$ ($0.1\text{--}0.2\text{ }\mu\text{S/cm}$) và điện trở suất đạt từ $5\text{ M}\Omega\cdot\text{cm}$ đến $10\text{ M}\Omega\cdot\text{cm}$ ($5\text{--}10\text{ M}\Omega\cdot\text{cm}$).

* Sơ đồ dây chuyền khử khoáng công nghiệp thể hiện đầy đủ các cụm thiết bị từ cấp nước thô đến nước thành phẩm:
  - **Hình 1.** Sơ đồ công nghệ hệ thống xử lý nước tinh khiết và khử khoáng công nghiệp (Purified Water Treatment System)
    - <img src="ch08_advanced_treatment/assets/fig_01_p2.jpeg" alt="Hình 1" />
    - **Hình này chứng minh điều gì**
      - Sơ đồ xác lập dây chuyền khử khoáng demineralisation 2 giai đoạn: cụm cột đôi Cation Exchanger - Anion Exchanger tạo nước trung gian $\approx 1\text{ }\mu\text{S/cm}$, nối tiếp cột Mixed Bed Exchanger tinh chế nước đạt độ dẫn điện $0.1\text{--}0.2\text{ }\mu\text{S/cm}$ ($5\text{--}10\text{ M}\Omega\cdot\text{cm}$).
    - **Từ đâu mà thấy được**
      - Nhánh trên từ trái qua phải: bể Water Storage $\rightarrow$ Filters $\rightarrow$ Cation Exchanger $\rightarrow$ Anion Exchanger $\rightarrow$ bồn chứa trung gian ghi nhãn $\sim 1\text{ }\mu\text{S/cm}$ ($\sim 1\text{ Mohms/cm}^2$).
      - Cột Mixed Bed Exchanger nhận nước qua Service Water Pump và xả Demineralised Water ở mức $0,1\text{ to }0,2\text{ }\mu\text{S/cm}$ ($5\text{ to }10\text{ Mohms/cm}^2$).

#### 8.1.3 Hệ thống xử lý và tuần hoàn nước hồ bơi (Water Treatment System for Swimming Pool)

* Đặc tính ô nhiễm và nguyên lý thủy lực tuần hoàn nước hồ bơi:
  * Nước hồ bơi tiếp nhận liên tục các chất bài tiết từ người bơi (mồ hôi, nước tiểu, tế bào da chết, tóc), hóa chất mỹ phẩm và vi sinh vật gây bệnh (*Staphylococcus aureus*, *Pseudomonas aeruginosa*).
  * Hệ thống vận hành theo nguyên lý tuần hoàn cưỡng bức khép kín liên tục (closed-loop recirculation).
  * Chu kỳ chu chuyển toàn bộ thể tích nước trong bể (Turnover time $t_{\text{turnover}}$) quy định trong khoảng từ $4\text{ giờ}$ đến $6\text{ giờ}$ ($4\text{--}6\text{ h}$):
    $$t_{\text{turnover}} = \frac{V_{\text{pool}}}{Q_{\text{recirc}}} \le 4.0\text{--}6.0\text{ h}$$
    Trong đó $V_{\text{pool}}$ là dung tích hồ bơi ($\text{m}^3$) và $Q_{\text{recirc}}$ là lưu lượng bơm tuần hoàn ($\text{m}^3\text{/h}$).

* Hệ thống thu gom nước mặt và nước đáy hồ:
  * Cửa thu nước mặt Skimmer (vị trí 12):
    * Đặt ngang mép nước thành hồ, thu gom từ $60\%$ đến $80\%$ ($60\text{--}80\%$) tổng lưu lượng tuần hoàn.
    * Hút váng dầu mỡ, bọt bẩn, bụi bẩn nổi và các chất kỵ nước tập trung ở lớp vi bề mặt sâu $0\text{--}15\text{ cm}$.
  * Phễu thu nước đáy Main Drain (vị trí 14):
    * Bố trí tại vị trí sâu nhất ở đáy hồ với nắp chống xoáy xoáy lốc an toàn (anti-vortex cover).
    * Thu gom từ $20\%$ đến $40\%$ ($20\text{--}40\%$) lưu lượng tuần hoàn, hút các hạt cặn nặng lắng đọng và hỗ trợ khuấy đảo đồng đều nhiệt độ hồ bơi.
  * Họng hút vệ sinh Vacuum Line (vị trí 15):
    * Kết nối đường ống mềm gắn bàn hút cặn đáy cầm tay để làm sạch định kỳ rong rêu và bùn đáy hồ.

* Trạm bơm tuần hoàn và bình lọc áp lực cát thạch anh:
  * Bơm tuần hoàn chuyên dụng (vị trí 7): trang bị giỏ tiền lọc rác thô (hair and lint strainer) để giữ lại tóc và rác lớn trước khi nước vào cánh bơm.
  * Bình lọc cát áp lực cao tốc (vị trí 2):
    * Vỏ bình đúc bằng sợi thủy tinh composite chịu ăn mòn hóa chất và áp suất vận hành $2.0\text{--}3.5\text{ bar}$.
    * Lớp vật liệu lọc cát thạch anh phân cấp dày $0.6\text{--}1.0\text{ m}$ với tốc độ lọc bề mặt đạt từ $20\text{ m/h}$ đến $35\text{ m/h}$ ($20\text{--}35\text{ m/h}$).
    * Loại bỏ các hạt cặn lơ lửng, huyền phù kích thước $\ge 15\text{--}20\text{ }\mu\text{m}$, đưa độ đục về mức $< 0.5\text{ NTU}$.
  * Van điều khiển đa cổng (Multi-port valve - vị trí 1 và 9):
    * Gắn trên đỉnh hoặc thân bình lọc để vận hành linh hoạt 6 chế độ: Lọc (Filter), Rửa ngược (Backwash), Rửa xuôi định hình (Rinse), Xả đáy bỏ (Waste), Tuần hoàn không qua lọc (Recirculate), Đóng ngắt (Closed).
    * Rửa ngược định kỳ khi chênh lệch áp suất lọc tăng vượt ngưỡng $\Delta P \ge 0.5\text{--}0.7\text{ bar}$ so với áp ban đầu.

* Cụm định lượng hóa chất, điều chỉnh pH và khử trùng nước:
  * Thiết bị châm hóa chất khử trùng (vị trí 26):
    * Sử dụng bộ châm clo viên tan chậm (TCCA) hoặc bơm định lượng châm dung dịch natri hypoclorit ($\text{NaOCl}$).
    * Clo tự do hòa tan tạo thành axit hipocloro ($\text{HOCl}$) có hoạt tính diệt khuẩn cực mạnh:
      $$\text{Cl}_2 + \text{H}_2\text{O} \rightleftharpoons \text{HOCl} + \text{H}^+ + \text{Cl}^-$$
      $$\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^- \quad (\text{p}K_a = 7.54 \text{ tại } 25^\circ\text{C})$$
    * Nồng độ clo dư tự do (Free Residual Chlorine) phải luôn duy trì ổn định trong khoảng từ $1.0\text{ mg/L}$ đến $3.0\text{ mg/L}$ ($1.0\text{--}3.0\text{ mg/L}$).
  * Điều chỉnh cân bằng $\text{pH}$ hồ bơi:
    * Giữ $\text{pH}$ tối ưu trong khoảng hẹp từ $7.2$ đến $7.6$ ($7.2\text{--}7.6$) để bảo đảm tỷ lệ $\text{HOCl}$ hoạt tính chiếm $> 50\text{--}70\%$, chống kích ứng mắt và niêm mạc người bơi.
    * Châm axit ($\text{HCl}$ hoặc $\text{NaHSO}_4$) khi $\text{pH} > 7.6$; châm bazơ ($\text{Na}_2\text{CO}_3$) khi $\text{pH} < 7.2$.

* Cụm kiểm soát nhiệt độ, điều khiển và mạng lưới vòi phun trả nước:
  * Bộ gia nhiệt (Heater / Heat exchanger - vị trí 19 và 6): cấp nhiệt bổ sung để duy trì nhiệt độ nước tiện nghi từ $26^\circ\text{C}$ đến $28^\circ\text{C}$ ($26\text{--}28^\circ\text{C}$).
  * Tủ điều khiển điện tử (Control panel - vị trí 13): tự động kiểm soát chu kỳ vận hành bơm, đo đếm thế oxy hóa khử ($\text{ORP} \ge 700\text{ mV}$) và đóng ngắt hệ thống gia nhiệt.
  * Hộp điều khiển mực nước tự động (vị trí 31): tự động cấp nước sạch bù đắp lượng nước bốc hơi và tổn thất rửa lọc.
  * Các đầu phun trả nước (Return jets / Inlets - vị trí 11 và 16): bố trí dọc thành hồ đối diện skimmer để tạo dòng thủy lực tuần hoàn đều khắp thể tích hồ.
  * Đèn chiếu sáng âm nước (Underwater lights - vị trí 23): cung cấp ánh sáng an toàn ban đêm.

* Sơ đồ cấu tạo không gian tổng thể hệ thống tuần hoàn nước hồ bơi:
  - **Hình 2.** Cấu tạo và sơ đồ tuần hoàn xử lý nước hồ bơi (Water Treatment System for Swimming Pool)
    - <img src="ch08_advanced_treatment/assets/fig_02_p2.jpeg" alt="Hình 2" />
    - **Hình này chứng minh điều gì**
      - Minh họa sơ đồ tuần hoàn khép kín gồm hệ thu nước mặt skimmer (12), hút đáy main drain (14), bơm tuần hoàn (7), bình lọc cát đa tầng (2), van điều khiển đa hướng (1, 9), cụm châm hóa chất (26) và đầu phun trả nước sạch (11, 16).
    - **Từ đâu mà thấy được**
      - Nhìn vào thành hồ và đáy hồ: các họng skimmer (12) bố trí ngang mép nước, lỗ thoát đáy (14) ở lòng sâu nhất kết nối đường ống về bơm (7).
      - Cụm phòng kỹ thuật phía dưới: bơm tuần hoàn (7) đẩy nước qua bình lọc áp lực hình cầu (2) có van đỉnh (9), qua bộ châm hóa chất (26) trước khi quay về dàn ống màu đỏ cấp trả cho các vòi phun (11, 16).

#### 8.1.4 Quy trình tái sinh nhựa và xử lý dòng thải hoàn nguyên (Resin Regeneration & Waste Neutralisation in Demineralisation)

* Hiện tượng suy giảm dung lượng và sự cần thiết của chu trình hoàn nguyên nhựa:
  * Sau một chu kỳ lọc nước demineralisation, các nhóm chức năng trên hạt nhựa bị bão hòa hoàn toàn bởi các ion muối khoáng thu giữ từ nước nguồn.
  * Nồng độ ion xuyên thủng qua lớp hạt làm độ dẫn điện của dòng nước ra tăng đột biến, đòi hỏi phải dừng tháp để thực hiện chu trình tái sinh hóa chất (chemical regeneration).
  * Chu trình tái sinh hoàn trả hạt nhựa trở về trạng thái hoạt tính ban đầu ($\text{R-H}^+$ đối với cation và $\text{R-OH}^-$ đối với anion).

* Các bước vận hành của chu trình tái sinh tháp Cation và Anion:
  * Giai đoạn 1 - Rửa ngược (Backwash flow):
    * Cấp dòng nước từ đáy cột lên trên với lưu lượng làm giãn nở tầng nhựa từ $40\%$ đến $50\%$ ($40\text{--}50\%$).
    * Loại bỏ toàn bộ cặn lơ lửng, hạt vỡ bám dính cơ học trên bề mặt hạt nhựa và tái sắp xếp phân tầng kích thước hạt.
  * Giai đoạn 2 - Bơm dung dịch hóa chất hoàn nguyên (Chemical injection):
    * Tháp Cation: Bơm dung dịch axit clohydric ($\text{HCl}$) nồng độ $4\text{--}8\%$ từ bồn Storage HCl qua bồn Break Tank vào tháp để thế chỗ các cation kim loại:
      $$\text{R}_n\text{-M} + n\text{H}^+ \rightarrow n\text{R-H} + \text{M}^{n+}$$
    * Tháp Anion: Bơm dung dịch natri hydroxit ($\text{NaOH}$) nồng độ $4\text{--}5\%$ từ bồn Storage NaOH (được gia nhiệt lên $35\text{--}40^\circ\text{C}$ để tăng cường khả năng rửa trôi axit silicic $\text{SiO}_2$) qua Break Tank vào tháp để thế chỗ các gốc anion:
      $$\text{R}_m\text{-A} + m\text{OH}^- \rightarrow m\text{R-OH} + \text{A}^{m-}$$
  * Giai đoạn 3 - Rửa chậm (Slow rinse / Displacement):
    * Đẩy dung dịch hóa chất còn đọng trong các khe rỗng hạt nhựa bằng nước khử khoáng ở cùng lưu lượng bơm hóa chất để kéo dài thời gian tiếp xúc phản ứng.
  * Giai đoạn 4 - Rửa nhanh (Fast rinse):
    * Xối rửa lớp hạt bằng nước cấp ở tốc độ làm việc danh định nhằm xả sạch triệt để lượng hóa chất hoàn nguyên dư thừa cho đến khi độ dẫn điện đạt tiêu chuẩn vận hành.

* Kỹ thuật phân tách và hoàn nguyên cột trao đổi hạt hỗn hợp Mixed Bed:
  * Tách lớp nhựa bằng thủy lực (hydraulic separation):
    * Dòng nước rửa ngược từ đáy đẩy hạt nhựa phân tầng rõ rệt nhờ sự chênh lệch khối lượng riêng:
      * Hạt nhựa Anion nhẹ hơn ($\rho \approx 1.08\text{--}1.10\text{ g/cm}^3$) nổi lên ở nửa trên của cột.
      * Hạt nhựa Cation nặng hơn ($\rho \approx 1.25\text{--}1.30\text{ g/cm}^3$) chìm xuống ở nửa dưới của cột.
  * Tái sinh hóa chất đồng thời qua hệ thống ống phân phối trung tâm:
    * Dung dịch kiềm $\text{NaOH}$ được châm từ đỉnh cột đi xuống qua tầng Anion và rút ra tại mặt phân giới giữa hai lớp nhựa.
    * Dung dịch axit $\text{HCl}$ được châm từ đáy cột đi lên qua tầng Cation và cùng rút ra tại mặt phân giới.
  * Xáo trộn đồng nhất hạt nhựa (air mixing):
    * Sau khi rửa sạch hóa chất dư, sục khí nén sạch không dầu từ đáy cột trong $10\text{--}15\text{ phút}$ để hòa trộn đều hai loại hạt nhựa trước khi đưa vào chu kỳ lọc tiếp theo.

* Hệ thống tháp rửa khí Scrubber và an toàn hóa chất:
  * Axit clohydric đậm đặc trong bồn chứa Storage HCl có áp suất hơi cao, liên tục bay hơi sinh ra khói axit $\text{HCl}$ ăn mòn mạnh và gây nguy hiểm cho người vận hành.
  * Tháp hấp thụ khí Scrubber (Scrubber Column) lắp đặt cạnh bồn axit thu gom toàn bộ hơi axit thoát ra:
    * Tháp chứa lớp đệm tiếp xúc rỗng (packing rings) với dòng dung dịch kiềm loãng tuần hoàn tưới từ đỉnh tháp xuống.
    * Phản ứng trung hòa hơi axit diễn ra tức thời:
      $$\text{HCl}_{\text{(khí)}} + \text{NaOH}_{\text{(dung dịch)}} \rightarrow \text{NaCl} + \text{H}_2\text{O}$$
    * Không khí sạch được xả an toàn ra ngoài môi trường.

* Bể trung hòa nước thải hoàn nguyên (Neutralisation Sump) và bơm khuấy trộn (Blending Pump):
  * Dòng nước thải hoàn nguyên tháp Cation có tính axit rất mạnh ($\text{pH} \le 1.5\text{--}2.0$) chứa nồng độ ion $\text{H}^+, \text{Ca}^{2+}, \text{Mg}^{2+}, \text{Cl}^-$ cao.
  * Dòng nước thải hoàn nguyên tháp Anion có tính kiềm rất mạnh ($\text{pH} \ge 12.0\text{--}12.5$) chứa nồng độ ion $\text{OH}^-, \text{SO}_4^{2-}, \text{SiO}_3^{2-}$ cao.
  * Cả hai dòng thải độc hại được dẫn về bể trung hòa tập trung (Neutralisation Sump).
  * Bơm tuần hoàn khuấy trộn (Blending pump) vận hành liên tục để hòa trộn đều hai dòng thải, kích hoạt phản ứng tự trung hòa giữa lượng axit và kiềm dư thừa:
    $$\text{H}^+ + \text{OH}^- \rightarrow \text{H}_2\text{O}$$
  * Hệ thống châm bổ sung hóa chất tự động kiểm soát giá trị $\text{pH}$ trong ngưỡng quy chuẩn xả thải môi trường ($6.5 \le \text{pH} \le 8.5$) trước khi xả ra nguồn tiếp nhận (Waste water).

* Sơ đồ chi tiết chu trình hoàn nguyên và trạm trung hòa nước thải:
  - **Hình 3.** Quy trình hoàn nguyên hóa chất và hệ thống xử lý nước thải trung hòa (Demineralised Water Regeneration and Neutralisation System)
    - <img src="ch08_advanced_treatment/assets/fig_03_p3.jpeg" alt="Hình 3" />
    - **Hình này chứng minh điều gì**
      - Thể hiện chi tiết mạng lưới cấp hóa chất tái sinh ($\text{HCl}$, $\text{NaOH}$) cho các tháp trao đổi ion, kết hợp tháp rửa khí Scrubber và bể Neutralisation Sump cùng bơm Blending Pump để trung hòa nước thải hoàn nguyên.
    - **Từ đâu mà thấy được**
      - Khu vực đáy bồn hóa chất: bồn Storage HCl và Storage NaOH nối với các bồn đệm Break Tank phân phối hóa chất tái sinh (đường màu xanh lục và đỏ) lên đỉnh/đáy các tháp trao đổi.
      - Phía bên phải: đường xả To Neutralisation Sump thu gom nước thải hoàn nguyên về bể Neutralisation Sump có bơm Blending Pump xả ra Waste Water; tháp Scrubber Column đặt cạnh bồn axit để xử lý khí thoát.

### 8.2 Hệ thống xử lý nước tinh khiết (Purified Water Treatment System)

#### 8.2.1 Sơ đồ chu trình công nghệ sản xuất nước khử khoáng và nước tinh khiết (Demineralised & Purified Water Process Train)

- Định nghĩa và tiêu chuẩn kỹ thuật của nước tinh khiết (Purified Water) và nước siêu tinh khiết (Ultrapure Water):
  - Nước tinh khiết (Demineralised / Deionised Water): Nước được tách bỏ gần như hoàn toàn các ion muối khoáng hòa tan, đạt độ dẫn điện $\kappa \le 0{,}1 - 0{,}2\ \mu\text{S/cm}$ tại $25^\circ\text{C}$ (điện trở suất $\rho \ge 5 - 10\ \text{M}\Omega\cdot\text{cm}$) và tổng chất rắn hòa tan $\text{TDS} < 1\ \text{mg/L}$.
  - Nước siêu tinh khiết (Ultrapure Water - UPW): Cấp nước có độ sạch cao nhất phục vụ ngành công nghiệp vi điện tử, bán dẫn và phòng thí nghiệm phân tích vi lượng, đạt điện trở suất giới hạn lý thuyết $\rho = 18{,}2\ \text{M}\Omega\cdot\text{cm}$ tại $25^\circ\text{C}$ ($\kappa = 0{,}055\ \mu\text{S/cm}$) và hàm lượng tổng cacbon hữu cơ $\text{TOC} < 1 - 2\ \text{ppb}$.
- Cấu trúc chuỗi dây chuyền công nghệ đa rào cản (Multi-Barrier Treatment Train):
  - Khối tiền xử lý hóa lý (Pretreatment Stage):
    - Khử trùng sơ cấp bằng clo hóa (Chlorination) kiểm soát sự phát triển của vi sinh vật và sinh vật bám từ nguồn nước cấp.
    - Quá trình keo tụ và tạo bông (Coagulation - Flocculation) kết hợp bể lắng trọng lực (Sedimentation) nhằm kết tụ và loại bỏ phần lớn cặn lơ lửng, chất hữu cơ thô và xả bùn đáy (Sludge disposal).
    - Cụm lọc đa tầng (Multi-media filtration) hoặc mô-đun màng siêu lọc (Ultrafiltration - UF, kích thước khe lọc $0{,}01 - 0{,}05\ \mu\text{m}$) nhằm hạ chỉ số mật độ bùn xuống mức an toàn $\text{SDI}_{15} < 3{,}0$.
    - Công đoạn khử clo dư (Dechlorination) bằng dung dịch natri bisulfit ($\text{NaHSO}_3$) để ngăn ngừa hiện tượng oxy hóa phân hủy lớp màng polyamide mỏng.
    - Châm hóa chất chống cáu cặn (Antiscalant) kết hợp thiết bị lọc tinh cartridge (Fine filtration, kích thước $1 - 5\ \mu\text{m}$) để ngăn ngừa kết tủa muối canxi sunfat ($CaSO_4$) và silica ($SiO_2$).
  - Khối phân tách màng thẩm thấu ngược áp lực cao (Reverse Osmosis Stage):
    - Bơm cao áp (High pressure pump, áp suất vận hành $55 - 70\ \text{bar}$ đối với nước biển hoặc $12 - 18\ \text{bar}$ đối với nước lợ) kết hợp thiết bị thu hồi năng lượng đẳng áp (Energy Recovery Device - ERD / PX) với hiệu suất thu hồi thế năng dòng brine đạt $\ge 96\%$.
    - Cụm màng thẩm thấu ngược sơ cấp (Seawater Reverse Osmosis - SWRO) phân tách dòng cấp thành dòng nước sạch thu hồi và dòng nước muối đậm đặc xả thải (Brine disposal).
    - Hệ thống súc rửa màng tại chỗ (Cleaning In Place - CIP) phục vụ tẩy rửa cáu cặn vô cơ và màng sinh học định kỳ.
  - Khối hậu xử lý và các công đoạn đánh bóng (Post-treatment & Polishing Steps):
    - Nhánh cấp nước sinh hoạt và tưới tiêu: Trải qua quá trình khử Bo (Boron removal process), tái khoáng hóa và trung hòa (Remineralization & Neutralisation), sau đó khử trùng (Disinfection) đạt chuẩn WHO ($\text{TDS} < 450\ \text{mg/L}$).
    - Nhánh cấp nước công nghệ (Process Water): Qua màng lọc thẩm thấu ngược nước lợ cấp hai (Brackish Water RO - BWRO) đạt $\text{TDS} < 50\ \text{mg/L}$.
    - Nhánh cấp nước khử khoáng và siêu tinh khiết: Dòng nước sau màng BWRO được dẫn qua tháp trao đổi ion (Ion Exchange - IX), trung hòa pH, sau đó qua tháp trao đổi hạt hỗn hợp (Mixed Bed IX) và thiết bị điện khử ion (Electrodialysis / EDI) đạt điện trở suất $10 - 18\ \text{M}\Omega\cdot\text{cm}$ trước khi nạp vào bồn chứa phân phối.
  - **Hình 5.** Sơ đồ chu trình công nghệ tổng thể sản xuất nước khử khoáng và nước siêu tinh khiết
    - <img src="ch08_advanced_treatment/assets/fig_05_p4.jpeg" alt="Hình 5" />
  - **Hình này chứng minh điều gì**
    - Sơ đồ chuỗi công nghệ liên hoàn từ tiền xử lý, thẩm thấu ngược áp lực cao đến các công đoạn đánh bóng (IX, Mixed Bed, EDI) để sản xuất các cấp nước có độ tinh khiết phân tầng.
  - **Từ đâu mà thấy được**
    - Khối tiền xử lý (Pretreatment): Chlorination $\to$ Coagulation $\to$ Flocculation $\to$ Sedimentation $\to$ Ultrafiltration / Multi-media $\to$ Dechlorination $\to$ Antiscalant $\to$ Fine Filtration.
    - Khối màng chính (Reverse Osmosis): High pressure pump $\to$ Energy Recovery $\to$ Seawater Reverse Osmosis $\to$ Brine disposal.
    - Khối đánh bóng (Polishing steps): Brackish Water RO $\to$ Ion Exchange (IX) $\to$ pH Neutralisation $\to$ Mixed Bed IX $\to$ EDI, tạo ra nước khử khoáng ($\kappa = 0{,}1 - 10\ \mu\text{S/cm}$) và nước siêu tinh khiết ($\rho = 10 - 18\ \text{M}\Omega\cdot\text{cm}$).

#### 8.2.2 Quy trình công nghệ màng và các công đoạn đánh bóng (Membrane Processes & Polishing Stages)

- Cơ chế phân tách của màng thẩm thấu ngược (RO Separation Mechanism):
  - Cấu tạo màng composite polyamide (TFC - Thin Film Composite) với kích thước mắt lọc danh định cỡ hạ nanomet ($0{,}0001\ \mu\text{m} = 0{,}1\ \text{nm}$).
  - Quá trình phân tách tuân theo mô hình hòa tan - khuếch tán (Solution-Diffusion Model): Phân tử nước hòa tan vào màng và khuếch tán qua lớp màng chọn lọc dưới gradient áp suất thủy lực lớn hơn áp suất thẩm thấu ($\Delta P > \Delta\pi$), trong khi các ion muối khoáng bị cản trở bởi lực đẩy tĩnh điện và kích thước hydrat hóa.
  - Hiệu suất loại bỏ ion hòa tan đạt trên $99{,}0 - 99{,}5\%$ đối với cation đa hóa trị ($Ca^{2+}, Mg^{2+}, Fe^{3+}$) và đạt $98{,}5 - 99{,}2\%$ đối với cation đơn hóa trị ($Na^+, K^+, Cl^-$).
- Công đoạn khử khoáng bằng hệ thống trao đổi ion hai cột (Two-Bed Demineralisation System):
  - Cột trao đổi Cation axit mạnh (Strong Acid Cation - SAC resin, dạng $H^+$):
    - Hạt nhựa polystyrene mang nhóm chức axit sulfonic ($-\text{SO}_3\text{H}$) bắt giữ toàn bộ cation kim loại và phóng thích ion $H^+$ vào dung dịch:
      $$2\text{R-SO}_3\text{H} + \text{Ca}^{2+} \rightleftharpoons (\text{R-SO}_3)_2\text{Ca} + 2\text{H}^+$$
      $$\text{R-SO}_3\text{H} + \text{Na}^+ \rightleftharpoons \text{R-SO}_3\text{Na} + \text{H}^+$$
    - Nước sau tháp cation mang tính axit mạnh do chứa các axit vô cơ tương ứng ($HCl, H_2SO_4, HNO_3, H_2CO_3$).
    - Tái sinh cột cation: Dùng dung dịch axit clohydric ($HCl\ 4 - 6\%$) cấp từ bồn lưu trữ (Storage HCl) qua bồn đo thể tích (Break tank). Hơi axit thoát ra được thu gom và xử lý qua tháp hấp thụ rửa khí (Scrubber column).
  - Cột trao đổi Anion bazơ mạnh (Strong Base Anion - SBA resin, dạng $OH^-$):
    - Hạt nhựa mang nhóm chức amoni bậc bốn ($-\text{NR}_3\text{OH}$) hấp phụ các anion gốc axit và phóng thích ion $OH^-$:
      $$\text{R-NR}_3\text{OH} + \text{Cl}^- \rightleftharpoons \text{R-NR}_3\text{Cl} + \text{OH}^-$$
      $$2\text{R-NR}_3\text{OH} + \text{SO}_4^{2-} \rightleftharpoons (\text{R-NR}_3)_2\text{SO}_4 + 2\text{OH}^-$$
      $$\text{R-NR}_3\text{OH} + \text{HSiO}_3^- \rightleftharpoons \text{R-NR}_3\text{HSiO}_3 + \text{OH}^-$$
    - Tái sinh cột anion: Dùng dung dịch kiềm natri hydroxit ($NaOH\ 4 - 5\%$) gia nhiệt ($35 - 45^\circ\text{C}$ để tăng hiệu quả khử silica) từ bồn lưu trữ (Storage NaOH) qua bồn định lượng (Break tank).
  - Phản ứng tự trung hòa tạo nước tinh khiết trung tính:
    $$\text{H}^+ + \text{OH}^- \rightleftharpoons \text{H}_2\text{O}$$
    - Nước sau hệ thống hai cột Cation - Anion đạt độ dẫn điện $\kappa \approx 1\ \mu\text{S/cm}$ (điện trở suất $\rho \approx 1\ \text{M}\Omega\cdot\text{cm}$).
- Cột đánh bóng hạt hỗn hợp (Mixed Bed Exchanger Polishing):
  - Cột chứa hỗn hợp đồng đều giữa hạt nhựa cation axit mạnh và anion bazơ mạnh theo tỷ lệ thể tích $1 : 1{,}5$ hoặc $1 : 2$.
  - Cấu trúc hạt phân tán xen kẽ tương đương với hàng nghìn cặp cột Cation - Anion nối tiếp nhau trong cùng một lớp vật liệu, triệt tiêu hoàn toàn hiện tượng rò rỉ muối (sodium slip) và rò rỉ silica.
  - Nước ra khỏi tháp Mixed Bed đạt độ dẫn điện cực nhỏ $\kappa = 0{,}1 - 0{,}2\ \mu\text{S/cm}$ (điện trở suất $\rho = 5 - 10\ \text{M}\Omega\cdot\text{cm}$).
  - Quy trình tái sinh tháp Mixed Bed: Phân tầng hạt nhựa bằng rửa ngược (hạt anion nhẹ nổi lên trên, hạt cation nặng chìm xuống dưới), tái sinh riêng biệt bằng $HCl$ và $NaOH$, rửa sạch rồi trộn đều lại bằng khí nén sạch không dầu.
- Công nghệ điện khử ion liên tục (Continuous Electrodeionization - CEDI / EDI):
  - Khối CEDI kết hợp màng bán thấm trao đổi ion chọn lọc (màng CEM và AEM) cùng lớp hạt nhựa trao đổi ion đặt xen kẽ dưới tác dụng của điện trường một chiều (DC).
  - Phân tử nước bị phân ly liên tục tại ranh giới màng thành các ion $H^+$ và $OH^-$ dưới tác dụng của điện thế cao, tự động tái sinh hạt nhựa liên tục mà không cần hóa chất axit hay bazơ.
  - Dòng sản phẩm đạt điện trở suất ổn định $\rho = 15 - 18\ \text{M}\Omega\cdot\text{cm}$, vận hành liên tục không gián đoạn chu kỳ hoàn nguyên.
- Hệ thống trung hòa nước thải hoàn nguyên (Neutralisation Sump & Environmental Protection):
  - Dung dịch xả thải hoàn nguyên có tính axit cao từ cột Cation và tính bazơ cao từ cột Anion được dẫn về hố thu trung hòa (Neutralisation sump).
  - Bơm hòa trộn (Blending pump) tuần hoàn sục khí cưỡng bức để hai dòng chất thải tự trung hòa lẫn nhau, bổ sung lượng hóa chất cân bằng tự động để duy trì dải pH nước xả đạt $6{,}5 - 8{,}5$ theo quy chuẩn xả thải công nghiệp.

#### 8.2.3 Hệ thống vòng tuần hoàn thủy lực và kiểm soát chất lượng (Recirculation Hydraulic Loop & Quality Control)

- Động học tái nhiễm bẩn của nước tinh khiết và yêu cầu vòng tuần hoàn kín (Sanitary Recirculation Loop):
  - Nước khử khoáng có độ tinh khiết cao là dung môi không no có xu hướng hòa tan khí cacbonic ($CO_2$) từ khí quyển cực nhanh, tạo thành axit cacbonic ($H_2CO_3$) làm giảm pH ($5{,}5 - 6{,}0$) và tăng độ dẫn điện.
  - Khi lưu trữ trong điều kiện tĩnh, vi sinh vật dị dưỡng dễ phát triển và hình thành màng sinh học (biofilm) trên thành bồn và đường ống.
  - Biện pháp kỹ thuật: Nước tinh khiết bắt buộc phải được tuần hoàn liên tục $24/7$ qua mạng lưới phân phối kín bằng thép không gỉ vi sinh inox 316L (độ nhám bề mặt bên trong $Ra \le 0{,}4 - 0{,}8\ \mu\text{m}$) với vận tốc dòng chảy tối thiểu $v \ge 1{,}0 - 1{,}5\ \text{m/s}$ nhằm tạo dòng chảy rối triệt tiêu khả năng bám dính của vi khuẩn.
- Kiến trúc thủy lực tuần hoàn khép kín mô phỏng:
  - Cơ chế thu gom đa điểm (Multiple Suction Hydraulics): Thu hồi nước mặt qua các cửa thu bề mặt (skimmers) để hớt màng váng nổi và thu gom nước đáy qua phễu thu đáy (main drain) để thu gom cặn lắng và duy trì sự xáo trộn đồng đều.
  - Cụm bơm tuần hoàn và lọc áp lực liên tục: Đảm bảo chu kỳ luân chuyển thể tích toàn bộ hệ thống (turnover time) từ $4 - 6\ \text{giờ/chu kỳ}$.
  - Cụm điều khiển và định lượng hóa chất tự động: Tích hợp tủ điều khiển giám sát trực tuyến thông số pH, độ dẫn điện, nồng độ khử trùng và cụm gia nhiệt/khử khuẩn trước khi đẩy dòng nước sạch trở lại các đầu phun cấp (return inlets).
  - **Hình 4.** Sơ đồ nguyên lý vòng tuần hoàn thủy lực xử lý nước khép kín
    - <img src="ch08_advanced_treatment/assets/fig_04_p3.jpeg" alt="Hình 4" />
  - **Hình này chứng minh điều gì**
    - Cấu trúc hệ thống thủy lực tuần hoàn khép kín gồm bơm đẩy, bình lọc áp lực, cụm kiểm soát hóa chất/khử trùng và mạng lưới phân phối cấp hồi liên tục.
  - **Từ đâu mà thấy được**
    - Tuyến thu hồi: Cửa thu nước mặt (12 - skimmer) và cửa hút đáy (14 - main drain) hợp dòng về rọ lọc rác thô và máy bơm tuần hoàn (7).
    - Cụm xử lý trung tâm: Nước được bơm qua bình lọc áp lực (2), qua tủ điều khiển tự động (13), cụm châm hóa chất (19) và bộ gia nhiệt/khử trùng (26).
    - Tuyến cấp hồi lưu: Dòng nước sạch sau xử lý được đẩy qua các đầu phun trả nước (11, 16) tạo vòng tuần hoàn liên tục không có góc chết thủy lực.

#### 8.2.4 Cấu tạo thiết bị mô-đun lọc nước tinh khiết POU (Purified Water Module Hardware & Components)

- Cấu trúc phần cứng mô-đun lọc nước tinh khiết tại điểm dùng (Point-of-Use Hardware Assembly):
  - Thiết kế tích hợp nguyên cụm nhỏ gọn phục vụ cho phòng kiểm nghiệm, phòng y tế và nhu cầu ăn uống gia đình chất lượng cao.
  - Khối tiền xử lý 3 cốc lọc đứng (Pre-treatment Canisters):
    - Cốc số 1 (Stage 1): Chứa lõi lọc cặn sợi quấn hoặc ép nhiệt polypropylene (PP) $5\ \mu\text{m}$, giữ lại tạp chất lơ lửng, cát sét, rỉ sét đường ống.
    - Cốc số 2 (Stage 2): Chứa than hoạt tính gáo dừa dạng hạt (GAC), hấp phụ lượng lớn clo dư, trihalomethanes ($THMs$) và hợp chất hữu cơ bay hơi ($VOCs$).
    - Cốc số 3 (Stage 3): Chứa than hoạt tính ép khối (CTO - Carbon Block), lọc tinh hạt cặn $\le 5\ \mu\text{m}$, giữ bụi than và khử triệt để clo tự do trước màng.
  - Khối màng lọc thẩm thấu ngược (RO Membrane Housing):
    - Vỏ màng composite chịu áp nằm ngang phía trên cụm cốc lọc, chứa cuộn màng Filmtec thẩm thấu ngược $0{,}0001\ \mu\text{m}$ tiêu chuẩn NSF/ANSI 58.
    - Cổng xả phân dòng: Dòng nước tinh khiết (permeate) đi qua van một chiều về bình áp; dòng nước thải cô đặc (concentrate) đi qua van hạn chế dòng (flow restrictor) xả ra đường thoát nước.
  - Bình tích áp thủy khí màng ngăn (Pressurized Diaphragm Storage Tank):
    - Bồn kim loại sơn tĩnh điện dung tích chứa $12\ \text{L}$ (12L Tank), tích hợp màng ngăn cao su butyl thực phẩm chia khoang chứa nước ngọt và khoang đệm khí nén phía dưới.
    - Áp suất nạp khí rỗng tiêu chuẩn: $35 - 50\ \text{kPa}$ ($5 - 7\ \text{psi}$).
    - Chức năng: Lưu trữ nước tinh khiết sản xuất chậm từ màng RO và giải phóng lưu lượng tức thời $1{,}5 - 3{,}0\ \text{L/phút}$ qua vòi lấy nước.
  - Khối lọc tinh khử mùi vị sau màng và vòi chuyên dụng (Post-treatment & Dispense Faucet):
    - Lõi than hoạt tính dạng ống thẳng (In-line Post-GAC polishing filter) lắp sau bình áp để tinh chế cảm quan, khử mùi vị lạ phát sinh trong bồn chứa.
    - Vòi cổ ngỗng bằng thép không gỉ mạ crôm chuyên dụng (gooseneck faucet) cùng hệ thống dây dẫn PE trắng an toàn thực phẩm.
  - **Hình 6.** Thiết bị lọc nước tinh khiết thẩm thấu ngược đa cấp nguyên cụm
    - <img src="ch08_advanced_treatment/assets/fig_06_p4.jpeg" alt="Hình 6" />
  - **Hình này chứng minh điều gì**
    - Cấu tạo phần cứng hoàn chỉnh của cụm thiết bị sản xuất nước tinh khiết POU gồm cụm cốc lọc đa cấp, vỏ màng RO, bình tích áp màng ngăn và phụ kiện kết nối đồng bộ.
  - **Từ đâu mà thấy được**
    - Khối lọc chính (Model FS409 Reverse Osmosis): 2 cốc lọc tiền xử lý thẳng đứng màu trắng, vỏ màng RO nằm ngang gắn phía trên cùng lõi lọc tinh in-line.
    - Bình tích áp dự trữ (12L Tank): Bồn hình trụ tròn màu trắng có van khóa phía trên, nhãn thông số "12L TANK".
    - Phụ kiện kết nối: Vòi lấy nước cổ ngỗng (gooseneck tap), cuộn ống dây dẫn nước trắng, khóa mở cốc lọc bằng nhựa và các đầu cút nối van cấp nước.

#### 8.2.5 Tính toán kỹ thuật và thông số vận hành hệ thống màng và trao đổi ion (Engineering Calculations & Operational Parameters)

- Phương trình thủy lực vận chuyển qua màng thẩm thấu ngược (Solution-Diffusion Transport Equations):
  - Phương trình thông lượng nước thấm ($J_w$):
    $$J_w = K_w \cdot (\Delta P - \Delta\pi) = K_w \cdot \text{NDP}$$
    - $J_w$: Thông lượng nước thấm qua bề mặt màng ($\text{L}/(\text{m}^2\cdot\text{h})$ hay $\text{LMH}$).
    - $K_w$: Hệ số thấm nước của vật liệu màng ($\text{LMH/bar}$).
    - $\text{NDP}$: Áp suất dẫn động thực qua màng (Net Driving Pressure, $\text{bar}$).
    - $\Delta P$: Chênh lệch áp suất thủy lực trung bình hai phía màng ($\text{bar}$):
      $$\Delta P = \left(\frac{P_{\text{feed}} + P_{\text{concentrate}}}{2}\right) - P_{\text{permeate}}$$
    - $\Delta\pi$: Chênh lệch áp suất thẩm thấu trung bình hai phía màng ($\text{bar}$):
      $$\Delta\pi = \left(\frac{\pi_{\text{feed}} + \pi_{\text{concentrate}}}{2}\right) - \pi_{\text{permeate}}$$
  - Thông lượng khuếch tán chất tan qua màng ($J_s$):
    $$J_s = B_s \cdot (C_m - C_p)$$
    - $J_s$: Thông lượng muối khuếch tán qua màng ($\text{g}/(\text{m}^2\cdot\text{h})$).
    - $B_s$: Hệ số thấm chất tan của màng ($\text{LMH}$).
    - $C_m, C_p$: Nồng độ muối tại bề mặt màng và trong dòng permeate ($\text{mg/L}$).
  - Tỷ lệ thu hồi thể tích nước sạch ($Y$):
    $$Y = \left(\frac{Q_p}{Q_f}\right) \times 100\% = \left(\frac{Q_p}{Q_p + Q_c}\right) \times 100\%$$
  - Tỷ lệ loại bỏ muối hòa tan ($R$):
    $$R = \left(1 - \frac{C_p}{C_f}\right) \times 100\%$$
  - Phương trình cân bằng khối lượng chất tan tổng thể:
    $$Q_f \cdot C_f = Q_p \cdot C_p + Q_c \cdot C_c$$
    $$C_c = \frac{Q_f \cdot C_f - Q_p \cdot C_p}{Q_c} = C_f \cdot \left[\frac{1 - Y \cdot (1 - R)}{1 - Y}\right]$$

- Phương trình tính toán kích thước và dung lượng cột trao đổi ion:
  - Dung lượng trao đổi tổng cộng của cột ($E_{\text{tot}}$):
    $$E_{\text{tot}} = V_{\text{resin}} \cdot q_{\text{working}}$$
    - $E_{\text{tot}}$: Tổng đương lượng ion mà cột hạt nhựa có thể hấp phụ trong một chu kỳ ($\text{eq}$ hay $\text{mol}_{\text{eq}}$).
    - $V_{\text{resin}}$: Thể tích lớp hạt nhựa trong cột trao đổi ($\text{m}^3$ hoặc $\text{L}$).
    - $q_{\text{working}}$: Dung lượng trao đổi làm việc thực tế của hạt nhựa ($\text{eq/L}$ hoặc $\text{eq/m}^3$). Với hạt SAC ($H^+$ form), $q_{\text{working}} \approx 1{,}2 - 1{,}6\ \text{eq/L}$; với hạt SBA ($OH^-$ form), $q_{\text{working}} \approx 0{,}8 - 1{,}1\ \text{eq/L}$.
  - Thể tích nước xử lý được trong một chu kỳ trước điểm xuyên phá ($V_{\text{cycle}}$):
    $$V_{\text{cycle}} = \frac{V_{\text{resin}} \cdot q_{\text{working}}}{\sum C_{\text{ions, feed}}}$$
    - $\sum C_{\text{ions, feed}}$: Tổng nồng độ đương lượng của các cation (đối với cột Cation) hoặc các anion (đối với cột Anion) trong nước cấp ($\text{eq/m}^3$).
  - Khối lượng hóa chất hoàn nguyên yêu cầu cho một chu kỳ tái sinh ($m_{\text{chem}}$):
    $$m_{\text{chem}} = E_{\text{tot}} \cdot M_{\text{eq}} \cdot \alpha_{\text{stoich}}$$
    - $M_{\text{eq}}$: Đương lượng gam của hóa chất hoàn nguyên ($M_{\text{eq, HCl}} = 36{,}46\ \text{g/eq}$; $M_{\text{eq, NaOH}} = 40{,}00\ \text{g/eq}$).
    - $\alpha_{\text{stoich}}$: Hệ số dư hóa chất so với tỷ lượng lý thuyết ($\alpha_{\text{stoich}} \approx 1{,}5 - 2{,}5$).

- Bảng phân loại các cấp độ tinh khiết của nước theo tiêu chuẩn quốc tế (ISO 3696 & ASTM D1193):

| Chỉ tiêu Kỹ thuật | Cấp 1 (Grade 1 / Ultrapure Water) | Cấp 2 (Grade 2 / Purified Water) | Cấp 3 (Grade 3 / Primary Water) |
|---|---|---|---|
| Độ dẫn điện tại $25^\circ\text{C}$ ($\mu\text{S/cm}$) | $\le 0{,}055 - 0{,}10$ | $\le 1{,}0$ | $\le 5{,}0$ |
| Điện trở suất tại $25^\circ\text{C}$ ($\text{M}\Omega\cdot\text{cm}$) | $\ge 10{,}0 - 18{,}2$ | $\ge 1{,}0$ | $\ge 0{,}2$ |
| Tổng cacbon hữu cơ ($\text{TOC}$, $\text{ppb}$) | $< 10 - 20$ | $< 50$ | $< 200$ |
| Hàm lượng Silica hòa tan ($SiO_2$, $\mu\text{g/L}$) | $< 3 - 5$ | $< 10$ | $< 100$ |
| Tổng lượng vi sinh vật ($\text{CFU/mL}$) | $< 1$ | $< 10$ | $< 100$ |
| Công nghệ xử lý chủ yếu | RO cấp 2 + Mixed Bed + EDI + UV 185 nm | RO + Trao đổi ion Cation/Anion 2 cột | Chưng cất đơn hoặc RO sơ cấp đơn tầng |
| Lĩnh vực ứng dụng chính | Sản xuất vi mạch bán dẫn, sắc ký HPLC, quang phổ ICP-MS | Nuôi cấy mô, pha chế dung dịch chuẩn, nước cấp nồi hơi cao áp | Rửa dụng cụ thủy tinh, nước cấp cho máy tạo nước siêu tinh khiết |

### 8.3 Hệ thống xử lý nước hồ bơi (Water Treatment System for Swimming Pool)

#### 8.3.1 Nguyên lý thủy lực và chu trình tuần hoàn khép kín (Hydraulic Circulation Principles)

* Chu trình tuần hoàn khép kín (closed-loop recirculation) bảo đảm chất lượng nước hồ bơi liên tục đáp ứng các tiêu chuẩn vệ sinh dịch tễ và an toàn cho người bơi:
  * Nước hồ bơi liên tục tiếp nhận chất ô nhiễm từ người bơi (mồ hôi, dầu bài tiết, mỹ phẩm, vi sinh vật) và môi trường ngoài trời (bụi, lá cây, bào tử rêu tảo).
  * Hệ thống tuần hoàn liên tục thu gom, lọc sạch cặn lơ lửng, khử trùng tiêu diệt mầm bệnh, và phân phối đồng đều nước đã xử lý trở lại hồ.
* Thời gian chu chuyển nước (turnover period, $T$) là thông số thủy lực cơ bản để tính toán quy mô toàn bộ hệ thống xử lý:
  * Thời gian chu chuyển biểu diễn thời gian cần thiết để bơm tuần hoàn luân chuyển một thể tích nước bằng đúng dung tích toàn bộ hồ bơi ($V$):
    $$T = \frac{V}{Q}$$
  * Trong đó $V$ là thể tích hồ bơi ($\text{m}^3$), $Q$ là lưu lượng tuần hoàn của trạm bơm ($\text{m}^3/\text{h}$), và $T$ là thời gian chu chuyển ($\text{h}$).
  * Tiêu chuẩn thiết kế quy định thời gian chu chuyển tùy theo loại hình và mật độ người bơi:
    * Hồ bơi thi đấu và hồ người lớn công cộng: $T = 4 - 6\text{ h}$.
    * Hồ bơi gia đình hoặc khách sạn nghỉ dưỡng: $T = 6 - 8\text{ h}$.
    * Hồ vầy trẻ em và hồ bán công cộng mật độ cao: $T = 1 - 2\text{ h}$.
* Lưu lượng thiết kế của trạm bơm tuần hoàn ($Q$) được xác định từ thể tích hồ và thời gian chu chuyển yêu cầu:
  $$Q = \frac{V}{T_{\text{design}}}$$
  * Hệ số an toàn và lưu lượng dự phòng thường được cộng thêm $10 - 15\%$ để bù trừ suy giảm lưu lượng khi áp lực bình lọc tăng cao do tích tụ cặn bẩn.
* Phân bổ dòng thu nước đảm bảo thu gom hiệu quả cả chất ô nhiễm nổi trên mặt nước và cặn lắng dưới đáy hồ:
  * Dòng thu nước bề mặt qua các hộp thu nước mặt (skimmers) chiếm tỷ lệ $60 - 80\%$ tổng lưu lượng tuần hoàn:
    * Váng dầu, mỡ bôi trơn, bụi nổi và chất hữu cơ nhẹ tập trung chủ yếu ở tầng nước bề mặt có độ sâu $0 - 15\text{ cm}$.
    * Vận tốc tràn qua mép thu nước skimmer duy trì từ $0.3 - 0.5\text{ m/s}$ để tạo hiệu ứng hút váng bề mặt liên tục.
  * Dòng thu nước tầng đáy qua các phễu thu đáy (main drains) đảm bảo $20 - 40\%$ tổng lưu lượng tuần hoàn:
    * Cặn nặng, hạt cát, và bùn kết tủa lắng xuống đáy dốc của lòng hồ được dẫn lưu về phễu thu đáy.
    * Tốc độ dòng chảy qua lưới chắn phễu thu đáy bị giới hạn $\le 0.5\text{ m/s}$ nhằm triệt tiêu nguy cơ hút dính nguy hiểm đối với người tắm.

#### 8.3.2 Cấu tạo thiết bị và các phân hệ công nghệ (Component Architecture and System Layout)

* Hệ thống xử lý nước hồ bơi tiêu chuẩn bao gồm 5 phân hệ công nghệ chính liên kết thủy lực khép kín:
  * Phân hệ thu gom nước mặt và đáy: gồm các hộp skimmer (12), phễu thu đáy (14), khớp hút chân không vệ sinh (15), và tuyến ống hút góp (7).
  * Phân hệ tiền xử lý và bơm áp lực: gồm giỏ chắn rác thô (hair and lint strainer) và máy bơm ly tâm tuần hoàn (1).
  * Phân hệ lọc áp lực: gồm bình lọc cát thạch anh nhiều tầng (2) và van điều khiển đa ngả 6 vị trí (9).
  * Phân hệ gia nhiệt và phụ trợ: gồm thiết bị gia nhiệt nước (6), hộp tự động cân bằng bù nước (31), và đèn chiếu sáng âm nước (23).
  * Phân hệ châm hóa chất và phân phối trả nước: gồm bơm định lượng hóa chất (19), bình châm clo tự động (26), tủ điện điều khiển (13), ống góp phân phối (16), và các đầu phun trả nước (11).
  * **Hình 4.** Sơ đồ cấu tạo và nguyên lý tuần hoàn hệ thống xử lý nước hồ bơi
#### 8.3.3 Quá trình lọc áp lực và vận hành van điều khiển đa ngả (Multi-port Valve Operation)

* Bình lọc cát áp lực nhiều tầng (Sand Filter, chi tiết 2) là trái tim của quá trình tách cặn cơ học trong xử lý nước hồ bơi:
  * Vỏ bình chế tạo bằng vật liệu composite quấn sợi thủy tinh (fiberglass reinforced polyester) chịu áp suất làm việc tối đa $2.5 - 4.0\text{ bar}$.
  * Cơ chế giữ cặn dựa trên sự phối hợp giữa sàng lọc cơ học, lắng quán tính và hấp phụ tĩnh điện trong các khe rỗng giữa các hạt cát.
* Cấu trúc tầng vật liệu lọc bên trong bình lọc cát:
  * Tầng cát lọc chính: cát thạch anh (silica sand) có kích thước hiệu dụng $d_{10} = 0.45 - 0.55\text{ mm}$, hệ số đồng nhất $U_c \le 1.5$, chiều dày tầng lọc $L = 0.4 - 0.7\text{ m}$.
  * Tầng than antraxít hỗ trợ (tùy chọn cho lọc hai lớp): kích thước hạt $d = 0.8 - 1.2\text{ mm}$, chiều dày $0.2 - 0.3\text{ m}$ đặt trên lớp cát để tăng khả năng chứa cặn.
  * Tầng sỏi đỡ đáy: sỏi thạch anh tròn cạnh kích thước $2 - 5\text{ mm}$ và $5 - 10\text{ mm}$, chiều dày $0.15 - 0.25\text{ m}$, bao bọc các ống thu nước răng lược (lateral underdrain) ở đáy bình.
* Tốc độ lọc và tính toán diện tích bề mặt bình lọc cát:
  * Tốc độ lọc thiết kế ($v_{\text{filt}}$) đối với bình lọc cát áp lực hồ bơi:
    $$v_{\text{filt}} = 20 - 35\text{ m/h}$$
    * Lọc tốc độ tiêu chuẩn (standard rate): $v_{\text{filt}} = 20 - 25\text{ m/h}$, cho chất lượng nước sau lọc cao nhất ($\text{Turbidity} < 0.5\text{ NTU}$).
    * Lọc tốc độ cao (high-rate filtration): $v_{\text{filt}} = 30 - 50\text{ m/h}$, giúp tiết kiệm diện tích lắp đặt phòng kỹ thuật.
  * Diện tích mặt cắt ngang yêu cầu của bình lọc ($A_f$):
    $$A_f = \frac{Q}{v_{\text{filt}}}$$
    * Đường kính bình lọc ($D$) được tính theo hình trụ tròn:
      $$D = \sqrt{\frac{4 \cdot A_f}{\pi}}$$
* Van điều khiển đa ngả 6 vị trí (Multi-port Valve, chi tiết 9):
  * Lắp đặt trên đỉnh bình lọc (top-mount) hoặc bên hông bình lọc (side-mount), chuyển đổi chế độ vận hành bằng tay gạt xoay:
  * Chế độ 1: Lọc bình thường (Filter):
    * Nước đi từ đỉnh bình xuống qua lớp vật liệu lọc, cặn bẩn bị giữ lại, nước trong thu ở đáy qua ống răng lược và đi ra tuyến ống cấp trở lại hồ.
  * Chế độ 2: Rửa ngược (Backwash):
    * Dòng nước đảo chiều, đi từ đáy bình ngược lên qua lớp cát làm giãn nở tầng vật liệu lọc, cuốn trôi bùn cặn ra đường xả thải (Waste drain).
    * Chu kỳ rửa ngược được kích hoạt khi tổn thất áp lực qua bình lọc tăng thêm $\Delta P \ge 0.5 - 0.7\text{ bar}$ so với áp lực ban đầu lúc vật liệu lọc sạch.
    * Tốc độ rửa ngược duy trì $v_{\text{bw}} = 30 - 45\text{ m/h}$ để bảo đảm độ giãn nở tầng cát đạt $E = 20 - 30\%$, thời gian rửa từ $3 - 5\text{ phút}$.
  * Chế độ 3: Rửa xuôi ổn định (Rinse):
    * Nước đi từ trên xuống như chế độ lọc nhưng xả bỏ ra đường thoát nước thải trong thời gian $1 - 2\text{ phút}$.
    * Tác dụng nén chặt lại tầng cát sau rửa ngược và loại bỏ triệt để cặn bẩn còn sót dưới đáy bình, tránh đẩy cặn vào hồ bơi.
  * Chế độ 4: Xả bỏ trực tiếp (Waste):
    * Nước từ bơm đi thẳng ra cống thoát nước mà không đi qua lớp cát lọc.
    * Sử dụng khi hút cặn đáy hồ có nồng độ bùn đậm đặc hoặc khi cần hạ mực nước hồ bơi nhanh chóng.
  * Chế độ 5: Tuần hoàn tắt (Recirculate):
    * Dòng nước bỏ qua bình lọc, đi thẳng từ bơm trở lại hồ bơi.
    * Sử dụng để khuấy trộn nhanh hóa chất hòa tan khi vừa châm vào hồ bơi hoặc duy trì dòng chảy khi sửa chữa bình lọc.
  * Chế độ 6: Đóng kín hoàn toàn (Closed):
    * Ngăn chặn toàn bộ các cổng lưu chất qua van.
    * Sử dụng khi bảo trì, vệ sinh giỏ lọc bơm tuần hoàn mà không làm trào nước từ hồ bơi về phòng máy.

#### 8.3.4 Cân bằng hóa nước, khử trùng và kiểm soát chất lượng nước (Water Chemistry, Disinfection & Water Balance)

* Khử trùng bằng hóa chất clo là biện pháp bắt buộc để tiêu diệt mầm bệnh và oxy hóa chất hữu cơ:
  * Khí clo hoặc các hợp chất clo hóa khi hòa tan vào nước tạo thành axit hipoclorơ ($\text{HOCl}$) và ion hipoclorit ($\text{OCl}^-$):
    $$\text{Cl}_2 + \text{H}_2\text{O} \rightleftharpoons \text{HOCl} + \text{H}^+ + \text{Cl}^-$$
    $$\text{NaOCl} + \text{H}_2\text{O} \rightarrow \text{HOCl} + \text{Na}^+ + \text{OH}^-$$
    $$\text{Ca(OCl)}_2 + 2\text{H}_2\text{O} \rightarrow 2\text{HOCl} + \text{Ca}^{2+} + 2\text{OH}^-$$
  * Cân bằng phân ly giữa $\text{HOCl}$ và $\text{OCl}^-$ phụ thuộc khắt khe vào $\text{pH}$ của nước:
    $$\text{HOCl} \rightleftharpoons \text{H}^+ + \text{OCl}^- \quad (pK_a \approx 7.54 \text{ tại } 25^\circ\text{C})$$
    * Axit hipoclorơ ($\text{HOCl}$) có hoạt tính diệt khuẩn mạnh gấp $80 - 100$ lần so với ion hipoclorit ($\text{OCl}^-$) do cấu trúc phân tử trung hòa điện dễ dàng khuếch tán qua màng lipid của tế bào vi khuẩn.
    * Ở mức $\text{pH} = 7.2$, tỷ lệ $\text{HOCl}$ chiếm khoảng $66\%$; ở $\text{pH} = 7.5$, tỷ lệ $\text{HOCl}$ đạt khoảng $50\%$; ở $\text{pH} = 8.0$, tỷ lệ $\text{HOCl}$ tụt giảm xuống chỉ còn khoảng $21\%$.
* Thiết bị định lượng hóa chất khử trùng (chi tiết 19 và 26):
  * Bình châm clo viên tự động dạng inline/offline (In-line Chlorinator, chi tiết 26):
    * Sử dụng clo hữu cơ dạng viên nén TCCA (Trichloroisocyanuric acid, $90\%$ clo hoạt tính) hòa tan chậm theo lưu lượng dòng chảy.
    * Viên nén phân giải giải phóng clo kết hợp axit xyanuric ($\text{H}_3\text{Cy}$) đóng vai trò chất ổn định chống quang phân dưới tác động của tia cực tím mặt trời:
      $$\text{HOCl} + \text{H}_3\text{Cy} \rightleftharpoons \text{H}_2\text{ClCy} + \text{H}_2\text{O}$$
  * Bơm định lượng màng điện từ châm hóa chất tự động (Chemical Dosing Pump, chi tiết 19):
    * Bơm dung dịch $\text{NaOCl}$ khử trùng và dung dịch axit $\text{HCl}$ / $\text{NaHSO}_4$ hạ $\text{pH}$ hoặc xút $\text{NaOH}$ / $\text{Na}_2\text{CO}_3$ nâng $\text{pH}$.
    * Tự động điều khiển theo tín hiệu đo trực tuyến từ cảm biến đo thế oxy hóa khử ($\text{ORP}$) và điện cực $\text{pH}$.
* Kiểm soát các chỉ tiêu chất lượng nước hồ bơi tiêu chuẩn:
  * Nồng độ clo dư tự do (Free Available Chlorine): duy trì trong khoảng $1.0 - 3.0\text{ mg/L}$.
  * Nồng độ clo liên kết (Combined Chlorine - cloramin): khống chế $\le 0.4\text{ mg/L}$ (cloramin là nguyên nhân chính gây cay mắt, rát da và mùi nồng khó chịu trong hồ bơi).
  * Độ $\text{pH}$ thiết kế: duy trì nghiêm ngặt trong khoảng $7.2 - 7.6$:
    * Nếu $\text{pH} < 7.2$: nước gây ăn mòn đường ống kim loại, hòa tan vữa xi măng mạch gạch và làm cay mắt người bơi.
    * Nếu $\text{pH} > 7.6$: hiệu lực diệt khuẩn của clo suy giảm nghiêm trọng và xuất hiện nguy cơ đóng cặn canxi trên bề mặt cát lọc.
  * Độ kiềm tổng (Total Alkalinity - $\text{TA}$): duy trì trong khoảng $80 - 120\text{ mg/L}$ tính theo $\text{CaCO}_3$, đóng vai trò hệ đệm chống sốc $\text{pH}$.
  * Độ cứng canxi (Calcium Hardness - $\text{CH}$): duy trì trong khoảng $200 - 400\text{ mg/L}$ tính theo $\text{CaCO}_3$ để bảo vệ bề mặt bê tông hồ bơi.
  * Nồng độ chất ổn định axit xyanuric (Cyanuric Acid): duy trì $30 - 50\text{ mg/L}$ cho hồ bơi ngoài trời (không vượt quá $100\text{ mg/L}$ để tránh hiện tượng khóa clo - chlorine lock).
* Đánh giá xu hướng cân bằng nước bằng chỉ số bão hòa Langelier ($\text{LSI}$):
  $$\text{LSI} = \text{pH} - \text{pH}_s$$
  * Giá trị $\text{pH}_s$ là độ $\text{pH}$ bão hòa canxi cacbonat, được xác định theo công thức:
    $$\text{pH}_s = (9.3 + A + B) - (C + D)$$
    * Trong đó hệ số $A$ phụ thuộc hàm lượng tổng chất rắn hòa tan ($\text{TDS}$), $B$ phụ thuộc nhiệt độ nước ($T^\circ\text{C}$), $C$ phụ thuộc độ cứng canxi ($\text{CH}$), và $D$ phụ thuộc độ kiềm tổng ($\text{TA}$).
  * Tiêu chuẩn cân bằng nước: $-0.3 \le \text{LSI} \le +0.3$:
    * $\text{LSI} < -0.3$: Nước có tính xâm thực và ăn mòn thiết bị kim loại.
    * $\text{LSI} > +0.3$: Nước có tính bão hòa quá mức, gây kết tủa cặn trắng canxi trên gạch và làm tắc nghẽn bình lọc cát.

#### 8.3.5 So sánh công nghệ tuần hoàn hồ bơi với các quy trình màng xử lý nâng cao (Comparative Analysis with Advanced Membrane Systems)

* Sự khác biệt cốt lõi giữa hệ thống lọc cát tuần hoàn hồ bơi và các công nghệ xử lý màng nâng cao (Advanced Membrane Systems):
  * Hệ thống hồ bơi là quy trình xử lý khối lớn tuần hoàn nội bộ (recirculation loop), ưu tiên tách hạt huyền phù thô ($> 10 - 20\text{ \mu m}$) và duy trì nồng độ chất khử trùng dư tồn lưu trong không gian thể tích hồ.
  * Quy trình xử lý nước tinh khiết (Demineralised Water), khử mặn nước biển (SWRO) và lọc sinh hoạt gia đình (POU RO) là các quy trình phân tách màng chuyên sâu một chiều (single-pass separation), loại bỏ triệt để ion hòa tan, vi khuẩn và vi rút ở cấp độ phân tử ($< 0.0001\text{ \mu m}$).
* Quy trình xử lý khử mặn nước biển (Seawater Reverse Osmosis - SWRO):
  * Khác với chu trình áp lực thấp của hồ bơi ($P \le 2.5\text{ bar}$), SWRO vận hành dưới áp suất cực cao ($55 - 70\text{ bar}$) để vượt qua áp suất thẩm thấu tự nhiên của nước biển ($\pi \approx 25 - 30\text{ bar}$).
  * Đòi hỏi hệ thống tiền xử lý phức tạp (keo tụ, lọc đa tầng, lọc tinh cartridge) để bảo vệ màng bán thấm polyamide khỏi bị tắc nghẽn và bám bẩn.
  * **Hình 7.** Sơ đồ quy trình công nghệ khử mặn nước biển (SWRO)
    - <img src="ch08_advanced_treatment/assets/fig_07_p5.jpeg" alt="Hình 7" />
    - **Hình này chứng minh điều gì**
      - Công nghệ màng SWRO đòi hỏi quy trình tiền xử lý nghiêm ngặt và áp suất vận hành rất cao so với lọc cát tuần hoàn.
    - **Từ đâu mà thấy được**
      - Khối tiền xử lý gồm keo tụ, lọc đa tầng, khử clo và lọc tinh cartridge bảo vệ màng.
      - Bơm cao áp (High pressure pump) kết hợp bộ thu hồi năng lượng (Energy Recovery) đẩy nước qua màng Seawater Reverse Osmosis.
      - Dòng nước được tách thành nước thành phẩm (Drinking Water) và dòng thải muối (Brine disposal).
* Hệ thống lọc nước sinh hoạt gia đình 4 cấp thẩm thấu ngược (4-Stage POU Household RO System):
  * Quy mô xử lý quy ước tại điểm sử dụng (Point-of-Use - POU) với lưu lượng nhỏ ($10 - 15\text{ L/h}$), phân tách dòng nước cấp thành dòng nước uống tinh khiết và dòng nước thải cô đặc xả bỏ.
  * Sử dụng bình tích áp màng cao su (pressurized diaphragm tank) để lưu trữ nước thành phẩm, khắc phục tốc độ lọc chậm của màng RO.
  * **Hình 8.** Thiết bị hệ thống lọc nước thẩm thấu ngược gia đình 4 cấp Model FS409
    - <img src="ch08_advanced_treatment/assets/fig_08_p5.jpeg" alt="Hình 8" />
    - **Hình này chứng minh điều gì**
      - Hệ thống lọc nước uống gia đình POU sử dụng kết cấu mô-đun nhỏ gọn gồm các cốc lọc nối tiếp và bình áp tích nước.
    - **Từ đâu mà thấy được**
      - Khung giá đỡ mang 2 cốc lọc thô bên dưới cùng vỏ màng RO và lõi than chức năng nằm ngang phía trên.
      - Bình áp kín màu trắng dung tích $12\text{ L}$ (12L Tank) có van khóa bảo ôn nước tinh khiết.
      - Bộ phụ kiện vòi lấy nước uống inox và ống dẫn PE áp lực cao kết nối các cấp lọc.
  * **Hình 9.** Sơ đồ nguyên lý và thủy lực hệ thống lọc nước thẩm thấu ngược gia đình 4 cấp
    - <img src="ch08_advanced_treatment/assets/fig_09_p6.jpeg" alt="Hình 9" />
    - **Hình này chứng minh điều gì**
      - Nguyên lý phân tách một chiều qua màng RO (cấp 3) tạo ra dòng nước uống sạch vào bình tích áp và dòng xả cặn ra cống.
    - **Từ đâu mà thấy được**
      - Nước từ nguồn cấp đi tuần tự qua cấp 1 (Sediment Filter) và cấp 2 (Carbon Filter) để tiền xử lý.
      - Màng RO (cấp 3) xả nước đậm đặc qua bộ hạn chế dòng (flow restrictor) đến cống thải (Waste Drain).
      - Nước sau màng tích trữ trong bình áp (Storage Tank) rồi qua cấp 4 (Post Carbon Filter) ra vòi sử dụng.
* Quy trình sản xuất nước tinh khiết khử khoáng công nghiệp (Demineralised Water Treatment System):
  * Sử dụng cơ chế trao đổi ion chuyên sâu qua các cột hạt nhựa cation acid mạnh, anion bazơ mạnh và cột hỗn hợp mixed bed để loại bỏ toàn bộ muối hòa tan.
  * Đạt độ tinh khiết cực cao với độ dẫn điện chỉ từ $0.1 - 0.2\text{ \mu S/cm}$ (điện trở suất $5 - 10\text{ M}\Omega\cdot\text{cm}$), phục vụ các ngành công nghiệp vi điện tử, bán dẫn và nước cấp lò hơi áp lực cao.
  * **Hình 3.** Sơ đồ dây chuyền sản xuất nước khử khoáng công nghiệp (Demineralised Water System)

### 8.4 Quy trình công nghệ khử mặn nước biển (Seawater Treatment Process)

#### 8.4.1 Tổng quan công nghệ khử mặn nước biển SWRO

* Khử mặn nước biển bằng thẩm thấu ngược (Seawater Reverse Osmosis - SWRO) là công nghệ màng phân tách để chuyển hóa nước biển thành nước ngọt phục vụ ăn uống và công nghiệp:
  * Nguồn nước biển tự nhiên có nồng độ tổng chất rắn hòa tan ($TDS$) rất cao, dao động trong khoảng từ $35,000\text{ mg/L}$ đến $45,000\text{ mg/L}$ ($35\text{--}45\text{ g/L}$).
  * Áp suất thẩm thấu tự nhiên ($\pi$) của nước biển đạt giá trị rất lớn, xấp xỉ từ $28\text{ bar}$ đến $36\text{ bar}$ ở $25^\circ\text{C}$ (ước tính thực nghiệm khoảng $0.80\text{ bar}$ cho mỗi $1,000\text{ mg/L } TDS$).
  * Quá trình thẩm thấu ngược cưỡng bức dung môi (nước) đi xuyên qua màng bán thấm từ phía dung dịch đậm đặc sang phía dung dịch loãng bằng cách cấp áp suất thủy lực bên ngoài ($P_f$) vượt quá áp suất thẩm thấu tự nhiên ($\Delta P > \Delta \pi$).
* Lớp màng mỏng bán thấm composite (Thin-Film Composite - TFC) giữ lại hầu hết các ion khoáng hòa tan và tạp chất:
  * Hiệu suất khử muối (salt rejection, $R$) của màng SWRO hiện đại đạt trên $99.4\text{--}99.7\%$.
  * Màng loại bỏ hoàn toàn các hạt lơ lửng, vi khuẩn, virus, nội độc tố vi sinh và các hợp chất hữu cơ hòa tan.
  * Nước ngọt thành phẩm (permeate) đạt tiêu chuẩn nước uống quốc tế của Tổ chức Y tế Thế giới (WHO) với $TDS < 450\text{ mg/L}$ và quy chuẩn kỹ thuật quốc gia QCVN 01-1:2018/BYT ($TDS \le 500\text{ mg/L}$).

#### 8.4.2 Dây chuyền tiền xử lý nước biển bảo vệ màng RO

* Dây chuyền tiền xử lý (Pretreatment Train) bảo vệ màng SWRO khỏi hiện tượng tắc nghẽn vật lý, cáu cặn hóa học và bám bẩn sinh học:
  * Công trình thu nước biển (Sea Water Intake): Sử dụng đường ống ngầm khơi xa trang bị chóp nón giảm vận tốc (velocity cap, vận tốc dòng chảy $v \le 0.15\text{ m/s}$) hoặc hệ thống giếng ngầm ven biển (beach wells) nhằm giảm thiểu sinh vật phù du và rác trôi nổi.
  * Khử trùng sơ bộ (Chlorination): Châm hóa chất clo tự do ($\text{Cl}_2$) hoặc natri hypoclorit ($\text{NaOCl}$) định kỳ để ức chế hàu biển, hà bám và màng vi sinh vật bám bám dính trên đường ống dẫn thô.
  * Keo tụ và tạo bông (Coagulation - Flocculation): Châm muối sắt ($\text{FeCl}_3$) với liều lượng $1.0\text{--}5.0\text{ mg/L}$ tại buồng trộn nhanh và tạo bông chậm để kết cụm các hạt keo vô cơ và chất hữu cơ tự nhiên (NOM).
  * Lắng (Sedimentation) và Lọc đa tầng (Multi-media Filtration - MMF): Nước biển qua bể lắng trọng lực hoặc bể tuyển nổi khí hòa tan (DAF) rồi đi qua các lớp cát thạch anh và than antraxít để hạ độ đục xuống dưới $0.5\text{ NTU}$.
* Công nghệ màng siêu lọc (Ultrafiltration - UF) nâng cao chất lượng nước trước màng RO:
  * Màng UF dạng sợi rỗng (hollow fiber) với kích thước mao quản $0.01\text{--}0.05\ \mu\text{m}$ (ngưỡng cắt phân tử $10,000\text{--}100,000\text{ Da}$) tạo hàng rào cơ học loại bỏ hạt keo siêu mịn và vi sinh vật.
  * Tiền xử lý bằng UF kiểm soát chỉ số mật độ bùn đạt $\text{SDI}_{15} < 2.5\text{--}3.0\text{ %/min}$, ngăn ngừa hiện tượng bẩn màng RO không thuận nghịch.
* Kiểm soát hóa học nghiêm ngặt trước khi cấp vào cụm màng RO:
  * Khử clo dư (Dechlorination): Châm natri bisunfit ($\text{NaHSO}_3$) tại đường ống trước lọc cartridge để trung hòa hoàn toàn clo tự do ($\text{HOCl}, \text{OCl}^-$), ngăn ngừa phân hủy oxy hóa liên kết amide của màng mỏng polyamide:
    $$\text{NaHSO}_3 + \text{HOCl} \rightarrow \text{NaHSO}_4 + \text{HCl}$$
  * Châm chất ức chế cáu cặn (Antiscalant): Bổ sung hóa chất nhóm phosphonate hoặc polycarboxylate ($1.0\text{--}3.0\text{ mg/L}$) để ức chế sự kết tinh vượt quá giới hạn hòa tan của canxi sunfat ($\text{CaSO}_4$), bari sunfat ($\text{BaSO}_4$) và canxi cacbonat ($\text{CaCO}_3$).
  * Lọc tinh an toàn (Fine Cartridge Filtration): Cụm lõi lọc sợi bện polypropylene kích thước $1\text{--}5\ \mu\text{m}$ giữ lại các hạt cặn cơ học sót lại nhằm bảo vệ trực tiếp cánh bơm cao áp và bề mặt màng.

#### 8.4.3 Cụm thẩm thấu ngược cao áp SWRO và Thiết bị thu hồi năng lượng ERD

* Cụm thẩm thấu ngược áp lực cao (High-Pressure RO System) vận hành ở dải áp suất thủy lực cực lớn:
  * Bơm cao áp (High Pressure Pump): Tạo áp suất làm việc $P_f = 55\text{--}70\text{ bar}$ ($5.5\text{--}7.0\text{ MPa}$) để thắng áp suất thẩm thấu và tạo thông lượng dòng thấm.
  * Tỷ lệ thu hồi nước ngọt một cấp ($Y$): Thiết kế ở dải an toàn $Y = 40\%\text{--}50\%$ nhằm kiểm soát nồng độ muối của dòng cô đặc không vượt quá giới hạn bão hòa gây đóng cặn:
    $$Y = \frac{Q_p}{Q_f} \times 100\%$$
    Trong đó $Q_p$ là lưu lượng nước ngọt thành phẩm ($\text{m}^3/\text{h}$), $Q_f$ là lưu lượng nước biển cấp vào ($\text{m}^3/\text{h}$).
  * Hệ thống rửa màng tại chỗ (Cleaning In Place - CIP): Cụm bồn pha hóa chất và bơm tuần hoàn định kỳ súc rửa màng bằng axit nhẹ (hòa tan cặn vô cơ) và dung dịch kiềm yếu (tách màng sinh học và cặn hữu cơ).
* Thiết bị thu hồi năng lượng (Energy Recovery Device - ERD) tối ưu hóa chi phí điện năng:
  * Dòng nước thải cô đặc muối (brine, lưu lượng $Q_c = Q_f - Q_p$) rời màng mang áp suất dư rất cao ($P_c \approx 60\text{--}63\text{ bar}$).
  * Bộ trao đổi áp suất đẳng tích (Isobaric Pressure Exchanger - PX) truyền trực tiếp áp suất từ dòng brine sang một phần dòng nước biển mới với hiệu suất thu hồi $\ge 95\text{--}96\%$.
  * Thiết bị ERD giúp giảm suất tiêu thụ điện riêng ($SEC$) từ $7\text{--}9\text{ kWh/m}^3$ xuống còn $2.5\text{--}3.5\text{ kWh/m}^3$ nước ngọt thành phẩm, tiết kiệm tới $60\%$ tổng điện năng tiêu thụ của nhà máy.
* Sơ đồ thủy lực màng RO thể hiện cơ chế phân tách thành hai dòng sản phẩm và dòng cô đặc xả bỏ:
  * Dòng cấp đi qua màng bán thấm tạo ra dòng thành phẩm tinh khiết và dòng thải muối qua cơ cấu tiết lưu điều chỉnh áp lực.
  * **Hình 10.** Sơ đồ nguyên lý thủy lực và đường dòng quy trình màng thẩm thấu ngược RO
    - <img src="ch08_advanced_treatment/assets/fig_10_p7.jpeg" alt="Hình 10" />
    - **Hình này chứng minh điều gì**
      - Quy trình công nghệ màng RO phân tách hai nhánh: dòng nước sạch qua màng tích trữ vào bình áp và dòng xả cô đặc qua bộ hạn chế lưu lượng (flow restrictor) xả cống.
    - **Từ đâu mà thấy được**
      - Vỏ màng RO số 3 có đường nước tinh khiết đi vào bình chứa Fresh Water Storage Tank và lõi số 4, cùng đường xả đậm đặc đi qua van hạn chế dòng (SLOW) ra cống xả (Waste drain) với quy trình xả súc rửa 30 giây.
* Xử lý chất thải và bảo vệ môi trường biển:
  * Bùn lắng từ công đoạn keo tụ được đưa về bể nén bùn và ép cơ học thành bánh bùn khô (sludge disposal).
  * Dòng muối cô đặc ($TDS \approx 65,000\text{--}75,000\text{ mg/L}$) được xả phân tán ra xa bờ qua hệ thống đầu khuếch tán đa vòi (multi-port diffusers) để hòa trộn nhanh với nước biển tự nhiên.

#### 8.4.4 Dây chuyền hậu xử lý, tái khoáng và đánh bóng nước siêu tinh khiết

* Khử Bo (Boron Removal Process) đáp ứng tiêu chuẩn nước ăn uống và nước tưới:
  * Trong nước biển tự nhiên, Bo tồn tại chủ yếu ở dạng axit boric trung hòa điện tích ($\text{B(OH)}_3$ hoặc $\text{H}_3\text{BO}_3$) với nồng độ $4.0\text{--}5.0\text{ mg/L}$.
  * Phân tử $\text{B(OH)}_3$ có kích thước nhỏ và không mang điện tích nên dễ dàng khuếch tán xuyên qua màng SWRO ở điều kiện $\text{pH}$ trung tính.
  * Để đạt khuyến cáo WHO ($\text{Boron} < 0.5\text{ mg/L}$), nước thành phẩm cấp 1 được kiềm hóa nâng $\text{pH} > 9.5$ để chuyển hóa thành anion borat $\text{B(OH)}_4^-$ rồi đưa qua màng RO cấp 2 (RO Pass 2), hoặc dẫn qua cột nhựa trao đổi ion chuyên dụng chứa gốc chelate glucamine.
* Quá trình tái khoáng hóa và ổn định hóa hóa học (Remineralization & Neutralisation):
  * Nước sau màng RO bị mất gần như toàn bộ khoáng chất, chứa $\text{CO}_2$ hòa tan tự do dẫn đến $\text{pH}$ axit ($5.5\text{--}6.2$) và chỉ số bão hòa Langelier âm sâu ($\text{LSI} < -2.0$), gây ăn mòn mãnh liệt đường ống kim loại.
  * Nước được sục khí $\text{CO}_2$ và dẫn qua tháp tiếp xúc chứa hạt đá vôi canxit ($\text{CaCO}_3$):
    $$\text{CaCO}_3\text{(r)} + \text{CO}_2\text{(k)} + \text{H}_2\text{O} \rightarrow \text{Ca}^{2+} + 2\text{HCO}_3^-$$
  * Phản ứng hòa tan nâng nồng độ ion $\text{Ca}^{2+}$ lên $50\text{--}80\text{ mg/L}$ và độ kiềm lên $40\text{--}70\text{ mg/L}$ (tính theo $\text{CaCO}_3$), đưa $\text{LSI}$ về trạng thái cân bằng an toàn từ $0.0$ đến $+0.2$.
  * Khử trùng lần cuối (Disinfection): Châm clo hoặc chloramine duy trì nồng độ clo dư tự do $0.2\text{--}0.5\text{ mg/L}$ để bảo vệ nước trên mạng lưới đường ống cấp nước sinh hoạt WHO ($TDS < 450\text{ mg/L}$).
* Dây chuyền sản xuất nước kỹ thuật và nước siêu tinh khiết (Polishing Steps):
  * Nước công nghiệp (Process Water): Nước ngọt permeate qua màng RO nước lợ (Brackish Water RO - BWRO) và trung hòa $\text{pH}$ để đạt nồng độ muối siêu thấp $TDS < 50\text{ mg/L}$.
  * Nước khử khoáng (Demi / Pure Water): Dòng nước tiếp tục qua cột trao đổi ion hai tầng (Cation - Anion) hoặc cột hỗn hợp Mixed Bed IX, đưa độ dẫn điện xuống dải $0.1\text{--}10\ \mu\text{S/cm}$.
  * Nước siêu tinh khiết (Ultra Pure Water - UPW): Sử dụng công nghệ điện tích thẩm tách liên tục (Electrodeionization - EDI) kết hợp hạt trao đổi ion đánh bóng chuyên sâu:
    * Điện trở suất đạt ngưỡng giới hạn $10\text{--}18\ \text{M}\Omega\cdot\text{cm}$ ở $25^\circ\text{C}$ (độ dẫn điện cực nhỏ $0.055\text{--}0.1\ \mu\text{S/cm}$).
    * Cung cấp nước siêu sạch cho các ngành công nghệ cao như sản xuất bán dẫn, vi mạch điện tử và dược phẩm.

#### 8.4.5 Cấu trúc thiết bị module hóa và điều khiển chu trình vận hành tự động

* Thiết kế module hóa (Containerization) và nhiệt đới hóa (Tropicalization):
  * Hệ thống lọc màng RO được chế tạo thành các khối khung trượt (skid-mounted) hoặc lắp đặt đồng bộ trong container chịu tải nhằm rút ngắn thời gian xây lắp và chống chịu ăn mòn hơi muối biển.
  * Tích hợp bơm cao áp cánh quạt inox duplex/super duplex chống ăn mòn ion clorua mặn.
* Bộ điều khiển vi máy tính tự động hóa chu trình vận hành:
  * Bo mạch vi điều khiển (Micro Computer Controller) tích hợp các cảm biến áp suất, cảm biến độ dẫn điện và rơ-le ngắt áp cao/áp thấp.
  * Tự động kích hoạt chu trình xả rửa màng tốc độ cao (auto-flush) khi khởi động hoặc sau chu kỳ lọc để cuốn trôi lớp muối cô đặc bám trên bề mặt màng.
  * **Hình 11.** Cấu hình thiết bị phần cứng cụm module thẩm thấu ngược RO tích hợp
    - <img src="ch08_advanced_treatment/assets/fig_11_p8.jpeg" alt="Hình 11" />
    - **Hình này chứng minh điều gì**
      - Cấu trúc module thực tế tích hợp bơm cao áp, cụm vỏ màng RO chịu áp nằm ngang, các cột lọc tiền xử lý đứng và bộ vi điều khiển giám sát chu trình tự động.
    - **Từ đâu mà thấy được**
      - Hình ảnh thiết bị hiển thị bơm tăng áp kim loại phía sau, vỏ màng RO nằm ngang phía trên, 3 cốc lọc trụ phía dưới, hộp điều khiển Micro Computer Controller với đèn LED trạng thái và bình tích áp $12\text{ L}$.
* Hệ thống bình tích áp đệm khí phục vụ phân phối nước liên tục:
  * Do lưu lượng thấm qua màng RO diễn ra liên tục nhưng với tốc độ ổn định, hệ thống trang bị bình áp màng đàn hồi (diaphragm storage tank) để tích trữ nước tinh khiết dưới áp lực khí nén.
  * Khi mở vòi sử dụng (faucet), áp suất túi khí đẩy nước qua lõi lọc tinh than hoạt tính hậu xử lý (post-GAC) mà không cần khởi động tức thời bơm cấp.
  * **Hình 12.** Tổ hợp skid thiết bị hoàn chỉnh và hệ thống trữ áp màng đệm khí
    - <img src="ch08_advanced_treatment/assets/fig_12_p9.jpeg" alt="Hình 12" />
    - **Hình này chứng minh điều gì**
      - Thiết kế module hóa hoàn chỉnh trang bị đầy đủ đường ống kết nối áp lực, van bi đóng ngắt nguồn cấp và bình áp đệm khí phục vụ phân phối nước liên tục.
    - **Từ đâu mà thấy được**
      - Khối thiết bị đồng bộ đi kèm cuộn ống dẫn PE trắng, cờ-lê tháo lắp cốc lọc chuyên dụng, van bi cấp nước và bình áp hình trụ $12\text{ L}$ sơn tĩnh điện màu trắng.

#### 8.4.6 Động học phân tách màng và các phương trình tính toán thủy lực SWRO

* Phương trình thông lượng thể tích nước qua màng ($J_w$):
  * Thông lượng nước tỷ lệ thuận với áp suất động lực thực tế tác dụng lên màng ($\text{NDP}$ - Net Driving Pressure):
    $$J_w = K_w \times \text{NDP} = K_w \times (\Delta P - \Delta \pi)$$
  * Trong đó:
    * $J_w$: Thông lượng dòng thấm qua màng ($\text{L}/(\text{m}^2\cdot\text{h})$ hoặc $\text{LMH}$).
    * $K_w$: Hệ số tính thấm nước của màng ($\text{LMH/bar}$ hoặc $\text{L}/(\text{m}^2\cdot\text{h}\cdot\text{bar})$).
    * $\Delta P$: Chênh lệch áp suất thủy lực qua màng, $\Delta P = P_{\text{feed, avg}} - P_p = \frac{P_f + P_c}{2} - P_p$ ($\text{bar}$).
    * $\Delta \pi$: Chênh lệch áp suất thẩm thấu qua màng, $\Delta \pi = \pi_{\text{feed, avg}} - \pi_p = \frac{\pi_f + \pi_c}{2} - \pi_p$ ($\text{bar}$).
* Phương trình thông lượng muối qua màng ($J_s$):
  * Thông lượng muối vận chuyển qua màng theo cơ chế khuếch tán nồng độ:
    $$J_s = B \times (C_m - C_p)$$
  * Trong đó:
    * $J_s$: Thông lượng muối qua màng ($\text{g}/(\text{m}^2\cdot\text{h})$).
    * $B$: Hệ số tính thấm muối của màng ($\text{LMH}$ hoặc $\text{m/h}$).
    * $C_m$: Nồng độ muối tại sát bề mặt màng ($\text{mg/L}$), bị gia tăng do hiện tượng phân cực nồng độ:
      $$C_m = C_p + (C_{\text{bulk}} - C_p) \exp\left(\frac{J_w}{k_m}\right)$$
      với $k_m$ là hệ số truyền khối chuyển chất ($\text{LMH}$).
    * $C_p$: Nồng độ muối trong dòng nước thấm qua màng ($\text{mg/L}$).
* Phương trình tính toán áp suất thẩm thấu ($\pi$):
  * Tính theo phương trình Van 't Hoff cho dung dịch loãng và bán loãng:
    $$\pi = \phi \times i \times C \times R_{\text{gas}} \times T$$
  * Trong đó:
    * $\phi$: Hệ số thẩm thấu hiệu chỉnh thực nghiệm ($\phi \approx 0.90\text{--}0.93$ đối với nước biển).
    * $i$: Hệ số phân ly ion ($i = 2$ đối với muối $\text{NaCl}$).
    * $C$: Nồng độ mol của muối hòa tan ($\text{mol/m}^3$).
    * $R_{\text{gas}}$: Hằng số khí lý tưởng ($8.314\text{ J}/(\text{mol}\cdot\text{K})$).
    * $T$: Nhiệt độ tuyệt đối của nước biển ($\text{K}$).
* Nồng độ muối trong dòng thải cô đặc ($C_c$):
  * Xác định dựa trên phương trình cân bằng vật chất:
    $$C_c = \frac{Q_f C_f - Q_p C_p}{Q_c} = \frac{C_f - Y C_p}{1 - Y}$$
  * Với tỷ lệ thu hồi $Y = 45\%$ và nước biển đầu vào $C_f = 36,000\text{ mg/L}$, nồng độ dòng cô đặc tăng vọt lên $C_c \approx 65,000\text{--}66,000\text{ mg/L}$.
* Diện tích bề mặt màng yêu cầu ($A_m$) và số lượng phần tử màng ($N_{\text{elem}}$):
  * Tổng diện tích bề mặt màng lọc cần lắp đặt:
    $$A_m = \frac{Q_p \times 1,000}{J_w}$$
  * Số phần tử màng chuẩn kích thước công nghiệp (8040, diện tích $A_{\text{elem}} \approx 40.8\text{ m}^2$/phần tử):
    $$N_{\text{elem}} = \left\lceil \frac{A_m}{A_{\text{elem}}} \right\rceil$$

### 8.5 Quy trình xử lý nước sinh hoạt 4 giai đoạn (Household Tap Water Treatment)

#### 8.5.1 Tổng quan và sơ đồ thủy lực hệ thống lọc POU (System Flowsheet & Hydraulic Layout)

- Mục đích và cấu hình của hệ thống xử lý nước sinh hoạt gia đình (POU - Point of Use):
  - Hệ thống xử lý nước máy cục bộ tại vòi sử dụng công nghệ màng lọc thẩm thấu ngược (RO) kết hợp với các cấp tiền xử lý và hậu xử lý.
  - Quy trình cơ bản gồm 4 giai đoạn truyền thống hoặc nâng cấp thành quy trình 5 giai đoạn hoàn chỉnh (05 stage filter process) nhằm kéo dài tuổi thọ màng và cải thiện chất lượng cảm quan.
- Sơ đồ dòng chảy thủy lực và các thiết bị phụ trợ (Model FS510):
  - Tuyến cấp nước thô: Nước từ đường ống cấp chính (Water mains) đi qua van bi khóa (Ball valve) vào hệ thống.
  - Cảm biến áp suất thấp (Low pressure switch): Đặt tại đầu vào trước lõi lọc số 1 nhằm ngắt nguồn điện để bảo vệ bơm khi áp lực đường ống cấp không đủ hoặc mất nguồn nước.
  - Bơm tăng áp (Booster pump) và công tắc dòng chảy (Flow switch): Đặt trước lõi than hoạt tính nhằm nâng áp suất dòng nước lên mức yêu cầu ($3 - 6\ \text{bar}$) để vượt qua áp suất thẩm thấu của màng RO.
  - Tuyến phân dòng sau màng RO (Stage 4):
    - Dòng nước sạch (Permeate): Đi qua cảm biến áp suất cao (High pressure switch) để tự động dừng bơm khi áp suất bình tích áp đạt ngưỡng đầy, sau đó nạp vào bình chứa nước ngọt (Fresh water storage tank) hoặc đi qua lõi khử mùi vị (Stage 5) ra vòi sử dụng (Tap / Faucet).
    - Dòng nước thải đậm đặc (Concentrate / Brine): Dẫn qua cụm xả rửa thủ công (Manual flush) đi vào đường thoát nước thải (Waste / Drain).
  - **Hình 13.** Sơ đồ nguyên lý dây chuyền xử lý nước cấp gia đình POU (FS510)
    - <img src="ch08_advanced_treatment/assets/fig_13_p10.jpeg" alt="Hình 13" />
    - **Hình này chứng minh điều gì**
      - Hệ thống tích hợp 5 cấp lọc liên hoàn cùng bơm tăng áp và bình tích áp.
    - **Từ đâu mà thấy được**
      - Thứ tự dòng chảy: Nguồn cấp (Water mains) $\to$ (1) $\to$ Bơm $\to$ (2) $\to$ (3) $\to$ (4) $\to$ (5) $\to$ Vòi nước (Faucet).
      - Rẽ nhánh màng RO: Đường thấm (permeate) nạp bình chứa (Storage tank) và lõi (5); đường cô đặc (concentrate) xả thải (Waste drain).

#### 8.5.2 Chi tiết các giai đoạn trong quy trình lọc 5 cấp (Five-Stage Filtration Process)

- Phân loại chức năng 5 giai đoạn xử lý theo sơ đồ chu trình:
  - Hệ thống chia thành 3 nhóm chức năng: Tiền xử lý bảo vệ màng (Giai đoạn 1–3), Khử muối và mầm bệnh bằng màng RO (Giai đoạn 4), và Tinh chế cảm quan (Giai đoạn 5).
  - **Hình 14.** Cấu trúc chi tiết quy trình 5 giai đoạn lọc xử lý nước sinh hoạt
    - <img src="ch08_advanced_treatment/assets/fig_14_p11.jpeg" alt="Hình 14" />
    - **Hình này chứng minh điều gì**
      - Quy trình phân chia ranh giới bảo vệ: Tiền lọc cơ học và hóa học $\to$ màng RO $\to$ khử mùi vị sau bình chứa.
    - **Từ đâu mà thấy được**
      - Nhãn định danh 5 cấp: (1) Sediment filter, (2) GAC filter, (3) Carbon block, (4) RO membrane, (5) Taste reduction.
      - Vị trí các van và công tắc điều khiển: Low pressure switch ở đầu vào, High pressure switch trên đường permeate, Manual flush trên đường waste.

##### 8.5.2.1 Giai đoạn tiền xử lý (Stage 1 – Stage 3: Sediment, GAC, CTO)

- Giai đoạn 1 (Stage 1 | Sediment filter - Lõi lọc cặn):
  - Cấu tạo: Vật liệu sợi polypropylene (PP) nguyên sinh được ép nhiệt đa lớp (melt-blown spun depth cartridge).
  - Kích thước lọc danh định: $5\ \mu\text{m}$.
  - Chức năng: Ngăn chặn và giữ lại các tạp chất cơ học lơ lửng, hạt cát, cặn bùn, và vảy rỉ sét từ đường ống phân phối nước.
  - Tác dụng bảo vệ: Giảm độ đục của nước nguồn, chống gây nghẽn bề mặt cho lõi than hoạt tính và màng RO phía sau.
- Giai đoạn 2 (Stage 2 | Carbon Filter - Lõi than hoạt tính hạt GAC):
  - Cấu tạo: Hạt than hoạt tính gáo dừa dạng rời (Granular Activated Carbon - GAC), kích thước hạt $10 - 30\ \text{mesh}$.
  - Chức năng: Hấp phụ lượng clo dư do khử trùng cấp nước đô thị ($Cl_2, HOCl, OCl^-$), khử các hợp chất hữu cơ hòa tan, dung môi công nghiệp và mùi clo.
  - Tác dụng bảo vệ màng: Loại bỏ triệt để clo tự do nhằm ngăn chặn hiện tượng oxy hóa phá hủy lớp polyamide của màng RO.
- Giai đoạn 3 (Stage 3 | Carbon Block - Lõi khối than nén CTO):
  - Định danh CTO: Viết tắt của Chlorine, Taste, and Odor reduction (khử clo, mùi và vị).
  - Cấu tạo: Chế tạo từ khối than hoạt tính dạng bột đặc (solid carbon block) kết hợp chất kết dính polymer nhiệt dẻo được ép đùn (extrusion), khác hoàn toàn với lõi GAC nén từ hạt than rời.
  - Chức năng kép:
    - Loại bỏ triệt để các tạp chất rắn mịn hơn ($1 - 5\ \mu\text{m}$) và các hóa chất độc hại còn sót lại sau lõi số 2.
    - Giữ lại các hạt bụi mịn carbon (carbon fines) thoát ra từ lõi GAC phía trước.
  - Khả năng chống khuẩn (Bacteriostatic property): Lõi CTO không cho phép vi khuẩn phát triển vì cấu trúc khối đặc không có khoảng trống kẽ hở cho vi sinh vật cư trú hay tạo màng sinh học (biofilm).
  - Yêu cầu bảo trì: Khuyến cáo thay thế lõi CTO đồng thời khi thay thế lõi than hoạt tính hạt GAC để duy trì lưu lượng và độ sạch màng.

##### 8.5.2.2 Giai đoạn khử khoáng thẩm thấu ngược và hậu xử lý (Stage 4 – Stage 5: RO & Post-GAC)

- Giai đoạn 4 (Stage 4 | Filmtec Reverse Osmosis Membrane - Màng thẩm thấu ngược Filmtec):
  - Cấu tạo màng: Màng mỏng composite polyamide (TFC - Thin Film Composite) cuộn tròn xoắn ốc (spiral-wound element).
  - Kích thước khe lọc danh định: Cỡ nanomet ($\approx 0{,}0001\ \mu\text{m} = 0{,}1\ \text{nm}$).
  - Hiệu quả xử lý:
    - Loại bỏ $> 95 - 99\%$ tổng chất rắn hòa tan (TDS), bao gồm ion kim loại nặng ($Pb^{2+}, As^{3+}, Cd^{2+}, Cr^{6+}$), ion vô cơ ($Na^+, Cl^-, SO_4^{2-}, NO_3^-$).
    - Loại bỏ $> 99{,}99\%$ vi khuẩn, virus gây bệnh và các phân tử hữu cơ phức tạp.
  - Vận hành phân dòng: Phân tách nguồn nước đầu vào thành dòng permeate tinh khiết thu hồi và dòng concentrate đậm đặc xả thải ra cống (Waste drain) cuốn trôi các chất bẩn bám trên bề mặt màng.
- Bình tích áp dự trữ nước sạch (Fresh water storage tank):
  - Cấu tạo: Bình tích áp thủy khí chứa màng ngăn cao su butyl (butyl diaphragm) phân cách khoang nước và đệm khí nén.
  - Áp suất nạp khí rỗng (Pre-charge pressure): $35 - 50\ \text{kPa}$ ($5 - 7\ \text{psi}$).
  - Tác dụng: Lưu trữ nước permeate sản xuất chậm từ màng RO ($130 - 200\ \text{mL/min}$), cung cấp tức thời lưu lượng xả lớn ($1{,}5 - 3\ \text{L/min}$) cho vòi uống khi người dùng mở vòi.
- Giai đoạn 5 (Stage 5 | Taste Reduction - Lõi khử mùi vị than hậu xử lý):
  - Cấu tạo: Lõi lọc than hoạt tính gáo dừa dạng thẳng đặt trên đường ống (In-line Post-GAC filter cartridge).
  - Vị trí: Lắp sau bình tích áp, trên đường dẫn nước sạch đến vòi sử dụng (Tap / Faucet).
  - Chức năng: Khử dư vị cao su hoặc mùi tồn đọng sau thời gian lưu trong bình chứa, cân bằng lại vị thanh ngọt tự nhiên của nước uống tinh khiết.

#### 8.5.3 Đặc tính kỹ thuật của lõi khối than nén CTO so với lõi than hạt GAC

- So sánh bản chất cấu trúc và cơ chế lọc:
  - Cấu trúc hạt vs Khối đùn: Lõi GAC chứa hạt than rời chuyển động tự do trong cốc lọc; lõi CTO là khối than bột đúc nguyên khối đồng nhất có kích thước lỗ đồng đều $1 - 5\ \mu\text{m}$.
  - Hiện tượng dòng chảy tắt (Channeling): GAC dễ xuất hiện các khe hở dòng chảy tắt khi áp suất nước biến động, làm giảm hiệu quả xử lý; CTO loại bỏ hoàn toàn nguy cơ dòng chảy tắt nhờ cấu trúc rắn định hình cố định.
  - Tích tụ vi sinh vật: Nước đọng trong khoảng kẽ hở giữa các hạt than của lõi GAC là môi trường thuận lợi cho vi khuẩn dị dưỡng phát triển; CTO không có khoảng trống kẽ hở nên vi khuẩn không thể bám dính và phát triển bên trong lõi.
  - Khả năng lọc cơ học: GAC không có khả năng lọc cặn cơ học và thường phóng thích bụi than; CTO hoạt động như màng lọc cặn tinh cấp độ $1\ \mu\text{m}$, bảo vệ an toàn tuyệt đối cho màng RO.

| Thông số / Đặc tính | Lõi than hoạt tính hạt (GAC Filter - Stage 2) | Lõi khối than nén (CTO Filter - Stage 3) |
|---|---|---|
| Dạng vật liệu | Hạt than hoạt tính rời ($10 - 30\ \text{mesh}$) | Khối composite than bột ép đùn nguyên khối |
| Kích thước lọc cơ học | Không định mức (phóng thích bụi than) | Lọc cặn danh định $1 - 5\ \mu\text{m}$ |
| Nguy cơ tạo dòng chảy tắt | Cao khi chịu áp lực xung động | Bằng không nhờ khối ma trận rắn cố định |
| Khả năng ức chế vi khuẩn | Thấp (kẽ hở tạo điều kiện sinh khối bám dính) | Cao (khối đặc triệt tiêu khoảng trống kẽ hở) |
| Vai trò chính trong hệ thống | Hấp phụ lượng lớn clo dư và hợp chất hữu cơ | Khử hóa chất tinh, giữ bụi than và lọc cặn bảo vệ màng |
| Chu kỳ thay thế khuyến cáo | $6 - 12\ \text{tháng}$ | $6 - 12\ \text{tháng}$ (thay đồng thời cùng GAC) |

#### 8.5.4 Quy trình vận hành, bảo trì và thay thế định kỳ (Operation & Preventive Maintenance)

- Chu kỳ thay thế các lõi lọc trong hệ thống:
  - Lõi lọc cặn số 1 (Sediment filter): Thay thế sau $3 - 6\ \text{tháng}$ (tùy độ đục nước nguồn).
  - Lõi than hoạt tính số 2 (GAC filter) và Lõi khối than nén số 3 (CTO filter): Thay thế đồng thời sau $6 - 12\ \text{tháng}$ để đảm bảo nồng độ clo tự do trước màng luôn đạt $< 0{,}05\ \text{mg/L}$.
  - Màng lọc thẩm thấu ngược số 4 (Filmtec RO membrane): Thay thế sau $24 - 36\ \text{tháng}$ ($2 - 3\ \text{năm}$) khi hiệu suất loại bỏ muối giảm xuống dưới $90\%$ hoặc lưu lượng thấm sụt giảm mạnh.
  - Lõi than hậu xử lý số 5 (Post-GAC taste reduction): Thay thế sau $12\ \text{tháng}$.
- Quy trình súc rửa và kiểm soát áp lực:
  - Thao tác súc rửa màng (Manual flush): Mở van xả rửa thủ công định kỳ $1 - 2\ \text{tuần/lần}$ trong thời gian $2 - 3\ \text{phút}$ để cuốn trôi lớp cáu cặn khoáng bám trên bề mặt màng RO ra đường xả thải.
  - Kiểm tra áp suất đệm khí bình tích áp: Đo áp suất khí qua van Schrader khi bình rỗng hoàn toàn, duy trì ở mức chuẩn $35 - 50\ \text{kPa}$ ($5 - 7\ \text{psi}$) để tránh hiện tượng lưu lượng vòi yếu dù bình đầy nước.

### 8.6 Hệ thống lọc nước sinh hoạt gia đình 5 cấp (5-Stage Household Filter Process)

#### 8.6.1 Cấu hình tổng quan và cụm thiết bị phần cứng (Hardware Overview & System Components)

- Khái niệm và mục đích của hệ thống lọc POU gia đình:
  - Hệ thống xử lý nước tại điểm sử dụng (Point-of-Use - POU) chuyển đổi trực tiếp nước máy sinh hoạt thành nước uống tinh khiết đạt tiêu chuẩn nước uống đóng chai.
  - Thiết bị loại bỏ độ đục, hóa chất khử trùng, hợp chất hữu cơ dễ bay hơi, kim loại nặng, ion vô cơ hòa tan và vi sinh vật gây bệnh.
  - Cấu trúc tiêu chuẩn bao gồm giá đỡ kim loại, 3 cốc lọc thô đặt dọc, bơm trợ lực, vỏ màng RO nằm ngang, bình tích áp chứa nước sạch và vòi lấy nước độc lập.
- Thiết kế phần cứng mô-đun hóa (Model FS520 / FS510):
  - Giá treo khung thép sơn tĩnh điện: Cố định 3 cốc lọc kích thước $10\ \text{inch}$ ($254\ \text{mm}$) ở tầng dưới và nâng đỡ cụm bơm áp lực, vỏ màng, lõi khoáng ở tầng trên.
  - Cốc lọc số 1 trong suốt (Clear housing): Cho phép người dùng quan sát mức độ bám bẩn của lõi lọc bông để xác định thời điểm thay thế trực quan.
  - Cốc lọc số 2 và 3 đục mờ (Opaque white/blue housings): Ngăn cản ánh sáng trực tiếp xuyên thấu, triệt tiêu nguy cơ phát triển tảo và rêu bề mặt bên trong cốc than.
  - Bảng điều khiển vi xử lý (Micro Computer Controller): Tích hợp hệ thống đèn LED chỉ thị nguồn điện, trạng thái bơm, cảnh báo rò rỉ nước, tự động sục rửa màng và đồng hồ đếm chu kỳ thay lõi.
  - Bình tích áp thủy khí (Accumulator Tank): Bình thép bọc màng polymer dung tích danh định $12\ \text{L}$ ($3{,}2\ \text{gal}$), lưu trữ nước tinh khiết dưới áp suất khí nén để cấp nước nhanh khi mở vòi.
  - **Hình 12.** Cụm thiết bị phần cứng hệ thống lọc nước RO gia đình 5 cấp (Model FS520)
#### 8.6.2 Sơ đồ nguyên lý và chu trình dòng thủy lực (Hydraulic Flowsheet & Circuit Architecture)

- Phân vùng chức năng trong chu trình thủy lực:
  - Tuyến nạp nước thô và bảo vệ bơm: Nước từ nguồn cấp chính (Water mains) đi qua van trích nước bi (Feed adapter ball valve) và cảm biến áp suất thấp (Low Pressure Switch).
  - Tuyến tạo áp qua màng: Dòng nước sau lọc cặn thô được bơm tăng áp nén lên áp suất vận hành $4 - 7\ \text{bar}$ ($60 - 100\ \text{psi}$) trước khi đẩy qua 2 cấp than hoạt tính và nạp vào vỏ màng RO.
  - Tuyến phân dòng màng RO: Màng RO tách dòng nạp thành dòng thấm tinh khiết (permeate) và dòng thải cô đặc (concentrate / brine).
  - Tuyến nước sạch và tích trữ áp lực: Dòng permeate đi qua van một chiều, cảm biến áp suất cao (High Pressure Switch), rồi nạp vào bình tích áp và đi qua lõi khử mùi vị (Stage 5) tới vòi uống.
  - Tuyến xả thải và kiểm soát dòng cô đặc: Dòng cô đặc đi qua cụm van tiết lưu hạn chế lưu lượng (Flow Restrictor) kết hợp van sục rửa thủ công (Manual Flush Valve) dẫn ra đường thoát cống (Waste / Drain).
  - **Hình 13.** Sơ đồ nguyên lý thủy lực và chu trình dòng chảy hệ thống RO 5 cấp (Model FS510)
#### 8.6.3 Chi tiết kỹ thuật 5 cấp lọc chức năng (Detailed Engineering of 5 Filtration Stages)

- Phân bố ranh giới xử lý của 5 cấp lọc:
  - Cụm tiền xử lý (Giai đoạn 1 – 3): Loại bỏ hạt cơ học lơ lửng, keo tụ, clo tự do và hóa chất hữu cơ nhằm bảo vệ đầy đủ màng thẩm thấu ngược.
  - Cụm khử muối sâu (Giai đoạn 4): Tách bỏ muối khoáng hòa tan, ion kim loại nặng và mầm bệnh vi sinh vật qua lớp màng chọn lọc phân tử.
  - Cụm hoàn thiện cảm quan (Giai đoạn 5): Tinh chế chất lượng cảm quan, hấp phụ khí hòa tan và khử mùi dư sau bình chứa.
  - **Hình 14.** Cấu trúc quy trình 5 giai đoạn lọc xử lý nước sinh hoạt (05 Stage Filter Process)
##### 8.6.3.1 Cụm tiền xử lý 3 cấp: Sediment (PP), Than hoạt tính hạt (GAC) và Khối than nén (CTO)

- Giai đoạn 1 | Lõi lọc cặn cơ học (Stage 1: Sediment Filter):
  - Cấu tạo: Vật liệu sợi bông xốp polypropylene (PP) nguyên sinh được nung chảy và thổi sợi đa lớp (melt-blown spun polypropylene cartridge).
  - Kích thước khe hở danh định: $5\ \mu\text{m}$.
  - Cơ chế lọc: Cơ chế lọc sâu (depth filtration). Mật độ sợi tăng dần từ lớp ngoài vào trong lõi, giữ các hạt cặn theo độ sâu của lớp vật liệu.
  - Đối tượng loại bỏ: Rỉ sét đường ống, bùn đất, cát mịn, tảo lơ lửng và chất không tan có đường kính $> 5\ \mu\text{m}$.
  - Mục tiêu xử lý: Giảm chỉ số độ đục nước nguồn về mức $\text{NTU} < 1$, bảo vệ bơm áp lực và chống tắc nghẽn bề mặt lõi than phía sau.
  - Tuổi thọ định mức: $3 - 6\ \text{tháng}$ (tùy thuộc tải lượng chất rắn lơ lửng của nước cấp).
- Giai đoạn 2 | Lõi than hoạt tính dạng hạt (Stage 2: Granular Activated Carbon - GAC):
  - Cấu tạo: Chứa hạt than hoạt tính gáo dừa dạng hạt rời (granular activated coconut shell carbon), cấp hạt $10 - 30\ \text{mesh}$.
  - Diện tích bề mặt riêng: $900 - 1.100\ \text{m}^2/\text{g}$, cung cấp dung lượng hấp phụ lớn nhờ hệ thống vi mao quản (micropores $< 2\ \text{nm}$).
  - Cơ chế xử lý:
    - Hấp phụ vật lý các hợp chất hữu cơ dễ bay hơi (VOCs), thuốc bảo vệ thực vật, trihalomethanes ($\text{THMs}$) và chất gây mùi vị.
    - Khử hóa học clo dư tự do ($Cl_2, HOCl, OCl^-$) thành ion clorua vô hại theo phản ứng khử trên bề mặt carbon:
      $$\text{C}^* + 2\text{HOCl} \to \text{CO}_2 + 2\text{H}^+ + 2\text{Cl}^-$$
  - Mục tiêu bảo vệ màng RO: Đưa nồng độ clo dư tự do về mức $< 0{,}05\ \text{mg/L}$. Màng mỏng polyamide TFC bị clo oxy hóa và phá hủy liên kết amide không thể đảo ngược khi nồng độ clo vượt ngưỡng $0{,}1\ \text{mg/L}$.
  - Nhược điểm vật lý: Lõi hạt rời dễ phát tán bụi than mịn (carbon fines) xuôi dòng và dễ hình thành dòng chảy tắt (channeling) khi chịu xung áp.
  - Tuổi thọ định mức: $6 - 12\ \text{tháng}$.
- Giai đoạn 3 | Lõi khối than nén ép đùn (Stage 3: Carbon Block Filter - CTO):
  - Ý nghĩa ký hiệu CTO: Chlorine, Taste, and Odor reduction (chuyên biệt khử clo dư, mùi vị tồn dư và cặn mịn).
  - Cấu tạo vật liệu: Hỗn hợp bột than hoạt tính siêu mịn kết hợp keo kết dính polymer nhiệt dẻo được ép nén dưới nhiệt độ và áp suất cao thành khối rắn đồng nhất (extruded solid carbon block).
  - Cấu trúc vật lý khác biệt so với GAC:
    - GAC cấu thành từ các hạt than rời tự do nén ép cơ học đơn thuần bên trong vỏ nhựa.
    - CTO là khối xốp đặc rắn nguyên khối, không có khoang rỗng tự do giữa các hạt.
  - Chức năng kép:
    - Hấp phụ hóa học: Tiếp tục hấp phụ triệt để dư lượng clo và hóa chất hữu cơ còn sót lại sau lõi GAC.
    - Lọc cơ học tinh: Khe hở danh định $1 - 5\ \mu\text{m}$ giữ lại toàn bộ hạt cặn mịn và chặn triệt để bụi than mịn thoát ra từ lõi GAC số 2.
  - Đặc tính ức chế vi khuẩn (Bacteriostatic Property):
    - Cấu trúc khối carbon nén đặc triệt tiêu các khoang kẽ hở vĩ mô và vùng nước tù đọng.
    - Vi khuẩn không có không gian để định cư, phân chia tế bào hoặc hình thành màng màng sinh học (biofilm) như trong đệm than hạt rời.
  - Yêu cầu thay thế đồng bộ: Luôn thay thế lõi CTO đồng thời với lõi GAC ($6 - 12\ \text{tháng}$) nhằm duy trì chỉ số mật độ bùn ($\text{SDI}_{15} < 3 - 5$) cho dòng nạp màng RO.

| Tiêu chí kỹ thuật | Lõi than hoạt tính hạt (GAC Filter - Cấp 2) | Lõi khối than nén (CTO Filter - Cấp 3) |
|---|---|---|
| Dạng vật liệu cấu thành | Hạt than gáo dừa tự do ($10 - 30\ \text{mesh}$) | Bột than hoạt tính liên kết keo ép đùn nguyên khối |
| Cấu trúc không gian hạt | Đệm hạt rời rạc, có khe hở kẽ hạt lớn | Khối xốp rắn đồng nhất, triệt tiêu khe hở rỗng |
| Khả năng lọc cặn cơ học | Kém; phát tán bụi than mịn vào dòng nước | Tốt; cấp lọc cơ học định mức $1 - 5\ \mu\text{m}$ |
| Rủi ro tạo dòng chảy tắt (Channeling) | Cao khi áp suất nguồn nước biến động | Bằng không nhờ ma trận dẫn dòng cố định |
| Nguy cơ phát triển màng sinh học | Cao do nước đọng tại các kẽ hở hạt rời | Rất thấp vì không có không gian cho khuẩn bám dính |
| Chức năng chính | Hấp phụ thô clo dư và hóa chất hữu cơ | Khử hóa chất tinh, giữ bụi than và lọc cặn bảo vệ màng |
| Chu kỳ thay thế | $6 - 12\ \text{tháng}$ | $6 - 12\ \text{tháng}$ (khuyến cáo thay đồng bộ với GAC) |

##### 8.6.3.2 Cấp khử muối màng thẩm thấu ngược Filmtec RO và Cơ chế phân tách (Stage 4)

- Cấu tạo màng thẩm thấu ngược Filmtec (Filmtec Reverse Osmosis Membrane):
  - Cấu trúc màng mỏng composite (Thin-Film Composite - TFC): Gồm 3 lớp liên kết chặt chẽ:
    - Lớp nền vải không dệt polyester chịu lực (độ dày $\approx 120\ \mu\text{m}$).
    - Lớp đệm vi màng xốp polysulfone (độ dày $\approx 40\ \mu\text{m}$).
    - Lớp rào cản siêu mỏng polyamide thơm chọn lọc (aromatic polyamide active layer, độ dày $\approx 0{,}2\ \mu\text{m}$).
  - Dạng cuộn xoắn ốc (Spiral-wound element): Các túi màng phẳng (membrane leaves) ghép đôi bọc lưới dẫn dòng thấm (permeate spacer) cuộn tròn quanh ống thu nước trung tâm (permeate core tube), ngăn cách bởi lưới dẫn dòng nạp (feed spacer mesh).
  - Kích thước lỗ lọc danh định: Cỡ hạ nanomet ($\approx 0{,}1 - 0{,}2\ \text{nm} = 0{,}0001\ \mu\text{m}$).
- Động học và cơ chế phân tách phân tử:
  - Cơ chế hòa tan - khuếch tán (Solution-Diffusion Model): Nước và chất tan hòa tan vào lớp polyme polyamide đặc sít rồi khuếch tán qua màng dưới gradient thế hóa:
    $$J_w = A \cdot (\Delta P - \Delta \pi)$$
    $$J_s = B \cdot (C_m - C_p)$$
    Trong đó:
    - $J_w$: Thông lượng nước thấm ($\text{L}/(\text{m}^2\cdot\text{h})$).
    - $A$: Hệ số thấm nước của màng ($\text{L}/(\text{m}^2\cdot\text{h}\cdot\text{bar})$).
    - $\Delta P$: Độ chênh áp lực thủy tĩnh qua màng ($\text{bar}$).
    - $\Delta \pi$: Độ chênh áp suất thẩm thấu giữa dung dịch cấp và dòng thấm ($\text{bar}$).
    - $J_s$: Thông lượng chất tan qua màng ($\text{g}/(\text{m}^2\cdot\text{h})$).
    - $B$: Hệ số thấm chất tan của màng ($\text{m/h}$).
    - $C_m, C_p$: Nồng độ chất tan tại bề mặt màng và trong dòng thấm ($\text{mg/L}$).
  - Hiệu ứng loại trừ tĩnh điện Donnan (Donnan Exclusion): Lớp polyamide mang điện tích âm yếu trong môi trường nước trung tính ($\text{pH } 6 - 8$), giúp đẩy lùi các ion mang điện tích âm (anion) và giữ lại các cation tương ứng để bảo toàn trung hòa điện tích.
- Hiệu suất ngăn chặn chất ô nhiễm (Rejection Efficiency):
  - Tách bỏ tổng chất rắn hòa tan (TDS): Hiệu suất loại bỏ đạt $95 - 99\%$.
  - Tách bỏ ion kim loại nặng và độc tố: Loại bỏ $> 96 - 99\%$ chì ($Pb^{2+}$), asen ($As^{3+}, As^{5+}$), cadmi ($Cd^{2+}$), crom ($Cr^{6+}$), thủy ngân ($Hg^{2+}$) và nitrat ($NO_3^-$).
  - Tách bỏ vi sinh vật: Rào cản tuyệt đối với vi khuẩn ($> 99{,}99\%$), virus ($> 99{,}99\%$), ký sinh trùng nang ($Giardia, Cryptosporidium$), độc tố nội sinh pyrogens và vi nhựa.
- Thủy lực dòng chảy màng RO:
  - Dòng cấp (Feed) đi theo hướng dọc trục trong khe giữa các tấm màng (cross-flow pattern).
  - Dòng thấm (Permeate) thẩm thấu xuyên qua lớp màng, chảy xoắn ốc vào ống trung tâm thu nước sạch, dẫn tới bình chứa và vòi uống.
  - Dòng cô đặc (Concentrate / Brine) mang theo toàn bộ ion khoáng và tạp chất bị giữ lại, quét sạch liên tục bề mặt màng và xả ra đường thoát cống.
  - Tỷ lệ thu hồi nước sạch gia đình:
    $$Y = \frac{Q_{\text{permeate}}}{Q_{\text{feed}}} \times 100\% \approx 20 - 30\%$$
    Tỷ lệ nước thải/nước sạch tương ứng dao động từ $2{,}5:1$ đến $4:1$.
  - Tuổi thọ định mức: $24 - 36\ \text{tháng}$ (tương đương công suất $15.000 - 20.000\ \text{L}$).

##### 8.6.3.3 Cấp tinh chế cảm quan và tái tạo vị Post-Carbon T33 (Stage 5)

- Cấu tạo và vị trí lắp đặt (Stage 5: Taste Reduction Filter):
  - Thiết kế dạng ống kín inline (In-line cartridge model T33): Cổng kết nối nhanh $1/4\ \text{inch}$ đặt ngay trước vòi lấy nước.
  - Vật liệu: Than hoạt tính gáo dừa độ tinh khiết cao rửa axit (acid-washed coconut shell GAC), chỉ số iod $> 1.050\ \text{mg/g}$.
  - Vị trí trong hệ thống: Lắp đặt sau ngã rẽ bình tích áp, trên đường dẫn nước sạch trực tiếp đến vòi uống (Tap / Faucet).
- Cơ chế và chức năng xử lý:
  - Lọc đánh bóng nước tinh khiết (Polishing Filtration): Hấp phụ triệt để lượng vết các hợp chất hữu cơ bay hơi sinh ra trong quá trình nước tiếp xúc kéo dài với màng cao su butyl bên trong bình tích áp.
  - Khử mùi lạ và khí hòa tan: Loại bỏ khí hòa tan gây mùi ngái, mùi clo dư vi lượng hoặc vị chua nhẹ do khử hết khoáng của màng RO.
  - Cải thiện vị giác: Cân bằng độ $\text{pH}$ nhẹ và hoàn thiện vị thanh ngọt tự nhiên cho nước uống trực tiếp.
  - Tuổi thọ định mức: $12\ \text{tháng}$ (hoặc tương đương dung tích $5.000 - 7.500\ \text{L}$).

#### 8.6.4 Cụm thiết bị áp lực và cơ chế tự động hóa thủy lực (Hydraulic Pressure & Automated Control Loop)

- Bơm tăng áp thủy lực (Hydraulic Booster Pump):
  - Chủng loại: Bơm màng dịch chuyển tích cực (positive displacement diaphragm pump) vận hành bằng động cơ điện một chiều $24\ \text{VDC}$ đi kèm bộ đổi nguồn (adapter).
  - Thông số vận hành: Áp suất tạo ra $4 - 7\ \text{bar}$ ($60 - 100\ \text{psi}$), lưu lượng bơm $0{,}8 - 1{,}5\ \text{L/min}$.
  - Chức năng kỹ thuật: Áp lực mạng lưới cấp nước sinh hoạt thường thấp ($1 - 2\ \text{bar}$), không đủ tạo áp lực truyền động tịnh ($\Delta P - \Delta \pi$). Bơm nâng áp suất dòng nước vượt qua áp suất thẩm thấu và thắng trở lực màng.
- Rơ-le áp suất thấp (Low Pressure Switch - LPS):
  - Cấu tạo: Công tắc tiếp điểm điện loại thường mở (Normally Open - NO).
  - Vị trí: Đặt tại đầu vào trước lõi số 1 hoặc giữa lõi 1 và bơm.
  - Áp suất ngắt: Cài đặt ở ngưỡng $0{,}2 - 0{,}4\ \text{bar}$ ($3 - 5\ \text{psi}$).
  - Cơ chế bảo vệ: Khi mất nước nguồn hoặc áp lực cấp yếu (bị nghẽn đường ống), áp suất giảm dưới ngưỡng ngắt mạch điện, ngắt điện cuộn hút bảo vệ bơm chống chạy khô (dry run), cháy cuộn dây và xâm thực cánh bơm.
- Rơ-le áp suất cao (High Pressure Switch - HPS):
  - Cấu tạo: Công tắc tiếp điểm điện loại thường đóng (Normally Closed - NC).
  - Vị trí: Lắp đặt trên đường nước tinh khiết permeate, sau van một chiều và trước bình tích áp.
  - Áp suất tác động: Ngưỡng ngắt áp $2{,}5 - 3\ \text{bar}$ ($35 - 45\ \text{psi}$); ngưỡng đóng lại $1{,}5 - 2\ \text{bar}$ ($22 - 30\ \text{psi}$).
  - Cơ chế điều khiển:
    - Khi bình tích áp nạp đầy nước hoặc đóng vòi lấy nước, áp suất dòng permeate tăng chạm ngưỡng $2{,}5 - 3\ \text{bar}$. Rơ-le HPS mở tiếp điểm, ngắt mạch cấp điện cho bơm dừng hoạt động.
    - Khi người dùng mở vòi uống nước, áp suất bình tích áp tụt giảm xuống dưới $1{,}5 - 2\ \text{bar}$. Tiếp điểm rơ-le HPS tự động đóng lại, khởi động bơm nạp nước bù.
- Van cơ tự động ngắt 4 cửa (Auto-Shutoff Valve - ASV) và Van một chiều màng (Check Valve):
  - Van một chiều màng RO (Permeate Check Valve):
    - Lắp cố định tại cổng thoát nước sạch permeate của vỏ màng RO.
    - Chức năng: Ngăn dòng nước mang áp suất cao từ bình tích áp dội ngược vào ống thu nước trung tâm màng RO khi bơm dừng. Áp suất dội ngược sẽ làm bung tách các lớp màng composite (membrane delamination) và phá hủy hoàn toàn lõi màng.
  - Van cơ ngắt tự động 4 cửa (Auto-Shutoff 4-Way Valve - ASV):
    - Cấu tạo: Thân van chứa màng đàn hồi phân tách khoang áp suất cao (nước permeate) và khoang áp suất nguồn (dòng cấp sau lõi tiền xử lý).
    - Tỷ số áp suất đóng ngắt: Thiết kế theo tỷ lệ tiết diện màng cơ học xấp xỉ $2:1$ đến $1{,}5:1$.
    - Cơ chế ngắt dòng: Khi áp suất permeate đạt khoảng $60 - 67\%$ áp suất dòng cấp, lực đẩy màng đàn hồi thắng lực lò xo, đóng kín cửa cấp nước vào màng RO.
    - Vai trò then chốt: Chấm dứt hiện tượng nước cấp tiếp tục rò rỉ chảy qua màng xả lãng phí ra cống thải khi máy đã ngắt điện (trong các cấu hình không sử dụng van điện từ).
- Bình tích áp thủy khí chứa nước sạch (Permeate Hydro-Pneumatic Accumulator Tank):
  - Cấu tạo: Vỏ bình bằng thép cán nguội hoặc nhựa composite cao cấp, dung tích $12\ \text{L}$ ($3{,}2\ \text{gal}$). Bên trong chứa bóng khí cao su butyl (butyl bladder) chia bình làm 2 khoang cách ly tuyệt đối: khoang khí nén dưới đáy và khoang nước sạch ở phía trên.
  - Áp suất nạp khí tiêu chuẩn (Pre-charge pressure): $35 - 50\ \text{kPa}$ ($5 - 7\ \text{psi}$) khi bình rỗng hoàn toàn, bơm qua đầu van xe đạp (Schrader valve).
  - Nguyên lý nén đệm khí:
    - Khi lọc, màng RO tạo nước sạch rất chậm ($100 - 200\ \text{mL/min}$). Nước nạp vào khoang nước ép màng cao su nén khoang khí lại, tích trữ thế năng áp lực đến khi áp suất đạt $2{,}5 - 3\ \text{bar}$.
    - Khi mở vòi uống, đệm khí giãn nở tức thời đẩy màng cao su phóng luồng nước sạch ra vòi với lưu lượng xả đạt $1{,}5 - 3\ \text{L/min}$, đáp ứng nhu cầu rót nước nhanh chóng của người sử dụng.
- Cụm điều tiết dòng thải (Flow Restrictor) và Van sục rửa màng (Manual Flush Valve):
  - Van tiết lưu hạn chế lưu lượng (Flow Restrictor):
    - Ống mao dẫn hoặc lỗ tiết lưu chuẩn (ký hiệu định mức $300 - 450\ \text{mL/min}$).
    - Tạo áp phản hồi (backpressure) bên trong vỏ màng để duy trì áp lực qua màng, đồng thời điều hòa tỷ lệ dòng thải cuốn trôi cặn bẩn bám dính.
  - Cụm van sục rửa màng thủ công (Manual Flush):
    - Đặt bắt cầu song song với van tiết lưu.
    - Khi người dùng mở van sục rửa, toàn bộ dòng nước bỏ qua van tiết lưu, xả tự do với vận tốc dòng chảy lớn cuốn phăng lớp cặn phân cực bám trên bề mặt màng RO ra cống.

#### 8.6.5 Vận hành, cân bằng thủy lực và quy chuẩn bảo dưỡng thay thế (Operation & Preventative Maintenance)

- Tổng hợp thông số kỹ thuật và vai trò của 5 cấp lọc:

| Cấp lọc | Tên cấp lọc & Vật liệu | Kích thước danh định / Vật liệu | Chức năng công nghệ cốt lõi | Chu kỳ thay thế khuyến cáo |
|---|---|---|---|---|
| **Cấp 1** | Lõi lọc cặn (Sediment Filter) | Sợi polypropylene đùn nhiệt ($5\ \mu\text{m}$) | Giữ cát, bùn, gỉ sét, cặn lơ lửng, hạ độ đục $\text{NTU} < 1$ | $3 - 6\ \text{tháng}$ |
| **Cấp 2** | Than hoạt tính hạt (GAC Filter) | Than gáo dừa dạng hạt ($10 - 30\ \text{mesh}$) | Hấp phụ clo dư ($< 0{,}05\ \text{mg/L}$), khử thuốc trừ sâu, dung môi, mùi | $6 - 12\ \text{tháng}$ |
| **Cấp 3** | Khối than nén (CTO Filter) | Khối bột than ép đùn ($1 - 5\ \mu\text{m}$) | Khử hóa chất tinh, giữ bụi than, chống màng vi sinh vật | $6 - 12\ \text{tháng}$ |
| **Cấp 4** | Màng Filmtec RO (RO Membrane) | Polyamide composite màng mỏng ($0{,}1\ \text{nm}$) | Loại bỏ $> 95 - 99\%$ TDS, ion kim loại nặng, vi khuẩn, virus | $24 - 36\ \text{tháng}$ |
| **Cấp 5** | Than tinh chế vị (Post-GAC T33) | Than hoạt tính gáo dừa rửa axit dạng inline | Đánh bóng cảm quan, khử mùi tiếp xúc bóng cao su, tạo vị ngọt | $12\ \text{tháng}$ |

- Quy chuẩn vận hành và kiểm tra bảo dưỡng định kỳ:
  - Thao tác súc rửa màng RO (Flushing):
    - Mở van sục rửa màng thủ công $1 - 2\ \text{lần/tuần}$, duy trì trong $3 - 5\ \text{phút}$ để cuốn trôi lớp cáu cặn muối canxi cacbonat và màng sinh học bám dính.
  - Kiểm tra và tái nạp áp suất bình tích áp:
    - Khi nhận thấy vòi nước chảy chậm dù bình tích áp đầy nặng, khóa van bình, xả kiệt nước trong khoang nước.
    - Dùng đồng hồ đo áp suất qua van Schrader. Nếu áp suất giảm dưới $0{,}3\ \text{bar}$ ($4\ \text{psi}$), dùng bơm tay nạp lại về ngưỡng chuẩn $35 - 50\ \text{kPa}$ ($5 - 7\ \text{psi}$).
  - Đo lường và kiểm soát chỉ số TDS (Total Dissolved Solids):
    - Dùng bút đo TDS kiểm tra định kỳ nguồn nước thô ($TDS_{\text{in}}$) và nước thành phẩm tại vòi ($TDS_{\text{out}}$).
    - Tính toán tỷ lệ loại bỏ muối:
      $$R = \left(1 - \frac{TDS_{\text{out}}}{TDS_{\text{in}}}\right) \times 100\%$$
    - Khi tỷ lệ $R < 90\%$ hoặc giá trị $TDS_{\text{out}} > 50\ \text{ppm}$ đối với nước máy thông thường, màng RO đã suy thoái và cần phải thay mới.

