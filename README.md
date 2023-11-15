<!DOCTYPE html>
<html lang="en">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(135deg, rgba(3, 9, 145, 0.8 ) 40%, rgba( 993, 99, 0.9) 60%);
            background-attachment: fixed;
            height: 100vh;
            width: 100vw;
            font-family: 'Roboto', sans-serif;
            color: white;
        }


        #logo {
            width: 200px;
            margin-bottom: 10px;
        }


        #avatar {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            margin-bottom: 30px;
        }


        .left-column {
            width: 400px;
            display: flex;
            flex-direction: column;
            align-items: center;
            border-right: 2px solid rgba(255, 255, 255,800);
            padding-right:20px;
        }
        .right-column {
            width: 470px;
            margin-left: 50px;
            line-height: 1.32;
        }


        .card {
            background: rgba(0, 0, 0, 0.3);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(200px);
            width: 1000px;
            height: 710px;
            padding: 50px;
            border-radius: 50px;
            display: flex;
            justify-content: space-between;
        }
        h1{
            margin-bottom: 12px;
            color:greenyellow;
            align-items:center
        }
        h2 {
            margin-bottom: 8px;
            align-items:center;
        }


        p {
            font-size: 25px;
            line-height: 1.7;
        }


        a {
            color: white;
        }


        .section {
            margin-bottom: 0px;
        }


        main {
            height: 100%;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .contacts {
           
            box-shadow: 0 1px 10px rgba(0, 0, 0, 0.9);
            padding: 20px;
            border-radius: 20px;
            margin-top: 20px;
        }


            .contacts a {
                display: block;
                margin-bottom: 20px;
                text-decoration: none;
                color: white;
            }


            .contacts img {
                width: 25px;
                height: 25px;
                margin-right: 10px;
            }
    </style>
</head>


<body>
    <main>
        <div class="card">
            <!-- Left Column -->
            <div class="left-column">
                <!-- Content for left column goes here --> <img id="logo"                     src="https://lh3.googleusercontent.com/pw/ADCreHdaOMYiUdjIlNAkd_b5__H927yPc0fySkMRdRf1qaRgU26I1UW89DW_9LsfRbU7yvUEOfkbvk1sYWqNZIgNFAf40q51O1fZeMm91sAFycV-reJJcLw=w2400" />
                <img id="avatar" src="https://s1.zerochan.net/Bongo.Cat.600.3353167.jpg" alt="" />
                <div class="highlights">
                    <h1><strong>Phan Đức Thành Phát</strong></h1>
                    <p><strong>KHMT2023.3</strong></p>
                    <p><strong>UIT VNUHCM </strong></p>
                    <p><strong>
                        From Huế Mộng Huế Mơ city</strong></p>
                </div>
            </div> <!-- Right Column -->
            <div class="right-column">
                <!-- Content for right column goes here -->
                <div class="section">
                    <h1>About Me</h1>
                </div>
                <div class="section">
                    <h2>My Hobbies</h2>
                    <ul>
                        <!--Mấy Bạn thêm bao nhiêu.. thì nhiêu cái li ở dưới này nha-->
                        <li>Đá Bóng</li>
                        <li>Đánh Cầu Lông</li>
                        <li>Nghe Nhạc</li>
                    </ul>
                </div>
                <div class="section">
                    <h2>My Future Goals</h2>
                    <ul>
                        <!--Mấy Bạn thêm bao nhiêu.. thì nhiêu cái li ở dưới này nha-->
                        <li>Nhiều hơn 2 anh iu</li>
                        <li>Du lịch Châu  u</li>
                        <li>Ra Trường Đúng Hạn</li>
                    </ul>
                </div>
                <!--ngang này là giống mấy anh chị rùi á còn ở dưới là thêm nha-->
                <div class="section">
                    <h2>Tâm sự zới mình ik </h2>
                <form>
                    <!--các bạn có thể đặt câu hỏi tương tác ở đây-->
                    <div>
                        <label>Bạn quá thích mình gòi đúng khum</label>
                    <input type="radio" placeholder=/>
                    <select>
                        <option>yeahh</option>
                        <option>đúng òi ó</option>
                        <option>biết gòi còn hỏi</option>
                    </select>
                   </div>


                   <div>
                    <label>Bạn bị gay à</label>
                    <input type="radio" placeholder=/>
                    <select>
                        <option>có thể coi là zạ</option>
                        <option>nửa nửa </option>
                        <option>nhiều chút ít</option>
                    </select>
                   </div>
                </form>
                <div class="contacts">
                    <h2>Contact me</h2>
                    <a href="https://www.facebook.com/profile.php?id=100043974591502"><img src="https://banghieuviet.org/wp-content/uploads/2023/08/logo-facebook-vector-02.jpg" alt="">FaceBook</a>
                    <a href="https://github.com/kelvin2250"><img src="https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png" alt="">Github</a>
                    <a href="https://www.instagram.com/thanhhppphat/?hl=en"><img src="https://rubee.com.vn/admin/webroot/upload/image//images/bai-viet/logo-instagram-4.jpg" alt="">Instagram</a>  
            </div>
        </div>
    </main>
</body>


</html>
