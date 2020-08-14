<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>最終作業</title>
    <link rel="stylesheet" href="CSS/style12.css">
</head>
<body>
    <div class="wrap">
        <ul class="followers">
            <li><a href="#" class="FB"><img src="https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/facebookIcon.png" alt="">粉絲團</a></li>
            <li><a href="#" class="Twitter"><img src="https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/twitterIcon.png" alt="">追蹤我們</a></li>
        </ul>
        <div class="logo">
            <h2><a href="#">Hex School</a></h2>
            <ul>
                <li><a href="#">首頁</a></li>
                <li><a href="#">產品介紹</a></li>
                <li><a href="#">聯絡我們</a></li>
            </ul>
        </div>
        <div class="banner">
            <h2>六角學院</br>
            讓您奠定良好的前端基礎</h2>
        </div>
        <ul class="course">
            <li class="content"><img src="https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/html.png" alt="">
            <h2>HTML 5教學</h2>
            <p>主流前端網站設計的基礎就在六角學院，在這裡不再是填鴨式教學，而是透過實際的範例，瞭解正確的網站開發流程，講師均具有業界開發經驗，讓學員學習業界主流的開發方法。</p>
        </li>
            <li class="content"><img src="https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/rwd.png" alt="">
            <h2>響應式網站設計</h2>
            <p>響應式網站設計(Responsive web design)，目前大多使用者均是以手機瀏覽的情況下，響應式網站已經是必備的。六角學院將會提供業界響應式開發方法，讓學生瞭解行動版開發技巧。</p>
        </li>
            <li class="content"><img src=" https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/jQuery.png" alt="">
            <h2>jQuery實戰教學</h2>
            <ul>本課程有以下特色
                <li>瞭解變數的使用方法</li>
                <li>學習並操作DOM</li>
                <li>學習基本數學運算方法</li>
                <li>套件的操作及運用</li>
            </ul>
        </li>
        </ul>
        <h2 class="comparison">線上及實體課程差異</h2>
        <table class="details">
            <tr>
                <th>項目</th>
                <th>Hex School線上課程</th>
                <th>一般線上課程</th>
                <th>實體課程</th>
            </tr>
            <tr>
                <td>費用</td>
                <td class="green">較低</td>
                <td class="green">較低</td>
                <td>較高</td>
            </tr>
            <tr>
                <td>學習效果</td>
                <td>一般</td>
                <td class="green">較低</td>
                <td class="green">很好</td>
            </tr>
            <tr>
                <td>Code Review</td>
                <td class="green">有</td>
                <td>無</td>
                <td>不一定</td>
            </tr>
            <tr>
                <td>課程更新速度</td>
                <td class="green">普通</td>
                <td class="green">普通</td>
                <td>較慢</td>
            </tr>
            <tr>
                <td>多次複習</td>
                <td class="green">可</td>
                <td class="green">可</td>
                <td>不可</td>
            </tr>
            <tr>
                <td>字幕</td>
                <td class="green">有</td>
                <td>不一定</td>
                <td>板書</td>
            </tr>
        </table>
        <form action="HW12-最終作業.html">
            <h2>對我們課程有興趣嗎?</br>
            歡迎留下您的資料</h2>
            <div class="container">
                <textarea name="information" id="" cols="55" rows="15"></textarea>
                <ul>
                    <li>
                        <label for="id">姓名</label>
                        <input type="text" name="id" id="id" placeholder="六角講師" class="user">
                    </li>
                    <li>
                        <label for="phone">電話</label>
                        <input type="text" name="phone" id="phone" placeholder="0912345678" class="user">
                    </li>
                    <li>
                        <label for="email">電子信箱</label>
                        <input type="text" name="email" id="email" placeholder="hexschool@gmail.com" class="user">
                    </li>
                    <li><input type="submit" value="送出" class="submit"></li>
                </ul>
            </div>
        </form>
        <div class="footer">
            <img src="https://raw.githubusercontent.com/hexschool/HTMLHWSource/master/singlePage/footerLogo.png" alt="">
            <div class="contact">
                <p>聯絡我們：<span>hexschool@gmail.com</span></p>
                <p>電話：<span>0912345678</span></p>
            </div>
        </div>
    </div>
</body>
</html>