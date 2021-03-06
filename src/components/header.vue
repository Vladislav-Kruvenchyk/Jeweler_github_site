<template>
	<div class="header">
		<nav class="header_navbar">
			<div class="header_container">
				<div class="header_navbar_logo">
					<div class="header_logo"></div>
				</div>
				<div class="header_navbar_menu">
					<div class="header_navbar_item">
						<div class="header_navbar_link">
							<a href="">О комплексе</a>
						</div>
						<div class="header_navbar_link">
							<a href="">О комплексе</a>
						</div>
						<div class="header_navbar_link">
							<a href="">Новости</a>
						</div>
						<div class="header_navbar_link">
							<a href="">Медиа-банк</a>
						</div>
						<div class="header_navbar_link">
							<a href="">Контакты</a>
						</div>
					</div>
				</div>
				<div class="header_navbar_end">
					<div class="header_navbar_end_search">
						<div class="header_navbar_search">
							<div class="header_navbar_icon_search"></div>
						</div>
						<div class="header_navbar_icon_item">
							<div class="header_navbar_icon"></div>
						</div>
						<div class="header_navbar_english">English</div>
					</div>
				</div>
			</div>
		</nav>
		<div class="header_footer">
			<div class="header_footer_wrapper">
				<div class="header_footer_left">
					<div class="header_inner">
						<div class="header_title">ЭКСПОФОРУМ</div>
						<div class="header_subtitle">
							конгрессно-выставочный центр <br />
							Санкт-Петербурга
						</div>
						<div class="header_slider">
							<div class="header_info">
								О комплексе
							</div>
							<div class="header_control"></div>
						</div>
					</div>
				</div>
				<div class="header_footer_right">
					<div class="header_footer_wrap">
						<div class="header_footer_box">
							<div class="header_footer_content">
								<div class="header_subtitle_rignt">
									Календарь <br />
									мероприятий
								</div>
								<div class="header_slider_right">
									<div class="header_info_right">
										Подробнее
									</div>
									<div class="header_control_right"></div>
								</div>
							</div>
						</div>
						<div class="header_footer_box_one">
							<div class="header_footer_content">
								<div class="header_subtitle_rignt">
									Как добраться <br />
									до Экспофорума
								</div>
								<div class="header_slider_right">
									<div class="header_info_right">
										Подробнее
									</div>
									<div class="header_control_right"></div>
								</div>
							</div>
						</div>
						<div class="header_footer_box_two">
							<div class="header_footer_content">
								<div class="header_subtitle_bottom_rignt">
									Онлайн-заявка <br />
									на организацию мероприятия
								</div>
								<div class="header_slider_right">
									<div class="header_info_right">
										Подробнее
									</div>
									<div class="header_control_right"></div>
								</div>
							</div>
						</div>
						<div class="header_footer_box_tree">
							<div class="header_footer_content">
								<div class="header_subtitle_bottom_rignt">
									План <br />
									и инфраструктура комплекса
								</div>
								<div class="header_slider_right">
									<div class="header_info_right">
										Подробнее
									</div>
									<div class="header_control_right"></div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
export default {
	name: 'Header',
};
</script>
<style lang="scss" scoped>
.header {
	width: 100%;
	height: 800px;
	background: url('../assets/img/block_header/bgc.png') center center;
	background-size: cover;
	&_navbar {
		display: flex;
		width: 100%;
		height: 90px;
		border-bottom: 1px solid #ffffff;
	}
	&_container {
		display: flex;
		width: 100%;
		overflow: hidden;
	}
	&_navbar_logo {
		display: flex;
		width: 20%;
		height: 90px;
		align-items: center;
		justify-content: center;
	}
	&_logo {
		width: 176px;
		height: 24px;
		background: url('../assets/img/block_header/logo 1.png');
		background-size: cover;
	}
	// Меню navbar

	&_navbar_menu {
		display: flex;
		width: 60%;
		height: 90px;
		align-items: center;
		justify-content: center;
	}
	&_navbar_item {
		display: flex;
		width: 726px;
	}
	&_navbar_link {
		display: flex;
		width: 100%;
		height: 2rem;
		justify-content: center;
		align-items: center;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		text-align: center;
		color: #ffffff;
		a {
			color: #fff;
			overflow: hidden;
		}
	}

	//nvbar_and
	&_navbar_end {
		display: flex;
		width: 20%;
		height: 90px;
	}
	&_navbar_end_search {
		display: flex;
		align-items: center;
	}
	&_navbar_search {
		display: flex;
		justify-content: flex-end;
	}
	&_navbar_icon_search {
		display: flex;
		width: 20px;
		height: 17px;
		background: url('../assets/img/block_header/Search.png');
		background-size: cover;
	}
	&_navbar_icon_item {
		display: flex;
		width: 18rem;
		justify-content: flex-end;
		margin-right: 1rem;
	}
	&_navbar_icon {
		width: 20px;
		height: 18px;
		background: url('../assets/img/block_header/Globe.png');
		background-size: cover;
	}
	&_navbar_english {
		display: flex;
		align-items: center;
		height: 2rem;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		color: #ffffff;
	}
	// footer content
	&_footer {
		display: flex;
		width: 100%;
	}
	&_footer_wrap {
		display: flex;
		flex-wrap: wrap;
		width: 600px;
		height: 359px;
	}
	&_footer_left {
		display: flex;
		width: 50%;
		justify-content: flex-end;
		margin-top: 12rem;
	}
	&_inner {
		display: flex;
		width: 535px;
		height: 224px;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	&_title {
		display: flex;
		justify-content: center;
		font-family: 'Plumb';
		font-style: normal;
		font-weight: bold;
		font-size: 64px;
		line-height: 160%;
		text-transform: uppercase;
		color: #ffffff;
	}
	&_subtitle {
		display: flex;
		margin-left: 8rem;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 24px;
		line-height: 140%;
		color: #ffffff;
	}
	&_slider {
		display: flex;
		height: 2rem;
		margin-left: 8rem;
	}
	&_info {
		display: flex;
		width: 7rem;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		color: #ffffff;
	}
	&_control {
		display: flex;
		height: 8px;
		width: 16px;
		margin-top: 7px;
		background: url('../assets/img/block_header/Arrow 1.png');
		background-size: cover;
	}
	&_footer_right {
		display: flex;
		width: 50%;
		height: 40rem;
		align-items: flex-end;
	}
	&_footer_wrapper {
		display: flex;
		width: 100%;
	}
	&_footer_box,
	&_footer_box_one {
		display: flex;
		background: #2378fc;
		width: 255px;
		height: 148px;
	}
	&_footer_box_one {
		margin-left: 2rem;
		background: #30bcc9;
	}
	&_footer_box_two,
	&_footer_box_tree {
		display: flex;
		margin-top: 2rem;
		background: #ffc41e;
		width: 255px;
		height: 175px;
	}
	&_footer_box_tree {
		margin-left: 2rem;
		background: #f6404f;
	}
	&_footer_content {
		display: flex;
		flex-direction: column;
	}
	&_subtitle_rignt,
	&_subtitle_bottom_rignt {
		display: flex;
		height: 4rem;
		margin-top: 2rem;
		justify-content: flex-start;
		padding-left: 3rem;
		align-items: center;
		font-family: 'Circe';
		font-style: normal;
		font-weight: 500;
		font-size: 21px;
		line-height: 130%;
		letter-spacing: -0.01em;
		color: #ffffff;
	}
	&_subtitle_bottom_rignt {
		height: 6rem;
	}
	&_slider_right {
		display: flex;
		padding-left: 2.1rem;
		margin-top: 10px;
	}
	&_info_right {
		display: flex;
		height: 2rem;
		justify-content: center;
		width: 7rem;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		color: #ffffff;
	}
	&_control_right {
		display: flex;
		height: 8px;
		width: 16px;
		margin-top: 7px;
		background: url('../assets/img/block_header/Arrow 1.png');
		background-size: cover;
	}
}
</style>
