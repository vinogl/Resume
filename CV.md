<!DOCTYPE html>
<html lang="en">
<head>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

<style>

    body {
        margin: 0px;
        width: 820px;
        height: 1160px;
        margin: auto;
    }

	.top_head {
		background-color: #000033;
		width: 100%;
		
	}

	.top_head .info {
		color: white;
		text-align: right;
		padding: 5px;
	}
    
    .person {
        float: left;
        display: flex;
        flex-wrap: wrap;
        width: 75%;
        justify-content: space-between;
    }

    .person .info {
        width: 45%;
        font-weight: 500;
        font-size: 14px;
        margin: 5px;
        text-indent: 30px;
    }

    .person .info_long {
        width: 100%;
        font-weight: 500;
        font-size: 18px;
        margin: 5px;
        text-indent: 30px;
    }

    .table {
        font-size: 15px;
        margin-left: 40px;
    }

    .img {
        margin-right: 10px;
    }

    .img .info {
        box-shadow: 5px 5px 5px rgba(0, 0, 0, .5);
    }

    .skill {
        font-weight: 500;
        font-size: 14px;
        margin-left: 30px;
    }

    .block {
        color: #060202;
    }

    .block .info {
        font-size: 14px;
        margin-left: 10px;
    }

    .award {
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        font-weight: 500;
        font-size: 14px;
        justify-content: space-between;
    }

    .award .time {
        width: 30%;
        display: inline-block;
        box-sizing: border-box;
        text-indent: 50px;
    }

    .award .info {
        text-align: left;
        padding-left: 10px;
        width: 70%;
        display: inline-block;
        box-sizing: border-box;
        text-indent: -30px;
    }

    .self_in {
        font-weight: 500;
        font-size: 14px;
        margin-left: 50px;
    }

	.note {
		display: none;
	}

</style>
</head>

<body>

<div class="top_head">
    <h4 class="info">个人简历</h4>
</div>

<h3>个人资料</h3>
<hr/>

<div class="person">
    <div class="info">姓名: 龚理</div>
    <div class="info">出生年月: 1998-09</div>
    <div class="info">籍贯: 湖南省岳阳市</div>
    <div class="info">名族: 汉</div>
    <div class="info">政治面貌: 中共党员</div>
    <div class="info">学位学历: 硕士研究生</div>
    <div class="info">电话: 18810856901</div>
    <div class="info">邮箱: gongli.vino@gmail.com</div>
	<div>
		<br />
    	<div class="info_long">求职意向: 大数据分析、算法工程师等相关岗位</div>
	</div>
</div>

<div class="img">
	<img src="https://github.com/vinogl/Resume/blob/master/.ID_photo.jpg?raw=true" width="120px" height="150px" class="info">
</div>


<br/>
<br/>

<h3>教育背景</h3>
<hr/>

<table class="table">
    <thead>
    <tr>
        <th align="center">时间</th>
        <th align="center">学校</th>
        <th align="center">专业(学位-学历)</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td align="center">  2016.09~2020.06  </td>
        <td align="center">  中国石油大学(北京)  </td>
        <td align="center">  过程装备与控制工程(学士-本科)  </td>
    </tr>
    <tr>
        <td align="center">  2020.09~2023.06  </td>
        <td align="center">  北京交通大学  </td>
        <td align="center">  机械电子工程(硕士-研究生)  </td>
    </tr>
    </tbody>
</table>


<h3>专业技能</h3>
<hr/>

<ul class="skill">
    <li>外语能力: <code>CET-6</code></li>
    <li>编程语言: <code>Python</code>, <code>C</code>, <code>Matlab</code></li>
    <li>Python框架: <code>Pytorch</code>, <code>OpenCV-Python</code>, <code>PyQt5</code>, <code>Django</code>, ...
    <li>数据库: <code>Oracle</code>, <code>MySql</code>, <code>SqlServer</code>
    <li>操作系统: <code>MacOS</code>, <code>Kali_linux</code>, <code>Ubuntu</code>, <code>CentOS</code>, <code>Debian</code>,
        <code>Windows</code></li>
    <li>容器技术: <code>Docker</code></li>
    <li>多媒体软件: <code>AE</code>, <code>Pr</code>, <code>PS</code>, <code>Au</code>
</ul>

<h3>硕士课题项目</h3>
<hr/>

<blockquote class="block">
    <p><strong>卫星故障预测的时间序列分析技术(中国电子科技集团公司第五十四研究所)</strong></p>
    <p class="info"><strong>项目描述:</strong></p>
    <p class="info">  项目基于卫星遥测数据，通过数据处理、序列模式挖掘、预测建模及深度学习算法，开发面向卫星故障预测的时间序列分析模块，为在轨卫星健康管理平台提供技术支撑。</p>
    <p class="info"><strong>个人贡献:</strong></p>
    <ol class="info">
        <li>在实验室部署<code>Oracle</code>数据库服务端，并导入备份遥测数据；</li>
        <li>使用升维算法(<code>MTF</code>, <code>GAF</code>, <code>RP</code>)提取遥测数据的升维特征;</li>
        <li>基于小样本算法(<code>Siamese Network</code>, <code>Triplet Network</code>)的电源系统遥测数据升维特征故障检测;</li>
        <li>小样本检测算法优化(<code>DropBlock</code>)，提高了模型检测的准确率;</li>
        <li>研究样本增强算法，加强检测模型的泛化能力。</li>
    </ol>
</blockquote>

<h3>实习经历</h3>
<hr/>

<blockquote class="block">
    <p><strong>人民交通出版传媒管理有限公司(交通运输部直属企业单位)</strong><br/>
        <strong>实习部门: 信息中心</strong>      <strong>实习时间: 2021.06-2021.09</strong></p>
    <ul class="info">
        <li>独立开发了图书信息源-GUI管理工具(<code>Python-PyQt5</code>, <code>SqlServer</code>)</li>
        <li>独立部署<code>zabbix</code>网络、服务器、虚拟机监测系统(部署在<code>CentOS</code>系统)</li>
        <li>网络、服务器日常运维管理</li>
    </ul>
</blockquote>

<blockquote class="block">
    <p><strong>湖南省临湘市人民法院</strong><br/>
        <strong>实习部门: 综合办公室</strong>     <strong>实习时间: 2020.06-2020.09</strong></p>
    <ul class="info">
        <li>微信公众号后台运维</li>
        <li>网络计算机技术支持</li>
    </ul>
</blockquote>

<h3>在校获奖情况</h3>
<hr/>

<div class="award">
    <div class="time">2021.11</div>
    <div class="info">北京交通大学一等奖学金</div>
    <div class="time">2021.11</div>
    <div class="info">“飞鲨杯”第七届中国研究生未来飞行器创新大赛决赛三等奖</div>
    <div class="time">2019.01</div>
    <div class="info">数学建模美赛H奖</div>
    <div class="time">2018.11</div>
    <div class="info">亚太杯数学建模S奖</div>
    <div class="time">2018.10</div>
    <div class="info">中国石油大学(北京)校内机器人大赛二等奖</div>
    <div class="time">2018.05</div>
    <div class="info">北京市五一数学建模市级二等奖</div>
    <div class="time">2018.05</div>
    <div class="info">第九届节能减排比赛校级二等奖</div>
    <div class="time">2018.01</div>
    <div class="info">数学建模美赛S奖</div>
    <div class="time">2017.10</div>
    <div class="info">中国石油大学(北京)大学物理竞赛三等奖</div>
</div>

<h3>自我评价</h3>
<hr/>

<div class="self_in">
    <div>善于学习新技术，思维逻辑强，数学与计算机能力强；</div>
    <div>外向型性格，乐观开朗，善于与人交流，善于团队协作；</div>
    <div>兴趣爱好广泛，擅长篮球、吉他、游泳、散打、网球。</div>
</div>
<br/>
<br/>

</body>
</html>