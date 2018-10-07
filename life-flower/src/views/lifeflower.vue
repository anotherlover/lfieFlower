<style lang="less" scoped>
body{width:100%;height: 100%;box-sizing: border-box;}
.lifeflower{
	width: 100%;
	height: 100%;
	.header{
		height: 80px;
		line-height: 80px;
		border-bottom: 1px solid rgb(153,153,153);
		// logo
		.header-logo{
			width: 100px;
			height: 50px;
			line-height: 50px;
			background: pink;
			float: left;
			position: relative;
			top: 15px;
			left: 200px;
			font-size:32px;
			border-radius: 3px;
		}
		// nav
		.header-nav{
			font-family:'MicrosoftYaHei';
			font-size:16px;
			width: 480px;
			margin: 0 auto;
			margin-right:160px;
			height:80px;
			line-height: 80px;
			ul{
				display: block;
				li{
					display: block;
					float:left;
					width: 120px;
					a{
						color:rgb(255,255,255);
						padding-left:22px;
					}
					a:hover{color:#2d8cf0}
					a.index{background: url('../assets/img/shouye-wei.png') 0 3px no-repeat}
					a.index:hover{background: url('../assets/img/shouye.png') 0 3px no-repeat}
					a.product{background: url('../assets/img/chanpin-wei.png') 0 3px no-repeat}
					a.product:hover{background: url('../assets/img/chanpin.png') 0 3px no-repeat}
					a.community{background: url('../assets/img/shequ-wei.png') 0 3px no-repeat}
					a.community:hover{background: url('../assets/img/shequ.png') 0 3px no-repeat}
					a.contact{background: url('../assets/img/lianxi-wei.png') 0 3px no-repeat}
					a.contact:hover{background: url('../assets/img/lianxi.png') 0 3px no-repeat}
				}
			}
		}
	}
	.content{
		min-height: 700px;
		img.banner{width: 100%;}
		.product{
			// width: 800px;
			margin:0 auto;
			.product-content{
				font-size: 18px;
				color:rgb(153,153,153);
				font-family: 'MicrosoftYaHei';
				.product-content-UI{
					margin-right: 25px;
				}
				.product-content-web{
					margin-right:25px;
				}
				.common{
					width:260px;
					height:160px;
					border:2px solid rgb(153,153,153);
					position: relative;
					display: inline-block;
					margin-top:80px;
					margin-bottom:150px;
					.rect{
						width:10px;
						height:20px;
						background: #2d8cf0;
						position: absolute;
						top:0;
						right:40px;
					}
					.title{
						display: block;
						position: absolute;
						top:40px;
						left:15px;
						a{
							color: rgb(153,153,153);
						}
						a:hover{
							color:#2d8cf0
						}
					}
					.detail{
						position:absolute;
						height: 50px;
						bottom: 25px;
						margin-right: 30px;
						left:10px;
						font-size:14px;
						padding-right: 50px;
						padding-top:10px;
						text-align: left;
					}
					.ui-bg{
						background: url('../assets/img/ui.png') 160px 0 no-repeat;
					}
					.web-bg{
						background: url('../assets/img/qianduan.png') 160px 0 no-repeat;
					}
					.back-bg{
						background: url('../assets/img/houtai.png') 160px 0 no-repeat;
					}
				}
			}
			
		}
		.advantage{
			margin:0 auto;
			.advantage-content{
				margin-top:80px;
				margin-bottom:150px;
				text-align: center;
				.a{margin-right:50px;}
				font-family: 'MicrosoftYaHei';
				color: rgb(255,255,255);
				.container{
					display: inline-block;
					width: 240px;
					min-height:200px;
					position: relative;
					text-align:center;
					p{
						font-size:14px;
						display: block;
						margin-top:10px;
						margin-bottom:30px;
					}
					span{
						font-size:12px;
					}
				}
			}
			
		}
		.information{
			margin:0 auto;
			.info-content{
				font-family: 'MicrosoftYaHei';
				.common{
					// min-width:350px;
					height:240px;
					// border:1px solid red;
					display: inline-block;
					margin-top:80px;
					li{
						height:20px;
						margin-bottom:16px;
						font-size:14px;
						list-style: none;
						padding-left:46px;
						background: url('../assets/img/icon.png') 0 0 no-repeat;
						a{
							color:rgb(255,255,255);
							display: block;
							border-bottom:1px solid rgb(153,153,153);
						}
						a:hover{
							color:rgb(27,223,253);
						}
					}
				}
				.t{padding-right:130px;}
			}
		}
		.more{
			width:240px;
			height:50px;
			line-height: 50px;
			font-family: 'MicrosoftYaHei';
			font-size:16px;
			margin:0 auto;
			margin-bottom:60px;
			text-align: center;
			border:1px solid rgb(153,153,153);
			border-radius:3px;
			a{
				height: 16px;
				width:64px;
				color:rgb(255,255,255);
			}
			a:hover{color:#2d8cf0}
		}
	}
}
.footer{
	height:330px;
	background: url('../assets/img/dibu.png');
}
</style>
<template>
		<div>
			<div class="lifeflower" :style="{backgroundImage:'url('+bg+')'}">
				<div class="header">
					<!-- logo -->
					<div class="header-logo">LOGO</div>
					<!-- nav -->
					<div class="header-nav">
						<ul>
							<li><a href="#" class="index">首页</a></li>
							<li><a href="#" class="product">案例产品</a></li>
							<li><a href="#" class="community">社区</a></li>
							<li><a href="#" class="contact">联系我们</a></li>
						</ul>
					</div>
				</div>
				<div class="content">
					<img src="../assets/img/banner.png" alt="nothing is possible" class="banner">
					<!-- 经营项目 -->
					<div class="product">
						<img src="../assets/img/01.png" alt="">
						<div class="product-content ">
							<!-- UI -->
							<div class="product-content-UI common">
								<div class="rect"></div>
								<div class="title">
									<a href="#">UI设计</a>
								</div>
								<div class="detail ui-bg">
									<span>专业为您打造属于您公司的唯一独特界面</span>
								</div>
							</div>
							<!-- 前端 -->
							<div class="product-content-web common">
								<div class="rect"></div>
								<div class="title">
									<a href="#">前端搭建</a>
								</div>
								<div class="detail web-bg">
									<span>完美页面搭建，快速实现页面的成型</span>
								</div>
							</div>
							<!-- 后台 -->
							<div class="common">
								<div class="rect"></div>
								<div class="title">
									<a href="#">后台运维</a>
								</div>
								<div class="detail back-bg">
									<span>大数据时代，你值得拥有最新黑科技</span>
								</div>
							</div>
						</div>
					</div>
					<!-- 我们的优势 -->
					<div class="advantage">
						<img src="../assets/img/02.png" alt="">
						<div class="advantage-content">
							<div class="container a">
								<img src="../assets/img/1.png" alt="">
								<p>极速搭建 周期更短</p>
								<span>我们有一个成熟的团队随时等候你的唤醒 下单后即可根据需求完成相应任务</span>
							</div>
							<div class="container a">
								<img src="../assets/img/2.png" alt="">
								<p>专业品质 量身定做</p>
								<span>我们致力于拿出我们最专业的态度与职业精神为您服务</span>
							</div>
							<div class="container a ">
								<img src="../assets/img/3.png" alt="">
								<p>定位全国</p>
								<span>我们的服务范围涉及全国各个城市</span>
							</div>
							<div class="container">
									<img src="../assets/img/4.png" alt="">
									<p>100%信誉保障</p>
									<span>用最真诚的心对待每一位客户，品质是我们的底气信誉是我们的代言词</span>
								</div>
							</div>
					</div>
					<!-- 产品资讯 -->
					<div class="information">
						<img src="../assets/img/03.png" alt="">
						<div class="info-content">
							<div class="common t">
								<ul>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
								</ul>
							</div>
							<div class="common t">
								<ul>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
								</ul>
							</div>
							<div class="common">
								<ul>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
									<li><a href="">JAVA行业稳步提升，逐步迈入国际化视野</a></li>
								</ul>
							</div>	
						</div>
					</div>
					<!-- 查看更多 -->
					<div class="more">
							<a href="">查看更多</a>
					</div>
				</div>
    	</div>
			<div class="footer" style='clear:both'>footer</div>
	</div>
</template>
<script>
import Img from '../assets/img/beijing.png'
export default {
    data(){
			return{
				bg:Img
			}
		}
}
</script>


