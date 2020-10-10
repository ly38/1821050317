﻿# 1821050317
1821050317 Đinh Thị Cẩm Ly - Bài thu hoạch Thiết kế website

Mã nguồn: 
thuchanh1.html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thư Viện Nhỏ</title>
    <link rel="StyleSheet" href="cs1.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

</head>

<body background="https://images.unsplash.com/photo-1472905981516-5ac09f35b7f4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1353&q=80">
<header>
    <h1>Thư Viện Nhỏ</h1>
    <h3>Góc Nhỏ Cho Những Người Yêu Sách</h3>
</header>
<nav>
    <ul>
        <li><a data-section="home">Home</a></li>
        <li><a data-section="books">Sách Hay Cho Bạn</a></li>
        <li class="dropdown">
            <a href="javascript:void(0)" class="dropbtn" >Thư Viện</a>
            <div class="dropdown-content">
                <a data-section="link1">Sách Quốc Văn</a>
                <a data-section="link2">Sách Ngoại Văn</a>
            </div>
        </li>
        <li><a data-section="news" style="cursor: pointer;">Tin Tức</a></li>
        <li><a data-section="review">Cảm Nhận</a></li>
        <li><a data-section="writing">Viết lách</a></li>
        <li><a data-section="suggest">Góp ý</a></li>
        <li style="float:right"><a data-section="about">About us</a></li>
    </ul>
</nav>

<section id="home" class="hideable-section">
    <ul>
        <img src="https://www.nxbtre.com.vn/Images/Slide/Slide_4444444444444444444.jpg" alt="autor" style="width: auto;height: auto;padding: 0px">
        <h4>Sách Tháng 10 Nổi Bật</h4>
        <li>
            <a href=""><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195755.jpg" alt="novel1" title="Mùi Hoàng Kim"></a>
            <p class="caption">Mùi Hoàng Kim</p>
        </li>
        <li>
            <a href=""><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/small_image/400x400/9df78eab33525d08d6e5fb8d27136e95/i/m/image_186479.jpg" alt="book" title="Ngược Mặt Trời">
            </a>
            <p class="caption">Ngược Mặt Trời</p>
        </li>
        <li>
            <a href=""><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/m/u/muonkiepnhansinh.jpg" alt="novel1" title="Muôn Kiếp Nhân Sinh"></a>
            <p class="caption">Muôn Kiếp Nhân Sinh</p>
        </li>
        <li>
            <a href=""><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/i/m/image_181032.jpg" alt="novel1" title="Sherlock Holmes"></a>
            <p class="caption">Sherlock Holmes</p>

        </li>
        <li>
            <a href=""><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/b/i/bia_mot-ngay-khac_final_1.jpg" alt="novel1" title="Một Ngày Khác"></a>
            <p class="caption">Một Ngày Khác</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/c/o/cover-1---m_-_om-_m_1.jpg" alt="novel1" title="Mộ Đom Đóm"></a>
            <p class="caption">Mộ Đom Đóm</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/8/9/8935250754606.jpg" alt="novel1" title="Colorful"></a>
            <p class="caption">Colorful</p>
        </li>
    </ul>
</section>

<section id="books" class="hideable-section">
    <ul>
        <div>
            <h4>Sách văn học kinh điển không thể bỏ lỡ</h4>
        </div>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_25836.jpg" alt="novel111" title="Oliver Twist"></a>
            <p class="caption">Oliver Twist</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_182843.jpg" alt="book" title="Cuốn Theo Chiều Gió">
            </a>
            <p class="caption">Cuốn Theo Chiều Gió</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_181775.jpg" alt="novel1" title="Toto-chan Bên Cửa Sổ"></a>
            <p class="caption">Toto-chan Bên Cửa Sổ</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/i/m/image_181032.jpg" alt="novel1" title="Sherlock Holmes"></a>
            <p class="caption">Sherlock Holmes</p>

        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/k/i/kieu-hanh-va-dinh-kien-&#45;&#45;bia-ao-mem_1.jpg" alt="novel1" title="Kiêu Hãnh Và Định Kiến"></a>
            <p class="caption">Kiêu Hãnh Và Định Kiến</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_180504.jpg" alt="novel1" title="Ông Già Và Biển Cả"></a>
            <p class="caption">Ông Già Và Biển Cả</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_183012.jpg" alt="novel1" title="Không Gia Đình"></a>
            <p class="caption">Không Gia Đình</p>
        </li>
    </ul>
</section>

<section id="link1" class="hideable-section">
    <ul>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_55892.jpg" alt="novel11" title="Dế Phèn Phiêu Lưu Ký"></a>
            <p class="caption">Dế Mèn Phiêu Lưu Ký</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/m/a/mat-biec_bia-mem_in-lan-thu-44.jpg" alt="book1" title="Mắt Biếc"></a>
            <p class="caption">Mắt Biếc</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_10025.jpg" alt="novel12" title="Đời Thừa"></a>
            <p class="caption">Đời Thừa</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/8/9/8934974132042.gif" alt="novel13" title="Bảy Bước Tới Mùa Hè"></a>
            <p class="caption">Bảy Bước Tới Mùa Hè</p>

        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/p/8/p86213eb__a_tr_____c_1.jpg" alt="novel15" title="Thanh Xuân Ấy Mình Đã Từng Thương"></a>
            <p class="caption">Thanh Xuân Ấy</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/c/o/cover-1---m_-_om-_m_1.jpg" alt="novel1" title="Mộ Đom Đóm"></a>
            <p class="caption">Mộ Đom Đóm</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_187010.jpg" alt="novel1" title="Hoàng Tử Bé"></a>
            <p class="caption">Hoàng Tử Bé</p>
        </li>
    </ul>
</section>

<section id="link2" class="hideable-section">
    <ul>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_194952.jpg" alt="novel19" title="Me Before You"></a>
            <p class="caption">Me Before You</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/9/7/9780525505976.jpg" alt="book7" title="Still Me"></a>
            <p class="caption">Still Me</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_25784.jpg" alt="novel51" title="The Longest Ride"></a>
            <p class="caption">The Longest Ride</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/i/m/image_181032.jpg" alt="novel1" title="Sherlock Holmes"></a>
            <p class="caption">Sherlock Holmes</p>

        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_38799.jpg" alt="novel61" title="A Dog's Promise"></a>
            <p class="caption">A Dog's Promise</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/8/9/8934986053137.jpg" alt="novel1" title="Not That I Could Tell"></a>
            <p class="caption">Not That I Could Tell</p>
        </li>
        <li>
            <a href="#"><img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/thumbnail/362x/9df78eab33525d08d6e5fb8d27136e95/8/9/8935250754606.jpg" alt="novel1" title="Colorful"></a>
            <p class="caption">Colorful</p>
        </li>
    </ul>
</section>

<section id="news" class="hideable-section">
    <ul>
        <div>
            <img src="https://znews-photo.zadn.vn/w660/Uploaded/pirr/2020_10_06/van_hoa_doc.jpg" alt="photo">
        </div>
        <div>
            <h4><a href="https://www.nxbtre.com.vn/diem-tin/de-xuat-thanh-lap-uy-ban-quoc-gia-phat-trien-van-hoa-doc-54316.html">Đề xuất thành lập ủy ban quốc gia phát triển văn hóa đọc</a></h4>

        </div>
    </ul>
    <ul>
        <div>
            <img src="https://znews-photo.zadn.vn/w660/Uploaded/mdf_nsozxd/2020_10_02/1.png" alt="photo">
        </div>
        <div>
            <h4><a href="https://zingnews.vn/tieu-thuyet-cua-nguoi-viet-duoc-dich-thanh-sach-o-my-post1137346.html">Tiểu thuyết của người Việt được dịch thành sách ở Mỹ</a></h4>
        </div>
    </ul>
</section>

<section id="review" class="hideable-section">
    <ul>
        <div>
            <img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/8/9/8936048123468_1.jpg" alt="photo">
        </div>
        <div>
            <h4><a href="#">Nhiều hơn lời nói...</a></h4>
            <p><em>Review "Garden Word"</em></p>
            <p><em>Được viết bởi: Bọt Biển</em></p>
            <p>&ensp;&ensp;Bạn có tự hỏi trên đường đời bạn gặp được người như ý một cách bất ngờ....</p>
        </div>
    </ul>
    <ul>
        <div>
            <img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_195509_1_39879.jpg" alt="photo">
        </div>
        <div>
            <h4><a href="#">Lỡ nhau trong khoảnh khắc</a></h4>
            <p><em>Review "5cm/s"</em></p>
            <p><em>Được viết bởi: Quả Lê Nho Nhỏ</em></p>
            <p>&ensp;&ensp;5cm/s là tấc độ của cánh hoa anh đào rơi, cũng là lúc người ta lỡ nhau một đời ....</p>
        </div>
    </ul>
    <ul>
        <div>
            <img src="https://cdn0.fahasa.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/image_188765.jpg" alt="photo">
        </div>
        <div>
            <h4><a href="#">Chỉ là thất tình, không sao cả</a></h4>
            <p><em>Review "Hôm nay tôi thất tình"</em></p>
            <p><em>Được viết bởi: Love</em></p>
            <p>&ensp;&ensp;Thất tình mất rồi....</p>
        </div>
    </ul>
</section>

<section id="writing" class="hideable-section">
    <ul>
        <li>
            <div>
                <div>
                    <img src="https://images.unsplash.com/photo-1580227060192-5d0b91d751fe?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&q=80" alt="flower" >
                </div>
                <h4><a href="#">Hoa Hướng Dương</a></h4>
                <p>Tác Giả: Doraemon Lê</p>
                <p>Ngày ấy,trong mắt tôi toàn màu hồng.....</p>
            </div>
        </li>
        <li>
            <div>
                <div>
                    <img src="https://images.unsplash.com/photo-1527345931282-806d3b11967f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80" alt="readbook">
                </div>
                <h4><a href="#">Người Thầy</a></h4>
                <p>Tác Giả: Duy Duy</p>
                <p>Người thầy vẫn lặng lẽ đi về chốn xưa</p>
            </div>
        </li>
        <li>
            <div>
                <div>
                    <img src="https://images.unsplash.com/photo-1500401898870-473f0335a73e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" alt="tree">
                </div>
                <h4><a href="#">Cây cao</a></h4>
                <p>Tác Giả: Hoa Đào</p>
                <p>Nhà tôi có một vườn cây lớn vô cùng</p>
            </div>
        </li>
    </ul>
</section>

<section id="about" class="hideable-section">
    <div style="background: white">
        <h1><em>Chào Mừng Bạn Đến với Thư Viện Nhỏ</em></h1>
        <img src="https://longreadsblog.files.wordpress.com/2019/07/beach-book.jpg?w=1200" alt="bookpt" style="width:50%;height:50%;">
        <div style="font-family: Calibri; color: black;">
            <p>Bạn có niềm đam mê với sách?</p>
            <p> Bạn có đang tìm kiếm những cuốn sách hay?</p>
            <p><strong>Thư Viện Nhỏ</strong>chính là nơi dành cho bạn.</p>
            <p><strong>Thư Viện Nhỏ</strong> được thành lập vào ngày 10/10/2020 với mong muốn chia sẻ những cuốn sách hay, những lời văn đẹp đến với mọi người.</p>
            <p>Chúng tôi mong rằng chúng ta có thể kết nối với nhau thông qua sở thích, đam mê đến từ những cuốn sách.</p>
            <p>Đón đọc những tin tức mới nhất về những cuốn sách cùng những thông tin thú vị liên tục được cập nhật.</p>
            <p>Trở thành nhà văn với chuyên mục Viết Lách.</p>
            <p>Hàng ngàn đầu sách thú vị đang chờ bạn khám phá và trải nghiệm.</p>
            <p>Chúc các bạn có những phút giây vui vẻ và thư giãn bên những cuốn sách.</p>
        </div>
</section>

<section id="suggest" class="hideable-section">
    <form>
        <table>
            <tr>
                <th align="left">Họ và tên: </th>
                <td><input type="text" id="name" name="name" required><br></td>
            </tr>
            <tr>
                <th align="left">Email</th>
                <td><input type="text" id="email" name="email" required></td>
            </tr>
            <tr>
                <th align="left">Ý kiến của bạn: </th>
                <td>
                    <textarea rows="10" cols="30"></textarea>
                </td>
            </tr>
            <tr>
                <th align="left"></th>
                <td><input type = "submit" value = 'Gửi'></td>
            </tr>
        </table>
    </form>
</section>

<footer>
    <p><em>Họ Và Tên: Đinh Thị Cẩm Ly</em></p>
    <p><e>Mã sinh viên: 1821050317</e></p>
</footer>

<script>
    $(function() {
        $('nav ul li a').click(function() {
            // Lấy section để hiển thị
            var $section = $('#' + $(this).data('section'));

            // Nếu đang hiện thì không làm gì.
            // Nếu không, ẩn tất cả các se cho hiện (kiểu fade in) phần mong muốn.
            if (!$section.is(':visible')) {
                $('.hideable-section').hide();
                $section.fadeIn();
            }
        });
    });
</script>
</body>
</html>

cs1.css
* {
    margin: 0;
    box-sizing: border-box;
    padding-left: 20px;
    padding-right: 20px;
    color: #666;
}


/* Header/logo tiêu đề */

header {
    padding-top: 5px;
    padding-bottom: 5px;
    text-align: center;
    background: lightblue;
    color: white;
    height: 120px;
}


/* Tăng kích thước font chữ cho header */

header h1 {
    font-size: 40px;
}

header h1,
h2,
h3 {
    color: white;
}

section {
    padding: 20px;
}

ul{
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #f3f3f3;
}

li {
    float: left;
}

li a,
.dropbtn {
    display: inline-block;
    color: #666;
    text-align: center;
    padding: 10px 10px;
    text-decoration: none;
}

li a:hover:not(.active),
.dropdown:hover .dropbtn {
    color: white;
    background-color: lightskyblue;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: lightblue;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
}

.dropdown-content a {
    color: #666;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {
    background-color: lightblue;
}

.dropdown:hover .dropdown-content {
    display: block;
}


/* Landing page */

.hideable-section {
    display: none;
}

.hideable-section:first-of-type {
    display: block;
}

img {
    float: left;
    padding: 10px;
    width: 191px;
    height: 191px
}

table {
    border-style: solid;
    box-sizing: initial;
    background: white;
}

div {
    padding: 16px 8px;
    color: black;
    font-size: initial;
}
h4 {
    color: #555555;
    font-size: 24px;
    display: block;
}
.caption {
    text-align: center;
    padding: 4px 4px 3px 4px;
    margin-right:auto;
    margin-left:auto;
    -moz-border-radius: 3px;
    -khtml-border-radius: 3px;
    border-radius: 3px;
}

footer {
    left: 0;
    bottom: 0;
    width: 100%;
    background-color: lightblue;
    color: black;
    text-align: center;
    position: sticky;
    top: 100%;
}

Website:








