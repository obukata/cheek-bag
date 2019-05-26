<template>
	<header class="page-header">
		<div class="header-body">
			<div class="header-main">
				<h1 class="header-logo">Cheek bag</h1>
				<el-menu mode="horizontal">
					<el-menu-item index="1">Scripts</el-menu-item>
					<el-menu-item index="2">Animations</el-menu-item>
					<el-menu-item index="3">Styles</el-menu-item>
				</el-menu>
			</div>
		</div>
	</header>
</template>

<style lang="scss">
.page-header {
	position: fixed;
	top: 0;
	left: 0;
	width: 100%;
	z-index: 1000;
	.header-body {
		padding-top: 30px;
		display: flex;
		justify-content: center;
		width: 100%;
	}
	.header-logo {
		color: #35495e;
	}
	.header-main {
		display: flex;
		align-items: center;
		justify-content: space-between;
		margin: 0 30px;
		padding: 0 35px 0 30px;
		width: 100%;
		border-radius: 10px;
		box-shadow: 0 1px 6px rgba(0, 0, 0, 0.16);
		background: #fff;
	}
}
</style>
