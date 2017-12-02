<template>
 	<div class="mp-header">
 		<a class="mp-header-left"><</a>
 		<div class="mp-header-title">
 			<a>
 				<i class=""></i>
 				<div>景点/目的地/主题</div>
 			</a>
 		</div>
 		<div class="mp-header-right"><a><div class="mp-header-city">北京</div><div class="mp-header-triangle"></div></a></div>
 	</div>
</template>

<script>
export default {}
</script>

<style>
	.mp-header {
		position:relative;
		height:.88rem;
		background:#00bcd4;
		color:white;
	}
	.mp-header-left {
		display:inline-block;
		padding:.2rem;
		font-size:.36rem;
		line-height:.48rem;
	}
	.mp-header-title {
		position:absolute;
		left:.8rem;
		right:1.28rem;
		top:.14rem;
		height:.6rem;
		background:#fff;
		color:#ccc;
		line-height:.6rem;
		border-radius:.06rem;
	}
	.mp-header-right {
		height:.88rem;
		line-height:.88rem;
		padding:0 .1rem;
		float:right;
		margin-right:.28rem;
		text-align:center;
	}
	.mp-header-right::after {
		content:"\0020";
		position:absolute;
		top:.36rem;
		right:.13rem;
		border-left:.12rem solid transparent;
		border-right:.12rem solid transparent;
		border-top:.14rem solid #fff;
	}
	.mp-header-city {
		width:.9rem;
		overflow:hidden;
		white-space:nowrap;
		text-overflow:ellipsis;

	}
</style>
