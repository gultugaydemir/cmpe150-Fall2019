# cmpe150-Fall2019-Project1
<html>
<head><meta http-equiv=Content-Type content="text/html; charset=UTF-8">
<style type="text/css">
<!--
span.cls_002{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_002{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_003{font-family:Times,serif;font-size:12.1px;color:rgb(255,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_003{font-family:Times,serif;font-size:12.1px;color:rgb(255,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_004{font-family:Times,serif;font-size:12.1px;color:rgb(255,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_004{font-family:Times,serif;font-size:12.1px;color:rgb(255,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_005{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_005{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_006{font-family:Arial,serif;font-size:10.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_006{font-family:Arial,serif;font-size:10.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_007{font-family:Arial,serif;font-size:10.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_007{font-family:Arial,serif;font-size:10.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_010{font-family:"Calibri Bold",serif;font-size:11.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_010{font-family:"Calibri Bold",serif;font-size:11.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_011{font-family:Courier New,serif;font-size:14.1px;color:rgb(0,199,124);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_011{font-family:Courier New,serif;font-size:14.1px;color:rgb(0,199,124);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_009{font-family:Courier New,serif;font-size:14.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_009{font-family:Courier New,serif;font-size:14.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
-->
</style>
<script type="text/javascript" src="Question_files/wz_jsgraphics.js"></script>
</head>
<body>
<div style="position:absolute;left:50%;margin-left:-297px;top:0px;width:595px;height:841px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="Question_files/background1.jpg" width=595 height=841></div>
<div style="position:absolute;left:70.82px;top:69.04px" class="cls_002"><span class="cls_002">CMPE 150 C - Fall 2019 - Project 1</span></div>
<div style="position:absolute;left:70.82px;top:96.66px" class="cls_003"><span class="cls_003">IMPORTANT NOTE: </span><span class="cls_004">You will not submit this project and it will not be graded. However,</span></div>
<div style="position:absolute;left:70.82px;top:110.46px" class="cls_004"><span class="cls_004">there will be a similar question to this one in the first midterm. You are encouraged to solve</span></div>
<div style="position:absolute;left:70.82px;top:124.26px" class="cls_004"><span class="cls_004">the project on your own. Please do not memorize the solution since the question in the exam</span></div>
<div style="position:absolute;left:70.82px;top:138.06px" class="cls_004"><span class="cls_004">will not be the exact same question here.</span></div>
<div style="position:absolute;left:70.82px;top:165.90px" class="cls_005"><span class="cls_005">Write a program which reads an integer </span><span class="cls_002">N </span><span class="cls_005">and a character</span><span class="cls_002"> sym</span><span class="cls_005"> from the user and prints a</span></div>
<div style="position:absolute;left:70.82px;top:179.70px" class="cls_005"><span class="cls_005">'</span><span class="cls_002">tree</span><span class="cls_005">' with height defined by N  trunk parts by using /, \  and </span><span class="cls_002">sym</span><span class="cls_005"> characters. For instance, if N</span></div>
<div style="position:absolute;left:70.82px;top:193.50px" class="cls_005"><span class="cls_005">is 5 and sym is L, then tree will have 5 trunk parts in which trunk is represented by sym and</span></div>
<div style="position:absolute;left:70.82px;top:207.30px" class="cls_005"><span class="cls_005">the leaves are represented with /, \ characters.</span></div>
<div style="position:absolute;left:70.82px;top:235.02px" class="cls_005"><span class="cls_005">If you look at the first example, you can observe followings:</span></div>
<div style="position:absolute;left:88.82px;top:262.86px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   The given inputs are 5 and L, which means N is 5 and the sym is L.</span></div>
<div style="position:absolute;left:88.82px;top:276.69px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   Leaves consist of / and \ symbols</span></div>
<div style="position:absolute;left:88.82px;top:290.49px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   Tree has 5 trunk parts and the height of each part is related with its level.  The trunk is</span></div>
<div style="position:absolute;left:106.82px;top:304.29px" class="cls_005"><span class="cls_005">represented with L.</span></div>
<div style="position:absolute;left:88.82px;top:318.09px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   The height and width of the bottom trunk also changes with N.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-297px;top:851px;width:595px;height:841px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="Question_files/background2.jpg" width=595 height=841></div>
<div style="position:absolute;left:70.82px;top:68.80px" class="cls_005"><span class="cls_005">In the second example:</span></div>
<div style="position:absolute;left:88.82px;top:96.66px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   means N is 6 and the sym is |.</span></div>
<div style="position:absolute;left:88.82px;top:110.46px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   Leaves consist of / and \ symbols</span></div>
<div style="position:absolute;left:88.82px;top:124.26px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   Tree has 6 trunk parts and the height of each part is related with its level.  The trunk is</span></div>
<div style="position:absolute;left:106.82px;top:138.06px" class="cls_005"><span class="cls_005">represented with |.</span></div>
<div style="position:absolute;left:88.82px;top:151.86px" class="cls_006"><span class="cls_006"></span><span class="cls_007"> </span><span class="cls_005">   The height and width of the bottom trunk also changes with N.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-297px;top:1702px;width:595px;height:841px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="Question_files/background3.jpg" width=595 height=841></div>
<div style="position:absolute;left:70.82px;top:69.16px" class="cls_010"><span class="cls_010">Examples</span></div>
<div style="position:absolute;left:70.82px;top:90.42px" class="cls_011"><span class="cls_011">8 f</span></div>
<div style="position:absolute;left:188.42px;top:106.26px" class="cls_009"><span class="cls_009">/f\</span></div>
<div style="position:absolute;left:180.02px;top:122.10px" class="cls_009"><span class="cls_009">//f\\</span></div>
<div style="position:absolute;left:171.62px;top:137.94px" class="cls_009"><span class="cls_009">///f\\\</span></div>
<div style="position:absolute;left:171.62px;top:153.78px" class="cls_009"><span class="cls_009">///f\\\</span></div>
<div style="position:absolute;left:163.22px;top:169.74px" class="cls_009"><span class="cls_009">////f\\\\</span></div>
<div style="position:absolute;left:154.82px;top:185.58px" class="cls_009"><span class="cls_009">/////f\\\\\</span></div>
<div style="position:absolute;left:163.22px;top:201.42px" class="cls_009"><span class="cls_009">////f\\\\</span></div>
<div style="position:absolute;left:154.82px;top:217.26px" class="cls_009"><span class="cls_009">/////f\\\\\</span></div>
<div style="position:absolute;left:146.42px;top:233.10px" class="cls_009"><span class="cls_009">//////f\\\\\\</span></div>
<div style="position:absolute;left:138.02px;top:248.94px" class="cls_009"><span class="cls_009">///////f\\\\\\\</span></div>
<div style="position:absolute;left:154.82px;top:264.90px" class="cls_009"><span class="cls_009">/////f\\\\\</span></div>
<div style="position:absolute;left:146.42px;top:280.77px" class="cls_009"><span class="cls_009">//////f\\\\\\</span></div>
<div style="position:absolute;left:138.02px;top:296.61px" class="cls_009"><span class="cls_009">///////f\\\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:312.45px" class="cls_009"><span class="cls_009">////////f\\\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:328.29px" class="cls_009"><span class="cls_009">/////////f\\\\\\\\\</span></div>
<div style="position:absolute;left:146.42px;top:344.13px" class="cls_009"><span class="cls_009">//////f\\\\\\</span></div>
<div style="position:absolute;left:138.02px;top:360.09px" class="cls_009"><span class="cls_009">///////f\\\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:375.93px" class="cls_009"><span class="cls_009">////////f\\\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:391.77px" class="cls_009"><span class="cls_009">/////////f\\\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:407.61px" class="cls_009"><span class="cls_009">//////////f\\\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:423.45px" class="cls_009"><span class="cls_009">///////////f\\\\\\\\\\\</span></div>
<div style="position:absolute;left:138.02px;top:439.29px" class="cls_009"><span class="cls_009">///////f\\\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:455.25px" class="cls_009"><span class="cls_009">////////f\\\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:471.11px" class="cls_009"><span class="cls_009">/////////f\\\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:486.95px" class="cls_009"><span class="cls_009">//////////f\\\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:502.79px" class="cls_009"><span class="cls_009">///////////f\\\\\\\\\\\</span></div>
<div style="position:absolute;left:96.02px;top:518.63px" class="cls_009"><span class="cls_009">////////////f\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:87.62px;top:534.47px" class="cls_009"><span class="cls_009">/////////////f\\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:550.43px" class="cls_009"><span class="cls_009">////////f\\\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:566.27px" class="cls_009"><span class="cls_009">/////////f\\\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:582.11px" class="cls_009"><span class="cls_009">//////////f\\\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:597.95px" class="cls_009"><span class="cls_009">///////////f\\\\\\\\\\\</span></div>
<div style="position:absolute;left:96.02px;top:613.79px" class="cls_009"><span class="cls_009">////////////f\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:87.62px;top:629.63px" class="cls_009"><span class="cls_009">/////////////f\\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:79.22px;top:645.50px" class="cls_009"><span class="cls_009">//////////////f\\\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:70.82px;top:661.46px" class="cls_009"><span class="cls_009">///////////////f\\\\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:163.22px;top:677.30px" class="cls_009"><span class="cls_009">ffffffff</span></div>
<div style="position:absolute;left:163.22px;top:693.14px" class="cls_009"><span class="cls_009">ffffffff</span></div>
<div style="position:absolute;left:163.22px;top:708.98px" class="cls_009"><span class="cls_009">ffffffff</span></div>
<div style="position:absolute;left:163.22px;top:724.82px" class="cls_009"><span class="cls_009">ffffffff</span></div>
<div style="position:absolute;left:163.22px;top:740.66px" class="cls_009"><span class="cls_009">ffffffff</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-297px;top:2553px;width:595px;height:841px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="Question_files/background4.jpg" width=595 height=841></div>
<div style="position:absolute;left:70.82px;top:67.84px" class="cls_011"><span class="cls_011">3 w</span></div>
<div style="position:absolute;left:104.42px;top:83.82px" class="cls_009"><span class="cls_009">/w\</span></div>
<div style="position:absolute;left:96.02px;top:99.66px" class="cls_009"><span class="cls_009">//w\\</span></div>
<div style="position:absolute;left:87.62px;top:115.50px" class="cls_009"><span class="cls_009">///w\\\</span></div>
<div style="position:absolute;left:87.62px;top:131.34px" class="cls_009"><span class="cls_009">///w\\\</span></div>
<div style="position:absolute;left:79.22px;top:147.18px" class="cls_009"><span class="cls_009">////w\\\\</span></div>
<div style="position:absolute;left:70.82px;top:163.02px" class="cls_009"><span class="cls_009">/////w\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:178.98px" class="cls_009"><span class="cls_009">www</span></div>
<div style="position:absolute;left:104.42px;top:194.82px" class="cls_009"><span class="cls_009">www</span></div>
<div style="position:absolute;left:70.82px;top:300.69px" class="cls_011"><span class="cls_011">4 |</span></div>
<div style="position:absolute;left:121.22px;top:316.53px" class="cls_009"><span class="cls_009">/|\</span></div>
<div style="position:absolute;left:112.82px;top:332.37px" class="cls_009"><span class="cls_009">//|\\</span></div>
<div style="position:absolute;left:104.42px;top:348.21px" class="cls_009"><span class="cls_009">///|\\\</span></div>
<div style="position:absolute;left:104.42px;top:364.05px" class="cls_009"><span class="cls_009">///|\\\</span></div>
<div style="position:absolute;left:96.02px;top:379.89px" class="cls_009"><span class="cls_009">////|\\\\</span></div>
<div style="position:absolute;left:87.62px;top:395.85px" class="cls_009"><span class="cls_009">/////|\\\\\</span></div>
<div style="position:absolute;left:96.02px;top:411.69px" class="cls_009"><span class="cls_009">////|\\\\</span></div>
<div style="position:absolute;left:87.62px;top:427.53px" class="cls_009"><span class="cls_009">/////|\\\\\</span></div>
<div style="position:absolute;left:79.22px;top:443.37px" class="cls_009"><span class="cls_009">//////|\\\\\\</span></div>
<div style="position:absolute;left:70.82px;top:459.23px" class="cls_009"><span class="cls_009">///////|\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:475.07px" class="cls_009"><span class="cls_009">||||</span></div>
<div style="position:absolute;left:112.82px;top:490.91px" class="cls_009"><span class="cls_009">||||</span></div>
<div style="position:absolute;left:112.82px;top:506.87px" class="cls_009"><span class="cls_009">||||</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-297px;top:3404px;width:595px;height:841px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="Question_files/background5.jpg" width=595 height=841></div>
<div style="position:absolute;left:70.82px;top:67.84px" class="cls_011"><span class="cls_011">7 y</span></div>
<div style="position:absolute;left:171.62px;top:83.82px" class="cls_009"><span class="cls_009">/y\</span></div>
<div style="position:absolute;left:163.22px;top:99.66px" class="cls_009"><span class="cls_009">//y\\</span></div>
<div style="position:absolute;left:154.82px;top:115.50px" class="cls_009"><span class="cls_009">///y\\\</span></div>
<div style="position:absolute;left:154.82px;top:131.34px" class="cls_009"><span class="cls_009">///y\\\</span></div>
<div style="position:absolute;left:146.42px;top:147.18px" class="cls_009"><span class="cls_009">////y\\\\</span></div>
<div style="position:absolute;left:138.02px;top:163.02px" class="cls_009"><span class="cls_009">/////y\\\\\</span></div>
<div style="position:absolute;left:146.42px;top:178.98px" class="cls_009"><span class="cls_009">////y\\\\</span></div>
<div style="position:absolute;left:138.02px;top:194.82px" class="cls_009"><span class="cls_009">/////y\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:210.66px" class="cls_009"><span class="cls_009">//////y\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:226.50px" class="cls_009"><span class="cls_009">///////y\\\\\\\</span></div>
<div style="position:absolute;left:138.02px;top:242.34px" class="cls_009"><span class="cls_009">/////y\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:258.18px" class="cls_009"><span class="cls_009">//////y\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:274.17px" class="cls_009"><span class="cls_009">///////y\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:290.01px" class="cls_009"><span class="cls_009">////////y\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:305.85px" class="cls_009"><span class="cls_009">/////////y\\\\\\\\\</span></div>
<div style="position:absolute;left:129.62px;top:321.69px" class="cls_009"><span class="cls_009">//////y\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:337.53px" class="cls_009"><span class="cls_009">///////y\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:353.37px" class="cls_009"><span class="cls_009">////////y\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:369.21px" class="cls_009"><span class="cls_009">/////////y\\\\\\\\\</span></div>
<div style="position:absolute;left:96.02px;top:385.17px" class="cls_009"><span class="cls_009">//////////y\\\\\\\\\\</span></div>
<div style="position:absolute;left:87.62px;top:401.01px" class="cls_009"><span class="cls_009">///////////y\\\\\\\\\\\</span></div>
<div style="position:absolute;left:121.22px;top:416.85px" class="cls_009"><span class="cls_009">///////y\\\\\\\</span></div>
<div style="position:absolute;left:112.82px;top:432.69px" class="cls_009"><span class="cls_009">////////y\\\\\\\\</span></div>
<div style="position:absolute;left:104.42px;top:448.53px" class="cls_009"><span class="cls_009">/////////y\\\\\\\\\</span></div>
<div style="position:absolute;left:96.02px;top:464.39px" class="cls_009"><span class="cls_009">//////////y\\\\\\\\\\</span></div>
<div style="position:absolute;left:87.62px;top:480.35px" class="cls_009"><span class="cls_009">///////////y\\\\\\\\\\\</span></div>
<div style="position:absolute;left:79.22px;top:496.19px" class="cls_009"><span class="cls_009">////////////y\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:70.82px;top:512.03px" class="cls_009"><span class="cls_009">/////////////y\\\\\\\\\\\\\</span></div>
<div style="position:absolute;left:154.82px;top:527.87px" class="cls_009"><span class="cls_009">yyyyyyy</span></div>
<div style="position:absolute;left:154.82px;top:543.71px" class="cls_009"><span class="cls_009">yyyyyyy</span></div>
<div style="position:absolute;left:154.82px;top:559.55px" class="cls_009"><span class="cls_009">yyyyyyy</span></div>
<div style="position:absolute;left:154.82px;top:575.51px" class="cls_009"><span class="cls_009">yyyyyyy</span></div>
</div>

</body>
</html>
