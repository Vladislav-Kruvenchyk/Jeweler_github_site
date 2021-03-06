<template>
	<div class="information">
		<div class="information_container">
			<div class="information_wrapper">
				<div class="information_column">
					<div class="information_item">
						<div class="information_title">Организаторам</div>
					</div>
					<div class="information_inner">
						<div class="information_link">
							<a href="" class="information_link_subtitle"
								>Документы организаторам</a
							>
						</div>
						<div class="information_item">
							<div class="information_list">Услуги организаторам</div>
						</div>
						<div class="information_item">
							<div class="information_list">Выставочные площади</div>
						</div>
						<div class="information_item">
							<div class="information_list">Рестораны и кафе</div>
						</div>
						<div class="information_item">
							<div class="information_list">Конгресс-центр</div>
						</div>
						<div class="information_item">
							<div class="information_list">Спорт-центр</div>
						</div>
					</div>
				</div>
				<div class="information_column">
					<div class="information_item">
						<div class="information_title">Экспонентам</div>
					</div>
					<div class="information_inner_one">
						<div class="information_item">
							<div class="information_list">Общие условия участия</div>
						</div>
						<div class="information_item">
							<div class="information_list">Услуги экспонентам</div>
						</div>
						<div class="information_item">
							<div class="information_list">Документы экспонентам</div>
						</div>
						<div class="information_item">
							<div class="information_list">Центр деловых контактов</div>
						</div>
						<div class="information_item">
							<div class="information_list">Забронировать гостиницу</div>
						</div>
					</div>
				</div>
				<div class="information_column">
					<div class="information_item">
						<div class="information_title">Посетителям</div>
					</div>
					<div class="information_inner_two">
						<div class="information_item">
							<div class="information_list">Сервисы</div>
						</div>
						<div class="information_item">
							<div class="information_list">
								Онлайн-регистрация <br />
								на мероприятие
							</div>
						</div>
						<div class="information_item">
							<div class="information_list">Забронировать гостиницу</div>
						</div>
						<div class="information_item">
							<div class="information_list">Центр деловых контактов</div>
						</div>
					</div>
				</div>
				<div class="information_column_footer">
					<div class="information_item">
						<div class="information_title">Прессе</div>
					</div>
					<div class="information_inner_tree">
						<div class="information_item">
							<div class="information_list">Аккредитация</div>
						</div>
						<div class="information_item">
							<div class="information_list">Пресс-служба</div>
						</div>
						<div class="information_item">
							<div class="information_list">Правила аккредитации</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
export default {
	name: 'Information',
};
</script>
<style lang="scss" scoped>
.information {
	width: 100%;
	height: 426px;
	background: #2378fc;
	&_container {
		display: flex;
		width: 100%;
		height: 100%;
		align-items: center;
		justify-content: center;
	}
	&_wrapper {
		display: flex;
		width: 1114px;
		height: 276px;
		justify-content: center;
	}
	&_column {
		display: flex;
		width: 18rem;
		height: 276px;
		align-items: center;
		flex-direction: column;
	}
	&_column_footer {
		display: flex;
		width: 14rem;
		height: 276px;
		padding-left: 1rem;
		align-items: center;
		flex-direction: column;
	}
	&_item {
		display: flex;
		width: 15rem;
		margin-top: 12px;
	}
	&_title {
		display: flex;
		height: 3rem;
		justify-content: flex-start;
		font-family: 'Circe';
		font-style: normal;
		font-weight: 500;
		font-size: 30px;
		line-height: 130%;
		letter-spacing: -0.01em;
		color: #ffffff;
	}

	&_inner {
		display: flex;
		width: 15rem;
		margin-top: 1rem;
		flex-direction: column;
	}
	&_inner_one,
	&_inner_two,
	&_inner_tree {
		display: flex;
		width: 13.9rem;
		margin-top: 4px;
		flex-direction: column;
	}
	&_link {
		display: block;
	}
	&_link_subtitle {
		display: flex;
		overflow: hidden;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		text-decoration-line: underline;
		font-size: 16px;
		line-height: 135%;
		color: #ffc41e;
	}
	&_list {
		display: flex;
		overflow: hidden;
		font-family: 'Circe';
		font-style: normal;
		font-weight: normal;
		font-size: 16px;
		line-height: 135%;
		color: #ffffff;
	}
}
</style>
