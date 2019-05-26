<template>
	<div id="page--index" class="container">
		<main class="page-main">
			<article>
				<section>
					<div class="grid">
						<div class="panel panel01 panel-large panel-vertical panel-green">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel02 panel-small panel-green">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel03 panel-small panel-blue">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel04 panel-small panel-red">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel05 panel-small panel-yellow">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel06 panel-small panel-green">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel07 panel-small panel-blue">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel08 panel-small panel-yellow">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel09 panel-small panel-red">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
						<div class="panel panel10 panel-large panel-blue">
							<a href="##">
								<div class="panel-body">
									<span class="panel-title-sub">Animation</span>
									<h2 class="panel-title">ふわふわ浮く雲のアニメーション</h2>
								</div>
							</a>
						</div>
					</div>
				</section>
			</article>
		</main>
	</div>
</template>

<style lang="scss">
.page-main {
	padding-top: 150px;
}
.grid {
	display: grid;
	grid-template-columns: 1fr 1fr 1fr 1fr;
	grid-template-rows: auto auto auto auto;
	grid-gap: 10px;
	padding: 0 30px;
	width: 100%;
	.panel {
		border-radius: 10px;
		width: 100%;
		padding-top: 100%;
		height: 0;
		position: relative;
		display: flex;
		justify-content: center;
		align-items: center;
		a {
			position: absolute;
			width: 100%;
			height: 100%;
			top: 0;
			left: 0;
			display: flex;
			justify-content: center;
			align-items: center;
			padding: 20px;
			text-decoration: none;
			color: #35495e;
		}
	}
	.panel01 {
		grid-row: 1 / 3;
		grid-column: 1 / 3;
	}
	.panel10 {
		grid-row: 3 / 5;
		grid-column: 3 / 5;
	}
	.panel-large {
		.panel-title {
			font-size: 2rem;
		}
	}
	.panel-small {
		.panel-title {
			font-size: 1.2rem;
		}
	}
	.panel-vertical {
		.panel-body {
			writing-mode: tb-rl;
		}
	}
	.panel-title {
		font-weight: bold;
	}
	.panel-title-sub {
		font-weight: bold;
	}
	.panel-green {
		background: #eaf4eb;
	}
	.panel-red {
		background: #f4eaee;
	}
	.panel-blue {
		background: #eaf2f4;
	}
	.panel-yellow {
		background: #f4f4ea;
	}
}
</style>
