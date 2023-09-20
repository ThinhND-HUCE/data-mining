# Bài tập
## Chương 2. Dữ liệu, đo lường và xử lý dữ liệu
<ol>
  <li>(2.2) Giả sử dữ liệu phân tích bao gồm thuộc tính tuổi. Các giá trị tuổi cho các bộ dữ liệu được sắp xếp theo thứ tự tăng dần là 13, 15, 16, 16, 19, 20, 20, 21, 22, 22, 25, 25, 25, 25, 30, 33, 33, 35, 35, 35, 35, 36, 40, 45, 46, 52, 70.
    <ol type="a">
      <li>Tìm <i>trung bình</i>, <i>trung vị</i> của dữ liệu</li>
      <li>Tìm <i>mode</i> của dữ liệu. Nhận xét về tính đa mode của dữ liệu (tức là hai mode, ba mode, v.v.)</li>
      <li>Tìm <i>trung điểm</i> của dữ liệu</li>
      <li>Tìm (thô) tứ phân vị thứ nhất (Q1) và tứ phân vị thứ ba (Q3) của dữ liệu</li>
      <li>Cho tóm tắt năm số liệu của dữ liệu</li>
      <li>Vẽ biểu đồ hộp của dữ liệu</li>
    </ol>
  </li>

  <li>(2.3) Giả sử các giá trị cho một tập dữ liệu được nhóm thành các khoảng. Các khoảng và tần số tương ứng như sau
    <table border="1"; align="center">
      <tr> <th>age</th> <th>frequency</th> </tr>
      <tr> <td>1-5</td> <td>200</td> </tr>
      <tr> <td>6-15</td> <td>450</td> </tr>
      <tr> <td>16-20</td> <td>300</td> </tr>
      <tr> <td>21-50</td> <td>1500</td> </tr>
      <tr> <td>51-80</td> <td>700</td> </tr>
      <tr><td>81-110</td><td>44</td></tr>
    </table>
    Tính một trung vị xấp xỉ cho dữ liệu
  </li>

  <li>(2.7) Giả sử một bệnh viện đã kiểm tra dữ liệu về tuổi và lượng mỡ cơ thể cho 18 người trưởng thành được chọn ngẫu nhiên với kết quả sau
    <table border="1"; align="center">
      <tr> <th>tuổi</th> <td>23</td> <td>23</td> <td>27</td> <td>27</td> <td>39</td>
        <td>41</td> <td>47</td> <td>49</td> <td>50</td>
      </tr>
      <tr><th>%mỡ</th> <td>9.5</td> <td>26.5</td> <td>7.8</td> <td>17.8</td> <td>31.4</td>
        <td>25.9</td> <td>27.4</td> <td>27.2</td> <td>31.2</td>
      </tr>
      <tr>
        <th>tuổi</th><td>52</td> <td>54</td> <td>54</td> <td>56</td> <td>57</td>
        <td>58</td> <td>58</td> <td>60</td> <td>61</td>
      </tr>
      <tr>
        <th>%mỡ</th> <td>34.6</td> <td>42.5</td> <td>28.8</td> <td>33.4</td> <td>30.2</td>
        <td>34.1</td> <td>32.9</td> <td>41.2</td> <td>35.7</td>
      </tr>
    </table>
    <ol type="a">
      <li>Tính trung bình, trung vị và độ lệch chuẩn của <i>tuổi</i> và <i>%mỡ</i></li>
      <li>Vẽ biểu đồ hộp cho <i>tuổi</i> và <i>%mỡ</i></li>
      <li>Vẽ <i>biểu đồ phân tán</i> và <i>biểu đồ phân vị kép</i> dựa trên hai biến này</li>
    </ol>
  </li>

  <li>(2.9) Cho hai đối tượng được biểu diễn bởi các bộ dữ liệu (22, 1, 42, 10) và (20, 0, 36, 8)
    <ol type="a">
      <li>Tính <i>khoảng cách Euclide</i> giữa hai đối tượng</li>
      <li>Tính <i>khoảng cách Manhattan</i> giữa hai đối tượng</li>
      <li>Tính <i>khoảng cách Minkowski</i> giữa hai đối tượng, với $h=3$</li>
      <li>Tính <i>khoảng cách supremum</i> giữa hai đối tượng</li>
    </ol>
  </li>

  <li>(2.11) Việc xác định và lựa chọn các thước đo tính tương đồng trong phân tích dữ liệu là rất quan trọng. Tuy nhiên, nói chung không có thước đo nào có ưu thế hơn hẳn. Kết quả có thể thay đổi tùy theo thước đo được sử dụng. Tuy nhiên, các thước đo tưởng chừng như khác nhau nhưng sau một số phép biến đổi có thể tương đương nhau.
    <div>
    Giả sử ta có tập dữ liệu 2-D sau
    </div>
    <table border="1"; align="center">
      <tr> <th></th> <th>$A_1$</th> <th>$A_2$</th> </tr>
      <tr> <th>$x_1$</th> <td>1.5</td> <td>1.7</td> </tr>
      <tr> <th>$x_2$</th> <td>2</td> <td>1.9</td> </tr>
      <tr> <th>$x_3$</th> <td>1.6</td> <td>1.8</td> </tr>
      <tr> <th>$x_4$</th> <td>1.2</td> <td>1.5</td> </tr>
      <tr> <th>$x_5$</th> <td>1.5</td> <td>1.0</td> </tr>
    </table>
    <ol type="a">
      <li>Xem dữ liệu là các điểm dữ liệu hai chiều. Cho điểm dữ liệu mới $x = (1.4, 1.6)$ là một truy vấn, xếp hạng các điểm dữ liệu trong cơ sở dữ liệu dựa trên độ tương đồng với truy vấn theo khoảng cách Euclid, khoảng cách Manhattan, khoảng cách supremum và độ tương đồng cos
      </li>
      <li>Chuẩn hóa tập dữ liệu để làm cho chuẩn của mỗi điểm dữ liệu bằng 1. Sử dụng khoảng cách Euclid trên dữ liệu đã biến đổi để xếp hạng các điểm dữ liệu        
      </li>
    </ol>
  </li>

  <li>(2.14, dữ liệu như bài 2.2) Cho dữ liệu sau (theo thứ tự tăng dần) cho thuộc tính tuổi: 13, 15, 16, 16, 19, 20, 20,21, 22, 22, 25, 25, 25, 25, 30, 33, 33, 35 , 35, 35, 35, 36, 40, 45, 46, 52, 70.
    <div>
      Sử dụng phương pháp <i>làm mịn bằng các trung bình khoảng</i> để làm mịn những dữ liệu này, sử dụng các khoảng cùng tần số cỡ 3. Minh họa các bước. <i>Nhận xét về tác động của kỹ thuật này đối với dữ liệu đã cho</i>
    </div>
  </li>

  <li>(2.17) Chuẩn hóa nhóm dữ liệu 200, 300, 400, 600, 1000 bằng phương pháp
    <ol type="a">
      <li>chuẩn hóa min-max bằng cách điều chỉnh $new\_min = 0$ và $new\_max = 1$</li>
      <li>chuẩn hóa z</li>
      <li>chuẩn hóa z dùng trung bình độ lệch tuyệt đối thay vì độ lệch chuẩn</li>
      <li>chuẩn hóa bằng thang thập phân</li>
    </ol>
  </li>

  <li>(2.18, dữ liệu như bài 2.14) Cho dữ liệu sau (theo thứ tự tăng dần) cho thuộc tính tuổi: 13, 15, 16, 16, 19, 20, 20,21, 22, 22, 25, 25, 25, 25, 30, 33, 33, 35 , 35, 35, 35, 36, 40, 45, 46, 52, 70.
    <ol type="a">
      <li>Sử dụng phương pháp chuẩn hóa min-max để biến đổi giá trị 35 của thuộc tính <i>tuổi</i> vào khoảng [0.0, 1.0]</li>
      <li>Sử dụng phương pháp chuẩn hóa z để biến đổi giá trị 35 của thuộc tính tuổi, trong đó độ lệch chuẩn của <i>tuổi</i> là 12.70 năm</li>
      <li>Sử dụng phương pháp chuẩn hóa bằng thang thập phân để biến đổi giá trị 35 cho thuộc tính <i>tuổi</i></li>
      <li><i>Nhận xét về phương pháp bạn sẽ ưu tiên sử dụng cho dữ liệu đã cho, đưa ra lý do tại sao bạn lựa chọn phương pháp đó</i></li>
    </ol>
  </li>(2.19, dữ liệu như bài 2.7) Giả sử một bệnh viện đã kiểm tra dữ liệu về tuổi và lượng mỡ cơ thể cho 18 người trưởng thành được chọn ngẫu nhiên với kết quả sau
    <table border="1"; align="center">
      <tr> <th>tuổi</th> <td>23</td> <td>23</td> <td>27</td> <td>27</td> <td>39</td>
        <td>41</td> <td>47</td> <td>49</td> <td>50</td>
      </tr>
      <tr><th>%mỡ</th> <td>9.5</td> <td>26.5</td> <td>7.8</td> <td>17.8</td> <td>31.4</td>
        <td>25.9</td> <td>27.4</td> <td>27.2</td> <td>31.2</td>
      </tr>
      <tr>
        <th>tuổi</th><td>52</td> <td>54</td> <td>54</td> <td>56</td> <td>57</td>
        <td>58</td> <td>58</td> <td>60</td> <td>61</td>
      </tr>
      <tr>
        <th>%mỡ</th> <td>34.6</td> <td>42.5</td> <td>28.8</td> <td>33.4</td> <td>30.2</td>
        <td>34.1</td> <td>32.9</td> <td>41.2</td> <td>35.7</td>
      </tr>
    </table>
    <ol type="a">
      <li>Chuẩn hóa hai thuộc tính bằng phương pháp chuẩn hóa z</li>
      <li>Tính <i>hệ số tương quan</i> (hệ số Pearson). Hai thuộc tính này có tương quan dương hay âm? Tính hiệp phương sai của chúng</li>
    </ol>
  <li>(2.20) Giả sử một nhóm gồm 12 bản ghi giá bán đã được sắp xếp như sau:
    <div align="center">5, 10, 11, 13, 15, 35, 50, 55, 72, 92, 204, 215</div>
    Chia chúng thành ba khoảng bằng phương pháp
    <ol>
      <li>chia cùng tần số</li>
      <li>chia cùng độ rộng</li>
      <li><i>phân cụm</i></li>
    </ol>
  </li>

  <li>(2.22, dữ liệu như bài 2.14) Cho dữ liệu sau (theo thứ tự tăng dần) cho thuộc tính tuổi: 13, 15, 16, 16, 19, 20, 20,21, 22, 22, 25, 25, 25, 25, 30, 33, 33, 35 , 35, 35, 35, 36, 40, 45, 46, 52, 70.
  <ol type="a">
    <li>Vẽ biểu đồ tần suất với độ rộng bằng nhau là 10</li>
    <li><i>Ví dụ minh họa cho từng phương pháp lấy mẫu sau: SRSWOR, SRSWR, lấy mẫu theo cụm, lấy mẫu theo lớp. Sử dụng mẫu cỡ 5 và các lớp "thanh niên", "trung niên" và "người cao tuổi"</i></li>
  </ol>
    
  </li>
</ol>

## Chương 4. Khám phá mẫu: khái niệm cơ bản và phương pháp
<ol>
  <li>(4.6) Một cơ sở dữ liệu có 5 giao dịch. Cho $min\_sup = 60\%$ và $min\_conf = 80\%$
    <table border="1"; align="center">
      <tr><th>TID</th> <th>Mặt hàng</th></tr>
      <tr><td>T100</td> <td>{M, O, N, K, E, Y}</td></tr>
      <tr><td>T200</td> <td>{D, O, N, K, E, Y}</td></tr>
      <tr><td>T300</td> <td>{M, A, K, E}</td></tr>
      <tr><td>T400</td> <td>{M, U, C, K, Y}</td></tr>
      <tr><td>T500</td> <td>{C, O, O, K, I, E}</td></tr>
    </table>
    <ol>
      <li>Tìm tất cả các tập mục phổ biến theo phương pháp các Apriori và <i>FP-Growth</i>. <i>So sánh hiệu suất của hai quá trình khai thác dữ liệu này</i></li>
      <li>Liệt kê tất cả các luật kết hợp <i>mạnh</i> (với giá $s$ và độ tin cậy $c$) phù hợp với lượng từ phổ dụng sau đây, trong đó $X$ là biến đại diện cho khách hàng, và $item_i$ đề cập đến các biến đại diện cho các mặt hàng (ví dụ: "A", "B", v.v.):</li>
      <div align="center">$\forall X \in transaction,\;buys(X,ite{m_1})\; \wedge \;buys(X,ite{m_2})\; \Rightarrow \;buys(X,ite{m_3})\quad [s,c]$</div>
    </ol>
  </li>

  <li>(4.8) Một cơ sở dữ liệu có 4 giao dịch. Cho $min\_sup = 60\%$ và $min\_conf = 80\%$
    <table border="1"; align="center">
      <tr><th>cust_ID</th> <th>TID</th> <th>Mặt hàng (dưới dạng thương hiệu-danh mục sản phẩm)</th></tr>
      <tr><td>01</td> <td>T100</td> <td>{King’s-Crab, Sunset-Milk, Dairyland-Cheese, Best-Bread}</td></tr>
      <tr><td>02</td> <td>T200</td> <td>{Best-Cheese, Dairyland-Milk, Goldenfarm-Apple, Tasty-Pie, Wonder-Bread}</td></tr>
      <tr><td>01</td> <td>T300</td> <td>{Westcoast-Apple, Dairyland-Milk, Wonder-Bread, Tasty-Pie}</td></tr>
      <tr><td>03</td> <td>T400</td> <td>{Wonder-Bread, Sunset-Milk, Dairyland-Cheese}</td></tr>
    </table>
    <ol>
      <li>Theo mức độ chi tiết của <i>item_category</i> (ví dụ: $item_i$ có thể là "<i>Milk</i>"), với mẫu quy tắc
        <div align="center">$\forall X \in transaction,\;buys(X,ite{m_1})\; \wedge \;buys(X,ite{m_2})\; \Rightarrow \;buys(X,ite{m_3})\quad [s,c]$</div>
        liệt kê tập $k$-mục phổ biến với $k$ lớn nhất, và <i>tất cả</i> các quy tắc kết hợp <i>mạnh</i> (với giá $s$ và độ tin cậy $c$ của chúng) chứa tập $k$-mục phổ biến với $k$ lớn nhất.
      </li>
      <li>Theo mức độ chi tiết của <i>brand-item_category</i> (ví dụ: $item_i$ có thể là "<i>Sunset-Milk</i>"), với mẫu quy tắc
        <div align="center">$\forall X \in customer,\;buys(X,ite{m_1})\; \wedge \;buys(X,ite{m_2})\; \Rightarrow \;buys(X,ite{m_3})$</div>
        liệt kê tập $k$-mục phổ biến với $k$ lớn nhất (không cần ghi ra các quy tắc)
      </li>
    </ol>
  </li>

  <li>(4.14) Bảng tiếp liên sau tổng hợp dữ liệu giao dịch tại siêu thị, trong đó $hot\; dogs$ chỉ các giao dịch chứa xúc xích, $\overline{hot\; dogs}$ chỉ các giao dịch không chứa xúc xích, $hamburgers$ chỉ các giao dịch chứa hamburger, và $\overline{hamburgers}$ chỉ các giao dịch không chứa hamburger.
    <table border="1"; align="center">
      <tr> <th></th> <th>$hot\; dogs$</th> <th>$\overline{hot\; dogs}$</th> </tr>
      <tr> <th>$hamburgers$</th> <td>2000</td> <td>500</td> </tr>
      <tr> <th>$\overline{hamburgers}$</th> <td>1000</td> <td>1500</td> </tr>
    </table>
    <ol>
      <li>Giả sử phát hiện được luật kết hợp $hot dogs \Rightarrow hamburgers$. Với ngưỡng giá tối thiểu 25% và ngưỡng tin cậy tối thiểu 50%, luật kết hợp này có mạnh không?</li>
      <li>Dựa trên dữ liệu trên, việc mua xúc xích có độc lập với việc mua hamburger không? Nếu không, có mối quan hệ <i>tương quan</i> nào giữa hai sự kiện này?</li>
      <li><i>So sánh việc sử dụng các chỉ số <i>all_confidence</i>, <i>max_confidence</i>, <i>Kulczynski</i> và <i>cosine</i> với chỉ số <i>lift</i> và <i>tương quan</i> trên dữ liệu đã cho</i></li>
    </ol>
  </li>
</ol>

## Chương 6. Phân loại: khái niệm cơ bản và phương pháp
<ol>
  <li>(Ví dụ 6.1) Từ các bộ dữ liệu huấn luyện được gán nhãn lớp từ cơ sở dữ liệu khách hàng của một cửa hàng điện tử, sử dụng khuếch đại thông tin, xây dựng cây quyết định cho thuộc tính <i>buys_computer</i>
    <table border="1"; align="center">
      <tr> <th>RID</th> <th>age</th> <th>income</th> <th>student</th> <th>credit_rating</th> <th>Class: buys_computer</th> </tr>
      <tr> <td>1</td> <td>youth</td> <td>high</td> <td>no</td> <td>fair</td> <td>no</td> </tr>
      <tr> <td>2</td> <td>youth</td> <td>high</td> <td>no</td> <td>excellent</td> <td>no</td> </tr>
      <tr> <td>3</td> <td>middle_aged</td> <td>high</td> <td>no</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>4</td> <td>senior</td> <td>medium</td> <td>no</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>5</td> <td>senior</td> <td>low</td> <td>yes</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>6</td> <td>senior</td> <td>low</td> <td>yes</td> <td>excellent</td> <td>no</td> </tr>
      <tr> <td>7</td> <td>middle_aged</td> <td>low</td> <td>yes</td> <td>excellent</td> <td>yes</td> </tr>
      <tr> <td>8</td> <td>youth</td> <td>medium</td> <td>no</td> <td>fair</td> <td>no</td> </tr>
      <tr> <td>9</td> <td>youth</td> <td>low</td> <td>yes</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>10</td> <td>senior</td> <td>medium</td> <td>yes</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>11</td> <td>youth</td> <td>medium</td> <td>yes</td> <td>excellent</td> <td>yes</td> </tr>
      <tr> <td>12</td> <td>middle_aged</td> <td>medium</td> <td>no</td> <td>excellent</td> <td>yes</td> </tr>
      <tr> <td>13</td> <td>middle_aged</td> <td>high</td> <td>yes</td> <td>fair</td> <td>yes</td> </tr>
      <tr> <td>14</td> <td>senior</td> <td>medium</td> <td>no</td> <td>excellent</td> <td>no</td> </tr>
    </table>

  </li>

  <li>(6.7) Bảng sau chứa dữ liệu huấn luyện từ cơ sở dữ liệu nhân viên. Dữ liệu đã được tổng quát hóa. Ví dụ, "31...35" của <i>age</i> đại diện cho khoảng độ tuổi từ 31 đến 35. Đối với mỗi dòng dữ liệu, <it>count</it> chỉ số bộ dữ liệu có các giá trị của <i>department</i> (phòng ban), <i>status</i> (tình trạng), <i>age</i> (độ tuổi), và <i>salary</i> (lương) được cho dòng đó.
    <table border="1"; align="center">
      <tr> <th>department</th> <th>status</th> <th>age</th> <th>salary</th> <th>count</th> </tr>
      <tr> <td>sales</td> <td>senior</td> <td>31...35</td> <td>46K...50K</td> <td>30</td> </tr>
      <tr> <td>sales</td> <td>junior</td> <td>26...30</td> <td>26K...30K</td> <td>40</td> </tr>
      <tr> <td>sales</td> <td>junior</td> <td>31...35</td> <td>31K...35K</td> <td>40</td> </tr>
      <tr> <td>systems</td> <td>junior</td> <td>21...25</td> <td>46K...50K</td> <td>20</td> </tr>
      <tr> <td>systems</td> <td>senior</td> <td>31...35</td> <td>66K...70K</td> <td>5</td> </tr>
      <tr> <td>systems</td> <td>junior</td> <td>26...30</td> <td>46K...50K</td> <td>3</td> </tr>
      <tr> <td>systems</td> <td>senior</td> <td>41...45</td> <td>66K...70K/td> <td>3</td> </tr>
      <tr> <td>marketing</td> <td>senior</td> <td>36...40</td> <td>46K...50K</td> <td>10</td> </tr>
      <tr> <td>marketing</td> <td>junior</td> <td>31...35</td> <td>41K...45K</td> <td>4</td> </tr>
      <tr> <td>secretary</td> <td>senior</td> <td>46...50</td> <td>36K...40K</td> <td>4</td> </tr>
      <tr> <td>secretary</td> <td>junior</td> <td>26...30</td> <td>26K...30K</td> <td>6</td> </tr>
    </table>
  </li>
</ol>
