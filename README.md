<!DOCTYPE html>
<html>
<h1>信息管理与信息系统2019年度大二下学期课程表：</h1>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>fzs</title>
    <style>
        table,
        td,

        th {

            border: 1px solid rgb(2, 128, 121);
            height: 2px;
            width: 2px;
            box-shadow: 2px 3px 3px rgb(8, 153, 129);
        }

        th:hover {
            position: relative;
            top: 4px;
            left: 5px
        }

        .cell {
            height: 3em;
            width: 3em;
        }
    </style>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
    <script src="main.js"></script>
</head>

<body>
    <table style="width: 1000px; height: 500px;margin: 20px auto 50px;">

        <tr>
            <td rowspan="3">上午</td>
            <th></th>
            <th>星期一</th>
            <th>星期二</th>
            <th>星期三</th>
            <th>星期四</th>
            <th>星期五</th>
            <th>星期六</th>
            <th>星期日</th>
        </tr>

        <tr>

            <th>第一节(08:20-10:00)</th>
            <th style="background-color:rgb(55, 226, 175)" onmousedown="mDown1(this)" onmouseup="mOut1(this)">
                web应用开发技术_01</th>
               
            <script>
                
                function mDown1(obj) 
               
               
                {
                    obj.innerHTML = "教室：西区第一公共教学楼C411 <br>任课教师：吕成功   1-15周"
                }

                function mOut1(obj) {
                    obj.innerHTML = "web应用开发技术_01"
                }
            </script>
            <th onmousedown="mDown2(this)" onmouseup="mOut2(this)" style="background-color:turquoise" ;>大学英语四级（A）_64</th>
            <script>
                function mDown2(obj) {

                    obj.innerHTML = "教室：西区第一公共教学楼C221<br>任课教师:张蔚  1-17周";
                }

                function mOut2(obj) {

                    obj.innerHTML = "大学英语四级（A）_64";
                }
            </script>
            <th onmousedown="mDown3(this)" onmouseup="mOut3(this)" style="background-color:rgb(247, 104, 216)" ;>管理信息系统_02</th>
            <script>
                function mDown3(obj) {

                    obj.innerHTML = "教室：西区第一公共教学楼C105<br>任课教师：刘烨 1-15周（单周）";
                }

                function mOut3(obj) {

                    obj.innerHTML = "管理信息系统_02";
                }
            </script>
            <th onmousedown="mDown4(this)" onmouseup="mOut4(this)" style="background-color:rgb(243, 120, 120)" ;>数据库原理及应用_01<br>运营管理_02</th>
                <script>
                    function mDown4(obj) {
    
                        obj.innerHTML = "双周：数据库原理及应用_01  教室@西区第一公共教学楼B405<br>任课教师：吴君2-14周（双周） <br>单周：运营管理_02  教室@西区第一公共教学楼B405  1-15周（单周）<br>任课教师：刘亮";
                    }
    
                    function mOut4(obj) {
    
                        obj.innerHTML = "数据库原理及应用_01<br>运营管理_02";
                    }
                </script>
            <th  onmousedown="mDown5(this)" onmouseup="mOut5(this)" style="background-color:turquoise" ;>大学英语四级（A）_64 </th>
            <script>
                function mDown5(obj) {

                    obj.innerHTML = "单周：教室@西区外语学院楼219<br>双周：教室@西区第一公教C219 <br>任课教师：张蔚 1-17周";
                }

                function mOut5(obj) {

                    obj.innerHTML = "大学英语四级（A）_64";
                }
            </script>
            <th></th>
            <th></th>
        </tr>

        <tr>
            <th>第二节(10:20-12:00)</th>
            <th onmousedown="mDown6(this)" onmouseup="mOut6(this)" style="background-color:rgb(250, 102, 159)" ;>毛泽东思想与中国特色社会主义理论体系概论_13 </th>
            <script>
                function mDown6(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼A120 <br>任课教师：顾洪英 1-16周";
                }

                function mOut6(obj) {

                    obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13";
                }
            </script>
            <th onmousedown="mDown7(this)" onmouseup="mOut7(this)" style="background-color:lightgrey" ;> 管理科学基础_01</th>
            <script>
                function mDown7(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼C411<br>任课教师：赵方方3-17周";
                }

                function mOut7(obj) {

                    obj.innerHTML = "管理科学基础_01";
                }
            </script>
            <th onmousedown="mDown8(this)" onmouseup="mOut8(this)" style="background-color:rgb(183, 115, 218)" ;>毛泽东思想与中国特色社会主义理论体系概论_13 </th>
            <script>
                function mDown8(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼A120 <br>任课教师：顾洪英";
                }

                function mOut8(obj) {

                    obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13 1-16周";
                }
            </script>
             <th onmousedown="mDown10(this)" onmouseup="mOut10(this)" style="background-color:rgb(192, 128, 230)" ;> 管理科学基础_01</th>
             <script>
                 function mDown10(obj) {
 
                     obj.innerHTML = "教室@西区第一公共教学楼C411<br>任课教师：赵方方 3-17周";
                 }
 
                 function mOut10(obj) {
 
                     obj.innerHTML = "管理科学基础_01";
                 }
             </script>
            <th onmousedown="mDown9(this)" onmouseup="mOut9(this)" style="background-color:rgb(80, 221, 151)" ;>运营管理_02</th>
            <script>
                function mDown9(obj) {

                    obj.innerHTML = " 教室@西区第一公共教学楼B405<br>任课教师：刘亮，邓华 1-15周";
                }

                function mOut9(obj) {

                    obj.innerHTML = "运营管理_02";
                }
            </script>
            <th></th>
            <th></th>

        </tr>

        <tr>
            <td colspan="9" style=" text-align: center; ">午休</td>
        </tr>
        <tr>
            <td rowspan="2">下午</td>

            <th>第三节(14:00-15:40)</th>
            <th onmousedown="mDown11(this)" onmouseup="mOut11(this)" style="background-color:rgb(18, 214, 123)" ;>管理信息系统_02</th>
            <script>
                function mDown11(obj) {

                    obj.innerHTML = "教室：西区第一公共教学楼C105<br>任课教师：刘烨 1-15周";
                }

                function mOut11(obj) {

                    obj.innerHTML = "管理信息系统_02";
                }
            </script>
            <th onmousedown="mDown12(this)" onmouseup="mOut12(this)" style="background-color:rgb(141, 54, 76)" ;>形势与政策2_41</th>
            <script>
                function mDown12(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼C123)5-7周上<br>任课教师：邵夏，李坤 5-7周";
                }

                function mOut12(obj) {

                    obj.innerHTML = "形势与政策2_41";
                }
            </script>
            <th onmousedown="mDown13(this)" onmouseup="mOut13(this)" style="background-color:rgb(255, 153, 122)" ;>会计学_01</th>
            <script>
                function mDown13(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼B101 单周上<br>任课教师：姜红  1-17周;"
                }

                function mOut13(obj) {

                    obj.innerHTML = "会计学_01";
                }
            </script>
            <th onmousedown="mDown14(this)" onmouseup="mOut14(this)" style="background-color:rgb(240, 166, 166)" ;>体育课</th>
            <script>
                function mDown14(obj) {

                    obj.innerHTML = "教室@健身馆2-17周<br>任课教师：1-15周";
                }

                function mOut14(obj) {

                    obj.innerHTML = "体育课";
                }
            </script>
             <th onmousedown="mDown15(this)" onmouseup="mOut15(this)" style="background-color:rgb(146, 236, 93)" ;>毛泽东思想与中国特色社会主义理论体系概论_13 </th>
             <script>
                 function mDown15(obj) {
 
                     obj.innerHTML = "教室@西区第一公共教学楼A120 <br>任课教师：顾洪英 1-16周";
                 }
 
                 function mOut15(obj) {
 
                     obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13";
                 }
             </script>
            <th></th>
            <th></th>
        </tr>
 ；
        <tr>

            <th>第四节(16:00-17:40)</th>
            <th onmousedown="mDown16(this)" onmouseup="mOut16(this)" style="background-color:rgb(12, 128, 93)" ;>电子商务_01 </th> <script>
                function mDown16(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼B303 3-17周 <br>任课教师：张亮 3-17周";
                }

                function mOut16(obj) {

                    obj.innerHTML = "电子商务_01";
                }
            </script>
            <th onmousedown="mDown17(this)" onmouseup="mOut17(this)" style="background-color:rgb(144, 95, 207)" ;>数据库原理及应用_01</th>
            <script>
                function mDown17(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼B405<br>任课教师：吴君1-14 周";
                }

                function mOut17(obj) {

                    obj.innerHTML = "数据库原理及应用_01";
                }
            </script>
            <th></th>
            <th onmousedown="mDown18(this)" onmouseup="mOut18(this)" style="background-color:rgb(255, 153, 122)" ;>会计学_01</th>
            <script>
                function mDown18(obj) {

                    obj.innerHTML = "教室@西区第一公共教学楼B101 单周上<br>任课教师：姜红 3-17周";
                }

                function mOut18(obj) {

                    obj.innerHTML = "会计学_01";
                }
            </script>
            <th></th>
            <th></th>
            <th></th>
        </tr>

        <tr>
            <td colspan="9" style=" text-align: center; ">晚饭</td>

        </tr>
        <tr>
            <td rowspan="1">晚上</td>
            <th>第五节(6:30-8:20)</th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
        </tr>

        </tr>


</body>

</html>
