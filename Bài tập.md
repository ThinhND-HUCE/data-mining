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
      <li></li>
      <li></li>
      <li></li>
    </ol>
    Sử dụng các phương pháp chuẩn hóa (1) , (2) điểm z, (3) điểm z dùng trung bình độ lệch tuyệt đối thay vì độ lệch chuẩn, và (4) thang thập phân để chuẩn hóa nhóm dữ liệu 
    
  </li>
</ol>

