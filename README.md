<!DOCTYPE html>
<!-- saved from url=(0045)http://smilecoc.vip/data_dashboard/index.html -->
<html lang="en" style="font-size: 99.7396px;"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="renderer" content="webkit">
    <meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=no">

    <script type="text/javascript" src="./智慧物流服务中心-首页_files/rem.js.下载"></script>
    <link rel="stylesheet" href="./智慧物流服务中心-首页_files/style.css">
    <title>智慧物流服务中心-首页</title>
<link rel="stylesheet" href="./智慧物流服务中心-首页_files/layer.css" id="layui_layer_skinlayercss" style=""><link type="text/css" rel="stylesheet" href="./智慧物流服务中心-首页_files/laydate.css"><link type="text/css" rel="stylesheet" href="./智慧物流服务中心-首页_files/laydate(1).css" id="LayDateSkin"></head>

<body style="visibility: visible;">
    <div class="container-flex" tabindex="0" hidefocus="true">
        <div class="box-left">
            <div class="left-top">
                <div class="current-num">
                    <div>当前到件量</div>
                    <p>123,456,789</p>
                </div>
            </div>
            <div class="left-center">
                <div class="title-box">
                    <h6>派件入库量占比</h6>
                </div>
                <div class="chart-box pie-chart">
                    <div id="pie" _echarts_instance_="ec_1652530513073" style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative;"><div style="position: relative; overflow: hidden; width: 241px; height: 296px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="241" height="296" style="position: absolute; left: 0px; top: 0px; width: 241px; height: 296px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                    <div>
                        <div class="pie-data">

                        <p><span><i class="legend" style="background:#0e94eb"></i></span>顺丰<span class="pie-number" style="color:#0e94eb">192581</span>30.87%</p><p><span><i class="legend" style="background:#c440ef"></i></span>京东<span class="pie-number" style="color:#c440ef">215635</span>34.08%</p><p><span><i class="legend" style="background:#efb013"></i></span>EMS<span class="pie-number" style="color:#efb013">224585</span>35.49%</p></div>
                    </div>
                </div>
            </div>
            <div class="left-bottom">
                <div class="title-box">
                    <h6>广东省寄派件数据</h6>
                    <img class="line-img" src="./智慧物流服务中心-首页_files/line-blue.png" alt="">
                    <button id="filBtn"><img src="./智慧物流服务中心-首页_files/select_icon.png" alt="">筛选</button>
                </div>
                <div class="chart-box">
                    <div class="filter-con" id="filCon" data-type="1">
                        <div class="select" tabindex="0" hidefocus="true">
                            <div class="select-div">
                                派件
                            </div>
                            <ul class="select-ul">
                                <li class="active" data-value="1">派件</li>
                                <li data-value="2">寄件</li>
                            </ul>
                        </div>
                        <div class="select" tabindex="0" hidefocus="true">
                            <div class="select-div">
                                公司
                            </div>
                            <ul class="select-ul company">
                                <li class="active" data-value="">公司</li>
                                <li data-value="1">顺丰</li>
                                <li data-value="2">京东</li>
                                <li data-value="2">EMS</li>
                            </ul>
                        </div>
                        <div class="select" tabindex="0" hidefocus="true">
                            <div class="select-div">
                                快件类型
                            </div>
                            <ul class="select-ul">
                                <li class="active" data-value="">快件类型</li>
                                <li data-value="0">文件</li>
                                <li data-value="1">物品</li>
                            </ul>
                        </div>
                    </div>
                    <div id="gdMap" class="gd-map" _echarts_instance_="ec_1652530513075" style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative;"><div style="position: relative; overflow: hidden; width: 483px; height: 312px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="483" height="312" style="position: absolute; left: 0px; top: 0px; width: 483px; height: 312px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                </div>
            </div>
        </div>
        <div class="box-center">
            <div class="center-top">
                <h1>智慧物流服务中心</h1>
            </div>
            <div class="center-center">
                <div class="weather-box">
                    <div class="data">
                        <p class="time" id="time">20:19:57</p>
                        <p id="date"><span>2022/5/14</span><span>pm</span><span>周6</span></p>
                    </div>
                    <div class="weather">
                        <img id="weatherImg" src="./智慧物流服务中心-首页_files/weather_img01.png" alt="">
                        <div id="weather">
                            <p class="active">多云</p>
                            <p>16-22℃</p>
                            <p>深圳市南山区</p>
                        </div>
                    </div>
                </div>
                <img src="./智慧物流服务中心-首页_files/line_bg.png" alt="">
                <div class="select-box">
                    <ul id="barType">
                        <li class="active" data-value="1">派件</li>
                        <li data-value="2" class="">寄件</li>
                    </ul>
                    <div data-type="2">
                        <div class="select" tabindex="0" hidefocus="true">
                            <div class="select-div">顺丰</div>
                            <ul class="select-ul company" style="display: none;">
                                <li class="" data-value="">公司</li>
                                <li data-value="1" class="active">顺丰</li>
                                <li data-value="2">京东</li>
                                <li data-value="2">EMS</li>
                            </ul>
                        </div>
                        <div class="select" tabindex="0" hidefocus="true">
                            <div class="select-div">文件</div>
                            <ul class="select-ul" style="display: none;">
                                <li class="" data-value="">快件类型</li>
                                <li data-value="0" class="active">文件</li>
                                <li data-value="1">物品</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="center-bottom">
                <div class="chart-box">
                    <div id="chart4" style="width: 100%; height: 95%; -webkit-tap-highlight-color: transparent; user-select: none; position: relative;" _echarts_instance_="ec_1652530513079"><div style="position: relative; overflow: hidden; width: 758px; height: 619px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="758" height="619" style="position: absolute; left: 0px; top: 0px; width: 758px; height: 619px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas><canvas data-zr-dom-id="zr_2" width="758" height="619" style="position: absolute; left: 0px; top: 0px; width: 758px; height: 619px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                </div>
                <div class="city-data">
                    <div class="city-box">
                        <p id="titleQ"><span>吉林</span>到珠海</p>
                        <ul class="city-btn" data-city="1">
                            <li class="active">全网</li>
                            <li>ABCDE</li>
                            <li>FGHIJ</li>
                            <li>KLMNO</li>
                            <li>PQRST</li>
                            <li>UVWXYZ</li>
                        </ul>
                        <ul class="city-div" id="city"><li>北京</li><li>天津</li><li>河北</li><li>山西</li><li>内蒙古</li><li>辽宁</li><li class="active">吉林</li><li>黑龙江</li><li>上海</li><li>江苏</li><li>浙江</li><li>安徽</li><li>福建</li><li>江西</li><li>山东</li><li>河南</li><li>湖北</li><li>湖南</li><li>广东</li><li>海南</li><li>广西</li><li>甘肃</li><li>陕西省</li><li>新疆维吾尔</li><li>青海</li><li>宁夏</li><li>重庆</li><li>四川省</li><li>贵州省</li><li>云南省</li><li>西藏</li><li>台湾</li><li>澳门</li><li>香港</li></ul>
                    </div>
                    <ul class="ranking-box" style="display: none;"><li><span></span><p>城市</p><p>派件</p></li><li><span>1</span><p>天津市</p><p>178546</p></li><li><span>2</span><p>湖南省</p><p>125687</p></li><li><span>3</span><p>福建省</p><p>78452</p></li><li><span>4</span><p>北京市</p><p>57841</p></li><li><span>5</span><p>江苏省</p><p>45879</p></li><li><span>6</span><p>海南</p><p>28584</p></li><li><span>7</span><p>四川省</p><p>14852</p></li><li><span>8</span><p>浙江省</p><p>12589</p></li><li><span>9</span><p>重庆市</p><p>5261</p></li><li><span>10</span><p>香港特别行政区</p><p>2563</p></li></ul>
                    <div class="enlarge-box">
                        <button class="enlarge-btn" id="fangda"></button>
                        <ul class="modal-btn">
                            <li>
                                <div></div>1</li>
                            <li>
                                <div></div>2</li>
                            <li>
                                <div></div>3</li>
                            <li>
                                <div></div>4</li>
                            <li>
                                <div></div>5</li>
                            <li>
                                <div></div>6</li>
                        </ul>
                    </div>
                </div>
            </div>

        </div>
        <div class="box-right">
            <div class="right-top">
                <div class="title-box">
                    <h6 id="barTitle">派件数据</h6>
                    <img class="line-img" src="./智慧物流服务中心-首页_files/line-blue.png" alt="">
                    <button data-state="1" id="tabBtn"><img src="./智慧物流服务中心-首页_files/chart_icon.png" alt=""><span>图表</span></button>
                </div>
                <p class="unit">单位：件</p>
                <div class="chart-box">
                    <div id="chart3" style="width: 100%; height: 100%; -webkit-tap-highlight-color: transparent; user-select: none; position: relative;" _echarts_instance_="ec_1652530513077"><div style="position: relative; overflow: hidden; width: 483px; height: 275px; padding: 0px; margin: 0px; border-width: 0px; cursor: default;"><canvas data-zr-dom-id="zr_0" width="483" height="275" style="position: absolute; left: 0px; top: 0px; width: 483px; height: 275px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div style="position: absolute; display: none; border-style: solid; white-space: nowrap; z-index: 9999999; transition: left 0.4s cubic-bezier(0.23, 1, 0.32, 1) 0s, top 0.4s cubic-bezier(0.23, 1, 0.32, 1) 0s; background-color: rgba(50, 50, 50, 0.7); border-width: 0px; border-color: rgb(51, 51, 51); border-radius: 4px; color: rgb(255, 255, 255); font: 14px / 21px &quot;Microsoft YaHei&quot;; padding: 5px; left: 146px; top: 213px;">入库件<br><span style="display:inline-block;margin-right:5px;border-radius:10px;width:10px;height:10px;background-color:#0e94eb;"></span>入库件: 584</div><div style="display: none;"></div><div style="display: none;"></div><div></div></div>
                </div>
                <div class="data-box" style="display:none;">
                    <table class="table1" style="">
                        <tbody><tr>
                            <td>入库件</td>
                            <td colspan="3" class="table-data dph-data1">584</td>
                        </tr>
                        <tr class="bg-color">
                            <td rowspan="2">在库件</td>
                            <td rowspan="2" class="table-data dph-data2">841</td>
                            <td>正常件</td>
                            <td class="table-data dph-data3">689</td>
                        </tr>
                        <tr class="bg-color">
                            <td>滞留件</td>
                            <td class="table-data dph-data5">152</td>
                        </tr>
                        <tr>
                            <td rowspan="2">出库件</td>
                            <td rowspan="2" class="dph-data6">321</td>
                            <td>派送件</td>
                            <td class="table-data dph-data7">200</td>
                        </tr>
                        <tr>
                            <td>自提件</td>
                            <td class="table-data dph-data8">121</td>
                        </tr>
                        <tr class="bg-color">
                            <td>退签件</td>
                            <td colspan="3" class="table-data dph-data9">92</td>
                        </tr>
                        <tr>
                            <td>丢失件</td>
                            <td colspan="3" class="table-data dph-data4">100</td>
                        </tr>
                    </tbody></table>
                    <table class="table1" style="display: none;">
                        <tbody><tr>
                            <td>入库件</td>
                            <td colspan="3" class="table-data mail-data1">568</td>
                        </tr>
                        <tr class="bg-color">
                            <td rowspan="2">在库件</td>
                            <td rowspan="2" class="table-data mail-data2">242</td>
                            <td>正常件</td>
                            <td class="table-data mail-data7">122</td>
                        </tr>
                        <tr class="bg-color">
                            <td>滞留件</td>
                            <td class="table-data mail-data4">120</td>
                        </tr>

                        <tr>
                            <td>出库件</td>
                            <td colspan="3" class="mail-data6">125</td>
                        </tr>
                        <tr class="bg-color">
                            <td>丢失件</td>
                            <td colspan="3" class="mail-data3">287</td>
                        </tr>
                        <tr>
                            <td>撤销件</td>
                            <td colspan="3" class="table-data mail-data5">152</td>
                        </tr>
                    </tbody></table>
                </div>
            </div>
            <div class="right-center">
                <div class="title-box">
                    <p id="switchBtn"><span class="active" data-datatype="income">收入数据</span><img class="line-img" src="./智慧物流服务中心-首页_files/line-blue.png" alt=""><span data-datatype="expend">支出数据</span></p>
                    <img class="line-img" src="./智慧物流服务中心-首页_files/line-blue.png" alt="">
                    <button id="dateBtn"><img src="./智慧物流服务中心-首页_files/data_icon.png" alt="">日期</button>
                </div>
                <div class="data-box">
                    <p class="data-number" id="totalProfit">123,456.5元</p>
                    <div class="time-box" id="timeBox">
                        <div class="time-div">
                            <input class="time-input" type="text" value="" id="startTime">
                            <img src="./智慧物流服务中心-首页_files/selsct_time.png" alt="">
                        </div>
                        <div class="time-div end">
                            <input class="time-input" type="text" value="" id="endTime">
                            <img src="./智慧物流服务中心-首页_files/selsct_time.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="right-bottom">
                <div class="title-box">
                    <button id="setBtn"><img src="./智慧物流服务中心-首页_files/settings_icon.png" alt="">设置</button>
                </div>
                <div class="data-box">
                    <div class="settings-box">
                        <p><img src="./智慧物流服务中心-首页_files/teacher_icon.png" alt="">今日值班：<span id="name_a"></span><span id="date_a"></span></p>
                        <p><img src="./智慧物流服务中心-首页_files/people_iocn.png" alt="">负责人：<span id="lea_a"></span></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container" style="visibility: visible; display: none;">
        <div class="pop-up" style="visibility: hidden">
            <span class="close-pop"></span>
            <h2 class="title">当前到件量</h2>
            <div class="pop-data-box">
                <p>123,456,789</p>
            </div>
        </div>

        <div class="pop-up" style="visibility: hidden">
            <span class="close-pop"></span>
            <h2 class="title">派件入库量占比</h2>
            <div class="chart-box pie-chart">
                <div id="pie1" _echarts_instance_="ec_1652530513074" style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative;"><div style="position: relative; overflow: hidden; width: 50px; height: 100px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="50" height="100" style="position: absolute; left: 0px; top: 0px; width: 50px; height: 100px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                <div>
                    <div class="pie-data">
                    <p><span><i class="legend" style="background:#0e94eb"></i></span>顺丰<span class="pie-number" style="color:#0e94eb">192581</span>30.87%</p><p><span><i class="legend" style="background:#c440ef"></i></span>京东<span class="pie-number" style="color:#c440ef">215635</span>34.08%</p><p><span><i class="legend" style="background:#efb013"></i></span>EMS<span class="pie-number" style="color:#efb013">224585</span>35.49%</p></div>
                </div>
            </div>
        </div>

        <div class="pop-up" style="visibility: hidden">
            <span class="close-pop"></span>
            <h2 class="title">广东省寄派件数据 </h2>
            <div class="filter-con pop-filter" style="display:flex" data-type="3">
                <div class="select" tabindex="0" hidefocus="true">
                    <div class="select-div">
                        派件
                    </div>
                    <ul class="select-ul">
                        <li class="active" data-value="1">派件</li>
                        <li data-value="2">寄件</li>
                    </ul>
                </div>
                <div class="select" tabindex="0" hidefocus="true">
                    <div class="select-div">
                        公司
                    </div>
                    <ul class="select-ul company">
                        <li class="active" data-value="">公司</li>
                        <li data-value="1">顺丰</li>
                        <li data-value="2">京东</li>
                        <li data-value="2">EMS</li>
                    </ul>
                </div>
                <div class="select" tabindex="0" hidefocus="true">
                    <div class="select-div">
                        快件类型
                    </div>
                    <ul class="select-ul">
                        <li class="active" data-value="">快件类型</li>
                        <li data-value="0">文件</li>
                        <li data-value="1">物品</li>
                    </ul>
                </div>
            </div>
            <div class="chart-box pop-chart">
                <div id="gdMaps" class="gd-map" _echarts_instance_="ec_1652530513076" style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative;"><div style="position: relative; overflow: hidden; width: 100px; height: 90px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="100" height="90" style="position: absolute; left: 0px; top: 0px; width: 100px; height: 90px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
            </div>
        </div>

        <div class="pop-up" style="visibility: hidden">
            <span class="close-pop"></span>
            <div class="filter-con pop-filters" style="display:flex" data-type="4">
                <div class="select-pop" tabindex="0" hidefocus="true">
                    <ul id="barTypes">
                        <li class="active" data-value="1">派件</li>
                        <li data-value="2">寄件</li>
                    </ul>
                </div>
                <div class="select" tabindex="0" hidefocus="true">
                    <div class="select-div">
                        公司
                    </div>
                    <ul class="select-ul company">
                        <li class="active" data-value="">公司</li>
                        <li data-value="1">顺丰</li>
                        <li data-value="2">京东</li>
                        <li data-value="2">EMS</li>
                    </ul>
                </div>
                <div class="select" tabindex="0" hidefocus="true">
                    <div class="select-div">
                        快件类型
                    </div>
                    <ul class="select-ul">
                        <li class="active" data-value="">快件类型</li>
                        <li data-value="0">文件</li>
                        <li data-value="1">物品</li>
                    </ul>
                </div>
            </div>
            <div class="cont-div" style="visibility: hidden">
                <div class="chart-box pop-charts">
                    <div id="chart4s" style="width: 100%; height: 95%; -webkit-tap-highlight-color: transparent; user-select: none; position: relative;" _echarts_instance_="ec_1652530513080"><div style="position: relative; overflow: hidden; width: 100px; height: 95px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="100" height="95" style="position: absolute; left: 0px; top: 0px; width: 100px; height: 95px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas><canvas data-zr-dom-id="zr_2" width="100" height="95" style="position: absolute; left: 0px; top: 0px; width: 100px; height: 95px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                </div>
            </div>
            <div class="cont-div" style="visibility: hidden">
                <h2 class="title" id="barTitles">派件数据</h2>
                <button class="btn-class" data-state="1" id="tabBtns"><img src="./智慧物流服务中心-首页_files/chart_icon.png" alt=""><span>图表</span></button>
                <div class="chart-box pop-chart">
                    <div id="chart3s" style="width: 100%; height: 90%; -webkit-tap-highlight-color: transparent; user-select: none; position: relative;" _echarts_instance_="ec_1652530513078"><div style="position: relative; overflow: hidden; width: 100px; height: 90px; padding: 0px; margin: 0px; border-width: 0px;"><canvas data-zr-dom-id="zr_0" width="100" height="90" style="position: absolute; left: 0px; top: 0px; width: 100px; height: 90px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"></canvas></div><div></div></div>
                </div>
                <div class="data-box" style="top:25%;width:8.6rem;display:none;">
                    <table class="table2">
                        <tbody><tr>
                            <td>入库件</td>
                            <td colspan="3" class="table-data dph-data1">584</td>
                        </tr>
                        <tr class="bg-color">
                            <td rowspan="2">在库件</td>
                            <td rowspan="2" class="table-data dph-data2">841</td>
                            <td>正常件</td>
                            <td class="table-data dph-data3">689</td>
                        </tr>
                        <tr class="bg-color">
                            <td>滞留件</td>
                            <td class="table-data dph-data5">152</td>
                        </tr>
                        <tr>
                            <td rowspan="2">出库件</td>
                            <td rowspan="2" class="dph-data6">321</td>
                            <td>派送件</td>
                            <td class="table-data dph-data7">200</td>
                        </tr>
                        <tr>
                            <td>自提件</td>
                            <td class="table-data dph-data8">121</td>
                        </tr>
                        <tr class="bg-color">
                            <td>退签件</td>
                            <td colspan="3" class="table-data dph-data9">92</td>
                        </tr>
                        <tr>
                            <td>丢失件</td>
                            <td colspan="3" class="table-data dph-data4">100</td>
                        </tr>
                    </tbody></table>
                    <table class="table2" style="display:none;">
                        <tbody><tr>
                            <td>入库件</td>
                            <td colspan="3" class="table-data mail-data1">568</td>
                        </tr>
                        <tr class="bg-color">
                            <td rowspan="2">在库件</td>
                            <td rowspan="2" class="table-data mail-data2">242</td>
                            <td>正常件</td>
                            <td class="table-data mail-data7">122</td>
                        </tr>
                        <tr class="bg-color">
                            <td>滞留件</td>
                            <td class="table-data mail-data4">120</td>
                        </tr>

                        <tr>
                            <td>出库件</td>
                            <td colspan="3" class="mail-data6">125</td>
                        </tr>
                        <tr class="bg-color">
                            <td>丢失件</td>
                            <td colspan="3" class="mail-data3">287</td>
                        </tr>
                        <tr>
                            <td>撤销件</td>
                            <td colspan="3" class="table-data mail-data5">152</td>
                        </tr>
                    </tbody></table>
                </div>
            </div>
            <div class="cont-div" style="visibility: hidden">
                <h2 class="title" id="titles"></h2>
                <button class="btn-class" id="dateBtns"><img src="./智慧物流服务中心-首页_files/data_icon.png" alt="">日期</button>
                <div class="data-box  pop-time">
                    <div class="time-box" id="timeBoxs">
                        <div class="time-div">
                            <input class="time-input" type="text" value="" id="startTimes">
                            <img src="./智慧物流服务中心-首页_files/selsct_time.png" alt="">
                        </div>
                        <div class="time-div end">
                            <input class="time-input" type="text" value="" id="endTimes">
                            <img src="./智慧物流服务中心-首页_files/selsct_time.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="pop-data-box" id="totalProfits">
                    <p></p>
                </div>
            </div>
            <div class="pop-data">
                <div class="city-data">
                    <div class="city-box">
                        <p id="titleQs"><span>全网</span>到珠海</p>
                        <ul class="city-btn" data-city="2">
                            <li class="active">全网</li>
                            <li>ABCDE</li>
                            <li>FGHIJ</li>
                            <li>KLMNO</li>
                            <li>PQRST</li>
                            <li>UVWXYZ</li>
                        </ul>
                        <ul class="city-div" id="citys"><li>北京</li><li>天津</li><li>河北</li><li>山西</li><li>内蒙古</li><li>辽宁</li><li>吉林</li><li>黑龙江</li><li>上海</li><li>江苏</li><li>浙江</li><li>安徽</li><li>福建</li><li>江西</li><li>山东</li><li>河南</li><li>湖北</li><li>湖南</li><li>广东</li><li>海南</li><li>广西</li><li>甘肃</li><li>陕西省</li><li>新疆维吾尔</li><li>青海</li><li>宁夏</li><li>重庆</li><li>四川省</li><li>贵州省</li><li>云南省</li><li>西藏</li><li>台湾</li><li>澳门</li><li>香港</li></ul>
                    </div>
                    <ul class="ranking-box"><li><span></span><p>城市</p><p>派件</p></li><li><span>1</span><p>天津市</p><p>178546</p></li><li><span>2</span><p>湖南省</p><p>125687</p></li><li><span>3</span><p>福建省</p><p>78452</p></li><li><span>4</span><p>北京市</p><p>57841</p></li><li><span>5</span><p>江苏省</p><p>45879</p></li><li><span>6</span><p>海南</p><p>28584</p></li><li><span>7</span><p>四川省</p><p>14852</p></li><li><span>8</span><p>浙江省</p><p>12589</p></li><li><span>9</span><p>重庆市</p><p>5261</p></li><li><span>10</span><p>香港特别行政区</p><p>2563</p></li></ul>

                </div>
            </div>
        </div>
        <div class="pop-up" style="visibility: visible">
            <span class="close-pop"></span>
            <h2 class="title">设置</h2>
            <div class="set-div">
                <div class="set-box">
                    <label class="four-f" for="">排班日期</label>
                    <div class="time-div">
                        <input class="time-input" type="text" value="" id="times">
                        <img src="./智慧物流服务中心-首页_files/selsct_time.png" alt="">
                    </div>
                </div>
                <div class="set-box">
                    <label for="">值班人</label>
                    <input type="text" value="">
                    <button class="plus" id="addT"></button>
                    <button class="mineus" id="mineusT" style="display:none;"></button>
                </div>
                <div class="set-box">
                    <label for="">负责人</label>
                    <input type="text" value="">
                    <button class="plus" id="addL" style=""></button>
                    <button class="mineus" id="mineusL" style="display: none;"></button>
                    <button class="add-btn" id="addSet"><img src="./智慧物流服务中心-首页_files/plus.png" alt="">添加</button>
                </div>
                <table class="table3">
                    <thead>
                        <tr>
                            <th>值班人</th>
                            <th>排班日期</th>
                            <th>负责人</th>
                            <th>操作</th>
                        </tr>
                    </thead>
                    <tbody id="tList">
<!--
                        <tr>
                            <td colspan="4">
                                <p style="width:9.6rem;">暂无数据</p>
                            </td>
                        </tr>
-->
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                       <td>1</td>
                   </tr>
                    </tbody>
                </table>
                <div class="pages-div">
                    <button class="prev"></button>
                    <p id="page"><span>0</span>/<span>0</span></p>
                    <button class="next"></button>
                    <input type="number">
                    <button class="skip">跳转</button>
                </div>
            </div>
            <div class="tishi">日期已存在!</div>
            <div class="edit-div" style="display:none;">
                <h4>编辑</h4>
                <span class="close-edit"></span>
                <div class="set-box">
                    <label for="">值班人</label>
                    <input class="input-edit" id="editT" type="text" value="">
                </div>
                <div class="set-box">
                    <label for="">负责人</label>
                    <input class="input-edit" id="editL" type="text" value="">
                </div>
                <div class="set-box edit-box">
                    <button id="qxEdit">取消</button>
                    <button id="qdEdit">确定</button>
                </div>
            </div>
        </div>
    </div>

<script type="text/javascript" src="./智慧物流服务中心-首页_files/jquery-3.3.1.min.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/layer.min.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/laydate.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/echarts.min.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/china.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/guangdong.js.下载"></script>
<script type="text/javascript" src="./智慧物流服务中心-首页_files/base.js.下载"></script>
<script type="text/javascript">
    $('document').ready(function () {
        $("body").css('visibility', 'visible');
        var localData = [$('#teacher').val(), $('#start').val() + '/' + $('#end').val(), $('#leader').val()]
        localStorage.setItem("data", localData);
        $('#conBtn').on('click', function () {
            localData = [$('#teacher').val(), $('#start').val() + '/' + $('#end').val(), $('#leader').val()]
            if (typeof (Storage) !== "undefined") {
                localStorage.setItem("data", localData);
                var arr = localStorage.getItem("data").split(',');
                $('#name_a').html(arr[0]);
                $('#date_a').html(arr[1]);
                $('#lea_a').html(arr[2]);
            }
        })
        $('#fangda').on('click', function () {
            if ($(this).siblings('ul').is(":hidden")) {
                $(this).addClass('active').siblings('ul').show();
            } else {
                $(this).removeClass('active').siblings('ul').hide();
            }
        })

        $('.modal-btn>li').on('click', function () {
            var index = $(this).index();
            if (index <= 2) {
                $('.container').attr('style', 'visibility: visible').find('.pop-up').eq(index).attr('style', 'visibility: visible').siblings().attr('style', 'visibility: hidden');
            } else if (index > 2 && index < 5) {
                $('.container').attr('style', 'visibility: visible').find('.pop-up').eq(3).attr('style', 'visibility: visible').siblings().attr('style', 'visibility: hidden');
                if (index != 3) {
                    $('.pop-data .ranking-box').hide();
                } else {
                    $('.pop-data .ranking-box').show();
                }
                $('.cont-div').eq(index - 3).attr('style', 'visibility: visible').siblings('.cont-div').attr('style', 'visibility: hidden');
            } else if (index == 5) {
                $('.container').attr('style', 'visibility: visible').find('.pop-up').eq(3).attr('style', 'visibility: visible').siblings().attr('style', 'visibility: hidden');
                $('.pop-data .ranking-box').hide();
                if ($('#switchBtn').find('.active').data('datatype') == "income") {
                    $('#titles').html('收入数据');
                    $('#totalProfits').html('123,456.5元');
                    $('.cont-div').eq(2).attr('style', 'visibility: visible').siblings('.cont-div').attr('style', 'visibility: hidden');
                } else if ($('#switchBtn').find('.active').data('datatype') == 'expend') {
                    $('#titles').html('支出数据');
                    $('#totalProfits').html('32,111.4元');
                    $('.cont-div').eq(2).attr('style', 'visibility: visible').siblings('div').attr('style', 'visibility: hidden');
                }
            }
        })
    })
</script>



</body></html>
