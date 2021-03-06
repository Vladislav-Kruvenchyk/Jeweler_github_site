<template>
	<div class="new">
		<div class="new_container">
			<div class="new_wrapper">
				<div class="new_block_left">
					<div class="new_box_img">
						<div class="new_img"></div>
						<div class="new_img_one"></div>
					</div>
				</div>
				<div class="new_block_right">
					<div class="new_box_right">
						<div class="new_header_left">
							<div class="new_title">Новости</div>
						</div>
						<div class="new_slider_right">
							<div class="new_info_right">
								Все мероприятия
							</div>
							<div class="new_control_right"></div>
						</div>
					</div>
					<div class="new_content_right">
						<div class="new_item_right">
							<div class="new_img_right_one"></div>
							<div class="new_sidebar_right">
								<div class="new_data_right">4 января 2020 г.</div>
								<div class="new_subject_right">
									Как объединилась реальность и <br />
									виртуальность – LIKEE PARTY
								</div>
							</div>
						</div>
						<div class="new_item_right">
							<div class="new_img_right_two"></div>
							<div class="new_sidebar_right">
								<div class="new_data_right">4 января 2020 г.</div>
								<div class="new_subject_right">
									Как объединилась реальность и <br />
									виртуальность – LIKEE PARTY
								</div>
							</div>
						</div>
						<div class="new_item_right">
							<div class="new_img_right"></div>
							<div class="new_sidebar_right">
								<div class="new_data_right">4 января 2020 г.</div>
								<div class="new_subject_right">
									Как объединилась реальность и <br />
									виртуальность – LIKEE PARTY
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
	name: 'New',
};
</script>
<style lang="scss" scoped>
.new {
	width: 100%;
	height: 649px;
	&_container {
		display: flex;
		width: 100%;
		height: 649px;
		align-items: center;
		justify-content: center;
	}
	&_wrapper {
		display: flex;
		width: 1114px;
		height: 500px;
		justify-content: center;
	}
	&_block_left {
		display: flex;
		flex-direction: column;
		width: 45%;
	}
	&_box_img {
		display: flex;
		flex-direction: column;
	}
	&_img {
		width: 445px;
		height: 215px;
		background: url('../assets/img/block_new/ad-1.png');
		background-size: cover;
	}
	&_img_one {
		width: 445px;
		height: 215px;
		margin-top: 4rem;
		background: url('../assets/img/block_new/ad-2.png');
		background-size: cover;
	}
	//Правый блок

	&_block_right {
		display: flex;
		width: 55%;
		flex-direction: column;
	}
	&_box_right {
		display: flex;
		width: 100%;
		height: 2rem;
	}
	&_header_left {
		display: flex;
		width: 50%;
		height: 4rem;
	}
	&_title {
		font-family: 'Plumb';
		font-style: normal;
		font-weight: 500;
		font-size: 30px;
		line-height: 130%;
		letter-spacing: -0.01em;
		color: #2e373b;
	}
	&_slider_right {
		display: flex;
		width: 50%;
		height: 4rem;
		justify-content: flex-end;
	}
	&_info_right {
		display: flex;
		width: 12rem;
		font-family: Plumb;
		font-style: normal;
		font-weight: 500;
		font-size: 21px;
		line-height: 130%;
		text-align: right;
		letter-spacing: -0.01em;
		text-decoration-line: underline;
		color: #2e373b;
	}
	&_control_right {
		width: 30px;
		height: 14px;
		margin-top: 10px;
		background: url('../assets/img/block_new/Arrow 1.png');
		background-size: cover;
	}
	// Контент блока новости
	&_content_right {
		display: flex;
		flex-direction: column;
		width: 100%;
	}
	&_item_right {
		display: flex;
		margin-top: 2.1rem;
	}
	&_img_right {
		width: 160px;
		height: 120px;
		background: url('../assets/img/block_new/Rectangle 11.png');
		background-size: cover;
	}
	&_img_right_one {
		width: 160px;
		height: 120px;
		background: url('../assets/img/block_new/Rectangle 11 (1).png');
		background-size: cover;
	}
	&_img_right_two {
		width: 160px;
		height: 120px;
		background: url('../assets/img/block_new/Rectangle 11 (2).png');
		background-size: cover;
	}
	&_sidebar_right {
		display: flex;
		flex-direction: column;
		padding-left: 2rem;
	}
	&_data_right {
		margin-top: 10px;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		color: #f6404f;
	}
	&_subject_right {
		margin-top: 1rem;
		font-family: 'Plumb';
		font-style: normal;
		font-weight: 500;
		font-size: 21px;
		line-height: 130%;
		letter-spacing: -0.01em;
		color: #2e373b;
	}
}
</style>
