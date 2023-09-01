
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <title>Trương Văn An</title>
</head>
<body>
    <div class="wrapper">
        <header>
            <div class="row-header">
                <div class="row1">
                    <div class="logo">L❤️VE</div>
                    <ul>
                        <li class="active"><a href="#">Home</a></li>
                        <li><a href="#">about</a></li>
                        <li><a href="#">Blog</a></li>
                    </ul>
                </div>
                <div class="dark-night">
                    <i class="fa-solid fa-moon"></i>
                </div>
            </div>
        </header>
        <section>
            <form action="">
                <h2>Hãy nhập ngày 2 bạn bắt đầu yêu nhau vào đây.</h2>
                <div class="form-date">
                    <input type="text" placeholder="Ngày" id="inpDay">
                    <input type="text" placeholder="Tháng" id="inpMonth">
                    <input type="text" placeholder="Năm" id="inpYear">
                </div>
                <div class="date">Ngày<div class="day"></div>tháng<div class="month"></div>năm<div class="year"></div></div>
                <div class="imgUser">
                    <div class="userImg">
                        <input type="file" name="" id="userLove1" hidden>
                        <input type="button" id="btnUser1" value="Ảnh Nam">
                        <input type="text" id="textBoy" placeholder="Tên bạn Nam">
                        <span id="textUser1"></span>
                    </div>
                    <div class="userImg">
                        <input type="file" name="" id="userLove2" hidden>
                        <input type="button" id="btnUser2" value="Ảnh Nữ">
                        <input type="text" id="textGirl" placeholder="Tên bạn nữ">
                        <span id="textUser2"></span>
                    </div>
                </div>
                <button type="submit" class="btn">Chấp nhận</button>
            </form>
            <div class="boxDate">
                <h2>Đã Yêu</h2>
                <div class="items">
                    <div class="item">
                        <div id="itemNumberMonths">0</div>
                        <div class="itemText">Tháng</div>
                    </div>
                    <div class="item">
                        <div id="itemNumberDays">0</div>
                        <div class="itemText">Ngày</div>
                    </div>
                    <div class="item">
                        <div id="itemNumberHours">0</div>
                        <div class="itemText">Giờ</div>
                    </div>
                    <div class="item">
                        <div id="itemNumberMinutes">0</div>
                        <div class="itemText">Phút</div>
                    </div>
                    <div class="item">
                        <div id="itemNumberSeconds">0</div>
                        <div class="itemText">Giây</div>
                    </div>
                </div>
            </div>
            <div class="user">
                <div class="userItem">
                    <div class="image" id="image1">
                        <img src="" alt="">
                        <span>Ảnh</span>
                    </div>
                    <span id="textBoyimg"></span>
                </div>
                <div class="userItem">
                    <div class="image" id="image2">
                        <img src="" alt="">
                        <span>Ảnh</span>
                    </div>
                    <span id="textGirlimg"></span>
                </div>
                <div class="boxheart">
                    <div class="heart"></div>
                    <p id="textDay">Day</p>
                    <span>Ngày</span>
                </div>
            </div>
        </section>
    </div>
</body>
<script src="app.js"></script>
</html>
