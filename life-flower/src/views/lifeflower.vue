<style lang="less" scoped>
body{width:100%;height: 100%;}
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
			width: 800px;
			margin:0 auto;
			margin-top:80px;
			margin-bottom:150px;
		}
	}
	.footer{
		height: 100px;
	}
}
</style>
<template>
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
					<div class="product-content">
						<!-- UI -->
						<div></div>
						<!-- 前端 -->
						<div></div>
						<!-- 后台 -->
						<div></div>
					</div>
				</div>
			</div>
			<div class="footer">footer</div>
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


