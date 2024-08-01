<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>مجتمع فنی تهران</title>
     <link rel="stylesheet" href="style.css">   
</head>
<body>
    <header>
        <h1>سایت مجتمع فنی تهران</h1>
        <h2>اسامی دانشجویان و امتیازات</h2>
    </header>
    <main>
        <div id="studentsScore">
            <table>
                <tr>
                    <th>نام</th>
                    <th>نام خانوادگی</th>
                    <th>درجه</th>
                </tr>
                <tr>
                    <td>هدیه</td>
                    <td>جلالی</td>
                    <td>A</td>
                </tr>
                <tr>
                    <td>هلیا</td>
                    <td>خنجری</td>
                    <td>B</td>
                </tr>
                <tr>
                    <td>ثمینه</td>
                    <td>عسگری</td>
                    <td>C</td>
                </tr>
                <tr>
                    <td>ملینا </td>
                    <td>خرسندی</td>
                    <td>D</td>
                </tr>
                <tr>
                    <td>ملیکا</td>
                    <td>حسینیان</td>
                    <td>E</td>
                </tr>
            </table>
        </div>
        <div id="studentsSidebar">
            <a href="google.com">کلاس 1</a>
            <a href="google.com">کلاس 2</a>
        </div>
    </main>
    <section>
        <div>
            <h2>لینک های مفید</h2>
            <a href="">امتیازات نهایی</a>
        </div>
        <div>
            <h2>لینک های مفید</h2>
            <a href="">امتیازات میان فصل</a>
        </div>
        
    </section>
    <footer>
        <p>تمامی حقوق سایت مطعلق به مجتمع فنی تهران میباشد
        </p>
    </footer>
</body>
</html>


*{
    direction: rtl;
    box-sizing: border-box;
    font-family: Vazirmatn FD;
    margin: 0px;
}
header{
    background-color: rgba(139, 255, 255, 0.5);
}
main,div section div{
    border: .5px solid #c2c2c2;
    float: right;
}
section div{
    width: 33.3%;
}
div#studentsScore{
    width: 70%;
}
div#studentsSidebar{
    width: 30%;
}
h1,h2{
text-align: center;
}
table{
    width: 100%;
    border: .5px solid #c2c2c2;
    border-collapse: collapse;
}
div#studentsScore{
    text-align: right;
    padding: 10px;
    height: 200px;
}
div#studentsScore table tr td{
    padding: 5px;
}
div#studentsScore table tr td.score{
    text-align: left;
}
div#studentsScore table tr td,th{
    border: .5px solid #c2c2c2;
    border-collapse: collapse;
    border-radius: 5%;
}
div#studentsScore table tr th{
    text-align: center;
    background-color: rgba(139, 255, 255, 0.5);
}
a{
    display: block;
    text-align: left;
    padding: 10px;
}
section{
    clear: both;
}
section div a{
    text-align: right;
}
div#studentsSidebar{
    width: 30%;
    border-right: 1px solid black;
    background-color: rgba(139, 255, 255, 0.5);
    height: 200px;
}
footer{
    background-color:rgba(139, 255, 255, 0.5);
}
footer p{
    text-align: center;
}
